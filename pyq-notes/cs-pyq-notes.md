# Control Systems – Formula/Concept vs. Question Count Analysis

**Source:** Study Material – GTD PYQs 2026 (Control Systems)  
**Total Questions Analyzed:** 58+ (Pages 1-32)

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
| **1** | **Transfer Function & Block Diagram Reduction** <br> `C/R = G₁G₂ / (1 + G₁G₂H)` <br> Mason's Gain Formula: `T = (ΣP_kΔ_k) / Δ` | **~12** | Block diagram/SFG, Forward paths, Loops, Gains. | **Overall transfer function** , **Number of forward paths/loops** , **Mason's gain**. | Q6, Q11, Q12, Q13, Q21, Q23, Q25, Q28, Q32, Q44, Q45, Q48, Q53, Q54, Q57, Q58 |
| **2** | **Time Response (2nd Order System)** <br> `T(s) = ω_n² / (s² + 2ζω_n s + ω_n²)` <br> `%M_p = e^(-πζ/√(1-ζ²))` <br> `t_s = 4/(ζω_n)` <br> `t_r ≈ 1.8/ω_n` <br> `ω_d = ω_n√(1-ζ²)` | **~14** | Damping ratio (ζ), Natural frequency (ω_n), Transfer function. | **% Overshoot** , **Settling time** , **Rise time** , **Peak time** , **Damped frequency** , **System type** (over/under/critically damped). | Q4, Q10, Q15, Q18, Q19, Q20, Q21, Q22, Q24, Q36, Q38, Q41, Q49, Q52 |
| **3** | **Steady State Error** <br> `e_ss = lim(s→0) sE(s)` <br> `e_ss = A/(1+K_p)` (Step, Type 0) <br> `e_ss = A/K_v` (Ramp, Type 1) <br> `e_ss = A/K_a` (Parabolic, Type 2) <br> `K_p = lim(s→0) G(s)H(s)` <br> `K_v = lim(s→0) sG(s)H(s)` <br> `K_a = lim(s→0) s²G(s)H(s)` | **~12** | Input type (Step/Ramp/Parabolic), System Type, Open loop transfer function. | **Steady state error** , **Error constants (K_p, K_v, K_a)** , **System type** from error values. | Q5, Q8, Q9, Q11, Q12, Q13, Q16, Q27, Q29, Q30, Q32, Q33, Q34, Q43, Q44, Q46, Q51, Q55, Q58, Q59 |
| **4** | **Stability (Routh-Hurwitz)** <br> Routh array construction <br> `s³ + a₁s² + a₂s + a₃ = 0` <br> Condition: `a₁a₂ > a₀a₃` | **~10** | Characteristic equation, System parameters (K). | **Stability range** of K, **Number of roots in RHP** , **Marginal stability** condition, **Auxiliary equation**. | Q1, Q2, Q5, Q6, Q10, Q12, Q15, Q16, Q17, Q18, Q19, Q20, Q21, Q22, Q24, Q27, Q28, Q31, Q35, Q36, Q38, Q40 |
| **5** | **Root Locus** <br> `1 + G(s)H(s) = 0` <br> `Σ angles = (2q+1)180°` <br> `K = 1/|G(s)H(s)|` (Magnitude criterion) <br> Breakaway: `dK/ds = 0` <br> Asymptotes: `σ = (Σpoles - Σzeros)/(n-m)`, `Φ = (2q+1)180°/(n-m)` | **~8** | Open loop poles/zeros, Gain K. | **Breakaway point** , **Asymptote centroid/angle** , **Angle of departure** , **Value of K** at a point, **Stability range**. | Q5, Q8, Q9, Q14, Q23, Q24, Q25, Q26, Q29, Q31, Q33, Q34, Q36, Q39 |
| **6** | **Frequency Response (Bode, Nyquist)** <br> `GM = 1/|G(jω_pc)H(jω_pc)|` (in dB) <br> `PM = 180° + ∠G(jω_gc)H(jω_gc)` <br> `M_r = 1/(2ζ√(1-ζ²))` <br> `ω_r = ω_n√(1-2ζ²)` | **~12** | Transfer function, Gain/Phase crossover frequencies. | **Gain Margin** , **Phase Margin** , **Resonant peak** , **Resonant frequency** , **Stability from Nyquist plot**. | Q1, Q2, Q6, Q7, Q11, Q12, Q13, Q14, Q16, Q18, Q20, Q21, Q24, Q25, Q26, Q28, Q29, Q30, Q34, Q36, Q37, Q43, Q44, Q46, Q47, Q53, Q54, Q55 |
| **7** | **Compensators (Lead, Lag, PID)** <br> Lead: `G_c(s) = (s+z)/(s+p)` where `z > p` <br> Lag: `G_c(s) = (s+z)/(s+p)` where `z < p` <br> Max phase lead: `sinφ_m = (1-α)/(1+α)` <br> `ω_m = 1/(T√α)` | **~6** | Compensator transfer function, Pole/zero locations. | **Type of compensator** (Lead/Lag), **Maximum phase shift** , **Effect on transient/steady state**. | Q1, Q2, Q3, Q4, Q5, Q6, Q7, Q8, Q9, Q10, Q13, Q14, Q17, Q18, Q19, Q20, Q22, Q24 |
| **8** | **State Space Analysis** <br> `ẋ = Ax + Bu` <br> `y = Cx + Du` <br> `T(s) = C(sI - A)⁻¹B + D` <br> Controllability: `Q_c = [B AB A²B ...]` <br> Observability: `Q_o = [Cᵀ AᵀCᵀ (Aᵀ)²Cᵀ ...]` <br> `Φ(t) = L⁻¹{(sI - A)⁻¹}` | **~8** | A, B, C, D matrices, Initial conditions. | **State transition matrix** , **Controllability/Observability** , **Transfer function** from state model, **Stability** from eigenvalues. | Q1, Q2, Q3, Q5, Q6, Q7, Q8, Q10, Q11, Q12, Q13, Q14, Q16, Q17, Q18, Q19, Q20 |

---

## 🧭 The 5-Question Decision Flowchart

| Step | Question to Ask | If YES → | If NO → |
| :---: | :-------------------------------------------------------------- | :--- | :--- |
| **1** | **Is it about finding the overall transfer function?** | Use **Block Diagram Reduction** or **Mason's Gain Formula** | Go to Step 2 |
| **2** | **Is it about system response to an input?** | Use **Time Response** formulas (ζ, ω_n, %M_p, t_s) | Go to Step 3 |
| **3** | **Is it about steady state error?** | Use **Steady State Error** formulas (K_p, K_v, K_a) | Go to Step 4 |
| **4** | **Is it about stability?** | Use **Routh-Hurwitz** (if no K) or **Root Locus** (if K varies) | Go to Step 5 |
| **5** | **Is it about frequency response?** | Use **Bode/Nyquist** plots (GM, PM) | It's **State Space** or **Compensator** problem. |

---

## 🔑 How to Identify the Topic from the Question

| Keywords in Question | Topic | Go-to Formula |
| :--- | :--- | :--- |
| "Block diagram", "signal flow graph", "overall transfer function" | **Transfer Function** | Mason's Gain Formula |
| "Damping ratio", "natural frequency", "overshoot", "settling time" | **Time Response** | 2nd order system formulas |
| "Steady state error", "unit step/ramp/parabolic input" | **Steady State Error** | K_p, K_v, K_a |
| "Routh array", "characteristic equation", "stability range" | **Stability (Routh)** | Routh-Hurwitz criterion |
| "Root locus", "breakaway point", "asymptotes" | **Root Locus** | Angle/Magnitude criteria |
| "Bode plot", "Nyquist plot", "gain margin", "phase margin" | **Frequency Response** | GM, PM formulas |
| "Lead compensator", "lag compensator", "phase shift" | **Compensators** | G_c(s) = (s+z)/(s+p) |
| "State variable", "state transition matrix", "controllability" | **State Space** | ẋ = Ax + Bu |

---

## 📝 The Ultimate "What Happens When..." Cheat-Sheet

| Change Made | Effect |
| :--- | :--- |
| **↑ Gain (K)** | ↓ Damping ratio (ζ) → ↑ % Overshoot, ↓ Settling time (if ζ < 1) |
| **↑ Damping ratio (ζ)** | ↓ % Overshoot, ↑ Settling time |
| **↑ Natural frequency (ω_n)** | ↓ Rise time, ↓ Settling time, ↑ Bandwidth |
| **↑ System Type** | ↓ Steady state error for higher order inputs |
| **↑ Error constant (K_p, K_v, K_a)** | ↓ Steady state error |
| **Adding a pole** | ↓ Stability margin, ↑ Settling time |
| **Adding a zero** | ↑ Stability margin, ↓ Settling time |
| **Lead compensator** | ↑ Bandwidth, ↑ Phase margin (improves transient) |
| **Lag compensator** | ↓ Bandwidth, ↓ Steady state error (improves steady state) |
| **PID controller** | Improves both transient (D) and steady state (I) |
| **Negative feedback** | ↓ Gain, ↑ Bandwidth, ↑ Stability |
| **Positive feedback** | ↑ Gain, ↓ Stability (may become unstable) |

---

## 🎯 Top 10 Concepts to Score >90%

| Rank | Concept | Weightage | Key Formulas |
| :---: | :-------------------------------------------------------------- | :---: | :--- |
| **1** | **Time Response (2nd Order)** | ~15% | T(s), %M_p, t_s, t_r, ω_d |
| **2** | **Steady State Error** | ~13% | e_ss, K_p, K_v, K_a |
| **3** | **Transfer Function & Block Diagram** | ~13% | Mason's Gain Formula |
| **4** | **Frequency Response (Bode/Nyquist)** | ~13% | GM, PM, M_r, ω_r |
| **5** | **Stability (Routh-Hurwitz)** | ~11% | Routh array, stability range |
| **6** | **Root Locus** | ~9% | Breakaway, asymptotes, K |
| **7** | **State Space Analysis** | ~9% | ẋ = Ax + Bu, controllability/observability |
| **8** | **Compensators** | ~7% | Lead: z>p, Lag: z<p |
| **9** | **Laplace Transforms** | ~5% | Initial/Final value theorems |
| **10** | **Analogous Systems** | ~5% | Force-voltage/current analogy |

---

## 📌 Quick Reference Card (Exam Day)

| Concept | Formula | Quick Tip |
| :--- | :--- | :--- |
| **2nd Order T(s)** | `ω_n² / (s² + 2ζω_n s + ω_n²)` | ζ < 1: Underdamped |
| **% Overshoot** | `e^(-πζ/√(1-ζ²)) × 100` | ζ ↑ → %M_p ↓ |
| **Settling Time** | `t_s = 4/(ζω_n)` | 2% tolerance band |
| **Rise Time** | `t_r ≈ 1.8/ω_n` | For 10% to 90% |
| **Damped Frequency** | `ω_d = ω_n√(1-ζ²)` | Used in underdamped response |
| **K_p (Type 0)** | `lim(s→0) G(s)H(s)` | Step error = 1/(1+K_p) |
| **K_v (Type 1)** | `lim(s→0) sG(s)H(s)` | Ramp error = 1/K_v |
| **K_a (Type 2)** | `lim(s→0) s²G(s)H(s)` | Parabolic error = 1/K_a |
| **GM** | `1/|G(jω_pc)H(jω_pc)|` | In dB: 20 log(GM) |
| **PM** | `180° + ∠G(jω_gc)H(jω_gc)` | PM > 0 → Stable |
| **Resonant Peak** | `M_r = 1/(2ζ√(1-ζ²))` | Valid for ζ < 0.707 |
| **Resonant Frequency** | `ω_r = ω_n√(1-2ζ²)` | |
| **Routh Stability** | All 1st column elements > 0 | Sign change → Unstable |
| **Breakaway Point** | `dK/ds = 0` | Occurs on real axis |
| **Lead Compensator** | `z > p` (zero closer to origin) | Improves transient |
| **Lag Compensator** | `z < p` (pole closer to origin) | Improves steady state |
| **State Transition Matrix** | `Φ(t) = L⁻¹{(sI - A)⁻¹}` | e^(At) |

---

## ✅ Step-by-Step Problem Solving Approach

1. **Read the question** → Identify the topic using keywords.
2. **Follow the Decision Flowchart** → Decide which formula family to use.
3. **Write down given values** → Identify ζ, ω_n, K, etc.
4. **Pick the relevant formula** → Apply the formula.
5. **Solve and verify** → Check units and magnitude.

---

# 📝 FULL PYQ ANALYSIS — All 256 Control Systems Questions (Concept through PYQ)

> Source: Study_Material__GTD_PYQs_2026_05_26_2_Control_Systems_PD.pdf (OHM Institute)
> Every question: answer + options, the concept it teaches, and how the examiner twists it.

**Legend:** Q = question · Ans = correct option · Concept = new term/principle · Twist = examiner variation → new answer

## Unit 1: Basics & Mathematical Modelling (58 Qs)

58 questions. Answers matched from the OHM solutions (two-column PDF). Question numbering restarts per unit, so all IDs below are Unit-1 numbers.

**Q1 (EPDCL-10):** Negative feedback leads to:
(a) more stability (b) more gain (c) less gain (d) less bandwidth
**Ans: (a,c)** — Negative feedback reduces gain, increases bandwidth, and improves stability (key marks both a and c).
**Concept:** Negative feedback properties: `Af = G/(1+GH)` — denominator >1 lowers gain, stabilises.
**Twist:** Positive feedback `Af = G/(1−GH)` → gain *increases*, stability worsens → (b) instead of (c). Bandwidth variation: negative feedback *increases* bandwidth, so "less bandwidth" is false.

**Q2 (APGenco-12):** TF = 1/[(s+1)(s+2)]. The impulse response is:
(a) e^-2t − e^-t (b) e^-2t + e^-t (c) e^-t + e^-2t (d) e^-t − e^-2t
**Ans: (d)** — Impulse response = L⁻¹{G(s)} = partial fractions 1/(s+1) − 1/(s+2) → e^-t − e^-2t.
**Concept:** Impulse response = L⁻¹{TF}; PFD of real distinct poles.
**Twist:** Same TF but *unit step* input → ½ − e^-t + ½e^-2t. TF s/[(s+1)(s+2)] → impulse response −e^-t + 2e^-2t.

**Q3 (APGenco-12):** If r(t) has units °C and c(t) has units mm, units of block gain K are:
(a) °C (b) mm/°C (c) mm (d) °C/mm
**Ans: (b)** — K = c(t)/r(t) → mm/°C.
**Concept:** Gain units = output units / input units.
**Twist:** r in volts, c in mm → K = mm/volt. Swap: c in °C, r in mm → K = °C/mm (option d).

**Q4 (APGenco-12):** Two signal flow graphs are equivalent (first: X1→5→X2→4→X3, loop 0.5; second: X1→G→X3, loop H). Value of G and H:
(a) 9, 4.5 (b) 9, 3.5 (c) 20, 8 (d) 20, 2
**Ans: (d)** — First graph M = 4×5 = 20, loop L = 4×0.5 = 2 → X3/X1 = 20/(1−2) = −20; second = G/(1−H) → G = 20, H = 2.
**Concept:** SFG equivalence: overall gain M/(1−L) matched term-by-term.
**Twist:** Branch gains 5→2 (M = 8, L = 2) → X3/X1 = 8/(1−2) = −8 → G = 8, H = 2. If loop sign positive (1+L) → G = 20 with 1+H = −1 → H = −2.

**Q5 (APSPDCL-12):** Which system has the tendency to oscillate?
(a) closed loop system (b) open loop system (c) either (a) or (b) (d) both (a) and (b)
**Ans: (d)** — Both open- and closed-loop systems can oscillate (poles on the imaginary axis / poorly damped).
**Concept:** Oscillation tendency depends on pole location, not on the loop being open/closed.
**Twist:** Second-order closed loop with ζ→0 → sustained oscillation. Open loop with poles on jω axis also oscillates.

**Q6 (APSPDCL-12):** Overall gain of the block diagram (G1∥G2 feeding G3∥G4) is:
(a) G1G2G3G4 (b) G1+G2+G3+G4 (c) G1G2+G3G4 (d) (G1+G2)(G3+G4)
**Ans: (d)** — Parallel blocks add: (G1+G2) in cascade with (G3+G4).
**Concept:** Block diagram reduction: parallel → sum, cascade → product.
**Twist:** One summing sign to subtraction → (G1−G2)(G3+G4). Remove G2 → G1(G3+G4).

**Q7 (HMWS-12):** Speed TF ω(s)/V(s) = 100/(2+10s). 1 volt of input corresponds to output:
(a) 100 rad/sec (b) 1 rad/sec (c) 100/12 rad/sec (d) 50 rad/sec
**Ans: (d)** — V(s)=1/s; FVT: lim s→0 s·[100/(2+10s)]·(1/s) = 100/2 = 50 rad/s.
**Concept:** Final-value theorem on a step-excited TF.
**Twist:** 2-volt step → 100 rad/s. If denominator 2+10s→ (1+10s), gain 100 → steady state 100.

**Q8 (HMWS-12):** Servo motor drives a load (J, f) through gear ratio 10. Equivalent parameters referred to motor shaft:
(a) Jeq=0.01J and feq=0.01f (b) Jeq=10J and feq=10f (c) Jeq=0.1J and feq=0.1f (d) Jeq=100J and feq=100f
**Ans: (a)** — Jeq = (N1/N2)²J = (1/10)²J = 0.01J; feq = 0.01f.
**Concept:** Gear ratio referral: load quantities scale by (gear ratio)² when referred to motor shaft.
**Twist:** Gear ratio 5 → Jeq = J/25 = 0.04J. Referred to *load* side → Jeq = 100J (option d).

**Q9 (Transco-12):** Impulse response is e^-2t·u(t). To get response t·e^-2t·u(t), the input must be:
(a) 2e^-t·u(t) (b) ½e^-2t·u(t) (c) e^-2t·u(t) (d) e^-t·u(t)
**Ans: (c)** — G(s)=1/(s+2); C(s)=1/(s+2)² ⇒ R(s)=C(s)/G(s)=1/(s+2) ⇒ r(t)=e^-2t·u(t).
**Concept:** Invert the TF: R(s) = C(s)/G(s).
**Twist:** Desired output e^-2t with G(s)=1/(s+2) → R(s)=1 → input is an impulse δ(t). If G=1/(s+2)² and output 1/(s+2)³ → R=1/(s+2) → e^-2t.

**Q10 (Transco-12):** LTI system output c(t). If r(t) is passed through block with TF e^-s, the modified output is:
(a) c(t)/(1+e^t) (b) c(t)/(1+e^-t) (c) c(t−1)u(t−1) (d) c(t)u(t−1)
**Ans: (c)** — e^-s is a 1-second pure delay → output shifted: c(t−1)u(t−1).
**Concept:** Time-shifting property of Laplace transform (delay by T → multiply by e^-sT).
**Twist:** Delay e^-2s → c(t−2)u(t−2). Advance e^+s → c(t+1) (non-causal).

**Q11 (EPDCL-14):** Unity feedback, G(s) = K/[s(s+2)(s²+2s+2)]. Closed-loop TF for K = 1:
(a) 1/(s+1)³ (b) 1/(s+1)⁴ (c) 1/[(s+1)²(s²+2s+1)] (d) 1/(s²+2s+1)²
**Ans: (b,c,d)** — Characteristic eq 1+G=0 with K=1 gives (s+1)⁴ = 0; options b, c, d all reduce to 1/(s+1)⁴.
**Concept:** CLTF = G/(1+G); characteristic equation 1+G = 0.
**Twist:** K = 0 → poles at open-loop poles 0, −2, −1±j. K = 16 → (s+1)⁴ pattern breaks (root-locus shift).

**Q12 (EPDCL-14):** Number of forward paths in the SFG (branches a,d,f,h,e,b,c,g between y1–y5):
(a) 2 (b) 3 (c) 5 (d) 4
**Ans: (d)** — Paths: adfh, eh, adg, ecdg.
**Concept:** A forward path runs input→output touching no node twice; count all such paths.
**Twist:** Remove branch c → 3 paths (option b). Add a branch → 5 paths (option c).

**Q13 (EPDCL-14):** Overall TF of the system (U→+→+→G(s)→Y with a 1/G(s) feedback path):
(a) −1 (b) Indeterminate (c) 1 (d) Infinity
**Ans: (a)** — Forward path G(s), loops L1 = G·(1/G) = 1 and L2 = G(s); Δ = 1−L1−L2 = −G(s) ⇒ Y/U = G/(−G) = −1.
**Concept:** Mason's gain formula with a self-loop cancel: Δ = 1 − ΣL.
**Twist:** Feedback 1/(2G) → L1 = ½ ⇒ Δ = ½−G ⇒ TF = G/(½−G). Change feedback sign → Δ changes sign of result.

**Q14 (EPDCL-14):** For step input of magnitude 2, response y(t)=2+0.4e^-60t−2.4e^-10t. Closed-loop TF is:
(a) 1200/[(s+10)(s+60)] (b) 1200/[s(s+10)(s+60)] (c) 600/[(s+10)(s+60)] (d) 1200/[(s−10)(s+60)]
**Ans: (c)** — Y(s)=2/s+0.4/(s+60)−2.4/(s+10) = 1200/[s(s+60)(s+10)]; with R(s)=2/s, Y/R = 600/[(s+60)(s+10)].
**Concept:** Reconstruct TF from step response = (s·Y(s))/(step magnitude).
**Twist:** Unit step (magnitude 1) → same TF 600/[(s+10)(s+60)]. Poles +10 (option d) would give e^+10t growth — unstable.

**Q15 (EPDCL-14):** Force-current analogous electrical system for the two-mass mechanical system (K3, M2, K2, K1, M1, F(t)):
(a)–(d): electrical networks with C/L mapping variants
**Ans: (d)** — F↔i, M↔C, K↔1/L (force-current analogy); the network with CM dv/dt and (1/L)∫v dt terms matches.
**Concept:** Force-current analogy: F↔i, M↔C, B↔1/R, K↔1/L.
**Twist:** Force-*voltage* analogy → M↔L, K↔1/C, B↔R. Add friction B in the mechanical model → add a resistance term.

**Q16 (APSPDCL-14):** In force-current analogy, capacitance is analogous to:
(a) compliance of spring (b) mass (c) damping coefficient (d) spring constant
**Ans: (b)** — Force-current: mass M ↔ capacitance C.
**Concept:** F-I analogy table: F↔i, M↔C, B↔1/R, K↔1/L.
**Twist:** Force-voltage: mass ↔ L (option shifts). Damping B ↔ 1/R in F-I (not option c here).

**Q17 (HMWS-15):** Laplace transform of t·e^at:
(a) 1/(s²−a) (b) 1/(s²+a) (c) 1/(s−a)² (d) s/(s+a)²
**Ans: (c)** — L{t·e^at} = 1/(s−a)² (case n=1 of n!/(s−a)^(n+1)).
**Concept:** Frequency-domain differentiation / L{t^n·e^at} = n!/(s−a)^(n+1).
**Twist:** t²e^at → 2/(s−a)³. t·e^-at → 1/(s+a)² (a → −a).

**Q18 (TSSPDCL-15):** Laplace transform of the waveform shown (v ramps from 0 to 4 between t=1 and t=2):
(a) (4/s²)e^-s (b) (4/s)e^-s² (c) (1/s²)e^-s/4 (d) (1/s⁴)e^-s/2
**Ans: (a)** — Signal = 4(t−1)u(t−1) → V(s) = (4/s²)e^-s (delayed ramp).
**Concept:** Delayed ramp: a(t−T)u(t−T) → (a/s²)e^-sT.
**Twist:** Delay to t=2 → (4/s²)e^-2s. Undelayed ramp 4t → 4/s².

**Q19 (TSNPDCL-15):** Laplace transform of the pulse shown (f(t)=10 between t=1 and t=2):
(a) (10/s)e^-s (b) (10/s)(e^-s+e^-2s) (c) (10/s)(e^-s−e^-2s) (d) 10(e^-s−e^-2s)
**Ans: (c)** — f(t)=10[u(t−1)−u(t−2)] → F(s)=(10/s)(e^-s−e^-2s).
**Concept:** Pulse = difference of two delayed step functions; L{u(t−T)} = e^-sT/s.
**Twist:** Pulse from t=0 to 1 → (10/s)(1−e^-s). Height 5 → (5/s)(e^-s−e^-2s).

**Q20 (TSNPDCL-15):** Unity feedback, G(s) = 1/[s(s+2)]. Closed-loop poles are at:
(a) 0, −2 (b) 2.46, −4.46 (c) −1, −1 (d) −1, −2
**Ans: (c)** — 1+G=0 → s²+2s+1=(s+1)² → poles −1, −1.
**Concept:** Closed-loop poles = roots of characteristic equation 1+G(s)=0.
**Twist:** G=2/[s(s+2)] → poles −1±j (oscillatory). G=K/[s(s+2)], K<1 → two real distinct poles.

**Q21 (APGenco-17):** Signal flow graph transmittance from A to B (branch 3, loop −3):
(a) 3 (b) zero (c) 4/3 (d) 3/4
**Ans: (d)** — T = 3/(1−(−3)) = 3/4.
**Concept:** Mason's gain for a single forward path with one feedback loop: P/(1−L).
**Twist:** Loop +3 (positive feedback) → 3/(1−3) = −1.5. Branch 3→4 → 4/(1−(−3)) = 1.

**Q22 (APTransco-17):** Unity feedback, G(s) = K(s+1.1)(s+2.2)/[s(s+3.3)(s+4.4)]. For K=0 the closed-loop poles are:
(a) All real and distinct (b) One real and two complex conjugates (c) All real and repeated (d) Complex and non-repeated
**Ans: (a)** — K=0 → poles are the open-loop poles 0, −3.3, −4.4 (all real, distinct).
**Concept:** Closed-loop poles at K=0 coincide with open-loop poles (root-locus start points).
**Twist:** K→∞ → poles → open-loop zeros −1.1, −2.2 plus one at ∞. Moderate K → one real + complex pair (option b).

**Q23 (TSTransco-18):** Block diagram (R→+→(1/s)→+→(1/s)→C; feedback 2 around inner loop). C(s)/R(s):
(a) s/(s²+2s+1) (b) 1/(s²+2s+2) (c) s/(s²+2s+2) (d) 1/(s²+2s+1)
**Ans: (d)** — Inner loop 1/s/(1+2/s)=1/(s+2); outer cascade+unity feedback → 1/[s(s+2)+1] = 1/(s²+2s+1).
**Concept:** Block diagram reduction: inner loop G/(1+GH) then outer unity loop.
**Twist:** Inner feedback gain 2→3 → 1/(s²+3s+1). Remove inner feedback → 1/(s²+1).

**Q24 (TSTransco-18):** TF has a zero at −1, pole at −2, gain factor 2 (G=2(s+1)/(s+2)). Unit step response:
(a) e^-2t − 1 (b) 1 − e^-2t (c) 1 + e^-2t (d) e^-2t
**Ans: (c)** — C(s)=2(s+1)/[s(s+2)] = 1/s + 1/(s+2) → c(t)=1+e^-2t.
**Concept:** Partial fractions of C(s)=G(s)·(1/s).
**Twist:** Gain factor 1 → C(s)=(s+1)/[s(s+2)] → c(t)=½(1+e^-2t). Pole −3 → 1 + (2/3)e^-3t.

**Q25 (TSTransco-18):** Overall TF of the system (R→+→G1→+→G2→C; inner feedback H2, outer H1):
(a) G1G2/(1+G1H1+G1G2H1) (b) G1G2/(1+G2H2+G1G2H1) (c) G1G2/(1+G2H2+G1G2H2) (d) G1G2/(1−G2H2−G1G2H1)
**Ans: (b)** — Inner loop G2/(1+G2H2); outer feedback H1 → G1G2/(1+G2H2+G1G2H1).
**Concept:** Cascade of inner-loop and outer-loop reductions; positive inner feedback would give 1−G2H2.
**Twist:** H1=H2=1 → G1G2/(1+G2+G1G2). Remove H2 → G1G2/(1+G1G2H1).

**Q26 (TS Transco-18):** An electric motor with high torque/inertia ratio has:
(a) lower motor time constant and faster dynamic response (b) higher motor time constant and slow dynamic response (c) lower motor time constant and slow dynamic response (d) higher motor time constant and faster dynamic response
**Ans: (a)** — τm ∝ J/T; high T/J → small time constant → faster response.
**Concept:** Motor time constant τm ≈ (R·J)/(Kt·Kb) — inversely related to torque/inertia ratio.
**Twist:** Low torque/inertia ratio → larger time constant, slower response (option b).

**Q27 (APEPDCL-19):** Match List-I (Synchro, Amplidyne, Servo, RC Network) with List-II (Amplifier, Activator, Compensator, Transducer):
(a) (a-iv)(b-i)(c-ii)(d-iii) (b) (a-i)(b-ii)(c-iii)(d-iv) (c) (a-iv)(b-iii)(c-ii)(d-i) (d) (a-iii)(b-ii)(c-iv)(d-i)
**Ans: (a)** — Synchro=transducer, Amplidyne=amplifier, Servo=activator, RC network=compensator.
**Concept:** Control-system components: synchro senses, amplidyne amplifies, servo activates, RC compensates.
**Twist:** Swap Servo and RC → option (d). Add tachogenerator → also a transducer.

**Q28 (APEPDCL-19):** Transfer function of the system (R→+→G2→+→G1→C; H1 outer feedback, H2 inner):
(a) G2/(1+G2H1+G1G2) (b) G1G2/(1+G1H2+G1G2H1) (c) G1G2/(1+G2H1+G1G2H2) (d) G1H1/(1+G2H1+G1G2H2)
**Ans: (b)** — Inner loop G1/(1+G1H2); outer feedback H1 → G1G2/(1+G1H2+G1G2H1).
**Concept:** Two-loop reduction: inner loop first (H2), outer loop (H1) second.
**Twist:** Remove H1 → G1G2/(1+G1H2). Swap H1/H2 positions → denominator terms reorder.

**Q29 (APSPDCL-19):** Unit impulse response of TF 3s/(s+2):
(a) 3δ(t) − 6e^-2t (b) 3 − 6e^-2t (c) 3e^-2t (d) 3e^2t
**Ans: (a)** — 3s/(s+2) = 3 − 6/(s+2) → 3δ(t) − 6e^-2t (improper TF gives an impulse term).
**Concept:** L⁻¹ of improper TF → δ(t) terms plus exponentials.
**Twist:** TF 3/(s+2) → 3e^-2t (option c). TF s/(s+2) → δ(t) − 2e^-2t.

**Q30 (APSPDCL-19):** TF Eb(s)/ω(s) of the dc servo-motor (Kb constant):
(a) Kb/s² (b) Kb/s (c) Kb (d) Kb s
**Ans: (c)** — Eb = Kb·ω ⇒ Eb(s)/ω(s) = Kb.
**Concept:** Back-emf constant: Eb(s) = Kb·ω(s) — pure gain block.
**Twist:** ω(s)/Eb(s) = 1/Kb. With motor dynamics (J,B) → Eb/ω = Kb·[s(Js+B)]-type rational TF.

**Q31 (APSPDCL-19):** Feedback amplifier with closed-loop gain 100 and feedback factor 9. Open-loop gain:
(a) 100 (b) 900 (c) 1,000 (d) 10,000
**Ans: (—)** — G/(1+9G)=100 → G = −100/899 ≈ −0.11; not in options (OHM marks *).
**Concept:** Af = G/(1+GH); solve for G given Af and H.
**Twist:** Feedback factor β=0.09 → G = 100(1+0.09G) → negative again (flawed data). If H=0.09 with Af=100 → G ≈ 111 (≈option c).

**Q32 (APSPDCL-19):** C/R for the SFG shown (forward paths 10 and 5, loops −20 and −10):
(a) 15/31 (b) 15/21 (c) −10/29 (d) −15/29
**Ans: (a)** — M1=10, M2=5; Δ=1−(−20−10)=31 → C/R=(10+5)/31 = 15/31.
**Concept:** Mason's gain: T = ΣPkΔk/Δ; Δ = 1 − ΣL (touching loops here).
**Twist:** Remove path 5 → 10/31. If loops were non-touching, add their product term into Δ.

**Q33 (APSPDCL-19):** In force-current analogy, mass in a mechanical system is analogous to:
(a) conductance G (b) inverse of inductance 1/L (c) capacitance C (d) resistance R
**Ans: (c)** — Force-current: mass M ↔ capacitance C.
**Concept:** F-I analogy: M↔C, B↔1/R, K↔1/L, F↔i.
**Twist:** Spring stiffness K ↔ 1/L (option b). Damping B ↔ 1/R (option a is wrong: G is conductance).

**Q34 (APTransco-19):** Unity feedback system with impulse response c(t)=−te^-t+2e^-t. Open-loop TF:
(a) (2s+1)/s² (b) (s+1)/s² (c) (s+1)/(s+2)² (d) s/(s+1)²
**Ans: (a)** — T(s)=−1/(s+1)²+2/(s+1)=(2s+1)/(s+1)²; G=T/(1−T)=(2s+1)/s².
**Concept:** From closed-loop TF to open-loop: G = T/(1−T) (unity feedback).
**Twist:** c(t)=te^-t → T=1/(s+1)² → G=1/[s(s+2)]. Non-unity feedback H → G = T/[H(1−T)].

**Q35 (APTransco-19):** Open-loop converted to closed-loop negative unity feedback. Compared to open loop, the closed loop has:
(a) Overall gain increased (b) Bandwidth reduced (c) Effect of parameter variations reduced (d) Disturbance rejection capability reduced
**Ans: (c)** — Negative feedback reduces gain sensitivity to parameter variations, increases bandwidth, increases disturbance rejection.
**Concept:** Negative feedback: gain ↓ (G/(1+G)), bandwidth ↑, sensitivity & disturbance effect ↓.
**Twist:** Positive feedback → gain increases but stability degrades. Sensitivity S = 1/(1+GH) — feedback lowers it.

**Q36 (APTransco-19):** Block diagram (R→+→+→1/[s(s+1)]→C; feedback s). C(s)/R(s):
(a) 1/(s²+2s+2) (b) 1/(s²+s+2) (c) s/(s²+2s+1) (d) 1/(s²+2s+1)
**Ans: (d)** — Inner loop with feedback s → 1/[s(s+1)+s]=1/(s²+2s); outer unity loop → 1/(s²+2s+1).
**Concept:** Derivative feedback inside a loop: G/(1+GH).
**Twist:** Inner feedback s→2s → denominator s²+3s+1. Remove inner feedback → 1/(s²+s+1).

**Q37 (APPSC-20):** The nodes in a signal flow graph are represented by small ___:
(a) circles (b) arrows (c) squares (d) rectangles
**Ans: (a)** — Nodes are small circles; branches are line segments with arrows.
**Concept:** SFG terminology: nodes (circles) and directed branches (gains).
**Twist:** Arrows represent *branches*, not nodes (option b is a distractor). Self-loop = branch from a node to itself.

**Q38 (APPSC-20):** Magnitude of the unit impulse function at t=0:
(a) Infinite (b) Unity (c) Zero (d) One
**Ans: (a)** — δ(t)=∞ at t=0 (area under it = 1).
**Concept:** Unit impulse δ(t): infinite height, zero width, unit area.
**Twist:** Area of δ(t) = 1 → "unity" refers to area, not magnitude (option b trap). δ(at) scaling → area changes by 1/|a|.

**Q39 (APPSC-20):** In a signal flow graph, loops that do not possess any common node are known as ___ loops:
(a) Non-touching (b) feedback gain (c) touching (d) forward gain
**Ans: (a)** — Non-touching loops share no nodes; they appear as product terms in Δ.
**Concept:** Non-touching loops → their gain product enters Δ with + sign.
**Twist:** Touching loops share ≥1 node (option c) → product term excluded. Mason's Δ = 1 − ΣL + Σ(product of non-touching pairs).

**Q40 (APPSC-20):** Pole at s=−4. Representation in the Laplace domain:
(a) 1/(s+4) (b) 1/(s−4) (c) s/(s−5) (d) s/(s+5)
**Ans: (a)** — A pole at s=−4 gives factor (s+4) in the denominator.
**Concept:** Pole ↔ denominator root; s=−4 ⇔ (s+4)=0.
**Twist:** Pole at s=+4 (RHP) → 1/(s−4) (option b) — unstable. Two poles −4,−5 → 1/[(s+4)(s+5)].

**Q41 (APPSC-20):** The signal flow graph is appropriate for which of the following?
(a) Linear time invariant system (b) Dynamic system (c) Invertible system (d) Causal system
**Ans: (a)** — SFG models a set of linear algebraic equations → linear time-invariant systems.
**Concept:** SFG applicability: linear (time-invariant) systems only.
**Twist:** Non-linear systems cannot be drawn as SFG. Mason's formula requires linear graph algebra.

**Q42 (APPSC-20):** In spite of negative feedback, the control system still has instability because:
(a) components used have non-linearity (b) system has large negative phase angle at high frequencies (c) approximation in mathematical analysis (d) dynamic equations not being known exactly
**Ans: (a)** — Nonlinear components (saturation, backlash) cause instability even with negative feedback.
**Concept:** Negative feedback improves but cannot guarantee stability if nonlinearities exist.
**Twist:** Excess lag/negative phase at high frequency (option b) also causes instability via reduced phase margin. Conditionally stable systems.

**Q43 (APPSC-20):** If C/R = s/(s²+s+2), and the block diagram is R→+→(1/s)→+→G(s)→(s-block)→C, then G(s):
(a) s (b) 1 (c) 1/s (d) −s/(s³+s²−s−2)
**Ans: (a)** — C/R = G(s)/[1+G/s+G+sG] = s/(s²+s+2) ⇒ comparing gives G(s)=s.
**Concept:** Write the closed-loop TF from the block diagram and equate to the given TF.
**Twist:** If the s-block is removed → denominator changes → G(s)=1. If given C/R=1/(s²+s+2) → G(s)=1.

**Q44 (APPSC-20):** Overall TF of the block diagram (R→G1→Σ→G2→C; G3 feeds Σ; H1 feedback on G2):
(a) (G1G2+G2G3)/(1+G2H1) (b) (G1G2+G2G3)/(1+G3H1) (c) (G1G3+G2G3)/(1+G2G3H1) (d) G1G2+G2G3
**Ans: (a)** — Mason: M1=G1G2, M2=G3G2, Δ=1+G2H1 → C/R=(G1G2+G3G2)/(1+G2H1).
**Concept:** Mason's gain formula; parallel forward paths add in numerator.
**Twist:** Remove H1 → G2(G1+G3) (option d). Remove G3 → G1G2/(1+G2H1).

**Q45 (APPSC-20):** G(s)=Y(s)/U(s) for the system (two integrators, gains 3 and 12 in feedback):
(a) 1/[27(1+s/6)(1+s/9)] (b) 1/[18(1+s/12)(1+s/3)] (c) 1/[27(1+s/12)(1+s/9)] (d) 1/[27(1+s/9)(1+s/3)]
**Ans: (a)** — Forward 2/s²; loops −3/s, −12/s, −18/s² and product 36/s² → G(s)=2/(s²+15s+54)=1/[27(1+s/6)(1+s/9)].
**Concept:** Mason's gain with non-touching-loop product term in Δ.
**Twist:** Change feedback 3→6 → s²+... denominator changes. Drop the non-touching product → different Δ.

**Q46 (TSSPDCL-22):** The principles of homogeneity and superposition are applicable to:
(a) Linear time variant system (b) Non-linear time variant system (c) Linear time invariant system (d) Non-linear time invariant system
**Ans: (c)** — Homogeneity + superposition define linearity; exam answer is LTI.
**Concept:** Superposition & homogeneity ⇔ linearity.
**Twist:** They also hold for any *linear* (time-varying) system (option a), but not for nonlinear (options b, d).

**Q47 (TSSPDCL-22):** F(s)=(s+2)/[s(s+1)]. Initial and final values of f(t) are respectively:
(a) 1, 2 (b) 2, 1 (c) 1, 1 (d) 2, 2
**Ans: (a)** — IVT: lim s→∞ (s+2)/(s+1) = 1; FVT: lim s→0 (s+2)/(s+1) = 2.
**Concept:** Initial- and final-value theorems.
**Twist:** F(s)=(s+2)/(s+1) (no pole at origin) → FVT gives 2 but is invalid (poles must be in LHP; s=−1 OK here). If pole in RHP → FVT invalid.

**Q48 (TSNPDCL-22):** Transfer function of the system (R→Σ→G1→Σ→G2→C with two unit taps):
(a) G1G2+2G2+2 (b) G1G2+2G2−2 (c) G1G2−2G2−2 (d) G1G2−2G2+2
**Ans: (b)** — Forward paths G1G2, G2, G2, −1, −1; no loops → Δ=1 ⇒ C/R = G1G2+2G2−2. (Deleted from final key.)
**Concept:** Mason's gain with no loops: T = Σ forward path gains.
**Twist:** Remove the −1 paths → G1G2+2G2 (≈option d). Add a loop → Δ≠1, denominator appears.

**Q49 (TSPSC-AEE-23):** Laplace transform of f(t) is s/(s²−4). The function f(t) is:
(a) sin(2t) (b) cosh(2t) (c) sinh(2t) (d) cos(2t)
**Ans: (b)** — s/(s²−a²) ↔ cosh(at); with a=2 → cosh(2t).
**Concept:** L{cosh(at)} = s/(s²−a²); L{sinh(at)} = a/(s²−a²).
**Twist:** 2/(s²−4) → sinh(2t). s/(s²+4) → cos(2t) (option d).

**Q50 (TSPSC-AEE-23):** Laplace transform of y''+ay'+by=f(t), with y(0)=5, y'(0)=10:
(a) s²Y+10s+5+a(sY+10)+bY=F (b) s²Y−5s−10+a(sY−5)+bY=F (c) s²Y−10s−5+a(sY−10)+bY=F (d) s²Y+5s+10+a(sY+5)+bY=F
**Ans: (b)** — L{y''}=s²Y−5s−10; L{y'}=sY−5 → s²Y−5s−10+a(sY−5)+bY=F.
**Concept:** Laplace of derivatives: L{y'} = sY−y(0); L{y''} = s²Y−sy(0)−y'(0).
**Twist:** Zero initial conditions → s²Y+a sY+bY=F. y(0)=5, y'(0)=0 → s²Y−5s+a(sY−5)+bY=F.

**Q51 (TSPSC-AEE-23):** Dynamics x''+6x'+5x=10(1−e^-t). Steady-state value of x(t):
(a) 5/3 (b) 1 (c) 2 (d) 3/2
**Ans: (c)** — X(s)=10/[s(s+1)(s²+6s+5)]; FVT: lim s→0 sX(s)=10/[(1)(5)] = 2.
**Concept:** Final-value theorem on forced response.
**Twist:** Input 10(1−e^-2t) → different FVT. Remove the s factor in denominator → FVT invalid.

**Q52 (TSPSC-AEE-23):** Unity-feedback closed loop, output y(t)=e^-2t·u(t) for a unit impulse input. Open-loop TF:
(a) s/(s+1) (b) 1/(s+3) (c) 1/(s+2) (d) 1/(s+1)
**Ans: (d)** — T(s)=Y(s)/R(s)=1/(s+2); G=T/(1−T)=1/(s+1).
**Concept:** T from impulse response; invert CLTF→OLTF: G = T/(1−T).
**Twist:** y(t)=e^-t → T=1/(s+1) → G=1/s. Feedback H=2 → G=T/(1−2T)=1/s.

**Q53 (TSSPDCL-AE-2023):** Number of forward paths and combinations of two non-touching loops in the SFG (branches G1,G2,G3,G4,G5,G6,G7; loops −H1, −H2):
(a) 3 and 1 (b) 3 and 2 (c) 4 and 1 (d) 4 and 2
**Ans: (a)** — Forward paths: G1G2G3G4G5, G1G6G4G5, G1G2G7 (3); non-touching loop pair: −G4H1 & −G2G7H2 (1 pair).
**Concept:** Counting forward paths and non-touching loop pairs for Mason's Δ.
**Twist:** Remove G7 branch → 2 forward paths. Add a second feedback loop → 2 non-touching pairs (option b).

**Q54 (TSPSC-AEE-23):** Determine the transfer function of the figure (branches 2, 8, 4; feedback loop 5):
(a) 64/5 (b) 64/39 (c) 8/5 (d) 64/4
**Ans: (b)** — Mason: forward path 2×8×4=64, Δ1=1, loop gain yields Δ=39 → T = 64/39 (per key; some editions print Δ=41 → 64/41).
**Concept:** Mason's gain formula: T = ΣPkΔk/Δ.
**Twist:** Feedback sign + (positive) → Δ = 1−38 → 64/(−37) negative. Branch 2 removed → forward path 32.

**Q55 (TSPSC-AEE-23):** Identify correct statements about SFG. I. SFG is a graphical representation of relationships between variables of a set of linear algebraic equations. II. Net gain between input and output nodes (overall gain) is given by Mason's T = (1/Δ)ΣPkΔk:
(a) Only I (b) Neither I nor II (c) Only II (d) Both I and II
**Ans: (d)** — Both statements correctly describe SFG and Mason's gain formula.
**Concept:** SFG definition; Mason's gain formula T = ΣPkΔk/Δ.
**Twist:** Single forward path, no loops → T = P1/Δ1. Net gain between any two nodes is the overall transmittance.

**Q56 (TSPSC-AEE-23):** Identify correct statements. I. Loops are non-touching if they share no common node. II. A path traverses connected branches along branch arrows with no node traversed more than twice:
(a) Neither I nor II (b) Only II (c) Both I and II (d) Only I
**Ans: (c)** — Both per OHM key (note: the rigorous definition of a path is "no node traversed more than once" — check the examiner's wording).
**Concept:** Non-touching loops (no shared node); path = branch traversal along arrow direction.
**Twist:** If examiner says "no node traversed more than once" → statement II strict/true; if "twice" is used, treat as a definition trap.

**Q57 (TSPSC-AEE-23):** TF of the block diagram (R→+→G1→+→G2→C; H1 feedback on G1):
(a) G1G2/(1+G1H1) (b) G1G2/(1+H1) (c) G1/(1+H1)+G2 (d) G1G2/(1+G1G2H1)
**Ans: (a)** — Inner loop G1/(1+G1H1); cascade with G2 → G1G2/(1+G1H1).
**Concept:** Inner-loop reduction then cascade.
**Twist:** H1=1 → G1G2/(1+G1). Feedback taken from the output → G1G2/(1+G1G2H1) (option d).

**Q58 (TSPSC-AEE-23):** TF of the block diagram (two inner loops H1 on G1G2, H2 on G3G4, in cascade):
(a) G1G2G3G4/[1+G3G4H2+G1G2H1+G1G2G3G4H1H2] (b) 1/(1+G1G2H1)+1/(1+G3G4H2) (c) G1G2/(1+G1G2H1)+G3G4/(1+G3G4H2) (d) G1G2G3G4/(1+G1G2G3H1H2)
**Ans: (a)** — Mason: P1=G1G2G3G4, Δ1=1, Δ=1+(G1G2H1+G3G4H2)+G1G2H1·G3G4H2 (non-touching product included).
**Concept:** Mason's gain with two non-touching loops — their product term appears in Δ.
**Twist:** Loops touching (share node) → drop the H1H2 product term. Remove H2 → shorter denominator.

## Unit 2: Time Response (59 Qs)

Transient response (1st/2nd order), damping ζ, ωn, tr/tp/ts/%MP, steady-state error, error constants Kp/Kv/Ka.

---

**Q1 (EPDCL-10):** The steady-state part is the response that has a constant value without variations and remains constant as t → ___
(a) ∞ (b) 0 (c) tr (d) ts
**Ans: (a)** — Steady-state part = response as t→∞ after transients die out.
**Concept:** Steady-state vs transient part of response; ess = lim t→∞ of error.
**Twist:** Ramp input → steady-state part grows linearly (no constant value) → ess finite via Kv. Step → constant steady state.

**Q2 (EPDCL-10):** The damping factor of a system is unity, the system is
(a) over damped (b) under damped (c) critically damped (d) unstable
**Ans: (c)** — ζ=1 gives real, equal poles → critically damped step response.
**Concept:** ζ=1 critical, ζ>1 overdamped, ζ<1 underdamped, ζ=0 undamped.
**Twist:** ζ=0 → sustained oscillations (undamped); ζ<1 → damped sinusoid with overshoot.

**Q3 (EPDCL-10):** The type of a system depends on the number of
(a) Poles on s-plane (b) Poles at infinity (c) Poles at origin of s-plane (d) Zeros at infinity
**Ans: (c)** — Type = number of poles at s=0 in the open-loop TF.
**Concept:** Type is set by poles at origin of G(s); defines steady-state error behaviour.
**Twist:** Type-1 (one pole at origin) → Kv finite, ramp ess=1/Kv. Type-2 → ramp ess=0.

**Q4 (APGenco-12):** Damping ratio of the second-order system whose unit-step response (fig: peak 1.24, i.e. 24% overshoot) is
(a) 1 (b) 2 (c) 0.414 (d) zero
**Ans: (c)** — %MP=24% → ζ = −ln(0.24)/√(π²+ln²(0.24)) ≈ 0.414.
**Concept:** ζ from %overshoot: ζ = −ln(%MP/100)/√(π²+ln²(%MP/100)).
**Twist:** %MP=9.5% → ζ≈0.6; %MP=16.3% → ζ≈0.5.

**Q5 (APGenco-12):** Unity feedback, G(s)=K/[s(s+2)]. If ess for unit ramp is 0.05, the allowed K is
(a) 20 (b) 40 (c) 10 (d) 80
**Ans: (b)** — Kv = lim s·G = K/2; ess=1/Kv=0.05 → K=40.
**Concept:** Kv=lim sG(s); ess(ramp)=1/Kv.
**Twist:** Ramp magnitude 10 → ess = 10/Kv = 0.5 (same K). G=K/[s(s+10)] → Kv=K/10.

**Q6 (APGenco-12):** Initial value of f(t) with F(s)=(s+1)/[(s+2)(s+3)] is
(a) 0 (b) 1 (c) ∞ (d) 1/6
**Ans: (b)** — IVT: f(0⁺)=lim_{s→∞} sF(s) = lim (s²+s)/(s²+5s+6) = 1.
**Concept:** Initial value theorem f(0⁺)=lim sF(s) as s→∞.
**Twist:** F(s)=(s+2)/[(s+1)(s+3)] → f(0⁺)=1 (leading coefficient ratio). Higher-order numerator → ∞.

**Q7 (APSPDCL-12):** Unity feedback G(s)=K/[s(s+1)]. As K→∞ the damping ratio tends to
(a) 1/2 (b) 1 (c) 0 (d) ∞
**Ans: (c)** — CLTF ωn=√K, 2ζωn=1 → ζ=1/(2√K) → 0 as K→∞.
**Concept:** For G=K/[s(s+1)], ζ=1/(2√K); raising K lowers ζ (more overshoot).
**Twist:** Lowering K raises ζ (more damping); K=1 → ζ=0.5.

**Q8 (HMWS-12):** Unity feedback G(s)=9/[s(0.2s+1)], unit step input, ess is
(a) 0.1 (b) 1/9 (c) 0.2 (d) 0
**Ans: (d)** — Type-1 (pole at origin) → Kp=∞ → ess=1/(1+Kp)=0.
**Concept:** Step ess = 1/(1+Kp); type≥1 gives ess=0.
**Twist:** Make it type-0 (G=9/(s+1)) → Kp=9, ess=1/10.

**Q9 (HMWS-12):** Type-1, 2nd-order system; ωn increased by 25%, ess to unit ramp
(a) increased by 20% (b) equal to 2δ/ωn (c) decreased by 21% (d) decreased by 20%
**Ans: (d)** — ess∝1/ωn; ×1/1.25=0.8 → decrease 20%.
**Concept:** Type-1 ramp ess=1/Kv=2ζ/ωn; ess∝1/ωn.
**Twist:** ωn doubled → ess halved (50% decrease); ωn halved → ess doubled.

**Q10 (HMWS-12):** Peak overshoot 4.32%, ωn=5 rad/s. Dominant pole location is
(a) 3.5325+j5.535 (b) 2.535+j2.525 (c) 2.535+j3.535 (d) −3.535+j3.535
**Ans: (d)** — %MP=4.32% → ζ=0.707; pole = −ζωn±jωn√(1−ζ²) = −3.535±j3.535.
**Concept:** Pole location −ζωn ± jωd, ωd=ωn√(1−ζ²).
**Twist:** %MP=16.3% → ζ=0.5, ωn=5 → pole −2.5±j4.33.

**Q11 (HMWS-12):** ess for input 2u(t) to a type-0 system is
(a) 1/[2(1+kp)] (b) 2/(1+kp) (c) 1/kp (d) 0
**Ans: (b)** — For type-0, ess = A/(1+Kp) with A=2.
**Concept:** Step ess = A/(1+Kp), A=input magnitude.
**Twist:** Unit step (A=1) → ess=1/(1+Kp). Kp→∞ → ess→0.

**Q12 (Transco-12):** For a type-2 feedback system, ess for a ramp input is
(a) infinite (b) constant (c) zero (d) indeterminate
**Ans: (c)** — Type-2 → Kv=∞ → ess(ramp)=1/Kv=0.
**Concept:** Type-2: step→0, ramp→0, parabolic→1/Ka (finite).
**Twist:** Type-1 ramp → finite 1/Kv; type-0 ramp → ∞.

**Q13 (EPDCL-14):** Unity negative feedback, T(s)=(a_{n−1}s+a_n)/(sⁿ+a₁sⁿ⁻¹+…+a_{n−1}s+a_n). ess for unit ramp is
(a) a_n/a_{n−1} (b) infinity (c) zero (d) a_n/a_{n−2}
**Ans: (c)** — G(s)=T/(1−T) ends with s² in denominator → Kv=∞ → ess=0.
**Concept:** If closed-loop T has denominator constant a_n and numerator has no sⁿ/sⁿ⁻¹, open loop is type-2 → ramp ess=0.
**Twist:** If numerator had an extra s (type-1) → Kv finite → ess = 1/Kv.

**Q14 (APSPDCL-14):** The unit parabolic function may be regarded as the
(a) integral of the unit step (b) differential of the unit step (c) differential of the unit ramp (d) integral of the unit ramp
**Ans: (d)** — ∫(ramp) = ∫t dt = t²/2 = parabolic.
**Concept:** Impulse→∫→step→∫→ramp→∫→parabola (successive integration).
**Twist:** Ramp = integral of step; step = integral of impulse.

**Q15 (APSPDCL-14):** Step response of the block diagram (r → sum → K/[s(s+2)] → c, unity feedback) for K=1 is
(a) over-damped (b) critically-damped (c) under-damped (d) undamped
**Ans: (b)** — CLTF=1/(s²+2s+1)=(1/(s+1))²; ωn=1, ζ=1 → critical.
**Concept:** From CLTF compare to s²+2ζωn s+ωn².
**Twist:** K=4 → ζ=0.5 underdamped; K→large → ζ→0 undamped.

**Q16 (APSPDCL-14):** ess to unit ramp for unity feedback G(s)=20/[s(s+2)(s²+2s+2)] is
(a) 0 (b) 5 (c) 0.2 (d) ∞
**Ans: (c)** — Kv=lim s·G = 20/(2·2)=5; ess=1/Kv=0.2.
**Concept:** Kv = lim sG(s); ramp ess = 1/Kv.
**Twist:** Ramp magnitude 5 → ess=1.0; G=20/[s(s+2)(s²+2s+2)(s+10)] → Kv=20/40=0.5, ess=2.

**Q17 (ISRO-14):** Most likely reason for large overshoot in a control system
(a) High gain in a system (b) Presence of dead time delay (c) High positive corrective torque (d) High retarding torque
**Ans: (a)** — High K lowers ζ (ζ∝1/√K) → large overshoot.
**Concept:** Gain ↑ → ζ ↓ → %MP ↑; overdamping kills overshoot.
**Twist:** Dead time delay → added phase lag → reduced phase margin → instability/oscillation.

**Q18 (TSSPDCL-15):** Second-order type-1 system for continuous oscillations: time response ∝ (fn = natural freq)
(a) 1−cos(4πfn t) (b) 1−cos(2πfn t) (c) 1−sin(2πfn t) (d) 1−sin(4πfn t)
**Ans: (b)** — Sustained (continuous) oscillation → response 1−cos(ωn t), ωn=2πfn.
**Concept:** Undamped (ζ=0) oscillation → 1−cos ωn t; ωn=2πfn.
**Twist:** Underdamped ζ<1 → 1−e^{−ζωnt}·cos(ωd t) (decaying oscillations).

**Q19 (TSSPDCL-15):** Damped frequency of oscillations of the system (block diag: R→sum→20/((s+1)(s+5))→C, H=0.2 feedback) is
(a) 4 cycles/sec (b) (2/π) rad/sec (c) 4 rad/sec (d) (4/π) cycles/sec
**Ans: (c)** — CLTF=100/(s²+6s+25): ωn=5, ζ=0.6 → ωd=5√(1−0.36)=4 rad/s.
**Concept:** ωd = ωn√(1−ζ²).
**Twist:** Remove H (unity) → CLTF=20/(s²+6s+25), ωn=5, ζ=0.6 → ωd=4 rad/s same; gain up → ωn↑, ωd↑.

**Q20 (TSNPDCL-15):** 2nd-order zero-initial-conditions system, impulse response c(t)=10e^{−5t}sin10t. Unit step steady-state value is
(a) 0 (b) 1.0 (c) 0.5 (d) 0.8
**Ans: (d)** — T(s)=100/((s+5)²+10²)=100/(s²+10s+125); c(∞)=T(0)=100/125=0.8.
**Concept:** c(∞)=lim s·(1/s)·T(s)=T(0) (DC gain) via FVT.
**Twist:** Impulse amplitude 20e^{−5t}sin10t → T(0)=400/125=3.2.

**Q21 (HMWS-15):** Unity feedback G(s)=k/[s(1+sT)]. Factor to multiply k so ζ rises from 0.3 to 0.6
(a) 0.25 (b) 2.0 (c) 4.0 (d) 0.5
**Ans: (a)** — ζ∝1/√k; ζ²∝1/k → K₂=K₁(0.3/0.6)²=K₁/4 → factor 0.25.
**Concept:** For G=k/[s(1+sT)], ωn=√(k/T), ζ=1/(2√(kT)) → ζ∝1/√k.
**Twist:** Halve ζ (0.6→0.3) → multiply k by 4.

**Q22 (TSTransco-15):** Unity feedback G(s)=9/[s(s+1)]. Damping ratio ζ is
(a) 1.0 (b) 0.3 (c) 0.6 (d) 0.5
**Ans: (—)** — CLTF=9/(s²+s+9): ωn=3, ζ=1/(2ωn)=1/6≈0.167 — not among options (source key: *).
**Concept:** ζ=1/(2√K) for G=K/[s(s+1)] → 1/(2·3)=0.167.
**Twist:** G=1/[s(s+1)] → ζ=0.5 (option d); G=100/[s(s+1)] → ζ=0.05.

**Q23 (TSTransco-15):** CLTF C(s)/R(s)=1/(1+s). Steady-state value c(∞) for unit step is
(a) 1.0 (b) 0.5 (c) Zero (d) 2
**Ans: (a)** — c(∞)=lim s·(1/s)·1/(1+s)=1.
**Concept:** c(∞)=T(0) = DC gain of closed loop (FVT).
**Twist:** T(s)=2/(1+2s) → c(∞)=2; T(s)=K/(1+s) → c(∞)=K.

**Q24 (TSTransco-15):** A control system with unit damping factor gives
(a) Oscillatory response (b) Undamped response (c) Critically damped response (d) No response
**Ans: (c)** — ζ=1 → real equal poles → critical damping.
**Concept:** ζ=1 critical (no overshoot, fastest without oscillation).
**Twist:** ζ>1 overdamped (sluggish); ζ<1 underdamped (overshoot + oscillation).

**Q25 (TSTransco-15):** How can the steady-state error be reduced?
(a) By decreasing the type (b) By increasing system gain (c) By decreasing the static error constant (d) By increasing the input
**Ans: (b)** — Raising gain (or type) increases Kp/Kv/Ka → lowers ess.
**Concept:** ess ↓ as Kp/Kv/Ka ↑; type ↑ → lower-order inputs give ess=0.
**Twist:** Raise type 0→1 → step ess→0 (was 1/(1+Kp)).

**Q26 (APGenco-17):** Unit-step response c(t)=4+3t−4e^{−t}. Poles and zeros:
(a) pole at origin, pole at −1, zero at −3/7 (b) pole at origin, pole at −3/7, zero at −1 (c) zero at −4, poles at −3/7 and 4 (d) zero at 4, poles at −3/7 and 4
**Ans: (a)** — TF = d/dt[step] = (7s+3)/[s(s+1)]: poles 0,−1; zero −3/7.
**Concept:** Impulse response = d/dt(step response); TF = L{impulse}.
**Twist:** c(t)=1−e^{−2t} → TF=2/(s+2), pole at −2 only.

**Q27 (APGenco-17):** A type-2 system has zero steady-state error for
(a) Ramp input (b) Parabolic input (c) Both Ramp and parabolic inputs (d) Step input only
**Ans: (a)** — Type-2: Ka finite, Kp=Kv=∞ → ess=0 for step and ramp; among options, ramp.
**Concept:** Type-2 errors: step 0, ramp 0, parabolic 1/Ka (finite).
**Twist:** Parabolic to type-2 → ess=1/Ka finite; type-3 → parabolic also 0.

**Q28 (APTransco-17):** Unit impulse response R(t) and unit step response S(t) of the same network. R(t) is
(a) equal to dS(t)/dt (b) equals the integral of S(t) (c) the reciprocal of S(t) (d) has no relation with S(t)
**Ans: (a)** — Impulse = derivative of step response (L{s·(1/s)}=1).
**Concept:** Impulse response = d/dt(step response); step = ∫impulse.
**Twist:** Step response = integral of impulse response; ramp = double integral.

**Q29 (APTransco-17):** Unity feedback CLTF Y/R = ωn²/(s²+2ζωn s+ωn²). System Kv is
(a) ωn/(2ζ) (b) 1 (c) ∞ (d) 2ζ/ωn
**Ans: (a)** — G(s)=ωn²/[s(s+2ζωn)] → Kv=lim sG=ωn/(2ζ).
**Concept:** Kv = lim sG(s); type-1 open loop → Kv=ωn/(2ζ).
**Twist:** If CLTF is type-0 (no free s), Kv=0; raising ωn raises Kv (lower ess).

**Q30 (APTransco-17):** Zero ess for step, finite ess for ramp, ∞ ess for parabolic → system is
(a) Type-0 (b) Type-1 (c) Type-2 (d) Type-3
**Ans: (b)** — Type-1: step 0, ramp 1/Kv finite, parabolic 1/Ka=∞.
**Concept:** Type determined by error pattern (Kp, Kv, Ka).
**Twist:** Step 0, ramp 0, parabolic finite → type-2; all inputs finite → type-0.

**Q31 (TSSPDCL-18):** Unity feedback GA=9/[s(s+1)], GB=16/[s(s+2)]. Correct statement:
(a) System A has higher overshoot than B (b) A has lower overshoot than B (c) A has lower settling time than B (d) Both have equal settling times
**Ans: (a)** — ζA=1/6 < ζB=1/4 → A more overshoot; also ts∝1/(ζωn) → A higher ts.
**Concept:** Lower ζ → higher %MP; ts = 4/(ζωn).
**Twist:** Make K_A=16 → ζA=1/8, still less than ζB=1/4 → A more overshoot.

**Q32 (TSTransco-18):** Kp, Kv, Ka for system (block diag: R→sum→10/[s(s+1)(s+5)]→C, H=1/s) are
(a) 0,10,∞ (b) 0,∞,10 (c) ∞,∞,2 (d) 0,2,∞
**Ans: (c)** — GH=10/[s²(s+1)(s+5)]: Kp=∞, Kv=∞, Ka=lim s²GH=10/5=2.
**Concept:** Kp=lim G, Kv=lim sG, Ka=lim s²G (H included: G·H).
**Twist:** H=1 (unity) → GH=10/[s(s+1)(s+5)]: Kp=∞, Kv=10/5=2, Ka=0 → (∞,2,0).

**Q33 (TSTransco-18):** Type-2 feedback system, ess for ramp input is
(a) infinite (b) constant (c) zero (d) indeterminate
**Ans: (c)** — Type-2 → Kv=∞ → ess=0.
**Concept:** Type-2 ramp ess=0 (s² in G denominator).
**Twist:** Type-1 ramp → 1/Kv finite; type-2 parabolic → 1/Ka finite.

**Q34 (APEPDCL-19):** Unity feedback G(s)=40(s+2)/[s(s+1)(s+4)]. ess for ramp of magnitude 5 is
(a) 0.4 (b) 0.2 (c) 0.25 (d) 0.3
**Ans: (c)** — Kv=40·2/(1·4)=20; ess=5/Kv=0.25.
**Concept:** Kv=lim sG; ess=Amplitude/Kv.
**Twist:** Unit ramp → ess=0.05; G=20(s+2)/[s(s+1)(s+4)] → Kv=10, ess=0.5.

**Q35 (APEPDCL-19):** Type-2 feedback system, ess for ramp input is
(a) indeterminate (b) infinite (c) constant (d) zero
**Ans: (d)** — Kv=∞ → ess(ramp)=0.
**Concept:** Type-2 → ramp ess=0; parabolic ess=1/Ka finite.
**Twist:** Parabolic input to type-2 → 1/Ka; type-1 ramp → finite 1/Kv.

**Q36 (APEPDCL-19):** Unit-step response of unity feedback G(s)=1/[s(s+1)]. Maximum overshoot is
(a) 0.173 (b) 0.143 (c) 0.153 (d) 0.163
**Ans: (d)** — CLTF=1/(s²+s+1): ωn=1, ζ=0.5 → %MP=e^{−πζ/√(1−ζ²)}=0.163.
**Concept:** %MP = e^{−πζ/√(1−ζ²)}×100.
**Twist:** ζ=0.707 → %MP≈4.3%; ζ=0.3 → %MP≈37%.

**Q37 (APEPDCL-19):** If unit-step response of a network is (1−e^{αt}), its unit impulse response is
(a) (1−α)e^{−αt} (b) αe^{−αt} (c) αe^{−t/α} (d) (1/α)e^{−αt}
**Ans: (b)** — Impulse = d/dt(step) = d/dt(1−e^{−αt}) = αe^{−αt} (source key: *).
**Concept:** Impulse response = derivative of step response (IVT/FVT link).
**Twist:** Step=(1/α)(1−e^{−αt}) → impulse=e^{−αt}; step=1−e^{−t} → impulse=e^{−t}.

**Q38 (APEPDCL-19):** Natural frequency of unity feedback G(s)=10/[s(s+1)] is
(a) 2.3 rad/sec (b) 3.16 rad/sec (c) 0.5 rad/sec (d) 4.6 rad/sec
**Ans: (b)** — CLTF=10/(s²+s+10) → ωn=√10=3.16 rad/s.
**Concept:** ωn=√K for G=K/[s(s+1)].
**Twist:** G=100/[s(s+1)] → ωn=10; G=4/[s(s+1)] → ωn=2.

**Q39 (APEPDCL-19):** CLTF C/R=2(s−1)/[(s+2)(s+1)]. Unit step output is
(a) infinity (b) −3e^{−2t}+4e^{−t}−1 (c) −3e^{−2t}−4e^{−t}+1 (d) zero
**Ans: (b)** — Partial fractions of C(s)=2(s−1)/[s(s+2)(s+1)] → c(t)=−1−3e^{−2t}+4e^{−t}.
**Concept:** Output = L⁻¹{T(s)·(1/s)} via partial fractions; RHP zero → negative coefficient.
**Twist:** Same T with unit ramp → ramp output grows unbounded (pole at origin).

**Q40 (APEPDCL-19):** Unity feedback G(s)=K/[s(Js+B)] (J=inertia, B=viscous damping). Transient spec NOT affected by variation of K is
(a) damped frequency of oscillations (b) rise time (c) settling time (d) peak overshoot
**Ans: (c)** — CLTF=K/(s²J+Bs+K): ζωn=B/(2J) → ts=4/(ζωn)=8J/B independent of K.
**Concept:** ts=4/(ζωn) → for this plant ζωn=B/(2J), K cancels; ωd=√(K/J−B²/4J²) and Mp depend on K.
**Twist:** Increase B (more damping) → ts=8J/B decreases; increase J → ts rises.

**Q41 (APSPDCL-19):** Characteristic equation s²+6s+9=0. System is
(a) Undamped (b) Under damped (c) Critically damped (d) Over damped
**Ans: (c)** — (s+3)²: ωn=3, ζ=6/(2·3)=1 → critical.
**Concept:** Discriminant/ζ: b²−4ac=0 → repeated real poles → ζ=1.
**Twist:** s²+6s+10 → ωn=√10, ζ=0.95 (underdamped, small overshoot); s²+6s+5 → ζ=6/(2√5)=1.34 (overdamped).

**Q42 (APSPDCL-19):** Final value of f(t) with F(s)=2(s+1)/[s(s+3)(s+5)] is
(a) 0 (b) 2/13 (c) 2/75 (d) does not exist
**Ans: (c)** — FVT: f(∞)=lim sF(s)=2·1/(3·5)=2/75.
**Concept:** Final value theorem f(∞)=lim_{s→0} sF(s) (valid if poles in LHP).
**Twist:** F(s)=2(s+1)/[(s+3)(s+5)] (no pole at origin) → f(∞)=2/15 (DC gain).

**Q43 (APSPDCL-19):** Unit-step ess for unity feedback G(s)=120(s+2)/[(s+3)(s+4)] is
(a) ∞ (b) 1/21 (c) 0 (d) 1/20
**Ans: (b)** — Kp=120·2/(3·4)=20 → ess=1/(1+20)=1/21.
**Concept:** Type-0 → ess=1/(1+Kp).
**Twist:** Double gain → Kp=40, ess=1/41; G=120(s+2)/[s(s+3)(s+4)] (type-1) → ess=0.

**Q44 (APTransco-19):** Unity feedback G(s)=K/[s(s+1)]. ess for unit step is
(a) ∞ (b) zero (c) 1/K (d) K
**Ans: (b)** — Type-1 → Kp=∞ → ess=1/(1+Kp)=0.
**Concept:** Pole at origin → zero step error (Kp=∞).
**Twist:** G=K/(s+1) (type-0) → ess=1/(1+K); ramp input here → ess=1/Kv.

**Q45 (APPSC-20):** When 1/[s(s+1)] is the closed-loop transfer function, ess to unit step is
(a) 0.5 (b) one (c) T (d) +∞
**Ans: (a)** — Per key: E(s)=R(s)[1−T(s)], FVT gives 0.5.
**Concept:** ess = lim_{s→0} s·R(s)[1−T(s)] from closed-loop T directly.
**Twist:** T(s)=1/(s+1) → ess=1−T(0)=0; T(s)=4/(s²+0.4s+4) → ess=0.

**Q46 (TSSPDCL-22):** CLTF T(s)=4/(s²+0.4s+4). ess due to unit step is
(a) 4 (b) 1 (c) 0 (d) Infinity
**Ans: (c)** — e(∞)=lim s(1/s)[1−T(s)] = 1−T(0)=1−4/4=0.
**Concept:** Unit step ess = 1 − T(0) (closed-loop DC gain = 1).
**Twist:** T(s)=4/(s²+0.4s+2) → T(0)=2 → ess=−1 (non-unity DC gain).

**Q47 (TSSPDCL-22):** Z(s)=V(s)/I(s)=s/(s+3). At rest for t<0, v(t) for t≥0 if i(t)=3u(t) is
(a) e^{−t} (b) e^{−3t} (c) 3e^{−3t} (d) 4e^{−t}
**Ans: (c)** — V(s)=Z(s)·(3/s)=3/(s+3) → v(t)=3e^{−3t}u(t).
**Concept:** Output = impedance × input; inverse Laplace of V(s).
**Twist:** i(t)=u(t) (unit) → v(t)=e^{−3t}; Z(s)=1/(s+3) with i=3u(t) → v(t)=e^{−3t}.

**Q48 (TSSPDCL-22):** The ramp function is obtained from the unit impulse at t=0 by
(a) differentiating impulse once (b) differentiating impulse twice (c) integrating impulse once (d) integrating impulse twice
**Ans: (d)** — impulse→∫→step→∫→ramp (integrate twice).
**Concept:** Repeated integration of impulse generates step, ramp, parabola.
**Twist:** Step = single integral of impulse; parabolic = triple integral.

**Q49 (TSSPDCL-22):** G(s)=100/(s²+20s+100). This system is
(a) underdamped (b) overdamped (c) critically damped (d) unstable
**Ans: (c)** — ωn=10, 2ζωn=20 → ζ=1 → critical.
**Concept:** Compare denominator with s²+2ζωn s+ωn².
**Twist:** 100/(s²+20s+101) → ζ>1 overdamped; 100/(s²+10s+100) → ζ=0.5 underdamped.

**Q50 (TSSPDCL-22):** Pole-zero plot (zero −3; poles 0, −2±j1); steady-state (DC) gain 6. G(s) is
(a) 5(s+3)/(s²+4s+4) (b) 10(s+3)/[s(s²+4s+5)] (c) 2(s+3)/[s(s²+4s+5)] (d) 10(s+3)/[s(s+2)²]
**Ans: (b)** — G=K(s+3)/[s(s²+4s+5)]; DC gain=3K/5=6 → K=10.
**Concept:** Build G from poles/zeros; DC gain = lim_{s→0}G fixes K.
**Twist:** DC gain 3 → K=5 → option (c) 2(s+3)/… gives DC gain 6/5≠3 (K=5 → 5(s+3)/…).

**Q51 (TSNPDCL-22):** Kp, Kv, Ka for G(s)=13/[(s+13)(s+5)(2s+1)] are
(a) 0.2, 0, 0 respectively (b) 0.1, 0, 0 (c) 0.2, 0, ∞ (d) 0.1, 0, ∞
**Ans: (a)** — Kp=13/(13·5·1)=0.2; Kv=lim sG=0; Ka=0.
**Concept:** Kp=lim G, Kv=lim sG, Ka=lim s²G; type-0 → Kv=Ka=0.
**Twist:** Add pole at origin → Kv=Kp·? (finite), Ka=0; G=13(s+2)/[(s+13)(s+5)] → Kp=13·2/(13·5)=0.4.

**Q52 (TSNPDCL-22):** Damping coefficient α=4.8 and damped frequency ωd=6.4 of a 2nd-order system → ζ and ωn are
(a) 0.6 and 4.2 (b) 0.8 and 8 (c) 0.8 and 4.2 (d) 0.6 and 8
**Ans: (d)** — α=ζωn=4.8, ωd=ωn√(1−ζ²)=6.4 → ωn=√(4.8²+6.4²)=8, ζ=4.8/8=0.6.
**Concept:** ωn=√(α²+ωd²), ζ=α/ωn (poles −α±jωd).
**Twist:** α=4, ωd=3 → ωn=5, ζ=0.8; α=6, ωd=8 → ωn=10, ζ=0.6.

**Q53 (TSPSC-AEE-23):** Steady-state response to unit step for H(s)=(s+4)/[(s+1)(s+3)] is
(a) 4/3 (b) 3/4 (c) 2 (d) Infinite
**Ans: (a)** — c(∞)=lim s(1/s)H(s)=4/3 (FVT, all poles LHP).
**Concept:** c(∞)=H(0)= DC gain.
**Twist:** H(s)=(s+2)/[(s+1)(s+3)] → c(∞)=2/3; H(s)=(s+4)/[(s+1)(s+2)] → c(∞)=2.

**Q54 (TSPSC-AEE-23):** Correct pair(s) related to Laplace transform:
I. IVT: f(0⁺)=lim_{s→∞} sF(s). II. FVT: f(∞)=lim_{s→0} sF(s).
(a) Neither I nor II (b) Both I and II (c) Only II (d) Only I
**Ans: (b)** — Both statements are the correct theorems.
**Concept:** IVT uses s→∞; FVT uses s→0 (valid only for poles in LHP/at origin).
**Twist:** FVT fails if F(s) has poles on jω or RHP (sinusoids) → f(∞) undefined.

**Q55 (TSPSC-AEE-23):** Correct pairs of input vs ess for type-1 system:
I. Unit step: 0. II. Unit ramp: 1/Kv. III. Unit parabolic: 0.
(a) I and II only (b) II and III only (c) I, II, III (d) I and III only
**Ans: (a)** — Type-1: step 0, ramp 1/Kv finite, parabolic ∞ (not 0).
**Concept:** Type-1 errors: 0, 1/Kv, ∞ for step/ramp/parabola.
**Twist:** Type-2: parabolic finite 1/Ka; type-0: step 1/(1+Kp).

**Q56 (TSPSC-AEE-23):** Match time-response spec ↔ expression:
I Peak time; II Peak overshoot; III Rise time; IV Settling time, with 1: 4/(ζωn), 2: π/(ωn√(1−ζ²)), 3: e^{−πζ/√(1−ζ²)}, 4: [π−tan⁻¹(√(1−ζ²)/ζ)]/(ωn√(1−ζ²))
(a) I-2, II-3, III-4, IV-1 (b) I-4, II-2, III-3, IV-1 (c) I-1, II-2, III-3, IV-4 (d) I-3, II-2, III-4, IV-1
**Ans: (a)** — tp=π/ωd (2), %MP=exp(−πζ/√(1−ζ²)) (3), tr=(π−β)/ωd (4), ts=4/(ζωn) (1).
**Concept:** tp=π/ωd, %MP=e^{−πζ/√(1−ζ²)}, ts=4/(ζωn), tr=(π−β)/ωd.
**Twist:** 5% band → ts=3/(ζωn); 2% band → ts=4/(ζωn).

**Q57 (TSPSC-AEE-23):** Correct statement(s): I. ts = time to reach & stay within tolerance band. II. td = time to reach 50% of final value (first attempt). III. ess = error between actual and desired output as t→∞.
(a) I, II and III (b) II and III only (c) I and II only (d) I and III only
**Ans: (a)** — All three definitions are correct.
**Concept:** Definitions of ts (tolerance band), td (50% point), ess (t→∞ error).
**Twist:** tr (rise time) = 10%→90% (or 0→100%) of final value; tp = time to first peak.

**Q58 (TSPSC-AEE-23):** Ramp error applied to a type-2 system → ess for ramp is
(a) Zero (b) 1/Kv (c) Kv (d) Infinity
**Ans: (a)** — Type-2 → Kv=∞ → ess=1/∞=0.
**Concept:** Type-2 ramp ess=0 (Kv infinite); parabolic → 1/Ka finite.
**Twist:** Type-1 ramp → 1/Kv finite; type-0 ramp → ∞.

**Q59 (TSGenco-24):** ess for unit ramp of first-order system (block diag: R→sum→1/(Ts+1)→C, unity feedback) is
(a) T (b) 2T (c) 0 (d) ∞
**Ans: (a)** — Kv=lim s·[1/(Ts+1)]=1/T → ess=1/Kv=T.
**Concept:** Kv=lim sG(s); ramp ess=1/Kv.
**Twist:** G=2/(Ts+1) → Kv=2/T, ess=T/2; G=1/(s+1) (T=1) → ess=1.

---
**Count: 59 questions.**

## Unit 3: Stability & Routh (40 Qs)

Questions 1–40 (numbering restarts per unit). Answers matched from the OHM Unit-3 Answer Key and solutions by content.

**Q1 (EPDCL-10):** Which of the following system is stable?
(a) As²+Bs+C=0 (b) As⁴+Bs²+Cs+D=0 (c) −As²+Bs−C=0 (d) As²−Bs−C=0
**Ans: (a)** — For stability all coefficients must be present and have the same sign; only (a) satisfies this necessary condition.
**Concept:** Routh necessary condition: all coefficients of the characteristic equation present and same-sign.
**Twist:** missing term → immediately unstable, e.g. s³+2s²+5 (s-term absent) → unstable. Same sign but a zero coefficient → unstable.

**Q2 (EPDCL-10):** The first column of the Routh table contains the integers 2, 4, −5, 3. The system is
(a) Stable (b) Unstable (c) Marginally stable (d) Absolutely stable
**Ans: (b)** — A negative entry (2 sign changes) in the first column → unstable.
**Concept:** Number of Routh first-column sign changes = number of RHP roots.
**Twist:** first-column zero → ε-method. Row of zeros → auxiliary equation (marginal roots), not plain sign-change counting.

**Q3 (APGenco-12):** An example of a bounded signal is
(a) e⁻⁴ᵗ (b) e²ᵗ (c) t (d) eᵗ sin t
**Ans: (a)** — e⁻⁴ᵗ decays with t (stays bounded); the others grow without bound.
**Concept:** Bounded signal = finite for all t (LHP pole → bounded natural response).
**Twist:** e⁴ᵗ (RHP exponent) → unbounded. eᵗ sin t → unbounded despite oscillation.

**Q4 (APGenco-12):** A transfer function has a second-order denominator and constant gain in the numerator.
(a) two zeros at the origin (b) two finite zeros (c) two zeros at infinity (d) one zero at infinity
**Ans: (c)** — Two finite poles and no finite zeros → both zeros at infinity.
**Concept:** Zeros at infinity = n − m (poles − finite zeros); n=2, m=0 → two zeros at infinity.
**Twist:** add one finite zero → one zero at infinity. Branches of the root locus going to infinity = n − m.

**Q5 (APGenco-12):** Unity feedback with G(s)H(s)=K/[s(s+4)(s+16)]; the root locus intersects the jω axis at
(a) ±j2 (b) ±j4 (c) ±j8 (d) does not intersect the jω axis
**Ans: (c)** — CE s³+20s²+64s+K=0; at K=1280 the s¹ row is zero, auxiliary 20s²+1280=0 → s=±j8.
**Concept:** jω-axis crossing found when Routh s¹ row → 0; K=1280 and ω=√(1280/20)=√64=8.
**Twist:** poles at 0,−2,−6 → different K and ω. Below the critical K → no crossing (all roots LHP).

**Q6 (APSPDCL-12):** The feedback system with CE s⁴+2Ks³+s²+5s+5=0 is
(a) unstable for all values of K (b) stable for all K (c) stable for positive K (d) stable for zero K
**Ans: (a)** — Routh array shows a first-column sign change for every K (OHM flags an error in the question's derivation).
**Concept:** Routh first-column sign change for all K → unstable for every gain.
**Twist:** K=0 → CE s⁴+s²+5s+5 still has a sign change → unstable. Very large K → s¹ element stays negative → unstable.

**Q7 (APSPDCL-12):** For making an unstable system stable
(a) gain of the system should be decreased (b) gain should be increased (c) number of zeros should be increased (d) number of poles should be increased
**Ans: (c)** — Adding zeros bends root-locus branches to the left (toward stability).
**Concept:** Adding zeros → loci pulled left (stabilising); adding poles → loci pulled right (destabilising).
**Twist:** adding a pole at the origin drives a branch into the RHP → less stable. A near-origin zero pulls the locus further left → strongly stabilising.

**Q8 (APSPDCL-12):** The breakaway point of the root locus for G(s)H(s)=K(s+10)/[(s+2)(s+5)] lies
(a) between −10 and ∞ (b) at −∞ (c) between −2 and origin (d) between −2 and −5
**Ans: (d)** — Zero at −10, poles at −2 and −5; breakaway occurs between the two adjacent poles (−2 and −5).
**Concept:** Breakaway point lies between two adjacent real open-loop poles (or between a real zero and ∞), found via dK/ds=0.
**Twist:** compute dK/ds of the CE to get the exact breakaway value. Between zero (−10) and ∞ a break-in point tends toward −∞.

**Q9 (HMWS-12):** Electromechanical system CE s³+6Ks²+(K+2)s+3=0, K the forward gain. The condition for closed-loop stability is
(a) k=0.52 (b) k=2 (c) k=0 (d) k=−2.528
**Ans: (a, b)** — Routh: stable for K>0 and 6K²+12K−3>0 → K>0.225; both 0.52 and 2 satisfy.
**Concept:** Routh limit of K: s¹ row numerator 6K²+12K−3>0 → K>0.225 (roots −2.225, +0.225).
**Twist:** full range K>0.225. If asked "range of K" instead of a value → K>0.225 (all options above it are stable).

**Q10 (Transco-12):** The number of roots of 2s⁴+s³+3s²+5s+7=0 lying in the right half of the s-plane is
(a) Zero (b) One (c) Two (d) Three
**Ans: (c)** — Routh first column has two sign changes → two RHP roots.
**Concept:** Routh first-column sign changes = number of RHP (unstable) roots.
**Twist:** if the first column were all positive → zero RHP roots (stable). First-column zero → ε-method.

**Q11 (APTransco-12):** There are three zeros and two poles of G(s)H(s). There will be
(a) three root loci (b) two root loci (c) five root loci (d) one root locus
**Ans: (a)** — Number of loci = max(n, m) = 3 (three zeros, two poles).
**Concept:** Number of root-locus branches = number of open-loop poles; if zeros > poles, branches = number of zeros (max of n, m).
**Twist:** n>m (more poles) → loci = n, with n−m branches going to infinity. Here (m=3>n=2) one branch comes from infinity.

**Q12 (EPDCL-14):** Positive-feedback (unity) system G(s)=K/(s²+1)². The system stability according to Routh is
(a) Unstable K>0 (b) Stable for 0<K<1 (c) Stable for K>0 (d) Marginally stable for 0<K<1
**Ans: (d)** — Positive feedback: CE = 1−G = 0 → s⁴+2s²+1−K=0; for 0<K<1 all roots lie on the jω axis → marginally stable.
**Concept:** Marginal stability: imaginary-axis roots (auxiliary s⁴+2s²+1−K). Positive feedback uses 1−G(s)=0, not 1+G(s)=0.
**Twist:** K>1 → real positive root → unstable. Same G with negative feedback (1+G=0) → CE s⁴+2s²+1+K=0 has missing terms → unstable for all K.

**Q13 (ISRO-14):** If the non-repeated poles of a system lie on the imaginary axis, the system will be
(a) Stable (b) Conditionally stable (c) Marginally stable (d) Unstable
**Ans: (c)** — Simple (non-repeated) poles on the jω axis → system at the verge of instability = marginally stable.
**Concept:** Marginal stability: simple imaginary-axis roots (constant-amplitude oscillation).
**Twist:** repeated poles on the jω axis → t·sin term → unbounded → unstable (not marginal).

**Q14 (APSPDCL-14):** Unity feedback G(s)=K/[s(s+4)(s+5)]. The break-away point lies between
(a) −4 and −∞ (b) −4 and −5 (c) 0 and −5 (d) 0 and −4
**Ans: (d)** — RL plot (poles 0, −4, −5, no finite zeros): breakaway lies between 0 and −4.
**Concept:** Breakaway point on a real-axis segment between two adjacent poles (or pole and zero) where dK/ds=0.
**Twist:** dK/ds of s(s+4)(s+5) gives 3s²+18s+20=0 → confirm valid root. The segment −4 to −5 has no locus (even-count rule) → no breakaway there.

**Q15 (HMWS-15):** The number of roots of s⁴+4s³+s²+8s+1=0 on the right side of the s-plane is
(a) 3 (b) 2 (c) 0 (d) 1
**Ans: (b)** — Routh first column shows two sign changes → two RHP roots.
**Concept:** Routh first-column sign changes = RHP root count (any order equation).
**Twist:** change the constant or s³ coefficient → different sign-change count. First-column zero → ε-method.

**Q16 (HMWS-15):** First two rows of the Routh tabulation of a third-order system are s³: 1 1; s²: 2 2. This means there are
(a) Two roots at ±j2 and one in left half (b) Two roots at ±j2 and one in right half (c) Two roots at ±j and one in left half (d) Two roots at ±j and one in right half
**Ans: (c)** — s¹ row = 0 → auxiliary 2s²+2=0 → s=±j; remaining root is in the left half.
**Concept:** Row of zeros → auxiliary equation from the row above → imaginary-axis roots; remainder gives the LHP/RHP root.
**Twist:** auxiliary 2s²−2=0 → s=±1 (real) → one RHP root → unstable. Different s² row (e.g., 2 −2) changes the auxiliary roots.

**Q17 (HMWS-15):** CE s⁴+2s³+6s²+8s+8=0. Which is the symmetric root pair of the system?
(a) ±j3 (b) ±j√2 (c) ±j2 (d) ±j1
**Ans: (c)** — Routh row of zeros → auxiliary s²+4=0 → s=±j2.
**Concept:** Symmetric (imaginary-axis) root pair found from the auxiliary equation (a purely even polynomial).
**Twist:** change the constant so aux = s²+8 → ±j2√2. Change middle coefficients → aux = s²+1 → ±j1.

**Q18 (TSTransco-15):** According to the Routh–Hurwitz stability criterion, for a stable system the correct statement is
(a) Roots are in the right half of the s-plane (b) Roots are in the left half of the s-plane (c) Roots in RHP and on imaginary axis (d) Roots in LHP and on imaginary axis
**Ans: (b)** — Routh–Hurwitz stability requires all characteristic roots in the LHP.
**Concept:** Routh–Hurwitz: all roots must lie in the left half of the s-plane.
**Twist:** roots on the imaginary axis → marginally stable (allowed only if simple). Roots in RHP → unstable.

**Q19 (TSTransco-15):** First two rows of Routh's tabulation of a fourth-order system are s⁴: 1 10 5; s³: 2 20. The number of roots on the right half of the s-plane is
(a) 0 (b) 2 (c) 3 (d) 4
**Ans: (b)** — s² row first element = 0 → ε-method → two sign changes → 2 RHP roots.
**Concept:** First-column zero → replace 0 by ε (→0⁺) and continue; sign changes count RHP roots.
**Twist:** if the s² element were positive nonzero → 0 RHP roots (stable). Row of zeros instead → auxiliary equation.

**Q20 (TSSPDCL-15):** The third-order polynomial P(s)=a₁s³+a₂s²+a₃s+a₀ is stable if
(a) a₂a₀>a₁a₃ (b) a₂a₃<a₀a₁ (c) a₂a₀<a₁a₃ (d) a₂a₃>a₀a₁
**Ans: (d)** — Routh s¹ element (a₂a₃−a₁a₀)/a₂ > 0 → a₂a₃ > a₁a₀.
**Concept:** Routh–Hurwitz cubic condition: all coefficients positive and a₂a₃ > a₁a₀.
**Twist:** a₂a₃ = a₁a₀ → s¹ row zero → marginal. Negative a₂ or a₀ → immediately unstable.

**Q21 (TSNPDCL-15):** The range of K for which s³+Ks²+(K+2)s+3=0 is stable is
(a) K>0 (b) K>1 (c) −3<K<1 (d) 1<K<3
**Ans: (b)** — Routh: K>0 and K²+2K−3>0 → K>1 (and K>−3); combined K>1.
**Concept:** Routh limit of K: s¹ numerator K²+2K−3>0 → K>1.
**Twist:** marginal value K=1 (roots ±jω). For −3<K<1 → sign change → unstable.

**Q22 (APGenco-17):** Closed-loop transfer function 10/[s[(s+3)(s+4)+K]]. The system is stable for
(a) Any value of K (b) No value of K (c) K=10 (d) 3<K<12
**Ans: (b)** — CE s³+7s²+(12+K)s = 0 has no constant term → never stable for any K.
**Concept:** Necessary condition: constant term a₀ must be nonzero — a missing constant term → always unstable.
**Twist:** if a small constant term were present, Routh would give a K-range. The pole at s=0 already sits on the boundary → not stable.

**Q23 (APGenco-17):** Whether a given point in the s-plane lies on the root locus of a system can be determined by
(a) Magnitude criterion (b) Angle criterion (c) Both magnitude and angle criteria (d) Break-in and break-away criteria
**Ans: (b)** — The angle criterion alone is sufficient to test whether a point lies on the locus.
**Concept:** Angle criterion (∠G(s)H(s)=±180°) tests membership; magnitude criterion gives the K value at a locus point.
**Twist:** once a point is confirmed on the locus, the magnitude criterion gives K. K = |product of pole distances|/|product of zero distances|.

**Q24 (APTransco-17):** Unity-feedback G(s)=K(s+13)/[s(s+3)(s+7)]. The allowable maximum value of K for closed-loop stability is
(a) 50 (b) 60 (c) 70 (d) 80
**Ans: (c)** — CE s³+10s²+(K+21)s+13K=0; s¹ element (10(K+21)−13K)/10>0 → K<70.
**Concept:** Routh limit of K: s¹ row zero at K=70 (jω-axis crossing / max stable gain).
**Twist:** stability range 0<K<70. At K=70 the auxiliary equation gives s=±j√(13K/10)=±j√91 → oscillation frequency.

**Q25 (APTransco-17):** After drawing the root locus, the closed-loop poles for a specified gain K can be determined from
(a) Magnitude criterion alone (b) Angle criterion alone (c) Both magnitude and angle criteria (d) Angle of departure and arrival
**Ans: (a)** — For a point already on the locus, the magnitude criterion alone fixes K.
**Concept:** Magnitude criterion: K = |D(s)|/|N(s)| evaluated at the locus point.
**Twist:** to find K for a point ON the locus → magnitude criterion; to test if a point is ON the locus → angle criterion.

**Q26 (TSTransco-18):** Statements on root locus: 1. Break-away points always occur on the negative real axis. 2. A point on the real axis lies on the locus if the number of real poles+zeros to the right is even. 3. Branches going to infinity = poles − zeros. 4. K on the locus is found by the magnitude criterion. Which are NOT correct?
(a) 3 and 4 (b) 1 and 3 (c) 1 and 2 (d) 1, 3 and 4
**Ans: (c)** — Statement 1 is false (breakaway can occur off the negative real axis) and statement 2 is false (must be ODD, not even).
**Concept:** Real-axis locus rule: odd count to the right. Breakaway points need not be on the negative real axis.
**Twist:** statements 3 and 4 are correct (n−m branches to infinity; magnitude criterion gives K). Remember the "odd rule" for real-axis segments.

**Q27 (APEPDCL-19):** The number of roots of 2s⁴+s³+3s²+5s+7=0 that lie in the right half of the s-plane is
(a) three (b) zero (c) one (d) two
**Ans: (d)** — Routh first column has two sign changes → two RHP roots (same equation as Q10).
**Concept:** Routh first-column sign changes = RHP root count.
**Twist:** change the s² coefficient so the s²-row element is positive → zero RHP roots (stable). First-column zero → ε-method.

**Q28 (APSPDCL-19):** CE s³+13s²+30s+K=0. Which statement is NOT TRUE?
(a) System stable for 0<K<390 (b) System oscillates for K=390 (c) Frequency of oscillation is 30 rad/s (d) The auxiliary equation is 13s+390
**Ans: (d)** — At K=390 the auxiliary equation is 13s²+390=0 (not 13s+390); oscillation frequency is √30 rad/s.
**Concept:** Marginal stability / row of zeros → auxiliary equation from the s² row (13s²+390=0) gives s=±j√30.
**Twist:** correct oscillation frequency = √30 ≈ 5.48 rad/s (not 30). Slightly below K=390 → stable; above → unstable.

**Q29 (APSPDCL-19):** Unit-feedback forward path G(s)=K/[s(s+1)(s+9)]. If s=j3 lies on the root locus, the value of K is
(a) 13 (b) 30 (c) 27 (d) 90
**Ans: (d)** — K = |j3|·|j3+1|·|j3+9| = 3·√10·√90 = 90.
**Concept:** Magnitude criterion: K = product of pole distances / product of zero distances at the locus point.
**Twist:** point s=j2 → K = 2·√5·√85 ≈ 41.2. With a zero (s+2) → divide by its distance.

**Q30 (APSPDCL-19):** Which is the time-domain analysis method of control systems?
(a) Nyquist diagrams (b) Root-locus method (c) Bode-plot representation (d) Nichol's chart
**Ans: (b)** — Root-locus method is time-domain; Nyquist, Bode and Nichol's are frequency-domain.
**Concept:** Classification: root locus = s-plane/time-domain; Bode/Nyquist/Nichols = frequency-domain.
**Twist:** if asked "frequency-domain method" → any of Bode/Nyquist/Nichols.

**Q31 (APTransco-19):** Unity feedback G(s)=K(s+1)/[s(s−1)(s+6)]. The system is unstable for
(a) K>7.5 (b) K=7.5 (c) 0<K<7.5 (d) any value of K>0
**Ans: (c)** — Routh: stable for 5(K−6)−K>0 → K>7.5; hence unstable for 0<K<7.5.
**Concept:** K-range from Routh: s¹ element 5(K−6)−K>0 → K>7.5.
**Twist:** at K=7.5 → row of zeros → marginal. For K>7.5 the pole at s=+1 is pulled into the LHP → stable.

**Q32 (APTransco-19):** G(s)H(s)=16(s+1)/[s(s+2)(s+4)]. The centroid and angles of asymptotes are
(a) −2.5, 45°, −45° (b) −3, 60°, −60° (c) −2.5, 90°, 270° (d) −2.5, 30°, −30°
**Ans: (c)** — Centroid = [(−2−4)−(−1)]/(3−1) = −5/2 = −2.5; angles (2q+1)180°/(3−1) → 90°, 270°.
**Concept:** Centroid σ=(Σpoles−Σzeros)/(n−m); asymptote angles = (2q+1)180°/(n−m).
**Twist:** n−m=2 → angles always 90°, 270°. Change pole sum (e.g., poles 0,−3,−5) → centroid −3.5.

**Q33 (TSSPDCL-22):** The root locus of K/[s(s+2)(s+3)] has its breakaway point located at
(a) (−5.5, 0) (b) (−2.48, 0) (c) (−4, 0) (d) (−0.784, 0)
**Ans: (d)** — dK/ds: 3s²+10s+6=0 → s=−0.785 (valid); s=−2.55 invalid (no locus between −2 and −3).
**Concept:** Breakaway point via dK/ds=0 (K=−[s³+5s²+6s]); discard roots not on real-axis locus segments.
**Twist:** s=−2.55 is rejected because the segment −2 to −3 has no locus (even-count rule); only the leftmost valid breakaway −0.785 is kept.

**Q34 (TSNPDCL-22):** G(s)H(s)=K(s+5)/(s²+4s+20) has breakaway points s₁=−10 and s₂=0. Check the validity of the points.
(a) −10 (valid), 0 (invalid) (b) −10 (valid), 0 (valid) (c) −10 (invalid), 0 (valid) (d) −10 (invalid), 0 (invalid)
**Ans: (a)** — Poles at −2±j4, zero at −5; breakaway occurs between a pole and a zero or between a zero and ∞ → −10 valid, 0 invalid.
**Concept:** Breakaway/break-in points lie between two adjacent poles or between a real zero and ∞ (complex-conjugate pair splitting).
**Twist:** break-in between zero (−5) and −∞ validates −10; point 0 is beyond the zero with no locus segment → invalid.

**Q35 (TSPSC-AEE-23):** CE s⁴+3s³+5s²+6s+K+10=0. What should be the condition on K so that the system is stable?
(a) −10<K<−4 (b) K>10 (c) K>−4 (d) K>−10
**Ans: (a)** — Routh: K+10>0 → K>−10 and −(K+4)>0 → K<−4; combined −10<K<−4.
**Concept:** Routh K-limit for a 4th-order equation: constant term and s¹ element give a window for K.
**Twist:** K=−4 → marginal (s¹ row zero). K=−10 → constant term zero → root at origin → not stable. K>−4 → negative s¹ element → unstable.

**Q36 (TSSPDCL-AE-23):** The value of gain at the breakaway point of the root locus of GH=K/[s(s+1)] is
(a) 0.5 (b) 0.25 (c) 0.75 (d) Infinity
**Ans: (b)** — Breakaway at s=−0.5; K=|s|·|s+1| = 0.5·0.5 = 0.25.
**Concept:** Gain at a locus point by magnitude criterion: K = |D(s)|/|N(s)|; breakaway of s²+bs+K at s=−b/2.
**Twist:** for s(s+4) → breakaway at −2, K=4. For s(s+2) → breakaway −1, K=1.

**Q37 (TSSPDCL-AE-23):** Assertion (A): Zero-input stability is called asymptotic stability. Reason (R): In the absence of input, the output tends to a finite value irrespective of initial conditions.
(a) A true, R not true (b) Both A and R are true (c) Both are not true (d) A false, R true
**Ans: (b)** — Both are true (per OHM key).
**Concept:** Asymptotic stability = zero-input response decays to zero for any initial condition.
**Twist:** strictly the response tends to ZERO (not merely finite); "finite but non-zero" → marginal stability, not asymptotic.

**Q38 (TSPSC-AEE-23):** Unity feedback, forward G(s)=K/[s(s+2)(s+4)]. The range of K for stability is
(1) 0<K<520 (2) −48<K<0 (3) −52<K<0 (4) 0<K<48
**Ans: (d) → (4)** — CE s³+6s²+8s+K=0; (48−K)/6>0 and K>0 → 0<K<48.
**Concept:** Routh K-limit for a cubic: s¹ element >0 → K<48; constant term → K>0.
**Twist:** K=48 → marginal (aux eq 6s²+48=0 → ±j√8). K<0 → negative constant term → unstable. K>48 → unstable.

**Q39 (TSGenco-24):** G(s)=K/[s(s+4)(s²+4s+20)]. The angle of departure at the pole (−2+j4) is
(a) −90° (b) +90° (c) −74.7° (d) +74.7°
**Ans: (a)** — Angle of departure evaluated so ∠GH=180° at the complex pole; works out to −90°.
**Concept:** Angle of departure at a complex pole = 180° − (Σangles from other poles − Σangles from zeros).
**Twist:** adding a zero changes the departure angle (e.g., +74.7° when the branch is pulled right). Depends on exact pole/zero geometry.

**Q40 (TSGenco-24):** Unity feedback G(s)=30/[s(s+1)(s+T)], T a variable parameter. The closed-loop system will be stable for all values of
(a) T>0 (b) 0<T<3 (c) T>5 (printed "T>t" in PDF) (d) 3<T<5
**Ans: (c)** — CE s³+(1+T)s²+Ts+30=0; T>−1 and T²+T−30>0 → T>5 (option (c), misprinted "T>t").
**Concept:** Routh on a parameter T: s¹ numerator T²+T−30>0 → T>5 (with T>−1 from the s² row).
**Twist:** at T=5 → marginal (aux eq 6s²+30=0 → ±j√5). For 0<T<5 → sign change → unstable.

## Unit 4: Frequency Response (55 Qs)

**Q1 (EPDCL-10):** A stable system yields _____ gain margin.
(a) negative (b) positive (c) zero (d) infinite
**Ans: (b)** — For a stable system both gain margin and phase margin are positive.
**Concept:** Stable ⇔ GM > 0 dB and PM > 0.
**Twist:** Unstable system → GM negative; marginally stable → GM = 0 dB. → (a)/(c).

**Q2 (EPDCL-10):** Phase margin is defined as the difference of the angle corresponding to the gain crossover frequency and _____.
(a) 180° (b) –180° (c) 90° (d) –90°
**Ans: (b)** — PM = 180° + ∠G(jωgc); it is the additional phase lag needed to reach instability.
**Concept:** PM = 180° + ∠G(jωgc), measured at the gain crossover frequency.
**Twist:** PM measured with respect to +180° → wrong; PM at phase crossover = 0. → (a) trap.

**Q3 (EPDCL-10):** The unit circle of the Nyquist plot transforms into the 0 dB line of the amplitude plot of the Bode diagram _____.
(a) at 0 frequency (b) at low frequency (c) at high frequency (d) at any frequency
**Ans: (d)** — |G(jω)| = 1 (unit circle) is the 0 dB line regardless of frequency.
**Concept:** Unit circle |G| = 1 ⇔ 0 dB line (20log10 1 = 0).
**Twist:** |G| = 2 → +6 dB; |G| = 0.5 → −6 dB. → mapping is frequency-independent.

**Q4 (APGenco-12):** G(s) = 200(s+2)/(s(s²+10s+100)). At very high frequencies the Bode gain curve has a slope of _____.
(a) –6 dB/octave (b) –12 dB/octave (c) 6 dB/octave (d) 12 dB/octave
**Ans: (b)** — 3 poles (−60 dB/dec) + 1 zero (+20 dB/dec) = −40 dB/dec = −12 dB/octave.
**Concept:** HF slope = −20·(poles − zeros) dB/dec; octave = half a decade.
**Twist:** 2 poles + 1 zero → −20 dB/dec = −6 dB/octave → (a). 4 poles + 1 zero → −18 dB/octave.

**Q5 (APSPDCL-12):** A system has 12 poles and 2 zeros. Its high frequency asymptote in its magnitude plot will have a slope of _____.
(a) –60 dB/dec (b) –120 dB/dec (c) –200 dB/dec (d) –240 dB/dec
**Ans: (c)** — Slope = −20×(12 − 2) = −200 dB/dec.
**Concept:** HF asymptote slope = −20(poles − zeros) dB/dec.
**Twist:** 10 poles + 2 zeros → −160 dB/dec; 12 poles + 0 zeros → −240 dB/dec → (d).

**Q6 (APSPDCL-12):** The Nyquist plot of a transfer function is shown (crosses the negative real axis at −0.2). The gain margin is _____.
(a) 5 (b) 8 (c) 10 (d) 15
**Ans: (a)** — GM = 1/|a| = 1/0.2 = 5.
**Concept:** GM = 1/|G(jωpc)H(jωpc)|, where a = real-axis crossing magnitude.
**Twist:** Crossing at −0.4 → GM = 2.5; crossing at −0.5 → GM = 2 (marginal); crossing at −2 → GM = 0.5 (unstable).

**Q7 (APSPDCL-12):** If the gain of the open loop system is doubled, the gain margin _____.
(a) gets one fourth (b) gets halved (c) gets doubled (d) is not affected
**Ans: (b)** — GM = 1/|G(jωpc)|, so doubling gain halves GM.
**Concept:** GM ∝ 1/K (K in G(s)H(s)).
**Twist:** Gain tripled → GM = one-third; gain halved → GM doubled; gain ×4 → GM = one-fourth → (a).

**Q8 (HMWS-12):** The initial shape of the Bode plot gives an indication of _____.
(a) type of the system (b) nature of the system time response (c) system stability (d) order of the system
**Ans: (a)** — Initial slope of the Bode plot depends on the type (number of integrators) of the system.
**Concept:** Initial slope = −20N dB/dec, N = system type.
**Twist:** Initial slope −40 dB/dec → type-2 system; initial slope +20 dB/dec → zero at origin (differentiator-type).

**Q9 (HMWS-12):** In the G⁻¹(jω) plane, the constant M circle has the following centre and radius: (figure: s-plane vs GH-plane) _____.
(a) (x,y) = (−1,0); r = M (b) (x,y) = (1,0); r = M (c) (x,y) = (−1,0); r = 1/M (d) (x,y) = (1,0); r = 1/M
**Ans: (c)** — In the inverse (G⁻¹) plane the constant-M locus is a circle centred at (−1,0) with radius 1/M.
**Concept:** Constant-M circles in the G⁻¹ plane: centre (−1,0), radius 1/M.
**Twist:** In the direct G-plane, M-circles have centre −M²/(M²−1), radius M/(M²−1); M = 1 degenerates to the line x = −1/2.

**Q10 (HMWS-12):** Which of the following transfer functions is a non-minimum phase transfer function?
(a) (s+1)/((s+2)(s+3)(s+4)) (b) (s+1)(s+2)/(s(s+3)(s+4)) (c) 10(s+1)/(s²(s+3)) (d) (s−1)/((s+2)(s+3))
**Ans: (d)** — It has a zero in the right-half of the s-plane.
**Concept:** Non-minimum phase ⇔ RHP poles and/or zeros.
**Twist:** Pole at +1 (e.g., 1/(s−1)) is also non-minimum phase (and unstable); (s+1)/(s−1) is an all-pass non-minimum phase system.

**Q11 (Transco-12):** The closed-loop transfer function is C(s)/R(s) = 1/(1+s). For the input r(t) = sin t, the steady state value of c(t) is _____.
(a) (1/2)cos t (b) 1 (c) (1/2)sin t (d) (1/√2)sin(t − π/4)
**Ans: (d)** — At ω = 1: |G(j1)| = 1/√2, ∠G = −45°, so c(t) = (1/√2)sin(t − π/4).
**Concept:** Sinusoidal steady state: |G(jω)|·A·sin(ωt + ∠G(jω)).
**Twist:** Input cos t → (1/√2)cos(t − π/4); input sin 2t → (1/√5)sin(2t − 63.4°).

**Q12 (EPDCL-14):** G(s) = K/((s−1)(s²+4s+7)) with unity negative feedback; Nyquist plot in GH-plane. For K > 0 the system is stable for _____.
(a) 7 < K < 16 (b) 0 < K < 16 (c) 0 < K < 7 (d) K > 0
**Ans: (a)** — P = 1 (RHP pole at s = 1), need N = 1 CCW encirclement → K/16 < 1 and K/7 > 1 → 7 < K < 16.
**Concept:** Nyquist N = P − Z; stable ⇒ Z = 0 ⇒ N = P (CCW).
**Twist:** Pole moved to LHP (s+1) → P = 0 → stable for all K > 0 → (d). Non-unity K ranges shift the crossing.

**Q13 (EPDCL-14):** The magnitude Bode plot of a minimum-phase G(s)H(s) is shown (20 dB level, corners at ω = 1 and ω = 10). The transfer function is _____.
(a) 10(s+1)(s+10)/s (b) (s+1)(s+10)/s (c) s(s+10)/(s+1) (d) 10s(s+10)/(s+1)
**Ans: (b)** — Slopes −20→0→+20 ⇒ integrator + zeros at 1 and 10; K = 10 (20 dB at ω=1) → G(s) = (s+1)(s+10)/s.
**Concept:** Read corner frequencies (slope +20 = zero, −20 = pole) and K from a low-frequency point.
**Twist:** Slopes +20→0→−20 (flipped) ⇒ poles instead of zeros → s/((s+1)(s+10))-type; start slope +20 ⇒ zero at origin.

**Q14 (APSPDCL-14):** P: gain margin is determined from the gain at the gain crossover frequency. Q: phase margin is determined from the phase at the phase crossover frequency. Correct option:
(a) Only P is correct (b) Only Q is correct (c) Neither is correct (d) Both are correct
**Ans: (c)** — GM uses the gain at the PHASE crossover; PM uses the phase at the GAIN crossover — both statements are wrong.
**Concept:** GM ↔ phase crossover; PM ↔ gain crossover.
**Twist:** "GM from gain at phase crossover" → correct statement (P would be true). "PM from phase at gain crossover" → correct statement (Q would be true).

**Q15 (APSPDCL-14):** Principle of argument is the basis for _____.
(a) Compensation using Bode plots (b) Compensation using pole-placement (c) Nyquist criterion (d) R-H criterion
**Ans: (c)** — The Nyquist stability criterion is based on the principle of argument.
**Concept:** Principle of argument → Nyquist criterion (encirclement mapping).
**Twist:** R-H is algebraic (Routh array) not principle of argument; Bode design uses margins not encirclements.

**Q16 (APSPDCL-14):** The slope of the Bode gain plot of G(s) = Ks/((s+1)(s+10)) between ω = 1 and ω = 10 is _____.
(a) zero slope (b) –20 dB/decade (c) –40 dB/decade (d) +20 dB/decade
**Ans: (a)** — Zero at origin (+20), poles at 1 and 10 (−20 each): slope is +20 before ω=1, 0 between 1 and 10, −20 after 10.
**Concept:** Slope between corner frequencies = net of ±20 dB/dec contributions (type-N initial −20N).
**Twist:** G = K/((s+1)(s+10)) (no zero at origin) → −20 dB/dec between 1 and 10 → (b); G = Ks(s+10)/(s+1) → +40 dB/dec between 1 and 10.

**Q17 (HMWS-15):** A rough measure of bandwidth of a system is _____.
(a) Undamped natural frequency (b) Gain crossover frequency (c) Resonant frequency (d) Phase crossover frequency
**Ans: (b)** — The gain crossover frequency approximates the bandwidth.
**Concept:** Bandwidth ≈ ωgc; exact BW at |T| = 0.707 (−3 dB).
**Twist:** Exact 2nd-order bandwidth = ωn√(1−2ζ²+√(2−4ζ²+4ζ⁴)); higher bandwidth → faster response.

**Q18 (HMWS-15):** G(s)H(s) = 10(s+1)/(s(s−1)). The gain margin of the system is _____.
(a) +10 dB (b) –20 dB (c) –10 dB (d) +20 dB
**Ans: (b)** — ωpc = 1, |G(jωpc)H(jωpc)| = 10, GM = 20log(1/10) = −20 dB.
**Concept:** GM = 20log(1/|G(jωpc)H(jωpc)|) at the −180° crossing.
**Twist:** If pole at s=1 becomes s=−1 → phase never reaches −180° → GM = ∞. Numerator gain 1 instead of 10 → GM = 0 dB.

**Q19 (HMWS-15):** Unity feedback G(s) = (s+2)/((s+1)(s−1)); number of encirclements of (−1, j0) in Nyquist plot and closed-loop system is _____.
(a) No encirclements, unstable (b) One clockwise, unstable (c) Two counterclockwise, unstable (d) One counterclockwise, stable
**Ans: (d)** — P = 1, N = 1 CCW → Z = P − N = 0, so the closed-loop system is stable.
**Concept:** Z = P − N; CCW encirclements cancel RHP open-loop poles.
**Twist:** Same TF without RHP pole (s+2)/((s+1)(s+3)) → P = 0, no encirclement; G with 2 RHP poles → N = 2 CCW required.

**Q20 (HMWS-15):** The phase angle at ω = infinity for G(jω) = 90(1+j0.5ω)/(jω(1+jω)(1+j2ω)) is _____.
(a) –90° (b) –180° (c) 270° (d) 90°
**Ans: (b)** — High-ω phase = +90° (zero) − 90° (integrator) − 90° − 90° (two poles) = −180°.
**Concept:** Phase at ω→∞ = 90°(nz) − 90°(np), poles include integrators.
**Twist:** Remove the zero → phase −270°; add one more zero → −90°. At ω=0 phase = −90° (type-1).

**Q21 (TSGenco-15):** The gain margin for the system with G(s)H(s) = 2(1+s)/s² is _____.
(a) ∞ (b) 0 (c) 1 (d) –∞
**Ans: (a)** — Phase = −180° + tan⁻¹ω never reaches −180° (except ω→0), so no phase crossover → GM = ∞.
**Concept:** GM = ∞ when the polar plot never crosses the negative real axis.
**Twist:** G = 2/s² (no zero) → phase fixed at −180° → GM = 1 (0 dB), marginally stable. G = 2(1−s)/s² → phase approaches −270°, GM finite.

**Q22 (TSGenco-15):** A linear stable time-invariant system forced with x(t) = A sin ωt. Under steady state, the output y(t) will be _____.
(a) A sin(ωt+φ), φ = tan⁻¹|G(jω)| (b) |G(jω)| A sin[ωt + ∠G(jω)] (c) |G(jω)| A sin[2ωt + ∠G(jω)] (d) A|G(jω)| sin[ω + ∠G(jω)] (garbled)
**Ans: (b)** — Steady-state output = |G(jω)|·A·sin(ωt + ∠G(jω)).
**Concept:** Sinusoidal steady-state: amplitude scaled by |G(jω)|, phase shifted by ∠G(jω).
**Twist:** cos input → cos form with same magnitude/phase; changing ω changes both |G| and ∠G.

**Q23 (TSTransco-15):** Phase margin is the amount of angle to make the system _____.
(a) Oscillatory (b) Stable (c) Unstable (d) Exponential
**Ans: (c)** — PM is the additional phase lag that brings the system to the verge of instability.
**Concept:** PM = 180° + ∠G(jωgc).
**Twist:** PM > 0 → stable; PM = 0 → marginal (sustained oscillation); PM < 0 → unstable.

**Q24 (TSNPDCL-15):** Polar plot of a feedback control system, open-loop stable with K = 1, is shown (crosses real axis at 0.4, ω=∞ at origin, (−1,0) marked). If K is doubled the system will be _____.
(a) stable with less oscillations (b) unstable (c) stable with more oscillations (d) sustained oscillations
**Ans: (c)** — Doubling K shifts the crossing to −0.8 (still > −1) → stable but closer to (−1,0) → more oscillatory step response.
**Concept:** Increasing K reduces margins → more oscillation; crossing beyond −1 → unstable.
**Twist:** K tripled → crossing at −1.2 < −1 → unstable → (b); K such that crossing = −1 exactly → sustained oscillations → (d).

**Q25 (APGenco-17):** Which statement is INCORRECT in relation to NYQUIST and BODE analysis?
(a) Number of closed-loop poles in the RHP can be determined using Nyquist criterion (b) Bode analysis uses two plots, magnitude and phase (c) Nyquist analysis uses two plots, magnitude and phase (d) Relative stability can be assessed from both
**Ans: (c)** — Nyquist analysis uses a single complex (polar) plot, not two separate plots.
**Concept:** Nyquist = one plot of G(jω)H(jω) (magnitude + phase in one curve); Bode = two plots.
**Twist:** Nichols chart (M vs phase) also uses two axes like Bode; relative stability comes from both Nyquist and Bode.

**Q26 (TSSPDCL-18):** The gain margin of G(s) = 1/(s(s+1)(s+2)) is _____.
(a) 2.3 (b) 3.6 (c) 1.2 (d) 6
**Ans: (d)** — Standard form K/(s(sT1+1)(sT2+1)): ωpc = 1/√(T1T2) = √2, |G(jωpc)| = 1/6, GM = 6.
**Concept:** ωpc = 1/√(T1T2); GM = 1/|G(jωpc)|.
**Twist:** G = 1/(s(s+1)(s+3)) → ωpc = 1/√3, different GM; doubling K halves GM.

**Q27 (TSSPDCL-18):** Statements about time/frequency responses of a 2nd-order system: 1. Peak overshoot indicates damping; 2. Resonance peak depends on damping and natural frequency; 3. Resonance frequency depends only on damping; 4. Resonance peak and frequency are design performance measures. Correct statements:
(a) 1 and 4 (b) 1, 2 and 4 (c) 2 and 3 (d) 3 and 4
**Ans: (a)** — Mp = e^(−ζπ/√(1−ζ²)) depends on ζ (true); Mr = 1/(2ζ√(1−ζ²)) depends on ζ only (2 false); ωr = ωn√(1−2ζ²) depends on ζ and ωn (3 false); 4 true.
**Concept:** Mr depends only on ζ; ωr depends on ζ and ωn.
**Twist:** Mr ↔ ζ (Mr up ⇔ ζ down); ωr independent of ωn? No — ωr grows with ωn; ζ > 0.707 → no resonance peak.

**Q28 (TSTransco-18):** The asymptotic Bode plot of G(s) is shown (4 dB, corner frequencies 0.1–100, slopes −20→0→−20→−40). The transfer function G(s) is _____.
(a) 10⁴(s+2)/(s(s+10)(s+100)) (b) 1580(0.5s+1)/(s(0.1s+1)(0.01s+1)) (c) 1580(s+2)/(s(s+10)(s+100)) (d) 1000s(s+2)/((s+10)(s+100))
**Ans: (c)** — Zero at 2, poles at 0, 10, 100; 20log K − 20log 2 = 4 → K = 3.16 → G(s) = 1580(s+2)/(s(s+10)(s+100)).
**Concept:** Reconstruct TF from corner frequencies and one gain point.
**Twist:** 0 dB initial level (K = 2) → numerator 2; initial +20 slope → zero at origin (option (d) style).

**Q29 (TSTransco-18):** Unity negative feedback with G(s) = 4/(s(s+1)). The damped natural frequency ωd (rad/s) is _____.
(a) 2√(1−(0.5)²) (b) 4√(1−(0.25)²) (c) 2√(1+(0.25)²) (d) 2√(1−(0.25)²)
**Ans: (d)** — CLTF = 4/(s²+s+4): ωn = 2, ζ = 1/(2·2) = 0.25, ωd = 2√(1−0.25²).
**Concept:** ωd = ωn√(1−ζ²); ωn = √K, ζ = 1/(2√K).
**Twist:** G = 16/(s(s+4)) → ωn = 4, ζ = 0.5 → ωd = 4√(0.75) → (b) trap; G = 4/(s(s+2)) → ωn=2, ζ=0.5.

**Q30 (TSTransco-18):** The frequency response of G(s) = 1/(s(s+1)(s+2)) plotted in the complex G(jω) plane (0 < ω < ∞) is (figure, options a–d) _____.
(a) polar plot tangent to −3/4 (b) plot crossing at −3/4 with ω=0 (c) plot with ω=0 at origin (d) plot tangent to −1/6
**Ans: (a)** — For K/(s(sT1+1)(sT2+1)) the polar plot is tangent to −K(T1+T2) = −(1/2)(1+1/2) = −3/4.
**Concept:** Type-1 third-order polar plot tangent point = −K(T1+T2).
**Twist:** K = 2, T1 = 1, T2 = 2 → tangent at −2(1+2) = −6; type-0 G = K/((s+1)(s+2)) starts on the real axis at K/2.

**Q31 (TSTransco-18):** The constant M loci plot is symmetrical with respect to _____.
(a) Real axis and imaginary axis (b) M = 1 straight line and the real axis (c) M = 1 straight line and the imaginary axis (d) M = 1 straight line
**Ans: (b)** — Constant-M circles are symmetric about the real axis and about the M = 1 straight line.
**Concept:** M-circles: symmetric about real axis and M = 1 line (x = −1/2).
**Twist:** For M = 1 the circle degenerates to the straight line x = −1/2; N-circles pass through the origin.

**Q32 (TSTransco-18):** For a second-order linear system, the correct relationship between bandwidth and natural frequency is _____.
(a) Bandwidth equals natural frequency (b) No relationship (c) Inversely proportional (d) Directly proportional
**Ans: (d)** — ωb = ωn√(1−2ζ² + √(2−4ζ²+4ζ⁴)) — bandwidth ∝ ωn.
**Concept:** Bandwidth = ωn·f(ζ); at ζ = 0.707, ωb = ωn.
**Twist:** Higher bandwidth → faster response (smaller rise time); for ζ < 0.707 BW increases with ζ up to a point.

**Q33 (APEPDCL-19):** Unity feedback G(s) = 1/((s−1)(s+2)(s+3)). How many times does the Nyquist plot of G(s) encircle the origin?
(a) Thrice (b) Once (c) Never (d) Twice
**Ans: (b)** — By the argument principle, encirclements of the origin = Z − P = 0 − 1 = one (CCW).
**Concept:** Encirclements of origin by the G-mapping = Z_G − P_G.
**Twist:** No RHP pole → zero encirclements of origin → (c); two RHP poles → twice → (d).

**Q34 (APEPDCL-19):** In the Bode plot of a unity feedback control system, the phase of G(jω) at the gain crossover frequency is −125°. The phase margin is _____.
(a) 125° (b) –125° (c) –55° (d) 55°
**Ans: (d)** — PM = 180° + (−125°) = 55°.
**Concept:** PM = 180° + ∠G(jωgc).
**Twist:** Phase at ωgc = −200° → PM = −20° (unstable); phase −90° → PM = 90°.

**Q35 (APSPDCL-19):** The minimum-phase transfer function whose magnitude plot is shown (40 dB at low freq, corners at ω = 2 and ω = 10) is _____.
(a) Ks/((s+2)(s+10)) (b) K(s+2)(s+10)/s (c) K(s+2)/(s(s+10)) (d) K(s+10)/(s(s+2))
**Ans: (b)** — Slopes −20→0→+20 ⇒ one integrator and zeros at 2 and 10 → G(s) = K(s+2)(s+10)/s.
**Concept:** Zeros where slope rises by +20 dB/dec, poles where it drops.
**Twist:** Slopes reversed (0→−20→−40) ⇒ poles at 2, 10 → K/((s+2)(s+10))-type; starting slope +20 ⇒ zero at origin.

**Q36 (APSPDCL-19):** The polar plot of G(s) = 1/(s(Ts+1)) has intersection(s) on (apart from the origin) _____.
(a) neither the real axis nor the imaginary axis (b) both axes (c) the real axis only (d) the imaginary axis only
**Ans: (a)** — The type-1 polar plot starts at −90° (∞) and ends at the origin; it does not cross either axis.
**Concept:** Polar plot of 1/(s(Ts+1)): ω=0 at −90°, ω=∞ at 0.
**Twist:** Type-0 G = K/((sT1+1)(sT2+1)) starts on the real axis; G = 1/(s²(Ts+1)) starts at −180° and ends −270°.

**Q37 (APTransco-19):** A system has a damping ratio of 0.4. The frequency response exhibits a resonant peak of _____.
(a) 2.25 (b) 1.36 (c) 1.8 (d) 2
**Ans: (b)** — Mr = 1/(2ζ√(1−ζ²)) = 1/(2×0.4×√0.84) = 1.36.
**Concept:** Mr = 1/(2ζ√(1−ζ²)).
**Twist:** ζ = 0.5 → Mr = 1.155; ζ = 0.3 → Mr = 1.75; ζ > 0.707 → no resonance peak.

**Q38 (—):** Which unit is accepted for measurement of magnitude in Bode plots?
(a) Decibel (b) Deviation (c) Decimal (d) Degree
**Ans: (a)** — Magnitude is measured in decibels (dB = 20log10|G|).
**Concept:** Magnitude unit dB; phase unit degrees.
**Twist:** Phase is expressed in degrees → (d) trap; power gain would use 10log (dB but for power).

**Q39 (APPSC-20):** Due to adding a pole at s = 0, the angle of shifting in the Nyquist plot of the system will _____.
(a) shift 90° clockwise (b) shift 180° anticlockwise (c) shift 90° anticlockwise (d) 0° shift
**Ans: (a)** — Each pole at the origin contributes −90°, shifting the plot 90° clockwise.
**Concept:** Pole at origin → −90° (clockwise rotation of plot).
**Twist:** Two poles at origin → 180° shift; a zero at origin adds +90° (anticlockwise) → (c).

**Q40 (APPSC-20):** The Bode plot slope is expressed as _____.
(a) –6 dB/octave (b) –7 dB/octave (c) –8 dB/octave (d) –6 dB/decade
**Ans: (a)** — One-pole slope = −20 dB/decade = −6 dB/octave.
**Concept:** 6 dB/octave ≡ 20 dB/decade (one pole).
**Twist:** Two poles → −12 dB/octave (−40 dB/dec); "−6 dB/decade" (d) is a wrong (too small) value.

**Q41 (APPSC-20):** The Nyquist stability criterion requires the polar plot of _____.
(a) open loop transfer function (b) closed loop transfer function (c) characteristic equation (d) gain
**Ans: (a)** — Nyquist plots the open-loop G(jω)H(jω) and checks encirclements of (−1, j0).
**Concept:** Open-loop plot → closed-loop stability via N = P − Z.
**Twist:** The (−1, j0) point corresponds to the closed-loop characteristic equation 1 + GH = 0.

**Q42 (APPSC-20):** If poles are added at the origin, the polar plot gets shifted by _____ at ω = 0.
(a) –90° (b) –180° (c) –60° (d) –45°
**Ans: (a)** — Each pole at the origin adds −90° at ω = 0.
**Concept:** Integrator(s) set the ω→0 start angle: type-1 → −90°, type-2 → −180°.
**Twist:** Two poles at origin → −180° → (b); zero at origin → +90° start.

**Q43 (TSSPDCL-22):** G(s) = (s−1)/((s+2)(s+3)) is _____.
(a) Stable and minimum phase (b) Stable and non-minimum phase (c) Unstable and non-minimum phase (d) Unstable and minimum phase
**Ans: (b)** — Both poles in LHP (stable), zero in RHP (non-minimum phase).
**Concept:** Stability from poles; minimum-phase from poles AND zeros all in LHP.
**Twist:** G = (s−1)/((s−2)(s+3)) → unstable & non-minimum phase → (c); G = (s+1)/((s+2)(s+3)) → minimum phase.

**Q44 (TSSPDCL-22):** The initial slope of the Bode plot gives an indication of _____.
(a) Type of the system (b) Nature of the system’s time response (c) System stability (d) Gain margin
**Ans: (a)** — Initial slope = −20N dB/dec, N = system type.
**Concept:** type-N initial slope = −20N.
**Twist:** Initial slope −40 → type-2; initial slope +20 → zero at origin (type −1).

**Q45 (TSNPDCL-22):** If the resonant peak of a standard second-order system is 5, the approximate damping ratio is _____.
(a) 0.5, 9.5 (b) 0.05, 0.95 (c) 0.05, 0.95 (d) 0.5, 9.5
**Ans: (c)** — Mr = 1/(2ζ√(1−ζ²)) = 5 → 20ζ²−20ζ⁴−1 = 0 → ζ² = 0.95, 0.05 → ζ ≈ 0.95, 0.05.
**Concept:** Mr → two ζ solutions when Mr > 1.
**Twist:** Mr = 2 → 4ζ²−4ζ⁴−1 = 0 → ζ ≈ 0.38, 0.92; Mr = 1 (ζ = 0.707) → no resonance.

**Q46 (TSPSC-AEE-23):** G(s)H(s) = πe^(−0.25s)/s. The gain crossover frequency (rad/s) is _____.
(a) 2π (b) π (c) π/2 (d) π/4
**Ans: (b)** — |G(jω)H(jω)| = π/ω = 1 → ωgc = π (transport delay contributes no magnitude).
**Concept:** ωgc where |G| = 1; delay e^(−sT) affects only phase.
**Twist:** Numerator 2π → ωgc = 2π; numerator π/2 → ωgc = π/2. Delay only reduces PM, not ωgc.

**Q47 (TSPSC-AEE-23):** If the Nyquist plot of G(s)H(s) passes through (−1 + j0), the phase margin is likely to be _____.
(a) 45 degree (b) 180 degree (c) 0 degree (d) 90 degree
**Ans: (c)** — At the critical point ∠G(jωgc)H(jωgc) = −180°, so PM = 180° − 180° = 0°.
**Concept:** Passing through (−1,j0) ⇒ PM = 0, GM = 0 dB (marginal stability).
**Twist:** Plot crosses left of −1 → PM < 0 (unstable); plot stays right of −1 → PM > 0 (stable).

**Q48 (TSPSC-AEE-23):** G(s) = (1−s)/(1+s). A. minimum phase; B. BIBO stable; C. all-pass. Which are true?
(a) B only (b) A and B only (c) B and C only (d) A, B and C
**Ans: (c)** — RHP zero ⇒ non-minimum phase (A false); pole at −1 ⇒ BIBO stable (B true); mirror-image pole/zero ⇒ all-pass (C true).
**Concept:** All-pass: |G(jω)| = 1, RHP zeros mirrored by LHP poles.
**Twist:** G = (1−s)/(1−2s) → RHP pole ⇒ NOT BIBO stable; G = (s−1)/(s+1) is also all-pass.

**Q49 (TSSPDCL-AE-2023):** Correct statement about the Nyquist contour:
(a) entire jω axis and a semicircle of finite radius (b) entire jω axis and a semicircle of infinite radius (c) encloses the entire RHP traversed counterclockwise (d) on the jω-axis ω varies from 0 to ∞
**Ans: (b)** — Nyquist contour = entire jω axis + infinite-radius semicircle enclosing the RHP.
**Concept:** D-shaped Nyquist contour with infinite-radius semicircle.
**Twist:** Poles on the jω-axis need small indentations (semicircular bumps); direction of traversal is clockwise by convention.

**Q50 (TSSPDCL-AE-2023):** Match for the Bode phase plot: a. pole at origin, b. two poles at origin, c. zero at origin, d. two zeros at origin — with phases P.180, Q.90, R.−90, S.−180, T.0:
(a) a-R; b-S; c-Q; d-P (b) a-R; b-S; c-T; d-P (c) a-Q; b-P; c-R; d-S (d) a-Q; b-P; c-R; d-T
**Ans: (a)** — 1/s → −90°, 1/s² → −180°, s → +90°, s² → +180°.
**Concept:** Each pole at origin −90°, each zero at origin +90°.
**Twist:** Zero at origin (s) adds +90° (not 0) → traps (b)/option T; s² adds +180°.

**Q51 (TSPSC-AEE-23):** Chronological order for constructing the Bode plot: I. identify corner frequencies; II. draw smooth curve through corrected points; III. rewrite TF in time-constant form; IV. draw phase curve for each factor and add algebraically.
(a) I, IV, II, III (b) III, I, II, IV (c) II, I, III, IV (d) IV, I, III, II
**Ans: (b)** — Rewrite in time-constant form → identify corners → draw smooth asymptotic curve → add phase curves.
**Concept:** Bode construction sequence.
**Twist:** Common wrong order: identify corners before rewriting → (a)/(c) traps.

**Q52 (TSGenco-24):** In which case is a control system NOT stable?
(a) Gain margin and Phase margin are positive (b) Damping ratio is less than zero (c) All poles in the LHS of s-plane (d) Phase crossover frequency greater than gain crossover frequency
**Ans: (b)** — Negative damping ratio → growing oscillations → unstable.
**Concept:** Stable: GM > 0, PM > 0, ωpc > ωgc, all poles LHP, ζ > 0.
**Twist:** ωpc < ωgc → GM < 0 → unstable; GM = 0 dB & PM = 0 → marginally stable.

**Q53 (TSGenco-24):** G(s) = K/(s(s+1)). The value of K for gain crossover frequency 10 rad/s is approximately _____.
(a) 1 (b) 10 (c) 1000 (d) 100
**Ans: (d)** — |G(j10)| = K/(10√(10²+1)) = 1 → K = 10√101 ≈ 100.
**Concept:** ωgc where |G(jω)| = 1 → K = ωgc√(ωgc²+1).
**Twist:** ωgc = 1 → K = √2 ≈ 1.414; ωgc = 100 → K ≈ 10⁴.

**Q54 (TSGenco-24):** G(s) = (s+2)/((s+1)(s−1)). The number of encirclements of (−1 + j0) by the Nyquist plot is _____.
(a) 1 clockwise (b) 2 clockwise (c) 1 counterclockwise (d) zero
**Ans: (c)** — P = 1 (pole at +1), closed loop stable (Z = 0) → N = P − Z = 1 CCW encirclement.
**Concept:** Z = P − N; stable requires Z = 0.
**Twist:** Same TF with no RHP pole (s+2)/((s+1)(s+3)) → P = 0 → no encirclements → (d); G with 2 RHP poles → 2 CCW needed.

**Q55 (TSGenco-24):** Statement (I): Phase-lead compensation is used to increase rise time and decrease overshoot. Statement (II): Phase-lag compensation improves relative stability of a system. Which are correct?
(a) Both (I) and (II) are correct (b) Only (II) is correct (c) Both are not correct (d) Only (I) is correct
**Ans: (b)** — Lead REDUCES rise time (faster response), so (I) is wrong; lag improves relative stability, (II) true.
**Concept:** Phase lead → faster/speedier (reduced rise time, more overshoot); phase lag → better relative stability, less steady-state error.
**Twist:** Correct (I): lead decreases rise time & increases overshoot → would be true → (a) if reworded. Lag also used to reduce steady-state error.

## Unit 5: Design of Control Systems (24 Qs)

Root locus / lead-lag compensators / PID controllers / gain selection. Answers verified against the official OHM answer key (1b 2d 3b 4b 5a 6a 7d 8b 9d 10a 11d 12b 13a 14d 15a 16a 17a 18b 19b 20b,d 21b 22b 23c 24a).

**Q1 (APSPDCL-12):** Lead compensator G(s) = 4(1+0.15s)/(1+0.05s) — the maximum phase shift obtainable is
(a) 15° (b) 30° (c) 45° (d) 60°
**Ans: (b)** — α = 0.05/0.15 = 1/3, sinφm = (1−α)/(1+α) = (2/3)/(4/3) = 1/2 → φm = 30°.
**Concept:** lead max phase shift φm = sin⁻¹[(1−α)/(1+α)]; α = zero-time-constant/pole-time-constant (α<1), DC gain 4 doesn't enter.
**Twist:** α = 1/4 → sinφm = 3/5 → φm ≈ 37°. α → 0 → φm → 90° (unattainable in practice).

**Q2 (HMWS-12):** The lag compensator
(a) improves both steady state and transient response (b) improves steady state only (c) improves transient only (d) improves steady state and reduces speed of transient response
**Ans: (d)** — lag raises low-frequency gain (lower ess) but the pole placed near the origin makes the transient decay slowly (slower response).
**Concept:** lag → ↑ low-frequency gain → ↓ steady-state error, with a slowly-decaying transient (reduced speed).
**Twist:** "reduce steady-state error" → lag or PI. "improve transient AND steady state" → lead-lag.

**Q3 (Transco-12):** Phase lead compensations are used to
(a) increase rise time and decrease overshoot (b) decrease both rise time and overshoot (c) increase both rise time and overshoot (d) decrease rise time and increase overshoot
**Ans: (b)** — lead raises the gain-crossover frequency → larger bandwidth → smaller rise time, and added phase margin lowers overshoot.
**Concept:** lead → ↑ωgc → ↑bandwidth → ↓tr and ↓%Mp (improved damping).
**Twist:** effect on bandwidth → bandwidth increases. Effect on phase margin → PM increases.

**Q4 (APSPDCL-14):** Compensator K(s+3.618)/(s+0.576) is
(a) Lead compensator (b) Lag compensator (c) Lag or lead depending on value of K (d) Lag-lead compensator
**Ans: (b)** — pole at −0.576 lies right of zero at −3.618 (pole closer to jω axis) → lag.
**Concept:** classification by pole/zero location, independent of K: pole right of zero → lag; zero right of pole → lead.
**Twist:** K(s+3.618)/(s+6.5) (zero right of pole) → lead. Swapping pole/zero → lead.

**Q5 (HMWS-15):** Effect of phase lead compensator on rise time and bandwidth
(a) Rise time decreases and bandwidth increases (b) Both decrease (c) Rise time increases and bandwidth decreases (d) Both increase
**Ans: (a)** — lead → higher gain-crossover frequency → larger bandwidth and smaller rise time.
**Concept:** lead → ↑ωgc → ↑BW → ↓tr.
**Twist:** lag → tr increases and BW decreases (both get worse). lead-lag → tr↓ and BW↑ with ess also improved.

**Q6 (HMWS-15):** Which compensator is used to increase the speed of the response?
(a) Lead compensator (b) Lag compensator (c) Lead-lag compensator (d) None of the above
**Ans: (a)** — lead speeds the response (shorter rise/settling time); lag slows it.
**Concept:** lead → faster transient; lag → slower transient.
**Twist:** "improve steady-state accuracy" → lag. "increase damping at a fixed ess" → lead.

**Q7 (TS-Genco-15):** If stability error for step input and speed of response are the design criteria, the recommended controller is
(a) P controller (b) PD controller (c) PI controller (d) PID controller
**Ans: (d)** — derivative part improves transient/speed, integral part eliminates steady-state error.
**Concept:** PID = PD (↑ξ, fast transient) + PI (type↑, ess→0).
**Twist:** only ess → PI. only transient/speed → PD. only speed at no accuracy demand → P/PD.

**Q8 (TSTransco-15):** To regulate steady-state error to zero in a negative feedback control system, one employs
(a) Proportional control (b) Integral control (c) Derivative control (d) Proportional-Derivative control
**Ans: (b)** — integral action eliminates steady-state error (type raised, ess→0).
**Concept:** integral control → type↑ → zero steady-state error for step (ramp if type-2).
**Twist:** zero error for ramp → type-2 (double integral). PD → ess unchanged.

**Q9 (TSSPDCL-15):** A differentiator is not usually used in a control system, because it
(a) reduces damping (b) increases error (c) reduces gain margin (d) increases input noise
**Ans: (d)** — the s-term amplifies high-frequency noise.
**Concept:** differentiator → noise amplification; practical D-action is band-limited, e.g. Kds/(1+τs).
**Twist:** pure differentiator in a PD → noise; use filtered/approximate derivative (Ks/(s+a)). PD increases damping (not noise source in ideal case).

**Q10 (TSNPDCL-15):** Phase lead compensator Gc(s) = K(1+s/z)/(1+s/p), p, z > 0. Then
(a) z < p (b) z > p (c) z > Kp (d) z > K/p
**Ans: (a)** — lead requires the zero (−z) to lie right of the pole (−p), i.e., z < p.
**Concept:** lead condition: zero closer to origin than pole (z < p); lag: z > p.
**Twist:** z > p → lag (phase lag, low-pass). K only scales gain, does not decide lead/lag.

**Q11 (APGenco-17):** Which is CORRECT with respect to a LAG-LEAD compensator?
(a) It is similar to PI controller (b) It acts as band-pass filter (c) It is a second-order system with one zero and two poles (d) It acts as a band-reject filter
**Ans: (d)** — lead portion is high-pass, lag portion is low-pass; their series gives band-reject (band-stop) behavior.
**Concept:** lag-lead = low-pass (lag) + high-pass (lead) → band-reject filter (two poles + two zeros, second order).
**Twist:** lag alone → low-pass filter. lead alone → high-pass filter. lag-lead ≈ PD+PI = PID-like control action.

**Q12 (APEPDCL-19):** When a PD controller is used in a system, which of the following is affected?
(a) Natural frequency (b) Damping ratio (c) Type of the system (d) Steady state error
**Ans: (b)** — PD adds derivative action that increases the damping ratio (improves transient); ωn, type and ess unchanged.
**Concept:** PD → ↑ξ → ↓%Mp, ↓tr; ωn, type, ess unaffected.
**Twist:** PI → type↑, ess→0. PID → both ξ↑ and ess→0.

**Q13 (APEPDCL-19):** If lead compensator is (s+a)/(s+b) and lag compensator is (s+p)/(s+q), which condition is satisfied?
(a) a < b and p > q (b) a > b and p < q (c) a > b and p > q (d) a < b and p < q
**Ans: (a)** — lead: zero −a right of pole −b ⇒ a < b; lag: pole −q closer to origin than zero −p ⇒ p > q.
**Concept:** lead → zero nearer origin (smaller coefficient); lag → pole nearer origin (zero coefficient larger).
**Twist:** a > b, p < q would both be "lead-like" (impossible classification). a<b and p<q → violates lag condition (pole not nearer origin).

**Q14 (APTransco-19):** Lead compensator Gc(s) = (1+0.12s)/(1+0.04s) can provide a maximum phase shift of
(a) 90° (b) 60° (c) 45° (d) 30°
**Ans: (d)** — α = 0.04/0.12 = 1/3, sinφm = 1/2 → φm = 30° (same math as Q1).
**Concept:** φm = sin⁻¹[(1−α)/(1+α)]; unity DC gain here, but gain value never changes phase lead.
**Twist:** Gc = 4(1+0.15s)/(1+0.05s) → still 30°. α = 0.25 → ≈ 37°. Large α (≈1) → tiny φm.

**Q15 (APPSC-20):** Which one is the correct input to a controller?
(a) Error signal (b) Desired variable value (c) Sensed signal (d) Signal of fixed amplitude not dependent on desired variable value
**Ans: (a)** — the controller receives the error (actuating) signal e = r − b.
**Concept:** controller input = error signal; its output drives the plant.
**Twist:** input to plant → controller output. input to feedback element → plant output.

**Q16 (APPSC-20):** Advantage of pole-zero cancellation while designing a controller
(a) The system order is reduced (b) The system order is increased (c) Error reduced to optimum level (d) Controller cost become low
**Ans: (a)** — a coincident pole-zero pair cancels, lowering the effective system order (simpler dynamics).
**Concept:** pole-zero cancellation removes a mode → order reduction.
**Twist:** exact cancellation risky — mismatched cancellation leaves a hidden slow pole (slow tail) or near-RHP pole (instability).

**Q17 (APPSC-20):** To obtain improved steady-state and transient response, the following compensator may be used
(a) lead-lag compensator (b) lag compensator (c) lead compensator (d) lead-lead compensator
**Ans: (a)** — lag improves ess, lead improves transient; lag-lead gives both.
**Concept:** lead-lag = lead (transient) + lag (steady-state).
**Twist:** only transient → lead. only steady-state → lag. controller form of both → PID.

**Q18 (TSSPDCL-22):** Which compensation is adopted for improving transient response of a negative unity feedback system?
(a) Phase lag compensation (b) Phase lead compensation (c) Gain compensation (d) Both phase and gain compensation
**Ans: (b)** — phase-lead improves damping/PM → better transient; lag only fixes steady state.
**Concept:** lead → transient; lag → steady-state.
**Twist:** improving steady-state → lag. improving both → lead-lag.

**Q19 (TSSPDCL-22):** Phase network Gc(s) = (s+1/T)/(s+1/aT) with a < 1 provides maximum phase lead at a frequency of
(a) 1/T (b) 1/(T√a) (c) 1/(aT) (d) 1/(√(aT))
**Ans: (b)** — ωm = √[(1/T)(1/aT)] = 1/(T√a); and sinφm = (1−a)/(1+a).
**Concept:** ωm = geometric mean of the zero (1/T) and pole (1/aT) frequencies.
**Twist:** if a > 1 → lag network, but ωm still 1/(T√a) (now a phase-lag frequency). Changing a changes φm, not the form of ωm.

**Q20 (TSNPDCL-22):** In lag-compensator and lead-compensator networks, if R1 = R2 = R, the respective transfer functions are
(a) (1+sRC)/(2+sRC) and (1+sRC)/(1+2sRC) (b) (1+sRC)/(1+2sRC) and (1+sRC)/(2+sRC) (c) (1+2sRC)/(1+sRC) and (2+sRC)/(1+sRC) (d) (2+sRC)/(1+sRC) and (1+2sRC)/(1+sRC)
**Ans: (b, d)** — with R1=R2=R: lag TF = (1+sRC)/(1+2sRC) (pole −1/2RC closer to jω axis); lead TF = (1+sRC)/(2+sRC) (zero −1/RC closer to jω axis); option (d) gives the same lag/lead roles (multi-correct key).
**Concept:** passive RC lag: pole nearer origin than zero; passive RC lead: zero nearer origin than pole.
**Twist:** general R1≠R2: lag = (1+sR2C)/(1+s(R1+R2)C); lead = (R2/(R1+R2))(1+sR1C)/(1+s(R1R2/(R1+R2))C). Asked "which is the lag one" → the TF with pole closer to origin.

**Q21 (TSPSC-AEE-23):** Which of the following can be the result of introducing integral action in the forward path of a unity feedback system?
(a) Reduced noise immunity (b) Elimination of steady-state error (c) Increased stability margin (d) Faster system response
**Ans: (b)** — integral action raises system type → steady-state error eliminated.
**Concept:** integral → type↑ → ess→0; stability margin typically DECREASES (PI reduces PM).
**Twist:** "result on stability margin" → stability margin decreases (less stable). "result of derivative action" → noise amplification.

**Q22 (TSPSC-AEE-23):** Transfer function G(s) = (s+α)/(s+β) could represent a lead compensator, if
(a) α = 3, β = 1 (b) α = 1, β = 2 (c) α = 3, β = 2 (d) α = −3, β = −1
**Ans: (b)** — lead requires the zero (α) closer to origin than the pole (β): α = 1 < β = 2.
**Concept:** lead condition in coefficients: 0 < α < β.
**Twist:** α = 3, β = 1 → lag. negative α/β → zero/pole in RHP (non-minimum phase) — not a valid lead/lag classification.

**Q23 (TSSPDCL-AE-2023):** Identify the correct statement from the following
(a) PD controller increases the damping ratio and peak overshoot of the system (b) PD controller decreases the damping ratio and peak overshoot of the system (c) PI controller increases the order of the system by one (d) PI controller becomes more stable than the original one
**Ans: (c)** — PD raises ξ and LOWERS %Mp ((a),(b) wrong); PI adds a pole at origin → order +1 and less stable.
**Concept:** PD → ↑ξ, ↓%Mp; PI → type↑, order+1, stability worsens.
**Twist:** "PD effect on %Mp" → %Mp decreases. "PI effect on ess" → ess→0.

**Q24 (TSPSC-AEE-23):** Phase-lead network G(s) = (1+T1s)/(1+T2s). Case I: T1=T2=0.04; Case II: T1=T2=0.01; Case III: T1=0.04, T2=0.01. Arrange in increasing order of the frequency at which maximum phase lead occurs.
(a) Case I, Case III, Case II (b) Case I, Case II, Case III (c) Case II, Case I, Case III (d) Case III, Case I, Case II
**Ans: (a)** — ωm = 1/√(T1T2): Case I = 1/0.04 = 25, Case III = 1/√(0.04·0.01) = 50, Case II = 1/0.01 = 100 → I < III < II.
**Concept:** ωm = 1/√(T1T2) (symmetric in T1, T2); smaller time constants → higher ωm.
**Twist:** swap Case III to T1=0.01, T2=0.04 → ωm still 50 (symmetric). Both T = 0.04 vs 0.01 → 25 vs 100 rad/s.

---
**Concept quick-map:** lead → ↑PM/↑BW/↓tr/↓%Mp (transient); lag → ↓ess (steady state); lead-lag → both; PD → ↑ξ, %Mp↓; PI → type↑, ess→0, less stable; PID = PD + PI; max lead phase φm = sin⁻¹[(1−α)/(1+α)] at ωm = 1/(T√α).

## Unit 6: State Space Analysis (20 Qs)

**Q1 (HMWS-12):** State model ẋ = [[−1,0],[0,3]]x + [[1],[1]]u; x₁(0)=x₂(0)=0, y = [1 0]x. Unit-step response y(t):
(a) 1 + e^(−t) (b) (1/3)[1 − e^(−3t)] (c) 1 − e^(−t) (d) 2 + e^(−t)
**Ans: (c)** — T(s) = C(sI−A)⁻¹B = 1/(s+1); step response L⁻¹[(1/s)(1/(s+1))] = 1 − e^(−t).
**Concept:** T(s) = C(sI−A)⁻¹B + D; system response via transfer function from state model.
**Twist:** If C = [0 1] (output is 2nd state only), TF = 1/(s−3) → y(t) = (1/3)[1 − e^(−3t)] → (b). Nonzero initial conditions add zero-input term Φ(t)x(0).

**Q2 (EPDCL-14):** Y/U = (b₁s² + b₂s + b₃)/(s³ + a₁s² + a₂s + a₃) in SFG (three cascaded 1/s blocks, states x₁,x₂,x₃). System matrix A:
(a) [[0,1,0],[0,0,1],[−a₃,−a₂,−a₁]] (b) [[−a₁,1,0],[−a₂,0,1],[−a₃,0,0]] (c) [[−a₁,−a₂,−a₃],[1,0,0],[0,1,0]] (d) [[0,0,−a₃],[1,0,−a₂],[0,1,−a₁]]
**Ans: (c)** — Node equations: ẋ₁ = −a₁x₁ − a₂x₂ − a₃x₃, ẋ₂ = x₁, ẋ₃ = x₂.
**Concept:** phase-variable (controller canonical) form from signal-flow graph: companion matrix with feedback −aᵢ in first row.
**Twist:** Reversing state indexing (x₃ = first integrator output) transposes A to observer canonical [[0,0,−a₃],[1,0,−a₂],[0,1,−a₁]] → (d). Numerator b-coefficients enter via feedforward paths straight to y (fill C, not A).

**Q3 (HMWS-15):** ẋ = Ax + Bu with A = [[1,0],[1,1]]. State transition matrix:
(a) [[eᵗ, eᵗ],[0, eᵗ]] (b) [[eᵗ, 0],[t eᵗ, eᵗ]] (c) [[eᵗ, 0],[eᵗ, eᵗ]] (d) [[eᵗ, t eᵗ],[0, eᵗ]]
**Ans: (b)** — [sI−A]⁻¹ = [[1/(s−1), 0],[1/(s−1)², 1/(s−1)]] → L⁻¹ = [[eᵗ, 0],[t eᵗ, eᵗ]].
**Concept:** φ(t) = e^(At) = L⁻¹[(sI−A)⁻¹]; repeated eigenvalue (1) gives t·eᵗ term in off-diagonal (Jordan block).
**Twist:** A = [[1,1],[0,1]] (upper-triangular) → φ(t) = [[eᵗ, t eᵗ],[0, eᵗ]] → (d). Distinct eigenvalues A = diag(1,3) → diag(eᵗ, e³ᵗ).

**Q4 (HMWS-15):** Which variable cannot be taken as a state variable:
(a) Output of the integrator (b) Voltage across a capacitor (c) Current passing through a resistor (d) Current passing through an inductor
**Ans: (c)** — Resistor is not an energy-storage element.
**Concept:** state variables = outputs of energy-storage elements (integrator output, capacitor voltage, inductor current).
**Twist:** Capacitor current (not voltage) also cannot be a state — it is a dependent variable of dv_C/dt. Both v_C and i_L needed when network has both energy-storage elements.

**Q5 (HMWS-15):** Which is not true:
(a) In state model, initial conditions are taken into consideration (b) In transfer function model, initial conditions are taken zero (c) Transfer function applicable only for linear time-invariant systems (d) State model of the system is unique
**Ans: (d)** — State model depends on choice of state variables, hence not unique.
**Concept:** state-space realization is non-unique; transfer function is unique (assumes zero IC).
**Twist:** Similarity transformation x̄ = Px gives infinitely many equivalent state models with the same TF. Eigenvalues, TF, controllability/observability are invariant under that transform.

**Q6 (HMWS-15):** ẋ = Ax + Bu, A = [[−1,2],[0,2]], B = [[0],[1]]:
(a) Unstable and uncontrollable (b) Stable but uncontrollable (c) Unstable but controllable (d) Stable and controllable
**Ans: (c)** — Q_c = [B AB] = [[0,2],[1,2]], det ≠ 0 → controllable; |sI−A| = (s+1)(s−2) → pole at +2 in RHP → unstable.
**Concept:** controllability rank test rank[B AB] = n; eigenvalues of A = poles → stability.
**Twist:** B = [[1],[0]] → Q_c = [[1,−1],[0,0]] singular → uncontrollable (still unstable) → (a). Interchanging eigenvalues (A = [[2,0],[−1,−1]]-like) does not change controllability unless B structure changes.

**Q7 (TSGenco-15):** ẋ = [[−1,0],[0,−2]]x + [[0],[1]]u, y = [1 2]x:
(a) Completely controllable (b) Not completely controllable (c) Completely observable (d) Not completely observable
**Ans: (b, c)** — Q_c = [[0,0],[1,−2]] singular → not completely controllable; Q_o = [[1,−1],[2,−4]], det ≠ 0 → completely observable.
**Concept:** Kalman's rank tests: rank[B AB] = n for controllability, rank[Cᵀ AᵀCᵀ] = n for observability.
**Twist:** y = [1 0]x → Q_o = [[1,−1],[0,0]] singular → unobservable. B = [[1],[0]] (drives the −1-mode) → Q_c = [[1,−1],[0,0]] singular too → still uncontrollable; B = [[1],[1]] → controllable.

**Q8 (TSGenco-15):** Second-order system Ẋ = AX + BU. If x₁(t) = x₂(t), then system is:
(a) Controllable (b) Uncontrollable (c) Observable (d) Unstable
**Ans: (b)** — x₁ = x₂ forces equal rows of A and B, giving |Q_c| = v(pt+qv) − v(pt+qv) = 0 → uncontrollable.
**Concept:** linearly dependent state variables ⇒ singular controllability matrix; effective order drops below n.
**Twist:** If x₁ and x₂ independent (general 2×2 A), |Q_c| = t(rt+sv) − v(pt+qv) ≠ 0 in general → controllable. Constraint x₁ = x₂ leaves only one independent state, so rank[B AB] < 2.

**Q9 (TSGenco-15):** Transfer function for Ẋ = AX + BU, Y = CX + DU:
(a) D + C(sI−A)⁻¹B (b) B(sI−A)⁻¹C + D (c) D(sI−A)⁻¹B + C (d) C(sI−A)⁻¹D + B
**Ans: (a)** — T(s) = C(sI−A)⁻¹B + D.
**Concept:** T(s) = C(sI−A)⁻¹B + D (Laplace with zero IC).
**Twist:** D = 0 ⇒ T(s) = C(sI−A)⁻¹B. Order matters for matrix dims: C·(sI−A)⁻¹·B, not B·(…)·C. Eigenvalues of A = poles of T(s).

**Q10 (TSSPDCL-15):** ẋ(t) = A(t)x(t) + B(t)u(t), y(t) = C(t)x(t) + d(t)u(t) represents:
(a) Discrete time-invariant (b) Continuous time-invariant (c) Continuous time-variant (d) Discrete time-variant
**Ans: (c)** — All matrices are explicit functions of time t, so continuous-time and time-varying.
**Concept:** time-variant system when A,B,C,d depend explicitly on t (vs. constants → LTI).
**Twist:** A,B,C,d constant → continuous time-invariant → (b). Difference equations x(k+1) = Ax(k) + Bu(k) → discrete system.

**Q11 (APGenco-17):** ẋ = AX + BU, A = [[1,0],[1,1]]. State transition matrix:
(a) [[t eᵗ, 0],[eᵗ, eᵗ]] (b) [[t eᵗ, 0],[eᵗ, e^(−t)]] (c) [[e^(−t), 0],[t e^(−t), e^(−t)]] (d) [[eᵗ, 0],[t eᵗ, eᵗ]]
**Ans: (d)** — Same as Q3: [sI−A]⁻¹ → φ(t) = [[eᵗ, 0],[t eᵗ, eᵗ]].
**Concept:** e^(At) for Jordan block with repeated eigenvalue.
**Twist:** A = diag(1,−1) → φ(t) = diag(eᵗ, e^(−t)). A = −I → φ(t) = e^(−t)I.

**Q12 (TSSPDCL-18):** T(s) = 1/(s³ + 3s² + 2s + 10) in state variable form. System matrix A:
(a) [[0,0,1],[0,1,0],[−10,−2,−3]] (b) [[0,1,1],[0,0,1],[−10,−2,−3]] (c) [[0,1,0],[0,0,1],[−10,−2,−3]] (d) [[0,1,0],[0,0,1],[−3,−2,−10]]
**Ans: (c)** — Controllable canonical form: A = [[0,1,0],[0,0,1],[−a₀,−a₁,−a₂]] with (a₀,a₁,a₂) = (10,2,3).
**Concept:** phase-variable (controllable canonical) companion form — bottom row = −denominator coefficients in ascending order.
**Twist:** T(s) = 1/(s³+10s²+2s+3) → A = [[0,1,0],[0,0,1],[−3,−2,−10]] → (d). Observer canonical form is the transpose: [[0,0,−10],[1,0,−2],[0,1,−3]].

**Q13 (TSTransco-18):** ẋ = [[−1,1,0],[0,−1,0],[0,0,−2]]x + [[0],[4],[0]]u, y = [1 1 1]x:
(a) Controllable and observable (b) Uncontrollable and observable (c) Uncontrollable and unobservable (d) Controllable and unobservable
**Ans: (b)** — Kalman's test gives not controllable but observable.
**Concept:** controllability/observability via rank of [B AB A²B] and [C; CA; CA²] (or Jordan-form mode analysis).
**Twist:** If B = [[1],[4],[0]] (drive enters the −1-mode), system becomes controllable & observable → (a). If C = [1 0 0], only 1st state observed → becomes unobservable.

**Q14 (APEPDCL-19):** ẋ = [[2,0],[0,2]]x + [[1],[1]]u. State transition matrix:
(a) [[e^(−2t), 1],[1, e^(−2t)]] (b) [[e^(2t), 0],[0, e^(2t)]] (c) [[e^(−2t), 0],[0, e^(−2t)]] (d) [[e^(2t), 1],[1, e^(2t)]]
**Ans: (b)** — A = 2I ⇒ [sI−A]⁻¹ = diag(1/(s−2), 1/(s−2)) ⇒ φ(t) = diag(e^(2t), e^(2t)).
**Concept:** e^(At) for diagonal A = diag(e^(λ₁t), …, e^(λₙt)); scalar matrix ⇒ e^(kt)I.
**Twist:** A = −2I → φ(t) = diag(e^(−2t), e^(−2t)) → (c). A = [[2,1],[0,2]] → φ(t) = [[e^(2t), t e^(2t)],[0, e^(2t)]].

**Q15 (TSSPDCL-22):** Second-order Ẋ = AX + BU, Y = CX + DU controllable & observable if rank of both matrices is 2:
(a) [B AB] and [C CA] (b) [B;AB] and [C;CA] (c) [B;AB] and [C CA] (d) [B AB] and [C;CA]
**Ans: (d)** — Controllability matrix Q_c = [B AB]; observability matrix Q_o = [C; CA] (rows stacked).
**Concept:** Q_c = [B AB A²B … A^(n−1)B]; Q_o = [C; CA; CA²; …; CA^(n−1)].
**Twist:** n-th order: use n columns of B-terms and n rows of C-terms. Controllability uses columns of B (and AB), observability uses rows of C (and CA) — reversing these gives wrong matrices (options b, c).

**Q16 (TSPSC-AEE-23):** ẋ = [[0,1],[−3,−6]]x + [[1],[0]]u, y = [1 0]x:
(a) Stable and observable, but not controllable (b) Stable and controllable, but not observable (c) Controllable, observable, but unstable (d) Controllable, observable and stable
**Ans: (d)** — CM = [[1,0],[0,−3]] rank 2 (controllable); OM = [[1,0],[0,1]] rank 2 (observable); |sI−A| = s² + 6s + 3 → roots −0.55, −5.45 → stable.
**Concept:** full controllability (det Q_c ≠ 0), full observability (det Q_o ≠ 0), stability from eigenvalues of A.
**Twist:** y = [0 1]x → OM = [[0,1],[−3,−6]] det = 3, still observable. B = [[0],[1]] → CM = [[0,1],[1,−6]] rank 2, still controllable — stability is set only by A.

**Q17 (TSSPDCL-AE-2023):** State transition matrix of A = diag(1,2,3):
(a) diag(e^(3t), e^(2t), e^t) (b) diag(e^(−3t), e^(−2t), e^(−t)) (c) diag(e^t, e^(2t), e^(3t)) (d) diag(e^(−t), e^(−2t), e^(−3t))
**Ans: (c)** — [sI−A]⁻¹ = diag(1/(s−1), 1/(s−2), 1/(s−3)) ⇒ φ(t) = diag(e^t, e^(2t), e^(3t)).
**Concept:** transition matrix of diagonal A = e^(At) = diag(e^(λᵢt)) — eigenvalue order preserved.
**Twist:** A = diag(−1,−2,−3) → φ(t) = diag(e^(−t), e^(−2t), e^(−3t)) → (d). For non-diagonalizable or repeated λ use modal matrix: φ(t) = P·diag(e^(λᵢt))·P⁻¹.

**Q18 (TSSPDCL-AE-2023):** Steady-state error for unit step input of ẋ = [[0,1],[−4,−2]]x + [[0],[1]]u, y = [1 0]x:
(a) 0.25 (b) 0 (c) 0.5 (d) 0.75
**Ans: (d)** — TF = C(sI−A)⁻¹B = 1/(s²+2s+4); open-loop position constant K_p = 1/3 ⇒ e_ss = 1/(1+K_p) = 3/4 = 0.75.
**Concept:** e_ss for unit step = 1/(1+K_p), K_p = lim G(s) (type-0 system).
**Twist:** For unit ramp input, e_ss = 1/K_v = 2 (type-0 → infinite). Forcing y = [0 1]x gives TF = s/(s²+2s+4) (type-1) → step e_ss = 0.

**Q19 (TSPSC-AEE-23):** ẋ = [[−2,0],[0,−4]]x + [[1],[0]]u, y = [1 1]x. Transfer function:
(a) 1/(s+4) (b) 1/(s+2) (c) (s²+6s+8)/[(s+2)(s+4)] (d) 1/[(s+2)(s+4)]
**Ans: (b)** — T(s) = C(sI−A)⁻¹B + D = [1 1]·diag(1/(s+2), 1/(s+4))·[1;0] = 1/(s+2).
**Concept:** T(s) = C(sI−A)⁻¹B; only modes reached by u and seen by y appear (mode −4 decoupled).
**Twist:** B = [1;1] → TF = 1/(s+2) + 1/(s+4) = (2s+6)/[(s+2)(s+4)]. C = [0 1] → TF = 1/(s+4) → (a).

**Q20 (TSGenco-24):** Which is not true:
(a) State model of a system is unique (b) State space model applicable for MIMO, non-linear and time-variant systems (c) Transfer function applicable only for linear time-invariant systems (d) In state model, initial conditions are taken into consideration
**Ans: (a)** — Multiple state-space models exist for a given system depending on state-variable selection.
**Concept:** non-uniqueness of state-space realization (unlike TF, which is unique).
**Twist:** Similarity transform x̄ = Px keeps TF, eigenvalues, controllability/observability identical but changes A, B, C. A minimal realization is unique only up to similarity.

> Total: 256 questions annotated.

---

# 📋 FORMULA SUMMARY — Exam-Day Sheet (Control Systems)

## 1. Basics & Modelling
- **CLTF = G/(1+GH)** · Mason: T = ΣPkΔk/Δ · characteristic eq: 1+GH = 0

## 2. Time Response
- **%MP = e^(−ζπ/√(1−ζ²))×100** · tp = π/ωd · ts = 4/(ζωn) · ωd = ωn√(1−ζ²)
- **Kp = lim G · Kv = lim sG · Ka = lim s²G** · ess depends on system type & input

## 3. Stability (Routh)
- **Routh first column all > 0** → stable · row of zeros → auxiliary equation · marginal: imaginary-axis roots

## 4. Frequency Response
- **GM = 1/|G(jω)| at ∠=−180° · PM = 180° + ∠G at |G|=1** · stable: PM>0, GM>0
- **Nyquist: N = P − Z** · Mr (resonant) ↔ ζ · slope −20dB/dec per pole

## 5. Design
- Root locus: poles→zeros · **lead → ↑PM/speed · lag → ↓ess · PD ↑damping · PI ↓ess**

## 6. State Space
- **ẋ = Ax + Bu, y = Cx + Du** · eigenvalues of A = poles · |sI−A| = 0
- **Controllability: rank[B AB A²B] = n · Observability: rank[C; CA; CA²] = n**
