# Electrical Machines: Complete Exam Preparation Guide

**Source:** Study Material - GTD PYQs 2026 (Transformers, DC Machines, Induction Motors, Synchronous Machines)  
**Total Questions Analyzed:** 400+ (Pages 1-142)

---

## 📚 Table of Contents

1. [Formula/Concept vs. Question Count Analysis](#-formulaconcept-vs-question-count-analysis)
2. [The 5-Question Decision Flowchart](#-the-5-question-decision-flowchart)
3. [How to Identify the Machine Type from the Question](#-how-to-identify-the-machine-type-from-the-question)
4. [Quick Decision Matrix for Excitation Type (DC Machines)](#-quick-decision-matrix-for-excitation-type-dc-machines)
5. [The Ultimate "What Happens When..." Cheat-Sheet](#-the-ultimate-what-happens-when-cheat-sheet)
6. [Key Relationships to Memorize](#-key-relationships-to-memorize)
7. [Top 20 Concepts to Score >90%](#-top-20-concepts-to-score-90)
8. [Quick Reference Card (Exam Day)](#-quick-reference-card-exam-day)
9. [Step-by-Step Problem Solving Approach](#-step-by-step-problem-solving-approach)

---

## 📊 Formula/Concept vs. Question Count Analysis

**Sorted by Number of Questions (Descending Order)**

| S.No | Formula / Concept | No. of Qs | What They GIVE in the Question | What They ASK in the Question | Mapped Question Numbers | Example Question (PDF Reference) |
| :---: | :--- | :---: | :--- | :--- | :--- | :--- |
| **1** | **EMF Equation & Magnetic Circuit** <br> E = 4.44 f N Φ <br> E = (P Φ N Z) / (60 A) | **~45** | Voltage, Frequency, Turns, Flux density, Core area, Speed, Number of Poles, Conductors (Z), Winding type (Lap/Wave). | Calculated the **missing parameter** (e.g., Find Area, Turns, Speed, Flux, or Generated EMF). | **TF:** Q16, Q17, Q18, Q20, Q22, Q154 <br> **DC:** Q3, Q30, Q35, Q38, Q47, Q93, Q117, Q121, Q132, Q145, Q149 <br> **SM:** Q9, Q40, Q41, Q121, Q126 | **Q3 (DC):** "4 pole, 1200rpm, 1520 conductors, flux 0.01Wb. Find EMF?" <br> **Q20 (TF):** "1000 turns, 222V, 0.1 Wb/m². Find Area?" |
| **2** | **Transformer Voltage Regulation** <br> VR = R_pu cosφ ± X_pu sinφ <br> VR = (E - V) / V × 100 | **~32** | %R (or R_pu), %X (or X_pu), Load Power Factor (Lag/Lead), Short circuit test voltage/current, No-load & Full-load voltages. | **Percentage voltage regulation** at a specific load (or find condition for zero/max regulation). | **TF:** Q56, Q74, Q75, Q76, Q77, Q78, Q79, Q80, Q81, Q82, Q130, Q147, Q153 <br> **SM:** Q72, Q83, Q88, Q144 | **Q74 (TF):** "R=0.2pu, X=0.6pu. VR at 0.8pf lag?" <br> **Q78 (TF):** "1% R, 4% X. VR at 0.8 lag and 0.8 lead?" |
| **3** | **Efficiency & Losses (Transformer/DC)** <br> η = Output / Input <br> P_cu ∝ I² <br> Max Efficiency: P_i = P_cu | **~30** | kVA rating, Iron loss (Pi), Full-load copper loss (Pcu), Load fraction (x), Output power, Input power, Power factor. | **Efficiency** at full/half load, **Copper loss** at a fraction of load, **Load fraction** for maximum efficiency. | **TF:** Q39, Q40, Q45, Q60, Q61, Q62, Q63, Q64, Q65, Q66, Q67, Q68, Q69, Q70, Q71, Q72, Q73, Q121, Q139, Q140, Q149 <br> **DC:** Q14, Q19, Q36, Q89, Q111, Q138, Q172 <br> **IM:** Q5, Q6, Q7, Q8, Q9 | **Q63 (TF):** "40kVA, Pi=400W, Pcu=800W. Fraction of rated load at max efficiency?" <br> **Q39 (TF):** "Full load Cu loss=1600W. Cu loss at half-load?" |
| **4** | **Induction Motor Torque & Slip** <br> s = (N_s - N_r) / N_s <br> T ∝ (s E₂² R₂) / (R₂² + (sX₂)²) <br> T ∝ V² | **~28** | Supply Frequency, Number of Poles, Rotor Speed, Rotor resistance (R2), Standstill reactance (X2), Supply Voltage. | **Slip** at various conditions, **Torque** (Starting, Max, Full-load), Ratio of torques, or **Speed** of motor. | **Basics/Slip:** Q1-Q17 <br> **Torque Eqs:** Q1-Q15 <br> **Characteristics:** Q1-Q11 | **Q11 (IM):** "400V, 4-pole, 1440rpm. Find slip?" <br> **Q3 (IM - Torque):** "Supply voltage reduced by 10%. Max torque decrease by?" |
| **5** | **DC Motor Speed & Back EMF** <br> E_b = V_t - I_a R_a <br> N ∝ E_b / φ | **~25** | Terminal Voltage (Vt), Armature Current (Ia), Armature Resistance (Ra), Field Current (If), Speed (N). | **Back EMF (Eb)** , **Speed** after adding resistance/ changing flux, or **Armature current** under new conditions. | **DC:** Q5, Q10, Q23, Q41, Q69, Q73, Q79, Q86, Q103, Q109, Q115, Q118, Q122, Q126, Q129, Q148, Q150, Q157, Q158, Q161, Q164, Q167, Q173 | **Q73 (DC):** "150V motor, Ra=0.4Ω, Eb=142V. Find Ia?" <br> **Q122 (DC):** "200V, 1000rpm, Ia=17.5A, Ra=0.4Ω. Find external resistance to reduce speed to 600rpm?" |
| **6** | **Auto-Transformer Rating** <br> VA_AT = (1 / (1-K)) × VA_2W <br> K = V_LV / V_HV | **~22** | Rating of the original two-winding transformer (kVA), Primary and Secondary voltages of the auto-transformer. | **kVA rating** of the auto-transformer, **Power transferred conductively/inductively**, or **Currents** in different windings. | **TF:** Q99, Q102, Q105, Q106, Q107, Q108, Q109, Q110, Q111, Q122, Q129, Q131, Q141, Q155 | **Q106 (TF):** "100V/10V, 50VA to 100V/110V AT. Find rating?" <br> **Q102 (TF):** "N1=210, N2=140, Iin=60A. Find output and common winding currents?" |
| **7** | **Parallel Operation of Transformers & Alternators** <br> S_A / S_B = Z_B / Z_A <br> Load Sharing ∝ Rating | **~18** | kVA ratings of two machines, % impedance, Speed regulation (droop) of alternators, Total load to be shared. | **Load shared** by each machine, **System frequency** after loading, or **Conditions** required for parallel operation. | **TF:** Q112, Q113, Q114, Q115, Q116, Q135, Q143 <br> **SM:** Q39, Q45, Q109, Q117, Q129 | **Q39 (SM):** "40MVA & 60MVA, 5% reg, total load 80MW. Find load sharing?" <br> **Q117 (SM):** "200MW & 400MW, 4% & 5% droop, load 600MW. Find system frequency?" |
| **8** | **Transformer Connections (3-Phase)** <br> V_L = V_Ph (Δ) <br> V_L = √3 × V_Ph (Y) <br> Open Delta Capacity = 57.7% of Δ-Δ | **~15** | Primary line voltage & current, Turns ratio per phase, Connection type (Y-Δ, Δ-Y, Δ-Δ, V-V/Open Delta). | **Secondary line voltage/current** , **Capacity** of an open delta (V-V) bank, or **Phase difference** between primary and secondary. | **TF:** Q86, Q88, Q89, Q90, Q91, Q92, Q93, Q94, Q95, Q96, Q97, Q123, Q133, Q138, Q156 | **Q133 (TF):** "600 & 150 turns, supply 1.5kV. Find secondary voltage for (a) delta-star (b) star-delta?" <br> **Q95 (TF):** "In Δ-Δ, one phase burns. What % of rated output?" |
| **9** | **Synchronous Motor/Alternator (Phasor & Power)** <br> P = (E_f × V_t) / X_s × sinδ <br> I_a = (V_t - E_f) / (jX_s) | **~14** | Synchronous Reactance (Xs), Terminal Voltage (Vt), Excitation EMF (Ef), Load Angle (δ), Armature Current (Ia). | **Maximum power output** , **Armature current** , **Power factor** (leading/lagging), or identifying the **mode of operation** (motor/generator). | **SM:** Q13, Q19, Q22, Q59, Q110, Q121, Q125, Q127, Q134, Q137, Q139, Q142, Q143, Q150 | **Q142 (SM):** "Xs=0.4pu, Ef=1.2pu, δ=30°. Find power output/phase?" <br> **Q19 (SM):** "Xs=1pu, V=1pu, Ef=1.5pu, current=0+j0.5. Find mode of operation?" |
| **10** | **Starting Methods of Induction Motors** <br> T_st ∝ V² <br> I_st ∝ V <br> Star-Delta: T_st(Y) / T_st(DOL) = 1/3 | **~13** | Direct-on-line (DOL) starting current/torque, % tapping of auto-transformer, or connection type (Star/Delta). | **Reduced starting current or torque** when using a starter, or the ratio of starting to full-load torque. | **IM - Starting:** Q1, Q2, Q3, Q4, Q5, Q6, Q7, Q8, Q9, Q10, Q11, Q12, Q13, Q14, Q15 | **Q6 (IM - Start):** "DOL torque 320Nm. Auto-transformer 50% tapping. Find starting torque?" <br> **Q8 (IM - Start):** "Delta, DOL starting current=30A. Star-Delta starter starting current?" |
| **11** | **Testing of Transformers (OC & SC)** <br> P_i = V_1 × I_0 × cosφ_0 <br> P_cu = I_sc² × R_eq | **~12** | Open circuit (OC) test data (V, I, W), Short circuit (SC) test data (V, I, W). | **Core/Iron loss** , **Copper loss** , **No-load power factor** , or to find **Equivalent circuit parameters**. | **TF:** Q31, Q48, Q49, Q50, Q52, Q53, Q54, Q55, Q57, Q58 <br> **IM - Testing:** Q4, Q5 | **Q31 (TF):** "No-load: 0.6A, 64W, 200V. Find iron loss component of current?" <br> **Q56 (TF):** "SC test: 15V, 10A, 80W. Find % regulation at UPF?" |
| **12** | **Single-Phase Induction Motor Theory** <br> s_f = s (Forward) <br> s_b = 2 - s (Backward) <br> T ∝ I_1 × I_2 × sinθ | **~10** | Motor speed (Nr), Synchronous speed (Ns), or type of motor (Capacitor start, Shaded pole, etc.). | **Rotor EMF frequency** for forward/backward fields, **Starting torque** relation, or **Identification** of motor type for an application. | **IM - 1Ph:** Q6, Q10, Q16, Q27, Q32, Q34, Q35, Q40 | **Q10 (IM - 1Ph):** "4-pole, 50Hz, running at 1300rpm. Find forward and backward rotor frequencies?" <br> **Q34 (IM - 1Ph):** "Capacitor-start motor starting torque is directly related to angle θ between winding currents by?" |
| **13** | **Speed Control of DC Motors** <br> N ∝ (V_t - I_a R_a) / φ <br> (Field / Armature Control) | **~8** | Motor type (Shunt/Series), Terminal voltage, Field current, Armature resistance, External resistance added. | **New speed** after changing field current or armature voltage, or **Method of speed control** to achieve a specific speed. | **DC:** Q71, Q103, Q122, Q126, Q129, Q150, Q155, Q157 | **Q71 (DC):** "Rated speed 1050rpm. To run at 1200rpm, which speed control scheme is used?" <br> **Q103 (DC):** "5kW, 220V, 1500rpm, runs at 1550rpm on NL. Voltage reduced to 165V. Find new speed?" |
| **14** | **Harmonics & Crawling/Cogging** <br> f_h = h × f <br> N_crawl ≈ N_s / 7 | **~8** | Supply frequency, Harmonic order (e.g., 5th, 7th), Motor speed, Slot combinations. | **Frequency** of harmonic currents, **Speed** at which crawling occurs, or method to **reduce harmonics** (like skewing). | **IM - Harmonics:** Q1-Q10, Q18, Q19 <br> **SM - Harmonics:** Q1, Q15, Q65, Q112, Q116, Q163 | **Q7 (IM - Harm):** "Slip at nth harmonic is approximately?" <br> **Q1 (SM - Harm):** "To minimize 5th and 7th harmonics, coil-span must be?" |
| **15** | **Armature Reaction & Commutation (DC)** <br> (Interpoles, Compensating windings) | **~7** | Type of machine (Motor/Generator), Power factor, Brush position, Field current. | **Nature of armature reaction** (magnetizing/demagnetizing), Function of **interpoles**, or **Demagnetizing AT/pole**. | **DC:** Q59, Q90, Q102, Q116, Q146, Q153, Q165, Q171 <br> **SM:** Q66, Q90, Q98, Q119, Q122, Q146, Q173 | **Q90 (DC):** "In DC machine, interpoles are used to?" <br> **Q165 (DC):** "6-pole, 248A, wave wound, brushes on GNA. Demagnetizing AT/pole?" |
| **16** | **Swinburne's / Hopkinson's Test** <br> (Losses in DC Machines) | **~6** | No-load input power, Armature & Field resistances, Voltage and Current during the test. | **Constant losses** , **Efficiency** of the machine, or the **Purpose** of the test. | **DC:** Q19, Q70, Q78, Q135, Q136 | **Q19 (DC):** "By conducting Swinburn's test, which losses can be determined?" <br> **Q135 (DC):** "Which test(s) are called non-loading tests of DC machines?" |
| **17** | **Losses in Transformers (Hysteresis & Eddy Current)** <br> P_h ∝ f <br> P_e ∝ f² | **~6** | Frequency, Loss values at different frequencies, Flux density. | **Separation of losses** , **Effect of frequency** on losses, or **Methods to reduce** losses. | **TF:** Q38, Q42, Q43, Q46, Q51, Q61, Q136, Q144, Q146 | **Q38 (TF):** "Core loss 46W at 50Hz, 80W at 70Hz. Find hysteresis and eddy current loss at 60Hz?" |
| **18** | **DC Generator Characteristics** | **~6** | Load current, Terminal voltage, Field current, Speed. | **Identifying characteristics curves** for series, shunt, and compound generators, or **Voltage build-up** conditions. | **DC:** Q22, Q51, Q62, Q63, Q80, Q83, Q106, Q119, Q147, Q174 | **Q63 (DC):** "Graph represents which characteristic of DC shunt generator?" <br> **Q147 (DC):** "Over compounded generator... terminal voltage at 600A?" |
| **19** | **Induction Motor Equivalent Circuit & Power Flow** | **~6** | Input power, Stator losses, Slip, Mechanical losses. | **Rotor copper loss** , **Air gap power** , **Mechanical power developed** , or **Efficiency**. | **IM - Power Flow:** Q1, Q2, Q3, Q4, Q5, Q6, Q7, Q8, Q9, Q10 | **Q1 (IM - Power Flow):** "Power input=60kW, stator losses=1kW, slip=4%. Find rotor copper loss?" |
| **20** | **Synchronous Machine Construction & Starting** | **~5** | Rotor type, Excitation, Load conditions. | **Function of damper winding** , **Starting methods** , or **Identification of rotor type** for specific applications. | **SM:** Q7, Q42, Q60, Q64, Q78, Q79, Q84, Q85, Q107, Q111, Q120, Q164, Q170 | **Q7 (SM):** "While starting synchronous motor, field winding should be?" <br> **Q107 (SM):** "Specifications of turbo-alternator rotor diameter, stator core length, poles?" |

---

## 🧭 The 5-Question Decision Flowchart (For Any Problem)

Ask these 5 questions in order. Your formula will reveal itself.

| Step | Question to Ask | If YES → | If NO → |
| :---: | :--- | :--- | :--- |
| **1** | **Is there a rotating part (rotor)?** | Go to Step 2 | It's a **TRANSFORMER** (Static device). Use: E = 4.44 f N Φ, VR, η, P_cu ∝ I² |
| **2** | **Does it have a commutator?** | It's a **DC MACHINE** → Go to Step 3 | It's an **AC MACHINE** (IM or SM) → Go to Step 4 |
| **3** | **Is it converting Mechanical→Electrical?** | **DC GENERATOR**: Use E_g = V_t + I_a R_a (or + I_a R_a + V_brush) | **DC MOTOR**: Use E_b = V_t - I_a R_a, N ∝ E_b / φ, T ∝ φ × I_a |
| **4** | **Does it have a DC supply on rotor (field)?** | **SYNCHRONOUS MACHINE**: Use P = (E_f × V_t) / X_s × sinδ, I_a = (V_t - E_f) / (jX_s), VR | **INDUCTION MOTOR**: Use s = (N_s - N_r) / N_s, T ∝ (sE₂²R₂) / (R₂² + (sX₂)²), T ∝ V² |
| **5** | **Is it self-excited? (DC only)** | **SHUNT**: I_f = V_t / R_f, I_a = I_L - I_f <br> **SERIES**: I_a = I_f = I_L, T ∝ I_a² | **SEPARATELY EXCITED**: I_f is independent, I_a = I_L. Use same formulas as shunt. |

---

## 🔑 How to Identify the Machine Type from the Question

| Keywords in Question | Machine Type | Go-to Formula |
| :--- | :--- | :--- |
| "Transformer", "turns ratio", "primary/secondary", "core", "laminations", "Buchholz relay" | **Transformer** | EMF Eq, VR, Efficiency, OC/SC tests |
| "Commutator", "brushes", "armature", "field winding", "back emf", "lap/wave wound" | **DC Machine** | DC formulas (see above) |
| "Slip", "synchronous speed", "rotor resistance", "standstill", "cage", "crawling/cogging" | **Induction Motor** | Slip, Torque equations |
| "Synchronous", "excitation", "load angle", "V-curve", "infinite bus", "damper winding" | **Synchronous Machine** | Power/Phasor equations |
| "Alternator", "prime mover", "voltage regulation" (without transformer), "turbo-alternator" | **Alternator (SM)** | VR = (E - V) / V, E = 4.44 f N Φ |
| "Self-excited", "shunt", "series", "compound", "separately excited" | **DC Machine (Excitation Type)** | Use the excitation decision matrix below |

---

## ⚡ Quick Decision Matrix for Excitation Type (DC Machines)

| Type | Field Connection | I_f | I_a | Torque Equation | Speed Characteristic | Applications |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Separately Excited** | External DC source | I_f = V_f / R_f | I_a = I_L | T ∝ φ × I_a | N ∝ (V_t - I_aR_a) / φ | Ward-Leonard systems, precision drives |
| **Shunt** | Parallel with armature | I_f = V_t / R_f | I_a = I_L - I_f | T ∝ φ × I_a | N ∝ (V_t - I_aR_a) / φ (Nearly constant) | Machine tools, lathes, constant speed applications |
| **Series** | Series with armature | I_f = I_a = I_L | I_a = I_L | T ∝ I_a² | N ∝ 1 / I_a (Drooping) | Traction, cranes, hoists, electric trains |
| **Cumulative Compound** | Shunt + Series (aiding) | I_f = I_sh + I_se | I_a = I_L - I_sh | T ∝ (φ_sh + φ_se) × I_a | Medium droop | Rolling mills, intermittent high torque loads |
| **Differential Compound** | Shunt + Series (opposing) | I_f = I_sh - I_se | I_a = I_L - I_sh | T ∝ (φ_sh - φ_se) × I_a | Rising characteristic | Arc welding (wide voltage variation) |

---

## 📝 The Ultimate "What Happens When..." Cheat-Sheet

### Section A: DC Motors

| Change Made | Which Motor | Effect on Speed (N) | Effect on Torque (T) | Effect on Current (I) | Effect on Voltage (V) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **↑ Armature Resistance (Ra)** | DC Shunt Motor | ↓ Decreases | ↓ Decreases (slightly) | ↓ Decreases | - |
| **↑ Field Resistance (Rf)** | DC Shunt Motor | ↑ Increases | ↓ Decreases (T ∝ φ × I_a) | ↑ Increases (I_a ↑ to maintain T) | - |
| **↑ Supply Voltage (Vt)** | DC Shunt Motor | ↑ Increases | ↑ Increases (T ∝ φ × I_a) | ↑ Increases | - |
| **↓ Field Current (If)** | DC Series Motor | ↑↑ Increases (Danger! Overspeed) | ↓↓ Decreases (T ∝ I_a²) | ↑ Increases | - |
| **↑ Load (Torque)** | DC Shunt Motor | ↓ Slightly decreases | ↑ Increases (to match load) | ↑ Increases | - |
| **↑ Load (Torque)** | DC Series Motor | ↓ Decreases | ↑ Increases (T ∝ I_a²) | ↑ Increases | - |
| **Armature Reaction ↑** | Any DC Motor | ↑ Increases (flux weakening) | ↓ Decreases | ↑ Increases | - |
| **Adding Series Resistance** | DC Shunt Motor | ↓ Decreases (speed control below base) | ↓ Decreases | ↓ Decreases | - |
| **Adding Series Resistance** | DC Series Motor | ↓ Decreases | ↓ Decreases | ↓ Decreases | - |
| **Adding Shunt Resistance (Diverter)** | DC Series Motor | ↑ Increases (speed control above base) | ↓ Decreases | ↑ Increases (armature current) | - |
| **Plugging (Reversing Armature)** | DC Motor | Rapidly ↓ to zero (braking) | Reverses direction | ↑ Increases (high) | - |
| **Dynamic Braking (Armature shorted)** | DC Motor | ↓ Decreases (braking) | Opposes motion | ↓ Decreases | - |

### Section B: Induction Motors

| Change Made | Effect on Speed (N) | Effect on Torque (T) | Effect on Current (I) | Effect on Slip (s) | Effect on Power Factor |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **↑ Supply Voltage (V)** | → Same (N_s depends on f, not V) | ↑ Increases (T ∝ V²) | ↑ Increases | ↓ Decreases | → Same |
| **↓ Supply Voltage (V)** | → Same | ↓↓ Decreases (T ∝ V²) | ↑ Increases (to maintain torque) | ↑ Increases | ↓ Decreases |
| **↑ Frequency (f)** | ↑ Increases (N_s ∝ f) | ↓ Decreases (T ∝ 1/f² if V constant) | ↓ Decreases | ↓ Decreases | ↓ Decreases |
| **↓ Frequency (f) [V/f constant]** | ↓ Decreases | → Same (T_max constant) | → Same | → Same | → Same |
| **↑ Rotor Resistance (R2)** | ↓ Decreases (for same load) | ↑ Increases (Starting torque ↑) | ↓ Decreases | ↑ Increases | ↑ Increases |
| **↑ Load (Torque)** | ↓ Decreases | ↑ Increases (to match load) | ↑ Increases | ↑ Increases | ↓ Decreases |
| **Air Gap ↑** | → Same | ↓ Decreases | ↑ Increases (magnetizing current ↑) | → Same | ↓ Decreases |
| **Skewing (Rotor bars)** | → Same | → Same (reduces cogging) | → Same | → Same | → Same |
| **Saturation ↑** | → Same | ↓ Decreases | ↑ Increases | → Same | ↓ Decreases |
| **Adding External Resistance (Slip-ring)** | ↓ Decreases (for same load) | ↑ Increases (Starting torque) | ↓ Decreases | ↑ Increases | ↑ Increases |

### Section C: Synchronous Machines

| Change Made | Machine Mode | Effect on Speed (N) | Effect on Torque (T) | Effect on Current (I) | Effect on Power Factor | Effect on Load Angle (δ) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **↑ Excitation (If)** | Motor | → Same (Speed is fixed) | → Same (if load is constant) | ↓ Decreases (up to UPF), then ↑ Increases | ↑ Increases (leading) | ↓ Decreases |
| **↓ Excitation (If)** | Motor | → Same | → Same (if load is constant) | ↑ Increases | ↓ Decreases (lagging) | ↑ Increases |
| **↑ Excitation (If)** | Generator | → Same (Speed is fixed) | → Same (if load is constant) | ↑ Increases | ↓ Decreases (lagging) | ↓ Decreases |
| **↓ Excitation (If)** | Generator | → Same | → Same (if load is constant) | ↑ Increases | ↑ Increases (leading) | ↑ Increases |
| **↑ Load (Torque/Power)** | Motor | → Same (Speed is fixed) | ↑ Increases | ↑ Increases | ↓ Decreases | ↑ Increases |
| **↑ Load (Power)** | Generator | ↓ Slightly decreases (droop) | ↑ Increases | ↑ Increases | ↓ Decreases | ↑ Increases |
| **Loss of Excitation** | Motor/Generator | → Same (if connected to grid) | ↓ Decreases | ↑ Increases | ↓↓ Decreases (lagging) | ↑ Increases |
| **Hunting (Load oscillates)** | Motor | → Same (average) | Oscillates | Oscillates | Oscillates | Oscillates |

### Section D: Transformers

| Change Made | Effect on Voltage | Effect on Current | Effect on Losses | Effect on Efficiency |
| :--- | :--- | :--- | :--- | :--- |
| **↑ Load (I₂ ↑)** | ↓ Decreases (due to VR) | ↑ Increases | ↑ Increases (P_cu ∝ I²) | ↓ Decreases (after max efficiency point) |
| **↑ Supply Voltage (V₁)** | ↑ Increases | ↓ Decreases (if load is constant) | ↑ Increases (Core loss increases) | ↓ Decreases (due to increased core loss) |
| **↑ Frequency (f)** [V/f constant] | → Same | → Same | ↑ Increases (P_cu ∝ I², P_h ∝ f) | ↓ Decreases |
| **↑ Frequency (f)** [V constant] | → Same | ↑ Increases | ↑ Increases (P_e ∝ f², P_h ∝ f) | ↓ Decreases |
| **↑ Core Area** | → Same (if turns adjusted) | → Same | ↓ Decreases (flux density ↓) | ↑ Increases |
| **↑ Air Gap in Core** | → Same | ↑ Increases (magnetizing current ↑) | ↑ Increases | ↓ Decreases |
| **Parallel Operation (One TF fails)** | → Same (if load shared) | ↑ Increases (other TF carries more) | ↑ Increases | ↓ Decreases |

---

## 📌 Key Relationships to Memorize

| Relationship | Formula | When to Use |
| :--- | :--- | :--- |
| **DC Shunt: Speed vs Flux** | N ∝ 1 / φ | When field current changes |
| **DC Shunt: Torque vs Ia** | T ∝ I_a | When armature current changes (flux constant) |
| **DC Series: Torque vs Ia** | T ∝ I_a² | When armature current changes (flux ∝ Ia) |
| **IM: Torque vs Voltage** | T ∝ V² | When supply voltage changes |
| **IM: Torque vs Slip (low slip)** | T ∝ s | Near synchronous speed |
| **IM: Torque vs Slip (high slip)** | T ∝ 1/s | Near standstill |
| **IM: Starting Torque Max** | R_2 = X_2 | Condition for maximum starting torque |
| **IM: Slip at Max Torque** | s_mT = R_2 / X_2 | To find slip at maximum torque |
| **IM: Rotor Frequency** | f_2 = s × f_1 | When rotor EMF frequency is asked |
| **SM: Power vs Load Angle** | P ∝ sinδ | For cylindrical rotor |
| **SM: Reactive Power vs Excitation** | Q ∝ (E_f × cosδ - V_t) | For V-curve problems |
| **SM: Reluctance Power** | P_rel ∝ (1/X_q - 1/X_d) × sin2δ | For salient pole machines |
| **Transformer: Copper Loss** | P_cu ∝ I² | When load current changes |
| **Transformer: Efficiency Max** | P_i = P_cu | Condition for maximum efficiency |
| **Transformer: Voltage Regulation** | VR = R_pu cosφ ± X_pu sinφ | For approximate VR calculation |
| **Transformer: OC Test** | P_i = V_1 × I_0 × cosφ_0 | To find core loss |
| **Transformer: SC Test** | P_cu = I_sc² × R_eq | To find copper loss and equivalent resistance |
| **DC Generator: EMF** | E_g = V_t + I_a R_a | For shunt/separately excited generator |
| **DC Generator: EMF** | E_g = V_t + I_a(R_a + R_se) | For series/compound generator |
| **DC Motor: Back EMF** | E_b = V_t - I_a R_a | For shunt/separately excited motor |
| **DC Motor: Back EMF** | E_b = V_t - I_a(R_a + R_se) | For series/compound motor |

---

## 🎯 Top 20 Concepts to Score >90% (COMPLETE TABLE)

| Rank | Concept | Weightage | Key Formulas | Mapped Question Numbers |
| :---: | :--- | :---: | :--- | :--- |
| **1** | **EMF Equation & Magnetic Circuits** | **~11%** | E = 4.44 f N Φ <br> E = (P Φ N Z) / (60 A) | **TF:** Q16, Q17, Q18, Q20, Q22, Q154 <br> **DC:** Q3, Q30, Q35, Q38, Q47, Q93, Q117, Q121, Q132, Q145, Q149 <br> **SM:** Q9, Q40, Q41, Q121, Q126 |
| **2** | **Transformer Voltage Regulation** | **~8%** | VR = R_pu cosφ ± X_pu sinφ <br> VR = (E - V) / V × 100 | **TF:** Q56, Q74, Q75, Q76, Q77, Q78, Q79, Q80, Q81, Q82, Q130, Q147, Q153 <br> **SM:** Q72, Q83, Q88, Q144 |
| **3** | **Efficiency & Losses** | **~7.5%** | η = Output / Input <br> P_cu ∝ I² <br> Max η: P_i = P_cu | **TF:** Q39, Q40, Q45, Q60, Q61, Q62, Q63, Q64, Q65, Q66, Q67, Q68, Q69, Q70, Q71, Q72, Q73, Q121, Q139, Q140, Q149 <br> **DC:** Q14, Q19, Q36, Q89, Q111, Q138, Q172 |
| **4** | **Induction Motor Torque & Slip** | **~7%** | s = (N_s - N_r) / N_s <br> T ∝ (sE₂²R₂) / (R₂² + (sX₂)²) <br> T ∝ V² | **Basics/Slip:** Q1-Q17 <br> **Torque Eqs:** Q1-Q15 <br> **Characteristics:** Q1-Q11 |
| **5** | **DC Motor Speed & Back EMF** | **~6%** | E_b = V_t - I_a R_a <br> N ∝ E_b / φ | **DC:** Q5, Q10, Q23, Q41, Q69, Q73, Q79, Q86, Q103, Q109, Q115, Q118, Q122, Q126, Q129, Q148, Q150, Q157, Q158, Q161, Q164, Q167, Q173 |
| **6** | **Auto-Transformer Rating** | **~5.5%** | VA_AT = (1 / (1-K)) × VA_2W <br> K = V_LV / V_HV | **TF:** Q99, Q102, Q105, Q106, Q107, Q108, Q109, Q110, Q111, Q122, Q129, Q131, Q141, Q155 |
| **7** | **Parallel Operation** | **~4.5%** | S_A / S_B = Z_B / Z_A <br> Load Sharing ∝ Rating | **TF:** Q112, Q113, Q114, Q115, Q116, Q135, Q143 <br> **SM:** Q39, Q45, Q109, Q117, Q129 |
| **8** | **Transformer Connections (3-Phase)** | **~4%** | V_L = V_Ph (Δ) <br> V_L = √3 × V_Ph (Y) <br> Open Delta = 57.7% | **TF:** Q86, Q88, Q89, Q90, Q91, Q92, Q93, Q94, Q95, Q96, Q97, Q123, Q133, Q138, Q156 |
| **9** | **Synchronous Motor/Alternator Power** | **~3.5%** | P = (E_f × V_t) / X_s × sinδ <br> I_a = (V_t - E_f) / (jX_s) | **SM:** Q13, Q19, Q22, Q59, Q110, Q121, Q125, Q127, Q134, Q137, Q139, Q142, Q143, Q150 |
| **10** | **Starting Methods of IM** | **~3%** | T_st ∝ V² <br> I_st ∝ V <br> Star-Delta: T_st(Y) / T_st(DOL) = 1/3 | **IM - Starting:** Q1, Q2, Q3, Q4, Q5, Q6, Q7, Q8, Q9, Q10, Q11, Q12, Q13, Q14, Q15 |
| **11** | **Testing of Transformers (OC & SC)** | **~3%** | P_i = V_1 × I_0 × cosφ_0 <br> P_cu = I_sc² × R_eq | **TF:** Q31, Q48, Q49, Q50, Q52, Q53, Q54, Q55, Q57, Q58 <br> **IM - Testing:** Q4, Q5 |
| **12** | **Single-Phase Induction Motor** | **~2.5%** | s_f = s <br> s_b = 2 - s <br> T ∝ I_1 × I_2 × sinθ | **IM - 1Ph:** Q6, Q10, Q16, Q27, Q32, Q34, Q35, Q40 |
| **13** | **Speed Control of DC Motors** | **~2%** | N ∝ (V_t - I_a R_a) / φ | **DC:** Q71, Q103, Q122, Q126, Q129, Q150, Q155, Q157 |
| **14** | **Harmonics & Crawling/Cogging** | **~2%** | f_h = h × f <br> N_crawl ≈ N_s / 7 | **IM - Harmonics:** Q1-Q10, Q18, Q19 <br> **SM - Harmonics:** Q1, Q15, Q65, Q112, Q116, Q163 |
| **15** | **Armature Reaction & Commutation** | **~1.8%** | Interpoles, Compensating windings, Demagnetizing AT/pole | **DC:** Q59, Q90, Q102, Q116, Q146, Q153, Q165, Q171 <br> **SM:** Q66, Q90, Q98, Q119, Q122, Q146, Q173 |
| **16** | **Swinburne's / Hopkinson's Test** | **~1.5%** | Losses in DC Machines | **DC:** Q19, Q70, Q78, Q135, Q136 |
| **17** | **Hysteresis & Eddy Current Losses** | **~1.5%** | P_h ∝ f <br> P_e ∝ f² | **TF:** Q38, Q42, Q43, Q46, Q51, Q61, Q136, Q144, Q146 |
| **18** | **DC Generator Characteristics** | **~1.5%** | Internal, External, and Open Circuit Characteristics | **DC:** Q22, Q51, Q62, Q63, Q80, Q83, Q106, Q119, Q147, Q174 |
| **19** | **IM Equivalent Circuit & Power Flow** | **~1.5%** | P_ag = P_in - P_stator_loss <br> P_cu(rotor) = s × P_ag | **IM - Power Flow:** Q1, Q2, Q3, Q4, Q5, Q6, Q7, Q8, Q9, Q10 |
| **20** | **SM Construction & Starting** | **~1.2%** | Damper winding, Salient vs Cylindrical rotor | **SM:** Q7, Q42, Q60, Q64, Q78, Q79, Q84, Q85, Q107, Q111, Q120, Q164, Q170 |

---

## 📌 Quick Reference Card (Exam Day)

| Concept | Formula | Quick Tip |
| :--- | :--- | :--- |
| EMF Eq (TF/Alt) | E = 4.44 × f × N × Φ | Use Φ = B × A if flux density is given |
| EMF Eq (DC) | E = (P × Φ × N × Z) / (60 × A) | Lap: A = P; Wave: A = 2 |
| VR (Lagging) | VR = R_pu cosφ + X_pu sinφ | Sign is POSITIVE for lagging |
| VR (Leading) | VR = R_pu cosφ - X_pu sinφ | Sign is NEGATIVE for leading |
| Max Efficiency | P_i = P_cu | x = √(P_i / P_cu(FL)) where x = load fraction |
| Auto-TF Rating | VA_AT = (1 / (1-K)) × VA_2W | K = V_LV / V_HV (for step-down AT) |
| Open Delta Capacity | 57.7% of Δ-Δ bank | Also (1/√3) × 100% |
| Slip | s = (N_s - N_r) / N_s | At standstill: s = 1; At synchronous: s = 0 |
| Starting Torque (IM) | T_st ∝ V² | Reducing voltage reduces torque by square of voltage ratio |
| DC Back EMF | E_b = V_t - I_a R_a | At starting: E_b = 0 (since speed = 0) |
| Hysteresis Loss | P_h ∝ f | Increases with frequency |
| Eddy Current Loss | P_e ∝ f² | Increases with square of frequency |
| OC Test | Measures core loss | No-load current is drawn at low pf (~0.2-0.3) |
| SC Test | Measures copper loss | Conducted at rated current, low voltage |
| Damper Winding | Provides starting torque & prevents hunting | Used in synchronous motors |
| Interpoles | Improve commutation | Connected in series with armature |

---

## 🧠 Step-by-Step Problem Solving Approach

Follow this systematic approach for every numerical problem:

| Step | Action | Example |
| :---: | :--- | :--- |
| **1** | **Read the question carefully** | Underline keywords: "shunt motor", "series generator", "transformer", "slip", "synchronous" |
| **2** | **Identify the machine type** | Use the [How to Identify the Machine Type](#-how-to-identify-the-machine-type-from-the-question) table |
| **3** | **Follow the Decision Flowchart** | Go through the 5 questions to narrow down the formula family |
| **4** | **Write down all given values** | Vt = 220V, Ia = 17.5A, Ra = 0.4Ω, N1 = 1000rpm, N2 = ? |
| **5** | **Identify what is being asked** | "Find external resistance to reduce speed to 600rpm" |
| **6** | **Pick the relevant formula** | N ∝ E_b / φ and E_b = V_t - I_a R_a |
| **7** | **Solve step-by-step** | Show all intermediate steps to avoid calculation errors |
| **8** | **Verify your answer** | Check units and magnitude. Compare with options if available. |

---

## 🏆 Final Summary

| Priority | Action |
| :---: | :--- |
| **1** | **Master Top 5 Concepts** (EMF Eq, VR, Efficiency, Torque/Slip, DC Speed) - These cover ~40% of the paper |
| **2** | **Practice all numerical problems** from the PDF using the step-by-step approach |
| **3** | **Don't ignore theory questions** - They are easy marks and cover ~20% of the paper |
| **4** | **Use the "What Happens When..." cheat-sheet** for quick reference during revision |
| **5** | **Create and revise a formula sheet** daily before the exam |
| **6** | **Take mock tests** to improve speed and accuracy |

---

**Good luck with your exam preparation! 🎯**

---

# 📝 EMBEDDED PYQs — Ohm Institute PDF (GENCO/TRANSCO/DISCOMs)

> Source: Study_Material__GTD_PYQs_2026_05_26_3_Electrical_Machine.pdf  
> Contains ~1872 PYQs across 4 units. Selected representative Qs below.

---

## Section A: Transformers

**Q1 (Transco-12):** Function of oil in transformer:
(a) Insulation & cooling &emsp; (b) Lightning protection  
(c) Short circuit protection &emsp; (d) Lubrication  
**Answer: (a)**

**Q2 (SSC-JE-13):** Two parallel conductors with opposite currents:
(a) Attract &emsp; (b) Repel &emsp; (c) Axial force &emsp; (d) No force  
**Answer: (b)** — Opposite currents repel

**Q10 (TSGenco-15):** Core laminated to reduce:
(a) Hysteresis loss &emsp; (b) Eddy-current loss  
(c) Magnetic noise &emsp; (d) Magnetizing current  
**Answer: (b)** — Lamination reduces eddy current loss (∝ thickness²)

**Q16 (APSPDCL-12):** 220V/12-0-12V transformer, EMF/turn=1V. Secondary turns:
(a) 12 center-tap &emsp; (b) 220 center-tap  
(c) 24 no center-tap &emsp; (d) 24 with center-tap  
**Solution:** V₂=24V (12+12), N₂ = V₂/(EMF/turn) = 24/1 = 24 turns with center-tap. **Answer: (d)**

**Q20 (TSGenco-15):** 50Hz, 1000 turns, secondary EMF=222V, Bm=0.1Wb/m². Core area?
**Solution:** E=4.44fNΦm → Φm = 222/(4.44×50×1000) = 0.001 Wb. Area = Φm/Bm = 0.001/0.1 = **0.01 m². Answer: (b)**

**Q56 (TSNPDCL-15):** 4 kVA, 200/400V transformer. SC test: 15V, 10A, 80W on HV. %Reg at full load UPF?
**Solution:** Full load I_HV = 4000/400 = 10A. SC gives full-load current at 15V, 80W.  
Zeq = 15/10 = 1.5Ω, Req = 80/100 = 0.8Ω, Xeq = √(1.5²-0.8²) = 1.27Ω  
%Reg at UPF = I×R/V × 100% = 10×0.8/400 × 100 = **2%. Answer: (a)**

**Q74 (APGenco-12):** Transformer R=0.2pu, X=0.6pu. PU voltage regulation at 0.8pf lag:
(a) 0.52 &emsp; (b) 0.42 &emsp; (c) 0.62 &emsp; (d) 0.36  
**Solution:** VR = Rcosφ + Xsinφ = 0.2×0.8 + 0.6×0.6 = 0.16+0.36 = **0.52. Answer: (a)**

**Q106 (HMWS-15):** 100V/10V, 50VA transformer → 100V/110V auto-transformer. New VA rating?
**Solution:** K=100/110 = 0.909. VA_AT = 1/(1-K)×VA_2W = 1/(1-0.909)×50 = 11×50 = **550VA. Answer: (d)**

**Q133 (TSSPDCL-15):** 600 primary turns, 150 secondary turns, supply 1.5kV. Secondary voltage for (a) star-delta, (b) delta-star?
**Solution:** Per-phase ratio = 600/150 = 4.  
(a) Star-delta: V_ph(pri)=1500/√3=866V, V_ph(sec)=866/4=216.5V, V_L(sec)=216.5V (delta)  
(b) Delta-star: V_ph(pri)=1500V, V_ph(sec)=1500/4=375V, V_L(sec)=375×√3=649.5V

**Q38 (TSGenco-15):** Core loss 46W at 50Hz, 80W at 70Hz. Find hysteresis & eddy current at 60Hz:
**Solution:** P_c = Af + Bf². At 50Hz: 50A+2500B=46. At 70Hz: 70A+4900B=80.  
Solve: A=0.5, B=0.0084. At 60Hz: P_h=0.5×60=30W, P_e=0.0084×3600=30.24W. Total=60.24W.

---

## Section B: DC Machines

**Q3 (APSPDCL-12):** 4-pole, 1200rpm, lap wound, 1520 conductors, flux=0.01Wb. Find EMF:
**Solution:** For lap: A=P=4. E = PΦNZ/(60A) = 4×0.01×1200×1520/(60×4) = 72960/240 = **304V**

**Q19 (APGenco-12):** Swinburne's test determines:
(a) Constant losses &emsp; (b) Variable losses  
(c) Both &emsp; (d) Temperature rise  
**Answer: (a)** — Swinburne's = no-load test, measures constant losses (iron + friction)

**Q73 (APSPDCL-12):** 150V DC motor, Ra=0.4Ω, Eb=142V. Find Ia:
**Solution:** Eb = V - IaRa → 142 = 150 - Ia×0.4 → Ia = 8/0.4 = **20A**

**Q90 (TSNPDCL-15):** Interpoles in DC machine are used to:
(a) Improve commutation &emsp; (b) Increase torque  
(c) Reduce losses &emsp; (d) Increase speed  
**Answer: (a)** — Interpoles cancel armature reaction mmf at commutating zone

**Q122 (HMWS-15):** 200V DC shunt motor, 1000rpm, Ia=17.5A, Ra=0.4Ω. External resistance to reduce speed to 600rpm (load torque constant)?
**Solution:** Eb₁ = 200-17.5×0.4 = 193V. With constant torque, Ia₂ = Ia₁ (Φ same since shunt).  
Eb₂/Eb₁ = N₂/N₁ → Eb₂ = 193×600/1000 = 115.8V.  
115.8 = 200 - 17.5×(0.4+R_ext) → 17.5×(0.4+R_ext) = 84.2 → R_ext = 4.81-0.4 = **4.41Ω**

**Q165 (TSGenco-24):** 6-pole DC machine, 248A, wave wound, brushes on GNA. Demagnetizing AT/pole?
**Solution:** Wave: A=2. I_a = 248A. For wave, each parallel path current = 248/2 = 124A.  
With brushes on GNA, demagnetizing AT/pole ≈ (I_a×Z)/(2×P×A) × (brush shift). Without specific shift, theoretical = 0 for GNA.

---

## Section C: Three-Phase Induction Motor

**Q1 (EM PDF):** Slip of 3-ph IM at standstill:
(a) 0 &emsp; (b) 1 &emsp; (c) 0.5 &emsp; (d) ∞  
**Answer: (b) 1** — at standstill N=0, s = (Ns-0)/Ns = 1

**Q11 (EM PDF):** 400V, 4-pole, 50Hz, IM runs at 1440rpm. Slip?
**Solution:** Ns = 120×50/4 = 1500rpm. s = (1500-1440)/1500 = **0.04 (4%)**

**Q3 (Torque eq):** Supply voltage reduced by 10%. Maximum torque decreases by:
**Solution:** Tmax ∝ V². V₂ = 0.9V₁. T₂/T₁ = (0.9)² = 0.81. Decrease = **19%. Answer: (d)**

**Q6 (Starting):** DOL torque = 320 Nm. Auto-transformer 50% tapping → starting torque?
**Solution:** T_st ∝ V², with 50% tap V₂=0.5V₁. T_st = 320×0.5² = 320×0.25 = **80 Nm**

**Q8 (Starting):** DOL starting current in delta = 30A. Star-delta starter starting current?
**Solution:** In star: V_ph = V_L/√3. I_ph(star) = V_L/(√3×Z). I_L(star) = V_L/(√3×Z).  
In delta: I_ph(delta) = V_L/Z, I_L(delta) = √3×V_L/Z = 30A.  
I_L(star)/I_L(delta) = 1/3. I_L(star) = 30/3 = **10A**

**Q10 (1-Ph IM):** 4-pole, 50Hz, running at 1300rpm. Forward and backward rotor frequencies:
**Solution:** Ns = 1500rpm. s = (1500-1300)/1500 = 0.133.  
Forward freq = s×f = 0.133×50 = **6.67 Hz**.  
Backward slip = 2-s = 1.867. Backward freq = (2-s)×f = 1.867×50 = **93.33 Hz. Answer: (a) 93.33 Hz, 6.67 Hz**

---

## Section D: Synchronous Machines

**Q7 (EM PDF):** While starting synchronous motor, field winding should be:
(a) Open &emsp; (b) Short-circuited &emsp; (c) Connected to DC &emsp; (d) Connected to AC  
**Answer: (b)** — Short-circuited during starting to protect from induced high voltage

**Q19 (EM PDF):** Xs=1pu, V=1pu, Ef=1.5pu, Ia=0+j0.5. Mode of operation?
**Solution:** Ia = (V-Ef)/jXs = (1-1.5∠δ)/j1 = 0+j0.5.  
This gives δ negative (Ef leads V) → generating mode (over-excited).  
**Answer: Generator with leading pf**

**Q39 (EM PDF):** Two alternators: 40MVA & 60MVA, 5% regulation each, total load 80MW. Load sharing?
**Solution:** S₁/S₂ = Z₂/Z₁ = 1 (same %Z). S₁ = 40/(40+60)×80 = 32MW, S₂ = 48MW.  
With same %Z, load shared in proportion to rating.

**Q107 (EM PDF):** Turbo-alternator rotor characteristics:
(a) Large diameter, short axial length, many poles  
(b) Small diameter, long axial length, 2-4 poles  
(c) Salient pole construction  
(d) Vertical shaft design  
**Answer: (b)** — Turbo-alternator = cylindrical rotor, high speed, 2-4 poles

**Q142 (EM PDF):** SM: Xs=0.4pu, Ef=1.2pu, δ=30°. Power output/phase?
**Solution:** P = (Ef×V/Xs)sinδ = (1.2×1/0.4)×sin30° = 3×0.5 = **1.5 pu**

---

> **Total embedded PYQs: 22 (selected from ~1872 EM questions)**

---