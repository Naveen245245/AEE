# Power Systems (T&D) – Formula/Concept vs. Question Count Analysis

**Source:** Study Material – GTD PYQs 2026 (Power Systems T&D, Module-1 & 2)  
**Total Questions Analyzed:** 214+ (Pages 1-32)

---

## 📚 Table of Contents

1. [Formula/Concept vs. Question Count Analysis](#-formulaconcept-vs-question-count-analysis)
2. [The 5-Question Decision Flowchart](#-the-5-question-decision-flowchart)
3. [How to Identify the Topic from the Question](#-how-to-identify-the-topic-from-the-question)
4. [The Ultimate "What Happens When..." Cheat-Sheet](#-the-ultimate-what-happens-when-cheat-sheet)
5. [Top 15 Concepts to Score >90%](#-top-15-concepts-to-score-90)
6. [Quick Reference Card (Exam Day)](#-quick-reference-card-exam-day)

---

## 📊 Formula/Concept vs. Question Count Analysis

| S.No | Formula / Concept | No. of Qs | What They GIVE in the Question | What They ASK in the Question | Mapped Question Numbers |
| :---: | :-------------------------------------------------------------- | :---: | :--- | :--- | :--- |
| **1** | **ABCD Parameters of Transmission Lines** <br> Short: `[1 Z; 0 1]` <br> Medium (π): `A = 1 + YZ/2, B = Z, C = Y(1 + YZ/4), D = 1 + YZ/2` <br> Medium (T): `A = 1 + YZ/2, B = Z(1 + YZ/4), C = Y, D = 1 + YZ/2` <br> Long: `A = cosh(γl), B = Z_c sinh(γl), C = (1/Z_c) sinh(γl), D = cosh(γl)` | **~18** | Line length, Z (series impedance), Y (shunt admittance), Frequency, Nominal π or T model. | **Calculate A, B, C, D parameters** , Sending/Receiving end voltage/current, Regulation, **Ferranti effect compensation**. | Q16, Q22, Q45, Q67, Q97, Q100, Q133, Q149, Q173, Q177, Q192, Q202, Q205 |
| **2** | **Corona Loss & Critical Voltage** <br> `P_c ∝ (V - V_d)^2` <br> `P_c ∝ (f + 25)` <br> `V_d ∝ r * δ * ln(d/r)` | **~14** | Line voltage, Frequency, Conductor size, Spacing, Weather conditions. | **Corona loss** at different voltages/frequencies, **Critical disruptive voltage** , **Methods to reduce corona**. | Q3, Q17, Q26, Q48, Q73, Q106, Q109, Q132, Q138, Q147, Q148, Q165, Q166, Q167, Q171, Q182, Q185 |
| **3** | **Sag & Tension Calculations** <br> `S = (w L²) / (8 T)` <br> (Catenary/Parabola) | **~10** | Span length (L), Weight per unit length (w), Tension (T), Temperature, Ice/wind loading. | **Sag** in conductor, **Tension** variation with temperature, **Stringing chart** usage. | Q12, Q19, Q46, Q49, Q50, Q77, Q127 |
| **4** | **String Efficiency (Insulators)** <br> `η_string = (Voltage across string) / (n × Voltage across lowest disc) × 100` <br> Voltage distribution: `V2 = V1 + (Cg/C) * V1` | **~14** | Number of discs, Capacitance (self & earth/pin), Voltage across lowest disc, Total string voltage. | **String efficiency** , **Voltage distribution** across discs, **Guard ring** purpose. | Q11, Q33, Q47, Q71, Q78, Q81, Q94, Q103, Q104, Q128, Q136, Q145, Q168, Q186, Q199, Q206 |
| **5** | **Inductance & Capacitance of Lines** <br> `L = 0.2 ln(GMD/GMR) mH/km` <br> `C = (2πε₀) / ln(GMD/GMR) F/m` <br> GMR for bundled conductors: `(r' * d12 * d13 * d14)^(1/4)` | **~12** | Conductor radius, Spacing (GMD), Bundle details, Line length. | **Inductance per phase/km** , **Capacitance per phase/km** , **GMR/GMD** , **Effect of bundling/transposition**. | Q13, Q21, Q55, Q75, Q76, Q108, Q110, Q137, Q139, Q150, Q155, Q161, Q180, Q200 |
| **6** | **Ferranti Effect** <br> `V_r > V_s` (No-load/light load) <br> Compensated by **Shunt Reactor** | **~8** | Line length, Voltage, ABCD parameters, Load condition. | **Ferranti effect** identification, **Compensation method** , **Receiving end voltage** calculation. | Q25, Q83, Q144, Q177, Q181, Q195, Q208 |
| **7** | **Surge Impedance & SIL** <br> `Z_c = √(L/C)` <br> `SIL = V_L² / Z_c` <br> `SIL ∝ V²` | **~8** | Inductance, Capacitance, Line voltage. | **Surge impedance** , **Surge Impedance Loading (SIL)** , **Effect of compensation** on SIL. | Q23, Q80, Q93, Q107, Q125, Q197, Q212 |
| **8** | **Per Unit System** <br> `Z_pu(new) = Z_pu(old) × (V_base(old) / V_base(new))² × (MVA_base(new) / MVA_base(old))` | **~12** | Old & new base kV, MVA, Old per unit impedance. | **New per unit impedance** , **Base impedance** , **Actual impedance**. | Q1-Q13 (Module-2) |
| **9** | **Symmetrical Components** <br> `I_a0 = (1/3)(I_a + I_b + I_c)` <br> `I_a1 = (1/3)(I_a + aI_b + a²I_c)` <br> `I_a2 = (1/3)(I_a + a²I_b + aI_c)` <br> `a = 1∠120°` | **~12** | Line currents, Sequence impedances (Z₁, Z₂, Z₀). | **Zero/Positive/Negative sequence currents** , **Relation between sequence impedances** for different equipment. | Q1-Q19 (Module-2) |
| **10** | **Fault Analysis (Symmetrical & Unsymmetrical)** <br> `I_f = E / Z₁` (3-phase) <br> `I_f = 3E / (Z₁ + Z₂ + Z₀ + 3Z_n)` (LG) <br> `I_f = √3 E / (Z₁ + Z₂)` (LL) <br> `SC MVA = Base MVA / Z_pu` | **~14** | Sequence impedances, Neutral grounding impedance, Generator/Transformer ratings. | **Fault current** (LG, LL, LLG, 3-phase), **Short circuit MVA** , **Sequence voltage/current relations** at fault. | Q1-Q23 (Module-2 Fault) |
| **11** | **Power System Stability (Swing Equation)** <br> `M * (d²δ/dt²) = P_a` <br> `H = KE / G` <br> `α = P_a / M` <br> `M = (G H) / (180 f)` | **~14** | Inertia constant (H), Rating (G), Frequency, Mechanical/Electrical power. | **Kinetic energy stored** , **Angular acceleration** , **Swing equation** , **Equal area criterion** application. | Q1-Q45 (Module-2 Stability) |
| **12** | **Load Flow Analysis (Newton-Raphson, Gauss-Seidel)** <br> `ΔP = J₁₁ Δδ + J₁₂ ΔV` <br> `ΔQ = J₂₁ Δδ + J₂₂ ΔV` <br> `Y_bus` building | **~14** | Bus types (Slack, PV, PQ), Line admittances, Power injections. | **Jacobian matrix size** , **Y_bus** elements, **Bus classification** , **Convergence** of methods. | Q1-Q38 (Module-2 Load Flow) |
| **13** | **Economic Load Dispatch (ELD)** <br> `IC = dF/dP` <br> `IC₁ = IC₂ = ... = λ` (for economic operation) <br> `F(P) = aP² + bP + c` | **~12** | Cost functions of generators, Total load demand. | **Incremental Fuel Cost** , **Economic allocation** of load between units, **Load factor** , **Diversity factor**. | Q1-Q74 (Module-3) |
| **14** | **Protection (Relays, Circuit Breakers)** <br> `Plug Setting Multiplier = (Fault current) / (CT ratio × Relay Setting)` <br> `Breaking Capacity (MVA) = √3 V_L I_br` <br> `Making Capacity = 2.55 × Breaking Capacity` | **~16** | CT ratio, Relay setting, Fault current, Voltage, MVA rating. | **PSM** , **Breaking/Making current** , **Type of relay** for specific application, **CT ratio** for differential protection. | Q1-Q123 (Module-3 Protection) |
| **15** | **Cable Parameters (Capacitance & Insulation Resistance)** <br> `C_ph = 2 C_ab` (3-core) <br> `R_ins ∝ 1/length` <br> `Dielectric stress E ∝ 1/x` <br> `E_max / E_min = D/d` | **~8** | Cable length, Core diameter, Overall diameter, Capacitance between cores. | **Capacitance per phase** , **Insulation resistance** , **Dielectric stress** ratio, **Grading** purpose. | Q61, Q62, Q63, Q69, Q82, Q88, Q120, Q126, Q157, Q160, Q175, Q211 |

---

## 🧭 The 5-Question Decision Flowchart

| Step | Question to Ask | If YES → | If NO → |
| :---: | :-------------------------------------------------------------- | :--- | :--- |
| **1** | **Is it about a transmission/distribution line?** | Go to Step 2 | Go to Step 3 |
| **2** | **Is the line length > 250 km?** | **Long Line**: Use hyperbolic functions (cosh, sinh) or ABCD parameters | **Short/Medium Line**: Use Nominal π/T or Short line model |
| **3** | **Is it about a cable or insulator?** | **Cable**: Use capacitance/insulation formulas <br> **Insulator**: Use string efficiency formulas | Go to Step 4 |
| **4** | **Is it about a fault or protection?** | **Fault**: Use sequence networks & fault current formulas <br> **Protection**: Use relay/CT formulas | Go to Step 5 |
| **5** | **Is it about system operation (load flow, stability, ELD)?** | **Load Flow**: Use Y_bus, Jacobian <br> **Stability**: Use swing equation, equal area <br> **ELD**: Use incremental cost | It's a **theory/definition** question. |

---

## 🔑 How to Identify the Topic from the Question

| Keywords in Question | Topic | Go-to Formula |
| :--- | :--- | :--- |
| "ABCD", "sending end", "receiving end", "nominal π", "nominal T" | **ABCD Parameters** | Matrix multiplication, π/T model formulas |
| "Corona", "corona loss", "critical voltage", "disruptive" | **Corona** | P_c ∝ (V - V_d)², P_c ∝ (f+25) |
| "Sag", "tension", "span", "stringing chart" | **Sag & Tension** | S = wL²/(8T) |
| "String efficiency", "insulator disc", "voltage distribution" | **Insulators** | η_string = V_string / (n × V_lowest) |
| "Inductance", "capacitance", "GMD", "GMR", "bundled" | **Line Parameters** | L = 0.2 ln(GMD/GMR), C = 2πε₀ / ln(GMD/GMR) |
| "Ferranti effect", "no-load", "receiving end voltage" | **Ferranti Effect** | V_r > V_s, Shunt reactor compensation |
| "Surge impedance", "SIL", "natural loading" | **Surge Impedance & SIL** | Z_c = √(L/C), SIL = V²/Z_c |
| "Per unit", "base kV", "base MVA" | **Per Unit System** | Z_pu(new) formula |
| "Symmetrical components", "sequence currents", "operator a" | **Symmetrical Components** | I_a0, I_a1, I_a2 formulas |
| "Fault current", "LG fault", "LL fault", "short circuit MVA" | **Fault Analysis** | Sequence network connections |
| "Stability", "swing equation", "inertia constant", "equal area" | **Power System Stability** | M(d²δ/dt²) = P_a, H = KE/G |
| "Load flow", "Newton-Raphson", "Gauss-Seidel", "Y_bus", "Jacobian" | **Load Flow Analysis** | Y_bus building, Jacobian matrix |
| "Incremental cost", "economic load dispatch", "load factor" | **ELD** | IC₁ = IC₂ = λ |

---

## 📝 The Ultimate "What Happens When..." Cheat-Sheet

| Change Made | Topic | Effect |
| :--- | :--- | :--- |
| **↑ Voltage (V)** | Corona Loss | ↑ Increases (∝ V²) |
| **↑ Frequency (f)** | Corona Loss | ↑ Increases (∝ f+25) |
| **↑ Conductor Radius (r)** | Corona Loss | ↓ Decreases |
| **↑ Span Length (L)** | Sag | ↑ Increases (∝ L²) |
| **↑ Tension (T)** | Sag | ↓ Decreases (∝ 1/T) |
| **↑ Ice/Wind Loading** | Sag | ↑ Increases (weight increases) |
| **↑ Number of Discs (n)** | String Efficiency | ↓ Decreases (usually) |
| **↑ Pin-to-Earth Capacitance** | String Efficiency | ↓ Decreases |
| **↑ Line Length** | ABCD - A | ↓ Decreases |
| **↑ Line Length** | ABCD - B | ↑ Increases |
| **↑ Line Length** | Ferranti Effect | ↑ Increases |
| **↑ Series Capacitor Compensation** | SIL | ↑ Increases (SIL ∝ 1/√(L/C)) |
| **↑ Shunt Reactor** | Ferranti Effect | ↓ Decreases (compensates) |
| **↑ Shunt Capacitor** | Voltage Profile | ↑ Improves (provides reactive power) |
| **↑ Base MVA** | Per Unit Z | ↑ Increases |
| **↑ Base kV** | Per Unit Z | ↓ Decreases (∝ 1/V²) |
| **↑ Fault Current** | Circuit Breaker Rating | ↑ Must be higher |
| **↑ Load Demand** | Frequency | ↓ Decreases |
| **↑ Generation** | Frequency | ↑ Increases |

---

## 🎯 Top 15 Concepts to Score >90%

| Rank | Concept | Weightage | Key Formulas |
| :---: | :-------------------------------------------------------------- | :---: | :--- |
| **1** | **ABCD Parameters** | ~8% | Short/Medium/Long line models |
| **2** | **Corona Loss & Critical Voltage** | ~6% | P_c ∝ (V-V_d)², P_c ∝ (f+25) |
| **3** | **String Efficiency (Insulators)** | ~6% | η_string, Voltage distribution |
| **4** | **Inductance & Capacitance of Lines** | ~5% | L = 0.2 ln(GMD/GMR), C formula |
| **5** | **Per Unit System** | ~5% | Z_pu(new) formula |
| **6** | **Symmetrical Components** | ~5% | I_a0, I_a1, I_a2 formulas |
| **7** | **Fault Analysis** | ~6% | I_f for LG, LL, LLG, 3-Φ |
| **8** | **Power System Stability** | ~6% | Swing equation, H = KE/G |
| **9** | **Load Flow Analysis** | ~6% | Y_bus, Jacobian matrix size |
| **10** | **ELD (Economic Load Dispatch)** | ~5% | IC₁ = IC₂ = λ |
| **11** | **Protection (Relays & CBs)** | ~7% | PSM, Breaking/Making Capacity |
| **12** | **Sag & Tension** | ~4% | S = wL²/(8T) |
| **13** | **Ferranti Effect** | ~3% | V_r > V_s, Shunt reactor compensation |
| **14** | **Surge Impedance & SIL** | ~3% | Z_c = √(L/C), SIL = V²/Z_c |
| **15** | **Cable Parameters** | ~3% | C_ph, R_ins, Dielectric stress |

---

## 📌 Quick Reference Card (Exam Day)

| Concept | Formula | Quick Tip |
| :--- | :--- | :--- |
| **Short Line ABCD** | `[1 Z; 0 1]` | B = Z, A = D = 1 |
| **Medium π - A** | `1 + YZ/2` | A and D are equal |
| **Medium π - B** | `Z` | B is same as short line |
| **Medium π - C** | `Y(1 + YZ/4)` | C is modified |
| **Medium T - B** | `Z(1 + YZ/4)` | B is modified |
| **Medium T - C** | `Y` | C is same as short line |
| **Corona Loss** | `P_c ∝ (V - V_d)²` | V_d = critical voltage |
| **Sag** | `S = wL²/(8T)` | Use parabola for small spans |
| **String Efficiency** | `η = V_string / (n × V_lowest)` | Low η → poor voltage distribution |
| **Inductance** | `L = 0.2 ln(GMD/GMR) mH/km` | GMR = r' for solid conductor |
| **Capacitance** | `C = (2πε₀) / ln(GMD/GMR) F/m` | GMR = r (actual radius) |
| **Per Unit Z** | `Z_pu(new) = Z_pu(old) × (V_old/V_new)² × (MVA_new/MVA_old)` | |
| **LG Fault Current** | `I_f = 3E / (Z₁ + Z₂ + Z₀ + 3Z_n)` | Sequence networks in series |
| **LL Fault Current** | `I_f = √3E / (Z₁ + Z₂)` | Z₀ not involved |
| **3-Φ Fault Current** | `I_f = E / Z₁` | Only positive sequence |
| **Swing Equation** | `M(d²δ/dt²) = P_m - P_e` | M = GH/(180f) |
| **SIL** | `SIL = V_L² / Z_c` | At SIL, V_r = V_s |
| **Ferranti Effect** | `V_r > V_s` at no-load | Compensate with shunt reactor |
| **PSM** | `PSM = I_f / (CT ratio × Relay Setting)` | |
| **Breaking Capacity** | `BC (MVA) = √3 V_L I_br` | |
| **Making Capacity** | `MC = 2.55 × BC (Current)` | |

---

## ✅ Step-by-Step Problem Solving Approach

1. **Read the question** → Identify the topic using keywords.
2. **Follow the Decision Flowchart** → Decide which formula family to use.
3. **Write down given values** → Convert to per unit if needed.
4. **Pick the relevant formula** → Apply the formula.
5. **Solve and verify** → Check units and magnitude.

---

# 📝 FULL PYQ ANALYSIS — All 549 Power Systems Questions (Concept through PYQ)

> Source: Study_Material__GTD_PYQs_2026_05_26_4_Power_Systems_PDF.pdf (OHM Institute — GENCO/TRANSCO/DISCOMs)
> Every question: answer + options, the concept it teaches, and how the examiner twists it.

**Legend:** Q = question · Ans = correct option · Concept = new term/principle · Twist = examiner variation → new answer

## Unit 1: Power System-1 — Transmission & Distribution (214 Qs)
OHM Institute PYQs (GENCO/TRANSCO/DISCOMs) — Q1–Q214

**Q1 (EPDCL-10):** Maximum permissible operating temperature of class-E insulating material
(a) 130°C (b) 180°C (c) 120°C (d) 105°C
**Ans: (c)** — Class E limit is 120°C (A-105, B-130, C-180, F-155).
**Concept:** Insulation class temperature ratings (A105/B130/C180/E120/F155).
**Twist:** class-B → 130°C; class-A → 105°C.

**Q2 (EPDCL-10):** Distributed parameter models for transmission lines must be considered if line is
(a) <100 km (b) >100 to <150 km (c) <50 km (d) >250 km
**Ans: (d)** — Distributed model needed for long lines (>250 km).
**Concept:** Line classification by length: short <80, medium 80–250, long >250 km.
**Twist:** 500 Hz excitation on 50 km line → electrically long (see Q89); medium line → nominal π/T lumped model.

**Q3 (EPDCL-10):** Undesirable effects of corona
(a) Power loss (b) Harmonic currents (c) Radio interference (d) All 1, 2 and 3
**Ans: (d)** — Corona causes power loss, harmonics and radio interference.
**Concept:** Corona discharge side effects.
**Twist:** corona's one advantage → reduces lightning surge magnitude (Q109).

**Q4 (EPDCL-10):** Important requirements of a good distribution system
(a) Reliability (b) Proper voltage (c) Both (a) and (b) (d) Feeders
**Ans: (c)** — Good distribution needs proper voltage, availability on demand, reliability.
**Concept:** Distribution system design requirements.
**Twist:** design criterion for radial distributor size → voltage drop (Q87).

**Q5 (SSC-JE-10):** Ratio of puncture voltage to flashover voltage of an insulator
(a) Equal to one (b) Lower than one (c) Zero (d) Greater than one
**Ans: (d)** — Safety factor = puncture/flashover > 1.
**Concept:** Insulator safety factor.
**Twist:** if ratio < 1 → flashover occurs before puncture damage is wrong; puncture must never happen first.

**Q6 (SSC-JE-10):** The earth's potential is taken as
(a) Infinite (b) Supply voltage (c) 1 volt (d) Zero
**Ans: (d)** — Earth area → ∞, so R = ρl/A ≈ 0, potential 0 V.
**Concept:** Earth as zero-potential reference.
**Twist:** earth continuity conductor connects equipment body to this reference (Q116).

**Q7 (SSC-JE-10):** Advantage of transmitting power at high voltage
(a) Current small (b) Power loss less (c) Voltage drop less (d) All the above
**Ans: (d)** — Higher V → lower I → lower I²R loss and IR drop.
**Concept:** P=√3VI; loss ∝ 1/V².
**Twist:** not an advantage → corona loss increases with V (Q171); conductor size ∝ 1/V² (Q121).

**Q8 (SSC-JE-10):** Skin effect exists only in
(a) LV dc overhead (b) HV dc overhead (c) Cable carrying dc (d) AC transmission
**Ans: (d)** — Skin effect needs time-varying flux, only in AC.
**Concept:** Skin effect = AC phenomenon.
**Twist:** skin effect raises effective AC resistance with frequency (Q56); DC cables carry more current (Q85).

**Q9 (SSC-JE-10):** Voltage drop is the main consideration while designing a
(a) Feeder (b) Distributor (c) Service main (d) All
**Ans: (b)** — Distributor design is governed by voltage drop.
**Concept:** Feeder (current-carrying, no tapping) vs distributor (voltage-drop-limited).
**Twist:** radial distributor size criterion → voltage drop (Q87); feeder → current density.

**Q10 (SSC-JE-10):** Distribution transformers designed for max efficiency nearly at
(a) 100% of full load (b) 50% of full load (c) 25% of full load (d) 10% of full load
**Ans: (b)** (best match) — Max η at ~70–75% of full load; nearest option 50%.
**Concept:** Distribution transformer load factor at max efficiency (options lack 70-75%).
**Twist:** power transformer → max η at/near full load (100%).

**Q11 (SSC-JE-11):** In suspension insulator, the potential drop is
(a) Maximum across the lower disc (b) Maximum across the topmost disc (c) Max at midpoint disc (d) Uniformly distributed
**Ans: (a)** — Potential drop is maximum across the lowest disc.
**Concept:** Non-uniform distribution due to shunt capacitance to earth.
**Twist:** pin-to-earth capacitance → lower discs stressed most; guard ring equalizes (Q81).

**Q12 (APGenco-12):** Stringing chart is useful for
(a) Design of tower (b) Design of insulator string (c) Finding the sag in the conductor (d) Distance between towers
**Ans: (c)** — Stringing chart = graph of sag/tension vs temperature.
**Concept:** Stringing chart → sag & tension vs temp.
**Twist:** also used to compute erection tension at any temperature (Q19, Q127).

**Q13 (APGenco-12):** The self GMD method is used to evaluate
(a) Inductance (b) Capacitance (c) Inductance and capacitance (d) Tower distance
**Ans: (a)** — Self-GMD computes inductance only (not capacitance).
**Concept:** GMR/self-GMD in L = 0.2 ln(GMD/GMR).
**Twist:** capacitance uses conductor radius, not GMR; mutual-GMD for two-wire spacing.

**Q14 (APGenco-12):** Velocity of travelling wave through a cable of relative permittivity 36
(a) 3×10⁸ (b) 2×10⁸ (c) 0.5×10⁸ (d) 10⁸ m/s
**Ans: (c)** — v = 3×10⁸/√εr = 3×10⁸/√36 = 0.5×10⁸ m/s.
**Concept:** v = c/√(μεr); εr slows wave in cables.
**Twist:** overhead (εr≈1) → ~3×10⁸; coaxial v=1/√(LC) (Q174).

**Q15 (APGenco-12):** Coefficient of reflection for current wave
(a) 1 (b) 2 (c) –1 (d) 0
**Ans: (a)/(c)** — ρI = (R0–RL)/(R0+RL), varies from –1 to +1 depending on termination.
**Concept:** Reflection coefficients for current and voltage.
**Twist:** open end → current reflection –1 (voltage +1); short end → current +1, voltage –1.

**Q16 (APGenco-12):** ABCD: A=D=0.8∠1°, B=170∠85°, C=0.002∠90.4°, Vs=400 kV; Vr at no load
(a) 400 kV (b) 500 kV (c) 320 kV (d) 417 kV
**Ans: (b)** — No-load Vr = Vs/A = 400/0.8 = 500 kV (Ferranti rise).
**Concept:** Vr(nl) = Vs/A at I_r=0.
**Twist:** A=0.5 → Vr = 2Vs (Q205, 1600 kV from 800 kV).

**Q17 (APGenco-12):** Bundled conductors used in EHV primarily to reduce
(a) Surge impedance (b) I²R losses (c) Voltage drop (d) Corona loss
**Ans: (d)** — Bundling primarily cuts corona loss and radio interference.
**Concept:** Bundling ↑ GMR → ↓ voltage gradient → ↓ corona.
**Twist:** secondary effect → surge impedance falls (Q165 says primary corona, Q23/SIL uses Zc).

**Q18 (Transco-SE-12):** Rule 77 of Indian Electricity Rules (1956) for overhead lines gives
(a) Materials and strength (b) Max stress & factor of safety (c) Earthing (d) Clearance above ground of lowest conductor
**Ans: (d)** — Rule 77 → ground clearance of lowest conductor.
**Concept:** IE Rules clearance tables.
**Twist:** 6.3 m clearance corresponds to 110–165 kV range (Q96).

**Q19 (Transco-SE-12):** Stringing charts are used to calculate
(a) String efficiency (b) ABCD parameters (c) Corona (d) Tension and sag at any temperature
**Ans: (d)** — Sag/tension vs temperature.
**Concept:** Stringing chart for sag-tension at temp.
**Twist:** sag independent of tower height (Q49).

**Q20 (Transco-SE-12):** Due to proximity effect, the effective internal reactance of the conductor
(a) Decreases (b) Increases (c) Does not change (d) Becomes infinity
**Ans: (a)** — Proximity effect redistributes current, lowering effective internal reactance.
**Concept:** Proximity effect (neighbouring conductors) vs skin effect.
**Twist:** skin effect increases AC resistance with frequency (Q56); proximity increases resistance too.

**Q21 (Transco-12):** Inductance of single-phase two-wire line per km doubles when distance between wires is
(a) Doubled (b) Increased fourfold (c) Increased as square of original (d) Radius doubled
**Ans: (c)** — L ∝ ln(d/r'); doubling L ⇒ ln(d2/r')=2ln(d1/r') ⇒ d2=d1².
**Concept:** L = 0.4 ln(GMD/GMR) mH/km.
**Twist:** GMR ↑ (bundling) → inductance ↓; GMD ↑ → L ↑ (logarithmic, not linear).

**Q22 (Transco-12):** 210 km line has certain ABCD; if length made 100 km
(a) A increases and B decreases (b) A and B both decrease (c) A and B both increase (d) A decreases and B increases
**Ans: (a)** — Shorter line: A & D increase, B & C decrease.
**Concept:** ABCD vs length (A→1, B→0 as length→0).
**Twist:** longer line → A decreases, B increases (Q100 200→60 km same relation).

**Q23 (Transco-12):** Surge impedance loading of a line is proportional to
(a) V² (b) V (c) √V (d) V³
**Ans: (a)** — SIL = V²/Zc.
**Concept:** SIL = V²/Zc.
**Twist:** series compensation reduces effective reactance → SIL ↑ by 1/(1–K) (Q212).

**Q24 (Transco-12):** Under no load, current in a transmission line is due to
(a) Corona (b) Capacitance of the line (c) Spinning reserve (d) Back flow from earth
**Ans: (b)** — No-load current = charging current from line capacitance.
**Concept:** Ferranti/charging current.
**Twist:** this charging current causes Vr>Vs at light load (Ferranti, Q25).

**Q25 (Transco-12):** No-load receiving end voltage more than sending end voltage is called
(a) Ferranti effect (b) Skin effect (c) Proximity effect (d) Corona
**Ans: (a)** — Ferranti effect: Vr>Vs at light/no load on long lines.
**Concept:** Ferranti effect.
**Twist:** neutralize with shunt reactor (Q181, Q177); on full load at lag pf effect vanishes.

**Q26 (Transco-12):** Corona loss reduced by hollow conductor because
(a) Current density reduced (b) Eddy current eliminated (c) Radius increased for same cross-section (d) Better ventilation
**Ans: (c)** — Hollow gives larger radius for same area → lower gradient → less corona.
**Concept:** Hollow conductors ↑ effective radius.
**Twist:** hollow also cools conductor (ventilation) but the corona reason is radius (Q148).

**Q27 (Transco-12):** Valve elements of non-linear resistance in valve-type lightning arrester are
(a) Porcelain (b) Stainless steel (c) Zeolite (d) Silicon carbide
**Ans: (d)** — Valve blocks are silicon carbide (SiC).
**Concept:** SiC valve arrester.
**Twist:** modern ZnO gapless arresters replace SiC (better protective margin).

**Q28 (Transco-12):** Lightning arrester discharging 65,000–100,000 A
(a) Station type (b) Line type (c) Distribution type (d) Rod gaps
**Ans: (b)** — Line type: 65–100 kA; station <100 kA; distribution <65 kA.
**Concept:** LA discharge current ratings.
**Twist:** station type <100 kA handles substation duty; distribution <65 kA for feeders.

**Q29 (Transco-12):** Used to reduce tower footing resistance
(a) Ground rods (b) Counterpoise (c) Horn gap (d) Surge absorber
**Ans: (a)** — Ground rods reduce tower footing resistance.
**Concept:** Tower earthing.
**Twist:** counterpoise improves surge performance of high-resistivity soil.

**Q30 (Transco-12):** Size of aluminium pipe for rigid bus at 66 kV
(a) 40 mm (b) 65 mm (c) 80 mm (d) 100 mm
**Ans: (b)** — 66 kV → 65 mm dia pipe (33→40, 132/220→80, 400→100).
**Concept:** Rigid busbar diameter vs voltage.
**Twist:** 400 kV → 100 mm; 33 kV → 40 mm.

**Q31 (Transco-12):** Breaker maintenance facility provided in
(a) Double busbar (b) Single busbar (c) Main and transfer bus scheme (d) All
**Ans: (c)** — Main & transfer bus allows breaker maintenance without outage.
**Concept:** Substation bus schemes.
**Twist:** double bus gives flexibility/reliability but transfer bus is for maintenance.

**Q32 (Transco-12):** For low voltage up to 11 kV, preferred insulator
(a) Pin type (b) Suspension type (c) Strain type (d) None
**Ans: (a)** — Pin type for up to ~33 kV.
**Concept:** Insulator types by voltage.
**Twist:** suspension/strain for higher voltage & long spans; dead-end → strain type (Q72).

**Q33 (Transco-12):** 5-disc string, pin-earth C = 1/6 of mutual; voltage across middle unit as % of applied
(a) 11.15 (b) 13.1 (c) 17.1 (d) 34.85
**Ans: (c)** — Solve iterative voltage distribution with m=6; middle unit ≈17.1%.
**Concept:** m = Cg/C, iterative string voltage distribution.
**Twist:** guard ring/grading makes distribution uniform → each unit ~20% (Q81).

**Q34 (Transco-12):** Train 600 A, 8 km, substations 575 V and 590 V, track 0.04 Ω/km go+return; min potential point from 575 V end
(a) 6 km (b) 3.67 km (c) 3.97 km (d) 3.77 km
**Ans: (b)** — dV_P/dx=0 ⇒ x = 22.01/6 = 3.67 km.
**Concept:** DC traction fed at both ends — minimum potential location.
**Twist:** equal end voltages → min potential at centre (4 km).

**Q35 (Transco-12):** Most economical AC distribution system
(a) 2-ph 4-wire (b) 2-ph 3-wire (c) 3-ph 4-wire (d) 3-ph 3-wire
**Ans: (d)** — AC 3-phase 3-wire is most economical.
**Concept:** conductor volume vs system.
**Twist:** 3-ph 4-wire needed for single-phase loads (lighting) → (b) secondary distribution (Q52).

**Q36 (Transco-12):** For distributor, if voltage rating increased 'n' times, conductor size reduces to
(a) 1/n (b) 1/n² (c) 1/n⁴ (d) 1/√n
**Ans: (b)** — Area A ∝ 1/V² (constant power, constant loss).
**Concept:** conductor volume ∝ 1/V².
**Twist:** same saving for transmission lines (Q121, Q54); 200→400 V saves 75% (Q102).

**Q37 (Transco-12):** ACSR stands for
(a) Aluminium Copper Steel Reinforced (b) Aluminium Copper Stranded Reinforced (c) Aluminium Conductor Steel Reinforced (d) Aluminium Conductor Stranded Reinforced
**Ans: (c)** — Aluminium Conductor Steel Reinforced.
**Concept:** ACSR construction.
**Twist:** steel core → tensile strength (Q170), aluminium carries current.

**Q38 (Transco-12):** Total connected load per sub-circuit in house wiring
(a) 400 W (b) 800 W (c) 1500 W (d) 2000 W
**Ans: (b)** — Max 800 W per light/fan sub-circuit.
**Concept:** IE wiring sub-circuit limits.
**Twist:** power sub-circuit loads are higher (separate).

**Q39 (Transco-12):** Rated voltage of a 3-phase power system is given as
(a) RMS phase (b) Peak phase (c) RMS line-to-line (d) Peak line-to-line
**Ans: (c)** — Rating = rms line-to-line voltage.
**Concept:** system nominal voltage convention.
**Twist:** string/phase voltage = V_L/√3 (Q145); cable test uses peak (Q126).

**Q40 (Transco-12):** Short/medium/long line concept primarily based on
(a) Nominal voltage (b) Physical length (c) Wavelength (d) Power transmitted
**Ans: (c)** — Based on wavelength/electrical length.
**Concept:** line length vs λ (=6000 km at 50 Hz).
**Twist:** 50 km at 500 Hz is electrically 500 km → long line (Q89).

**Q41 (Transco-12):** Fixed complex power flow, sending end V; real power loss ∝
(a) V (b) V² (c) 1/V² (d) 1/V
**Ans: (c)** — P_loss = S²R/V² ⇒ ∝ 1/V².
**Concept:** transmission loss ∝ 1/V².
**Twist:** raising V 2× → loss ¼ (Q196).

**Q42 (Transco-12):** Buses 1,2 via j5Ω; V1=100∠30°, V2=100∠0°; P and Q from bus 1
(a) 1000 W, 268 VAR (b) 276.9 W, –134 VAR (c) 276.9 W, –56.7 VAR (d) –276.9 W, 56.7 VAR
**Ans: (a)** — P=V1V2/X sinδ=1000 W; Q=V1²/X−V1V2/X cosδ=268 VAR.
**Concept:** two-bus power flow equations.
**Twist:** δ→0 ⇒ Q≈0 (reactive flows from high |V| to low |V|, Q213).

**Q43 (Transco-12):** HVDC link figure: power flows A→B; voltages VAB, VCD with I>0
(a) VAB<0, VCD<0, VAB>VCD (b) VAB>0, VCD>0, VAB<VCD (c) VAB>0, VCD>0, VAB>VCD (d) VAB>0, VCD<0, VAB>VCD
**Ans: (c)** — DC power flows high→low potential; rectifier side higher than inverter side.
**Concept:** HVDC power transfer direction.
**Twist:** to reverse flow, reverse converter voltage (current can't reverse easily).

**Q44 (APSPDCL-12):** Number of strands on a 3-layer cable
(a) 24 (b) 7 (c) 37 (d) 19
**Ans: (d)** — N = 3n²−3n+1 = 19 for n=3.
**Concept:** stranded conductor strand count.
**Twist:** 1 layer → 7; 3-layer cable overall diameter (2x−1)d (Q164).

**Q45 (APSPDCL-12):** ZL/2 in the T-equivalent shown can be represented as
(a) (A–1)C (b) (A–1)B (c) (A–1)/C (d) B/(A–1)
**Ans: (c)** — In T-network A=1+YZ/2, C=Y ⇒ Z/2=(A–1)/C.
**Concept:** nominal T ABCD relations.
**Twist:** π-model B=Z, C=Y(1+YZ/4) (Q97, Q202).

**Q46 (APSPDCL-12):** Between 2 supports, due to sag the conductor takes shape of
(a) Parabola (b) Hyperbola (c) Catenary (d) Semi-circle
**Ans: (c)** — Catenary (parabola for spans <1000 ft).
**Concept:** sag curve shape.
**Twist:** short span → parabola; sag formula S=wL²/8T uses parabolic approximation (Q77).

**Q47 (APSPDCL-12):** In suspension insulator, potential drop maximum across
(a) Top disc (b) Centre disc (c) Lowest disc (d) Depends on number of discs
**Ans: (c)** — Maximum across the lowest (line) disc.
**Concept:** string voltage distribution.
**Twist:** highest stress on bottom disc → corona/grading there (Q103, Q199).

**Q48 (APSPDCL-12):** Chances of corona maximum during
(a) Dry weather (b) Humid weather (c) Winter (d) Hot summer
**Ans: (b)** — Humidity/wet weather lowers disruptive critical voltage → more corona.
**Concept:** corona depends on air density/conditions.
**Twist:** moisture ↓ V_d (Q147); winter (high density) lowers Vd too.

**Q49 (HMWS-12):** Sag 2.5 m at span 250 m; tower height increased 25% → sag
(a) Reduced 25% (b) Increased 25% (c) Reduced 12.5% (d) Increased 12.5%
**Ans: (—)** — Sag is independent of tower height (S=wL²/8T); key marked (*), no option.
**Concept:** Sag depends on span, weight, tension — not support height.
**Twist:** increasing span does increase sag (S∝L²); ice adds weight → more sag (Q51).

**Q50 (HMWS-12):** Variation of tension T with atmospheric temperature t (graph, curves I–IV)
(a) Curve I (b) Curve II (c) Curve III (d) Curve IV
**Ans: (a)** — Tension is maximum at low temperature (contraction), falls as temp rises.
**Concept:** sag-tension vs temperature.
**Twist:** sag is inverse of tension → max sag in summer; stringing chart plots this (Q19).

**Q51 (HMWS-12):** Effect of ice deposition on conductor
(a) Increased skin effect (b) Reduced corona losses (c) Increased weight (d) Reduced sag
**Ans: (c)** — Ice adds weight to conductor.
**Concept:** ice/wind loading on lines.
**Twist:** increased weight → increased sag & tension; also larger effective radius → less corona.

**Q52 (HMWS-12):** 3-phase, 4-wire system commonly used for
(a) Primary distribution (b) Secondary distribution (c) Primary transmission (d) Secondary transmission
**Ans: (b)** — 3-ph 4-wire serves single-phase loads in secondary distribution.
**Concept:** distribution voltage systems.
**Twist:** 3-ph 3-wire for primary distribution/transmission.

**Q53 (HMWS-12):** Material NOT used for transmission/distribution of power
(a) Tungsten (b) Copper (c) Aluminium (d) Cadmium copper
**Ans: (a)** — Tungsten is for filaments, not conductors.
**Concept:** conductor materials.
**Twist:** cadmium copper = high-strength alloy for overhead; Al replaces Cu on weight basis.

**Q54 (HMWS-12):** In a transmission system, weight of copper used ∝
(a) E² (b) E (c) 1/E² (d) 1/E
**Ans: (c)** — For constant loss, conductor volume ∝ 1/V².
**Concept:** material economy vs voltage.
**Twist:** doubling voltage → ¼ copper (Q102, Q121).

**Q55 (HMWS-12):** Bundling of conductors done primarily to
(a) Reduce reactance (b) Increase reactance (c) Increase radio interference (d) Reduce radio interference
**Ans: (d)** — Bundling reduces corona → reduces radio interference.
**Concept:** bundling → GMR ↑, gradient ↓, corona ↓, RI ↓.
**Twist:** also reduces line reactance (secondary) → higher SIL (Q23).

**Q56 (HMWS-12):** Increase in frequency of transmission line causes
(a) No change in resistance (b) Increase in line resistance (c) Decrease in line resistance (d) Decrease in series reactance
**Ans: (b)** — Higher f → stronger skin effect → AC resistance increases.
**Concept:** f ↑ ⇒ R_ac ↑ (skin), X_L = 2πfL ↑ too.
**Twist:** corona loss ∝ (f+25) (Q167, Q185); dielectric loss ∝ f (Q123).

**Q57 (HMWS-12):** Power factor correction devices installed at
(a) Sending end (b) Near earthing point (c) Load end (d) Anywhere
**Ans: (c)** — Capacitors at load end minimize feeder losses & improve voltage profile.
**Concept:** shunt compensation placement.
**Twist:** series capacitor for line compensation (Q142); shunt reactor for Ferranti (Q181).

**Q58 (SSC-JE-12):** IE rules max allowable variation between declared and actual voltage at consumer premises
(a) ±4.5% (b) ±3% (c) ±3.5% (d) ±4%
**Ans: (d)** — Permissible variation ±4% (consumer); ±6% elsewhere.
**Concept:** IE voltage regulation limits.
**Twist:** at consumer terminals ±6% (Q111); ±12% in rural.

**Q59 (SSC-JE-12):** Resistance of insulations with temperature rise
(a) Increases rapidly (b) Increases slowly (c) Doesn't change (d) Decreases
**Ans: (d)** — Insulators have negative temperature coefficient.
**Concept:** insulation resistance vs temp.
**Twist:** metals (+ve temp coeff) behave opposite.

**Q60 (SSC-JE-13):** Small pockets of air in HV cable provide ___ permittivity, ___ electric field → breakdown initiated
(a) High, high (b) Low, low (c) Low, high (d) High, low
**Ans: (c)** — Air pockets: low εr, high stress concentration → partial discharge.
**Concept:** internal voids & dielectric breakdown.
**Twist:** this is why cables are degassed / gas-pressure or impregnated paper.

**Q61 (SSC-JE-13):** Capacitance between any two cores of 3-core cable (sheath earthed) = 3 µF; capacitance per phase
(a) 1.5 µF (b) 6 µF (c) 1 µF (d) None
**Ans: (b)** — C_ph = 2C_ab = 6 µF.
**Concept:** cable capacitance relation C_ph=2C_ab.
**Twist:** with 1 µF between cores → 2 µF/phase (Q69); capacitance ∝ length (Q74).

**Q62 (SSC-JE-13):** In insulated cable core d, overall D; ratio of max to min dielectric stress
(a) (D/d)^½ (b) (D/d)² (c) D/d (d) d/D
**Ans: (c)** — Emax/Emin = D/d.
**Concept:** E∝1/x in cable dielectric.
**Twist:** stress max at conductor surface, min at sheath (Q160).

**Q63 (SSC-JE-13):** 2 m sample insulation resistance 10 MΩ; 8 m sample of same cable
(a) 40 MΩ (b) 2.5 MΩ (c) 2 MΩ (d) 100 Hz
**Ans: (b)** — R ∝ 1/length ⇒ R = 10×(2/8) = 2.5 MΩ.
**Concept:** R_ins ∝ 1/length.
**Twist:** 10 km→1 MΩ, 50 km → 0.2 MΩ (Q82); 100 km → 0.1 MΩ (Q88).

**Q64 (EPDCL-14):** Characteristic impedance: series Z=0.1 Ω/unit, shunt Y=0.001 mho/unit
(a) 0.0001 (b) 0.01 (c) 100 (d) 10
**Ans: (d)** — Zc = √(z/y) = √(0.1/0.001) = 10 Ω.
**Concept:** Zc = √(L/C) = √(z/y).
**Twist:** overhead ~400 Ω, cable ~50 Ω (Q93, Q125); SIL=V²/Zc (Q23).

**Q65 (EPDCL-14):** Line 3% R, 5% X; % regulation at full load, 0.8 pf LEAD
(a) 8 (b) 5.4 (c) –0.6 (d) –2
**Ans: (c)** — %VR = %R cosφ − %X sinφ = 2.4 − 3 = −0.6%.
**Concept:** %VR = Rcosφ ± Xsinφ (lead −).
**Twist:** lag pf → + (2.4+3=5.4); zero regulation at leading pf φ=90°−θ (Q90, Q92).

**Q66 (EPDCL-14):** Single-phase short line j0.6Ω, resistive load 500 A at 400 V; sending end pf
(a) Unity (b) 0.8 lagging (c) 0.8 leading (d) 0.6 lagging
**Ans: (b)** — Z_s=R_L+jX, R_L=400/500=0.8; pf=0.8/√(0.8²+0.6²)=0.8 lag.
**Concept:** sending-end pf from load & line impedance.
**Twist:** line resistance equal reactance → pf lead 0.707 for zero reg (Q92).

**Q67 (EPDCL-14):** Short transmission line transmission parameters
(a) 1, Z, 0, 1 (b) 0, 1, 1, Z (c) Z, 0, 1, 1 (d) 1, 1, Z, 0
**Ans: (a)** — [A B; C D] = [1 Z; 0 1].
**Concept:** short line ABCD.
**Twist:** medium π: A=D=1+YZ/2, B=Z, C=Y(1+YZ/4) (Q97, Q202); end-condenser A=1+ZY (Q149).

**Q68 (EPDCL-14):** Electrical power transmission network will be
(a) Symmetrical but not reciprocal (b) Reciprocal but not symmetrical (c) Both symmetrical and reciprocal (d) Neither
**Ans: (c)** — Passive line network: A=D (symmetrical) and AD−BC=1 (reciprocal).
**Concept:** ABCD symmetry & reciprocity.
**Twist:** with transformer at one end → symmetry lost but still reciprocal.

**Q69 (EPDCL-14):** Three-core cable, C between two conductors (sheath earthed) = 1 µF; C per phase
(a) 0.33 (b) 3 (c) 0.5 (d) 2
**Ans: (d)** — C_ph = 2C_ab = 2 µF.
**Concept:** 3-core cable capacitance.
**Twist:** C between core and sheath gives different relation — careful with what is measured (Q61).

**Q70 (EPDCL-14):** Shunt capacitors used in distribution lines
(a) Provide reactive power compensation (b) Reduce line losses (c) Reduce voltage drop (d) Reduce sending end voltage
**Ans: (a)** — Shunt capacitor supplies reactive power, improves pf.
**Concept:** shunt capacitor compensation.
**Twist:** series capacitor ↑ power transfer capability (Q142); shunt reactor reduces Ferranti (Q181).

**Q71 (EPDCL-14):** 3-insulator string, lowest unit 10 kV, string efficiency 90%; total string voltage
(a) 3 kV (b) 27 kV (c) 30 kV (d) 9 kV
**Ans: (b)** — V_tot = η·n·V_bottom = 0.9×3×10 = 27 kV.
**Concept:** string efficiency η = V_string/(n·V_lowest).
**Twist:** 38 kV/4 discs/bottom 12 kV → 79.16% (Q78); 100 kV/5 discs/25 kV → 80% (Q186).

**Q72 (EPDCL-14):** Conductors dead-ended or direction change → insulators used
(a) Shackle type (b) Suspension type (c) Pin type (d) Strain type
**Ans: (d)** — Strain insulators at dead-ends/line turns.
**Concept:** insulator selection by mechanical duty.
**Twist:** LV distribution direction change → shackle type.

**Q73 (EPDCL-14):** Corona loss will increase with
(a) ↑ conductor size, ↓ frequency (b) ↓ conductor size, ↓ frequency (c) ↓ conductor size, ↑ frequency (d) ↑ size, ↑ frequency
**Ans: (c)** — Corona loss rises as conductor radius ↓ and frequency ↑ (loss ∝ f+25).
**Concept:** corona loss ∝ (f+25)(V−Vd)², ↓ with bigger conductor.
**Twist:** hollow/bundled conductor ↑ radius → ↓ corona (Q26, Q132).

**Q74 (EPDCL-14):** Charging reactance of 10 km line = 500 Ω; if length doubled
(a) 1000 (b) 500 (c) 2000 (d) 250
**Ans: (d)** — C ∝ length, X_C=1/(2πfC) → length doubled ⇒ X_C halved = 250 Ω.
**Concept:** charging reactance ∝ 1/length.
**Twist:** charging current ∝ length; longer line → more Ferranti (Q144).

**Q75 (EPDCL-14):** Inductance of a transmission line is minimum when
(a) GMD & GMR both high (b) GMD low & GMR high (c) GMD & GMR both low (d) GMD high & GMR low
**Ans: (b)** — L = 0.2 ln(GMD/GMR); minimum when ratio smallest.
**Concept:** L ∝ ln(GMD/GMR).
**Twist:** bundling ↑GMR → ↓L; transposition keeps GMD equal per phase (Q161).

**Q76 (APSPDCL-14):** 10 km single-phase two-wire line, spacing 1.5 m, diameter 1 cm; circuit inductance
(a) 50 mH (b) 45.3 mH (c) 19.6 mH (d) 23.8 mH
**Ans: (d)** — L = 0.4 ln(d/r') mH/km ×10 = 23.8 mH.
**Concept:** L_loop = 0.4 ln(GMD/GMR) mH/km.
**Twist:** 3-phase per-phase uses 0.2 ln(GMD/GMR); bundled GMR formula (Q137).

**Q77 (APSPDCL-14):** Span 220 m, conductor 700 kg/1000 m, max tension 1400 kg; max sag
(a) 3.02 m (b) 2.85 m (c) 2.45 m (d) 1.2 m
**Ans: (a)** — S = wL²/8T = 0.7×220²/(8×1400) = 3.02 m.
**Concept:** S = wL²/8T.
**Twist:** tension halved → sag doubles; ice+wind weight → combined w (Q51).

**Q78 (APSPDCL-14):** String potential 38 kV, 4 discs, lowest disc 12 kV; string efficiency
(a) 79.16% (b) 70% (c) 50% (d) 100%
**Ans: (a)** — η = 38/(4×12)×100 = 79.16%.
**Concept:** η = V_str/(n·V_lowest).
**Twist:** bottom disc 33.33% of total → η=75% (Q168); grading → η→100% (Q199).

**Q79 (APSPDCL-14):** Distribution transformer 11 kV/400 V (3-phase) usually
(a) Star-star (b) Delta-delta (c) Star-delta (d) Delta-star
**Ans: (d)** — Δ primary (11 kV), Y secondary (400 V) for neutral.
**Concept:** distribution transformer connection.
**Twist:** Δ-star provides 3rd-harmonic trap on HV side & neutral for LV loads.

**Q80 (APSPDCL-14):** |Vs|=|Vr| and |Is|=|Ir| → line called
(a) Infinite line (b) Natural line (c) Tuned line (d) Lossless line
**Ans: (c)** — Tuned line: |Vs|=|Vr|, |Is|=|Ir|.
**Concept:** tuned/natural lines.
**Twist:** at SIL (natural loading) Vr=Vs with flat profile (Q95, Q107).

**Q81 (APSPDCL-14):** Guard ring is used for
(a) Increasing potential across each unit (b) Equalizing potential across each unit (c) Decreasing potential (d) Both (a) and (b)
**Ans: (b)** — Guard ring equalizes potential distribution across discs.
**Concept:** guard ring / grading ring.
**Twist:** it reduces earth capacitance effect of lowest unit (Q94); alternative = capacitance grading (Q199).

**Q82 (APSPDCL-14):** Cable insulation resistance 10 km = 1 MΩ; for 50 km
(a) 0.02 MΩ (b) 5 MΩ (c) 0.2 MΩ (d) 2 MΩ
**Ans: (c)** — R ∝ 1/length ⇒ 1×(10/50) = 0.2 MΩ.
**Concept:** R_ins ∝ 1/length.
**Twist:** 100 km → 0.1 MΩ (Q88); leakage resistance same scaling (Q120).

**Q83 (ISRO-14):** Ferranti effect on long overhead lines experienced when
(a) Lightly loaded (b) Full load unity pf (c) Full load 0.8 lag (d) Overloaded
**Ans: (a)** — Ferranti occurs at light/no load.
**Concept:** Ferranti effect condition.
**Twist:** at SIL loading Vr=Vs (Q107); compensated by shunt reactor (Q181).

**Q84 (ISRO-14):** Power transmission lines transposed to reduce
(a) Skin effect (b) Ferranti effect (c) Transmission loss (d) Interference with neighboring communication lines
**Ans: (d)** — Transposition balances phases & reduces inductive interference.
**Concept:** transposition purpose.
**Twist:** also balances per-phase inductance/capacitance (Q155); for communication lines (Q124).

**Q85 (ISRO-14):** Current carrying capacity of cables in DC > AC mainly due to
(a) Absence of harmonics (b) No stability limit (c) Smaller dielectric loss (d) Absence of ripple
**Ans: (c)** — DC has smaller dielectric loss → higher thermal rating.
**Concept:** cable thermal limit & dielectric loss.
**Twist:** AC adds skin/proximity + dielectric loss; dielectric loss ∝ f (Q123).

**Q86 (ISRO-14):** Conductor carries more current on surface than core → known as
(a) Skin effect (b) Corona (c) Permeability (d) Unsymmetrical fault
**Ans: (a)** — Non-uniform current toward surface = skin effect.
**Concept:** skin effect.
**Twist:** proximity effect from neighbouring conductors (Q20); only in AC (Q8).

**Q87 (TGenco-15):** Main criterion for selection of size of a radial distribution system
(a) Voltage drop (b) Corona loss (c) Temperature rise (d) Capital cost
**Ans: (a)** — Radial distributor sizing is voltage-drop limited.
**Concept:** distribution design criterion.
**Twist:** EHV line sizing → corona (Q169); cables → thermal limit (Q134).

**Q88 (TGenco-15):** Cable insulation resistance 10 km = 1 MΩ; for 100 km
(a) 1 MΩ (b) 10 MΩ (c) 0.1 MΩ (d) 0.01 MΩ
**Ans: (c)** — R ∝ 1/length ⇒ 1×(10/100) = 0.1 MΩ.
**Concept:** R_ins ∝ 1/length.
**Twist:** 50 km → 0.2 MΩ (Q82); 2 m→8 m sample 10→2.5 MΩ (Q63).

**Q89 (TGenco-15):** 500 Hz excitation, 50 km short power line modelled as
(a) Short line (b) Medium line (c) Long line (d) Data insufficient
**Ans: (c)** — Effective length = (f/50)×50 = 500 km → long line.
**Concept:** electrical length depends on frequency.
**Twist:** at 50 Hz same 50 km is short; wavelength λ=v/f governs (Q40).

**Q90 (TGenco-15):** Short line R and L equal, regulation zero → load
(a) Unity pf (b) Zero pf (c) 0.707 leading (d) 0.707 lagging
**Ans: (c)** — Zero regulation needs leading pf, φ=45° when R=X ⇒ 0.707 lead.
**Concept:** zero regulation at leading load.
**Twist:** R=X=1 ratio, φ=90°−45°=45° lead (Q92); lag load always +ve regulation.

**Q91 (TSTransco-15):** Skin effect: major portion of current near ___ of conductor
(a) Surface (b) Center (c) Complete cross-section (d) Axis
**Ans: (a)** — Current concentrates at the surface.
**Concept:** skin effect current distribution.
**Twist:** hollow conductors exploit this — carry current on periphery (Q148).

**Q92 (TSTransco-15):** Short line r/x = 1.0, regulation zero when load pf
(a) Unity (b) 0.707 lead (c) 0.707 lag (d) Zero pf lead
**Ans: (b)** — φ = 90° − tan⁻¹(X/R) = 45° ⇒ 0.707 lead.
**Concept:** zero regulation condition.
**Twist:** r/x > 1 changes the leading angle; pure inductive load → max lag regulation.

**Q93 (TSTransco-15):** Surge impedance for overhead line taken as
(a) 10–20 Ω (b) 50–60 Ω (c) 100–200 Ω (d) 1000–2000 Ω
**Ans: (c)** — Overhead line Zc ~100–200 Ω (400 Ω typical).
**Concept:** Zc = √(L/C).
**Twist:** underground cable ~50 Ω (Q125); with bundling Zc decreases.

**Q94 (TSTransco-15):** Purpose of guard ring in transmission lines
(a) Reduce earth capacitance of lowest unit (b) Increase earth capacitance of lowest unit (c) Reduce losses (d) Reduce line reactance
**Ans: (a)** — Guard ring reduces effective earth capacitance of lowest unit.
**Concept:** guard ring mechanism.
**Twist:** grading capacitors instead (Q199); effect = equalized voltage (Q81).

**Q95 (TSSPDCL-15):** In tuned power lines, no load
(a) Vr = Vs numerically (b) Ir = Is numerically (c) No voltage drop (d) All the above
**Ans: (d)** — Tuned line: |Vr|=|Vs|, |Ir|=|Is|, no drop.
**Concept:** tuned (natural) line.
**Twist:** SIL loading gives flat voltage profile (Q107); resonant line has βl=π.

**Q96 (TSSPDCL-15):** Minimum clearance 6.3 m to ground required for voltages
(a) <66 kV (b) 66–110 kV (c) >165 kV (d) 110–165 kV
**Ans: (d)** — 6.3 m clearance corresponds to 110–165 kV.
**Concept:** IE ground clearance rules.
**Twist:** Rule 77 governs clearance (Q18); higher V → more clearance.

**Q97 (TSSPDCL-15):** B-parameter ratio and C-parameter ratio of nominal π vs nominal T model
(a) (1+YZ/4), (1+YZ/4) (b) (1+YZ/4), 4/(YZ+4) (c) 1/(1+YZ/4), (YZ+4)/4 (d) 4/(YZ+4), (YZ+4)/4
**Ans: (d)** — Bπ/BT = 4/(4+YZ); Cπ/CT = (YZ+4)/4.
**Concept:** nominal π vs T parameters: Bπ=Z, BT=Z(1+YZ/4); Cπ=Y(1+YZ/4), CT=Y.
**Twist:** A and D same (1+YZ/2) for both models (Q202).

**Q98 (TSSPDCL-15):** Theft of electricity dealt in ___ of Indian Electricity Rules
(a) Section 134 (b) Section 135 (c) Section 136 (d) Section 137
**Ans: (b)** — Theft → Section 135 (Electricity Act 2003).
**Concept:** Electricity Act theft provisions.
**Twist:** Section 136 is for the abetment/attempt; 135 for theft itself.

**Q99 (TSNPDCL-15):** Load compensation in power systems is a process to
(a) Maintain better voltage profile (b) Increase short circuit capacity (c) Generate harmonics (d) Compensate line reactance
**Ans: (a)** — Load compensation maintains voltage profile/pf.
**Concept:** load compensation purpose.
**Twist:** same as Q162; line (series) compensation boosts power transfer (Q194).

**Q100 (TSNPDCL-15):** 200 km line has ABCD; length reduced to 60 km
(a) A increases, B decreases (b) A and B increase (c) A decreases, B decreases (d) A and B decrease
**Ans: (a)** — Shorter line: A,D ↑ ; B,C ↓.
**Concept:** ABCD vs length.
**Twist:** Q22 identical (210→100 km); longer line: A↓, B↑.

**Q101 (TSNPDCL-15):** Voltage impressed at A of line AB, two components f(t−x/v) and f(t+x/v)
(a) f(t−x/v) is backward (b) f(t+x/v)−f(t−x/v) = total voltage (c) Sum of the two is total voltage (d) f(t+x/v) is forward
**Ans: (c)** — Total voltage = sum of forward (t−x/v) and backward (t+x/v) waves.
**Concept:** travelling wave components.
**Twist:** characteristic impedance ties V & I waves; reflected waves from mismatched termination (Q135).

**Q102 (TSNPDCL-15):** DC 2-wire 200 V raised to 400 V; % saving in conductor material (same power, distance, loss)
(a) 50 (b) 40 (c) 75 (d) 60
**Ans: (c)** — A1/A2=(V2/V1)²=4; saving=(A1−A2)/A1=75%.
**Concept:** conductor volume ∝ 1/V².
**Twist:** 200→400 V is 2× → saves 75%; n× voltage → 1/n² area (Q121).

**Q103 (TSNPDCL-15):** Voltage across identical suspension discs different due to
(a) Surface leakage currents (b) Series capacitance of lines (c) Shunt capacitance to ground (d) Series and shunt capacitances
**Ans: (c)** — Shunt (pin-to-earth) capacitance causes unequal division.
**Concept:** string voltage distribution cause.
**Twist:** self + shunt capacitance (Q104) → non-uniform; guard ring fixes (Q94).

**Q104 (HMWS-15):** Two discs C each, pin-earth C; string efficiency for 22 kV string
(a) 86% (b) 75% (c) 90% (d) 50%
**Ans: (b)** — m=1 ⇒ V2=2V1; η=(V1+V2)/(2V2)=3/4=75%.
**Concept:** η with K=C_g/C=1.
**Twist:** K→0 ⇒ η→100% (no earth capacitance); 2-disc K=0.2 → 91.6% (Q128).

**Q105 (HMWS-15):** Accurate load flow on large power system, best method
(a) FDLF (b) Gauss-Seidel (c) Decoupled (d) Newton-Raphson
**Ans: (d)** — NR is most accurate for large systems.
**Concept:** load flow methods.
**Twist:** fast-decoupled for speed; G-S simple but slow convergence.

**Q106 (HMWS-15):** EHV transmission efficiency ↑ by ↓ corona loss, achieved by
(a) Thin conductors (b) Bundled conductors (c) Thick conductors (d) Increasing line spacing
**Ans: (b)** — Bundling reduces corona loss.
**Concept:** bundling for corona.
**Twist:** larger radius or spacing also ↓ corona but spacing ↑ inductance; bundling is economical.

**Q107 (HMWS-15):** If loading = surge impedance loading, receiving end voltage
(a) Independent of loading (b) < sending end (c) Equal to sending end (d) > sending end
**Ans: (c)** — At SIL, Vr = Vs (flat voltage profile).
**Concept:** SIL = natural loading.
**Twist:** light load → Vr>Vs (Ferranti); heavy load → Vr<Vs.

**Q108 (HMWS-15):** Horizontal spacing 'd' rearranged to equilateral triangle side 'd'
(a) C ↓, L ↑ (b) C ↑, L ↓ (c) C & L same (d) C ↓, L ↓
**Ans: (b)** — Equivalent GMD decreases (from ∛(d·d·2d) to d) ⇒ L↓, C↑.
**Concept:** GMD vs configuration.
**Twist:** transposition balances GMD per phase (Q155); L ∝ ln(GMD), C ∝ 1/ln(GMD).

**Q109 (HMWS-15):** Advantage of corona in a power system
(a) Power loss more (b) Increase charging currents (c) Reduces high voltage lightning waves (d) Power loss less
**Ans: (c)** — Corona dissipates/attenuates high-frequency surge magnitudes.
**Concept:** corona protective effect on surges.
**Twist:** downsides: loss, RI, harmonics (Q3); that's why it's minimized (Q106).

**Q110 (HMWS-15):** Presence of earth in overhead lines
(a) No effect (b) Increases inductance (c) Decreases C, increases L (d) Increases capacitance
**Ans: (d)** — Earth increases effective capacitance.
**Concept:** earth as conducting plane → capacitance ↑.
**Twist:** increases tower height → capacitance ↓, inductance unchanged (Q180).

**Q111 (SSC-JE-S1-14):** IE rules permissible variation of voltage at consumer end
(a) ±10% (b) ±12% (c) ±2% (d) ±6%
**Ans: (d)** — Consumer end ±6%.
**Concept:** IE voltage variation rules.
**Twist:** declared vs actual at consumer ±4% (Q58); feeder regulation separately.

**Q112 (SSC-JE-S1-14):** Bundled conductors in EHV provide
(a) Increased line reactance (b) Reduced line capacitance (c) Reduced voltage gradient (d) Increased corona loss
**Ans: (c)** — Bundling ↓ voltage gradient (electric stress).
**Concept:** E = Vph/[GMR ln(GMD/GMR)]; bundling ↑GMR → ↓E.
**Twist:** ↓gradient → ↓corona (Q17); also ↓X_L (Q55).

**Q113 (SSC-JE-S1-14):** Rated voltage of a 3-phase power system
(a) rms phase (b) peak phase (c) rms line-to-line (d) peak line-to-line
**Ans: (c)** — System rating = rms line-to-line.
**Concept:** rated voltage convention.
**Twist:** phase voltage = V_L/√3 for string design (Q145).

**Q114 (SSC-JE-S1-14):** Excitation control method satisfactory for
(a) Low voltage lines (b) High voltage lines (c) Short lines (d) Long lines
**Ans: (c)** — Excitation (voltage) control works for short lines.
**Concept:** voltage control methods by line length.
**Twist:** long lines use shunt compensation/SVC; short lines use excitation/tap change.

**Q115 (SSC-JE-S1-14):** Highest transmission AC voltage in India
(a) 132 kV (b) 220 kV (c) 400 kV (d) 750 kV
**Ans: (d)** — Highest AC = 750 kV (765 kV class).
**Concept:** Indian voltage levels.
**Twist:** ±800 kV HVDC; national grid at 400/765 kV.

**Q116 (SSC-JE-S2-14):** Conductor connecting metal body of equipment to earth is
(a) Neutral continuity conductor (b) Earth discontinuity conductor (c) Earth continuity conductor (d) Neutral discontinuity conductor
**Ans: (c)** — Earth continuity conductor.
**Concept:** earthing conductors.
**Twist:** earth continuity prevents shock; neutral ≠ earth (carries load current).

**Q117 (SSC-JE-S2-14):** Insulation widely used for covering internal wiring cables
(a) Paper (b) Wood (c) Glass (d) PVC
**Ans: (d)** — PVC used for domestic/internal wiring.
**Concept:** cable insulation materials.
**Twist:** butyl rubber for cables with near-natural-rubber properties (Q207).

**Q118 (SSC-JE-S2-14):** Earthing electrodes placed within what distance (m) from building
(a) 4 (b) 2.5 (c) 1.5 (d) 0.5
**Ans: (c)** — 1.5 m from building.
**Concept:** earthing installation rule.
**Twist:** electrode depth/pit size per IE rules (plate ~3 m deep).

**Q119 (SSC-JE-S2-14):** Power distribution by cable generally adopted for line length
(a) <10 km (b) >10 km (c) <50 km (d) >50 km
**Ans: (c)** — Cables used for short/urban lengths (<50 km).
**Concept:** cable vs overhead choice.
**Twist:** cables costlier & higher charging current — limited to short urban runs.

**Q120 (SSC-JE-S2-14):** Leakage resistance 50 km cable = 1 MΩ; 100 km cable
(a) 0.5 MΩ (b) 2 MΩ (c) 0.66 MΩ (d) None
**Ans: (a)** — R ∝ 1/length ⇒ 1×(50/100)=0.5 MΩ.
**Concept:** leakage/insulation R ∝ 1/length.
**Twist:** Q82 (50 km → 0.2 MΩ), Q88 (100 km → 0.1 MΩ) same rule.

**Q121 (SSC-JE-S2-14):** If voltage increased 'n' times, size of conductor
(a) Increase n times (b) Reduce 1/n (c) Increase n² (d) Reduce 1/n²
**Ans: (d)** — Area ∝ 1/V².
**Concept:** conductor size ∝ 1/V².
**Twist:** weight ∝ 1/E² (Q54); 2× voltage saves 75% material (Q102).

**Q122 (SSC-JE-S2-14):** Wire placed on top of a transmission line acts as
(a) Phase wire (b) Neutral (c) Transmission wire (d) Ground wire
**Ans: (d)** — Top wire = earth/ground (shield) wire.
**Concept:** overhead earth/static wire.
**Twist:** shield wire intercepts lightning → reduces tower footing resistance need (Q29).

**Q123 (SSC-JE-S2-14):** Dielectric loss is proportional to
(a) f^½ (b) f (c) f² (d) f³
**Ans: (b)** — P = V²(2πfC)tanδ ⇒ ∝ f.
**Concept:** dielectric loss = V²ωC tanδ.
**Twist:** DC cables lower dielectric loss (Q85); corona loss ∝ (f+25) (Q167).

**Q124 (APTransco-17):** Transmission lines transposed to reduce
(a) Ferranti effect & voltage level (b) Skin effect & efficiency (c) Proximity effect & current density (d) Interference with neighboring communication lines
**Ans: (d)** — Transposition reduces inductive interference with communication lines.
**Concept:** transposition purpose.
**Twist:** also balances phase constants (Q155, Q84).

**Q125 (APTransco-17):** Surge impedance of 60-mile underground cable = 50 Ω; for 30 miles
(a) 25 Ω (b) 50 Ω (c) 100 Ω (d) 200 Ω
**Ans: (b)** — Zc independent of length.
**Concept:** Zc = √(L/C) per unit — length-independent.
**Twist:** Q197 (300→150 km, still 180 Ω); cable ~50 Ω vs overhead ~400 Ω (Q93).

**Q126 (APTransco-17):** Single core cable peak 220 kV, max stress 20 kV/mm; economical overall core diameter
(a) 28.2 mm (b) 26.4 mm (c) 24.4 mm (d) 22.0 mm
**Ans: (d)** — G_max = 2V_peak/d ⇒ d = 2×220/20 = 22 mm.
**Concept:** optimum d for min stress: d = 2V/Gmax.
**Twist:** min stress at conductor surface requires R/r = e (2.718) → thickness 1.718 cm (Q157).

**Q127 (APTransco-17):** Stringing chart is used for
(a) Finding the sag in the conductor (b) Design of towers (c) Design of insulator string (d) Distance between towers
**Ans: (a)** — Stringing chart → sag.
**Concept:** stringing chart = sag/tension vs temp.
**Twist:** Q12, Q19 same; used during stringing at different temperatures.

**Q128 (APTransco-17):** 2-unit suspension string, self C, ground 0.2C, each withstands 11 kV; string efficiency
(a) 78% (b) 82% (c) 80% (d) 84%
**Ans: (—)** — m=5, η=91.6% (not in options; key marked *).
**Concept:** η = (V1+V2)/(2V2), m=C/Cg.
**Twist:** with K=Cg/C=0.2 → 91.6%; K=1 (Q104) → 75%.

**Q129 (APTransco-17):** Precise control of reactive current entering T&D systems can be minimized by
(a) Synchronous condenser (b) Static VAR capacitor (c) Capacitor bank (d) Thyristor switched reactor in parallel with capacitor
**Ans: (d) (or b)** — Key: (d) or (b); TCR+capacitor = SVC gives precise control.
**Concept:** static VAR compensation.
**Twist:** SVC also regulates voltage in heavy/light load (Q141).

**Q130 (APTransco-17):** Vs=10 kV/ph, Vr=9.5 kV/ph, IR drop 150 V/ph, Vr pf 0.8; sending end pf
(a) 0.745 lag (b) 0.775 lag (c) 0.8 lag (d) 0.85 lag
**Ans: (b)** — cosφs = (Vr cosφr + IR)/Vs = (9.5k×0.8+150)/10k = 0.775.
**Concept:** sending-end pf computation.
**Twist:** lagging pf assumed; if pf leading → sending end pf can lead.

**Q131 (APTransco-17):** DC distributor length λ, r Ω/m, fed both ends equal voltages, uniformly loaded i A/m; power loss
(a) i²rλ/3 (b) i²rλ/4 (c) i²rλ³/8 (d) i²rλ³/12
**Ans: (d)** — Uniform load fed both ends: P_loss = i²rλ³/12.
**Concept:** DC distributor losses.
**Twist:** fed at one end → i²rλ³/3; equal voltages both ends halves losses.

**Q132 (APTransco-17):** Corona loss in transmission lines reduced by
(a) Small diameter conductors (b) Bundled conductors (c) Less spacing (d) Increasing transmission voltage
**Ans: (b)** — Bundling ↓ corona loss.
**Concept:** corona loss reduction.
**Twist:** bigger radius, higher spacing, lower V (Q73, Q148); DC also lower (Q185).

**Q133 (APTransco-17):** B and C of medium line by nominal T model
(a) (1+YZ/2), Z (b) (1+YZ/2), Y (c) Z, Y(1+YZ/4) (d) Z(1+YZ/4), Y
**Ans: (d)** — Nominal T: B=Z(1+YZ/4), C=Y.
**Concept:** nominal T ABCD.
**Twist:** π model: B=Z, C=Y(1+YZ/4) (Q97); A=D=1+YZ/2 for both.

**Q134 (APGenco-17):** Main limitation for power handling capability of short lines and cables
(a) Power factor (b) Stability (c) Thermal effect limit (d) Conductor size
**Ans: (c)** — Short lines/cables limited by thermal rating.
**Concept:** line limits by length.
**Twist:** medium → voltage drop; long → stability (Q143).

**Q135 (APGenco-17):** Travelling wave surge resistance R0 terminated by RL, RL>R0
(a) No reflected wave (b) Partial reflection of reversal of current only (c) Partial reflection of reversal of voltage only (d) Reversal of both current and voltage
**Ans: (b)** — ρV=(RL−R0)/(RL+R0)>0 (+), ρI=(R0−RL)/(R0+RL)<0 (−): current reverses.
**Concept:** reflection coefficients.
**Twist:** RL<R0 → voltage reverses; RL=R0 → no reflection (matched).

**Q136 (APGenco-17):** 3-insulator string, pin-earth/self = 1/4, top unit 8 kV; string voltage
(a) 22.5 kV (b) 24 kV (c) 26 kV (d) 32.5 kV
**Ans: (d)** — V1=8; V2=1.25×8=10; V3=10+0.25×18=14.5; total=32.5 kV.
**Concept:** iterative string distribution with m=4.
**Twist:** bottom unit carries max (Q47); guard ring evens it out (Q81).

**Q137 (APGenco-17):** GMR of 4-bundled conductor, radius r, spaced d
(a) (r·d12·d13·d14)^¼ (b) (r·e^{-1/4}d12d13d14)^{-1/4} (c) (r·e^{-1/4}d12d13d14)^{-14} (d) (r·e^{-1/4}·d12·d13·d14)^¼
**Ans: (d)** — GMR_bundle = (r'·d12·d13·d14)^¼, r'=re^{-1/4}.
**Concept:** bundled conductor GMR.
**Twist:** 3-strand triangle GMR = (e^{-0.25}r·2r·2r)^⅓ (Q139, Q179).

**Q138 (APGenco-17):** Corona loss 100 kW at 60 kV/ph, 25 kW at 50 kV/ph; disruptive critical voltage
(a) 40 kV (b) 43.6 kV (c) 49.6 kV (d) 50 kV
**Ans: (a)** — P∝(V−Vd)²; (60−Vd)/(50−Vd)=2 ⇒ Vd=40 kV.
**Concept:** corona loss ∝ (V−Vd)².
**Twist:** at Vd itself loss→0; moisture ↓Vd (Q147).

**Q139 (APGenco-17):** GMR of 3 strands each radius r in triangle
(a) (3r·r·r)^⅓ (b) (e^{-0.25}r·2r·2r)^⅓ (c) (e^{-0.5}r·2r·2r)^⅓ (d) (e^{-1/3}r·2r·2r)^⅓
**Ans: (b)** — GMR = (r'·2r·2r)^⅓, r'=re^{-0.25}.
**Concept:** 3-strand conductor GMR.
**Twist:** r'=re^{-0.25} always for self-distance; Q179 repeats for triangle.

**Q140 (APGenco-17):** Reactive power compensation in feeders leads to
(a) Poor voltage profile (b) Improved voltage profile (c) Negative/zero sequence currents (d) Expensive voltage regulators
**Ans: (b)** — Reactive compensation improves voltage profile.
**Concept:** shunt compensation benefit.
**Twist:** over-compensation raises V too high — SVC regulates (Q141).

**Q141 (APGenco-17):** System voltage enhanced in heavy load, reduced in light load by
(a) Shunt capacitor (b) Shunt reactor (c) Active power filter (d) Static VAR Compensator
**Ans: (d)** — SVC supplies/absorbs vars to hold voltage.
**Concept:** SVC voltage control.
**Twist:** fixed shunt capacitor alone raises V always (bad at light load) → need SVC.

**Q142 (TSSPDCL-18):** Capacitor connected in series with the line is used to
(a) Enhance power factor (b) Enhance power system capability (c) Decrease the losses (d) Decrease power transfer
**Ans: (b)** — Series capacitor ↓ X_L → ↑ power transfer capability.
**Concept:** series compensation.
**Twist:** Pmax=V1V2/X_L; 25% series comp ↑ SIL to 1.33× (Q212).

**Q143 (TSSPDCL-18):** Line operating with 80° phase shift; load suddenly increased
(a) Phase displacement will increase (b) Decrease (c) Not change (d) Surge impedance increases
**Ans: (a)** — P=V1V2/X sinδ; more load → larger δ.
**Concept:** power-angle relation.
**Twist:** at δ=90° max power (stability limit); >90° unstable — long lines (Q134).

**Q144 (TSTransco-18):** Long line open at receiving end, Vr=400 kV; sending end voltage
(a) <400 kV (b) =400 kV (c) >400 kV (d) ≥400 kV
**Ans: (a)** — Open end → Ferranti: Vr>Vs ⇒ Vs<400 kV.
**Concept:** Ferranti effect on open line.
**Twist:** Vs/ A relation Q16: Vs fixed → Vr=Vs/A rises; add shunt reactor to equalize (Q177).

**Q145 (TSTransco-18):** String efficiency 80% of 400 kV 3-phase line; voltage across string
(a) 400 kV (b) (400/√3) kV (c) (500/√3) kV (d) 320 kV
**Ans: (b)** — Voltage across string = phase voltage = V_L/√3.
**Concept:** phase voltage across suspension string.
**Twist:** string voltage always V_L/√3, η only relates bottom unit (Q186).

**Q146 (TSTransco-18):** 11 kV motor 100 kVA @0.8 lag; 60 kVAR capacitor → pf unity; apparent power from system
(a) 100 kVA (b) 40 kVA (c) 160 kVA (d) 80 kVA
**Ans: (d)** — S×pf const: 100×0.8=S2×1 ⇒ 80 kVA.
**Concept:** pf correction — active power unchanged.
**Twist:** capacitor 60 kVAR just cancels Q=60 kVAR; motor current reduces.

**Q147 (TSTransco-18):** As moisture content in air increases, disruptive critical voltage
(a) Decreases (b) Increases (c) Constant (d) Infinite
**Ans: (a)** — Moisture lowers voltage gradient needed for discharge → Vd decreases.
**Concept:** disruptive critical voltage vs humidity.
**Twist:** corona more likely in humid weather (Q48); winter high density also lowers Vd.

**Q148 (TSTransco-18):** Corona loss reduced by hollow conductors because
(a) Current density reduced (b) Eddy current eliminated (c) Radius increased for given cross-section (d) Better ventilation
**Ans: (c)** — Hollow ↑ radius → ↓ gradient → ↓ corona.
**Concept:** hollow conductor purpose.
**Twist:** Q26 same; also used for cooling in high-current bus (Q182).

**Q149 (TSTransco-18):** End condenser method: values of A and D
(a) A=1+ZY, D=1+ZY (b) A=1+ZY, D=1 (c) A=1−ZY, D=1+ZY (d) A=1, D=1+ZY
**Ans: (b)** — End condenser (capacitor at far end): A=1+ZY, D=1.
**Concept:** end condenser ABCD.
**Twist:** nominal π lumps Y/2 at both ends; end-condenser lumps all Y at receiving end.

**Q150 (APSPDCL-19/APTransco-19):** 1.6 km, 3.3 kV, horizontal 762 mm centres, dia 3.5 mm; equivalent spacing
(a) 560 (b) 760 (c) 960 (d) 862
**Ans: (c)** — Deq = ∛(d·d·2d) = ∛(762·762·1524) = 960 mm.
**Concept:** equivalent (GMD) spacing horizontal.
**Twist:** equilateral triangle side d → Deq=d (Q108); Deq used in L & C.

**Q151 (APSPDCL-19):** Transmission line modelled as π in simulations because
(a) Number of nodes more in T-model (b) Nodes less in T (c) Equal nodes (d) No nodes
**Ans: (a)** — π model has fewer nodes than T (preferred for load flow).
**Concept:** π vs T network node count.
**Twist:** both give identical terminal behaviour; π avoids extra bus.

**Q152 (APSPDCL-19):** Active power in a transmission line can be controlled using
(a) Series capacitor (b) Shunt capacitor (c) Shunt inductor (d) Phase shifting transformer
**Ans: (d)** — Phase-shifting transformer controls P (changes δ effectively).
**Concept:** power flow control.
**Twist:** reactive power via shunt compensation; series capacitor ↑ capability not direction.

**Q153 (APSPDCL-19/APTransco-19):** Eth=0.9∠0, Zth=0.25∠90 pu; raise bus to 1.0 pu; MVAR of capacitor (base 100 MVA)
(a) 10 (b) 20 (c) 30 (d) 40
**Ans: (d)** — Qc = VL×ΔV/X = 1×0.1/0.25 = 0.4 pu = 40 MVAR.
**Concept:** capacitor sizing for voltage support.
**Twist:** ΔV=V_target−E; ΔV=0.1 needed; Q ∝ 1/X.

**Q154 (APSPDCL-19):** Real part of propagation constant of a transmission line
(a) Phase constant (b) Attenuation constant (c) Stability constant (d) Reliability factor
**Ans: (b)** — γ=α+jβ; α=attenuation (real), β=phase (imag).
**Concept:** propagation constant γ=√((r+jωL)(g+jωC)).
**Twist:** lossless line α=0, only β — used in surge impedance (Q212).

**Q155 (APSPDCL-19):** Conductors not spaced equilaterally, transposition done to
(a) Decrease line inductance (b) Increase line capacitance (c) Balance the three phases (d) Increase line resistance
**Ans: (c)** — Transposition balances per-phase parameters.
**Concept:** transposition for balance.
**Twist:** also reduces interference (Q124); Deq = ∛(d1d2d3) (Q200).

**Q156 (APSPDCL-19):** Z matrix [4 3; 3 6]; Y22 of corresponding Y matrix
(a) 0.5 (b) 0.267 (c) –0.267 (d) 0.42
**Ans: (b)** — Y22=Z11/(Z11Z22−Z12²)=4/(24−9)=4/15=0.267.
**Concept:** Z↔Y conversion (Y=Z⁻¹).
**Twist:** Y11=6/15=0.4; off-diagonal Y12=−3/15=−0.2.

**Q157 (APSPDCL-19):** Single core cable, conductor radius 1 cm; insulation thickness for min stress at conductor surface
(a) 1.718 cm (b) 1 cm (c) 2 cm (d) 2.718 cm
**Ans: (a)** — Min stress at R/r=e ⇒ R=2.718 cm, thickness=R−r=1.718 cm.
**Concept:** optimum cable dimensions R/r=e.
**Twist:** economical diameter d=2V/Gmax (Q126); Emax at conductor, Emin at sheath (Q160).

**Q158 (APSPDCL-19):** Discs of strain insulators are used in ___ plane
(a) Smooth (b) Horizontal (c) Slant (d) Vertical
**Ans: (b)** — Strain insulator discs in horizontal plane.
**Concept:** strain insulator mounting.
**Twist:** suspension strings vertical; strain strings horizontal at dead-ends/turns (Q72).

**Q159 (APSPDCL-19):** 10-node system, Z44=j0.5 pu, V4=1.5∠2°; capacitor −j3.5 pu added; current drawn
(a) 0.428∠88° (b) 0.5∠92° (c) 0.5∠88° (d) 0.428∠92°
**Ans: (b)** — Ic = V/(Zth−jXc) = 1.5∠2°/(j0.5−j3.5)=1.5∠2°/(−j3)=0.5∠92°.
**Concept:** capacitor current in Z-bus.
**Twist:** current leads voltage by ~90° for capacitor; sign depends on −j convention.

**Q160 (APSPDCL-19):** Minimum dielectric stress in a cable is at
(a) Lead sheath (b) Armour (c) Bedding (d) Conductor surface
**Ans: (a)** — Stress ∝1/x, min at outermost (sheath).
**Concept:** E=1/(x ln(D/d)) · V.
**Twist:** max at conductor surface (Q62); grading equalizes stress (Q175).

**Q161 (APSPDCL-19):** Same inductance per phase → lines are
(a) Twisted (b) Bundled (c) Stranded (d) Transposed
**Ans: (d)** — Transposition equalizes phase inductance.
**Concept:** transposition for equal L.
**Twist:** bundled affects GMR (Q137); transposed gives Deq (Q155).

**Q162 (APSPDCL-19):** Load compensation in power systems is a process to
(a) Compensate line reactance (b) Maintain better voltage profile (c) Increase short circuit capacity (d) Generate harmonics
**Ans: (b)** — Load compensation improves voltage profile.
**Concept:** load compensation.
**Twist:** Q99 identical; series (line) compensation targets reactance (Q194).

**Q163 (APSPDCL-19):** Small birds on overhead line don't get electrocuted because
(a) Body resistance high (b) Lines insulated (c) Bird legs don't conduct (d) Negligible voltage across the bird
**Ans: (d)** — Bird bridges negligible length → negligible voltage.
**Concept:** low impedance between bird legs.
**Twist:** if bird touches pole+line → electrocuted (potential difference to ground).

**Q164 (APSPDCL-19):** 'x' layers, each layer diameter 'd'; overall diameter of stranded conductor
(a) (2x+1)d (b) (2x−1)d (c) (3x−1)d (d) (6x−3)d
**Ans: (b)** — Overall dia = (2x−1)d.
**Concept:** stranded conductor geometry.
**Twist:** strands = 3x²−3x+1 (Q44); GMR from strand r (Q139).

**Q165 (APSPDCL-19):** Bundled conductors in EHV primarily for reducing
(a) Corona loss (b) Surge impedance (c) I²R loss (d) Voltage across line
**Ans: (a)** — Primary purpose: corona loss.
**Concept:** bundling purpose.
**Twist:** Q17/Q132 same; Q23 shows SIL (via Zc) changes as secondary effect.

**Q166 (APSPDCL-19):** Corona loss increases with
(a) ↑ frequency, ↓ conductor size (b) ↑ frequency, ↑ conductor size (c) ↓ frequency, ↑ conductor size (d) ↓ frequency, ↓ conductor size
**Ans: (a)** — Corona loss ∝(f+25) and ↑ as radius ↓.
**Concept:** corona loss factors.
**Twist:** Q73 same; bigger radius/spacing reduces loss (Q132).

**Q167 (APSPDCL-19):** Corona loss 1.2 kW/ph/km at 50 Hz; at 60 Hz
(a) 1.36 kW (b) 1 kW (c) 0.5 kW (d) 0.667 kW
**Ans: (a)** — P∝(f+25): 1.2×85/75 = 1.36 kW.
**Concept:** corona loss ∝ (f+25).
**Twist:** DC (f=0): loss ×25/75 = 1/3 → Q185 (3→1 kW).

**Q168 (APSPDCL-19):** 4-unit string, bottom unit 33.33% of total voltage; string efficiency
(a) 75% (b) 25% (c) 33.33% (d) 66.7%
**Ans: (a)** — η=1/(4×0.3333)=75%.
**Concept:** η = 1/(n×V4/V_total).
**Twist:** Q78 (79.16%), Q186 (80%) same formula family.

**Q169 (APSPDCL-19):** Primary consideration in deciding conductor size of EHV lines
(a) Power loss (b) Voltage drop (c) Current density (d) Corona
**Ans: (d)** — EHV sizing governed by corona.
**Concept:** EHV conductor sizing.
**Twist:** LV/medium → voltage drop (Q87); short lines → thermal (Q134).

**Q170 (APSPDCL-19):** In ACSR, steel core provided to
(a) Increase tensile strength (b) Compensate skin effect (c) Neutralize proximity effect (d) Reduce line inductance
**Ans: (a)** — Steel core adds mechanical strength.
**Concept:** ACSR construction.
**Twist:** aluminium strands carry current; steel carries tension → longer spans.

**Q171 (APSPDCL-19):** NOT an advantage of transmitting at high voltages
(a) Reduced risk of corona (b) High efficiency (c) Better regulation (d) Lesser conductor material
**Ans: (a)** — Corona loss increases with V (disadvantage).
**Concept:** HV transmission trade-offs.
**Twist:** HV: ↓I → ↓I²R, ↓voltage drop, ↓material (Q7, Q41).

**Q172 (APSPDCL-19):** N-bus system with L lines; nonzero elements in Y-bus
(a) 2N+L (b) N+L (c) 2L (d) N+2L
**Ans: (d)** — Nonzero = N diagonal + 2L off-diagonal = N+2L.
**Concept:** Y-bus sparsity.
**Twist:** for N=10, L=15 → 40 elements vs 100 dense.

**Q173 (APSPDCL-19):** 35 km line, lumped impedance 20 Ω; ABCD form
(a) [20 0;1 1] (b) [1 20;0 1] (c) [1 0;2 1] (d) [1 0;20 1]
**Ans: (b)** — Short line: A=D=1, B=Z=20, C=0.
**Concept:** short-line ABCD matrix.
**Twist:** 35 km is short → ignore shunt; >80 km needs π (Q67, Q192).

**Q174 (APSPDCL-19):** Coaxial cable L=0.2 µH/m, C=245 pF/m; wave velocity
(a) 143 m/µs (b) 14.3 m/s (c) 1.43 µm/s (d) 0.143 m/s
**Ans: (a)** — v=1/√(LC)=142.85×10⁶ m/s=143 m/µs.
**Concept:** v=1/√(LC).
**Twist:** also v=c/√εr (Q14); Zc=√(L/C) (Q64).

**Q175 (APTransco-19):** Grading of cables performed to achieve
(i) Uniform stress (ii) Reduction in quantity of insulation (iii) Reduction in quality of insulation
(a) (i),(ii) (b) (ii) (c) (i),(iii) (d) (ii),(iii)
**Ans: (a)** — Grading gives uniform stress & less insulation quantity.
**Concept:** cable grading.
**Twist:** dielectric grading (ε layers) or capacitance grading; never lowers quality — so (iii) wrong.

**Q176 (APTransco-19):** Unbalance node: leaving 20, 25 MW; entering 60, 30 MW; balancing power
(a) 30 MW leaving (b) 45 MW leaving (c) 45 MW entering (d) 22.5 each way
**Ans: (b)** — Entering 90, leaving 45 ⇒ need 45 MW leaving.
**Concept:** node power balance.
**Twist:** sign convention crucial; generation vs load at PV/PQ nodes.

**Q177 (APTransco-19):** Vs=400 kV, A=D=0.8∠0, B=100∠90°, C=0.5e-6∠90°; inductive shunt reactor for Ferranti
(a) 1500 Ω (b) 750 Ω (c) 500 Ω (d) 300 Ω
**Ans: (c)** — A+B/(jX)=1 ⇒ 0.8+100/X=1 ⇒ X=500 Ω.
**Concept:** shunt reactor sizing for Ferranti.
**Twist:** reactor at receiving end raises effective A→1; Q144 shows need.

**Q178 (APTransco-19):** Line with equal end voltages; third source at mid-point (case1) or 75% from sending end (case2); max power ratio
(a) 1:1:1 (b) 1:2:1/0.75 (c) 1:2:4 (d) 1:4:16
**Ans: (b)** — Pmax:V²/X; mid-comp → 2V²/X; at 75% → V²/0.75X; ratio 1:2:1/0.75.
**Concept:** intermediate compensation Pmax.
**Twist:** mid-point compensation doubles capability; 1:2:1/0.75 = 1:2:1.333.

**Q179 (APTransco-19):** GMR of three strands radius r (figure)
(a) (e^{-0.25}r·2r·2r)^⅓ (b) (e^{0.25}r·2r·3r)^⅓ (c) (e^{-0.5}r·r·2r)^⅓ (d) (e^{0.5}2r·2r·2r)^⅓
**Ans: (a)** — GMR = (r'·d12·d13)^⅓ with r'=re^{-0.25}.
**Concept:** 3-strand GMR.
**Twist:** identical Q139; bundled 4-conductor GMR Q137.

**Q180 (TSSPDCL-2022):** Effect on L and C with increase in tower height
(a) L↑, C↓ (b) L↓, C↑ (c) L same, C↓ (d) L same, C↑
**Ans: (c)** — Height affects only earth capacitance; inductance unchanged.
**Concept:** tower height vs line constants.
**Twist:** earth present → C ↑ (Q110); raising conductor → C ↓.

**Q181 (TSSPDCL-2022):** Device used to neutralize Ferranti effect in medium/long lines
(a) Shunt capacitor (b) Series resistor (c) Series capacitor (d) Shunt reactor
**Ans: (d)** — Shunt reactor absorbs charging vars → reduces Ferranti.
**Concept:** Ferranti compensation.
**Twist:** shunt reactor sizing (Q177); series capacitor is for power transfer (Q142).

**Q182 (TSSPDCL-2022):** Hollow conductors used in transmission lines to
(a) Reduce weight of copper (b) Improve stability (c) Reduce corona (d) Increase power transmission capacity
**Ans: (c)** — Hollow conductor reduces corona (bigger radius).
**Concept:** hollow conductor purpose.
**Twist:** Q26/Q148 same; also internal cooling in high-current applications.

**Q183 (TSSPDCL-2022-Set-D):** Ring main distribution preferred to radial because
(a) Less voltage drop and more reliable supply (b) Less voltage drop and high pf (c) High pf and less expensive (d) High pf and more reliable
**Ans: (a)** — Ring main: less voltage drop, more reliability.
**Concept:** ring vs radial distribution.
**Twist:** radial simpler/cheaper but less reliable; ring can be sectionalized.

**Q184 (TSSPDCL-2022):** Flue gases after boiler pass through (correct order) 1. ID fan, 2. Air-preheater, 3. Superheater, 4. Economiser
(a) 3,4,2,1 (b) 1,4,2,3 (c) 3,2,4,1 (d) 4,2,3,1
**Ans: (a)** — Superheater → economiser → air-preheater → ID fan.
**Concept:** thermal plant flue gas path.
**Twist:** reversed order = upstream heat recovery; ID fan last pulls gas out.

**Q185 (TSSPDCL-2022):** Corona loss 400 kV, 50 Hz = 3 kW/km/ph; DC with same configuration
(a) 3 kW (b) 9 kW (c) 1 kW (d) 1.5 kW
**Ans: (c)** — P∝(f+25): 3×25/75 = 1 kW/km/ph.
**Concept:** corona loss f-dependence.
**Twist:** Q167 same relation (50→60 Hz); DC has no f+25 term beyond 25.

**Q186 (TSNPDCL-2022):** Phase-ground 100 kV, 5-disc string, bottom disc 25 kV; string efficiency
(a) 83.3% (b) 100% (c) 80% (d) 64%
**Ans: (c)** — η=100/(5×25)×100=80%.
**Concept:** η = V_ph/(n·V_bottom).
**Twist:** Q78, Q168 same formula; V_ph=V_L/√3 for the string (Q145).

**Q187 (TSNPDCL-2022):** 3-φ 110 kV, 50 Hz, 100 km, 220 MVA load, 24 MW loss; line resistance
(a) 2 Ω (b) 6 Ω (c) 18 Ω (d) 0.6 Ω
**Ans: (b)** — I=220M/(√3·110k); 3I²R=24MW ⇒ R=6 Ω/ph.
**Concept:** line loss 3I²R.
**Twist:** loss 24 MW at 220 MVA = ~11% — high for 110 kV; R scales with S².

**Q188 (TSNPDCL-2022):** Back-to-back HVDC link used to
(a) Increase transmission capability (b) Decrease line losses (c) Provide stable interconnection (d) Reduce voltage drop
**Ans: (c)** — B2B HVDC provides stable asynchronous interconnection.
**Concept:** back-to-back HVDC.
**Twist:** used between unsynchronised systems (e.g., India regional grids); P controlled by firing angle (Q43).

**Q189 (TSNPDCL-2022):** Line with mid-point series capacitor; max voltage located at
(a) a (b) b (c) c (d) d
**Ans: (c)** — Series cap causes voltage jump; max at capacitor mid-point terminal c.
**Concept:** series-compensated voltage profile.
**Twist:** Vc rises above sending level (Ferranti-like); shunt reactor at that point controls.

**Q190 (TSNPDCL-2022):** Undesirable property of an electrical insulating material
(a) High dielectric strength (b) High relative permittivity (c) High thermal conductivity (d) High insulation resistivity
**Ans: (b)** — High εr is undesirable (more capacitive loss/current).
**Concept:** insulator material properties.
**Twist:** want high dielectric strength, high resistivity, good thermal conductivity — but low εr.

**Q191 (TSNPDCL-2022):** Two supply systems requiring same conductor volume as a DC system (max potential to earth equal)
(a) AC 2-φ4-wire; 2-φ3-wire (b) AC 2-φ4-wire; 3-φ4-wire (c) AC 2-φ4-wire; 3-φ3-wire (d) AC 2-φ3-wire; 3-φ3-wire
**Ans: (c)** — 2-φ4-wire and 3-φ3-wire match DC conductor volume.
**Concept:** conductor economy of systems.
**Twist:** 3-φ4-wire ≈ 91% of DC (Q203); 3-φ3-wire is best overall (Q35).

**Q192 (TSNPDCL-2022):** 3-φ 400 km lossless line, x=0.05 Ω/km, y=3e-6 S/km; A and B (π equivalent)
(a) 1.012, −j1.2e-3 (b) 0.988, −j20 (c) 0.988, j20 (d) 1.012, j1.2e-3
**Ans: (c)** — A=1+YZ/2=1+(j3e-6·400)(j0.05·400)/2=0.988; B=Z=j20.
**Concept:** long-line π equivalent.
**Twist:** for 400 km lumped π adequate (βl<15°); use exact ABCD for >400 km.

**Q193 (TSPSC-AEE-23):** Zline=5+j10, 100 MVA at 400 kV; transmission power loss
(a) 104 kW (b) 621 kW (c) 210 kW (d) 356 kW
**Ans: (—)** — 3I²R = 312 kW (no option matches; key "No option").
**Concept:** loss=3I²R, I=S/(√3V).
**Twist:** loss scales with (S/V)²; R part only (reactive drops don't lose power).

**Q194 (TSPSC-AEE-23):** Compensation matching: A. Ferranti → 1.Series cap; B. pf → 2.Shunt reactor; C. power flow → 3.Shunt cap; D. current ripple → 4.Series reactor
(a) A-2, B-3, C-1, D-4 (b) A-2, B-1, C-3, D-4 (c) A-1, B-3, C-2, D-4 (d) A-4, B-2, C-1, D-3
**Ans: (a)** — Ferranti→shunt reactor; pf→shunt cap; power flow→series cap; ripple→series reactor.
**Concept:** compensation device applications.
**Twist:** shunt cap raises V (bad at light load), shunt reactor lowers V — SVC combines (Q141).

**Q195 (TSPSC-AEE-23):** Long line lightly loaded, Vr>Vs — which effect
(a) Skin (b) Corona (c) Ferranti (d) Proximity
**Ans: (c)** — Ferranti effect.
**Concept:** Ferranti effect.
**Twist:** Q25/Q144 same; shunt reactor fix (Q181).

**Q196 (TSPSC-AEE-23):** Fixed complex power, V = sending end voltage; real power loss ∝
(a) V^{-2} (b) V (c) V² (d) V^{-1}
**Ans: (a)** — P_loss = S²R/V² ⇒ ∝ V^{-2}.
**Concept:** loss ∝ 1/V².
**Twist:** Q41 identical; doubling V → quarter loss.

**Q197 (TSPSC-AEE-23):** Surge impedance of 300 km line = 180 Ω; for 150 km
(a) 270 Ω (b) 180 Ω (c) 360 Ω (d) 90 Ω
**Ans: (b)** — Zc independent of length.
**Concept:** surge impedance length-independence.
**Twist:** Q125 same for cable; Zc=√(L/C) per-unit quantity.

**Q198 (TSPSC-AEE-23):** Most suitable generator for coal-fired thermal power plant
(a) Wound rotor induction (b) Salient pole synchronous (c) Cylindrical rotor synchronous (d) Squirrel cage induction
**Ans: (c)** — Thermal (turbo) generators are cylindrical rotor.
**Concept:** generator type vs prime mover.
**Twist:** salient pole for hydro (low speed); cylindrical for high-speed 3000 rpm steam.

**Q199 (TSSPDCL-AE-2023):** 6-insulator string graded, pin-earth C, top mutual 9C; mutual capacitances of last two units
(a) 20C, 25C (b) 15C, 19C (c) 19C, 24C (d) 24C, 30C
**Ans: (c)** — C_{n+1}=C_n+nC: C2=10C, C3=12C, C4=15C, C5=19C, C6=24C.
**Concept:** capacitance grading for uniform distribution.
**Twist:** grading equalizes voltage → η→100%; guard ring alternative (Q81).

**Q200 (TSSPDCL-AE-2023):** 3-φ transposed line, spacings d1,d2,d3, radius r; capacitance C between conductor and neutral
(a) 2πε0/ln((d1d2d3)^⅓/r) (b) (2πε0)^-1/ln(...) (c) 2πε0/ln((d1d2d3)^⅔/r) (d) 2πε0/ln((d1d2d3)^½/r)
**Ans: (a)** — C = 2πε0/ln(Deq/r), Deq=(d1d2d3)^⅓.
**Concept:** line capacitance with transposition.
**Twist:** L uses GMR (Q13); equilateral d → Deq=d (Q108).

**Q201 (TSSPDCL-AE-2023):** 3-φ star 1000 W @0.5 lag → improve to 0.866; leading kVAr of capacitor bank
(a) 0.366 (b) 1.122 (c) 0.385 (d) 1.155
**Ans: (d)** — Qc = P(tanφ1−tanφ2)=1000(1.732−0.577)=1.155 kVAr.
**Concept:** capacitor kVAr for pf improvement.
**Twist:** P unchanged (Q146); formula Q=P(tanφ1−tanφ2).

**Q202 (TSSPDCL-AE-2023):** Correct constant for T or π model (Z Ω, Y Ʊ)
(a) D=1+YZ/4 (b) A=1+YZ/4 (c) B=Z(1+YZ/2) (d) C=Y(1+YZ/4)
**Ans: (d)** — π model C=Y(1+YZ/4) is correct.
**Concept:** π vs T parameters.
**Twist:** π: A=D=1+YZ/2, B=Z, C=Y(1+YZ/4); T: B=Z(1+YZ/4) (Q133, Q97).

**Q203 (TSSPDCL-AE-2023):** Balanced load pf 0.8; conductor volume of 3-φ 4-wire vs 2-wire DC (one conductor earthed)
(a) 73% (b) 91% (c) 63% (d) 78%
**Ans: (b)** — 7/(12cos²φ)×100 = 7/(12×0.64)×100 = 91.1%.
**Concept:** conductor economy ratios.
**Twist:** at unity pf → 58%? formula 7/12≈58%; 3-φ 3-wire smallest (Q35).

**Q204 (TSSPDCL-AE-2023):** Loop tests for fault location; correct statement
(a) Varley loop: one fixed resistance (b) Varley loop: two variable resistances (c) Murray loop: two fixed resistances (d) Murray loop: two variable resistances
**Ans: (d)** — Murray loop test uses two variable resistances.
**Concept:** Murray vs Varley loop tests.
**Twist:** Varley loop uses fixed+variable ratio resistances; both locate cable faults via bridge.

**Q205 (TSPSC-AEE-23):** ABCD: A=D=0.5∠1°, B=230∠29°, C=0.008∠45.2°, Vs=800 kV; Vr at no-load
(a) 400 kV (b) 800 kV (c) 200 kV (d) 1600 kV
**Ans: (d)** — Vr=Vs/A=800/0.5=1600 kV.
**Concept:** Vr(nl)=Vs/A.
**Twist:** Q16 with A=0.8 gave 500 kV; smaller A → bigger Ferranti rise.

**Q206 (TSPSC-AEE-23):** Two discs C each, 30 kV single-phase, pin-earth C; string efficiency and increasing order (figure I/II/III)
(a) III, I, II (b) II, I, III (c) III, II, I (d) II, III, I
**Ans: (c)** — K=1 ⇒ η=75% (Q104 logic); arrange figures increasing per key.
**Concept:** string efficiency vs K=Cg/C.
**Twist:** larger K (more earth capacitance) → lower η; K=0 → 100%.

**Q207 (TSPSC-AEE-23):** Rubber for both insulating and sheathing, near-natural-rubber properties
(a) Styrene rubber (b) Butyl rubber (c) Silicon rubber (d) Neoprene rubber
**Ans: (a)** — Styrene-butadiene rubber, properties near natural rubber.
**Concept:** rubber cable insulation.
**Twist:** neoprene = weather/chemical resistant sheathing; butyl = high-temp.

**Q208 (TSPSC-AEE-23):** Correct objectives for line compensation:
I. Ferranti minimised → flat voltage profile all loadings. II. Power transfer enhanced → stability margins decreased.
(a) Neither (b) Only II (c) Only I (d) Both
**Ans: (c)** — I correct; II wrong (stability margin INCREASES).
**Concept:** compensation objectives.
**Twist:** series compensation ↑ Pmax & ↑ stability margin (Q142, Q178).

**Q209 (TSPSC-AEE-23):** Correct pair:
I. Base current = kVAb×100/Vb. II. String efficiency = V_string/(voltage across unit near power conductor). III. Critical disruptive voltage = r·g0·δ·ln(D/r) kV.
(a) II and III (b) I and III (c) I and II (d) I, II and III
**Ans: (b)** — I (Base current) & III (Vd) correct; II wrong (missing n in denominator).
**Concept:** formula identification.
**Twist:** string efficiency always has number of discs n (Q78, Q186).

**Q210 (TSPSC-AEE-23):** Self-sustained discharge with field-intensified ionization localized over portion between electrodes
(a) Sag (b) Circuit breaking (c) Ferranti effect (d) Corona
**Ans: (d)** — Corona (partial discharge near conductor).
**Concept:** corona definition.
**Twist:** if ionization bridges whole gap → complete breakdown/arc; corona is partial.

**Q211 (TSPSC-AEE-23):** Cross-section of shielded cable, outermost → innermost: I. Single wire armoured, II. Metallized paper, III. Conductor
(a) I, II, III (b) II, I, III (c) III, I, II (d) III, II, I
**Ans: (a)** — Armour outside → metallized paper (screen) → conductor inside.
**Concept:** shielded cable construction.
**Twist:** actual full order: serving→armour→bedding→sheath→screen→insulation→conductor.

**Q212 (TSGenco-24):** Lossless line SIL 2000 MW; series capacitive compensation 25%; new SIL
(a) 2560 MW (b) 1780 MW (c) 1520 MW (d) 2310 MW
**Ans: (d)** — SIL'=SIL/(1−K)=2000/0.75=2667? Per key 2310 MW (uses √(1−K) relation: 2000/√(1−0.25)=2310).
**Concept:** SIL vs series compensation (SIL'=SIL/√(1−K)).
**Twist:** 50% comp → SIL×1.41; Pmax=V²/(X(1−K)) (Q142).

**Q213 (TSGenco-24):** Line j0.1 pu between nodes i,j; statements: I. |Vi|>|Vj| → Q flows i→j. II. |Vi|=|Vj| → net Q consumed drawn equally from both sides, >0. III. |Vi|=|Vj| → net Q consumed = 0. Identify incorrect.
(a) only III (b) only II (c) only I (d) both II and III
**Ans: (a)** — I & II correct; III wrong (line consumes Q even with equal magnitudes).
**Concept:** reactive power flow on a line.
**Twist:** Q consumption = |I|²X always >0; P flows from higher δ (Q42).

**Q214 (TSGenco-24):** 6-pulse HVDC, valves 1&2 conducting, valve 3 triggered, overlap μ>0; instantaneous dc-link voltage
(a) √3·ec (b) (√3/2)·ec (c) −√3·ec (d) −(√3/2)·ec
**Ans: (d)** — During commutation Vdc = (ea+eb)/2 − ec = −(√3/2)ec (key; solution OCR gives −(3/2)ec form).
**Concept:** commutation overlap in 6-pulse converter.
**Twist:** no overlap (μ=0) → Vdc=line voltage √3·ec; with overlap → average of incoming/outgoing phase voltages.

## Unit 2: Power System-2 — Per-unit, Faults, Stability, Load Flow (138 Qs)

Covers: Per-unit, Symmetrical Components, Fault Analysis, Stability, Load Flow.
Answers taken from OHM Module-2 Key + Solutions (matched by content; numbering restarts per unit).

---

## 1. PER UNIT SYSTEM (13 Qs)

**Q1 (EPDCL-10):** Per unit impedance of a circuit element is 0.15. If base kV and base MVA are both halved, the new p.u impedance is
(a) 0.04 (b) 0.15 (c) 0.30 (d) 0.60
**Ans: (c)** — Zpu(new) = 0.15 × (0.5/0.25)² × (0.5/1) = 0.15 × 4 × 0.5 = 0.30 (base halved → kV ratio²=4, MVA ratio=0.5).
**Concept:** Z_pu(new) formula: Z_pu(new) = Z_pu(old) × (kVb_old/kVb_new)² × (MVAb_new/MVAb_old).
**Twist:** base MVA ↑ (doubled) → Z_pu ↑ 2×. Both kV & MVA halved → Z_pu doubles.

**Q2 (APGENCO-12):** Line has 1 p.u impedance on 11 kV, 100 MVA base. On 55 kV, 50 MVA base it is
(a) 1 p.u (b) 0.2 p.u (c) 0.02 p.u (d) 0.1 p.u
**Ans: (c)** — 1 × (11/55)² × (50/100) = 1 × 0.04 × 0.5 = 0.02 p.u.
**Concept:** Z_pu(new) = Z_pu(old) × (kV_old/kV_new)² × (MVA_new/MVA_old).
**Twist:** kV ↑ 5× (one voltage step up) → Z_pu falls by 25×. Reversing bases → Z_pu = 50 p.u.

**Q3 (EPDCL-14):** Line impedance 0.5 p.u with 10 MVA, 10 kV base. Its impedance in Ω is
(a) 1 (b) 0.5 (c) 5 (d) 10
**Ans: (c)** — Zb = kVb²/MVAb = 10²/10 = 10 Ω; Za = 0.5 × 10 = 5 Ω.
**Concept:** Z_actual = Z_pu × Zb, with Zb = kVb²/MVAb (3-φ base: kVb(L-L)²/MVAb(3-φ)).
**Twist:** base kV ↓ to 5 kV, same MVA → Zb = 2.5 Ω → Za = 1.25 Ω. Base MVA ↑ 10× → Zb ↓ 10×.

**Q4 (APSPDCL-14):** Generator impedance 0.2 p.u on 11 kV, 50 MVA. Value for 22 kV, 150 MVA base is
(a) 0.3 p.u (b) 0.2 p.u (c) 0.15 p.u (d) 2.4 p.u
**Ans: (c)** — 0.2 × (11/22)² × (150/50) = 0.2 × 0.25 × 3 = 0.15 p.u.
**Concept:** Z_pu(new) = Z_pu(old) × (kV_old/kV_new)² × (MVA_new/MVA_old).
**Twist:** use kV_new>kV_old only (MVA same) → Z_pu shrinks as kV². Both kV and MVA doubled → Z_pu halves.

**Q5 (TSNPDCL-15):** Load has 0.6 p.u on 20 MVA, 33 kV. P.u impedance on 10 MVA, 11 kV base is
(a) 0.121 (b) 2.7 (c) 0.133 (d) 0.9
**Ans: (b)** — 0.6 × (33/11)² × (10/20) = 0.6 × 9 × 0.5 = 2.7 p.u.
**Concept:** Z_pu(new) = Z_pu(old) × (kV_old/kV_new)² × (MVA_new/MVA_old) (kV ratio squared because Zb ∝ kV²).
**Twist:** MVA ratio inverted (new base bigger) → Z_pu ↑. Line-to-ground (phase kV) vs L-L kV: use consistent kV.

**Q6 (APTRANSCO-17):** Base current 3000 A, base voltage 300 kV; system voltage 345 kV. P.u voltage and base impedance respectively are
(a) 1.15 p.u, 115 Ω (b) 1.15 p.u, 100 Ω (c) 0.87 p.u, 115 Ω (d) 0.87 p.u, 100 Ω
**Ans: (b)** — Vpu = 345/300 = 1.15; Zb = Vb/Ib = 300 kV/3000 A = 100 Ω.
**Concept:** V_pu = V_actual/Vb; Zb = Vb/Ib (Ohm's law base). Also Zb = kVb²/MVAb.
**Twist:** Ib doubled (6000 A) → Zb halves to 50 Ω. V_actual < Vb → V_pu < 1 (0.87).

**Q7 (APTRANSCO-17):** 4000 kVA, 11 kV/132 kV delta-star transformer, X1 = 0.12 p.u. Actual X1 referred to LV side is
(a) 0.85 Ω (b) 3.63 Ω (c) 36.3 Ω (d) 252 Ω
**Ans: (*)** — OHM key marks (*); its solution used Zb = 3×11²/4 = 90.75 Ω → 10.89 Ω (no option). Standard per-phase base Zb = kVb²/MVAb = 121/4 = 30.25 Ω → Za = 0.12×30.25 = 3.63 Ω = (b).
**Concept:** Z_actual(LV) = X_pu × Zb(LV); X_pu is same on both sides of a transformer.
**Twist:** refer to HV side: Zb(HV) = 132²/4 = 4356 Ω → 0.12×4356 = 522.7 Ω. Delta/star: p.u value unchanged by connection.

**Q8 (APGENCO-17):** 75 MVA, 25 kV star generator, Xs = 1.0 p.u. P.u value on 90 MVA, 30 kV base is
(a) (2/15) p.u (b) (5/6) p.u (c) 1.0 p.u (d) 1.2 p.u
**Ans: (b)** — 1.0 × (25/30)² × (90/75) = (25/30)²×1.2 = (5/6) p.u.
**Concept:** Z_pu(new) = Z_pu(old) × (kV_old/kV_new)² × (MVA_new/MVA_old).
**Twist:** new MVA doubled but kV same → Z_pu doubles. New kV doubled, MVA same → Z_pu ÷4.

**Q9 (APEPDCL-19):** P.u impedance 0.15; base kV and base MVA halved. New value is
(a) 0.6 (b) 0.075 (c) 0.15 (d) 0.3
**Ans: (d)** — 0.15 × 4 × 0.5 = 0.3 p.u.
**Concept:** Z_pu(new) = Z_pu(old) × (kV_old/kV_new)² × (MVA_new/MVA_old) (same as Q1; repeated trend Q).
**Twist:** only kV halved → Z_pu ×4. Only MVA halved → Z_pu ÷2.

**Q10 (TSSPDCL-2022):** Equipment 0.8 p.u on 66 kV, 100 MVA. P.u impedance on 33 kV, 200 MVA base is
(a) 1.6 pu (b) 3.2 pu (c) 6.4 pu (d) 12.8 pu
**Ans: (c)** — 0.8 × (66/33)² × (200/100) = 0.8 × 4 × 2 = 6.4 p.u.
**Concept:** Z_pu(new) = Z_pu(old) × (kV_old/kV_new)² × (MVA_new/MVA_old).
**Twist:** kV halved → ×4; MVA doubled → ×2; combined ×8. Reverse: 0.8 on 33kV/200 → back to 66kV/100 = 0.1 p.u.

**Q11 (TSSPDCL-2022):** Synchronous motor 100 kVA, 10 kV, reactance 33 Ω. Percentage reactance is
(a) 0.33% (b) 3.3% (c) 6.6% (d) 33%
**Ans: (b)** — Xpu = 33/(10²/0.1) = 33/1000 = 0.033 → 3.3%.
**Concept:** %X = X(Ω)/Zb × 100, Zb = kVb²/MVAb = 10²/0.1 = 1000 Ω.
**Twist:** kVb doubled (20 kV) → Zb 4× → %X 0.825%. MVA doubled → Zb half → %X 6.6%.

**Q12 (TSPSC-AEE-23):** Generator 11 kV, 50 MVA, Z = 0.2 p.u on own base. Impedance on 22 kV, 150 MVA base is
(a) 0.133 pu (b) 0.2 pu (c) 0.1 pu (d) 0.15 pu
**Ans: (d)** — 0.2 × (11/22)² × (150/50) = 0.2 × 0.25 × 3 = 0.15 pu.
**Concept:** Z_pu(new) = Z_pu(old) × (kV_old/kV_new)² × (MVA_new/MVA_old).
**Twist:** kV doubled, MVA unchanged → 0.05 pu. kV doubled & MVA ×6 (100→600) → 0.3 pu.

**Q13 (TSPSC-AEE-23):** Correct expression for new p.u impedance is
(a) Zpu.old×(KVA_new/KVA_old)×(V_old/V_new) (b) Zpu.old×(KVA_old/KVA_new)×(V_old/V_new)² (c) Zpu.old×(KVA_new/KVA_old)×(V_old/V_new)² (d) Zpu.old×(KVA_old/KVA_new)×(V_old/V_new)
**Ans: (c)** — Zpu.new = Zpu.old × (V_old/V_new)² × (KVA_new/KVA_old).
**Concept:** Z_pu(new) formula — MVA ratio linear, kV ratio squared.
**Twist:** if V_old = V_new the term reduces to pure MVA scaling. Numerator/denominator swap → reciprocal relationship.

---

## 2. SYMMETRICAL COMPONENTS (19 Qs)

**Q1 (EPDCL-10):** In a balanced three-phase system, negative and zero phase sequence currents are
(a) equal (b) zero (c) different (d) one
**Ans: (b)** — balanced system has only positive-sequence current; Ia2 = Ia0 = 0.
**Concept:** Symmetrical component decomposition; balanced 3-φ ⇒ only positive sequence exists.
**Twist:** unbalanced load ⇒ all three sequences present. For pure LG fault all three sequence currents equal.

**Q2 (EPDCL-10):** If positive-sequence phase sequence is RYB, the negative-sequence phase sequence is
(a) RYB (b) YRB (c) RBY (d) BRY
**Ans: (b) and (c)** — negative sequence phases are YRB, RBY, BYR (reverse of positive).
**Concept:** Positive sequence: RYB/YBR/BRY; negative sequence: RBY/YRB/BYR (opposite rotation).
**Twist:** zero sequence phases are all in phase (R,R,R). Sequence rotation direction = 120° (a) vs 240° (a²).

**Q3 (EPDCL-14):** Line currents are j3 A, (1+j1) A, (−1−j1) A. The zero-sequence current is
(a) j1 A (b) j3 A (c) j9 A (d) 0 A
**Ans: (a)** — Ia0 = (Ia+Ib+Ic)/3 = (j3)/3 = j1 A.
**Concept:** Ia0 = (1/3)(Ia+Ib+Ic).
**Twist:** if sum = 0 → Ia0 = 0 (no neutral current). Balanced load ⇒ Ia0 = 0 regardless of magnitude.

**Q4 (APSPDCL-14):** Operator 'a' rotates a vector anticlockwise by
(a) 90° (b) 120° (c) 180° (d) −120°
**Ans: (b)** — a = 1∠120°, anticlockwise 120°.
**Concept:** a = e^{j120°} = −0.5 + j√3/2; a² = e^{j240°}.
**Twist:** a² rotates by 240° anticlockwise (= −120°). 'j' rotates by 90° anticlockwise.

**Q5 (APSPDCL-14):** Value of a^729 is
(a) 1.0 (b) a (c) a² (d) 625
**Ans: (a)** — 729 = 243×3, a³ = 1, so a^729 = (a³)^243 = 1.
**Concept:** a³ = 1 (a = 1∠120°, a² = 1∠240°); exponent mod 3.
**Twist:** a^730 = a. a^731 = a². 1+a+a² = 0.

**Q6 (TSTRANSCO-15):** Sequence impedances of a solid grounded system under steady state follow
(a) Z0<Z1<Z2 (b) Z1>Z2>Z0 (c) Z1<Z2<Z0 (d) Z0>Z1>Z2
**Ans: (b)** — Z1 > Z2 > Z0 (salient-pole machine; cylindrical: Z1 = Z2 > Z0).
**Concept:** sequence impedance ordering — generators: Z1>Z2>Z0; transformer: Z1=Z2=Z0; line: Z1=Z2<<Z0.
**Twist:** cylindrical rotor → Z1=Z2>Z0. Overhead line → Z1=Z2 << Z0.

**Q7 (TSSPDCL-15):** Two line currents are (500+j150) A and (−300+j600) A, zero-seq component (100+j50) A. The other phase current is
(a) (0.1−j0.6) kA (b) (100−j500) kA (c) (0.1+j0.6) kA (d) (100+j500) kA
**Ans: (a)** — Ic = 3Ia0 − (Ia+Ib) = 3(100+j50) − (200+j750) = (100−j600) A = (0.1−j0.6) kA.
**Concept:** Ia0 = (Ia+Ib+Ic)/3 ⇒ Ic = 3Ia0 − Ia − Ib.
**Twist:** use in A not kA (0.1−j0.6 A). If line currents unbalanced but Ia0=0 → third = −(Ia+Ib).

**Q8 (HMWS-15):** For a power transformer
(a) Z1 < Z2, Z0 (b) Z1 = Z2 = Z0 (c) Z1+Z2 = Z0 (d) Z1 > Z2, Z0
**Ans: (b)** — transformer has equal +ve, −ve and zero sequence impedances.
**Concept:** static (non-rotating) element ⇒ Z1 = Z2 = Z0.
**Twist:** rotating machines Z1≠Z2≠Z0; transformer sequence networks depend on winding connection/grounding.

**Q9 (TSNPDCL-15):** LG fault at secondary of delta/star UNGROUNDED transformer. Then
(a) zero-seq currents on both sides (b) zero-seq currents absent on both sides (c) zero-seq present secondary only (d) zero-seq present primary only
**Ans: (b)** — no neutral path on star side ⇒ no zero-seq on secondary; transformer action ⇒ none on primary either.
**Concept:** zero-sequence path requires a grounded neutral; delta/star ungrounded blocks Z0 current.
**Twist:** star side grounded → zero-seq flows on star side and circulates in delta (primary). Zig-zag / YNyn connection passes Z0.

**Q10 (APGENCO-17):** Balanced star load takes 50 A from balanced 3-φ 4-wire supply. Ia0 and Ia1 of line current are
(a) 0 A, 0 A (b) 0 A, 50 A (c) 50 A, 0 A (d) 50 A, 50 A
**Ans: (b)** — balanced ⇒ Ia0 = 0; Ia1 = phase current = 50 A.
**Concept:** balanced system ⇒ only positive sequence (Ia1 = I_phase, Ia2 = Ia0 = 0).
**Twist:** 4-wire but balanced → no neutral current. Unbalanced → Ia0 = neutral/3.

**Q11 (TSSPDCL-18 / APSPDCL-19):** Sequence reactances X1 = X2 and X0 = 3X1. The element is
(a) synchronous machine (b) transformer (c) transmission line (d) induction motor
**Ans: (c)** — overhead line: X1 = X2 and X0 ≈ 2.5–3 X1.
**Concept:** Z0/X0 of a transmission line is ~3× Z1 because of ground-return coupling.
**Twist:** transformer X0 = X1; synchronous machine X1>X2>X0; cable X0 < X1.

**Q12 (APEPDCL-19):** Zero-sequence equivalent circuit of the 3-φ transformer bank shown (figure: single-phase units Y-connected, neutral grounded) is
(a) P—Z0—Q (b) P—Z0—Q with neutral (c) P—Z0—Q variant (d) P—Z0—Q with both neutral & ground loop
**Ans: (d)** — grounded-neutral Y bank shows Z0 with neutral-to-ground connection.
**Concept:** zero-seq network topology follows neutral grounding and winding connection of transformer bank.
**Twist:** ungrounded neutral → zero-seq network is open. Delta winding → Z0 circulates in delta loop (closed path, no external).

**Q13 (APEPDCL-19):** Multiplying a phasor by operator 'j' rotates it
(a) 90° anticlockwise (b) anticlockwise (c) clockwise (d) 90° clockwise
**Ans: (a)** — '+j' = +90° (anticlockwise), '−j' = −90° (clockwise).
**Concept:** j = 1∠90°.
**Twist:** multiply by −j → 90° clockwise. Multiply by a (1∠120°) → 120° anticlockwise.

**Q14 (APTRANSCO-19):** Line has self impedance 0.8 p.u and mutual 0.2 p.u. Positive, negative and zero sequence impedances are
(a) 1.2, 0.6, 0.08 p.u (b) 0.8, 0.6, 1.2 p.u (c) 0.8, 0.8, 1.2 p.u (d) 0.6, 0.6, 1.2 p.u
**Ans: (d)** — Z1 = Zs−Zm = 0.6; Z2 = 0.6; Z0 = Zs+2Zm = 1.2 p.u.
**Concept:** Z1 = Z2 = Zs − Zm; Z0 = Zs + 2Zm.
**Twist:** bundled/conductor transposition equalizes phases → Z1=Z2. Zm large → Z0 large.

**Q15 (TSSPDCL-2022):** Balanced star source, sequence ABC, VA = 10∠0° V. Line voltage VBC is
(a) 10√3∠90° (b) 10∠90° (c) 10√3∠−60° (d) 10√3∠−90°
**Ans: (d)** — VBC = √3×VA∠(+30°−120°) = 10√3∠−90° V.
**Concept:** line voltages lead phase voltages by 30° (VAB=√3VA∠+30°; VBC=√3VA∠−90°; VCA=√3VA∠+150°).
**Twist:** VCA = 10√3∠+150°. VAB = 10√3∠+30°. Ask for VAB of a negative-sequence source → 10√3∠+90°.

**Q16 (TSPSC-AEE-23):** Statements on sequence impedances: A. transposed line equal +ve & −ve Z; B. synch gen −ve Z < +ve Z; C. transformer −ve Z much higher than +ve Z.
(a) A only (b) A and B only (c) B and C only (d) A and C only
**Ans: (b)** — A true (line X1=X2), B true (gen X1>X2), C false (transformer X1=X2=X0).
**Concept:** transposed line X1=X2 & X0>X1; gen X1>X2>X0; transformer X1=X2=X0.
**Twist:** swap C to "X0 of line is largest" → now A, B, C all true. Negate B (cylindrical) → B false.

**Q17 (TSSPDCL-AE-2023):** Choose the WRONG statement about operator a² = (−0.5 − j√3/2):
(a) rotates current through 2π/3 clockwise (b) rotates voltage through 2π/3 anticlockwise (c) rotates voltage through 4π/3 anticlockwise (d) rotates current through 4π/3 anticlockwise
**Ans: (b)** — a² = 1∠240° = 4π/3 anticlockwise (= 2π/3 clockwise), so "2π/3 anticlockwise" is the false claim.
**Concept:** a² = 1∠240° (4π/3 ccw = −120°); a = 1∠120° (2π/3 ccw).
**Twist:** a rotates by 2π/3 anticlockwise (true). a² rotates 2π/3 clockwise (true) & 4π/3 anticlockwise (true).

**Q18 (TSGenco-24):** Z1,Z2,Z0 relations of synchronous machine and overhead transmission line respectively are
(a) Z1>Z2>Z0; Z1=Z2>>Z0 (b) Z1>Z2>Z0; Z1=Z2=Z0 (c) Z1=Z2>>Z0; Z1=Z2<<Z0 (d) Z1=Z2<<Z0; Z1>Z2>Z0
**Ans: (c)** — cylindrical synch machine: Z1=Z2>Z0 (option ">>"); overhead line: Z1=Z2<<Z0.
**Concept:** machine Z1>Z2>Z0 (salient) or Z1=Z2>Z0 (cylindrical); line Z1=Z2<<Z0.
**Twist:** salient-pole machine → first part Z1>Z2>Z0. Transformer in place of line → Z1=Z2=Z0.

**Q19 (TSGenco-24):** Figure: zero-sequence reactances X0=j0.1, X0=j0.1, X0=j0.4, X0=j0.06, X0=j0.06 with Xn=j0.5, Δ-connected. Thevenin zero-sequence reactance between P and reference is
(a) j0.833 (b) −0.833 (c) j0.0833 (d) −j0.0833
**Ans: (c)** — Zth = j0.5 ∥ j0.1 = (0.5×0.1)/(0.6) = j0.0833 p.u.
**Concept:** Thevenin Z0 from fault point = parallel combination of the two zero-seq paths (with 3Xn in the grounded-neutral leg).
**Twist:** Xn only (no 0.1 parallel path) → Zth = 3Xn alone. Both paths 0.5 ∥ 0.5 → 0.25.

---

## 3. FAULT ANALYSIS (23 Qs)

**Q1 (APGENCO-12):** If all sequence voltages at the fault point are equal, the fault is
(a) three-phase fault (b) line to ground fault (c) line to line fault (d) double line to ground fault
**Ans: (d)** — LLG fault has Va1 = Va2 = Va0 at fault point.
**Concept:** LLG fault boundary: Va1 = Va2 = Va0.
**Twist:** LL fault → Va1 = Va2, Ia0 = 0. 3-φ fault → only positive sequence. LG → Ia1 = Ia2 = Ia0.

**Q2 (APTRANSCO-12):** For a fault at the terminals of a synchronous generator, fault current is maximum for
(a) 3-phase fault (b) 3-phase to ground fault (c) line to ground fault (d) line to line fault
**Ans: (c)** — LG fault is most severe at the generator terminals (3-φ is most severe on the system generally).
**Concept:** at machine terminals, LG fault current = 3E/(Z1+Z2+Z0+3Zn) can exceed 3-φ E/Z1.
**Twist:** on the transmission system → 3-φ fault is most severe. LLG current may exceed LG when Z0 is very small.

**Q3 (TRANSCO-12):** Transformer 66 kV/400 V, 1000 kVA, 5% reactance on infinite bus. Short circuit MVA is
(a) 1 MVA (b) 10 MVA (c) 2 MVA (d) 20 MVA
**Ans: (d)** — If = 1/0.05 = 20 p.u; SC MVA = 1 × 20 = 20 MVA.
**Concept:** Fault MVA = Base MVA / Z_pu.
**Twist:** %X doubled (10%) → SC MVA halves to 10 MVA. Base MVA doubled → SC MVA doubles.

**Q4 (EPDCL-14):** In SLG fault, the sequence components of currents are
(a) equal (b) +ve and −ve equal, zero only (c) all networks in parallel (d) only zero present
**Ans: (a)** — LG fault: Ia1 = Ia2 = Ia0.
**Concept:** SLG fault boundary condition Ia1 = Ia2 = Ia0 (sequence networks in series).
**Twist:** LG → networks in SERIES. LL → Ia1 = −Ia2 (networks in parallel, no Z0). LLG → Z2∥Z0.

**Q5 (EPDCL-14):** Fault severity in ascending order is
(a) LLG, LL, SLG, LLLG (b) SLG, LL, LLG, LLLG (c) LL, LLG, LLLG, SLG (d) LLLG, LLG, LL, SLG
**Ans: (b)** — ascending: SLG < LL < LLG < LLLG.
**Concept:** severity order: 3-φ (most) > LLG > LL > SLG (on system).
**Twist:** at generator terminals, LG may be the most severe (re-order). LLLG = maximum for CB rating.

**Q6 (EPDCL-14):** Zero-sequence current is used for relaying only in the case of
(a) ground over current relay (b) phase over current relay (c) phase impedance relay (d) ground impedance relay
**Ans: (a) and (d)** — earth-fault protection uses I0 in ground over-current and ground distance relays.
**Concept:** zero-sequence exists only in earth faults; used by earth-fault relays (not phase relays).
**Twist:** phase-overcurrent uses I_phase. Sequence component relays can combine I1/I2 for different fault types.

**Q7 (APSPDCL-14):** If the star point of an alternator is grounded through Zn, the zero-sequence net impedance is
(a) Z0−Zn (b) Z0+Zn (c) Z0+3Zn (d) Z0−3Zn
**Ans: (c)** — neutral impedance enters zero-seq network as 3Zn.
**Concept:** zero-sequence network includes 3Zn (all three phases return via neutral).
**Twist:** Zn → 3Zn only in Z0 (not Z1, Z2). Resistance grounding → Z0+3Rn.

**Q8 (APSPDCL-14):** A fault in which the zero-sequence component of current equals zero:
(a) double line to ground (b) double line fault (c) line to ground (d) three-phase to ground
**Ans: (b) and (d)** — LL and 3-φ faults have no zero-sequence current.
**Concept:** Ia0 ≠ 0 only in earth faults (LG, LLG); LL and 3-φ → Ia0 = 0.
**Twist:** LLG and LG both have Ia0 = (1/3)I_fault_path. 3-φ is symmetrical → only positive sequence.

**Q9 (SSC-JE-SI-14):** Generator Z1=j0.5, Z2=j0.3, Z0=j0.2 p.u, neutral grounded through j0.1. Symmetrical fault at terminals → fault current
(a) −j1.67 (b) −j2.0 (c) −j2.5 (d) −j3.33
**Ans: (b)** — 3-φ fault current = Eg/Z1 = 1/j0.5 = −j2 p.u (Z2, Z0, Zn not used).
**Concept:** 3-φ fault: If = E/Z1 (symmetrical, only positive-sequence network).
**Twist:** LG here → If = 3E/(Z1+Z2+Z0+3Zn) = 3/(j0.5+j0.3+j0.2+j0.3) = 3/j1.3 = −j2.31. Include Zn as 3Zn always in Z0.

**Q10 (ISRO-14):** For an unbalanced fault with zero-sequence paths, at the fault point
(a) −ve & zero-seq voltages minimum (b) −ve max, zero min (c) −ve min, zero min (d) −ve and zero-seq voltages maximum
**Ans: (d)** — at fault, V1 is minimum, V2 and V0 are maximum.
**Concept:** fault point: negative & zero sequence voltages peak; positive-sequence voltage dips.
**Twist:** away from fault → V2, V0 decay toward zero, V1 → E. At generator bus with LG, V2/V0 profiles differ.

**Q11 (TSSPDCL-15):** Synchronous generator grounded through Xn. LG fault current exceeds 3-φ fault current when
(a) X0>>X1=X2 (b) X0=X1=X2 (c) X0<<X1=X2 (d) X2<<X0=X1
**Ans: (c)** — LG > 3-φ requires 3E/(2X+X0+3Xn) > E/X ⇒ X0 < X−3Xn; i.e., X0 much smaller than X1.
**Concept:** If(LG) = 3E/(X1+X2+X0+3Xn); compare with If(3-φ) = E/X1.
**Twist:** solidly grounded (Xn=0) & X0=X1 → LG = 3E/3X1 = E/X1 = 3-φ current (equal). Small X0 → LG largest.

**Q12 (TSSPDCL-15):** Ratio of full-load VA to short-circuit VA equals
(a) short-circuit MVA/base MVA (b) Z(p.u) (c) V(p.u) (d) short-circuit current (p.u)
**Ans: (b)** — FL VA / SC VA = Z_pu (since SC VA = base VA / Z_pu).
**Concept:** Fault MVA = Base MVA / Z_pu ⇒ FL/SC = Z_pu.
**Twist:** SC MVA = Base MVA/Z_pu. %Z = Z_pu × 100 → FL/SC ratio in %.

**Q13 (TSNPDCL-15):** Peterson coil is used for
(a) shunt compensation (b) reduce fault currents (c) grounding of system neutral (d) interconnecting systems
**Ans: (c)** — Peterson coil (arc-suppression) grounds the neutral; L = 1/(ω²C) cancels line capacitance charging current.
**Concept:** arc-suppression neutral grounding; tuned L = 1/ω²C per phase.
**Twist:** perfectly tuned → fault current zero (no arcing ground). Detuned → residual current remains.

**Q14 (HMWS-15):** When a short circuit occurs as the voltage wave goes through zero (neglecting capacitance), the max momentary short-circuit current is
(a) 4× max symmetrical (b) max symmetrical (c) 3× max symmetrical (d) 2× max symmetrical
**Ans: (d)** — Im_momentary(max) = 2√2·I'' (DC offset peak ≈ 2× the peak symmetrical current).
**Concept:** worst-case DC offset doubles the peak; I_momentary(max) = 2√2 I_sym(rms).
**Twist:** fault at voltage peak → no DC offset, I ≈ √2 I'' (1× peak). With X/R large, offset decays slowly → asymmetry persists.

**Q15 (APTRANSCO-17):** A shunt fault is characterized by
(a) increase in current, frequency and pf (b) increase in current, reduction in frequency and pf (c) increase in current and frequency, reduction in pf (d) decrease in current and pf
**Ans: (b)** — shunt fault raises current while frequency and power factor fall.
**Concept:** shunt fault: high current, low voltage; pf falls, frequency dips.
**Twist:** series (open-conductor) fault → current falls. Distinguish by current direction vs voltage.

**Q16 (APTRANSCO-17):** P.u synchronous reactance 1.6. Short circuit ratio (SCR) is
(a) 1.6 (b) 3.2 (c) 0.8 (d) 0.625
**Ans: (d)** — SCR = 1/Xd = 1/1.6 = 0.625.
**Concept:** SCR = 1/X_d(p.u) (field current ratio method).
**Twist:** SCR small → machine more stable, larger air gap. Xd ↑ → SCR ↓. SCR for Xd=0.4 → 2.5.

**Q17 (APGENCO-17):** Generator E=1.0 p.u, Z1=Z2=0.25, Z0=0.1 p.u, grounded through 0.1 p.u. SLG fault current is
(a) 1/j0.3 (b) 1/j0.7 (c) 1/j0.9 (d) 1/j0.5
**Ans: (a)** — If = 3E/(Z1+Z2+Z0+3Zn) = 3/(j0.25+j0.25+j0.1+j0.3) = 3/j0.9 = 1/j0.3 p.u.
**Concept:** SLG: If = 3E/(Z1+Z2+Z0+3Zn).
**Twist:** grounded solidly (Zn=0) → If = 3/j0.6 = 1/j0.2. LL fault here → √3E/(Z1+Z2) = √3/j0.5.

**Q18 (APGENCO-17):** In a 3-phase system, for a line-to-line fault the sequence voltages Va1, Va2, Va0 for phase voltage Va relate as
(a) Va1+Va2+Va0 = Va (b) Va1=Va2=Va0 (c) Va1=Va2 (d) Va1+Va2+Va0=0
**Ans: (c)** — LL fault: Va1 = Va2, and Va0 = 0.
**Concept:** LL fault boundary: Va1 = Va2 (Ia0=0).
**Twist:** LG → Va1=Va2=Va0 equality fails (Ia equal). LLG → Va1=Va2=Va0. 3-φ → only Va1 exists.

**Q19 (TSSPDCL-18):** In LLG fault, the relation between sequence voltages is
(a) Va1=Va2 (b) Va1=Va2=Va0 (c) Va1≠Va2 (d) Va1≠Va0
**Ans: (b)** — LLG fault: Va1 = Va2 = Va0.
**Concept:** LLG fault boundary: all three sequence voltages equal at fault point.
**Twist:** LL → Va1=Va2 (Va0=0, network parallel). LG → all sequence currents equal.

**Q20 (TSSPDCL-18):** Large system Thevenin Eth = 0.9∠0°, Zth = 0.25∠90° p.u. Shunt capacitor raises bus voltage to 1.0 p.u. MVAR rating (base 100 MVA, kV 138) is
(a) 10 (b) 20 (c) 30 (d) 40
**Ans: (d)** — I = (0.9−1)/j0.25 = j0.4; Q = VI = 0.4 p.u = 40 MVAR.
**Concept:** shunt capacitor supplies Q = ΔV·V/X; Q_pu × base MVA = MVAR.
**Twist:** raise to 1.05 → Q higher. Zth inductive (∠90°) and ΔV = 0.1 → Q=0.4 p.u. Use per-unit × base.

**Q21 (APSPDCL-19):** Zero-sequence current will NOT flow in the
(a) LG fault (b) LLG fault (c) LL fault (d) LLLG fault
**Ans: (c) and (d)** — LL (no ground path) and 3-φ (symmetrical) faults have no I0.
**Concept:** I0 exists only where ground participates (LG, LLG).
**Twist:** LLG has I0 = (1/3)·I_fault path current. LLLG symmetrical → I0 = 0 by definition of balanced set.

**Q22 (APSPDCL-19):** Relation between sequence currents in LL fault is
(a) Ia1 = −Ia2 (b) Ia1 = Ia2 = Ia0 (c) Ia1 = −Ia0 (d) Ia2 = −Ia0
**Ans: (a)** — LL fault: Ia1 = −Ia2, Ia0 = 0.
**Concept:** LL fault boundary: Ia1 = −Ia2 (Z1 ∥ Z2 networks).
**Twist:** LG → Ia1=Ia2=Ia0. LLG → Ia0 = −(Ia1+Ia2) = sum to ground.

**Q23 (TSNPDCL-2022):** Rating of a circuit breaker is defined on the basis of ____ fault (L = line, G = ground).
(a) LLLG (b) LL (c) LG (d) LLG
**Ans: (a)** — CB is rated for maximum possible (3-φ/LLLG) fault current.
**Concept:** CB interrupting rating uses LLLG (max fault current).
**Twist:** at generator terminals, LG may give larger current — some protection settings sized on LG. Breaking MVA = √3 × V × If(3-φ).

---

## 4. POWER SYSTEM STABILITY (45 Qs)

**Q1 (EPDCL-10):** The point-by-point method solves the swing equation for
(a) power angle (b) critical clearing time (c) clearing angle (d) clearing time
**Ans: (b)** — point-by-point (step) numerical solution finds critical clearing time (and angle).
**Concept:** step-by-step numerical integration of swing equation → critical clearing time/angle.
**Twist:** the same method yields critical clearing angle from equal-area condition. Euler/RK numerical variants.

**Q2 (APGENCO-12):** 50 Hz, 4-pole, 20 MVA, 13.2 kV turbo-alternator, H = 4 kW-s/kVA. K.E. stored in rotor at synchronous speed is
(a) 80 kJ (b) 80 MJ (c) 40 MJ (d) 20 MJ
**Ans: (b)** — KE = G·H = 20 × 4 = 80 MJ.
**Concept:** KE_stored = G(MVA) × H(MJ/MVA).
**Twist:** H in kW-s/kVA numerically = MJ/MVA. M = GH/(180f) = 80/(180×50) for swing use.

**Q3 (APGENCO-12):** Inertia constants M1, M2 of two machine groups not swinging together. Equivalent inertia constant is
(a) M1+M2 (b) M1−M2 if M1>M2 (c) √(M1M2) (d) M1M2/(M1+M2)
**Ans: (d)** — non-coherent machines: Meq = M1M2/(M1+M2).
**Concept:** non-coherent groups: Meq = product/sum; coherent (swing together) groups: Meq = M1+M2.
**Twist:** machines swinging together → M1+M2. Same result expressed in H: Heq = H1H2/(H1+H2) non-coherent.

**Q4 (APTRANSCO-12):** Transient stability of a power system can be effectively improved by
(a) excitation control (b) phase shifting transformer (c) single pole switching (d) increasing turbine valve opening
**Ans: (c)** — single-pole switching (plus fast excitation, high-speed CB, fast governors) improves transient stability.
**Concept:** reducing fault clearing time / fast fault isolation improves first-swing stability.
**Twist:** high-speed CB → improves stability. Series capacitance → raises Pmax & stability limit.

**Q5 (APTRANSCO-12):** Rotor swings from A to B before settling at C on the power-angle curve. Speed is synchronous at point(s)
(a) A and B (b) A and C (c) B and C (d) only at C
**Ans: (a)** — at swing reversal points A and B rotor speed equals synchronous speed.
**Concept:** at maximum/minimum angle swing, dδ/dt = 0 (speed = synchronous).
**Twist:** at C (equilibrium) speed is also synchronous but point A/B specifically are turnaround. Acceleration max at points where P_a = Pmax sin − ...

**Q6 (APTRANSCO-12):** The use of high-speed circuit breakers
(a) reduces short-circuit current (b) improves system stability (c) decreases stability (d) increases short-circuit current
**Ans: (b)** — faster fault clearing → less rotor acceleration → improved transient stability.
**Concept:** clearing time reduction lowers the accelerating area (EAC).
**Twist:** they do NOT reduce fault current magnitude. Combined with single-pole switching → further gain.

**Q7 (TSTRANSCO-12):** 100 MVA, 11 kV, 8-pole, 50 Hz, H = 4 MJ/MVA generator. Stored rotor energy at synchronous speed is
(a) 100 MJ (b) 400 MJ (c) 800 MJ (d) 12.5 MJ
**Ans: (b)** — KE = G·H = 100 × 4 = 400 MJ.
**Concept:** KE = G·H (independent of poles/kV/f — only rating and H).
**Twist:** H = 8 → 800 MJ. Use in M = GH/180f for swing equation.

**Q8 (APSPDCL-12):** 4-pole turbo generator (500 MVA, 22 kV) has angular acceleration 437.8 elec.deg/s². Equivalent in rpm/s is
(a) 1500 (b) 36.48 (c) 145.92 (d) 72.97
**Ans: (b)** — α_mech = α_elec/(3P)? — OHM: 437.8/(3×4) = 36.48 rpm/s (key answer).
**Concept:** electrical↔mechanical angle conversion via pole pairs (α_mech = α_elec × 2/P); rpm/s = mech°/s² ÷ 360.
**Twist:** 2-pole machine → mech = elec (÷2 in conversion). 6-pole → divide by 3 more.

**Q9 (APSPDCL-12):** 50 Hz generator H=6 and motor H=4 MJ/MVA through reactance. Generator delivers 1.0 p.u, drops to 0.6 p.u on fault. Angular acceleration is
(a) 360 (b) 180 (c) 1500 (d) 1800
**Ans: (c)** — Heq = 6×4/10 = 2.4; M = 2.4/(180×50) = 1/3750; α = Pa/M = 0.4/(1/3750) = 1500 elec.deg/s².
**Concept:** Pa = Pm − Pe; M = Heq/(180f); α = Pa/M.
**Twist:** fault removes more power (Pe → 0) → α = 1/(1/3750) = 3750. 60 Hz system → M smaller, α larger.

**Q10 (APSPDCL-12):** Synchronizing power coefficient can be written as
(a) Pa cosδ0 (b) Pmax cosδ0 (c) Pe cosδ0 (d) Pmax sinδ0
**Ans: (b)** — Ps = dP/dδ at δ0 = Pmax cosδ0.
**Concept:** synchronizing power coefficient Ps = dP/dδ = Pmax·cosδ0 (P = Pmax sinδ).
**Twist:** steady-state stability requires Ps > 0 → δ < 90°. At δ0 = 0 → Ps = Pmax.

**Q11 (APSPDCL-12):** Equal area criterion can be applied to
(a) multi-machine systems (b) any system on infinite bus (c) single machine connected to infinite bus (d) systems with induction machines
**Ans: (c)** — EAC is exact for single machine connected to infinite bus.
**Concept:** EAC valid for one-machine infinite-bus (2-machine reducible to SMIB) systems.
**Twist:** 2-machine systems approximately (reduce to equivalent single machine). Multi-machine needs digital simulation.

**Q12 (HMWS-12):** Stability of the power system is NOT affected by
(a) generator reactance (b) line reactance (c) line losses (d) excitation of generator
**Ans: (c)** — line losses do not alter the P–δ stability picture (idealised lossless analysis).
**Concept:** Pmax = E·V/X; X (generator + line reactance) and excitation (E) govern stability; line losses (R) do not.
**Twist:** X ↑ → Pmax ↓ → less stable. Excitation ↓ (E↓) → lower Pmax.

**Q13 (HMWS-12 / EPDCL-14):** 100 MVA, 11 kV water-wheel generator, H = 4. Energy stored in rotor at synchronous speed is
(a) 400 MJ (b) 400 kJ (c) 25 MJ (d) 25 kJ
**Ans: (a)** — KE = G·H = 100 × 4 = 400 MJ.
**Concept:** KE = G × H.
**Twist:** H=4 & G=500 → 2000 MJ. Watch unit: kW-s/kVA ≡ MJ/MVA.

**Q14 (EPDCL-14):** Critical clearing time of a fault is related to
(a) steady state stability limit (b) short-circuit current limit (c) transient stability limit (d) reactive power limit
**Ans: (c)** — critical clearing time belongs to transient-stability analysis.
**Concept:** t_cr defined by equal-area for transient stability.
**Twist:** critical clearing ANGLE corresponds to same EAC. Above t_cr the machine loses synchronism (first swing).

**Q15 (EPDCL-14):** In power system stability,
(a) steady-state limit = transient limit (b) steady-state < transient (c) steady-state > transient (d) transient with governor > steady-state
**Ans: (c)** — steady-state stability limit is always greater than transient stability limit.
**Concept:** transient stability limit < steady-state limit (disturbances reduce margin).
**Twist:** with fast excitation steady-state limit rises. Series compensation raises both.

**Q16 (EPDCL-14):** Equal area criteria is applied to calculate
(a) steady-state power limit (b) transient current limit (c) critical clearing voltage angle (d) critical clearing torque angle and time
**Ans: (d)** — EAC computes critical clearing angle and time.
**Concept:** EAC → δ_cr and t_cr for transient faults.
**Twist:** EAC also gives max angle δ_max reached. It does NOT give steady-state Pmax (that needs Ps=0).

**Q17 (APSPDCL-14):** Equal area criteria is applicable for
(a) two machine system (b) single machine system (c) multi machine system (d) none
**Ans: (a)** — EAC applies to (equivalent) two-machine systems (incl. SMIB).
**Concept:** EAC for SMIB and two-machine equivalents; not general multi-machine.
**Twist:** single machine + infinite bus is the classic application (option b in other papers). For multi-machine use transient simulation.

**Q18 (APSPDCL-14):** Transient stability limit of a power system can be increased by introducing
(a) shunt capacitance (b) shunt inductance (c) series capacitance (d) series inductance
**Ans: (c)** — series capacitor compensation cuts effective X, raising Pmax and both stability limits.
**Concept:** Pmax = EV/X; series compensation reduces X.
**Twist:** shunt capacitance mainly boosts voltage/VAr, not Pmax limit. Series inductor RAISES X → lowers limit.

**Q19 (ISRO-14):** Inertia constants of two machines not swinging together are M1, M2. Equivalent inertia constant is
(a) M1−M2 (b) M1+M2 (c) M1M2/(M1+M2) (d) M1M2/(M1−M2)
**Ans: (c)** — non-coherent groups: Meq = M1M2/(M1+M2).
**Concept:** non-coherent: product/sum; coherent: sum.
**Twist:** swinging together → M1+M2. Same H-formula Heq = H1H2/(H1+H2).

**Q20 (ISRO-14):** For a fault, critical clearing time is related to
(a) transient stability limit (b) reactive power limit (c) short-circuit current limit (d) steady-state stability limit
**Ans: (a)** — t_cr is a transient-stability quantity.
**Concept:** t_cr from EAC / swing integration.
**Twist:** larger machine H → longer t_cr. Higher inertia → more time to clear.

**Q21 (TSGENCO-15):** Large ac generator supplying infinite bus is suddenly short-circuited at its terminals; with prime-mover input and voltage behind transient reactance constant, rotor acceleration is
(a) inversely proportional to moment of inertia (b) inversely proportional to square of voltage (c) proportional to square of short-circuit current (d) proportional to short-circuit power
**Ans: (a)** — α = Pa/M; M ∝ J (moment of inertia), so α ∝ 1/J.
**Concept:** M = J·ω_s (or GH/180f); acceleration ∝ Pa/M.
**Twist:** higher inertia → lower α (longer t_cr). α also ∝ Pa = Pm − Pe.

**Q22 (TSGENCO-15):** Steady-state stability of a power system is improved by
(a) reducing fault clearing time (b) using double circuit line instead of single circuit (c) single pole switching (d) decreasing generator inertia
**Ans: (b)** — parallel (double-circuit) line halves X, raising PSSSL = EV/X.
**Concept:** PSSSL = EV/X; ↓X ⇒ ↑ limit.
**Twist:** fault-clearing time affects TRANSIENT, not steady-state stability. Series compensation also lowers X.

**Q23 (TSGENCO-15):** Rotor swings A→B settling at C. Speed during oscillation is synchronous at
(a) A and B (b) A and C (c) B and C (d) only at C
**Ans: (a)** — swing extremes A & B are where dδ/dt = 0 (synchronous speed).
**Concept:** at angle maxima/minima speed equals synchronous.
**Twist:** at C speed also synchronous but the extremes A/B define reversal. Speed is max mid-swing between A and B.

**Q24 (TSGENCO-15):** Which statement is true?
(a) steady-state limit > transient limit (b) steady-state = transient (c) steady-state < transient (d) no relation can be made
**Ans: (a)** — steady-state stability limit exceeds transient stability limit.
**Concept:** SS limit = EV/X (small disturbances); transient limit lower (faults).
**Twist:** fast AVR raises steady-state limit toward E'/X'd. Transient limit improves with faster clearing.

**Q25 (TSGENCO-15):** Equal area criterion gives information regarding
(a) stability region (b) absolute stability (c) relative stability (d) swing curves
**Ans: (b)** — EAC determines absolute (first-swing) stability of SMIB.
**Concept:** EAC → absolute stability (yes/no synchronism).
**Twist:** margin A1 vs A2 quantifies how close to instability (relative margin). Swing curve computed numerically, not by EAC.

**Q26 (TSSPDCL-15):** 60 Hz, 4-pole, 100 MVA, 11 kV, H = 8 MJ/MVA. Mechanical input raised to 80 MW, electrical 60 MW. Rotor acceleration is
(a) 270 elec.deg/s² (b) 337.5 (c) 225 (d) 810
**Ans: (a)** — M = 100×8/(180×60) = 8/108; α = Pa/M = 20/(8/108) = 270 elec.deg/s².
**Concept:** α = Pa/M, M = GH/(180f).
**Twist:** f = 50 Hz → M = 8/90, α = 225. Pa doubled (40 MW) → α = 540.

**Q27 (TSSPDCL-15):** In operating region δ < 70°, synchronizing power coefficient is
(a) larger in round-rotor than salient-pole (b) same in both (c) larger in salient-pole than round-rotor (d) zero in both
**Ans: (*)** — δ<45°: salient-pole machine Ps larger; 45°<δ<90°: cylindrical-rotor Ps larger (region-dependent).
**Concept:** Ps = dP/dδ; salient pole has reluctance-power term dominating at small δ; round rotor (cylindrical) overtakes beyond ~45°.
**Twist:** δ < 45° → salient pole (option c). δ > 45° → round rotor (option a). δ = 90° → Ps = 0 (limit).

**Q28 (HMWS-15):** Steady-state stability of a power system is improved by
(a) decreasing generator inertia (b) using double circuit line instead of single circuit (c) single pole switching (d) reducing fault clearing time
**Ans: (b)** — double-circuit line reduces X → raises PSSSL = EV/X.
**Concept:** PSSSL = EV/X.
**Twist:** (c) & (d) help transient stability only. Decreasing inertia worsens stability.

**Q29 (HMWS-15):** From stability point of view, generator connected to synchronous motor, preferable grounding is
(a) generator neutral resistance and motor neutral reactance (b) both neutrals resistance (c) both neutrals reactance (d) generator neutral reactance and motor neutral resistance
**Ans: (a)** — generator grounded via resistance (limits LG fault current), motor via reactance.
**Concept:** resistance grounding reduces LG fault current & transient torque; reactance grounding on motor side.
**Twist:** high Xn on generator → 3Xn in Z0 raises LG fault impedance (less severe). Reversed grounding worsens torque pulsations.

**Q30 (APTRANSCO-17):** 2-pole, 50 Hz, 100 MVA, 33 kV turbo-alternator, J = 10⁷ kg-m², Xs = 0.5 p.u. Natural time period of oscillation is
(a) 7.874 s (b) 15.748 s (c) 23.622 s (d) 24.9 s
**Ans: (d)** — KE_s = ½Jω²s = 5×314² MJ → H = KE/(100) ; M = H/(πf); ωn = √(K/M), K = Pmax = 2 p.u; Tn = 2π/ωn = 24.9 s.
**Concept:** Tn = 2π√(M/K); K = synchronizing coefficient Pmax·cosδ0; M = GH/(180f).
**Twist:** δ0 = 0 → K = Pmax = 2 p.u. If Xs doubled (1.0) → Pmax = 1, Tn longer. Higher inertia → longer period.

**Q31 (APTRANSCO-17):** Inertia constants M1, M2 of two groups which swing TOGETHER. System inertia constant is
(a) M1−M2 (b) M1/(M1+M2) (c) M1+M2 (d) M1/(M1−M2)
**Ans: (c)** — coherent machines: Meq = M1 + M2.
**Concept:** coherent: sum; non-coherent: product/sum.
**Twist:** non-coherent → M1M2/(M1+M2). All units on common base: H scaled by G before summing.

**Q32 (APGENCO-17):** Transient stability studies are usually carried out over a time period of
(a) two or more seconds (b) several time swings (c) time interval of first swing (d) sustained oscillations
**Ans: (c)** — transient stability focuses on the first swing (usually < 1 s).
**Concept:** first-swing (transient) stability analysis.
**Twist:** mid-term stability extends to ~seconds; long-term includes governor/AGC.

**Q33 (APGENCO-17):** The swing equation of a synchronous machine is based on
(a) relative motion between load angle and stator magnetic field (b) maximum power flow through a point (c) net torque and angular displacement (d) relation between excitation voltage and current
**Ans: (c)** — swing equation: M(d²δ/dt²) = Pa (net accelerating torque vs angular displacement).
**Concept:** M(d²δ/dt²) = Pa; M = GH/180f.
**Twist:** linearized (small-signal) form M·Δδ'' + K·Δδ = 0 gives natural frequency. Pa = Pm − Pe.

**Q34 (TSSPDCL-18):** In rotor angle stability, condition for stability is
(a) dP/dδ = 0 (b) dδ/dt = 0 (c) dV/dt = 0 (d) dQ/dδ = 0
**Ans: (b)** — stable equilibrium when dδ/dt = 0 (and Ps > 0).
**Concept:** rotor-angle stability: at steady state dδ/dt = 0 with synchronizing coefficient positive.
**Twist:** static stability also needs dP/dδ > 0 (option a zero = limit point). Both together ⇒ stable.

**Q35 (APSPDCL-19):** Angular acceleration: 20 MVA, 11 kV, 50 Hz, 4-pole, H = 9.0 kW-s/kVA, input 26,800 HP, output 16 MW.
(a) 300.5 (b) 220.5 (c) 250.5 (d) 199.5
**Ans: (d)** — Pa = 26,800×0.746×10⁻³ − 16 = 19.99 − 16 = 3.99; M = 20×9/(180×50) = 0.02; α = 3.99/0.02 = 199.5 elec.deg/s².
**Concept:** Pa = P_in − P_out (MW); M = GH/(180f); α = Pa/M.
**Twist:** HP→MW = ×0.746 (trap: use 0.746). 26,800 HP ≈ 20 MW (net Pa small). f=60 → M smaller, α larger.

**Q36 (APSPDCL-19):** 50 Hz, 4-pole, 20 MVA, 13.2 kV alternator, H = 4 kW-s/kVA. K.E. stored in rotor at synchronous speed is
(a) 80 kJ (b) 80 MJ (c) 40 MJ (d) 20 MJ
**Ans: (b)** — KE = G·H = 20 × 4 = 80 MJ.
**Concept:** KE = G × H.
**Twist:** H in kW-s/kVA numerically = MJ/MVA. G doubles (40 MVA) → 160 MJ.

**Q37 (APSPDCL-19):** In rotor angle stability, condition for stability is
(a) dP/dδ = 0 (b) dδ/dt = 0 (c) dV/dt = 0 (d) dQ/dδ = 0
**Ans: (b)** — rotor-angle stability requires dδ/dt = 0 at equilibrium.
**Concept:** equilibrium: dδ/dt = 0 (rotor at synchronous speed); needs Ps = dP/dδ > 0.
**Twist:** dP/dδ = 0 → marginal (limit point, δ = 90°). Negative dP/dδ → unstable.

**Q38 (APSPDCL-19):** Six identical machines on same bus, each H = 5 MJ/MVA, 60 MVA. Base = combined 360 MVA. Equivalent machine inertia constant is
(a) 5 (b) 10 (c) 15 (d) 20
**Ans: (a)** — Heq = ΣGiHi/Gsys = 6×60×5/360 = 5 MJ/MVA.
**Concept:** Heq = Σ(Gi·Hi)/Gsys (coherent machines on common base).
**Twist:** all machines on their own bases with different H → convert each to system base first. Non-coherent groups → product/sum rule.

**Q39 (APSPDCL-19):** Equal Area Criterion (EAC) is a method to determine
(a) steady-state stability (b) small-signal stability (c) frequency stability (d) transient stability
**Ans: (d)** — EAC determines (first-swing) transient stability.
**Concept:** EAC → transient stability of SMIB.
**Twist:** small-signal stability uses synchronizing coefficient / eigenanalysis. EAC cannot handle sustained oscillations.

**Q40 (APEPDCL-19):** For which case can the equal area criterion of stability be used?
(a) isolated alternator without load (b) one machine and infinite bus (c) isolated alternator with load (d) many machines and infinite bus
**Ans: (b)** — EAC applies to a single machine connected to an infinite bus.
**Concept:** EAC valid for SMIB (one machine + infinite bus).
**Twist:** two machines → reduce to equivalent SMIB. Many machines → numerical transient simulation required.

**Q41 (APEPDCL-19):** Which of the following will NOT affect the stability of the power system?
(a) load angle δ (b) generator reactance (c) line losses (d) excitation of generators
**Ans: (c)** — line losses do not affect stability (lossless P–δ analysis).
**Concept:** stability governed by X, E (excitation), δ; not by R/losses.
**Twist:** δ ↑ toward 90° → less stable. Generator reactance ↓ → Pmax ↑.

**Q42 (APEPDCL-19):** Inertia constants M1, M2 of two groups which swing together. System inertia constant is
(a) M1−M2 (b) M1/(M1+M2) (c) M1/(M1−M2) (d) M1+M2
**Ans: (d)** — coherent groups: Meq = M1 + M2.
**Concept:** coherent → sum; non-coherent → product/sum.
**Twist:** if not swinging together → Meq = M1M2/(M1+M2). Traps: fractional options are for other combos.

**Q43 (APEPDCL-19):** Inertia constant H of a 200 MVA machine is 2 p.u. Its value on 400 MVA base is
(a) 0.4 (b) 4.0 (c) 2.0 (d) 1.0
**Ans: (d)** — H_sys = G_mc·H_mc/G_sys = 200×2/400 = 1.0.
**Concept:** H converts with base: H_new = H_old × (G_old/G_new).
**Twist:** base MVA doubled → H halves. Base MVA halved → H doubles.

**Q44 (TSPSC-AEE-23):** Which could be the effect of using high-speed circuit breakers?
(a) reduced reliability (b) improved stability (c) reduced short-circuit current (d) increased short-circuit current
**Ans: (b)** — fast clearing improves transient stability.
**Concept:** faster clearing → smaller accelerating area.
**Twist:** HS CB does not change fault-current magnitude. Reliability is secondary; primary benefit is stability.

**Q45 (TSGenco-24):** Six identical machines on same bus, each H = 5, 60 MVA; base = 360 MVA. Equivalent inertia constant (MJ/MVA) is
(a) 5 (b) 10 (c) 15 (d) 20
**Ans: (a)** — Heq = 6×60×5/360 = 5 MJ/MVA.
**Concept:** Heq = ΣGiHi/Gsys (coherent machines).
**Twist:** only 2 of 6 identical → Heq unchanged (5). Different ratings → weighted average by G.

---

## 5. LOAD FLOW ANALYSIS (38 Qs)

**Q1 (EPDCL-10):** The bus at which real and reactive powers are NOT specified is
(a) slack bus (b) load bus (c) generator bus (d) impedance bus
**Ans: (a)** — slack bus: V and δ specified; P and Q are unknown.
**Concept:** slack (swing) bus sets V,δ and absorbs the mismatch; P,Q not pre-specified.
**Twist:** load (PQ) bus: P,Q specified. generator (PV) bus: P,V specified. Slack chosen with large inertia generator.

**Q2 (APGENCO-12):** Load flow studies involve solving simultaneous
(a) linear algebraic equations (b) non-linear algebraic equations (c) linear differential equations (d) non-linear differential equations
**Ans: (b)** — power-flow equations are non-linear algebraic (P = V ΣYV).
**Concept:** non-linear algebraic (transcendental) nodal power equations.
**Twist:** solved iteratively (GS/NR/FDLF). Small-signal stability uses differential equations.

**Q3 (APGENCO-12):** 12-bus system, 3 voltage-controlled buses. Dimensions of Jacobian matrix are
(a) 21×21 (b) 21×19 (c) 19×19 (d) 19×21
**Ans: (c)** — Npq = 12−3−1 = 8; size = (Npv + 2Npq) = 19 → 19×19.
**Concept:** NR (polar) Jacobian size = (N_pv + 2N_pq) × (same).
**Twist:** formula also (2N − Npv − 2) = 24−3−2 = 19. If no PV buses → 21×21.

**Q4 (TRANSCO-12):** Gauss-Seidel load flow disadvantages — tick the INCORRECT statement.
(a) unreliable convergence (b) slow convergence (c) choice of slack bus affects convergence (d) good initial guess for voltages essential for convergence
**Ans: (d)** — GS does NOT need a good initial guess (that is a NR requirement); so (d) is the incorrect "disadvantage".
**Concept:** GS needs no good starting solution (converges from flat start); NR needs good initialization.
**Twist:** NR needs good initial guess (true disadvantage). GS convergence depends on slack-bus choice (true).

**Q5 (APSPDCL-12):** Value of acceleration factor used in Gauss-Seidel load flow is
(a) 1.59 (b) 1.66 (c) 1.0 (d) 1.6
**Ans: (d)** — typical GS acceleration factor α = 1.6.
**Concept:** acceleration factor ≈ 1.6 accelerates GS convergence.
**Twist:** α too large → divergence. FDLF uses fixed (no acceleration factor) but decoupled matrices.

**Q6 (APSPDCL-12):** Z-bus of the system (figure: buses 1-2 with branches j0.08, j0.5, j0.08; each to ground j0.2) is
(a) [[j0.08, j0.5],[j0.5, j0.58]] (b) [[j0.08, j0.08],[j0.08, j0.58]] (c) [[j0.08, −j0.5],[−j0.5, j0.58]] (d) [[j0.08, −j0.08],[−j0.08, j0.58]]
**Ans: (b)** — Z11 = j0.08, Z12 = Z21 = j0.08, Z22 = j0.58.
**Concept:** Zbus = Ybus⁻¹; driving-point and transfer impedances from the network.
**Twist:** network simplified by paralleling the three branches between 1-2 → y12 = −j(1/0.08+1/0.5+1/0.08). Zbus symmetric (passive).

**Q7 (HMWS-12):** The voltage of a bus can be controlled by controlling
(a) phase angle (b) reactive power of the bus (c) active power of the bus (d) phase angle and reactive power
**Ans: (b)** — bus voltage is controlled by reactive power injection.
**Concept:** V–Q coupling: Q controls voltage; P controls frequency/angle.
**Twist:** phase angle ↔ active power flow. Capacitors/inductors/AVR regulate Q → V.

**Q8 (EPDCL-14):** Off-diagonal element Yij of a bus admittance matrix is equal to
(a) admittance of element between i and j (b) minus of admittance at buses i,j (c) minus of admittance of element between i and j (d) same as diagonal element
**Ans: (c)** — Yij = −y_ij (negative of line admittance).
**Concept:** Ybus: Yij = −y_ij; Yii = sum of admittances incident on bus i.
**Twist:** with tapped/transformer branch (off-nominal ratio) → Yij = −a·y. Mutual couplings change diagonal sum.

**Q9 (EPDCL-14):** Number of iterations will be LEAST in which method?
(a) Gauss (b) Gauss-Seidel (c) Fast decoupled (d) Newton-Raphson
**Ans: (d)** — NR converges in fewest iterations (quadratic convergence).
**Concept:** NR ~2-5 iterations (quadratic); GS ~dozens (linear); FDLF ~10 (but fast per iteration).
**Twist:** FDLF is fastest per iteration but more iterations than NR. GS needs most iterations.

**Q10 (APSPDCL-14):** At slack bus, which combination of variables are specified?
(a) V, δ (b) P, Q (c) P, V (d) Q, V
**Ans: (a)** — slack bus specifies V and δ; P and Q are computed.
**Concept:** slack: V,δ specified (P,Q unknown); PV: P,V; PQ: P,Q.
**Twist:** generator (PV) bus: P,V specified. Load (PQ) bus: P,Q specified.

**Q11 (APSPDCL-14):** Which statement is normally correct for a Zbus matrix?
(a) null matrix (b) sparse matrix (c) full matrix (d) unity matrix
**Ans: (c)** — Zbus is a full matrix; Ybus is sparse.
**Concept:** Zbus = Ybus⁻¹ → dense; Ybus sparse (network topology).
**Twist:** sparsity rises with system size for Ybus. Zbus needed for fault studies.

**Q12 (APSPDCL & ISRO-14):** In GS power flow, iterations may be reduced if voltage correction is multiplied by
(a) Gauss constant (b) acceleration factor (c) deceleration constant (d) blocking factor
**Ans: (b)** — acceleration factor (α≈1.6) reduces GS iterations.
**Concept:** V_new = V_old + α·ΔV.
**Twist:** wrong α → divergence. α<1 (deceleration) for ill-conditioned cases.

**Q13 (TSGENCO-15):** Correct combination of specified quantities for Load/Generator/Slack buses:
(a) P,V / P,Q / P,δ (b) P,Q / P,V / V,δ (c) V,δ / P,δ / P,Q (d) P,δ / Q,V / Q,δ
**Ans: (b)** — Load: P,Q; Generator: P,V; Slack: V,δ.
**Concept:** bus type ↔ specified variables (PQ: P,Q; PV: P,V; slack: V,δ).
**Twist:** swap slack & load specs → impossible set. Identify slack by fixed |V| & δ=0.

**Q14 (TSTRANSCO-15):** Load flow studies involve solving simultaneous
(a) linear algebraic equations (b) non-linear algebraic equations (c) linear differential equations (d) non-linear differential equations
**Ans: (b)** — power-flow is a set of non-linear algebraic equations.
**Concept:** non-linear algebraic (sin, |V|² terms) solved iteratively.
**Twist:** transient stability adds differential equations. Small-signal linearizes around solution.

**Q15 (TSTRANSCO-15):** NR is superior to GS because
(a) time per iteration in NR < GS (b) NR iterations more than GS (c) iterations not independent of size in NR (d) NR convergence not affected by slack-bus selection
**Ans: (d)** — NR convergence is insensitive to slack-bus selection (GS is sensitive).
**Concept:** NR: quadratic, robust to slack choice; GS: sensitive, needs more iterations.
**Twist:** NR per-iteration cost is higher (Jacobian). FDLF approximates constant Jacobian.

**Q16 (TSSPDCL-15):** Generally in a power system, load is represented as
(a) constant power in both LF and stability (b) constant power in load flow, constant impedance in stability (c) constant power in stability, constant impedance in load flow (d) constant impedance in both
**Ans: (b)** — load flow uses constant-power (PQ) model; stability uses constant-impedance model.
**Concept:** LF: P,Q fixed; transient stability: load ∝ V² (constant impedance).
**Twist:** ZIP models combine constant power, current, impedance. Motor loads add inertia dynamics.

**Q17 (TSSPDCL-15):** Diagonal elements of a nodal admittance matrix are strengthened by adding
(a) shunt capacitors (b) shunt inductances (c) generators (d) resistive loads
**Ans: (b)** — shunt inductance adds |y| to Yii (diagonal).
**Concept:** Yii = sum of branch + shunt admittances; shunt reactor/inductor boosts diagonal.
**Twist:** shunt capacitor adds negative reactance (also strengthens |Yii|). Loads as shunt admittances also add to diagonal.

**Q18 (TSNPDCL-15):** Specified variable at any PV bus for load flow are
(a) real and reactive power (b) real power and load angle (c) real power and voltage magnitude (d) voltage magnitude and load angle
**Ans: (c)** — PV bus specifies P and |V|.
**Concept:** PV bus: P,|V| specified; Q,δ computed.
**Twist:** PQ bus: P,Q. Slack: V,δ. PV Q limit violated → convert to PQ.

**Q19 (TSNPDCL-15):** Which is true for bus impedance matrix?
(a) sparse (b) diagonally dominant elements (c) inverse of the bus admittance matrix (d) each element reciprocal of corresponding Ybus element
**Ans: (c)** — Zbus = Ybus⁻¹.
**Concept:** Zbus = [Ybus]⁻¹ (full matrix).
**Twist:** NOT element-wise reciprocal (option d is a trap). Ybus sparse ↔ Zbus dense.

**Q20 (TSNPDCL-15):** Admittance matrix Y for the network (fig: bus1–2 Xd'=j0.2, 1–3 X1'=j0.4, 2–3 X2'=j0.4) is
(a) [[j5,0,−j5],[0,j5,−j5],[−j5,−j5,j10]] (b) [[−j5,0,j5],[0,−j5,j5],[j5,j5,−j10]] (c) [[−j5,0,−j5],[0,j5,−j5],[−j5,−j5,j10]] (d) [[−j5,j10,j5],[j10,−j5,j5],[j5,j5,−j10]]
**Ans: (b)** — Y12 = −j5 (1/j0.2), Y13 = Y23 = −j2.5 (1/j0.4) with negative off-diagonals; key/options scaled set → Y = (b).
**Concept:** Yii = sum incident y; Yij = −y_ij.
**Twist:** check signs: off-diagonals are negative of branch admittance. Diagonal must equal −(sum of off-diagonals in row).

**Q21 (HMWSS-15):** 20-bus system with one voltage-controlled bus, size of Jacobian matrix is
(a) 38×38 (b) 32×32 (c) 19×19 (d) 16×16
**Ans: (a)** — size = (2n−2) = 38 → 38×38 (one slack, Npv=1, Npq=18 → Npv+2Npq = 1+36=37? key uses 2n−2).
**Concept:** NR Jacobian size = (2N − Npv − 2) = 40−1−2 = 37... OHM uses (2n−2)=38 with 1 PV bus (per key).
**Twist:** standard (2N−Npv−2); with Npv=1 → 37. No PV buses (only slack) → 2N−2 = 38.

**Q22 (HMWSS-15):** Load flow study is carried out for
(a) load frequency control (b) stability studies (c) system planning (d) fault calculations
**Ans: (c)** — load flow is used for planning and system design/expansion studies.
**Concept:** LF for planning, operation scheduling, contingency studies.
**Twist:** fault studies use Zbus. Stability uses time-domain sim. LFC is a separate control problem.

**Q23 (APTRANSCO-17):** 5-bus testing system with 6 lines and 1 transformer: number of non-zero elements in Y-bus is
(a) 25 (b) 12 (c) 11 (d) 19
**Ans: (d)** — nonzero elements = N + 2L = 5 + 2×7 = 19 (7 branches total).
**Concept:** non-zero elements = N + 2·L (each line adds 2 off-diagonals; N diagonal).
**Twist:** L counted as total branches (6 lines + 1 transformer = 7). For fully connected graph L = N(N−1)/2.

**Q24 (APTRANSCO-17):** Voltages of generator and infinite bus are 0.92∠10° and 1.0∠0°. Which statement is correct?
(a) active power gen→infinite, reactive infinite→gen (b) both active & reactive gen→infinite (c) reactive gen→infinite, active infinite→gen (d) both from infinite→gen
**Ans: (a)** — P ∝ E·V sinδ (δ>0 → P flows generator→bus); Q ∝ (E² − E·V cosδ) → |E|<V → Q flows infinite bus→generator.
**Concept:** P ∝ V1V2 sinδ/X; Q ∝ (V1² − V1V2cosδ)/X.
**Twist:** raise |E| > V (0.92→1.05) → Q also flows out. δ negative → P reverses. |E|=|V| and δ>0 → P only.

**Q25 (TSSPDCL-18):** Compared to NR (polar) load flow, the fast decoupled load flow
(a) takes fewer iterations (b) takes more iterations (c) obtains solution without iterations (d) takes same iterations
**Ans: (b)** — FDLF takes MORE iterations than NR (but each is much cheaper).
**Concept:** FDLF decouples P–δ and Q–V with constant matrices → more iterations, faster overall.
**Twist:** FDLF is fastest overall for large systems. NR converges in fewest iterations.

**Q26 (TSTRANSCO-18):** 3-bus system, admittances y12=(10−j20), y13=(10−j30), y23=(16−j32). First row of Ybus is
(a) [(20−j50), (−10+j20), (−10+j30)] (b) [(20−j50), (10−j20), (10−j30)] (c) [(10−j20), (−10+j20), (−10+j30)] (d) [(20+j50), (−10+j20), (−10+j30)]
**Ans: (a)** — Y11 = y12+y13 = (20−j50); Y12 = −y12 = (−10+j20); Y13 = −y13 = (−10+j30).
**Concept:** Yii = sum of incident admittances; Yij = −y_ij.
**Twist:** Y22 = y12+y23 = (26−j52), off-diag −(16−j32). Sign of j flips in off-diagonal.

**Q27 (TSTRANSCO-18):** Number of iterations for convergence increases significantly with number of buses in
(a) G-S algorithm (b) N-R algorithm (c) both G-S and N-R (d) fast decoupled
**Ans: (a)** — GS iterations grow with system size; NR iterations are nearly size-independent.
**Concept:** GS: linear convergence, iteration count ∝ size; NR: ~constant iterations regardless of size.
**Twist:** NR per-iteration cost grows (~N²) but count stays small. FDLF shares GS-type size dependence.

**Q28 (APSPDCL-19):** A voltage-controlled bus is treated as a load bus in a later iteration when its
(a) active power limit is violated (b) voltage limit is violated (c) reactive power limit is violated (d) current limit is violated
**Ans: (c)** — PV bus hits Q limit → becomes PQ bus.
**Concept:** PV→PQ conversion on reactive-power (VAr) limit violation.
**Twist:** PQ bus hitting voltage limit → becomes PV bus. This is generator capability enforcement.

**Q29 (APSPDCL-19):** FDLF method is suitable for
(a) high voltage transmission system (b) medium voltage transmission system (c) distribution system (d) none
**Ans: (a)** — FDLF works well for high-voltage (high X/R) transmission networks.
**Concept:** FDLF assumes decoupled P–δ, Q–V (valid for high X/R EHV networks).
**Twist:** distribution (low X/R) → GS better (radial, high R). NR works for both.

**Q30 (APSPDCL-19):** The Jacobian matrix of NR (polar) form provides information pertaining to
(a) real power flow (b) reactive power flow (c) losses (d) sensitivity information
**Ans: (d)** — Jacobian gives sensitivity of P & Q to δ and |V|.
**Concept:** J = [[∂P/∂δ, ∂P/∂|V|],[∂Q/∂δ, ∂Q/∂|V|]] → sensitivity.
**Twist:** decoupled forms use ∂P/∂δ (B') and ∂Q/∂V (B''). Losses not directly in J.

**Q31 (APSPDCL-19):** System: 10 buses, 1 slack, 3 PV, 6 load. Number of equations for NR (polar) load flow is
(a) 10 (b) 15 (c) 20 (d) 25
**Ans: (b)** — equations = Npv + 2Npq = 3 + 2×6 = 15.
**Concept:** NR (polar) unknown count = Npv + 2Npq.
**Twist:** rectangular form → 2(N−1). No PV buses → 2×9=18.

**Q32 (APEPDCL-19):** If a load bus voltage violates its limit in any iteration, it is switched to
(a) swing bus (b) P–Q bus (c) P–V bus (d) reference bus
**Ans: (c)** — voltage-limit violation at PQ bus → convert to PV bus.
**Concept:** PQ→PV on voltage violation (inverse of Q-limit rule).
**Twist:** PV bus Q-limit violation → PQ. Slack bus cannot switch.

**Q33 (APEPDCL-19):** Y-bus of 300-bus system is 80% sparse. Number of transmission lines must be
(a) 9000 (b) 36000 (c) 8850 (d) 35850
**Ans: (c)** — nonzero = N + 2NL = 300 + 2NL; sparsity 80% ⇒ 20% nonzero = 18000 = 300²−300−2NL → NL = 8850.
**Concept:** %nonzero = (N+2NL)/N²; NL from sparsity.
**Twist:** sparsity = (N² − N − 2NL)/N². Fully connected → no sparsity.

**Q34 (APEPDCL-19):** For load flow, quantities normally specified at the voltage-controlled bus are
(a) P and δ (b) P and Q (c) P and V (d) Q and V
**Ans: (c)** — PV bus specifies P and V (magnitude).
**Concept:** PV bus: P, |V| specified; Q, δ solved.
**Twist:** slack: V,δ. PQ: P,Q. Generator without AVR → PQ (fixed Q).

**Q35 (APEPDCL-19):** Initially the voltage at all PQ buses for NR load flow is taken as
(a) 1∠45° (b) 1∠90° (c) 1∠0° (d) 1∠180°
**Ans: (c)** — flat start: V = 1∠0° p.u.
**Concept:** flat start initialization (1.0 p.u, 0°) for PQ buses.
**Twist:** PV buses start at |V| specified, δ=0. NR needs good initial guess (unlike GS).

**Q36 (TSPSC-AEE-23):** Gauss-Seidel technique is commonly used in power systems for
(a) stability analysis (b) load flow analysis (c) fault analysis (d) unit commitment
**Ans: (b)** — GS is a load-flow solution technique.
**Concept:** GS iterative load flow (also used in distribution power flow).
**Twist:** NR/FDLF for transmission LF. Fault analysis uses Zbus. Unit commitment is optimization.

**Q37 (TSGenco-24):** The Jacobian matrix of NR (polar) form provides information pertaining to
(a) real power flow (b) reactive power flow (c) losses (d) sensitivity information
**Ans: (d)** — Jacobian gives sensitivities of P,Q w.r.t. δ,|V|.
**Concept:** J entries are ∂P/∂δ, ∂P/∂V, ∂Q/∂δ, ∂Q/∂V (sensitivity).
**Twist:** used to compute ΔP, ΔQ corrections and, at solution, voltage/reactive sensitivities. Not a flow report per se.

**Q38 (TSGenco-24):** Ybus for the system (fig: 3 buses, lines −j10 between 1–3, 2–3, and a 1:1.1 transformer branch −j10 between 1–2). Per-unit admittances.
(a) [[−j12.1,j11,j10],[j11,−j10,j10],[j10,j10,−j20]] (b) [[−j22.1,j11,j10],[j11,−j20,j10],[j10,j10,−j20]] (c) [[−j20,j11,j10],[j11,−j20,j10],[j10,j10,−j22.1]] (d) [[−j20,j11,j10],[j11,−j10,j10],[j10,j10,−j12.1]]
**Ans: (b)** — off-nominal transformer (1:1.1): Y12 = −a·y = −1.1(−j10) = j11, tapped branches −j1.1 & +j1 → Y11 = −j10−j11−j1.1 = −j22.1, Y22 = −j11+j1−j10 = −j20, Y33 = −j10−j10 = −j20.
**Concept:** off-nominal tap transformer: Y12 = −a·y; Y11 += a²y; Y22 += y; shunt terms a(a−1)y, (1−a)y.
**Twist:** tap below 1 (e.g., 1:0.9) → different Y11/Y22. Unbalance factors a² and (1−a) reverse signs.

---
**Total: 138 questions (13 Per-unit + 19 Symmetrical + 23 Fault + 45 Stability + 38 Load Flow).**

## Unit 3: Power System-3 — ELD/LFC + Protection (197 Qs)

Source: OHM Institute, Power Systems-3 Previous Year Questions on Module-3 (GENCO/TRANSCO/DISCOM).
Answer keys verified against the document's Module-3 Key tables and per-question Solution entries.

---

## Part A — ELD, EPG, LFC (Economic Load Dispatch / Load-Frequency Control / Plant economics) — 74 Qs

**Q1 (EPDCL-10):** Which of the following comes under operational cost of power system?
(a) Fuel cost (b) Labour cost (c) Both (a) and (b) (d) Interest and taxes
**Ans: (c)** — fuel cost and labour cost are running/operational charges.
**Concept:** Operating (running) cost = fuel + labour; interest & taxes are fixed charges.
**Twist:** "Interest and taxes + depreciation" → these are fixed charges, not operating cost. "Which is NOT a running cost" → option (d).

**Q2 (SSC-JE-10):** The value of diversity factor is:
(a) Less than one (b) Greater than one (c) Equal to one (d) Any one of the above
**Ans: (b)** — DF = sum of individual max demands / station max demand > 1.
**Concept:** Diversity factor (DF) always > 1 because consumer peaks don't coincide.
**Twist:** "Station max demand = 22000, sum of individual MD = 30000" → DF = 1.36. "DF=1" → all consumers peak simultaneously (rare).

**Q3 (SSC-JE-10):** The tariff most suitable for large industrial consumers is:
(a) Flat demand rate (b) Block meter rate (c) Two-part tariff (d) All the above
**Ans: (c)** — two-part tariff (fixed + running) suits large industrial loads.
**Concept:** Two-part tariff = Rs/kW-max demand + Rs/kWh energy.
**Twist:** "Domestic consumers" → block meter rate. "Max demand + energy + PF clause" → three-part tariff.

**Q4 (SSC-JE-10):** The knowledge of diversity factor helps in computing:
(a) Plant capacity (b) Average load (c) Units generated (d) Peak demand
**Ans: (a)** — Plant capacity = station max demand / DF.
**Concept:** Plant capacity determined via diversity factor.
**Twist:** "Knowledge of demand factor" → helps compute plant capacity from connected load. "DF ↑" → smaller installed capacity → lower fixed cost.

**Q5 (APGenco-12):** Cost function of a 50 MW generator F(pi) = 225 + 53pi + 0.02pi². At 100% loading the Incremental Fuel Cost (IFC) will be:
(a) Rs. 55 per MWh (b) Rs. 55 per MW (c) Rs. 33 per MWh (d) Rs. 33 per MW
**Ans: (a)** — IFC = dF/dP = 53 + 0.04×50 = Rs 55/MWh.
**Concept:** ELD: IFC = dF(P)/dP; 100% loading → Pi = rating = 50 MW.
**Twist:** "80% loading" → IFC = 53 + 0.04×40 = 54.6. "Find F at no-load" → 225 = no-load cost.

**Q6 (Transco-12):** Generating station connected load 450 MW, max demand 250 MW, units 615×10⁶/year. Load factor:
(a) 0.586 (b) 0.615 (c) 0.281 (d) 0.725
**Ans: (c)** — LF = 615×10⁶/(250×10³×8760) = 0.281.
**Concept:** LF = units generated / (MD × 8760).
**Twist:** "Use connected load 450 in denominator" → wrong 0.156 (trap). "Plant use factor = units/(PC×8760)" → needs plant capacity.

**Q7 (Transco-12):** The plant capacity is determined by:
(a) Maximum demand of a consumer (b) Plant use factor (c) Simultaneous maximum demand of all consumers (d) Load factor
**Ans: (c)** — plant sized for simultaneous max demand of all consumers.
**Concept:** Plant capacity ∝ sum of simultaneous max demands = station MD.
**Twist:** "If DF known, plant capacity = MD/DF". "Sum of individual MD (non-simultaneous)" → overestimates.

**Q8 (Transco-12):** Power plant max demand 15 MW, load factor 50%, plant capacity factor 40%. Operating reserve:
(a) 3 MW (b) 3.75 MW (c) 6.0 MW (d) 7.5 MW
**Ans: (b)** — RC = Pmax(LF−PCF)/PCF = 15(0.5−0.4)/0.4 = 3.75 MW.
**Concept:** Reserve capacity = Pmax(LF−PCF)/PCF.
**Twist:** "LF=0.6, PCF=0.48, Pmax=30" → RC = 7.5 MW (Q9). "PCF=LF" → reserve = 0.

**Q9 (APSPDCL-12):** Generating station max demand 30 MW, LF 0.6, PCF 0.48; reserve capacity:
(a) 37.5 MW (b) 7.5 MW (c) 19.5 MW (d) 12 MW
**Ans: (b)** — RC = 30(0.6−0.48)/0.48 = 7.5 MW.
**Concept:** Reserve capacity formula above.
**Twist:** "LF=0.6, PCF=0.5, MD=30" → RC = 6 MW (Q18). "Compute plant capacity = MD+RC" → 37.5 MW (distractor).

**Q10 (APSPDCL-12):** Given max power transmitted through a line Pmax, with 60% series capacitor compensation, max power transfer becomes:
(a) Pmax/0.4 (b) 0.4 Pmax (c) Pmax/0.6 (d) 0.6 Pmax
**Ans: (a)** — X reduces to 0.4X, Pmax ∝ 1/X → P = Pmax/0.4 = 2.5 Pmax.
**Concept:** Series compensation: X' = (1−k)X; Pmax ∝ 1/X'.
**Twist:** "40% compensation" → P = Pmax/0.6. "100% compensation" → theoretically infinite (practical limit).

**Q11 (APSPDCL-12):** Industrial consumer 1500 kW at 0.8 pf lag for 12 h and 1000 kW at UPF for 12 h. Daily load factor:
(a) 0.666 (b) 0.833 (c) 0.8 (d) 1.25
**Ans: (b)** — avg load = (1500×12+1000×12)/24 = 1250; LF = 1250/1500 = 0.833.
**Concept:** LF = average load / maximum demand (pf of 0.8 irrelevant — kW load given).
**Twist:** "If kVA loads given" → convert kVA×pf to kW first. "LF = 1250/2000" (using 1500+1000) → wrong 0.625 trap.

**Q12 (HMWS-12):** Connected load 120 kW, peak 100 kW, base 25 kW, avg 48 kW. Load factor:
(a) 40% (b) 48% (c) 325% (d) 83.3%
**Ans: (b)** — LF = 48/100 = 48%.
**Concept:** LF = avg/peak (connected load and base load are distractors).
**Twist:** "Use connected load 120" → 40% (trap a). "Use base load 25" → wrong.

**Q13 (HMWS-12):** In distribution system for PF improvement, PF-correction devices are installed at:
(a) The sending end (b) Near the earthing point (c) The load end (d) Anywhere in the circuit
**Ans: (c)** — capacitors placed near load end reduce line current/losses.
**Concept:** Shunt capacitors at load end for PF correction.
**Twist:** "Which position minimizes losses" → load end. "Series capacitors" → for voltage drop compensation on long lines.

**Q14 (SSC-JE-12):** Connected load 2 kW, max demand 1.5 kW. Demand factor:
(a) None of these (b) 0.75 (c) 0.375 (d) 1.33
**Ans: (b)** — DF = MD/connected load = 1.5/2 = 0.75.
**Concept:** Demand factor = max demand / connected load.
**Twist:** "Compute load factor" → need energy + hours. "DF never exceeds 1" → true; "1.33" would be MD/avg (trap).

**Q15 (SSC-JE-13):** Which is correct?
(a) Load factor = capacity factor × utilization factor (b) Utilization factor = capacity factor × load factor (c) Capacity factor = load factor × utilization factor (d) No relation
**Ans: (c)** — Capacity factor = load factor × utilization factor.
**Concept:** PCF = LF × utilization factor (CF = avg load/PC).
**Twist:** "Plant use factor = units/(PC×hrs)" — different from capacity factor. "Utilization factor = MD/PC".

**Q16 (EPDCL-14):** Most economical power factor, rate per max demand Rs 20/yr, expenditure per kVA Rs 3.8/yr:
(a) 0.19 lag or lead (b) 0.9 lag or lead (c) 0.9 lag (d) 0.9 lead
**Ans: (c)** — most economical PF = sqrt(1−(x/y)²) with x=3.8, y=20 → 0.9 lag.
**Concept:** Most economical PF = sqrt(1−(Rs/kVA / Rs/kW)²); always lagging.
**Twist:** "x=0, free kVA" → PF = 1. "y=x" → PF = 0. Note: arithmetic with given numbers yields ≈0.98; OHM intends 0.9.

**Q17 (APSPDCL-14):** Performance criteria to assess power quality:
(a) Power factor (b) Harmonics (c) Profile of voltage (d) All the above
**Ans: (d)** — PF, harmonics and voltage profile all assess PQ.
**Concept:** Power quality parameters: PF, harmonics, voltage profile.
**Twist:** "Also frequency deviation / sag-swell" → included. "Only THD" → insufficient.

**Q18 (APSPDCL-14):** Station MD 30 MW, LF 60%, PCF 50%; reserve capacity:
(a) 5 MW (b) 4 MW (c) 6 MW (d) 10 MW
**Ans: (c)** — RC = 30(0.6−0.5)/0.5 = 6 MW.
**Concept:** RC = Pmax(LF−PCF)/PCF.
**Twist:** "PCF=0.48, LF=0.6" → RC = 7.5 MW. "LF=PCF" → RC=0.

**Q19 (APSPDCL-14):** Reserve generating capacity not in service but in operation is:
(a) Hot reserve (b) Cold reserve (c) Firm hot reverse (d) Spinning reserve
**Ans: (a)** — hot reserve: in operation (boiler hot) but not synchronized/loaded.
**Concept:** Hot reserve (in operation, not loaded) vs spinning reserve (synchronized, rotating) vs cold reserve (shut down).
**Twist:** "Synchronized and rotating at no load" → spinning reserve (d). "Shut down" → cold reserve.

**Q20 (ISRO-14):** In load-frequency control with free governor action, a load increase in steady state is met:
(a) Only by decrease of load demand due to frequency drop (b) Only by increased generation via steam valve (c) Partly by increased generation and partly by decrease of load demand (d) Partly by increased generation and partly by increased excitation
**Ans: (c)** — steady state: both governor response and load's frequency-sensitivity (D) share the change.
**Concept:** ΔPm − ΔPL = DΔf + (1/R)Δf for speed-governing; two effects share.
**Twist:** "Tie-line included, no governor" → Δf = −ΔP/D. "Both areas participate" → ACE-based AGC.

**Q21 (SSC-JE-S1-14):** Station supplies 15000, 12000, 8500, 6000, 450 kW; station MD 22000 kW. Diversity factor:
(a) 0.52 (b) 0.68 (c) 1.34 (d) 1.91
**Ans: (d)** — DF = (15000+12000+8500+6000+450)/22000 = 1.91.
**Concept:** DF = Σ individual MD / station MD.
**Twist:** "Add a new consumer MD 1000 kW" → DF changes. "Use station MD/ΣMD" → 0.52 (trap a).

**Q22 (SSC-JE-S1-14):** If max demand = plant capacity:
(a) Plant reserve capacity will be zero (b) Diversity factor will be unity (c) Load factor will be unity (d) Load factor will be nearly 60%
**Ans: (a)** — reserve = plant capacity − MD = 0.
**Concept:** Reserve capacity = PC − MD.
**Twist:** "MD > PC" → overloaded plant, not allowed. "PCF=1" requires MD×8760 = units.

**Q23 (SSC-JE-S1-14):** MD 2 kW, daily energy 20 units. Load factor:
(a) 10.15% (b) 41.6% (c) 50% (d) 21%
**Ans: (b)** — avg load = 20/24 = 5/6 kW; LF = (5/6)/2 = 41.6%.
**Concept:** LF = (energy/24 h)/MD.
**Twist:** "Energy = 24 units" → avg = 1 kW, LF = 50% (Q26). "Energy = 20 units, MD = 1 kW" → 83.3%.

**Q24 (SSC-JE-S1-14):** Diversity factor has a direct effect on:
(a) Fixed cost of the unit generated (b) Variable cost of unit (c) Both variable and fixed cost (d) Operating cost
**Ans: (a)** — higher DF → smaller plant capacity → lower fixed/capital cost.
**Concept:** DF affects installed capacity → fixed (capital) cost.
**Twist:** "Load factor affects..." → both fixed and running cost per unit. "DF affects operating cost" → false.

**Q25 (SSC-JE-S1-14):** Annual consumption 700800 units, MD 200 kW. Load factor:
(a) 20% (b) 40% (c) 50% (d) 70%
**Ans: (b)** — avg = 700800/8760 = 80 kW; LF = 80/200 = 40%.
**Concept:** LF = (annual units/8760)/MD.
**Twist:** "Consumption 700800, MD 100 kW" → LF = 80%. "Use 365 days only" → 43.8%.

**Q26 (SSC-JE-S2-14):** MD 2 kW, daily energy 24 units. Load factor (%):
(a) 24 (b) 41.6 (c) 50 (d) 80
**Ans: (c)** — avg = 24/24 = 1 kW; LF = 1/2 = 50%.
**Concept:** Same as Q23 but energy = 24 units.
**Twist:** "Energy 20 units" → 41.6%. "Units/day higher" → LF rises linearly.

**Q27 (SSC-JE-S2-14):** Daily load: 2000 kW @0.8 lag for 12 h, 1000 kW UPF for 12 h. Load factor:
(a) 0.5 (b) 0.75 (c) 0.6 (d) 2.0
**Ans: (b)** — avg = (2000×12+1000×12)/24 = 1500; LF = 1500/2000 = 0.75.
**Concept:** LF = avg/MD (0.8 pf given but loads already in kW — distractor).
**Twist:** "1500 kW @0.8 + 1000 kW UPF" → avg 1250, LF 0.833 (Q71). "kVA given" → multiply by pf.

**Q28 (SSC-JE-S2-14):** To reduce cost of electricity generated:
(a) LF and DF must be low (b) LF low, DF high (c) LF high, DF low (d) LF and DF must be high
**Ans: (d)** — high LF and DF spread fixed cost over more units / smaller capacity.
**Concept:** Cost/unit falls with higher LF & DF.
**Twist:** "Maximize DF only" → reduces fixed cost; "LF=1" → ideal. "Peak demand high" → cost rises.

**Q29 (SSC-JE-S1-14):** Distribution losses in transferring power from station to consumer are accounted under:
(a) Fixed charges (b) Running charges (c) Cost of fuel (d) Maintenance cost
**Ans: (b)** — distribution losses are running charges.
**Concept:** Running charges include losses + fuel + labour.
**Twist:** "Capital cost of lines" → fixed charge. "Loss of revenue" → tariff adjustments.

**Q30 (TSGenco-15):** IC1 = 25+0.2PG1, IC2 = 32+0.2PG2, total load 250 MW (no losses). Economic allocation:
(a) PG1=140.25, PG2=109.75 (b) PG1=109.75, PG2=140.75 (c) PG1=PG2=125 (d) PG1=100, PG2=150
**Ans: (—)** — IC1=IC2 gives PG1=142.5, PG2=107.5 MW; no option matches (OHM key: *).
**Concept:** ELD: equal incremental cost IC1=IC2=λ.
**Twist:** "Option (a) of Q62/APTransco-19" → same numbers with PG1=142.5, PG2=107.5 as a valid option. "Include transmission loss" → modified by penalty factor.

**Q31 (TSGenco-15):** Most appropriate operating speeds (rpm) for Thermal, Nuclear, Hydropower generators:
(a) 3000, 300 and 1500 (b) 3000, 3000 and 300 (c) 1500, 1500 and 3000 (d) 1000, 900 and 750
**Ans: (b)** — thermal & nuclear 3000 rpm (2-pole 50 Hz), hydro ~300 rpm (many poles).
**Concept:** N = 120f/P; 2-pole → 3000 rpm at 50 Hz.
**Twist:** "60 Hz system" → 3600 rpm. "Hydro with high head, Pelton" → ~500 rpm.

**Q32 (TSGenco-15):** Storage battery generally used in electric power station:
(a) Zinc carbon (b) Lead acid (c) Nickel cadmium (d) Lithium-ion
**Ans: (b)** — lead-acid batteries are standard station storage.
**Concept:** Station DC supply → lead-acid battery.
**Twist:** "Acid density indicates charge" (Q41). "Long standby, low maintenance" → Ni-Cd.

**Q33 (TSGenco-15):** 24-h load table (0–6:40, 6–8:50, 8–12:60, 12–14:50, 14–18:70, 18–22:80, 22–24:40 MW). Load factor:
(a) 0.75 (b) 0.71 (c) 0.60 (d) 0.68
**Ans: (b)** — energy = 6×40+2×50+4×60+2×50+4×70+4×80+2×40 = 1360 MWh; LF = 1360/(80×24) = 0.708 ≈ 0.71.
**Concept:** LF = area under load curve/(peak×24).
**Twist:** "Peak 100 MW instead of 80" → LF = 0.567. "2-h intervals differently" → recompute area.

**Q34 (TSGenco-15):** LF=70%, capacity factor=50%, used factor=60%, MD=20 MW. Annual energy production:
(a) 122.8 GWh (b) 198.55 GWh (c) 128.2 GWh (d) 188.82 GWh
**Ans: (a)** — Annual energy = LF×MD×8760 = 0.7×20×8760 = 122.64 ≈ 122.8 GWh.
**Concept:** Energy = LF × MD × 8760 (PCF, use factor are distractors).
**Twist:** "Use PCF 0.5 → energy = PCF×PC×8760" → needs PC. "MD=25" → 153.3 GWh.

**Q35 (TSGenco-15):** For lower cost of electrical energy generation, the load factor:
(a) And DF should be low (b) Low but DF high (c) High but DF low (d) And DF both should be high
**Ans: (d)** — both high reduce per-unit cost.
**Concept:** Cost per unit ∝ 1/(LF×DF) effect on fixed charges.
**Twist:** "Which factor matters more for fixed cost" → DF. "For running cost" → LF.

**Q36 (TSTransco-15):** Reflector mirrors employed for exploiting solar energy are called:
(a) Mantle (b) Heliostats (c) Diffusers (d) Ponds
**Ans: (b)** — heliostats track and concentrate sunlight.
**Concept:** Heliostat = tracking reflector for solar tower CSP.
**Twist:** "Flat plate collector component" → not heliostat. "Solar pond" → combined collector+storage (Q48).

**Q37 (TSTransco-15):** Capital cost of a power plant depends on:
(a) Total installed capacity only (b) Total number of units only (c) Total installed capacity and number of units (d) Neither
**Ans: (c)** — depends on installed capacity and number of units.
**Concept:** Capital cost ∝ installed capacity × (unit count effect).
**Twist:** "Number of units ↑" → specific cost can drop (economy of scale). "Land, cooling water" → also capital items.

**Q38 (TSTransco-15):** Load duration curve for unity load factor is of:
(a) Rectangular shape (b) Triangular shape (c) L-shape (d) I-shape
**Ans: (a)** — constant load → flat/rectangular LDC.
**Concept:** LDC shape: LF=1 → rectangle; LF<1 → L/tapered.
**Twist:** "Realistic system LF~0.4-0.6" → L-shape. "Triangular" → LF = 0.5 (base/top triangle).

**Q39 (TSTransco-15):** Knowledge of diversity factor helps in computing:
(a) Plant capacity (b) Average load (c) Unit (kWh) generated (d) Peak demand
**Ans: (a)** — plant capacity.
**Concept:** Plant capacity = MD/DF (same as Q4).
**Twist:** "Load factor knowledge" → computes average load/units. "Demand factor" → plant capacity from connected load.

**Q40 (TSTransco-15):** Load factor is the:
(a) Ratio of max load on station to sum of consumer max loads (b) Ratio of average demand to maximum demand (c) Factor used for increasing load (d) Reciprocal of (a)
**Ans: (b)** — LF = average demand/max demand.
**Concept:** Definitions: LF, DF (MD/connected), diversity (Σindiv MD/MD).
**Twist:** "Option (a) is diversity factor inverse". "LF can exceed 1" → false.

**Q41 (TSTransco-15):** In lead-acid battery, the density of acid indicates:
(a) Charge of the battery (b) Level of acid (c) e.m.f of the battery (d) Damage of plates
**Ans: (a)** — specific gravity of acid measures state of charge.
**Concept:** SG ~1.28 full charge, ~1.12 discharged.
**Twist:** "Acid level" → checked visually, not density. "e.m.f" → roughly proportional but density is the charge indicator.

**Q42 (TSTransco-15):** Battery of series-connected cells (each v volts, capacity k). Battery voltage & capacity:
(a) V=nv, capacity=k (b) V=nv, capacity=nk (c) V=v, capacity=nk (d) V=v, capacity=k
**Ans: (a)** — series: voltages add, capacity (Ah) unchanged.
**Concept:** Series → add V, same Ah; parallel → same V, add Ah.
**Twist:** "Parallel cells" → V=v, capacity=nk. "Series for voltage, parallel for current" → hybrid.

**Q43 (TSTransco-15):** Power in the wind is proportional to:
(a) Wind velocity (b) (Wind velocity)² (c) (Wind velocity)³ (d) (Wind velocity)/2
**Ans: (c)** — P ∝ V³.
**Concept:** P_wind = ½ρAV³.
**Twist:** "P ∝ A (swept area) and V³" → D²V³ (Q47). "Doubling V" → 8× power.

**Q44 (TSTransco-15):** For a PV cell, VOC, ISC, V, I. At maximum power point (MPP):
(a) V < VOC and I = ISC (b) V < VOC and I < ISC (c) V = VOC and I = ISC (d) V = VOC and I < ISC
**Ans: (b)** — at MPP both V and I are below their open/short-circuit values.
**Concept:** MPP: V_mpp < VOC, I_mpp < ISC; P = V×I maximized.
**Twist:** "Fill factor = Pmax/(VOC·ISC)" → <1. "V=VOC, I=0" → P=0.

**Q45 (TSTransco-15):** Accurate equivalent circuit of PV cell (with RS series, RP parallel). For this cell:
(a) RP = RS (b) RP < RS (c) RP > RS (d) Product RP·RS = 1
**Ans: (c)** — RP (shunt, MΩ) >> RS (series, mΩ).
**Concept:** Ideal PV: small RS, large RP.
**Twist:** "Which dominates losses" → series RS → current loss; shunt RP → leakage. "Ideal cell" → RS=0, RP=∞.

**Q46 (TSSPDCL-15):** Unit heat rate characteristic of a thermal unit shows:
(a) Heat input per kWh of output vs MW output (b) Heat input per kW of output vs MW output (c) Heat input per kWh vs MWh output (d) Heat input per kW vs MWh output
**Ans: (a)** — unit heat rate = kJ/kWh vs net MW output.
**Concept:** Heat rate curve → converts to fuel-cost/IC curves for ELD.
**Twist:** "Slope of heat-rate vs load" → related to IFC. "Incremental heat rate" → d(heat)/d(P).

**Q47 (TSSPDCL-15):** If D is rotor swept-area diameter and V wind speed, wind power ∝:
(a) AV² (b) A²V³ (c) D²V³ (d) D³V²
**Ans: (c)** — P ∝ A·V³ ∝ D²·V³.
**Concept:** P = ½ρ(πD²/4)V³.
**Twist:** "A and V both" → AV³ (not in options; note). "D doubled" → 4× power at same V.

**Q48 (TSSPDCL-15):** A solar pond is a combination of:
(a) Solar energy storage and heat collection (b) Solar energy collection and heat storage (c) Solar energy collection and energy storage (d) All the above
**Ans: (b)** — solar pond collects solar energy and stores it as heated salt water.
**Concept:** Solar pond: collection + heat storage (salt-gradient pond).
**Twist:** "Electricity storage" → not the pond's role. "Flat plate collector + tank" → separate storage.

**Q49 (TSSPDCL-15):** According to IE Rules 1956, breaking strength of all overhead line conductors shall be:
(a) Not less than 450 kg (b) Not less than 350 kg (c) Not less than 250 kg (d) Not less than 500 kg
**Ans: (b)** — Rule 74: breaking strength ≥ 350 kg (≥150 kg for low-voltage short spans on consumer premises).
**Concept:** IE Rule 74 — material & strength of overhead conductors.
**Twist:** "Span <15 m, LV, consumer premises" → 150 kg minimum. "Rule number asked" → 74.

**Q50 (TSSPDCL-15):** Unit commitment is a procedure in which:
(a) Scheduling total generation economically (b) Optimal combination of units chosen at any given time (c) Most efficient machines selected for financial economy (d) Machines selected for minimum reactive loss
**Ans: (b)** — UC picks which units ON at each hour (on/off decisions).
**Concept:** Unit commitment = on/off decisions (commitment); ELD = loading of committed units.
**Twist:** "ED vs UC" → ELD allocates load among committed units; UC decides commitment. "Start-up/shut-down costs" → UC constraints.

**Q51 (TSSPDCL-15):** A Pyrheliometer measures:
(a) Temperature of solar PV cell (b) Intensity of direct solar radiation at normal incidence (c) Intensity of indirect solar radiation (d) Efficiency of a solar PV cell
**Ans: (b)** — direct beam radiation at normal incidence.
**Concept:** Pyrheliometer → direct (beam) radiation; pyranometer → global/total.
**Twist:** "Total (global) radiation" → pyranometer. "Diffuse radiation" → shaded pyranometer.

**Q52 (HMWS-15):** If penalty factor of a power plant is unity, its incremental transmission loss is:
(a) 0.5 (b) −1.0 (c) Zero (d) 1.0
**Ans: (c)** — L = 1/(1−∂PL/∂PG); L=1 → ∂PL/∂PG = 0.
**Concept:** Penalty factor L = 1/(1 − ∂PL/∂PG).
**Twist:** "∂PL/∂PG = 0.2" → L = 1/0.8 = 1.25. "Losses ignored" → L=1 for all units.

**Q53 (HMWS-15):** Diversity factor is always:
(a) Zero (b) Less than one (c) Greater than one (d) Equal to one
**Ans: (c)** — DF > 1 always.
**Concept:** Σ individual MD > station MD.
**Twist:** "Load factor can be < or = 1". "DF = 1" → all consumers peak at same time.

**Q54 (HMWS-15):** Main function of economizer of a boiler plant is to:
(a) Increase steam production (b) Reduce fuel consumption (c) Increase steam pressure (d) Increase boiler life
**Ans: (b)** — preheats feed water with flue gas → saves fuel.
**Concept:** Economizer preheats feedwater; superheater raises steam temp; air preheater heats combustion air.
**Twist:** "Superheater function" → increases steam temperature (not pressure). "Feed water pump" → develops pressure (Q65).

**Q55 (APGenco-17):** Demand factor 0.5, load factor 0.2, connected load 400 MW. Average demand:
(a) 40 MW (b) 100 MW (c) 140 MW (d) 280 MW
**Ans: (a)** — MD = 0.5×400 = 200; avg = 0.2×200 = 40 MW.
**Concept:** MD = DF×CL; avg = LF×MD.
**Twist:** "Average = LF×DF×CL". "MD = 100 (distractor)".

**Q56 (TSSPDCL-18):** If real power demand suddenly increases, system frequency will:
(a) Increase (b) Remain same (c) Decrease (d) First increase then decrease
**Ans: (c)** — extra load drawn from stored kinetic energy → speed/frequency falls.
**Concept:** Sudden ΔP → Δf dip (KE ∝ f²).
**Twist:** "Generation increased fast" → governor restores. "AGC" → frequency returns to nominal via secondary control.

**Q57 (TSSPDCL-18):** Regulation R=1%, damping D=0.8. Change in generation for a frequency drop of 0.0015 p.u:
(a) 0.0015 (b) −0.0015 (c) 0.15 (d) −0.15
**Ans: (c)** — ΔPg = −Δf/R = −(−0.0015)/0.01 = +0.15 p.u.
**Concept:** LFC: ΔPg = −Δf/R (p.u.); drop Δf = −0.0015.
**Twist:** "Δf = +0.0015 (rise)" → ΔPg = −0.15 (generation reduced). "R=2%" → 0.075.

**Q58 (APSPDCL-19):** Tariff quoted in Rs/unit; unit here refers to:
(a) kW (b) kVAh (c) kWh (d) Ampere-hours
**Ans: (c)** — energy unit = kWh.
**Concept:** 1 unit = 1 kWh.
**Twist:** "Demand charges in Rs/kVA". "Billing on kVAh" → PF incentive (some utilities).

**Q59 (APSPDCL-19):** For economic operation of generators in a thermal plant, all plants should operate:
(a) At maximum efficiency (b) At the same incremental fuel cost (c) Such that fuel costs are same (d) At different incremental fuel costs
**Ans: (b)** — equal λ (IC1=IC2=...=λ) minimizes total fuel cost.
**Concept:** ELD coordination: IC1=IC2=λ (neglecting losses).
**Twist:** "Losses included" → modify IC with penalty factors. "Max efficiency ≠ economic" → max efficiency point not the ELD solution.

**Q60 (APSPDCL-19):** Demand factor for an electrical system is the ratio of:
(a) Relative power to total power (b) Maximum demand to connected load (c) Maximum demand to average load (d) Average power to maximum power
**Ans: (b)** — DF = MD/connected load.
**Concept:** DF ≤ 1.
**Twist:** "LF = avg/MD (d)". "Diversity factor = Σ indiv MD/MD".

**Q61 (APEPDCL-19):** Connected load 100 kW, peak 80 kW, base 20 kW, avg 40 kW. Load factor:
(a) 80% (b) 40% (c) 50% (d) 60%
**Ans: (c)** — LF = 40/80 = 50%.
**Concept:** LF = avg/peak.
**Twist:** "Use connected load 100" → 40% (trap b). "Use base load 20" → 25%.

**Q62 (APTransco-19):** IC1 = 25+0.2PG1, IC2 = 32+0.2PG2, total 250 MW. Economic allocation:
(a) PG1=142.5, PG2=107.5 (b) PG1=109.75, PG2=140.25 (c) PG1=PG2=125 (d) PG1=100, PG2=150
**Ans: (a)** — IC1=IC2 → PG1−PG2=35, PG1+PG2=250 → PG1=142.5, PG2=107.5.
**Concept:** ELD: equal incremental cost.
**Twist:** "Same equations but load 300 MW" → PG1=167.5, PG2=132.5. "Same IC slope, different intercept" → solve 2×2.

**Q63 (APTransco-19):** Consumer uses 600 kWh/day at LF 0.40; LF raised to 0.70 without increasing MD. Energy consumed:
(a) 950 kWh (b) 1000 kWh (c) 1050 kWh (d) 1100 kWh
**Ans: (c)** — MD = 600/0.4 = 1500 kW; energy = 0.7×1500 = 1050 kWh.
**Concept:** Energy = LF × MD × hours.
**Twist:** "LF to 0.8" → 1200 kWh. "Daily hours = 24 always".

**Q64 (TSPSC-AEE-23):** G1 (200 MW) and G2 (400 MW) in parallel, total 300 MW, both 4% droop. Individual powers:
(a) G1=50, G2=250 (b) G1=200, G2=100 (c) G1=150, G2=150 (d) G1=100, G2=200
**Ans: (d)** — equal % droop → share in proportion to ratings: P1:P2 = 200:400 → 100:200 MW.
**Concept:** Parallel generators: ΔP ∝ rating when droop equal (Δf common).
**Twist:** "Droop G1=4%, G2=2%" → G2 responds more per unit (share not proportional). "Total 600 MW" → 200/400.

**Q65 (TSPSC-AEE-23):** Which develops pressure in the working-fluid cycle of a thermal power plant?
(a) Superheater (b) Steam turbine (c) Condenser (d) Feed water pump
**Ans: (d)** — feed water pump creates the boiler/working pressure.
**Concept:** FWP raises pressure; superheater raises temp; turbine converts; condenser creates vacuum.
**Twist:** "Superheater" → temperature not pressure. "Condenser" → vacuum/low pressure.

**Q66 (TSSPDCL-AE-2023):** Annual LDC of 30 MW station is straight line 20 MW → 5 MW. Units generated/year:
(a) 109.5×10⁶ (b) 175.2×10⁶ (c) 219.0×10⁶ (d) 131.4×10⁶
**Ans: (a)** — Units = area = ½×15×8760 + 5×8760 = 109500 MWh = 109.5×10⁶ kWh.
**Concept:** Units = area under LDC (kWh); trapezoid area.
**Twist:** "Installed 30 MW unused" → irrelevant to energy (only LDC area). "Line 30→10 MW" → 175.2×10⁶.

**Q67 (TSSPDCL-AE-2023):** Hydro station, reservoir force 50×10¹⁰ N at head 200 m, overall η=72%. Electrical energy available:
(a) 2×10⁵ MWh (b) 2×10⁵ kWh (c) 20000 kWh (d) 20000 MWh
**Ans: (d)** — E = mgh·η = F·h·η = 50×10¹⁰×200×0.72 = 7.2×10¹⁴ J = 20000 MWh (÷3.6×10⁹ J/MWh).
**Concept:** E = F·h·η (J) → MWh.
**Twist:** "Head 100 m" → 10000 MWh. "Energy in kWh" → 2×10⁷ kWh.

**Q68 (TSSPDCL-AE-2023):** Thermal station components in increasing order of efficiency:
(a) Boiler, Generator, Turbine (b) Turbine, Generator, Boiler (c) Boiler, Turbine, Generator (d) Turbine, Boiler, Generator
**Ans: (d)** — turbine (~30-40%) < boiler (~85-90%) < generator (~95-98%).
**Concept:** Typical efficiencies: turbine lowest, generator highest.
**Twist:** "Which has lowest efficiency" → steam turbine. "Overall station η" → product.

**Q69 (TSGenco-24):** IC1=0.008P1+8, IC2=0.0096P2+6.4, limits 625/100 MW, demand 800 MW. Economic loading:
(a) P1≈445, P2≈355 (b) P1≈355, P2≈445 (c) P1≈345, P2≈455 (d) P1≈455, P2≈345
**Ans: (c)** — IC1=IC2 → 0.008P1−0.0096P2 = −1.6; P1+P2=800 → P1=345, P2=455.
**Concept:** ELD: IC1=IC2=λ (with generator limits).
**Twist:** "Check limits" → 345/455 within 100–625. "Demand 600" → recompute (~255/345).

**Q70 (TSGenco-24):** Yearly duration curve straight line 140 MW → 30 MW. Units: one 80 MW + two 50 MW. Plant capacity factor:
(a) 0.607 (b) 0.472 (c) 0.388 (d) 0.632
**Ans: (b)** — PC = 80+100 = 180 MW; avg = 30 + ½(140−30) = 85 MW; PCF = 85/180 = 0.472.
**Concept:** PCF = average load / plant capacity.
**Twist:** "Avg of LDC = mean of endpoints" (linear). "PC = 130 (only one 50)" → 0.654 trap.

**Q71 (TSGenco-24):** Consumer 1500 kW @0.8 lag for 12 h, 1000 kW UPF for 12 h. Daily load factor:
(a) 0.833 (b) 0.666 (c) 1.5 (d) 0.8
**Ans: (a)** — avg = 1250 kW; LF = 1250/1500 = 0.833.
**Concept:** LF = avg/MD (same as Q11).
**Twist:** "Include pf in avg power" → kW already given. "2000/1000 pattern" → LF = 0.75 (Q27).

**Q72 (TSGenco-24):** Hydel plant, discharge 3000 m³/s, head 30 m, plant efficiency 79%. Power:
(a) 697.5 MW (b) 345.2 MW (c) 823.7 MW (d) 423.1 MW
**Ans: (a)** — P = η·g·Q·H = 0.79×9.81×3000×30 = 697.5 MW.
**Concept:** P = ηρgQH (ρ=1000 kg/m³); ρgQH in W.
**Twist:** "η=100%" → 883 MW. "Head 20 m" → 465 MW. "Q in m³/hr" → divide by 3600.

**Q73 (TSGenco-24):** Which turbine has the highest specific speed?
(a) Pelton (b) Kaplan (c) Francis (d) Impulse
**Ans: (b)** — Kaplan (axial, low head, high specific speed) has highest Ns.
**Concept:** Ns order: Kaplan > Francis > Pelton/Impulse.
**Twist:** "Highest head" → Pelton. "Impulse vs reaction" → Pelton is impulse, low Ns.

**Q74 (TSGenco-24):** Statements on solar PV I-V:
I. Constant T: Pmax ∝ irradiation. II. Constant irradiation: Pmax ∝ temperature.
(a) Both correct (b) Both incorrect (c) I correct, II incorrect (d) I incorrect, II correct
**Ans: (c)** — Pmax ∝ irradiation (I true); Pmax ∝ 1/T (temperature rise lowers Voc, II false).
**Concept:** Pmax ↑ with irradiance, ↓ with temperature.
**Twist:** "Voc vs temperature" → inverse. "Isc vs irradiation" → proportional.

---

## Part B — PROTECTION (Relays, Circuit Breakers, Grounding, Surge Protection) — 123 Qs

**Q1 (EPDCL-10):** Which portion of the power system is least prone to faults?
(a) Alternators (b) Switchgear (c) Transformers (d) Overhead lines
**Ans: (a)** — alternators (with good maintenance) are least fault-prone; overhead lines most.
**Concept:** Fault statistics: overhead lines > transformers > switchgear > alternators.
**Twist:** "Most fault-prone" → overhead lines. "Transformers need Buchholz" → internal faults.

**Q2 (EPDCL-10):** Buchholz relay is used in protection of:
(a) Transmission lines (b) Circuit breakers (c) Transformers (d) Generators
**Ans: (c)** — Buchholz protects oil-immersed transformers (>500 kVA).
**Concept:** Buchholz: gas/incipient faults in transformers.
**Twist:** "Can't be used on" → air-cooled transformer (Q4). "Connected between tank and conservator" (Prot Q66).

**Q3 (EPDCL-10):** In inverse-time overcurrent relays, the current-time characteristic is:
(a) Parabolic (b) Exponential (c) Linear (d) Hyperbolic
**Ans: (d)** — inverse time: t decreases as I increases (approx. hyperbolic).
**Concept:** IDMT: t = 0.14·TMS/(PSM^0.02 − 1).
**Twist:** "Very inverse / extremely inverse" → different exponents. "Definite time" → flat after threshold.

**Q4 (SSC-JE-10):** Buchholz relay cannot be used on:
(a) 500 kV transformer (b) 1000 kV transformer (c) Three-phase transformers (d) Air-cooled transformer
**Ans: (d)** — needs oil; air-cooled (dry-type) transformers can't use Buchholz.
**Concept:** Buchholz requires oil-filled conservator system.
**Twist:** "Oil-immersed >500 kVA" → used. "Dry-type" → use different protection (overcurrent/differential).

**Q5 (SSC-JE-10):** Differential relays protect equipment against:
(a) Internal faults (b) Reverse current (c) Over voltage (d) Over current
**Ans: (a)** — differential detects internal faults by current imbalance.
**Concept:** Differential protection = compare currents at two ends.
**Twist:** "Merz-Price" → unit protection (busbar/generator/transformer). "External faults" → balanced, no trip.

**Q6 (SSC-JE-10):** The lightning arrestor is connected:
(a) In series with the line (b) Between line and earth (c) To a pole near the line (d) To circuit breaker
**Ans: (b)** — LA is connected line-to-earth (shunt).
**Concept:** LA diverts surge to ground; series connection would block power flow.
**Twist:** "Location of LA" → near transformer (Prot Q53). "Bypass/isolator for LA" → for maintenance.

**Q7 (SSC-JE-10):** 3-φ transformer star-delta. For protection, the CT connection should be:
(a) Star-star (b) Delta-star (c) Delta-delta (d) Star-delta
**Ans: (b)** — CT primary (HV star side) in delta; CT secondary in star, so connection = delta-star.
**Concept:** CT compensation matches transformer vector group (removes 30° phase shift & zero-seq).
**Twist:** "Transformer delta-star" → CTs star-delta. "Wrong CT connection" → relay maloperation on external faults.

**Q8 (SSC-JE-11):** L=1 H, C=0.01 μF, interrupted current 10 A. Voltage across breaker contacts:
(a) 50 kV (b) 57 kV (c) 60 kV (d) 100 kV
**Ans: (d)** — V = i√(L/C) = 10×√(1/0.01×10⁻⁶) = 100 kV.
**Concept:** Restriking voltage = i√(L/C).
**Twist:** "L=4 H, i=5 A" → 100 kV (Prot Q87). "L=5 H" → V = 5×√(5/0.01e-6) = 111.8 kV (compare Q101).

**Q9 (APGenco-12):** Operating time of an instantaneous relay is:
(a) 0.001 sec (b) 0.01 sec (c) 0.1 sec (d) 1 sec
**Ans: (c)** — ~0.1 s for instantaneous relays.
**Concept:** Instantaneous relay operating time ≈ 0.1 s (few cycles).
**Twist:** "Modern digital relays" → few ms (Prot Q97). "IDMT at high PSM" → approaches definite minimum.

**Q10 (APGenco-12/HMWS-12):** For a round wire, approximate fusing current is given by:
(a) K·d^3 (b) K·d² (c) (1/K)·d (d) d³
**Ans: (a)** — fusing current I = K·d^(3/2) (document renders exponent as 3).
**Concept:** I_fusing = K·d^(3/2) (d = diameter).
**Twist:** "d doubled" → I ×2.83. "Fusing factor = min fusing current/current rating" (Prot Q116).

**Q11 (APGenco-12):** Relay 5 A, 2.2 s IDMT, setting 125%, TMS 0.6, CT 400/5, fault current 4000 A. Relay operating (pick-up) current:
(a) 6.25 A (b) 5 A (c) 8 A (d) 2.2 A
**Ans: (a)** — pickup = 1.25 × 5 = 6.25 A.
**Concept:** Pickup = (PS/100) × CT secondary rating.
**Twist:** "Operating time with TMS 0.6" → t = 0.14×0.6/(PSM^0.02−1) with PSM=4000/(80×6.25)=8. "Setting 50% CT 400/5" → PSM 10 (Prot Q26).

**Q12 (APGenco-12):** Auto-reclosing is used in case of:
(a) Lightning arrester (b) Bulk oil CB (c) Air blast CB (d) Minimum oil CB
**Ans: (c)** — auto-reclose suits EHV air-blast CBs (fast, transient faults).
**Concept:** Auto-reclosing clears transient faults; used with fast CBs (air-blast).
**Twist:** "Single-phase auto-reclose" → improves stability. "Dead time" → de-ionization time.

**Q13 (APGenco-12):** Severe overvoltages are produced during arcing faults when neutral is:
(a) Isolated (b) Solidly earthed (c) Earthed through low resistance (d) Earthed through inductive coil
**Ans: (a)** — isolated neutral: healthy phases rise to √3× line-to-neutral during arcing ground fault.
**Concept:** Isolated-neutral system → overvoltages (arcing ground); grounding limits it.
**Twist:** "Peterson coil" → tunes out capacitive current (Prot/M2). "Solidly earthed" → no such rise, high fault current.

**Q14 (Transco-SE-12):** In a tuned line:
(a) RE voltage & current numerically equal to SE values (b) RE voltage & current greater than SE (c) RE voltage > SE, currents equal (d) RE & SE voltages equal, SE current < RE current
**Ans: (a)** — tuned (SIL-loaded) line: |Vs|=|Vr| and |Is|=|Ir|.
**Concept:** Tuned line → Vr = Vs (Ferranti/SIL balance).
**Twist:** "Line loaded above SIL" → Vr < Vs. "Below SIL" → Vr > Vs (Ferranti).

**Q15 (Transco-12):** Power-frequency rms voltage across breaker contacts after transients die out and arc finally extinguished in all poles:
(a) Recovery voltage (b) Restriking voltage (c) Cut-in voltage (d) Race voltage
**Ans: (a)** — recovery voltage (steady-state, after restriking transients decay).
**Concept:** Restriking voltage (transient) → Recovery voltage (steady rms).
**Twist:** "Initial high-frequency transient" → restriking voltage. "If restrike occurs, arc reignites".

**Q16 (Transco-SE-12):** In resistance switching, the function of the shunt resistor:
(a) Distribute currents uniformly in multi-break CB (b) Increase transient voltages when switching inductive/capacitive loads (c) Reduce the rate of rise of restriking voltage (RRRV) (d) Deionize medium between contacts
**Ans: (c)** — shunt resistor damps oscillation → reduces RRRV.
**Concept:** Resistance switching: R damps ½LI² ↔ ½CV² energy → lower RRRV.
**Twist:** "Critical R = 0.5√(L/C)" (Prot Q80/Q101). "Exponential recovery without overshoot" → critical damping.

**Q17 (Transco-12):** Number of poles per phase of a breaker is a function of:
(a) Current to be chopped (b) Operating voltage (c) Power frequency (d) Recovery voltage
**Ans: (b)** — more poles/phase at higher operating voltage.
**Concept:** Series breaks per phase ∝ operating voltage (voltage distribution).
**Twist:** "Multiple breaks share voltage" → grading capacitors. "Gas pressure" → dielectric strength.

**Q18 (Transco-12):** Capacitor switching is easily done with:
(a) Air blast CB (b) Oil CB (c) Vacuum CB (d) SF6 CB
**Ans: (c)** — vacuum CBs interrupt capacitor current without restrike.
**Concept:** Vacuum CB: no restrike, many switching ops → capacitor bank switching.
**Twist:** "Also SF6 can" → but VCB preferred for cost/restrike (Prot Q29/Q96). "High reliability, low maintenance" (Prot Q102).

**Q19 (Transco-12):** A distance relay is inherently directional if its R-X characteristic is:
(a) A straight line offset from origin (b) A circle enclosing origin (c) A parabola with focus at origin (d) A circle passing through origin
**Ans: (d)** — circle through origin = Mho = inherently directional.
**Concept:** Mho relay circle passes through origin → only forward faults.
**Twist:** "Circle centered at origin" → impedance relay (non-directional). "Straight horizontal line" → reactance relay (Prot Q89).

**Q20 (Transco-SE-12):** Most efficient torque-producing actuating structure in an induction relay:
(a) Shaded pole structure (b) Watt-hour meter structure (c) Single induction loop structure (d) Induction cup structure
**Ans: (d)** — induction cup (drag-cup) gives highest torque/inertia ratio.
**Concept:** Induction cup: low inertia, high torque, common in high-speed relays.
**Twist:** "Max driving torque condition" → quadrature fluxes (Prot Q122). "Disc relay" → used in IDMT.

**Q21 (Transco-12):** The line trap unit in carrier-current relaying:
(a) Offers high impedance to 50 Hz signals (b) Offers high impedance to carrier-frequency signals (c) Offers low impedance to carrier-frequency signals (d) Acts as protective device
**Ans: (b)** — line trap tuned to 50 Hz → low impedance to power frequency, high impedance to carrier.
**Concept:** Line trap: keeps carrier on the line; blocks carrier into station bus.
**Twist:** "Wave trap blocks carrier". "Coupling capacitor" → lets carrier in/out.

**Q22 (Transco-12):** Protection relay for low fault settings and high speed in a transformer:
(a) Merz-Price protection (b) Harmonic restraint relay (c) Buchholz relay (d) Translay relay
**Ans: (b)** — harmonic-restraint (biased differential) relay for high-speed transformer protection.
**Concept:** Harmonic restraint blocks tripping on magnetizing inrush (2nd harmonic).
**Twist:** "Inrush has 2nd harmonic" → restraint. "Buchholz" → slow, gas faults only.

**Q23 (Transco-12):** Wattmetric relay with directional characteristic protects a generator against:
(a) Loss of excitation (b) Over speed (c) Failure of prime mover (d) Earth fault
**Ans: (c)** — reverse-power relay (watts) trips when generator takes power (prime-mover failure).
**Concept:** Reverse power = motoring of generator → prime mover failure.
**Twist:** "Turbine failure / reverse power" (Prot Q123). "Loss of excitation" → offset mho (Prot Q91).

**Q24 (Transco-12):** Best-suited relay for 3-zone protection scheme:
(a) Impedance relay (b) Reactance relay (c) Mho relay (d) Overcurrent relay
**Ans: (c)** — Mho relay best for stepped 3-zone distance protection.
**Concept:** 3-zone distance protection (Mho for long EHV lines).
**Twist:** "Short line" → reactance relay (Prot Q41). "Long EHV line" → mho (Prot Q76).

**Q25 (Transco-12):** Non-shielding method of overvoltage protection is based on:
(a) Allowing arc path between ground and conductor (b) Insulation breakdown (c) Switching capacitor banks (d) None
**Ans: (b)** — spark gaps/LA work by insulation breakdown (non-shielding).
**Concept:** Shielding (ground wire/masts) vs non-shielding (LA, spark gaps).
**Twist:** "Shielding methods" → ground wire, lightning masts (Prot Q73). "LA diverts to ground".

**Q26 (Transco-12):** Fault current 2000 A, relay setting 50%, CT 400:5. Plug setting multiplier (PSM):
(a) 25 (b) 15 (c) 50 (d) 10
**Ans: (d)** — relay pickup = 0.5×5 = 2.5 A; CT secondary = 2000/80 = 25 A; PSM = 25/2.5 = 10.
**Concept:** PSM = If / (CT ratio × relay setting current).
**Twist:** "Fault 2100, setting 70%, CT 300:5" → PSM = 10 (Prot Q108). "Setting 100%" → PSM = 25.

**Q27 (Transco-12):** In a biased differential relay, bias is defined as ratio of:
(a) Number of turns of restraining and operating coil (b) Operating coil current to restraining coil current (c) Fault current to operating coil current (d) Fault current to restraining coil current
**Ans: (a)** — bias = nr/no (restraining/operating coil turns).
**Concept:** Biased (percentage) differential: slope = nr/no; trip at nr/no = (i1−i2)/((i1+i2)/2) (Prot Q118).
**Twist:** "Bias winding reduces sensitivity to external faults/CT mismatch". "Slope setting 10-40%".

**Q28 (Transco-12/SSC-JE-13):** Resistance switching is normally employed in:
(a) All breakers (b) Bulk oil breakers (c) Minimum oil breakers (d) Air blast circuit breakers
**Ans: (d)** — air-blast CBs (also SF6) use resistance switching.
**Concept:** Resistance switching → reduces RRRV in air-blast/SF6 CBs.
**Twist:** "Capacitor switching" → vacuum. "Where high RRRV expected" → shunt resistance (Prot Q80).

**Q29 (Transco-12):** Considering cost and effectiveness, best CB for capacitor-bank switching:
(a) Vacuum (b) Air blast (c) SF6 (d) Oil
**Ans: (a)** — vacuum CB (no restrike, low cost).
**Concept:** VCB for capacitor switching (Prot Q96).
**Twist:** "HV capacitor banks" → SF6 sometimes. "Frequent switching" → vacuum.

**Q30 (APSPDCL-12):** Relay most likely to operate during power swings:
(a) Reactance relay (b) Impedance relay (c) Mho relay (d) Buchholz relay
**Ans: (a)** — reactance relay has no power-swing blocking → operates during swings.
**Concept:** Power swings: mho least affected; reactance most affected (no directional/swing limit).
**Twist:** "Which relay has power-swing blocking" → mho. "Distance relay reach on swings" → use mho with blinder.

**Q31 (APSPDCL-12/SSC-JE-10):** OCB 1500 A, 2000 MVA, 33 kV. Making current (kA):
(a) 51.51 (b) 35 (c) 89.28 (d) 154.54
**Ans: (c)** — I_break = 2000/(√3×33) = 34.99 kA; I_making = 2.55×34.99 = 89.2 kA.
**Concept:** Making capacity = 2.55 × breaking capacity.
**Twist:** "Only breaking current asked" → 35 kA (b, trap). "1500 A rated current is distractor".

**Q32 (APSPDCL-12):** Rating of lightning arrester for a 220 kV, 3-φ system:
(a) 220 kV, 10 kA (b) 220 kV, 5 kA (c) 198 kV, 10 kA (d) 198 kV, 2 kA
**Ans: (c)** — LA voltage = 1.1×220×0.8 (earthing coefficient) ≈ 193.6 ≈ 198 kV; 10 kA discharge.
**Concept:** LA rating = 1.1×V_L×C (C≈0.8 earthed, 1.0 ungrounded).
**Twist:** ">66 kV stations" → 10 kA arresters (Prot solution note). "Solidly earthed" → coefficient 0.8.

**Q33 (APSPDCL-12):** Overcurrent relay, current setting 125%, CT 400/5. Pick-up value:
(a) 6.25 A (b) 500 A (c) 100 A (d) 80 A
**Ans: (a)** — pickup = 1.25×5 = 6.25 A.
**Concept:** Pickup = PS% × CT secondary rating.
**Twist:** "Fault current 4000 A, setting 125%, TMS 0.6" → PSM = 4000/(80×6.25) = 8 (Prot Q11). "Pickup in primary amps" → 500 A (trap b).

**Q34 (APSPDCL-12):** Merz-Price protection is more suitable for:
(a) Transformers (b) Generators (c) Transmission lines (d) Loads
**Ans: (b)** — Merz-Price (circulating-current differential) for generators (also transformers with ratio/bias correction).
**Concept:** Merz-Price = percentage differential; suited to generators.
**Twist:** "Transformers need bias + ratio match" → differential with compensation. "Lines" → distance instead.

**Q35 (HMWS-12):** Minimum arcing voltage is least in the case of:
(a) Carbon (b) Copper (c) Silver (d) Tungsten
**Ans: (c)** — silver has the lowest minimum arcing voltage.
**Concept:** Contact material: silver → low arcing voltage, low contact resistance.
**Twist:** "Contact material for low arc erosion" → tungsten. "Silver plated contacts".

**Q36 (HMWS-12):** The resistance of an electric arc can be increased by:
(a) Increasing concentration of ionized particles (b) Reducing the arc length (c) Splitting the arc (d) Increasing the arc cross-section
**Ans: (c)** — arc splitting (arc chutes) increases arc resistance.
**Concept:** Arc resistance ↑ by cooling, lengthening, splitting.
**Twist:** "Arc quenching methods" → lengthening + splitting + cooling. "Blast" → air/SF6 blast.

**Q37 (HMWS-12):** Fault clearing time of a CB is usually of:
(a) Few seconds (b) One second (c) Few minutes (d) Few cycles of supply voltage
**Ans: (d)** — fault cleared within a few cycles (2-8 cycles).
**Concept:** CB total clearing time ≈ 3-8 cycles (relay + breaker).
**Twist:** "Instantaneous relay ~0.1 s" (Prot Q9). "High-speed CB < 3 cycles".

**Q38 (HMWS-12):** Which CB takes minimum time in installation?
(a) Air blast (b) Minimum oil (c) Bulk oil (d) SF6
**Ans: (d)** — SF6 (metal-clad, compact) installs fastest.
**Concept:** SF6 CB: compact, gas insulated, quick installation, low maintenance.
**Twist:** "High reliability minimum maintenance" → SF6/vacuum (Prot Q102). "Bulk oil" → heavy, slow install.

**Q39 (HMWS-12):** For long EHV/UHV transmission lines we normally use:
(a) Air circuit breaker (b) Air blast circuit breaker (c) Oil circuit breaker (d) Isolating switch
**Ans: (b)** — air-blast (and SF6) CBs for EHV/UHV.
**Concept:** EHV lines → air-blast/SF6 (fast, high voltage).
**Twist:** "Also SF6 correct" → OHM keys air-blast. "Auto-reclose with air-blast" (Prot Q12).

**Q40 (HMWS-12):** Under-voltage relays are mostly used for:
(a) Transformer protection (b) Bus-bar protection (c) Motor protection (d) Feeder protection
**Ans: (c)** — undervoltage relays protect motors (avoid re-acceleration/stalling).
**Concept:** UV relay → motor protection (drop-out on sag).
**Twist:** "Thermal relay" → overload (Prot Q55). "Motor protection suite" → UV + overload + single phasing.

**Q41 (HMWS-12/EPDCL-14):** A relay used on short transmission lines is:
(a) Mho relay (b) Reactance relay (c) Impedance relay (d) Admittance relay
**Ans: (b)** — reactance relay for short lines (fault resistance/arc doesn't shift reach).
**Concept:** Short lines → reactance relay (immune to arc resistance).
**Twist:** "Medium lines" → impedance relay (Prot Q72). "Long lines" → mho (Prot Q24/76).

**Q42 (HMWS-12):** Match List-I (Thyrite arrester, Sag template, Cable sheaths, Circuit breaker) with List-II (Tower location, Cross bonding, Restriking voltage, Non-linear resistance):
(a) 4,1,3,2 (b) 4,1,2,3 (c) 1,4,3,2 (d) 4,3,1,2
**Ans: (b)** — Thyrite→Non-linear (4), Sag template→Tower location (1), Cable sheaths→Cross bonding (2), CB→Restriking (3).
**Concept:** Cross-bonding for cable sheaths; sag template for tower location.
**Twist:** "Sag template also for stringing chart". "Thyrite → nonlinear V-I resistance".

**Q43 (SSC-JE-12):** In a thyrite lightning arrester, the resistance:
(a) Is low at low current and high at high current (b) Increases linearly with applied voltage (c) Decreases linearly with applied voltage (d) Is high at low current and low at high current
**Ans: (c)** — per OHM key: thyrite resistance decreases with applied voltage.
**Concept:** Thyrite = silicon-carbide nonlinear resistor; note many texts state resistance is high at low current / low at high current (option d).
**Twist:** "Surge → low resistance path to ground" (Prot Q79). "Non-linear resistance" (Prot Q42).

**Q44 (SSC-JE-12):** Magnetic blowout coils are generally used in:
(a) Air break circuit breaker (b) Air blast circuit breaker (c) Oil circuit breaker (d) Vacuum circuit breaker
**Ans: (b)** — magnetic blowout in air-blast/air-break CBs to deflect and stretch arc.
**Concept:** Magnetic blowout → arc lengthening (air-blast CBs).
**Twist:** "Blowout in DC breakers". "Air-blast uses high-pressure air" → arc extinction.

**Q45 (SSC-JE-13):** Compared to breaking capacity, the making capacity of a CB should be:
(a) More (b) Less (c) Equal (d) Unrelated
**Ans: (a)** — making = 2.55 × breaking.
**Concept:** Making capacity (asymmetrical, includes DC) = 2.55× breaking.
**Twist:** "Symmetrical making = 1.8× breaking (approx)". "Rated breaking in MVA" (Prot Q69).

**Q46 (SSC-JE-13):** In a motor starter, the electromechanical contactor provides inherent protection against:
(a) Over-current (b) Short-circuit (c) Single-phasing (d) Under-voltage
**Ans: (d)** — contactor drops out on undervoltage (inherent UV protection).
**Concept:** Contactor: UV release; does NOT protect overload/SC (needs relays/fuses).
**Twist:** "Overload relay added externally". "No-volt coil" → undervoltage protection.

**Q47 (EPDCL-14):** In an IDMT electromagnetic overcurrent relay, minimum time is achieved because of:
(a) Electromagnetic damping (b) Proper mechanical design (c) Appropriate time delay element (d) Saturation of the magnetic circuit
**Ans: (d)** — magnetic saturation at high currents flattens the time curve → minimum time.
**Concept:** IDMT: saturation limits torque growth → definite minimum time.
**Twist:** "High fault current" → PSM large → time approaches min. "Inverse curve exponent".

**Q48 (EPDCL-14):** When voltage is high and current to be interrupted is low, the preferred CB is:
(a) Oil CB (b) Air blast CB (c) Air break CB (d) Vacuum CB
**Ans: (d)** — vacuum CB suited for high voltage, low current interruption.
**Concept:** VCB: high voltage withstand, low current interruption (no restrike).
**Twist:** "High voltage high current" → SF6/oil. "Current chopping" → vacuum (Prot Q61).

**Q49 (APSPDCL-14):** Shape of the disc of an induction disc relay:
(a) Circular (b) Spiral (c) Elliptical (d) Triangular
**Ans: (b)** — spiral/coiled disc (drag-cup style) in induction relays.
**Concept:** Induction disc/spiral element for IDMT relays.
**Twist:** "Cup type" → induction cup (Prot Q20). "Spiral spring" → reset mechanism.

**Q50 (APSPDCL-14):** For remote operation, a CB must be equipped with a:
(a) Time delay trip (b) Shunt trip (c) Inverse time trip (d) None
**Ans: (b)** — shunt trip coil allows remote tripping.
**Concept:** Shunt trip: external command trips the breaker.
**Twist:** "Close coil for remote closing". "Trip circuit supervision".

**Q51 (ISRO-14):** Reactance relay is normally preferred for protection against:
(a) Overload currents only (b) Phase faults only (c) Earth faults only (d) High voltage protection only
**Ans: (c)** — earth faults: earth resistance is variable → reactance relay (reach immune to resistance).
**Concept:** Reactance relay → earth fault protection (short lines).
**Twist:** "Ground fault relaying preferred relay" → reactance (Prot Q76). "Arc resistance immunity".

**Q52 (ISRO-14):** If a combination of HRC fuse and CB is used, the CB operates for:
(a) Low overload currents (b) Short-circuit currents (c) All abnormal currents (d) Combination never used
**Ans: (a)** — fuse clears heavy SC; CB handles low overloads (back-up protection).
**Concept:** HRC fuse + CB: fuse for short-circuit, CB for overload (fuse-backup).
**Twist:** "Fuse ruptures on SC first". "CB opens first on overload".

**Q53 (ISRO-14):** Lightning arrestor should be located:
(a) Away from the CB (b) Near the circuit breaker (c) Near the transformer (d) Away from the transformer
**Ans: (c)** — LA placed as close as possible to the protected transformer.
**Concept:** LA near transformer → minimal lead length for surge protection.
**Twist:** "Surge reaches protected equipment fast". "Lead length" → keep short.

**Q54 (ISRO-14):** The earth wire should not be thinner than a:
(a) 20 SWG wire (b) 16 SWG wire (c) 10 SWG wire (d) 8 SWG wire
**Ans: (d)** — min earth wire 8 SWG (largest size of earth lead per IS/IEE).
**Concept:** IE/IS: earth wire not less than 8 SWG.
**Twist:** "Largest earth lead 3 SWG". "Earth continuity conductor sizing".

**Q55 (ISRO-14):** A thermal protection switch provides protection against:
(a) Overload (b) Temperature (c) Short circuit (d) Over voltage
**Ans: (a)** — thermal switch (bimetallic) → overload protection.
**Concept:** Thermal overload (heat ∝ I²t).
**Twist:** "HRC fuse" → short circuit (Prot Q77). "Thermal + magnetic" → motor protection.

**Q56 (ISRO-14):** Ring system 33 kV (supplies at both ends), nodes 1-5 (5 = load). Directional overcurrent relays needed at:
(a) 1 and 4 (b) 2 and 3 (c) 1, 4 and 5 (d) 2, 3 and 5
**Ans: (b)** — at the ring points (2 and 3) where fault current can flow both ways; source ends use non-directional.
**Concept:** Directional OC at ring/parallel-feed points; non-directional at source ends.
**Twist:** "Parallel feeders from one end" → non-directional source, directional load end (Prot Q85). "Ring main" → directional at both ring nodes.

**Q57 (ISRO-14):** Correct opening sequence of isolator, CB, earthing switch:
(a) Open CB → open isolator → close earthing switch (b) Open isolator → close CB → open earthing switch (c) Close earthing switch → open CB → open isolator (d) Close CB → close isolator → open earthing switch
**Ans: (a)** — CB first (interrupts load), then isolator (no-load), then earthing switch (safety).
**Concept:** Opening: CB → isolator → earth switch; closing is reverse.
**Twist:** "Isolator must not make/break load current". "Closing sequence" → earth switch out → isolator → CB.

**Q58 (ISRO-14):** RRRV (rate of rise of restriking voltage) depends upon:
(a) Resistance of system only (b) Inductance only (c) Capacitance only (d) Inductance and capacitance of the system
**Ans: (d)** — RRRV = i·ω/(√2) depends on L and C (ω=1/√(LC)).
**Concept:** RRRV ∝ 1/√(LC); restriking frequency f = 1/(2π√(LC)).
**Twist:** "Restriking voltage = i√(L/C)" (Prot Q8). "Frequency of restriking = 1/√(LC) rad/s" (Prot Q93).

**Q59 (SSC-JE-SI-14):** Protection that does not respond to faults beyond its zone even if fault current passes through the zone:
(a) Busbar protection (b) Unit protection (c) Generator protection (d) Back-up protection
**Ans: (b)** — unit protection responds only to internal faults.
**Concept:** Unit protection (differential) → internal faults only; external faults balanced out.
**Twist:** "Differential = unit protection". "Back-up protection" → responds to external faults too.

**Q60 (SSC-JE-SI-14):** An isolator is used in series with air-blast CB at UHV lines because:
(a) Current to be interrupted will be large (b) Gap between CB contacts is small, so isolator is used to switch off voltage (c) Gap between CB poles is small (d) CB life is enhanced
**Ans: (b)** — small contact gap → isolator provides the visible isolation/voltage withstand.
**Concept:** Isolator: no-load switching, provides visible air gap at UHV.
**Twist:** "Isolator can't break load current". "Bus-side isolator + line-side isolator".

**Q61 (SSC-JE-SI-14):** For average load currents, current chopping occurs more frequently in:
(a) OCBs (b) ACBs (c) SF6 CBs (d) VCBs
**Ans: (b)** — air-blast (ACB) CBs chop small inductive currents (high interrupting speed, poor at low current).
**Concept:** Current chopping: ACB (air blast) most prone at low currents.
**Twist:** "Chooping causes overvoltage" → needs surge protection. "Vacuum chopping" → also possible but OHM keys ACB.

**Q62 (SSC-JE-S2-14):** Supplier's fuse in a domestic wiring system is provided:
(a) After the energy meter (b) Before the energy meter (c) Before distribution board (d) After main switch
**Ans: (a)** — supplier's fuse after the energy meter (protects consumer wiring).
**Concept:** Supplier fuse position: after energy meter, protects consumer circuit.
**Twist:** "Main fuse before meter" → seals/utility. "Distribution board fuses" → sub-circuits.

**Q63 (SSC-JE-S2-14):** Equipment used to limit short-circuit current level in a sub-station:
(a) Isolators (b) Lightning switch (c) Coupling capacitor (d) Series reactor
**Ans: (d)** — series reactor limits short-circuit current.
**Concept:** Series reactor → current-limiting reactor (SC level control).
**Twist:** "Reactors also reduce fault MVA". "Neutral grounding reactor" → different role.

**Q64 (TSTransco-15):** Which portion of the power system is least prone to fault?
(a) Alternators (b) Switchgear (c) Transformers (d) Overhead lines
**Ans: (a)** — alternators least fault-prone (same as Prot Q1).
**Concept:** Fault frequency: overhead lines >> transformers > switchgear > alternators.
**Twist:** "Most prone" → overhead lines. "Cables" → less prone than OHL.

**Q65 (TSTransco-15):** The material used in liquid fuses is:
(a) SF6 (b) Distilled water (c) Carbon tetra chloride (d) Transformer oil
**Ans: (c)** — carbon tetrachloride (CCl4) used in liquid fuses.
**Concept:** Liquid fuse: carbon tetrachloride extinguishing medium.
**Twist:** "HRC fuse fill material" → quartz sand. "Liquid fuse is obsolete".

**Q66 (TSTransco-15):** Buchholz relay is:
(a) Located in the conservator tank (b) Located in the transformer tank itself (c) Connected in the pipe connecting main tank and conservator (d) Installed in the circuit breaker
**Ans: (c)** — Buchholz sits in the pipe between transformer tank and conservator.
**Concept:** Buchholz location: pipe between main tank and conservator.
**Twist:** "Gas collection top / oil surge bottom". "Slow internal/incipient faults".

**Q67 (TSTransco-15):** For protection of rotating machines against lightning surges, _____ is used:
(a) Lightning arrester (b) Capacitor (c) Combination of lightning arrester and capacitor (d) Lightning conductor and arrester
**Ans: (c)** — LA + capacitor (capacitor limits steep wavefront dv/dt on motor windings).
**Concept:** Rotating machine surge protection = LA + capacitor (slow wavefront).
**Twist:** "Transformer surge" → LA alone adequate. "Steep-fronted surges damage motor interturn".

**Q68 (TSTransco-15):** Transformer no-load inrush current is maximum if supply is switched on:
(a) At peak voltage value (b) At zero voltage value (c) At half voltage value (d) At 0.866-time voltage value
**Ans: (b)** — switching at voltage zero → maximum flux offset → maximum inrush.
**Concept:** Inrush: max at V=0 switching (flux doubling); min at V=peak.
**Twist:** "Inrush produces 2nd harmonic" → harmonic-restraint differential (Prot Q22). "Switching at peak" → no inrush.

**Q69 (TSTransco-15):** Breaking capacity of a CB is usually expressed in terms of:
(a) Ampere (b) Volts (c) MW (d) MVA
**Ans: (d)** — breaking capacity in MVA (√3·V·I).
**Concept:** Breaking capacity (MVA) = √3·V_L·I_break.
**Twist:** "Symmetric breaking current in kA". "1000 MVA at 66 kV → I = 8.75 kA".

**Q70 (TSTransco-15):** A negative-sequence relay is used for protection of:
(a) Generator (b) Transformer (c) Motor (d) Long transmission lines
**Ans: (a)** — negative-sequence relay protects generator against unbalance.
**Concept:** Negative-sequence current → rotor heating (2nd-harmonic currents) in generators.
**Twist:** "Also induction motors" → but OHM keys generator. "Unbalanced faults detection".

**Q71 (TSSPDCL-15):** For selecting a CB, _____ should be determined:
(a) Initial (subtransient) current on short-circuit only (b) Transient current at interruption only (c) Resonant frequency only (d) Both (a) and (b)
**Ans: (d)** — need both initial short-circuit current (making) and interruption current (breaking).
**Concept:** CB selection: rated making (initial SC) + breaking (interruption) currents.
**Twist:** "Rated normal current + breaking capacity also needed". "Transient recovery voltage".

**Q72 (TSSPDCL-15):** Choose the WRONG statement:
(a) Impedance relay less affected by synchronizing power surges than reactance relay (b) Impedance relay less affected by arc resistance than mho relay (c) Impedance relay more affected by synchronizing power surges than reactance relay (d) Impedance relay used for protecting medium-length lines
**Ans: (c)** — impedance relay is LESS affected by power swings than reactance relay, so (c) is the wrong statement.
**Concept:** Power-swing susceptibility: reactance > impedance > mho; arc-resistance: mho most affected.
**Twist:** "Mho best for long lines (least swing effect)". "Reactance for short/earth faults".

**Q73 (TSSPDCL-15):** In overvoltage protection scheme:
(a) Ground wire is shielding; spark gaps & lightning arrestors are non-shielding (b) Ground wire non-shielding; spark gaps & LA shielding (c) Ground wire & spark gaps shielding; LA non-shielding (d) Ground wire & LA shielding; spark gaps non-shielding
**Ans: (a)** — shielding: ground wire, masts, grid; non-shielding: spark gaps, LA.
**Concept:** Shielding (intercept) vs non-shielding (discharge) methods.
**Twist:** "Shielding intercepts strokes". "Non-shielding uses insulation breakdown" (Prot Q25).

**Q74 (TSSPDCL-15):** IDMT relays are used to protect a transformer against:
(a) Internal short circuits (b) Open circuits (c) External short circuits (d) Oil leakage
**Ans: (c)** — IDMT OC acts as backup for external short-circuits (through faults).
**Concept:** Transformer backup: IDMT for external faults; differential/Buchholz for internal.
**Twist:** "Internal faults" → differential + Buchholz. "Backup protection" → IDMT.

**Q75 (TSSPDCL-15):** Resistance grounding is normally used for:
(a) High-voltage long overhead transmission lines (b) Low-voltage short overhead transmission lines (c) EHV long overhead lines (d) All the above
**Ans: (b)** — resistance grounding for LV short lines (limits fault current, reduces damage).
**Concept:** Grounding methods: solid (HV), resistance (LV), reactance/Peterson coil (cable/line charging).
**Twist:** "Solid grounding for HV" → low overvoltages, high fault current. "Peterson coil" → capacitive fault current compensation.

**Q76 (TSSPDCL-15):** Correct statements:
1. Reactance relays preferred for ground fault relaying
2. Impedance relays most suitable for long lines
3. Mho relays best suited for long lines
4. Reactance relays widely used for medium lines
(a) All (b) 1 and 3 (c) 2 and 4 (d) 1, 2 and 4
**Ans: (b)** — reactance for ground faults (1), mho for long lines (3); impedance is for medium, not long (2 false).
**Concept:** Relay choice: reactance (short/earth), impedance (medium), mho (long).
**Twist:** "Statement 4" → reactance NOT for medium (impedance is). "Statement 2" → impedance for medium not long.

**Q77 (TSSPDCL-15):** HRC fuses provide best protection against:
(a) Lightning (b) Short circuits (c) Overload (d) Over voltage
**Ans: (b)** — HRC fuse (fast, current-limiting) best for short circuits.
**Concept:** HRC fuse: high rupturing capacity, current limiting → SC protection.
**Twist:** "Overload" → thermal/MCB. "HRC + CB combination" → CB for overload (Prot Q52).

**Q78 (TSSPDCL-15/TSTransco-15):** The arc voltage in a CB is:
(a) In phase with the arc current (b) Lagging by 90° (c) Leading by 90° (d) Lagging by 45°
**Ans: (a)** — arc behaves like a pure resistance → arc voltage in phase with arc current.
**Concept:** Arc voltage ∝ (residual resistance) in phase with current.
**Twist:** "Arc current zero crossing" → arc extinguished. "Restriking" → voltage transient.

**Q79 (TSNPDCL-15):** A thyrite type lightning arrester:
(a) Blocks surge voltages (b) Absorbs surge voltage (c) Returns the surge to source (d) Offers low resistance path to surge currents
**Ans: (d)** — LA offers low resistance to surge (diverts to ground), high resistance at power frequency.
**Concept:** Thyrite/SiC arrester: nonlinear resistance → low at surge, high at power freq.
**Twist:** "ZnO arrester" → even sharper nonlinearity, no gap. "At power frequency" → high resistance → no follow current.

**Q80 (TSNPDCL-15):** When high RRRV is expected, CB with shunt resistance is used; to ensure exponential build-up to 50 Hz recovery without overshoot, R (L = line inductance, C = line-ground capacitance):
(a) √(L/C) (b) LC (c) 0.5√(L/C) (d) √(LC)
**Ans: (c)** — critical damping resistance R = 0.5√(L/C).
**Concept:** Critical damping R = ½√(L/C) → no overshoot (exponential recovery).
**Twist:** "Overshoot allowed" → smaller R. "R = ½√(L/C) = 11.18 kΩ" (Prot Q101).

**Q81 (HMWS-15):** Lightning may be regarded as:
(a) Transient, high current electric discharge (b) Transient, low current electric discharge (c) Transient, high current magnetic discharge (d) None
**Ans: (a)** — lightning = transient high-current electric discharge.
**Concept:** Lightning: kV-MV potentials, kA currents, μs duration.
**Twist:** "Surge impedance of lightning channel ~400 Ω". "Steep wavefront".

**Q82 (HMWS-15):** 33 kV/6.6 kV star-delta transformer; LV-side CT 400/5. Suitable HV-side CT ratio:
(a) 160:5√3 (b) 80:5√3 (c) 80:5/√3 (d) 80:5
**Ans: (c)** — HV line current = 400×6.6/33 = 80 A; HV CT delta-connected → secondary 5/√3; ratio 80 : 5/√3.
**Concept:** CT matching for star-delta transformer (compensate ratio & phase shift).
**Twist:** "LV CT star → secondary 5 A". "HV CT delta → 5/√3 A" (Prot Q95, Q106).

**Q83 (HMWS-15):** For complete protection of a 3-phase line:
(a) Two phase and one-earth fault relays (b) Three phase and two-earth fault relays (c) Two phase and two-earth fault relays (d) Three phase and three-earth fault relays
**Ans: (a)** — two phase + one earth fault relays give complete line protection.
**Concept:** Minimum relay set: 2 phase + 1 earth OC relays.
**Twist:** "Phase faults" → overcurrent on 2 phases covers all LL/LLG. "Earth faults" → 1 earth relay (residual).

**Q84 (HMWS-15):** Rate of rise of restriking voltage depends upon:
(a) The inductance and capacitance of the system (b) Inductance only (c) Capacitance only (d) Type of CB
**Ans: (a)** — RRRV depends on L and C (same as Prot Q58).
**Concept:** RRRV ∝ ω where ω=1/√(LC).
**Twist:** "Frequency of restriking = 1/(2π√LC)". "RRRV reduced by resistance switching".

**Q85 (HMWS-15):** For protection of parallel feeders fed from one end, relays required:
(a) Directional relays at both ends (b) Non-directional at both ends (c) Directional at source, non-directional at load end (d) Non-directional at source, directional at load end
**Ans: (d)** — source end: non-directional; load end: directional.
**Concept:** Parallel feeders (one-end fed): directional OC at load end, non-directional at source.
**Twist:** "Both-ends-fed (ring)" → directional at both ends. "Directional relays needed where fault current can reverse".

**Q86 (APTransco-17):** A reactance relay is:
(a) Voltage restrained directional relay (b) Directional restrained over-current relay (c) Voltage restrained over-current relay (d) Directional restrained over-voltage relay
**Ans: (b)** — reactance relay operates on current with directional restraint (over-current + directional).
**Concept:** Reactance relay: measures X; directional restrained OC type.
**Twist:** "Impedance relay" → voltage-restrained. "Mho" → voltage-restrained directional.

**Q87 (APTransco-17):** 132 kV system, C = 0.01 μF, L = 4 H; magnetizing current interrupted = 5 A (instantaneous). Voltage across CB pole:
(a) 132 kV (b) 10 kV (c) 220 kV (d) 100 kV
**Ans: (d)** — V = i√(L/C) = 5×√(4/0.01×10⁻⁶) = 5×2×10⁴ = 100 kV.
**Concept:** Restriking voltage = i√(L/C) (line).
**Twist:** "L=1H, i=10A" → 100 kV (Prot Q8). "L=5H" → 111.8 kV (before resistance).

**Q88 (APGenco-17):** In an induction-type directional overcurrent relay, the driving torque is due to interaction of magnetic fields derived from:
(a) Current in the potential coil (b) Both voltage and current in the relay windings (c) Directional element and non-directional element (d) Non-directional element and trip circuit
**Ans: (c)** — torque from directional (voltage-polarized) and non-directional (current) elements.
**Concept:** Directional OC relay: directional unit (polarizing) + non-directional (current) unit.
**Twist:** "Polarizing quantity = voltage". "Operating quantity = current". "Wrong polarization → wrong direction".

**Q89 (APGenco-17):** Operating characteristic of a reactance-type distance relay:
(a) A stepped waveform for increasing reactance (b) A straight line for constant reactance (c) A circle for constant reactance (d) A set of circles for variable reactance
**Ans: (b)** — reactance relay: horizontal straight line at constant X on R-X plane.
**Concept:** Reactance relay: X = const → horizontal line; immune to arc resistance.
**Twist:** "Impedance relay" → circle centered origin. "Mho" → circle through origin (Prot Q115).

**Q90 (APGenco-17):** Prospective voltage across CB contacts for series L and shunt C is:
(a) Directly proportional to (LC) (b) Inversely proportional to (LC) (c) Directly proportional to √(L/C) (d) Inversely proportional to √(L/C)
**Ans: (c)** — V = i√(L/C) ∝ √(L/C).
**Concept:** V = i·√(L/C).
**Twist:** "V ∝ √(L/C), not (LC)". "R to suppress = ½√(L/C)".

**Q91 (TSSPDCL-18):** Loss-of-excitation protection scheme for a large generating unit employs:
(a) Under frequency relays (b) Offset Mho relay (c) Reactance relay (d) Percentage differential relay
**Ans: (b)** — offset mho (loss-of-field) relay for generator excitation loss.
**Concept:** Loss of excitation → offset mho (impedance falls into circle).
**Twist:** "Steady-state stability limit" → generator PQ. "Reverse power" → prime-mover failure (Prot Q23).

**Q92 (TSTransco-18):** Arc resistance causes a distance relay to:
(a) Under-reach (b) Over-reach (c) Under or over-reach depending on line length (d) Reach unchanged
**Ans: (a)** — arc resistance increases impedance seen → under-reach.
**Concept:** Fault arc resistance → apparent impedance ↑ → relay under-reaches.
**Twist:** "Reactance relay immune to arc R". "Over-reach from decaying DC" → digital relays (Prot Q94).

**Q93 (TSTransco-18):** CB equivalent circuit: 10 mH, 400 pF (fig). Frequency of restriking voltage:
(a) 1000 kHz (b) 5000 kHz (c) 500×10³ rad/sec (d) 200×10³ rad/sec
**Ans: (c)** — ω = 1/√(LC) = 1/√(10×10⁻³ × 400×10⁻¹²) = 1/√(4×10⁻¹²) = 1/(2×10⁻⁶) = 500×10³ rad/s.
**Concept:** Restriking frequency ω = 1/√(LC).
**Twist:** "f in Hz" → ω/2π = 79.6 kHz. "L=10 mH, C=400 pF" → as given. "R for damping = ½√(L/C)".

**Q94 (TSTransco-18):** Overreaching of a distance relay due to decaying DC component is avoided by:
(a) Electromechanical relay (b) Solid state relay (c) Digital relay (d) Impedance relay
**Ans: (c)** — digital relays filter DC offset / use algorithms to avoid overreach.
**Concept:** Digital relays: DFT/filtering removes decaying DC offset.
**Twist:** "DC offset creates asymmetrical fault current". "Memory polarization" → other mitigation.

**Q95 (TSTransco-18):** 10 MVA, 132/66 kV (star-delta) transformer, circulating-current protection, pilot current 5 A. CT ratios both sides:
(a) 43.71/5, 87.4/5 (b) 43.71/(5/1.732), 87.4/5 (c) 87.4/5, 43.71/(5/1.732) (d) 43.71/5, 87.4(5/1.732)
**Ans: (b)** — HV line I = 43.74 A with delta CT → 43.71 : (5/√3); LV line I = 87.48 A with star CT → 87.4 : 5.
**Concept:** Circulating-current (Merz-Price) on transformer: CT ratio/connection match.
**Twist:** "HV delta CT → secondary 5/√3". "LV star CT → secondary 5 A" (Prot Q82, Q106).

**Q96 (APSPDCL-19):** Capacitor switching is easily done with:
(a) Oil CB (b) Air blast CB (c) Vacuum CB (d) Both (a) and (b)
**Ans: (c)** — vacuum CB (no restrike) for capacitor switching.
**Concept:** VCB → capacitor/line-charging current without restrike.
**Twist:** "Restrike → overvoltage on capacitor". "Frequent switching" → vacuum (Prot Q18/Q29).

**Q97 (APEPDCL-19):** Operating time of an instantaneous relay is of the order of:
(a) Few micro seconds (b) Few nano seconds (c) Few milliseconds (d) Few minutes
**Ans: (c)** — instantaneous relay operates in a few ms.
**Concept:** Instantaneous relay: few ms (vs ~0.1 s in Prot Q9 — OHM varies by exam).
**Twist:** "IDMT relay" → 0.1–s order. "Digital relay" → sub-cycle ms.

**Q98 (APEPDCL-19):** Which CB does NOT use a pneumatic operating mechanism?
(a) Bulk-oil CB (b) Air blast CB (c) SF6 blast CB (d) Air break CB
**Ans: (a)** — bulk-oil CB uses spring/hydraulic/electromagnetic, not pneumatic.
**Concept:** Pneumatic mechanism: air-blast/SF6; oil CB → spring/hydraulic.
**Twist:** "Air-blast uses compressed air" (both extinction + mechanism). "SF6 blast" → pneumatic too.

**Q99 (APEPDCL-19):** Most fuses operate due to the:
(a) Cooling effect of current (b) Heating effect of current (c) Magnetic effect of current (d) Electrostatic effect of current
**Ans: (b)** — fuse melts by I²R heating.
**Concept:** Fuse = thermal (heating) element.
**Twist:** "I²t characteristic". "Time-current inverse" → thermal.

**Q100 (APEPDCL-19):** Match the symbols (a, b, c, d) with equipment (i) CT, (ii) Lightning arrester, (iii) Earthing switch, (iv) Isolator:
(a) a-iv, b-iii, c-ii, d-i (b) a-i, b-ii, c-iii, d-iv (c) a-ii, b-iii, c-i, d-iv (d) a-iii, b-i, c-iv, d-ii
**Ans: (a)** — per key: symbol (a)=isolator(iv), (b)=earthing switch(iii), (c)=lightning arrester(ii), (d)=CT(i).
**Concept:** Substation one-line symbols.
**Twist:** "Earthing switch symbol resembles ground + switch". "Isolator symbol = knife switch".

**Q101 (APEPDCL-19):** 132 kV, C = 0.01 μF, L = 5 H, magnetizing current interrupted 5 A. Resistance across contacts to eliminate restriking:
(a) 111.8 Ω (b) 11.18 kΩ (c) 111.8 kΩ (d) 11.18 Ω
**Ans: (b)** — R = ½√(L/C) = ½√(5/0.01×10⁻⁶) = ½√(5×10⁸) = ½×22361 = 11.18 kΩ.
**Concept:** Critical resistance = ½√(L/C) (Prot Q80).
**Twist:** "L=1H" → R = ½√(1e8) = 5 kΩ. "No resistance switching" → restrike → 111.8 kV.

**Q102 (APEPDCL-19):** Which CB has high reliability and minimum maintenance?
(a) SF6 gas CB (b) Oil CB (c) Air blast CB (d) Vacuum CB
**Ans: (d)** — vacuum CB: sealed, minimum maintenance, high reliability.
**Concept:** VCB: sealed contacts, no arc products → min maintenance.
**Twist:** "SF6" → also low maintenance (Prot Q38). "Minimum time installation" → SF6.

**Q103 (APEPDCL-19):** In distance protection, the relay measures _____ of the line from relay to fault point:
(a) Zero sequence impedance (b) Negative sequence impedance (c) Positive sequence impedance (d) Self-impedance
**Ans: (c)** — distance relay measures positive-sequence impedance.
**Concept:** Distance relays use Z1 to compute reach.
**Twist:** "Ground faults use residual compensation (K0)". "3-φ → Z1 only".

**Q104 (APEPDCL-19):** 3-phase 66 kV oil CB rated 1200 A, 800 MVA, 3 s. Symmetrical breaking current:
(a) 70 kA (b) 35 kA (c) 3.8 kA (d) 1.2 kA
**Ans: (a)** — per OHM solution using S = √3·V·I → I = 70 kA (document's computation uses 8000 MVA internally).
**Concept:** Symmetrical breaking current = S/(√3·V); note: with rated 800 MVA the arithmetic gives ≈7 kA, but OHM keys 70 kA.
**Twist:** "66 kV, 800 MVA" → check MVA base. "33 kV, 2000 MVA → 35 kA" (Prot Q110).

**Q105 (APTransco-19):** Match relay with application:
1. Buchholz 2. Translay 3. Carrier phase-comparison 4. Directional overcurrent 5. Negative-sequence → P. Feeder, Q. Transformer, R. Radial distribution, S. Generator, T. Ring main distributor, U. Long overhead line:
(a) 1-P, 2-Q, 3-T, 4-R, 5-S (b) 1-Q, 2-R, 3-T, 4-U, 5-P (c) 1-S, 2-Q, 3-S, 4-T, 5-U (d) 1-Q, 2-P, 3-U, 4-T, 5-S
**Ans: (d)** — Buchholz→Transformer, Translay→Feeder, Carrier phase-comparison→Long overhead line, Directional OC→Ring main distributor, Negative-seq→Generator.
**Concept:** Relay-to-zone mapping (carrier for long EHV lines; directional for ring mains).
**Twist:** "Translay for parallel feeders". "Negative sequence for unbalance in machines".

**Q106 (APTransco-19):** 400/33000 V transformer star-delta; CTs on 400 V side 1000/5. Required CT ratio on 33 000 V side:
(a) 7/5 (b) 5/7 (c) 3/5 (d) 5/2
**Ans: (a)** — IL2 = 400×1000/33000 = 400/33 A; with star-CT 5√3 A pilot → ratio = (400/33)/(5√3) ≈ 7/5.
**Concept:** CT ratio matching for star-delta transformer (Prot Q82/Q95).
**Twist:** "HV side delta CT → pilot 5√3 A". "Wrong connection" → unbalanced operation.

**Q107 (APTransco-19):** L = 1 H, C = 0.01 μF, instantaneous interrupted current 10 A. Voltage across breaker contacts:
(a) 50 kV (b) 57 kV (c) 60 kV (d) 100 kV
**Ans: (d)** — V = i√(L/C) = 100 kV (same as Prot Q8).
**Concept:** V = i√(L/C).
**Twist:** "i=5A" → 50 kV (trap a). "L=4H" → 100 kV (Prot Q87).

**Q108 (TSSPDCL-2022):** Fault current 2100 A, relay setting 70%, CT 300:5. PSM:
(a) 10 (b) 15 (c) 12 (d) 20
**Ans: (a)** — PSM = 2100/((300/5)×(0.7×5)) = 2100/(60×3.5) = 10.
**Concept:** PSM = If/(CT ratio × pickup).
**Twist:** "Setting 50%, CT 400:5, fault 2000 A" → PSM = 10 (Prot Q26). "PSM >20" → instantaneous.

**Q109 (TSNPDCL-2022):** CB "interrupting time" is the period between:
(a) Energizing of tripping coil and extinguishing of arc (b) Energizing of tripping coil and opening of CB (c) Fault occurrence and extinguishing of arc (d) Fault occurrence and opening of CB
**Ans: (a)** — interrupting (breaking) time = tripping-coil energization to arc extinction.
**Concept:** Interrupting time = trip-coil energize → arc extinction.
**Twist:** "Total clearing time" = relay time + interrupting time. "Opening time" = coil to contact separation.

**Q110 (TSPSC-AEE-23):** 3-phase 33 kV oil CB rated 1500 A, 2000 MVA, 2 s. Symmetrical breaking current:
(a) 40 kA (b) 25 kA (c) 35 kA (d) 50 kA
**Ans: (c)** — I = 2000×10⁶/(√3×33×10³) = 35 kA.
**Concept:** SBC = √3·V_L·I.
**Twist:** "66 kV, 800 MVA → 7 kA (or per OHM 70)". "Making current = 2.55×35 = 89 kA".

**Q111 (TSPSC-AEE-23):** Buchholz relay is commonly used for protection of:
(a) Generators (b) Transformers (c) Transmission lines (d) Busbars
**Ans: (b)** — transformers (internal/incipient faults).
**Concept:** Buchholz = transformer gas/surge relay.
**Twist:** "Not on air-cooled". "Located in tank-conservator pipe" (Prot Q66).

**Q112 (TSPSC-AEE-23):** Relay used for transmission line distance protection, inherently directional:
(a) Reactance relay (b) MHO relay (c) OHM relay (d) Impedance relay
**Ans: (b)** — Mho (circle through origin) is inherently directional.
**Concept:** Mho: passes through origin → only forward faults (Prot Q19).
**Twist:** "Impedance relay" → non-directional circle. "Reactance" → horizontal line, needs directional unit.

**Q113 (TSPSC-AEE-23):** The value of current or voltage below which a relay opens its contacts and returns to original position:
(a) Reset level (b) Pick up level (c) Reach (d) Pick down level
**Ans: (a)** — reset level = value below which relay resets.
**Concept:** Pickup level (operate) vs reset level (drop-out); reset ratio.
**Twist:** "Operating level = pickup". "Reset ratio = reset/pickup (<1 for OC)".

**Q114 (TSPSC-AEE-23):** On a radial system, relay farthest from source set minimum, increasing towards source. Per Indian standards, operating value should exceed:
(a) 0.1 times of setting (b) 1.3 times of setting (c) 0.8 times of setting (d) 0.5 times of setting
**Ans: (b)** — operating current ≥ 1.3 × setting (grading margin) per IS.
**Concept:** OC relay grading: pickup ≈1.3× load; time grading margin.
**Twist:** "Discrimination margin ~0.4-0.5 s". "Current grading near source higher".

**Q115 (TSPSC-AEE-23):** Match distance-relay characteristics (I Directional, II Impedance, III Angle-impedance, IV Mho) with R-X curves (1-4):
(a) I-1, II-2, III-3, IV-4 (b) I-3, II-4, III-1, IV-2 (c) I-2, II-4, III-3, IV-1 (d) I-2, II-1, III-3, IV-4
**Ans: (d)** — per OHM key: Directional→2, Impedance→1, Angle-impedance→3, Mho→4.
**Concept:** R-X characteristics: directional straight line; impedance circle (center origin); angle-impedance offset circle; mho circle through origin.
**Twist:** "Angle-impedance = offset impedance". "Mho circle through origin → inherent directionality".

**Q116 (TSPSC-AEE-23):** Fusing factor is the ratio of:
(a) Maximum fusing current / Fuse rating (b) Minimum fusing current / Fuse rating (c) Minimum fusing current / Maximum fuse rating (d) Fuse rating / Minimum prospective current
**Ans: (b)** — fusing factor = minimum fusing current / fuse (current) rating.
**Concept:** Fusing factor >1 (typically 1.25-1.45).
**Twist:** "Fusing current ∝ d^3/2" (Prot Q10). "Lower fusing factor" → more sensitive.

**Q117 (TSPSC-AEE-23):** Tendency of a relay to operate at impedances larger than its setting is known as:
(a) Reset time (b) Overreach (c) Operating time (d) Auxiliary relays
**Ans: (b)** — overreach = operation beyond set reach.
**Concept:** Overreach (DC offset/transients) vs underreach (arc resistance).
**Twist:** "Arc resistance → under-reach" (Prot Q92). "DC offset → overreach avoided by digital relays" (Prot Q94).

**Q118 (TSPSC-AEE-23):** The expression for a biased differential relay is:
(a) nr/no = (i1−i2)/(i1+i2) (b) nr/no · (i1−i2)/(i1+i2) (c) nr/no = (i1+i2)/(i1−i2) (d) nr/no = (i1+i2)/(i1−i2)²
**Ans: (a)** — at verge: n0(i1−i2) = (nr/2)(i1+i2) → nr/no = (i1−i2)/((i1+i2)/2) = 2(i1−i2)/(i1+i2); OHM keys (a).
**Concept:** Biased/percentage differential: slope = nr/no; restrains on external through-faults.
**Twist:** "Bias definition nr/no" (Prot Q27). "Slope 10-40%". "Inrush restraint by 2nd harmonic".

**Q119 (TSPSC-AEE-23):** SF6 breaker statements:
I. Current chopping minimized by SF6 at low pressure & low velocity.
II. CB performance not affected by atmospheric conditions.
III. Electrical clearances drastically reduced due to low dielectric strength of SF6.
(a) I, II and III (b) II and III only (c) I and III only (d) I and II only
**Ans: (d)** — I & II correct; III wrong (SF6 has HIGH dielectric strength → clearances can be reduced).
**Concept:** SF6: high dielectric strength (3× air), sealed, no atmospheric effect, low chopping at low pressure.
**Twist:** "SF6 density/arc time constant". "SF6 toxicity of arced byproducts".

**Q120 (TSPSC-AEE-23):** Insulating fluids commonly used for CBs:
I. Air at atmospheric pressure, II. Compressed air, III. Ultra-high vacuum, IV. Oil producing hydrogen for arc extinction:
(a) I, III, IV (b) II, III, IV (c) I, II, III, IV (d) I, II, III
**Ans: (c)** — all four are used as interrupting/insulating media.
**Concept:** CB media: air, compressed air, vacuum, oil (hydrogen), SF6.
**Twist:** "Which NOT used" → none of the four. "Hydrogen produced by oil arc decomposition".

**Q121 (TSPSC-AEE-23):** Statements on protection relay:
I. Fuse protects equipment against overloads and/or short circuits.
II. Fuse element melts on excessive current, isolating the faulty device.
(a) Only II (b) Neither I nor II (c) Only I (d) Both I and II
**Ans: (d)** — both statements correct.
**Concept:** Fuse = sacrificial protective device (I²t melting).
**Twist:** "Fuse vs MCB" → MCB reusable. "Discrimination with fuse".

**Q122 (TSGenco-24):** To maximize driving torque in an induction-type instrument, flux of shunt coil and series coil should be:
(a) In phase with each other (b) Displaced by 45° (c) In quadrature with each other (d) Displaced by 60°
**Ans: (c)** — T ∝ φsh·φse·sinθ; max at θ = 90° (quadrature).
**Concept:** Induction torque ∝ φ1φ2 sinθ → max at 90° phase shift.
**Twist:** "Power factor meter" → uses phase shift. "Shaded pole" → 90° split.

**Q123 (TSGenco-24):** Reverse power protection is applied for:
(a) Over speed (b) Excitation failure (c) Turbine failure (d) Stator earth fault
**Ans: (c)** — reverse power trips generator when prime mover (turbine) fails.
**Concept:** Reverse-power (wattmetric) relay → prime-mover/turbine failure (Prot Q23).
**Twist:** "Loss of excitation" → offset mho (Prot Q91). "Over speed" → mechanical governor/overspeed trip.

---

*End of Unit 3 analysis — 197 questions (74 ELD/EPG/LFC + 123 PROTECTION).*

> Total: 549 questions annotated.

---

# 📋 FORMULA SUMMARY — Exam-Day Sheet (Power Systems)

## 1. Transmission & Distribution
- ABCD: short [1 Z; 0 1] · medium π: A=D=1+YZ/2, B=Z, C=Y(1+YZ/4) · long: A=coshγl, B=Zc·sinhγl
- **Sag S = wL²/(8T)** · string eff: η = V_str/(n·V_lowest)
- **L = 0.2 ln(GMD/GMR) mH/km** · C = 2πε0/ln(GMD/GMR) · corona ∝ (V−Vd)² ∝ (f+25)
- **Ferranti: Vr > Vs (no-load) → shunt reactor** · **Zc = √(L/C), SIL = V²/Zc** (overhead ≈400Ω, cable ≈50Ω)
- Insulation: A=105 · E=120 · B=130 · F=155 · H=180°C

## 2. Per-unit, Faults, Stability, Load Flow
- Z_pu(new) = Z_pu(old)(V_old/V_new)²(MVA_new/MVA_old)
- Symm comp: I0=(Ia+Ib+Ic)/3 · I1=(Ia+aIb+a²Ic)/3 · I2=(Ia+a²Ib+aIc)/3
- Faults: **LG 3E/(Z1+Z2+Z0)** · **LL √3E/(Z1+Z2)** · **3-Φ E/Z1** · SC MVA = baseMVA/Z_pu
- **LG most common (~70–80%)** · swing: M(d²δ/dt²)=Pa, M=GH/180f · NR Jacobian (2N−Npv−2)

## 3. Protection
- **PSM = If/(CT ratio × PS)** · **IDMT t = 0.14·TMS/(PSM^0.02 − 1)**
- Breaking MVA = √3·VL·Ibr · **Making = 2.55 × breaking**
- Buchholz=transformer · differential=transformer/bus · Mho distance=long EHV · OC=radial · **CT secondary never open**
