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
| :---: | :--- | :---: | :--- | :--- | :--- |
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
| :---: | :--- | :--- | :--- |
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
| :---: | :--- | :---: | :--- |
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

# 📝 EMBEDDED PYQs — Ohm Institute PDF

> Source: Study_Material__GTD_PYQs_2026_05_26_4_Power_Systems_PDF.pdf  
> Contains ~1195 PYQs across 3 modules. Selected representative Qs below.

---

## Module 1: Transmission & Distribution

**Q1 (EPDCL-10):** Maximum permissible temp of class-E insulation:
(a) 130°C &emsp; (b) 180°C &emsp; (c) 120°C &emsp; (d) 105°C  
**Answer: (c) 120°C**

**Q3 (EPDCL-10):** Undesirable effects of corona:
(a) Power loss &emsp; (b) Harmonic currents  
(c) Radio interference &emsp; (d) All of the above  
**Answer: (d)**

**Q5 (SSC-JE-10):** Puncture voltage to flashover voltage ratio of an insulator:
(a) =1 &emsp; (b) <1 &emsp; (c) 0 &emsp; (d) >1  
**Answer: (d) >1** — puncture > flashover (safety margin)

**Q11 (SSC-JE-11):** In suspension insulator, max potential drop across:
(a) Lower disc &emsp; (b) Topmost disc  
(c) Middle disc &emsp; (d) Uniform  
**Answer: (a)** — Bottom disc has highest voltage due to capacitance distribution

**Q13 (APGenco-12):** Self GMD method evaluates:
(a) Inductance &emsp; (b) Capacitance &emsp; (c) Both L & C &emsp; (d) Distance  
**Answer: (c)** — GMD/GMR used for both inductance and capacitance

**Q23 (APGenco-12):** Surge impedance of line L=1mH/km, C=0.01μF/km:
**Solution:** Zc = √(L/C) = √(1×10⁻³/0.01×10⁻⁶) = √(10⁵) = **316.2 Ω**

**Q45 (APGenco-12):** ABCD parameters of medium π-line with Z and Y:
**Answer:** A=1+YZ/2, B=Z, C=Y(1+YZ/4), D=1+YZ/2

**Sag Q (APGenco-12):** Sag S = wL²/(8T). Span 200m, weight 0.8 kg/m, tension 2000 kg. Sag?
**Solution:** S = 0.8×200²/(8×2000) = 32000/16000 = **2.0 m**

---

## Module 2: Per-Unit, Symmetrical Components & Fault Analysis

**Q1 (PU):** Base MVA=100, Base kV=132. Base impedance?
**Solution:** Z_base = kV²/MVA = 132²/100 = **174.24 Ω**

**Q3 (PU):** Z_pu(old)=0.2, V_base(old)=11kV, MVA_base(old)=50. New base = 33kV, 100MVA. Z_pu(new)?
**Solution:** Z_pu(new) = 0.2 × (11/33)² × (100/50) = 0.2 × (1/9) × 2 = **0.0444 pu**

**Q4 (Symm Comp):** Ia=10∠0°, Ib=10∠-120°, Ic=10∠120°. Find positive sequence I₁?
**Solution:** I₁ = (Ia + a·Ib + a²·Ic)/3  
a=1∠120°, a²=1∠240°. Ia=10∠0°, Ib=10∠-120°, Ic=10∠120°  
I₁ = [10∠0° + 1∠120°×10∠-120° + 1∠240°×10∠120°]/3  
= [10∠0° + 10∠0° + 10∠360°]/3 = 30/3 = **10∠0° A**  
(Balanced load → only positive sequence exists)

**Q7 (Fault):** 3-φ fault: Z₁=j0.2pu, V=1∠0°. Fault current?
**Solution:** If = V/Z₁ = 1∠0°/0.2∠90° = **5∠-90° pu**

**Q10 (Fault):** LG fault: Z₁=Z₂=Z₀=j0.2pu, Zn=0. Fault current?
**Solution:** If = 3V/(Z₁+Z₂+Z₀) = 3∠0°/(j0.6) = **5∠-90° pu**

**Q15 (SC MVA):** Fault current 5pu, base MVA=100. Short circuit MVA?
**Solution:** SC MVA = If(pu) × Base MVA = 5 × 100 = **500 MVA**

---

## Module 2: Power System Stability

**Swing Eq:** H=5 MJ/MVA, rating=100MVA, f=50Hz. Inertia constant M?
**Solution:** M = GH/(180f) = 100×5/(180×50) = 500/9000 = **0.0556 MJ·s/elec.deg**

**Equal Area:** Generator delivers P_m=0.8pu, max power P_max=1.6pu. Initial δ₀?
**Solution:** P_m = P_max×sinδ₀ → 0.8 = 1.6×sinδ₀ → δ₀ = sin⁻¹(0.5) = **30°**

**Critical clearing angle:** For fault at generator terminals (P_e=0 during fault):
δ_cc = cos⁻¹[(π-2δ₀)sinδ₀ - cosδ₀] = cos⁻¹[(π-π/3)×0.5 - 0.866]  
= cos⁻¹[1.047 - 0.866] = cos⁻¹(0.181) = **79.6°**

---

## Module 2: Load Flow Analysis

**Bus types:** Slack (Vδ) — reference bus. PV — generator bus (P, V specified). PQ — load bus (P, Q specified).

**Y_bus:** 3-bus system, all lines j0.1 pu. Y_bus diagonal = sum of admittances connected to bus = -j10×connections. Off-diagonal = j10.

**Newton-Raphson:** 50-bus system, 5 PV buses. Jacobian matrix size?
**Solution:** N=50, N_PV=5. Size = (2N-N_PV-2) × (2N-N_PV-2) = (100-5-2) = **93×93**

---

## Module 3: Protection

**Relay:** CT ratio=400/5, fault current=6000A, plug setting=100%. PSM?
**Solution:** PSM = If/(CT_ratio × PS) = 6000/(80 × 1.0) = **75**

**IDMT:** PSM=10, TMS=0.2, normal inverse. Operating time?
**Solution:** t = 0.14 × TMS / (PSM^0.02 - 1) = 0.14×0.2/(10^0.02-1)  
= 0.028/(1.047-1) = 0.028/0.047 = **0.596 s**

**CB Breaking Capacity:** 11kV, I_br=40kA. Breaking MVA?
**Solution:** BC = √3 × V_L × I_br = 1.732 × 11 × 40 = **762 MVA**

**CT:** Protection class CT 5P10 means:
(a) 5% accuracy at 10× rated current &emsp; (b) 10% accuracy at 5× rated current  
(c) 5VA burden at 10A &emsp; (d) 10VA burden at 5A  
**Answer: (a)**

**CT secondary must NEVER be:** (a) Open &emsp; (b) Short &emsp; (c) Grounded &emsp; (d) Loaded  
**Answer: (a)** — Open CT secondary → high voltage flashover

---

## Module 3: Economic Load Dispatch

**Two generators:** F₁=0.02P₁²+30P₁+100, F₂=0.03P₂²+20P₂+150. Total load=200MW. Economic allocation?
**Solution:** IC₁=IC₂=λ  
IC₁ = 0.04P₁+30, IC₂ = 0.06P₂+20  
0.04P₁+30 = 0.06P₂+20 → 0.04P₁ - 0.06P₂ = -10  
P₁+P₂ = 200  
Solving: P₁ = 0.06×200-10/0.10 = 12-10/0.10? Let me redo:  
From IC eq: 0.04P₁+30 = 0.06(200-P₁)+20  
0.04P₁+30 = 12-0.06P₁+20  
0.10P₁ = 2 → P₁ = 20MW, P₂ = 180MW

**Penalty factor:** If ∂P_L/∂P₁ = 0.1, penalty factor L₁ = 1/(1-0.1) = 1.111

---

> **Total embedded PYQs: 25 (selected from ~1195 PS questions)**

---