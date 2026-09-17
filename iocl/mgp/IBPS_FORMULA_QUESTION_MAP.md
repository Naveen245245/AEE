# IBPS / IOCL Non-Technical — Formula → Question-Variety Map

Companion to [IBPS_FORMULA_SHEET.md](IBPS_FORMULA_SHEET.md). The sheet gives you the **formulas**;
this page gives you **how each formula is actually asked** across the eight sets in `pr/`.

Built by inventorying all **799 questions** (sets 1–6 = 100 each, set 7 = 84, set 8 = 115).

> **Provenance:** the source PDFs in `pr-pdf/` ship **without an answer key**. Every answer in `pr/`
> is a derivation tagged `[VERIFIED]` / `[JUDGEMENT CALL]` / `[BROKEN SOURCE]` / `[AMBIGUOUS STEM]`.
> See [REPAIR_BRIEF.md](REPAIR_BRIEF.md). Items tagged broken/ambiguous are excluded from the tables
> below and indexed in §D.

**How to use it:** a formula you can write down is worth marks only if you recognise it wearing a
costume. Each section below lists the costumes that actually appeared, so you can drill *recognition*
rather than re-deriving the same base formula.

---

# §0 — Coverage matrix: what each set actually tests

Read down a column to see a set's shape; read across a row to see how widely a topic is used.

| Topic | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| **A1** % & Fractions | ● | | | ● | | ● | | ● |
| **A2** Profit & Loss | ● | ● | ● | ● | ○ | ● | | |
| **A3** SI & CI | ● | ● | ● | ● | ● | ● | | |
| **A4** Ratio & Partnership | ● | ● | ● | ● | ● | ● | | |
| **A5** Average & Ages | ● | ● | ● | ● | ● | ● | | |
| **A6** Time & Work | ● | ● | ● | ● | ● | ● | | ● |
| **A7** Speed, Distance & Time | ● | ● | ● | ● | ● | ● | | |
| **A8** Mixtures | ● | | ● | ● | ● | ● | | |
| **A9** Number Series | ● | | ● | ● | ● | ● | ● | ● |
| **A10** Quadratic Comparison | | ● | | ● | ● | ● | | |
| **A11** Approximation | ● | ● | ● | | | | | |
| **A12** Mensuration | ● | | ● | ● | | ● | | |
| **A13** Set Theory (Venn) | | | | | ● | | | |
| **A14** Data Interpretation | ● | ● | ● | ● | ● | ● | ● | ● |
| **A15** "Can't be determined" | | ● | | | ● | | | |
| **B1** Seating & Arrangement | | ● | ● | ● | ● | ● | ● | ● |
| **B2** Floor / Box / Month Puzzle | ● | ● | ● | ● | ● | ● | | ● |
| **B3** Syllogism | ● | ● | | ● | ● | ● | ● | |
| **B4** Inequality | | ● | | ● | ● | | | ○ |
| **B5** Blood Relations | ● | ● | ● | | ● | | | ● |
| **B6** Direction Sense | ● | | | ● | ● | | | ● |
| **B7** Coding-Decoding | | | ● | ● | | | | |
| **B8** Machine Input-Output | | | | | | | ● | ● |
| **B9** Letter / Digit Pair | ● | ● | ● | ● | ● | ● | | |
| **B10** Data Sufficiency | | | | | | | ● | |
| **B11** Statement-based Reasoning | | | | | | | ● | ● |
| **C1** Error Spotting | ● | ● | ● | ● | ● | ● | ● | ● |
| **C2** Para Jumble | ● | ● | ● | ● | ● | | ● | ● |
| **C3** Cloze Test | ● | ● | ● | ● | | | | ● |
| **C4** Phrase / Word Replacement | ● | ● | | ● | | ● | ● | ● |
| **C5** Phrasal Verbs | ● | | ● | | | | | |
| **C6** Synonyms & Word Usage | | ● | ● | ● | ● | ● | | ● |
| **C7** Reading Comprehension | ● | ● | ● | ● | ● | ● | ● | ● |
| **C8** Match Columns / Odd One Out | ● | ● | | | | | | ● |

● = present · ○ = present but `[BROKEN SOURCE]`

**What the matrix tells you:**

1. **Only four topics appear in all eight sets: A14 (DI), C1 (Error Spotting) and C7 (RC)** — plus
   A14's cousin B1 in seven. These are the spine of the paper.
2. **Set 7 is a different exam.** It is the only set with B10 (Data Sufficiency, 15 questions) and
   one of only two with B8 and B11. It also drops A6, A7, A8, A10, A11, A12 entirely and has no
   puzzles at all. Do not treat it as representative.
3. **Set 8 is the longest (115 Q) and the puzzle-heaviest** — three full circular/linear blocks.
4. **A11 (Approximation) lives only in sets 1–3**, A13 (Venn) only in set 5, B7 only in 3–4.
   If you drill only one or two sets you will never see these.

---

# §A — QUANTITATIVE APTITUDE

## A1 — Percentages & Fractions

**Core:** successive change $= x + y + \frac{xy}{100}$ (signed) · reverse % $=$ value $\div (1 \pm r)$

| # | How it is asked | Where |
|---|---|---|
| 1 | **Chained deductions on a shrinking base** — deduct %, then % *of the remainder*, then again; back-solve income from the savings left. | S1 Q87, S4 Q63 |
| 2 | **Two fractions taken on the *same* post-deduction base** (not nested) — the trap is compounding them when you shouldn't. | S6 Q48 |
| 3 | **% of a total after a ratio split** — passed/failed classes, males in ratio 1:3. | S8 Q79, S8 Q80 |
| 4 | **% as a ratio of two summed groups** — $\sum A / \sum B \times 100$ over two data rows. | S8 Q49 |

**Coaching line:** the only real decision is *"is this percentage taken on the original or on the
remainder?"* Write the base next to each percentage before you compute anything.

## A2 — Profit & Loss

**Core:** $SP = MP(1-d)$ · $MP = CP(1+m)$ · $SP = CP(1+m)(1-d)$ · same SP at $\pm x\%$ ⇒ loss $\left(\frac{x}{10}\right)^2\%$

| # | How it is asked | Where |
|---|---|---|
| 1 | **Markup and discount both survive to a stated profit** — solve $CP(1+m)(1-d) = CP + \text{profit}$. | S1 Q75 |
| 2 | **Markup rate itself is the unknown** (e.g. $2R\%$), loss % and SP given → back out both. | S1 Q76 |
| 3 | **Discount defined relative to a variable** — discount is $d\%$, loss is $(d-11)\%$; second article's profit $= 1.5d\%$. Two unknowns, two equations. | S4 Q37, S3 Q92 |
| 4 | **Two-stage sale** — sold at loss first, then re-sold at profit; discount measured against MP of the *second* stage. | S2 Q96 |
| 5 | **Chained CP→SP across two items** — chair's CP equals table's SP; total profit given. | S6 Q55 |

**Coaching line:** when the discount/markup rate is itself a variable, the question is simultaneous
equations, not a profit formula. Count the unknowns before choosing a method.

## A3 — Simple & Compound Interest

**Core:** $SI = \frac{PRT}{100}$ · $CI = P\left[(1+\frac{R}{100})^T - 1\right]$ · $CI - SI = \frac{PR^2}{10^4}$ (2 yr)

| # | How it is asked | Where |
|---|---|---|
| 1 | **SI on one principal = CI on another** (+ a constant) — two principals, equate and solve. | S1 Q93, S3 Q88 |
| 2 | **Principal of the CI leg is a multiple of the SI leg** (2×) — same formula, different base. | S5 Q54 |
| 3 | **Rate switches midway** — $SI = P(r_1t_1 + r_2t_2)$; put to you as a Quantity I vs II comparison. | S1 Q98 |
| 4 | **SI on the CI-matured amount** — *sequential*, not parallel: compound first, then simple on the result. | S4 Q38 |
| 5 | **Difference of the two interests is the given**, principal sought. | S2 Q97 |
| 6 | **Same principal, two rates × two times** (9%/3 yr vs 8%/4 yr) — pure substitution. | S6 Q53 |

**Coaching line:** variant 4 is the trap. Read whether the second interest is charged on the
*original* principal or on the *amount*. One word changes the answer.

## A4 — Ratio, Proportion & Partnership

**Core:** $P_1:P_2 = (C_1T_1):(C_2T_2)$

| # | How it is asked | Where |
|---|---|---|
| 1 | **Capital withdrawn / changed mid-period** — one partner invests for only part of the year. | S1 Q94, S2 Q92, S4 Q62, S3 Q89 |
| 2 | **One capital is the unknown**, other capitals and the profit split given. | S1 Q94, S5 Q47 |
| 3 | **One capital replaced mid-year** with a different expression ($5X-400$ then $5X-200$). | S4 Q62 |
| 4 | **Unequal months across three partners** (6/12/6), largest share asked. | S6 Q46 |
| 5 | **Ratio derived from a mean** — A's wins derived from avg(A lost, B won); the ratio is a *by-product*, not given. | S3 Q96–Q100 |
| 6 | **Extra entities bolted on** — D lost $= 1.25 \times$ A lost, D won $=$ C won$/2 + 5$. | S3 Q99 |

**Coaching line:** the set-3 block (Q96–Q100) is the hardest form here — you are not given a ratio
at all, you must *manufacture* one before the partnership formula applies.

## A5 — Average & Ages

**Core:** $\text{Sum} = \text{Avg} \times n$ · ratio-to-age: $\frac{ax+t}{bx+t} = \frac{c}{d}$

| # | How it is asked | Where |
|---|---|---|
| 1 | **Subgroup average from the overall average** — girls' average from class total minus boys. | S1 Q95, S3 Q94 |
| 2 | **Mean of an excluded group** — 30 students at 40, 24 boys at 36 → mean of the excluded girls. | S3 Q94 |
| 3 | **Ratio + a time-shifted relation** — 3:2 now, five-years-ago relation, future sum equals a third person's age. | S1 Q96 |
| 4 | **Shift-then-sum**: sum after 10 years given, present difference asked. | S6 Q50, S5 Q46 |
| 5 | **Average of consecutive integers/evens = middle term** — two such sets compared with a fixed offset. | S1 Q97 |
| 6 | **An entrant changes the average** — new member $= \text{avg}' \times (n+1) - \text{avg} \times n$. | S1 Q100 |
| 7 | **Ages built from pairwise linear relations** — $P=2(Q-4)$, $R=(P+Q)/2$, $R-16=10$. | S3 Q87 |
| 8 | **Age expressions in two variables** — man $3p+2q$, son $p$, daughter $q$, $p = q+3$. | S4 Q64 |

**Coaching line:** variants 5 and 7 are the discriminators. Consecutive-number averages are a
*one-liner* if you see them — the middle term — and a two-minute slog if you don't.

## A6 — Time & Work

**Core:** $\frac{1}{A} + \frac{1}{B} = \frac{1}{T}$ · efficiency $\propto \frac{1}{\text{time}}$

| # | How it is asked | Where |
|---|---|---|
| 1 | **Work given as a percentage or fraction, not days** — 40% in 8 days, 2/3 in 2 days, 25% in 7 days. | S1 Q90, S4 Q40, S6 Q54 |
| 2 | **Efficiency stated as "x% more efficient"** — this means time ratio, not a rate multiplier. | S3 Q86, S5 Q53 |
| 3 | **Chained efficiencies** — Ritu 60% > Rakesh, Rahul 12.5% < Ritu; three-person combined. | S5 Q53 |
| 4 | **Two unknowns (men and women efficiencies)** — solve simultaneous gang equations. | S2 Q98 |
| 5 | **Men-day equivalence** — $M_1D_1 = M_2D_2$ across three worker types; 30 women replaced by 8 men. | S8 Q74–Q78 |
| 6 | **Discharge-rate framing** — battery capacity/rate instead of persons/days; answer as clock time. | S8 Q46–Q50 |

**Coaching line:** "300% more efficient" means $C = 4B$, not $C = 3B$. This exact trap appears at
S3 Q86.

## A7 — Speed, Distance & Time

**Core:** $D = ST$ · equal distances: $\text{avg} = \frac{2s_1s_2}{s_1+s_2}$ · boat: $B = \frac{D+U}{2}$, $S = \frac{D-U}{2}$

| # | How it is asked | Where |
|---|---|---|
| 1 | **Trains: one crosses a platform, another a pole** — sum of lengths from two separate crossings. | S1 Q88 |
| 2 | **Train overtakes a moving person/athlete** → $L = (v-u)t$, then platform crossing gives the rest. | S2 Q95 |
| 3 | **Two trains, same direction** — relative speed supplies the equation that yields one train's length. | S3 Q90 |
| 4 | **Train length expressed via $x$** — pole in $x$, platform in $x+9$, then a dog; answer is an expression. | S4 Q60 |
| 5 | **Stream speed changed by a percentage** mid-question (raised 80%), then new distance. | S1 Q92 |
| 6 | **Upstream:downstream ratio given**, one leg's time given → speeds, then a new distance. | S5 Q51, S6 Q52 |
| 7 | **Common unknown time on both legs** — 90 km in $t$, 72 km in $t+1$. | S4 Q59 |
| 8 | **Average speed compared against the slower leg** — the harmonic-mean trap. | S5 Q52 |
| 9 | **Bike $= 0.9 \times$ car, and the *car* takes longer** — the wording reverses the intuitive assumption. | S6 Q49 |

**Coaching line:** variant 8 is the single highest-frequency trap in this topic across the sets —
the average of two speeds is *never* the arithmetic mean.

## A8 — Mixtures & Alligation

**Core:** $\text{Final pure} = P\left(1-\frac{x}{V}\right)^n$ · alligation $\frac{q_1}{q_2} = \frac{c_2-c_m}{c_m-c_1}$

| # | How it is asked | Where |
|---|---|---|
| 1 | **Add one component to hit a target ratio** — water only, target 1:1. | S1 Q89 |
| 2 | **Remove $Y$ (both components pro-rata), then add both milk and water** to a new ratio. | S1 Q99 |
| 3 | **Removal preserves the ratio** — add 25 L milk so milk is 400% more than water (i.e. 5×). | S5 Q48 |
| 4 | **Draw off a fraction, top up with a *mixture*** — 75% drawn, 40 L of 40% milk added. | S4 Q39 |
| 5 | **Unknown amount added** — solve for water $x$ in the added 60 L; final milk $= 2 \times$ water. | S4 Q65 |
| 6 | **Two vessels linked multiplicatively** (B milk $= 1.2 \times$ A milk) — *not* alligation, just ratio chaining. | S3 Q93 |
| 7 | **Find the volume removed** — final 3:2 after adding 18 L water. | S6 Q51 |

**Coaching line:** the pivotal question is always *"what does removal take out?"* — it takes the
mixture in its current ratio, never the pure component.

## A9 — Number Series

**Core:** the 8-step pattern checklist in the sheet (§A9). Run it in order, every time.

| # | Pattern actually used | Where |
|---|---|---|
| 1 | **Differences are squares of consecutive primes** | S1 Q77, S5 Q42 |
| 2 | **Differences are consecutive primes** (subtracted) | S3 Q80, S6 Q33, S4 Q35 |
| 3 | **Second-order differences linear** ($+2,+3,+4,\dots$) | S5 Q41, S6 Q35, S4 Q32 |
| 4 | **Second difference constant** (e.g. $+1.2$) | S7 Quant Q7–Q10 |
| 5 | **Alternating sign multiples of 11** ($-11,+22,-33$) | S3 Q76 |
| 6 | **Pure geometric** ($\div 3$ chain) | S3 Q77 |
| 7 | **Consecutive odd multipliers** ($\times3,\times5,\times7$) | S5 Q45 |
| 8 | **Fractional multipliers rising by 1** ($\times1.5,\times2.5,\dots$) | S6 Q31 |
| 9 | **$a_n = a_{n-1}\cdot 2 + 1$ constant** | S6 Q32 |
| 10 | **Alternating $-n^2$, $+n^3$** | S6 Q34 |
| 11 | **Differences $= n^2+1$** (odd squares) | S4 Q33 |
| 12 | **Difference recursion** $d_n = 2d_{n-1}+1$ | S4 Q34 |
| 13 | **Successive division by $10/n$** | S4 Q36 |
| 14 | **Odd multiples of 7** ($7,21,35,49$) | S5 Q43 |
| 15 | **Decimal increment** ($+1.5,+3,+4.5$) | S5 Q44 |
| 16 | **Two interleaved difference runs** | S3 Q78 |
| 17 | **Wrong-term format** (find the term breaking the rule) | most of the above |
| 18 | **Blank-in-the-middle** vs **blank-at-an-end** — different search order | S4 Q32–Q36 |

**Coaching line:** two formats, two strategies. **Wrong term** → test each option by substitution
against the rule *all others* satisfy. **Missing term** → build the rule from the known terms first,
and note that a blank at the *start* usually means the rule is multiplicative (variant 7, 8, 13).

## A10 — Quadratic Equations (Quantity I vs II)

**Core:** factorise both, compare **root by root** — the table in the sheet (§A10) is the whole method.

| # | How it is asked | Where |
|---|---|---|
| 1 | **Root ranges fully disjoint** — every $x$ root beyond every $y$ root → clean $<$ or $>$. | S2 Q66, S2 Q67, S5 Q31, S6 Q45 |
| 2 | **A repeated (perfect-square) root** in one equation — $x^2$ has a double root. | S4 Q41, S4 Q43 |
| 3 | **A shared root** — one root common to both; this alone forces $\le$ or $\ge$. | S2 Q68, S4 Q44, S5 Q32, S5 Q33, S6 Q41, S6 Q43 |
| 4 | **Roots point both ways** → **no relation / can't be determined**. | S4 Q42, S5 Q34, S5 Q35, S6 Q42, S6 Q44 |
| 5 | **Fractional roots** ($4/3$, $19/3$, $1.5$) that sit close to the other equation's roots. | S6 Q42, S5 Q35, S4 Q43 |
| 6 | **All roots negative** — sign handling alone decides the option. | S2 Q69 |
| 7 | **Large $|ac|$ products** ($221$, $132$) — factorisation speed test. | S6 Q44 |

**Coaching line:** 4 of the 19 questions here answer **"no relation / can't be determined"**. When
one root of I is bigger and one is smaller, stop — that *is* the answer. Do not hunt for a relation
that isn't there.

## A11 — Approximation & Simplification

**Core:** round to convenient numbers, then strict BODMAS — but **map the structure of the equation
before computing**.

| # | How it is asked | Where |
|---|---|---|
| 1 | **Unknown isolated on one side of "="** — read the equals sign position first. | S1 Q84, S2 Q70 |
| 2 | **Nested fraction inside the numerator** — flat reading changes the answer. | S1 Q85 |
| 3 | **Squared denominator** in a division term. | S1 Q82 |
| 4 | **Unknown appears squared** ($?^2 - 16$). | S3 Q84, S2 Q71 |
| 5 | **Unknown is a subtrahend** (LHS − ? = RHS). | S2 Q72 |
| 6 | **Unknown multiplied by a percentage-of term**. | S2 Q73 |
| 7 | **The unknown IS the percentage** (what % of 60…). | S2 Q70 |
| 8 | **Odd percentage** (319.87%) with a ×5.99 multiplier. | S1 Q86 |
| 9 | **Rounding direction matters** — 28.86 must go *up* to 29 to hit any option. | S1 Q83 |
| 10 | **Two separate percentages of different round numbers, summed**. | S3 Q81 |
| 11 | **Divisor chain** — $(\sqrt{\ } + \text{fraction}) \div$ a two-digit decimal. | S3 Q82 |

**Coaching line:** this topic is 80% *structure reading*, 20% arithmetic. Before rounding anything,
rewrite the equation with the unknown boxed and the operations in order.

## A12 — Mensuration

**Core:** rectangle $A = LB$, $P = 2(L+B)$, circle/cylinder per the sheet.

| # | How it is asked | Where |
|---|---|---|
| 1 | **Purely symbolic** — $l = 1.2b$, square's side = breadth; answer is a ratio. | S1 Q91 |
| 2 | **Square's side equals the rectangle's length** (shared dimension) with an area ratio given. | S3 Q95 |
| 3 | **One dimension changed at a time**; ask the $P:A$ ratio. | S4 Q61 |
| 4 | **Cylinder CSA/TSA ratio** with $r:h = 7:6$ given. | S6 Q47 |
| 5 | **Path around a rectangle** (from the sheet) — inside vs outside. | — |

**Coaching line:** every mensuration question in these sets is a **ratio** question, not an
area-computation. Set up the algebraic ratio and cancel; never compute actual areas.

## A13 — Set Theory (Venn)

Appears in **one block only** — S5 Q36–Q40, and it is the most instructive block in the paper.

| # | How it is asked | Where |
|---|---|---|
| 1 | **Category A difference**, but the A∩C-only cell is unpinned → **can't be determined**. | S5 Q36 |
| 2 | **B:C ratio given**, but B∩C-only unpinned → **can't be determined**. | S5 Q37 |
| 3 | **Percentage of a single derived "only-A" cell**. | S5 Q38 |
| 4 | **Complement count** — "at most two categories" $=$ total − triple. | S5 Q39 |
| 5 | **Sum of the three "only" cells** expressed as $10x$. | S5 Q40 |

**Coaching line:** two of these five legitimately answer *"can't be determined"*, because the data
fixes the intersection cells only **in sum**. If a question needs an individual cell you were never
given, the answer is not a number.

## A14 — Data Interpretation

**The largest topic in the paper — 8 of 8 sets, 100 questions.** Uses only four formulas:
$\text{part}/\text{whole} \times 100$, $\text{avg} = \frac{\Sigma}{n}$, ratio, and
$\frac{a-b}{b} \times 100$ for % more/less.

| # | How it is asked | Where |
|---|---|---|
| 1 | **Direct read-off** — single bar/cell value. | S8 Q51, Q55; S3 Q69 |
| 2 | **Sum of a row/column across a block**. | S3 Q73, Q74; S8 Q52, Q61, Q65 |
| 3 | **Ratio of two derived cells** (not raw cells). | S1 Q71; S2 Q76, Q83; S5 Q59; S6 Q60, Q61 |
| 4 | **Average of unlike cells** ($\Sigma/3$ across categories). | S1 Q68; S2 Q68, Q77, Q85, Q90; S6 Q38, Q63 |
| 5 | **% = part/whole** across mixed types. | S1 Q67, Q72; S2 Q74, Q89 |
| 6 | **% more / % less between two derived quantities** — the denominator is the *base*. | S2 Q80; S5 Q57, Q62; S6 Q37, Q62; S8 Q54 |
| 7 | **Two-variable simultaneous solve** from the table, then a cost ratio. | S1 Q66; S4 Q52; S2 Q86 |
| 8 | **A hypothetical new entity (shop F / city F / bag F) invented in the question**, built from two conditions on the existing table. | S1 Q70; S2 Q78, Q81, Q88; S4 Q47, Q54; S6 Q39 |
| 9 | **Derived column** — unsold = manufactured − sold; invalid = registered − valid; rejected = applied − accepted. | S1 Q71, Q72; S5 Q61; S7 Quant Q1; S8 Q66–Q70 |
| 10 | **Unit price × count** (revenue), with per-item prices differing. | S1 Q69, Q75; S4 Q49; S6 Q36, Q65 |
| 11 | **Fraction-of-a-cell then a difference** (e.g. $2/5$ of one cell, then subtract). | S3 Q66; S5 Q58; S8 Q57 |
| 12 | **Internal ratio given inside a row** ($X:Y = 3:4$) — the ratio is stated, not read. | S3 Q68; S4 Q53 |
| 13 | **A cell defined by an offset** ($200 + $ another cell; $1.25 \times$; $1.2 \times$). | S3 Q70; S2 Q78; S6 Q39 |
| 14 | **Pie chart: angle ↔ value** ($\frac{\theta}{360} \times$ total). | S8 Q56–Q60 |
| 15 | **Caselet with no chart** — 5 given relations, one aggregate asked. | S2 Q86 |
| 16 | **Answer is exactly 0%** — two cells are identical; the trap is assuming they differ. | S3 Q69; S6 Q56 |
| 17 | **Back-solve an unknown entity from a given average**. | S4 Q48, S5 Q60 |
| 18 | **Multi-stage chain** — 5 steps: tax→income, +25%, ratio 9:10, rent fraction. | S5 Q60 |
| 19 | **"Definitely true" with a bound** — max/min of a difference. | S8 Q64 |

**Coaching line (the biggest single lesson in this whole document):** in the original source files,
**four of the DI blocks had their chart data read one gridline too high** (sets 1, 2, 3 and 5).
Every question in the block then missed every option. The protocol is in the sheet §A14 — find the
baseline, count gridlines between labelled ticks, and **sanity-check by computing a question you can
verify another way**. If three derived answers miss all options, the data is wrong, not your maths.

## A15 — "Can't be determined"

| # | Why it is genuinely the answer | Where |
|---|---|---|
| 1 | **One equation, two unknowns** — $k(8-x) = 25$ admits two integer solutions. | S2 Q93 |
| 2 | **A later year's income is never linked to the earlier one**; the 20% base is unknown. | S5 Q55 |

**Coaching line:** do not force a number because the options contain one. Forcing a value here costs
you the mark you already have.

---

# §B — REASONING

## B1 — Seating & Arrangement

**Core:** the facing table in the sheet §B1 — **left/right invert with facing**. That single table
decides more questions in these sets than every other reasoning rule combined.

| # | How it is asked | Where |
|---|---|---|
| 1 | **Linear row, all facing north** — left = lower index. Direct lookup. | S3 Q20–Q24, S6 Q67 |
| 2 | **Linear row facing south** — left/right reversed (the trap). | S6 Q68 |
| 3 | **Row length itself is unknown** — must be derived from the clue set before any question can be answered. | S2 Q1–Q3, S4 Q98–Q100, S6 Q79 |
| 4 | **Two rows facing each other** — right/left mirror between rows. | S2 Q31–Q35 |
| 5 | **Circular, facing centre** — right = anticlockwise. | S5 Q94, S5 Q95, S8 Q36–Q40 |
| 6 | **Circular, mixed facing (some in, some out)** — per-person flip. | S3 Q1–Q5, S4 Q66–Q70, S8 Q32–Q35 |
| 7 | **Square table with centre/outside mix**. | S4 Q66–Q70 |
| 8 | **Vacant seats in the row** — count *persons*, skipping the gaps. | S8 Q16–Q20 |
| 9 | **A value is attached to each seat** (flowers, ages) — arrange, then map. | S8 Q16–Q20, S5 Q91–Q95 |
| 10 | **"Immediately senior/junior to"** as a positional clue rather than a rank clue. | S8 Q21–Q25 |
| 11 | **Analogy over positions** — $B \to DGM :: D \to ?$; solve the position mapping first. | S2 Q19, S3 Q14, S1 Q35 |
| 12 | **Odd one out by facing direction, not identity**. | S3 Q4, S4 Q66, S5 Q78 |

**Coaching line:** four different answer shapes appear in every block — *direct lookup*,
*count between*, *statement verification*, *odd one out*. Count-between is
$|p_1 - p_2| - 1$; write that expression down rather than counting on your fingers.

## B2 — Floor / Box / Month / Year Puzzles

| # | How it is asked | Where |
|---|---|---|
| 1 | **Floors × flats (P-west / Q-east)** — a 2-D grid, not a line. | S1 Q1–Q5 |
| 2 | **Person × month × colour** triple assignment. | S1 Q14–Q18 |
| 3 | **Months × two dates (9th/26th) × colours** — 6 slots. | S2 Q12–Q16 |
| 4 | **Years ↔ ages** — age $= 2024 - $ year; the mapping is arithmetic, not positional. | S2 Q26–Q30, S3 Q10–Q14 |
| 5 | **Boxes stacked, positional clues**. | S3 Q26–Q30, S4 Q76–Q80, S6 Q87–Q90 |
| 6 | **Month/date/state slots**. | S4 Q84–Q88 |
| 7 | **Grouping, not ordering** — persons → cities, groups only; "who visits with K". | S6 Q75–Q78, S4 Q90–Q94, S8 Q41–Q44 |
| 8 | **Rank ordering + a lettering direction** — 13 boxes, "F = 13-toffee box" fixes the orientation. | S8 Q5–Q8 |
| 9 | **Post hierarchy ordering** (city × designation) with a family tree folded in. | S8 Q21–Q25 |
| 10 | **"Related to" = immediately below** — a euphemism you must decode. | S3 Q29 |
| 11 | **Symmetric above/below condition** → the bottommost item. | S3 Q30, S5 Q70 |

**Coaching line:** the method is in the sheet §B2 — fix the most restrictive clue, branch
explicitly, and **verify every clue at the end**. The sets contain multiple puzzles where the
author's own arrangement contradicted a clue (S5 Q66–Q70 had G and D transposed; S3 Q1–Q5's
arrangement produced no printed option). If your arrangement can't produce any option, the
arrangement is wrong — do not defer to a key that doesn't exist.

## B3 — Syllogism

| # | How it is asked | Where |
|---|---|---|
| 1 | **"Only a few A are B"** → some-are **and** some-are-not. This phrasing dominates. | S1 Q7–Q9, S2 Q22–Q24, S4 Q71, S6 Q73 |
| 2 | **Possibility conclusions** ("can be") — valid unless contradicted. | S1 Q8, S1 Q9, S2 Q22, S4 Q73, S6 Q72 |
| 3 | **A universal-negative conclusion** ("No Gate is Subway") that is *not* forced. | S4 Q71 |
| 4 | **Both conclusions breakable, and not complementary** → neither follows. | S4 Q72, S5 Q73 |
| 5 | **"Only pen is city"** — exclusive wording, only one conclusion follows. | S6 Q74 |
| 6 | **Reverse-engineer the statement set** from given conclusions. | S7 Reas Q1 |
| 7 | **A possibility explicitly destroyed by a negative premise**. | S2 Q23 |

**Coaching line:** the sheet's rule stands — a possibility is valid unless it *contradicts* a
statement. Most wrong answers here come from treating a possibility as invalid because it isn't
forced; that is not the test being applied.

## B4 — Inequality

| # | How it is asked | Where |
|---|---|---|
| 1 | **Two chains joined by a pivot** — neither conclusion decidable. | S2 Q11, S5 Q98, S5 Q99, S4 Q97 |
| 2 | **A conclusion using an entity absent from the statements** — automatic no. | S2 Q10 |
| 3 | **Fully transitive chain** — both conclusions true. | S5 Q100, S4 Q95 |
| 4 | **Shared upper bound only** — $S$ and $L$ both $<$ something, so $S < L$ is not definite. | S2 Q9 |
| 5 | **Numeric inequality symbols**. | S4 Q96 |
| 6 | **Coded symbols that are never defined** — see §D. | S8 Q1 |

**Coaching line:** transitivity holds only when symbols point the same way. Two chains joined by a
pivot is the default shape here — expect "neither follows" more often than "either or".

## B5 — Blood Relations

| # | How it is asked | Where |
|---|---|---|
| 1 | **Three-generation chain**, two-hop link (A → B → C). | S1 Q20 |
| 2 | **In-law mapping must be resolved first** (sister-in-law, daughter-in-law). | S1 Q21, S2 Q6, S5 Q80 |
| 3 | **Gender count** — count males/females, not relationships. | S1 Q22, S2 Q7, S8 Q4 |
| 4 | **Gender deliberately unfixed** → "uncle or aunt", undeterminable. | S8 Q2 |
| 5 | **"Opposite gender" clue** — one gender derived indirectly. | S2 Q7 |
| 6 | **Paternal vs maternal line** decides the label. | S5 Q81, S3 Q7 |
| 7 | **Coded relation symbols** (+ @ # etc.). | S8 Q2–Q4 |
| 8 | **"Only niece" forces the remaining genders**. | S8 Q4 |

**Coaching line:** *sister-in-law* has **two** meanings (spouse's sister **or** sibling's wife).
If the stem doesn't disambiguate, that ambiguity is usually the point.

## B6 — Direction Sense

| # | How it is asked | Where |
|---|---|---|
| 1 | **Coordinate tracking with turns** — $\sqrt{\Delta x^2 + \Delta y^2}$. | S1 Q29, S4 Q81 |
| 2 | **"Direction of X w.r.t. Y" where BOTH components are non-zero** → strictly north-east, and the options contain both "East" and "North-east". | S1 Q28, S5 Q88 |
| 3 | **Mid-path consecutive left turns** of a small distance — the small offset is the whole question. | S1 Q28 |
| 4 | **Odd one out over point pairs** — four pairs aligned one way, one the other. | S1 Q30, S8 Q14 |
| 5 | **A point injected in the question** that never appeared in the setup. | S5 Q89, S8 Q13 |
| 6 | **Sum of path lengths** vs displacement — distance travelled ≠ displacement. | S5 Q87 |
| 7 | **Coded directions with two lengths each**. | S8 Q12–Q14 |

**Coaching line:** if your displacement isn't a clean Pythagorean triple (3-4-5, 5-12-13, 8-15-17,
7-24-25), you mis-stepped — go back. And read "direction of F w.r.t. L" literally: $\Delta x = 85,
\Delta y = 3$ is **north-east**, not east.

## B7 — Coding-Decoding

Appears only in **sets 3 and 4**.

| # | How it is asked | Where |
|---|---|---|
| 1 | **Word-overlap intersection** — two words share a code pair; solve simultaneously. | S3 Q15, S3 Q17, S4 Q74 |
| 2 | **Hypothetical reassignment** ("jar = uh") then code a new phrase. | S3 Q16 |
| 3 | **Three-word phrase** mixing fixed codes with one swapped. | S3 Q18 |
| 4 | **Reverse direction** — given the code, find the word. | S3 Q19 |
| 5 | **Common-word intersection across three lines** — find the word present in one line only. | S4 Q74 |

**Coaching line:** write the plain word and the code **letter-by-letter in columns**. The
intersection method only works if you can see which letters are common.

## B8 — Machine Input-Output

Appears only in **sets 7 and 8**.

| # | How it is asked | Where |
|---|---|---|
| 1 | **Numbers leave to the LEFT** (descending), **words to the RIGHT** (alphabetical). | S7 Reas Q2–Q6 |
| 2 | **Transformation applied while moving**: odd −5, even +3; vowels-sorted then consonants-sorted. | S7 Reas Q3–Q6 |
| 3 | **Query the intermediate step**, not the final one ("Step V", "Step II"). | S7 Reas Q2, Q3, Q6 |
| 4 | **"Sum of all odd numbers in Step II"** / "square of the 2nd-highest in Step III" — arithmetic *on top of* the machine. | S7 Reas Q3, Q5 |
| 5 | **Word → letter-shift → digit → symbol**, multi-stage final coding. | S8 Q29–Q31 |

**Coaching line:** reproduce every given step exactly *before* trusting your rule. In set 7 the
correct rule reproduced all five illustration strings — that is the standard of proof. A rule that
fits four of five is wrong.

## B9 — Letter & Digit Pairs

| # | How it is asked | Where |
|---|---|---|
| 1 | **"Same gap as the alphabet" over a scrambled number** — exhaustive check of all pairs; usually exactly one hit. | S1 Q6, S2 Q5 |
| 2 | **Same, over a word** — CHAIRMAN; sometimes three hits and the answer is a *count*. | S3 Q31, S4 Q89, S5 Q90 |
| 3 | **Letter-group gap pattern** (+1,+2 / +2,+1,+3) — odd one out breaks the gap. | S1 Q13, S2 Q25, S5 Q86 |
| 4 | **Extract letters by position, then find the word** — two-stage; may ask a letter of the word. | S1 Q19, S3 Q9, S4 Q75, S5 Q96 |
| 5 | **Count of meaningful words**, not the word itself. | S2 Q4, S4 Q75 |
| 6 | **Digit transformation** (odd −1, even −2) then sum the non-repeated. | S6 Q71 |
| 7 | **Alphabetical-order comparison** and count unchanged slots. | S8 Q15 (broken) |

**Coaching line:** "same gap" means
$|\text{position difference in word}| = |\text{alphabetical value difference}|$. Count **all** pairs
mechanically — eyeballing is where these marks are lost.

## B10 — Data Sufficiency

**Appears only in set 7 (Q11–Q25), 15 questions.** Options are fixed, so the tree in the sheet §B10
is fully mechanical.

| # | How it is asked | Where |
|---|---|---|
| 1 | **Any ONE statement alone suffices** | S7 Quant Q14, Q17, Q18, Q21, Q23 |
| 2 | **Any TWO together suffice** | S7 Quant Q22, Q24, Q25 |
| 3 | **All three needed** | S7 Quant Q13, Q15 |
| 4 | **Two statements are the SAME fact restated** — a deliberate redundancy trap. | S7 Quant Q19 |
| 5 | **I and III together, or II alone** — mixed-sufficiency shape. | S7 Quant Q11, Q12 |
| 6 | **Only one specific statement works** (CP/SP/total-profit). | S7 Quant Q16 |
| 7 | **Speed alone with either crossing statement**. | S7 Quant Q20 |
| 8 | **Topics drawn from across the syllabus** — mensuration, boats, ages, trains, ratio, work. | all |

**Coaching line:** stop the moment you have *enough*. Do not solve fully. And judge each statement
**independently first, then jointly** — never import statement I's data into your judgement of II alone.

## B11 — Statement-based Reasoning

Appears only in **sets 7 and 8**.

| # | How it is asked | Where |
|---|---|---|
| 1 | **Implicit assumptions** — negate the assumption; if the argument collapses, it was implicit. | S7 Reas Q16–Q20, S8 Q9, S8 Q10 |
| 2 | **Course of action** — must be practical, feasible and relevant. | S7 Reas Q21–Q25, S8 Q26 |
| 3 | **Strong arguments** — must give a *reason*, not an assertion. | S7 Reas Q26–Q29, S8 Q11 |
| 4 | **Inference** — must follow from the passage alone. | S8 Q27 |
| 5 | **Hypothesis** — reject politically-motivated or speculative ones. | S8 Q28 |
| 6 | **Four-argument format** (vs the usual three) — extremes/evidence test. | S8 Q11 |

**Coaching line:** assumption questions are won by **negation** — assume the opposite and see if the
argument survives. If it survives fine, that wasn't the assumption.

---

# §C — ENGLISH

## C1 — Error Spotting

**Appears in all 8 sets** — the highest-frequency English topic.

| # | Error type actually tested | Where |
|---|---|---|
| 1 | **Subject–verb agreement** (singular subject, plural verb; collective nouns) | S3 Q44, S3 Q46, S3 Q54, S4 Q9, S4 Q12, S2 Q23 |
| 2 | **Parenthetical phrase doesn't pluralise** ("along with", "as well as") | S3 Q47, S7 Eng Q24, S7 Eng Q27 |
| 3 | **Correlative agreement** ("neither…nor" takes the nearer subject) | S3 Q54, S7 Eng Q25 |
| 4 | **Tense consistency / sequence of tenses** | S4 Q10, S6 Q19 |
| 5 | **Past-time adverbial requires a finite past verb** ("on Friday") | S6 Q20, S6 Q21 |
| 6 | **Past perfect for the earlier of two past acts** | S6 Q22 |
| 7 | **Infinitive after "to"** | S4 Q11, S2 Q61 |
| 8 | **Conditional / third conditional** ("If I would have known") | S3 Q47, S3 Q48 |
| 9 | **Parallelism** (gerund must pair with gerund) | S2 Q62 |
| 10 | **Article before a vowel sound** | S2 Q64 |
| 11 | **Preposition collocation** ("Despite of") | S3 Q55, S7 Eng Q22 |
| 12 | **Pronoun agreement** ("youth **which**" → who) | S7 Eng Q21 |
| 13 | **Auxiliary form** ("have being" → have been) | S2 Q65 |
| 14 | **Wrong part of speech** (noun where verb required) | S3 Q56 |
| 15 | **Punctuation** (stray comma) | S8 Q92 |
| 16 | **No error at all** — the honest option | S3 Q57, S4 Q13, S6 Q22, S6 Q23 |
| 17 | **"Pick the error-free sentence"** format (no error type given) | S1 Q48–Q51, S5 Q15–Q19 |

**Coaching line:** run the 9-point checklist in the sheet §C1 **in order**. Items 12, 13, 15 and 16
are the ones this bank adds beyond the usual list — and note that 4 of the sets ask the *inverted*
format where you pick the clean sentence, which you cannot solve by finding an error.

## C2 — Para Jumble

| # | How it is asked | Where |
|---|---|---|
| 1 | **Full sequence asked** | S5 Q14, S5 Q30 |
| 2 | **Single position asked** — "which is FIRST / SECOND / THIRD / FOURTH / FIFTH" | S2 Q50–Q54, S3 Q49–Q53, S4 Q17–Q21, S5 Q10–Q13, S5 Q28–Q29, S8 Q96–Q100 |
| 3 | **"Which / Whereas / However" as the hinge** — must follow the clause it contrasts | S1 Q36, S1 Q38 |
| 4 | **Pronoun antecedent chain** ("This" binds B to A) | S1 Q37, S4 Q18 |
| 5 | **"Therefore" forces the last position** | S1 Q37, S3 Q53 |
| 6 | **Correlative pair** ("On one hand … on the other hand") | S1 Q39 |
| 7 | **Already coherent → no rearrangement required** | S7 Eng Q11, S8 Q98 |
| 8 | **Fragment assembly** (parts of ONE sentence, not separate sentences) | S7 Eng Q8–Q12 |
| 9 | **"Published in 2000" participial opener** | S8 Q96 |

**Coaching line:** the position-asking format (variant 2) is the dominant one and it is *easier* —
you only need to fix one sentence's place, not the whole order. Find the opener, then find the
sentence that must follow it.

## C3 — Cloze Test

| # | How it is asked | Where |
|---|---|---|
| 1 | **Single blank, collocation decided** ("critical for", "profound impact") | S1 Q52–Q57, S3 Q58–Q62, S2 Q45–Q49 |
| 2 | **Part of speech decides it** — a blank after *feel* needs an adjective, not a noun | S1 Q53, S2 Q45 |
| 3 | **Two-blank items** — adverb + participle, adjective + noun, noun + adverb, verb + adjective | S4 Q22–Q25 |
| 4 | **Parallel form agreement** (must match "builds" in "not only … but also") | S1 Q55 |
| 5 | **Blank inside an RC passage**, not a standalone cloze | S3 Q43 |
| 6 | **Idiom/completion** ("threw … into chaos", "bridge the gap") | S3 Q61, S5 Q27 |
| 7 | **7-blank passage** — sustain a consistent register across all seven | S8 Q109–Q115 |
| 8 | **Sense-reversed distractors that are grammatical** ("constrain" vs "enforce") | S2 Q48, S2 Q49 |

**Coaching line:** ask **two** questions of every blank — (i) what part of speech, (ii) what tone.
That alone eliminates most options before you consider meaning.

## C4 — Phrase / Word Replacement

| # | How it is asked | Where |
|---|---|---|
| 1 | **Swap two word-pairs at once** (A–C and B–D) | S1 Q58, S2 Q56, S4 Q14–Q16 |
| 2 | **Swap one adjacent pair** | S1 Q61, S2 Q55, S2 Q58 |
| 3 | **No swap needed** — the null-swap distractor | S1 Q60, S2 Q57, S4 Q28, S6 Q18, S8 Q105, S8 Q106 |
| 4 | **swap two words across sentences** | S8 Q101–Q104 |
| 5 | **Synonym substitution** (stimulus → relief; hypothesis → assumption) | S6 Q24–Q30 |
| 6 | **"since twenty years" → "for twenty years"** (duration vs point in time) | S7 Eng Q26 |
| 7 | **Phrase correction** (missing preposition, adverb form, SVA inside a phrase) | S4 Q27, S4 Q29, S4 Q30 |
| 8 | **"so … as" → "so … that"** for result | S7 Eng Q30 |
| 9 | **Word-order correctness (A/B/C)** — five questions all answer A-B-C | S6 Q91–Q95 |
| 10 | **A correct form absent from the options** — see §D | S7 Eng Q29 |

**Coaching line:** variant 3 appears **six times**. Before hunting for a swap, check whether the
sentence is already correct — "No rearrangement required" is a live answer, and it is the one
students refuse to pick.

## C5 — Phrasal Verbs

Appears only in **sets 1 and 3**.

| # | How it is asked | Where |
|---|---|---|
| 1 | **One phrasal verb, three contexts** — decide which usages are correct | S1 Q64, S1 Q65, S3 Q63, S3 Q64, S3 Q65 |
| 2 | **All three usages correct** ("bring up", "check out") | S1 Q64, S3 Q65 |
| 3 | **A literal usage among figurative ones** (the sun "comes up") — the literal one breaks it | S3 Q63, S3 Q64 |
| 4 | **Only partly correct** — other contexts need a *different* phrasal verb ("look into", "look over") | S1 Q65 |

**Coaching line:** the test is always *figurative vs literal*. One of the three sentences uses the
verb in its plain physical sense — that is the one that fails.

## C6 — Synonyms & Word Usage

| # | How it is asked | Where |
|---|---|---|
| 1 | **Synonym in passage context** (altered → modified; erosion → decay; allure → attraction) | S5 Q20–Q24, S8 Q91 |
| 2 | **Antonym** (approach → withdraw; build → demolish; vital → trivial; bright → dim) | S3 Q42, S4 Q8, S5 Q8, S6 Q11 |
| 3 | **One word, three uses — pick the valid ones** ("interest", "fellow", "accent", "wind") | S6 Q1–Q3, S4 Q26 |
| 4 | **Idiom used in three sentences** (DARK HORSE; literal use is wrong) | S2 Q60 |
| 5 | **Fill-in-blank forced by a clause** ("so … that" needs magnitude; "Despite" needs a negative) | S5 Q25, S5 Q26 |
| 6 | **Fixed collocation** ("bridge the gap") | S5 Q27 |
| 7 | **Synonym with a multi-option answer** (all three given synonyms correct) | S6 Q13 |
| 8 | **Meaning of a figurative phrase in context** ("blessing in disguise") | S6 Q12 |

**Coaching line:** variant 3 turns on **part of speech**. "Wind" is valid as a verb (to wind a
bandage) and wrong as the two nouns offered — check the grammatical role before the meaning.

## C7 — Reading Comprehension

**Appears in all 8 sets.** Passage topics: economy/startups (S2), sustainability (S3), climate (S4),
rural development (S5), a review (S6), India's progress (S7), inflation + GNH + flexible working (S8).

| # | Question type | Where |
|---|---|---|
| 1 | **Three-statement true/false validation** — the dominant format | S1 Q42, Q43; S2 Q37; S3 Q36, Q38; S7 Eng Q17 |
| 2 | **Identify the INCORRECT / NOT-true statement** — reverse your checking | S2 Q40; S3 Q37; S5 Q5; S6 Q9; S8 Q83 |
| 3 | **Central idea / tone / author's view** | S1 Q40; S3 Q40; S4 Q5; S7 Eng Q18; S8 Q84, Q87 |
| 4 | **Cause / reason / mechanism** | S1 Q41; S2 Q36; S3 Q41; S4 Q1, Q2, Q6; S6 Q5, Q7; S8 Q82 |
| 5 | **Contextual synonym** | S1 Q46, Q47; S2 Q43, Q44; S5 Q6, Q9; S6 Q10, Q13 |
| 6 | **Word replacement in context** ("weather" → climate) | S1 Q45; S2 Q42 |
| 7 | **Vocabulary in context / meaning of a phrase** | S6 Q12; S7 Eng Q16; S8 Q81, Q90 |
| 8 | **Fill a blank embedded in the passage** | S1 Q44; S2 Q41; S5 Q7 |
| 9 | **Direct figure retrieval** — one number | S2 Q39; S7 Eng Q13 |
| 10 | **Application / example matching** — pick the situation illustrating a concern | S2 Q38; S7 Eng Q20 |
| 11 | **Role / significance of a named body** | S3 Q41; S4 Q3, Q4; S8 Q86 |
| 12 | **"All of these" / "None of these"** as the correct option | S5 Q2, Q4; S6 Q7, Q9 |
| 13 | **Inference from a phrase** ("happiness is the end goal") | S8 Q85, Q89 |
| 14 | **Multi-cause** ("All of these") | S6 Q7 |
| 15 | **Antonym in passage** | S5 Q8 |

**Coaching line:** the **three-statement validation** format (variant 1) is the most common single
shape in the paper, and it is scored all-or-nothing on a combination. Treat each statement
independently, mark it T/F, *then* match the combination — never reason backwards from the options.

## C8 — Match the Columns / Odd One Out

Appears only in **sets 1, 2 and 8**.

| # | How it is asked | Where |
|---|---|---|
| 1 | **Clause pairing by grammar and meaning** — only some pairs form a sentence | S1 Q62, S1 Q63, S2 Q59 |
| 2 | **Conditional clause needs its consequence clause** | S8 Q93 |
| 3 | **Paired past verbs lock the match** ("created and fed") | S8 Q94 |
| 4 | **Preposition needs its agent** ("by" + agent; "keen on" + gerund) | S8 Q95 |
| 5 | **The correct matching is absent from the options** — see §D | S1 Q63 |

**Coaching line:** match on **grammar first, meaning second**. A fragment starting with *that /
which / who* needs an antecedent noun; one starting with *at / of / with* needs a word that takes
that preposition.

---

# §D — Index of `[BROKEN SOURCE]` and `[AMBIGUOUS STEM]` items

**30 questions across the eight sets are not valid MCQs.** They are excluded from the tables above.
Do not drill these — and if you meet something similar in the real paper, trust your derivation
over the printed options and move on.

| Set | Questions | Why |
|---|---|---|
| S1 | Q74 | Bar-graph DI; forces CP 1680, options 2000–4200. No reconciliation. |
| S1 | Q78, Q79, Q80, Q81 | Number series; no single-term substitution yields a clean rule. |
| S2 | Q75, Q79 | Balls DI; derived gap (10) and requirement (+71) absent from options. |
| S2 | Q91 | Boat/stream forces $2X = 72$; options also duplicate "18". |
| S2 | Q94 | "Half pathway" undefined; both 88 and 176 defensible. |
| S3 | Q83 | Approximation: printed minus sign forces a negative answer; all options positive. |
| S3 | Q85 | Approximation: four printed division signs give ≈24; options 87–103. |
| S4 | Q31 | Number series derives 82; options 80/84/90/96/100. |
| S4 | Q58 | "Original fraction" ambiguous; literal reading absent from options. |
| S5 | Q49 | Profit & loss forces $CP_A = 150$; options 135–195. |
| S5 | Q50 | Mensuration; number of semicircles under-specified. |
| S6 | Q69, Q70 | Parallel rows; facing/parity constraints unsatisfiable. |
| S6 | Q84, Q85, Q86 | Circular arrangement; pair splits 3–2, "exactly between" has no referent, immediate-left absent from options. |
| S6 | Q88 | Box puzzle; B forced to the top, nothing above it. |
| S6 | Q96, Q97, Q98, Q99, Q100 | Linear row of 9; **clue set is unsatisfiable** — no permutation works. |
| S7 | — | none |
| S8 | Q1 | Coded inequality; operators `* % $ # @` never defined anywhere in the paper. |
| S8 | Q15 | Alphabetical-order sets; every option refers to a missing set IV. |
| S8 | Q43, Q45 | State–bank grid; two options are both true, so no unique answer. |

**Note on set 6:** eleven of its questions come from arrangements that cannot exist. Set 6 is the
weakest set in the bank — do not use it to judge your own accuracy.

---

# §E — Where to drill, by return on effort

| Priority | Topic | Why |
|---|---|---|
| 1 | **A14 Data Interpretation** | In all 8 sets, 100 questions. But note the 4 misread chart blocks — use the §A14 protocol. |
| 2 | **C7 Reading Comprehension** | In all 8 sets, 15 distinct question types. The three-statement format alone recurs in 6 sets. |
| 3 | **B1 Seating + B2 Puzzles** | ~76 + ~69 questions; the block that decides whether you finish the reasoning section. |
| 4 | **C1 Error Spotting** | In all 8 sets, 39 questions. Pure checklist — highest marks per minute of study. |
| 5 | **A9 Number Series** | In 7 of 8 sets, 26 questions. 18 distinct patterns catalogued above; drill *recognition*. |
| 6 | **A6/A7 Time-Work-Speed** | A6 in 7 sets (16 Q), A7 in 6 sets (11 Q), with recurring efficiency and harmonic-mean traps. |
| 7 | **A10 Quadratic comparison** | 19 questions, and 4 of them answer "can't be determined". |
| — | **B10 Data Sufficiency** | Only set 7. **Skip unless your actual paper's pattern is confirmed to include it** — the exam pattern is unverified. |
| — | **B7 Coding, C5 Phrasal Verbs, A13 Venn** | Rare (1–2 sets each). Learn the method, don't drill the volume. |

**Three traps that recur across the whole bank:**

1. **A percentage/markup rate that is itself a variable** (S1 Q76, S4 Q37, S3 Q92, S5 Q60) — these
   are simultaneous equations wearing a formula's clothes.
2. **Left/right inverting with facing** (B1) — the single most repeated mechanical error.
3. **"Can't be determined" as the honest answer** (A15, A13, S4 Q72, S7 Quant Q14, Q19) — do not
   manufacture a number because the options contain one.

---

**Caveats.** The eight sets carry **no answer key** — every answer in `pr/` is a derivation. The exam
pattern (negative marking, duration, section weights) is **unverified**, so do not plan around an
assumed pattern. Non-technical is out of scope for the `/iocl` coach, which covers the technical
paper only; this page and `IBPS_FORMULA_SHEET.md` are the separate track for these sets.
