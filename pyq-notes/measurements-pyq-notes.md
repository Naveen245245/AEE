# Measurements – Formula/Concept vs. Question Count Analysis

**Source:** Study Material – GTD PYQs 2026 (Measurements)  
**Total Questions Analyzed:** 110+ (Pages 1-30)

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
| **1** | **Basics of Indicating Instruments (PMMC, MI, EDM)** <br> PMMC: `T_d ∝ I`, Scale: Uniform, DC only <br> MI: `T_d ∝ I²`, Scale: Non-uniform, AC/DC <br> EDM: `T_d ∝ I² dM/dθ`, AC/DC <br> `R_sh = R_m/(m-1)` <br> `R_sc = R_m(m-1)` <br> Sensitivity: `S = 1/I_FSD Ω/V` <br> `m = I/I_m` (for ammeter), `m = V/V_m` (for voltmeter) | **~20** | Meter resistance (R_m), Full-scale current (I_m), Desired range (I or V). | **Shunt/series resistance** , **Sensitivity** , **Torque equation** , **Type of instrument** from scale/construction. | Q2, Q7, Q11, Q18, Q19, Q21, Q22, Q25, Q30, Q34, Q38, Q42, Q48, Q49, Q50, Q51, Q54, Q62, Q64, Q67, Q70, Q71, Q73, Q76, Q83, Q86, Q88, Q95, Q98, Q100 |
| **2** | **Instrument Transformers (CT & PT)** <br> CT: `R = n + (I_e/I_s)` (Actual ratio) <br> Ratio error: `(K_n - R)/R × 100` <br> Phase angle: `θ = (180/π)(I_e cos(α+δ) / (n I_s))` <br> PT: Burden in VA <br> CT secondary must NEVER be open | **~10** | CT ratio, Secondary current, Magnetizing/loss component, Burden. | **Ratio error** , **Phase angle** , **Burden** , **CT ratio for protection** , **Causes of errors**. | Q12, Q15, Q39, Q43, Q44, Q55, Q57, Q80 |
| **3** | **Power Measurement (Wattmeters)** <br> 1-Φ: `P = VI cosφ` <br> 2-Wattmeter: `P = W₁ + W₂` <br> `tanφ = √3(W₁ - W₂)/(W₁ + W₂)` <br> `cosφ` from tanφ <br> `W₁ = V_L I_L cos(30-φ)`, `W₂ = V_L I_L cos(30+φ)` <br> EDM Wattmeter: `θ ∝ P` (Uniform scale) | **~16** | Load voltage, Current, Power factor, Two-wattmeter readings. | **Total power** , **Power factor** , **Reactive power** , **Wattmeter connection error** , **Creeping** in energy meters. | Q4, Q6, Q9, Q10, Q16, Q17, Q19, Q22, Q24, Q26, Q27, Q33, Q35, Q36, Q38, Q39, Q40, Q41, Q45, Q46, Q48, Q50, Q52, Q53, Q58, Q60, Q63, Q64 |
| **4** | **Energy Meters** <br> `Meter Constant = N / Energy (kWh)` <br> `Error = (Measured - True) / True × 100` <br> Creeping: Due to over-compensation in pressure coil <br> `Phantom loading`: Low power testing | **~8** | Number of revolutions, Load (V, I, pf, time), Meter constant. | **Energy consumed** , **Error in meter** , **Creeping cause** , **Phantom loading purpose**. | Q25, Q27, Q37, Q42, Q50, Q52 |
| **5** | **Bridges (Wheatstone, Kelvin, AC Bridges)** <br> Wheatstone: `R_x = R₂R₃/R₁` <br> Kelvin: Low resistance measurement <br> Maxwell: Medium Q inductance <br> Hay: High Q inductance <br> Schering: Capacitance & dielectric loss <br> Wien: Frequency measurement <br> Anderson: Precise inductance | **~14** | Bridge components (R, L, C), Source frequency, Balance condition. | **Unknown R/L/C** , **Q factor** , **Dissipation factor** , **Frequency** , **Bridge type identification**. | Q1, Q2, Q3, Q8, Q10, Q11, Q15, Q19, Q20, Q21, Q23, Q24, Q26, Q27, Q29, Q32, Q33, Q35, Q37, Q38, Q39, Q40, Q45, Q46, Q48, Q49, Q50, Q52, Q54 |
| **6** | **CRO & Electronic Measurements** <br> `f_y / f_x = Horizontal tangencies / Vertical tangencies` (Lissajous) <br> Deflection sensitivity: `X = (D * l * V_d) / (2 * d * E_a)` <br> `Resolution = Full scale / Number of counts` (DVM) <br> `SNR = 1.78 + 6.02n dB` | **~10** | CRO settings (Volts/div, Time/div), Lissajous pattern, DVM display. | **Frequency** from Lissajous, **Amplitude** from CRO display, **Resolution** of DVM, **Transducer** type. | Q8, Q10, Q14, Q33, Q39, Q42, Q47, Q50, Q52 |
| **7** | **Transducers** <br> LVDT: Measures displacement <br> Strain gauge: `GF = (ΔR/R)/(ΔL/L)` <br> Thermocouple: Seebeck effect <br> Thermistor: Negative temp coefficient <br> Piezoelectric: Measures pressure/force | **~8** | Transducer type, Physical quantity to be measured. | **Transducer application** , **Working principle** , **Gauge factor** . | Q11, Q12, Q13, Q21, Q25, Q26, Q27, Q28, Q29, Q37, Q38 |
| **8** | **Errors in Measurement** <br> Absolute error: `A_m - A_t` <br> % error: `(A_m - A_t)/A_t × 100` <br> Limiting error: `( % LE × FSV ) / 100` <br> Combination of errors: `ΔR = ΔR₁ + ΔR₂ + ...` (series) | **~8** | Measured value, True value, Full-scale value, Tolerance %. | **Absolute error** , **% limiting error** , **Error propagation** in series/parallel, **Static vs dynamic error**. | Q16, Q52, Q53, Q77, Q87, Q92, Q96, Q104, Q105, Q106, Q107 |

---

## 🧭 The 5-Question Decision Flowchart

| Step | Question to Ask | If YES → | If NO → |
| :---: | :--- | :--- | :--- |
| **1** | **Is it about an instrument (ammeter/voltmeter)?** | Use **Basics of Instruments** formulas (R_sh, R_sc, sensitivity) | Go to Step 2 |
| **2** | **Is it about a transformer (CT/PT)?** | Use **Instrument Transformer** formulas (ratio error, phase angle) | Go to Step 3 |
| **3** | **Is it about power/energy measurement?** | Use **Wattmeter/Energy Meter** formulas | Go to Step 4 |
| **4** | **Is it about a bridge circuit?** | Use **Bridge** formulas (Wheatstone, Kelvin, AC bridges) | Go to Step 5 |
| **5** | **Is it about a CRO or transducer?** | Use **CRO/Transducer** formulas | It's a **theory/error** question. |

---

## 🔑 How to Identify the Topic from the Question

| Keywords in Question | Topic | Go-to Formula |
| :--- | :--- | :--- |
| "Ammeter", "voltmeter", "shunt", "multiplier", "sensitivity" | **Basics of Instruments** | R_sh = R_m/(m-1) |
| "CT", "current transformer", "ratio error", "burden" | **Instrument Transformers** | Ratio error, Phase angle |
| "Wattmeter", "two-wattmeter", "power factor", "energy meter" | **Power/Energy Measurement** | P = W₁ + W₂, tanφ |
| "Wheatstone", "Kelvin", "Schering", "Maxwell" | **Bridges** | Balance condition products |
| "CRO", "Lissajous", "DVM", "transducer" | **Electronic Measurements** | f_y/f_x, GF, sensitivity |

---

## 📝 The Ultimate "What Happens When..." Cheat-Sheet

| Change Made | Effect |
| :--- | :--- |
| **↑ Shunt resistance** (Ammeter) | ↓ Range (multiplying power decreases) |
| **↑ Series resistance** (Voltmeter) | ↑ Range |
| **↑ Sensitivity** | ↓ Full-scale current (more sensitive) |
| **↑ CT burden** | ↑ Ratio & phase errors |
| **CT secondary open** | ↑ High voltage (dangerous) |
| **↑ Temperature** (Manganin) | ↓ Resistance (very low temp coefficient) |
| **↑ Frequency** (MI voltmeter) | ↑ Error (frequency compensated with capacitor) |
| **↑ Power factor** | ↑ Wattmeter reading |
| **↑ Number of insulator discs** | ↓ String efficiency (for identical discs) |

---

## 🎯 Top 10 Concepts to Score >90%

| Rank | Concept | Weightage | Key Formulas |
| :---: | :--- | :---: | :--- |
| **1** | **Basics of Indicating Instruments** | ~18% | R_sh, R_sc, sensitivity, torque |
| **2** | **Power Measurement (Wattmeters)** | ~15% | P = W₁+W₂, tanφ |
| **3** | **Bridges** | ~13% | Balance conditions |
| **4** | **Instrument Transformers** | ~9% | Ratio error, phase angle |
| **5** | **Energy Meters** | ~7% | Meter constant, error |
| **6** | **CRO & Electronic Measurements** | ~9% | Lissajous, deflection sensitivity |
| **7** | **Transducers** | ~7% | LVDT, strain gauge, thermocouple |
| **8** | **Errors in Measurement** | ~7% | Absolute error, limiting error |
| **9** | **AC Bridges (Schering, Wien, etc.)** | ~6% | Bridge type identification |
| **10** | **Meter Construction** | ~5% | Damping, controlling torque |

---

## 📌 Quick Reference Card (Exam Day)

| Concept | Formula | Quick Tip |
| :--- | :--- | :--- |
| **Ammeter Shunt** | `R_sh = R_m/(m-1)` | m = I/I_m |
| **Voltmeter Multiplier** | `R_sc = R_m(m-1)` | m = V/V_m |
| **Sensitivity** | `S = 1/I_FSD Ω/V` | Higher S → Better meter |
| **MI Torque** | `T_d ∝ I²` | Non-uniform scale |
| **PMMC Torque** | `T_d ∝ I` | Uniform scale |
| **EDM Torque** | `T_d ∝ I² dM/dθ` | Used in wattmeters |
| **2-Wattmeter P** | `P = W₁ + W₂` | For balanced 3-Φ load |
| **2-Wattmeter tanφ** | `tanφ = √3(W₁-W₂)/(W₁+W₂)` | |
| **Wheatstone Balance** | `R₁R₄ = R₂R₃` | For DC resistance |
| **Kelvin Bridge** | For low resistance (≤1Ω) | Uses 4-terminal |
| **Maxwell Bridge** | Medium Q coils | Q < 10 |
| **Hay Bridge** | High Q coils | Q > 10 |
| **Schering Bridge** | Capacitance, loss angle | For dielectric measurement |
| **Wien Bridge** | Frequency | `f = 1/(2π√(R₁R₂C₁C₂))` |
| **Lissajous f_y/f_x** | Horizontal tangencies / Vertical tangencies | |
| **Gauge Factor** | `GF = (ΔR/R)/(ΔL/L)` | For strain gauge |
| **LVDT** | Measures displacement | Linear Variable Differential Transformer |
| **Thermocouple** | Seebeck effect | Converts temperature to voltage |

---

# 📝 EMBEDDED PYQs — Ohm Institute PDF

> Source: Study_Material__GTD_PYQs_2026_05_26_9_Measurements_PDF.pdf  
> Contains ~655 PYQs across 4 units. Selected representative Qs below.

---

## Topic 1: Basics of Measuring Instruments (PMMC, MI, EDM)

**Q1 (EPDCL-10):** PMMC instrument measures:
(a) Only DC &emsp; (b) Only AC &emsp; (c) Both &emsp; (d) None  
**Answer: (a)** — PMMC = DC only (polarized magnet)

**Q2 (EPDCL-10):** A 1 mA, 100 Ω meter. What shunt is needed for 100 mA range?
(a) 1.01 Ω &emsp; (b) 1.0 Ω &emsp; (c) 0.99 Ω &emsp; (d) 0.1 Ω  
**Solution:** m = I/Im = 100/1 = 100. Rsh = Rm/(m-1) = 100/99 = **1.01 Ω**  
**Answer: (a)**

**Q4 (APGenco-12):** MI instrument scale is:
(a) Linear &emsp; (b) Non-linear &emsp; (c) Uniform &emsp; (d) Logarithmic  
**Answer: (b)** — MI torque ∝ I² → non-uniform scale

**Q11 (APSPDCL-12):** Voltmeter sensitivity S = 1/Ifsd. If FSD = 50 μA, S in kΩ/V:
(a) 20 &emsp; (b) 50 &emsp; (c) 100 &emsp; (d) 200  
**Solution:** S = 1/(50×10⁻⁶) = 20,000 Ω/V = **20 kΩ/V**  
**Answer: (a)**

**Q14 (TRANSCO-AE-12):** 100 μA meter with 2 kΩ resistance. Voltmeter range with multiplier Rse = 18 kΩ:
**Solution:** V = Ifsd(Rm + Rse) = 100×10⁻⁶×(2000+18000) = 100×10⁻⁶×20000 = 2V

**Q22 (HMWS-12):** EDM instrument torque:
(a) T ∝ I &emsp; (b) T ∝ I² &emsp; (c) T ∝ I²·dM/dθ &emsp; (d) T ∝ V²  
**Answer: (c)** — Electrodynamometer: T = I₁I₂·dM/dθ

---

## Topic 2: Power & Energy Measurement

**Q1 (EPDCL-10):** Two-wattmeter method: W₁=500W, W₂=300W, balanced 3-φ. Total power?
(a) 800W &emsp; (b) 200W &emsp; (c) 1000W &emsp; (d) 400W  
**Answer: (a)** — P = W₁ + W₂ = 800W

**Q3 (APGenco-12):** Power factor from W₁=500, W₂=300:
**Solution:** tanφ = √3(W₁-W₂)/(W₁+W₂) = √3×200/800 = 0.433, φ = 23.4°, **pf = cos23.4° = 0.918**

**Q5 (APSPDCL-12):** Energy meter constant = 600 rev/kWh. A load takes 10 min for 50 rev. Power?
**Solution:** Energy = 50/600 = 0.0833 kWh. Time = 10/60 = 0.167 h.  
P = 0.0833/0.167 = **0.5 kW = 500W**

**Q9 (Transco-12):** Phantom loading is used to test meters because:
(a) Saves power &emsp; (b) High accuracy  
(c) Easy to set up &emsp; (d) All of the above  
**Answer: (a)** — Phantom loading uses reduced voltage/current separately to test at rated VA without full power draw

**Q12 (TSNPDCL-15):** Creeping in energy meter is due to:
(a) Over-compensation in pressure coil &emsp; (b) Friction  
(c) Temperature &emsp; (d) Voltage fluctuation  
**Answer: (a)**

---

## Topic 3: Bridge Measurements (R, L, C)

**Q1 (EPDCL-10):** Wheatstone bridge is used for measuring:
(a) Medium resistance &emsp; (b) Low resistance  
(c) High resistance &emsp; (d) Insulation resistance  
**Answer: (a)** — Wheatstone: 1Ω to 1MΩ range

**Q4 (APGenco-12):** Kelvin bridge measures:
(a) Low resistance &emsp; (b) Medium resistance &emsp; (c) High resistance &emsp; (d) Capacitance  
**Answer: (a)** — Kelvin: ≤1Ω

**Q8 (HMWS-12):** Schering bridge is used for:
(a) Capacitance & dielectric loss &emsp; (b) Inductance  
(c) Frequency &emsp; (d) Low resistance  
**Answer: (a)** — Schering = capacitance measurement

**Q15 (APSPDCL-14):** Maxwell bridge measures:
(a) Medium Q inductance &emsp; (b) High Q inductance  
(c) Capacitance &emsp; (d) Frequency  
**Answer: (a)** — Maxwell: Q < 10. Hay: Q > 10

**Q18 (TSSPDCL-15):** Wien bridge measures:
(a) Frequency &emsp; (b) Capacitance &emsp; (c) Inductance &emsp; (d) Resistance  
**Answer: (a)** — f = 1/(2π√(R₁R₂C₁C₂))

---

## Topic 4: Electronic Measurements & Transducers

**Q1 (EPDCL-10):** CRO timebase generator produces:
(a) Sine wave &emsp; (b) Square wave &emsp; (c) Sawtooth &emsp; (d) Triangular  
**Answer: (c)** — Sawtooth sweep

**Q4 (APGenco-12):** Lissajous pattern: horizontal tangencies=2, vertical tangencies=3. If f_y = 150 Hz, f_x = ?
**Solution:** f_x/f_y = vertical/horizontal = 3/2. f_x = 150×3/2 = **225 Hz**

**Q7 (APSPDCL-12):** LVDT measures:
(a) Displacement &emsp; (b) Pressure &emsp; (c) Temperature &emsp; (d) Force  
**Answer: (a)** — Linear Variable Differential Transformer

**Q10 (Transco-12):** Thermocouple works on:
(a) Seebeck effect &emsp; (b) Peltier effect &emsp; (c) Thomson effect &emsp; (d) Hall effect  
**Answer: (a)**

**Q13 (HMWS-12):** Strain gauge: ΔR/R = 0.001, GF = 2. Strain ΔL/L?
**Solution:** GF = (ΔR/R)/(ΔL/L) → ΔL/L = 0.001/2 = **0.0005 = 500 μ strain**

**Q22 (TSNPDCL-15):** A 3½ digit DMM maximum count:
(a) 999 &emsp; (b) 1999 &emsp; (c) 3999 &emsp; (d) 9999  
**Answer: (b) 1999** — ½ = MSB can be 0 or 1 only

---

> **Total embedded PYQs: 20 (selected from ~655 Measurement questions)**

---

---