# IBPS Solution-File Repair Brief

## Situation

`pr-pdf/*.pdf` are Margdarshan Prep IBPS question sets (Reasoning, English, Quantitative Aptitude).
`pr/*.md` are solution files for them, generated earlier. They cover every question, but two defects were found:

1. **Bare answers** — some entries are just `**Q52.** (c) offer` with no reasoning at all.
2. **Hand-waves** — some entries compute something that matches no option and then write
   `Not in options. Standard key: **(d) 176** (if different)`. These are not solutions; they are guesses.

**Critical fact: the PDFs contain NO answer key.** Verified by searching every set for an answer-key
section — none exist. Therefore every "standard key" claim in the existing files is unsourced and must
not be trusted or repeated. Every answer must be derived from the question itself.

## Your task

For each flagged block in your assigned file:

- **Bare answer** → write the actual reasoning that leads to the answer, using the source passage/stem.
- **Hand-wave** → derive the correct answer properly. It will very often match an option once the
  source data is read correctly (see below). If it still matches no option, tag it `[BROKEN SOURCE]`.
- Delete every `Standard key:` / `if different` / `Not in options` phrase — replace with real derivation
  or a provenance tag. **No guessing.**

## Recovering garbled data (the main cause of "not in options")

`pdftotext -layout` drops or misaligns table columns and chart labels. The data is in the PDF text
layer — recover it by coordinates:

```bash
# find the page containing the question
for p in $(seq 1 50); do pdftotext -f $p -l $p "pr-pdf/IBPS SET 02.pdf" - 2>/dev/null | grep -q "Q74\." && echo "page $p"; done

# dump that page with coordinates, filter to the table region, sort by y then x
pdftotext -f 34 -l 34 -bbox "pr-pdf/IBPS SET 02.pdf" - 2>/dev/null | python3 -c "
import sys,re
for l in sys.stdin:
    m=re.search(r'xMin=\"([\d.]+)\" yMin=\"([\d.]+)\" xMax=\"([\d.]+)\" yMax=\"([\d.]+)\">([^<]*)<',l)
    if m:
        x,y,x2,y2,w=float(m.group(1)),float(m.group(2)),float(m.group(3)),float(m.group(4)),m.group(5)
        print(f'x={x:7.1f} y={y:7.1f}  {w}')
" | sort -k2
```

Cluster the words by `x` to rebuild columns, and by `y` to rebuild rows. Header text is often centred
over its column and can sit at a different x than the values — use the y-order to align rows.

Also check the page with `pdftotext` without `-layout` (reading order differs), and `pdfimages -list`
to see whether a chart is an embedded image rather than text.

### The validation rule — use this to know you are right

After reconstructing the data, compute the answers to **several** questions in the same block. If your
reconstruction is correct, they will hit the printed options **exactly** — not approximately.
If 3+ questions land exactly on options and none of the alternatives do, the reconstruction is proven.
If your numbers produce "no option matches" repeatedly, your reconstruction is wrong — go back and
re-read the table, do not tag `[BROKEN SOURCE]` yet.

**Worked example (set 2, Q74–Q79, `IBPS SET 02.pdf` page 34).** The extractor dropped the Total column.
The text layer gives the difference column `60,198,188,76,330` and the % red column `62.5,66.5,70,60,72`.
Using Total instead of Difference makes row A's red balls 37.5 (non-integer) and answers match nothing.
Using Difference gives, via `R−B=d` and `R/(R+B)=p`:

| Bag | Red | Blue | Total |
|---|---|---|---|
| A | 150 | 90 | 240 |
| B | 399 | 201 | 600 |
| C | 329 | 141 | 470 |
| D | 228 | 152 | 380 |
| E | 540 | 210 | 750 |

Q74 → 690/300 = **230** = option (a) exactly. Q76 → 690:90 = **23:3** = option (c) exactly.
Q77 → 1167/3 = **389** = option (d) exactly. Q78 → 675−75 = **600** = option (e) exactly.
The existing file says Q74 is "Standard key (c) 240" — that is **wrong**; the correct answer is (a) 230.
Q75 derives 10 and matches no option → `[BROKEN SOURCE]`. Q79 is self-inconsistent → `[BROKEN SOURCE]`.
Four exact hits settle it. Apply this same standard throughout.

## Provenance tags — required on every repaired entry

Add a legend block near the top of the file, and tag each repaired entry:

```markdown
> **Provenance:** These question sets ship **without an answer key**, so every answer below is a
> derivation, not an official key. **[VERIFIED]** = re-derived from the source data and the result
> matches a printed option exactly. **[JUDGEMENT CALL]** = subjective (English usage/comprehension);
> the best reading is given with reasons. **[BROKEN SOURCE]** = stem, data or options are internally
> inconsistent; not a valid MCQ, kept for audit.
```

- `> **[VERIFIED]** ...` — include the arithmetic/arrangement proof and name the option it hits.
- `> **[JUDGEMENT CALL]** ...` — for English items (cloze, synonyms, fill-in-the-blanks, RC, word
  replacement/usage). Give the reasoning for the chosen option and say why the nearest distractor is wrong.
- `> **[BROKEN SOURCE]** ...` — state the derived value and that no option matches.

## Honesty rules

- Do **not** invent data that is not in the PDF. If a table or chart genuinely cannot be recovered,
  say so and tag `[AMBIGUOUS STEM]` rather than fabricating numbers.
- Do **not** write "standard key", "as per key", or "if different". If you cannot derive it, tag it.
- Puzzle arrangements: give the final arrangement and show the constraint checks for each answer.
  If the constraints admit no consistent arrangement matching the options, tag `[BROKEN SOURCE]` and
  show which constraint conflicts.
- Keep the existing file structure, heading style and `**Answer: (x) ...**` format. Match the
  surrounding markdown/LaTeX conventions (`$...$` for math).
- Only touch the flagged blocks. Leave already-correct entries alone.

## Deliverable

Edit your assigned `pr/ibps-setN.md` in place. Report back: number of blocks repaired, list of
questions re-tagged `[BROKEN SOURCE]` or `[JUDGEMENT CALL]`, and anything you could not recover.
