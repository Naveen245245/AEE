# IBPS / IOCL — Formula & Method Sheet

Covers every topic that appears across the eight question sets in `pr/` (Reasoning, Quantitative
Aptitude, English). Built by inventorying all 799 questions, not from a generic syllabus.

> **How to use this:** Part A is formulas you must be able to write from memory. Part B is *methods* —
> the constraint-checking procedures that actually decide puzzle answers. Part C is a grammar/usage
> checklist. The **[nb]** notes flag the traps that caused real errors in these sets.

---

# PART A — QUANTITATIVE APTITUDE

## A1. Percentages & Fractions

Learn this table cold — it converts most calculation into mental arithmetic:

| Fraction | % | Fraction | % |
|---|---|---|---|
| 1/2 | 50% | 1/9 | 11.11% |
| 1/3 | 33.33% | 1/10 | 10% |
| 1/4 | 25% | 1/11 | 9.09% |
| 1/5 | 20% | 1/12 | 8.33% |
| 1/6 | 16.66% | 1/15 | 6.66% |
| 1/7 | 14.28% | 1/16 | 6.25% |
| 1/8 | 12.5% | 1/20 | 5% |

**Successive change (use for "increased then decreased"):**
$$x + y + \frac{xy}{100} \quad \text{(signed — a decrease is negative)}$$
Two successive changes of +20% and −20% give $20 - 20 - \frac{400}{100} = -4\%$.

**Reverse percentage (the #1 trap):** if income after a 25% rise is 180, the original is
$\frac{180}{1.25} = 144$, **not** $180 \times 0.75$.

**[nb]** Set 5 Q60 turned on this: tax = 36 is ¼ of income ⇒ income = 36 × 4 = 144, then ×1.25 for the
next year. Applying the rent to the *pre-tax* income gives a wrong answer that still reached the printed
option — two compensating errors.

## A2. Profit & Loss

$$SP = CP + \text{Profit}, \qquad \%P = \frac{SP - CP}{CP} \times 100$$
$$MP = CP\left(1 + \frac{\text{markup}\%}{100}\right), \qquad SP = MP\left(1 - \frac{\text{discount}\%}{100}\right)$$

**Combined markup-then-discount:** $SP = CP \times (1+m)(1-d)$. Equate to $CP + \text{profit per item}$.

> **Set 1 Q75 (exact):** markup 20%, discount 10%, profit ₹85 → $1.08\,CP = CP + 85$ → $CP = 1062.5$ →
> $MP = 1.2 \times 1062.5 = 1275$.

**Two articles, same SP, +x% and −x%:** there is always a **loss** of $\left(\frac{x}{10}\right)^2\%$.
**Two articles, same CP, +x% and −x%:** net **zero** profit/loss.

## A3. Simple & Compound Interest

$$SI = \frac{P \cdot R \cdot T}{100}$$
$$CI = P\left[\left(1+\frac{R}{100}\right)^T - 1\right]$$

**Two-year shortcut (memorise this one):**
$$\text{CI} - \text{SI} = \frac{P R^2}{10^4}$$
For 3 years: $\text{CI} - \text{SI} = P\left(\frac{3R^2}{10^4} + \frac{R^3}{10^6}\right)$.

**Half-yearly:** rate = R/2, periods = 2T. **Quarterly:** rate = R/4, periods = 4T.

> **Set 1 (Compound & SI, exact):** SI on X at 15% for 2 yr = 0.30X; CI on 2X at 8% = 2X × 0.1664 =
> 0.3328X; difference 0.0328X = 820 → X = 25,000.

## A4. Ratio, Proportion & Partnership

$$P_1 : P_2 = (C_1 T_1) : (C_2 T_2) \quad \text{(capital × time)}$$

If A withdraws after *t* months, count his capital for *t* months and the remainder separately.
**Dividing a number in ratio a:b:c:** parts are $\frac{a}{a+b+c}N$, etc.

## A5. Average & Ages

$$\text{Average} = \frac{\text{Sum}}{n}, \qquad \text{Sum} = \text{Average} \times n$$
$$\text{Age now} = \text{Age } t \text{ yrs ago} + t; \qquad \text{Age now} = \text{Age } t \text{ yrs hence} - t$$

**Change in average when one item is replaced:** weight of new = weight of old + (change in avg × n).

**Ages in ratio a:b, $t$ years later ratio c:d:**
$$\frac{ax + t}{bx + t} = \frac{c}{d} \;\Rightarrow\; x = \frac{t(d - c)}{bc - ad}$$

## A6. Time & Work

$$W = \frac{1}{a} + \frac{1}{b} \quad\text{per day when A takes } a \text{, B takes } b \text{ days}$$
$$\text{Together} = \frac{ab}{a+b} \text{ days}$$

**Efficiency ∝ 1/time.** If Ritu is *x*% more efficient than Rakesh, their time ratio is
$\frac{1}{1+x/100} : 1$.

> **Set 5 Q53 (exact):** Ritu 60% more efficient ⇒ time ratio 5:8; difference 3 units = 18 days ⇒
> Rakesh 48 d, Ritu 30 d; Rahul 12.5% less efficient than Ritu ⇒ 1.4 (Rakesh = 1) ⇒ $48/1.4$ d.
> Combined $= \frac{1}{30}+\frac{1}{48}+\frac{7}{240} = \frac{1}{12}$ → **12 days**.

**Working together with a third:** $\frac{1}{a}+\frac{1}{b}+\frac{1}{c} = \frac{1}{T}$.
**A+C do x days, then B joins:** track work-days, not days.

## A7. Speed, Distance, Time

$$D = S \times T, \qquad \text{Average speed} = \frac{\text{Total distance}}{\text{Total time}}$$
Equal distances at $s_1$ and $s_2$: $\quad \text{Avg} = \frac{2 s_1 s_2}{s_1 + s_2}$ (harmonic mean, **not** the arithmetic average)

**Trains — the three cases:**
- Crossing a pole/person: $T = \frac{L_{train}}{S}$
- Crossing a platform: $T = \frac{L_{train} + L_{platform}}{S}$
- Two trains, same direction: $T = \frac{L_1 + L_2}{S_1 - S_2}$ · opposite: $\frac{L_1+L_2}{S_1+S_2}$

Convert: $1 \text{ km/h} = \frac{5}{18}$ m/s · $1 \text{ m/s} = \frac{18}{5}$ km/h

**Boats & streams:**
$$S_{down} = B + S, \quad S_{up} = B - S, \quad B = \frac{S_{down}+S_{up}}{2}, \quad S = \frac{S_{down}-S_{up}}{2}$$

> **Set 5 Q51:** upstream:downstream = 3:5 ⇒ 60 km each way in 16 h 10 m gives the two speeds; then
> time = distance/speed for 37 km.

## A8. Mixtures & Alligation

**Repeated replacement (memorise):**
$$\text{Final pure} = P\left(1 - \frac{x}{V}\right)^n$$
where V = total volume, x = amount removed each time, n = number of operations.

**Alligation** (two ingredients at cost $c_1, c_2$, mixture at $c_m$):
$$\frac{q_1}{q_2} = \frac{c_2 - c_m}{c_m - c_1}$$

> **Set 1 Q99 (exact):** 3:5, 120 L → milk 45, water 75. Remove Y, add 10 L milk + 15 L water, new
> ratio 8:13 → $13(55 - \tfrac{3Y}{8}) = 8(90 - \tfrac{5Y}{8})$ → Y = 40.

## A9. Number Series — pattern checklist

Run this list **in order**. This is the actual decision procedure.

1. **Difference of differences constant?** (2nd-order AP)
2. **Constant ratio?** (GP)
3. **Differences are squares / cubes / primes / factorials?** → 1, 4, 9, 16 · 1, 8, 27, 64 · 2, 3, 5, 7 · 1, 2, 6, 24
4. **$a_n = a_{n-1}\cdot k + c$** with k, c small constants? (then test $k = n$: $a_n = a_{n-1}\cdot n$)
5. **$a_n = a_{n-1}\cdot n \pm n$** — very common in the ×2+2, ×3+3 family
6. **Two interleaved subsequences** (odd positions / even positions), each with its own rule
7. **Alternating ×k and +c** operations
8. **Squares/cubes of position ± small constant:** $n^2 \pm k$, $n^3 \pm k$

**Wrong-term questions:** the answer is the term that breaks the rule that **all the others** satisfy.
Test each option by substitution — a correct series must satisfy the rule at *every* step, not just the
two neighbours of the changed term.

**[nb]** A "short, clean fit" is not proof. In set 1 Q80, the last three terms satisfied $a_n = a_{n-1}n+n$
exactly (100×5+5 = 505, 505×6+6 = 3036, 3036×7+7 = 21259) — yet extending it backwards broke on
**three** steps, so it was not the generator. If a rule needs more than one correction, it is the wrong
rule, not a wrong term.

## A10. Quadratic Equations — the comparison method

Solve both, then compare **root by root** (this is what "Quantity I vs II" asks):

| Roots of I | Roots of II | Conclusion |
|---|---|---|
| $x < y$ (both roots) | | I < II |
| $x > y$ (both roots) | | I > II |
| $x \le y$ (one strict) | | I ≤ II |
| one root of each equal, other differs | | relation holds only if all four pairings agree |
| otherwise | | **cannot be determined** |

**Factorising $ax^2+bx+c=0$:** find two numbers with product $ac$ and sum $b$.

**[nb]** When *one* root of I is bigger and *one* is smaller, the answer is **"no relation / can't be
determined"** — this is the single most common trap.

## A11. Approximation & Simplification

**Rounding rules for these papers:**
- Round to the nearest "convenient" number that makes the arithmetic clean: 44.93 → 45, 26.99 → 27, 4.99 → 5
- Squares to memorise: 12²=144, 27²=729, 29²=841, 31²=961, 37²=1369
- Cubes: 5³=125, 6³=216, 7³=343
- √1368 ≈ 37 (since 37² = 1369)

**BODMAS + fraction-to-decimal:** 1/8 = 0.125, 1/16 = 0.0625, 3/8 = 0.375, 5/8 = 0.625.

**[nb]** Set 1 Q84 hinges on **where the equals sign is**. The stem reads
"3875 ÷ (4.99)³ **= ? −** {(24)² ÷ 47.98}" — the unknown is isolated on one side, so it is
$31 = ? - 12 \Rightarrow ? = 43$, not $31 - 12 = 19$. Always map the equation structure before computing.

**[nb]** Watch for **nested fractions**: $\frac{(26.99)^2 - 138.99 - \left(\frac{360.08}{3.99}\right)}{9.99}$
has 360.08/3.99 *inside* the numerator. Flat text extraction flattens this and changes the answer.

## A12. Mensuration (only what the sets use)

| Shape | Perimeter | Area |
|---|---|---|
| Rectangle | $2(L+B)$ | $L \times B$ |
| Square | $4a$ | $a^2$ |
| Circle | $2\pi r$ | $\pi r^2$ |
| Semicircle | $\pi r + 2r$ | $\frac{\pi r^2}{2}$ |

**Pathway around a rectangle:** width $w$ outside → area $= 2w(L+B) + 4w^2$; inside → $2w(L+B) - 4w^2$.
**Largest semicircle inside a rectangle:** radius = min(L, B)/2.

## A13. Set Theory (Venn)

Two sets: $\quad n(A \cup B) = n(A) + n(B) - n(A \cap B)$
Three sets: $\quad n(A\cup B\cup C) = \sum n(A) - \sum n(A\cap B) + n(A\cap B\cap C)$
Exactly one: $\quad \sum n(A) - 2\sum n(A \cap B) + 3n(A\cap B\cap C)$

**Method:** put the triple-intersection in the centre and work outwards; the "exactly two" figures are
what usually go wrong.

> **Set 5 Q36–Q40:** the categories were under-determined — the double-count cells were fixed only in
> *sum*, which is why two of the five questions legitimately answer "can't be determined".

## A14. Data Interpretation — the reading protocol

**[nb] This is where the source files were most wrong.** In sets 1, 2, 3 and 5, chart values had been
read **one gridline too high**, which silently broke every question in the block.

1. **Find the baseline.** The x-axis is value 0. Confirm it — do not assume.
2. **Count the gridlines between two labelled ticks.** If the axis labels every 20 but gridlines every
   4, know which lines are which.
3. **Read every series off the same axis.** In a bar chart, the label may be centred over the *group*,
   not the individual bar.
4. **Sanity-check with a question you can compute another way.** If several derived answers miss all
   options, the data — not your arithmetic — is wrong.

**Pie chart:** $\text{value} = \frac{\text{angle}}{360} \times \text{total}$;
$\text{angle} = \frac{\text{value}}{\text{total}} \times 360$.
**"X is what % more/less than Y":** $\frac{X-Y}{Y}\times100$ (more) · $\frac{Y-X}{Y}\times100$ (less).
**[nb]** The denominator is the **base you are comparing against**, not the larger number.

## A15. "Can't be determined" — when it is genuinely the answer

The correct choice whenever a required quantity is **not pinned by the stem**:
- a rate/base is never stated (set 5 Q55)
- a later year's income/value is never linked to an earlier one
- a distribution is fixed only in total, not in its parts (set 5 Q36–Q37)

Do not force a number just because the options contain one.

---

# PART B — REASONING

## B1. Seating & Arrangement — direction rules

| Arrangement | Facing | **Left** | **Right** |
|---|---|---|---|
| Linear row | North | lower position (west) | higher position (east) |
| Linear row | South | higher position | lower position |
| Circular | **Centre** | **clockwise** | **anticlockwise** |
| Circular | **Outside** | anticlockwise | clockwise |

**"Immediate left/right"** = adjacent. **"2nd to the left"** = one person in between.

**Two-row (parallel) puzzles:** decide once whether right/left mirror between rows, and state it. In
these papers, facing rows **mirror**.

**[nb]** Use "nobody between X and Y" as *adjacent*, but "how many between" as $|pos_X - pos_Y| - 1$.

## B2. Puzzle method (floor, box, month, year, category)

1. **Fix the anchor.** Find the most restrictive clue: "3 floors above", "only two before", "one
   between X and Y", "X is at an end".
2. **Draw the skeleton grid and fill certainties only.** Every clue entered must be *forced*.
3. **Branch explicitly** when a clue admits two cases, and carry both until one fails.
4. **Verify at the end against every clue** — this is not optional and catches the swap errors.

**[nb]** Set 5 Q66–70: the arrangement had **G and D transposed**. That alone put G *four* floors above
Fibres where the clue said three, and silently corrupted two answers. A single constraint check at the
end would have caught it.

**[nb]** Set 3 Q1–Q5: the file's own arrangement contradicted itself and the "answer" it gave was not
among the options. If your arrangement can't produce any option, the arrangement is wrong — go back,
don't defer to a key.

## B3. Syllogism — Venn method

Draw **minimal** overlap for "some", full containment for "all", and disjoint for "no".

| Statement | Valid conclusions |
|---|---|
| All A are B | Some B are A (converse valid) |
| Some A are B | Some B are A (converse valid) |
| No A is B | No B is A |
| Some A are **not** B | **only** Some B are not A is NOT valid — nothing follows simply |

**"Possibility" cases:** a conclusion is a possibility unless it *contradicts* a statement. When asked
about possibility, most non-contradictory options are possible — check the negative ones carefully.

## B4. Inequality

**Direct:** $A > B \ge C$ ⇒ $A > C$ (transitivity holds only when the symbols point the same way).
- Same direction ⇒ relation definite
- Opposite directions ⇒ **either-or** case
- $\ge$ / $\le$ pairs ⇒ can conclude $\ge$ or $\le$

**Coded:** decode one symbol at a time into $>, <, \ge, \le, =$, then run the direct method.

**"Either-or"** applies when two conclusions are complementary:
$A > B$ and $A \le B$ — exactly one must be true.

## B5. Blood Relations

**Symbols (coded form):** build a **generation tree**, not a sentence.
- Males: □ / + ; Females: ○ / −
- Vertical = parent-child, horizontal = siblings/spouse

**Key vocabulary:** *maternal* = mother's side, *paternal* = father's side. *Niece/nephew* = sibling's
child. *Sister-in-law* = spouse's sister **or** sibling's wife. *Only son* = the sole son (siblings may
be daughters).

**[nb]** Gender is often **not determined** — if the stem never fixes a person's sex, "uncle or aunt"
is the honest answer (set 8 Q2–Q4).

## B6. Direction Sense

Track $(x, y)$ with north $= +y$, east $= +x$. At each turn:

| Facing | Left turn | Right turn |
|---|---|---|
| East | North | South |
| North | West | East |
| West | South | North |
| South | East | West |

**Shortest distance** $= \sqrt{\Delta x^2 + \Delta y^2}$ — expect clean Pythagorean triples (3-4-5,
5-12-13, 8-15-17, 7-24-25). If you don't get one, you mis-stepped.

**[nb]** "Direction of F with respect to L" when $\Delta x = 85, \Delta y = 3$: both components are
non-zero, so **strictly North-east**. The option set often contains both East and North-east — read the
question as written and note the ambiguity rather than silently dropping the small offset.

## B7. Coding-Decoding

1. **Letter shift** (+n / −n, alternating)
2. **Position-value arithmetic** (A = 1 … Z = 26)
3. **Reversal** (last letter first, etc.)
4. **Conditional / conditional-on-vowel** rules (encode differently if a vowel is present)
5. **Symbol substitution** — assign each letter a symbol from two examples and solve simultaneously

**Technique:** write the plain word and the code **letter-by-letter in columns**, then look for which
letters changed.

## B8. Machine Input-Output

The rule is always one of:
- **Sorting numbers ascending/descending**, taken one or two per step from the **left end**
- **Sorting words alphabetically**, taken from the **right end**
- Numbers and words interleaved (numbers right, words left, or alternating)
- A **transformation** applied while moving (e.g. odd −5, even +3; or reversing letters)

**Method:** reproduce the given steps exactly first. If your rule reproduces all the illustration
steps, it is right — then apply it to the new input.

**[nb]** Set 7's machine rule was "numbers leave in descending order (odd −5, even +3) to the **left**
end; words leave alphabetically, rewritten as vowels-sorted + consonants-sorted, to the **right** end."
All five illustration strings reproduced exactly before it was trusted.

## B9. Letter / Digit Pair questions

**"Same gap as the alphabet"** — a pair qualifies when
$$|\text{position in word difference}| = |\text{alphabetical value difference}|$$
Count **all 28 pairs**; it is almost never more than 2–3.

**Alphabetical order:** compare position by position and count unchanged slots — do not eyeball.

**Word formation (nth letters → meaningful word):** extract the letters, then check anagram families.
A single shared letter set can only make one real word in most cases.

**Odd one out (letter groups):** check the pattern of **gaps** between consecutive letters (+3, −5
stays constant across the group). The odd one breaks the gap pattern.

## B10. Data Sufficiency

Answer options are fixed, so the decision tree is mechanical:

| Situation | Answer |
|---|---|
| I alone sufficient | (a) |
| II alone sufficient | (b) |
| Each alone sufficient | (c) |
| **Both together** sufficient, neither alone | (d) |
| Even together insufficient | (e) |

**Rule:** stop the moment you have *enough* — do not solve fully. Test each statement independently
**first**, then jointly. Never use statement I's data while judging statement II alone.

## B11. Statement-based Reasoning

**Assumption** — an unstated premise the argument *needs*. Test by negating it: if the argument
collapses, it was an assumption.
**Conclusion / Inference** — must follow from the passage **alone**, with no outside knowledge.
**Course of Action** — must be a *practical, feasible, relevant* step that addresses the problem.
**Strong Argument** — must be relevant to the issue, and give a reason (not just an assertion).
**Cause & Effect** — identify which event is the cause independently, not which is mentioned first.

---

# PART C — ENGLISH

## C1. Error Spotting — checklist, run in this order

1. **Subject–verb agreement** — ignore parenthetical phrases: *"The manager, along with his
   assistants, **was** present."* The verb follows the **first** subject.
   - *Either/or, neither/nor* → verb agrees with the **nearer** subject
   - *Each, every, everyone, nobody* → **singular**
2. **Tense consistency** — a past-tense sentence stays past unless the logic requires a shift.
3. **Articles** — *a* before consonant sounds, *an* before vowel **sounds** (an hour, a university).
4. **Prepositions** — the highest-yield trap. Memorise collocations: *comprise* (no "of"),
   *superior to*, *prefer to*, *comply with*, *consist of*, *despite* (no "of").
5. **Parallelism** — items in a list share the same form (all gerunds, or all infinitives).
6. **Degree of comparison** — never double: *"more better"*, *"most best"* are wrong.
7. **Pronoun agreement** — *"Students … who"* (people), not *"which"*.
8. **Countable vs uncountable** — *much* + uncountable, *many* + countable, *fewer/little* correctly.
9. **Redundancy** — *"return back"*, *"discuss about"*, *"revert back"*.

**[nb]** In set 7 Q21: *"youth **which** are currently facing unemployment"* → **who**, because youth
refers to people.

## C2. Sentence Rearrangement / Para Jumbles

**Find the opener** — the sentence that stands alone: no pronoun without antecedent
(it, this, they), no connector (however, therefore, thus), introduces the topic.

**Then chain by:**

| Signal | Action |
|---|---|
| Pronoun (this, it, these) | must follow its **antecedent** |
| *However / But / Whereas* | must follow the clause it **contrasts** |
| *Therefore / Hence / Thus* | near the **end** |
| *On one hand … On the other hand* | the pair must be in that order, other sentence between them |
| *Furthermore / Moreover / Also* | continues the **same** idea, never opens |
| Chronology / general → specific | order follows |

**Final check:** the last sentence is normally evaluative or conclusive, not a new detail.

## C3. Cloze Test

Read the sentence around the blank and ask **two** questions: (i) what part of speech is needed?
(ii) what is the tone (positive / negative / neutral)?

- A blank after *feel / is / are* needs an **adjective**, not a noun — this alone eliminates options
- Match the **collocation** (offer guidance, foster relationships, critical for)
- Choose by **sense**, never by length or familiarity

## C4. Phrase / Word Replacement

The replacement must fit **both** grammar and meaning, and keep the sentence's original intent.

- **"since twenty years" → "for twenty years"** (since + point in time, for + duration)
- **"an year" → "a year"**, **"one of my friend" → "one of my friends"**
- Keep the **tense** of the surrounding clause
- **"so ... as" → "so ... that"** when expressing result

## C5. Phrasal Verbs (high-frequency for these papers)

| Verb | Meaning | Verb | Meaning |
|---|---|---|---|
| put off | postpone | give in | surrender |
| call off | cancel | look into | investigate |
| bring about | cause | carry out | execute |
| come across | find by chance | put up with | tolerate |
| break down | stop working | take after | resemble |
| turn down | reject / reduce | get along | have a good relationship |

## C6. Synonyms & Word Usage

Learn by **root**, not by list: *bene-* good, *mal-* bad, *ver-* truth, *cred-* believe, *dict-* speak,
*scrib-* write, *path-* feeling.
**Word usage** questions test whether a word is used in its **correct sense and part of speech** — check
the register (formal/informal) as well as the meaning.

## C7. Reading Comprehension

1. Read the **questions first**, then the passage — you will know what to look for.
2. **Fact** questions: locate and match wording, but beware of **paraphrase traps** — the right answer
   is usually a rewording, not a copy.
3. **Inference**: must follow from the passage alone. If it needs outside knowledge, it is wrong.
4. **Tone / author's purpose**: adjectives in the passage decide it. Match the *degree* — "critical" is
   not the same as "hostile".
5. **Vocabulary in context**: substitute your option back into the sentence and re-read.
6. **"EXCEPT" / "NOT true"** — reverse your checking: three options must be verifiably in the passage.

## C8. Match the Columns / Odd One Out (phrases)

Check grammar **and** logic of each fragment pair. A fragment starting with *that / which / who* needs
an antecedent noun; one starting with *at / of / with* needs the preceding word to take that preposition.

**[nb]** These questions are frequently defective — the grammatically best matching is sometimes absent
from the options entirely. Reason to the best available option and note the defect rather than forcing.

---

# Exam-day arithmetic

- **Squares to 40, cubes to 15, tables to 20, reciprocals to 1/20** — these carry approximation,
  simplification, DI and series.
- **Percent ↔ fraction** conversions above.
- **Pythagorean triples**: (3,4,5) (5,12,13) (8,15,17) (7,24,25) (20,21,29).
- **Prime squares** (used in set 1 Q77): 11²=121, 13²=169, 17²=289, 19²=361, 23²=529, 29²=841.
- **Inverse-square-style sequences** appear often — check the difference against this list first.

---

## Caveats about these sources

- **The eight sets carry no answer key.** Every worked answer in `pr/` is a derivation, tagged
  `[VERIFIED]`, `[JUDGEMENT CALL]`, `[BROKEN SOURCE]` or `[AMBIGUOUS STEM]`. See `REPAIR_BRIEF.md`.
- **The exam pattern is unverified.** Whether negative marking applies, the duration and the section
  weights are not settled by any public source — do not plan around an assumed pattern.
- **Non-technical (aptitude/reasoning/English) is out of scope for the `/iocl` coach**, which covers
  the technical paper only. This sheet exists separately for the IBPS-style sets.
