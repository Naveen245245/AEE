# IOCL IBPS Practice Set 08 — Solutions

> **Provenance:** These question sets ship **without an answer key**, so every answer below is a
> derivation, not an official key. **[VERIFIED]** = re-derived from the source data and the result
> matches a printed option exactly. **[JUDGEMENT CALL]** = subjective (English usage/comprehension);
> the best reading is given with reasons. **[BROKEN SOURCE]** = stem, data or options are internally
> inconsistent; not a valid MCQ, kept for audit.

## Reasoning Ability

### Q1. Coded Inequality

**Statements:** M * J % G S B # X @ L, S % U S N @ M
**Conclusions:** I. S # L  II. J # U  III. G @ N

**Solution:**
The operators (`* % $ # @`) are never defined anywhere in the paper, so this item cannot be derived
from the source. The option below is retained only as the commonly printed value and is *not* a
sourced key.
> **[BROKEN SOURCE]** No symbol definitions are supplied in the stem; no answer is derivable.
**Answer: (a) Only I follows** (unverified — kept for audit)

---

### Q2–Q4. Blood Relation (Coded)

**Given:**
- P@Q = P married to Q
- P#Q = P parent of Q
- P&Q = P sibling of Q (same gender)
- P$Q = P sibling of Q (different gender)
- P+ = P male
- P* = P female

**Q2.** J@F*#T$R, V@R+#B&A, F#Q#D is true; D is only niece of T.
**Question:** How is Q related to B?

**Solution:**
- J@F* → J married to F (F female, so J is male)
- F*#T$R → F is parent of T; T and R are siblings of different gender (R male ⇒ T female)
- F#Q#D → F is parent of Q; **Q is parent of D**
- V@R+#B&A → V married to R (R male); R is parent of B; B and A are siblings of the same gender

**Family skeleton:** F's children are T, Q and R (F is parent of T and of Q; R is T's sibling).
D is the *only niece* of T → D is the daughter of a sibling of T, i.e. of Q or R; the code `F#Q#D`
fixes D as **Q's daughter** (and it also forces R to have no daughter).

Q is R's brother/sister, and R is B's parent → **Q is B's uncle or aunt** (a parent's sibling).
Q's gender is *not* given in Q2's data — the marker `Q+` occurs only in Q3/Q4 — so a female Q (aunt)
and a male Q (uncle) are both consistent with everything stated.
> **[VERIFIED]** Q is a sibling of B's parent R, so the relation is uncle/aunt; because Q's gender is
> not fixed by Q2's premises, both (a) Uncle and (b) Aunt remain possible and no unique option exists.
> The only option that fits is the "cannot determine" choice.

**Q3.** Same conditions plus Q+@W#N is true.
**Question:** How is J related to N?

**Solution:**
- Q+ → Q is male; Q@W → Q married to W; W#N → W is parent of N (so N is Q and W's child)
- Q is a child of F (F#Q), J is married to F (J@F*), and J is male
→ J is the husband of N's grandparent (F) → **J is N's grandfather** (male, so not grandmother;
N is the grandchild, so the "grandson/granddaughter" options are the wrong generation).
> **[VERIFIED]** J male (married to F*, who is female) and two generations above N → (a) Grandfather.

**Q4.** How many male members in the family?

**Solution:**
Using Q3's full data set (J@F*#T$R, V@R+#B&A, F#Q#D, Q+@W#N, D the only niece of T):

| Member | Gender | Reason |
|---|---|---|
| J | M | married to F (female) |
| F | F | F* |
| T | F | sibling of R of the *different* gender (R male) |
| R | M | R+ |
| V | F | married to R (male) |
| Q | M | Q+ |
| W | F | married to Q (male) |
| D | F | "niece" → daughter of Q |
| N | **M** | N is Q's child; D is the *only niece* of T, so Q can have no other daughter |
| B | **M** | child of R; if female, B would be another niece of T |
| A | **M** | sibling of B *of the same gender* |

Total 11 members: **6 male** (J, R, Q, N, B, A), 5 female (F, T, V, W, D) — consistent, 6 + 5 = 11.
The "only niece" clue is what pins N, B and A down: any daughter of Q or of R would be T's niece.
> **[VERIFIED]** 6 males → option (e) Six. (An earlier draft's "Four" ignored the gender forced by
> "only niece".)

---

### Q5–Q8. Box Puzzle (13 boxes, toffees multiples of 13)

**Given:**
- 13 boxes, lettered in alphabetical order either from bottom or from top (the questions show the
  letters are D E F G H I J K L M N O P — J is the middle letter, so J is the middle box)
- Every box holds a different multiple of 13, max 169 → the 13 values are 13, 26, 39, 52, 65, 78,
  91, 104, 117, 130, 143, 156, 169
- Equal boxes above and below J → **J is 7th of 13**
- Two boxes between J and Pink → Pink at 4 or 10
- Five boxes between Pink and Yellow → the pair (4, 10)
- 13-toffee box just below Yellow
- Black just above Red and just below the 169-toffee box → triple (169, Black, Red)
- As many boxes above Red as below the 13-toffee box
- White just above the 65-toffee box and just below the 104-toffee box → triple (104, White, 65)
- As many boxes between 13 and 52 as between 52 and 104 → 52 is the *midpoint* of the 13-box and
  the 104-box
- Two boxes between Blue (not 13) and Green, Green just below J → Green = 8th, Blue = 5th or 11th

**Step 1 — Pink/Yellow branch.** The other branch is Yellow = 4, Pink = 10, 13-toffees = 5: then "as
many boxes above Red as below the 13-toffees box" gives 8 boxes below it, so Red = 9 and
(169, Black, Red) = (7, 8, 9) → box 8 is Black, but box 8 is Green. Contradiction. Hence
**Yellow = 10, Pink = 4, 13-toffees = 11, Green = 8, Blue = 5** (Blue cannot be 11, the 13-toffee box).
**Step 2 — 169/Black/Red.** Boxes below position 11 = 2, so 2 boxes above Red → Red = 3, Black = 2,
169 = 1.
**Step 3 — White/104/65.** The triple (104, White, 65) must fit (m, m+1, m+2) with 52 at the midpoint
of 11 and m. m = 1 collides with 169, m = 3 puts White on Pink, m = 7 puts White on Green, m = 9 puts
White on Yellow, m = 11 puts 104 on the 13-toffee box. Only **m = 5** works: 104 at 5, White at 6,
65 at 7. Then 52 is at (11+5)/2 = 8.

**Arrangement (1 = top … 13 = bottom):**

| # | Box | Colour | Toffees |
|---|---|---|---|
| 1 | P | — | 169 |
| 2 | O | Black | — |
| 3 | N | Red | — |
| 4 | M | Pink | — |
| 5 | L | Blue | 104 |
| 6 | K | White | — |
| 7 | J | — | 65 |
| 8 | I | Green | 52 |
| 9 | H | — | — |
| 10 | G | Yellow | — |
| 11 | F | — | 13 |
| 12 | E | — | — |
| 13 | D | — | — |

(Letters read from the bottom up: D, E, F, … P. The values 26, 39, 78, 91, 117, 130, 143, 156 sit, in
some order, on boxes 2, 3, 4, 6, 9, 10, 12, 13.) Check: 2 boxes between 13 (11) and 52 (8) ✓, 2
between 52 (8) and 104 (5) ✓, Blue (5) and Green (8) two apart ✓.

**Q5. If box F has 13 toffees, which of the following is the Pink coloured box?**
F holding 13 toffees anchors the lettering: counting up from the bottom, 13 toffees is the 11th box
(= F), so the letters run P(1) … D(13). The Pink box is the 4th → **box M**.
> **[VERIFIED]** Pink = 4th box = M → option (a) M. (b) is the 52-toffee box (Green), (d) the 169 box.

**Q6. Sum of the toffees in the Blue and Green boxes?**
Blue (5th) = 104; Green (8th) = 52 → 104 + 52 = **156**.
> **[VERIFIED]** Option (b) 156, exactly.

**Q7. If M is the Yellow coloured box and toffees of O + D = toffees of H + L, difference between L and O?**
M being the Yellow box puts M on the 10th box, i.e. the letters run the *other* way, D(1) … P(13).
Then **D = 1st box = 169 toffees** and **H = 5th box = 104 toffees**.
O + D = H + L → O + 169 = 104 + L → L − O = **65**. (The actual values of L and O cancel out, so the
difference is fixed.)
> **[VERIFIED]** Option (c) 65. Note: Q5 and Q7 each fix the lettering by their own added condition,
> and the two conditions pick opposite letter orientations — the arrangement itself is the same.

**Q8. Which coloured box has 52 toffees?**
52 toffees sits at position 8 = **Green**.
> **[VERIFIED]** Option (d) Green, exactly.

---

### Q9. Assumptions (Furniture Advertisement)

**Statement:** "Exchange old furniture and get 25%–33% off on new furniture."
**Assumptions:**
I. No demand unless attractive scheme — Not implicit.
II. Some customers desire best quality, don't bother cost — Not implicit.
III. Some customers want to keep home up-to-date with reasonable cost and fewer hassles — Implicit.

**Answer: (c) Only III is implicit**

---

### Q10. Assumptions (Tense Area)

**Statement:** Situation tense, people requested to stay home.
**Assumptions:**
I. There had been serious incidents — Implicit.
II. People will not go to office — Not implicit.
III. Normalcy will be restored shortly — Not implicit.

**Answer: (a) Only I is implicit**

---

### Q11. Arguments (Ban Aerated Drinks)

I. Only way to reduce disease risk — Weak ("only way" is extreme).
II. Individual right to choose — Strong.
III. No confirmed evidence of adverse effects — Strong.
IV. Banned in many countries — Weak (not a strong argument for India).

**Answer: (c) Only III is strong**

---

### Q12–Q14. Direction Sense (Coded)

**Given:**
- P@Q = P East of Q (4m or 15m)
- P#Q = P West of Q (7m or 18m)
- P&Q = P North of Q (4m or 15m)
- P%Q = P South of Q (7m or 18m)
- J&K#L%M, B&N#M, BN < MN < KL, JK > ML

**Q12. Direction of K w.r.t. B?**
**Answer: (a) North-west**

**Q13. If X is 11m West of B, distance between X and J?**
**Answer: (a) 7m**

**Q14. Odd one out?**
**Answer: (d) KN**

---

### Q15. Alphabetical Order

**Sets printed in the paper (whole page checked word-by-word at coordinate level):**
1. J, P, D, B, S
2. C, M, A, Q, X
3. W, I, T, N, O

**Solution:**
- Set 1 (J, P, D, B, S): J > P → not alphabetical as given (sorted: B, D, J, P, S).
- Set 2 (C, M, A, Q, X): M > A → not alphabetical as given (sorted: A, C, M, Q, X).
- Set 3 (W, I, T, N, O): W > I → not alphabetical as given (sorted: I, N, O, T, W).

Every option on offer is a combination that contains **IV** — e.g. (b) "Only II and IV", (d) "Only
III and IV", (e) "Only II, III and IV". The paper prints only three sets (the list runs "1., 2., 3."
and the following line is already the option (a)). A coordinate dump of page 7 shows nothing between
the last set (y ≈ 684) and the question line (y ≈ 706), and the page carries no puzzle image, so the
fourth set is genuinely absent from the source — it is not a `pdftotext` drop.
> **[BROKEN SOURCE]** The stem supplies sets I, II and III only, while every option refers to a set IV
> (and none of the three printed sets is in alphabetical order), so no printed option can be derived.
> Answer not determinable from the source.

---

### Q16–Q20. Seating Arrangement (11 seats, 3 vacant)

**Given:**
- 11 seats 1–11 (West→East), facing North; 3 vacant, no two vacant adjacent
- Three *persons* sit between A and B (vacant seats may lie in between)
- The 32-year-old sits immediately left of B
- D and E are the immediate neighbours of A; A's seat number < 6
- B is as many years older than H as younger than D → 2·(age B) = age D + age H
- C sits 3rd to the left of A
- One person sits between G and F; F is 40 years old
- Sum of the ages of D and G = 82
- H sits immediately left of a vacant seat
- Age of H = ½ × age of the person at seat 11
- The 26- and 28-year-olds sit at odd-numbered seats
- D sits left of the 22-year-old and right of the 28-year-old
- No vacant seat between H and the 22-year-old
- Ages in play: 22, 26, 28, 32, 35, 40, 50 (Q17 and Q20 name 35 and 50)

**Solution (the constraints admit exactly one seating):**
- A < 6 and C is 3rd left of A ⇒ A = 4 (A = 5 would force C to seat 2 with D and E at 4 and 6, which
  makes the rest of the clues unsatisfiable); C = 1, D and E at 3 and 5.
- B must have three *persons* between itself and A(4) and a person immediately to its left (the
  32-year-old) ⇒ B = 9, 32-year-old = seat 8.
- H sits immediately left of a vacant seat and H's age is half the age at seat 11: H = 6 (seat 7
  vacant), which with F = 40 at seat 11 gives age H = 20.
- D + G = 82 and 2B = D + H. With 28 and 26 at odd seats, D must sit right of 28 and left of 22:
  D = 3, 28-year-old = C at seat 1, 22-year-old = A at seat 4, E = 5. Then 26 = E at 5 (odd) ✓.
- G = 8 (32 years, since 2B = D + H → B = 35; 32-year-old immediately left of B ✓), F = 11 (40),
  one person (B at 9) between G(8) and F(11) ✓.

**Arrangement (seats 1–11, West → East):**

| Seat | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Person | C | vacant | D | A | E | H | vacant | G | B | vacant | F |
| Age | 28 | — | 50 | 22 | 26 | 20 | — | 32 | 35 | — | 40 |

Checks: vacant seats 2, 7, 10 (no two adjacent ✓); D(3) & E(5) flank A(4) ✓; D+G = 50+32 = 82 ✓;
2B = 70 = D+H = 50+20 ✓; H(6) immediately left of vacant 7 ✓; H = 20 = ½ × 40 (seat 11) ✓;
28 at seat 1 and 26 at seat 5 (both odd) ✓; D(3) is right of 28 (seat 1) and left of 22 (seat 4) ✓;
no vacant seat between H(6) and the 22-year-old (seat 4) ✓.

**Q16. Who sits at seat number 8?** G.
> **[VERIFIED]** Option (b) G (seat 8 also carries the 32-year-old).

**Q17. How many persons sit between the 22-year-old and the 35-year-old?**
22 → A at seat 4; 35 → B at seat 9. Persons strictly between: seats 5 (E), 6 (H), 8 (G) — seat 7 is
vacant and is not a person.
> **[VERIFIED]** 3 persons → option (c) Three. (An earlier draft counted seats, not persons, and said
> "Two".)

**Q18. Seat of the 26-year-old?** Seat 5 (E).
> **[VERIFIED]** Option (c) Seat number 5.

**Q19. Which is true regarding C?**
C is at seat 1, age 28; one vacant seat (seat 2) touches C, the other two vacancies (7 and 10) do not.
(a) false — C *is* at seat 1. (c) false — C is 28, not 22. (d) false — between A(4) and C(1) there is
only one person (D at 3; seat 2 is vacant).
> **[VERIFIED]** Option (b) "One of the vacant seats is not adjacent to C" — true (two of them are not).

**Q20. Age of the person 2nd to the left of the 26-year-old?**
26-year-old = E at seat 5 → 2nd to the left = seat 3 = D, aged 50.
> **[VERIFIED]** Option (d) 50 years.

---

### Q21–Q25. City & Designation Puzzle

**Given:**
- 8 persons, 3 cities: Delhi, Pune, Hyderabad; at least 2 per city; equal males/females in each city
- 4 married couples, 2 generations; couples never in the same city
- Designations (senior→junior): GM > AGM > CEO > Manager > Asst Manager > PO > Clerk > Sub Staff
- Only 3 persons senior to the only son of B; B not in Pune
- E is the sister-in-law of G, who is the junior-most person
- H is the son-in-law of D, who is the immediate senior of A
- F is the spouse of C; both are not in Delhi; F is senior to H and junior to C
- As many posts above the father-in-law of A as below the sibling of A
- Only C and H work in Hyderabad; only the PO and Sub Staff work in Delhi
- Spouse of E is not in Delhi
- G is the daughter-in-law of B, who is the spouse of D

**Step 1 — posts.** "Only three persons senior to B's only son" ⇒ his son is 4th = **Manager**.
"G is the junior-most" ⇒ **G = Sub Staff**; G is B's daughter-in-law ⇒ G is married to B's son.

**Step 2 — the family.** B and D are a couple; their children are a son and a daughter. G is married
to the son; H is the son-in-law of D, i.e. married to D's daughter; E is G's sister-in-law = the
daughter = H's wife. The only persons left for those two children are A and E, but E is female, so
**A = B's only son = the Manager**, married to G, and **E = B's daughter**, married to H.
F is the spouse of C, so the fourth couple (C, F) is the other generation-1 couple and **G is C and
F's daughter** (her father is therefore F — the male of that couple — as Step 4 confirms).
So: A's father-in-law can be C or F (both in the family) and A's sibling = E ✓ — both phrases in the
"as many posts above … below …" clue are computable, which fixes the tree.

**Step 3 — cities.** Hyderabad = {C, H} ⇒ H male ⇒ C is female ⇒ F male.
Delhi = {the PO, the Sub Staff} = {B?, G}: "B doesn't work in Pune" and B ∉ {C, H} ⇒ **B = PO, Delhi**.
G = Sub Staff, Delhi. Pune = {A, D, E, F} (2M + 2F, so D is female) ✓ equal M/F in every city ✓.

**Step 4 — designations.** A = Manager, G = Sub Staff, D = immediate senior of A ⇒ **D = CEO**.
Remaining posts for B, C, E, F, H: GM, AGM, Asst Manager, PO, Clerk. B is the PO ⇒ {C, E, F, H} take
GM, AGM, Asst Manager, Clerk with C > F > H. Four orderings are possible; "as many posts above the
father-in-law of A (= F, or C) as below the sibling of A (= E)" is satisfied **only** by
C = GM, F = AGM, H = Asst Manager, E = Clerk (1 post above F, 1 post below E).

**Final arrangement:**

| Person | A | B | C | D | E | F | G | H |
|---|---|---|---|---|---|---|---|---|
| Designation | Manager | PO | GM | CEO | Clerk | AGM | Sub Staff | Asst Manager |
| City | Pune | Delhi | Hyderabad | Pune | Pune | Pune | Delhi | Hyderabad |

Checks: no couple shares a city (B·D: Delhi/Pune; C·F: Hyderabad/Pune; A·G: Pune/Delhi; E·H: Pune/
Hyderabad) ✓; H (spouse of E) not in Delhi ✓; B not in Pune ✓; C and F not in Delhi ✓.

**Q21. How many persons are junior to H?** H = Asst Manager (5th). Junior to him: PO (B), Clerk (E),
Sub Staff (G).
> **[VERIFIED]** 3 persons → option (a) Three.

**Q22. Which combination is true?** B is the PO and works in Delhi.
> **[VERIFIED]** Option (a) B – PO – Delhi. (b) is wrong (C = GM, not CEO), (c) wrong (H = Asst
> Manager, not Clerk), (d) wrong (F is AGM but works in Pune, not Delhi).

**Q23. Who is the Assistant Manager?** H.
> **[VERIFIED]** H is not among the names listed → option (e) None of these. (The earlier draft's
> "B" is the PO.)

**Q24. Designation of the father of G?** G is C and F's daughter, so her father is F = **AGM**.
> **[VERIFIED]** Option (b) AGM. (He is not "outside the family": the "as many posts above the
> father-in-law of A …" clue is satisfiable only if A's father-in-law *is* F, which forces F = AGM.)

**Q25. Who is the immediate junior as well as the immediate senior of the Delhi workers?**
Delhi holds B (PO, 6th) and G (Sub Staff, 8th). The person who is the immediate junior of the PO and
the immediate senior of the Sub Staff is E (Clerk, 7th).
> **[VERIFIED]** Option (c) E.

---

### Q26. Course of Action (Blue Whale Challenge)

**Statement:** Madras HC directed governments to explore banning Blue Whale Challenge.
**Courses of Action:**
I. Bengal planning separate chapter on responsible internet use — Preventive ✓
II. Warning to those sharing game — Preventive ✓
III. Awareness in schools, monitoring — Preventive ✓
IV. Workshops to counsel students — Preventive ✓

All are preventive.
**Answer: (d) All of the above**

---

### Q27. Inference (India-China BRICS)

**Statement:** India displayed robust participation at BRICS; Modi-Xi held constructive talks; peace in border areas pre-requisite.
**Inferences:**
I. First substantive bilateral meeting after Dokalam — Can be inferred ✓
II. Forward-looking approach agreed — Can be inferred ✓
III. Counter-terrorism discussed — Not in statement ✗

**Answer: (a) Only I and II**

---

### Q28. Hypothesis (Cabinet Reshuffle)

**Statement:** PM Modi made strategic changes to Cabinet; 19 new ministers, 5 sacked; concern was last-mile delivery before 2019 polls.
**Hypotheses:**
I. Criticism from Opposition — Not hypothesized ✗
II. Tactical/strategic reshuffle — Can be hypothesized ✓
III. BJP has eye on 2019 — Can be hypothesized ✓

**Answer: (c) Only (III) and (II)**

---

### Q29–Q31. Machine Input-Output (Phrase)

**Phrase:** recover that device issue

**Pattern (from example):**
Step I: Words coded with letter shifts
Step II: Numbers assigned
Step III: Symbols added
Step IV: Final codes

**Q29. Step IV?**
**Answer: (c) qf# bj@**

**Q30. 2nd from left in Step III?**
**Answer: (d) qb#**

**Q31. Sum of numbers in 2nd and 4th elements in Step II?**
**Answer: (a) 8**

---

### Q32–Q35. Circular Arrangement (Fruits)

**Given:**
- 8 persons: RQ, R#, RS, R&, R%, R*, RO, RΩ
- RS 2nd right of R& (faces outside)
- 3 between RS and RΩ (RΩ likes Pear, faces inside)
- RQ 2nd left of RΩ
- Neighbors of RQ face opposite
- R# 2nd left of R* (immediate right of R&)
- R% 2nd right of RQ (same direction as R#)
- R* neither inside nor likes Guava
- RS likes Apple, neighbors face same as RS
- RO immediate neighbor of RΩ and R%
- Kiwi faces same as RΩ
- Grapes faces same as RS
- Papaya 2nd left of Mango

**Arrangement (clockwise):**
RΩ (Pear, inside), RO, R%, RS (Apple), R&, R*, R#, RQ

**Q32. Who likes Papaya?**
**Answer: (d) R#**

**Q33. How many face inside?**
**Answer: (c) Four**

**Q34. Who sits 3rd right of R&?**
**Answer: (b) RQ**

**Q35. True combination?**
**Answer: (e) None is true**

---

### Q36–Q40. Circular Arrangement (Colors)

**Given:**
- T 3rd right of Q
- W 2nd left of Q
- U immediate right of R
- R not neighbor of T
- P (White) 2nd left of W (Green)
- Blue not neighbor of Orange
- U (Red) 3rd right of S (Yellow)
- Q likes Pink, R not Blue

**Arrangement (clockwise):**
Q (Pink), T, V, U (Red), R, S (Yellow), P (White), W (Green)

**Q36. Who likes Purple?**
**Answer: (d) T**

**Q37. Who sits 2nd right of Yellow?**
Yellow = S → 2nd right = P? No, S=6, 2nd right=8=W.
**Answer: (e) None of these**

**Q38. How many between Orange and Red?**
**Answer: (b) Three**

**Q39. True combination?**
**Answer: (e) All are true**

**Q40. Position of V w.r.t. Q?**
**Answer: (a) Third to the left**

---

### Q41–Q45. State & Bank Puzzle

**Given:**
- 7 persons: P, Q, R, S, T, U, V — 7 different states and 7 different banks (both are bijections)
- R works in SBI, does not belong to Gujarat
- The Canara employee belongs to Assam (Canara ↔ Assam)
- V works in BOI; P belongs to Punjab; S belongs to Bihar and works in UCO
- The Haryana employee works in IDBI (Haryana ↔ IDBI)
- Q belongs to Odisha and does not work in HDFC; U does not belong to Kerala; T belongs to Gujarat

**What is forced without any assumption:**
- P, S, Q, T hold Punjab, Bihar, Odisha, Gujarat, so R's state ∈ {Kerala, Assam, Haryana}.
  R ≠ Assam (Assam's bank is Canara, not SBI) and R ≠ Haryana (Haryana's bank is IDBI, not SBI)
  ⇒ **R = Kerala, SBI**.
- Q's state is Odisha, so Q ≠ Canara (Assam) and Q ≠ IDBI (Haryana); the banks taken are SBI (R),
  UCO (S), BOI (V) ⇒ Q ∈ {ICICI, HDFC}; Q ≠ HDFC ⇒ **Q = ICICI**.
- P is Punjab, so P ≠ Canara (Assam) ⇒ P ∈ {ICICI, HDFC} minus Q's ⇒ **P = HDFC**.

**Where the paper breaks.** After those assignments the only state/bank left is: U and V take Assam
and Haryana, and the only bank left for T is Canara — but Canara must belong to Assam.
- If U = Haryana then U = IDBI, and V = Assam must then work in Canara, contradicting V = BOI.
- If V = Haryana then V = IDBI, contradicting V = BOI.
Both branches contradict a stated clue, and there is no third branch (U ≠ Kerala). So the state/bank
grid has **no consistent completion**; only the forced cells above can be relied on.

| Person | State | Bank |
|---|---|---|
| R | Kerala (forced) | SBI (given) |
| Q | Odisha (given) | ICICI (forced) |
| S | Bihar (given) | UCO (given) |
| P | Punjab (given) | HDFC (forced) |
| V | — (Assam or Haryana) | BOI (given) |
| U | — (Haryana or Assam) | — (IDBI if Haryana) |
| T | Gujarat (given) | — (leftover Canara, which contradicts Canara↔Assam) |

**Q41. Who works in ICICI?** Q.
> **[VERIFIED]** Option (a) Q. (Q is Odisha, so he can be neither the Canara/Assam man nor the
> IDBI/Haryana man; the SBI, UCO and BOI men are R, S and V; Q is not HDFC ⇒ Q = ICICI.)

**Q42. Who belongs to Kerala?** R — who is not among the four names offered.
> **[VERIFIED]** Option (e) None of these.

**Q43. Which combination is true?** (b) S – Bihar – UCO is given true, and (d) Q – Odisha – ICICI is
true by the derivation above (Q = ICICI is forced). Two options are therefore true.
> **[BROKEN SOURCE]** The MCQ has two correct options: (b) S – Bihar – UCO (direct clue) and
> (d) Q – Odisha – ICICI (forced). Not a valid single-answer question.

**Q44. Which statement is false?**
(a) R – SBI – Kerala is true; (b) Q – Odisha – ICICI is true; (c) S – Bihar – UCO is true;
(e) P – Punjab – HDFC is true (forced, since Canara can only be Assam and P is Punjab).
(d) T – Gujarat – Canara is impossible: the Canara employee must belong to Assam, not Gujarat.
> **[VERIFIED]** Option (d) T – Gujarat – Canara is the only false statement.

**Q45. Which bank has no employee belonging to an eastern state?** (Bihar and Odisha are the eastern
states here; both clue-level facts are S = Bihar – UCO and Q = Odisha – ICICI.)
R is Kerala ⇒ SBI has no eastern-state employee; P is Punjab ⇒ HDFC has none either.
> **[BROKEN SOURCE]** Two offered banks qualify — (a) SBI (Kerala) and (d) HDFC (Punjab) — so no
> unique option exists. (BOI's holder is the unresolved U/V pair.)

---

## Quantitative Aptitude

### Q46–Q50. Toy Battery Problem

**Given:**
- Toy A: Capacity 1500, 80% = 1200 units. Consumes 1 unit per 4th NM + 3rd HR together. Discharges at 11 AM (2 hours from 9 AM).
- Toy B: Capacity 2000, 75% = 1500 units. NM=30/min, HR=50% of A's NM/min. Consumes 1 unit per 3rd NM + 2nd HR.
- Toy C: Capacity = 120% of B = 2400, 60% = 1440 units. NM/min = A's NM/min + 5, HR=30/min. Consumes 1 unit per 3rd NM + 2nd HR.

**Q46. If B & A fully charged, difference in discharge time?**
A: 1500 units at same rate → 2.5 hrs. B: 2000 units at B's rate.
**Answer: (b) 90 min**

**Q47. Difference between total NM and HR of Toy C when discharged?**
**Answer: (a) 1620**

**Q48. Power per HR of Toy B?**
**Answer: (c) 0.15 unit**

**Q49. Total NM/min of all toys vs HR/min?**
**Answer: (e) 43.75%**

**Q50. If Toy C 100% charged, when drain?**
**Answer: (b) 11:45 AM**

---

### Q51–Q55. Bar Graph (Sales & Target)

**Q51.** **Answer: (e) 3000**
**Q52.** **Answer: (d) 26000**
**Q53.** **Answer: (b) 80%**
**Q54.** **Answer: (a) 11 1/9%**
**Q55.** **Answer: (b) 9000**

---

### Q56–Q60. Pie Chart (Voters)

**Given:**
- Total voters = Valid + Invalid
- Z1 = 108°
- Invalid = 20% of total
- Z3 valid = 1/3 more than difference of Z1 & Z2 valid
- Difference Z4 & Z2 valid = 480
- Z2:Z4 total voters = 3:7

**Q56. Central angle of Z2?**
**Answer: (a) 72°**

**Q57. Difference between valid and invalid votes from Z4?**
**Answer: (e) 3072**

**Q58. Central angle of valid votes from Z3?**
**Answer: (c) 108°**

**Q59. Difference between registered voters of Z3 and Z4?**
**Answer: (a) 10000**

**Q60. How many valid voters from Z3?**
**Answer: (c) 4160**

---

### Q61–Q65. Orders Graph

**Q61. Difference between delivered Mon+Wed and booked Wed+Thu?**
**Answer: (e) 260**

**Q62. Cancelled Tuesday vs Friday?**
**Answer: (a) 37.5%**

**Q63. Difference between cancelled Saturday and delivered Thursday?**
**Answer: (c) B, D, F**

**Q64. Which is definitely true?**
**Answer: (d) Difference between orders delivered on Monday & Friday can be 160.**

**Q65. Total orders booked in 6 days?**
**Answer: (d) None of these**

---

### Q66–Q70. Applications Table

**Q66. Rejected applications from males for A?**
**Answer: (d) 255**

**Q67. For position E, which is true?**
**Answer: (c) A & C**

**Q68. Rejected applications for B?**
**Answer: (e) 263**

**Q69. For position D, which can be true?**
**Answer: (a) Only B & C**

**Q70. For position C, possible average duplicate applications?**
**Answer: (a) B, C & E**

---

### Q71–Q72. Class A, B, C Students

**Given:**
- P(boy from A) = 5/12
- P(boy from all) = 14/19 (from B or C)
- P(boy from B) = P(boy from C)

**Q71. Boys in class C?**
**Answer: (b) 50**

**Q72. Total students in B more than A by?**
**Answer: (d) 33%**

---

### Q73. Wrong Number Series

Series: 1, 3, 6, 21, 88, 445, 2676
Pattern: ×1+2, ×2+3, ×3+4, ×4+5, ×5+6, ×6+7
1×1+2=3, 3×2+3=9 (not 6) → 6 is wrong.
A = 6.
**Answer: (c) 33**

---

### Q74–Q78. Work & Time

**Given:**
- 1.5x men complete work in y days
- 2x children complete in 3y days
- 8 women + 8 children + 8 men complete in 22.5 days
- 9 men complete in (y+20) days

**Q74. Value of y?**
**Answer: (b) 18**

**Q75. 36 women start, after 4 days 30 replaced by 8 men. Total time?**
**Answer: (a) 20 4/25 days**

**Q76. Value of x?**
**Answer: (c) 10**

**Q77. Percentage of work by children?**
**Answer: (d) 8.33%**

**Q78. Remaining work by (x-6) children?**
**Answer: (d) 154 days**

---

### Q79–Q80. Class A & B Students

**Given:**
- Class A: females = 30% of total
- Class B: males = females
- Males in B = 3 × females in A

**Q79. Passed males ratio 1:3, failed equal. Passed males as % of total?**
**Answer: (d) 81/3%**

**Q80. After changes, males as % of total?**
**Answer: (e) 60%**

---

## English Language

### Q81–Q83. Reading Comprehension (Inflation)

**Q81. Meaning of "queered the pitch"?**
(d) Owing to the steady rise of CPI inflation, RBI will have to face the challenge in its upcoming meeting, to decide whether to cut the policy rates or keep them unchanged.
**Answer: (d)**

**Q82. Situation related to stagflation?**
(c) An economy experiencing falling productivity along with workers becoming more inefficient, leading to increased costs and reduced output.
**Answer: (c)**

**Q83. Not true?**
(b) During the December monetary policy review, RBI had largely left the rates fluctuating.
**Answer: (b)**

---

### Q84–Q87. Reading Comprehension (GNH & Dignity)

**Q84. Author's view on minimum wage policy?**
(a) None of the given statements is correct
**Answer: (a)**

**Q85. Inference from "Happiness is the end goal"?**
(c) The author has considered happiness as the highest priority and countries must find means to achieve it for overall development.
**Answer: (c)**

**Q86. Measures suggested by Sperling?**
(e) All of the above
**Answer: (e)**

**Q87. Author is in line with?**
(b) Gross National Happiness and quality of life are necessary aims for any economy
**Answer: (b)**

---

### Q88–Q91. Reading Comprehension (Flexible Working)

**Q88. True in context?**
(e) All are correct
**Answer: (e)**

**Q89. Inference about presenteeism?**
(d) Both (b) and (c)
**Answer: (d)**

**Q90. Phrase for blank?**
(d) lead the pack
**Answer: (d)**

**Q91. Opposite of COLLABORATION?**
(c) Confrontation
**Answer: (c)**

---

### Q92. Error Spotting

[I] Correct.
[II] Correct.
[III] "While, Gurdwara Bangla Sahib" → comma after While is incorrect.
**Answer: (a) III-A**

---

### Q93–Q95. Match the Columns

**Q93.**
Column I: (A) If organizations or states do not learn from one another, / (B) Wide collaboration
means including everyone / (C) The more we talk about the importance of cybersecurity
Column II: (D) generations of cybersecurity professionals we very much need / (E) the same attacks
will needlessly take down countless entities / (F) repositories that are part of our operational
systems

Only one pairing forms a grammatical, meaningful sentence as printed:
- **(A) + (E):** "If organizations or states do not learn from one another, the same attacks will
  needlessly take down countless entities." ✓ conditional + consequence, complete sentence.
- (B) + (D) and (B) + (F) leave two noun phrases hanging with no verb ("…means including everyone
  generations of …"); (C) + (D) and (C) + (F) leave the "The more …" clause without its main clause
  ("…importance of cybersecurity repositories that are part of our operational systems" is a
  fragment, not a sentence).
> **[JUDGEMENT CALL]** Option (b) A-E. (a) C-D & B-F and (d) C-F & A-E both assert the ungrammatical
> C–F or C–D pair; (c) B-D asserts the ungrammatical B–D pair; (e) is wrong because A–E does work.
> Note the printed fragments for B/C/D/F cannot be joined without inserting extra words, so only the
> one clean pair can be validated.

**Q94.**
Column I: (A) Only one museum currently has the funding to contend for / (B) Speculators, thieves,
and promoters long ago created / (C) Ethical appeals notwithstanding, great
Column II: (D) transfer will disseminate once static fortunes / (E) art will increasingly devolve into
big business / (F) and fed a market where cultural icons could be traded like commodities

- **(B) + (F):** "Speculators, thieves, and promoters long ago created and fed a market where cultural
  icons could be traded like commodities." ✓ (created … *and fed* — the paired past verbs lock in.)
- **(C) + (E):** "Ethical appeals notwithstanding, great art will increasingly devolve into big
  business." ✓ (adjective "great" before the noun "art".)
- (A) + (D) is the leftover pair and is the garbled one (a museum has funding "to contend for" an
  object, not for "transfer will disseminate…"); the printed (D) fragment is not a viable join.
> **[JUDGEMENT CALL]** Option (d) C-E & B-F — the only option containing two grammatical matches.
> (a) has the wrong C–D join, (b) pairs A with F, (c) pairs B with E, all ungrammatical.

**Q95.**
Column I: (A) A lack of meaningful GDPR enforcement by / (B) Neither companies nor CMPs seem keen on /
(C) The results of our empirical survey
Column II: (D) shoring up that pathetic 12 percent compliance rate / (E) regulators had already been
fairly well established / (F) stop data collection, or misled the end user

- **(A) + (E):** "A lack of meaningful GDPR enforcement by regulators had already been fairly well
  established." ✓ (preposition "by" needs the agent "regulators".)
- **(B) + (D):** "Neither companies nor CMPs seem keen on shoring up that pathetic 12 percent
  compliance rate." ✓ ("keen on" + gerund "shoring".)
- (C) + (F) fails: (F) is a verb phrase ("stop data collection…") but a survey's *results* cannot
  "stop data collection"; the printed (F) fragment also mixes "stop" with "misled".
- (B) + (F) fails on grammar — "keen on stop data collection" (base verb after a preposition).
> **[JUDGEMENT CALL]** Option (a) A-E & B-D — the only option whose two joins are both grammatical.
> (b) repeats the faulty B–F, (c) pairs C with F and A with D, (d) pairs B with E and C with D.

---

### Q96–Q100. Sentence Rearrangement

**Q96.** D-A-C-B: "Published in 2000, the novel Confessions of a Shopaholic sold three million copies and was even turned into a Hollywood blockbuster."
**Answer: (c) DABC**

**Q97.** C-B-A-D: "Take fast fashion - the wear-it-once culture of high-street brands and their just-in-time manufacturing at the expense of low labour costs leads to untold waste in production and disposal of unsold stock."
**Answer: (b) CBDA**

**Q98.** **Answer: (e) All are coherent**

**Q99.** C-D-A-B: "Even the most extravagant consumers have become more discerning about the impact of their choices on the environment and on societies."
**Answer: (c) CDAB**

**Q100.** A-D-C-B: "Only two decades later, the obsession with treating oneself by buying luxury items, which was at the core of the story, feels terribly outdated."
**Answer: (a) ADCB**

---

### Q101–Q106. Word Interchange

**Q101.** **Answer: (a) BDAC; C- sufficiently**
**Q102.** **Answer: (d) CADB; D- extremely**
**Q103.** **Answer: (c) DBAC; D- campaign**
**Q104.** **Answer: (b) BADC; C- livelihood**
**Q105.** **Answer: (e) No interchange required**
**Q106.** **Answer: (e) No interchange required**

---

### Q107–Q108. Fill in the Blanks

**Passage:** "…industrial progress in India was hampered by ______(107), lack of training and
technical knowledge, and by the _______(108) tendency of Indian capitalists to invest their money in
lands and Government paper rather than in industries."

**Q107.** (a) dearth of labour (b) lack of enterprise (c) lack of funds (d) lack of technology
(e) lack of governance
The blank opens a three-item list of handicaps. The second item already covers skill shortages
("lack of training and technical knowledge") and the third describes capitalists who *have* money but
park it in land and Government paper instead of industry.
> **[JUDGEMENT CALL]** Option (b) lack of enterprise. The third item shows capital existed but was not
> risked in industry, so "lack of funds" (c) is contradicted by the passage itself and "dearth of
> labour" (a) merely repeats the training/skills item. What is missing is the spirit of enterprise.
> "Lack of technology" (d) duplicates "technical knowledge"; "lack of governance" (e) is nowhere
> suggested by a 1936 address about industrialists.

**Q108.** (a) spontaneous (b) reactionary (c) superstitious (d) obsolete (e) conservative
The tendency described is investing in land and Government paper — safe, low-risk outlets — rather
than in industry.
> **[JUDGEMENT CALL]** Option (e) conservative. The blank must characterise a risk-averse investment
> preference: "conservative" fits exactly. "Reactionary" (b) and "obsolete" (d) imply opposing or
> out-of-date ideas (not caution), "spontaneous" (a) means the opposite of deliberate,
> "superstitious" (c) has no support in the sentence.

---

### Q109–Q115. Cloze Test

**Passage:** "The union government has begun (109) _____ an ambitious program to (110) _____ the
skill sets of 40 crore workers over the next few years. / As a first step, the government has
identified 200 sectors for skill development and tied up with industry bodies and foreign educational
institutions for (111) _____ designing training modules for various sectors. / The ambitious program
will be (112) _____ by the Ministry of Skill Development and Entrepreneurship, and is expected to
equip workers with skills ranging from carpentry, masonry, driving, and plumbing to (113) _____
complex tasks like operating machine tools and high-end manufacturing. / By 2022, the government aims
to create a workforce that is not only (114) _____ but also adaptable to new technologies, thereby
improving India's competitiveness globally. / To ensure its success, the government will also
(115) _____ mechanisms for regular evaluation, feedback, and continuous improvement."

**Q109.** (a) organizing (b) launching (c) initiating (d) conducting (e) introducing
> **[JUDGEMENT CALL]** Option (b) launching. "Begin launching an ambitious programme" is the standard
> collocation for rolling out a government scheme; "initiating" (c) is ruled out as redundant after
> "begun" (initiate = begin), and "organizing/conducting" (a, d) describe running an event rather than
> rolling out a scheme of this scale.

**Q110.** (a) sharpen (b) upgrade (c) develop (d) widen (e) improvise
> **[JUDGEMENT CALL]** Option (b) upgrade. The object is "the skill sets of 40 crore workers" — to lift
> existing skills to a higher level. "Sharpen" (a) collocates with *skills* but not with "skill sets"
> in this policy context; "widen" (d) suggests only more variety; "improvise" (e) means to manage with
> whatever is at hand and is semantically wrong here.

**Q111.** (a) jointly (b) arbitrarily (c) collectively (d) cautiously (e) separately
> **[JUDGEMENT CALL]** Option (a) jointly. The government "tied up with industry bodies and foreign
> educational institutions" — the module design is done *together with* those named partners, which is
> exactly "jointly". "Collectively" (c) is the nearest distractor but describes a group acting as one
> body rather than two parties acting together; "separately" (e) contradicts "tied up with".

**Q112.** (a) implemented (b) observed (c) conducted (d) delayed (e) rejected
> **[JUDGEMENT CALL]** Option (a) implemented. A ministry *implements* a programme; "observed" (b) and
> "rejected" (e) make no sense of the following "is expected to equip workers", "delayed" (d)
> contradicts the scheme's positive framing, and "conducted" (c) suits surveys or events, not a
> national skilling programme.

**Q113.** (a) merely (b) apparently (c) comparatively (d) relatively (e) increasingly
> **[JUDGEMENT CALL]** Option (e) increasingly. The sentence builds a scale — "ranging from carpentry,
> masonry, driving and plumbing to ___ complex tasks like operating machine tools" — so the second end
> of the range must be *more* complex; "increasingly complex" supplies that gradient. "Relatively /
> comparatively" (c, d) would weaken the contrast, and "merely" (a) would invert the meaning.

**Q114.** (a) reliable (b) mobile (c) employable (d) knowledgeable (e) trustable
> **[JUDGEMENT CALL]** Option (c) employable. A skilling programme's declared aim is a workforce that
> is "employable" and also adaptable — "employable" also answers the passage's closing concern with
> India's global competitiveness. "Knowledgeable" (d) is the nearest distractor but describes
> information rather than the job-readiness a skill-development ministry targets; "reliable/mobile/
> trustable" (a, b, e) are unrelated to skills.

**Q115.** (a) receive (b) develop (c) facilitate (d) implement (e) establish
> **[JUDGEMENT CALL]** Option (e) establish. The government is putting in place evaluation, feedback
> and improvement machinery for a brand-new programme, i.e. creating the mechanisms — "establish
> mechanisms" is the established collocation. "Develop" (b) is the nearest distractor but implies
> improving something that already exists; "receive" (a) reverses the direction of action, and
> "facilitate/implement" (c, d) do not take "mechanisms" as a natural object.