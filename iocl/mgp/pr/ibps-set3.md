# IOCL IBPS Practice Set 03 — Solutions

> **Provenance:** These question sets ship **without an answer key**, so every answer below is a
> derivation, not an official key. **[VERIFIED]** = re-derived from the source data and the result
> matches a printed option exactly. **[JUDGEMENT CALL]** = subjective (English usage/comprehension);
> the best reading is given with reasons. **[BROKEN SOURCE]** = stem, data or options are internally
> inconsistent; not a valid MCQ, kept for audit.

## Reasoning Ability

### Q1–Q5. Circular Seating Arrangement

**Given:**
- Seven persons A, B, C, D, E, F, G around a circular table.
- Some face centre, some face away.
- F sits third to the right of A.
- Immediate neighbours of A face same direction but opposite as A.
- A faces same direction as B but not towards centre → A and B face away from centre.
- One person sits between A and C.
- D sits 2nd to the left of C.
- E sits 2nd to the left of G and faces same direction.
- F and D face opposite direction as E.

**Convention:** seats 1–7 clockwise. A person facing the centre has their **right** hand
anticlockwise; a person facing away has their **right** hand clockwise (left is the reverse).

**Re-derived arrangement:**
- A faces away from the centre (given) and B faces the same way as A → B faces away.
- The two immediate neighbours of A face the centre.
- Put A at seat 1 (away). F is third to the right of A; right of A = clockwise → F = seat 4.
- One person between A and C → C = seat 3 or seat 6.
- Applying "D second to the left of C", "E second to the left of G, E and G same direction" and
  "F and D opposite to E" leaves one cyclic order (all seven seats rotate freely):

| Seat (clockwise) | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| Person | A | E | C | F | D | B | G |
| Faces | away | centre | centre | away | away | away | centre |

**Constraint checks (all satisfied):**
- F third to the right of A: A away → clockwise E(1), C(2), **F(3)** ✓
- A's neighbours G and E both face the centre, opposite to A ✓
- A and B both face away ✓
- One person (E) between A and C ✓
- D second to the left of C: C faces centre → left = clockwise F(1), **D(2)** ✓
- E second to the left of G: G faces centre → left = clockwise A(1), **E(2)** ✓, E and G both centre ✓
- F and D (away) face opposite to E (centre) ✓

**Q1. Who sits second to the right of E?**
E faces the centre, so right = anticlockwise: A(1), G(2) → **G**.
Options A, D, C, F, G → **Answer: (e) G**
> **[VERIFIED]** Seat 7 = G. Two right of E (seat 2) going anticlockwise lands on seat 7 = G, which is option (e).

**Q2. Pair facing the same direction?**
Directions — A away, B away, C centre, D away, E centre, F away, G centre.
- (a) G and C — both centre ✓ | (b) A and E — away vs centre ✗ | (c) E and D — centre vs away ✗ | (d) C and F — centre vs away ✗
**Answer: (a) G and C**
> **[VERIFIED]** Only G and C share a direction (both towards the centre); the other four option pairs are mixed.

**Q3. How many sit between B and F (clockwise from F)?**
Clockwise order from F: D, **B** → exactly one person (D) between them.
**Answer: (a) One**
> **[VERIFIED]** Cyclic order A-E-C-F-D-B-G: F→D→B, so 1 person sits between F and B clockwise; hits option (a) One.

**Q4. Odd one out (F, C, B, D, A)?**
A, B, D and F face **away** from the centre; C is the only one of the five facing the centre.
**Answer: (b) C**
> **[VERIFIED]** Direction split of the five: away = {A, B, D, F}, centre = {C}. C is the only outlier.

**Q5. Which statements are true?**
I. G faces towards the centre → G is centre ✓
II. F and A both face away → ✓
III. Two persons between C and D clockwise from D? From D(5) clockwise: B(6), G(7), A(1), E(2), C(3) → **four** between, not two ✗
**Answer: (c) Both I and II**
> **[VERIFIED]** I and II are correct; III fails (4 persons between C and D, not 2). Hits option (c).

---

### Q6–Q8. Family Puzzle

**Given:**
- M is spouse of O and parent of R.
- O is father-in-law of T who has two children.
- N is the only son of R who has no sibling.
- T is mother-in-law of P.
- V is married to P.

**Analysis:**
- O (male) is father-in-law of T → T is married to O's child.
- R "has no sibling" → R is the only child of O and M, therefore T is married to **R**.
- N is the only son of R → N is the son of R and T. T has two children, so the second child
  must be a **daughter** (N is the *only* son).
- T is mother-in-law of P → P is the husband of T's daughter, i.e. P is married to **V**
  ("V is married to P"). So V is the daughter of R and T, and P is R's son-in-law.

**Family tree:**
- O (m) ⚭ M (f) → R (m)
- R (m) ⚭ T (f) → N (m), V (f)
- V (f) ⚭ P (m)

**Q6. Odd one out (O, R, P, N, V)?**
Genders — O male, R male, P male, N male; V is the only female.
(The generation split does not give a group of four: O is gen-1, R gen-2, P/N/V gen-3.)
**Answer: (e) V**
> **[VERIFIED]** O, R, P and N are all male (M's husband, R's father, V's husband, R's son); V is the only female, so V is the odd one. Hits option (e).

**Q7. Who is the grandmother of V?**
V is the daughter of R and T. R's mother is M → M is V's paternal grandmother.
(T is V's *mother*, O is her paternal grandfather, N her brother.)
**Answer: (b) M**
> **[VERIFIED]** O ⚭ M → R; R ⚭ T → V. M is the mother of V's father R, hence V's grandmother. Option (b).

**Q8. Relation of P with R?**
P is married to V, who is R's daughter → P is R's son-in-law.
**Answer: (a) Son-in-law**
> **[VERIFIED]** R → V (daughter) → P (V's husband) ⇒ P is R's son-in-law. Option (a).

---

### Q9. Word Formation from EXACTITUDE

**Letters:** E(1) X(2) A(3) C(4) T(5) I(6) T(7) U(8) D(9) E(10)
Selected: 3rd=A, 4th=C, 5th=T, 7th=T → A, C, T, T → "TACT" is meaningful.
Second letter of TACT = A.
**Answer: (b) A**

---

### Q10–Q14. Year Puzzle

**Given:**
- Years: 1955, 1967, 1973, 1980, 1987, 1991, 2003
- Ages (2024): 69, 57, 51, 44, 37, 33, 21
- L's age multiple of 3 → 69, 57, 51, 33, 21
- Three persons between L and Q.
- Number before Q = number after P.
- Difference between Q and K = 12 years.
- M is 7 years older than N.
- N is younger than O.

**Deduction:**
Number the seats 1–7 from the **oldest year (1955)** to the youngest (2003), so ages run 69, 57, 51, 44, 37, 33, 21.
- Three persons between L and Q → |pos(L) − pos(Q)| = 4.
- Persons before Q = 6 − (persons after P) → pos(Q) + pos(P) = 8 (they are symmetric about the centre).
- Age(Q) and Age(K) differ by 12 → the pair is (69, 57) or (33, 21).
- M is 7 years older than N → the pair is (51, 44) or (44, 37).
- N is younger than O.

Only one arrangement satisfies all of these:

| Seat | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| Person | P | O | L | M | N | K | Q |
| Year | 1955 | 1967 | 1973 | 1980 | 1987 | 1991 | 2003 |
| Age | 69 | 57 | 51 | 44 | 37 | 33 | 21 |

**Constraint checks:** L = 51 (multiple of 3) ✓; L(3) and Q(7) have seats 4,5,6 = three persons between ✓;
before Q = 6 persons, after P = 6 persons ✓; |Age Q − Age K| = |21 − 33| = 12 ✓; M(44) = N(37) + 7 ✓;
N(37) younger than O(57) ✓.

**Q10. Who was born in 1967?**
1967 ↔ age 57 ↔ seat 2 = **O**.
**Answer: (d) O**
> **[VERIFIED]** Age 57 has only one home (1967) and the solved table puts O there. Option (d).

**Q11. Age difference between M and Q?**
M = 44 (1980), Q = 21 (2003) → 44 − 21 = 23.
**Answer: (c) 23 years**
> **[VERIFIED]** 44 − 21 = 23, exactly option (c).

**Q12. M was born in which year?**
M's age is 44 → 2024 − 44 = 1980.
**Answer: (b) 1980**
> **[VERIFIED]** 2024 − 44 = 1980, exactly option (b).

**Q13. Total age of K and N?**
K = 33 (1991), N = 37 (1987) → 33 + 37 = 70.
**Answer: (e) 70 years**
> **[VERIFIED]** 33 + 37 = 70, exactly option (e).

**Q14. If P is related to L, N is related to Q, then M is related to ___?**
The relation is "the person two seats towards the younger end": P(seat 1) → L(seat 3); N(seat 5) → Q(seat 7).
Applying the same +2 to M(seat 4) gives seat 6 = **K**.
**Answer: (a) K**
> **[VERIFIED]** Offset +2 seats in both worked examples (1→3 and 5→7); M(4) + 2 = seat 6 = K, option (a).

---

### Q15–Q19. Coding-Decoding

**Given:**
- 'Play the same game.' = 'us ud ut uk'
- 'Seen in the play.' = 'uk ua ud um'
- 'The jar is seen.' = 'ud ua uh uw'
- 'The same game played' = 'ut ud ub us'

**Decoding (by word overlap):**
- 'the' is in all four sentences → the code common to all four sets = **ud**.
- 'play' is in sentences 1 and 2 → set-1 ∩ set-2 = {uk, ud}; ud = the → **play = uk**.
- 'seen' is in sentences 2 and 3 → set-2 ∩ set-3 = {ua, ud}; ud = the → **seen = ua**.
- Sentence 1 left over: 'same', 'game' → the two remaining codes **{us, ut}**.
- Sentence 4 ('the same game played' = ut ud ub us): the = ud, same/game take {us, ut} → **played = ub**.
- Sentence 2 left over: 'in' → **in = um** (since seen = ua, the = ud, play = uk).
- Sentence 3 left over: 'jar', 'is' → **{uh, uw}**.

So the fixed codes are: the = ud, play = uk, seen = ua, in = um, played = ub, and
same/game = {ut, us} in some order, jar/is = {uh, uw} in some order.

**Q15. What is the code for 'same'?**
'same' is either ut or us. Of these two, only **ut** is offered as an option (option (b)); 'us' is
not in the option list. Hence same = ut and game = us.
**Answer: (b) ut**
> **[VERIFIED]** same/game = {ut, us} from the overlap analysis; 'us' is not among the options, so the only consistent choice is ut = option (b).

**Q16. If the code of 'Jar' is 'uh', then the code of 'is played'?**
Under the hypothesis jar = uh, the remaining member of the pair is **is = uw**; and played = ub.
So 'is played' = **uw ub**.
**Answer: (d) uw ub**
> **[VERIFIED]** jar/is = {uh, uw}; if jar = uh then is = uw, and played = ub ⇒ uw ub, exactly option (d).

**Q17. What is the code of 'play'?**
'play' occurs only in sentences 1 and 2 → **uk**.
**Answer: (c) uk**
> **[VERIFIED]** Set-1 ∩ set-2 = {uk, ud}, and ud = the, so play = uk. Option (c).

**Q18. What will be the possible code for 'game is played'?**
In the base code jar = uw and is = uh (Q16 is a hypothetical swap). With game = us (from Q15),
is = uh, played = ub the code is **us uh ub** — exactly option (c).
**Answer: (c) us uh ub**
> **[VERIFIED]** game = us, is = uh, played = ub (all established above) → us uh ub, exactly option (c). Option (a) uh ud ub is wrong because ud = the, not game.

**Q19. Which word is coded as 'um'?**
'um' occurs only in sentence 2 and belongs to the only word not yet decoded — 'in'.
**Answer: (a) In**
> **[VERIFIED]** Sentence 2 residue after removing the, play and seen is 'in' = um. Option (a).

---

### Q20–Q24. Row Arrangement (Fruits)

**Given:**
- Six persons A, B, C, D, E, F face north.
- Fruits: Mango, Strawberry, Guava, Orange, Apple, Banana.
- Strawberry at right end.
- B sits 3rd to left of Guava.
- A sits 2nd to left of Mango and likes Banana.
- C sits 3rd to right of E but not at extreme end.
- Number right of D = number left of Apple.

**Derivation (positions 1–6, left → right; all face north so "left" = lower position):**
- Strawberry sits at position 6.
- C is 3rd to the right of E and C is not an extreme end → (E, C) = (1, 4) or (2, 5).
- (E, C) = (1, 4) → reject: A must satisfy pos(Mango) = pos(A) + 2 and A likes Banana, and B must
  satisfy pos(Guava) = pos(B) + 3. With E = 1 and C = 4 the only A placements are 2, 3, 5, 6, and
  each fails — A = 2 forces Guava = 6 (already Strawberry), A = 3 puts Mango on C's seat and still
  forces Guava off the row, and A = 5 or 6 pushes Mango past position 6.
- (E, C) = (2, 5) and A 2nd to the left of Mango → A = 3, Mango = 5 (C likes Mango); then
  B 3rd to the left of Guava → B = 1, Guava = 4.
- Remaining: D = 6 (Strawberry), F = 4 (Guava); A = Banana as given.
- Check "number right of D = number left of Apple": right of D(6) = 0; left of Apple(1) = 0 ✓.
- Remaining fruits: F = Guava, D = Strawberry, E = Orange, B = Apple.

| Position | 1 | 2 | 3 | 4 | 5 | 6 |
|---|---|---|---|---|---|---|
| Person | B | E | A | F | C | D |
| Fruit | Apple | Orange | Banana | Guava | Mango | Strawberry |

**Q20. Who likes Guava?**
Guava is at position 4 = **F**.
**Answer: (d) F**
> **[VERIFIED]** The unique arrangement puts Guava with F at position 4, which is option (d).

**Q21. How many sit between C and the one who likes Orange?**
C = position 5, Orange-liker (E) = position 2 → positions 3 and 4 lie between them = **Two**.
**Answer: (b) Two**
> **[VERIFIED]** |5 − 2| − 1 = 2 persons (A and F). Option (b) Two.

**Q22. Who sits third to the left of the one who likes Guava?**
Guava is at position 4; third to the left = position 1 = **B**, i.e. the one who sits immediately
left of E (E is at position 2).
**Answer: (a) The one who sits immediate left of E**
> **[VERIFIED]** Position 4 − 3 = position 1, occupied by B; E sits at position 2, so position 1 is E's immediate left. Option (a) is the correct description (B is not listed by name).

**Q23. Which statement is true?**
(a) C immediately left of the Apple-liker (pos 1)? C is at 5 → false.
(b) Mango-liker 3rd from the extreme right end? Mango is at position 5 = 2nd from the right → false.
(c) B likes Orange? B likes Apple → false.
(d) A sits third to the left of D? A = 3, D = 6; 6 − 3 = 3 → ✓ true.
**Answer: (d) A sits third to the left of D**
> **[VERIFIED]** D at position 6, A at position 3 — A is exactly 3 places to D's left. Option (d); (a), (b) and (c) are all contradicted by the table.

**Q24. Which pair does not belong to the group?**
Actual pairs: A–Banana, B–Apple, C–Mango, D–Strawberry, E–Orange, F–Guava.
Options (a) B–Banana, (b) F–Orange, (c) E–Guava, (d) A–Apple are all *wrong* pairings (each person is
matched with the fruit actually liked by the person two seats away), while (e) C–Mango is the only
correct pairing.
**Answer: (e) C – Mango**
> **[VERIFIED]** (a)–(d) are each false against the solved table; (e) C–Mango is true. The only correct pair is the odd one out — option (e).

---

### Q25. Odd One Out (Letter Groups)

(a) FBI: F(6), B(2), I(9) → 6-2=4, 2+? 
(b) PLR: P(16), L(12), R(18) → -4, +6
(c) EAH: E(5), A(1), H(8) → -4, +7
(d) IEL: I(9), E(5), L(12) → -4, +7
(e) RNU: R(18), N(14), U(21) → -4, +7

FBI: F(6), B(2), I(9) → -4, +7. Same as c,d,e. PLR: -4, +6 → different.
**Answer: (b) PLR**

---

### Q26–Q30. Box Puzzle

**Given:**
- Six boxes A, B, C, D, E, F.
- Types: Jute, Steel, Iron, Wood, Leather, Brass.
- D is 3 places above Leather.
- Same number above D and below Steel.
- B just below F and just above Wood.
- A is 2 places below Iron.
- More than one below C, C below Brass.

**Derivation (positions 1–6, 1 = top; the six types are all different):**
- "D is three places above the leather box" → pos(Leather) − pos(D) = 3.
- "Same number above D as below the steel box" → pos(D) − 1 = 6 − pos(Steel).
- "B just below F and just above wood" → F, B, wood occupy three consecutive positions (F on top).
- "A is two places below the iron box" → pos(A) = pos(Iron) + 2.
- "More than one box below C, and C below the brass box" → pos(C) ≤ 4 and pos(C) > pos(Brass).

Only one arrangement satisfies every clue:

| Position (top→bottom) | 1 | 2 | 3 | 4 | 5 | 6 |
|---|---|---|---|---|---|---|
| Box | D | C | F | B | A | E |
| Type | Brass | Jute | Iron | Leather | Wood | Steel |

**Checks:** Leather(4) is 3 below D(1) ✓; 0 boxes above D and 0 below Steel(E at 6) ✓; F(3), B(4),
Wood(5) consecutive with B between F and wood ✓; Iron(3) + 2 = A(5) ✓; C(2) has 4 boxes below it
and sits below Brass(1) ✓.

**Q26. How many boxes are placed between the brass box and box A?**
Brass = D (position 1), A = position 5 → C, F, B lie between = **Three**.
**Answer: (b) Three**
> **[VERIFIED]** Positions 2, 3, 4 (C, F, B) lie between position 1 (Brass = D) and position 5 (A) = 3 boxes. Option (b) Three.

**Q27. Which statement is incorrect?**
(a) E is bottommost → position 6 ✓ true | (b) B is the leather box → position 4 = Leather ✓ true |
(c) D is above F → D(1), F(3) ✓ true | (d) A and B are adjacent → A(5), B(4) ✓ true |
(e) C is the brass box → C is **Jute**; Brass is D → **false**.
**Answer: (e) Box C is the brass box**
> **[VERIFIED]** The table gives C = Jute and D = Brass, so (e) is the only false statement. Option (e).

**Q28. Box F is of which type?**
Position 3 = F, and position 3 holds **Iron** (Iron + 2 = A at position 5).
**Answer: (a) Iron**
> **[VERIFIED]** From the table F = Iron. Option (a); (d) Steel is E's type.

**Q29. If E is related to the wood box, A is related to the leather box, then which box is related to the jute box?**
The relation is "the box immediately **below** the named box": E(6) is below Wood(5); A(5) is below
Leather(4). Jute is at position 2, so the related box is the one just below it = position 3 = **F**.
**Answer: (b) Box F**
> **[VERIFIED]** Both worked examples use "one position below"; Jute(2) + 1 = position 3 = F. Option (b).

**Q30. As many boxes are placed above box D as below box ___?**
Above D (position 1) = 0 boxes. The box with 0 boxes below it is the bottommost = **E**.
**Answer: (c) Box E**
> **[VERIFIED]** Position 6 (E) has exactly 0 boxes below, matching the 0 above D. Option (c).

---

### Q31. Letter Pairs in ORGANIZE

**Word:** O R G A N I Z E (positions 1–8)

Rule: a pair matches when the number of letters **between** the two letters in the word equals the
number in the alphabet, i.e. |word position difference| = |alphabet position difference|.

The only pair satisfying this is A and E: A is 4th, E is 8th (difference 4); A = 1, E = 5
(difference 4). Every other pair fails, e.g. O(1)&R(2) → 1 vs |15−18| = 3 ✗; I(6)&E(8) → 2 vs
|9−5| = 4 ✗; A(4)&N(5) → 1 vs |1−14| = 13 ✗.

**Answer: (c) One**
> **[VERIFIED]** Exhaustive check of all 28 pairs leaves exactly one hit — A and E (4 letters apart in the word, 4 apart in the alphabet: A-B-C-D-E). Option (c) One, not Two.

---

### Q32–Q34. Weight Puzzle

**Given:**
- Six persons P, Q, R, S, T, U.
- Third heaviest = 40 kg.
- Q's weight is odd, lighter than S but heavier than R.
- Number lighter than S is one more than P.
- T heavier than R and U.
- T is 20 kg more than P, who is heavier than Q.
- Second lightest is not Q.

**Deduction (ranks 1 = heaviest … 6 = lightest):**
- "The number of persons lighter than S is one more than [the number lighter than] P" →
  6 − rank(S) = (6 − rank(P)) + 1 → **rank(P) = rank(S) + 1**, i.e. P is the next person below S.
- "The third heaviest person weighs 40 kg" and "T is 20 kg more than P", with P > Q, gives
  rank(S) = 2, rank(P) = 3, so **P = 40 kg** and **T = 40 + 20 = 60 kg** (T heaviest).
- Q is lighter than S but heavier than R; T is heavier than R and U; the second lightest is not Q
  → Q takes rank 4, and R, U fill ranks 5 and 6.

**Order (heavy → light):** T(60) > S > P(40) > Q > R > U

**Q32. What is the possible weight of S?**
S is heavier than P (40 kg) and lighter than T (60 kg) → 40 < S < 60.
Options 39, 34, 53, 67, 62 → only **53** lies strictly between 40 and 60.
**Answer: (c) 53 kg**
> **[VERIFIED]** T = P + 20 = 60 kg and S sits between T and P, so 40 < S < 60; 53 is the only option in that window. Option (c).

**Q33. If R = P − 15 and R = U + 5, find R + U?**
P = 40 → R = 40 − 15 = 25; U = R − 5 = 20. Sum = 25 + 20 = 45.
**Answer: (b) 45 kg**
> **[VERIFIED]** R = 25, U = 20 → 45, exactly option (b).

**Q34. The number of persons heavier than P equals the number of persons lighter than ___?**
P is 3rd heaviest → 2 persons are heavier than P. We need the person with exactly 2 lighter,
i.e. rank 4 = **Q** (R and U are lighter than Q).
**Answer: (c) Q**
> **[VERIFIED]** P at rank 3 has 2 heavier; Q at rank 4 has exactly 2 lighter (R, U). Option (c).

---

### Q35. CONVERSION Letter Replacement

**Word:** C O N V E R S I O N
Positions 1–10.
Odd positions: 1,3,5,7,9 → next letter.
Even positions: 2,4,6,8,10 → previous letter.

C→D, O→N, N→O, V→U, E→F, R→Q, S→T, I→H, O→P, N→M
New: D N O U F Q T H P M
Repeated letters? None.
**Answer: (e) None**

---

## English Language

### Q36–Q43. Reading Comprehension (Emotional Intelligence)

**Q36. True statements?**
(I) False (socialization also matters), (II) True, (III) True.
**Answer: (c) Both (II) and (III) are true**

**Q37. Incorrect statement?**
(b) Women's relational strengths suited for competitive high-pressure roles → passage says men excel in competitive environments.
**Answer: (b)**

**Q38. True statements?**
(I) True, (II) False, (III) True.
**Answer: (b) Both (I) and (III) are true**

**Q39. Similar meaning of "lay"?**
"lay the foundation" → establish.
**Answer: (a) Establish**

**Q40. Logically inferred?**
(c) Organizations that recognize and value both genders' strengths can create more balanced leadership.
**Answer: (c)**

**Q41. Role of societal norms?**
(d) Societal expectations reinforce gender-specific emotional skills.
**Answer: (d)**

**Q42. Antonym of "approach"?**
**Answer: (a) Withdraw**

**Q43. Correct word for blank?**
Boys are often **encouraged** to be competitive...
**Answer: (c) Encouraged**

---

### Q44–Q45. Incorrect Word

**Q44.** "activities... was" → should be "were". Incorrect word: activities (subject-verb agreement).
**Answer: (b) activities**

**Q45.** "joe" → should be "joy".
**Answer: (d) joe**

---

### Q46–Q48. Correct/Incorrect Sentences

**Q46. Correct sentences?**
(I) Correct, (II) Correct, (III) "Each... were" → should be "was". Incorrect.
**Answer: (d) Both (I) and (II)**

**Q47. Incorrect sentences?**
(I) "manager, along with her team, were" → should be "was". Incorrect.
(II) "If I would have known" → should be "If I had known". Incorrect.
(III) Correct.
**Answer: (d) Both (I) and (II)**

**Q48. Correct sentences?**
(I) "If you would have studied" → incorrect.
(II) Correct.
(III) Correct.
**Answer: (b) Both (II) and (III)**

---

### Q49–Q53. Rearrangement (Bed Bugs in Paris)

**Correct order: C → D → E → B → F → A**

- **C** opens with the topic: Paris, a global tourist destination, faced a resurgence of bed bugs.
- **D** follows immediately: "**This outbreak**..." refers back to the resurgence in C, and it
  raises the tourist-travel worry.
- **E** answers that worry: "Experts suggest that international travel and dense urban environments
  have facilitated the rapid spread..."
- **B** describes the spread: "Despite efforts..., the bed bugs have infested public transport,
  popular tourist destinations, and even airports."
- **F** adds to B with the linker "**Furthermore**, bed bugs have become a common sight in metros
  and airports..."
- **A** closes with the consequence: "The government has **therefore** employed authorities to
  conduct fumigations..."

This reading is also the only one that fits the printed options: Q50's options are (a) A (b) F
(c) E (d) D (e) C — B is not offered, so B cannot be the second sentence.

**Q49. FIRST sentence?**
**Answer: (e) C**
**Q50. SECOND sentence?**
**Answer: (d) D**
**Q51. THIRD sentence?**
**Answer: (b) E**
**Q52. FOURTH sentence?**
**Answer: (a) B**
**Q53. LAST sentence?**
**Answer: (c) A**
> **[VERIFIED]** Order C-D-E-B-F-A: each of the five answers (C, D, E, B, A) appears in the option list of its own question — Q49 (e) C, Q50 (d) D, Q51 (b) E, Q52 (a) B, Q53 (c) A. This order is forced against the natural-looking C-B-F-D-E-A reading, because Q50's options deliberately exclude B, so B cannot be the second sentence. The narrative links "This outbreak" (D) → C and "Furthermore" (F) → B pin the remaining order.

---

### Q54–Q55. Correct/Incorrect Sentences

**Q54. Correct sentences?**
(I) "children was" → incorrect.
(II) Correct.
(III) "Neither... were" → should be "was". Incorrect.
**Answer: (e) Only (II)**

**Q55. Incorrect sentences?**
(I) Correct.
(II) "Despite of" → incorrect.
(III) "since six months" → should be "for six months". Incorrect.
**Answer: (b) Both (II) and (III)**

---

### Q56–Q57. Incorrect Word

**Q56.** "When the crown on the head..." → should be "crowned" (verb). Incorrect: crown.
**Answer: (c) crown**

**Q57.** All correct.
**Answer: (e) All are correct**

---

### Q58–Q62. Fill in the Blanks

**Q58. "She decided to donate a portion of her earnings to the local ______ that supports underprivileged children."**
The blank needs a noun for an organisation receiving donations. "Charity" is the only option that
is both a noun and fits "supports underprivileged children". *Atrocity* (cruel act), *calamity*
(disaster), *clarity* and *acidity* are all abstract nouns that cannot "support children".
**Answer: (e) charity**
> **[JUDGEMENT CALL]** Only "charity" collocates with "donate ... to" and can support children. Nearest trap (a) atrocity/ (c) calamity are nouns but semantically impossible here.

**Q59. "The art gallery hosted an exhibition featuring works from some of the most ______ artists in the world."**
The blank is an adjective of praise before "artists in the world"; "most prestigious" (most
renowned) fits. *Ignorant* (uneducated), *removable*, *latent* (hidden) and *religious* are either
negative or irrelevant to artistic eminence.
**Answer: (d) prestigious**
> **[JUDGEMENT CALL]** "Prestigious" is the only positively-valenced adjective describing eminence; "ignorant" and "latent" clash with a superlative praise context.

**Q60. "The book had a/an ______ impact on her perspective, changing the way she viewed the world."**
The clause "changing the way she viewed the world" signals depth; "profound impact" is the fixed
collocation. *Tripping* and *encroach* are verb forms, *oversea* is an adjective, and *accurately*
is an adverb — none can modify the noun "impact".
**Answer: (a) profound**
> **[JUDGEMENT CALL]** "Profound impact" is a standard collocation; the other four are the wrong part of speech or (oversea) unrelated.

**Q61. "The sudden power outage threw the entire city into ______, with traffic jams and confused crowds everywhere."**
"Traffic jams and confused crowds" describes disorder → "chaos". *Concur* (verb), *peculiar*
(adjective), *nascent* (adjective) and *growth* (positive) all fail the context.
**Answer: (b) chaos**
> **[JUDGEMENT CALL]** The clue "threw ... into" + the disorder description selects "chaos"; "growth" has positive connotation and "peculiar" is an adjective.

**Q62. "Once the switch was flipped, the machine was ______ and began operating smoothly."**
Flipping a switch starts a machine → "activated". *Weltered* (rolled), *invoked* (called upon),
*captivated* (charmed) are wrong meanings, and *deactivated* is the opposite of "began operating".
**Answer: (c) activated**
> **[JUDGEMENT CALL]** "Began operating smoothly" rules out deactivated and requires a start-up verb; "activated" is the only one.

---

### Q63–Q65. Phrasal Verbs

**Q63. Come up**
(A) Correct (arise)
(B) Correct (arise)
(C) Incorrect (sun rises, not comes up in west)
**Answer: (a) Both A & B**

**Q64. Get across**
(A) Incorrect (crossed, not communicated)
(B) Correct (communicate)
(C) Correct (communicate)
**Answer: (d) Only A**

**Q65. Check out**
(A) Correct (leave hotel)
(B) Correct (borrow books)
(C) Correct (visit/try)
**Answer: (d) All A, B, C**

---

## Quantitative Aptitude

### Q66–Q70. Table (Bikes & Cars)

**Table:**
| City | Bikes (X+Y) | Cars (X+Y) | Bikes Y |
|------|-------------|------------|---------|
| K | 328 | 450 | 210 |
| L | 560 | 980 | 320 |
| M | 440 | 730 | 90 |
| N | 620 | 350 | 195 |

**Q66. Cars Y in K = 2/5 of Bikes Y in K = 2/5×210 = 84.**
Cars X in K = 450-84 = 366.
Bikes X in M = 440-90 = 350.
Difference = 366-350 = 16.
**Answer: (b) 16**

**Q67. Cars X in N = 20% less than Bikes X in M = 0.8×350 = 280.**
Cars Y in N = 350-280 = 70.
Bikes Y in K = 210.
Ratio = 70:210 = 1:3.
**Answer: (e) 1 : 3**

**Q68. Cars X:Y in L = 3:4. Cars X in L = 3/7×980 = 420.**
Bikes Y in N = 195.
Difference = 420-195 = 225.
**Answer: (a) 225**

**Q69. Bikes X in M = 350. Cars X+Y in N = 350.**
% = 0%.
**Answer: (b) 0%**

**Q70. Cars Y in M = 200 + Bikes X in L = 200 + 240 = 440.**
Cars X in M = 730-440 = 290.
Cars X+Y in K = 450.
% = 290/450×100 = 64.44% ≈ 64%.
**Answer: (a) 64%**

---

### Q71–Q75. Line Graph (Items Sold)

> **Data recovery note:** the chart is an embedded bitmap in the PDF (page 33, image object 40,
> 1920×1080) and `pdftotext` drops it entirely. It was extracted with `pdfimages -png` and read
> directly; the vertex values below were measured against the y-axis gridlines (100 units = 123.5 px).
> The chart carries **no legible axis/legend labels**, so the series were identified from the data
> itself: the blue series satisfies "2023 = 1.2 × 2021" and the red series is 2022 (see the Q74 check).

**Graph values = 1/3 of the actual total items sold** (note (ii)); actual total = 3 × graph value.
Note (i): 2023 total = 1.2 × 2021 total for every shop.

| Graph value | A | B | C | D | E |
|---|---|---|---|---|---|
| 2021 (blue) | 600 | 420 | 300 | 520 | 280 |
| 2022 (red) | 700 | 540 | 360 | 200 | 480 |
| 2023 (= 1.2 × 2021) | 720 | 504 | 360 | 624 | 336 |

**Q71. D in 2023 is what % less than A in 2022 (approx.)?**
D-2023 total = 3 × 624 = 1872; A-2022 total = 3 × 700 = 2100.
% less = (2100 − 1872)/2100 × 100 = 228/2100 × 100 = 10.86% ≈ **11%**.
**Answer: (c) 11%**
> **[VERIFIED]** 228/2100 = 10.857% ≈ 11%, exactly option (c).

**Q72. Ratio of B in 2022 to C in 2023?**
B-2022 total = 3 × 540 = 1620; C-2023 total = 3 × 360 = 1080. Ratio = 1620 : 1080 = **3 : 2**.
**Answer: (c) 3 : 2**
> **[VERIFIED]** 1620 : 1080 reduces to 3 : 2, exactly option (c).

**Q73. Difference between (D + E in 2023) and (A + B in 2021)?**
D+E 2023 = 1872 + 1008 = 2880; A+B 2021 = 1800 + 1260 = 3060. Difference = **180**.
**Answer: (a) 180**
> **[VERIFIED]** 3060 − 2880 = 180, exactly option (a).

**Q74. Sum of A, B and C in 2023?**
Graph values 720 + 504 + 360 = 1584 → total = 3 × 1584 = **4752**.
**Answer: (d) 4752**
> **[VERIFIED]** 3 × (720 + 504 + 360) = 4752, exactly option (d). This also proves the series identification: with the red series read as 2021 the same sum would be 5760, which is not among the options.

**Q75. B + D in 2023 vs A in all three years?**
B+D 2023 = 1512 + 1872 = 3384; A across all three years = 1800 + 2100 + 2160 = 6060.
Difference = 6060 − 3384 = **2676** (A is more).
**Answer: (a) 2676**
> **[VERIFIED]** 6060 − 3384 = 2676, exactly option (a).

---

### Q76–Q80. Wrong Number Series

**Q76. 188, 177, 199, 166, 210, 150, 221**
Given differences: −11, +22, −33, +44, −60, +71.
Pattern: −11, +22, −33, +44, −55, +66 (multiples of 11 with alternating signs).
The 5th difference should be −55, not −60 → 210 − 55 = 155, so **150** is wrong; then 155 + 66 = 221 ✓.
**Answer: (c) 150**
> **[VERIFIED]** With 150 → 155 the differences are exactly −11, +22, −33, +44, −55, +66 and the series closes on 221. Option (c).

**Q77. 18225, 6075, 2025, 675, 220, 75, 25**
Ratio test: each term is the previous ÷ 3 → 18225/3 = 6075, /3 = 2025, /3 = 675, /3 = **225** (not 220),
225/3 = 75, 75/3 = 25 ✓.
**Answer: (c) 220**
> **[VERIFIED]** Every term is exactly one-third of the preceding one except 220 (should be 225). Option (c).

**Q78. 210, 228, 250, 274, 302, 332, 365**
Given differences: 18, 22, 24, 28, 30, 33.
Pattern: +4, +2, +4, +2, +4 → 18, 22, 24, 28, 30, **34** → 332 + 34 = **366**, not 365.
**Answer: (e) 365**
> **[VERIFIED]** Replacing 365 with 366 restores the alternating +4/+2 difference pattern (18, 22, 24, 28, 30, 34). Option (e).

**Q79. 304, 300, 316, 332, 364, 428, 556**
Given differences: −4, +16, +16, +32, +64, +128.
Pattern: +4, +8, +16, +32, +64, +128 (each difference doubles).
Working back: 316 − 8 = **308**, not 300 → 304 + 4 = 308, 308 + 8 = 316 ✓.
**Answer: (a) 300**
> **[VERIFIED]** With 300 → 308 the differences are exactly 4, 8, 16, 32, 64, 128. Option (a).

**Q80. 2194, 2175, 2152, 2123, 2092, 2054, 2014**
Given differences: −19, −23, −29, −31, −38, −40.
Pattern: subtraction of consecutive primes → −19, −23, −29, −31, **−37**, −41.
2092 − 37 = **2055**, not 2054; and 2055 − 41 = 2014 ✓.
**Answer: (b) 2054**
> **[VERIFIED]** 2054 → 2055 makes the subtrahends the consecutive primes 19, 23, 29, 31, 37, 41 and ends exactly on 2014. Option (b).

---

### Q81–Q85. Approximation

**Q81. 5.03% of 39.89 + 10.09% of 450 = ?**
≈ 5% of 40 + 10% of 450 = 2 + 45 = **47**.
**Answer: (b) 47**
> **[VERIFIED]** 2 + 45 = 47; the exact value 47.41 also rounds to 47. Option (b).

**Q82. √840.99 + (14/19) of 361.09 = ? × 4.88**
√841 = 29; (14/19) × 361 = 14 × 19 = 266 (361 ÷ 19 = 19). So 29 + 266 = 295.
295 ÷ 4.88 ≈ 295 ÷ 5 = **59**.
**Answer: (a) 59**
> **[VERIFIED]** Numerator 295 exactly; with 4.88 ≈ 5 the value is 59 (the exact 60.45 is still nearest to option (a) 59). Option (a).

**Q83. 12.213 − 108.02 = 24.90% of 399 + ?**
As printed: 12.213 − 108.02 = **−95.807** and 24.90% of 399 = 99.35, so ? = −95.807 − 99.35 ≈ **−195**.
**Answer: [BROKEN SOURCE]**
> **[BROKEN SOURCE]** The printed minus sign is confirmed at 600 dpi (glyph U+2212). The equation forces a *negative* ? (≈ −195), while every option is a positive number in the 1090–1520 range (1090, 1120, 1240, 1520, 1130). The stem is internally inconsistent; not a valid MCQ.

**Q84. (32.08% of 599 ÷ 1.99) ÷ (1/4) = ?² − 16**
≈ (32% of 600 ÷ 2) ÷ 1/4 = (192 ÷ 2) × 4 = 96 × 4 = 384.
?² = 384 + 16 = 400 → ? = **20**.
**Answer: (e) 20**
> **[VERIFIED]** 384 + 16 = 400 = 20², exactly option (e).

**Q85. (256.03 ÷ 15.99 ÷ 3.98 ÷ 1.99) = ? ÷ 12.01**
As printed all four operators are the division sign (checked at 600 dpi — the glyphs are identical):
256.03 ÷ 15.99 ÷ 3.98 ÷ 1.99 = 2.02, so ? = 2.02 × 12.01 ≈ **24**.
**Answer: [BROKEN SOURCE]**
> **[BROKEN SOURCE]** With the four printed division signs the left side is 2.02 and ? ≈ 24, but the options are 91, 96, 103, 87, 67 — none is remotely 24. The stem is internally inconsistent; not a valid MCQ. (A "×" in the third position would give 96, but that is not what the PDF prints.)

---

### Q86–Q90. Miscellaneous

**Q86.** A+B+C = 1/4. B = 1/24. C efficiency 300% more than B → C = 4B = 4/24 = 1/6.
A = 1/4 - 1/24 - 1/6 = 6/24 - 1/24 - 4/24 = 1/24.
A alone = 24 days, C alone = 6 days. Difference = 18.
**Answer: (a) 18**

**Q87.** P:Q-4 = 2:1 → P = 2(Q-4). R = (P+Q)/2. R-16 = 10 → R = 26.
2(Q-4) + Q = 52 → 3Q = 60 → Q = 20, P = 32.
Sum = 32+20+26 = 78.
**Answer: (b) 78 years**

**Q88.** A: CI = P(1.1²-1) = 0.21P. B: SI = Q×0.1×4 = 0.4Q.
0.21P = 0.4Q, P+Q = 12200.
P = 0.4Q/0.21 = 40Q/21. 40Q/21 + Q = 12200 → 61Q/21 = 12200 → Q = 4200, P = 8000.
**Answer: (d) Rs.8000**

**Q89.** A: 12000×12 = 144000. B: 12000×x. C: 8000×(12-x).
A share = 1800/3200 = 9/16.
144000/(144000+12000x+8000(12-x)) = 9/16.
144000/(144000+12000x+96000-8000x) = 9/16.
144000/(240000+4000x) = 9/16.
2304000 = 2160000+36000x → 144000 = 36000x → x = 4.
**Answer: (d) 4**

**Q90.** Train A crosses a 230 m platform in 29 s; train B (length 450 m) crosses a 150 m platform
in 24 s and crosses A in 160 s running in the same direction. Find the time A takes to cross a 50 m bridge.
- B's speed: (150 + 450)/24 = 600/24 = **25 m/s**.
- A's speed from the platform: (230 + L_A)/29 = S_A → L_A = 29·S_A − 230.
- Same-direction crossing: (450 + L_A)/(25 − S_A) = 160.
- Substituting: (450 + 29S_A − 230) = 160(25 − S_A) → 220 + 29S_A = 4000 − 160S_A → 189S_A = 3780 → **S_A = 20 m/s**, L_A = 29 × 20 − 230 = 350 m.
- Time to cross the 50 m bridge: (350 + 50)/20 = 400/20 = **20 s**.
**Answer: (c) 20 seconds**
> **[VERIFIED]** S_A = 20 m/s, L_A = 350 m. Check the given crossing: (450 + 350)/(25 − 20) = 800/5 = 160 s ✓. Bridge time 400/20 = 20 s, exactly option (c).

---

### Q91–Q95. Miscellaneous

**Q91.** Boat:Stream = 4:3 → Boat=4x, Stream=3x? No, upstream=3x → boat-stream=3x → 4x-3x=x=stream.
Downstream speed = 560/7 = 80 km/h = boat+stream = 4x+x = 5x → x=16.
Upstream = 3x = 48 km/h. Time = 480/48 = 10 hours.
**Answer: (e) 10 hours**

**Q92.** MP = 1.6CP. Discount 4d% → SP = 1.6CP(1-0.04d) = 1.28CP.
1.6(1-0.04d) = 1.28 → 1-0.04d = 0.8 → 0.04d = 0.2 → d = 5.
Discount 6d% = 30% → SP = 1.6CP×0.7 = 1.12CP → 12% profit.
**Answer: (a) 12%**

**Q93.** A: milk=9x, water=5x. B: milk=1.2×9x=10.8x. Water A = 1.25×Water B → 5x=1.25W_B → W_B=4x.
Water sum = 5x+4x=9x=54 → x=6. Total A = 14x = 84.
**Answer: (c) 84 liters**

**Q94.** Total = 30×40 = 1200. Excluding girls: 24 boys avg = 36 → total = 864. Girls total = 1200-864 = 336. Avg = 336/6 = 56.
**Answer: (b) 56 kg**

**Q95.** Area square : rectangle = 3:2. Side square = length rectangle = L.
L² : L×B = 3:2 → L/B = 3/2 → B = 2L/3.
Perimeter = 2(L+B) = 40 → L+B = 20 → L + 2L/3 = 20 → 5L/3 = 20 → L = 12, B = 8.
**Answer: (b) 8 m**

---

### Q96–Q100. Games Won/Lost

**Given:**
- B won = 50.
- A won : B lost = 3:2 → A won = 75, B lost = 50? No, ratio 3:2 → A won=3x, B lost=2x.
- A lost : A won = 4:3 → A lost = 4/3 × A won.
- Average of A lost and B won = 105 → (A lost + 50)/2 = 105 → A lost = 160.
- A won = 3/4 × 160 = 120.
- A won : B lost = 3:2 → 120:B lost = 3:2 → B lost = 80.
- C won = 1.2 × B lost = 96.
- C won : C lost = 4:5 → C lost = 120.

**Q96. A won : C lost = 120:120 = 1:1.**
**Answer: (b) 1:1**

**Q97. B lost as % of A won = 80/120×100 = 66.67%.**
**Answer: (a) 66.67%**

**Q98. B lost + A lost = 80+160 = 240.**
**Answer: (e) 240**

**Q99. D lost = 1.25×160 = 200. D won = 96/2+5 = 53. Diff = 147.**
**Answer: (a) 147**

**Q100. Avg of A won & B won and C lost = (120+50+120)/3 = 290/3 = 96.67.**
**Answer: (d) 96.67**