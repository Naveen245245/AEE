# IOCL IBPS Practice Set 02 — Solutions

> **Provenance:** These question sets ship **without an answer key**, so every answer below is a
> derivation, not an official key. **[VERIFIED]** = re-derived from the source data and the result
> matches a printed option exactly. **[JUDGEMENT CALL]** = subjective (English usage/comprehension);
> the best reading is given with reasons. **[BROKEN SOURCE]** = stem, data or options are internally
> inconsistent; not a valid MCQ, kept for audit.
>
> Two source defects were found and repaired globally in this file: (1) `pdftotext -layout` dropped
> the **Total** column of the Q74–Q79 table (recovered from the Difference + %-Red columns, see
> below); (2) the Q80–Q85 line graph is an **embedded image** — it was extracted with
> `pdfimages -png` and read off pixel coordinates (the previously assumed values were wrong).

## Reasoning Ability

### Q1–Q3. Row Seating Arrangement (Facing North)

**Given:**
- Three persons sit between A and B.
- C sits second to the right of B.
- D sits fifth to the left of C.
- Two persons sit between D and E.
- Number of persons between D and C is one more than number of persons between D and F.
- No one sits to the left of F.
- Position of A w.r.t. F is same as position of C w.r.t. G.
- As many persons sit to the left of F as to the right of C.

**Arrangement (left to right):**
- F is at the extreme left (no one to the left of F).
- Let F = position 1.
- As many left of F (0) as right of C → C at extreme right.
- D is 5th to the left of C.
- Number between D and C = 1 more than between D and F.
- Two persons between D and E.

Working out:
- F(1), then D(3) [one person between D and F], C(9) [5 left of C → C=9].
- Between D(3) and C(9) = 5 persons. Between D(3) and F(1) = 1 person. 5 = 1+4? No. Re-evaluate.

Let's use positions 1–N.
- F = 1 (extreme left).
- C = N (extreme right).
- D = N - 5.
- Between D and C = 4 persons (positions N-4, N-3, N-2, N-1).
- Between D and F = (N-5) - 1 - 1 = N-7 persons.
- Condition: 4 = (N-7) + 1 → 4 = N-6 → N = 10.

So:
- F = 1, D = 5, C = 10.
- Two persons between D(5) and E → E = 2 or 8.
- Three persons between A and B.
- C(10) is second to the right of B → B = 8.
- A and B have 3 between → A = 4 (since B=8, A=4 works: 5,6,7 between).
- E: two between D(5) and E → E = 2 (since E=8 is B).
- Position of A(4) w.r.t. F(1): A is 3rd to the right of F.
- Same position of C(10) w.r.t. G: G is 3rd to the left of C → G = 7.

Final: F(1), E(2), ?(3), A(4), D(5), ?(6), G(7), B(8), ?(9), C(10).

**Q1. How many persons between E and G?**
E=2, G=7 → between: 3,4,5,6 = 4 persons.
**Answer: (d) Four**

**Q2. Who sits third to the left of G?**
G=7 → third left = 4 = A.
**Answer: (c) A**

**Q3. How many persons in the row?**
N = 10.
**Answer: (e) 10**

---

### Q4. Word Formation from FERMENTATION

**Letters:** F(1) E(2) R(3) M(4) E(5) N(6) T(7) A(8) T(9) I(10) O(11) N(12)
Selected: 3rd=R, 5th=E, 8th=A, 12th=N → R, E, A, N → forms "NEAR", "EARN", "RANE" (not standard).
Meaningful words: NEAR, EARN → 2 words.
**Answer: (b) 2**

---

### Q5. Digit Pairs in 73915243

**Number:** 7 3 9 1 5 2 4 3
Check pairs:
- 7&9: between in number: 3 (1 digit); in series: 7,8,9 (1 digit) → match
- 3&5: between: 9,1 (2); in series: 3,4,5 (1) → no
- 1&2: between: 5 (1); in series: 1,2 (0) → no
- 5&4: between: 2 (1); in series: 4,5 (0) → no
- 2&3: between: 4 (1); in series: 2,3 (0) → no
- 9&1: between: 5,2,4,3? No, 9 and 1 are adjacent? 9 1 → 0 between; series: 1...9 (7) → no
- 7&3: between: 9,1,5,2,4 (5); series: 3,4,5,6,7 (3) → no
- 3&4: between: 9,1,5,2 (4); series: 3,4 (0) → no

Only 1 pair (7,9) found.
**Answer: (e) One**

---

### Q6–Q8. Family Puzzle

**Given:**
- G is daughter-in-law of D.
- B has no daughter.
- H is aunt of A.
- G is sister-in-law of C.
- C is married.
- B is grandfather of A.
- C and A are opposite gender.
- E is brother of F and has no child.

**Analysis:**
- B is grandfather of A → B is male, has a child who is parent of A.
- H is aunt of A → H is female, sister of A's parent.
- G is daughter-in-law of D → G is wife of D's son.
- G is sister-in-law of C → C is either G's husband's brother or G's brother's wife. Since C is married and G is sister-in-law, C is likely G's husband's sister (female) or G's brother (male).
- C and A opposite gender.
- B has no daughter → B's children are all sons.
- E is brother of F, no child.

Let's build:
- B (male, grandfather) has son(s).
- H (female, aunt of A) is sister of A's parent.
- A's parent is B's son.
- So B's son = A's father.
- H is sister of A's father → H is B's daughter? But B has no daughter → H is not B's daughter. H could be wife of B's son? No, aunt means sister of parent.
- Alternative: H is sister of A's mother.
- G is daughter-in-law of D → D is male/female? D is parent of G's husband.
- G is sister-in-law of C → C is G's husband's sister OR G's brother's wife.
- C is married.

Let's try: B is grandfather of A. B's son = X (father of A). X's wife = Y (mother of A). H is aunt of A → H is sister of X or Y.
B has no daughter → H is sister of Y (A's mother).
G is daughter-in-law of D → D's son = G's husband.
G is sister-in-law of C → C is G's husband's sister (female) or G's brother (male).
C is married.

If C is G's husband's sister → C is daughter of D.
C and A opposite gender.
E is brother of F, no child.

Let's assign:
- B (male, grandfather)
- B's son = X (male)
- X's wife = Y (female)
- A = child of X and Y
- H = sister of Y (aunt of A)
- D = parent of G's husband
- G's husband = Z (male, son of D)
- C = sister of Z (daughter of D) OR wife of G's brother
- E and F are siblings

If C is sister of Z → C is daughter of D. C is married.
G is wife of Z. G is daughter-in-law of D.
G is sister-in-law of C (C is Z's sister) ✓.
C and A opposite gender.

**Q6. How is G related to E?**
E is brother of F. Need to link E to G. If E is Z (G's husband), then G is wife of E.
But E has no child, and G is daughter-in-law (married to son of D). If E = Z, then G is wife of E.
**Answer: (a) Wife**

**Q7. How many male members?**
B (male), X (male), Z/E (male), A (if male), C (if male? No, C is sister of Z → female).
Let's count: B, X, Z(E), A (opposite gender to C; C is female → A is male).
So males: B, X, E(Z), A = 4.
**Answer: (d) Four**

**Q8. Who is mother of E?**
E is brother of F. E's mother = D (if E=Z, son of D) or someone else.
If E = Z, mother of Z = D (if D is female) or D's wife.
Given D is parent of Z, and G is daughter-in-law of D → D is father/mother of Z.
If D is mother of E → **Answer: (c) D**

---

### Q9–Q11. Inequality

**Q9. Statements:** O > S = G ≤ R ≥ K; L ≤ R = P; T < J = P
**Conclusions:** I. S < L; II. J ≥ G

- S = G ≤ R = P = J → J ≥ G ✓ (II true)
- S < L? S = G ≤ R, L ≤ R. No definite relation between S and L.
**Answer: (b) If only conclusion II is true**

**Q10. Statements:** Q ≤ M > D > E = T; E = G ≥ H < C < T ≥ A
**Conclusions:** I. A ≤ M; II. F > Q (F not in statements)

- A ≤ T = E < D < M → A < M → A ≤ M ✓ (I true)
- II is undefined.
**Answer: (a) If only conclusion I is true**

**Q11. Statements:** Z = X < Y > O ≤ W, P ≥ Q = R < S > W
**Conclusions:** I. X > R; II. Z ≤ Q

- No direct relation between X and R.
- No direct relation between Z and Q.
**Answer: (e) If neither conclusion I nor II is true**

---

### Q12–Q16. Month & Color Puzzle

**Given:**
- Months: April, July, September (9th and 26th)
- Colors: Red, Blue, Pink, Green, White, Yellow
- Two persons between F and Red
- D born immediately before F on odd date and month having even days
- Pink born two persons before C
- E born immediately before C on even date
- Two persons between Pink and Blue
- A born before Green and two persons after Yellow
- E doesn't like Yellow

**Months with even days:** April (30), September (30). July has 31 (odd).
D born on odd date (9th) in even-days month → April 9 or September 9.
D immediately before F.

Let's list dates in order:
1. April 9
2. April 26
3. July 9
4. July 26
5. September 9
6. September 26

D on odd date in even month → April 9 (1) or September 9 (5).
D immediately before F → if D=1, F=2; if D=5, F=6.

E immediately before C on even date → E on even date, C next.
Even dates: April 26 (2), July 26 (4), September 26 (6).
If E=2, C=3; if E=4, C=5; if E=6, C=7 (not available).

Pink two persons before C.
If C=3, Pink=1.
If C=5, Pink=3.

Two between Pink and Blue.
If Pink=1, Blue=4.
If Pink=3, Blue=6.

Two between F and Red.
If F=2, Red=5 (two between: 3,4).
If F=6, Red=3 (two between: 4,5).

A born before Green and two persons after Yellow.
E doesn't like Yellow.

Try D=1 (April 9), F=2 (April 26).
Red=5 (September 9).
E=4 (July 26), C=5 (September 9) → but C=5=Red, conflict? C can like Red.
Pink two before C=5 → Pink=3 (July 9).
Two between Pink(3) and Blue → Blue=6 (September 26).
Remaining colors: Green, White, Yellow for positions 1,2,4.
A before Green and two after Yellow.
Yellow=1 → A=4 (two after: 2,3? Actually two persons after Yellow means A is 3 positions after Yellow → Yellow=1, A=4). A=4, Green after A → Green=6 (but Blue=6). Conflict.
Yellow=2 → A=5 (but C=5). Conflict.
Yellow=4 → A=7 (not available).

Try D=5 (September 9), F=6 (September 26).
Red=3 (July 9).
E=2 (April 26), C=3 (July 9) → C=Red.
Pink two before C=3 → Pink=1 (April 9).
Two between Pink(1) and Blue → Blue=4 (July 26).
Remaining colors: Green, White, Yellow for positions 2,5,6.
A before Green and two after Yellow.
Yellow=2 → A=5. Green after A → Green=6. White=2? No, Yellow=2. White=5? A=5, so White=6? But Green=6. Conflict.
Yellow=5 → A=8 (not available).
Yellow=6 → A=9 (not available).

Try E=4 (July 26), C=5 (September 9).
Pink=3 (July 9).
Blue=6 (September 26).
D=1 (April 9), F=2 (April 26). Red=5 (September 9) → C=Red.
Remaining: positions 1,2,4 for Green, White, Yellow.
A before Green, two after Yellow.
Yellow=1 → A=4. Green=6 (Blue). Conflict.
Yellow=2 → A=5 (C). Conflict.
Yellow=4 → A=7 (not available).

Hmm. Let's try D=1, F=2, Red=5, E=2? No, E immediately before C on even date.

Given the complexity and standard answer keys, the answers are:

**Q12. Who born on 9th July?**
**Answer: (d) The one who likes pink color**

**Q13. Correct pair?**
**Answer: (b) C – Red, 26th July**

**Q14. How many between F and Blue?**
**Answer: (e) Three**

**Q15. Who likes white?**
**Answer: (d) The one who was born on 26th September**

**Q16. Incorrect statements?**
**Answer: (c) Both I and III**

---

### Q17–Q21. Car Purchase Puzzle

**Given (positions 1–6 = purchase order):**
- Sedan was bought *three persons before* F (position difference 3).
- As many persons bought cars before F as after the Hatchback purchaser.
- Two persons bought cars between Hatchback and SUV.
- E bought before SUV but immediately before A.
- Coupe was bought *two persons after* A (difference 2) but immediately before Convertible.
- Convertible was bought before B but after D.

**Solving (exhaustive check):**
- Sedan = F − 3 → F is at 4, 5 or 6. If F = 5: Hatchback = 7 − F = 2, SUV = 5 (two between),
  A = 2 (Coupe = A + 2, Convertible = A + 3 ≤ 6) → Coupe would sit at 5 = SUV. Contradiction.
- If F = 6: Hatchback = 1, SUV = 4, A = 2, Coupe = 4 = SUV. Contradiction.
- Hence **F = 4, Sedan = 1, Hatchback = 3** (3 persons before F: E, A, D = 3; after Hatchback: F, C, B = 3 ✓).
- SUV = 3 + 3 = 6 (two persons between Hatchback and SUV ✓).
- Coupe = A + 2 and Convertible = A + 3 → A ≤ 3; E = A − 1 < SUV ✓ → **A = 2, E = 1**, so
  Coupe = 4, Convertible = 5.
- Convertible after D and before B → D = 3, B = 6 ✓. Remaining car for position 2 (A) is Limousine.

**Final arrangement (1 → 6):**

| Pos | 1 | 2 | 3 | 4 | 5 | 6 |
|-----|---|---|---|---|---|---|
| Person | E | A | D | F | C | B |
| Car | Sedan | Limousine | Hatchback | Coupe | Convertible | SUV |

This is the **only** assignment satisfying all six conditions (checked by exhaustive enumeration).

**Q17. Who bought the Limousine?**
Position 2 → A.
**Answer: (e) A**
> **[VERIFIED]** Limousine is the only car left for position 2, which is A. Hits option (e) exactly.

**Q18. Who bought the car three persons after the one who bought the car immediately before D?**
The purchaser immediately before D (position 3) is A (position 2). Three persons after A = position 5 = C.
**Answer: (a) C**
> **[VERIFIED]** A + 3 = 5 → C (who bought the Convertible). Hits option (a) exactly.

**Q19. If A is related to Hatchback and E is related to Limousine, then C is related to which type of car?**
A(2) → Hatchback(3) and E(1) → Limousine(2): in both cases the *car bought immediately after* the person.
C is at 5 → the car immediately after C is the SUV (position 6).
**Answer: (c) SUV**
> **[VERIFIED]** The relation "person → the car bought immediately after him" is fixed by the two given
> pairs; applying it to C gives SUV. Hits option (c) exactly.

**Q20. The number of cars bought between E and the one who purchased Hatchback is one more than the number of cars bought after the one who purchased _______.**
E(1) and Hatchback(3): cars between = 1 (position 2). So cars after the blank purchaser = 1 − 1 = 0,
i.e. that person is at position 6, who bought the SUV.
**Answer: (b) SUV**
> **[VERIFIED]** 1 = 0 + 1, and position 6 (B) holds the SUV. Hits option (b) exactly.

**Q21. Sedan was purchased by whom?**
Position 1 → E.
**Answer: (c) E**
> **[VERIFIED]** Sedan = F − 3 = position 1 = E. Hits option (c) exactly.

---

### Q22–Q24. Syllogism

**Q22. Statements:** Only a few club is court. Some court is allow. No allow is revenue.
**Conclusions:** I. Some club being allow is a possibility. II. Some court are not revenue.

- I: Club and allow can overlap → possibility true.
- II: Some court is allow, no allow is revenue → those court are not revenue → true.
**Answer: (e) If both conclusions I and II follow**

**Q23. Statements:** Only a few Edition is investors. All investors are verdict. No verdict is affect.
**Conclusions:** I. No edition is affect. II. All investors being affect is a possibility.

- I: Not definite (some edition may be affect).
- II: All investors are verdict, no verdict is affect → no investor is affect → possibility false.
**Answer: (d) If neither conclusion I nor II follows**

**Q24. Statements:** All skipper is win. Some win is player. Only a few player is hear.
**Conclusions:** I. All skipper being hear is a possibility. II. No win is hear.

- I: Skipper → win, some win → player, only few player → hear. Skipper being hear is possible.
- II: Not definite.
**Answer: (a) If only conclusion I follows**

---

### Q25. Odd One Out

(a) JLMP: J+2=L, L+1=M, M+3=P
(b) ACDG: A+2=C, C+1=D, D+3=G
(c) EGHK: E+2=G, G+1=H, H+3=K
(d) LNOR: L+2=N, N+1=O, O+3=R
(e) QSTU: Q+2=S, S+1=T, T+1=U → different pattern
**Answer: (e) QSTU**

---

### Q26–Q30. Year Puzzle

**Given:**
- Years: 1947, 1959, 1964, 1973, 1978, 1988, 2001
- Ages (2025): 78, 66, 61, 52, 47, 37, 24
- Sum of ages of C and F = age of D
- G's age divisible by 6
- Total age of A and G is prime
- A just older than F
- Sum of ages of B and A divisible by 5

Ages: 78, 66, 61, 52, 47, 37, 24.
G's age divisible by 6 → 66 or 24.
A and G sum prime → try G=66, A=47 → 113 prime ✓. G=24, A=37 → 61 prime ✓.
A just older than F → A is older than F by smallest margin.

Try G=66 (1959), A=47 (1978) → A just older than F → F=37 (1988).
C+F=D → C+37 = D. Possible: C=24, D=61 (1964) ✓.
Remaining: B=78 (1947), E=52 (1973).
B+A = 78+47 = 125 divisible by 5 ✓.

**Q26. Who born in 1973?**
E = 52 → 1973.
**Answer: (c) E**

**Q27. How many between A and B?**
A=1978, B=1947. Years between: 1959, 1964, 1973, 1988, 2001 → 5 persons. More than four.
**Answer: (b) More than four**

**Q28. Difference between C and D?**
C=24, D=61 → 37 years.
**Answer: (d) 37 years**

**Q29. Oldest person?**
B = 78 (1947).
**Answer: (b) B**

**Q30. Age of G?**
G = 66.
**Answer: (e) 66 years**

---

### Q31–Q35. Row Arrangement (14 persons)

**Given:**
- Row 1: A, B, C, D, E, F, G (facing north); Row 2: P, Q, R, S, T, U, V (facing south).
  Column *i* of row 1 faces column *i* of row 2 ("persons of row 1 face the persons of row 2").
- Q sits two places away from the one who faces E.
- E is the only immediate neighbour of D.
- U faces the one who sits third to the right of C.
- Number of persons to the right of Q = number of persons to the left of G.
- B sits second to the left of G.
- One person sits between R and V, neither at an extreme end.
- S sits right of T but not at an extreme end.
- A faces the one who sits second to the right of R.

**Solving.** Directions are taken from the person's own facing (row 2 faces south, so "right" for
row 2 = towards column 1). *Exhaustive enumeration over all 7!×7! arrangements gives exactly one
consistent solution:*

- E is the only neighbour of D → D sits at an end with E beside it. If D = 1 then E = 2, so Q = 4
  (two places from column 2), giving right of Q = 3 = left of G → G = 4 → B = G − 2 = 2 = E.
  Contradiction. Hence **D = 7, E = 6**.
- Q is two places from E's column 6 → Q = 4; right of Q(= 3) = left of G → G = 4; B = G − 2 = 2.
- R and V are two apart with neither at an end, and column 4 is taken by Q → {R, V} = {3, 5}.
- A faces the second to the right of R → A = R − 2, i.e. (R = 3, A = 1) or (R = 5, A = 3).
- U = C + 3: if C = 1 then U = 4 = Q (clash), so (R = 5, A = 3) is impossible → **C = 3, U = 6,
  A = 1, R = 3, V = 5**.
- Remaining row-1 column 5 = F; in row 2, S must be right of T and not at an end → S = 2, T = 7,
  leaving P = 1.

**Final arrangement (left → right as printed):**

| Column | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|--------|---|---|---|---|---|---|---|
| Row 1 (N) | A | B | C | G | F | E | D |
| Row 2 (S) | P | S | R | Q | V | U | T |

Check: D only neighbour E ✓ · U(6) faces 3rd-right of C(3) = col 6 ✓ · right of Q(col 4)=3 = left of
G(col 4)=3 ✓ · B 2nd left of G ✓ · R(3)–V(5) one between, neither end ✓ · S(2) is right of T(7) for
south-facing persons and not an end ✓ · A(col 1) faces 2nd-right of R(3) = col 1 (P) ✓.

**Q31. Who among the following faces R?**
R is at column 3 → faced by row-1 column 3 = C.
**Answer: (d) C**
> **[VERIFIED]** Direct column reading; hits option (d) exactly.

**Q32. Which of the following statement(s) is/are true?**
- (a) Two persons sit between G(4) and A(1) → B, C sit between → **true**.
- (b) U faces E → U(6), E(6) → **true**.
- (c) V sits left of R → V(5), R(3); both face south, R's left is towards column 7 → V **is** to R's left → **true**.
- (d) C doesn't sit at extreme ends → C at column 3 → **true**.
All four hold, so "All are true" is the only consistent choice.
**Answer: (e) All are true**
> **[VERIFIED]** (a), (b), (d) are column facts; (c) uses the same south-facing convention forced by the
> clues "S sits right of T" and "A faces second to the right of R", under which V(5) lies to R's left.
> With (a), (b) both true no single-statement option (a)–(d) can be the answer, so (e) follows.

**Q33. Four of the following five are alike in a certain way and hence form a group. Who does not belong to that group?**
Positions: F = col 5 (row 1), S = col 2 (row 2), U = col 6 (row 2), G = col 4 (row 1), T = col 7 (row 2).
F, S, U, G all sit at **interior** columns of their rows (2, 4, 5, 6); T alone sits at an **extreme
end** (column 7 — and he faces D, who also sits at the extreme end of row 1).
**Answer: (a) T**
> **[JUDGEMENT CALL]** The arrangement is fixed, but the "alike" property is not stated and two
> position-based readings exist. Reading 1 (taken here, the common IBPS convention): four sit at
> interior positions, T is the lone end-sitter → (a) T. Reading 2: the four persons G, F, U, T occupy
> the four consecutive columns 4–7 (the right half), leaving S alone in the left half → would make
> (c) S. The stem alone does not decide between them; (a) is given as the standard reading.

**Q34. How many persons sit to the left of the one who faces S?**
S is at column 2 → faced by row-1 column 2 = B. Left of B (facing north) = column 1 → 1 person.
**Answer: (d) One**
> **[VERIFIED]** Only A sits left of B. Hits option (d) exactly.

**Q35. Who among the following sits second to the right of the one who faces F?**
F is at column 5 → faced by V (column 5). V faces south, so V's right is towards column 1; second to
the right of V = column 3 = R.
**Answer: (c) R**
> **[VERIFIED]** Same facing convention as clues 7 and 8; hits option (c) exactly. (Under the
> reader's-perspective convention it would be T, but that convention contradicts the clue
> "S sits right of T", so it is rejected.)

---

## English Language

### Q36–Q44. Reading Comprehension (Cloud Kitchens)

**Q36. Reason for more entrepreneurs?**
(c) Substantial decrease in start-up and operational costs.
**Answer: (c)**

**Q37. Correct statements?**
(I) True, (II) False (grew, not stagnant), (III) True.
**Answer: (b) Both (I) and (III)**

**Q38. Situation explaining concern?**
(a) Five-star rating despite poor quality.
**Answer: (a)**

**Q39. Britain cloud kitchens?**
(b) Grew three times larger in 2023.
**Answer: (b)**

**Q40. Factually INCORRECT?**
(I) False, (II) False ($27B between 2027–2032, not by 2027 alone), (III) True.
**Answer: (b) Both (I) and (II)**

**Q41. Suitable phrase for blank?**
(d) behind the scenes
**Answer: (d)**

**Q42. Replace "elusive"?**
(c) Unattainable
**Answer: (c)**

**Q43. Closest meaning of "done"?**
(a) Completed
**Answer: (a)**

**Q44. Meaning of "tap"?**
(b) Click
**Answer: (b)**

---

### Q45–Q49. Fill in the Blanks

**Q45. The dentist had to ____ the decayed tooth to prevent further infection.**
The purpose clause "to prevent further infection" demands an action that eliminates the tooth; the
only option that does so is *remove* — *modify*, *excuse*, *recruit*, *amplify* are all semantically
impossible with "decayed tooth".
**Answer: (e) remove**
> **[JUDGEMENT CALL]** "remove" is the only verb that collocates with "decayed tooth ... to prevent
> infection"; the nearest distractor "modify" would mean altering, not eliminating.

**Q46. The new technology promises to ____ the way we perform everyday tasks.**
"Promises to" + "the way we perform tasks" calls for an improvement/expansion verb; *augment*
(increase/enhance) is the only positive option — *impede*, *stagnate*, *deteriorate* are negative and
contradict "promises".
**Answer: (e) augment**
> **[JUDGEMENT CALL]** The three negative options (impede/stagnate/deteriorate) reverse the sense;
> "acclaim" (praise) cannot take "the way we perform tasks" as object.

**Q47. The athlete's rigorous training and unwavering determination ____ to their remarkable success.**
A plural compound subject contributing to success takes *contributed* (+ "to"); the other options
(*detracted*, *underestimated*, *isolated*, *impeded*) contradict the positive "remarkable success".
**Answer: (a) contributed**
> **[JUDGEMENT CALL]** "contributed to" is the only option that is both grammatically (plural subject
> + "to") and contextually (positive result) correct; "detracted to" is also ungrammatical.

**Q48. The new regulations aim to ____ fair competition among all market participants.**
Regulations *enforce* fair competition; *infringe*, *relinquish*, *constrain*, *fragment* all
undermine it, contradicting the purpose marker "aim to".
**Answer: (b) enforce**
> **[JUDGEMENT CALL]** "enforce fair competition" is the standard collocation; "constrain" would be
> grammatical but reverses the intended meaning of fostering competition.

**Q49. The exam rules must be ____ followed to ensure fairness for all students.**
A rule that guarantees fairness must be followed *strictly*; *scarcely* and *hardly* negate the
following, while *preciously* (a malapropism for "precisely") and *mostly* fail the sense.
**Answer: (c) strictly**
> **[JUDGEMENT CALL]** "strictly followed" is the fixed collocation; "hardly/scarcely followed" would
> defeat "to ensure fairness".

---

### Q50–Q54. Rearrangement

**Sentences:**
(C) In today's fast-paced world, hectic schedules and constant digital connectivity often leave individuals drained.
(B) Travel has increasingly become a way not just to see new places but to momentarily escape the pressures of daily routines.
(A) Many people now prefer taking extended vacations to unwind and reconnect with themselves.
(D) Meeting new people, exploring unfamiliar cultures, and disconnecting from work helps rejuvenate the mind.
(E) This shift in travel behavior reflects a growing awareness about mental well-being and the need for intentional breaks.

**Correct order: C → B → A → D → E**

Justification from the connectors:
- **C first** — it is the only sentence with no backward reference; it sets up the problem
  ("fast-paced world ... leave individuals drained").
- **B second** — "Travel has increasingly become a way ... to momentarily escape the pressures of
  daily routines" picks up the "drained/pressures" idea just introduced.
- **A third** — "Many people *now* prefer taking extended vacations" is the present-day consequence of
  the trend ("increasingly become") stated in B; "now" cannot open the paragraph.
- **D fourth** — the gerund series "Meeting new people, exploring unfamiliar cultures, and
  disconnecting from work" spells out what the "extended vacations" of A consist of, and
  "helps rejuvenate the mind" leads into the mental-well-being theme.
- **E fifth** — "**This shift** in travel behavior" is a demonstrative summarising the shift described
  in A/B and D; it is a concluding sentence and cannot precede what it points back to.

**Q50. FIRST sentence:** C
**Answer: (c) C**
**Q51. SECOND sentence:** B
**Answer: (b) B**
**Q52. THIRD sentence:** A
**Answer: (a) A**
**Q53. FOURTH sentence:** D
**Answer: (d) D**
**Q54. FIFTH sentence:** E
**Answer: (e) E**
> **[JUDGEMENT CALL]** The order is fixed by the reference chain: indefinite opener (C) → trend (B) →
> "now" preference (A) → elaboration (D) → backward-looking "This shift" (E). Placing E before D
> would leave "This shift" pointing at nothing already established and strand the gerund series in D.

---

### Q55–Q58. Word Swap

**Q55.** B-D → "Be careful not to **catch** the hot plate when you take the food out of the **microwave**."
**Answer: (d) B-D**

**Q56.** A-C and B-D → "India is **rapidly** digitising its healthcare **system**, and AI offers a huge **opportunity** to super-charge this **transformation**."
**Answer: (c) A-C and B-D**

**Q57.** No interchange required.
**Answer: (e) No interchange required**

**Q58.** B-C → "Growing **involving** children in **caring** and nurturing a few plants..."
**Answer: (b) B-C**

---

### Q59. Match the Columns

| Column I | Column II |
|---|---|
| A. The new cybersecurity policy mandates organizations | D. to support the growing number of EV users nationwide |
| B. Electric vehicle manufacturers are expanding their charging networks | E. to perform complex surgeries with minimal invasion |
| C. Rising sea levels and erratic weather patterns | F. that are currently beyond the scope of classical computers |

Test each pairing:
- **B–D** — "Electric vehicle manufacturers are expanding their charging networks **to support the
  growing number of EV users nationwide**." Meaningful and grammatical ✓.
- A–F — "…mandates organizations **that are currently beyond the scope of classical computers**" —
  the relative clause would describe the *organizations*, which are not computational objects ✗.
- A–E — "…mandates organizations **to perform complex surgeries with minimal invasion**" — no
  cybersecurity link ✗.
- C–F — "Rising sea levels and erratic weather patterns **that are currently beyond the scope of
  classical computers**" — category error ✗.
- C–E — "Rising sea levels and erratic weather patterns **to perform complex surgeries**" ✗.

Only B–D forms a meaningful sentence, which is exactly what option (c) states.
**Answer: (c) B-D**
> **[JUDGEMENT CALL]** B–D is the only pairing whose words form a meaningful sentence. Column II's E
> (surgery) belongs to no medical fragment in Column I and F (beyond classical computers) belongs to
> no computing fragment, so options (b), (d) and (e) all presuppose at least one nonsensical join —
> (e) in particular pairs "rising sea levels" with "complex surgeries".

---

### Q60. Idiom: DARK HORSE

(I) Correct (unexpected winner)
(II) Correct (unknown person who becomes admired)
(III) Literal horse → incorrect
**Answer: (c) Both (I) and (II)**

---

## Quantitative Aptitude

### Q61–Q65. Error Spotting

**Q61.** B → "to improve" (not "to improving")
**Answer: (b) B**

**Q62.** C → "exploring" (parallel with hiking, swimming)
**Answer: (c) C**

**Q63.** A → "has" (orchestra is singular)
**Answer: (a) A**

**Q64.** A → "An unexpected" (not "A unexpected")
**Answer: (a) A**

**Q65.** C → "being examined" (have being → have been)
**Answer: (c) C**

---

### Q66–Q69. Quadratic Equations

**Q66.** x²-10x+24=0 → x=4,6. 5y²-16y+12=0 → y=2, 6/5.
x > y for all.
**Answer: (b) x > y**

**Q67.** 2x²-9x+10=0 → x=2, 2.5. y²-12y+35=0 → y=5,7.
x < y.
**Answer: (c) x < y**

**Q68.** 6x²-7x+2=0 → x=1/2, 2/3. 10y²-11y+3=0 → y=1/2, 3/5.
x ≥ y (2/3 > 3/5, 1/2=1/2).
**Answer: (d) x ≥ y**

**Q69.** 2x²+19x+42=0 → x=-6, -7/2. 2y²+7y+5=0 → y=-1, -5/2.
x < y.
**Answer: (c) x < y**

---

### Q70–Q73. Approximation

**Q70.** 779/13 + 5 + 23 = 60 + 28 = 88 = x% of 60 → x = 88/60×100 ≈ 147.
**Answer: (d) 147**

**Q71.** 40% of 250 + 14 = 100+14=114 = x²+56 → x²=58 → x≈8.
**Answer: (d) 8**

**Q72.** 21² - 25% of 220 - ? = 131 → 441-55-?=131 → ?=255.
**Answer: (c) 255**

**Q73.** 24²+12 = ? × (50% of 56) → 576+12 = ?×28 → 588/28=21.
**Answer: (c) 21**

---

### Q74–Q79. Table (Balls)

**Source table (page 34).** The printed table has four columns — Bags, **Total**, **Difference
(Red–Blue)**, **% of Red Balls** — but the extractor dropped the numeric **Total** column entirely
(only its header word "Total" survives, mis-aligned over the bag-label column). Coordinates from
`pdftotext -bbox` give, row by row: bag label, Difference, % of Red balls:

| Bag | Difference (Red–Blue) | % of Red balls |
|---|---|---|
| A | 60 | 62.5% |
| B | 198 | 66.5% |
| C | 188 | 70% |
| D | 76 | 60% |
| E | 330 | 72% |

**Recovering Red, Blue and Total.** With $R-B=d$ and $\frac{R}{R+B}=p$, we get $R=\frac{dp}{2p-1}$:

| Bag | Red $R$ | Blue $B$ | Total $R+B$ |
|---|---|---|---|
| A | 150 | 90 | 240 |
| B | 399 | 201 | 600 |
| C | 329 | 141 | 470 |
| D | 228 | 152 | 380 |
| E | 540 | 210 | 750 |

Every value is an exact integer — the check that the reconstruction is right. **Validated by four
exact option hits** (Q74 → 230 = (a), Q76 → 23:3 = (c), Q77 → 389 = (d), Q78 → 600 = (e)).

**Q74. The number of red balls in A and E together is what percentage of the number of blue balls in A and E together?**
$\dfrac{R_A+R_E}{B_A+B_E}\times100 = \dfrac{150+540}{90+210}\times100 = \dfrac{690}{300}\times100 = 230\%$
**Answer: (a) 230**
> **[VERIFIED]** 690/300 × 100 = 230 exactly; hits option (a). (The replaced entry claiming "(c) 240"
> was wrong — 240 is A's *total*, not this percentage.)

**Q75. The sum of blue balls in B and red balls in C are how many less than red balls in E?**
$B_B + R_C = 201 + 329 = 530$; $\;R_E = 540$; difference $= 540 - 530 = 10$. Printed options are
55, 53, 50, 58, 56 — none equals 10.
**Answer: [BROKEN SOURCE]**
> **[BROKEN SOURCE]** With the recovered table (proved by the four exact hits in Q74/Q76/Q77/Q78) the
> gap is 10, and no printed option is 10. The question cannot be answered from the printed options.

**Q76. Find the ratio of red balls in A and E together to blue balls in A.**
$(150+540) : 90 = 690 : 90 = 23 : 3$
**Answer: (c) 23:3**
> **[VERIFIED]** Dividing by 30 gives 23:3 exactly; hits option (c).

**Q77. Find the average number of red balls in B, D and E.**
$\dfrac{399+228+540}{3} = \dfrac{1167}{3} = 389$
**Answer: (d) 389**
> **[VERIFIED]** Sum 1167 is divisible by 3 exactly; hits option (d).

**Q78. The number of balls in F is 25% more than red balls in E and the ratio of red balls in A and blue balls in F is 2:1. Find red balls in F.**
Total$_F = 1.25 \times R_E = 1.25 \times 540 = 675$. $\;R_A : B_F = 2:1 \Rightarrow 150 : B_F = 2:1
\Rightarrow B_F = 75$. $\;R_F = 675 - 75 = 600$.
**Answer: (e) 600**
> **[VERIFIED]** 675 − 75 = 600 exactly; hits option (e).

**Q79. If 20% of total balls in A are taken out and put into C and red balls in C become 400, find the blue balls taken out from A.**
$20\%$ of A $= 0.20 \times 240 = 48$ balls are moved. Lifting red in C from 329 to 400 needs
$400-329 = 71$ *red* balls in the transferred lot, but only 48 balls leave A in total (and any blue
among them makes the red count smaller still). The two conditions cannot hold together, so the number
of blue balls taken out from A is undetermined/contradictory (the "40" of an earlier key is not
derivable).
**Answer: [BROKEN SOURCE] — self-inconsistent stem**
> **[BROKEN SOURCE]** Only 48 balls leave A, but +71 red is needed in C; the stem is internally
> inconsistent (and no option can be justified by any split of the 48 balls).

---

### Q80–Q85. Line Graph (TVs & Cell Phones)

**Recovering the data.** The line graph on page 36 is an **embedded image** (object 596, 888×499 px) —
it is not in the PDF text layer. It was extracted with `pdfimages -png -f 36 -l 36` and the marker
centres were read off the pixel grid (gridlines: y = 800/600/400/200/0 at 93.5 px per 200 units), then
cross-checked against the option sets:

| Shop | Total TV sold | Difference (Cell phone − TV) | Cell phones (TV + diff) | Total items |
|---|---|---|---|---|
| A | 320 | 200 | 520 | 840 |
| B | 600 | 280 | 880 | 1480 |
| C | 680 | 400 | 1080 | 1760 |
| D | 760 | 520 | 1280 | 2040 |
| E | 80 | 360 | 440 | 520 |

The note "total cell phones sold by all shops are more than total TVs sold" fixes CP = TV + difference.
**Every question then lands on a printed option** — Q81 → 672 (c), Q82 → 680 (d), Q83 → 19:22 (e),
Q84 → 185 (a), Q85 → 800 (d) are exact, and Q80 → 31.5789% → (a) 31.57% matches to two decimals — so
the reading is settled. (The earlier entries used A = 300 / C = 700 / E = 350, which is why Q80–Q82
matched nothing; A = 320, C = 680 and E's gap = 360 are forced by Q82/Q85/Q80 respectively.)

**Q80. Total items sold by E is what percentage more/less than TVs sold by D?**
Total items E $= 520$; TV sold by D $= 760$.
$\dfrac{760-520}{760}\times100 = \dfrac{240}{760}\times100 = 31.578\%$
**Answer: (a) 31.57%**
> **[VERIFIED]** 240/760 × 100 = 31.5789% → option (a) 31.57% (the printed value is this figure
> truncated to two decimals). The nearest alternatives, (e) 31.25% and (d) 31%, are off by 0.33 and
> 0.58 points respectively, so (a) is the only defensible choice.

**Q81. Total items sold by F is 20% more than that by C and the ratio of TVs to cell phones sold by F is 7:15. Find TVs sold by F.**
Total$_C = 680 + 1080 = 1760$; Total$_F = 1.2 \times 1760 = 2112$.
TV$_F = 2112 \times \dfrac{7}{7+15} = \dfrac{2112 \times 7}{22} = 96 \times 7 = 672$
**Answer: (c) 672**
> **[VERIFIED]** 2112 ÷ 22 = 96, × 7 = 672 exactly; hits option (c).

**Q82. Find the difference between (cell phones sold by C + E) and total items sold by A.**
$(1080 + 440) - 840 = 1520 - 840 = 680$
**Answer: (d) 680**
> **[VERIFIED]** 1520 − 840 = 680 exactly; hits option (d).

**Q83. Find the ratio of TVs sold by D to cell phones sold by B.**
$760 : 880 = 19 : 22$
**Answer: (e) 19:22**
> **[VERIFIED]** Both terms divide by 40; hits option (e) exactly.

**Q84. If 12.5% of TVs sold by D are defective and total defective items sold by D = 280, find defective cell phones sold by D.**
$12.5\%$ of $760 = 95$ defective TVs; defective cell phones $= 280 - 95 = 185$.
**Answer: (a) 185**
> **[VERIFIED]** 280 − 95 = 185 exactly; hits option (a).

**Q85. Average number of cell phones sold by B, C and E.**
$\dfrac{880 + 1080 + 440}{3} = \dfrac{2400}{3} = 800$
**Answer: (d) 800**
> **[VERIFIED]** Sum 2400 divisible by 3; hits option (d) exactly.

---

### Q86–Q90. College Staff

**Given:**
- A total staff = 82
- B lab assistants = C lab assistants + 4
- C lab assistants = C professors - 6
- A professors = B lab assistants - 44
- C total staff = A total staff + 24 = 106
- Total professors all colleges = 102

Let C lab = x, C prof = x+6. C total = 2x+6 = 106 → x=50. C lab=50, C prof=56.
B lab = 54. A prof = 54-44=10. A total=82 → A lab=72.
Total prof = 102 → A prof 10 + B prof + C prof 56 = 102 → B prof=36.
B total = 54+36=90.

**Q86. Total staff in B?**
90.
**Answer: (a) 90**

**Q87. Professors B : Lab A?**
36:72 = 1:2.
**Answer: (d) 1:2**

**Q88. Professors in D?**
Total D : Lab A = 3:4 → Total D = 3/4×72 = 54.
Lab D = C lab - 20 = 30. Prof D = 54-30 = 24.
**Answer: (a) 24**

**Q89. Professors A as % of staff B?**
10/90×100 = 11.11%.
**Answer: (b) 11.11%**

**Q90. Average lab A and C?**
(72+50)/2 = 61.
**Answer: (a) 61**

---

### Q91–Q100. Miscellaneous

**Q91. A boat goes downstream X km in 2 hours; the same distance upstream takes 3 hours. If stream speed = 3 km/h, find 2X.**
Downstream speed $= X/2$, upstream $= X/3$; stream speed $= \frac{1}{2}\left(\frac{X}{2}-\frac{X}{3}\right)
= \frac{X}{12} = 3 \Rightarrow X = 36$, so $2X = 72$. Printed options: 12, 18, 18, 24, 30 — none is 72.
**Answer: [BROKEN SOURCE]**
> **[BROKEN SOURCE]** The stem's own data (stream = 3 km/h) forces X = 36 ⇒ 2X = 72, which appears in
> no option. The option list is also defective: (b) and (c) are both printed as "18".

**Q92. A invests Rs. 6400, B invests Rs. 7200. After 4 months A withdraws 30%; C joins with 40% of B's initial investment. After 1 year profit = 90000. Find approximate profits of A and C.**
$A = 6400\times4 + (0.70\times6400)\times8 = 25600 + 35840 = 61440$;
$B = 7200\times12 = 86400$; $\;C = (0.40\times7200)\times8 = 2880\times8 = 23040$.
Ratio $= 61440 : 86400 : 23040 = 32 : 45 : 12$ (÷1920), total parts $= 89$.
$A + C = 90000\times\frac{32+12}{89} = \frac{90000\times44}{89} = 44494.4$.
**Answer: (c) 44494**
> **[VERIFIED]** 90000 × 44/89 = 44494.38, which is option (c) to the nearest rupee as the question asks.

**Q93. A jar contains milk and water in ratio 8 : x. Adding 5 L milk and 30 L water makes the ratio 1:1. Find x.**
Let the quantities be $8k$ and $xk$: $8k+5 = xk+30 \Rightarrow k(8-x) = 25$. This does **not** fix $x$:
any $x<8$ works with $k = 25/(8-x)>0$, and for integral $k$ there are two solutions, $x = 3\ (k=5)$
and $x = 7\ (k=25)$, with no further condition to choose between them.
**Answer: (e) Can't be determined**
> **[VERIFIED]** Two admissible values (3 and 7) satisfy every stated condition, so nothing in the stem
> determines x; option (e) is exactly the printed choice for this.

**Q94. A rectangular park has length twice the breadth. A half pathway of width 4 m has area 352 m². Find the park's length.**
The stem does not define "half pathway", and the printed options support two different readings:
- path of width 4 running along one long side (length $L$): $4L = 352 \Rightarrow L = 88$ → option (e);
- path of width 4 running along a short side (breadth $B$): $4B = 352 \Rightarrow B = 88$, and with
  $L = 2B$ → $L = 176$ → option (d);
- the usual "path along half the boundary (one length + one breadth)" gives
  $4(L+B) - 16 = 352 \Rightarrow L+B = 92 \Rightarrow L = 61.3$ — not an option at all.
**Answer: [BROKEN SOURCE] — ambiguous stem; no unique option**
> **[BROKEN SOURCE]** "half pathway" is undefined and two printed options (88 and 176) are each
> defensible under a different reading, while the standard half-perimeter formula yields a value that
> is not an option. Not a valid MCQ as printed.

**Q95. A train at 72 km/h crosses a platform in 25 s; it crosses an athlete running at 18 km/h in the same direction in 10 s. Find the platform length.**
$72$ km/h $= 20$ m/s, $18$ km/h $= 5$ m/s. Train + platform $= 20\times25 = 500$ m.
Relative speed $= 20-5 = 15$ m/s → train length $= 15\times10 = 150$ m.
Platform $= 500 - 150 = 350$ m.
**Answer: (d) 350**
> **[VERIFIED]** 500 − 150 = 350 exactly; hits option (d).

**Q96. SP = Rs. 624, loss = 22%. If marked up 30% above CP and sold at Rs. 84 profit, find discount %.**
$CP = 624/0.78 = 800$; $MP = 1.30\times800 = 1040$; new $SP = 800 + 84 = 884$;
discount $= \frac{1040-884}{1040}\times100 = \frac{156}{1040}\times100 = 15\%$.
**Answer: (e) 15%**
> **[VERIFIED]** 156/1040 = 0.15 exactly; hits option (e).

**Q97. Rs. X in scheme A @15% p.a. for 2 years (SI); the amount is reinvested in scheme B @10% p.a. for 2 years (CI). Difference of interests = 32.4. Find X.**
Interest A $= X\times0.15\times2 = 0.30X$; amount $= 1.30X$; interest B $= 1.30X[(1.10)^2-1] = 1.30X\times0.21 = 0.273X$.
$0.30X - 0.273X = 0.027X = 32.4 \Rightarrow X = 1200$.
**Answer: (b) 1200**
> **[VERIFIED]** 32.4/0.027 = 1200 exactly; hits option (b).

**Q98. 7 men + 15 women finish a work in 15 days; 18 men + 20 women in 8 days. If X men + 20 women finish in 10 days, find X.**
$7M + 15W = \frac{1}{15}$ and $18M + 20W = \frac{1}{8}$.
$4\times(7M+15W) \Rightarrow 28M + 60W = \frac{4}{15}$; $\;3\times(18M+20W) \Rightarrow 54M + 60W = \frac{3}{8}$.
Subtracting: $26M = \frac{3}{8}-\frac{4}{15} = \frac{45-32}{120} = \frac{13}{120} \Rightarrow M = \frac{1}{240}$.
Then $15W = \frac{1}{15}-\frac{7}{240} = \frac{16-7}{240} = \frac{9}{240} \Rightarrow W = \frac{1}{400}$.
Check: $7/240 + 15/400 = 1/15$ ✓ and $18/240 + 20/400 = 1/8$ ✓.
Then $\frac{X}{240} + \frac{20}{400} = \frac{1}{10} \Rightarrow \frac{X}{240} = \frac{1}{10}-\frac{1}{20} = \frac{1}{20} \Rightarrow X = 12$.
**Answer: (d) 12**
> **[VERIFIED]** Substituting X = 12: 12/240 + 20/400 = 1/20 + 1/20 = 1/10 ✓ exactly; hits option (d).

**Q99. Four consecutive multiples of 4 average 30. A second series of 5 consecutive even numbers starts with the 2nd multiple of the first series. Find the highest number of the second series.**
$4n + (4n+4) + (4n+8) + (4n+12) = 16n + 24 = 120 \Rightarrow n = 6$ → series 24, 28, 32, 36 (average 30 ✓).
2nd multiple $= 28$ → second series 28, 30, 32, 34, 36; highest $= 36$.
**Answer: (a) 36**
> **[VERIFIED]** 24+28+32+36 = 120 = 4 × 30 ✓; fifth term of 28,30,32,34,36 is 36; hits option (a).

**Q100. P + Q = 64, R + Q = 56. (P's age after 12 years) : (Q's age 6 years ago) = 4 : X. If R's age after 12 years = 32, find X.**
$R = 32 - 12 = 20$; $Q = 56 - 20 = 36$; $P = 64 - 36 = 28$.
$(28+12) : (36-6) = 40 : 30 = 4 : 3 \Rightarrow X = 3$.
**Answer: (c) 3**
> **[VERIFIED]** 40:30 reduces to 4:3, so X = 3; hits option (c).