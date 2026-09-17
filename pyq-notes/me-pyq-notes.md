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
| :---: | :-------------------------------------------------------------- | :---: | :--- | :--- | :--- | :--- |
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
| :---: | :-------------------------------------------------------------- | :--- | :--- |
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
| :---: | :-------------------------------------------------------------- | :---: | :--- | :--- |
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
| :---: | :-------------------------------------------------------------- | :--- |
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
| :---: | :-------------------------------------------------------------- |
| **1** | **Master Top 5 Concepts** (EMF Eq, VR, Efficiency, Torque/Slip, DC Speed) - These cover ~40% of the paper |
| **2** | **Practice all numerical problems** from the PDF using the step-by-step approach |
| **3** | **Don't ignore theory questions** - They are easy marks and cover ~20% of the paper |
| **4** | **Use the "What Happens When..." cheat-sheet** for quick reference during revision |
| **5** | **Create and revise a formula sheet** daily before the exam |
| **6** | **Take mock tests** to improve speed and accuracy |

---

**Good luck with your exam preparation! 🎯**

---

# 📝 FULL PYQ ANALYSIS — All 697 Machines Questions (Concept through PYQ)

> Source: Study_Material__GTD_PYQs_2026_05_26_3_Electrical_Machine.pdf (OHM Institute)
> Every question: answer + options, the concept it teaches, and how the examiner twists it.

**Legend:** Q = question · Ans = correct option · Concept = new term/principle · Twist = examiner variation → new answer

## Unit 1: Transformers (158 Qs)

**Q1 (Transco-12):** The function of oil in a transformer is
(a) to provide insulation and cooling (b) to provide protection against lightning (c) to provide protection against short circuit (d) to provide lubrication
**Ans: (a)** — Transformer oil gives both insulation and cooling.
**Concept:** Transformer oil = dielectric + coolant.
**Twist:** Purpose of silica-gel breather → absorb moisture entering with air; DGA (Dissolved Gas Analysis) of oil → detects incipient (overheating/arcing) faults.

**Q2 (SSC-JE-13):** Two parallel conductors carrying current in opposite directions will exert on each other
(a) an attractive force (b) a repulsive force (c) an axial force (d) no force
**Ans: (b)** — Opposite currents repel.
**Concept:** Parallel conductors: same direction attract, opposite repel.
**Twist:** Same-direction currents → attract; current in opposite direction in adjacent power cable → repulsion, mechanical stress on supports.

**Q3 (SSC-JE-13):** Silicon content in iron lamination is kept within 5% as it
(a) Makes the material brittle (b) Reduces the curie point (c) Increases hysteresis loss (d) Increases cost
**Ans: (a)** — Above ~5% Si makes the steel brittle.
**Concept:** Si steel: adding Si cuts hysteresis loss but above ~5% → brittleness (limited to 4–5%).
**Twist:** Reason Si is added at all → reduces hysteresis loss and increases resistivity (less eddy loss); only 0.5% Si suffices to cut hysteresis.

**Q4 (ISRO-14):** Buchholz relay is a
(a) Voltage sensitive device (b) Current sensitive device (c) Frequency sensitive device (d) Gas actuated device
**Ans: (d)** — Gas-actuated relay.
**Concept:** Buchholz = gas/oil-operated protection for incipient faults in oil-immersed transformers.
**Twist:** Mounting location → between main tank and conservator; it does NOT protect against external short circuits/overloads (use O/C–E/F relays + oil pressure).

**Q5 (ISRO-14):** With core type transformers, the limbs are stepped so as to
(a) Reduce the iron material and therefore iron loss (b) Provide better cooling (c) Reduce the conductor material and therefore I2R loss (d) Provide more mechanical strength to the core
**Ans: (c)** — Stepping makes cross-section near-circular, cutting copper length → lower I²R loss.
**Concept:** Stepped core → circular cross-section → less mean-turn length of winding.
**Twist:** Purpose of laminations → reduce eddy-current loss (Pe ∝ t²); purpose of silicon → reduce hysteresis loss.

**Q6 (SSC-JE-S2-14):** Stepped core is used in transformer in order to reduce
(a) Volume of iron (b) Volume of copper (c) Iron loss (d) Reluctance of core
**Ans: (b)** — Stepped (circular) core reduces copper volume.
**Concept:** Stepped core ⇒ circular core ⇒ shorter mean length of turn ⇒ less copper.
**Twist:** Equivalent circular diameter reduces conductor volume; if asked "purpose of step" → reduce copper + I²R loss.

**Q7 (SSC-JE-S2-14):** The north pole of a magnet is moved away from a metallic ring. The induced current in the ring flows
(a) Clockwise (b) Anti-clockwise (c) First anticlockwise and then clockwise (d) First clockwise and then anticlockwise
**Ans: (a)** — Clockwise (Lenz's law opposes flux decrease).
**Concept:** Lenz's law: induced current opposes the change in flux.
**Twist:** North pole moved TOWARDS ring → anticlockwise; south pole moved away → anticlockwise.

**Q8 (SSC-JE-S2-14):** Low voltage windings are placed nearer to the core in the case of concentric windings because
(a) It reduces hysteresis loss (b) It reduces eddy current loss (c) It reduces insulation requirement (d) It reduces leakage fluxes
**Ans: (c)** — LV near core needs less insulation against the core.
**Concept:** Concentric windings: LV innermost, HV outside (minimum insulation).
**Twist:** HV placed outermost → easier tapping and less insulation stress; swapping → more insulation material needed.

**Q9 (TSGenco-15):** The core of a transformer is made of
(a) Silicon steel (b) annealed copper (c) Seasoned wood (d) aluminium
**Ans: (a)** — Silicon steel.
**Concept:** Core material = high-permeability, low-loss silicon steel.
**Twist:** Reason → low hysteresis (Si) + low eddy loss (lamination); copper/alu are conductors → unusable.

**Q10 (TSGenco-15):** The core of a transformer is assembled with laminated sheets to reduce
(a) Hysteresis loss (b) Eddy – current loss (c) Magnetic noise (d) Magnetizing current
**Ans: (b)** — Lamination cuts eddy-current loss.
**Concept:** Pe ∝ Bm² f² t² (t = lamination thickness).
**Twist:** If asked how hysteresis is reduced → add silicon; lamination thickness halved → Pe reduced to 1/4.

**Q11 (TSTransco-15):** The desirable properties of transformer core material are
(a) Low permeability and low hysteresis loss (b) High permeability and high hysteresis loss (c) High permeability and low hysteresis loss (d) Low permeability and hysteresis loss
**Ans: (c)** — High permeability + low hysteresis loss.
**Concept:** Core material: high μ (low reluctance, low Iμ) + low hysteresis loss.
**Twist:** For permanent magnets → high retentivity + high coercivity (hard material); for cores → soft material.

**Q12 (TSNPDCL-15):** In a transformer, the core is laminated to reduce
(a) Copper losses in the core (b) Hysteresis losses only (c) Hysteresis and eddy current losses (d) Eddy current losses only
**Ans: (d)** — Lamination reduces eddy-current loss only.
**Concept:** Lamination → eddy current loss (hysteresis needs Si steel).
**Twist:** "Hysteresis loss is reduced by ___" → silicon content; thin laminations raise resistivity path for eddy currents.

**Q13 (APTransco-17):** The main purpose of using core in a transformer is to
(a) Decrease iron losses (b) Eliminate magnetic hysteresis (c) Reduce reluctance of the common magnetic circuit (d) Prevent eddy current loss
**Ans: (c)** — Core gives a low-reluctance flux path.
**Concept:** High-μ core ⇒ low reluctance ⇒ low magnetizing current.
**Twist:** If air gap introduced → reluctance up, Iμ up greatly (Q24); removing core → transformer action fails (flux linkage lost).

**Q14 (TSSPDCI-18):** Statements: (1) Transformer is a doubly excited magnetic system (2) Synchronous motor is a doubly excited magnetic system (3) Relay is a singly excited magnetic system.
(a) 1 and 2 (b) 2 and 3 (c) 1 only (d) 1, 2 and 3
**Ans: (b)** — Transformer is SINGLY excited (primary only); synchronous motor doubly; relay singly.
**Concept:** Doubly excited = field + armature both supplied (sync machine); transformer has only primary source.
**Twist:** DC series motor (single excitation) vs separately-excited DC motor (double); induction motor → singly excited.

**Q15 (Transco-13):** An isolation transformer has primary to secondary turn's ratio of
(a) 1:1 (b) 1:2 (c) 2:1 (d) 1:3
**Ans: (a)** — 1:1.
**Concept:** Isolation transformer = 1:1 turns ratio for galvanic isolation.
**Twist:** Used in medical equipment to break DC/earth paths; ratio changed to 1:2 → no longer isolation (becomes step-up).

**Q16 (APSPDCL-12):** A 220V/12-0-12V transformer has an emf/turn of 1V. The number of turns on secondary would be
(a) 12 with centre tap (b) 220 with centre tap (c) 24 with no centre tap (d) 24 with centre tap
**Ans: (d)** — Total secondary = 24 V → 24 turns, centre-tapped.
**Concept:** E/turn = E2/N2; V2 total = 24 V (two 12 V halves).
**Twist:** emf/turn = 2 V → N2 = 12 turns; if centre tap gives ±12 V, full secondary = 24 V → 24 turns.

**Q17 (APSPDCL-12):** An ideal transformer N1 = 100, N2 = 200 with mutual flux φm(t) = −0.05(t² − 2t). Magnitude of induced emf
(a) –5(t – 1) (b) –10(t – 1) (c) –5(t – 1)² (d) –20(t – 1)
**Ans: (d)** — E2 = N2 dφ/dt = 200×(−0.1)(t−1) = −20(t−1).
**Concept:** EMF equation E = N dφ/dt.
**Twist:** Use primary E1 = N1 dφ/dt → −10(t−1); if flux = −0.05t² → E2 = −20t (no (t−1) shift).

**Q18 (HMWS-12):** A 20-turn iron cored inductor is connected to a 100V, 50Hz source. Bm = 1 Wb/m². Cross-sectional area of core
(a) 0.15 m² (b) 0.345 m² (c) 0.0225 m² (d) 0.56 m²
**Ans: (c)** — Ac = 100/(4.44×1×50×20) = 0.0225 m².
**Concept:** E = 4.44 Bm Ac f N.
**Twist:** f doubled (100 Hz) → Ac halves to 0.01125 m²; N halved → Ac doubles.

**Q19 (APSPDCL-14):** Core of a two-winding transformer subjected to flux: 0→0.009 Wb (0–0.06 s), flat (0.06–0.1 s), 0.009→0 (0.1–0.12 s); N1=200, N2=500. Secondary induced-emf waveform
(a) 75 V pulse (b) 90 V / −30 V (c) 75 V / 0 / −225 V (d) +75 V / −30 V
**Ans: (c)** — E2 = −N2 dφ/dt: 500×0.15=75 V, then 0, then 500×(−0.45)=−225 V.
**Concept:** e = −N dφ/dt (slope of flux determines induced emf).
**Twist:** Steeper slope (0.009 over 0.01 s) → 450 V; N2 changed to 1000 → 150 V and −450 V.

**Q20 (TS Genco-15):** emf in secondary of 50 Hz, 1000-turn transformer is 222 V, Bm = 0.1 Wb/m². Cross-sectional area
(a) 0.1 m² (b) 0.01 m² (c) 1 m² (d) 0.001 m²
**Ans: (b)** — Ac = 222/(4.44×0.1×50×1000) = 0.01 m².
**Concept:** E = 4.44 Bm Ac f N.
**Twist:** E = 444 V with same data → 0.02 m²; N = 2000 → 0.005 m².

**Q21 (TS Genco-15):** Two coils, coupling coefficient 0.6, L1 = 0.4 H, L2 = 2.5 H. Mutual inductance M
(a) 0.6 H (b) 2.9 H (c) 2.1 H (d) 1.45 H
**Ans: (a)** — M = k√(L1L2) = 0.6×√(1.0) = 0.6 H.
**Concept:** M = k√(L1L2); k = M/√(L1L2).
**Twist:** k = 1 (tight coupling) → M = 1 H; if M = 0.8 H given, k = 0.8.

**Q22 (AP Genco-17):** Primary turns of 444V/222V, 50 Hz transformer with Ac = 100 cm², Bm = 1.0 T
(a) 100 (b) 200 (c) 222 (d) 400
**Ans: (b)** — N1 = 444/(4.44×1×100×10⁻⁴×50) = 200 turns.
**Concept:** E = 4.44 Bm Ac f N.
**Twist:** V = 222 V → N1 = 100; Bm = 0.5 T → N1 = 400.

**Q23 (TSSPDCI-18):** 220/110 V, 50 Hz transformer. (i) run at 220 V, 5% lower f → E21; (ii) run at 110 V, 50% lower f → E22. Ratio E21/E22
(a) 0.5 (b) 1.5 (c) 1.0 (d) 2
**Ans: (d)** — E21 = 110 V (turn ratio); E22 = 55 V (V/f kept const) → 110/55 = 2.
**Concept:** EMF ∝ f (Bm const); secondary voltage = (N2/N1)·V1.
**Twist:** Case (ii) voltage not halved (still 220 V) → E22 = 110 V → ratio 1; if V/f rule violated → core saturation (Bm rises).

**Q24 (HMWS-12):** When airgap is introduced in transformer core, then
(a) Reluctance of magnetic path is decreased (b) Hysteresis loss is decreased (c) Magnetizing current is greatly increased (d) Eddy current is increased
**Ans: (c)** — Air gap ⇒ low μ ⇒ high reluctance ⇒ Iμ increases greatly.
**Concept:** Iμ ∝ 1/μ; air gap destroys low-reluctance path.
**Twist:** Slightly cutting the core for metering inserts gap → magnetizing current up; consequence → poor power factor on no-load.

**Q25 (HMWS-12):** When the primary of a transformer is connected to a dc supply
(a) Primary draws small current (b) Core losses are increased (c) Primary leakage reactance is increased (d) Primary may burn out
**Ans: (d)** — DC → X = 0, only tiny winding R → huge current → burn-out.
**Concept:** Transformer is AC device; dc gives steady flux, no back-emf.
**Twist:** DC with a series resistor limits current → safe but no transfer; dΦ/dt = 0 → no induced emf.

**Q26 (HMWS-12):** The no-load pf of a transformer is small because
(a) Iron loss component of I0 is large (b) Magnetizing component of I0 is large (c) Magnetizing component of I0 is small (d) Copper losses are high
**Ans: (b)** — Magnetizing (quadrature) component dominates I0.
**Concept:** I0 = Iw + Iμ; cosφ0 ≈ 0.1–0.3 because Iμ ≫ Iw.
**Twist:** Improving core (higher μ) → lower Iμ → slightly higher pf; larger air gap → pf drops further.

**Q27 (HMWS-12):** A 230/2300 V transformer takes no-load current of 5A at 0.25 pf lagging. Core loss
(a) 300.2 W (b) 192.5 W (c) 212.6 W (d) 287.5 W
**Ans: (d)** — Pi = V1 I0 cosφ0 = 230×5×0.25 = 287.5 W.
**Concept:** Pi = V1 I0 cosφ0 (from OC test).
**Twist:** V = 115 V → Pi = 143.75 W; pf 0.2 → Pi = 230 W.

**Q28 (EPDCL-14):** Power factor of a transformer on no-load is poor due to
(a) Magnetizing reactance of the transformer (b) Open circuited secondary (c) Low primary winding resistance (d) Low no-load current
**Ans: (a)** — Magnetizing reactance draws large lagging reactive current.
**Concept:** No-load current is largely magnetizing (reactive) → low pf.
**Twist:** Same reason makes SC-test pf high (winding R dominates) and OC-test pf low; adding core gap worsens pf.

**Q29 (HMEWS-15):** In case of power transformer, the no-load current in terms of full load primary current is
(a) 40 to 50% (b) 15 to 30% (c) 30 to 40% (d) 3 to 5%
**Ans: (d)** — Power transformers: I0 ≈ 3–5% of IFL.
**Concept:** No-load current: power transformer 3–5%, distribution transformer 15–30%.
**Twist:** Distribution transformer (poor magnetic circuit) → 15–30%; large air gap → I0 rises toward 30%.

**Q30 (Transco-12):** Single-phase transformer 1:2, purely resistive load, magnetizing current 1A, secondary current 1A (neglect core loss & leakage). Primary current
(a) 1.41 A (b) 2 A (c) 2.24 A (d) 3 A
**Ans: (c)** — I1 = √(Iμ² + (I2/2)²) = √(1 + 4) = √5 = 2.24 A.
**Concept:** I1 = I0 + I′2; I′2 = (N2/N1)·I2; add as phasors (Iμ ⊥ load component).
**Twist:** Turns ratio 1:1 with I2 = 2 A → I1 = √(1+4) = 2.24 A again; purely resistive load → load component in phase, Iμ quadrature.

**Q31 (HMWS-15):** A transformer takes 0.6 A and absorbs 64 W when primary is connected to 200 V, 50 Hz, secondary open. Iron loss component of current
(a) 0.32 (b) 0.43 A (c) 1 A (d) 0.2 A
**Ans: (a)** — Iw = Pi/V1 = 64/200 = 0.32 A.
**Concept:** Iw = Pi/V1 (active component of I0).
**Twist:** Iμ = √(I0² − Iw²) = √(0.36−0.1024) = 0.507 A; V = 100 V → Iw = 0.64 A.

**Q32 (AP Transco-19):** Same setup as Q30 (1:2, resistive, Iμ = 1 A, I2 = 1 A). Primary current
(a) 1.41 A (b) 2 A (c) 2.24 A (d) 3 A
**Ans: (c)** — Same as Q30: √(1² + 2²) = 2.24 A.
**Concept:** I1 = √(Iμ² + I′2²).
**Twist:** If Iμ = 2 A → √(4+4) = 2.83 A; if I2 = 2 A (I′2 = 4 A) → √(1+16) = 4.12 A.

**Q33 (SSC-JE-13):** 100 kVA, 1100/220 V, r1 = 0.1 Ω, r2 = 0.004 Ω. Equivalent resistances referred to HV and LV sides
(a) 2.504 Ω & 0.2 Ω (b) 0.2 Ω & 0.008 Ω (c) 0.10016 Ω & 2.504 Ω (d) 0.008 Ω & 0.10016 Ω
**Ans: (b)** — R01 = r1 + K²r2 = 0.1 + 25×0.004 = 0.2 Ω; R02 = R01/K² = 0.008 Ω.
**Concept:** R01 = R1 + K²R2; R02 = R2 + R1/K²; K = N1/N2 = 5.
**Twist:** Turns ratio 2:1 → R01 = 0.1 + 4×0.004 = 0.116 Ω; refer R02 back → R02 = R01/K².

**Q34 (SSC-JE-SI-14):** A 10 Ω resistive load impedance-matched to a 6250 Ω source by a transformer. Ratio of primary to secondary turns
(a) 10 (b) 15 (c) 20 (d) 25
**Ans: (d)** — N1/N2 = √(6250/10) = √625 = 25.
**Concept:** Impedance matching: R′L = (N1/N2)² RL = Rsource.
**Twist:** Source 2500 Ω → ratio √250 = 15.8 ≈ 16; load 40 Ω, source 1000 Ω → ratio = 5.

**Q35 (Transco-12):** In core type furnace the secondary winding has
(a) No turns (b) More number of turns (c) Less number of turns (d) Equal to primary turns
**Ans: (c)** — Furnace needs large current at low voltage → few secondary turns.
**Concept:** Arc/induction furnace = step-down transformer for high current.
**Twist:** If voltage ratio 10:1 → secondary turns = N1/10; raising secondary turns reduces furnace current.

**Q36 (APEPDCL-19):** When a 50 Hz transformer is operating at 400 Hz, its kVA rating is
(a) Determine by load on secondary (b) Unaffected (c) Reduced to 1/8 (d) Increased to 8 times
**Ans: (d)** — kVA ∝ f (V ∝ f at const Bm) → 400/50 = 8×.
**Concept:** kVA ∝ f (V = 4.44 Bm A f N).
**Twist:** Operated at 25 Hz → derated to half; if voltage held constant while f raised → Bm drops, rating set by current limit (not 8×).

**Q37 (APEPDCL-19):** Transformer (1:1, C in series) fed at V0, output V1. Correct option (neglect Iμ)
(a) V1 < V0 for lagging pf load (b) V1 = V0 for leading pf load (c) V1 > V0 for leading pf load (d) V1 > V0 for lagging pf load
**Ans: (d)** — With lagging (inductive) load, transferred capacitor drop makes V1 > V0.
**Concept:** Series capacitor (negative reactance) transferred to primary; V1 − V0 = −jXc·I·(angle φ).
**Twist:** Leading (capacitive) load → V1 < V0 (option a); pure resistive → V1 depends only on IXc.

**Q38 (SSC-JE-11):** Core loss is 46 W at 50 Hz and 80 W at 70 Hz at same peak flux density. Hysteresis and eddy loss at 60 Hz
(a) 11 W, 20 W (b) 30 W, 45 W (c) 16 W, 30 W (d) 22 W, 40 W
**Ans: (d)** — Solve Pi = Af + Bf²: A = 0.3628, B = 0.0111 → Ph = 21.76 ≈ 22 W, Pe = 39.96 ≈ 40 W.
**Concept:** Iron loss separation: Pi = Ph + Pe = Af + Bf² (Bm const).
**Twist:** At 80 Hz → Ph = 29 W, Pe = 71 W; if Bm not const, Pe ∝ Bm² f² complicates separation.

**Q39 (Transco-SE-12):** The full load copper loss of a transformer is 1600 W. At half-load the copper loss will be
(a) 400 watts (b) 80 watts (c) 1600 watts (d) 6400 watts
**Ans: (a)** — Pcu = x²Pcu(FL) = 0.25×1600 = 400 W.
**Concept:** Pcu ∝ (load)².
**Twist:** At quarter-load → 100 W; at 150% load → 3600 W.

**Q40 (HMWS-12):** A transformer has full-load copper loss of 400 W. Copper loss at half full load
(a) 50 W (b) 200 W (c) 400 W (d) 100 W
**Ans: (d)** — (0.5)²×400 = 100 W.
**Concept:** Pcu ∝ x².
**Twist:** 25% load → 25 W; 120% load → 576 W.

**Q41 (Transco-12):** The low voltage winding of a 400/230 V, 50 Hz transformer is connected to a 25 Hz supply. Supply voltage should be
(a) 230 V (b) 460 V (c) 115 V (d) 65 V
**Ans: (c)** — V/f = const → V2 = 230×(25/50) = 115 V.
**Concept:** V/f = 4.44 Bm A N must be kept const to avoid saturation.
**Twist:** If 230 V kept at 25 Hz → Bm doubles → saturation, high inrush & Iμ; HV side → 200 V.

**Q42 (SSC-JE-12):** Hysteresis losses are present in iron core coil when
(a) The current is unsymmetrical alternating only (b) The current in the coil is d.c. only (c) The current in the coil is sinusoidal only (d) The current in the coil is alternating
**Ans: (d)** — Any alternating current gives hysteresis loss.
**Concept:** Hysteresis loss ∝ f Bm^n; requires cyclic magnetization (any alternating waveform).
**Twist:** Steady dc → no cyclic B–H loop → no hysteresis loss (only static I²R); unsymmetrical ac still has hysteresis.

**Q43 (SSC-JE-12):** Eddy current loss in ferromagnetic core is proportional to
(a) Square root of frequency (b) Frequency (c) Reciprocal of frequency (d) Square of frequency
**Ans: (d)** — Pe ∝ Bm² f² t².
**Concept:** Eddy-current loss ∝ f².
**Twist:** Hysteresis loss ∝ f; doubling f doubles Ph but quadruples Pe.

**Q44 (SSC-JE-12):** Magnetic materials used to prepare permanent magnets should have
(a) Small hysteresis loop (b) High retentivity (c) Low coercive force (d) Steeply rising magnetization curve
**Ans: (b)** — Permanent magnets need high retentivity (residual flux).
**Concept:** Hard magnetic material: high retentivity + high coercivity (wide loop).
**Twist:** Electromagnet core → soft material (small loop, high μ, low coercivity); high coercivity → resists demagnetization.

**Q45 (SSC-JE-12):** In a 1-phase transformer, copper loss at full load is 600 W. At half load it will be
(a) 75 Watts (b) 600 Watts (c) 300 Watts (d) 150 Watts
**Ans: (d)** — (0.5)²×600 = 150 W.
**Concept:** Pcu ∝ x².
**Twist:** Quarter load → 37.5 W; double load → 2400 W.

**Q46 (SSC-JE-12):** If frequency of input voltage is increased keeping the magnitude of the voltage unchanged, then
(a) Both hysteresis and eddy current loss increase (b) Hysteresis increases, eddy decreases (c) Hysteresis increases, eddy unchanged (d) Hysteresis decreases, eddy remains unchanged
**Ans: (d)** — At const V, Bm falls with f: Ph ∝ V^1.6 f^−0.6 (decreases), Pe ∝ V² (unchanged).
**Concept:** V/f rule: raising f lowers Bm.
**Twist:** If flux kept constant while f rises → Ph increases ∝ f, Pe ∝ f²; const V/f (both up) → Pe ∝ f², Ph ∝ f.

**Q47 (SSC-JE-S2-14):** Hysteresis is the phenomenon in the magnetic circuit by which
(a) H lags behind B (b) B lags behind H (c) B and H are always same (d) Setting up a constant flux
**Ans: (b)** — B lags behind H.
**Concept:** Hysteresis: B–H curve; B lags H (trailing loop).
**Twist:** Loop area → energy lost per cycle ∝ Bm^n; silicon reduces area.

**Q48 (HMWS-12):** We can find ____ of the transformer with open circuit test
(a) Copper losses (b) Total equivalent resistances (c) Turns ratio (d) Total equivalent leakage reactance
**Ans: (c)** — OC test gives core loss, shunt parameters and turns ratio.
**Concept:** OC test (one side open, rated V on other) → Pi, I0, R0, X0.
**Twist:** SC test gives copper loss, equivalent R & X (series params); OC at low pf current (Q50).

**Q49 (HMWS-12):** In short circuit test on a transformer, we generally short circuit the
(a) Low voltage winding (b) High voltage winding (c) Either low or high voltage winding (d) Neither low nor high voltage winding
**Ans: (a)** — LV side shorted, reduced voltage on HV side.
**Concept:** SC test: short LV, apply reduced V on HV until rated current flows.
**Twist:** For a 220/2200 V unit → short the 220 V side; if HV shorted and LV supplied → rated current at lower voltage on LV.

**Q50 (Transco-12):** In transformers, which statement is valid?
(a) In OC test, copper losses obtained; in SC test, core losses (b) In OC test, current drawn at high pf (c) In SC test, current at zero pf (d) In OC test, current drawn at low pf
**Ans: (d)** — OC-test current is drawn at low pf.
**Concept:** OC test pf ≈ 0.1–0.3 lag (Iμ dominates); SC test pf ≈ 0.9–1.0 (R dominates).
**Twist:** SC test at unity-type pf → copper loss = Vsc·Isc·Watt-meter reading; OC test gives Pi only.

**Q51 (SSC-JE-12):** Graph of Pi/f vs f: intercept 0.01, slope 0.001. Hysteresis and eddy losses at 100 Hz
(a) 10 W, 50 W (b) 1 W, 5 W (c) 1 W, 10 W (d) 10 W, 100 W
**Ans: (c)** — Pi/f = A + Bf: Ph = Af = 0.01×100 = 1 W; Pe = Bf² = 0.001×10⁴ = 10 W.
**Concept:** Iron-loss separation via Pi/f vs f straight line (slope B, intercept A).
**Twist:** At 50 Hz → Ph = 0.5 W, Pe = 2.5 W; slope 0.002 → Pe = 20 W at 100 Hz.

**Q52 (EPDCL-14):** During short circuit test, the core losses are negligible. This is because
(a) The voltage applied across the HV side is a fraction of its rated voltage and so is the mutual flux (b) The current on the LV side is very small (c) The power factor is high (d) Iron becomes fully saturated
**Ans: (a)** — SC test applies small voltage → small mutual flux → negligible core loss.
**Concept:** Core loss ∝ V² ∝ φ²; SC test V ≈ 5–10% of rated.
**Twist:** OC test conversely at rated V gives full core loss but tiny copper loss; full-load efficiency needs BOTH tests.

**Q53 (ISRO-14):** While conducting short-circuit test on a transformer, the following side is short circuited
(a) High voltage side (b) low voltage side (c) primary side (d) secondary side
**Ans: (b)** — Low voltage side short-circuited.
**Concept:** SC test: short the LV side (rated current at small voltage).
**Twist:** Either winding can be shorted for the test, but convention is LV; supplies at reduced voltage to avoid huge current.

**Q54 (TSTransco-15):** Two identical transformers, iron loss Pi and full-load copper loss Pc, are put to back-to-back test and full load current flows. Total input power
(a) 2Pi (b) Pc (c) Pi + Pc (d) 2(Pi + Pc)
**Ans: (d)** — Sumpner's test total = 2Pi + 2Pc.
**Concept:** Back-to-back (Sumpner's) test: both machines carry full load → 2Pi + 2Pcu.
**Twist:** If only one transformer is tested in Sumpner's... (n/a); at half load current → 2Pi + 2×0.25Pc.

**Q55 (TSNPDCL-15):** From an open circuit test on a transformer, the no-load power factor was determined. Most likely value
(a) 0.9 (b) unity (c) 0.8 (d) 0.4
**Ans: (d)** — No-load pf is very poor, ~0.2–0.3 (lowest given = 0.4).
**Concept:** cosφ0 = Iw/I0, typically 0.1–0.3 lag.
**Twist:** SC-test pf instead → near unity; power transformer I0 3–5% still gives low pf.

**Q56 (TSNPDCL-15):** SC test on 4 kVA, 200/400 V: 15 V, 10 A, 80 W. % regulation at full load unity pf
(a) 2 (b) 4 (c) 1 (d) –2
**Ans: (a)** — %VR@upf = %R = (Pcu/VA)×100 = (80/4000)×100 = 2%.
**Concept:** At unity pf, VR = %R only; Pcu from SC test = full-load copper loss.
**Twist:** At 0.8 lag with %X known → VR = %R(0.8)+%X(0.6); at leading pf VR = %R·cosφ − %X·sinφ.

**Q57 (APEPDCL-19):** The best method to obtain the efficiency of two identical transformers under loading conditions is
(a) Back-to-back test (b) open circuit test (c) Short circuit test (d) no load test
**Ans: (a)** — Back-to-back (Sumpner's) test.
**Concept:** Sumpner's test gives efficiency at ANY load without wasting load power.
**Twist:** For separation of hysteresis & eddy → OC test at two frequencies; for series impedance/regulation → SC test.

**Q58 (AP Transco-19):** Which statement is valid for transformers?
(a) OC test → copper losses, SC test → core losses (b) OC test draws high pf current (c) SC test draws zero pf current (d) OC test draws low pf current
**Ans: (d)** — OC-test current is at low pf.
**Concept:** Same as Q50: OC low pf (Iμ dominates), SC high pf.
**Twist:** SC test current ~rated at 5% V → copper loss measured directly by wattmeter.

**Q59 (EPDCL-10):** In a transformer, all day efficiency
(a) is higher than the full load efficiency (b) is maximum efficiency (c) is lower than the full load efficiency (d) None of these
**Ans: (c)** — All-day (energy) efficiency < full-load efficiency (energy ratio over 24 h).
**Concept:** All-day η = kWh output / kWh input over 24 h; low no-load kWh drags it down.
**Twist:** Transformer running full load 24 h → all-day η = full-load η (Q72); for distribution, iron loss charged 24 h makes all-day η lower.

**Q60 (SSC-JE-10):** Transformer at full load with maximum efficiency; iron loss = 1000 W. Copper loss at half of full-load
(a) 250 W (b) 300 W (c) 400 W (d) 500 W
**Ans: (a)** — Max η at FL → Pi = Pcu(FL) = 1000 W; at half load Pcu = 0.25×1000 = 250 W.
**Concept:** Max efficiency at Pi = x²Pcu(FL).
**Twist:** Max η at 70% load, Pi = 500 W → Pcu(FL) = 500/0.49 = 1020 W; half-load Pcu = 255 W.

**Q61 (SSC-JE-10):** 2 kVA transformer, core loss 46 W at 50 Hz and 80 W at 70 Hz, same peak flux density. Hysteresis and eddy loss at 60 Hz
(a) 500 W (b) 400 W (c) 300 W (d) 275 W
**Ans: (c)** — Given key (source solution refers to max-η: total = 2Pi; printed key (c)).
**Concept:** Iron-loss separation Pi = Af + Bf² (question data identical to Q38).
**Twist:** Actually solving A=0.3628, B=0.0111 gives Ph≈22 W, Pe≈40 W at 60 Hz (as Q38) — verify printed key; at 100 Hz → Ph≈36 W, Pe≈111 W.

**Q62 (SSC-JE-11):** 100 kVA transformer, max efficiency at 80% of full load, total loss under this condition 1000 W. Ohmic loss at full load
(a) 781.25 W (b) 1250 W (c) 1562.5 W (d) 12500 W
**Ans: (a)** — At max η: x²Pcu = Pi = 500 W → Pcu(FL) = 500/0.64 = 781.25 W.
**Concept:** At max η: Pi = Pcu = x²Pcu(FL); total = 2Pi.
**Twist:** Max η at 50% load, total loss 800 W → Pcu(FL) = 400/0.25 = 1600 W; at half load total = Pi + 0.25×1600.

**Q63 (SSC-JE-11):** 40 kVA transformer, core loss 400 W, full-load copper loss 800 W. Fraction of rated load at maximum efficiency
(a) 50% (b) 62.3% (c) 70.7% (d) 100%
**Ans: (c)** — x = √(Pi/Pcu) = √(400/800) = 0.707.
**Concept:** Max η at x = √(Pi/Pcu(FL)).
**Twist:** Pi = Pcu(FL) → x = 1 (full load); Pi = 100 W, Pcu = 400 W → x = 0.5.

**Q64 (AP Genco-12):** A transformer has maximum efficiency at 3/4 of full load. Ratio of iron loss (Pi) and full load copper loss (Pc)
(a) 3/4 (b) 16/9 (c) 9/16 (d) 3/4 (alt)
**Ans: (c)** — Pi/Pc = x² = (3/4)² = 9/16.
**Concept:** Max η: Pi = x² Pc.
**Twist:** Max η at half load → Pi/Pc = 1/4; at 80% load → 16/25.

**Q65 (Transco-12):** 440/110 V, 1-phase transformer, primary resistance 0.03 Ω, iron loss 150 W. Secondary current at which maximum efficiency occurs
(a) 63.56 A (b) 70.28 A (c) 82.80 A (d) 46.39 A
**Ans: (c)** — R02 = r2 + (110/440)²×0.03 = 0.0218 Ω; I2 = √(Pi/R02) = √(150/0.0218) = 82.8 A.
**Concept:** I2 = √(Pi/R02); R02 = R2 + R1/K².
**Twist:** r1 = 0.12 Ω → R02 = 0.0275, I2 = 73.8 A; Pi = 300 W → I2 = 117 A.

**Q66 (Transco-12):** 50 kVA, iron loss 500 W, full-load copper 800 W. Efficiency at full load 0.8 pf lagging (%)
(a) 92 (b) 89.56 (c) 96.85 (d) 79.82
**Ans: (c)** — η = 40/(40+0.5+0.8) = 96.85%.
**Concept:** η = x·S·cosφ / (x·S·cosφ + Pi + x²Pcu).
**Twist:** At half load (x=0.5) → η = 20/(20+0.5+0.2) = 96.6%; unity pf → η = 97.5%.

**Q67 (HMWS-12):** Transformer efficiency 85%, works at 100 V, 4 kVA, secondary 200 V. Primary current
(a) 40 A (b) 30 A (c) 20 A (d) 10 A
**Ans: (a)** — I1 = kVA×1000/V1 = 4000/100 = 40 A (source ignores η in this step).
**Concept:** V1I1 = V2I2 (kVA basis); actual input = output/η.
**Twist:** Including η: I1 = Pout/(ηV1) = 4000/(0.85×100) = 47 A; with secondary current = 4 kVA/200 = 20 A.

**Q68 (EPDCL-14):** The efficiency of a power transformer at relatively light loads is quite low. This is due to
(a) Small copper losses (b) Small secondary output (c) High fixed loss in comparison to the output (d) Poor power factor
**Ans: (c)** — Fixed iron loss dominates at light load.
**Concept:** η = 1/(1 + loss/output); iron loss fixed → loss/output high at light load.
**Twist:** At very heavy load copper loss dominates (Pcu ∝ x²) → η drops again; max η where the two cross.

**Q69 (EPDCL-14):** A 2 kVA transformer has iron loss 150 W and full-load copper loss 250 W. Maximum efficiency occurs when total loss is
(a) 500 W (b) 400 W (c) 300 W (d) 100 W
**Ans: (c)** — Total loss at max η = 2Pi = 300 W.
**Concept:** At max η total loss = 2Pi (= 2×Pcu at that load).
**Twist:** Pi = 200 W → total = 400 W; load fraction x = √(150/250) = 0.775.

**Q70 (HMWS-15):** A transformer has at full-load iron loss 900 W and copper loss 1600 W. It will have maximum efficiency at a load of
(a) 66.6% (b) 125% (c) 75% (d) 13.3%
**Ans: (c)** — x = √(900/1600) = 0.75.
**Concept:** x = √(Pi/Pcu(FL)).
**Twist:** Pi = 400 W, Pcu = 1000 W → x = 0.632; max η at 125% load means Pi = 1.5625×Pcu.

**Q71 (TSSPDCL-15):** At full-load iron loss and copper loss are 3000 W and 4000 W. Total loss at maximum efficiency
(a) 7000 W (b) 6000 W (c) 8000 W (d) 4000 W
**Ans: (b)** — Total at max η = 2Pi = 6000 W.
**Concept:** Total loss at max η = 2Pi (independent of Pcu(FL)).
**Twist:** Pi = 4000, Pcu = 3000 → total at max η = 8000 W; the max-η load = √(Pi/Pcu).

**Q72 (TSSPDCL-15):** A transformer operates 24 hours a day at full load. Its full-load efficiency is
(a) Equal to all day efficiency (b) More than all day efficiency (c) Less than all day efficiency (d) Equal to maximum efficiency
**Ans: (a)** — Constant full load all day → all-day η = full-load η.
**Concept:** All-day η = energy out/in over 24 h; if loaded full 24 h → equals FL η.
**Twist:** Idle 12 h at no load → all-day η < FL η (iron kWh charged while idle); lightly loaded day → much lower.

**Q73 (AP Transco-19):** No-load loss 64 W (OC test). SC test at 90% rated current gives 81 W. Transformer shows maximum efficiency at
(a) 50.0% (b) 64.0% (c) 80.0% (d) 88.8% of rated current
**Ans: (d)** — Given key: x = √(Pi/Pcu@90%×0.81) = √(64/81) = 0.8888.
**Concept:** Pcu(FL) = 81/0.81 = 100 W; x = √(Pi/Pcu(FL)).
**Twist:** Correct math gives x = √(64/100) = 0.8 (option c) — source key uses 81; if SC loss at 90% is 81 W the FL copper loss is 100 W → 80%.

**Q74 (APGenco-12):** Single-phase transformer R = 0.2 pu, X = 0.6 pu. pu voltage regulation at 0.8 pf lagging
(a) 0.52 (b) 0.42 (c) 0.62 (d) 0.36
**Ans: (a)** — VR = R·cosφ + X·sinφ = 0.2×0.8 + 0.6×0.6 = 0.52.
**Concept:** VR(pu) = Rpu cosφ ± Xpu sinφ.
**Twist:** 0.8 pf leading → VR = 0.16 − 0.36 = −0.2 (negative); unity pf → VR = 0.2.

**Q75 (Transco-SE-12):** A transformer can have regulation closer to zero on
(a) Lagging power factor (b) Leading power factor (c) Zero power factor (d) Unity power factor
**Ans: (b)** — Leading pf load can give near-zero (even negative) regulation.
**Concept:** VR = R cosφ − X sinφ (leading) can vanish when R cosφ = X sinφ.
**Twist:** Exact zero requires tanφ = R/X at leading pf; lagging pf always gives positive VR (Q147).

**Q76 (Transco-2):** In a transformer, zero voltage regulation at full load is
(a) Not possible (b) Possible at unity power factor load (c) Possible at leading power factor load (d) Possible at lagging power factor load
**Ans: (c)** — Zero VR possible at a leading pf load.
**Concept:** VR = Rcosφ − Xsinφ = 0 → leading pf.
**Twist:** Zero VR at tanφ = R/X leading; at lagging pf VR is always > 0.

**Q77 (APSPDCL-14):** 3.3 kV/400 V, single-phase transformer needs 330 V for full-load current at φsc = 75°. Voltage regulation at full load, 0.707 lagging
(a) 4.33% (b) 8.66% (c) 16.2% (d) 14.3%
**Ans: (b)** — Zpu = 330/3300 = 0.1; Rpu = 0.1cos75°=0.0259, Xpu = 0.1sin75°=0.0966; VR = (0.0259+0.0966)×0.707 ≈ 0.085 → ~8.5–8.66%.
**Concept:** VR = Rpu cosφ + Xpu sinφ; R & X from SC-test data.
**Twist:** 0.707 leading → VR = (0.0259−0.0966)×0.707 ≈ −0.05 (−5%); unity pf → 2.59%.

**Q78 (HMWS-15):** A transformer has % resistance 1% and % reactance 4%. Its voltage regulation at 0.8 pf lagging and 0.8 pf leading
(a) 4.8% and −1.6% (b) 3.2% and −1.6% (c) 3.2% and −3.2% (d) 2.4% and −0.8%
**Ans: (b)** — Lag: 1×0.8+4×0.6 = 3.2%; Lead: 1×0.8−4×0.6 = −1.6%.
**Concept:** VR% = %R cosφ ± %X sinφ (sign − for leading).
**Twist:** 0.6 pf lag → 1×0.6+4×0.8 = 3.8%; 0.6 lead → −2.6%.

**Q79 (TSTransco-15):** A transformer has negative voltage regulation when its load power factor is
(a) Zero (b) Unity (c) Leading (d) Lagging
**Ans: (c)** — Leading pf gives negative VR.
**Concept:** VR = R cosφ − X sinφ < 0 for leading load.
**Twist:** Heavily lagging load → largest positive VR; capacitive (leading) → secondary voltage exceeds no-load value.

**Q80 (APGenco-17):** Condition for maximum regulation of a single-phase transformer with equivalent resistance req, reactance xeq and load pf angle φ
(a) cosφ = req/xeq (b) cosφ = xeq/req (c) tanφ = req/xeq (d) tanφ = xeq/req
**Ans: (d)** — d(VR)/dφ = 0 → tanφ = xeq/req.
**Concept:** VR = req cosφ + xeq sinφ; max at tanφ = xeq/req (lagging).
**Twist:** Max VR magnitude = √(req² + xeq²); zero VR at tanφ = req/xeq (leading).

**Q81 (APTransco-19):** 100 kVA, 1000/100 V, 50 Hz transformer, 5% series-impedance drop, 3% due to resistance. % regulation at full load 0.8 lagging
(a) 4.8 (b) 6.8 (c) 8.8 (d) 10.8
**Ans: (a)** — %X = √(5²−3²) = 4%; VR = 3×0.8 + 4×0.6 = 4.8%.
**Concept:** %X = √(%Z²−%R²); VR = %R cosφ + %X sinφ.
**Twist:** 0.8 leading → 3×0.8 − 4×0.6 = 0%; 0.9 lag → 3×0.9+4×0.436 = 4.44%.

**Q82 (APSPDCL-19):** Single-phase transformer R = 0.1 pu, X = 0.4 pu. Voltage regulation at full load 0.8 pf lag
(a) 16% (b) 32% (c) 25% (d) 30%
**Ans: (b)** — VR = 0.1×0.8 + 0.4×0.6 = 0.32 = 32%.
**Concept:** VR(pu) = Rpu cosφ + Xpu sinφ.
**Twist:** 0.6 lag → 0.08+0.32 = 0.40 (40%); leading 0.8 → 0.08−0.24 = −0.16.

**Q83 (TSTransco-15):** The inrush current of a transformer at no load is maximum if the supply voltage is switched on
(a) at peak voltage value (b) at zero voltage value (c) at half voltage value (d) at 0.866 time voltage value
**Ans: (b)** — Switching at voltage zero gives max inrush.
**Concept:** Inrush peak when switch-on instant is at zero crossing of voltage (worst residual flux alignment).
**Twist:** Switch at peak voltage → minimum inrush; residual flux opposite polarity adds to worst inrush.

**Q84 (TSSPDCL-15):** The phase difference between any two successive third harmonic voltages in a 3-ϕ transformer is
(a) zero radians (b) π/2 radians (c) π/3 radians (d) 2π/3 radians
**Ans: (a)** — All 3rd harmonics are in phase (zero-sequence).
**Concept:** Triplen (3rd) harmonics are zero-sequence → 0° apart.
**Twist:** Fundamental sequence displacement is 120° (2π/3); 5th harmonic displacement = 5×120° = 600° ≡ 240°.

**Q85 (TSNPDCL-15):** Statements: (1) Magnetizing current in 1-ϕ transformer is sinusoidal (2) Magnetizing currents in 3-ϕ supply lines are sinusoidal (3) In 1-ϕ transformer magnetizing current is non-sinusoidal but induced voltages are sinusoidal.
(a) 1 and 3 (b) 2 only (c) 2 and 3 (d) 1 only
**Ans: (c)** — (1) wrong; 1-ϕ Iμ has 3rd harmonic (non-sinusoidal); (2) & (3) correct.
**Concept:** 3rd-harmonic magnetizing current in 1-ϕ; in 3-ϕ delta/star line currents cancel triplens.
**Twist:** Y-Y without delta → third-harmonic distortion in voltage; Δ-winding provides circulating path for 3rd harmonic.

**Q86 (APGenco-12):** Connection of three single-phase transformer bank (two secondaries per phase) results in
(a) 3-phase to 2-phase conversion (b) 3-phase to 3-phase conversion (c) 2-phase to 3-phase conversion (d) 3-phase to 6-phase conversion
**Ans: (d)** — Double-secondary bank → 3-ϕ to 6-ϕ conversion.
**Concept:** 6 output windings phase-shifted by 60° → 6-phase rectifier supply.
**Twist:** Scott connection → 3-ϕ to 2-ϕ; zig-zag gives neutral for unbalanced loads.

**Q87 (Transco-12):** Which of the following transformers should never have the secondary open circuited, while the primary is energized?
(a) Power transformer (b) Potential transformer (c) Current transformer (d) Auto transformer
**Ans: (c)** — CT secondary open → very high induced voltage (insulation/arc hazard).
**Concept:** CT operates at short-circuit conditions; opening secondary removes load from flux path → huge emf.
**Twist:** PT secondary open is safe (like normal transformer); PT secondary short → high current hazard.

**Q88 (APSPDCL-12):** A 230/2300 V, Y/Δ 3-phase transformer rated 230 kVA. Its rated secondary current/phase
(a) 33.33 A (b) 133.33 A (c) 66.66 A (d) 30.33 A
**Ans: (a)** — Secondary Δ: Iph = S/(3·Vph) = 230k/(3×2.3k) = 33.33 A.
**Concept:** Δ connection: line = √3·phase; kVA = 3·Vph·Iph.
**Twist:** Secondary Y (if flipped) → line current = S/(√3×2300) = 57.7 A; primary Y line current = 230k/(√3×230) = 577 A.

**Q89 (SSC-JE-12):** 3-ϕ transformer, primary Δ, secondary Y, per-phase turns ratio 6, primary line voltage 200 V. Secondary voltage
(a) 693 V (b) 1200 V (c) 58 V (d) 2078 V
**Ans: (d)** — E2(phase) = 6×200 = 1200 V; line = √3×1200 = 2078 V.
**Concept:** Phase ratio N2/N1 = 6; line V scales with √3 in Y.
**Twist:** If turns ratio is line-to-line based → careful; Δ-Y with ratio 6 gives 2078 V, Y-Δ with ratio 6 gives V2 = 6×200/√3 = 693 V.

**Q90 (SSC-JE-SI-14):** A delta-star transformer has phase-to-phase voltage transformation ratio a:1 [delta phase : star phase]. The line-to-line voltage ratio of star–delta is given by
(a) √3/a (b) √3a (c) 3/a (d) a
**Ans: (b)** — V2(LL)/V1(LL) = √3·(E2/E1) = √3·a.
**Concept:** Y-Δ: line ratio = √3 × phase ratio (secondary Y line = √3·E2).
**Twist:** Δ-Y (swap sides) → ratio = a/√3; if phase ratio is 1:a → line ratio = √3/a.

**Q91 (SSC-JEE-S2-14):** If K is the phase-to-phase voltage ratio, the line-to-line voltage ratio in a 3-phase Y-Δ transformer is
(a) K (b) K/√3 (c) √3 K (d) √3/K
**Ans: (c)** — Line-to-line ratio = √3 × phase ratio = √3K.
**Concept:** Y-Δ: line ratio = √3·(phase ratio).
**Twist:** Δ-Y → line ratio = K/√3; Y-Y or Δ-Δ → line ratio = K.

**Q92 (TSNPDCL-15):** Star-delta connected 3-ϕ transformer, 11 kV on star side, line current 20 A, per-phase turns ratio 11. Secondary line voltage and line current
(a) 577 V, 381 A (b) 550 V, 220 A (c) 635 V, 381 A (d) 1 kV, 220 A
**Ans: (a)** — E2 = (1/11)(11 kV/√3) = 577 V; I2 = (11 kV/577 V)×20 = 381 A.
**Concept:** Phase EMF divides by turns ratio; kVA conserved (√3·VL·IL).
**Twist:** Turns ratio 10 → V2 = 635 V, I2 = 381 A? (recompute: E2 = 11k/√3/10 = 635 V, I2 = 11k/0.635k×20 = 346 A); Δ-Y bank → different V/I.

**Q93 (APGenco-17):** The main application of delta/zig-zag connected 3-phase transformer is to supply
(a) Balanced loads (b) Unbalanced loads (c) Furnace loads (d) Single phase loads
**Ans: (b)** — Δ/zig-zag gives a neutral for unbalanced loads with balanced voltages.
**Concept:** Zig-zag secondary suppresses zero-sequence impedance → good for unbalanced/single-phase loads.
**Twist:** Δ-Δ → supplies balanced 3-ϕ loads; star-star → third-harmonic voltage distortion (no delta path).

**Q94 (APEPDCL-19):** In Y/Δ connection, with respect to phase difference from primary to secondary, possible ways
(I) ±30° Y/Δ (II) ±60° (III) ±90°
(a) (I) and (III) are possible (b) (I) is only possible (c) (II) and (III) are possible (d) (I) and (II) are possible
**Ans: (b)** — Only ±30° displacement is possible for Y-Δ.
**Concept:** Y-Δ phase shift is always a multiple of 30° (vector groups like Yd1, Yd11).
**Twist:** Y-Y → 0°; Δ-Δ → 0°; Y-Δ standard groups: +30° (Yd1) or −30° (Yd11).

**Q95 (HMWS-12):** In a 3-phase delta-delta transformer, one phase has burnt up. The transformer will then supply
(a) Zero output (b) Rated output (c) 56.7% of its rated output (d) 86.6% of its rated output
**Ans: (c)** — Open delta delivers 57.7% of Δ-Δ rating.
**Concept:** V-V (open delta): capacity = 0.577 × Δ-Δ; each unit carries line current.
**Twist:** Two of three transformers → 57.7%; reconnecting V-V back to Δ-Δ raises capacity by 73.2% (Q97).

**Q96 (ISRO-14):** In a three-phase delta transformer bank one phase burns up. The transformer will supply
(a) 57.7% of its rating (b) Zero output (c) 63% of its output rating (d) At full output rating
**Ans: (a)** — Open-delta capacity = 57.7%.
**Concept:** One unit removed → open delta, 1/√3 of capacity.
**Twist:** Two identical Δ-Δ banks with one unit lost each → still 57.7% per bank; voltage ratio held.

**Q97 (APTransco-17):** When a V-V three-phase transformer system is converted into a Δ-Δ system, increase in capacity of the system is
(a) 86.6% (b) 50% (c) 57.7% (d) 73.2%
**Ans: (d)** — Δ-Δ = 1.732 × V-V → increase 73.2%.
**Concept:** kVA(Δ-Δ) = √3·kVA(V-V).
**Twist:** Adding the third unit raises rating by 73.2%; conversely removing one drops it to 57.7%.

**Q98 (ISRO-14):** In Scott-connection, if the ratio of the main transformer is 'K', then the teaser transformer has transformation ratio of
(a) 2K/√3 (b) √3K/2 (c) K/√3 (d) K/2
**Ans: (a)** — Teaser ratio = 0.866×K = (√3/2)K (given key as 2K/√3 arrangement).
**Concept:** Scott (T) connection: teaser on 86.6% tap → ratio 0.866 of main.
**Twist:** Main 1:1 → teaser 0.866:1; main K:1 → teaser 0.866K:1; used for 3-ϕ to 2-ϕ (two-phase) conversion.

**Q99 (APGenco-12):** A 25 kVA, 2000/200 V two-winding transformer connected as autotransformer (2000 V → 2200 V, fig). Full-load kVA of the connection
(a) 125 kVA (b) 275 kVA (c) 375 kVA (d) 175 kVA
**Ans: (b)** — VA_AT = 25/(1−K), K = LV/HV = 2000/2200 = 10/11 → 25/(1/11) = 275 kVA.
**Concept:** Autotransformer rating = S(1/1−K); K = LV/HV.
**Twist:** Step-up to 2400 V (K = 2000/2400 = 5/6) → VA = 150 kVA; step-down 2200/200 (K = 1/11) → VA = 27.5 kVA.

**Q100 (APSPDCL-12):** The apparent disadvantage of auto transformer as compared to two-winding transformers
(a) Power rating is greater (b) Efficiency is low (c) Conductive isolation is not present (d) Voltage regulation is low
**Ans: (c)** — No galvanic isolation (electrical connection between windings).
**Concept:** Autotransformer disadvantage: no isolation, high short-circuit current (low impedance).
**Twist:** Benefit → higher kVA rating for same copper; risk → fault current larger (lower leakage impedance).

**Q101 (SSC-JE-12):** An autotransformer used with a sodium vapour lamp should have high
(a) Leakage reactance of windings (b) VA rating (c) Transformation ratio (d) Winding resistance
**Ans: (a)** — High leakage reactance limits lamp current (ballast action).
**Concept:** Leakage reactance acts as series ballast to limit/ignite lamp current.
**Twist:** If a resistive ballast used instead → higher loss; a separate choke (high inductance) also works.

**Q102 (SSC-JE-12):** In an auto-transformer, primary winding turns 210, secondary 140. Input current 60 A. Currents in output and in common winding
(a) 40 A, 100 A (b) 90 A, 30 A (c) 90 A, 150 A (d) 40 A, 20 A
**Ans: (b)** — I2 = I1×(N1/N2) = 60×210/140 = 90 A; common = I2 − I1 = 30 A.
**Concept:** Amp-turn balance N1I1 = N2I2; common-winding current = difference.
**Twist:** Step-up (output 210, common 140): Iout = I1×(140/210) = 40 A, common = I1−Iout = 20 A; turns ratio 2:1 → Iout = 120 A, common = 60 A.

**Q103 (EPDCL-14):** In an auto-transformer, power is transferred through
(a) Conduction process only (b) Induction process only (c) Both Conduction and Induction processes (d) Mutual coupling
**Ans: (c)** — Power transferred by both conduction and induction.
**Concept:** Series (common) part transfers conductivity, shunt part inductively.
**Twist:** Inductive share = (1−K); conductive share = K; two-winding → induction only.

**Q104 (ISRO-14):** In an auto-transformer, power is transferred through
(a) Conduction process only (b) Induction process only (c) Both Conduction and Induction processes (d) Mutual coupling
**Ans: (c)** — Both conduction and induction.
**Concept:** Same as Q103.
**Twist:** Fraction transferred conductively = K (= V2/V1); induction fraction = (1−K).

**Q105 (SSC-JE-82-14):** In an autotransformer of voltage ratio V1/V2 (V1 > V2), the fraction of power transferred inductively is proportional to
(a) V1/(V1+V2) (b) V2/V1 (c) (V1−V2)/(V1+V2) (d) (V1−V2)/V1
**Ans: (d)** — P_inductive = (1−K) = (V1−V2)/V1.
**Concept:** P_inductive/P_total = 1 − V2/V1; P_conductive = V2/V1.
**Twist:** V2/V1 = 0.7 → inductive = 30%; conductivity transferred = 0.7 (Q108).

**Q106 (HMWS-15):** A 100 V/10 V, 50 VA transformer is converted to 100 V/110 V autotransformer. Rating of the autotransformer
(a) 100 VA (b) 500 VA (c) 110 VA (d) 550 VA
**Ans: (d)** — K = 100/110 = 10/11; VA_AT = 50/(1/11) = 550 VA.
**Concept:** VA_AT = S(2-wdg)/(1−K).
**Twist:** Converted to 100 V/120 V (K = 5/6) → 300 VA; step-down 110 V/10 V (K = 1/11) → 55 VA.

**Q107 (AP Genco-17):** 1100 kVA, 11 kV/1.1 kV two-winding transformer connected as 12.1 kV/11 kV step-down autotransformer. Rating of auto transformer
(a) 1000 kVA (b) 1100 kVA (c) 11000 kVA (d) 12100 kVA
**Ans: (d)** — K = 11/12.1 = 10/11; VA = 1100/(1/11) = 12100 kVA.
**Concept:** VA_AT = S/(1−K); K = LV/HV of autotransformer.
**Twist:** Used as 12.1 kV/1.1 kV (K = 1/11) → 1210 kVA; as 12.1/11 step-down, copper saving = (1−1/K) = 9%.

**Q108 (AP Transco-17):** A 3-kW load is supplied by an autotransformer with 0.7 transformation ratio. Conductively transferred power from primary to secondary
(a) 2.1 kW (b) 0.9 kW (c) 4.29 kW (d) 3 kW
**Ans: (a)** — P_cond = K×P = 0.7×3 = 2.1 kW.
**Concept:** P_conductive = K·P_total; P_inductive = (1−K)·P.
**Twist:** K = 0.5 → P_cond = 1.5 kW; K = 0.9 → P_cond = 2.7 kW, inductive = 0.3 kW.

**Q109 (TSSPDCL-18):** 2200/220 V, 22 kVA transformer, total losses 1 kW at full load unity pf. Reconnected as autotransformer 2200 V → 1980 V. Efficiency at full load, unity pf
(a) 0.965 (b) 0.995 (c) 0.97 (d) 0.927
**Ans: (b)** — Auto output = 1980×100 = 198 kW; η = 198/(198+1) = 0.995.
**Concept:** Auto full-load current = 22k/220 = 100 A; same loss, far larger output.
**Twist:** If losses doubled → η = 198/200 = 0.99; step-up to 2420 V → output 242 kW → η ≈ 0.996.

**Q110 (APEPDCL-19):** A 2:1 ratio two-winding transformer is connected as an auto transformer. Its kVA rating as auto vs two-winding
(a) 3 times (b) the same (c) 1.5 times (d) 2 times
**Ans: (a)** — K = N1/(N1+N2) = 2/3 → VA_AT = S/(1−2/3) = 3×S.
**Concept:** For 2:1 (step-down as auto step-up), K = 2/3 → 3× rating.
**Twist:** 1:1 ratio → K = 1/2 → 2× rating; 3:1 → K = 3/4 → 4× rating.

**Q111 (APSPDCL-19):** Auto transformer made from two-winding transformer with turns ratio N1/N2 = α. Ratio of magnetizing current of auto to two-winding transformer
(a) (α−1)/α (b) α/(α−1) (c) (α²−1)/α (d) α/(α²−1)
**Ans: (b)** — Iμ(auto)/Iμ(2wdg) = N1/(N1−N2) = α/(α−1).
**Concept:** Same flux needs same ampere-turns on effective turns: (N1−N2)·Iμ2 = N1·Iμ1.
**Twist:** Series additive polarity → N1/(N1+N2) = α/(α+1); α = 2 → ratio 2 (subtractive) or 2/3 (additive).

**Q112 (EPDCL-10):** Two transformers with leakage impedances Z1 = 0.1+j0.4 pu, Z2 = 0.05+j0.2 pu connected in parallel. Ratio of loads shared
(a) equal (b) 1:2 (c) 2:1 (d) 2:3
**Ans: (b)** — S1/S2 = Z2/Z1 = (0.05+j0.2)/(0.1+j0.4) = 1/2 → 1:2.
**Concept:** Parallel sharing: S ∝ 1/Z; S1/S2 = Z2/Z1.
**Twist:** Same pu impedance (Z2 = Z1) → share equally (Q115); Z1:Z2 = 2:1 on same base → S1:S2 = 1:2.

**Q113 (TSGenco-15):** An additional condition for parallel operation of three-phase transformers over single-phase transformers is that
(a) The transformers should belong to the same vector group (b) Ratios of winding resistance to reactance should be equal (c) The transformers should have same kVA ratings (d) They should not belong to the same vector group
**Ans: (a)** — Same vector group is the extra 3-ϕ requirement.
**Concept:** 3-ϕ parallel: same vector group (phase displacement) plus all 1-ϕ conditions.
**Twist:** Yd1 vs Yd11 → circulating currents; unequal X/R ratio → unequal load sharing though pu Z equal.

**Q114 (TSSPDCL-15):** Two 3-ϕ transformers cannot be operated in parallel if their
(a) kVAs are different (b) phase sequences are different (c) % impedances are different (d) Voltage ratios are different
**Ans: (b)** — Opposite phase sequence → catastrophic circulating currents.
**Concept:** Same phase sequence is a hard condition for parallel operation.
**Twist:** Different % impedance → load not shared per rating (but still operable); different kVA is allowed.

**Q115 (AP Genco-17):** Two transformers having the same pu impedance connected in parallel share the connected load
(a) Equally (b) In proportion to the respective ratings (c) In proportion to the voltage ratio (d) In proportion to the zero-phase displacement
**Ans: (a)** — Same pu Z on their own bases → equal sharing.
**Concept:** S1/S2 = Z2(pu)/Z1(pu); equal pu Z → S1 = S2.
**Twist:** Different ratings with same pu Z → share in proportion to ratings; same kVA, different pu Z → share inversely to Z.

**Q116 (TSSPDCL-18):** Statements: (1) Primary ampere-turns are significantly more than secondary ampere-turns (2) Flux in core stays the same for no-load and full-load (3) Two transformers in parallel, greater leakage impedance shares more load.
(a) 1 and 2 (b) 2 only (c) 1 and 3 (d) 3 only
**Ans: (b)** — (1) wrong: N1I1 ≈ N2I2 (balance); (3) wrong: higher leakage Z shares LESS load.
**Concept:** Ampere-turn balance; flux fixed by applied voltage; parallel sharing ∝ 1/Z.
**Twist:** Higher impedance unit carries less load; equal pu Z → proportional sharing.

**Q117 (APPSC-19):** MMF required to produce flux of 1 mWb in a 100-turn magnetic circuit is 50 AT. If turns doubled and current reduced by 50%, flux produced will be
(a) 2 mWb (b) 1 mWb (c) 0.5 mWb (d) 2.5 mWb
**Ans: (b)** — MMF = NI unchanged (2N×I/2 = NI) → flux constant = 1 mWb.
**Concept:** φ = MMF/R; flux depends on MMF and reluctance only.
**Twist:** Current halved without turns change → φ = 0.5 mWb; turns doubled, current same → φ = 2 mWb.

**Q118 (APPSC-19):** Reluctance of flux path is 2000 AT/Wb. Length reduced by 50% and area increased by 50%. New reluctance
(a) three times (b) one third (c) twice (d) half
**Ans: (b)** — R ∝ l/A → Rnew = (0.5/1.5)×R = R/3.
**Concept:** R = l/(μA); R ∝ l/A.
**Twist:** Length halved, area same → R/2; length doubled, area halved → 4R.

**Q119 (APPSC-19):** Core with relative permeability μr, length l m, N turns, current I. Flux density produced (Wb/m²)
(a) μ0μr l/NI (b) μ0 NIl/μr (c) NI/(μ0μr l) (d) μ0μr NI/l
**Ans: (d)** — B = φ/A = NI/(R·A) = μ0μr·N·I/l.
**Concept:** B = μH = μ0μr(NI/l).
**Twist:** Air core (μr = 1) → B = μ0NI/l; length doubled → B halved.

**Q120 (APPSC-19):** Flux linked with a single-turn coil φ = 6t² + 4t + 6. EMF induced in the coil in the fourth second
(a) 12 V (b) 52 V (c) 24 V (d) 6 V
**Ans: (a)** — Given key (source solution computes e = dφ/dt = 12t+4 at t=4 → 52 V, option b — key/option mismatch).
**Concept:** e = −dφ/dt; e(t) = 12t + 4.
**Twist:** Standard working: e(4) = 52 V (option b); average emf over 3–4 s = [φ(4)−φ(3)]/1 = 46 V; if φ = 3t² → e = 6t.

**Q121 (HMWS-2020):** Full-load voltage drops due to resistance and leakage reactance are 2% and 4%. Full-load copper loss equals iron loss. Efficiency at half-load, unity pf
(a) 95% (b) 92% (c) 97% (d) 94%
**Ans: (a)** — η = 0.5/(0.5+0.02+0.25×0.02) = 0.9523.
**Concept:** Rpu = %R/100 = 0.02 = Pi(pu) = Pcu(FL)(pu); η = x/(x+Pi+x²Pcu).
**Twist:** Full-load unity pf → η = 1/(1+0.04) = 96.15%; if Pi = 0.03 → half-load η = 0.5/0.53875 = 92.8%.

**Q122 (HMWS-2020):** 100 kVA, 2000/200 V two-winding used as autotransformer stepping 2000 V → 2200 V. Ratio of full-load losses (auto : two-winding)
(a) 1:11 (b) 11:10 (c) 10:11 (d) 1:10
**Ans: (a)** — Same W loss but VA rises 100 → 1100 kVA → pu loss ratio = 100/1100 = 1/11.
**Concept:** Loss magnitude unchanged; per-unit loss drops as rating rises (Loss/VA_AT).
**Twist:** Step-up to 2400 V (K = 5/6) → VA_AT = 600 kVA → pu ratio = 100/600 = 1/6; step-down 2200/2000 → 1100 kVA.

**Q123 (HMWS-2020):** True statements for delta-delta connected 3-phase transformer: (i) cross-section of each turn is small (ii) windings require more turns (iii) can be used for small H.V. transformers (iv) non-uniform loads
(a) (ii), (iii) and (iv) (b) (i), (iii) and (iv) (c) (i), (ii) and (iii) (d) (i), (ii) and (iv)
**Ans: (d)** — (i) phase current = 57.7% of line → small conductor; (ii) phase voltage = line → more turns; (iii) false (Δ-Δ used for LV/high-current); (iv) true.
**Concept:** Δ-Δ: Iph = IL/√3, Vph = VL → small current, many turns; Y-Δ for HV.
**Twist:** Star winding → fewer turns, larger conductor (Iph = IL); Δ winding at HV end is not preferred (insulation cost).

**Q124 (SSC-JE-20):** Which is the CORRECT expression of magnetic reluctance?
(a) l/H (b) B/H (c) φ/Fm (d) Fm/φ
**Ans: (d)** — R = Fm/φ (MMF/flux).
**Concept:** R = l/(μA) = Fm/φ (Ohm's law for magnetic circuits).
**Twist:** Permeance = φ/Fm = μA/l; R in parallel → total reluctance reduces.

**Q125 (SSC-JE-20):** MMF (Amp-turns) produced in a magnetic circuit with 60 turns carrying 0.5 A
(a) 10 (b) 20 (c) 30 (d) 40
**Ans: (c)** — MMF = NI = 60×0.5 = 30 AT.
**Concept:** F = NI (amp-turns).
**Twist:** 100 turns at 0.2 A → 20 AT; 50 turns at 0.8 A → 40 AT.

**Q126 (SSC-JE-20):** Magnitude of induced EMF in a coil if current changes from +2 A to −2 A in 0.5 s, mutual induction coefficient 0.5
(a) 2 (b) 4 (c) 3 (d) 6
**Ans: (b)** — E = M·dI/dt = 0.5×(4/0.5) = 4 V.
**Concept:** e2 = M·di1/dt.
**Twist:** M = 0.25 → 2 V; change over 1 s → 2 V; current 0 to −4 A in 0.25 s → 8 V.

**Q127 (SSC-JE-20):** Self-inductance (mH) of a 4 m long air-cored solenoid, cross-section 0.02 m², 60 turns
(a) 0.064 (b) 0.036 (c) 0.045 (d) 0.023
**Ans: (d)** — L = μ0N²A/l = 4π×10⁻⁷×3600×0.02/4 = 2.26×10⁻⁵ H ≈ 0.023 mH.
**Concept:** L = N²/R = μ0μr N²A/l.
**Twist:** Length 2 m → L = 0.045 mH; 120 turns → L = 0.09 mH (×4).

**Q128 (SSC-JE-20):** Tapings of a transformer are provided
(a) at the phase end of LV side (b) at the phase end of HV side (c) at the neutral side end of HV side (d) at the middle of HV side
**Ans: (d)** — Taps on middle of HV winding.
**Concept:** HV winding has many turns → fine voltage control; middle → balanced mechanical forces.
**Twist:** Taps on LV → coarse, high-current switching; HV neutral-end taps → simpler insulation at neutral.

**Q129 (SSC-JE-20):** In an auto transformer a part of energy transfer is through
(a) convection process (b) conduction process (c) induction process (d) radiation process
**Ans: (—)** — Source key gives "(-)" (no answer printed); standard answer: (b) conduction (plus induction).
**Concept:** Auto transformer transfers power by both conduction and induction (Q103/104).
**Twist:** Two-winding transformer → induction only; conduction share = K, induction share = 1−K.

**Q130 (SSC-JE-20):** Voltage regulation of transformer is given by
(a) (E² − V²)/V² (b) (E2 − V2)/E2 (c) (V2 − E2)/E2 (d) (V2 − E2)/V2
**Ans: (b)** — VR = (E2 − V2)/E2 (referred to secondary).
**Concept:** VR = (no-load − full-load)/no-load voltage.
**Twist:** Per-unit VR = Rpu cosφ ± Xpu sinφ; referred to primary → (E1−V1)/E1.

**Q131 (SSC-JE-20):** Which is the only transformer whose primary and secondary are connected to each other electrically?
(a) Shielded winding transformer (b) Insulating transformer (c) Auto transformer (d) Isolating transformer
**Ans: (c)** — Autotransformer (electrically connected windings).
**Concept:** Auto transformer: one continuous winding, conduction + induction.
**Twist:** Isolation/insulating transformer → 1:1 with full isolation; shielded winding → screens between windings.

**Q132 (SSC-JE-20):** The core of the transformer is made of
(a) copper (b) aluminium (c) air (d) laminated sheath
**Ans: (d)** — Laminated (silicon-steel) sheath.
**Concept:** Laminated silicon steel core (reduces eddy loss).
**Twist:** Material is silicon steel (Q9); lamination not for copper/aluminium (conductors would short the flux).

**Q133 (TSSPDCL-22):** A 3-ϕ transformer has 600 primary and 150 secondary turns, supply 1.5 kV. Secondary line voltage on no-load for (a) delta-star (b) star-delta
(a) 216.5 V, 649.5 V (b) 649.5 V, 216.5 V (c) 649.5 V, 375 V (d) 375 V, 216.5 V
**Ans: (b)** — Δ-Y: E2 = 0.375 kV, Y-line = √3×0.375 = 0.649 kV; Y-Δ: E2 = 1.5/√3 ×(150/600) = 0.2165 kV.
**Concept:** Phase EMFs scale by N ratio; line voltage = phase (Δ) or √3×phase (Y).
**Twist:** Ratio 4:1 on Δ-Δ → V2 = 375 V; turns ratio 10 → V2(Δ-Y) = 260 V.

**Q134 (TSSPDCL-22):** Load current of a 1-ϕ ideal transformer leads secondary voltage by 30°, no-load current lags supply voltage by 10°. Angle between no-load current and load component in primary
(a) 70° (b) 40° (c) 30° (d) 100°
**Ans: (b)** — Angle = 30° + 10° = 40°.
**Concept:** Load component reflects secondary phase (+30°); I0 is at −10° from V1; included angle = 40°.
**Twist:** Lead 45° + lag 15° → 60°; unity-pf load + I0 at −20° → 20°.

**Q135 (TSSPDCL-22):** Match for parallel operation of two transformers. (a) Necessary / (b) Essential with (i) same vector group (ii) same turns ratio (iii) same polarity (iv) same % impedance (v) same kVA rating
(a) (a)–(ii); (b)–(iv) (b) (a)–(iii); (b)–(iv) (c) (a)–(v); (b)–(ii) (d) (a)–(iv); (b)–(i)
**Ans: (d)** — Necessary: same % impedance; Essential: same vector group (also polarity, turns ratio).
**Concept:** Essential = mandatory (vector group, polarity, turns ratio); Necessary = desirable (same %Z, X/R).
**Twist:** Essential condition violated → circulating current; necessary (%Z) mismatch → load shared off-ratio.

**Q136 (TSSPDCL-22):** At no-load, plot W/f vs f; 'c' is y-intercept and 'm' is slope. Hysteresis and eddy current losses
(a) cf and mf² respectively (b) mf and c (c) c and mf (d) mf² and cf
**Ans: (a)** — W/f = Ph/f + Pe/f = c + mf → Ph = cf, Pe = mf².
**Concept:** Pi/f = A + Bf (straight line); slope B = Pe/f², intercept A = Ph/f.
**Twist:** Slope 0.001, intercept 0.01 at 100 Hz → Ph = 1 W, Pe = 10 W (Q51); if plot is Pi vs f² → slope gives Pe/f².

**Q137 (TSSPDCL-22):** Electrical machines are designed to have the maximum efficiency at
(a) Full load (b) 50% of full load (c) near about full-load (d) No load
**Ans: (c)** — Designed for max η near full load.
**Concept:** x = √(Pi/Pcu(FL)) tuned ≈ 0.75–1.0 by design.
**Twist:** Distribution transformers often max-η at 50–75% load; power transformers near full load.

**Q138 (TSSPDCL-22):** 3 single-phase transformers, each 100 kVA, connected in delta; one is taken out of service. Capacity of the system
(a) 200 kVA (b) 173.2 kVA (c) 36.6 kVA (d) 115.5 kVA
**Ans: (b)** — Open delta = 0.577×300 = 173.2 kVA.
**Concept:** Open delta (V-V) delivers 1/√3 of Δ-Δ.
**Twist:** Two 100 kVA units → 173.2 kVA; each unit must carry line current (overloads at same kVA per unit).

**Q139 (TSSPDCL-22):** Efficiency of a 65 kVA transformer is 0.96 at full-load as well as half-load. For this transformer at full-load, the copper loss
(a) is less than the core loss (b) is more than the core loss (c) is equal to the core loss (d) will be minimum
**Ans: (b)** — Equal η at FL and half-load ⇒ max η lies between ⇒ at full load Pcu > Pi.
**Concept:** η(x1) = η(x2) ⇒ xmax between; at FL beyond xmax, copper loss dominates.
**Twist:** If η equal at 50% and 75% → max at ~62%; if only FL given max → Pcu = Pi at FL.

**Q140 (TSNPDCL-22):** 1-ϕ, 90 kVA transformer, full-load copper 1200 W, iron 400 W, friction 132 W. Total losses at 80% full-load
(a) 1220 W (b) 1156 W (c) 1412 W (d) 1300 W
**Ans: (d)** — Pcu = 0.64×1200 = 768 W; total = 768+400+132 = 1300 W.
**Concept:** Total loss = x²Pcu(FL) + Pi + Pmech.
**Twist:** At full load → 1200+400+132 = 1732 W; at half load → 300+400+132 = 832 W.

**Q141 (TSNPDCL-22):** 20 kVA, 1-ϕ, 2000 V/200 V two-winding connected as auto to get 2200 V/200 V. Rating
(a) 18 kVA (b) 20 kVA (c) 22 kVA (d) 24 kVA
**Ans: (c)** — K = 200/2200 = 1/11; VA = 20/(1−1/11) = 22 kVA.
**Concept:** VA_AT = S/(1−K); K = LV/HV.
**Twist:** Step-up 2000→2400 V (K = 5/6) → 120 kVA; step-down 2200/200 (K = 1/11) → 22 kVA.

**Q142 (TSPSC-2023):** Which is a characteristic of an ideal transformer?
(a) Zero stored magnetic energy (b) Large magnetising current (c) Zero core flux (d) Infinite core reluctance
**Ans: (a)** — Ideal transformer: zero stored energy, zero losses, infinite μ (zero reluctance).
**Concept:** Ideal T/F: zero core/copper loss, zero leakage flux, linear B–H.
**Twist:** Real transformer → finite μ → magnetizing current needed; infinite core reluctance would mean no flux → no transfer.

**Q143 (TSPSC-2023):** For parallel operation of two 1-ϕ transformers with same voltage ratio and different kVA ratings, load is shared in proportion to ratings when transformers have
(a) Equal per unit impedances on their respective ratings (b) Same leakage reactance in ohms (c) Same magnetising reactance in ohms (d) Leakage reactance in ohms inversely proportional to ratings
**Ans: (a)** — Equal pu impedances on own bases → share ∝ kVA ratings.
**Concept:** S1/S2 ∝ kVA; pu Z equality on self-bases.
**Twist:** Unequal pu Z → share inversely to Z; if Z ∝ 1/kVA in ohms → also proportional sharing.

**Q144 (TSPSC-2023):** Which statements are entirely true regarding Eddy current?
(a) Minimized by low-hysteresis material; ∝ f² (b) Direction by Lenz's law; ∝ f² (c) Minimized by low-hysteresis material; ∝ f (d) Minimized by thin laminate; ∝ square of flux frequency
**Ans: (d)** — Thin laminations reduce eddy loss; eddy loss ∝ B²f².
**Concept:** Pe = KBm²f²t²; lamination reduces t.
**Twist:** Hysteresis (not eddy) is cut by Si addition; eddy loss ∝ f² but ∝ Bm².

**Q145 (TSPSC-2023):** Which is correct regarding Eddy currents in the coil?
(a) Eddy currents convert useful energy into heat and waste it (b) Eddy currents flow in straight lines without power loss (c) Eddy current helps in generating electrical energy (d) By laminated core, eddy currents are increased
**Ans: (a)** — Eddy currents cause heat loss (I²R in core).
**Concept:** Eddy currents = circulating currents → copper-like loss in core; reduced by lamination.
**Twist:** Laminations → eddy currents DECREASED (opposite of option d); high-resistivity (Si) steel also cuts them.

**Q146 (TSPSC-2023):** If Pe and Ph denote eddy and hysteresis loss in a core at frequency f, then
(a) Total (Pe+Ph) ∝ f (b) Pe ∝ f, Ph ∝ f² (c) Pe ∝ f² and Ph ∝ f (d) Pe and Ph both ∝ f²
**Ans: (c)** — Pe ∝ f², Ph ∝ f.
**Concept:** Ph = Af, Pe = Bf² (Bm const).
**Twist:** If V/f not held constant, Pe ∝ Bm²f² changes; doubling f doubles Ph, quadruples Pe.

**Q147 (TSPSC-2023):** In a transformer, load current kept constant while pf is varied. Zero voltage regulation will be observed when
(a) independent of load power factor (b) load power factor is leading (c) load power factor is lagging (d) at pf equal to unity
**Ans: (b)** — Zero VR at a leading pf.
**Concept:** VR = R cosφ − X sinφ = 0 ⇒ leading pf (tanφ = R/X).
**Twist:** Maximum VR at lagging pf (tanφ = X/R); at unity pf VR = Rpu only.

**Q148 (TSPSC-2023):** In a single-phase transformer from a constant input voltage, load current kept constant while pf is varied. Under this condition
(a) pf where max efficiency occurs depends on leakage inductance (b) max efficiency at 0.5 lead (c) max efficiency at 0.5 lag (d) max efficiency at unity power factor
**Ans: (d)** — With constant current, max efficiency at unity pf.
**Concept:** η = V2I2cosφ/(output+losses); fixed losses → η rises with cosφ → max at UPF.
**Twist:** Fixed VA, unity pf → highest output → highest η; at 0.5 lag η lower.

**Q149 (TSPSC-2023):** Maximum efficiency of a 1-ϕ transformer at unity pf is 90% under full-load conditions. Efficiency at half-load, same pf
(a) 90% (b) 84.5% (c) 87.8% (d) 88.3%
**Ans: (c)** — 0.9 = 1/(1+2pi) → pi = 0.055; η(0.5) = 0.5/(0.5+0.055+0.25×0.055) = 0.879.
**Concept:** At max η, pi = pcu(FL); η(x) = x/(x+pi+x²pcu).
**Twist:** Max η 95% → pi = 0.0263 → η(0.5) = 94.2%; full-load (not max) 90% ⇒ pi ≠ pcu(FL).

**Q150 (TSPSC-2023):** Purpose of using harmonic restraint function in power transformers
(a) To reduce harmonic power loss (b) To reduce harmonic content in voltage (c) To reduce harmonic content in current (d) To prevent false tripping due to magnetizing inrush current
**Ans: (d)** — Harmonic restraint blocks differential protection during inrush.
**Concept:** Differential protection restrains on harmonic content of inrush current.
**Twist:** Inrush contains large 2nd harmonic → restraint operates; internal faults are near-fundamental → trip.

**Q151 (TSSPDCL-AE-2023):** Statements: P. Concentric coils for core type, interleaved for shell type. Q. Reverse of P. R. Shell type preferred for low power, core for high power. S. Shell type preferred for high power, core for low power.
(a) P and R (b) Q and R (c) P and S (d) Q and S
**Ans: (c)** — P correct (concentric-core, interleaved-shell); S correct (shell → high current/low voltage).
**Concept:** Core type: concentric windings (HV outside); shell type: interleaved (low voltage, high current).
**Twist:** Core type → low current/high voltage (insulation needs); shell type → high current → many parallel strips.

**Q152 (TSSPDCL-AE-2023):** Which statement is NOT true with respect to a 1-ϕ transformer?
(a) If load current kept constant, max efficiency at U.P.F. (b) Transformer efficiency is maximum at the same load current regardless of variation in load p.f. (c) If load current kept constant, max efficiency occurs at 0.8 p.f. lagging (d) Core and copper loss unaffected by variation of p.f.
**Ans: (c)** — Constant-current max efficiency is at UPF, not 0.8 lag.
**Concept:** η at const current peaks at unity pf (Q148).
**Twist:** Losses (core & copper) are pf-independent (option d true); efficiency changes only via output power with pf.

**Q153 (TSSPDCL-AE-2023):** Full-load voltage drops are 3% and 4% due to resistance and leakage reactance. The full-load pf at which voltage drop is maximum and the pf at which it is zero
(a) 0.6 lag and 0.8 lag (b) 0.6 lag and 0.8 lead (c) 0.8 lead and 0.6 lag (d) 0.8 lag and 0.6 lead
**Ans: (b)** — Max drop: tanφ = X/R = 4/3 → cosφ = 0.6 lag; zero drop: tanφ = R/X = 3/4 → cosφ = 0.8 lead.
**Concept:** dVR/dφ = 0 ⇒ tanφ = X/R (lag); VR = 0 ⇒ tanφ = R/X (lead).
**Twist:** %R = %X → max at 0.707 lag, zero at 0.707 lead; only %R (X=0) → max at unity pf.

**Q154 (TSPSC-AEE-23):** The e.m.f. per turn for a single phase, 2200/220 V, 50 Hz transformer is approximately 20 volts. Secondary turns
(a) 11 (b) 121 (c) 16.92 (d) 110
**Ans: (a)** — N2 = V2/(emf/turn) = 220/20 = 11.
**Concept:** E/turn = E/N; N2 = V2/(E/turn).
**Twist:** emf/turn 10 V → N2 = 22; primary turns = 2200/20 = 110 (also option d); flux: φm = 20/(4.44×50) = 0.09 Wb.

**Q155 (TSGenco-24):** 11000/2200 V, 100 kVA two-winding used as autotransformer (windings in series). Which is NOT a possible value of voltage ratio and kVA output?
(a) 2200/13200 V; 120 kVA (b) 11000/13200 V; 600 kVA (c) 13200/2200 V; 120 kVA (d) 2200/13200 V; 600 kVA
**Ans: (d)** — K = 2200/13200 = 1/6 → VA = 100/(1−1/6) = 120 kVA, NOT 600 kVA.
**Concept:** VA_AT = S(1−K)⁻¹; K = LV/HV of autotransformer; winding sizes constrain connections.
**Twist:** 11000/13200 (K = 5/6) → 600 kVA (option b correct); 13200/2200 (K = 1/6) → 120 kVA (option c correct).

**Q156 (TSGenco-24):** Which statements are NOT correct? (i) Δ-Y used at beginning of HV transmission (ii) Open delta not possible with Y-Y (iii) Y-Δ used in 3-ϕ distribution (iv) Oscillatory neutral problems absent in Y-Y
(a) (i) and (ii) only (b) (ii) and (iii) only (c) (iii) and (iv) only (d) (i) and (iv) only
**Ans: (c)** — (iii) wrong: distribution is Δ-Y; (iv) wrong: Y-Y has oscillatory neutral (no 3rd-harmonic path).
**Concept:** Δ-Y at generator/HV end; Δ-Y for distribution (neutral for both loads); Y-Y lacks triplen-current path.
**Twist:** Y-Y neutral problems cured by delta tertiary/zig-zag; open-delta needs 3 single-phase units (Δ or Y both impossible without 3rd winding — statement (ii) correct).

**Q157 (TSGenco-24):** A 1 Ω resistive load is to be impedance matched by a transformer to a source with 6250 Ω internal resistance. Ratio of primary to secondary turns
(a) 10 (b) 15 (c) 20 (d) 25
**Ans: (d)** — (N1/N2)²·RL = Rs → (N1/N2)² = 6250/10 = 625 → N ratio 25 (source text says 1 Ω but works 10 Ω).
**Concept:** Impedance transformation R′ = (N1/N2)²·R.
**Twist:** If RL truly 1 Ω → ratio = √6250 ≈ 79; load 40 Ω, source 1000 Ω → ratio = 5; source 6250 Ω, load 25 Ω → ratio 15.8.

**Q158 (TSGenco-24):** 3-phase bank (three 1-ϕ transformers) steps down a 6600 V line; primary line current 20 A; Y/Δ connection, turns ratio 12. Output kVA of Y/Δ
(a) 132√3 (b) 66√3 (c) 132/√3 (d) 66/√3
**Ans: (a)** — S = √3·VL·IL = √3×6600×20 = √3×132 kVA.
**Concept:** kVA = √3·VL·IL (balanced 3-ϕ, ideal transformer).
**Twist:** Turns ratio 12 → V2(LL) = √3×6600/√3/12... (Δ secondary: V2 = (6600/√3)/12 = 317.5 V); output kVA same 132√3; if Y-Y → V2 = 6600/12 = 550 V.

## Unit 2: DC Machines (175 Qs)

**Q1 (EPDCL-10):** The armature of a dc machine is made up of laminated sheets to
(a) reduce hysteresis loss (b) reduce eddy-current loss (c) reduce armature copper-loss (d) increase dissipation of heat
**Ans: (b)** — Laminations confine eddy currents, cutting eddy-current loss (∝ square of lamination thickness).
**Concept:** Eddy-current loss Pe ∝ f²B²t²; lamination thickness t is reduced to cut Pe.
**Twist:** Make laminations thinner → Pe falls ∝ t². Hysteresis loss is set by material (silicon steel), not lamination thickness → no change.

**Q2 (EPDCL-10):** The number of parallel paths in the armature winding of a four-pole wave-connected machine having 22 coil-sides is
(a) 4 (b) 2 (c) 22 (d) 1
**Ans: (b)** — In a (simplex) wave winding, number of parallel paths A = 2 always, regardless of poles.
**Concept:** Winding: A = P for lap, A = 2 for wave.
**Twist:** 4-pole simplex lap → A = 4. 6-pole duplex wave → A = 2 × 2 = 4.

**Q3 (SSC-JE-10):** A 4-pole, 1200 rpm, DC lap wound generator has 1520 conductors, flux/pole 0.01 Wb. The EMF generated is
(a) 608 V (b) 304 V (c) 152 V (d) 76 V
**Ans: (b)** — E = (Z/A)(PΦN/60) = (1520/4)(4×0.01×1200/60) = 380 × 0.8 = 304 V (lap: A = P = 4).
**Concept:** EMF: E = (Z/A)(PΦN/60).
**Twist:** Same data but wave wound (A = 2) → E = 608 V. Flux halved → E = 152 V.

**Q4 (SSC-JE-10):** An electric motor may give noise due to
(a) magnetic effect (b) defective bearing (c) cooling air (d) all of the above
**Ans: (d)** — Noise can arise from magnetic forces, faulty bearings, and cooling-air flow.
**Concept:** Sources of motor noise: magnetic, mechanical (bearings), aerodynamic.
**Twist:** Only a loose bearing (mechanical) → same answer (d) still as one source; "cogging" noise in PM motors → magnetic.

**Q5 (SSC-JE-10):** The condition for maximum power output from a dc motor is
(a) Eb = V (b) Eb = V/2 (c) Eb = 0 (d) Eb = V/2
**Ans: (b)** — P = Eb·Ia = (Vt − IaRa)·Ia; dP/dIa = 0 → Vt = 2IaRa → Eb = Vt/2.
**Concept:** Max power output when Eb = Vt/2 (IaRa = Vt/2).
**Twist:** Max efficiency condition is not Eb = V/2 → efficiency peaks when variable loss = constant loss. Eb = V (back emf ≈ applied) → Ia ≈ 0, no power.

**Q6 (SSC-JE-11):** A 220 V shunt motor develops 60 N-m at an armature current of 10 A. Torque when armature current is 20 A
(a) 30 N-m (b) 240 N-m (c) 84 N-m (d) 120 N-m
**Ans: (d)** — Shunt: T = KaΦIa, Φ constant → KaΦ = 60/10 = 6 → T = 6 × 20 = 120 N-m.
**Concept:** Torque: T = KaΦIa; shunt motor Φ ≈ constant → T ∝ Ia.
**Twist:** If it were a series motor (unsaturated) → T ∝ Ia² → 4×60 = 240 N-m (option b).

**Q7 (SSC-JE-11):** The torque developed in a dc series motor in unsaturated magnetic circuit condition is
(a) almost practically constant at all load currents (b) directly proportional to load current (c) directly proportional to square of load current (d) inversely proportional to square of load current
**Ans: (c)** — Series motor Φ ∝ Ia; T = KaΦIa → T ∝ Ia² (unsaturated).
**Concept:** Torque: series T ∝ Ia² (unsaturated); T ∝ Ia (saturated).
**Twist:** Saturated series motor → T ∝ Ia (nearly linear). Flux halved (field weakened) at same Ia → T halves.

**Q8 (SSC-JE-11):** The type of DC generator used for arc welding should be a
(a) series generator (b) shunt generator (c) cumulatively compound generator (d) differentially compounded generator
**Ans: (d)** — Differentially compound generator gives a wide drop in terminal voltage for a small change in Ia — ideal for arc welding (drooping V-I).
**Concept:** Arc welding needs a sharply drooping (constant-current) characteristic → differentially compounded.
**Twist:** Battery charging → shunt (constant voltage). Booster in a dc system → series/separately excited.

**Q9 (AP Genco-12):** [Circuit: series motor with braking resistances R (in series with armature) and R1 (across field)]; per-unit values of R and R1 to get the shown speed-torque line through origin
(a) 0, 0.5 (b) 0.5, 0.5 (c) 0.5, ∞ (d) ∞, 0.5
**Ans: (d)** — A T-ω line through origin = dynamic braking: armature opened from supply → R = ∞; field still excited (R1 finite = 0.5) to brake by its own emf.
**Concept:** Dynamic braking: motor disconnected from supply, armature across resistance; speed-torque line passes through origin.
**Twist:** For plugging (reverse-current) braking → supply stays connected, R finite, R1 = 0 (line offset from origin).

**Q10 (AP Genco-12):** A 200 V dc shunt motor runs at 1000 rpm drawing 10 A, ra = 2 Ω. Braked by plugging; series resistance to restrict armature current to 10 A is
(a) 32 Ω (b) 36 Ω (c) 38 Ω (d) 40 Ω
**Ans: (b)** — Motoring: Eb = 200 − 10×2 = 180 V. Plugging: Ia = (Vt+Eb)/(ra+rex) → 10 = 380/(2+rex) → rex = 36 Ω.
**Concept:** Plugging: Ia = (Vt + Eb)/(ra + Rex) (supply and back-emf in series-aiding).
**Twist:** Restrict current to 5 A → rex = 74 Ω. Dynamic braking instead → Ia = Eb/(ra+Rex) → rex = 16 Ω.

**Q11 (AP Genco-12):** [Load characteristics I–IV for shunt, flat, over and differential compound] Match:
(a) p-I, q-II, r-III, s-IV (b) p-II, q-III, r-IV, s-I (c) p-III, q-II, r-I, s-IV (d) p-III, q-IV, r-I, s-II
**Ans: (c)** — p(shunt)-III mild droop; q(flat compound)-II level; r(over compound)-I rising; s(differential)-IV steep droop.
**Concept:** Load characteristics: shunt droops, flat compound ≈ constant, over compound rises, differential compound drops steeply.
**Twist:** Series generator → sharply rising V-I. Under-compound → falls between shunt and flat.

**Q12 (AP Genco-12):** A 36-slot, 4-pole, simplex lap wound machine (2 conductors/slot). Back pitch and front pitch adopted could be
(a) 15, 13 (b) 19, 17 (c) 21, 19 (d) 23, 21
**Ans: (b)** — yb = 2C/P ± 1 = 2(36)/4 ± 1 = 19, 17; yf = yb − 2 → (19,17).
**Concept:** Lap winding pitch: yb = (2C/P) ± 1; yf = yb − 2.
**Twist:** Wave winding → use average pitch (Z ± 2)/P. Simplex lap 36-slot 6-pole → yb = 12 ± 1 = 13, 11.

**Q13 (Transco-12):** The speed-torque characteristic of a series motor is a/an
(a) Circle (b) Parabola (c) Ellipse (d) Hyperbola
**Ans: (d)** — N = (Vt − IaRa)/KaΦ with Φ ∝ Ia and T ∝ Ia² → N ∝ 1/T, a hyperbola.
**Concept:** Series motor speed-torque: N ∝ 1/T (hyperbola).
**Twist:** Shunt motor → N drops slightly, a drooping straight line. Separately excited → like shunt.

**Q14 (Transco-12):** In a DC generator, if variable loss equals constant loss, then the efficiency is
(a) Zero (b) Minimum (c) Maximum (d) 50%
**Ans: (c)** — Efficiency is maximum when variable (copper) loss equals constant (iron + mechanical) loss.
**Concept:** Max η at x = √(Pi/Pcu); condition variable loss = constant loss.
**Twist:** At x less than optimum (light load) → η lower because constant loss dominates. At max η, efficiency is NOT 50%.

**Q15 (Transco-12):** The armature of a dc machine is laminated to reduce
(a) Copper loss (b) Eddy current loss (c) Friction loss (d) Windage loss
**Ans: (b)** — Lamination of the armature core cuts eddy-current loss.
**Concept:** Eddy-current loss reduction via lamination.
**Twist:** Poles are also laminated (same reason). Copper/friction/windage are unaffected by lamination.

**Q16 (Transco-12):** The initial flux in a dc generator is provided by
(a) Initial voltage (b) Initial power (c) Initial current (d) Residual magnetism
**Ans: (d)** — Self-excited build-up starts from residual magnetism in the poles.
**Concept:** Self-excitation requires residual flux.
**Twist:** If residual magnetism is lost → machine fails to build up voltage. Wrong field connection also prevents build-up.

**Q17 (Transco-12):** For the operation of a milling machine, the following motor is used
(a) DC series motor (b) DC shunt motor (c) DC compound motor (d) DC short shunt compound motor
**Ans: (b)** — Milling needs constant speed from no-load to full-load → shunt motor.
**Concept:** Constant-speed applications → shunt; variable-speed/high-torque → series.
**Twist:** Cranes/hoists → series. Rolling mill (intermittent high torque) → cumulative compound.

**Q18 (Transco-12):** In a series motor, the torque is
(a) proportional to armature current (b) proportional to square of the armature current (c) proportional to field current (d) constant
**Ans: (b)** — Series motor T = KaΦIa with Φ ∝ Ia → T ∝ Ia².
**Concept:** Torque: series T ∝ Ia² (unsaturated).
**Twist:** Saturated series motor → T ∝ Ia only. Shunt motor → T ∝ Ia.

**Q19 (Transco-12):** By conducting Swinburne's test on a DC machine, the following losses can be determined
(a) Constant losses (b) Variable losses (c) Armature copper losses (d) Friction and windage losses
**Ans: (a)** — Swinburne's (no-load) test measures constant losses (iron + mechanical + shunt-field copper).
**Concept:** Swinburne's test → constant losses only.
**Twist:** Variable (armature copper) loss is computed, not measured. Not valid for series machines (no stable no-load run).

**Q20 (Transco-12):** The series motors have a relatively
(a) Zero starting torque (b) Low starting torque (c) High starting torque (d) Medium starting torque
**Ans: (c)** — At start Ia is large and Φ ∝ Ia → T ∝ Ia² is high.
**Concept:** Series motor high starting torque (T ∝ Ia² at start).
**Twist:** Traction and cranes exploit this. Shunt motor has moderate starting torque.

**Q21 (Transco-12):** A dc shunt motor develops 15 N-m at 10 A load current. If load current is doubled, new torque is
(a) 0 N-m (b) 15 N-m (c) 30 N-m (d) 60 N-m
**Ans: (c)** — Shunt: T ∝ Ia → doubling Ia doubles torque to 30 N-m.
**Concept:** Torque: shunt T ∝ Ia.
**Twist:** Series motor, current doubled → T ∝ Ia² → 4× = 60 N-m (option d).

**Q22 (Transco-12):** The internal characteristic of a dc shunt generator is a plot between
(a) Induced emf and armature current (b) Terminal voltage and load current (c) Induced emf and field current (d) Terminal voltage and field current
**Ans: (a)** — Internal characteristic is Eg vs Ia.
**Concept:** Internal char: Eg–Ia; external char: Vt–IL; OCC: E–If.
**Twist:** External characteristic (Vt vs IL) drops more than internal due to armature-reaction and IaRa drops.

**Q23 (Transco-12):** The back emf of a motor at the time of starting is
(a) zero (b) maximum (c) moderate (d) infinite
**Ans: (a)** — Eb = KaΦω; at start ω = 0 → Eb = 0.
**Concept:** Back EMF: Eb = KaΦω; zero at standstill.
**Twist:** Full starting current flows at start (Eb = 0) → starter needed. After steady state Eb ≈ Vt − IaRa.

**Q24 (Transco-12):** At low flux densities, the flux in a dc generator varies
(a) Linearly with armature current (b) Non-linearly with armature current (c) Linearly with the field current (d) Non-linearly with the field current
**Ans: (c)** — On the linear (unsaturated) part of the B-H/magnetization curve, Φ ∝ If (linearly).
**Concept:** Unsaturated region: Φ ∝ If (linear); saturation → non-linear.
**Twist:** In the saturated region flux stays almost constant → increase If little effect. Series motor on linear region: Φ ∝ Ia.

**Q25 (Transco-12):** Which motor is used for intermittent high torque loads and for rolling mills?
(a) DC series motor (b) DC shunt motor (c) DC cumulative compound wound motor (d) DC differential compound wound motor
**Ans: (c)** — Cumulative compound gives high torque with moderate speed regulation for intermittent/rolling loads.
**Concept:** Applications: cumulative compound → rolling mills, intermittent high torque.
**Twist:** Traction → series. Machine tools (constant speed) → shunt. Differential compound → never for driving (unstable/over-speeds).

**Q26 (Transco-12):** In plugging of dc motors
(a) Connections to armature are reversed (b) Connections to field are reversed (c) Connections to both armature and field are reversed (d) Connections to supply are reversed
**Ans: (a)** — Plugging reverses only the armature connection (Ia reverses) while field polarity is kept, so torque reverses.
**Concept:** Plugging: reverse armature terminals (Ia) only.
**Twist:** Reverse armature AND field → torque direction unchanged, no braking. In a separately excited motor reversing armature supply → plugging.

**Q27 (Transco-12):** The motor enclosure used in the wood-working industry is
(a) Protected type (b) Totally enclosed fan cooled type (c) Flame proof type (d) Splash proof type
**Ans: (b)** — Wood dust/sawdust → totally enclosed fan-cooled (TEFC) prevents ingress.
**Concept:** TEFC for dusty environments (wood-working).
**Twist:** Flame-proof for explosive atmospheres (mines). Splash-proof for wet outdoor.

**Q28 (Transco-12):** The least expensive drive is
(a) belt drive (b) rope drive (c) chain drive (d) gear drive
**Ans: (a)** — Belt drive is cheapest; gear/chain are costlier.
**Concept:** Belt = least expensive; gear = precise, no slip.
**Twist:** For high torque exact-ratio → gear. Belt slips at high load → chain/rope for heavy.

**Q29 (Transco-12):** A dc motor drives a constant-power load. The per-unit torque when field current is reduced to half (rated = 1 pu) would be
(a) 0.5 pu (b) 1.0 pu (c) 2.0 pu (d) 1.5 pu
**Ans: (a)** — P = Tω constant; If halved → Φ halved → ω doubles → T halves = 0.5 pu.
**Concept:** Constant-power load: T ∝ 1/ω; N ∝ Vt/Φ.
**Twist:** Constant-torque load, field halved → speed doubles, torque stays 1 pu. Constant power with Φ halved at same Vt → Ia doubles.

**Q30 (APSPDCL-12):** A 2-pole wave wound dc generator has 120 conductors in each parallel path, driven at 1200 rpm, Φ = 0.02 Wb/pole. Induced emf
(a) 48 V (b) 96 V (c) 24 V (d) 124 V
**Ans: (b)** — Z = A × cond/path = 2×120 = 240; E = (240/2)(2×0.02×1200/60) = 120 × 0.8 = 96 V.
**Concept:** EMF: E = (Z/A)(PΦN/60); wave A = 2.
**Twist:** 4-pole lap, same Z → A = 4 → E = 48 V (option a). Doubling speed → 192 V.

**Q31 (APSPDCL-12):** [4 curves: Eg vs speed] Variation of OCC emf of a separately excited generator at constant field current and variable speed is
(a) 1 (b) 2 (c) 3 (d) 4
**Ans: (a)** — Field constant → Eg ∝ speed, a straight line through origin (curve 1).
**Concept:** Eg = KaΦω; constant Φ → Eg ∝ N (linear through origin).
**Twist:** Field varied at constant speed → saturating OCC (OCC shape). Speed halved → emf halves along the same line.

**Q32 (APSPDCL-12):** [Load torque vs speed characteristic of an industrial load] The motor suitable for this load is
(a) dc shunt motor (b) 3-phase induction motor (c) dc series motor (d) capacitor motor
**Ans: (c)** — Load requires high torque at low speed → dc series motor characteristic matches.
**Concept:** Series motor has high torque at low speed, low torque at high speed.
**Twist:** Constant-speed load (fan at fixed speed) → shunt. If load torque rises with speed (fan) → motor must give rising T, series mismatched.

**Q33 (HMWS-12):** The coupling field between the electrical and mechanical systems of a dc machine is
(a) electrical field (b) magnetic field (c) electro-static field (d) both electric and magnetic fields
**Ans: (b)** — Energy conversion in dc machines is via the magnetic field (air-gap flux).
**Concept:** Electromechanical coupling = magnetic field.
**Twist:** In electrostatic machines (vandeGraaff) coupling is electric; not used for rotating dc machines.

**Q34 (HMWS-12):** The current in armature conductors of a dc machine is
(a) pure dc (b) pulsating dc (c) ac (d) pure ac pulsating dc
**Ans: (c)** — Each armature conductor sees alternating current as it passes under N/S poles.
**Concept:** Conductor current is AC; commutator rectifies it to DC at terminals.
**Twist:** Terminal/brush current is DC, but conductor current is AC. In generator, armature EMF is AC, rectified externally.

**Q35 (HMWS-12):** An 8-pole, 250 V, wave wound generator has 200 conductors. If lap wound, number of conductors required (same emf)
(a) 800 (b) 100 (c) 3200 (d) 1600
**Ans: (a)** — E ∝ Z/A; wave A=2, lap A=P=8 → Z2 = Z1×(A2/A1) = 200×8/2 = 800.
**Concept:** EMF ∝ Z/A; lap needs A/P× more conductors for same emf.
**Twist:** 4-pole lap from wave → Z2 = 400. Keeping 200 conductors and rewinding lap → emf drops by factor P/2.

**Q36 (HMWS-12):** Stray losses consist of
(a) copper and iron losses (b) iron and mechanical losses (c) field copper loss and iron loss (d) frictional loss and copper loss
**Ans: (b)** — Stray losses = iron (core) losses + mechanical (friction + windage) losses.
**Concept:** Stray loss = iron + mechanical; constant losses add shunt-field copper loss.
**Twist:** Add shunt-field copper → constant losses. Variable loss = armature copper loss (+ brush contact).

**Q37 (HMWS-12):** A shunt generator delivers 195 A at 250 V. ra = 0.02 Ω, rsh = 50 Ω. Generated emf
(a) 246 V (b) 270 V (c) 282 V (d) 254 V
**Ans: (d)** — If = 250/50 = 5 A; Ia = 195+5 = 200 A; Eg = 250 + 200×0.02 = 254 V.
**Concept:** Generator: Eg = Vt + IaRa; Ia = IL + If.
**Twist:** Load current 400 A same Vt → Ia = 405, Eg = 258.1 V. Lower rsh → higher If → larger Ia.

**Q38 (HMWS-12):** If the flux per pole of a dc generator is halved but its speed is doubled, its generated emf will
(a) remain the same (b) be halved (c) be doubled (d) be quadrupled
**Ans: (a)** — Eg = KaΦω; (Φ/2)(2ω) = Φω → unchanged.
**Concept:** EMF: Eg = KaΦω.
**Twist:** Flux halved, speed constant → Eg halves. Flux halved, speed quadrupled → Eg doubles. Motor with Φ halved, Vt constant → speed doubles.

**Q39 (HMWS-12):** ___ motor has the best speed regulation.
(a) Series (b) Cumulatively compound (c) Shunt (d) Differentially compounded
**Ans: (c)** — Shunt motor has the smallest speed change from no-load to full-load (best regulation).
**Concept:** Speed regulation: shunt ≈ constant speed; series very poor.
**Twist:** Differentially compound → negative regulation (speed rises with load, unstable). Series → speed varies hugely.

**Q40 (HMWS-12):** A series motor will over speed when
(a) the load is increased (b) the field is opened (c) the armature circuit is opened (d) load is removed
**Ans: (d)** — Removing load → flux → ~0 → speed rises dangerously (runaway).
**Concept:** Series motor must never run without load (no-load → high speed).
**Twist:** Field opened (Φ→0) at constant Vt → similar runaway risk. Load increased → speed falls.

**Q41 (HMWS-12):** In a dc shunt motor, if terminal voltage is reduced to half, torque remaining the same, then
(a) speed remains same and armature current will be doubled (b) speed becomes half, armature current same (c) speed becomes half while armature current doubles (d) both speed and armature current double
**Ans: (a)** — Φ ∝ Vt → Φ halves; N ∝ Vt/Φ → speed constant; T constant & Φ halves → Ia doubles.
**Concept:** N ∝ Vt/Φ; shunt Φ ∝ Vt; T = KaΦIa.
**Twist:** Vt halved but load torque ∝ N (fan) → speed changes. Vt constant, Φ halved (field rheostat) → speed doubles.

**Q42 (Transco-12):** The torque-speed characteristic of a repulsion motor resembles which dc motor characteristic?
(a) Separately excited (b) shunt (c) Series (d) Compound
**Ans: (c)** — Repulsion motor (single-phase AC commutator motor) has a series-like drooping T-ω characteristic.
**Concept:** Repulsion motor behaves like a dc series motor.
**Twist:** If examiner asks universal motor → also series-like. Squirrel-cage induction → shunt-like flat region.

**Q43 (Transco-12):** Which motor is most suitable for computer printer drive?
(a) Reluctance motor (b) Hysteresis motor (c) Shaded pole motor (d) Stepper motor
**Ans: (d)** — Stepper motor gives precise incremental position control for printers.
**Concept:** Stepper → printers, X-Y drives, robotics.
**Twist:** Watch/clocks → hysteresis motor. Small fans → shaded pole.

**Q44 (Transco-12):** A 4-pole lap wound dc generator develops P watts at E volts. Two adjacent brushes are removed (worn out). With remaining brushes, developed voltage and power
(a) E, P (b) E/2, P/2 (c) E, P/4 (d) E, P/2
**Ans: (d)** — Only 2 of the 4 parallel paths feed; voltage unchanged (E), current halves → P/2.
**Concept:** Brushes = number of parallel paths (lap A = P); removing one reduces active paths.
**Twist:** Removing two opposite (not adjacent) brushes → also leaves 2 paths, E, P/2. 6-pole lap, two brushes removed → 4 paths → P still E, P×4/6.

**Q45 (SSC-JE-12):** Match List-I (motors) with List-II (characteristics): P. DC series–1. Constant speed; Q. DC shunt–2. High starting torque
(a) P-2, Q-1 (b) P-1, Q-1 (c) P-2, Q-2 (d) P-1, Q-2
**Ans: (a)** — Series → high starting torque; shunt → constant speed.
**Concept:** Series: high Ts, poor regulation; shunt: moderate Ts, constant speed.
**Twist:** Add cumulative compound → both high Ts and better regulation (P→2, Q→1 equivalent answer still a).

**Q46 (SSC-JE-12):** The motor characteristic best suited for traction purposes is that of a
(a) synchronous motor (b) induction motor (c) d.c. shunt motor (d) d.c. series motor
**Ans: (d)** — DC series motor (high starting torque, inherent speed-torque match) suits traction.
**Concept:** Traction → dc series motor.
**Twist:** Lift/crane → also series. Conveyor constant speed → shunt/induction.

**Q47 (SSC-JE-12):** A lap wound dc generator with 250 armature conductors runs at 1200 rpm. If generated emf is 200 V, the operating flux/pole is
(a) 0.04 Wb (b) 0.06 Wb (c) 0.02 Wb (d) 0.08 Wb
**Ans: (a)** — Lap: A = P, E = (Z/A)(PΦN/60) = ZΦN/60 → Φ = (200×60)/(250×1200) = 0.04 Wb.
**Concept:** EMF: E = ZΦN/60 for lap (A = P).
**Twist:** Wave wound (A = 2) with P = 4 → E = (Z/2)(4ΦN/60) → double the emf → Φ = 0.02 Wb for same E.

**Q48 (SSC-JE-12):** The direction of rotation of a dc shunt motor can be reversed by interchanging
(a) either field or armature terminals (b) the supply terminals (c) the field terminals only (d) the armature terminals only
**Ans: (a)** — Reversing either field OR armature reverses torque direction.
**Concept:** Reversal: reverse Φ or Ia (not both).
**Twist:** Reverse both field and armature (or supply) → direction unchanged. Interchanging armature and field supply → no rotation change.

**Q49 (SSC-JE-12):** Poles of dc machines are often laminated to reduce
(a) iron weight (b) armature reaction (c) hysteresis loss (d) eddy current loss
**Ans: (d)** — Laminated poles cut eddy-current loss in the pole body.
**Concept:** Eddy-current loss reduction via lamination (poles and armature).
**Twist:** Solid poles would heat from eddy currents. Hysteresis loss is material-dependent, not reduced by lamination.

**Q50 (SSC-JE-12):** Which motor can work satisfactorily on both AC and DC?
(a) Shunt motor (b) Induction motor (c) Synchronous motor (d) Series motor
**Ans: (d)** — DC series motor runs on AC too (universal motor, if compensated).
**Concept:** Universal (ac/dc) motor = series motor.
**Twist:** AC series motor has poorer commutation and lower torque (iron loss) than DC. Shunt motor on AC → pulsating flux, poor torque.

**Q51 (SSC-JE-13):** The load characteristic of a dc shunt generator is determined by
(a) the voltage drop in armature resistance (b) the voltage drop due to decreased field current and voltage drop in armature resistance (c) the voltage drop due to armature reaction and voltage drop in armature resistance (d) the voltage drop due to armature reaction
**Ans: (b)** — Load char Vt = Eg − IaRa; as IL rises Vt falls → If falls too (both drops included).
**Concept:** Vt = Eg − IaRa with If = Vt/Rf (self-excited coupling).
**Twist:** Separately excited generator → only IaRa drop matters (If constant) → option a. Over-compound → series field raises Vt with load.

**Q52 (SSC-JE-13):** Flux 100×10⁻⁶ Wb at end of long bar magnet withdrawn through a 1000-turn coil in 1/20 s. Induced emf
(a) 20.0 V (b) 2.0 V (c) 0.2 V (d) 0.02 V
**Ans: (b)** — |E| = N·dΦ/dt = 1000 × (100×10⁻⁶)/(1/20) = 1000 × 2×10⁻³ = 2 V.
**Concept:** Faraday's law: E = N·dΦ/dt.
**Twist:** Pull the magnet out twice as fast (1/40 s) → E = 4 V. Half the turns → 1 V.

**Q53 (SSC-JE-13):** If the supply polarity to the armature terminals of a separately excited dc motor is reversed, the motor will run under
(a) Plugging condition (b) Regenerative braking condition (c) Dynamic braking condition (d) Normal motoring condition
**Ans: (a)** — Reversing armature terminals alone reverses Ia → torque reverses → plugging (source key misprinted (b); reasoning is plugging).
**Concept:** Plugging: reverse armature (Ia) with field fixed.
**Twist:** Reverse the field terminals instead → same plugging. To get regenerative braking, raise Eg > Vt (increase speed/flux above rated).

**Q54 (SSC-JE-13):** [4 speed-torque curves] The speed-torque characteristic of a dc series motor operating from a constant-voltage supply is
(a) (b) (c) (d)
**Ans: (c)** — Series motor from constant V: N falls hyperbolically with T (curve c).
**Concept:** Series motor T-ω: N ∝ 1/√T on constant-voltage supply.
**Twist:** From a constant-current supply the series characteristic becomes linear drooping. Shunt motor → nearly flat line.

**Q55 (SSC-JE-13):** The purpose of using a dummy coil in a DC machine is to
(a) eliminate harmonics developed in the machine (b) eliminate harmonic reaction (c) bring mechanical balance of the armature (d) bring mechanical balance of the body of the motor
**Ans: (c)** — Dummy coils (in wave windings with odd slots) give mechanical balance of the armature, carry no current.
**Concept:** Dummy coil → mechanical balancing in wave winding.
**Twist:** Equalizer rings are used in lap winding (not dummy coils) to equalize current between paths.

**Q56 (SSC-JE-13):** The commutator in a dc machine acts as
(a) a mechanical inverter (b) a mechanical rectifier (c) current controller (d) either (a) or (b)
**Ans: (d)** — In a generator it rectifies (AC→DC); in a motor it inverts (DC→AC).
**Concept:** Commutator: rectifier in generator, inverter in motor.
**Twist:** Armature conductor current is always AC; terminal current is DC in both modes.

**Q57 (SSC-JE-13):** The commutator segments of a dc machine are made of
(a) tungsten (b) hard-drawn copper (c) soft copper (d) electrolytic copper
**Ans: (b)** — Hard-drawn copper segments resist wear at the brush contact.
**Concept:** Commutator material: hard-drawn copper.
**Twist:** Brushes are carbon/graphite (soft) to reduce commutator wear. Soft copper → rapid wear.

**Q58 (SSC-JE-13):** For a 6-pole dc machine with wave wound armature, the number of brushes required is
(a) 2 (b) 4 (c) 6 (d) 12
**Ans: (a)** — Wave winding A = 2 → only 2 brushes (usually at the two paths).
**Concept:** Brushes = number of parallel paths (wave A = 2).
**Twist:** 6-pole lap → 6 brushes. Duplex wave 6-pole → A = 4 → 4 brushes.

**Q59 (SSC-JE-13):** Function of interpoles in a DC machine is to
(a) reduce field winding heating (b) improve commutation (c) compensate for air-gap variation (d) reduce losses
**Ans: (b)** — Interpoles cancel reactance and armature-reaction emf at the commutating zone → sparkless commutation.
**Concept:** Interpoles → improve commutation.
**Twist:** Compensating winding reduces armature-reaction distortion under pole faces (not commutation). Interpoles carry armature current, in series with armature.

**Q60 (EPDCL-14):** In an electromechanical energy conversion device, the developed torque depends upon
(a) Stator field strength and torque angle (b) Rotor and stator field strength (c) Stator and rotor field strength and torque angle (d) Stator field strength only
**Ans: (c)** — T ∝ F1·F2·sin δ (both field strengths and torque angle).
**Concept:** Torque ∝ (stator mmf)(rotor mmf) sin δ.
**Twist:** δ = 0 → no torque (fields aligned). δ = 90° → max torque. Power angle swing in synchronous machine uses same sin δ.

**Q61 (EPDCL-14):** Wave winding is employed in a dc machine for
(a) High current and low voltage rating (b) Low current and high voltage rating (c) High current and high voltage rating (d) Low current and low voltage rating
**Ans: (b)** — Wave winding (A = 2) gives higher emf per path, lower current → high-voltage low-current.
**Concept:** Wave → low current, high voltage; lap → high current, low voltage.
**Twist:** Lap winding for high current (e.g., plating/welding generators). 8-pole wave → only 2 paths, low current.

**Q62 (EPDCL-14):** The slight curvature at the lower end of the OCC of a self-excited dc generator is due to
(a) Magnetic inertia (b) Residual flux (c) High speed (d) High field resistance
**Ans: (b)** — The OCC starts from the residual-flux voltage (curved lower end).
**Concept:** OCC lower curvature → residual magnetism.
**Twist:** If residual flux zero → OCC starts from origin; build-up fails. Steeper (higher speed) OCC → higher ceiling voltage.

**Q63 (EPDCL-14):** [Graph of Vt vs IL] The graph represents which characteristic of a dc shunt generator
(a) Internal characteristics (b) External characteristics (c) Open circuit characteristics (d) Magnetic characteristics
**Ans: (b)** — Vt vs IL is the external characteristic.
**Concept:** External: Vt–IL; Internal: Eg–Ia; OCC: E–If.
**Twist:** The internal characteristic lies above external (no IaRa drop); OCC is for field current (open-circuit) only.

**Q64 (EPDCL-14):** Which one among the following has the highest numerical value in a stepper motor?
(a) Detent torque (b) Holding torque (c) Dynamic torque (d) Ripple torque
**Ans: (b)** — Holding torque (excited, at standstill) is the largest.
**Concept:** Stepper torques: holding > detent (unexcited) > dynamic.
**Twist:** Detent torque exists even with no excitation. Holding torque falls as step rate rises (pull-out torque reduces).

**Q65 (EPDCL-14):** Which motor is most suitable for a computer printer drive?
(a) Reluctance motor (b) Hysteresis motor (c) Shade pole motor (d) Stepper motor
**Ans: (d)** — Stepper = precise discrete positioning for printers.
**Concept:** Stepper for position control (printers, plotters, robots).
**Twist:** Disk/tape drives needing smooth quiet rotation → hysteresis. Fans → shaded pole.

**Q66 (EPDCL-14):** One important precaution while conducting Field's test on a dc series M-G set is
(a) Speed must be maintained constant (b) Applied voltage to motor to be maintained at rated value (c) Generator current to be maintained constant (d) Generator field current to be maintained constant
**Ans: (b)** — Rated voltage must be held, else the series motor may over-speed and run away.
**Concept:** Field's test (series motor/generator) → keep voltage at rated value (safety against over-speed).
**Twist:** Swinburne's test → run at rated speed & flux (constant losses). In Field's test both machines are coupled on the same shaft.

**Q67 (APSPDCL-14):** Symmetrical duplex wave windings are not possible in dc machines, if
(a) no. of pole pairs is divisible by 2 (b) no. of slots is multiple of 2 (c) no. of pole pairs is an odd number (d) no. of commutator segments is multiple of 2
**Ans: (c)** — Symmetrical duplex/multiplex wave winding needs an even number of pole pairs.
**Concept:** Wave winding symmetry: multiplex wave needs even pole pairs (P/2 even).
**Twist:** 4-pole (2 pairs, even) → duplex wave possible. 6-pole (3 pairs, odd) → duplex wave not possible.

**Q68 (APSPDCL-14):** [ω-T line through origin; 4 circuits] The characteristic is related to a mode of dc shunt machine; pick the correct circuit
(a) (b) (c) (d)
**Ans: (a)** — Line through origin = dynamic braking: armature opened from supply, connected to external resistance; field kept energized.
**Concept:** Dynamic braking circuit: field on constant supply, armature across braking resistance.
**Twist:** Plugging circuit keeps supply connected with armature reversed (T-ω line offset). Regenerative braking returns power to source (line below T-axis).

**Q69 (APSPDCL-14):** Applied voltage of a separately excited dc motor suddenly changed by 1% (short duration); armature resistance drop is 5%. Assuming speed constant, change in armature current is
(a) 5% (b) 10% (c) 15% (d) 20%
**Ans: (d)** — Vt − IaRa = K (speed, flux constant). 0.95Vt → 0.99Vt − Ia2Ra = 0.95Vt → Ia2Ra = 0.04Vt vs Ia1Ra = 0.05Vt → Ia falls 20%.
**Concept:** ω = (Vt − IaRa)/KaΦ; at constant ω, Δ(Vt) = Δ(IaRa).
**Twist:** Voltage cut by 2% → ΔIa = 40%. Drop = 10%, ΔV = 1% → ΔIa = 10% (magnified by Vt/(IaRa) = 20).

**Q70 (ISRO-14):** One of the main advantages of Swinburne's test is that it
(a) is applicable both to shunt and compound motors (b) Needs one running test (c) is very economical and convenient (d) ignores any change in iron loss
**Ans: (c)** — No-load test → very economical and convenient (small power).
**Concept:** Swinburne's test = no-load/constant-loss test, economical.
**Twist:** It does not measure stray/load losses accurately and is invalid for series motors. Hopkinson's test is regenerative but needs two machines.

**Q71 (SSC-JE-S1-14):** Rated speed of a dc shunt motor is 1050 rpm; to run at 1200 rpm the scheme used is
(a) Armature circuit resistance control (b) Field resistance control (c) Ward-Leonard control (d) Varying frequency
**Ans: (b)** — Above base speed → weaken field (field-resistance control).
**Concept:** Speed control: above base speed → field control; below → armature control.
**Twist:** To run below rated speed (e.g., 800 rpm) → armature resistance control (constant torque). Constant power drive → field control.

**Q72 (SSC-JE-S1-14):** Two dc series motors in series draw current I at speed N. Connected in parallel taking current I, the speed of each motor is
(a) N (b) 2N (c) 4N (d) N/2
**Ans: (c)** — Parallel: each gets I/2 → Φ ∝ I/2; N ∝ Vt/Φ (Vt same) → N ∝ 1/(I/2) = 4× → 4N.
**Concept:** Series motor N ∝ Vt/Φ, Φ ∝ I; parallel halves per-motor current.
**Twist:** Series connection halves voltage per motor → N ∝ (Vt/2)/I. Series: both get full current I but half voltage → N halves.

**Q73 (SSC-JE-S1-14):** A 150 V dc motor, armature resistance 0.4 Ω, back emf 142 V. Armature current
(a) 10 A (b) 20 A (c) 150 A (d) 100 A
**Ans: (b)** — Ia = (Vt − Eb)/ra = (150−142)/0.4 = 20 A.
**Concept:** Motor: Ia = (Vt − Eb)/Ra.
**Twist:** Back emf 140 V → Ia = 25 A. At standstill Eb = 0 → Ia = 375 A (need starter).

**Q74 (SSC-JE-S1-14):** Which motor has high starting torque?
(a) a.c. series motor (b) d.c. series motor (c) induction motor (d) synchronous motor
**Ans: (b)** — DC series motor (T ∝ Ia² at start) has the highest starting torque.
**Concept:** High starting torque → dc series.
**Twist:** Synchronous motor has zero starting torque (needs damper winding + separate starting). Induction has moderate Tst.

**Q75 (SSC-JE-S1-14):** EMF induced in a coil rotating in a uniform magnetic field is maximum when the
(a) Flux linking with the coil is maximum (b) Rate of change of flux linkage is minimum (c) Rate of change of flux linkage is maximum (d) Rate of cutting flux by the coil sides is minimum
**Ans: (c)** — e = −dΦ/dt; maximum when rate of change of flux linkage is maximum (flux zero crossing).
**Concept:** e = −N dΦ/dt; e peak at Φ = 0.
**Twist:** EMF zero when flux linkage is maximum (top of sine). In a generator, EMF peaks when coil sides cut flux at max rate.

**Q76 (SSC-JE-S2-14):** The commutator of a DC generator acts as
(a) an amplifier (b) a rectifier (c) a load (d) a multiplier
**Ans: (b)** — In a generator, the commutator rectifies the AC armature emf to DC at brushes.
**Concept:** Commutator = mechanical rectifier (generator).
**Twist:** In a motor it acts as inverter (DC→AC in armature coils). Amplifier → generator action (amplidyne).

**Q77 (SSC-JE-S2-14):** Fleming's left-hand rule is applicable to
(a) DC generator (b) DC motor (c) Alternator (d) Transformer
**Ans: (b)** — Left-hand rule gives force direction on a current-carrying conductor in a field (motor).
**Concept:** Left hand → force (motor); right hand → induced emf (generator).
**Twist:** Fleming's right-hand rule → generator. Transformer uses Lenz/Faraday, not Fleming.

**Q78 (SSC-JE-S2-14):** Commutation conditions at full load for large DC machines can be efficiently checked by the
(a) Brake test (b) Swinburne's test (c) Hopkinson's test (d) Field test
**Ans: (c)** — Hopkinson's (back-to-back regenerative) test checks commutation at full load economically.
**Concept:** Hopkinson's test → full-load commutation check, economical.
**Twist:** Swinburne's test is no-load only (no commutation check). Field test is for series machines (efficiency of traction motors).

**Q79 (SSC-JE-S2-14):** The emf induced in a DC shunt generator is 230 V, ra = 0.1 Ω, armature current 200 A. Terminal voltage
(a) 200 V (b) 210 V (c) 230 V (d) 250 V
**Ans: (b)** — Vt = Eg − IaRa = 230 − 200×0.1 = 210 V.
**Concept:** Generator: Vt = Eg − IaRa.
**Twist:** Generator feeding 100 A → Vt = 220 V. Motor (Vt − Eb = IaRa) same numbers → Eb = 210 V.

**Q80 (HMWS-15):** A DC generator will be flat compound if
(a) Terminal voltage increases slightly with the load (b) Generated voltage is proportional to load current (c) It produces higher voltage at light load (d) Its terminal voltage remains constant irrespective of load current
**Ans: (d)** — Flat compound generator holds Vt constant over the load range.
**Concept:** Flat compound → constant terminal voltage (series field just compensates IaRa + AR drop).
**Twist:** Over-compound → Vt rises with load (for line-drop compensation). Differential compound → Vt falls steeply.

**Q81 (HMWS-15):** A DC series motor develops 20 N-m at 3 A load current. If current is increased to 6 A, torque developed will be
(a) 80 N-m (b) 20 N-m (c) 40 N-m (d) 10 N-m
**Ans: (a)** — Unsaturated series T ∝ Ia² → (6/3)² × 20 = 4×20 = 80 N-m.
**Concept:** Torque: series T ∝ Ia².
**Twist:** Current halved to 1.5 A → T = 5 N-m. Saturated (T ∝ Ia) → 40 N-m (option c).

**Q82 (HMWS-15):** The direction of rotation of a DC shunt motor is reversed by
(a) Reversing supply connections (b) Interchanging the armature and field connections (c) Adding resistance to the field circuit (d) Reversing armature connections
**Ans: (d)** — Reversing the armature connections reverses Ia → torque reverses.
**Concept:** Reversal: reverse armature or field current (not both).
**Twist:** Reversing supply terminals reverses both → rotation unchanged. Interchanging armature/field connections changes nothing (both still fed from same polarity).

**Q83 (HMWS-15):** The internal characteristic of the DC generator is the curve between
(a) Armature current and IR drop (b) Load current and terminal voltage (c) Field current and no-load voltage (d) Armature current and the generated e.m.f.
**Ans: (d)** — Internal characteristic: Eg vs Ia.
**Concept:** Internal: Eg–Ia; external: Vt–IL.
**Twist:** OCC is E vs If (field current). External characteristic drops more than internal (IaRa drop).

**Q84 (HMWS-15):** A cumulative compound dc motor runs at 1500 rpm on full load. If the series field is short-circuited, its speed
(a) Decreases (b) Remains unchanged (c) Increases (d) Becomes zero
**Ans: (c)** — Shorting the series field removes its flux → Φ falls → N ∝ 1/Φ rises.
**Concept:** N ∝ Vt/Φ; reducing Φ raises speed.
**Twist:** Overload (higher Ia) in cumulative compound → Φ↑, speed falls less than shunt. If series field reversed → differential → speed may rise dangerously.

**Q85 (HMWS-15):** Which motor is best suited for traction?
(a) Shaded pole motor (b) DC series motor (c) Stepper motor (d) DC shunt motor
**Ans: (b)** — DC series motor: high starting torque + matching speed-torque → traction.
**Concept:** Traction → dc series.
**Twist:** Battery-electric forklifts also series. Suburban railways (induction) use VVVF drives for regenerating ability.

**Q86 (HMWS-15):** A 250 V DC shunt motor takes 20 A total. rsh = 200 Ω, ra = 0.3 Ω. Armature current
(a) 16.62 A (b) 11.25 A (c) 18.75 A (d) 9.65 A
**Ans: (c)** — If = 250/200 = 1.25 A; Ia = IL − If = 20 − 1.25 = 18.75 A.
**Concept:** Shunt motor: Ia = IL − If; If = Vt/Rf.
**Twist:** Motor on load drawing 30 A → Ia = 28.75 A. rsh = 100 Ω → If = 2.5 A → Ia = 17.5 A.

**Q87 (HMWS-15):** Which motor is suitable for high starting torque?
(a) Differential compound motor (b) Cumulative compound motor (c) Series motor (d) Shunt motor
**Ans: (c)** — Series motor gives the highest starting torque.
**Concept:** High starting torque → series (T ∝ Ia²).
**Twist:** Differential compound → low/negative torque, never used. Cumulative compound → between series and shunt.

**Q88 (HMWS-15):** In a DC generator with lap connected winding, the number of brushes required is equal to
(a) Always equal to zero (b) Number of pairs of poles (c) Half the number of poles (d) Number of poles
**Ans: (d)** — Lap winding A = P → number of brushes = P.
**Concept:** Brushes = parallel paths (lap: A = P; wave: A = 2).
**Twist:** 8-pole lap → 8 brushes; 8-pole wave → 2 brushes. Duplex lap 6-pole → A = 12 → 12 brushes.

**Q89 (HMWS-15):** At no-load, the ratio of energy loss due to dynamic braking and counter-current braking of a separately excited dc motor is
(a) 2:1 (b) 3:1 (c) 1:2 (d) 1:3
**Ans: (—)** — Solution computes Ploss(dynamic)/Ploss(counter-current) = (E²/ra)/(2E)²/ra = 1:4, which is not among the printed options (source key printed (d)).
**Concept:** Braking loss: dynamic = E²/R; plugging/counter-current = (V+E)²/R ≈ 4E²/R.
**Twist:** Counter-current (plugging) wastes ~4× dynamic-braking energy. With external resistance, both losses reduce (energy split across resistances).

**Q90 (TSGenco-15):** In a dc machine, interpoles are used to
(a) Neutralize the effect of armature reaction in the interpolar region (b) Generate more induced emf in the armature (c) Avoid interference of armature flux with the main field flux (d) Reduce the demagnetizing effect of armature reaction
**Ans: (a)** — Interpoles cancel armature-reaction/commutation emf in the interpolar (commutating) zone.
**Concept:** Interpoles neutralize AR in the interpolar region.
**Twist:** Compensating winding (not interpoles) reduces AR distortion under the pole faces. Interpole polarity: same as main pole ahead for a generator.

**Q91 (TSGenco-15):** The function of a brush and commutator arrangement in a dc motor is to
(a) Produce unidirectional torque (b) Produce unidirectional current in the armature (c) Help in changing the direction of rotation (d) Reduce sparking
**Ans: (a)** — Commutation reverses coil current so the torque stays unidirectional as conductors cross pole boundaries.
**Concept:** Commutator → maintains unidirectional torque in motor (rectifies current in rotating frame).
**Twist:** In a generator the same arrangement rectifies armature AC into DC. Without commutation the motor would produce pulsating (net-zero) torque.

**Q92 (TSGenco-15):** Aluminium is not used as winding wire of the armature of a dc machine because
(a) Aluminium has low resistivity (b) A large winding space is taken by aluminium conductors and creates jointing problems (c) The thermal conductivity of aluminium is low (d) Aluminium has low conductivity as compared to copper
**Ans: (b, c & d)** — Aluminium: bigger cross-section for same resistance (option b), lower thermal conductivity (c), lower conductivity than copper (d); option (a) is false (Al resistivity is higher).
**Concept:** Conductor choice: copper preferred for armature (higher σ, smaller size, good joints).
**Twist:** Aluminium IS used in transmission lines (cheap, light). For same copper conductivity an aluminium conductor needs ~1.6× area → larger slots.

**Q93 (TSGenco-15):** The induced emf in the armature of a lap wound four-pole dc machine, 100 conductors, 600 rpm, 1 Wb/pole is
(a) 1000 V (b) 100 V (c) 600 V (d) 10,000 V
**Ans: (a)** — E = (Z/A)(PΦN/60) = (100/4)(4×1×600/60) = 25 × 40 = 1000 V.
**Concept:** EMF: E = (Z/A)(PΦN/60), lap A = P.
**Twist:** Same machine wave wound (A = 2) → E = 2000 V. 0.5 Wb/pole → 500 V.

**Q94 (TSGenco-15):** Stepper motors are used in
(a) Printers (b) lifts (c) Amplifiers (d) oscillators
**Ans: (a)** — Stepper motors for precise positioning → printers.
**Concept:** Stepper applications: printers, plotters, robotics.
**Twist:** Lifts (hoists) → dc series/induction. Amplifiers → dc machines in Ward-Leonard set.

**Q95 (TSTransco-15):** In dc machines, the armature windings are placed on the rotor because of the necessity for
(a) Electro mechanical energy conversion (b) Generation of voltage (c) Commutation (d) Development of torque
**Ans: (c)** — The armature is on the rotor so the commutator/brushes can switch coil currents (commutation).
**Concept:** Armature on rotor → commutator-based commutation.
**Twist:** Field on stator gives stationary poles. If the field were on the rotor, brushes would be needed for field power.

**Q96 (TSSPDCL-15):** Choose the incorrect choice: As load torque increases, speed of __ motor decreases.
(a) dc series (b) dc shunt (c) dc cumulative compound (d) dc differential compound
**Ans: (d)** — In a differentially compound motor speed RISES as load torque increases (negative regulation) — the incorrect statement.
**Concept:** Differential compound → speed increases with load (unstable).
**Twist:** Cumulative compound → speed falls less steeply than series. If flux aids more with load (over-compound motor) → speed drops slowly.

**Q97 (TSSPDCL-15):** Eddy current loss in a dc generator is 400 W at 40 Hz and constant flux density. At 50 Hz the loss is
(a) 256 W (b) 320 W (c) 500 W (d) 625 W
**Ans: (d)** — Pe ∝ f² → Pe2 = 400×(50/40)² = 625 W.
**Concept:** Eddy loss: Pe ∝ f² (constant B).
**Twist:** Hysteresis loss Ph ∝ f (not f²) → 400×(50/40) = 500 W (option c, a classic trap). If flux density also doubles → Pe ∝ B²f² → 4× = 2500 W.

**Q98 (TSSPDCL-15):** Identify the increasing order of voltage regulation of the following dc generators at same load:
(a) differential compound, shunt and under compound (b) shunt, differential compound and under compound (c) under compound, shunt and differential compound (d) shunt, under compound and differential compound
**Ans: (c)** — Under compound (slightly rising) < shunt (mild droop) < differential compound (steep droop).
**Concept:** Voltage regulation: over/under compound ≤ flat ≤ shunt ≤ differential.
**Twist:** Over-compound has negative regulation (Vt rises). Flat compound → near-zero regulation.

**Q99 (TSSPDCL-15):** The number of poles of an 8/6 stepper motor can be
(a) 3 (b) 4 (c) 6 (d) 7
**Ans: (d)** — 8/6 stepper → 8 stator poles, 6 rotor teeth; the number of rotor poles = 7 (given key; poles = 8+6−7 pattern in design tables).
**Concept:** Stepper notation: stator poles / rotor teeth; rotor poles count related.
**Twist:** 8/5 stepper → rotor poles 7 as well; stepping angle = 360/(rotor teeth × phases).

**Q100 (TSSPDCL-15):** At a given load torque:
(a) Speed of 1-Φ ac series motor = speed of dc series motor (b) Speed of ac series motor > speed of dc series motor (c) Power output of ac series motor > power output of dc series motor (d) Speed of ac series motor < speed of dc series motor
**Ans: (d)** — AC series motor has higher iron losses and reactance drop → less torque/speed than DC series at same load.
**Concept:** AC series (universal) runs slower than DC series at same torque (extra losses).
**Twist:** Compensated ac series → less drop; single-phase series at 50 Hz also has commutation/power-factor penalties.

**Q101 (TSSPDCL-15):** Basically, brushless dc motor is ___ and its torque-speed characteristics are similar to ___ .
(a) a dc motor ... asynchronous motor (b) a synchronous motor ... dc motor (c) an asynchronous motor ... dc motor (d) a dc motor ... synchronous motor
**Ans: (b)** — BLDC = PM synchronous motor with dc-motor-like T-ω characteristics.
**Concept:** BLDC = PMSM; electronic commutation gives dc-motor characteristics.
**Twist:** Add sensorless commutation (BEMF) → same machine. An induction motor has a drooping, not flat, characteristic.

**Q102 (TSSPDCL-15):** In a DC generator the windings of interpoles are connected:
(a) In series with main field winding, same polarity pole ahead (b) In series with main field, opposite polarity pole ahead (c) In series with the armature winding, same polarity as main pole ahead (d) In series with armature, opposite polarity as main pole ahead
**Ans: (c)** — Interpoles are in series with the armature; their polarity equals the next main pole ahead (in a generator) to aid commutation.
**Concept:** Interpole: series with armature; generator → same polarity as pole ahead.
**Twist:** For a motor the interpole polarity is opposite to the pole ahead. Compensating winding also in series with armature but under main poles.

**Q103 (TSSPDCL-15):** A 5 kW, 220 V, 1500 rpm dc shunt motor runs at 1550 rpm no-load on full voltage. If voltage is reduced to 165 V, speed (neglect armature resistance) is
(a) 1162.5 (b) 775 (c) 1200 (d) 1550
**Ans: (d)** — Neglecting ra: N ∝ Vt/Φ with Φ ∝ Vt → N constant → 1550 rpm.
**Concept:** Shunt motor: N ∝ Vt/Φ; both scale together → N invariant (ra neglected).
**Twist:** Include ra drop (IaRa fixed): N = (Vt−IaRa)/KaΦ → lowering Vt lowers N slightly. Reduce flux (field control) instead → N rises above 1550.

**Q104 (TSSPDCL-15):** In a 3-stack, variable reluctance stepper motor with 12 rotor teeth, the angle through which the rotor moves for one pulse is
(a) 12° (b) 5° (c) 10° (d) 30°
**Ans: (c)** — Step angle = 360/(n × teeth) = 360/(3×12) = 10°.
**Concept:** Stepper step angle = 360/(m × N).
**Twist:** 4-stack, 12 teeth → 7.5°. 3-stack, 24 teeth → 5° (option b).

**Q105 (TSSPDCL-15):** In a 2 kW, 200 V, 1000 rpm DC series motor, torque at full load was 0.3 N-m. Torque at half full load
(a) 0.2 (b) 0.15 (c) 0.075 (d) 0.1
**Ans: (c)** — Half power → I_HL = I_FL/2; T ∝ I² → T_HL = 0.3/4 = 0.075 N-m.
**Concept:** Series motor: P ∝ I (Vt const) and T ∝ I² → halving load → quarter torque.
**Twist:** Quarter load → T = 0.01875. Shunt motor at half load (T ∝ I, I halves) → T = 0.15.

**Q106 (APGenco-17):** A shunt generator develops stable output voltage if
(a) magnetizing characteristic is linear (b) magnetization characteristic is non-linear (c) field winding resistance is more than critical resistance (d) residual magnetism is equal to zero
**Ans: (b)** — Build-up is stable only when the field-resistance line cuts the magnetizing (saturated/non-linear) OCC.
**Concept:** Self-excitation: Rf line must intersect the saturated OCC (stable point).
**Twist:** Rf > critical resistance → no build-up. Residual magnetism = 0 → no start of build-up.

**Q107 (APGenco-17):** In a differentially compound dc motor
(a) the speed is constant as torque increases (b) the speed falls non-linearly as torque increases (c) the speed increases non-linearly as torque increases (d) the flux increases as the load increases
**Ans: (c)** — Series flux opposes shunt flux → net Φ falls with load → speed rises non-linearly.
**Concept:** Differential compound: speed rises with load (negative regulation).
**Twist:** Cumulative compound → speed falls with load (stabilizing). If series winding reversed accidentally → differential → over-speeding hazard.

**Q108 (APGenco-17):** The main purpose of permanent-magnet motors is
(a) to avoid the need for field supply (b) to provide high flux density (c) to provide control over flux level (d) to facilitate kW rating
**Ans: (a)** — PM replaces the field winding → no field supply/excitation losses.
**Concept:** PM motor → no field winding needed.
**Twist:** PM gives a fixed flux (no field control) → speed control only via armature. NdFeB magnets give high flux density but suffer demagnetization at high temp.

**Q109 (APTransco-17):** A 220 V separately excited dc motor takes 20 A, ra = 1.0 Ω, KaΦ = 1.5 (rad/sec). Speed of the motor is
(a) 1000 rpm (b) 2000/π rpm (c) 3000/π rpm (d) 4000/π rpm
**Ans: (d)** — ω = (220−20×1)/1.5 = 133.33 rad/s → N = 60ω/2π = 4000/π rpm.
**Concept:** ω = (Vt − IaRa)/KaΦ; N = 60ω/2π.
**Twist:** Ia = 40 A → N = 2000/π. Vt = 250 V, Ia = 20 → N = (230/1.5)×60/2π = 1464 rpm.

**Q110 (APTransco-17):** Number of commutator bars for a 4-pole, 2-layer, DC lap winding with 24 slots and one conductor per layer is
(a) 48 (b) 24 (c) 192 (d) 96
**Ans: (b)** — Commutator segments = number of coils = number of slots (2-layer, 1 coil/slot) = 24.
**Concept:** Commutator segments = number of coils.
**Twist:** 2 conductors/layer per slot (2 coils/slot) → 48 segments. Wave winding → segments still = coils.

**Q111 (APTransco-17):** The Eb/V ratio of a DC motor is an indication of its ___.
(a) Speed regulation (b) Starting torque (c) Efficiency (d) Running torque
**Ans: (c)** — Eb/V = (V − IaRa)/V = Pout/Pin = efficiency.
**Concept:** Eb/V = output/input = efficiency.
**Twist:** Eb/V = 0 at start → zero efficiency/back-emf. Eb/V → 1 at no-load (high speed, low Ia). Efficient motor → Eb/V close to 1.

**Q112 (APTransco-17):** Which test is usually conducted to determine the efficiency of traction motors?
(a) Field's test (b) Swinburne's test (c) Hopkinson's test (d) Retardation test
**Ans: (a)** — Field's test is used for dc series motors (traction).
**Concept:** Field's test → efficiency of series (traction) motors.
**Twist:** Swinburne's test → shunt/compound (no-load). Hopkinson's test → large shunt machines at full load. Retardation test → friction/windage (moment of inertia).

**Q113 (TSSPDCL-18):** A separately excited DC machine supplies 50 A at 220 V (ra = 0.2 Ω), then run as a motor with same Vt, I, speed. The ratio Φm/Φg is
(a) 1.11 (b) 0.913 (c) 0.8 (d) 1.21
**Ans: (b)** — Generator: Eg = 220+10 = 230 V; Motor: Eb = 220−10 = 210 V; Φm/Φg = Eb/Eg = 210/230 = 0.913.
**Concept:** Same speed, Ka constant → Φ ∝ E; generator E = Vt+IaRa, motor E = Vt−IaRa.
**Twist:** Higher Ia → ratio falls further; if ra = 0.4 → Φm/Φg = (220−20)/(220+20) = 0.833.

**Q114 (TSSPDCL-18):** Consider: 1. DC series used where high starting torque needed. 2. A starter provides high starting torque. 3. At higher loads a cumulative compound motor has higher torque than a shunt motor. Correct statements:
(a) 1 and 2 (b) 1 and 3 (c) 2 and 3 (d) 1 only
**Ans: (b)** — Series gives high starting torque (1); starter limits starting current, NOT torque (2 false); cumulative compound has extra series flux → more torque at high load (3 true).
**Concept:** Starter = current limiter (3-point/4-point); compound flux boosting.
**Twist:** A 4-point starter also prevents speed rise when field opens. Removing starter sections stepwise raises Eb and current.

**Q115 (TSSPDCL-18):** A 230 V dc series motor, ra + rse = 0.3 Ω, draws 40 A at 1000 rpm. At 20 A line current the flux is 60% of that at 40 A. Speed at 20 A, 230 V is
(a) 1317 rpm (b) 1713 rpm (c) 1137 rpm (d) 3117 rpm
**Ans: (b)** — Eb1 = 230−40×0.3 = 218 V; Eb2 = 230−20×0.3 = 224 V; N2 = N1×(Eb2/Eb1)×(Φ1/Φ2) = 1000×(224/218)×(1/0.6) = 1713 rpm.
**Concept:** Series motor: N ∝ Eb/Φ; Eb = Vt − Ia(ra+rse).
**Twist:** Flux at 20 A = 50% → N2 = 2055 rpm. rse dominant (0.5 Ω) → N2 = 1767 rpm.

**Q116 (TSSPDCL-18):** Which statements regarding DC machines are NOT correct? 1. Armature reaction decreases flux under the leading pole tip in a generator. 2. Resistance commutation is generally used in fractional kW machines. 3. Interpole polarity is opposite to the main pole ahead in a generator.
(a) 1 and 3 (b) 1 only (c) 2 and 3 (d) 2 only
**Ans: (c)** — Statement 1 true (AR weakens leading pole tip in generator); 2 true (resistance commutation in small machines); 3 FALSE (interpole in generator has SAME polarity as pole ahead) → 2 and 3... wait, key gives (c) meaning "2 and 3 are not correct"? The solution key states (c). Per the doc, statements 1 and 2 are correct, 3 incorrect → the NOT-correct statements are only 3, but key prints (c) = 2 and 3.
**Concept:** Armature reaction & commutation: AR weakens leading tip (gen); interpole same polarity as pole ahead (gen).
**Twist:** In a MOTOR the interpole polarity is opposite to the pole ahead. Resistance commutation (small machines) vs voltage commutation (interpoles, large machines).

**Q117 (APTransco-19):** An 8-pole, DC generator, simplex wave wound, 32 coils of 6 turns each, Φ = 0.06 Wb, running at 250 rpm. Induced armature voltage
(a) 96 V (b) 192 V (c) 384 V (d) 768 V
**Ans: (c)** — Z = 32×6×2 = 384; E = (384/2)(8×0.06×250/60) = 192 × 2 = 384 V.
**Concept:** EMF: E = (Z/A)(PΦN/60); wave A = 2.
**Twist:** Same machine lap wound (A = 8) → E = 96 V (option a). 16 coils → E = 192 V.

**Q118 (APTransco-19):** A 220 V, 10 kW, 900 rpm separately excited DC motor, ra = 0.02 Ω, develops 70 N-m at rated conditions (neglect rotational loss). Current drawn from supply
(a) 34.2 A (b) 30 A (c) 22 A (d) 4.48 A
**Ans: (b)** — Irated = 10 kW/220 = 45.45 A; Eb = 220−45.45×0.02 = 219.09 V; KaΦ = 219.09/94.25 = 2.324; Ia = T/KaΦ = 70/2.324 = 30.1 A.
**Concept:** T = KaΦIa; Eb = Vt − IaRa = KaΦω.
**Twist:** T = 140 N-m → Ia = 60 A. Rotational losses included → Ia slightly higher than 30 A.

**Q119 (APEPDCL-19):** [Four VL–IL curves] Which figure represents the load characteristic of a DC shunt generator?
(a) (b) (c) (d)
**Ans: (c)** — Shunt generator external char: Vt falls gently with IL (slight droop, curve c).
**Concept:** Shunt generator Vt–IL: mild droop from no-load to full-load.
**Twist:** Flat compound → level line; over compound → rising; differential compound → steep droop.

**Q120 (APEPDCL-19):** Small air gap between stator and armature of a DC machine
(a) facilitate high speed operation (b) reduce noise (c) provides high ventilation (d) provide stronger magnetic field
**Ans: (d)** — Small air gap → low reluctance → strong magnetic field with less mmf.
**Concept:** Air gap: small → stronger field, but increases armature-reaction and cogging effects.
**Twist:** Small gap makes machine sensitive to armature reaction (flux distortion) → interpoles/compensating winding needed. Large gap → weak field, poor utilization.

**Q121 (APEPDCL-19):** EMF induced in a conductor of active length 0.5 m moving at 70 m/s surface speed through 1.2 Wb/m² flux density is
(a) 42 volts (b) 116.67 volts (c) 29.17 volts (d) 70 volts
**Ans: (a)** — e = Blv = 1.2 × 0.5 × 70 = 42 V.
**Concept:** Induced EMF: e = Blv.
**Twist:** v = 100 m/s → 60 V. B = 2 Wb/m², l = 1 m → 140 V. Per-conductor emf × conductors in series gives machine emf.

**Q122 (APEPDCL-19):** A 200 V dc shunt motor at 1000 rpm takes 17.5 A armature current. Additional resistance to reduce speed to 600 rpm at same Ia (ra = 0.4 Ω)
(a) 4.0 Ω (b) 4.4 Ω (c) 4.8 Ω (d) 1.6 Ω
**Ans: (b)** — Eb1 = 200−17.5×0.4 = 193 V; Eb2 = 193×600/1000 = 115.8 V; 115.8 = 200−17.5(0.4+Rex) → Rex = 4.41 Ω.
**Concept:** Speed control by armature resistance: Eb ∝ N (Φ constant), Eb2 = Vt − Ia(ra+Rex).
**Twist:** Speed 500 rpm → Rex = 5.4 Ω. Ia = 25 A at 600 rpm → Rex = 2.99 Ω. Efficiency of such control is poor (I²R losses).

**Q123 (APEPDCL-19):** Function of commutator: I. AC→DC voltage in motor. II. AC→DC in generator. III. DC→AC in motor. IV. DC→AC in generator.
(a) (III) and (IV) are correct (b) (II) is correct (c) (I) and (II) are correct (d) (II) and (III) are correct
**Ans: (d)** — Generator: armature AC → DC (II); Motor: applied DC → armature AC (III).
**Concept:** Commutator: rectifier (generator), inverter (motor).
**Twist:** If the machine runs as a motor but the question says "AC→DC in motor" → false. Doubt trap: "convert AC to DC in case of motor" — wrong.

**Q124 (APEPDCL-19):** A 6-pole DC machine has duplex wave wound armature. The number of parallel current paths is
(a) 4 (b) 6 (c) 12 (d) 2
**Ans: (a)** — Duplex wave: A = m × 2 = 2×2 = 4.
**Concept:** A = m×2 (wave, m = multiplexing); A = m×P (lap).
**Twist:** Triplex wave 6-pole → A = 6. Simplex lap 6-pole → A = 6. Duplex lap 6-pole → A = 12.

**Q125 (APEPDCL-19):** A DC machine has interpole winding (IPW) and compensating winding (CPW). With respect to the armature,
(a) IPW in series, CPW in parallel (b) Both IPW and CPW are in series (c) Both IPW and CPW are in parallel (d) IPW in parallel, CPW in series
**Ans: (b)** — Both interpole and compensating windings are connected in series with the armature.
**Concept:** IPW and CPW both carry armature current (series).
**Twist:** In a generator the IPW/CPW must see Ia to produce the anti-AR mmf → series connection mandatory. Series field in a compound machine is also in series with armature.

**Q126 (APEPDCL-19):** A DC series motor draws 20 A from 260 V at 600 rpm, combined (ra + rse) = 1 Ω, constant torque load. If supply is reduced to 200 V, the speed becomes
(a) 450 RPM (b) 600 RPM (c) 800 RPM (d) 432 RPM
**Ans: (a)** — Eb1 = 260−20×1 = 240 V; constant T & unsaturated → Ia2 = Ia1 = 20 A; Eb2 = 200−20 = 180 V; N ∝ Eb/Ia (Φ∝Ia) → N2 = 600×(180/240) = 450 rpm.
**Concept:** Series motor constant torque → Ia constant; N ∝ Eb.
**Twist:** Constant-power load → Ia scales as 1/N → different speed. Voltage 175 V → N = 387.5 rpm.

**Q127 (APEPDCL-19):** A series motor is best suited for driving
(a) Machine tools (b) Lathes (c) Cranes and hoists (d) Shears and punches
**Ans: (c)** — Cranes and hoists need high starting torque at standstill and a drooping speed-torque curve → series motor.
**Concept:** Series motor → cranes/hoists/traction (high starting torque).
**Twist:** Lathes/machine tools → constant-speed shunt. Shears/punches (intermittent high torque) → cumulative compound.

**Q128 (APEPDCL-19):** Which statement is correct with regard to field control of a DC motor?
(a) It acts as constant speed and torque drive (b) It acts as constant torque drive (c) It acts as constant kW drive (d) It acts as constant speed drive
**Ans: (c)** — Field control gives speeds above base with P = EbIa ≈ constant → constant kW (constant power).
**Concept:** Field control → constant kW drive (above base speed).
**Twist:** Armature (voltage) control → constant torque drive (below base speed). Constant-power drive torque falls as speed rises.

**Q129 (APEPDCL-19):** A dc shunt motor on constant-voltage mains drives a speed-independent (constant) load torque. For decreasing speed by increasing flux/pole, the condition required is
(a) Eb < V/2 (b) Eb > V/2 (c) Eb = V/2 (d) Eb = 1 − V/2
**Ans: (b)** — For dω/dΦ < 0 with T constant → 2IaRa < Vt → Eb > Vt/2.
**Concept:** Speed fall with flux increase requires Eb > V/2 (else speed rises with Φ).
**Twist:** Eb < V/2 → increasing Φ actually RAISES speed (backwards region) — a classic trap. On load (big IaRa) always decreases speed.

**Q130 (APEPDCL-19):** [ω–TL lines labelled V1, V2, V3 for a shunt motor] Identify the correct option:
(a) V1 < V2 < V3 (b) V1 > V2 > V3 (c) V1 = V2 = V3 (d) V1 < V2 > V3
**Ans: (b)** — Higher terminal voltage → higher no-load speed → V1 > V2 > V3.
**Concept:** ω = Vt/KaΦ − (ra/(KaΦ)²)·T; higher Vt shifts line up.
**Twist:** Reduce Φ (weaker field) → steeper line with higher no-load speed. Same Vt, higher ra → steeper drop.

**Q131 (APEPDCL-19):** A 220 V dc series motor draws 10 A, ra + rse = 1 Ω. Braked by plugging; resistance in series to restrict current to 20 A is
(a) 15.5 Ω (b) 15.2 Ω (c) 10.2 Ω (d) 20.5 Ω
**Ans: (—)** — Eb = 220−10 = 210 V; Eb ∝ Ia → Eb(plug) = 420 V; 20 = (220+420)/(1+Rex) → Rex = 31 Ω (not among options; source key printed "*").
**Concept:** Plugging series motor: Eb(plug) = 2×Eb(motor); Ia = (Vt+Eb)/(ra+rse+Rex).
**Twist:** Restrict plugging current to 10 A → Rex = 62 Ω. If Eb ∝ ΦN and speed unchanged during plugging → doubling holds only if Φ∝Ia.

**Q132 (APEPDCL-19):** A dc generator has armature emf 100 V at Φ = 20 mWb/pole, N = 800 rpm. Generated emf at 1000 rpm, same flux
(a) 125 V (b) 110 V (c) 130 V (d) 115 V
**Ans: (a)** — E ∝ N → E2 = 100×1000/800 = 125 V.
**Concept:** EMF: E ∝ ΦN.
**Twist:** Flux halved at 1000 rpm → E = 62.5 V. N = 1200 rpm, Φ doubled → E = 300 V.

**Q133 (HMWS-2020):** Match load characteristics: (A) T = constant, (B) T ∝ N, (C) T ∝ N², (D) T ∝ 1/N — with (P) Compressors, (Q) Cranes during hoisting, (R) Boring machines, (S) Eddy current brakes:
(a) A-Q; B-S; C-P; D-R (b) A-S; B-Q; C-R; D-P (c) A-S; B-Q; C-P; D-R (d) A-R; B-S; C-Q; D-P
**Ans: (a)** — T const → crane hoisting (Q); T ∝ N → eddy-current brakes (S); T ∝ N² → compressors/fans (P); T ∝ 1/N → boring machines (R).
**Concept:** Load types: constant torque (hoists), ∝N (brakes), ∝N² (fans/compressors), ∝1/N (constant power/boring).
**Twist:** Fan/blower → T ∝ N². Traction → T ∝ 1/N (constant power at high speed).

**Q134 (HMWS-2020):** The average pitch of a 4-pole, double-layer, 21-slot armature used for wave winding is
(a) 10 (b) 9 (c) 12 (d) 11
**Ans: (d)** — Coil sides = 42; Ya = (42 ± 2)/4 = 11 or 10; average pitch must be an odd integer → 11.
**Concept:** Wave winding average pitch Ya = (Z ± 2)/P, odd number.
**Twist:** 4-pole, 23 slots → Ya = (46±2)/4 = 12 or 11 → 11. Simplex wave must have Ya odd (commutator).

**Q135 (HMWS-2020):** Which test(s) is/are called non-loading test(s) of DC machines?
(a) Swinburne's and Hopkinson's test only (b) Field and Hopkinson's test only (c) Swinburne's test only (d) Hopkinson's test only
**Ans: (c)** — Swinburne's test is the only no-load (non-loading) test; Hopkinson's and Field's load the machines.
**Concept:** Non-loading test: Swinburne's only.
**Twist:** Hopkinson's (back-to-back) and Field's (series) are loading tests (full-load). Retardation test is a no-load method for friction/windage.

**Q136 (HMWS-2020):** Match D.C. Generators — (A) Separately excited, (B) Series wound, (C) Shunt wound, (D) Differentially compound — with (P) Battery charging, (Q) Arc welding, (R) Booster, (S) Ward Leonard system:
(a) A-S; B-R; C-P; D-Q (b) A-R; B-S; C-Q; D-P (c) A-R; B-P; C-S; D-Q (d) A-P; B-R; C-Q; D-S
**Ans: (a)** — Separately excited → Ward Leonard (S); Series → booster (R); Shunt → battery charging (P); Differentially compound → arc welding (Q).
**Concept:** Generator applications: separately excited/Ward-Leonard; series/booster; shunt/battery; differentially compound/arc welding.
**Twist:** Arc welding could also use a flat-compound set; battery charging needs constant voltage (shunt).

**Q137 (HMWS-2020):** Number of sections of starter resistance for a 200 V dc shunt motor, ra = 0.25 Ω, maximum and minimum current 50 A and 25 A
(a) 3 (b) 6 (c) 5 (d) 4
**Ans: (d)** — R1 = Vt/Imax = 200/50 = 4; a = Imin/Imax = 0.5; (0.5)ⁿ = ra/R1 = 0.25/4 → n = 4.
**Concept:** Starter design: R1 = Vt/Imax, a = Imin/Imax, aⁿ = ra/R1.
**Twist:** Imax = 100 A → R1 = 2, n = 3. If Ia(max)/Ia(min) ratio higher (a = 0.4) → n increases (log).

**Q138 (HMWS-2020):** A 200 V, 10 kW dc shunt motor takes 2.5 A running light. ra = 0.5 Ω, rsh = 400 Ω, brush drop 2 V. Variable losses for maximum efficiency
(a) 994 W (b) 494 W (c) 394 W (d) 794 W
**Ans: (b)** — If = 0.5 A, Ia0 = 2 A; Prot = 200×2.5 − (2²×0.5 + 200×0.5 + 2×2) = 500 − 106 = 394 W; constant losses = Prot + VtIf = 394 + 100 = 494 W; at max η, variable = constant = 494 W.
**Concept:** Max η when variable (I²R) loss = constant losses; constant losses from no-load data.
**Twist:** Ignore brush drop → constant losses = 492 W. Double brush drop (4 V) → constant losses 498 W.

**Q139 (SSC-JE-20):** Commutator in DC generator is used for
(a) collecting of current (b) reduce losses (c) increase efficiency (d) convert AC armature current into DC
**Ans: (d)** — Commutator rectifies the AC armature current to DC at the brushes.
**Concept:** Commutator = rectifier (generator), inverter (motor).
**Twist:** In a motor the armature current is converted DC→AC. In both cases conductor current is AC.

**Q140 (SSC-JE-20):** DC machine windings are
(a) full pitched (b) short pitched (c) either of these (d) none of these
**Ans: (a)** — DC machines use full-pitched coils (for commutator/equalizing).
**Concept:** DC winding → full pitch; AC (induction) → short pitch/chording.
**Twist:** Short-pitched coils are used in AC machines to reduce harmonics. Full pitch in DC → simplest commutation.

**Q141 (SSC-JE-20):** The armature winding is connected to the external power source through a
(a) commutator system (b) brush system (c) commutator-brush system (d) none of these
**Ans: (c)** — Connection is via the combined commutator-brush system.
**Concept:** Armature ↔ external via commutator + brushes.
**Twist:** In a brushless dc machine the connection is via an electronic inverter (no brushes).

**Q142 (SSC-JE-20):** The emf induced in the dc generator armature winding is
(a) AC (b) DC (c) AC and DC (d) None of these
**Ans: (a)** — Inside the armature winding the induced emf is alternating; it becomes DC only after commutation.
**Concept:** Armature EMF = AC (rectified by commutator to DC at terminals).
**Twist:** At the brushes (output) it is DC. Conductor current alternates while terminal current is DC.

**Q143 (SSC-JE-20):** The direction of rotation of a DC shunt motor is reversed by
(a) reversing armature connections (b) interchanging the armature and field connection (c) adding resistance to the field circuit (d) reversing supply connections
**Ans: (a)** — Reversing the armature connections reverses Ia → torque reverses (source key misprinted (d); reasoning: reverse field or armature).
**Concept:** Reversal: reverse Φ or Ia (single of the two).
**Twist:** Reversing supply connections reverses both field and armature → no rotation change. Reversing only field connections also reverses rotation.

**Q144 (SSC-JE-20):** Which is a correct statement about a series motor?
(a) Its field winding consists of thicker wire and less turns (b) It can run easily without load (c) It has an almost constant speed (d) It has poor torque
**Ans: (a)** — Series field carries full Ia → thick wire, few turns.
**Concept:** Series field: thick, few turns (carries armature current).
**Twist:** Shunt field: thin, many turns (constant small current). Series motor must not run unloaded (runaway); it has high torque.

**Q145 (APPSC-19):** If the number of poles in a lap wound generator is doubled, then the generated emf
(a) Same (b) Doubled (c) Halved (d) None
**Ans: (a)** — Lap: A = P, so P/A = 1 → E = ZΦN/60 independent of poles.
**Concept:** Lap winding emf independent of P (P/A = 1).
**Twist:** Wave wound: E ∝ P → doubling poles doubles emf (option b). Lap with different A? no — A always = P.

**Q146 (APPSC-19):** In a shunt generator, the interpole winding carries the
(a) short circuit current (b) armature current (c) shunt field current (d) rated current
**Ans: (b)** — Interpoles are in series with the armature → they carry armature current.
**Concept:** Interpole winding carries Ia.
**Twist:** The compensating winding also carries Ia. The shunt field winding carries small field current (Vt/Rf).

**Q147 (TSSPDCL-22):** An over-compounded DC generator supplies a load at 220 V. If terminal voltage is 220.2 V at 10 A load, what is it at 600 A?
(a) 232 V (b) 208 V (c) 222 V (d) 220 V
**Ans: (a)** — Over-compounding: series-field mmf rises with load → generated emf rises → ≈232 V at 600 A (from the rising Vt-IL characteristic).
**Concept:** Over-compound generator: Vt rises with load (series boost > drops).
**Twist:** Flat compound → Vt stays 220 V at 600 A. Differential compound → Vt falls sharply (~208 V).

**Q148 (TSSPDCL-22):** A DC shunt motor on 220 V takes 11 A line. ra = 0.2 Ω, rsh = 220 Ω. Generated back emf
(a) 218 V (b) 222 V (c) 216 V (d) 224 V
**Ans: (a)** — If = 220/220 = 1 A; Ia = 11−1 = 10 A; Eb = 220 − 10×0.2 = 218 V.
**Concept:** Motor: Eb = Vt − IaRa; Ia = IL − If.
**Twist:** Line current 21 A → Ia = 20 → Eb = 216 V. rsh = 110 Ω → If = 2 → Ia = 9 → Eb = 218.2 V.

**Q149 (TSNPDCL-22):** A 6-pole lap-connected DC generator, 1000 conductors, Φ = 0.06 Wb. For 250 V emf, the speed lap and wave respectively are
(a) 83.3 rpm, 250 rpm (b) 250 rpm, 83.3 rpm (c) 166.7 rpm, 500 rpm (d) 500 rpm, 166.7 rpm
**Ans: (b)** — Lap (A = 6): 250 = (1000/6)(6×0.06×N/60) → N = 250 rpm; Wave (A = 2): 250 = (1000/2)(6×0.06×N/60) → N = 83.33 rpm.
**Concept:** EMF: E = (Z/A)(PΦN/60); wave gives 3× emf for same N.
**Twist:** 4-pole lap 250 V same Z → N = 375 rpm. Φ = 0.03 → double the speeds.

**Q150 (TSNPDCL-22):** A separately excited dc motor runs at 800 rpm at rated 440 V. Armature voltage reduced to 330 V and flux reduced proportionately. Approximate speed
(a) 800 rpm (b) 600 rpm (c) 1067 rpm (d) 450 rpm
**Ans: (a)** — ω = (Vt − IaRa)/KaΦ; Vt and Φ both scale by 330/440 = 0.75 → ω unchanged (neglect IaRa).
**Concept:** N ∝ Vt/Φ; proportional flux reduction keeps speed constant.
**Twist:** Flux NOT reduced (kept 440-V value) at 330 V → N ∝ 0.75 → 600 rpm (option b). Flux halved, Vt same → N doubles.

**Q151 (TSPSC-2023):** Which load offers a characteristic close to a constant load torque?
(a) Water pumping load (b) Traction load (c) Low speed hoist (d) Fan type of load
**Ans: (c)** — Hoists/lifts have constant torque irrespective of speed.
**Concept:** Loads: hoist = constant T; fan/compressor = T ∝ N²; pump = T ∝ N (approx.); traction = T ∝ 1/N.
**Twist:** Fan/blower → T ∝ N². Paper-mill/rolling (constant power) → T ∝ 1/N.

**Q152 (TSPSC-2023):** Which statement is true for dynamic braking of a separately excited DC motor?
(a) Supply reversed, armature terminals fixed (b) Armature terminals reversed, supply present (c) Supply removed and armature terminals shorted (d) Supply removed and armature terminals connected to a resistance
**Ans: (d)** — Dynamic braking: disconnect armature from supply and close it through a braking resistor (field kept excited).
**Concept:** Dynamic braking: armature across resistance, field excited; motor acts as generator.
**Twist:** Shorting armature (no R) → heavy braking current, high torque. Plugging → supply reversed/armature reversed (option a/b) with high loss.

**Q153 (TSPSC-2023):** About the armature mmf wave in a dc machine: A. sinusoidal shape; B. triangular shape; C. rotates with respect to armature; D. rotates with respect to stator. Which statements are true?
(a) B and D only (b) A and C only (c) A and D only (d) B and C only
**Ans: (d)** — Armature mmf is triangular (max along GNA, zero at pole axis) and is stationary in space (rotates w.r.t. armature).
**Concept:** Armature mmf wave: triangular, stationary in space.
**Twist:** With brushes shifted, the armature mmf develops demagnetizing + cross-magnetizing components. The air-gap (resultant) flux is distorted toward the pole tips.

**Q154 (TSPSC-2023):** If the magnetic circuit of a dc machine is saturated, armature reaction results in
(a) Increase or decrease depending on mode (b) Increase in flux per pole (c) No change in flux per pole (d) Decrease in the value of flux per pole
**Ans: (d)** — Under saturation, the flux added on one pole tip cannot compensate the drop on the other → net demagnetizing (flux per pole decreases).
**Concept:** Armature reaction in saturated machine → net flux reduction (demagnetizing).
**Twist:** Unsaturated machine → AR mainly distorts (cross-magnetizing) with little net Φ change. At heavy load, saturation → stronger demagnetization → speed rises in shunt motors.

**Q155 (TSPSC-2023):** Match speed-control methods: A. Armature voltage; B. Field current control; C. Diverter resistors; D. Rheostatic voltage control — with 1. Poor efficiency, 2. Speeds below base speed, 3. Speeds above base speed, 4. DC series motor:
(a) A-2, B-1, C-3, D-4 (b) A-2, B-3, C-4, D-1 (c) A-2, B-3, C-1, D-4 (d) A-4, B-2, C-1, D-3
**Ans: (b)** — Armature voltage → below base (2); field control → above base (3); diverter → series motor (4); rheostatic → poor efficiency (1).
**Concept:** Speed control mapping: armature=below base; field=above base; diverter=series; rheostatic=poor η.
**Twist:** Ward-Leonard (voltage) → below base with good efficiency. Chopper control → below base, efficient.

**Q156 (TSPSC-2023):** About a dc series motor: A. torque ∝ current; B. suitable only for small starting torque; C. can run even on single-phase ac supply. Which is/are true?
(a) C only (b) A and B only (c) B and C only (d) A, B and C
**Ans: (a)** — Series torque ∝ I² (A false); high starting torque application (B false); universal operation on AC (C true).
**Concept:** Series motor: T ∝ I², high starting torque, universal (AC/DC).
**Twist:** If the machine were saturated (T ∝ I), statement A becomes true. On AC, a series motor runs but with higher losses and lower torque.

**Q157 (TSPSC-2023):** A dc shunt motor at 220 V DC runs at 1200 rpm. Neglecting losses and saturation, speed when fed from 175 V DC
(a) 1100 rpm (b) 750 rpm (c) 950 rpm (d) 1200 rpm
**Ans: (d)** — N ∝ Vt/Φ with Φ ∝ Vt → speed unchanged at 1200 rpm.
**Concept:** Shunt motor: N ∝ Vt/Φ (Φ ∝ Vt) → N invariant (ra neglected).
**Twist:** If field held at rated (separately fed) while armature at 175 V → N ∝ 0.795 → ~955 rpm. Include IaRa → slight drop below 1200.

**Q158 (TSPSC-2023):** A dc shunt motor with ra = 0.15 Ω on 230 V supply has back emf 200 V. Armature current
(a) 250 A (b) 100 A (c) 200 A (d) 150 A
**Ans: (c)** — Ia = (Vt − Eb)/Ra = (230−200)/0.15 = 200 A.
**Concept:** Motor: Ia = (Vt − Eb)/Ra.
**Twist:** Eb = 215 V → Ia = 100 A. ra = 0.3 → Ia = 100 A. At standstill Eb = 0 → Ia = 1533 A (starter mandatory).

**Q159 (TSPSC-2023):** Tmotor = 0.1N − 10; Tload = 0.25N − 75 (N in rpm). Steady-state speed after excitation
(a) 666.3 RPM (b) 433.3 RPM (c) 0 RPM (d) 700 RPM
**Ans: (b)** — Tmotor = Tload → 0.1N − 10 = 0.25N − 75 → N = 433.3 rpm.
**Concept:** Steady state: Tmotor = Tload (intersection of T-N lines).
**Twist:** If Tmotor = 0.2N − 10 and Tload = 0.25N − 75 → N = 1300 rpm. If the load line is steeper with no intersection in motoring quadrant → no stable point.

**Q160 (TSPSC-2023):** Which armature voltage control method is employed when the supply is dc?
(a) Static Ward-Leonard schemes (b) Ward-Leonard schemes (c) Transformers with taps and an uncontrolled rectifier bridge (d) Chopper control
**Ans: (d)** — For a dc supply, a dc-dc chopper gives variable armature voltage.
**Concept:** DC supply → chopper control; AC supply → controlled rectifier/static Ward-Leonard.
**Twist:** From AC mains → phase-controlled rectifier. Chopper allows smooth below-base speed with high efficiency.

**Q161 (TSPSC-2023):** A 200 V, 1200 rpm, 100 A separately excited dc motor, ra = 0.1 Ω, braked by plugging from 1200 rpm. External resistance to limit braking current to twice full-load value
(a) 7.33 Ω (b) 1.5 Ω (c) 3.8 Ω (d) 10.2 Ω
**Ans: (—)** — Eb = 200 − 100×0.1 = 190 V; plugging: 200 A = (200+190)/(0.1+Rex) → Rex = 1.85 Ω (source key prints "near 1.85 Ω", not among options).
**Concept:** Plugging current limit: Ia = (Vt + Eb)/(Ra + Rex).
**Twist:** Limit to full-load (100 A) → Rex = 3.8 Ω (option c, appears!). Limit to 1.5× → Rex = 2.5 Ω. Dynamic braking (no Vt) → Rex = 0.85 Ω.

**Q162 (TSSPDCL-AE-2023):** Pick up correct statements: a. lap winding may need dummy coils; b. lap winding needs equalizer rings; c. wave winding may need dummy coils; d. wave winding needs equalizer rings:
(a) a and b only (b) b and c only (c) c and d only (d) d and a only
**Ans: (b)** — Lap uses equalizer rings (b); wave may use dummy coils for mechanical balance (c).
**Concept:** Equalizer rings → lap; dummy coils → wave (odd slots).
**Twist:** Dummy coils carry no current but balance mechanically. Equalizer rings prevent circulating currents between lap paths.

**Q163 (TSSPDCL-AE-2023):** Armature reaction neglected, for a shunt motor at constant Vt, If: a. N vs Ia is linear; b. N vs Ia non-linear; c. T vs Ia linear; d. T vs Ia non-linear:
(a) a and d true (b) b and c true (c) a and c true (d) b and d true
**Ans: (c)** — Φ constant → T = KaΦIa linear (c) and N = (Vt−IaRa)/KaΦ linear in Ia (a).
**Concept:** Shunt motor with Φ constant: N–Ia and T–Ia both linear.
**Twist:** Include armature reaction (Φ falls with Ia) → N–Ia curve becomes non-linear (rises less). At high Ia, saturation → T–Ia bends.

**Q164 (TSSPDCL-AE-2023):** A 125 V dc shunt motor, ra = 0.5 Ω, rsh = 125 Ω, draws 11 A at 600 rpm (constant torque). If 125 Ω is added in the field circuit, new speed is
(a) 1150 (b) 1200 (c) 600 (d) 900
**Ans: (a)** — If = 1 A, Ia = 10 A, Eb1 = 120 V. New rsh = 250 → If2 = 0.5 → Φ halves → Ia2 = 20 A → Eb2 = 125−10 = 115 V → N2 = 600×(115/120)×2 = 1150 rpm.
**Concept:** Field weakening: N ∝ Eb/Φ; constant torque → ΦIa constant.
**Twist:** Adding 375 Ω (rsh = 500) → If = 0.25, Ia = 40, Eb = 105 → N2 = 1050×... compute: N2 = 600×(105/120)×4 = 2100 rpm (runaway risk). Full field restored → back to 600 rpm.

**Q165 (TSPSC-AEE-23):** A 6-pole, 248 A, dc shunt generator, 360 conductors, wave wound, field 2 A, brushes on GNA. Demagnetizing ampere-turns per pole at full load
(a) 500 Ats/pole (b) 2500 Ats/pole (c) 0 Ats/pole (d) 3000 Ats/pole
**Ans: (c)** — With brushes on the geometrical neutral axis, there is no demagnetizing component → 0 Ats/pole.
**Concept:** Brushes on GNA → only cross-magnetizing AR (demagnetizing AT = 0).
**Twist:** Shift brushes by θ° → demagnetizing AT = (Ia·Z/2πP)·(2θ/180). Q171 shows ATd ∝ θ (5°<10°<20°).

**Q166 (TSPSC-AEE-23):** Frequency f of the emf generated in the armature is given by
(a) 120P/NS (b) 120/PNS (c) 120NS/P (d) PNS/120
**Ans: (d)** — NS = 120f/P → f = PNS/120.
**Concept:** f = PNS/120 (Hz) for NS rpm.
**Twist:** 4-pole, 1500 rpm → f = 50 Hz. In a dc machine armature emf frequency equals commutator-segment passing rate.

**Q167 (TSPSC-AEE-23):** Current drawn by a 240 V dc motor, ra = 0.8 Ω, back emf 180 V
(a) 120 A (b) 8 A (c) 75 A (d) 150 A
**Ans: (c)** — Ia = (Vt − Eb)/Ra = (240−180)/0.8 = 75 A.
**Concept:** Motor: Ia = (Vt − Eb)/Ra.
**Twist:** Eb = 210 V → Ia = 37.5 A. Supply 200 V, Eb 180 → Ia = 25 A. At starting Eb = 0 → 300 A.

**Q168 (TSPSC-AEE-23):** Internal torque of a dc generator, Eg = 420 V, Ia = 20 A, N = 1200 rpm
(a) 66.81 N-m (b) 80 N-m (c) 20 N-m (d) 108.5 N-m
**Ans: (a)** — T = Eg·Ia/ω = 420×20/(2π×1200/60) = 8400/125.66 = 66.81 N-m.
**Concept:** T = P/ω = EgIa/ω (internal/electromagnetic torque).
**Twist:** Shaft torque uses output power (VtIa) minus mechanical losses → lower. N = 1500 rpm → T = 53.5 N-m.

**Q169 (TSPSC-AEE-23):** Identify the correct pair(s): I. Motoring: back emf Eg < supply voltage Va. II. Regenerative braking: induced voltage Eg must be > supply voltage Va.
(a) Only II (b) Neither I nor II (c) Only I (d) both I and II
**Ans: (d)** — Motoring needs Va > Eg; regenerative braking needs Eg > Va (machine feeds power back).
**Concept:** Modes: motoring Va > Eg; regenerating Eg > Va.
**Twist:** In dynamic braking, Eg drives current through a resistor (no supply). In plugging, Va and Eg aid each other (largest current).

**Q170 (TSPSC-AEE-23):** The expression for energy loss during starting of a motor is
(a) ∫i²R dt (b) iR (c) i²R (d) (di/dt)R
**Ans: (a)** — Energy lost in the armature/starting resistance during starting = ∫i²R dt.
**Concept:** Starting energy loss: W = ∫i²R dt = ½Jω² (rotor kinetic energy for one start).
**Twist:** For repeated starts (cranes), the loss accumulates. Adding a starting rheostat shifts the loss from armature to the rheostat.

**Q171 (TSPSC-AEE-23):** A wave-wound 12-pole, 116 A dc shunt generator, 360 conductors, field 4 A. Brushes shifted from GNA by I. 5°, II. 10°, III. 20° (electrical). Demagnetizing Ats/pole in increasing order
(a) III, II, I (b) I, III, II (c) III, I, II (d) I, II, III
**Ans: (d)** — ATd = (Ia·Z/2πP)(2θ/180) → ATd ∝ θ → 5° < 10° < 20° → I, II, III.
**Concept:** Demagnetizing AT ∝ brush-shift angle θ.
**Twist:** Cross-magnetizing AT ∝ (1 − θ): largest at 0° shift. At θ = 90° (full shift) all AR is demagnetizing.

**Q172 (TSPSC-AEE-23):** Machine efficiency η is defined as
(a) (Input + Losses)/Input (b) Input/(Input + Losses) (c) 1 − Losses/Input (d) Output/(Input + Losses)
**Ans: (c)** — η = Output/Input = (Input − Losses)/Input = 1 − Losses/Input.
**Concept:** η = Output/Input = 1 − (losses/input).
**Twist:** η = Output/(Output + Losses) is equivalent. At maximum efficiency, variable loss = constant loss.

**Q173 (TSGenco-24):** A 250 V dc shunt motor takes 41 A at 800 rpm full load, ra = 0.2 Ω, rsh = 250 Ω. During stalling, 2 Ω placed in series with armature. Ratio of stalling to full-load torque
(a) 1.42 (b) 2.84 (c) 1.25 (d) 3.13
**Ans: (b)** — If = 1 A, Ia = 40 A; stalling: Eb = 0, Ia = 250/2.2 = 113.6 A; T ∝ Ia → ratio = 113.6/40 = 2.84.
**Concept:** Torque ∝ Ia (Φ const); stalling current = Vt/(ra+Rext).
**Twist:** No external resistance (only ra) → Ia = 1250 A → ratio 31.2 (damaging). Extra 3 Ω → ratio 2.08.

**Q174 (TSGenco-24):** Self-excited dc generators fail to build up at no-load. Correct reasons: (i) absence of residual magnetism; (ii) field resistance < critical resistance; (iii) speed > critical speed; (iv) field resistance > critical resistance; (v) speed < critical speed:
(a) (i), (ii), (iii) only (b) (i), (iii), (iv) only (c) (i), (iv), (v) only (d) (i), (ii), (v) only
**Ans: (c)** — Build-up fails if residual magnetism absent (i), Rf > critical (iv), or speed < critical (v).
**Concept:** Self-excitation needs residual flux, Rf < critical, speed > critical.
**Twist:** Wrong field connection also prevents build-up (not listed). Reversing the field connection reverses build-up polarity.

**Q175 (TSGenco-24):** A short-shunt dc compound generator supplies 100 A at 250 V; rsh = 130 Ω, ra = 0.1 Ω, rse = 0.1 Ω, brush drop 1 V/brush. EMF generated
(a) 270.2 V (b) 260.2 V (c) 262.2 V (d) 272.2 V
**Ans: (d)** — Ish = (250+100×0.1)/130 = 2 A; Ia = 102 A; Eg = 250 + 102×0.1 + 100×0.1 + 2 = 272.2 V.
**Concept:** Short-shunt: Ish = (Vt + Ise·rse)/rsh; Eg = Vt + IaRa + IseRse + brush drop.
**Twist:** Long-shunt connection: Ish = Vt/rsh → Ish = 1.923 A, Ia = 101.92, Eg = 250 + 10.19 + 10 + 2 = 272.2 V (close). Brush drop 0 → Eg = 270.2 V (option a trap).

## Unit 3: Induction Machines (183 Qs)

## Construction, RMF Theory

**Q1 (SSC-JE-13):** In squirrel-cage induction motor, the rotor conductors are
(a) open circuited (b) short circuited via end rings (c) short circuited via external reactance (d) short circuited via external resistance
**Ans: (b)** — Cage rotor bars are permanently shorted by the end rings at both ends.
**Concept:** Squirrel-cage rotor construction (bars + end rings).
**Twist:** Slip-ring rotor instead → rotor winding is open (star-connected terminals brought out) → answer changes to "wound rotor with external access". If the cage is double-cage → inner/outer bars shorted together by common end rings → still (b).

**Q2 (EPDCL-14):** A smaller air gap in a poly-phase induction motor helps to
(a) Reduce the chance of crawling (b) Increase the starting torque (c) Reduce the chance of cogging (d) Reduce the magnetizing current
**Ans: (d)** — Smaller air gap lowers reluctance → lower magnetizing mmf/current.
**Concept:** Magnetizing current ∝ air-gap reluctance; Xm ∝ 1/air-gap.
**Twist:** Air gap increased → magnetizing current rises and leakage reactance rises → no-load current increases. Smaller air gap also → less leakage flux → better power factor but higher noise/harmonics.

**Q3 (EPDCL-14):** The rotor of a 3-phase induction motor rotates in the same direction as that of stator rotating field. This can be explained by
(a) Faraday's law of electromagnetic induction (b) Lenz's law (c) Newton's law (d) Fleming's right-hand rule
**Ans: (b)** — Lenz's law: induced rotor currents oppose the relative motion, pulling the rotor to chase the field.
**Concept:** Lenz's law → motoring torque direction.
**Twist:** Ask "explains induced EMF direction" → Lenz's law again (Q13). Ask speed of rotor field wrt stator field → rotor field always rotates at Ns (0 rpm relative to stator field), never at 1440 rpm.

**Q4 (ISRO-14):** Dispersion coefficient σ is the coefficient of
(a) magnetizing current to supply voltage (b) open circuit voltage to short circuit current for the same excitement (c) magnetizing current to ideal short circuit current (d) short circuit current to magnetizing current
**Ans: (c)** — σ = magnetizing current / ideal short-circuit current.
**Concept:** Dispersion coefficient (stator leakage measure).
**Twist:** Relate to leakage reactance → larger σ means higher stator leakage. Ask "ideal short circuit" (no leakage) vs actual short circuit → ratio distinguishes leakage.

**Q5 (SSC-JE-S1-14):** The rotor slots, in an induction motor are usually not quite parallel to the shaft because it:
(a) improves the efficiency (b) helps the rotor teeth to remain under the stator teeth (c) helps in reducing the tendency of the rotor teeth to remain under the stator teeth (d) improves the power factor
**Ans: (c)** — Skewing avoids magnetic locking (cogging) between stator and rotor teeth.
**Concept:** Skewing of rotor slots.
**Twist:** Ask purpose of skewing directly → "eliminate locking tendency and reduce noise". Skewing also reduces harmonic/cogging torques and crawling, not efficiency or pf directly.

**Q6 (SSC-JE-SI-14):** The synchronous speed of a three-phase induction motor having 20 poles and connected to a 50 Hz source is:
(a) 300 rpm (b) 600 rpm (c) 1000 rpm (d) 1200 rpm
**Ans: (a)** — Ns = 120f/P = 120×50/20 = 300 rpm.
**Concept:** Ns = 120f/P.
**Twist:** 10 poles at 50 Hz → 600 rpm. Doubling poles → Ns halves; halving frequency → Ns halves.

**Q7 (HMWS-15):** The power factor of an induction motor at no load is around
(a) 0.8 lag (b) 0.2 lag (c) 0.5 lag (d) 0.2 lead
**Ans: (b)** — No-load current is mainly magnetizing (reactive) → very low pf ~0.1–0.2 lag.
**Concept:** No-load pf = very low lagging (magnetizing component dominates).
**Twist:** At full load → pf rises to 0.8–0.9 lag. It can never be leading on its own (motor draws magnetizing reactive power).

**Q8 (TSGenco-15):** A 400 V, 50Hz three phase induction motor rotates at 1440 rpm on full load. The motor is wound for
(a) 2 poles (b) 4 poles (c) 6 poles (d) 8 poles
**Ans: (b)** — Ns must be just above 1440 → 1500 rpm → P = 120×50/1500 = 4 poles.
**Concept:** Ns = 120f/P; Ns > Nr.
**Twist:** Rotor at 960 rpm → 6 poles (Ns=1000). Rotor at 720 rpm → 8 poles (Ns=750).

**Q9 (AP Transco-17):** A 3-phase, 4-pole, 50Hz induction motor runs at a speed of 1440 rpm. The rotating field produced by the rotor rotates at a speed of ____ rpm with respect to stator field
(a) 1500 (b) 0 (c) 1440 (d) 60
**Ans: (b)** — Rotor field and stator field are always stationary relative to each other (0 rpm); they must be in synchronism to produce torque.
**Concept:** Rotor field speed wrt stator field = 0 (always Ns).
**Twist:** Wrt rotor (at 1440 rpm) the field moves at 60 rpm (slip speed). Ask speed wrt stator → always 0.

**Q10 (TS Transco-18):** Rotor slot of the squirrel cage induction motor are skewed slightly, so as to
(a) increase the mechanical strength of rotor (b) make the rotor construction simple (c) eliminate locking tendency of the rotor and to reduce the noise (d) save the amount of copper required
**Ans: (c)** — Skewing eliminates magnetic locking (cogging) and reduces noise/harmonics.
**Concept:** Skewing → cogging/crawling suppression.
**Twist:** Skewing also reduces harmonic torques (asynchronous harmonics) → correct statement. It does NOT save copper or increase strength.

**Q11 (APEPDCL-19):** The total number of slots on the stator of a three phase 6-pole induction motor having 3 slots per pole per phase is
(a) 54 (b) 9 (c) 18 (d) 27
**Ans: (a)** — S = m·P·slots/pole/phase = 3×6×3 = 54.
**Concept:** Total slots = phases × poles × slots-per-pole-per-phase.
**Twist:** 4-pole, 4 slots/pole/phase, 3-phase → 48. Single-phase (m=1) 6-pole, 3 spp → 18.

**Q12 (APEPDCL-19):** If the peak value of phase mmf is Fmax. then the peak value of the rotating field caused by three phases is
(a) 1.5 Fmax (b) 0.5 Fmax (c) Fmax (d) 3Fmax
**Ans: (a)** — Resultant peak mmf = (3/2)·Fmax.
**Concept:** Three-phase resultant mmf = 1.5 × per-phase peak mmf.
**Twist:** If asked RMS or fundamental of resultant → still 1.5× the phase peak (m=3 gives 3/2 factor). If 6-phase (m=6) → 3 Fmax.

**Q13 (APSPDCL-19):** The law which gives the direction of the induced e.m.f is
(a) Faraday's law (b) Biot-Savart law (c) Lenz's law (d) Fleming's left-hand rule
**Ans: (c)** — Direction of induced EMF is given by Lenz's law.
**Concept:** Lenz's law vs Faraday's law (magnitude).
**Twist:** Ask magnitude of induced EMF → Faraday's law (e = -dφ/dt). Direction of force on conductor → Fleming's left-hand rule.

**Q14 (TSPSC-AEE-23):** Which option is correct in relation to electrical degree and mechanical degree?
(a) θelect = 2θmech/P (b) θelect = (P/2)θmech (c) θelect = θmech/P (d) θelect = P·θmech
**Ans: (b)** — θelectrical = (P/2)·θmechanical.
**Concept:** θe = (P/2)θm.
**Twist:** For P = 4, 360° mech → 720° elect. Ask per-pole arc → 180° elect = 360°/P mech.

## Basics and Slip Concepts

**Q15 (EPDCL-10):** A 50 Hz, 3-phase induction motor has a full load speed of 1440 rpm. The number of poles of the motor is
(a) 4 (b) 6 (c) 12 (d) 8
**Ans: (a)** — Ns just above 1440 is 1500 → 4 poles.
**Concept:** Ns = 120f/P.
**Twist:** F.L. speed 960 rpm → 6 poles; 720 rpm → 8 poles; 2850 rpm → 2 poles.

**Q16 (EPDCL-10):** A 3-phase cage rotor induction motor has its stator wound for 8 poles. The rotor of this motor can be used in any other induction motor of the same size and having
(a) 4 poles (b) 8 poles (c) 50 Hz (d) any number of poles
**Ans: (d)** — Cage rotor has no defined poles; it automatically develops the stator pole number.
**Concept:** Cage rotor pole-adaptivity.
**Twist:** Wound/slip-ring rotor → must match stator pole count (poles fixed). This is why cage rotors are interchangeable.

**Q17 (SSC-JE-10):** A 4-pole, 3-phase induction motor is running at 4% slip at full load. If the speed of the motor is 750 rpm, the supply frequency is:
(a) 16 2/3 Hz (b) 25 Hz (c) 50 Hz (d) 60 Hz
**Ans: (b)** — Ns = 750/0.96 = 781.25 rpm; f = P·Ns/120 = 4×781.25/120 = 26 Hz ≈ 25 Hz.
**Concept:** s = (Ns−Nr)/Ns, Ns = 120f/P.
**Twist:** s=4%, Nr=1440 → f=50 Hz (Ns=1500). Same method, s=2% → f slightly less.

**Q18 (AP Genco-12):** The name plate of a 3-phase induction motor reads V=400V, hp=5, f=50Hz, I=15A, Δ-connected, N=540 rpm. The number of poles for which stator winding is wound
(a) 10 (b) 12 (c) 14 (d) 16
**Ans: (a)** — Ns nearest above 540 is 600 → P = 120×50/600 = 10 poles.
**Concept:** Ns = 120f/P from nameplate speed.
**Twist:** N=290 rpm → 20 poles (Ns=300). N=720 → 8 poles (Ns=750).

**Q19 (AP Transco-12):** A 3-phase, 440V, 50Hz induction motor has 4% slip. The frequency of rotor emf will be
(a) 0.2 Hz (b) 2 Hz (c) 50 Hz (d) 200 Hz
**Ans: (b)** — f2 = s·f1 = 0.04×50 = 2 Hz.
**Concept:** rotor frequency = s·f.
**Twist:** s=10% → 5 Hz. Blocked rotor s=1 → 50 Hz (rotor freq = supply freq).

**Q20 (APSPDCL-12):** A 3-phase induction motor is run in counter clockwise direction as motor with reverse phase sequence of supply. The range of slip variation for this mode is
(a) 0 < s < 1 (b) 2 < s < 1 (c) 0 < s < –1 (d) 3 < s < 2
**Ans: (a)** — Motoring (any direction) keeps slip 0 < s ≤ 1.
**Concept:** Slip regions (motoring 0–1, generating <0, plugging 1–2).
**Twist:** Reverse rotation by phase reversal still motoring → 0<s≤1. Regeneration → s<0; plugging → 1<s<2.

**Q21 (HMWS-12):** One of the speeds of a 2-speed squirrel cage induction motor is 600 rpm (lower speed). The other speed will be
(a) 400 rpm (b) 2400 rpm (c) 1600 rpm (d) 1200 rpm
**Ans: (d)** — 2-speed cage motor via pole change (2:1 ratio) → 600×2 = 1200 rpm.
**Concept:** Pole-changing speed control (2:1 pole ratio).
**Twist:** Lower speed 750 rpm → higher 1500 rpm. Consequent-pole winding gives 2:1 speed steps.

**Q22 (HMWS-12):** A 4-pole, 50 Hz single phase induction motor has a slip of 5%. The speed of the motor will be
(a) 1425 rpm (b) 1500 rpm (c) 1200 rpm (d) 800 rpm
**Ans: (a)** — Nr = (1−s)Ns = 0.95×1500 = 1425 rpm.
**Concept:** Nr = (1−s)Ns.
**Twist:** Slip 2% → 1470 rpm. 6-pole (Ns=1000), 5% → 950 rpm.

**Q23 (SSC-JE-S1-14):** A 3-phase, 4 pole induction motor works on 3-phase, 50 c/s supply. If the slip of the motor is 4%. The actual speed will be
(a) 1550 rpm (b) 1460 rpm (c) 1440 rpm (d) 720 rpm
**Ans: (c)** — Nr = (1−0.04)×1500 = 1440 rpm.
**Concept:** Nr = (1−s)Ns.
**Twist:** 2% slip → 1470 rpm. 4% slip on 6-pole (Ns=1000) → 960 rpm.

**Q24 (SSC-JE-S2-14):** A 4-pole, 3-phase induction motor runs at 1440 rpm on a 50 Hz supply. Find the slip speed
(a) 2940 rpm (b) 1500 rpm (c) 1440 rpm (d) 60 rpm
**Ans: (d)** — Slip speed = Ns − Nr = 1500 − 1440 = 60 rpm.
**Concept:** slip speed = Ns − Nr = s·Ns.
**Twist:** Rotor frequency = slip speed × (P/120) = 60×4/120 = 2 Hz. If Nr = 1450 → slip speed 50 rpm.

**Q25 (TSGenco-15):** The slip of 400 V, three phase, 4-pole induction motor when rotating at 1440 rpm is
(a) 2% (b) 3% (c) 4% (d) 5%
**Ans: (c)** — s = (1500−1440)/1500 = 0.04.
**Concept:** s = (Ns−Nr)/Ns.
**Twist:** 1455 rpm → 3%. 1425 rpm → 5%.

**Q26 (TSSPDCL-22):** A three-phase, 6-pole induction motor on full-load runs at 920 rpm. It is supplied from a 4-pole alternator running at 1500 rpm. Calculate the full-load slip of the motor.
(a) 0.02 (b) 0.04 (c) 0.08 (d) 0.06
**Ans: (c)** — Alternator f = 1500×4/120 = 50 Hz; Ns(motor) = 120×50/6 = 1000; s = (1000−920)/1000 = 0.08.
**Concept:** Ns = 120f/P + slip.
**Twist:** 8-pole alternator at 1500 rpm → f=100 Hz → Ns=2000, s = (2000−1920)/2000 = 0.04. Two machines linked by same supply frequency.

**Q27 (TSSPDCL-22):** A 12-pole induction motor is fed from a 100 Hz supply. If the frequency of the rotor EMF at full-load is 2 Hz. Find the full-load speed.
(a) 960 rpm (b) 980 rpm (c) 940 rpm (d) 920 rpm
**Ans: (b)** — s = 2/100 = 0.02; Ns = 120×100/12 = 1000; Nr = 0.98×1000 = 980 rpm.
**Concept:** f2 = s·f1 → s; then Nr = (1−s)Ns.
**Twist:** Rotor EMF 5 Hz at 100 Hz supply → s=0.05 → Nr=950. Rotor freq at standstill = supply freq.

**Q28 (TSNPDCL-22):** A 3-phase, 440 V, 50 Hz induction motor full load slip is 10%. Then at full load speed, the frequencies of stator current and rotor current are
(a) 45 Hz and 45 Hz (b) 50 Hz and 5 Hz (c) 45 Hz and 5 Hz (d) 50 Hz and 45 Hz
**Ans: (b)** — Stator current frequency = supply 50 Hz; rotor = s·f = 0.1×50 = 5 Hz.
**Concept:** f2 = s·f1; stator frequency = f1.
**Twist:** s = 4% → rotor 2 Hz. Under locked rotor (s=1) → rotor = 50 Hz.

**Q29 (TSSPDCL-AE-23):** In operation of 3-φ induction motor, Fr is air-gap m.m.f., F2 rotor m.m.f., θ2 the angle by which rotor current lags rotor e.m.f. Correct statement?
(a) Fr leads F2 by (90 + θ2)° (b) Fr lags F2 by (90 + θ2)° (c) Fr leads F2 by (90 − θ2)° (d) Fr lags F2 by (90 − θ2)°
**Ans: (a)** — Air-gap mmf Fr leads rotor mmf F2 by (90 + θ2)°.
**Concept:** MMF phasor relation in induction motor.
**Twist:** At unity rotor pf (θ2 = 0) → Fr leads F2 by 90°. Rotor reactance dominant (θ2 large) → lead angle larger than 90°.

**Q30 (TSPSC-AEE-23):** A properly shunted centre-zero galvanometer is connected in the rotor circuit of a 4 pole, 50 Hz wound-rotor induction motor. If the galvanometer makes 120 complete oscillations in one minute, calculate the rotor speed.
(a) 1000 rpm (b) 1440 rpm (c) 1200 rpm (d) 960 rpm
**Ans: (b)** — fr = 120/60 = 2 Hz → s = 2/50 = 0.04 → Nr = 0.96×1500 = 1440 rpm.
**Concept:** rotor frequency = s·f (measured via oscillations).
**Twist:** 60 oscillations/min → fr=1 Hz → s=0.02 → Nr=1470. Galvanometer measures slip frequency directly.

**Q31 (TSGenco-24):** The time-period of rotor current of a 3-φ, 4-pole, 50 Hz induction motor is 200 ms. Then slip speed of the motor is
(a) 150 rpm (b) 1350 rpm (c) 75 rpm (d) 1425 rpm
**Ans: (a)** — fr = 1/0.2 = 5 Hz → s = 5/50 = 0.1 → slip speed = s·Ns = 0.1×1500 = 150 rpm.
**Concept:** slip speed = s·Ns = f2×(120/P).
**Twist:** T = 500 ms → fr=2 Hz → s=0.04 → slip speed 60 rpm. Period 100 ms → 300 rpm slip speed.

## Equivalent Circuit

**Q32 (HMWS-12):** The low power factor of an induction motor (3-phase) at low load results from
(a) high speed (b) low magnetizing component of no-load current I0 (c) high magnetizing component of no-load current I0 (d) high working component of no load current I0
**Ans: (c)** — At light load the no-load current is dominated by the magnetizing (reactive) component → very low lagging pf.
**Concept:** No-load current = magnetizing (reactive) + loss component.
**Twist:** Add capacitor/excitation → pf improves (Q117/Q121). Reduce air gap → less magnetizing current → higher pf.

**Q33 (HMWS-12):** If the air gap between the rotor and stator of a 3-phase induction motor is increased, then
(a) no-load current is decreased (b) leakage reactance is increased (c) leakage reactance is decreased (d) magnetizing current is decreased
**Ans: (b)** — Larger air gap → more leakage flux → leakage reactance increases; also magnetizing current increases.
**Concept:** Air gap ↑ → leakage reactance ↑, Xm ↓, magnetizing current ↑.
**Twist:** This raises no-load current and worsens pf. Air gap ↓ → magnetizing current ↓ (Q2).

**Q34 (HMWS-12):** The 3-phase induction motor is so designed that the rotor should have __ under running conditions.
(a) high resistance (b) high reactance (c) low resistance (d) large slip
**Ans: (c)** — Low rotor resistance → low Cu loss → high efficiency and low slip at full load.
**Concept:** Rotor designed for low R2 (running) — high R2 only useful at start.
**Twist:** High rotor resistance improves starting torque but hurts running efficiency (Q57). This is why slip-ring rotors use external resistance only during starting.

**Q35 (TS Transco-18):** The emf induced per phase in the rotor winding of a 3-phase induction motor is 100V at standstill. Under full load condition, this emf would be normally
(a) 100V (b) 50V (c) 4V (d) 0.2V
**Ans: (c)** — E2(FL) = s·E2(standstill) ≈ 0.05×100 = 5 V (closest 4 V).
**Concept:** Rotor EMF = s × standstill EMF.
**Twist:** Slip 2% → 2 V. At standstill (s=1) → 100 V (same as standstill). Rotor frequency follows same s-factor.

## Power Flow Diagram

**Q36 (SSC-JE-10):** The power input to a 3-phase, 50 Hz, 400 V, 4-pole induction motor is 60 kW and its stator losses are 1kW. If this motor is running at 4% slip, the rotor copper loss is
(a) 1.18 kW (b) 2.36 kW (c) 0.18 kW (d) 0.36 kW
**Ans: (b)** — Pag = 60−1 = 59 kW; Pcu(rotor) = s·Pag = 0.04×59 = 2.36 kW.
**Concept:** Pcu(rotor) = s·Pag.
**Twist:** Slip 2% → 1.18 kW. If rotor Cu loss given (2.36 kW) and s=0.04 → Pag = 59 kW.

**Q37 (HMWS-12):** In a 3-phase induction motor, the ratio of rotor copper loss and rotor input is given by
(a) s (b) 1/s (c) 1–s (d) s/(1–s)
**Ans: (a)** — Pcu(rotor)/Pag = s.
**Concept:** s = rotor Cu loss / air-gap power.
**Twist:** Rotor Cu loss / mechanical power developed = s/(1−s). Mechanical power / rotor input = (1−s).

**Q38 (HMWS-12):** A 3-phase induction motor is running at 2% slip. If the input to rotor is 1000W, then mechanical power developed by the motor is
(a) 20 W (b) 500 W (c) 200 W (d) 980 W
**Ans: (d)** — Pmech = (1−s)·Pag = 0.98×1000 = 980 W.
**Concept:** Pmech = (1−s)Pag.
**Twist:** s=2%, Pag=1000 → rotor Cu loss = 20 W. s=5% → Pmech = 950 W.

**Q39 (SSC-JE-12):** Slip of a 3-phase induction motor may be expressed as
(a) rotor copper loss/rotor power input (b) rotor copper loss/total input power (c) rotor power input/rotor copper loss (d) rotor copper loss/rotor core loss
**Ans: (a)** — s = rotor Cu loss / rotor input (air-gap power).
**Concept:** Slip definitions via power.
**Twist:** Rotor Cu loss/stator input is NOT slip (that's why (b) wrong). Add (1−s) ratio → mechanical power.

**Q40 (APSPDCL-14):** A 3-phase squirrel cage induction motor draws 10 kW from mains when loaded at a slip of 0.05. The stator losses and mechanical losses are 1kW and 550 W respectively. Its efficiency is
(a) 70% (b) 80% (c) 90% (d) 60%
**Ans: (b)** — Pag = 9 kW; Pmech = 0.95×9 = 8.55; Pout = 8.55−0.55 = 8 kW; η = 8/10 = 80%.
**Concept:** η = Pout/Pin via power-flow (Pag, Pmech, Pout).
**Twist:** Slip 2% → Pmech = 8.82 → η ≈ 82.7%. Stator loss 2 kW → Pag = 8 kW → η lower.

**Q41 (ISRO-14):** A 6 pole, 50 Hz, 3-φ induction motor is running at 950 rpm and has rotor Cu loss of 5kW. Its rotor input is ___ kW.
(a) 100 (b) 10 (c) 95 (d) 5.3
**Ans: (a)** — s = (1000−950)/1000 = 0.05; Pag = 5/0.05 = 100 kW.
**Concept:** Pag = Pcu(rotor)/s.
**Twist:** 8-pole at 705 rpm (s=0.06), Pcu=5 kW → Pag = 83.33 kW (Q43). s=0.1 → Pag = 50 kW.

**Q42 (TSSPDCL-15):** The input and efficiency of a 3-φ, 50 Hz, 1350 rpm, 4 pole induction motor is 9 kW and 80% respectively. Calculate its stator losses.
(a) 900 W (b) 1.80 kW (c) 1 kW (d) 1.75 kW
**Ans: (c)** — Pout = 7.2 kW; s = 0.1; Pag = 7.2/0.9 = 8 kW; Pstator = 9−8 = 1 kW.
**Concept:** Power-flow: Pstator loss = Pin − Pag.
**Twist:** η=90% → Pout=8.1 → Pag=9 → Pstator≈0. If mech losses non-negligible, subtract before computing Pag.

**Q43 (AP Transco-17):** An 8-pole, 50 Hz, three phase induction motor is running at 705 rpm and has a rotor copper loss of 5kW. Its rotor input is
(a) 5.06 kW (b) 0.3 kW (c) 100 kW (d) 83.33 kW
**Ans: (d)** — Ns = 750; s = 45/750 = 0.06; Pag = 5/0.06 = 83.33 kW.
**Concept:** Pag = Pcu(rotor)/s.
**Twist:** Slip speed fixed at 45 rpm but 6-pole (Ns=1000) → s=0.045 → Pag = 111 kW. Given Pcu and s, Pag independent of pole count once s known.

**Q44 (TS Transco-18):** A 3-phase induction motor runs at 3% slip and develops mechanical power equal to 10 kW. The air gap power is
(a) 9.7 kW (b) (10/0.97) kW (c) 10.30 kW (d) 10.03 kW
**Ans: (c)** — Pag = Pmech/(1−s) = 10/0.97 = 10.30 kW.
**Concept:** Pag = Pmech/(1−s).
**Twist:** s=5% → Pag = 10.53 kW. Rotor Cu loss = s·Pag = 0.03×10.3 = 0.31 kW.

**Q45 (APEPDCL-19):** The slip of an induction motor is the ratio of
(a) rotor copper loss of rotor output (b) stator copper loss of stator input (c) rotor copper loss to rotor input (d) rotor copper loss to stator input
**Ans: (c)** — Slip = rotor Cu loss / rotor input (air-gap power).
**Concept:** Slip from power ratios.
**Twist:** Slip = rotor Cu loss/rotor input ≠ stator Cu loss/input (option b trap). Mechanical power/rotor input = 1−s.

**Q46 (APSPDCL-19):** The following loss in electrical machine does not produce heat
(a) Copper losses (b) Eddy current loss (c) Hysteresis loss (d) Frictional loss
**Ans: (—)** — Every listed loss (Cu, eddy, hysteresis, friction) produces heat; no option is correct (key: "every power loss produces heat").
**Concept:** All machine losses → heat.
**Twist:** If asked "loss converted to heat except stored energy" → none. If forced to pick the "least heat" → friction also heats bearings → still heat.

## Torque Equations

**Q47 (AP Transco-12):** The maximum torque in an induction motor depends on
(a) Frequency (b) Rotor resistance (c) Supply current (d) Stator Inductance
**Ans: (a)** — Tmax = (3E2²)/(ωs·2X2); independent of rotor resistance, depends on supply frequency/reactance.
**Concept:** Tmax ∝ E²/ωs·X2 — independent of R2.
**Twist:** Rotor resistance ↑ → Tmax unchanged (Q56) but slip at Tmax ↑. Frequency ↑ → Tmax ↓.

**Q48 (HMWS-12):** If the supply voltage of a 3-phase induction motor is increased two times, then torque is
(a) increased two times (b) increased four times (c) decreased two times (d) decreased four times
**Ans: (b)** — T ∝ V².
**Concept:** T ∝ V².
**Twist:** V ×3 → T ×9. V reduced to half → T to 1/4 (Q50). This is the basis of stator voltage control.

**Q49 (Transco-12):** When the supply voltage to an induction motor is reduced by 10%, the maximum torque will decrease by approximately
(a) 5% (b) 10% (c) 20% (d) 40%
**Ans: (c)** — Tmax ∝ V² → (0.9)² = 0.81 → ~19% ≈ 20% decrease.
**Concept:** Tmax ∝ V².
**Twist:** V reduced 20% → torque 64% (36% decrease). V reduced 5% → ~10% decrease.

**Q50 (TS Genco-15):** Torque developed by a three-phase, 400V, induction motor is 100N-m. If the applied voltage is reduced to 200-V, the developed torque will be
(a) 50 N-m (b) 25 N-m (c) 200 N-m (d) 62.8 N-m
**Ans: (b)** — T ∝ V² → (200/400)²×100 = 25 N-m.
**Concept:** T ∝ V².
**Twist:** V reduced to 1/3 → T to 1/9. V doubled → 400 N-m.

**Q51 (TSTransco-15):** In an induction motor, if the flux density is reduced to one-half of its normal value, then the torque will
(a) reduce to one-half (b) reduce to one-fourth (c) remain unchanged (d) increase four times
**Ans: (a)*** — T ∝ Bm·V (∝ Bm at constant V); halving Bm halves torque (key marks it (*), not a listed option certainty).
**Concept:** T ∝ Bm; torque = (P/ωs)·(2π/... )·Bm² effectively ∝ Bm² if everything scales.
**Twist:** If both flux and current scale → T ∝ Bm² → one-fourth (option b). Halving flux also reduces saturation and current.

**Q52 (TSNPDCL-15):** A double cage induction motor has better starting and running characteristics because: (1) inner cage high R & X (2) inner cage low R & high X (3) outer cage high R & low X (4) outer cage low R & X. They are:
(a) 2, 4 (b) 1, 3 (c) 2, 3 (d) 1, 4
**Ans: (c)** — Inner cage: low R, high X; outer cage: high R, low X.
**Concept:** Double-cage rotor (outer high-R low-X, inner low-R high-X).
**Twist:** At start (slip high, f2 high) outer cage (high R) dominates → high starting torque; at run (low f2) inner cage (low R) dominates → low slip, good efficiency. Curve A (inner) has lower resistance than curve B (outer) — Q72.

**Q53 (TSNPDCL-15):** A 3-φ, 6 Pole induction motor is run with a rated voltage V and rated frequency 50 Hz. The maximum torque obtained is Tmt. If the motor is supplied with same voltage but a frequency of 60 Hz, the maximum torque would be approximately.
(a) 0.7 Tmt (b) 0.5 Tmt (c) 1.2 Tmt (d) Tmt
**Ans: (a)** — Tmax ∝ 1/f² → Tm2 = (50/60)²·Tmt = 0.694 ≈ 0.7 Tmt.
**Concept:** Tmax ∝ V²/f².
**Twist:** f halved (V constant) → Tmax ×4. With V/f constant → Tmax unchanged (Q99).

**Q54 (TSNPDCL-15):** A six pole, 3 phase 50Hz induction motor has a maximum torque of 10 Nm at 875 rpm. The torque at 5% slip is:
(a) 7.4 Nm (b) 5.2 Nm (c) 7.2 Nm (d) 6.9 Nm
**Ans: (d)** — Ns=1000, Smt=0.125; Te/Tmax = 2·Smt·s/(Smt²+s²) → Te = 10×(0.0125/0.018125) = 6.9 Nm.
**Concept:** Te/Tmax = 2·s·Smt/(s²+Smt²).
**Twist:** s=0.05 but Smt=0.125; if s=Smt → torque = Tmax. s=0.02 → Te smaller.

**Q55 (AP Transco-17):** The torque developed by any 3-phase induction motor at 0.8 p.u. slip is
(a) full-load torque (b) unstable torque (c) starting torque (d) break down
**Ans: (b)** — s=0.8 lies in the unstable (braking/overshoot) region of the T–s curve.
**Concept:** T–s curve regions (stable low-slip; unstable near s>smt).
**Twist:** s=0.05 (normal) → stable/full-load region. s=1 → starting torque. s=0.2 (smt) → breakdown torque.

**Q56 (TS Transco-18):** Maximum torque developed by a three-phase induction motor
(a) increases with increase in rotor resistance (b) decrease with increase in rotor resistance (c) is independent of rotor resistance (d) increases with decrease in rotor resistance
**Ans: (c)** — Tmax independent of rotor resistance; only slip at Tmax shifts.
**Concept:** Tmax independent of R2.
**Twist:** R2 doubled → Tmax same but Smt doubled (Q175). Starting torque (s=1) DOES rise with R2 up to Smt=1.

**Q57 (APEPDCL-19):** In a slip ring induction motor, if the rotor resistance is increased, then
(a) starting torque and efficiency increase (b) starting torque decreases but efficiency decreases (c) starting torque increases and efficiency decreases (d) starting torque and efficiency decrease
**Ans: (c)** — Tst ∝ R2 increases, but extra I²R raises Cu loss → efficiency falls.
**Concept:** R2 ↑ → Tst ↑, η ↓.
**Twist:** Too much R2 → Tst falls after Smt>1. This is exactly why external rotor resistance is used only during starting then shorted.

**Q58 (APEPDCL-19):** Maximum torque developed by an induction motor when the phase difference between stator flux and rotor current is
(a) 60° electrical (b) 0° electrical (c) 90° electrical (d) 45° electrical
**Ans: (c)** — Tmax when rotor current lags flux by 90° (i.e., φ2=45° gives T∝sin2φ2 max... key: 90°).
**Concept:** T ∝ Φ·I2·cosφ2; max when current in phase; standard key: phase diff 90° for max torque in IM torque equation.
**Twist:** Ask "phase angle between stator flux and rotor EMF" → rotor EMF lags flux by 90°. At Smt, rotor pf = 1/√2 (45°).

**Q59 (APEPDCL-19):** The starting current of a 3-φ induction motor is 5 times the rated current, while the full load slip is 4%. The ratio of starting torque to full load torque is
(a) 1.2 (b) 1.0 (c) 1.6 (d) 0.8
**Ans: (b)** — Tst/Tfl = (Ist/Ifl)²·sfl = 25×0.04 = 1.0.
**Concept:** Tst/Tfl = (Ist/Ifl)²·sfl.
**Twist:** Ist=5I, sfl=2% → ratio 0.5. Ist=6I, sfl=5% → 1.8.

**Q60 (TSSPDCL-AE-2023):** A 3-φ squirrel cage induction motor has a slip corresponding to maximum torque is 20%. Its starting current is five times the full-load current, then the full-load slip is
(a) 3% (b) 4% (c) 5% (d) 2%
**Ans: (b)** — Tst/Tfl = (Ist/Ifl)²·sfl·(Smt²+1)/(Smt²+sfl²); solving 25·sfl = (0.04+sfl²)/((1.04)·sfl) → sfl = 4%.
**Concept:** Full T–s ratio with Smt; not the simple (I ratio)²·sfl.
**Twist:** If Smt=1 (max starting torque at start) → Tst/Tfl = (Ist/Ifl)²·sfl directly. This is the "examiner twist" on Q59 — don't use simple formula when Smt≠1.

**Q61 (TSPSC-AEE-23):** Identify the correct statement related to the induction motor. I. It has inherent self-starting torque. II. It can operate only at lagging power factors.
(a) Both I and II (b) Only I (c) Only II (d) Neither I nor II
**Ans: (a)** — 3-φ IM is inherently self-starting (rotating field), and it always draws lagging reactive magnetizing current.
**Concept:** Self-starting + always lagging pf of 3-φ IM.
**Twist:** 1-φ IM is NOT self-starting (torque zero at start, Q170). Over-excited synchronous machine can run at leading pf, but IM cannot.

## Characteristics

**Q62 (EPDCL-10):** At s = 0 the torque of an induction motor is
(a) 0 (b) equal to full load (c) Very high (d) nearly zero
**Ans: (a)** — At synchronous speed, slip is zero → no induced rotor current → T = 0.
**Concept:** T = 0 at s = 0.
**Twist:** s=1 (standstill) → starting torque. s=0.04 → full-load torque. This is why the motor can never reach Ns (needs slip for torque).

**Q63 (SSC-JE-10):** In a 3-phase induction motor starting torque will be maximum when: (R2 rotor resistance, X2 rotor reactance)
(a) R2 = 1/X2 (b) R2 = X2 (c) R2 = X2² (d) R2 = X2
**Ans: (b)** — Max starting torque when rotor resistance equals standstill rotor reactance (R2 = X2, i.e., Smt = 1).
**Concept:** max starting torque at R2 = X2.
**Twist:** R2=2X2 → Smt=2>1 → starting torque falls below max. At start f2=f1 so X2 is standstill reactance.

**Q64 (AP Genco-12):** The rotor impedance of a slip ring induction motor is (0.1 + j0.6) Ω/ph. The resistance/ph to be inserted into rotor to get maximum torque at starting should be
(a) 0.1 Ω (b) 0.3 Ω (c) 0.4 Ω (d) 0.5 Ω
**Ans: (d)** — rex = X2 − r2 = 0.6 − 0.1 = 0.5 Ω.
**Concept:** For max Tst: r2 + rex = X2.
**Twist:** r2=0.02, X2=0.2 → rex=0.18 Ω (Q69). If r2 already = X2 → no external resistance needed.

**Q65 (HMWS-12):** A high starting torque can be obtained in a 3-phase induction motor by
(a) increasing rotor resistance (b) decreasing rotor resistance (c) increasing rotor reactance (d) keeping rotor resistance constant
**Ans: (a)** — Increasing rotor resistance (up to R2=X2) boosts starting torque.
**Concept:** Tst ∝ R2 (until Smt=1).
**Twist:** Rotor resistance increased too much → starting torque drops again (peak at R2=X2). For cage motors, can't add R externally → use double cage.

**Q66 (EPDCL-14):** In a three-phase slip ring induction motor high starting torque is achieved by
(a) Increase supply voltage (b) Increase supply frequency (c) Connecting a capacitor across the motor terminals (d) Connecting a star connected resistance across the slip ring terminals of the motor
**Ans: (d)** — External star-connected resistance in rotor circuit boosts starting torque.
**Concept:** Rotor resistance starter.
**Twist:** Capacitor across terminals improves pf, not starting torque. Voltage rise → torque ∝ V² but limited by saturation/inrush.

**Q67 (HMWS-15):** The starting torque of an induction motor is maximum when
(a) Rotor resistance is 1.414 times rotor reactance (b) Rotor resistance is twice the rotor reactance (c) Rotor resistance is half the rotor reactance (d) Rotor resistance equals rotor reactance
**Ans: (d)** — Max Tst at R2 = X2.
**Concept:** Max Tst at R2 = X2.
**Twist:** Max torque (breakdown) at Smt = R2/X2; starting (s=1) max when Smt=1. If R2=2X2 → Smt=2 → Tst < Tmax.

**Q68 (TSSPDCL-15):** In torque (T)–slip (s) characteristic of 3-φ squirrel cage induction motor, at maximum torque:
(a) dT/ds is maximum (b) dT/ds is zero (c) ds/dT is zero (d) slip is maximum
**Ans: (b)** — At Tmax the slope dT/ds = 0.
**Concept:** Tmax is a stationary point (dT/ds=0).
**Twist:** On stable side dT/ds>0, unstable side dT/ds<0; both give max at dT/ds=0. Load beyond Tmax → motor stalls.

**Q69 (TSSPDCL-15):** If per phase rotor resistance and reactance of 3-φ slip ring induction motor at standstill are 0.02 Ω and 0.2 Ω respectively then to obtain maximum starting torque, the external resistance to be connected in each phase of rotor is:
(a) 0.22 Ω (b) 0.18 Ω (c) 100 Ω (d) 0.20 Ω
**Ans: (b)** — rex = X2 − r2 = 0.2 − 0.02 = 0.18 Ω.
**Concept:** rex = X2 − r2 for max Tst.
**Twist:** If r2 = 0.02, X2 = 0.3 → rex = 0.28 Ω. If asked total rotor resistance → r2 + rex = X2 = 0.2 Ω.

**Q70 (TS SPDCL-18):** A 4 pole, 3 phase induction motor has a rotor resistance of 0.04 Ω and standstill reactance of 0.2 Ω per phase. The slip at which maximum torque occurs is
(a) 5 (b) 0.2 (c) 1 (d) 0.04
**Ans: (b)** — Smt = R2/X2 = 0.04/0.2 = 0.2.
**Concept:** Smt = R2/X2.
**Twist:** R2 doubled to 0.08 → Smt = 0.4. R2=X2 → Smt=1 (max starting torque). P = 4 is a distractor (does not affect Smt).

**Q71 (AP Transco-19):** The torque/speed curve of an induction motor is as shown in figure (points W, X, Y, Z). Which one of them represents the operation at a slip greater than 1?
(a) W (b) X (c) Y (d) Z
**Ans: (a)** — W lies in the braking (s>1, reverse rotation) portion of the T–s curve.
**Concept:** T–s curve regions (braking s>1, motoring 0<s<1, generating s<0).
**Twist:** Point at s=1 is starting torque; s<0 region is generating. Point beyond s=1 (reverse motoring/braking) is W.

**Q72 (APEPDCL-19):** The double cage induction motor torque-slip characteristics is shown in the following figure (curve A = inner cage, curve B = outer cage). Which statement is correct?
(a) Curve B is outer cage, resistances of B < A (b) Curve A is outer cage, resistance of A > B (c) Curve A is inner cage, resistance of A < B (d) Curve B is inner cage, resistance of B > A
**Ans: (c)** — Curve A (inner cage) has lower resistance than curve B (outer cage); outer cage provides high starting torque.
**Concept:** Double-cage: inner low-R, outer high-R.
**Twist:** Outer cage (high R) gives high starting torque peak at larger slip; inner cage (low R) gives high running torque at small slip. Combined curve shows both.

## Testing

**Q73 (EPDCL-10):** Under blocked rotor condition, the frequency of rotor currents in a 50Hz, 3-phase induction motor is
(a) Very low (b) Very high (c) 50 Hz (d) about 50 Hz
**Ans: (c)** — Blocked rotor: Nr=0, s=1 → f2 = s·f1 = 50 Hz.
**Concept:** Blocked-rotor test → s=1, f2=f1.
**Twist:** At full load s=0.04 → f2=2 Hz. Blocked rotor with reduced voltage to limit current → same s=1, f2=50 Hz.

**Q74 (SSC-JE-SI-14):** When the rotor of a three-phase induction motor is blocked, the slip is:
(a) 0 (b) 0.1 (c) 0.5 (d) 1
**Ans: (d)** — Nr=0 → s = (Ns−0)/Ns = 1.
**Concept:** Blocked rotor → s=1.
**Twist:** At synchronism s=0; at standstill s=1; plugging s≈2. Blocked-rotor test measures standstill impedance/reactance.

**Q75 (AP Genco-17):** A 3-phase induction motor under locked rotor condition and with stator supply, induces
(a) small voltage at slip frequency (b) large voltage at rotor frequency (c) zero voltage at zero frequency (d) large voltage at slip frequency
**Ans: (d)** — At locked rotor s=1 → rotor EMF = standstill value (large), at slip frequency = supply frequency.
**Concept:** Rotor EMF = s·E2 at frequency sf.
**Twist:** At full load (s≈0.05) rotor EMF small (~5%) at low slip frequency. At s=1 slip frequency equals supply frequency.

**Q76 (TSTransco-18):** A three-phase, 2000 V, Y-connected wound rotor induction motor has no-load test data: 2000 V, 15.3 amp and 10.1 kW. The core loss resistance rc of the approximate equivalent circuit is nearly
(a) 396 Ω (b) 686 Ω (c) 329 Ω (d) 666 Ω
**Ans: (a)** — Rc = V²/Piron = 2000²/10100 ≈ 396 Ω.
**Concept:** No-load test → Rc = V²/P.
**Twist:** 400 V, 10 kW iron loss → Rc = 16 Ω. Power measured in no-load test ≈ iron + friction+windage; subtract mech loss for true Rc.

**Q77 (AP Transco-19):** No-load test on a 3-phase induction motor conducted at different supply voltage, plot of input power vs voltage extrapolated to intersect the y-axis. The intersection point yields the
(a) core loss (b) stator copper loss (c) stray load loss (d) friction and winding loss
**Ans: (d)** — Extrapolation of P vs V to V=0 separates frequency-dependent mechanical loss (y-intercept) from V²-dependent iron loss.
**Concept:** No-load test separation: y-intercept = friction+windage loss.
**Twist:** Varying V changes iron loss (∝V²) but not mech loss. The slope term gives iron+Cu loss component.

## Starting

**Q78 (EPDCL-10):** A 3-phase induction motor takes a line current of 30A when started by direct switching. If a star-delta starter is used, the line current would be
(a) 30 A (b) 17.32 A (c) 10 A (d) 5 A
**Ans: (c)** — Star-delta reduces line current to 1/3 of DOL → 30/3 = 10 A.
**Concept:** Star-delta: line current = 1/3 of DOL.
**Twist:** DOL 45 A → star-delta 15 A. Torque also 1/3 (Q79). Current reduces by 66.7%.

**Q79 (AP Transco-12):** The ratio of starting torque to normal torque in case of a star delta starter will be
(a) 1/3 (b) 1/√3 (c) 1.0 (d) √3
**Ans: (a)** — Tst(YΔ)/Tst(DOL) = 1/3.
**Concept:** Star-delta: torque = 1/3 of DOL.
**Twist:** Voltage reduced to 1/√3 → T ∝ V² → (1/√3)² = 1/3. Autotransformer at x=0.5 → torque x²=1/4.

**Q80 (Transco-12):** An induction motor having full load torque of 60 N-m when delta-connected develops a starting torque of 120 N-m. For the same supply voltage, if the motor is changed to star-connection, the starting torque developed will be
(a) 40 N-m (b) 60 N-m (c) 90 N-m (d) 120 N-m
**Ans: (a)** — Tst(star) = Tst(delta)/3 = 120/3 = 40 N-m.
**Concept:** Tst(star) = Tst(delta)/3.
**Twist:** Tst(delta)=90 → star 30 N-m. This ratio assumes same supply line voltage.

**Q81 (SSC-JE-12):** In star-delta starting of three-phase induction motor, the starting voltage is reduced to
(a) 3 times of normal voltage (b) 1/3 times of normal voltage (c) 1/√3 times of normal voltage (d) √3 times of normal voltage
**Ans: (c)** — Phase voltage becomes V/√3.
**Concept:** Star connection → phase voltage = line/√3.
**Twist:** Starting voltage is 57.7% of rated → torque (1/√3)² = 1/3. If asked "reduced by" → 42.3%.

**Q82 (SSC-JE-12):** If the starting torque of a 3-phase induction motor is Tst for DOL starting, that for star-delta starting of the same motor is
(a) Tst/3 (b) √3·Tst (c) 3·Tst (d) Tst/√3
**Ans: (a)** — Star-delta starting torque = Tst(DOL)/3.
**Concept:** Tst(YΔ) = (1/3)Tst(DOL).
**Twist:** Autotransformer at x: torque = x²·Tst(DOL). Star-delta is equivalent to autotransformer x=1/√3.

**Q83 (HMWS-15):** An induction motor has a starting torque of 320 N-m when started by direct switching. If starting through an auto transformer with 50% tapping, the starting torque will be
(a) 640 N-m (b) 80 N-m (c) 160 N-m (d) 0.05 N-m
**Ans: (b)** — Tst(AT) = x²·Tst(DOL) = 0.25×320 = 80 N-m.
**Concept:** Autotransformer starting: Tst ∝ x².
**Twist:** 40% tapping → 0.16×320 = 51.2 N-m. 50% tapping of 200 N-m → 50 N-m (Q87).

**Q84 (HMWS-15):** I and T are the line current and torque respectively when DOL starter is used, these quantities when Y/Δ starter is used, are:
(a) I/2, T/4 (b) I/3, T/3 (c) I/2, T/2 (d) I/3, T/3
**Ans: (b)** — Both line current and torque reduce to 1/3 with star-delta.
**Concept:** Star-delta: I → I/3, T → T/3.
**Twist:** This matches autotransformer at x=1/√3: current ∝ x²? No — current ∝ x² actually; but star-delta gives I/3 exactly. Y/Δ torque 1/3, current 1/3.

**Q85 (TSGenco-15):** A delta-connected 400 V, 50 Hz, three-phase induction motor when direct-on-line takes a starting current of 30A. When the motor is started through star-delta starter, the starting current will be
(a) 3 A (b) 10 A (c) 15 A (d) 30 A
**Ans: (b)** — ISt(Y) = ISt(DOL)/3 = 30/3 = 10 A.
**Concept:** Star-delta line current = 1/3 of DOL.
**Twist:** DOL 15 A → star-delta 5 A. If the motor were wound for star (240 V) the numbers change.

**Q86 (TS SPDCL-18):** An induction motor is started with a star delta starter. The starting current and starting torque compared to direct on the starting are reduced by
(a) 1/3, 1/3 (b) 1/√3, 1/3 (c) 1/3, 1/3 (d) 1/√3, 1/√3
**Ans: (c)** — Both starting current and torque reduced to 1/3 of DOL values.
**Concept:** Star-delta reduces I and T both to 1/3.
**Twist:** Voltage reduces to 1/√3 (57.7%) but current and torque to 1/3 — the classic examiner trap: voltage is 1/√3, current/torque are 1/3.

**Q87 (TS Transco-18):** A 3-phase induction motor has a starting torque of 200 N-m when switched on directly to supply. If an auto-transformer with 50% tapping is used for starting, the torque would be
(a) 400 N-m (b) 200 N-m (c) 100 N-m (d) 50 N-m
**Ans: (d)** — Tst(AT) = 0.5²×200 = 50 N-m.
**Concept:** Tst ∝ x² for autotransformer.
**Twist:** 50% tapping torque is 1/4 (not 1/2) — the classic trap. 80 Nm at 30% → at 60% tapping → 320 Nm (Q88).

**Q88 (APEPDCL-19):** A starting torque of 80 Nm is developed in an induction motor by an autotransformer starter with a tapping of 30%. If the tapping of autotransformer is 60% then starting torque will be
(a) 320 Nm (b) 40 Nm (c) 160 Nm (d) 240 Nm
**Ans: (a)** — T ∝ x² → T2 = (0.6/0.3)²×80 = 4×80 = 320 Nm.
**Concept:** Tst ∝ (tapping)².
**Twist:** Tapping doubled → torque ×4 (not ×2). 30%→90% (×9) → 720 Nm.

**Q89 (APSPDCL-19):** A 3-phase slip ring induction motor has a stand still rotor impedance of (3+j4) Ω/ph and rotor emf of 100V/ph at stand still. Its rotor current at stand still is
(a) 25 A (b) 30 A (c) 35 A (d) 20 A
**Ans: (d)** — I = E2/|Z2| = 100/√(3²+4²) = 100/5 = 20 A.
**Concept:** Rotor current = sE2/|Z2|.
**Twist:** At slip s, E2 = sE2(s) → I2 = sE2/|r2+jsX2|. Add rotor resistance → current drops, pf improves.

**Q90 (TSNPDCL-22):** The direct-on-line starter for a large 3-φ induction motor has been replaced with a star-delta starter. Choose a wrong option.
(a) Starting torque is reduced by 66.7% (b) Starting voltage is reduced by 57.7% (c) Starting current is reduced to 33.3% (d) Starting torque is reduced to 33.3%
**Ans: (b)** — Voltage reduced TO 57.7% (i.e., reduced BY 42.3%); saying "reduced by 57.7%" is wrong.
**Concept:** Star-delta: V to 1/√3, I and T to 1/3.
**Twist:** Torque "reduced by 66.7%" = "reduced to 33.3%" — both correct (they are the same fact). The trap is "voltage reduced by 57.7%" vs "to 57.7%".

**Q91 (TSPSC-AEE-23):** Match methods of starting to their starting torque relations (I. Direct-on-line: Te,st/Te,fl = x²(Isc/Ifl)²·sfl; II. Stator resistor: = (1/3)(Isc.d/Ifl.d)²·sfl; III. Star delta: = (Ist/Ifl)²·sfl)
(a) I-1, II-2, III-3 (b) I-3, II-2, III-1 (c) I-3, II-1, III-2 (d) I-1, II-3, III-2
**Ans: (c)** — DOL→(3) full x=1; Stator resistor→(1) 1/3 factor; Star-delta→(2) (Ist/Ifl)²·sfl.
**Concept:** Starting method torque relations.
**Twist:** Autotransformer relation uses x²(Isc/Ifl)²·sfl where x=tapping; DOL is x=1. Star-delta torque = 1/3 of DOL.

**Q92 (TSGenco-24):** A 3-phase, 4-pole, 50 Hz Induction motor has full-load rated speed of 1425 rpm and takes 6 times its rated current under blocked rotor test. When started using auto transformer starter with 50% of normal voltage, the starting torque as a percentage of rated torque is
(a) 90% (b) 75% (c) 45% (d) 30%
**Ans: (c)** — sfl = 75/1500 = 0.05; Tst/Tfl = x²(Isc/Ifl)²·sfl = 0.25×36×0.05 = 0.45 = 45%.
**Concept:** Tst/Tfl = x²(Isc/Ifl)²·sfl.
**Twist:** Without autotransformer (x=1) → 90% (option a trap). 50% tapping → quarter the torque, hence 45%.

## Speed Control

**Q93 (APGenco-12):** The following speed-torque characteristics are obtained for a 3-phase induction motor (output constant, Ns shifts with constant Tmax not preserved). Pick the correct speed-control method.
(a) V/f control (b) E/f control (c) pole changing with f constant (d) stator voltage control, f constant
**Ans: (c)** — Ns changes (f constant) and Tmax NOT constant → pole-changing method.
**Concept:** Pole-changing speed control (Ns = 120f/P).
**Twist:** If Ns changes AND Tmax stays constant below rated f → V/f control (Q99). If only torque reduced at same Ns → stator voltage control (Q176).

**Q94 (APSPDCL-12):** The phasor diagram of rotor variables with Ej as injected emf (leading) provides
(a) sub synchronous speed without pf improvement (b) super synchronous speed without pf improvement (c) sub synchronous speed with pf improvement (d) super synchronous speed with pf improvement
**Ans: (c)** — Rotor EMF injection (leading) gives sub-synchronous speed with improved power factor.
**Concept:** Rotor EMF injection (slip-power recovery).
**Twist:** Inject EMF in phase opposition → super-synchronous speed (Q182). Inject in-phase (leading) → pf improves, speed slightly below Ns.

**Q95 (SSC-JE-13):** Which one of the following is a speed control method of three phase squirrel cage induction motor?
(a) Plugging method (b) Star-delta switch method (c) Pole-changing method (d) Centrifugal switching method
**Ans: (c)** — Pole-changing is the practical speed-control for cage rotors (no rotor access).
**Concept:** Pole-changing (consequent-pole) for cage motors.
**Twist:** Star-delta is a STARTING method, not speed control. Rotor-resistance control works only on slip-ring motors.

**Q96 (APSPDCL-14):** The following characteristics of 3-phase induction motor (T–s curves at different Ns, Tmax rising as Ns falls) refers to a speed control method. Identify correct option.
(a) V/f control (b) Variable V, f = frated (c) Variable f, V = Vrated (d) Cascade connection
**Ans: (c)** — V constant, f variable → Tmax and Tst rise as Ns falls.
**Concept:** Variable-frequency control with rated voltage (V constant, f↓ → flux↑).
**Twist:** If instead V/f kept constant → Tmax constant (Q97/Q99). Running above rated f → field weakening (Q177).

**Q97 (ISRO-14):** With V/f ratio keeping constant, if the frequency is decreased below the base value and the voltage is decreased proportionally, its starting torque and the peak torque for variable frequency and voltage will be
(a) both starting torque and peak torque will remain constant (b) Starting torque will increase and the peak torque remains constant (c) Starting torque will remain constant and peak torque will vary (d) both starting torque and peak torque will decrease
**Ans: (b)** — Tst ∝ (V/f)²·(1/f) → increases as f↓; Tmax ∝ (V/f)² → constant.
**Concept:** V/f control: Tmax constant; Tst rises at low f.
**Twist:** At very low f, stator IR drop reduces effective flux → torque actually falls (compensation needed). Below rated f = constant-torque region (Q104).

**Q98 (HMWS-15):** In V/f control of 3-phase induction motor, when operated above rated speed: (i) voltage decreases (ii) torque decreases (iii) power increases (iv) slip speed increases
(a) (ii) & (iv) are true (b) (i) & (iii) are true (c) (iii) & (iv) are true (d) (ii) & (iii) are true
**Ans: (a)** — Above rated f: V stays constant (field weakening), V/f falls → torque decreases, slip speed increases (power ≈ constant).
**Concept:** Above rated speed → constant-power/field-weakening region.
**Twist:** Voltage does NOT decrease (V is clamped at rated) — trap option (i). Slip speed rises because torque per unit slip falls.

**Q99 (TSGenco-15):** The speed of a three-phase induction motor is controlled by voltage variable frequency control (V/f constant). As the frequency is reduced, the maximum torque
(a) Decreases (b) Increases (c) Remains constant (d) None of the above
**Ans: (c)** — With V/f constant, Tmax ∝ (V/f)² = constant.
**Concept:** Tmax constant under V/f control.
**Twist:** Same V but f reduced → Tmax ∝ 1/f² rises (Q53). Below base frequency V/f constant → constant breakdown torque.

**Q100 (AP Transco-17):** In a 3-phase slip-ring induction motor, slip at some speed is 0.05. Speed reduced by inserting external rotor resistance, slip becomes 0.15. If rotor winding resistance per phase is 0.2 Ω, the external resistance is
(a) 0.2 Ω (b) 0.3 Ω (c) 0.4 Ω (d) 0.5 Ω
**Ans: (c)** — s ∝ R2 (constant load): 0.05/0.15 = 0.2/(0.2+rex) → rex = 0.4 Ω.
**Concept:** Rotor-resistance speed control: s ∝ (r2+rex).
**Twist:** If slip tripled → external R = 2× r2. This is valid only at constant torque; at constant power load the relation differs.

**Q101 (APSPDCL-19):** A 3-phase induction motor designed for 60 Hz has a full load output of 10 kW. Operated from 50 Hz keeping volts/Hz constant, its full load output would be approximately
(a) 7.3 kW (b) 10 kW (c) 8.3 kW (d) 12 kW
**Ans: (c)** — With V/f constant, P ∝ V ∝ f → P = (50/60)×10 = 8.33 kW.
**Concept:** Constant V/f → torque capacity constant → P ∝ f.
**Twist:** If V kept constant (not V/f) → P≈const (torque rises ∝ 1/f). Flux ∝ V/f must be kept to avoid saturation.

**Q102 (TSSPDCL-22):** A 3-φ, 4-pole, 50 Hz, 1480 rpm induction motor is fed from a 3-φ, 50 Hz cyclo-converter. When output of cyclo-converter is 1/3 of input frequency, what is the speed of induction motor at same slip speed?
(a) 520.0 rpm (b) 500.0 rpm (c) 480.0 rpm (d) 493.3 rpm
**Ans: (c)** — Ns=1500, slip speed=20; new f=50/3 → Ns=500 → Nr = 500−20 = 480 rpm.
**Concept:** Cycloconverter: f↓ → Ns↓; same slip speed → Nr = Ns − slip speed.
**Twist:** Same SLIP (not slip speed) → Nr = (1−s)·500 = 493.3 (option d trap). Read "same slip speed" vs "same slip" carefully.

**Q103 (TSSPDCL-22):** An AC induction motor rated 20 kW, 415 V, 3-phase, 4 pole, 50 Hz has full-load speed 1350 rpm. Operated by inverter with constant v/f control at 40 Hz, loaded at half-load. Determine the speed (linear torque-speed region).
(a) 1200 rpm (b) 1500 rpm (c) 1350 rpm (d) 1140 rpm
**Ans: (d)** — Ns(40Hz) = 1200; Nr always < Ns → 1140 rpm.
**Concept:** V/f control → Nr < Ns (slip needed for torque).
**Twist:** Half load → less slip, so Nr nearer 1200, but still < Ns → 1140 (only option <1200). At full load at 40 Hz the slip would be ~10%.

**Q104 (TSNPDCL-22):** The speed of a 3-φ induction motor is controlled using V/f control. Then,
(a) below rated f constant frequency region, above rated f constant voltage (b) below rated f constant voltage, above rated f constant frequency (c) below rated f constant power, above rated f constant torque (d) below rated f constant flux, above rated f constant power
**Ans: (d)** — Below rated f: constant flux (constant torque); above rated f: constant voltage (field weakening, constant power).
**Concept:** V/f control regions (constant-flux then constant-power).
**Twist:** Below rated f breakdown torque is constant; above rated f breakdown torque ∝ 1/f² falls while power ~constant.

**Q105 (TSNPDCL-22):** The following curves represent torque-speed characteristics of four motors (a, b, c, d). Match the speeds of motors at maximum torque. (1) Low speed (2) Speed < no-load speed (3) Speed < synchronous speed (4) Synchronous speed
(a) (1)–(d), (2)–(a), (3)–(c) (b) (1)–(a), (2)–(b), (3)–(c) (c) (2)–(b), (3)–(d), (4)–(c) (d) (2)–(c), (3)–(b), (4)–(d)
**Ans: (b)** — Low-speed motor (a); b runs below no-load speed; c below synchronous speed; d at synchronous (braking).
**Concept:** Reading T–N characteristics at max torque.
**Twist:** If torque peaks at Ns → that machine is a synchronous/dc machine, not an IM. Matching curves to operating regions (motoring, generating, braking).

**Q106 (TSNPDCL-22):** An AC induction motor rated 20 kW, 415 V, 3-φ, 4 pole, 50 Hz has full load speed 1350 rpm. The motor load is not reduced to half load. Determine the speed, assuming torque-speed between half and full load is linear.
(a) 1200 rpm (b) 1500 rpm (c) 1350 rpm (d) 1425 rpm
**Ans: (d)** — Reduced load → speed rises above 1350 but stays below Ns=1500 → 1425 rpm.
**Concept:** Lighter load → less slip → speed approaches Ns.
**Twist:** "Not reduced to half load" means some load reduction → speed between 1350 and 1500 → 1425 (only option). At true no-load → 1500 rpm.

## Generating and Braking

**Q107 (APGenco-12):** Given the phasor diagram of induction machine (rotor emf leading flux), identify its mode of operation.
(a) Motoring, > Ns (b) Generating, > Ns (c) Motoring, < Ns (d) Generating, < Ns
**Ans: (b)** — Rotor EMF reversed/leading flux indicates negative slip → generating mode, Nr > Ns.
**Concept:** Generating mode: s<0, Nr>Ns.
**Twist:** Motoring has s>0 (rotor EMF lags flux), Nr<Ns. Plugging/braking has s>1. Phasor of rotor EMF (−sE2) flips in generation.

**Q108 (Transco-12):** If an induction machine is run at above synchronous speed, it acts as
(a) a synchronous motor (b) an induction generator (c) an inductor motor (d) none of the above
**Ans: (b)** — Above Ns → negative slip → induction generator.
**Concept:** Induction generator at Nr > Ns.
**Twist:** To generate, machine must draw magnetizing current from grid (needs reactive power). Used in wind turbines.

**Q109 (APSPDCL-14):** During reverse current braking (plugging) of 3-phase induction motor, under no load condition energy dissipated in rotor circuit is
(a) equal to kinetic energy stored (b) twice the kinetic energy stored (c) three times the kinetic energy stored (d) four times the kinetic energy stored
**Ans: (c)** — During plugging the rotor circuit dissipates ~3× the stored kinetic energy.
**Concept:** Plugging dissipation (slip 2, energy ~3×KE).
**Twist:** Dynamic braking (dc injection) dissipates ~1× KE. Regeneration returns energy to supply instead of heating rotor.

**Q110 (HMWS-15):** The slip of a 3-phase induction motor is 0.05. At the instant of dynamic braking the slip is
(a) 0.05 (b) –0.05 (c) 1.95 (d) 0.95
**Ans: (c)** — At the instant braking is applied (as if field stationary), s = 2 − 0.05 = 1.95.
**Concept:** Slip at braking instant = 2 − s_motor.
**Twist:** s=0.03 → braking slip 1.97. For plugging from standstill → s=1; for reversal braking s→2.

**Q111 (TSPSC-AEE-23):** Match the regions of operation with slips. (I Motoring, II Regeneration, III Plugging; slips: 1 s<0, 2 1≤s≤2, 3 0≤s≤1)
(a) I-3, II-2, III-1 (b) I-1, II-2, III-3 (c) I-3, II-1, III-2 (d) I-2, II-1, III-3
**Ans: (c)** — Motoring 0≤s≤1, Regeneration s<0, Plugging 1≤s≤2.
**Concept:** Slip–mode mapping.
**Twist:** Motoring slip 0–1; braking/plugging 1–2; regeneration <0. At s=0 synchronous (no torque); s=1 standstill.

**Q112 (TSPSC-AEE-23):** Depending upon slip an induction motor can have: I. Motoring 0<S≤1; II. Braking S>1; III. Generating S<0. Identify correct pairs.
(a) I and III only (b) Only I (c) I, II and III (d) II and III only
**Ans: (c)** — All three modes are correct.
**Concept:** All slip modes valid.
**Twist:** Plugging is "braking" at s>1; regenerative braking is generating at s<0; motoring 0<s<1. At exactly s=0, T=0 (no mode torque).

**Q113 (TSPSC-AEE-23):** The regenerative braking would be effective only if the motor speed is _____.
(a) ω > ωmax only (b) ωmin < ω < ωmax (c) ω > ωmin only (d) ω < ωmin only
**Ans: (b)** — Regenerative braking effective in the speed range ωmin < ω < ωmax (where generated torque is sufficient).
**Concept:** Regenerative braking speed window.
**Twist:** Below ωmin the machine cannot sustain generation (no magnetizing/reaction). Above ωmax torque capability drops.

## Single-phase Induction Motor

**Q114 (SSC-JE-10):** Which of the following motor is used in household refrigerator?
(a) Synchronous motor (b) D.C. shunt motor (c) 3-phase induction motor (d) 1-phase induction motor
**Ans: (d)** — Household applications use single-phase induction motors.
**Concept:** 1-φ IM for domestic loads.
**Twist:** Ceiling fan → 1-φ capacitor motor; vacuum cleaner → universal motor (Q142); grinding → 3-φ where available.

**Q115 (SSC-JE-10):** A single-phase motor is made self-starting by the addition of a/an:
(a) Running (b) Starting winding (c) Electric starter (d) Autotransformer
**Ans: (b)** — Auxiliary/starting winding produces phase-split rotating field.
**Concept:** Phase-splitting for self-starting.
**Twist:** Add capacitor in series with auxiliary winding → better phase split (Q120). Remove auxiliary winding (pure 1-φ) → no starting torque.

**Q116 (AP Transco-12):** Which of the following motors will have relatively high-power factor
(a) Capacitor-run motor (b) Shaded pole motor (c) Capacitor-start motor (d) Split phase motor
**Ans: (a)** — Capacitor-run motor keeps a capacitor in circuit at all times → pf improved.
**Concept:** Capacitor-run → improved running pf.
**Twist:** Capacitor-start removes capacitor at speed → pf reverts low (that's why run capacitor gives best pf). Shaded-pole has worst pf.

**Q117 (AP Transco-12):** Which of the following motors can be used for unity power factor
(a) Schrage motor (b) Hysteresis motor (c) Shaded pole motor (d) Capacitor run motor
**Ans: (d)** — Capacitor-run (with suitably chosen capacitor) can be designed for near-unity pf.
**Concept:** Capacitor-run → unity pf possible.
**Twist:** Schrage motor gives variable-speed with pf improvement but not unity. Hysteresis has low pf; shaded-pole very low pf.

**Q118 (HMWS-12):** The direction of rotation of shaded-pole motor depends upon
(a) Supply frequency (b) which half of the pole is shaded (c) number of poles on the stator (d) supply voltage
**Ans: (b)** — Rotor turns from unshaded toward shaded portion of the pole.
**Concept:** Shaded-pole rotation sense.
**Twist:** Change shading ring to other half → reverse rotation (not by swapping supply lines). Shading ring makes flux in shaded part LAG (Q130).

**Q119 (Transco-12):** In case of a split phase motor, the phase shift between currents in the two windings is around
(a) 30 degree (b) 70 degree (c) 90 degree (d) 120 degree
**Ans: (a)** — Resistance split-phase gives only ~30–40° phase split.
**Concept:** Split-phase motor phase angle ~30°.
**Twist:** Capacitor-start motor achieves ~90° split (better starting torque). Perfect 90° is impractical; 30° gives weak but cheap starting.

**Q120 (Transco-12):** Starting torque can be obtained in a single-phase induction motor with identical main and auxiliary windings by connecting
(a) a capacitor across the mains (b) a capacitor in series with the machine (c) a capacitor in series with the auxiliary winding (d) the main and the auxiliary windings in series
**Ans: (c)** — Capacitor in series with auxiliary winding splits phases → starting torque.
**Concept:** Capacitor phase-splitting.
**Twist:** Identical windings need a capacitor (not just resistance) to create phase difference. Capacitor also helps pf (Q169).

**Q121 (Transco-12):** The type of single-phase induction motor having the highest power factor at full load is
(a) shaded pole type (b) split-phase type (c) capacitor start type (d) capacitor run type
**Ans: (d)** — Capacitor-run motor has the highest pf.
**Concept:** Capacitor-run → best pf.
**Twist:** Capacitor-start improves STARTING torque not running pf. Shaded-pole has worst pf (~0.4).

**Q122 (Transco-12):** For a single-phase capacitor start induction motor, which of the following statements is valid?
(a) The capacitor is used for power factor improvement (b) The direction of rotation can be changed by reversing the main winding terminals (c) The direction of rotation cannot be changed (d) The direction of rotation can be changed by interchanging the supply terminals
**Ans: (b)** — Reversing the main winding terminals (or the auxiliary winding) reverses rotation; capacitor is for phase splitting, not pf.
**Concept:** Reversal by swapping one winding.
**Twist:** Interchanging SUPPLY terminals does NOT reverse rotation (trap). Must reverse one winding. Reversing both windings also does nothing.

**Q123 (SSC-JE-12):** Based on revolving field theory, the forward and backward frequencies of the rotor emf of a 4-pole, 50 Hz, single-phase induction motor when running at 1300 rpm in the same direction of the forward field are respectively.
(a) 93.33 Hz, 6.67 Hz (b) 7.69 Hz, 107.69 Hz (c) 6.67 Hz, 93.33 Hz (d) 107.69 Hz, 7.69 Hz
**Ans: (c)** — Ns=1500, sf=0.133 → forward f=6.67 Hz; backward slip = 2−0.133=1.867 → f=93.35 Hz.
**Concept:** Two-revolving field: f_f = s·f, f_b = (2−s)·f.
**Twist:** At standstill s=1 → both fields 50 Hz. At near sync → forward freq→0, backward→~100 Hz (2f). Option (a) swaps the order — trap.

**Q124 (SSC-JE-12):** Universal motor is a ____ motor
(a) single phase induction (b) synchronous (c) shunt (d) series
**Ans: (d)** — Universal motor is a DC series motor designed to run on AC/DC.
**Concept:** Universal = AC/DC series motor.
**Twist:** Series field makes it work on AC (torque ∝ I² both half-cycles). Shunt motors would not run on AC (field flux lags).

**Q125 (SSC-JE-13):** The single-phase Induction Motor (IM) which does not have centrifugal switch is
(a) capacitor start single phase IM (b) resistance split single phase IM (c) capacitor start capacitor run single phase IM (d) permanent capacitor run single phase IM
**Ans: (d)** — Permanent capacitor-run (and capacitor-start-capacitor-run) motors keep the capacitor always in circuit → no centrifugal switch needed.
**Concept:** Capacitor-run motor has no CFS.
**Twist:** Capacitor-start and resistance-split motors use a centrifugal switch to cut the auxiliary circuit at ~75% speed. If CFS fails → overheating (Q127).

**Q126 (SSC-JE-13):** A universal motor is one which
(a) can run on any value of supply voltage (b) has infinitely varying speed (c) can operate on ac as well as dc voltage (d) can work as single phase or three phase motor
**Ans: (c)** — Runs on both AC and DC supplies.
**Concept:** Universal motor definition.
**Twist:** Speed of universal motor varies with load and can be very high at no load (Q144/option d). It is NOT "any voltage" — voltage rating still applies.

**Q127 (SSC-JE-13):** If the centrifugal switch of a single-phase resistance split induction motor does not open after starting of motor, then the motor
(a) will run above normal speed (b) will run below normal speed (c) will draw very small current (d) will draw high current and get over heated
**Ans: (d)** — Auxiliary winding is designed for brief duty; staying in circuit draws high current → overheating.
**Concept:** Centrifugal switch failure → burnout.
**Twist:** The auxiliary winding has high resistance (low X/R) and is not rated for continuous current. Same logic for capacitor-start winding.

**Q128 (EPDCL-14):** Two windings provided on the stator of a single-phase induction motor, one main winding and the other auxiliary winding are connected
(a) In parallel (b) In series (c) Either in series or parallel depending on the design (d) Through inductive coupling
**Ans: (a)** — Main and auxiliary windings are connected in parallel across the supply.
**Concept:** 1-φ motor winding connection.
**Twist:** Both windings are in parallel across the line; the capacitor (if any) is in series with only the auxiliary winding (Q147).

**Q129 (APSPDCL-14):** The following are the two sets (I, II) of connections shown for a capacitor motor. If T1, T2 are torques produced by connections I and II respectively, the correct option is
(a) T1 < T2 (b) T1 = T2 (c) T1 > T2 (d) T1 << T2
**Ans: (c)** — T ∝ Imain·Iaux·sinλ; parallel connection (I) gives higher main-winding current → T1 > T2.
**Concept:** T ∝ Im·Ia·sinφ.
**Twist:** The connection that raises main-winding current (parallel vs series of windings) raises torque. Angle λ between winding currents is what the capacitor sets.

**Q130 (ISRO-14):** In the shaded pole squirrel cage induction motor the flux in the shaded part always
(a) Leads the flux in the un-shaded pole segment (b) Lags the flux in the un-shaded pole segment (c) Out of phase with the flux in the unshaded pole segment (d) In phase with the flux in the un-shaded pole segment
**Ans: (b)** — Shading ring induces opposing current → flux in shaded part lags the unshaded flux.
**Concept:** Shaded-pole flux lag (creates rotation).
**Twist:** The lagging shaded flux gives a sweeping field → rotor moves unshaded→shaded (Q118). Reversing shading ring reverses rotation.

**Q131 (ISRO-14):** Thrust developed by a linear induction motor
(a) synchronous speed (b) rotor input (c) rotor input and synchronous speed (d) harmonics developed in the motor
**Ans: (a)** — Linear-IM thrust rises with speed and peaks near synchronous speed.
**Concept:** Linear induction motor thrust–speed.
**Twist:** Thrust ∝ (synchronous-field interaction); at zero speed thrust is at its maximum for a given slip frequency in many designs. Used in maglev.

**Q132 (SSC-JE-SI-14):** In which single-phase motor, the rotor has no teeth or winding?
(a) Split phase motor (b) Reluctance motor (c) Hysteresis motor (d) Universal motor
**Ans: (c)** — Hysteresis motor rotor is a smooth cylindrical ring of hard magnetic material (no teeth/winding).
**Concept:** Hysteresis motor rotor.
**Twist:** Reluctance motor rotor has salient teeth (no winding). Universal motor has wound armature. Hysteresis rotor has no winding/slots.

**Q133 (SSC-JE-SI-14):** Which of the following motor will give relatively high starting torque?
(a) Capacitor start motor (b) Capacitor run motor (c) Split phase motor (d) Shaded pole motor
**Ans: (a)** — Capacitor-start gives high starting torque.
**Concept:** Capacitor-start torque ranking.
**Twist:** Highest starting torque order: capacitor-start > resistance-split > shaded-pole. Capacitor-start-capacitor-run even higher (Q153).

**Q134 (SSC-JE-SI-14):** The least expensive fractional horse power motor is ____ motor.
(a) shaded pole (b) capacitor start (c) split phase (d) A.C. series
**Ans: (a)** — Shaded-pole motor is the cheapest/simplest FHP motor.
**Concept:** Shaded-pole = cheapest.
**Twist:** Shaded-pole has low efficiency and low pf but lowest cost → used in small fans. Split-phase costs more than shaded-pole.

**Q135 (SSC-JE-S1-14):** Which of the following motors can be run on A.C as well as D.C supply?
(a) universal motor (b) repulsion motor (c) synchronous motor (d) reluctance motor
**Ans: (a)** — Universal motor runs on AC and DC.
**Concept:** Universal (series) motor AC/DC.
**Twist:** Repulsion motor is AC only. Synchronous and reluctance need AC (or special drives). Universal is a DC-series motor modified for AC.

**Q136 (SSC-JE-S1-14):** The repulsion-start induction run motor is used because of:
(a) good-power factor (b) high efficiency (c) minimum cost (d) high starting torque
**Ans: (d)** — High starting torque without large starting current.
**Concept:** Repulsion-start induction-run motor.
**Twist:** Uses commutator/brushes at start (repulsion) then short-circuits to run as induction motor. Gives high Tst but is costlier/noisy.

**Q137 (SSC-JE-S2-14):** Which of the following applications needs frequent starting and stopping of electric motors.
(a) Air-conditioner (b) Lifts and hoists (c) Grinding mill (d) Paper mill
**Ans: (b)** — Lifts and hoists require frequent start/stop duty.
**Concept:** Duty cycle application.
**Twist:** Grinding/paper mills run continuously; AC operates cyclically but not as frequent. Start/stop duty needs motors rated for frequent reversals (S1–S5 duty).

**Q138 (SSC-JE-S2-14):** In a single-phase induction motor, speed sensitive centrifugal switch is connected in
(a) parallel with main winding (b) series with main winding (c) parallel with starting winding (d) series with starting winding
**Ans: (d)** — CFS is in series with the starting/auxiliary winding.
**Concept:** CFS location.
**Twist:** At ~75% speed the CFS opens, removing the starting winding. If it were in the main circuit the motor would stop.

**Q139 (SSC-JE-S2-14):** At starting the current through the starting winding (Is) of single-phase induction motor
(a) lags 'V' by 90° (b) leads 'V' by 90° (c) is nearly in phase with 'V' (d) leads 'V' by 75°
**Ans: (d)** — Capacitor in series with auxiliary winding makes its current lead the voltage (~75°).
**Concept:** Capacitor split-phase phase lead.
**Twist:** Without capacitor (resistance split) → auxiliary current lags slightly, ~30° split (Q119). Leads "by 90°" would be ideal but impossible.

**Q140 (SSC-JE-S2-14):** In a single-phase induction motor at start, the two revolving fields produce
(a) unequal torques in the rotor conductors (b) no torque in the rotor conductor (c) equal and opposite torque in the rotor conductor (d) equal torques in same direction in the rotor conductors
**Ans: (c)** — Forward and backward fields produce equal and opposite torques at standstill → net torque zero.
**Concept:** Two-revolving field theory at start.
**Twist:** Once rotor turns, forward torque exceeds backward torque → net torque. This is why 1-φ motor is not self-starting (Q170).

**Q141 (SSC-JE-S2-14):** Which of the following single-phase motors is available with speed as low as one revolution per minute?
(a) Shaded pole (b) Reluctance (c) Hysteresis (d) Universal
**Ans: (a)** — Shaded-pole motors can be built with many poles → very low speeds.
**Concept:** Shaded-pole low-speed capability.
**Twist:** Hysteresis/reluctance synchronous speeds are set by f/P. Universal runs fast. Shaded-pole with large pole count → slow (used in clock/microwave turntables).

**Q142 (SSC-JEE-S2-14):** A vacuum cleaner employ ____ motor.
(a) resistance split phase (b) capacitor starts (c) shaded pole (d) single phase series
**Ans: (d)** — Universal (single-phase series) motor for high-speed vacuum cleaner.
**Concept:** Universal motor application.
**Twist:** High-speed (10,000+ rpm) needed for vacuum/blender → universal. Electric shavers/grinders → universal.

**Q143 (SSC-JE-S2-14):** In capacitor start induction motor, the current in the
(a) supply lines leads the voltage (b) starting winding lags the voltage (c) main winding leads the voltage (d) starting winding leads the voltage
**Ans: (d)** — Starting (auxiliary) winding current leads voltage due to the series capacitor.
**Concept:** Capacitor → starting current leads.
**Twist:** Main winding (inductive) current lags voltage. The phase split comes from auxiliary current leading while main lags (Q139).

**Q144 (HMWS-15):** A universal motor is one which
(a) is available universally (b) can be marketed internationally (c) can be operated either on dc or ac supply (d) runs dangerously high speed on no load
**Ans: (c)** — Operates on both DC and AC.
**Concept:** Universal motor definition.
**Twist:** On no-load a universal motor runs at dangerously high speed (series characteristic) — option (d) is a property but not the definition. Best answer is (c).

**Q145 (AP Genco-17):** The equivalent rotor resistance r2' components in the equivalent circuit of a single-phase induction motor, based on two-revolving field theory, at any slip s are
(a) r2'/s and r2'/(1−s) (b) r2'/s and r2'/(2−s) (c) r2'/(2s) and r2'/(2(1−s)) (d) r2'/(2s) and r2'/(2(2−s))
**Ans: (d)** — Forward field: r2'/2s; backward field: r2'/(2(2−s)).
**Concept:** Two-revolving field equivalent circuit.
**Twist:** At standstill s=1 → both = r2'/2. Slip values s and (2−s) correspond to forward/backward slips. Option (c) uses wrong backward slip (2(1−s)) — trap.

**Q146 (AP Genco-17):** In the capacitor-start, capacitor-run single-phase induction motor
(a) two capacitors are connected across the main winding (b) when the centrifugal switch opens, the permanent capacitor is left in the auxiliary winding circuit (c) when the centrifugal switch opens, the permanent capacitor is left in the main winding circuit (d) two capacitors are connected across the auxiliary winding
**Ans: (b)** — Start capacitor (large, electrolytic) is cut out; the small running capacitor stays in the auxiliary circuit.
**Concept:** Capacitor-start capacitor-run circuit.
**Twist:** Start capacitor is for starting torque; run capacitor improves running pf/torque. Only the start (electrolytic) capacitor needs the switch.

**Q147 (AP Transco-17):** The starting torque of a capacitor-start induction run motor is directly related to the angle 'θ' between its two winding currents by the relation
(a) cos θ (b) sin θ (c) tan θ (d) sin θ/2
**Ans: (b)** — Tst ∝ Imain·Iaux·sinθ.
**Concept:** T ∝ sinθ of winding-current angle.
**Twist:** θ=90° ideal → max torque. Capacitor value sets θ; that's why capacitor-start gives high Tst.

**Q148 (APEPDCL-19):** In repulsion motor, maximum torque is developed when
(a) brush axis coincides with the field axis (b) brush axis is at 180° electrical to the field axis (c) brush axis is at 90° electrical to the field axis (d) brush axis is at 45° electrical to the field axis
**Ans: (d)** — Te ∝ sin2λ; maximum at λ = 45° brush shift.
**Concept:** Repulsion motor brush-angle for Tmax.
**Twist:** At 0° or 90° brush shift → no torque (short-circuited/no flux). At 45° → max torque; at 90° it behaves like shorted transformer.

**Q149 (APEPDCL-19):** If a ceiling fan fails to start, what could be the possible reasons? I. Supply voltage terminals reversed; II. Main winding open circuited; III. Auxiliary winding open circuited; IV. Main and auxiliary winding connections interchanged; V. Capacitor short circuited.
(a) (II) (III) and (V) (b) (I) (II) and (IV) (c) (I) (III) and (IV) (d) (II) (IV) and (V)
**Ans: (a)** — Open main or auxiliary winding, or shorted capacitor, prevent starting. Reversed terminals/interchanged connections do not stop a 1-φ motor.
**Concept:** 1-φ motor failure diagnosis.
**Twist:** A shorted capacitor kills the phase split → no starting torque; an open auxiliary winding does the same. Reversing supply lines never matters for 1-φ start.

**Q150 (APSPDCL-19):** Match motors (List-I) with parts (List-II): p. Universal motor-3. Commutator; q. Synchronous motor-1. Damper bars; r. 3-phase induction motor-2. Rotor bars
(a) p-3, q-1, r-2 (b) p-1, q-2, r-3 (c) p-2, q-3, r-1 (d) p-1, q-3, r-2
**Ans: (a)** — Universal→commutator; synchronous→damper bars; 3-φ IM→rotor bars.
**Concept:** Machine parts matching.
**Twist:** Damper bars are also in the synchronous rotor for starting; induction rotor has rotor bars. Repulsion motor also uses commutator.

**Q151 (APSPDCL-19):** A 440 V induction motor is started with reduced voltage of 220 V to reduce starting current. After motor picks up speed, full rated voltage is applied. Pick up corresponding s-T characteristics for the operation.
(a) low 220-V T-s curve then jump to 440-V curve (b) high-T then drop (c) 440V flat (d) 220V flat
**Ans: (a)** — At 220 V the T-s curve is the low (V²-scaled) curve; after switch-over torque jumps onto the 440 V characteristic.
**Concept:** Reduced-voltage starting s-T curves.
**Twist:** Torque scales as V² → at 220 V (half voltage) torque is 1/4. The correct plot shows start on low curve then transition to high curve at near-rated speed.

**Q152 (AP Transco-19):** For the load-time plot given below (periodic load pulses with start/brake between cycles), identify the type of load
(a) Continuous duty with intermittent periodic load (b) Continuous duty with starting and braking (c) Intermittent periodic duty without braking (d) Intermittent periodic duty with starting and braking
**Ans: (d)** — Load plot shows intermittent periodic duty with starting and braking.
**Concept:** Duty classification (S3–S7).
**Twist:** If no braking between pulses → intermittent periodic duty without braking (S3). Continuous duty → motor never stops. Duty type sets thermal rating.

**Q153 (TSSPDCL-AE-2023):** Which of the following single-phase Induction Motor has highest starting torque?
(a) Shaded pole motor (b) Permanent capacitor motor (c) Resistance split phase motor (d) Capacitor start motor
**Ans: (d)** — Capacitor-start motor has the highest starting torque.
**Concept:** 1-φ starting torque ranking.
**Twist:** Order (ascending Tst): shaded-pole < permanent-capacitor < resistance-split < capacitor-start < capacitor-start-capacitor-run. Higher torque costs more.

## Harmonic Analysis

**Q154 (SSC-JE-11):** If a 3-phase induction motor hums during starting up, the probable cause could be
(a) Unequal stator phase resistance (b) Open circuited rotor (c) Inter turn short circuit on rotor (d) Any of the above
**Ans: (c)** — Rotor inter-turn short causes non-uniform field → humming/vibration.
**Concept:** Humming from rotor faults.
**Twist:** Unbalanced supply/stator fault also causes hum, but the given key is rotor inter-turn short. Open rotor → no torque at all.

**Q155 (AP Transco-12):** The crawling in an induction motor is caused by
(a) High loads (b) Low supply voltages (c) Improper design of machine (d) Harmonics developed in the motor
**Ans: (d)** — Space/time harmonics (odd harmonics, esp. 7th) produce stable low-speed torque → crawling.
**Concept:** Crawling from harmonics.
**Twist:** Crawling occurs at ~1/7 of Ns (7th harmonic, an odd multiple). Even harmonics are absent in balanced 3-φ systems.

**Q156 (ISRO-14):** A three-phase induction motor running at 1440 rpm on rated supply will run at the following rpm when fuse of one phase gets burnt
(a) 1440 (b) 1380 (c) 1500 (d) zero
**Ans: (b)** — Single-phasing produces a backward field → negative torque → speed drops slightly (~1380 rpm).
**Concept:** Single-phasing (open line) behavior.
**Twist:** The motor continues to run (unloaded) but at reduced speed and higher current; under load it may stall. It never speeds up to 1500.

**Q157 (ISRO-14):** In the circle diagram for a 3-phase induction motor, the diameter of the circle is determined by
(a) total stator current (b) exciting current (c) rotor current (d) rotor current referred to stator
**Ans: (d)** — Circle diameter corresponds to rotor current referred to stator.
**Concept:** Circle diagram (rotor current = diameter).
**Twist:** Stator current locus is the circle; the diameter measures maximum rotor current referred to stator. Slip line location locates operating points.

**Q158 (ISRO-14):** The crawling in an induction motor is caused by
(a) Improper design of machine (b) low voltage supply (c) high loads (d) harmonics developed in the motor
**Ans: (d)** — Harmonics cause crawling.
**Concept:** Crawling ← harmonics.
**Twist:** Same as Q155 — low voltage only reduces torque, doesn't create crawl speed. Harmonics (7th etc.) give the stable sub-synchronous point.

**Q159 (SSC-JE-S2-14):** In a 3-phase induction motor crawling happens at
(a) any speed (b) no-load speed (c) odd multiples of fundamental (d) even multiples of fundamental
**Ans: (c)** — Crawling at sub-synchronous speed from odd space harmonics (e.g., 1/7 of Ns).
**Concept:** Crawling at 1/7 Ns (7th harmonic is odd).
**Twist:** 3rd harmonic is absent in balanced 3-φ; 5th/7th/11th... odd harmonics matter. Cogging (locked at standstill) is different from crawling.

**Q160 (HMWS-15):** The value of slip of a 3-phase induction motor at nth harmonic is approximately
(a) 1 (b) zero (c) n × slip (d) slip/n
**Ans: (a)** — Sn = s − (n−1)(Nr/Ns) ≈ 1 for the nth harmonic field.
**Concept:** Slip at nth harmonic ≈ 1.
**Twist:** For n=7, harmonic field rotates at Ns/7 (opposite) → Sn ≈ 1. If harmonic field rotates in forward direction at Ns/n and n large → slip≈1. Option (d) slip/n is a trap.

**Q161 (HMWS-15):** If an induction motor with certain ratio of rotor to stator slots, runs at the 1/7th of the normal rated speed, the motor is said to be
(a) Jogging (b) Crawling (c) Cogging (d) Hunting
**Ans: (b)** — Stable running at 1/7 of rated speed is crawling.
**Concept:** Crawling at 1/7 Ns.
**Twist:** Cogging = magnetic locking at standstill (refuses to start); crawling = runs at low sub-synchronous speed. Jogging = brief inching.

**Q162 (AP Transco-17):** Generally, crawling in squirrel cage induction motors is tendency to run stably at speeds as low as
(a) One-third of their synchronous speed (b) One-fifth of their synchronous speed (c) One-seventh of their synchronous speed (d) One-ninth of their synchronous speed
**Ans: (c)** — Crawling stable point near 1/7 of Ns (7th harmonic).
**Concept:** Crawling at 1/7 Ns.
**Twist:** Cogging (locking) relates to slot combinations (stator/rotor slots) rather than a fixed 1/7 speed. Skewing removes both crawling and cogging.

**Q163 (APSPDCL-19):** A 3-ph induction motor is drawing a current of 30 A at 0.8 pf lag from 3-ph mains at certain load. Due to fault a line gets opened. Now the current on single phasing when pf is 0.6 lag would be
(a) 20√3 A (b) 30√3 A (c) 35√3 A (d) 40√3 A
**Ans: (d)** — P = 3VIcosφ = VI'cosφ' → I' = 3×30×0.8/0.6 = 120 A = 40√3 A.
**Concept:** Power balance under single-phasing (P unchanged, pf drops).
**Twist:** If pf stayed 0.8 → I'=90 A. If load dropped → current lower. Single-phasing current can be √3× normal under same torque.

**Q164 (HMWS-20):** In a single-phase induction Motor, nearer to the synchronous speed
(a) Backward field is several times the forward field (b) Forward torque is equal to the backward torque (c) Forward and backward field are equal (d) Forward field is several times the backward field
**Ans: (d)** — Near Ns, backward-field slip ≈ 2 (high freq, small magnitude) → forward field dominates.
**Concept:** Forward vs backward field near synchronism.
**Twist:** At standstill both fields equal (net T=0); near Ns backward-field effects (double-frequency torque, extra loss) become negligible.

**Q165 (HMWS-20):** In a 3-phase induction motor, if air gap length is increased
(a) Magnetizing reactance is decreased (b) Stator and rotor resistances are increased (c) Magnetizing reactance is increased (d) Magnetizing reactance remains same
**Ans: (a)** — Xm = 2πf·(N²/Reluctance); air gap ↑ → reluctance ↑ → Xm ↓.
**Concept:** Xm ∝ 1/air-gap.
**Twist:** Smaller air gap → higher Xm, lower magnetizing current, better pf (Q2/Q33). Leakage reactance rises with air gap.

**Q166 (HMWS-20):** If the Aluminium rotor bars of a 3-phase Squirrel Cage Induction Motor are replaced by copper bars, then starting torque, maximum torque and slip at maximum torque would be respectively
(a) Same, same and more (b) More, less and more (c) Less, same and less (d) More, same and more
**Ans: (c)** — Cu has lower resistance: Tst ∝ R2 ↓, Tmax unchanged (independent of R2), Smt = R2/X2 ↓.
**Concept:** R2 ↓ → Tst ↓, Tmax same, Smt ↓.
**Twist:** This is why the same aluminium→copper swap raises efficiency (lower Cu loss) while cutting starting torque. Adding rotor resistance does the reverse (Q57).

**Q167 (SSC-JE-20):** In a 3-phase induction motor a balanced three phase supply is with electrical angle separation
(a) 30° (b) 60° (c) 90° (d) 120°
**Ans: (d)** — Phases separated by 120° electrical.
**Concept:** Balanced 3-φ = 120° separation.
**Twist:** If one phase opens (single-phasing) → only two windings in series → backward torque (Q156). 120° separation is what creates the rotating field.

**Q168 (SSC-JE-20):** The slip of induction motor 0.04 and frequency of motor 60 hz. Hence, the rotor current frequency
(a) 24 khz (b) 24 hz (c) 2.4 hz (d) 60 hz
**Ans: (c)** — f2 = s·f1 = 0.04×60 = 2.4 Hz.
**Concept:** f2 = s·f.
**Twist:** s=0.04 at 50 Hz → 2 Hz. Option (b) 24 Hz is the "s×f×10" trap. Blocked rotor s=1 → 60 Hz.

**Q169 (SSC-JE-20):** In a capacitor start and run motors the function of the running capacitor in series with the auxiliary winding is to ____.
(a) improve power factor (b) increase overload capacity (c) reduce fluctuations in torque (d) to improve torque
**Ans: (a)** — Running capacitor primarily improves power factor (and running torque slightly).
**Concept:** Run capacitor → pf improvement.
**Twist:** The START capacitor improves starting torque; the RUN capacitor improves pf/running performance (Q116/Q121). Permanently-connected run capacitor also smooths torque.

**Q170 (SSC-JE-20):** Torque developed by a single-phase induction motor at starting is
(a) pulsating (b) uniform (c) non-uniform (d) zero
**Ans: (d)** — At standstill forward/backward torques cancel → net starting torque = 0.
**Concept:** 1-φ IM not self-starting.
**Twist:** With a starting winding/capacitor → finite starting torque. While running, torque is pulsating at twice supply frequency (double-frequency torque).

**Q171 (TSNPDCL-AE-22):** A 3-φ induction motor is fed by a 3-φ inverter having fundamental and all odd harmonic voltages without 3rd harmonic components. The slip at 5th harmonic components is
(a) exactly equal to 0.2 (b) exactly equal to 1.0 (c) greater than 1.0 (d) between 0.5 and 1.0
**Ans: (c)** — s5 = (5Ns+Nr)/5Ns = 1 + (Nr/Ns)/5 > 1.
**Concept:** Slip at nth harmonic > 1 (5th harmonic rotates backward at 5Ns).
**Twist:** For 7th harmonic (forward) slip still ≈1 for large n. The 5th harmonic torque opposes the fundamental → braking/crawling.

**Q172 (TSGenco-24):** Which statements are correct? (i) Cogging and crawling less prominent in slip-ring machines. (ii) Induction harmonic torque reduced by skewing. (iii) Synchronous harmonic torques avoided by proper stator/rotor slot combination.
(a) (i) and (ii) only (b) (ii) and (iii) only (c) (i) and (iii) only (d) (i), (ii) and (iii)
**Ans: (d)** — All three statements correct.
**Concept:** Harmonic torque mitigation (slip-ring rotor R, skewing, slot combination).
**Twist:** Slip-ring motors can add external rotor resistance to suppress harmonic/crawling effects. Asynchronous harmonic torque → skewing; synchronous (slot) harmonic torque → slot-ratio choice.

## AE/AEE 2023

**Q173 (TSPSC-2023):** A three-phase induction motor with a 6-pole winding is rotating at 1200 rpm. The speed of rotation in electrical and mechanical radians per second are respectively
(a) 40π/3, 40π (b) 120π, 40π (c) 40π, 120π (d) 40π, 40π/3
**Ans: (b)** — ωm = 2π×1200/60 = 40π; ωe = (P/2)ωm = 3×40π = 120π.
**Concept:** ωe = (P/2)·ωm.
**Twist:** 4-pole at 1500 rpm → ωm=50π, ωe=100π. Mechanical rad/s always smaller than electrical by factor P/2.

**Q174 (TSPSC-2023):** At low values of operating slip, the torque developed in a three-phase induction motor is
(a) Proportional to the square of slip (b) Linearly proportional to slip (c) Independent of slip (d) Inversely proportional to slip
**Ans: (b)** — In the low-slip (stable) region Te ∝ s (T-s curve linear near s=0).
**Concept:** T ∝ s for small slip.
**Twist:** Near Smt, T rises to Tmax; beyond Smt (unstable side) T falls with s. T ∝ s² is wrong — that's for a DC machine flux relationship.

**Q175 (TSPSC-2023):** In rotor resistance control of an induction motor, with increase in rotor resistance
(a) Maximum torque remains unchanged, starting torque increases and slip at max torque increases (b) Maximum torque increases, starting torque increases and slip at max torque decreases (c) Maximum torque unchanged, starting torque decreases and slip at max torque increases (d) Maximum torque increases, starting torque increases and slip at max torque increases
**Ans: (a)** — Tmax independent of R2; Tst ∝ R2 (up to Smt=1); Smt = R2/X2 increases.
**Concept:** Rotor resistance control effect.
**Twist:** If R2 raised so far that Smt>1, starting torque then DECREASES (that's option (c) trap). Speed drops as slip increases at constant load (Q100).

**Q176 (TSPSC-2023):** Reducing the speed in a three-phase induction motor by using stator voltage control while supplying a constant torque load would result in
(a) Reduced efficiency (b) Reduction in rotor slip (c) Increased peak torque capability (d) Higher airgap flux within the machine
**Ans: (a)** — Voltage reduction at constant-torque load raises slip/rotor I²R loss → efficiency falls.
**Concept:** Stator voltage control → efficiency penalty.
**Twist:** At constant torque, V↓ → slip↑ → rotor Cu loss ↑ (T ∝ I2²r2/s with T const → I2²r2 ∝ s). Flux also falls (not rises), Tmax falls.

**Q177 (TSPSC-2023):** What is the status of machine flux, for frequency above rated (base) frequency, in a speed regulated V/f controlled induction motor drive?
(a) Machine flux may increase or decrease based on load (b) Machine flux increases from the rated flux (c) Machine flux decreases from the rated flux (d) Machine flux unchanged
**Ans: (c)** — Above rated f, V is clamped → flux ∝ V/f decreases (field weakening).
**Concept:** Field weakening above base frequency.
**Twist:** Below rated f, V/f constant → flux constant (constant-torque region, Q104). Above rated f → constant power, torque capability ∝ 1/f falls.

**Q178 (TSPSC-2023):** A three-phase induction motor rated 15 hp, 440 V has an efficiency of 85% and operates at pf 0.9 (lag), delivering rated output. What is the reactive power drawn?
(a) 5.11 kVAr (b) 7.42 kVAr (c) 6.38 kVAr (d) 8.21 kVAr
**Ans: (c)** — Q = (15×746/(0.85×0.9))×√(1−0.9²) ≈ 6362 VAR = 6.38 kVAr.
**Concept:** Q = S·sinφ from Pin/η and pf.
**Twist:** If pf=0.8 → Q = 7460 VAR. If efficiency ignored → Q changes. Watch hp→W conversion (×746) and sinφ = √(1−cos²φ).

**Q179 (TSPSC-2023):** What is the way of imparting braking action of three phase induction motor in plugging scheme?
(a) By increasing the stator voltage magnitude (b) by decreasing the stator voltage magnitude (c) By decreasing synchronous speed (d) By reversal of the phase sequence of the stator
**Ans: (d)** — Plugging = reversing phase sequence so the field rotates opposite → braking (slip > 1).
**Concept:** Plugging via phase-sequence reversal.
**Twist:** During plugging slip s≈2, energy ~3× KE dissipated in rotor (Q109). Dynamic braking uses DC injection instead.

**Q180 (TSPSC-2023):** The stator of a three-phase, 4-pole squirrel cage induction motor rated 1450 rpm at 50 Hz, is rewound to have six poles without any change made on the rotor. This motor would then
(a) run at the same speed with higher torque rating (b) operate with speed slightly below 1000 rpm at 50 Hz (c) fail to develop any torque (d) operate with speed slightly above 1800 rpm at 50 Hz
**Ans: (b)** — Cage rotor adapts to 6 poles → Ns=1000, runs slightly below 1000 rpm.
**Concept:** Cage rotor pole-adaptivity (Q16).
**Twist:** If the rotor were a wound/slip-ring rotor wound for 4 poles → it would NOT match 6-pole field (option c). Slightly below 1000 (slip>0), never 1000 exactly.

**Q181 (TSPSC-2023):** The speed of an induction motor is increased by increasing the frequency by 20%. If the magnetizing current is to remain constant, then
(a) slip must be increased by 20% (b) supply voltage must be increased by 20% (c) supply voltage must be decreased by 20% (d) supply voltage must be increased by 10%
**Ans: (b)** — Magnetizing current ∝ V/f; to keep it constant with f↑20%, V must also rise 20% (V/f constant).
**Concept:** Iμ ∝ V/f (constant flux → V ∝ f).
**Twist:** If V held constant while f↑20% → flux/magnetizing current FALLS (field weakening, Q177). Keeping Iμ constant is exactly V/f control.

**Q182 (TSPSC-2023):** In a slip power recovery scheme of 3-phase induction motor drives, what is the operating speed with respect to synchronous speed, if the power is injected into the rotor circuit from an external source?
(a) Motor speed reduces to zero (b) Motor speed is above the synchronous speed (c) Motor speed equals synchronous speed (d) Motor speed always below synchronous speed
**Ans: (b)** — Injecting power into rotor accelerates it → super-synchronous speed.
**Concept:** Slip-power recovery (Kramer drive) super-synchronous.
**Twist:** Recovering slip power (output) → sub-synchronous speed control; injecting power (input) → above Ns (Q94). Speed can exceed Ns because net rotor power is supplied externally.

**Q183 (TSPSC-2023):** What is the condition to achieve regenerative braking of induction motor?
(a) Synchronous speed should be increased by a factor of 1.5 (b) Synchronous speed should be a little higher than the rotor speed (c) Synchronous speed should be a little lower than the rotor speed (d) Synchronous speed should be doubled
**Ans: (c)** — Regeneration when Ns < Nr (negative slip, s<0).
**Concept:** Regenerative braking: Nr > Ns.
**Twist:** Motoring needs Ns>Nr (s>0). If Nr pulled above Ns (e.g., descending load) → machine generates and returns power. Plugging (Q179) is Ns reversed, not just lower.

## Unit 4: Synchronous Machines (181 Qs)

**Q1 (EPDCL-10):** To minimize both the 5th and 7th harmonics, the coil-span must be
(a) 144° (b) 6/7 pole-pitch (c) 5/6 pole-pitch (d) 120°
**Ans: (c)** — Coil span to kill harmonic n = 180°(1−1/n): 5th→144°, 7th→154.4°; average = 150° = 5/6 pole-pitch.
**Concept:** Harmonic elimination by chording — coil span = 180°(1−1/n).
**Twist:** eliminate only the 5th → 144° (4/5 pitch). Eliminate only the 7th → 6/7 pitch (154.4°).

**Q2 (EPDCL-10):** For fixed shaft load, armature current of a synchronous motor is minimum when power factor is
(a) less than unity & leading (b) unity (c) lagging (d) leading or lagging but not unity
**Ans: (b)** — P = VI·cosφ → I ∝ 1/cosφ; I is minimum at cosφ = 1 (UPF).
**Concept:** I = P/(V cosφ); minimum armature current at unity pf.
**Twist:** underexcited (lagging pf) → larger Ia. Overexcited (leading pf) → larger Ia.

**Q3 (EPDCL-10):** 500 kW, 3-ph, 3.3 kV, 50 Hz, 0.8 lag, 4-pole, star-connected synchronous motor (Xs = 15 Ω, Ra = 0). Stator current is
(a) 10.93 A (b) 1.093 A (c) 109.3 A (d) 0.1093 A
**Ans: (c)** — Ia = 500×10³/(√3 × 3300 × 0.8) = 109.31 A.
**Concept:** P = √3 VL IL cosφ.
**Twist:** at unity pf → 87.5 A. Delta connected → IL = √3 × Iph.

**Q4 (EPDCL-10):** The torque expression of a synchronous motor has
(a) two components (b) three components (c) four components (d) five components
**Ans: (a)** — Electromagnetic torque + reluctance torque (salient pole adds the reluctance term).
**Concept:** T = Tem + Trel (electromagnetic ∝ sinδ + reluctance ∝ sin2δ).
**Twist:** cylindrical rotor (Xq = Xd) → only 1 (electromagnetic) component. Salient pole → 2 components.

**Q5 (SSC-JE-10):** Variation in DC excitation of a synchronous motor causes variation in:
(a) speed (b) power factor (c) armature current (d) both (b) and (c)
**Ans: (d)** — Excitation changes pf and Ia (V-curve); speed stays constant.
**Concept:** V-curve (Ia vs If) & inverted-V (pf vs If) — excitation controls pf and Ia only.
**Twist:** overexcited → leading pf; underexcited → lagging pf (speed never changes).

**Q6 (SSC-JE-10):** 3-ph, 4-pole, 50 Hz synchronous motor; frequency, poles and load torque all halved. Motor speed will be
(a) 375 rpm (b) 75 rpm (c) 1500 rpm (d) 3000 rpm
**Ans: (c)** — N = 120f/P; halving both f and P leaves speed = 120×50/4 = 1500 rpm.
**Concept:** Ns = 120f/P (synchronous speed).
**Twist:** only f halved → 750 rpm. Only P halved → 3000 rpm.

**Q7 (SSC-JE-10):** While starting a synchronous motor, its field winding should be:
(a) kept open (b) connected to DC source (c) connected to AC source (d) kept short-circuited
**Ans: (d)** — Shorting the field lets the damper winding build induction (asynchronous) torque for starting.
**Concept:** Starting of synchronous motor — field shorted + damper winding.
**Twist:** after synchronizing, field is switched to DC supply.

**Q8 (SSC-JE-11):** 3-phase synchronous generator stator is star-connected because delta connection would
(a) have circulating currents due to triple-n harmonics (b) require more insulation/conductor (c) require larger conductor/core (d) result in short circuit
**Ans: (a)** — Delta allows 3rd/triple-n harmonic circulating currents; star suppresses them.
**Concept:** Star winding blocks triple-n harmonic circulating currents.
**Twist:** star needs less insulation than delta for same line voltage.

**Q9 (SSC-JE-11):** Alternator rated field current 3 A; develops 180 V at field current 1.5 A at rated speed. At 3 A field, generated voltage would be
(a) 360 V (b) 180 V (c) less than 360 V (d) 270 V
**Ans: (c)** — Eg ∝ flux ∝ If (linear estimate = 360 V) but hysteresis/saturation makes it slightly less than 360 V.
**Concept:** Eg = 4.44 f Φ T Kw; Eg ∝ If on linear (unsaturated) region.
**Twist:** if machine is strictly linear (no saturation) → exactly 360 V.

**Q10 (AP Genco-12):** Potier triangle of synchronous generator — segment DE refers to field current to compensate
(a) leakage reactance drop (b) armature reaction (c) saturation (d) resistance drop
**Ans: (b)** — DE = If for armature reaction drop; CD = If for leakage reactance drop.
**Concept:** Potier triangle (ZPF method) splits armature reaction and leakage reactance.
**Twist:** segment CD (horizontal side) → leakage reactance drop.

**Q11 (AP Genco-12):** In slip test on salient-pole machine, stator mmf alignment for maximum/minimum current drawn is
(a) 45°-to-q / d-axis (b) q-axis / 45°-to-d (c) d-axis / q-axis (d) q-axis / d-axis
**Ans: (d)** — Ia max when flux along q-axis (low Xq); Ia min when flux along d-axis (high Xd).
**Concept:** Slip test — Xd = Vmax/Imin, Xq = Vmin/Imax.
**Twist:** Xd > Xq always for salient-pole; cylindrical rotor → Xd = Xq.

**Q12 (AP Genco-12):** Two parallel generators G1, G2 equally sharing lagging kVAR. To shift kVAR from G2 to G1 keeping Vt fixed:
(a) raise If1 and lower If2 (b) lower If1 and raise If2 (c) lower If1 or raise If2 (d) raise If1 or lower If2
**Ans: (a)** — kVAR transfer is by excitation; raise G1, lower G2, with Vt = (Ef1+Ef2)/2 kept constant.
**Concept:** Reactive-power sharing ↔ field excitation; active power ↔ steam input.
**Twist:** to shift kW instead → increase steam/prime-mover input of G1.

**Q13 (AP Genco-12):** Salient-pole phasor diagram (IdXd, IqXq, V, E0) — correct mode of operation
(a) generator, lagging pf (b) generator, upf (c) motor, leading pf (d) motor, upf
**Ans: (c)** — Ef lags Vt → motoring; Ia leads Vt → leading pf.
**Concept:** Generator: Ef leads Vt by δ; Motor: Ef lags Vt by δ.
**Twist:** Ef leading Vt → generator. Ef = Vt with Ia in phase → motor, upf.

**Q14 (APTranso-12):** A synchronous motor can be used as a synchronous capacitor when it is
(a) over loaded (b) under loaded (c) over excited (d) under excited
**Ans: (c)** — Overexcited (leading pf) motor supplies reactive power like a capacitor.
**Concept:** Synchronous condenser = overexcited, no-load synchronous motor.
**Twist:** underexcited motor → behaves as an inductor (absorbs kVAR).

**Q15 (AP Transo-12):** Harmonic component of generated emf will be more in alternators with
(a) full pitch coils (b) short pitch coils (c) long pitch coils (d) none
**Ans: (a)** — Full-pitch winding keeps odd space harmonics; short-pitch (chording) suppresses them.
**Concept:** Short pitching eliminates harmonics (chording).
**Twist:** short-pitch 5/6 → eliminates 5th & 7th harmonics.

**Q16 (AP Transo-12):** V-curves for a synchronous motor represent the relation between
(a) armature current and field current (b) field current and speed (c) field current and pf (d) pf and speed
**Ans: (a)** — V-curve: Ia vs If; inverted-V: pf vs If.
**Concept:** V-curve / inverted-V curve.
**Twist:** inverted-V curve → pf vs field current.

**Q17 (APSPDCL-12):** Match List-I with List-II: (p) Damper bars (q) Rotor bars (r) Commutator vs 1. DC machine, 2. Synchronous machine, 3. Induction machine
(a) p-1,q-2,r-3 (b) p-3,q-1,r-2 (c) p-2,q-3,r-1 (d) p-3,q-2,r-1
**Ans: (c)** — Damper bars → synchronous; rotor bars → induction (squirrel cage); commutator → DC machine.
**Concept:** Machine constructional parts.
**Twist:** slip rings → synchronous machine (rotor field).

**Q18 (APSPDCL-12):** Stationary-armature conductors 1, 1', 2, 2' near rotor N/S poles — direction of induced emf at the instant (figure: 1,1' on d-axis; 2,2' on q-axis) is
(a) 1:(×) 1':(O) 2:(O) 2':(O) (b) 1:(O) 1':(O) 2:(×) 2':(O) (c) 1:(×) 1':(O) 2:(×) 2':(O) (d) 1:(O) 1':(×) 2:(O) 2':(×)
**Ans: (a)** — 1 & 1' lie along d-axis → maximum emf (opposite signs under N/S); 2 & 2' along q-axis → zero emf. Fleming's right-hand rule.
**Concept:** emf generation — Fleming's right-hand rule; d-axis vs q-axis conductors.
**Twist:** reverse rotor rotation → emf directions in 1,1' flip.

**Q19 (APSPDCL-12):** Synchronous machine, Xs = 1 pu, V = 1 pu; emf = 1.5 pu, current = (0 + j0.5) pu. Mode of operation is
(a) generator, lagging pf (b) generator, leading pf (c) motor, lagging pf (d) motor, leading pf
**Ans: (d)** — Motor: Ef = Vt − jIaXs = 1 − j(0+j0.5) = 1.5 pu (matches); Ia leads Vt by 90° → leading pf motor.
**Concept:** Ef = Vt − jIaXs (motor) / Ef = Vt + jIaXs (generator).
**Twist:** if Ef = 0.5 pu → generator (Ef = Vt + jIaXs). Ia real (in phase) → upf.

**Q20 (APSPDCL-12):** 3-phase, 16-pole, 108-slot alternator — phase grouping per phase for 60° phase spread
(a) 2,2,2,2 / 4-pole unit (b) 3,2,2,2 / 4-pole unit (c) 3,2,2,2 / 16-pole unit (d) 2,2,2,2 / 8-pole unit
**Ans: (b)** — Slots/pole = 108/16 = 6.75 = 27/4; basic 4-pole unit gives 9 slots/phase → distribution [3,2,2,2].
**Concept:** Slot distribution / phase grouping for 60° spread.
**Twist:** 120° spread → wider group (more slots per phase band).

**Q21 (APSPDCL-12):** Variation of synchronizing power with power angle for salient-pole machine (four Psy vs α curves) is
(a) straight line (b) single cos curve (c) sum of cosδ and cos2δ components (d) negative-only curve
**Ans: (c)** — Psy = (EfVt/Xd)cosδ + (Vt²/2)(1/Xq − 1/Xd)·2cos2δ.
**Concept:** Synchronizing power coefficient Psy = dP/dδ (salient-pole has extra cos2δ term).
**Twist:** cylindrical rotor → only (EfVt/Xs)cosδ term.

**Q22 (APSPDCL-12):** Supply frequency & voltage both reduced to Kf, KV — maximum power of motor becomes
(a) K times Pmax at f (b) (1/K) times (c) K² times (d) (1/K²) times
**Ans: (a)** — Pmax = EfVt/Xs; Xs = 2πfL; with V→kV, f→kf: Ef→kEf, Xs→kXs ⇒ Pmax(new) = (kEf·kV)/(kXs) = k·Pmax.
**Concept:** Pmax = EfVt/Xs with Xs ∝ f.
**Twist:** only V reduced (f fixed) → Pmax ∝ V². Only f reduced (V fixed) → Pmax ∝ 1/f.

**Q23 (APSPDCL-12):** Salient-pole synchronous machine, when speed becomes super-synchronous during hunting, damper bars develop
(a) synchronous motor torque (b) dc motor torque (c) induction motor torque (d) induction generator torque
**Ans: (d)** — Nr > Ns → slip reverses → induction-generator (braking) torque damps hunting.
**Concept:** Hunting — damper winding induction torque; super-synchronous → generator torque.
**Twist:** sub-synchronous speed during hunting → induction motor torque.

**Q24 (HMWS-12):** High-speed alternators are driven by
(a) diesel engines (b) hydraulic turbines (c) steam turbines (d) electric motors
**Ans: (c)** — Steam turbines run 3000 rpm (2-pole, cylindrical rotor).
**Concept:** Turbo-alternator (high speed); hydro → low-speed salient-pole.
**Twist:** low-speed alternators → diesel engine / hydraulic (water) turbine.

**Q25 (HMWS-12):** Number of cycles generated in a 6-pole alternator in one revolution
(a) 18 (b) 12 (c) 6 (d) 3
**Ans: (d)** — Cycles per revolution = P/2 = 3.
**Concept:** cycles/rev = P/2 (electrical degrees per rev = P×180°).
**Twist:** 8-pole → 4 cycles/rev. 2-pole → 1 cycle/rev.

**Q26 (HMWS-12):** Frequency of emf generated in an 8-pole alternator running at 900 rpm
(a) 60 Hz (b) 120 Hz (c) 30 Hz (d) 180 Hz
**Ans: (a)** — f = PN/120 = 8×900/120 = 60 Hz.
**Concept:** f = PN/120.
**Twist:** 4-pole at 1500 rpm → 50 Hz. 2-pole at 3000 rpm → 50 Hz.

**Q27 (HMWS-12):** Coil span falls short of full pitch by 60° (electrical) — pitch factor is
(a) 0.5 (b) 0.866 (c) 0.25 (d) 1.0
**Ans: (b)** — α = 60°; Kp = cos(α/2) = cos 30° = 0.866.
**Concept:** Pitch factor Kp = cos(α/2).
**Twist:** short pitch by 120° → Kp = cos 60° = 0.5. Full pitch → Kp = 1.

**Q28 (HMWS-12):** Per-phase DC armature resistance of an alternator is 0.5 Ω; effective AC resistance would be about
(a) 0.5 Ω (b) 0.25 Ω (c) 0.75 Ω (d) 4 Ω
**Ans: (c)** — Rac ≈ 1.5 × Rdc = 0.75 Ω (skin effect).
**Concept:** AC resistance > DC resistance due to skin effect (Rac ≈ 1.5 Rdc).
**Twist:** at very low frequency / thin conductors → Rac ≈ Rdc.

**Q29 (HMWS-12):** An under-excited synchronous motor behaves as
(a) a capacitor (b) a resistor (c) resistor-capacitor series (d) an inductor
**Ans: (d)** — Underexcited motor draws lagging (inductive) reactive power → acts as an inductor.
**Concept:** Underexcitation → lagging pf; overexcitation → leading pf.
**Twist:** overexcited motor → capacitor (leading kVAR supply).

**Q30 (HMWS-12):** Increased load demand in a synchronous motor is met by
(a) reduction in speed (b) increase in speed (c) decrease in stator current (d) relative shift between stator and rotor poles
**Ans: (d)** — Load increase retards rotor → load angle δ increases (speed stays constant).
**Concept:** Load-angle (torque angle) δ; synchronous speed is load-independent.
**Twist:** δ increase at constant excitation → P = (EfVt/Xs)sinδ increases.

**Q31 (HMWS-12):** Mechanical power developed by a synchronous motor is independent of
(a) applied stator voltage (b) torque angle (c) field excitation (d) speed
**Ans: (d)** — P = (EfVt/Xs)sinδ has no speed term; speed is constant anyway.
**Concept:** P = (EfVt/Xs)sinδ (independent of speed).
**Twist:** P ∝ Vt (stator voltage); P ∝ Ef (excitation).

**Q32 (HMWS-12):** A two-pole alternator running at 1500 rpm — its angular velocity is
(a) 118 rad/s (b) 192 rad/s (c) 157 rad/s (d) 212 rad/s
**Ans: (c)** — ω = 2πN/60 = 2π×1500/60 = 157 rad/s.
**Concept:** ω = 2πN/60 (mechanical rad/s).
**Twist:** 3000 rpm → 314 rad/s. At 50 Hz electrical, ωe = 2πf = 314 rad/s.

**Q33 (HMWS-12):** Synchronous impedance test, star alternator: SC line current 18.67 A, OC line-line voltage 240.3 V same excitation. Synchronous impedance
(a) 7.43 Ω (b) 12.4 Ω (c) 3.93 Ω (d) 5.84 Ω
**Ans: (a)** — Xs = (240.3/√3)/18.67 = 7.42 Ω/ph.
**Concept:** Zs = Voc(phase)/Isc (synchronous impedance test).
**Twist:** if line voltage mistakenly taken as phase → double the answer.

**Q34 (Transco-12):** During hunting of a synchronous motor
(a) negative-sequence currents generated (b) harmonics in armature (c) damper bar develops torque (d) field excitation increases
**Ans: (c)** — Hunting (Nr ≠ Ns) induces emf in damper bars → torque that damps oscillations.
**Concept:** Hunting — damper winding damping torque.
**Twist:** super-synchronous → induction generator (braking) torque in damper.

**Q35 (Transco-12):** Phase sequence of a 3-phase alternator will reverse if
(a) field current reversed, rotation same (b) field current same, direction of rotation reversed (c) field reversed & poles doubled (d) poles doubled without reversing field
**Ans: (b)** — Reverse rotation (or interchange any two terminals) reverses phase sequence.
**Concept:** Phase-sequence reversal.
**Twist:** interchange any two phase terminals of the output → reversed sequence.

**Q36 (SSC-JE-12):** Pitch factor for a full-pitched winding of a synchronous machine
(a) 0.9 (b) 0.0 (c) 1.0 (d) 0.5
**Ans: (c)** — α = 0° → Kp = cos(0) = 1.
**Concept:** Pitch factor Kp = cos(α/2) = 1 for full pitch.
**Twist:** short-pitched by 120° → 0.5; by 60° → 0.866.

**Q37 (SSC-JE-12):** Which is correct?
(a) effect of armature current on main flux is called armature reaction (b) effect of armature current on air-gap flux (c) effect of field current on main flux (d) effect of air-gap flux on armature current
**Ans: (a)** — Armature reaction = effect of armature (stator) MMF on the main field flux.
**Concept:** Armature reaction definition.
**Twist:** generator zpf-lag → demagnetizing; zpf-lead → magnetizing; upf → cross-magnetizing.

**Q38 (SSC-JE-12):** AC series motors are built with as few turns as possible to reduce
(a) Reactance (b) Iron losses (c) Speed (d) Flux
**Ans: (a)** — Fewer turns → lower series reactance (armature reaction compensation).
**Concept:** AC series motor — reactance reduction (also needs compensation for AR).
**Twist:** low-frequency supply → less reactance drop, better commutation.

**Q39 (SSC-JE-12):** Two alternators, 40 MVA and 60 MVA, in parallel supplying 80 MW; both speed regulation 5%. Load sharing
(a) 36, 44 MW (b) 40, 40 MW (c) 30, 50 MW (d) 32, 48 MW
**Ans: (d)** — Same droop → share ∝ rating: PA:PB = 2:3, PA+PB = 80 → 32 MW & 48 MW.
**Concept:** Parallel load sharing ∝ MVA rating (equal % droop).
**Twist:** unequal droops → use droop-slope equations (as in Q45/117).

**Q40 (SSC-JE-12):** emf per phase: Kd = 0.955, Kc = 0.966, f = 50 Hz, flux 25 mWb, 240 turns/phase
(a) 1228.81 V (b) 869.46 V (c) 1737.80 V (d) 2128.36 V
**Ans: (a)** — Ef = 4.44×25×10⁻³×50×240×0.966×0.955 = 1228.81 V/ph.
**Concept:** Ef = 4.44 f Φ T Kp Kd.
**Twist:** full pitch (Kp=1) & unity distribution → 1330 V. 120° spread → different Kd.

**Q41 (SSC-JE-13):** 4-pole generator at 1200 rpm — frequency and time period of emf
(a) 50 Hz, 0.02 s (b) 40 Hz, 0.025 s (c) 300 Hz, 0.0033 s (d) 2400 Hz
**Ans: (b)** — f = 4×1200/120 = 40 Hz; T = 1/40 = 0.025 s.
**Concept:** f = PN/120; T = 1/f.
**Twist:** 4-pole at 1500 rpm → 50 Hz, T = 0.02 s.

**Q42 (SSC-JE-13):** 3-phase synchronous motor is started by torque developed in
(a) high-speed steam turbine (b) damper winding on rotor (c) damper winding on stator (d) low-speed water turbine
**Ans: (b)** — Damper winding on the rotor provides induction (asynchronous) starting torque.
**Concept:** Damper winding starting of synchronous motor.
**Twist:** damper also damps hunting during running.

**Q43 (SSC-JE-13):** Two single-phase AC motors A (2 kW, 0.8 lag) and B (1 kW, 0.5 lag) from 1000 V — total current
(a) 4.5 A (b) 2.1 A (c) 4.41 A (d) 9 A
**Ans: (c)** — IA = 2.5∠−36.86°, IB = 2∠−60°; |IA+IB| = 4.41 A.
**Concept:** Complex current (phasor) addition.
**Twist:** both at same pf → currents add arithmetically (4.5 A).

**Q44 (SSC-JE-13):** Match List-I (DC motor, DC generator, Alternator, Induction motor) with List-II (Circle diagram, V-curve, OCC, Speed-Torque)
(a) a-iv,b-iii,c-i,d-ii (b) a-iii,b-iv,c-ii,d-i (c) a-iv,b-iii,c-ii,d-i (d) a-iii,b-iv,c-i,d-ii
**Ans: (c)** — DC motor→speed-torque; DC generator→OCC; Alternator→V-curve; IM→circle diagram.
**Concept:** Machine characteristics mapping.
**Twist:** synchronous generator (vs alternator) → inverted-V curve.

**Q45 (SSC-JE-13):** 300-kW alternator (4% reg) and 200-kW alternator (3% reg) in parallel — max total load without overloading either
(a) 500 kW (b) 567 kW (c) 425 kW (d) 257 kW
**Ans: (c)** — At 3% drop B is fully loaded (200 kW); machine A then carries 225 kW; total = 425 kW.
**Concept:** Parallel operation with different speed regulations (droop).
**Twist:** same % regulation → both reach full load together (500 kW).

**Q46 (SSC-JE-13):** Alternators are usually designed to generate which type of AC voltage
(a) fixed frequency (b) variable frequency (c) fixed current (d) fixed power factor
**Ans: (a)** — Alternators generate fixed-frequency voltage (synchronous speed).
**Concept:** Constant frequency generation.
**Twist:** as synchronous motor, speed is constant (fixed frequency).

**Q47 (EPDCL-14):** Synchronous machine on grid operating as generator — to make it operate as motor, the
(a) direction of rotation is reversed (b) shaft torque is reduced (c) field excitation decreased (d) field excitation increased
**Ans: (b)** — Reduce turbine input (shaft torque) below machine losses → it starts motoring.
**Concept:** Generator ↔ motor transition by prime-mover (shaft) power.
**Twist:** increase steam input → delivers more active power to grid.

**Q48 (EPDCL-14):** Synchronous generator, constant steam input, infinite bus, lagging pf. If excitation increased
(a) both power angle and pf decrease (b) both increase (c) δ decreases, pf increases (d) δ increases, pf decreases
**Ans: (a)** — P constant → sinδ ∝ 1/Ef → δ decreases; on lagging side, more If → pf decreases.
**Concept:** P = (EfVt/Xs)sinδ + inverted-V curve.
**Twist:** excitation decreased → δ increases, pf improves (toward UPF).

**Q49 (EPDCL-14):** 10-pole, 25 Hz alternator directly coupled to and driven by a 60 Hz synchronous motor — motor poles
(a) 48 (b) 12 (c) 24 (d) 16
**Ans: (c)** — Coupled same speed: N = 120×25/10 = 300 rpm; P(motor) = 120×60/300 = 24.
**Concept:** Directly coupled machines share speed; N = 120f/P.
**Twist:** roles reversed (25 Hz motor driving 60 Hz alternator) → P = 10.

**Q50 (EPDCL-14):** The synchronous reactance is the
(a) reactance due to armature reaction (b) reactance due to leakage flux (c) combined reactance of leakage flux and armature reaction (d) either AR or leakage
**Ans: (c)** — Xs = Xar + Xleakage.
**Concept:** Xs = Xar + Xl (synchronous reactance).
**Twist:** armature reaction component Xar varies with magnetic saturation.

**Q51 (EPDCL-14):** Slip test: Vmax = 108 V, Vmin = 96 V, Imax = 12 A, Imin = 10 A → Xd, Xq
(a) Xd = 10.8 Ω, Xq = 8 Ω (b) 9, 9.6 (c) 9.6, 9 (d) 8, 10.8
**Ans: (a)** — Xd = Vmax/Imin = 108/10 = 10.8 Ω; Xq = Vmin/Imax = 96/12 = 8 Ω.
**Concept:** Slip test: Xd = Vmax/Imin, Xq = Vmin/Imax.
**Twist:** swap Vmax↔Vmin pairing → wrong Xd, Xq (option d).

**Q52 (APSPDCL-14):** Distribution of conductors (12-slot figure) — possible windings
(a) 4-pole lap or 2-pole wave (b) 2-pole lap or 4-pole wave (c) 4-pole lap or 4-pole wave (d) 2-pole lap or 2-pole wave
**Ans: (—)** — Solution: insufficient data (answer key marks *).
**Concept:** Winding connection analysis (lap/wave).
**Twist:** n/a — question itself flagged as data-insufficient.

**Q53 (APSPDCL-14):** Match List-I (Shaded ring, Compoles, Damper bars, Slip rings) with List-II (Synchronous, 3-ph IM, 1-ph IM, DC machine)
(a) l-3,m-4,n-1,k-2 (b) l-4,m-1,n-2,k-3 (c) l-1,m-2,n-3,k-4 (d) l-2,m-3,n-4,k-1
**Ans: (a)** — Shaded ring→1-ph IM; Compoles→DC; Damper bars→synchronous; Slip rings→3-ph IM.
**Concept:** Machine component → machine type.
**Twist:** damper bars also used in 3-ph IM rotor (as squirrel cage).

**Q54 (APSPDCKL-14):** α = skew angle of rotor bars in squirrel-cage IM — skew factor
(a) cos(α/2) (b) sin(α/2)/(α/2) (c) cos(α/2)/(α/2) (d) sin(α/2)
**Ans: (b)** — Ksk = sin(α/2)/(α/2).
**Concept:** Skew factor (IM construction) Ksk = sin(α/2)/(α/2).
**Twist:** zero skew → Ksk = 1.

**Q55 (APSPDCL-14):** Lowest point on V-curve does not indicate unity pf. This is
(a) due to supply frequency variations (b) inaccurate meter readings (c) due to harmonics from deviation of counter-emf from a sine wave (d) due to increase in field current
**Ans: (c)** — Harmonics in the emf shift the minimum-current point away from UPF.
**Concept:** V-curve minimum vs harmonics.
**Twist:** pure sinusoidal supply → minimum Ia coincides with UPF.

**Q56 (APSPDCL-14):** Isolated generator (not on infinite bus) at rated OC voltage, 0.8 leading load increased with field unchanged — terminal-voltage characteristic (curves a,b,c,d) is
(a) a (b) b (c) c (d) d
**Ans: (b)** — Leading pf → magnetizing AR → Vt rises; 0.8 pf near UPF → curve (b) (slight rise).
**Concept:** Isolated-generator external characteristic — leading pf gives rise, lagging gives drop.
**Twist:** lagging load (demagnetizing AR) → terminal voltage falls (curve c/d).

**Q57 (APSPDCL-14):** Field currents: If0 (rated V, OC), If1 (rated V, full-load zpf lead), If2 (upf), If3 (zpf lag) — lowest field current is
(a) If0 (b) If3 (c) If2 (d) If1
**Ans: (d)** — ZPF leading (capacitive) load needs least field current (magnetizing AR helps).
**Concept:** Field-current requirement vs load pf (V-t curves).
**Twist:** highest field current → If3 (zpf lagging, demagnetizing AR).

**Q58 (APSPDCL-14):** Induced emf per phase e = 10 sin ωt + 2 cos(3ωt + 90°) — peak value
(a) 10 V (b) 11.5 V (c) 12.0 V (d) 13.2 V
**Ans: (c)** — At ωt = 90°: 10 sin90° + 2 cos(3×90°+90°) = 10 + 2 = 12 V.
**Concept:** Instantaneous sum of fundamental + 3rd harmonic.
**Twist:** if harmonics were at 60° phase → different peak; RMS = √(10²+2²)/√2.

**Q59 (APSPDCL-14):** Synchronous motor Xs = 1.0 pu, V = 1.0 pu; current when E = 0.5∠0° pu
(a) (0 + j0.5) (b) (0.5 + j0) (c) (0.5 + j0.5) (d) (1 + j1)
**Ans: (—)** — Solution gives Ia = (Vt−Ef)/jXs = (1−0.5)/j1 = (0 − j0.5) pu, not in options (key: *).
**Concept:** Ia = (Vt − Ef)/(jXs) (motor).
**Twist:** E = 1.5∠0° → Ia = (0 + j0.5) pu (leading, overexcited motor).

**Q60 (ISRO-14):** A pony motor is used for starting which motor?
(a) squirrel-cage IM (b) Schrage motor (c) synchronous motor (d) hysteresis motor
**Ans: (c)** — Pony (small auxiliary) motor is a starting method for synchronous motors.
**Concept:** Synchronous-motor starting methods (pony motor, damper, asynchronised starting).
**Twist:** damper-winding (asynchronous) starting is the common alternative.

**Q61 (ISRO-14):** Which DC motor has highest % increase in input current for given % increase in torque?
(a) series (b) shunt (c) cumulatively compound (d) separately excited
**Ans: (b)/(d)** — Shunt & separately-excited have constant flux (T ∝ Ia), so %ΔI = %ΔT (series has T ∝ Ia², lower %ΔI).
**Concept:** T = KΦIa — flux constancy decides current sensitivity.
**Twist:** series motor T ∝ Ia² → a given %ΔT needs only half %ΔI.

**Q62 (ISRO-14):** In an alternator during hunting, when speed becomes super-synchronous, damper bars develop
(a) reluctance torque (b) pseudo-stationary torque (c) eddy current torque (d) induction generator torque
**Ans: (d)** — Super-synchronous rotor → induction-generator (braking) torque in damper.
**Concept:** Hunting / damper-bar induction torque.
**Twist:** sub-synchronous → induction motor torque (accelerating).

**Q63 (ISRO-14):** Under no-load condition, the angle between induced voltage and supply voltage in a synchronous motor is
(a) zero (b) 45° (c) 90° (d) 180°
**Ans: (a)** — No-load: Ia = 0 → Vt = Ef → δ = 0.
**Concept:** Load angle δ = 0 at no load.
**Twist:** at full load δ rises to ~20–30°.

**Q64 (ISRO-14):** Synchronous motors are not self-starting because
(a) stator is not used (b) starting winding not provided (c) there is no slip (d) direction of instantaneous torque on the rotor reverses after half cycle
**Ans: (d)** — At standstill the alternating flux gives torque that reverses each half-cycle → zero average torque.
**Concept:** Zero average starting torque (no relative motion between fields at start).
**Twist:** damper winding converts it to self-starting (induction mode).

**Q65 (ISRO-14):** Main disadvantage of short-pitch winding in alternators
(a) reduces harmonics (b) reduces total voltage around armature coils (c) produces asymmetry (d) increases Cu of end connections
**Ans: (b)** — Short-pitch lowers the fundamental voltage of each coil.
**Concept:** Chording trade-off — fewer harmonics at cost of lower fundamental emf.
**Twist:** benefit of short pitch → harmonic (especially 5th, 7th) reduction.

**Q66 (ISRO-14):** Armature reaction in an alternator mainly affects
(a) rotor speed (b) terminal voltage per phase (c) frequency of armature current (d) generated voltage per phase
**Ans: (d)** — Magnetizing/demagnetizing AR changes the induced (generated) voltage per phase.
**Concept:** Armature reaction changes effective field flux → generated emf.
**Twist:** under load it also changes terminal voltage (regulation).

**Q67 (ISRO-14):** If the field of a synchronous motor is under-excited, the power factor will be
(a) lagging (b) leading (c) unity (d) more than unity
**Ans: (a)** — Underexcitation → motor draws lagging kVAR → lagging pf.
**Concept:** Excitation ↔ pf control.
**Twist:** overexcited → leading pf.

**Q68 (ISRO-14):** Synchronous capacitor is
(a) an over-excited synchronous motor running without mechanical load (b) over-excited motor driving a load (c) an ordinary static capacitor bank (d) a rotating dynamic capacitor bank
**Ans: (a)** — Overexcited, unloaded synchronous motor supplies reactive power.
**Concept:** Synchronous condenser.
**Twist:** under-excited unloaded motor → synchronous reactor (absorbs kVAR).

**Q69 (SSC-JE-S1-14):** Synchronous motor working at leading pf can be used as
(a) voltage booster (b) phase advancer (c) noise generator (d) mechanical synchronizer
**Ans: (a)** — Leading-pf (overexcited) motor supplies reactive power → boosts/regulates voltage.
**Concept:** Synchronous condenser — voltage regulation of system.
**Twist:** also improves overall system power factor.

**Q70 (SSC-JE-S1-14):** Speed of a P-pole synchronous machine in rpm
(a) 120f/P (b) 120P/f (c) 120Pf (d) 120/Pf
**Ans: (a)** — Ns = 120f/P.
**Concept:** Ns = 120f/P (rpm).
**Twist:** in rev/s → 2f/P; angular velocity ω = 4πf/P.

**Q71 (SSC-JE-S1-14):** Which condition is NOT mandatory for alternators operating in parallel?
(a) terminal voltage same (b) machines must have equal kVA ratings (c) same frequency (d) same phase sequence
**Ans: (b)** — Equal voltage, frequency & phase sequence are required; equal kVA rating is not.
**Concept:** Synchronizing/paralleling conditions.
**Twist:** for proportional load sharing, ratings matter but are not a synchronizing condition.

**Q72 (SSC-JE-S1-14):** Regulation of an alternator supplying resistive or inductive load is
(a) always negative (b) always positive (c) zero (d) infinity
**Ans: (b)** — Upf and lagging loads give positive regulation (voltage drops on load).
**Concept:** Voltage regulation polarity — lag/upf positive; leading negative.
**Twist:** leading (capacitive) load → negative regulation (V rises).

**Q73 (SSC-JE-S1-14):** Hydrogen is used in large alternators mainly to
(a) reduce distortion of waveform (b) cool the machine (c) strengthen the magnetic field (d) reduce eddy current loss
**Ans: (b)** — Hydrogen cooling (high specific heat, low windage) for large generators.
**Concept:** Hydrogen cooling of turbo-alternators.
**Twist:** also reduces windage loss (low density) vs air.

**Q74 (SSC-JE-S1-14):** For V-curves of a synchronous motor the graph is drawn between
(a) field current and armature current (b) terminal voltage and load factor (c) pf and field current (d) armature current and pf
**Ans: (a)** — V-curve: field current vs armature current.
**Concept:** V-curve / inverted-V curve.
**Twist:** inverted-V curve → pf vs field current.

**Q75 (SSC-JE-S1-14):** Low-frequency operation of AC series motor in traction
(a) improves commutation but pf/efficiency reduce (b) improves commutation, pf and efficiency (c) adversely affects commutation but pf improves (d) improves commutation but starting current increases
**Ans: (d)** — Low f → low reactance → better commutation but large starting current.
**Concept:** AC series motor reactance at low frequency (traction).
**Twist:** 50 Hz operation → higher reactance, worse commutation.

**Q76 (SSC-JE-S2-14):** If excitation of an alternator in parallel is increased above normal
(a) its pf becomes more lagging (b) pf becomes more leading (c) output current decreases (d) output kW decreases
**Ans: (a)** — Overexcited alternator on grid draws/injects lagging reactive current → pf more lagging.
**Concept:** Inverted-V: alternator excitation ↑ → pf worsens (lagging).
**Twist:** reducing excitation below normal → leading pf.

**Q77 (SSC-JE-S2-14):** In an alternator, effect of armature reaction is minimum at power factor of
(a) 0.5 lagging (b) 0.866 lagging (c) 0.866 leading (d) unity
**Ans: (d)** — At UPF AR is purely cross-magnetizing (least voltage effect); at zpf lag it is fully demagnetizing.
**Concept:** Armature reaction vs pf.
**Twist:** zpf leading → fully magnetizing (maximum effect on V).

**Q78 (SSC-JE-S2-14):** Damper winding in synchronous motors is used to
(a) suppress hunting (b) improve pf (c) develop reluctance torque (d) improve efficiency
**Ans: (a)** — Damper winding damps (suppresses) hunting oscillations.
**Concept:** Damper winding — hunting suppression.
**Twist:** also provides starting torque (asynchronous starting).

**Q79 (SSC-JE-S2-14):** Turbo-alternators have rotors of
(a) small diameter and long axial length (b) large diameter and long axial (c) large diameter and small axial (d) small diameter and small axial
**Ans: (a)** — High-speed (2-pole) cylindrical rotor: small diameter, long axial length.
**Concept:** Turbo (cylindrical) rotor vs salient-pole rotor.
**Twist:** salient-pole (hydro, low-speed) → large diameter, short axial length.

**Q80 (SSC-JE-S2-14):** A synchronous motor can be used as synchronous condenser when it is
(a) over excited (b) overloaded (c) under excited (d) under loaded
**Ans: (a)** — Overexcited synchronous motor = synchronous condenser.
**Concept:** Synchronous condenser (overexcitation, no load).
**Twist:** underexcited → absorbs reactive power (reactor).

**Q81 (SSC-JE-S2-14):** Which method gives higher than actual regulation of an alternator?
(a) ZPF method (b) MMF method (c) EMF method (d) ASA method
**Ans: (c)** — EMF (synchronous impedance) method overestimates regulation; MMF method underestimates.
**Concept:** EMF → pessimistic; MMF → optimistic; ZPF/ASA → close to actual.
**Twist:** MMF method → lower than actual regulation.

**Q82 (HMWS-15):** To reverse the phase sequence of voltage generated in an alternator
(a) not possible (b) interchange any two phase terminals (c) interchange all three terminals (d) reverse field winding connection
**Ans: (b)** — Interchanging any two phases reverses the phase sequence.
**Concept:** Phase-sequence reversal.
**Twist:** reversing rotor direction also reverses phase sequence.

**Q83 (HMWS-15):** Which method gives voltage regulation more than the actual value
(a) no-load method (b) synchronous impedance method (c) MMF method (d) zero power factor method
**Ans: (b)** — Synchronous impedance (EMF) method gives pessimistic (higher) regulation.
**Concept:** Regulation prediction methods.
**Twist:** MMF method → lower; ZPF (Potier) → accurate.

**Q84 (HMWS-15):** Damping winding in a synchronous motor is generally used
(a) to prevent hunting and provide starting torque (b) to reduce noise (c) to reduce eddy currents (d) to provide starting torque only
**Ans: (a)** — Damper winding: starting torque + hunting suppression.
**Concept:** Damper winding dual role.
**Twist:** if only hunting is the issue → still needs damper.

**Q85 (HMWS-15):** If excitation of a synchronous generator fails, it acts as
(a) induction generator (b) synchronous generator (c) induction motor (d) synchronous motor
**Ans: (a)** — Loss of excitation → machine continues as induction generator (draws magnetizing current from grid).
**Concept:** Loss-of-excitation behaviour.
**Twist:** under-excited → absorbs large lagging current from bus.

**Q86 (HMWS-15):** In an alternator, for a full-pitch stator winding, generated voltages in both coil sides are
(a) approximately 180° out of phase (b) in quadrature (c) exactly 180° out of phase (d) exactly in phase
**Ans: (d)** — Full-pitch: the two coil-side emfs are in phase (add, series aiding).
**Concept:** Full-pitch coil — coil sides 180° (elec) apart give in-phase emfs.
**Twist:** short-pitch coil → phase difference between side emfs (resultant reduced).

**Q87 (HMWS-15):** Synchronous reactance of an alternator represents
(a) a reactance connected in series with the generator (b) reactance at synchronous speed (c) field-winding reactance (d) armature reactance and leakage reactance
**Ans: (d)** — Xs = armature-reaction reactance + leakage reactance.
**Concept:** Xs = Xar + Xleakage.
**Twist:** Xar accounts for armature reaction (simulated by reactance).

**Q88 (HMWS-15):** Voltage regulation of an alternator depends on
(a) no-load current only (b) pf only (c) both load current and power factor (d) load current only
**Ans: (c)** — VR = (E−V)/V depends on load magnitude and its pf.
**Concept:** Voltage regulation = (E−Vt)/Vt; depends on load & pf.
**Twist:** leading load → negative regulation (V rises).

**Q89 (HMWS-15):** Distribution of load between two alternators in parallel can be changed by changing
(a) load currents (b) field excitation (c) driving torques of prime movers (d) phase sequence
**Ans: (c)** — Active (kW) sharing is set by prime-mover (steam/governor) input.
**Concept:** kW sharing ↔ prime-mover input; kVAR sharing ↔ excitation.
**Twist:** reactive power sharing changed by field excitation.

**Q90 (HMWS-15):** In an alternator for zero leading pf, the effect of armature reaction is
(a) zero effect (b) demagnetizing only (c) cross-magnetizing only (d) magnetizing only
**Ans: (d)** — zpf leading → purely magnetizing AR.
**Concept:** AR: zpf lag → demagnetizing; zpf lead → magnetizing; upf → cross.
**Twist:** zpf lagging → purely demagnetizing.

**Q91 (HMWS-15):** The 'V' curve of a synchronous motor shows relation between
(a) armature voltage and pf (b) pf and field current (c) armature current and pf (d) armature current and field current
**Ans: (d)** — V-curve: armature current vs field current.
**Concept:** V-curve.
**Twist:** inverted-V curve → pf vs field current.

**Q92 (HMWS-15):** Field winding of an alternator is excited by
(a) universal supply (b) AC supply (c) both DC and AC (d) DC supply
**Ans: (d)** — Field is energized by DC to produce steady main flux.
**Concept:** DC field excitation.
**Twist:** modern excitation via brushless AC exciter + rotating rectifier (still rectified DC on field).

**Q93 (HMWS-15):** Under short-circuit conditions, the power factor of an alternator is
(a) almost zero leading (b) unity (c) almost 0.6 lagging (d) almost zero lagging
**Ans: (d)** — SC current is limited by Xs, almost purely reactive → ~zero pf lagging.
**Concept:** SC test pf ≈ zero (lagging).
**Twist:** OC test → upf (open circuit draws no current).

**Q94 (TGenco-15):** In a synchronous generator delivering lagging pf load
(a) excitation emf leads terminal voltage by the power angle (b) lags by the power angle (c) leads by the pf angle (d) lags by the pf angle
**Ans: (a)** — Generator: Ef leads Vt by the load angle δ.
**Concept:** Ef leads Vt by δ (generator); Ef lags Vt by δ (motor).
**Twist:** motoring mode → Ef lags Vt by δ.

**Q95 (TS Transco-15):** Undamped frequency of oscillations of a synchronous machine is
(a) √(Pγ/M) (b) (Pγ/M)² (c) (Pγ/M)⁴ (d) √(Pγ/4M)... — options are (Pγ/M)^(0.5), ^2, ^4, (Pγ/4M)²
**Ans: (a)** — ωr = √(dP/dδ / M) = √(Psyn/M) — natural oscillation frequency.
**Concept:** ωr = √(Psyn/M); Psyn = synchronizing power coefficient.
**Twist:** with damping → damped frequency lower than undamped.

**Q96 (TS Transco-15):** Fall in speed of a DC generator due to increase in load can be corrected by
(a) cooling the armature (b) increasing the excitation (c) reducing load voltage (d) increasing the input to the prime mover
**Ans: (d)** — Increase prime-mover input (governor) restores speed (true for both DC and AC generators).
**Concept:** Speed/load regulation via prime-mover (governor).
**Twist:** for a synchronous generator, frequency ↔ speed governed by prime mover.

**Q97 (TS Transco-15):** In a synchronous machine, if the field flux axis is ahead of the armature field axis in the direction of rotation, the machine operates as
(a) synchronous motor (b) synchronous generator (c) asynchronous motor (d) asynchronous generator
**Ans: (b)** — Generator: main (field) pole axis leads armature field; armature pulls it back. Motor: armature field leads.
**Concept:** Field vs armature field axis (load angle) — generator vs motor.
**Twist:** armature field axis ahead of field → synchronous motor.

**Q98 (TSSPDCL-15):** In a 3-phase alternator, if there is only magnetizing armature reaction, the load is
(a) capacitive (b) inductive (c) resistive (d) inductive and resistive
**Ans: (a)** — Magnetizing AR occurs for leading (capacitive) load current.
**Concept:** AR vs pf: capacitive → magnetizing; inductive → demagnetizing.
**Twist:** inductive load → demagnetizing AR.

**Q99 (TSSPDCL-15):** The Potier triangle is always a/an __ triangle in VR measurement of 3-φ alternator using __ method
(a) equilateral … ZPF (b) isosceles … ZPF (c) right-angled … ZPF (d) obtuse … MMF
**Ans: (c)** — Potier triangle (from OCC + ZPF test) is a right-angled triangle.
**Concept:** Potier triangle / ZPF method.
**Twist:** horizontal side = leakage-reactance drop; vertical = armature-reaction drop.

**Q100 (TSSPDCL-15):** If Φm is peak flux, magnitudes of rotating magnetic field for 2-phase and 3-phase supply
(a) Φm and 1.5×Φm (b) Φm and √3×Φm (c) √2×Φm and 1.5×Φm (d) √2×Φm and √3×Φm
**Ans: (a)** — 2-phase RMF = (2/2)F1ph = Φm; 3-phase = (3/2)F1ph = 1.5Φm.
**Concept:** RMF amplitude = (m/2)×max per-phase mmf.
**Twist:** m-phase in general → (m/2)Fmax(phase).

**Q101 (TSSPDCL-15):** In the operating region (δ < 70°), synchronizing power coefficient is
(a) larger in round rotor than salient pole (b) same in both (c) larger in salient pole than round rotor (d) zero in both
**Ans: (a)/(c)** — 0–45°: salient > cylindrical (extra cos2δ term); 45–70°: equal. (Key marks both a & c.)
**Concept:** Psy = dP/dδ; salient pole adds (Vt²/2)(1/Xq − 1/Xd)·2cos2δ.
**Twist:** beyond 70° machine approaches instability; δ = 90° is steady-state limit.

**Q102 (TSSPDCL-15):** Constant-flux (V/f) control of 3-φ synchronous motor: V = kf at medium/rated frequencies; at very low frequencies supply voltage should be
(a) greater than kf (b) equal to kf^1.6 (c) less than kf (d) equal to kf
**Ans: (a)** — At low f, IR drop & residual/hysteresis flux need voltage boost V > kf.
**Concept:** V/f control with low-frequency voltage boost.
**Twist:** medium/high frequencies → V = kf exactly.

**Q103 (TSNPDCL-15):** Armature current on symmetrical 3-phase short circuit of a synchronous machine (salient pole)
(a) has q-axis current only (b) has d-axis current only (c) has both d & q axis currents (d) cannot be divided between q and d axis
**Ans: (b)** — 3-ph SC: Ia lags Ef by 90° → fully demagnetizing → only d-axis current (Iq = 0).
**Concept:** Symmetrical SC → d-axis current (pure demagnetization).
**Twist:** unsymmetrical faults → sequence components; at leading load Iq component appears.

**Q104 (TSNPDCL-15):** In a synchronous generator, excitation increased from low to normal value with fixed load
(a) Ia increases, pf decreases (b) Ia decreases, pf decreases (c) Ia decreases, pf increases & lagging (d) Ia decreases, pf increases & leading
**Ans: (d)** — Moving up the leading side of the V-curve: Ia falls and pf improves (leading).
**Concept:** V-curve / inverted-V with fixed P.
**Twist:** excitation beyond normal (overexcitation) → pf falls again (lagging).

**Q105 (TSNPDCL-15):** Damper winding in 3-phase synchronous motors is provided to
(a) prevent hunting only (b) provide starting torque and prevent hunting (c) provide starting torque only (d) prevent crawling
**Ans: (b)** — Damper: starting torque + anti-hunting.
**Concept:** Damper winding functions.
**Twist:** at synchronous speed damper carries no current (no slip).

**Q106 (TSNPDCL-15):** Slip test is performed to determine
(a) slip in an induction motor (b) Xd and Xq in a salient-pole alternator (c) synchronous impedance (d) positive/negative sequence impedances
**Ans: (b)** — Slip test gives Xd, Xq of salient-pole machines.
**Concept:** Slip test — Xd, Xq.
**Twist:** OC-SC test → Zs; it is not an IM slip measurement.

**Q107 (AP Genco-17):** 210 MW turbo-alternator — possible specs of rotor diameter, stator core length, poles
(a) 4.4 m, 1.2 m, 12 (b) 1.2 m, 4.4 m, 2 (c) 4.4 m, 1.2 m, 24 (d) 1.2 m, 4.4 m, 8
**Ans: (b)** — Turbo: high speed → few poles (2), small diameter, long axial core.
**Concept:** Turbo-alternator rotor proportions.
**Twist:** hydro alternator → large diameter, many poles, short axial.

**Q108 (AP Genco-17):** Reluctance torque of a 3-phase salient-pole synchronous generator is proportional to
(a) Xd − Xq (b) Xd × Xq (c) 1/Xd − 1/Xq (d) 1/Xq − 1/Xd
**Ans: (d)** — Preluctance = (3Vt²/2)(1/Xq − 1/Xd)sin2δ.
**Concept:** Reluctance power/torque ∝ (1/Xq − 1/Xd) sin2δ.
**Twist:** max reluctance torque at δ = 45°; cylindrical rotor (Xd=Xq) → zero reluctance torque.

**Q109 (AP Genco-17):** When two alternators operate in parallel, the cause of circulating current is
(a) increase in excitation of one machine (b) increase in driving torque of one machine (c) reduction in angular velocity of one (d) identical speed/load characteristics of both
**Ans: (a)/(b)** — Circulating current arises from excitation mismatch OR prime-mover (torque) mismatch.
**Concept:** Circulating currents in parallel operation.
**Twist:** identical excitation & torque → no circulating current, equal load split.

**Q110 (AP Genco-17):** Maximum possible power of 3-phase synchronous motor, Xs = 0.8 pu, bus 1.0 pu, excitation 1.2 pu
(a) 0.5 pu (b) 0.96 pu (c) 1.5 pu (d) 1.8 pu
**Ans: (c)** — Pmax = EfVt/Xs = 1.2×1.0/0.8 = 1.5 pu.
**Concept:** Pmax = EfVt/Xs.
**Twist:** with a line reactance Xl → Pmax = EfVt/(Xs+Xl).

**Q111 (AP Genco-17):** A synchronous capacitor is
(a) unloaded & under-excited synchronous motor (b) loaded & over-excited generator (c) unloaded & over-excited synchronous motor (d) generator loaded with a capacitor bank
**Ans: (c)** — Overexcited, unloaded synchronous motor.
**Concept:** Synchronous capacitor definition.
**Twist:** underexcited version → synchronous reactor.

**Q112 (AP Transco-17):** Fractional-pitch used for eliminating the 7th harmonic from alternator emf
(a) 2/3 (b) 5/6 (c) 7/8 (d) 6/7
**Ans: (d)** — Pitch = 1 − 1/n = 1 − 1/7 = 6/7.
**Concept:** Pitch for eliminating nth harmonic = (1 − 1/n).
**Twist:** 5th harmonic → 4/5; 3rd → 2/3.

**Q113 (AP Transco-17):** Keeping excitation constant, if steam supply of an alternator in parallel is increased
(a) it would over-run the other (b) its rotor falls back in phase (c) its share of load increases (d) its pf decreases
**Ans: (c)** — More steam → more active power delivered → its kW share rises.
**Concept:** kW sharing via prime-mover (steam) input.
**Twist:** increasing excitation instead → changes kVAR share, not kW.

**Q114 (AP Transco-17):** Effect of increasing load on a synchronous motor running with normal excitation
(a) increase both Ia and pf (b) decrease Ia, increase pf (c) increase Ia, decrease pf (d) decrease both Ia and pf
**Ans: (c)** — Load ↑ → δ ↑ → Ia rises and, at normal excitation, pf worsens (falls below upf).
**Concept:** Load angle & armature current vs load.
**Twist:** if motor was overexcited, pf improves initially before degrading.

**Q115 (AP Transco-17):** Ratio of rotor reactance to resistance for a two-phase servo motor
(a) equal to normal IM (b) less than normal IM (c) greater than normal IM (d) may be less or greater
**Ans: (b)** — Servo motors use high rotor resistance → X/R smaller → linear torque-speed.
**Concept:** Servo motor high rotor resistance (X/R < normal IM).
**Twist:** high rotor R gives stable, linear, positive-slope torque-speed for control.

**Q116 (AP Transco-17):** The 5th harmonic component of induced voltage in a 3-phase alternator can be eliminated by winding pitch of
(a) 2/3 (b) 4/5 (c) 5/6 (d) 6/7
**Ans: (b)** — Eliminate 5th → pitch = 1 − 1/5 = 4/5 (coil span 144°).
**Concept:** Chording for 5th harmonic (4/5 pitch).
**Twist:** eliminate 3rd → 2/3; eliminate 7th → 6/7.

**Q117 (TSSPDCL-18):** 200 MW (4% droop) and 400 MW (5% droop) generators, no-load 50 Hz, supplying 600 MW — system frequency
(a) 50 Hz (b) 49 Hz (c) 48.7 Hz (d) 47.7 Hz
**Ans: (d)** — PA = 0.625 PB, PA+PB=600 → PB=370 MW, droop x=4.61% → f = 50×(1−0.0461) = 47.69 Hz.
**Concept:** Parallel droop (governor) frequency-load characteristics.
**Twist:** equal droops & ratings → f = 50×(1 − 600/sum)/... different drop.

**Q118 (TSSPDCL-18):** Shaded-pole motor: (1) runs from unshaded→shaded part; (2) direction reversible; (3) highly noisy — correct statements
(a) 1 only (b) 2 and 3 (c) 3 only (d) 1 and 3
**Ans: (d)** — Runs unshaded→shaded (true); direction NOT reversible (false); noisy (true).
**Concept:** Shaded-pole single-phase motor.
**Twist:** reversing supply leads cannot reverse a shaded-pole motor.

**Q119 (TSSPDCL-18):** Statements: (1) armature & field mmfs rotate at same speed; (2) zpf-lag armature mmf demagnetizes main field in an alternator; (3) zpf-lead is magnetizing in a motor; (4) salient pole Xq = Xd — correct
(a) 1, 2 (b) 2, 3 (c) 3, 4 (d) 1, 2, 3
**Ans: (a)** — (1) true; (2) true (gen, zpf-lag → demag); (3) false (motor zpf-lead → demag); (4) false (Xd > Xq).
**Concept:** Armature reaction in gen vs motor; salient pole Xd > Xq.
**Twist:** motor zpf-lag → magnetizing (opposite to alternator).

**Q120 (TSSPDCL-18):** Statements: (1) damper windings prevent hunting; (2) Xs at higher exciting currents is larger; (3) sync motors preferred for high power at low speeds; (4) star-delta starters used to start sync motors — correct
(a) 1, 3 (b) 1, 4 (c) 2, 3 (d) 2, 3, 4
**Ans: (a)** — (1) true; (2) false (Xs saturates → smaller); (3) true; (4) false (auto-transformer starting).
**Concept:** Damper winding, Xs saturation, sync-motor applications.
**Twist:** Xs(unsaturated) > Xs(saturated) at high excitation.

**Q121 (TS Transco-18):** Y-connected generator, Xs = 5 Ω/ph, delivers 12 kVA upf, Vt = 200 V/ph — induced emf per phase
(a) √5 × 100 V (b) √3 × 100 V (c) √2 × 100 V (d) 200 V
**Ans: (a)** — Ia = 20 A; Ef = √(200² + (20×5)²) = √(40000+10000) = 224 V = √5×100 V/ph.
**Concept:** Ef = √[(Vt cosφ + IaRa)² + (Vt sinφ ± IaXs)²].
**Twist:** 0.8 lagging load → Ef = √[(Vt·0.8)² + (Vt·0.6 + IaXs)²] (larger).

**Q122 (TS Transco-18):** 3-phase synchronous generator at 0.8 pf lagging wrt excitation voltage — nature of armature reaction
(a) Magnetizing (b) Demagnetizing (c) Cross-magnetizing & partly demagnetizing (d) Partly demagnetizing & partly cross-magnetizing
**Ans: (d)** — 0.8 lag → AR is partly demagnetizing, partly cross-magnetizing.
**Concept:** AR at intermediate lagging pf.
**Twist:** zpf lag → purely demagnetizing; upf → purely cross.

**Q123 (TS Transco-18):** When speed exceeds synchronous speed during hunting, damper bars develop
(a) synchronous motor torque (b) induction motor torque (c) DC motor torque (d) induction generator torque
**Ans: (d)** — Nr > Ns → induction-generator (braking) torque.
**Concept:** Hunting — damper induction generator torque.
**Twist:** sub-synchronous → induction motor (accelerating) torque.

**Q124 (TS Transco-18):** Synchronous machine with field on stator, armature on rotor — steady-state air-gap field is
(a) stationary with respect to stator (b) stationary with respect to rotor (c) rotating at synchronous speed wrt stator (d) rotating at synchronous speed in direction of rotor
**Ans: (a)** — Inverted machine behaves like a DC machine → air-gap field stationary wrt stator.
**Concept:** Inverted synchronous machine / reversal of roles.
**Twist:** normal machine → air-gap field rotates at Ns relative to stator.

**Q125 (AP Transco-19):** 3-phase synchronous motor draws 200 A from the line at upf, rated load. Line current at 0.5 leading, same line voltage & load
(a) 100 A (b) 200 A (c) 300 A (d) 400 A
**Ans: (d)** — P constant → I ∝ 1/cosφ: I2 = 200×(1/0.5) = 400 A.
**Concept:** P = √3 VL IL cosφ (constant power, pf change).
**Twist:** 0.5 lagging pf → also 400 A (same cosφ magnitude).

**Q126 (AP Transco-19):** Field 20 A → SC armature current 400 A; OC terminal voltage 2000 V. Internal voltage drop at load current 200 A
(a) 1 V (b) 10 V (c) 100 V (d) 1000 V
**Ans: (d)** — Xs = (2000/√3)/400 = 2.88 Ω/ph; per-phase drop = 200×2.88 = 577 V; line drop = √3×577 = 1000 V.
**Concept:** Zs = Voc(ph)/Isc; drop = Ia·Xs.
**Twist:** if per-phase drop asked → 577 V (not 1000 V).

**Q127 (AP Transco-19):** If a synchronous motor runs at leading pf, its excitation-induced voltage Ef is
(a) equal to Vt (b) higher than Vt (c) less than Vt (d) dependent upon supply Vt
**Ans: (b)** — Leading pf motor = overexcited → Ef > Vt.
**Concept:** Overexcitation ⇒ leading pf ⇒ Ef > Vt.
**Twist:** lagging pf (underexcited) → Ef < Vt.

**Q128 (AP Transco-19):** In a salient-pole synchronous motor, reluctance torque is maximum when load angle (elec. deg) is
(a) 0 (b) 45 (c) 60 (d) 90
**Ans: (b)** — Reluctance power ∝ sin2δ → maximum at δ = 45°.
**Concept:** Reluctance torque ∝ sin2δ (max at 45°).
**Twist:** electromagnetic torque ∝ sinδ → max at δ = 90°.

**Q129 (APEPDCL-19):** Two generators G1, G2 equally charging kVAR, terminal voltage fixed — to shift part of kVAR from G2 to G1
(a) lower If of G1, raise If of G2 (b) lower If of G1 (c) raise If of G2 (d) raise If of G1 and lower If of G2
**Ans: (d)** — Raise G1 excitation, lower G2 (Vt = (Ef1+Ef2)/2 stays fixed).
**Concept:** kVAR sharing via excitation; Vt = (Ef1+Ef2)/2.
**Twist:** to shift kW → change prime-mover input instead.

**Q130 (APEPDCL-19):** Which machine is a double-excited electrical machine?
(a) Induction motor (b) DC series motor (c) DC shunt motor (d) Synchronous motor
**Ans: (d)** — Synchronous machine has two separate excitations: DC field + AC armature.
**Concept:** Double excitation (synchronous machine).
**Twist:** induction machine is singly excited (only stator).

**Q131 (APEPDCL-19):** Synchronous motor at constant load, excitation set for upf current; if excitation is increased, pf will be
(a) zero (b) leading (c) remains unity (d) lagging
**Ans: (b)** — Increase excitation beyond UPF point → overexcited → leading pf.
**Concept:** Excitation ↑ from upf → leading pf (V-curve).
**Twist:** excitation decreased from upf → lagging pf.

**Q132 (APEPDCL-19):** An unexcited single-phase synchronous motor is
(a) an AC series motor (b) a reluctance motor (c) a universal motor (d) a repulsion motor
**Ans: (b)** — Without excitation only reluctance torque remains → reluctance motor.
**Concept:** Reluctance motor = unexcited salient-pole synchronous motor.
**Twist:** excited → runs as a proper synchronous motor.

**Q133 (APEPDCL-19):** 3-φ salient-pole alternator delivering ~15% rated power; if excitation fails it acts as
(a) induction generator (b) synchronous motor (c) synchronous generator (d) reluctance generator
**Ans: (d)** — At low power the machine stays in synchronism via reluctance torque → reluctance generator.
**Concept:** Reluctance generator (loss of excitation at light load).
**Twist:** at heavy load, loss of excitation → falls out of step.

**Q134 (APEPDCL-19):** Round-rotor generator, leakage X 1%, AR reactance 9% at full-load upf; neglecting Ra, no-load emf at full-load upf, Vt = 1 pu
(a) 1.1 pu (b) 1.25 pu (c) 1.21 pu (d) 1.0 pu
**Ans: (d)** — Xs = 0.1 pu; Ef = √(1² + (1×0.1)²) = √1.01 ≈ 1.0 pu.
**Concept:** Ef(upf) = √(Vt² + (IaXs)²) ≈ Vt for small Xs.
**Twist:** Xs = 0.5 pu → Ef = √1.25 ≈ 1.12 pu.

**Q135 (APEPDCL-19):** Load characteristics of an alternator at different pf (curves A,B,C,D in figure) — the leading-pf characteristic is
(a) B and C (b) A and B (c) A and C (d) C and D
**Ans: (d)** — Leading pf → terminal voltage rises with load (curves C, D).
**Concept:** External characteristic vs pf.
**Twist:** lagging pf → voltage drops most (curves A, B).

**Q136 (APEPDCL-19):** What is the short ratio of a synchronous machine?
(a) 1/Xs(adjusted) in ohms (b) 1/Xs(unsaturated) in ohms (c) 1/Xs(unsaturated) pu (d) 1/Xs(adjusted) pu
**Ans: (d)** — Short ratio = 1/Xs(adjusted) in pu.
**Concept:** Short ratio = SCR = 1/Xs(saturated/adjusted, pu).
**Twist:** SCR is the field-current ratio (If for OC rated V)/(If for SC rated I).

**Q137 (APEPDCL-19):** Synchronous generator Xs = 1 pu connected to infinite bus (1 pu) through 0.2 pu line reactance; for max output 1.2 pu, generator emf
(a) 0.8 pu (b) 1.2 pu (c) 1.44 pu (d) 1.0 pu
**Ans: (c)** — Pmax = EfVt/(Xs+Xline) → 1.2 = Ef×1/1.2 → Ef = 1.44 pu.
**Concept:** Pmax = EfVt/(Xs + Xline).
**Twist:** no line reactance → Ef = 1.2 pu.

**Q138 (APEPDCL-19):** Which motor runs at the same speed from no-load to full load?
(a) Synchronous motor (b) Induction motor (c) DC shunt motor (d) Cumulatively compounded DC motor
**Ans: (a)** — Synchronous motor speed is constant (locked to supply frequency).
**Concept:** Constant-speed machine (synchronous).
**Twist:** induction motor speed drops slightly with load (slip).

**Q139 (APEPDCL-19):** Maximum torque delivered by a synchronous motor is proportional to
(a) 1/V² (b) V (c) V² (d) 1/V
**Ans: (c)** — Tmax ∝ Pmax = EfVt/Xs → with Ef ∝ V, Tmax ∝ V².
**Concept:** Tmax ∝ V² (Pmax = EfVt/Xs).
**Twist:** at fixed excitation, Tmax ∝ V only.

**Q140 (APSPDCL-19):** Front-end view of a simple loop alternator (conductors 2,3 under N; 5,6 under S; 1,4 on q-axis) — direction of emf at the instant (options give ×/O for 2,3,5,6)
(a) 2:O 3:O 5:× 6:× (b) 2:× 3:× 5:O 6:O (c) 2:O 3:O 5:× 6:O (d) 2:O 3:× 5:O 6:×
**Ans: (b)** — 2,3 under N → emf into page (×); 5,6 under S → emf out (O); 1,4 on q-axis → zero. Fleming's right-hand rule.
**Concept:** emf direction — Fleming's right-hand rule; d-axis vs q-axis conductors.
**Twist:** reverse rotation → directions of all active emfs flip.

**Q141 (APSPDCL-19):** Synchronizing power coefficient per mechanical degree for an alternator in terms of p (pole pair), P (power), α (load angle)
(a) (180/pπ)(dP/dα) (b) (180π/p)(dP/dα) (c) (pπ/180)(dP/dα) (d) (Pπ/p)(dP/dα) — watts
**Ans: (c)** — Per mechanical degree: Psy(mech) = (pπ/180)·(dP/dα).
**Concept:** Synchronizing power coefficient & electrical↔mechanical degree conversion.
**Twist:** per electrical degree → dP/dα directly.

**Q142 (APSPDCL-19):** 3-phase synchronous motor, Xs = 0.4 pu, emf = 1.2 pu — power output/phase at load angle 30°
(a) 1.0 pu (b) 1.5 pu (c) 0.75 pu (d) 1.2 pu
**Ans: (b)** — P = (EfVt/Xs)sinδ = (1.2×1/0.4)×0.5 = 1.5 pu.
**Concept:** P = (EfVt/Xs)sinδ.
**Twist:** δ = 90° → Pmax = 3 pu; δ = 45° → 2.12 pu.

**Q143 (APSPDCL-19):** Shape of armature mmf in alternators for a 60° phase-spread armature winding (four waveforms)
(a) stepped staircase with peak Fm (b) stepped staircase with 2Fm/3 plateau (c) triangular Fm (d) rectangular
**Ans: (b)** — 60° spread → staircase armature MMF approaching a sine (near-trapezoid, not flat-topped).
**Concept:** Armature MMF waveform vs phase spread.
**Twist:** 120° spread → flatter-topped staircase (more harmonics).

**Q144 (APSPDCL-19):** 400 V, 50 Hz alternator, full-load 0.8 pf lagging; on load throw-off voltage rises 50 V (f kept rated) — voltage regulation
(a) 15% (b) 8% (c) 20% (d) 12.5%
**Ans: (d)** — VR = (Ef − Vt)/Vt ×100 = (450 − 400)/400 ×100 = 12.5%.
**Concept:** %VR = (E − Vt)/Vt ×100.
**Twist:** rise of 100 V → 25% regulation.

**Q145 (APSPDCL-19):** R-phase slot distribution of a 24-slot, 4-pole, 3-ph lap double-layer winding (two conductors/slot) — first coil of R-phase (coil-side numbers)
(a) 25-38-26-40 (b) 1-10-3-12 (c) 1-14-3-16 (d) 5-13-6-14
**Ans: (c)** — Double layer: coil (1) top 1 → bottom 14; coil (2) top 3 → bottom 16.
**Concept:** Double-layer lap winding coil-side numbering (pitch ~14 slots).
**Twist:** single-layer → coils 1→13, 2→14 (different coil sides).

**Q146 (HMWS-20):** Angle between armature mmf and field mmf of a cylindrical-rotor synchronous generator at UPF and zpf-lagging load respectively
(a) 90° and 180° (b) 180° and 90° (c) 90° and 0° (d) 0° and 90°
**Ans: (a)** — UPF: AR ⊥ field flux (90°); zpf lag: AR directly opposes field (180°).
**Concept:** Armature reaction angle — cross (90°) vs demagnetizing (180°).
**Twist:** zpf leading → AR in phase with field (0° difference, aiding).

**Q147 (HMWS-20):** Slip test on salient-pole machine: voltage 30 V, 25 V; current 10 A, 6 A; armature resistance negligible — Xd, Xq
(a) 3 Ω and 4.16 Ω (b) 4.16 Ω and 3 Ω (c) 5 Ω and 2.5 Ω (d) 2.5 Ω and 5 Ω
**Ans: (c)** — Xd = Vmax/Imin = 30/6 = 5 Ω; Xq = Vmin/Imax = 25/10 = 2.5 Ω.
**Concept:** Slip test Xd = Vmax/Imin, Xq = Vmin/Imax.
**Twist:** swapping Vmax↔Vmin pairing → option (d) 2.5 & 5 Ω (wrong).

**Q148 (HMWS-20):** Statements: (A) VR by MMF method is pessimistic; (B) unsaturated Zs > saturated Zs; (C) VR by EMF method is much lower than actual; (D) during SC test air-gap flux density is very small
(a) C, D and A only (b) D, A and B only (c) A, B and C only (d) B, C and D only
**Ans: (b)** — B (Zs unsat > Zs sat) and D (SC flux small) are true; A & C are mis-stated (EMF method is pessimistic/higher, MMF is optimistic/lower). Key marks (b).
**Concept:** Regulation methods: EMF pessimistic, MMF optimistic; Zs saturation; SC test flux.
**Twist:** EMF method → higher than actual (pessimistic); MMF method → lower.

**Q149 (HMWS-20):** When a synchronous machine is loaded from floating conditions, the alternator begins operating at __ pf, the synchronous motor at __ pf
(a) Lagging; Lagging (b) Leading; Leading (c) Lagging; Leading (d) Leading; Lagging
**Ans: (d)** — From floating (δ=0): generator loaded → Q negative → leading pf; motor loaded → Q positive → lagging pf.
**Concept:** Reactive power sign at floating→loaded; Q = (Vt/Xs)(Efcosδ − Vt).
**Twist:** at floating exactly → upf (Q = 0).

**Q150 (HMWS-20):** With constant Ef, Vt, Zs of a synchronous motor, reactive power is __ and __ by the motor at max reactive-power input and max active-power input
(a) Delivered & absorbed (b) Delivered & delivered (c) Absorbed & absorbed (d) Absorbed & delivered
**Ans: (c)** — Solution states (c); note: its text reasoning (lagging → absorbing; leading → delivering) actually maps to option (d) — source inconsistency.
**Concept:** Motor Q vs operating point on V-curve (underexcited absorbs, overexcited delivers).
**Twist:** underexcited → absorbs kVAR; overexcited → delivers kVAR.

**Q151 (HMWS-20):** For the terminal voltage (Vt) of ZPF-leading operation to give the same short-circuit current as ZPF-lagging, Vt relative to Ef is
(a) Two times (b) Three times (c) Equal (d) Half
**Ans: (a)** — ZPF lead: Ef = Vt − Ef → Vt = 2Ef (Vt is twice Ef).
**Concept:** ZPF characteristics (Potier) — Vt = 2Ef for same Isc.
**Twist:** ZPF lagging → Vt = Ef − IaXs (different relation).

**Q152 (HMWS-20):** Which speed-torque curve belongs to an AC servomotor (curves I, II, III, IV)?
(a) III (b) IV (c) I (d) II
**Ans: (a)** — Servomotor: negative-slope, nearly-linear torque-speed (III).
**Concept:** Servomotor torque-speed linearity (high rotor resistance).
**Twist:** standard IM → curve with peaked torque (non-linear).

**Q153 (SSC-JE-20):** Which single-phase motor for a tape recorder?
(a) Reluctance motor (b) Hysteresis motor (c) Synchronous motor (d) Universal motor
**Ans: (b)** — Hysteresis motor: constant speed, quiet, low vibration — ideal for recorders/clocks.
**Concept:** Hysteresis motor applications.
**Twist:** electric clocks & timing devices also use hysteresis motors.

**Q154 (SSC-JE-20):** Direction of rotation of a hysteresis motor is determined by
(a) interchanging supply leads (b) position of shaded pole wrt main pole (c) retentivity of rotor material (d) none
**Ans: (b)** — Rotor always rotates from shaded pole towards unshaded pole.
**Concept:** Hysteresis motor rotation (shaded-pole direction).
**Twist:** interchanging supply leads cannot reverse it.

**Q155 (SSC-JE-20):** Purpose of the stator winding in a compensated repulsion motor
(a) provide mechanical balance (b) improve pf and provide better speed regulation (c) prevent hunting (d) eliminate armature reaction
**Ans: (b)** — Compensating (stator) winding improves pf & speed regulation.
**Concept:** Compensated repulsion motor.
**Twist:** compensation reduces armature reaction effect.

**Q156 (SSC-JE-20):** A hysteresis motor works on the principle of
(a) hysteresis loss (b) magnetization of rotor (c) eddy current loss (d) electromagnetic induction
**Ans: (a)** — Torque from hysteresis lag in the high-retentivity rotor.
**Concept:** Hysteresis motor principle.
**Twist:** rotor is a smooth cylinder of hardened steel (no slots/winding).

**Q157 (SSC-JE-20):** In a synchronous motor the armature current has higher values for
(a) high excitation only (b) low excitation only (c) both high and low excitation (d) none
**Ans: (c)** — V-curve: Ia is high at both over- and under-excitation extremes.
**Concept:** V-curve (Ia minimum at upf).
**Twist:** minimum armature current at unity pf.

**Q158 (SSC-JE-20):** An unexcited single-phase synchronous motor is called as
(a) universal motor (b) repulsion motor (c) AC series motor (d) reluctance motor
**Ans: (d)** — Unexcited synchronous motor = reluctance motor (salient rotor, reluctance torque).
**Concept:** Reluctance motor.
**Twist:** multi-phase version → synchronous reluctance motor.

**Q159 (SSC-JE-20):** A constant-speed motor is
(a) DC shunt motor (b) synchronous motor (c) induction motor (d) DC compound motor
**Ans: (b)** — Synchronous motor runs at constant speed regardless of load.
**Concept:** Constant-speed synchronous machine.
**Twist:** DC shunt is approximately constant speed (small drop); induction has slip.

**Q160 (SSC-JE-20):** In a synchronous motor, if the back-emf is approximately equal to the applied voltage
(a) torque is maximum (b) excitation is 100% (normal excitation) (c) excitation is zero percent (d) motor is fully loaded
**Ans: (b)** — Ef ≈ Vt → normal excitation (UPF point).
**Concept:** Normal excitation ↔ Ef ≈ Vt (upf).
**Twist:** Ef > Vt → overexcited (leading); Ef < Vt → underexcited (lagging).

**Q161 (SSC-JE-20):** A synchronous motor can operate at ____
(a) leading pf only (b) lagging pf only (c) unity pf only (d) lagging, leading and unity pf
**Ans: (d)** — Excitation control lets it run at any pf.
**Concept:** pf control via excitation.
**Twist:** under-excited → lag; over-excited → lead; normal → upf.

**Q162 (APPSC-19):** In a synchronous motor, excitation adjusted to make induced voltage equal to applied voltage — such excitation is called
(a) under excitation (b) normal excitation (c) over excitation (d) abnormal excitation
**Ans: (—)** — Solution: Ef = Vt, no option satisfies (key: *).
**Concept:** Normal excitation is Ef cosδ = Vt at load (Ef = Vt only at no-load/upf).
**Twist:** n/a — question flagged by source as unsatisfiable.

**Q163 (APPSC-19):** Air-gap flux has a 3rd harmonic; coils short-pitched by angle α for fundamental — pitch factor for the 3rd harmonic
(a) cos(3α/4) (b) cos(3α/2) (c) cos(2α/3) (d) cos(4α/3)
**Ans: (b)** — Kp3 = cos(3α/2) (α = chording angle).
**Concept:** Pitch factor for nth harmonic Kpn = cos(nα/2).
**Twist:** 5th harmonic → Kp5 = cos(5α/2).

**Q164 (TSSPDCL-22):** Damper winding: (A) carries no current at synchronous speed; (B) carries current when load changes; (C) is also called squirrel-cage winding; (D) consists of thin copper wires of many turns
(a) A true, B false (b) C true, D false (c) B true, C false (d) D true, A false
**Ans: (b)** — At Ns no current (A true); carries current during hunting/load change (B true); is a squirrel-cage (C true); made of thick bars, not thin many-turn wires (D false).
**Concept:** Damper (squirrel-cage) winding construction & function.
**Twist:** at synchronous speed damper current = 0 (no slip → no emf).

**Q165 (TSPSC-2023):** In a salient-pole synchronous generator, relation between Xd and Xq
(a) Xd = −Xq (b) Xd < Xq (c) Xd = Xq (d) Xd > Xq
**Ans: (d)** — Salient pole: Xd >> Xq (reluctance low on d-axis).
**Concept:** Xd > Xq for salient pole; Xd = Xq for cylindrical rotor.
**Twist:** cylindrical rotor → Xd = Xq.

**Q166 (TSPSC-2023):** Grid-connected synchronous generator at unity pf — increasing field excitation
(a) increases grid frequency (b) increases only active power (c) increases only reactive power (d) increases both active & reactive power
**Ans: (c)** — Excitation controls reactive power only; active power is set by steam input.
**Concept:** Inverted-V for generator; P from governor, Q from excitation.
**Twist:** increase steam input → only active power changes.

**Q167 (TSPSC-2023):** Reason behind the inability of an ideal synchronous motor to develop starting torque
(a) stator concentrated windings (b) rotor extremely heavy (c) relative velocity between stator and rotor mmf is large at starting (d) rotor winding very high reactance
**Ans: (c)** — At standstill the two mmfs have relative velocity Ns, so no average torque.
**Concept:** Starting torque failure — no relative-stationary fields at start.
**Twist:** damper winding (induction mode) provides the starting torque.

**Q168 (TSPSC-2023):** Short-pitched windings: A. reduce fundamental emf vs full-pitch; B. increase harmonic content; C. smaller overhang length — true statements
(a) C only (b) A and C only (c) A and B only (d) A only
**Ans: (b)** — A true (fundamental reduced); B false (short pitch neutralizes space harmonics); C true (shorter overhang).
**Concept:** Short pitching — fundamental ↓, harmonics ↓, overhang ↓.
**Twist:** fully-pitched → maximum fundamental but full harmonics.

**Q169 (TSPSC-2023):** A machine whose stator and rotor self-inductances are independent of rotor position will NOT develop any
(a) synchronizing torque (b) starting torque (c) reluctance torque (d) hysteresis torque
**Ans: (c)** — Uniform air-gap (L independent of position) → no reluctance torque.
**Concept:** Reluctance torque requires saliency (L vs rotor position).
**Twist:** cylindrical rotor (Xd = Xq) → reluctance torque = 0.

**Q170 (TSPSC-2023):** Machine most suitable as generator in a coal-fired thermal power plant
(a) wound-rotor induction generator (b) salient-pole synchronous generator (c) cylindrical-rotor synchronous generator (d) squirrel-cage induction generator
**Ans: (c)** — High-speed steam turbines → cylindrical-rotor (turbo) alternator.
**Concept:** Thermal → cylindrical rotor; hydro → salient pole.
**Twist:** low-head hydro station → salient-pole synchronous generator.

**Q171 (TSPSC-2023):** Field 20 A → SC armature 400 A; OC terminal voltage 2000 V. Internal voltage drop at load current 200 A
(a) 1000 V (b) 1 V (c) 10 V (d) 100 V
**Ans: (a)** — Zs = 2000/400 = 5 Ω; drop = 200×5 = 1000 V (line values used directly).
**Concept:** Zs = Voc/Isc; drop = Ia·Zs.
**Twist:** per-phase calculation → 2000/√3 then ×200/400 = 577 V/ph.

**Q172 (TSPSC-2023):** Armature reaction: A. generating mode aids field flux for leading current; B. opposes field flux for motor drawing leading pf; C. motoring mode always opposes — true statements
(a) A and B only (b) A only (c) B and C only (d) B only
**Ans: (a)** — Gen zpf-lead → magnetizing (aids) (A true); motor zpf-lead → demagnetizing (opposes) (B true); C false (motor zpf-lag magnetizes, aids).
**Concept:** Armature reaction gen vs motor (lead/lag table).
**Twist:** generator zpf-lag → demagnetizing.

**Q173 (TSSPDCL-AE-2023):** 3-φ cylindrical-rotor machine, Ia lags Ef by 90° — nature of armature reaction
(a) demagnetizing in motor, magnetizing in alternator (b) cross in motor, demag in alternator (c) magnetizing in motor, demagnetizing in alternator (d) demag in motor, cross in alternator
**Ans: (c)** — Alternator with lagging Ia → demagnetizing; motor with lagging Ia → magnetizing.
**Concept:** zpf-lag AR: alternator demag, motor magnetizing.
**Twist:** leading current → alternator magnetizing, motor demagnetizing.

**Q174 (TSSPDCL-AE-2023):** Assertion (A): SC characteristic of an alternator is a straight line. Reason (R): during SC test it operates under saturated conditions.
(a) A false, R true (b) A true, R false (c) both true (d) both false
**Ans: (b)** — A true (Ia ∝ If straight line); R false (SC test runs UNSATURATED).
**Concept:** SC characteristic linearity; unsaturated operation on SC test.
**Twist:** OC test runs on saturation knee (non-linear).

**Q175 (TSPSC-AEE-23):** Synchronous motor: I. constant synchronous speed at all loads; II. max torque proportional to supply voltage; III. operates only at leading pf — correct
(a) II and III only (b) I and III only (c) I and II only (d) I, II and III
**Ans: (c)** — I true; II true (per this source); III false (any pf possible).
**Concept:** Synchronous-motor characteristics.
**Twist:** source-consistency note — Q139 states Tmax ∝ V²; examiners may quote either V (fixed excitation) or V² (Ef ∝ V).

**Q176 (TSPSC-AEE-23):** I. peripheral distance between adjacent poles = pole-pitch; II. coil with two coil-sides 180 electrical degrees apart = full-pitch coil
(a) Only I (b) Neither I nor II (c) Both I and II (d) Only II
**Ans: (c)** — Both definitions are correct.
**Concept:** Pole pitch & full-pitch coil definitions.
**Twist:** short-pitch coil → coil span < 180° (elec).

**Q177 (TSPSC-AEE-23):** Correct sequence for the saturated synchronous-reactance method of voltage regulation
(a) I,II,V,IV,VI,III (b) I,II,IV,V,VI,III (c) I,II,III,IV,V,VI (d) I,V,IV,II,III,VI
**Ans: (c)** — Air-gap E → locate on OCC/air-gap line → saturation factor → Xsag → Xss → phasor diagram & VR.
**Concept:** Saturated synchronous-reactance (ASA-like) method procedure.
**Twist:** unsaturated (EMF) method skips the saturation factor step.

**Q178 (TSPSC-AEE-23):** Bad effects of hunting: I. severe mechanical stress & fatigue in shaft; II. surges in current & power flow; III. increased losses & temperature
(a) I, II and III (b) Only I (c) I and III only (d) II and III only
**Ans: (a)** — All three are bad effects of hunting.
**Concept:** Hunting — causes & effects.
**Twist:** damper winding & proper damping reduce hunting.

**Q179 (TSPSC-AEE-23):** Distribution factor for fractional-slot windings is obtained as
(a) Kd = sinσ/σ (b) Kd = sinσ/(σ/2) (c) Kd = 1 + sin(σ/2) (d) Kd = sin(σ/2)/(σ/2)
**Ans: (d)** — For fractional-slot winding the effective distribution factor Kd = sin(σ/2)/(σ/2).
**Concept:** Distribution factor for fractional-slot windings.
**Twist:** integral-slot 60° spread → Kd = sin(mγ/2)/(m sin(γ/2)).

**Q180 (TSGenco-24):** Incorrect statements: (i) round-rotor SM reactive power is max at load angle 90°; (ii) damper winding provides starting torque; (iii) in slip test emf in field winding is zero for Xq; (iv) synchronous condenser is overexcited motor driving a mechanical load
(a) (i),(ii),(iii) (b) (iii),(iv) (c) (ii),(iii),(iv) (d) (i),(iii),(iv)
**Ans: (d)** — (i) wrong (Q max at 0°, P max at 90°); (ii) correct; (iii) wrong (emf max along q-axis); (iv) wrong (condenser runs at no-load).
**Concept:** Reactive/active power vs δ; damper; slip test; synchronous condenser.
**Twist:** overexcited motor at no load = condenser; loaded = normal motor.

**Q181 (TSGenco-24):** Phasor diagram (IaXs at 90°, Ia, Ef, Vt) corresponds to
(a) under-excited alternator (b) under-excited synchronous motor (c) over-excited alternator (d) over-excited synchronous motor
**Ans: (a)** — Ef leads Vt (generator) and Ia leads Vt (leading pf → under-excited generator).
**Concept:** Phasor-diagram interpretation (Ef & Ia relative to Vt).
**Twist:** Ef lagging Vt → motor; Ia lagging (with over-excitation) → over-excited alternator.

> Total: 697 questions annotated.

---

# 📋 FORMULA SUMMARY — Exam-Day Sheet (Machines)

## 1. Transformers
- EMF: **E = 4.44 f N Φm** · Ratio K = N2/N1 = V2/V1 = I1/I2
- Referred: R01 = R1 + K²R2 (to primary) · R02 = R2 + R1/K² (to secondary)
- Regulation: %R = I(R01cosφ ± X01sinφ)/V1 ×100 (leading → −)
- **η max at x = √(Pi/Pcu)** · η = xScosφ/(xScosφ + Pi + x²Pcu) · all-day η = energy-based
- OC test → Pi · SC test → Pcu · Auto-transformer saving = (1 − 1/a)×100

## 2. DC Machines
- **EMF: E = PΦZN/60A** · **Torque: T = PΦZIa/2πA**
- Back EMF: Eb = V − IaRa · **Speed: N ∝ (V − IaRa)/Φ**
- Shunt: constant speed · Series: high starting torque, runaway on no-load

## 3. Induction Machines
- **Ns = 120f/P** · **s = (Ns − N)/Ns** · rotor frequency = s·f
- **T ∝ sR2/(R2² + s²X2²)** · max T at **s = R2/X2** · starting T ∝ rotor R
- V/f control → constant flux · rotor R ↑ → starting torque ↑, slip@maxT ↑

## 4. Synchronous Machines
- **f = PN/120** · E = 4.44 f N Φ (per phase)
- **VR = (E − V)/V ×100** · **P = (EV/Xs)·sinδ**
- V-curves: under-excited → lagging PF · over-excited → leading PF
- Hunting → damper winding · synchronizing: same V, f, phase, phase-seq

---

# 🧩 DC MACHINES — CRISP THEORY (Series / Shunt / Compound / Self- & Separately-Excited)

## The one principle
**There is only ONE set of formulas — the machine type changes only two things: Φ and Ia.**
Everything else is answering "what is Φ and what is Ia for this type?"
- **E = V − IaRa** (motor) · **E = V + IaRa** (generator)
- **T ∝ Φ·Ia**
- **N ∝ (V − IaRa)/Φ**

## 1. GENERATORS — by excitation

**Separately excited** (external DC field supply): independent of load, E = V + IaRa, flattest characteristic. No self-excitation.

**Self-excited** (field fed from its own armature) — **needs residual magnetism to build up**; if it won't build, reverse field connections or rotation:

| Type | Circuit | E / behavior |
|---|---|---|
| **Shunt** | field ∥ armature | E = V + IaRa, Ia = IL + Ish · mild droop, good constant voltage |
| **Series** | field in series with armature | E = V + Ia(Ra+Rs), Ia = IL · E **RISES** with load until saturation |
| **Cumulative compound** | Φ = Φsh + Φse | **Over** → E rises (long-distance feeders) · **Flat/level** → E constant · **Under** → E droops (less than shunt) |
| **Differential compound** | Φ = Φsh − Φse | **E collapses with load** → welding, not power |

## 2. MOTORS
| Type | Speed | Starting torque | Use |
|---|---|---|---|
| **Shunt** | ≈ constant | low | lathe, constant-speed loads |
| **Series** | **N ∝ 1/Ia → runaway at no-load** | **very high (T ∝ Ia²)** | traction, cranes, hoists |
| **Cumulative compound** | stable | high | elevators, rolling mills |
| **Differential compound** | **N rises with load (unstable)** | — | rarely used |
| **Separately excited** | precise (armature/field control) | — | speed-control drives |

## 3. Torque-speed characteristics (the key exam curve)
- **Shunt:** gentle droop — "flat"
- **Series:** high T at low N; N rises steeply at light load — "runaway"
- **Cumulative compound:** between the two
- **Differential compound:** N rises with T (negative slope) — **unstable**

## 4. The type map
| Type | Φ | Ia | Torque | Speed | Use |
|---|---|---|---|---|---|
| **Separately excited** | constant (ext. supply) | Ia = IL | T ∝ Ia | flat, precise control | speed-control drives |
| **Shunt** | ≈ constant | motor: Ia = IL − Ish | T ∝ Ia (moderate) | **≈ constant** (slight droop) | constant-speed (lathe) |
| **Series** | **∝ Ia** | Ia = IL = all current | **T ∝ Ia²** (high start T) | **N ∝ 1/Ia → runaway** | traction, cranes, hoists |
| **Cumulative compound** | Φsh + Φse | | high start T + stable speed | gentle droop | elevators, rolling mills |
| **Differential compound** | Φsh − Φse | | T drops as Ia ↑ | **N rises (unstable)** | welding, not power |
| **Over-compounded gen** | strong Φse | | | **E rises with load** | long-distance feeders |
| **Level/flat compounded gen** | matched Φse | | | E constant | constant-voltage supply |
| **Under-compounded gen** | weak Φse | | | E droops (less than shunt) | — |

## 5. The 3-step mapping (which formula for which type)
1. **Name the type** — "separately excited"/"external field" → SEP · "shunt" → SHUNT · "series" → SERIES · "cumulative/over/flat/under/differential compound" → COMPOUND (prefix = sign of series field) · "self-excited" = shunt or series or compound.
2. **Write Ia and Φ** — Series: **Ia = IL**, Φ ∝ Ia · Shunt/separate: **Φ = const**, Ia = IL − Ish (motor) or IL + Ish (gen) · Compound: **Φ = Φsh ± Φse** (+ cumulative, − differential).
3. **Plug into E, T, N** — the behavior falls out on its own.

## 6. Applications (frequent MCQ)
- Traction / crane / hoist → **Series motor** · Constant speed → **Shunt** · Elevator / rolling mill → **Cumulative compound**
- Constant-voltage supply → **Shunt or level-compounded generator** · Long-distance line feeding → **Over-compounded generator**
- Precise speed control → **Separately excited** · Welding → **Differential compound**
- **Never run a series motor unloaded** (runaway)

## 7. Speed-control mapping
- **Armature resistance control** → speed ↓ (shunt, below base)
- **Field (flux) control** → speed ↑ (above base)
- **Voltage control** → separately excited
- **Series motor** → series resistance / diverters

## 8. Memory hooks
- **Series** = same S: **S**tarts hard, **S**peed soars unloaded, **S**ame current through everything.
- **Shunt** = steady speed, weak start.
- Compound prefixes = series-field strength: **over** → rises · **under** → droops · **level** → flat · **differential** → series fights shunt (unstable).
- **Separately excited** = separate field supply → flattest + best speed control.
- **Self-excitation** build-up needs **residual magnetism**; reverse field connections or rotation if it won't build.

## 9. Self-check
1. Which motor for a crane hoist (huge starting torque)? And why does its speed soar when unloaded?
2. Shunt generator — does E rise or fall as load increases? Over-compounded?
3. T ∝ Ia² and N ∝ 1/Ia → which type did I just describe?

## DC MACHINES — Quick Reference (by excitation)

### GENERATORS
**Separately excited** (external DC field supply): E = V + IaRa, independent of load, flattest. No self-excitation.

**Self-excited** (field from own armature):
- **Shunt** (field ∥ armature): E = V + IaRa, Ia = IL + Ish · mild droop, good constant voltage
- **Series** (field in series): E = V + Ia(Ra+Rs), Ia = IL · E RISES with load until saturation
- **Compound** (both fields):
  - **Cumulative** (series aids shunt):
    - **Over-compounded** (strong series mmf): E RISES with load → long-distance feeding
    - **Flat/level** (just enough): constant voltage
    - **Under-compounded** (weak series mmf): E droops, but less than shunt
  - **Differential** (series opposes shunt): E COLLAPSES with load → welding, not power

**Build-up:** self-excitation needs **residual magnetism** + correct field polarity; reverse field connections or rotation if it won't build.

### MOTORS
- **Shunt:** N ∝ (V−IaRa)/Φ, Φ ≈ const → near-constant speed; low starting torque; constant-speed loads.
- **Series:** Φ ∝ Ia → **T ∝ Ia²** (pre-saturation); high starting torque; **N ∝ 1/Ia → runaway at no-load**; traction, cranes.
- **Compound:**
  - **Cumulative:** high starting torque (series) + stable speed (shunt) → hoists, elevators
  - **Differential:** speed rises with load (unstable) → rarely used
- **Separately excited:** precise speed control (armature control, field control).

---

# 🧩 INDUCTION MACHINES — CRISP THEORY (grounded in the PYQs)

## The one principle
**One rotating field, one torque formula.** Everything else is: which rotor, which phase, which starting method.
- **Ns = 120f/P** · **s = (Ns − N)/Ns** · rotor frequency = **s·f** · N = Ns(1−s)
- **T ∝ sR2/(R2² + s²X2²)** · **max T at s = R2/X2** · Tmax independent of rotor resistance

## 1. Construction — the two rotors (squirrel cage vs wound)
| Term | What it means | Consequence |
|---|---|---|
| **Squirrel cage** | rotor bars + end rings, no brushes | simple, robust, cheap, **low starting torque**, low maintenance |
| **Wound rotor / slip-ring** | rotor has 3-φ winding + slip rings + brushes | **external rotor resistance** → high starting torque + speed control |
| **Deep-bar / double-cage rotor** | cage shaped for skin effect | **high starting torque** in a squirrel cage (current pushed to outer bar at start → high R) |
| **Slip rings / brush gear** | contacts to rotor circuit | only in wound-rotor motors |

## 2. Rotating Magnetic Field (RMF) & mmf
- 3 balanced currents (120° apart) in 3-φ stator → a **resultant RMF** that rotates at **Ns = 120f/P**.
- Direction of rotation = **phase sequence** (swap any two phases → reverse).
- mmf = magnetomotive force (F = N·I); the resultant mmf wave is what rotates.
- Smaller air gap → lower magnetizing current (Xm ∝ 1/gap) but higher leakage/harmonics.

## 3. SINGLE-PHASE IM — Double Field Theory (the "not self-starting" reason)
A single-phase pulsating mmf = **two equal, opposite RMFs** (forward + backward, each ½ amplitude):
- At standstill both torques cancel → **not self-starting**.
- Once spun either way, forward field dominates → runs. Direction = whichever way you first spin it.
- **How to make it start — the auxiliary/main winding story** (Q116–122):

| 1-φ motor type | How it starts | Phase split | Starting torque | PF | Use |
|---|---|---|---|---|---|
| **Split-phase** | resistance split via auxiliary (start) winding | ~30° | low, cheap | low | fans, pumps |
| **Capacitor-start** | capacitor in series with auxiliary | ~90° | **high** | low (capacitor cut out at ~75% speed) | compressors, hard-start |
| **Capacitor-run** | capacitor **in circuit always** | ~90° | good | **best, near-unity** | Q116–117,121 |
| **Capacitor-start-capacitor-run** | two capacitors | | high + best PF | best | |
| **Shaded-pole** | shading coil on stator pole | tiny | **worst**, PF ~0.4 | worst | small fans, relays (cheapest) |

- **Reversal of 1-φ IM:** swap the **main** winding terminals OR the **auxiliary** winding — NOT the supply terminals (Q122).
- "Main winding" = run winding (always on) · "auxiliary winding" = start winding (cut out after starting).

## 4. Crawling, Cogging, Skewing (Q2–6)
| Term | What happens | Why | Fix |
|---|---|---|---|
| **Crawling** | motor runs at **~1/7 Ns** (or other sub-speed) | **7th space harmonic** torque | skewing, better slot design |
| **Cogging** | rotor teeth magnetically **lock** to stator teeth; won't start/rotate | tooth alignment | **skewing** the rotor slots |
| **Skewing** | rotor slots slanted | — | kills cogging + crawling + noise + harmonic torques |

## 5. Starting methods (3-φ) — the "starting and running methods" terms
| Method | What it does | Torque | Line current |
|---|---|---|---|
| **DOL** | full voltage | T_DOL | I_DOL (5–7× I_fl) |
| **Star-delta** | start in star, run in delta | **⅓ T_DOL** | **⅓ I_DOL** |
| **Autotransformer** (tap x) | reduced voltage x·V | **x² T_DOL** | **x² I_DOL** |
| **Rotor resistance** (wound rotor) | external R in rotor | **T rises toward Tmax** (Tmax unchanged) | current falls |
| VFD | low-frequency start | smooth, high | low |

**Key fact:** reduced-voltage starting cuts torque and line current by **x²** (or ⅓ for star-delta).

## 6. Speed control (running methods)
- **V/f control** → constant flux → **constant torque** below base speed (the big one)
- **Pole changing** (consequent poles / cascade) → Ns steps change
- **Rotor resistance** (wound rotor) → slip ↑, speed ↓ (lossy)
- **Frequency control** (VFD) → smooth variable speed

## 7. Torque-slip curve facts
- At s = 1 (standstill): starting torque; current high
- Max torque at **s = R2/X2** — adding rotor R shifts Tmax to higher slip but **doesn't change Tmax**
- Stable running region: s < smax (motor slows if loaded)
- Rotor freq = s·f; at standstill = f, at sync = 0

## 8. Don't confuse: **salient-pole vs cylindrical** belong to SYNCHRONOUS machines
- **Salient-pole** rotor → low-speed hydro generators (many poles, vertical)
- **Cylindrical** rotor → high-speed turbo generators (2/4 poles)
- When these words appear in an IM-flavoured question, they're comparing to synchronous — not an IM term.

## 9. Term → formula map (the "map the question" cheat)
| Examiner says | Reach for |
|---|---|
| "squirrel cage" | low start T, robust, no brushes |
| "wound rotor / slip ring" | external R → high start T, speed control |
| "RMF / mmf / rotating field" | **Ns = 120f/P**, direction = phase sequence |
| "single-phase not starting" | double field theory (fwd + bwd cancel) |
| "split-phase / auxiliary winding / main winding" | ~30° split, weak start |
| "capacitor-start / run" | ~90° split · run = best PF |
| "shaded pole" | worst PF ~0.4, cheapest, lowest T |
| "crawling" | 7th harmonic, ~N/7 |
| "cogging / locking" | teeth lock → **skewing** fixes |
| "deep bar / double cage" | skin effect → high start T (cage) |
| "star-delta / autotransformer" | start current & T ∝ x² (or ⅓) |
| "V/f" | constant flux, constant torque below base |
| "slip, rotor frequency" | s·f |
| "max torque" | s = R2/X2 |

## 10. Self-check
1. Why is a single-phase IM not self-starting — and what makes a capacitor-start motor start hard?
2. A motor crawls at ~1/7 Ns → which harmonic? What's the fix?
3. Star-delta starting reduces starting torque and line current to what fraction of DOL?
4. Which 1-φ motor has the best power factor — and why not capacitor-start?

---

# 🧩 SYNCHRONOUS MACHINES — CRISP THEORY (connect the dots)

## The one principle (the whole subject in 5 lines)
- **Stator = AC armature** (3-φ, where the EMF is made). **Rotor = DC field** (excitation).
- Stator AC makes an RMF at **Ns = 120f/P**; the rotor DC field **locks onto it** → rotor always runs at **exactly Ns (slip = 0)**.
- Power flows across the air gap through the **load angle δ** (angle between E and V).
- **Generator:** prime mover drives rotor → E leads V (δ > 0). **Motor:** load drags rotor → E lags V (δ < 0).
- Two rotors: **salient pole** (slow, hydro, Xd ≠ Xq) vs **cylindrical** (fast, turbo, Xd = Xq).

## 1. Construction & winding terms
| Term | What it is | Where / why | Impact |
|---|---|---|---|
| **Armature (stator)** | winding where EMF is generated | alternator/generator stator | E = 4.44 f N Φ |
| **Rotor / field** | DC-excited winding making main flux | supplies excitation | sets E |
| **Salient pole** | projecting poles, many poles, low speed | **hydro** (slow) | **Xd ≠ Xq** → reluctance power |
| **Cylindrical (non-salient)** | smooth rotor, 2–4 poles, high speed | **turbo** alternators | Xd ≈ Xq = Xs |
| **Single-phase / simple-pole alternator** | single-phase output (rare) | small/test machines | not the power-grid norm |
| **Pole pitch** | distance between adjacent poles = **180° electrical** | defines coil span | full-pitch coil spans one pole pitch |
| **Coil pitch / chorded coil** | actual coil span vs pole pitch | short-pitch (chord) coils | **kills specific nth harmonics** (kp = cos α/2) |
| **Distribution factor kd** | winding spread across slots | distributed winding | reduces harmonics + slightly the fundamental |
| **Progressive / regressive winding** | armature coils advance forward / backward | armature connection order | direction of EMF summing |
| **Air-gap mmf distribution** | how the mmf wave sits in the air gap | defines field shape | non-sinusoid → harmonics |
| **Quadrature (q) / direct (d) axis** | 90° across / along the field axis | salient-pole analysis | **Xd > Xq** |

## 2. Armature reaction — the demagnetization / magnetization story
**Definition:** stator (armature) current makes its own mmf that reacts with the rotor field.
| Mode | Power factor | Effect on field |
|---|---|---|
| Generator | **lagging (zpf)** | **DEMAGNETIZING** → E↓, terminal V drops |
| Generator | unity | cross-magnetizing (distorts) |
| Generator | **leading** | **MAGNETIZING** → V rises |
| Motor | leading / over-excited | magnetizing |
| Motor | lagging / under-excited | demagnetizing |

**The dot:** "demagnetization in the generator" = lagging-PF load. "Magnetization in the motor" = over-excited/leading operation. Same physics, flipped by mode + PF.

## 3. Reactances — saturated, unsaturated, Xd, Xq, SCR
| Term | What it is | Where / why | Impact |
|---|---|---|---|
| **Xs = Xar + Xl** | synchronous reactance = armature-reaction + leakage | cylindrical-rotor analysis | Pmax = EV/Xs |
| **Xd (direct-axis)** | reactance along the pole axis | salient-pole analysis | **Xd > Xq** |
| **Xq (quadrature-axis)** | reactance across the pole axis | salient-pole analysis | smaller than Xd |
| **Unsaturated impedance** | from air-gap line (no saturation) | OC/SC tests | higher value |
| **Saturated impedance** | from actual saturation curve | at rated voltage | lower value |
| **SCR (short-circuit ratio)** | If(rated V on OC)/If(rated I on SC) = 1/Xd(unsat) | rating & regulation | **high SCR → low Xd → better VR + stability, but bigger/costlier** |
| **Slip test** | drive rotor slightly below Ns, note max/min current | measures **Xd = Vmax/Imin, Xq = Vmin/Imax** | only valid when Xd ≠ Xq (salient); cylindrical gives equal |

## 4. Power, load angle, stability
- **Power-angle (salient pole):** **P = (EV/Xd)sinδ + (V²/2)(1/Xq − 1/Xd)·sin2δ**
  - Term 1 = excitation power · **Term 2 = reluctance power** — exists even with **zero excitation**.
- **Reluctance machine:** synchronous motor with **no DC field** — torque purely from the Xd−Xq saliency (term 2). Runs synchronously without excitation.
- **Load angle δ:** angle between E (rotor) and V (terminal). Generator δ>0, motor δ<0.
- **Synchronizing power coefficient:** **Psync = dP/dδ = (EV/Xs)cosδ** — restoring power per degree of δ. High → stiff + stable. At δ=90° → 0 → **steady-state stability limit** (Pmax = EV/Xs).
- **Hunting:** δ oscillates after a disturbance → **damper windings** damp it.

## 5. Modes, parallel operation, bus bar
- **Generator vs motoring mode:** power out (turbine drives) vs power in (load drags) → **δ sign flips**.
- **Bus bar / infinite bus:** alternators connect in parallel to the grid. **Synchronizing conditions:** same V, f, phase sequence, phase angle.
- After sync: **active power (kW) set by prime mover / governor** (turbine power) · **reactive power (kVAR) set by excitation**.
- **Prime mover power component:** the governor torque IS the P = (EV/Xs)sinδ component — δ is literally set by how much turbine power you feed in.
- **V-curves:** armature current vs field current at constant load. **Under-excited → lagging PF · over-excited → leading PF.** Over-excited motor = **synchronous condenser** (PF correction on the bus).

## 6. Voltage regulation & external characteristics
- **VR = (E − V)/V ×100** — found by EMF (sync-impedance), MMF, or ZPF/Potier method.
- **External characteristics:** terminal V vs load current → **lagging PF drops most ("drooping characteristics"), unity drops, leading rises**.
- **Potier triangle (ZPF test):** splits **armature reaction (DE)** from **leakage reactance drop (CD)**.

## 7. Term → dot map (the master map — question word → what it is)
| Examiner says | What it is | Impact / formula |
|---|---|---|
| "demagnetization (generator)" | armature reaction at lagging PF | E↓, V drops |
| "magnetization (motor)" | armature reaction at leading/over-excited | V rises |
| "saturated / unsaturated impedance" | OC curve (sat) vs air-gap line (unsat) | unsat higher |
| "Xd, Xq" | d/q-axis reactances (salient) | **Xd > Xq**, slip test measures them |
| "slip test" | measure Xd, Xq of salient machine | Xd = Vmax/Imin, Xq = Vmin/Imax |
| "salient pole / cylindrical" | hydro (slow, Xd≠Xq) / turbo (fast) | reluctance power term appears only for salient |
| "stator ac, rotor dc" | armature AC + field DC | that's the whole machine |
| "armature reaction" | stator mmf acting on main flux | depends on PF & mode |
| "quadrature / direct axis" | q / d axis of field | Xq vs Xd |
| "pole pitch 180°" | spacing between poles | coil span reference |
| "coil pitch / chord" | coil span vs pole pitch | kills nth harmonics (kp = cos α/2) |
| "nth harmonics" | space harmonics in EMF | short-pitch + distribution reduce |
| "air-gap mmf distribution" | shape of mmf wave | non-sinusoid → harmonics |
| "load angle δ" | angle E vs V | sets P = (EV/Xs)sinδ |
| "synchronizing power coefficient" | dP/dδ = (EV/Xs)cosδ | stability margin |
| "short circuit ratio (SCR)" | = 1/Xd(unsat) | high → better VR, costlier |
| "reluctance power / machine" | (V²/2)(1/Xq−1/Xd)sin2δ | torque without excitation |
| "bus bar / infinite bus" | grid they parallel to | sync: V,f,phase must match |
| "prime mover power component" | governor/turbine torque | sets kW + δ |
| "damper windings" | bars in pole faces | kill **hunting**, help sync |
| "V-curves" | Ia vs If | under-ex lagging, over-ex leading |
| "drooping characteristics" | lagging-PF external curve | V falls with load |
| "voltage regulation" | (E−V)/V ×100 | EMF / MMF / ZPF methods |
| "generator mode / motoring mode" | δ sign, power direction | gen δ>0, motor δ<0 |

## 8. Self-check
1. Why does a generator's voltage drop most at lagging PF load? (hint: armature reaction)
2. Slip test on a cylindrical machine gives Xd = Xq — why can't you get reluctance torque there?
3. Which power term keeps a reluctance machine running with zero excitation?
4. To raise a generator's terminal voltage on the bus bar — do you raise excitation or prime-mover power? Why?

---

# 🧩 AUTO-TRANSFORMER — CRISP THEORY (all variations, from the PYQs)

## The one idea
One winding with a tap — **windings electrically connected, no isolation**. One current passes *directly* (conduction) + one by induction → **far more kVA for the same copper**.

## The master formula + the #1 trap
**`VA_AT = S_two-winding / (1 − K)`**
**K = LV/HV of the AUTO connection as used** (NOT the original two-winding ratio). Find the common winding: **K = V_common / V_total.**
- Step-up 2000→2200: K = 2000/2200 = 10/11 (Q99)
- Step-down 12.1→11 kV: K = 11/12.1 = 10/11 (Q107)
- Two-winding 2:1 as step-up auto: **K = N1/(N1+N2) = 2/3** (Q110)

## The formula map — which formula for which question
| Asked | Formula | Worked example |
|---|---|---|
| **kVA rating** | **VA_AT = S/(1−K)** | 25/(1−10/11) = **275 kVA** (Q99) · 1100/(1/11) = **12100 kVA** (Q107) |
| **Rating multiple** (r:1 ratio) | **= r+1** (= 1/(1−K)) | 2:1 → 3× · 1:1 → 2× · 3:1 → 4× (Q110) |
| **Output current** | **I2 = I1·N1/N2** (amp-turn balance) | 60×210/140 = **90 A** (Q102) |
| **Common-winding current** | **I2 − I1** (step-down) / I1 − I2 (step-up) | 90 − 60 = **30 A** (Q102) |
| **Power by conduction** | **P_cond = K·P_total** | K=0.7, 3 kW → **2.1 kW** (Q108) |
| **Power by induction** | **P_ind = (1−K)·P** = (V1−V2)/V1·P | **0.9 kW** (Q105,108) |
| **Copper saving** | **(1 − K)×100%** = (1 − 1/a)×100% | a=1.1 → **9.1%** |
| **Magnetizing current ratio** | **α/(α−1)** | α=2 → 2× (Q111) |
| **Efficiency** | η = output/(output + loss) | same loss, output 198 kW → **0.995** (Q109) |
| **pu loss ratio (auto:2wdg)** | **S_2wdg / VA_AT** | 100/1100 = **1/11** (Q122) |
| **Disadvantage** | **no galvanic isolation** | high short-circuit current (Q100) |

## Common-winding current, made clear (Q102)
- **Amp-turn balance:** N1·I1 = N2·I2 → I2 = I1·(N1/N2)
- **Common winding carries the DIFFERENCE** (I2 − I1) → needs less copper → the saving.
- Step-up twist: common = I1 − I2 (swap direction).

## Efficiency & losses (Q109, Q122)
Same winding → same current & same **watts loss**, but kVA jumps:
- Q109: 22 kVA, 2200/220, loss 1 kW → auto 2200→1980: output = 1980×(22k/220) = **198 kW** → **η = 99.5%**
- Q122: loss watts same, VA 100→1100 → **pu loss = 1/11**

## Advantages / disadvantages / applications
- **Advantages:** more kVA per kg copper, lower losses, better regulation (low leakage), smaller
- **Disadvantages:** **no isolation** · **very high short-circuit current** (low leakage Z) · common-winding open = full-HV hazard
- **Most economical when K near 1** (small ratio, e.g., 400→440 V); large ratio → two-winding wins
- **Applications:** IM autotransformer **starter** (tap x → T_st ∝ x², line I ∝ x²), **variac**, voltage regulators, grid interconnection · sodium-vapour lamp needs **high leakage reactance** (ballast) (Q101)

## Memory hooks
- **"K = LV/HV of the auto connection"** — say it before every auto question
- **Rating multiple = 1/(1−K)**, and **2:1 → 3×**
- **Conductive = K · inductive = 1−K**
- **Common winding = difference current** (where the copper saving lives)
- **Same winding, same loss — far bigger kVA** (efficiency soars)
