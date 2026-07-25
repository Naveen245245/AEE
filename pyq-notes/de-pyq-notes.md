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
| :---: | :--- | :---: | :--- | :--- | :--- |
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
| :---: | :--- | :--- | :--- |
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
| :---: | :--- | :---: | :--- |
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

# 📝 EMBEDDED PYQs — Ohm Institute PDF

> Source: Study_Material__GTD_PYQs_2026_05_26_6_Digital_Circuits_P.pdf  
> Contains ~237 PYQs across 3 units. Selected representative Qs below.

---

## Topic 1: Number Systems & Boolean Algebra

**Q1 (EPDCL-10):** Binary 1101 in decimal:
(a) 11 &emsp; (b) 13 &emsp; (c) 15 &emsp; (d) 17  
**Answer: (b) 13** — 8+4+0+1 = 13

**Q2 (APGenco-12):** 2's complement of binary 1010:
(a) 0101 &emsp; (b) 0110 &emsp; (c) 1011 &emsp; (d) 1100  
**Solution:** Invert 1010 → 0101, Add 1 → 0110  
**Answer: (b) 0110**

**Q3 (APSPDCL-12):** Gray code of binary 1011:
**Solution:** G₃=1, G₂=1⊕0=1, G₁=0⊕1=1, G₀=1⊕1=0 → **1110**

**Q5 (APGenco-12):** Boolean expression for XOR:
(a) A'B + AB' &emsp; (b) AB + A'B' &emsp; (c) (A+B)(A'+B') &emsp; (d) A⊕B  
**Answer: (a)** — XOR = A'B + AB'

**Q7 (Transco-12):** De Morgan's law: (A+B)' = ?
(a) A' + B' &emsp; (b) A'B' &emsp; (c) (AB)' &emsp; (d) A+B  
**Answer: (b) A'B'**

**Q8 (HMWS-12):** Simplify: A + A'B = ?
(a) A &emsp; (b) B &emsp; (c) A+B &emsp; (d) A'B'  
**Solution:** A + A'B = A + B (absorption law)  
**Answer: (c)**

---

## Topic 2: Combinational & Sequential Circuits

**Q1 (EPDCL-10):** A multiplexer selects:
(a) One of many inputs &emsp; (b) One of many outputs  
(c) All inputs &emsp; (d) None  
**Answer: (a)** — MUX = many inputs, one output

**Q3 (APGenco-12):** In a full adder, sum S = ?
(a) A⊕B⊕C &emsp; (b) AB+BC+CA &emsp; (c) A+B+C &emsp; (d) (A⊕B)C  
**Answer: (a)** — Sum = A⊕B⊕Cin

**Q5 (TRANSCO-AE-12):** D-FF characteristic equation:
(a) Q'=D &emsp; (b) Q=D &emsp; (c) Q=T⊕Q &emsp; (d) Q=JQ'+K'Q  
**Answer: (b)** — D-FF: output follows D at clock edge

**Q7 (HMWS-12):** JK flip-flop. J=1, K=1, output toggles. If Q=0, after clock Q becomes:
(a) 0 &emsp; (b) 1 &emsp; (c) Toggle &emsp; (d) Invalid  
**Answer: (b) 1** — J=1, K=1 → toggle from 0 to 1

**Q9 (APSPDCL-14):** A 4-bit ripple counter with f_clk = 8 MHz. Output frequency?
(a) 2 MHz &emsp; (b) 4 MHz &emsp; (c) 0.5 MHz &emsp; (d) 1 MHz  
**Solution:** f_out = f_clk/2ⁿ = 8/16 = 0.5 MHz  
**Answer: (c) 0.5 MHz**

**Q11 (TSSPDCL-15):** A 4-bit Johnson counter has ___ states:
(a) 4 &emsp; (b) 8 &emsp; (c) 16 &emsp; (d) 2  
**Answer: (b) 8** — Johnson = 2n states = 2×4 = 8

---

## Topic 3: ADC & DAC

**Q1 (EPDCL-10):** An 8-bit Flash ADC requires ___ comparators:
(a) 8 &emsp; (b) 255 &emsp; (c) 256 &emsp; (d) 64  
**Answer: (b)** — 2ⁿ-1 = 255 comparators

**Q2 (APGenco-12):** An 8-bit SAR ADC takes ___ clock cycles per conversion:
(a) 8 &emsp; (b) 255 &emsp; (c) 256 &emsp; (d) 1  
**Answer: (a)** — SAR = n clocks per conversion

**Q4 (APSPDCL-12):** DAC output for V_ref=5V, input=1100₂ (4-bit):
**Solution:** D=12, Vo = V_ref×D/2ⁿ = 5×12/16 = 3.75V

**Q6 (Transco-12):** Resolution of 10-bit ADC as %:
(a) 0.1% &emsp; (b) 0.2% &emsp; (c) 0.5% &emsp; (d) 1%  
**Solution:** Resolution = 1/2ⁿ × 100 = 1/1024 × 100 = **0.0977% ≈ 0.1%**  
**Answer: (a)**

**Q7 (HMWS-12):** SNR of ideal 8-bit ADC:
(a) 49.9 dB &emsp; (b) 42.1 dB &emsp; (c) 56.2 dB &emsp; (d) 74 dB  
**Solution:** SNR = 1.78 + 6.02n = 1.78 + 48.16 = **49.94 dB**  
**Answer: (a)**

---

> **Total embedded PYQs: 18 (selected from ~237 DE questions)**

---

---