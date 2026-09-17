# Digital Circuits – Formula/Concept vs. Question Count Analysis

**Source:** Study Material – GTD PYQs 2026 (Digital Circuits)  
**Total Questions Analyzed:** 60+ (Pages 1-12)

---

## 📚 Table of Contents

1. [Formula/Concept vs. Question Count Analysis](#-formulaconcept-vs-question-count-analysis)
2. [The 5-Question Decision Flowchart](#-the-5-question-decision-flowchart)
3. [How to Identify the Topic from the Question](#-how-to-identify-the-topic-from-the-question)
4. [The Ultimate "What Happens When..." Cheat-Sheet](#-the-ultimate-what-happens-when-cheat-sheet)
5. [Top 10 Concepts to Score >90%](#-top-10-concepts-to-score-90)
6. [Quick Reference Card (Exam Day)](#-quick-reference-card-exam-day)

---

## 📊 Formula/Concept vs. Question Count Analysis

| S.No | Formula / Concept | No. of Qs | What They GIVE in the Question | What They ASK in the Question | Mapped Question Numbers |
| :---: | :-------------------------------------------------------------- | :---: | :--- | :--- | :--- |
| **1** | **Number Systems & Conversions** <br> Binary to Decimal: `Σ(bit × 2^n)` <br> Decimal to Binary: Repeated division by 2 <br> Binary to Gray: `G = B ⊕ (B >> 1)` <br> Gray to Binary: `B_n = G_n, B_{n-1} = B_n ⊕ G_{n-1}` <br> 2's complement: Invert + 1 | **~12** | Binary, Decimal, Octal, Hexadecimal, Gray code, 2's complement. | **Conversion** between number systems, **2's complement** representation, **Gray code** equivalent. | Q6, Q7, Q11, Q13, Q15-Q27 |
| **2** | **Boolean Algebra & Simplification** <br> Basic laws: `A+0=A`, `A+1=1`, `A·0=0`, `A·1=A` <br> De Morgan's: `(A+B)' = A'B'`, `(AB)' = A'+B'` <br> K-map: Grouping of 1s (2, 4, 8, ...) <br> SOP/POS forms | **~12** | Boolean expression, Truth table, K-map. | **Simplified Boolean expression** , **SOP/POS form** , **Truth table** to expression, **K-map minimization**. | Q1, Q4, Q5, Q8, Q10, Q14, Q17, Q20, Q22, Q27, Q28, Q29 |
| **3** | **Combinational Circuits (MUX, Adder, Comparator)** <br> MUX: `Y = Σ(m_i × I_i)` <br> Full Adder: `S = A⊕B⊕C`, `C_out = AB + C(A⊕B)` <br> Comparator: `A>B = AB'`, `A=B = (A⊕B)'`, `A<B = A'B` | **~10** | Input variables, MUX inputs, Adder/Comparator circuit. | **MUX output** expression, **Adder sum/carry** , **Comparator output** . | Q3, Q8, Q14, Q27 |
| **4** | **Sequential Circuits (Flip-Flops)** <br> D-FF: `Q(t+1) = D` <br> T-FF: `Q(t+1) = T⊕Q` <br> JK-FF: `Q(t+1) = JQ' + K'Q` <br> SR-FF: `Q(t+1) = S + R'Q` | **~10** | Present state (Q_n), Inputs (J, K, D, T, S, R), Clock. | **Next state** , **Flip-flop type** identification, **Characteristic table/equation**. | Q1, Q9, Q12, Q17, Q24, Q28 |
| **5** | **Counters** <br> Ripple/Asynchronous: `f_out = f_clk / 2^n` <br> Johnson counter: `2n` states <br> Ring counter: `n` states <br> MOD-n counter: counts from 0 to n-1 | **~8** | Number of flip-flops, Initial state, Number of clock pulses. | **Frequency division** , **State after N clocks** , **Number of unused states** , **Maximum clock frequency** of ripple counter. | Q2, Q3, Q4, Q6, Q11, Q15 |
| **6** | **ADC & DAC** <br> Flash ADC: `2^n - 1` comparators <br> Successive Approximation: `n` comparisons, `n` clocks <br> DAC: `V_o = (V_ref / 2^n) × D` <br> Resolution: `1/(2^n - 1)` <br> SNR: `1.78 + 6.02n` dB | **~8** | Number of bits (n), Reference voltage (V_ref), Digital input. | **Number of comparators** , **Conversion time** , **Output voltage** , **Resolution** , **SNR**. | Q1-Q28 |
| **7** | **Logic Gates (Universal)** <br> NAND & NOR are universal gates <br> AND, OR, NOT are basic gates <br> EX-OR: `Y = AB' + A'B` <br> EX-NOR: `Y = AB + A'B'` | **~6** | Gate symbols, Inputs. | **Output expression** , **Gate identification** , **Minimum gates** required to implement a function. | Q2, Q9, Q10, Q12, Q18, Q23 |

---

## 🧭 The 5-Question Decision Flowchart

| Step | Question to Ask | If YES → | If NO → |
| :---: | :-------------------------------------------------------------- | :--- | :--- |
| **1** | **Is it about numbers (binary, hex, Gray)?** | Use **Number Systems** formulas | Go to Step 2 |
| **2** | **Is it about Boolean expression simplification?** | Use **Boolean Algebra/K-map** | Go to Step 3 |
| **3** | **Does it have a clock?** | It's **Sequential** → Go to Step 4 | It's **Combinational** → Use MUX/Adder formulas |
| **4** | **Is it about a flip-flop?** | Use **Flip-Flop** characteristic equations | It's a **Counter** → Use counter formulas |
| **5** | **Is it about ADC or DAC?** | Use **ADC/DAC** formulas (comparators, conversion time, resolution) | It's a **theory/definition** question. |

---

## 🔑 How to Identify the Topic from the Question

| Keywords in Question | Topic | Go-to Formula |
| :--- | :--- | :--- |
| "Binary", "hexadecimal", "Gray code", "2's complement" | **Number Systems** | Conversion formulas |
| "Simplify", "Boolean", "K-map", "SOP", "POS" | **Boolean Algebra** | K-map minimization |
| "MUX", "multiplexer", "adder", "comparator" | **Combinational Circuits** | MUX/Adder expressions |
| "Flip-flop", "D-FF", "JK-FF", "present state" | **Flip-Flops** | Characteristic equations |
| "Counter", "clock pulses", "MOD-n", "ripple" | **Counters** | f_out = f_clk / 2^n |
| "ADC", "DAC", "comparators", "resolution", "conversion time" | **ADC/DAC** | Flash/SAR formulas |

---

## 📝 The Ultimate "What Happens When..." Cheat-Sheet

| Change Made | Effect |
| :--- | :--- |
| **↑ Number of bits (n)** | ↑ Resolution, ↑ Conversion time, ↑ Comparators (Flash) |
| **↑ Clock frequency** | ↓ Conversion time, ↑ Counter speed |
| **↑ Reference voltage** | ↑ Output voltage (DAC), ↑ Step size (ADC) |
| **Adding more flip-flops** | ↑ Counter modulus (2^n states) |
| **Johnson counter (n FF)** | 2n states (vs n for ring counter) |
| **K-map grouping** | Larger groups → Simpler expression |

---

## 🎯 Top 10 Concepts to Score >90%

| Rank | Concept | Weightage | Key Formulas |
| :---: | :-------------------------------------------------------------- | :---: | :--- |
| **1** | **Boolean Algebra & K-map** | ~20% | SOP, POS, De Morgan's, K-map grouping |
| **2** | **Number Systems** | ~20% | Binary to Gray, 2's complement, Base conversions |
| **3** | **Flip-Flops** | ~15% | D, T, JK, SR characteristic equations |
| **4** | **Counters** | ~12% | f_out = f_clk/2^n, MOD-n, Johnson states |
| **5** | **ADC & DAC** | ~12% | Comparators, resolution, conversion time |
| **6** | **Combinational Circuits (MUX, Adder)** | ~10% | MUX output, Full adder sum/carry |
| **7** | **Logic Gates** | ~6% | Universal gates (NAND, NOR) |
| **8** | **Multiplexer Implementation** | ~5% | Minimum MUX count |

---

## 📌 Quick Reference Card (Exam Day)

| Concept | Formula | Quick Tip |
| :--- | :--- | :--- |
| **Binary to Gray** | `G = B ⊕ (B >> 1)` | XOR with right shift |
| **Gray to Binary** | `B_n = G_n, B_{n-1} = B_n ⊕ G_{n-1}` | Start from MSB |
| **2's Complement** | Invert + 1 | Negative number representation |
| **De Morgan's** | `(A+B)' = A'B'`, `(AB)' = A'+B'` | |
| **D-FF** | `Q(t+1) = D` | Data passes through |
| **T-FF** | `Q(t+1) = T⊕Q` | Toggles when T=1 |
| **JK-FF** | `Q(t+1) = JQ' + K'Q` | |
| **Flash ADC Comparators** | `2^n - 1` | Very fast, high cost |
| **SAR ADC Conversion Time** | `n × T_clock` | 1 clock per bit |
| **DAC Output** | `V_o = V_ref × D / 2^n` | D = decimal input |
| **Resolution** | `1/(2^n - 1)` or `1/2^n` | Percentage resolution |
| **SNR (ADC)** | `1.78 + 6.02n` dB | For ideal ADC |
| **Ripple Counter f_out** | `f_clk / 2^n` | Each stage divides by 2 |
| **Johnson Counter States** | `2n` | n = number of FFs |

---

# 📝 FULL PYQ ANALYSIS — All 85 Digital Questions (Concept through PYQ)

> Source: Study_Material__GTD_PYQs_2026_05_26_6_Digital_Circuits_P.pdf (OHM Institute)
> Every question: answer + options, the concept it teaches, and how the examiner twists it.

**Legend:** Q = question · Ans = correct option · Concept = new term/principle · Twist = examiner variation → new answer

## Unit 1: Number System & Coding Conversion (29 Qs)

**Q1 (Transco-12):** For the circuit shown in figure (two-level NAND–NAND network with inputs P, Q and R, S), the Boolean expression for the output Y is
(a) P·Q·R·S (b) P + Q + R + S (c) (P + Q)(R + S) (d) (P + Q)(R + S)
**Ans: (b)** — two-level NAND–NAND is equivalent to AND–OR (De Morgan), giving Y = P + Q + R + S.
**Concept:** two-level logic equivalence; NAND–NAND realizes a sum-of-products (A·B = A + B).
**Twist:** draw same function with OR–NOR → realizes product-of-sums (P + Q)(R + S). Make it a single 4-input NAND on P, Q, R, S → Y = P·Q·R·S.

**Q2 (EPDCL-14):** The gate whose output is high when all inputs are low and low for all other combinations of inputs is
(a) OR gate (b) AND gate (c) NAND gate (d) NOR gate
**Ans: (d)** — NOR outputs 1 only at the all-0 input row (00 → 1).
**Concept:** NOR truth table; high only when every input is 0.
**Twist:** high when at least one input is high → OR gate. Low only when all inputs high → NAND gate. High only when all inputs high → AND gate.

**Q3 (APSPDCL-14):** Identify the 1-bit comparator circuit (four gate figures given as options a–d).
(a) [figure] (b) [figure] (c) [figure] (d) [figure]
**Ans: (a)** — the X-OR gate acts as the unequal (1-bit) comparator; its output is high when the two bits differ.
**Concept:** X-OR (A⊕B) detects inequality; X-NOR (A⊙B) detects equality in a 1-bit comparator.
**Twist:** ask which gate gives high when A = B → X-NOR (exclusive-NOR). Make it 2-bit comparator A1A0 > B1B0 → cascade of X-NORs + AND.

**Q4 (APSPDCL-14):** A network has the given truth table (x1 x2 f: 00→1, 01→1, 10→0, 11→1). f is given by
(a) x1 + x2 + x2 (b) x1 + x2 + x1x2 (c) x1 + x1x2 (d) x1x2 + x2x1
**Ans: (c)** — f = Σm(0,1,3) = x1' + x1x2 (= x1' + x2).
**Concept:** truth table → minterm list → simplified SOP.
**Twist:** invert f column (1100) → f = x1·x2'. Column 0111 → f = x1 + x2 (OR). Column 1000 → AND gate.

**Q5 (APSPDCL-14):** The circuit shown below is equivalent of (2-input gate network, figure; solution truth table 00→1, 01→1, 10→0, 11→1).
(a) [figure] (b) [figure] (c) [figure] (d) [figure]
**Ans: (d)** — the network reduces (via De Morgan) to f = x1·x2 = x1 + x2 (NAND-class single gate).
**Concept:** collapsing a multi-gate network into an equivalent single gate using De Morgan's theorems.
**Twist:** swap the NAND output with the inverted input line → becomes AND. Add a NOT at NAND output → AND gate.

**Q6 (HMWS-15):** In 2's complement representation, the number 11100101 represents the decimal number
(a) –27 (b) –31 (c) +27 (d) +37
**Ans: (a)** — MSB = 1 ⇒ negative; 2's complement of 11100101 = 00011011 = 27, so the value is –27.
**Concept:** decoding a 2's-complement number: if MSB = 1, magnitude = invert+1 of the bits; sign from MSB.
**Twist:** treat 11100101 as unsigned binary → +229. Ask 2's complement of +27 → 00011011.

**Q7 (HMWS-15):** Binary subtraction of decimal 15 from 43 will utilize which two's complement?
(a) 011100 (b) 110000 (c) 110001 (d) 101011
**Ans: (c)** — 43 − 15 = 43 + (−15); −15 in 6-bit 2's complement = 110001 (15 = 011111 → invert 100000 → +1).
**Concept:** subtraction by adding the 2's complement of the subtrahend; 2's comp of 15 (6-bit) = 110001.
**Twist:** actual result 43−15 = 28 = 011100 → option (a) is the RESULT, not the complement (trap). 15−43 → 2's complement of 43 = 110101 → sum gives −28.

**Q8 (—):** The reduced form of the Boolean expression A[B + C(AB + AC)] is (AB and AC carry overbars)
(a) AB (b) AB (c) AB (d) AB + BC
**Ans: (c)** — applying De Morgan, expansion and absorption reduces the expression to AB.
**Concept:** Boolean simplification; De Morgan ((AB)' = A+B), distribution, absorption A(1+...) = A.
**Twist:** replace the '·' inside with '+' → different simplification path. Verify by plugging A=1,B=0 rows rather than trusting one rule.

**Q9 (TS Genco-15):** The minimum number of 2-input NAND gates required to implement the Boolean function AB'C (A, B, C available) is
(a) two (b) three (c) five (d) six
**Ans: (c)** — 5 NAND gates (B' from 1 NAND; 3-variable AND from 2-input NAND + invert stages).
**Concept:** gate count for NAND-only realization; NOT = NAND with tied inputs; AND = NAND + NOT.
**Twist:** implement AB'C' → also 5 gates. Implement A+B+C with 2-input NANDs → 3 NANDs (2-input OR at top) vs 5 for 3-input.

**Q10 (TS Transco-15):** The Boolean expression Y(A,B,C) = A + BC is to be realized using 2-input gates of only one type. The minimum number of gates required is
(a) 1 (b) 2 (c) 3 (d) 4 or more
**Ans: (c)** — 3 NAND gates: BC (1), A' (1), then A'·(BC)' inverted (1) giving A + BC.
**Concept:** universal-gate (NAND) realization of OR-of-products; A + BC = (A'·(BC)')'.
**Twist:** realize A(B + C) → also 3 gates. Realize with NOR gates only → 3 NORs (dual).

**Q11 (TS Transco-15):** What is the Gray code word for the binary number 101011?
(a) 101011 (b) 110101 (c) 011111 (d) 111110
**Ans: (d)** — Gray bit = MSB copied, then each bit XOR'd with the previous binary bit: 1,1,1,1,1,0.
**Concept:** binary→Gray: g(i) = b(i) ⊕ b(i+1), MSB unchanged.
**Twist:** Gray 111110 back to binary → 101011. Binary 101011 → Gray 111110; check Gray of 1000 → 1100.

**Q12 (TSSPDCL-15):** Which of the following gates can be used to realize all possible combinational logic functions? i. OR ii. NOR iii. Exclusive-OR iv. NAND v. AND
(a) (iii), (iv) and (v) (b) (i), (iii) and (iv) (c) (ii) and (iv) (d) (i) and (v)
**Ans: (c)** — only the universal gates NAND and NOR are functionally complete.
**Concept:** universal gates (NAND, NOR, Implication, Inhibition) vs basic (AND, OR, NOT) and derived (EX-OR, EX-NOR).
**Twist:** which single gate is NOT universal → EX-OR/EX-NOR. Build a NOT using only NAND → tie inputs; using only NOR → tie inputs.

**Q13 (TS Transco-18):** Hexadecimal equivalent of decimal number 757.25 is
(a) 7B2.2B (b) 2F5.40 (c) 3E4.60 (d) 42A.8
**Ans: (b)** — integer 757 = 2F5 (repeated ÷16); fraction 0.25 × 16 = 4.0 ⇒ 2F5.4.
**Concept:** decimal→hex: repeated division by 16 for integer, repeated ×16 for fraction.
**Twist:** 757.25 → octal (1365.2) or binary (1011110101.01). Convert 2F5.4 back to decimal = 757.25.

**Q14 (APEPDCL-19):** The function f(A, B, C) = AB + A·C in SOP form using minterms is (terms carry complements)
(a) f = m0 + m2 + m6 + m7 (b) f = m0 + m1 + m2 + m3 (c) f = m0 + m2 + m4 (d) f = m0 + m2 + m5 + m6
**Ans: (a)** — expanding each product term with (X + X') gives Σm(0,2,6,7).
**Concept:** SOP → minterm expansion by introducing the missing variable in each term.
**Twist:** if the terms were AB + AC (no overbar) → Σm(5,6,7) — a common examiner trap. Convert to POS → product of maxterms ΠM(1,3,4,5).

**Q15 (APSPDCL-19):** The Gray code equivalent of binary 101 is
(a) 000 (b) 111 (c) 101 (d) 110
**Ans: (b)** — g2 = 1, g1 = 1⊕0 = 1, g0 = 0⊕1 = 1 → 111.
**Concept:** binary→Gray via successive XOR with previous bit.
**Twist:** Gray 111 → binary → 101. Binary 1010 → Gray 1111.

**Q16 (AE-TSNPDCL-22):** The decimal value of addition of two binary numbers 10111011 and 11101010 is
(a) 420 (b) 417 (c) 419 (d) 421
**Ans: (d)** — sum = 110100101₂ = 2⁸+2⁷+2⁵+2²+2⁰ = 421.
**Concept:** binary addition with carries, then positional weights (or add as decimal 187 + 234).
**Twist:** both operands as 8-bit → check the carry-out (bit 9). Add 11111111 + 00000001 → 100000000 = 256.

**Q17 (AE-TSSPDCL-22):** The multiplication of two binary numbers 1010 and 1101 is
(a) 10000010 (b) 10000001 (c) 10001010 (d) 10101101
**Ans: (a)** — 1010₂ × 1101₂ = 10 × 13 = 130 = 10000010₂.
**Concept:** binary multiplication = shift-and-add; convert via decimal for speed.
**Twist:** divide 10000010 by 1101 → 1010. Square 1010 → 1100100 (100).

**Q18 (AE-TSSPDCL-22):** Convert decimal number (185)₁₀ to Hexadecimal.
(a) 9B (b) B9 (c) C9 (d) A8
**Ans: (b)** — 185 ÷ 16 = 11 rem 9, 11 = B ⇒ B9 (remainders LSB-first).
**Concept:** decimal→hex repeated division by 16; 11 → B.
**Twist:** 185 → binary 10111001. 185 → octal 271. Reverse: B9 → decimal 185.

**Q19 (TSPSC-AEE-23):** The octal representation of 111100010001 is
(a) 6541 (b) 7421 (c) 7241 (d) 6512
**Ans: (b)** — group 3 bits from the right: 111 100 010 001 = 7 4 2 1 = 7421.
**Concept:** binary→octal = 3-bit groups (2³ = 8); binary→hex = 4-bit groups.
**Twist:** same number in hex = 1111 0001 0001 = F11. Convert octal 7421 back to binary (checks group-of-3 rule).

**Q20 (TSPSC-AEE-23):** What is the hexadecimal conversion of this binary number 1111?
(a) F (b) 4 (c) 8 (d) A
**Ans: (a)** — 1111₂ = 15 = F.
**Concept:** binary→hex via 4-bit groups.
**Twist:** 1001₂ → 9. 1111₂ read as 4-bit 2's complement → −1. Add leading zeros: 01111 → 0F.

**Q21 (TSPSC-AEE-23):** The decimal equivalent of the HEX number EF.A is
(a) 239.16 (b) 239.15 (c) 239.6 (d) 239.625
**Ans: (d)** — 14×16¹ + 15×16⁰ + 10×16⁻¹ = 224 + 15 + 0.625 = 239.625.
**Concept:** hex→decimal positional weights, including the 16⁻¹ fraction place.
**Twist:** EF.8 → 239.5. EF.A → binary 1110 1111 . 1010; octal EF.A → 357.5.

**Q22 (TSPSC-AEE-23):** Arrange the given binary numbers in increasing order: I. 0011, II. 1010, III. 0110, IV. 1110
(a) I, II, IV, III (b) I, III, II, IV (c) II, IV, III, I (d) III, I, IV, II
**Ans: (b)** — values 3, 6, 10, 14 → I, III, II, IV.
**Concept:** comparing binary magnitudes column-by-column (or via decimal).
**Twist:** decreasing order → IV, II, III, I. Insert 0101 (5) → order I, III, 0101, II, IV.

**Q23 (TSPSC-AEE-23):** Identify the correct statement(s) related to complements: I. For positive N in base r with n integer digits, r's complement = rⁿ − N for N≠0 and 0 for N=0. II. For positive N with n integer and m fraction digits, (r−1)'s complement = rⁿ − r⁻ᵐ − N.
(a) Only II (b) Both I and II (c) Neither I nor II (d) Only I
**Ans: (b)** — both definitions (r's complement and (r−1)'s complement of a mixed number) are correct.
**Concept:** definition of complement in any base for integer and mixed (fractional) numbers.
**Twist:** 1's complement of 23 = 76; 10's complement = 9's complement + 1 = 77. For a fraction like 0.25, 9's complement = 0.9999 − 0.25.

**Q24 (TSPSC-AEE-23):** Convert (67)₁₀ to binary number.
(a) 1000011 (b) 1100001 (c) 10011 (d) 1101011
**Ans: (a)** — 67 = 1000011₂ (repeated ÷2, remainders LSB-first).
**Concept:** decimal→binary repeated division by 2.
**Twist:** 67 → octal 103, hex 43. Verify 1000011₂ = 64 + 2 + 1 = 67.

**Q25 (TSPSC-AEE-23):** The 10's complement of (23)₁₀ is _____.
(a) 77 (b) 12 (c) 23 (d) 56
**Ans: (a)** — 9's complement = 99 − 23 = 76; 10's complement = 76 + 1 = 77.
**Concept:** 10's complement = 9's complement + 1 = 10ⁿ − N.
**Twist:** 9's complement of 23 → 76 (trap: don't add 1). 10's complement of 123 → 877. Use for subtraction: 80 − 23 = 80 + 77 − 100 = 57.

**Q26 (TSPSC-AEE-23):** Convert (152.2)₈ to decimal number.
(a) 106.25 (b) 384.2 (c) 152.2 (d) 214.52
**Ans: (a)** — 1×8² + 5×8¹ + 2×8⁰ + 2×8⁻¹ = 64 + 40 + 2 + 0.25 = 106.25.
**Concept:** octal→decimal positional weights including the 8⁻¹ fraction place.
**Twist:** (152.2)₈ → binary 001 101 010 . 010 → hex 6A.4. Keep fraction: (0.4)₈ = 0.5 decimal.

**Q27 (TSPSC-AEE-23):** Convert (123)₁₀ to hexadecimal number.
(a) 6C (b) 5D (c) 7B (d) 8A
**Ans: (c)** — 123 ÷ 16 = 7 rem 11(B) ⇒ 7B.
**Concept:** decimal→hex repeated division by 16.
**Twist:** 123 → binary 1111011. 123 → octal 173. Reverse: 7B → 123.

**Q28 (TSPSC-AEE-23):** Simplify the following Boolean function F = ABC + ABC + ABC + ABC (complemented terms, minterms 1,7,3,5).
(a) C (b) ABC (c) A + BC (d) AC
**Ans: (a)** — Σm(1,3,5,7) on a K-map groups to F = C.
**Concept:** K-map simplification; a column/row of minterms sharing one variable reduces to that variable.
**Twist:** Σm(0,2,4,6) → C̄. Σm(3,7) → BC. Add a minterm 0 → F = C + A'B'C' = C + A'B'.

**Q29 (TSPSC-AEE-23):** Identify the correct pair(s) from the given pairs: I. x + 0 = x: Postulate 2, II. x + x' = 1: Postulate 5, III. x + y = y + x: Postulate 3, IV. x(y + z) = xy + xz: Postulate 4.
(a) I, III and IV only (b) I, II, III and IV (c) III and IV only (d) I and II only
**Ans: (b)** — all four (identity, complement, commutative, distributive) are correctly matched.
**Concept:** Boolean algebra postulates 1–6 (identity, complement, commutative, distributive, associativity).
**Twist:** x·0 = 0 is a THEOREM (annulment), not a postulate → trap if asked to match. x + xy = x is the absorption theorem.

## Unit 2: Combinational & Sequential Circuits (28 Qs)

**Q1 (Transco-12):** The frequency of the clock applied to the rising-edge triggered D flip-flop (figure: D tied to Q-bar, toggle connection) is 10 kHz. The frequency of the signal at Q is:
(a) 10 kHz (b) 2.5 kHz (c) 20 kHz (d) 5 kHz
**Ans: (d)** — D-FF wired with D = Q' toggles on every clock edge, so f_Q = f_clk/2 = 5 kHz.
**Concept:** Toggle-mode D flip-flop (D = Q') divides clock frequency by 2.
**Twist:** Cascade two such toggle stages → f/4 = 2.5 kHz (option b). If D = Q (no feedback inversion), the FF holds state and Q is not a frequency divider.

**Q2 (AP Genco-12):** A 3-stage ripple counter uses flip-flops with 25 ns propagation delay and a strobe pulse of 10 ns width. Maximum reliable operating frequency:
(a) 16.67 MHz (b) 17.6 MHz (c) 12.67 MHz (d) 11.76 MHz
**Ans: (d)** — t_conv = n·tpd + t_strobe = 3×25 + 10 = 85 ns → f = 1/85 ns = 11.76 MHz.
**Concept:** Ripple counter period = n·tpd + clock/strobe pulse width; f_max = 1/(n·tpd + t_strobe).
**Twist:** Ignore strobe (only 3×25 = 75 ns) → f ≈ 13.3 MHz. A 4-stage counter with same delays → 110 ns → ≈ 9.09 MHz.

**Q3 (HMWS-12):** Initial state of a MOD-16 counter is 0110. After 37 clock pulses the state is:
(a) 1011 (b) 0110 (c) 0101 (d) 0001
**Ans: (a)** — 37 mod 16 = 5; 0110 + 5 = 1011.
**Concept:** Mod-N counter repeats every N pulses; state = (initial + count mod N) wrapped in n bits.
**Twist:** MOD-16 with 33 pulses → 0110 + 1 = 0111. If it were a down counter, 0110 − 5 = 0001 (option d).

**Q4 (HMWS-15):** The number of unused states in a 4-bit Johnson counter:
(a) 12 (b) 4 (c) 8 (d) 2
**Ans: (c)** — Unused = 2^4 − 2n = 16 − 8 = 8.
**Concept:** n-bit Johnson (switch-tail ring) counter has 2n states; unused = 2^n − 2n.
**Twist:** n = 3 → 8 − 6 = 2 unused. A plain ring counter uses only n states → 2^n − n unused.

**Q5 (HMWS-15):** Which of the following is NOT a characteristic of a flip-flop?
(a) It has one input terminal (b) It has two outputs (c) It has two outputs complementary to each other (d) It is a bistable device
**Ans: (a)** — An FF is bistable with two complementary outputs and needs at least data + clock inputs; "one input terminal" is false.
**Concept:** Flip-flop = bistable, two complementary outputs (Q, Q'); SR/JK/D/T/clock inputs.
**Twist:** SR-FF with S = R = 1 is a forbidden state; a latch is level-sensitive while an FF is edge-triggered.

**Q6 (TS Genco-15):** A 4-bit modulo-16 ripple counter uses JK flip-flops, each with 50 ns propagation delay. Maximum usable clock frequency:
(a) 20 MHz (b) 10 MHz (c) 5 MHz (d) 4 MHz
**Ans: (c)** — Total delay = 4 × 50 = 200 ns → f = 1/200 ns = 5 MHz.
**Concept:** n-bit ripple counter max f = 1/(n·tpd); modulus 2^n.
**Twist:** Mod-4 (2 FFs) → 10 MHz. A synchronous counter pays only one tpd → ≈ 20 MHz (option a). MSB output frequency = f_clk/2^n = 5 MHz/16.

**Q7 (TS Genco-15):** A 10-bit ADC, full-scale 10.24 V, ±LSB/2 accuracy, calibrated at 25 °C, operating 0–50 °C. Maximum net temperature coefficient:
(a) ±200 μV/°C (b) ±400 μV/°C (c) ±600 μV/°C (d) ±800 μV/°C
**Ans: (a)** — LSB = 10.24/1023 ≈ 10 mV; ±LSB/2 ≈ 5000 μV budget over the 25 °C swing from calibration → 5000/25 = 200 μV/°C.
**Concept:** Quantization step LSB = V_FS/(2^n − 1); temp-co budget = (±LSB/2)/ΔT from calibration point.
**Twist:** 8-bit, 5.12 V, ±LSB/2 over 20 °C → LSB = 5.12/255 = 20 mV, half = 10 mV → 500 μV/°C. Full ±LSB (not half) doubles it → 400 μV/°C.

**Q8 (TS Genco-15):** The output f of the 4-to-1 MUX (figure: select lines x, data lines on y) is:
(a) xy+x (b) x + y (c) x + y (d) xy+x
**Ans: (b)** — MUX truth table gives f = x + y.
**Concept:** 4-to-1 MUX: 2^n data inputs, n select lines; output is the sum of selected data terms (implements SOP).
**Twist:** Data lines 0,1,y,y' with x as select → implements XOR/XNOR. Tying all data inputs to 1 makes f = 1 (OR of all minterms).

**Q9 (AP Transco-17):** A switch-tail ring counter made with a single D flip-flop results in:
(a) T-FF (b) D-FF (c) SR-FF (d) JK-FF
**Ans: (a)** — One-stage Johnson (D = Q' feedback) toggles every clock → behaves as a T flip-flop.
**Concept:** Switch-tail (Johnson) counter; a single stage degenerates into a toggle (divide-by-2) circuit.
**Twist:** n-stage Johnson → mod-2n; 1-stage → mod-2. Reverse the feedback to D = Q and it just latches (no count).

**Q10 (TS Transco-18):** Clock frequency of an 8-bit successive-approximation ADC is 2 MHz. Conversion time per sample:
(a) 2 μs (b) 1 μs (c) 4 μs (d) 16 μs
**Ans: (c)** — T_conv = n·Tck = 8 × 0.5 μs = 4 μs.
**Concept:** SAR ADC conversion time = n clock cycles, independent of analog input value.
**Twist:** 10-bit at 1 MHz → 10 μs. Counter-ramp ADC worst case = (2^n − 1)·Tck (e.g., 12-bit, 1 MHz → 4095 μs).

**Q11 (TS Transco-18):** Present outputs of a 3-bit synchronous down counter are 110. After 7 clock pulses the outputs are:
(a) 110 (b) 111 (c) 101 (d) 100
**Ans: (b)** — Down count 110→101→100→011→010→001→000→111 (7th pulse) → 111.
**Concept:** 3-bit down counter sequence; 110 (6) − 7 = −1 → wraps to 111 (7).
**Twist:** 4-bit down counter from 1010 after 5 pulses → 0101. Up counter from 110 after 3 pulses → 001.

**Q12 (AP Transco-19):** Present output Qn of an edge-triggered JK flip-flop is 0. If J = 1, then Qn+1 is:
(a) logic 0 (b) Race around (c) Indeterminate (d) logic 1
**Ans: (d)** — J = 1 with Q = 0 sets the FF → Qn+1 = 1 (K irrelevant here).
**Concept:** JK characteristic: J=1 sets when Q=0; JK=11 toggles; edge-triggering avoids race-around.
**Twist:** Q = 1, J = 1, K = 1 → toggles to 0. Q = 1, J = 1, K = 0 → holds 1.

**Q13 (AP Transco-19):** Minimum number of 2-to-1 multiplexers required to realize an 8-to-1 multiplexer:
(a) 4 (b) 3 (c) 7 (d) 10
**Ans: (c)** — 8/2 + 4/2 + 2/2 = 4 + 2 + 1 = 7.
**Concept:** Mux tree: a 2^n:1 mux needs (2^n − 1) 2:1 muxes.
**Twist:** 16:1 → 15 muxes; 4:1 → 3 muxes; a 2:1 mux can also realize any 2-variable function.

**Q14 (APEPDCL-19):** A full adder is constructed by using:
(a) one OR gate and one half adder (b) two half adders and one OR gate (c) two half adders and two OR gates (d) one half adder and two OR gates
**Ans: (b)** — Sum = A⊕B⊕Cin (2 half adders), Carry = AB + Cin(A⊕B) (1 OR).
**Concept:** Full adder = 2 half adders + 1 OR gate; half adder = XOR + AND.
**Twist:** Full subtractor = 2 half subtractors + 1 OR gate. Using a MUX for sum changes the gate count (no half adders).

**Q15 (APSPDCL-19):** In a 4-bit Johnson counter sequence, the total number of states is:
(a) 1 (b) 3 (c) 4 (d) 8
**Ans: (d)** — 4-bit Johnson counter → 2n = 8 states.
**Concept:** n-bit Johnson counter has 2n states (mod-2n).
**Twist:** 4-bit ring counter → only 4 states. 3-bit Johnson → 6 states; unused states = 8 − 6 = 2.

**Q16 (AE-TSNPDCL-22):** Simplify the Boolean expression: K = ABC + ABC + ABC + ABC (m3, m6, m2, m7).
(a) AB (b) B (c) B (d) ABC
**Ans: (b)** — Σm(2,3,6,7) K-map pairs → K = B.
**Concept:** K-map minimization; adjacent minterm groups collapse to a single literal.
**Twist:** Σm(1,3,5,7) → C. Σm(4,5,6,7) → A. Σm(0,1,2,3) → A'.

**Q17 (AE-TSNPDCL-22):** The shaded area of the Venn diagram (sets A, B, C with overlap regions shaded) is represented by:
(a) A + B + C (b) AB + ABC (c) ABC + ABC (d) AB + ABC
**Ans: (d)** — Shaded region simplifies to AB + ABC.
**Concept:** Venn diagram → Boolean expression; region = intersection of literals, simplified by Boolean algebra.
**Twist:** Shaded A∩B only (no C part) → AB. Shaded only A∩B∩C → ABC.

**Q18 (TSPSC-AEE-23):** The gates designated as Universal Gates:
(a) NOT, OR and AND (b) XOR, OR and AND (c) XNOR, NOR and NAND (d) NOR and NAND
**Ans: (d)** — NAND and NOR are universal gates (can implement any Boolean function).
**Concept:** Universal gates NAND/NOR can build AND, OR, NOT, XOR; derived gates (XOR/XNOR) are not universal alone.
**Twist:** NAND alone builds AND, OR, NOT; a 3-input NAND is also universal. Implication and Inhibition are also functionally complete.

**Q19 (TSPSC-AEE-23):** Choose the correct statement:
(a) Moore and Mealy machine outputs do not depend on input (b) Moore and Mealy machine outputs depend on input (c) Moore and Mealy machine outputs depend on current state (d) Moore and Mealy machine outputs depend on both the input and the current state
**Ans: (c)** — Moore output depends only on present state; Mealy on present state + input; both depend on current state.
**Concept:** Moore vs Mealy FSM output dependence.
**Twist:** Mealy output can glitch (combinational path from input); Moore output is synchronous (clocked). Mealy→Moore conversion may need extra states.

**Q20 (TSPSC-AEE-23):** Minimum sum-of-products for Z = XY + XY + XY (m1, m2, m3):
(a) XY (b) XY (c) X + Y (d) X + Y
**Ans: (c)** — Σm(1,2,3) K-map → Z = X + Y.
**Concept:** 2-variable K-map minimization; all but m0 → OR of the two literals.
**Twist:** Σm(0,2) → Y'. Σm(0,1) → X'. Σm(1,2) → X⊕Y (XOR).

**Q21 (TSSPDCL-AE-2023):** Choose the wrong statement about a 3-φ full converter (figure: bridge, top switches S1, S3, S5 and bottom S4, S6, S2 across phases Va, Vb, Vc):
(a) When S1 conducts S4 should not conduct (b) When S6 conducts S3 should not conduct (c) When S2 conducts S5 should not conduct (d) When S3 conducts S4 should not conduct
**Ans: (d)** — S3 (top, phase b) and S4 (bottom, phase a) are different legs; only same-leg (complementary) pairs must not conduct together.
**Concept:** 3-φ bridge: S1-S4, S3-S6, S5-S2 are same-leg complementary pairs (no shoot-through); cross-leg devices may conduct.
**Twist:** Same-leg pairs: S1↔S4, S3↔S6, S5↔S2 must be complementary. Swap statement to "S3 conducts S6 should not" → correct (same leg).

**Q22 (TSSPDCL-AE-2023):** The minimized expression for output X (figure: A, B, C through gates to X) can be implemented by a:
(a) 2-input OR gate (b) 2-input AND gate (c) 2-input NAND gate (d) 2-input NOR gate
**Ans: (b)** — [(A+B)(B+C)]·B = AB → single 2-input AND gate.
**Concept:** Simplification of a multi-gate network to a minimal single gate.
**Twist:** [(A+B)(B+C)]·C → BC → 2-input AND. [(A+B)(A+C)]·A → A → buffer/connecting wire.

**Q23 (TSPSC-AEE-23):** Match the Gate with its Algebraic function (I EXOR, II EXNOR, III NAND, IV NOR with 1 (xy)', 2 (x+y)', 3 xy'+x'y, 4 xy+x'y'):
(a) I-2, II-4, III-3, IV-1 (b) I-1, II-3, III-2, IV-4 (c) I-3, II-2, III-1, IV-4 (d) I-3, II-4, III-1, IV-2
**Ans: (d)** — EXOR = xy'+x'y (3); EXNOR = xy+x'y' (4); NAND = (xy)' (1); NOR = (x+y)' (2).
**Concept:** Algebraic identities of logic gates.
**Twist:** XOR is an inequality (odd) detector; XNOR is equality. NAND = NOT-AND; NOR = NOT-OR; both universal.

**Q24 (TSPSC-AEE-23):** Identify the correct statement(s) about flip-flops: I. D-FF is used as a delay device or a latch to store 1 bit. II. In a JK flip-flop, if J = K, the resulting flip-flop is a D flip-flop.
(a) Neither I nor II (b) Only II (c) Only I (d) Both I and II
**Ans: (c)** — Only I; J = K makes it a T flip-flop (toggle), not a D-FF.
**Concept:** D-FF = data/delay/storage; J = K → T-FF; J = K' → D-FF.
**Twist:** J = K' → D flip-flop (option-c result for Q28). JK = 11 unclocked → race-around; edge-triggered → toggle.

**Q25 (TSPSC-AEE-23):** Identify the correct statement(s) about edge-triggered flip-flops: I. Setup time is time for input data to settle before the triggering edge. II. Hold time is time data must remain stable after the triggering edge. III. Maximum clock frequency is the highest rate at which the FF can be reliably triggered.
(a) I and III only (b) I and II only (c) II and III only (d) I, II and III
**Ans: (d)** — All three statements are correct.
**Concept:** Setup time, hold time, and f_max are the timing parameters of an edge-triggered flip-flop.
**Twist:** Setup violation → metastability (unpredictable output); hold violation cannot be cured by lowering clock frequency. f_max ≈ 1/(t_clk→Q + t_logic + t_setup).

**Q26 (TSPSC-AEE-23):** Chronological order of the combinational design procedure: I. determine input/output variables; II. state the problem; III. assign letter symbols; IV. derive truth table; V. draw logic diagram; VI. obtain simplified Boolean function.
(a) IV, III, II, I, VI, V (b) III, IV, V, VI, II, I (c) V, I, II, VI, III, IV (d) II, I, III, IV, VI, V
**Ans: (d)** — Problem stated → variables → symbols → truth table → simplify → logic diagram.
**Concept:** Combinational circuit design flow.
**Twist:** Sequential design inserts state table and state assignment before the flip-flop excitation equations. Verifying the design (recheck) is an added final step.

**Q27 (TSPSC-AEE-23):** Find sum (S) and carry (C) of the logic diagram (figure: x', y' and x, y feed gates producing S and C):
(a) S = (xy+x'y')', C = xy (b) S = x'y+xy', C = xy' (c) S = x+y, C = xy' (d) S = x+y, C = xy
**Ans: (a)** — S = x⊕y = (xy+x'y')' (XNOR inverted = XOR), C = xy → half-adder.
**Concept:** Half-adder: S = x⊕y, C = xy; XOR = (XNOR)'.
**Twist:** If C were xy' → not a valid adder carry (trap). Half-subtractor: D = x⊕y, B = x'y. Adding a third input Cin makes it a full adder.

**Q28 (TSGenco-24):** In a JK flip-flop, if the input of K is the inverse of J, the resulting flip-flop is:
(a) SR flip-flop (b) JK flip-flop itself (c) D flip-flop (d) T flip-flop
**Ans: (c)** — K = J' forces only set/clear states → D flip-flop (D = J).
**Concept:** JK with K = J' reduces to D-FF; J = K reduces to T-FF.
**Twist:** J = K → T flip-flop (toggles, divide-by-2). J = K = 1 at clock edge → complement; D-FF characteristic Q(t+1) = D.

## Unit 3: A/D & D/A Converters (28 Qs)

**Q1 (EPDCL-10):** Number of comparators needed to build a 6-bit simultaneous A/D converter
(a) 63 (b) 7 (c) 6 (d) 64
**Ans: (a)** — Flash (simultaneous) ADC needs 2^n − 1 = 2^6 − 1 = 63 comparators.
**Concept:** flash ADC: 2^n − 1 comparators.
**Twist:** 4-bit flash → 15 comparators. 8-bit flash → 255 comparators.

**Q2 (EPDCL-10):** Number of comparators needed to build a 6-bit counter type A/D converter
(a) 64 (b) 32 (c) 6 (d) 1
**Ans: (d)** — A counter (ramp) type ADC uses a single comparator plus a counter/DAC.
**Concept:** counter ADC: only 1 comparator.
**Twist:** n-bit counter ADC → still just 1 comparator. The counter (not the comparator count) grows with n.

**Q3 (EPDCL-10):** Which of the following is the fastest A/D converter
(a) counter type (b) successive approximation (c) dual slope (d) integrating type
**Ans: (b)** — Speed order: flash > successive approx > counter > dual-slope/integrating; flash not listed, so SAR is fastest here.
**Concept:** ADC speed ranking (SAR = n clocks, faster than counter/dual-slope).
**Twist:** if Flash ADC added → Flash fastest. Slowest always → dual-slope/integrating type.

**Q4 (EPDCL-10):** Maximum output voltage of an 8-bit D/A converter with 10 V supply
(a) 9.961 V (b) 9.691 V (c) 10 V (d) 5 V
**Ans: (a)** — Step = 10/256, V0(max) = (10/256) × 255 = 9.961 V.
**Concept:** DAC: Vout(max) = Vref × (2^n − 1)/2^n.
**Twist:** 8-bit, 5 V ref → 5 × 255/256 = 4.98 V. 12-bit, 10 V → 10 × 4095/4096 ≈ 9.998 V.

**Q5 (Transco-AE-12):** Number of comparisons carried out in a 3-bit flash-type A/D converter
(a) 16 (b) 7 (c) 4 (d) 3
**Ans: (b)** — N-bit flash uses 2^N − 1 = 2^3 − 1 = 7 comparators/levels.
**Concept:** flash ADC: 2^N − 1 comparators.
**Twist:** 4-bit flash → 15. 10-bit flash → 1023.

**Q6 (AP Genco-12):** Percent resolution of an 8-bit D/A converter
(a) 0.392 (b) 1/256 (c) 1/255 (d) (a) and (b) both
**Ans: (a)** — %Resolution = 1/(2^n − 1) × 100 = 1/255 × 100 = 0.392%.
**Concept:** percent resolution = [1/(2^n − 1)] × 100 (step relative to full scale).
**Twist:** 10-bit → 1/1023 × 100 ≈ 0.0978%. 12-bit → 1/4095 × 100 ≈ 0.0244%.

**Q7 (HMWS-12):** Logic gate family which consumes maximum power and has minimum propagation delay
(a) MOS (b) TTL (c) ECL (d) CMOS
**Ans: (c)** — ECL has the lowest propagation delay and highest power dissipation.
**Concept:** speed/power trade-off of logic families (ECL fastest, CMOS lowest power).
**Twist:** propagation delay order → ECL < TTL < DTL < CMOS. Minimum power → CMOS.

**Q8 (EPDCL-14):** Which of the following is a D/A converter
(a) Flash converter (b) Weighted resistor (c) Successive approximation (d) Dual slope
**Ans: (b)** — Weighted resistor is a D/A converter (with R-2R ladder & inverter R-2R).
**Concept:** binary-weighted resistor DAC.
**Twist:** R-2R ladder is also a DAC. Flash / successive-approximation / dual-slope are all ADCs.

**Q9 (APSPDCL-14):** The ADC having highest conversion speed
(a) Dual-slope ADC (b) Successive approximation ADC (c) Flash ADC (d) Servo ADC
**Ans: (c)** — Flash type > successive approx > counter type > dual-slope/integrating.
**Concept:** flash ADC: highest conversion speed (one-shot compare, 2^n − 1 comparators).
**Twist:** slowest → dual-slope/integrating. Flash speed constant regardless of input amplitude.

**Q10 (APSPDCL-14):** The memory which needs refreshing
(a) ROM (b) EPROM (c) SRAM (d) DRAM
**Ans: (d)** — DRAM stores bits on capacitors and needs periodic refresh.
**Concept:** DRAM: 1 transistor + 1 capacitor per bit, requires refresh.
**Twist:** SRAM (6-transistor cell) needs no refresh. ROM/EPROM are non-volatile, no refresh.

**Q11 (HMWS-15):** Number of comparators required in a 3-bit comparator type ADC
(a) 8 (b) 3 (c) 7 (d) 2
**Ans: (c)** — Comparator (flash) type needs 2^n − 1 = 2^3 − 1 = 7 comparators.
**Concept:** comparator-type (flash) ADC: 2^n − 1 comparators.
**Twist:** 4-bit → 15 comparators. 6-bit → 63.

**Q12 (HMWS-15):** In a flash A/D converter, the priority encoder is used to
(a) Select the last input (b) Select the highest value input (c) Select the lowest value input (d) Select the first input
**Ans: (b)** — The priority encoder picks the highest-value active comparator output.
**Concept:** priority encoder in flash ADC selects highest active level.
**Twist:** with two comparators active, ordinary encoder gives invalid output; priority encoder resolves to highest.

**Q13 (HMWS-15):** A 4-bit R/2R ladder digital-to-analog converter uses
(a) Four resistor values (b) Three resistor values (c) Five resistor values (d) Two resistor values
**Ans: (d)** — R-2R ladder needs only two resistor values (R and 2R).
**Concept:** R-2R ladder DAC uses only 2 resistor values (vs weighted-resistor's n values).
**Twist:** binary-weighted DAC needs n different resistor values; R-2R ladder overcomes that spread.

**Q14 (HMWS-15):** Main advantage of successive-approximation ADC over counter-ramp ADC
(a) Shorter conversion time (b) Less complex circuitry (c) Longer conversion time (d) More complex circuitry
**Ans: (a)** — SAR conversion time is shorter (n clocks vs up to 2^n − 1).
**Concept:** successive approximation: conversion time = n clock cycles.
**Twist:** 8-bit SAR → 8 clocks; 8-bit counter (full scale) → 255 clocks.

**Q15 (HMWS-15):** Practical use of binary-weighted digital-to-analog converters is limited to
(a) Op-amp comparators (b) 4-bit D/A converters (c) 8-bit D/A converters (d) R-2R ladder D/A converters
**Ans: (b)** — Binary-weighted DACs are practical only up to about 4 bits (huge resistor spread).
**Concept:** binary-weighted DAC limit: 4 bits (resistor values span 2^n−1 ratio).
**Twist:** 10-bit weighted → needs 512:1 resistance ratio → impractical; use R-2R ladder instead.

**Q16 (TS Transco-15):** A digital voltmeter has 4½ digit display. The 1 V range can read up to
(a) 1000 (b) 1.111 (c) 1.999 (d) 1999
**Ans: (—)** — Key marked '*'; solution: 4½-digit display (full digit 0–9, half digit 0/1) reads up to 1.9999 V (nearest option (c) 1.999).
**Concept:** 4½-digit display count = 19999; half digit is 0 or 1.
**Twist:** 3½-digit on 1 V range → 1.999 V. 4½-digit on 10 V range → 19.999 V.

**Q17 (APSPDCL-14):** For the T-flip-flop, Q(t+1) is given by
(a) T·Q̄(t) + T̄·Q(t) (b) T·Q̄(t) + Q(t) (c) T·Q̄(t) (d) T·Q(t)
**Ans: (a)** — T-FF characteristic equation Q(t+1) = T ⊕ Q(t) = T·Q̄(t) + T̄·Q(t).
**Concept:** T flip-flop: Q(t+1) = T ⊕ Q(t) (toggles when T = 1).
**Twist:** J = K = T makes a JK-FF behave as a T-FF. 4-bit binary counter built from T-FFs.

**Q18 (AP Transco-17):** Number of comparators required in a 4-bit comparator type ADC
(a) 16 (b) 15 (c) 17 (d) 12
**Ans: (b)** — 2^n − 1 = 2^4 − 1 = 15 comparators.
**Concept:** comparator-type (flash) ADC: 2^n − 1 comparators.
**Twist:** 8-bit → 255 comparators. 3-bit → 7.

**Q19 (AP Transco-17):** In a 5-bit weighted-resistor D/A converter, LSB resistor is 40 kΩ; the MSB resistor will be
(a) 0.4 kΩ (b) 3 kΩ (c) 2.8 kΩ (d) 2.5 kΩ
**Ans: (d)** — R(MSB) = R(LSB)/2^(n−1) = 40 kΩ/16 = 2.5 kΩ.
**Concept:** binary-weighted resistor DAC: resistance halves per bit toward MSB (ratio 2^(n−1)).
**Twist:** 8-bit, LSB 40 kΩ → MSB = 40/128 = 0.3125 kΩ. LSB-to-MSB ratio = 2^(n−1).

**Q20 (TSSPDCL-18):** Number of comparators required to design a 4-bit flash ADC
(a) 2 (b) 4 (c) 7 (d) 15
**Ans: (d)** — Flash ADC needs 2^n − 1 = 2^4 − 1 = 15 comparators.
**Concept:** flash ADC: 2^n − 1 comparators (for 2^n quantization levels).
**Twist:** 8-bit flash → 255 comparators. 3-bit flash → 7.

**Q21 (APEPDCL-19):** Minimum number of comparators used in an N-bit successive-approximation ADC
(a) 1 (b) N − 1 (c) N + 1 (d) 2N
**Ans: (a)** — SAR ADC needs only 1 comparator.
**Concept:** successive approximation: 1 comparator, DAC + SAR register, n clock cycles.
**Twist:** flash ADC needs 2^N − 1 comparators. SAR trades comparators for conversion time (n clocks).

**Q22 (APEPDCL-19):** A 6-bit DAC produces V0 = 0.25 V for input code 000001. V0 for input code 111101 is
(a) 2.5 V (b) 25 V (c) 30.50 V (d) 15.25 V
**Ans: (d)** — 111101 = 61; 61 × 0.25 = 15.25 V.
**Concept:** DAC output V0 = (code value) × step size (LSB weight = Vref/2^n).
**Twist:** code 111111 (63) → 15.75 V. code 100000 (32) → 8 V.

**Q23 (—):** Small timing error in ADC additional to noise is called as
(a) Flicker (b) Aliasing (c) Jitter (d) Shot noise
**Ans: (—)** — Key marked '*'; the small timing error on clock edges is jitter (option (c)).
**Concept:** clock jitter: uncertainty in sampling instant degrades ADC SNR.
**Twist:** quantization error (noise) = ±LSB/2 vs jitter (timing). Aliasing = undersampling, not timing error.

**Q24 (APSPDCL-19):** Conversion time of a 12-bit counter type ADC with 1 MHz clock, full-scale input
(a) 4.095 s (b) 4.095 ms (c) 4.094 µs (d) 2.048 ms
**Ans: (b)** — (2^12 − 1) × 1 µs = 4095 µs = 4.095 ms.
**Concept:** counter-type ADC conversion time = (2^n − 1) × Tclk (worst case, full scale).
**Twist:** 8-bit at 1 MHz → 255 µs. 12-bit at 2 MHz → 2.0475 ms.

**Q25 (TSPSC-AEE-23):** SNR of an ideal 10-bit ADC
(a) 81.96 dB (b) 51.96 dB (c) 61.96 dB (d) 71.96 dB
**Ans: (c)** — SNR(dB) = 1.78 + 6.02n = 1.78 + 60.2 = 61.98 ≈ 61.96 dB.
**Concept:** ideal ADC SNR = 6.02n + 1.76 dB (quantization noise only).
**Twist:** 12-bit → 1.78 + 72.24 ≈ 74 dB. 8-bit → 1.78 + 48.16 ≈ 49.94 dB.

**Q26 (TSPSC-AEE-23):** SAR and single-slope 10-bit ADCs take Ta and Tb for 3 V input. Times for 6 V input are approximately
(a) 2Ta, 2Tb (b) Ta, Tb (c) Ta, 2Tb (d) 2Ta, Tb
**Ans: (c)** — SAR time ∝ n (independent of amplitude) → Ta; single-slope time ∝ input voltage → 2Tb.
**Concept:** successive approximation: fixed n-clock time; single-slope/integrating: time ∝ analog input.
**Twist:** input halved to 1.5 V → SAR still Ta, single-slope → Tb/2. Counter ADC also ∝ input (like single-slope).

**Q27 (TSSPDCL-AE-2023):** A 10-bit D/A converter has a step size of 20 mV. Full-scale output voltage
(a) 20.46 V (b) 10.23 V (c) 5.12 V (d) 10.24 V
**Ans: (a)** — V_FS = step × (2^n − 1) = 20 mV × 1023 = 20.46 V.
**Concept:** step size Δ = V_FS/(2^n − 1); full-scale = step × (2^n − 1).
**Twist:** 8-bit, 10 mV step → 2.55 V. Full-scale 5 V, 10-bit → step = 5/1023 ≈ 4.887 mV.

**Q28 (TSPSC-AEE-23):** Identify the flip-flop from characteristic table (X Y Q(t+1): 0 0→Q, 0 1→0, 1 0→1, 1 1→Q̄)
(a) JK flip flop (b) SR flip flop (c) T flip flop (d) D flip flop
**Ans: (a)** — Table matches JK-FF with J = X, K = Y (00→hold, 01→reset, 10→set, 11→toggle).
**Concept:** JK flip-flop characteristic table (J, K = X, Y).
**Twist:** J = K = 1 → toggles (acts as T-FF). D-FF table: Q(t+1) = D for all entries.

> Total: 85 questions annotated.

---

# 📋 FORMULA SUMMARY — Exam-Day Sheet (Digital)

## 1. Number Systems
- Binary→Hex: 4-bit groups · BCD: 4-bit per digit · Excess-3 = BCD+3 · Gray: adjacent codes differ by 1 bit
- **2's complement = invert + 1** · range of n-bit: −2^(n−1) to +2^(n−1)−1
- 1's complement = just invert · parity bit for error detection

## 2. Combinational & Sequential
- De Morgan: (A·B)' = A'+B' · NAND/NOR are universal gates
- Mux: 2^n inputs → n select lines · Decoder: n inputs → 2^n outputs
- **JK: J=K=1 → toggle** · SR: S=R=1 invalid · Master-slave avoids race condition
- n flip-flops → **mod 2^n** counter · frequency divides by 2^n · ripple vs synchronous

## 3. A/D & D/A Converters
- **Flash ADC: 2^n − 1 comparators** (fastest) · successive-approx: n clocks/conv · dual-slope: slow, most accurate
- **Resolution / step size = Vref / 2^n** · quantization error = ±LSB/2 = ±Vref/2^(n+1)
- R-2R ladder DAC: Vout = (code/2^n)·Vref
