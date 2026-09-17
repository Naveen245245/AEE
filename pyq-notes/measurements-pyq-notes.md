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
| :---: | :-------------------------------------------------------------- | :---: | :--- | :--- | :--- |
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
| :---: | :-------------------------------------------------------------- | :--- | :--- |
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
| :---: | :-------------------------------------------------------------- | :---: | :--- |
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

# 📝 FULL PYQ ANALYSIS — All 281 Measurements Questions (Concept through PYQ)

> Source: Study_Material__GTD_PYQs_2026_05_26_9_Measurements_PDF.pdf (OHM Institute)
> Every question: answer + options, the concept it teaches, and how the examiner twists it.

**Legend:** Q = question · Ans = correct option · Concept = new term/principle · Twist = examiner variation → new answer

## Unit 1: Basics of Measuring Instruments (110 Qs)

**Q1 (EPDCL-10):** Which instrument is the cheapest disregarding the accuracy?
(a) PMMC (b) Moving iron (c) Electrodynamometer (d) Rectifier
**Ans: (b)** — Moving iron is the simplest, most robust and cheapest instrument.
**Concept:** Moving-iron instrument — cheapest, works on both a.c./d.c.; accuracy low.
**Twist:** Cheapest *accurate* for a.c. → dynamometer. | Most accurate for d.c. → PMMC.

**Q2 (EPDCL-10):** 1 mA ammeter has resistance 100 Ω; it is to be converted to a 1 A ammeter. Value of shunt resistance?
(a) 0.001 Ω (b) 0.1001 Ω (c) 1,00,000 Ω (d) 100 Ω
**Ans: (b)** — Rsh = Rm/(m−1), m = 1/10⁻³ = 1000 ⇒ Rsh = 100/999 = 0.1001 Ω.
**Concept:** Range extension of ammeter — shunt Rsh = Rm/(m−1) in parallel.
**Twist:** m = 100 → Rsh = 100/99 = 1.01 Ω. | If shunt 0.05 Ω with Rm = 0.2 Ω → m = Rm/Rsh + 1 = 5.

**Q3 (SSC-JE-10):** The controlling torque in a gravity-controlled meter is proportional to:
(a) cos θ (b) sin θ (c) tan θ (d) θ
**Ans: (b)** — Gravity control: Tc ∝ sin θ, hence non-uniform scale.
**Concept:** Gravity control Tc ∝ sin θ (non-linear scale); spring control Tc ∝ θ (linear scale).
**Twist:** Spring control → Tc ∝ θ, uniform scale. | Gravity control with large deflection → tan θ correction for equal divisions.

**Q4 (SSC-JE-10):** Potential transformers are used:
(a) to measure high ac voltage (b) to measure high dc voltage (c) both (a) and (b) (d) as protective device in high voltage circuits
**Ans: (a)** — Transformers work only on a.c.; PTs step down high a.c. voltage for meters.
**Concept:** Instrument transformer — PT steps down high a.c. voltage; CT steps down high current.
**Twist:** High current measurement → current transformer (CT). | DC high voltage → not PT; use resistance divider.

**Q5 (SSC-JE-10):** To increase the range of a voltmeter:
(a) a low resistance is connected in series (b) a low resistance is connected in parallel (c) a high resistance is connected in series (d) a high resistance is connected in parallel
**Ans: (c)** — Voltmeter range is extended by a series multiplier Rse = Rm(M−1).
**Concept:** Range extension of voltmeter — series multiplier (high resistance).
**Twist:** Ammeter range extension → low resistance shunt in parallel. | Multiplier value → Rse = Rm(M−1).

**Q6 (SSC-JE-11):** If θ represents deflection of pointer, the controlling torque in a spring controlled indicating instrument is proportional to:
(a) θ (b) θ² (c) 1/θ (d) sin θ
**Ans: (a)** — Spring control: Tc = kc·θ, giving a linear scale.
**Concept:** Spring control Tc ∝ θ — uniform/linear scale.
**Twist:** Gravity control → Tc ∝ sin θ (non-uniform). | Square-law deflection (MI) → θ ∝ I².

**Q7 (SSC-JE-11):** The range of a dc milliammeter can be extended by using a:
(a) low resistance in series (b) low resistance shunt (c) high resistance in series (d) high resistance shunt
**Ans: (b)** — A low-value shunt (parallel) bypasses current and extends the range.
**Concept:** Ammeter shunt — low resistance in parallel; Rsh = Rm/(m−1).
**Twist:** Extension of voltmeter → high resistance in series. | Shunt value for m = 8, Rm = 100 Ω → 14.3 Ω.

**Q8 (SSC-JE-11):** The response time of an indicating instrument is determined by its:
(a) Deflecting system (b) Damping system (c) Controlling system (d) Support type to the moving system
**Ans: (b)** — Damping decides whether response is over/under/critically damped.
**Concept:** Damping system — controls response time and settling of pointer.
**Twist:** PMMC damping → eddy-current (in aluminium former). | Over-damped → sluggish pointer; under-damped → oscillates.

**Q9 (Transco-12):** The pointer of an indicating instrument is generally made of:
(a) Copper (b) Aluminium (c) Silver (d) Soft steel
**Ans: (b)** — Aluminium is light, giving low inertia.
**Concept:** Pointer material — aluminium (light weight).
**Twist:** Spindle/pivot material → hardened steel. | Control spring material → phosphor-bronze.

**Q10 (Transco-12):** Electrostatic instruments are used as _____ only.
(a) Ammeters (b) Voltmeters (c) Watt meters (d) Energy meters
**Ans: (b)** — Electrostatic voltmeters measure high voltages (kV range), draw negligible current.
**Concept:** Electrostatic voltmeter — for high-voltage measurement, capacitance-based, works on d.c. and a.c.
**Twist:** Measuring current with electrostatic → not possible, low currents. | Measure d.c. kV → same instrument works.

**Q11 (Transco-12):** A 50 V range voltmeter has sensitivity of 20 kΩ/V. The total resistance of the voltmeter is:
(a) 2.5 kΩ (b) 0.4 kΩ (c) 10 kΩ (d) 1 MΩ
**Ans: (d)** — Rtotal = S × V = 20 k × 50 = 1 MΩ.
**Concept:** Sensitivity S = 1/Ifsd Ω/V; voltmeter resistance = S × range.
**Twist:** 100 V, 20 kΩ/V → 2 MΩ. | Given R = 1 MΩ, range 50 V → S = 20 kΩ/V.

**Q12 (APSPDCL-12):** Transformers used in conjunction with measuring instruments for measurement of high voltage and high currents are called:
(a) transformer meters (b) power transformers (c) pulse transformers (d) instrument transformers
**Ans: (d)** — Instrument transformers (CT and PT) are used with meters.
**Concept:** Instrument transformers — CT for current, PT for voltage, provide isolation and range.
**Twist:** High current measurement → CT (secondary never open). | High voltage → PT.

**Q13 (HMWS-12):** If the connections of a moving iron voltmeter connected in a circuit are interchanged, the voltmeter:
(a) will not give any deflection (b) will deflect in opposite direction (c) reading will remain unaffected (d) will burn out
**Ans: (c)** — MI works on I², deflection is independent of polarity.
**Concept:** Moving iron — Td ∝ V² / I², unaffected by reversal of polarity (works a.c./d.c.).
**Twist:** PMMC with reversed connections → reads negative (opposite deflection). | Center-zero PMMC with a.c. → reads negative of mean.

**Q14 (HMWS-12):** Which of the following instruments is exclusively used for measuring radio-frequency currents?
(a) Moving iron (b) Thermocouple (c) PMMC (d) Electro dynamic
**Ans: (b)** — Thermocouple (hot-wire) type gives true r.m.s. at radio frequencies.
**Concept:** Thermocouple ammeter — true r.m.s. independent of frequency/waveform, for r.f.
**Twist:** MI at r.f. → large frequency/eddy errors. | Waveform-independent r.m.s. → hot-wire/thermocouple.

**Q15 (HMWS-12):** The ratio error in the current transformer is attributed to:
(a) magnetizing component of no-load current (b) energy component of excitation current (c) leakage flux (d) power factor of the primary
**Ans: (b)** — Ratio error arises because the no-load (excitation) current disturbs the ideal turns-ratio relation.
**Concept:** CT ratio error — caused by no-load excitation current; %Ratio error = (Kn−R)/R × 100.
**Twist:** Phase-angle error in CT → also from excitation current. | Turns compensation in CT → reduces ratio error only.

**Q16 (HMWS-12):** The difference between the indicated value and the true value of a quantity is known as:
(a) Gross error (b) Absolute error (c) Dynamic error (d) Relative error
**Ans: (b)** — Absolute error = Am − At.
**Concept:** Absolute error = Am − At; relative error = (Am−At)/At × 100.
**Twist:** % error = (measured−true)/true × 100. | Static error = indicated − true (same as absolute).

**Q17 (HMWS-12):** An instrument gives maximum deflection for any amount of quantity passed through it. Which of the following pairs is present?
(a) deflecting and controlling force (b) controlling and damping (c) deflecting and damping (d) deflecting, controlling and damping
**Ans: (c)** — Without a controlling torque the pointer flies to full scale; only deflecting and damping act.
**Concept:** Controlling torque — needed to make deflection proportional to input.
**Twist:** No damping → pointer oscillates continuously. | No deflecting torque → no deflection.

**Q18 (HMWS-12):** A moving coil galvanometer is made into a dc ammeter by connecting:
(a) a low resistance across the meter (b) a high resistance in series with meter (c) a pure inductance across the meter (d) a capacitor in series with the meter
**Ans: (a)** — A low resistance shunt is connected across the meter to bypass heavy current.
**Concept:** Galvanometer → ammeter by low-resistance shunt (parallel).
**Twist:** Galvanometer → voltmeter by high series resistance (multiplier). | To double current range → Rsh = Rm.

**Q19 (HMWS-12):** A moving coil instrument has a resistance of 0.6 Ω and a full-scale deflection current of 0.1 A. To convert it into an ammeter of 0–15 A range, the resistance of the shunt should be:
(a) 0.6 Ω (b) 0.06 Ω (c) 0.1 Ω (d) 0.004 Ω
**Ans: (d)** — m = 15/0.1 = 150; Rsh = 0.6/149 = 0.004 Ω.
**Concept:** Rsh = Rm/(m−1); m = full range / meter FSD current.
**Twist:** Range 0–30 A, Rm = 0.6 Ω, FSD 0.1 A → Rsh = 0.6/299 ≈ 0.002 Ω. | If shunt 0.004 Ω, max current = 150 × 0.1 = 15 A.

**Q20 (Transco-12):** The effect of stray magnetic field on the actuating torque of a portable instrument is maximum when the operating field of the instrument and the stray fields are:
(a) perpendicular (b) parallel (c) inclined at 60° (d) inclined at 30°
**Ans: (b)** — Torque ∝ cos α; maximum when fields are parallel (α = 0°).
**Concept:** Stray-field error — T ∝ cos α, max at parallel, zero at perpendicular; shielding helps.
**Twist:** Fields perpendicular → stray-field effect minimum (zero). | PMMC is shielded to avoid stray fields.

**Q21 (Transco-12):** An ammeter has a current range of 0–5 A, and its internal resistance is 0.2 Ω. In order to change the range to 0–25 A we need to add a resistance of:
(a) 0.8 Ω in series with the meter (b) 1.0 Ω in series with the meter (c) 0.04 Ω in parallel with the meter (d) 0.05 Ω in parallel with meter
**Ans: (d)** — m = 25/5 = 5; Rsh = 0.2/4 = 0.05 Ω in parallel.
**Concept:** Shunt Rsh = Rm/(m−1) placed in parallel.
**Twist:** Range 0–50 A, Rm = 0.2 Ω → Rsh = 0.2/9 ≈ 0.022 Ω. | To get m = 5 with Rsh = 0.05 Ω → Rm = 0.2 Ω.

**Q22 (Transco-12):** A current of −8 + 6√2 (sin ωt + 30°) A is passed through a center-zero PMMC meter, a true r.m.s. meter and a moving iron instrument. The respective readings (in A) will be:
(a) 8, 6, 10 (b) 8, 6, 8 (c) −8, 10, 10 (d) −8, 2, 2
**Ans: (c)** — PMMC reads d.c. component −8 A; true r.m.s. and MI read √(64 + 36) = 10 A.
**Concept:** PMMC reads only d.c. (average); MI/true-r.m.s. read √(Idc² + Iac_rms²).
**Twist:** Only a.c. 6√2 sin → PMMC reads 0, MI reads 6. | If component were 6 sin (r.m.s. 6) → total r.m.s. = √(64+36) = 10 still.

**Q23 (SSC-JE-12):** In the circuit (100 V a.c., diode D forward resistance 2 Ω, 8 Ω in series, meter), forward resistance of diode is 2 Ω and reverse resistance is infinitely high. A list of meters (List-I: i. PMMC, ii. Hot wire) and readings (List-II: (a) 7.07 A, (b) 4.5 A, (c) 10 A, (d) 12.5 A). Correct option?
(a) i → b, ii → d (b) i → a, ii → b (c) i → b, ii → a (d) i → a, ii → c
**Ans: (c)** — Half-wave rectifier: Im = 100√2/10 = 14.14 A; PMMC (avg) = Im/π = 4.5 A; hot-wire (r.m.s.) = Im/2 = 7.07 A.
**Concept:** Half-wave rectifier: avg = Im/π, r.m.s. = Im/2 (with ideal diode, resistive load).
**Twist:** Full-wave rectifier → avg = 2Im/π, r.m.s. = Im/√2. | If 8 Ω load without diode → PMMC = 0, MI = 10 A.

**Q24 (SSC-JE-12):** An a.c. meter of resistance Rm and reactance Xm is connected in series with a resistance Rs. A shunt of impedance (Rsh + jXsh) is applied in parallel. The current division across the two branches will be independent of frequency when:
(a) Rs = Rsh/(Rm²+Xm²) (b) Xsh = Rm·Rsh/Xm (c) (Rs+Rm)²+Xm² = Rsh²+Xsh² (d) Xm/(Rm+Rs) = Xsh/Rsh
**Ans: (d)** — Equal time constants make current division frequency-independent: Xm/(Rm+Rs) = Xsh/Rsh.
**Concept:** Frequency-independent current division — equal X/R (time-constant) in the two branches.
**Twist:** Both branches purely resistive → division independent of frequency. | Capacitive branch → X/R equal condition changes sign.

**Q25 (SSC-JE-12):** Two meters X and Y required 40 mA and 50 mA respectively for full-scale deflection. Then:
(a) Data are insufficient to comment (b) X is more sensitive than Y (c) Y is more sensitive than X (d) Both are equally sensitive
**Ans: (b)** — Sensitivity S = 1/Ifsd: X = 25 Ω/V, Y = 20 Ω/V ⇒ X more sensitive.
**Concept:** Sensitivity = 1/Ifsd Ω/V — smaller FSD current ⇒ more sensitive.
**Twist:** If X = 40 mA, Y = 20 mA → Y more sensitive. | Same FSD currents → equal sensitivity.

**Q26 (SSC-JE-12):** A potentiometer measures 1.2 V between two points; a voltmeter (60 kΩ) measures 0.9 V. The input resistance between the two points:
(a) 20 kΩ (b) 45 kΩ (c) 80 kΩ (d) 60 kΩ
**Ans: (a)** — 1.2/R = 0.9/(R‖60k) ⇒ 4(60) = 3(R+60) ⇒ R = 20 kΩ.
**Concept:** Loading error — voltmeter draws current and reads low; the source resistance can be recovered.
**Twist:** Voltmeter reads 1.0 V (R=40 kΩ) → R = 20 kΩ. | High meter resistance → smaller loading error.

**Q27 (SSC-JE-12):** During measurement of low resistance using a potentiometer: drop across unknown = 0.531 V; drop across a 0.1 Ω standard in series = 1.083 V. The unknown resistor is:
(a) 108.3 milliohm (b) 20.4 milliohm (c) 53.1 milliohm (d) 49.03 milliohm
**Ans: (d)** — I = 1.083/0.1 = 10.83 A; Rx = 0.531/10.83 = 49.03 mΩ.
**Concept:** Potentiometer method for low resistance — same current through standard and unknown.
**Twist:** Standard 1 Ω, drop 1.083 V, unknown 0.531 V → Rx = 0.531/1.083 = 0.49 Ω. | Different current through each → error.

**Q28 (SSC-JE-12):** Which one of the following does not employ a null method of measurement?
(a) DC potentiometer (b) Kelvin double bridge (c) AC potentiometer (d) Megger
**Ans: (d)** — Megger is a direct-deflection (not null) instrument.
**Concept:** Null method — potentiometer and bridges balance until zero deflection.
**Twist:** Bridge balance (Wheatstone) → null method. | Potentiometer standardization → null.

**Q29 (SSC-JE-13):** In an indicating instrument, the springs are mainly used to:
(a) conduct the current to the coils (b) hold the pivot in position (c) control the pointer movement (d) reduce the vibration of the pointer
**Ans: (c)** — Springs (hair springs) provide the controlling torque for the pointer.
**Concept:** Control springs — provide controlling torque (Tc ∝ θ) and lead current in/out.
**Twist:** Gravity control replaces springs → Tc ∝ sin θ. | Springs also carry current to moving coil (dual role).

**Q30 (SSC-JE-13):** When a multiplier is added to an existing voltmeter for extending its range, its electromagnetic damping:
(a) remains unaffected (b) increases (c) decreases (d) changes by an amount depending on the controlling torque
**Ans: (c)** — Adding series multiplier reduces current and hence the electromagnetic (eddy) damping.
**Concept:** Multiplier resistance → reduces current → reduces eddy-current damping.
**Twist:** Shunt on ammeter → changes damping little / shifts operating point. | High multiplier → negligible damping.

**Q31 (SSC-JE-13):** A pulse voltage waveform v(t) = 10 V for 4 ms, 0 for 12 ms (period 16 ms) is measured by PMMC, PMMC+rectifier, and MI. Lists: a. PMMC – i. 5 V, b. PMMC rectifier – ii. 2.75 V, c. M.I. – iii. 2.5 V. Correct option?
(a) a-i, b-ii, c-iii (b) a-iii, b-ii, c-i (c) a-ii, b-iii, c-i (d) a-iii, b-i, c-ii
**Ans: (b)** — PMMC avg = 10×(4/16) = 2.5 V (iii); rectifier reads avg×1.11 = 2.775 ≈ 2.75 V (ii); MI r.m.s. = 10×√(4/16) = 5 V (i).
**Concept:** PMMC reads average; rectifier meter reads average × 1.11 (calibrated for sine); MI reads true r.m.s.
**Twist:** Duty cycle 6/16 → PMMC = 3.75 V, MI = 6.12 V. | Sine wave → rectifier reads correct r.m.s. (1.11 × avg).

**Q32 (SSC-JE-13):** If 110 V, 50 Hz is applied across a PMMC voltmeter of full-scale range (0–220) V and internal resistance 10 kΩ, the reading of the voltmeter will be:
(a) 0 V (b) 110√2 V (c) 78 V (d) 55 V
**Ans: (a)** — PMMC reads average of a.c.; for pure sine it is zero; pointer rests at 0 due to inertia/stopper.
**Concept:** PMMC — d.c. only; reads zero for pure a.c. (average = 0).
**Twist:** Half-wave rectified a.c. → PMMC reads Im/π (nonzero). | Full-wave rectified → 2Im/π.

**Q33 (SSC-JE-13):** An attenuator probe (100 kΩ series, 10 kΩ to amplifier of input capacitance 0.1 μF) — value of C connected across 100 kΩ to make the overall gain independent of frequency:
(a) 0.01 μF (b) 0.1 μF (c) 1 μF (d) 10 μF
**Ans: (a)** — RC-probe balance: 100 k × C = 10 k × 0.1 μ ⇒ C = 0.01 μF.
**Concept:** Compensated attenuator probe — R1C1 = R2C2 for frequency-independent ratio.
**Twist:** 10 k amplifier, 1 nF input → C = 0.1 nF. | Over-compensation → gain rises with frequency.

**Q34 (SSC-JE-13):** A voltmeter reads 124 V across a d.c. supply. With voltmeter (50 kΩ) in series with unknown X across the supply it reads 4 V. The value of X:
(a) 1550 kΩ (b) 1600 kΩ (c) 1.6 kΩ (d) 1.5 MΩ
**Ans: (d)** — I = 4/50 k = 80 μA; X = 120/80 μA = 1.5 MΩ.
**Concept:** Loading — voltage division between voltmeter and unknown series resistance.
**Twist:** Meter reads 12 V → X = (124−12)/12 × 50 k = 466.7 kΩ. | Meter reads 62 V → X = 50 kΩ.

**Q35 (EPDCL-14):** Identify the instrument which has no controlling torque:
(a) electrostatic voltmeter (b) power factor meter (c) watt meter (d) dynamometer type ammeter
**Ans: (b)** — Power factor meter, frequency meter and megger have no controlling torque.
**Concept:** No-controlling-torque instruments — P.F. meter, frequency meter (rest position by field).
**Twist:** Synchroscope → no controlling torque. | Without control, no restoring to zero.

**Q36 (EPDCL-14):** The instrument with good accuracy for measurement of A.C quantities is:
(a) dynamometer type (b) moving iron type (c) moving coil type (d) induction type
**Ans: (a)** — Electrodynamometer has best accuracy on a.c. (used as transfer standard).
**Concept:** Dynamometer — accurate on a.c. and d.c.; PMMC best on d.c.
**Twist:** Most accurate on d.c. → PMMC. | Cheapest on a.c. → moving iron.

**Q37 (APSPDCL-14):** Pick the odd man out:
(a) moving iron meter (b) moving coil meter (c) dynamometer wattmeter (d) watt-hour meter
**Ans: (d)** — Watt-hour meter is an integrating instrument; others are deflection-type.
**Concept:** Integrating instruments — watt-hour/energy meter (totals over time).
**Twist:** Odd among ammeter options for true-r.m.s. → thermocouple. | Integrating among given → watt-hour meter.

**Q38 (ISRO-14):** A meter has a full-scale deflection of 90° at a current of 1 A. The response of the meter is square law. Assuming spring control, the current for a deflection at 45° will be:
(a) 0.25 (b) 0.50 (c) 0.707 (d) 0.67
**Ans: (c)** — θ ∝ I² ⇒ I2 = I1√(θ2/θ1) = 1×√(45/90) = 0.707 A.
**Concept:** Square-law response (MI/electrodynamometer) — θ ∝ I², non-uniform scale.
**Twist:** Linear scale (PMMC) → 45° at 0.5 A. | θ = 22.5° at 1 A → square-law requires 0.5 A.

**Q39 (ISRO-14):** A 50 Hz bar-primary CT has a secondary with 500 turns supplying 5 A into a 1 Ω burden; magnetizing ampere-turns = 200. The phase angle between primary and secondary current is:
(a) 4.6° (b) 85.4° (c) 94.6° (d) 175.4°
**Ans: (a)** — I0 = 200/1 = 200 A; n = 500; θ ≈ (180/π)×[200×cos(0)/(500×5)] = 4.6°.
**Concept:** CT phase angle error — θ = (180/π)(I0cos(α+δ))/(n·Is).
**Twist:** Magnetizing AT = 100 → θ ≈ 2.3°. | If burden 2 Ω → more magnetizing current, larger phase error.

**Q40 (SSC-JE-S1-14):** Two voltmeters of (0–300 V) range are connected in parallel to an a.c. circuit. One (moving iron) reads 200 V. If the other is PMMC, its reading will be:
(a) slightly less than 200 V (b) zero V (c) 222 V (d) 127.4 V
**Ans: (b)** — PMMC reads average of pure a.c. = 0.
**Concept:** PMMC reads d.c./average only — zero on pure a.c.
**Twist:** Distorted waveform with d.c. component → PMMC reads the d.c. component. | Rectifier + PMMC → reads 200×1.11×avg... (r.m.s. calibrated).

**Q41 (SSC-JE-S1-14):** Moving coil (PMMC) and moving iron instruments can be distinguished by observing its:
(a) pointer (b) range (c) scale (d) size of terminals
**Ans: (c)** — PMMC has a uniform (linear) scale; MI has a non-uniform (cramped at start) scale.
**Concept:** Scale — uniform for PMMC (spring control, θ∝I), non-uniform for MI (θ∝I²).
**Twist:** Electrodynamometer scale → square law (non-uniform) unless shaped. | Hot-wire scale → non-uniform.

**Q42 (SSC-JE-S1-14):** A d.c. voltmeter has a sensitivity of 1000 Ω/V. When it measures half full-scale in 100 V range, the current through the voltmeter will be:
(a) 100 mA (b) 1 mA (c) 0.5 mA (d) 50 mA
**Ans: (c)** — Ifsd = 1/1000 = 1 mA; at half FSD current = 0.5 mA.
**Concept:** Sensitivity S = 1/Ifsd; meter current ∝ deflection.
**Twist:** Sensitivity 20 kΩ/V, 50 V range, half FSD → 1/20000 = 50 μA, half = 25 μA. | Full scale in 100 V at 1000 Ω/V → 1 mA.

**Q43 (SSC-JE-S1-14):** To increase the range of an a.c. ammeter, you would use:
(a) current transformer (b) a potential transformer (c) an inductance across the meter (d) a condenser across the meter
**Ans: (c)** — An inductive shunt (coil of extra turns) is connected in parallel with the meter.
**Concept:** A.C. ammeter range extension — parallel inductive shunt (or C.T.); d.c. ammeter uses plain resistive shunt.
**Twist:** D.c. ammeter range extension → resistive shunt in parallel. | Very large a.c. current → use C.T. instead.

**Q44 (SSC-JE-S2-14):** In which of the following transformers is the secondary winding always kept closed?
(a) current transformer (b) potential transformer (c) power transformer (d) distribution transformer
**Ans: (a)** — CT secondary must never be open; open secondary induces very high voltage.
**Concept:** CT secondary always shorted/closed — open secondary is dangerous (insulation breakdown).
**Twist:** PT secondary must not be short-circuited (high current). | Removing meter from CT → short the secondary first.

**Q45 (SSC-JE-S2-14):** In electro-dynamometer ammeter, the deflection of the pointer is proportional to:
(a) mean of currents in fixed coil and moving coil (b) square of the current in moving coil (c) RMS value of current in fixed coil (d) mean-square of current in fixed coil and moving coil
**Ans: (d)** — Td ∝ I1I2 with I1 = I2 = I ⇒ θ ∝ I² (mean-square of the currents).
**Concept:** Dynamometer ammeter — Td ∝ I1·I2·(dM/dθ), with series coils θ ∝ I².
**Twist:** Dynamometer wattmeter → θ ∝ V·I (product). | Dynamometer voltmeter → θ ∝ V².

**Q46 (SSC-JE-S2-14):** Which of the following instruments has the highest torque/weight ratio among the given instruments?
(a) attraction type MI instrument (b) repulsion type MI instrument (c) permanent magnet moving coil instrument (d) electrodynamometer instrument
**Ans: (c)** — PMMC has the highest torque/weight ratio (strong permanent-magnet field).
**Concept:** Torque/weight ratio — highest for PMMC, lowest for dynamometer.
**Twist:** Instrument with low torque → dynamometer (used as transfer std.). | MI torque/weight → moderate.

**Q47 (SSC-JE-S2-14):** If current through the operating coil of a moving iron instrument is doubled, the operating force becomes:
(a) one and a half times (b) 2 times (c) 3 times (d) 4 times
**Ans: (d)** — Force ∝ I²; doubling current → 4× force.
**Concept:** Moving iron force F ∝ I² (or V²).
**Twist:** Current tripled → force 9×. | PMMC torque → ∝ I (doubling gives 2×).

**Q48 (SSC-JE-S2-14):** A moving coil instrument has a resistance of 10 Ω and gives full-scale deflection at 0.5 V potential difference across it. How can it be adapted to measure a current up to 100 A?
(a) by connection shunt resistance of 0.005 Ω across the meter (b) by connecting shunt resistance of 2 Ω across the meter (c) by connecting shunt resistance of 5 Ω across the meter (d) by connecting shunt resistance of 10 Ω across the meter
**Ans: (a)** — Ia = 0.5/10 = 50 mA; m = 100/0.05 = 2000; Rsh = 10/1999 ≈ 0.005 Ω.
**Concept:** Ammeter conversion — Rsh = Rm/(m−1) with m = I/Ia.
**Twist:** Current up to 200 A, same meter → Rsh = 10/3999 ≈ 0.0025 Ω. | If shunt 0.005 Ω → full range = 2000 × 0.05 = 100 A.

**Q49 (SSC-JE-S2-14):** The multiplying power of the shunt of a milliammeter is 8. If the circuit current is 200 mA, then current through the meter is:
(a) 25 mA (b) 200 mA (c) 1600 mA (d) 3200 mA
**Ans: (a)** — Im = I/m = 200/8 = 25 mA.
**Concept:** Multiplying power m = I/I_m; meter current = total/m.
**Twist:** m = 8, I = 40 mA → Im = 5 mA. | Given Im = 25 mA, I = 200 mA → m = 8.

**Q50 (HMWS-15):** A meter has a full-scale angle of 90° at a current of 1 A, with perfect square-law response. Assuming spring control, the current for a deflection angle 45° will be:
(a) 0.67 A (b) 0.25 A (c) 0.707 A (d) 0.5 A
**Ans: (c)** — θ ∝ I²; I2 = 1×√(45/90) = 0.707 A.
**Concept:** Square-law scale — deflection ∝ square of current.
**Twist:** Linear PMMC → 0.5 A at 45°. | 60° deflection → I = √(60/90) = 0.816 A.

**Q51 (HMWS-15):** Two ammeters — one FSD 1 mA, 100 Ω; other FSD 10 mA, 25 Ω — connected in parallel. Total current they can carry without any meter reading out of scale?
(a) 5 mA (b) 10 mA (c) 11 mA (d) 1 mA
**Ans: (a)** — Common voltage 0.1 V: meter 1 takes 1 mA, meter 2 takes 0.1/25 = 4 mA ⇒ total 5 mA.
**Concept:** Parallel meters — limited by the meter that reaches FSD first (equal voltage across shunts).
**Twist:** Both 1 mA meters (100 Ω) in parallel → total 2 mA. | Series connection → equal current, sum of FSDs is not the limit.

**Q52 (HMWS-15):** The resistance of a circuit is found by measuring current and power fed into the circuit. If the limiting errors in power and current are ±1.5% and ±1% respectively, the limiting error in resistance will be:
(a) 3.5% (b) 1.5% (c) 2.5% (d) 1%
**Ans: (a)** — R = P/I² ⇒ %eR = 1.5 + 2×1 = 3.5%.
**Concept:** Limiting error propagation — errors add for products/quotients (powers multiply the exponent).
**Twist:** R = V/I with V ±1%, I ±1% → 2%. | R = P/I² with P ±2%, I ±0.5% → 3%.

**Q53 (HMWS-15):** Error due to change in frequency in a moving iron instrument is reduced by connecting a capacitor 'c' across the series resistance 'r'. If 'L' is the inductance of the coil, the readings will be independent of frequency only when:
(a) c = L/r (b) c = L²/r (c) c = Lr² (d) c = L/r²
**Ans: (d)** — c = L/r² (equivalently 0.41 L/r²) makes the MI voltmeter frequency-independent.
**Concept:** Frequency-error compensation in MI — capacitor across the series multiplier (c = L/r²).
**Twist:** r = 2000 Ω, L = 1 H → C = 1/4e6 = 0.25 μF. | r = 1000 Ω, L = 1 H → C = 1 μF.

**Q54 (HMWS-15):** Two 300 V full-scale voltmeters V1 and V2 having sensitivities 100 kΩ/V and 150 kΩ/V are connected in series to measure 500 V:
(a) V1 and V2 will read 0 V each (b) V1 will read 200 V and V2 will read 300 V (c) V1 will read 300 V and V2 will read 200 V (d) V1 and V2 will read 250 V each
**Ans: (b)** — Rm1 = 30 MΩ, Rm2 = 45 MΩ; V1 = 500×30/75 = 200 V, V2 = 300 V.
**Concept:** Series voltmeters — voltage divides by resistance (sensitivity); the meter with smaller FSD current (higher kΩ/V) reads more.
**Twist:** V1 = 100 kΩ/V, V2 = 200 kΩ/V, 500 V → V1 = 150 V, V2 = 350 V. | Both equal sensitivity → 250 V each.

**Q55 (HMWS-15):** In current transformers, turns compensation is provided mainly to reduce the:
(a) both ratio and phase angle errors (b) phase angle error (c) ratio error (d) power losses
**Ans: (c)** — Turns compensation corrects the turns ratio and mainly reduces the ratio error.
**Concept:** CT turns compensation — reduces ratio error.
**Twist:** Phase-angle error reduction → change secondary winding resistance / use auxiliary winding. | Compensation with shunt winding → ratio + phase.

**Q56 (HMWS-15):** PMMC type instruments normally use:
(a) no damping is required (b) fluid-friction damping (c) eddy current damping (d) air-friction damping
**Ans: (c)** — PMMC uses eddy-current damping (aluminium former/coil core).
**Concept:** Damping in PMMC — eddy-current (eddy currents in the former moving in the magnet field).
**Twist:** Electrodynamometer → air-friction damping. | Energy-meter disc → eddy-current (magnet) damping.

**Q57 (HMWS-15):** What will happen if a voltmeter is connected like an ammeter in series with the load?
(a) there will be almost no current in the circuit (b) the measurement will be too high (c) an inadmissibly high current will flow (d) the meter will burn out
**Ans: (a)** — The voltmeter's high internal resistance in series limits current to almost zero.
**Concept:** Loading — voltmeter must be in parallel; its high resistance in series chokes the circuit.
**Twist:** Ammeter connected in parallel across supply → burns out (large current). | Correct connection → voltmeter in parallel, ammeter in series.

**Q58 (HMWS-15):** A standard cell of 1.02 V used with a simple potentiometer balances at 50 cm. Then the emf of the cell that balances at 100 cm is:
(a) 3.06 V (b) 0.51 V (c) 4.08 V (d) 2.04 V
**Ans: (d)** — E ∝ length: E = 1.02 × (100/50) = 2.04 V.
**Concept:** Potentiometer — EMF proportional to balance length.
**Twist:** Balances at 40 cm → E = 0.816 V. | Same cell at 120 cm → E = 2.448 V.

**Q59 (HMWS-15):** Moving iron instruments can be used on:
(a) high frequency supply (b) D.C only (c) measure A.C and D.C (d) A.C only
**Ans: (c)** — MI works on I² (or V²), hence measures both a.c. and d.c.
**Concept:** Moving iron — a.c. and d.c. capable (polarity-independent).
**Twist:** MI on d.c. → works but reads with more error than PMMC (hysteresis). | PMMC on a.c. → reads zero.

**Q60 (TS Genco-15):** An unshielded moving iron voltmeter is used to measure voltage in an a.c. circuit. If a stray DC magnetic field having a component along the axis of the meter coil appears, the meter reading would be:
(a) unaffected (b) decreased (c) increased (d) either decreased or increased depending on the direction of the DC field
**Ans: (d)** — Stray d.c. field adds or subtracts depending on direction; shielding avoids it.
**Concept:** Stray-field error — unshielded instruments affected; shielding is provided.
**Twist:** Field perpendicular to coil axis → little effect. | Shielded meter → unaffected.

**Q61 (TS Genco-15):** A DC voltmeter has a sensitivity of 1000 Ω/volt. When it measures half full-scale in 100 V range, the current through the voltmeter is:
(a) 100 mA (b) 1 mA (c) 0.5 mA (d) 50 mA
**Ans: (c)** — Ifsd = 1 mA; half FSD → 0.5 mA.
**Concept:** S = 1/Ifsd; meter current ∝ deflection.
**Twist:** Sensitivity 10 kΩ/V, 50 V range → Ifsd = 100 μA; half FSD = 50 μA. | At 100 V full scale → 1 mA.

**Q62 (TS Genco-15):** A moving coil meter has 100 turns, length and depth 10 mm and 20 mm; positioned in uniform radial flux density 200 mT; coil current 50 mA. Torque on the coil:
(a) 200 μNm (b) 100 μNm (c) 2 μNm (d) 1 μNm
**Ans: (a)** — T = BINA = 200m×50m×100×(10×20×10⁻⁶) = 200 μNm.
**Concept:** PMMC torque T = B·I·N·A = NBAI.
**Twist:** B = 100 mT, I = 25 mA, N = 100, A = 200 mm² → 50 μNm. | Double N → double torque.

**Q63 (TS Genco-15):** Thermocouple data at 0°C: θ 20/100/300 °C → E 0.194/0.850/1.650 mV. Assuming parabolic relation, the neutral temperature is about:
(a) 300°C (b) 333°C (c) 366°C (d) 399°C
**Ans: (b)** — e = aT+bT²; from data a = 10⁻⁵, b = −1.5×10⁻⁸; Tn = −a/2b ≈ 333°C.
**Concept:** Neutral temperature — where thermo-emf is maximum; Tn = −a/2b for e = aT+bT².
**Twist:** Different (a,b) fit → Tn changes. | Inversion temperature = 2 × neutral temperature.

**Q64 (TS Genco-15):** A moving coil ammeter has a fixed shunt of 0.02 Ω. If the coil resistance is 1000 Ω and 500 mV is required across it for FSD, the current in the shunt is:
(a) 2 A (b) 10 A (c) 25 A (d) 2.5 A
**Ans: (c)** — Ish = Vm/Rsh = 0.5/0.02 = 25 A.
**Concept:** Shunt current — voltage across shunt = meter voltage = Im×Rm.
**Twist:** Rsh = 0.05 Ω, V = 500 mV → Ish = 10 A. | Rsh = 0.1 Ω, V = 100 mV → Ish = 1 A.

**Q65 (TS Genco-15):** Measurement of a non-electrical quantity involves four subsystems: (I) amplifier block, (II) display block, (III) instrumentation block, (IV) transducer block. Correct sequence:
(a) IV, I, III, II (b) IV, III, I, II (c) I, III, II, IV (d) I, II, III, IV
**Ans: (a)** — Transducer → amplifier → instrumentation → display.
**Concept:** Measurement chain — transducer, signal conditioning, processing, display.
**Twist:** Add A/D before display → transducer, amplifier, A/D, display. | Transducer directly to meter → no amplifier.

**Q66 (TS Genco-15):** Ideally, the damping torque should be:
(a) proportional to velocity of the moving system and operating current (b) proportional to the velocity of the moving system but independent of operating current (c) independent of the velocity of the moving system and proportional to the operating current (d) independent of the velocity of the moving system and operating current
**Ans: (b)** — Damping torque should be ∝ velocity, independent of the measured current.
**Concept:** Damping torque — proportional to speed of moving system, independent of input (so no steady-state error).
**Twist:** Deflecting torque → ∝ current (PMMC). | Controlling torque → ∝ deflection θ.

**Q67 (TSNPDCL-15):** A 5 A ammeter with 0.3 Ω resistance is to be used to measure current up to 20 A. The shunt resistance to be used is:
(a) 0.1 Ω (b) 0.2 Ω (c) 0.3 Ω (d) 1 Ω
**Ans: (a)** — m = 20/5 = 4; Rsh = 0.3/3 = 0.1 Ω.
**Concept:** Rsh = Rm/(m−1); m = I/I_m.
**Twist:** Up to 50 A with 5 A meter → m = 10, Rsh = 0.3/9 ≈ 0.033 Ω. | Rsh = 0.1 Ω, Rm = 0.3 → m = 4.

**Q68 (TSNPDCL-15):** In a PMMC instrument, the damping provided is:
(a) air damping (b) fluid damping (c) eddy current damping (d) magnetic damping using a magnet
**Ans: (c)** — PMMC uses eddy-current damping in the aluminium former.
**Concept:** PMMC damping — eddy-current (electromagnetic) damping.
**Twist:** Hot-wire/MI large-scale → air damping. | Dynamometer → air-friction.

**Q69 (TSNPDCL-15):** In a diode rectifier circuit (200 sin 100t, series L = 1 H) the PMMC meter will read:
(a) 1 A (b) 1.414 A (c) 2 A (d) 2.814 A
**Ans: (c)** — Half-wave: avg current = Vm/(ωL) = 200/(100×1) = 2 A.
**Concept:** PMMC reads average of half-wave rectified a.c.; avg = Vm/(ωL) for inductive circuit.
**Twist:** L = 2 H → 1 A. | Full-wave rectifier → 2Vm/(πωL) = 4 A (in magnitude).

**Q70 (AP Transco-17):** A moving coil meter has resistance 3 Ω and gives FSD with 30 mA. To measure voltage up to 300 V, the external series resistance is:
(a) 9997 Ω (b) 10000 Ω (c) 997 Ω (d) 10003 Ω
**Ans: (a)** — Vm = 30m×3 = 0.09 V; Rse = 3×(300/0.09 − 1) = 9997 Ω.
**Concept:** Voltmeter multiplier — Rse = Rm(V/Vm − 1) = (V − Im·Rm)/Im.
**Twist:** 150 V, 3 Ω, 30 mA → Rse = 4997 Ω. | Sensitivity 1000 Ω/V, 300 V → Rse = 300 kΩ − Rm.

**Q71 (AP Transco-17):** A PMMC has FSD of 100 μA and coil resistance 1 kΩ. To convert to an ammeter with FSD of 100 mA, the required shunt resistance is:
(a) 1 Ω (b) 1.001 Ω (c) 0.5 Ω (d) 10 Ω
**Ans: (b)** — Rsh = Rm/(I/Im − 1) = 1000/(1000 − 1) = 1.001 Ω.
**Concept:** Rsh = Rm/(m−1); m = I/Im.
**Twist:** I = 1 A, Im = 100 μA, Rm = 1 kΩ → Rsh ≈ 0.1 Ω. | m = 100, Rm = 1 kΩ → Rsh = 10.1 Ω.

**Q72 (AP Transco-17):** The pointer of a moving coil ammeter deflects from zero and comes to rest at the 2 A marking. In the steady deflected position:
(a) deflecting torque TD is zero (b) control torque TC is zero (c) both TD and TC are zero, damping torque Td ∝ 2 A (d) Td = 0
**Ans: (d)** — At steady position TD = TC; the damping torque (∝ velocity) is zero.
**Concept:** At equilibrium, deflecting = controlling; damping torque zero at rest.
**Twist:** While moving, Td ∝ velocity (nonzero). | Overdamped system → no overshoot, longer settle.

**Q73 (TSSPDCL-18):** A PMMC meter has a coil of area 200 mm², flux density 2 mWb/m², spring constant 0.16×10⁻⁶ Nm/rad, deflection 90° at 5 mA. Number of turns:
(a) 136 (b) 126 (c) 152 (d) 96
**Ans: (b)** — NBAI = Kcθ ⇒ N = 0.16e-6×(π/2)/(2000×200e-6×5e-3) = 126.
**Concept:** PMMC balance NBAI = Kcθ (Td = Tc).
**Twist:** θ = 60°, same data → N ≈ 84. | B = 4 mWb/m² → N ≈ 63.

**Q74 (TSSPDCL-18):** Regarding thermo-electric ammeters: 1. correct rms irrespective of frequency and waveform; 2. severely affected by stray magnetic fields; 3. primarily designed for high-frequency current; 4. low sensitivity. Which are correct?
(a) 2, 4 (b) 3, 4 (c) 1, 3, 4 (d) 1, 3
**Ans: (d)** — Thermocouple ammeters give true r.m.s. at any frequency/waveform, are for r.f., have high sensitivity, and are unaffected by stray fields.
**Concept:** Thermocouple (hot-wire) ammeter — true r.m.s., frequency-independent, high sensitivity.
**Twist:** Stray fields affect → MI not thermocouple. | Low sensitivity → PMMC with amplifier, not thermocouple.

**Q75 (TSSPDCL-18):** A potentiometer measures current: drop across a 0.1 Ω standard is balanced at 60 cm; standard cell emf 1.018 V balances at 50 cm. The circuit current is:
(a) 1.018 A (b) 10.18 A (c) 12.215 A (d) 1.221 A
**Ans: (c)** — V = 1.018×(60/50) = 1.2216 V; I = 1.2216/0.1 = 12.216 ≈ 12.215 A.
**Concept:** Potentiometer current measurement — E ∝ balance length, I = V/R.
**Twist:** 0.1 Ω standard at 25 cm, cell 1.018 V at 50 cm → I = 1.018×(25/50)/0.1 = 0.509 A. | Standard 1 Ω → I = 1.2216 A.

**Q76 (TSSPDCL-18):** A PMMC meter has internal resistance 200 Ω and FSD current 50 μA. The maximum voltage it can measure on its own is:
(a) 5 μV (b) 10 μV (c) 5 mV (d) 10 mV
**Ans: (d)** — V = Ifsd×R = 50μ×200 = 10 mV.
**Concept:** Voltage rating of a milliammeter — Vm = Ifsd·Rm.
**Twist:** R = 1 kΩ, Ifsd = 100 μA → 0.1 V. | Ifsd 50 μA, R 100 Ω → 5 mV.

**Q77 (TS Transco-18):** Errors which may be variable both in magnitude and nature (positive or negative) are classified as:
(a) Hysteresis error (b) Random errors (c) Systematic errors (d) Interaction errors
**Ans: (b)** — Random (accidental) errors vary in sign and magnitude.
**Concept:** Error classification — random vs systematic vs gross errors.
**Twist:** Reproducible constant error → systematic. | Mistake in reading → gross error.

**Q78 (APEPDCL-19):** For a given frequency, the deflecting torque of an induction ammeter is directly proportional to:
(a) current (b) current² (c) current³ (d) √current
**Ans: (b)** — Td ∝ φ1m·φ2m·sinα; both fluxes from the same current ⇒ Td ∝ I².
**Concept:** Induction ammeter — Td ∝ I² (fluxes in quadrature by shaded pole/shading).
**Twist:** Induction wattmeter → Td ∝ V·I·cosφ. | Induction energy meter → Td ∝ V·I.

**Q79 (APEPDCL-19):** A manganin swamp resistance is connected in series with a moving coil ammeter (milliammeter + shunt) in order to:
(a) minimize the effect of stray magnetic fields (b) minimize the effect of temperature variation (c) obtain large deflecting torque (d) reduce the size of the meter
**Ans: (b)** — Manganin/constantan have negligible temperature coefficient, swamping resistance reduces temperature error.
**Concept:** Swamping resistance — series resistance of low-temperature-coefficient material.
**Twist:** Shunt material → manganin (low temp. coefficient). | Swamp both for ammeter and shunt.

**Q80 (APEPDCL-19):** The primary current in a current transformer is dictated by:
(a) turns ratio (b) the secondary burden (c) the core of the transformer (d) load current
**Ans: (d)** — The primary current is set by the load; secondary burden does not control it.
**Concept:** CT — primary current is the line/load current (independent of burden).
**Twist:** CT secondary burden change → changes secondary current and ratio/phase error, not primary. | PT primary → supply voltage.

**Q81 (APEPDCL-19):** Which of the following is a dynamic characteristic of an instrument?
(a) threshold (b) hysteresis (c) fidelity (d) resolution
**Ans: (c)** — Fidelity, speed of response, measuring lag, dynamic error are dynamic characteristics.
**Concept:** Static vs dynamic characteristics — fidelity/response-time (dynamic); accuracy, precision, threshold, resolution, hysteresis (static).
**Twist:** Static characteristic → accuracy/precision/resolution. | Speed of response → dynamic.

**Q82 (APEPDCL-19):** For a given PMMC ammeter, the pointer deflects 90° for 10 mA. Due to ageing, the spring constant reduces by 10%. Deflection for 5 mA current?
(a) 50° (b) 90° (c) 81° (d) 45°
**Ans: (a)** — θ ∝ I/Kc: θ2 = 90 × (5/10) × (1/0.9) = 50°.
**Concept:** Ageing error — spring constant drop increases deflection for same current.
**Twist:** Spring constant reduces 20% → θ = 56.25°. | Kc unchanged → 45°.

**Q83 (APSPDCL-AE-19):** Which of the following is needed to extend the range of a milliammeter to read voltages of the order of 100 V?
(a) A parallel high-value resistance (b) A series high-value resistance (c) A parallel low-value resistance (d) A series low-value resistance
**Ans: (b)** — Voltmeter conversion needs a high-value series multiplier.
**Concept:** Milliammeter → voltmeter — series multiplier Rse = (V/Im) − Rm.
**Twist:** Ammeter conversion → low-value parallel shunt. | To read 1000 V → larger series R.

**Q84 (APSPDCL-19):** Which of the following statements is false?
(a) Moving coil instruments can be used on dc only (b) Moving iron instruments have a non-linear scale (c) Moving coil rectifier instrument has a linear scale (d) Moving iron instruments can be used only on ac
**Ans: (d)** — MI instruments work on both a.c. and d.c.; statement (d) is false.
**Concept:** MI — a.c./d.c. both (Td ∝ I²); PMMC — d.c. only.
**Twist:** PMMC on a.c. → reads zero (not false). | MI scale → non-uniform (true).

**Q85 (AP Transco-19):** Which statement is INCORRECT with regard to potentiometers?
(a) They can be used for ac magnetic testing (b) They are basically null-type instruments (c) Standardization of dc potentiometers is done using dc standard sources (d) Standardization of ac potentiometers is done using ac standard sources
**Ans: (d)** — A.C. potentiometers are standardized with a d.c. standard source (no a.c. standard available).
**Concept:** Potentiometer standardization — d.c. potentiometer with standard cell; a.c. potentiometer with d.c. standard + transfer instrument.
**Twist:** D.c. potentiometer → null method, standard cell. | A.c. potentiometer → standardized via d.c.

**Q86 (AP Transco-19):** A moving coil galvanometer is made into a dc ammeter by connecting:
(a) a low resistance across the meter (b) a high resistance across the meter (c) a high resistance in series with the meter (d) a low resistance in series with the meter
**Ans: (a)** — Low-resistance shunt in parallel.
**Concept:** Galvanometer → ammeter — parallel shunt.
**Twist:** Galvanometer → voltmeter — series multiplier. | Galvanometer → dc ammeter of small range — small shunt.

**Q87 (HMWSSB-20):** R1 = 40 Ω ±5%, R2 = 80 Ω ±5%, R3 = 50 Ω ±5%. Limiting error in ohms if connected in series?
(a) 8.5 (b) 17 (c) 4.25 (d) 2.16
**Ans: (a)** — ΔR1=2, ΔR2=4, ΔR3=2.5; total = 2+4+2.5 = 8.5 Ω.
**Concept:** Series limiting error — absolute errors add.
**Twist:** Parallel combination → relative errors add: 5+5+5 = 15% of equivalent. | R1=40±2%, R2=80±3% series → 0.8+2.4 = 3.2 Ω.

**Q88 (HMWSSB-20):** A milli-ammeter of 1.5 Ω resistance reads up to 100 milliamperes. The series resistance required to make it a voltmeter reading up to 100 V is:
(a) 1000 Ω (b) 1001.5 Ω (c) 998.5 Ω (d) 98.5 Ω
**Ans: (c)** — Vm = 1.5×0.1 = 0.15 V; Rse = 1.5×(100/0.15 − 1) = 998.5 Ω.
**Concept:** Voltmeter multiplier — Rse = (V − Vm)/Im.
**Twist:** 50 V, 1.5 Ω, 100 mA → Rse = 498.5 Ω. | Sensitivity = 1000 Ω/V → Rse = 100 kΩ − 1.5 Ω.

**Q89 (HMWSSB-20):** Which of the following statements is wrong with respect to M.I instruments?
(a) Scale is not uniform (b) For low voltage range, the power consumption is more (c) Repulsion type instruments are much more common than the attraction type (d) Attraction type instrument will usually have a more inductance than the corresponding repulsion instrument
**Ans: (b)** — Per OHM key; (b) is the wrong statement (M.I. actually consumes more power at low ranges, but the key marks it wrong — note that (d) is the textbook "true" distinguishing statement).
**Concept:** M.I. characteristics — non-uniform scale, both a.c./d.c., attraction vs repulsion type.
**Twist:** Wrong statement about MI scale → "uniform scale" (that is false). | M.I. used only on a.c. → false.

**Q90 (HMWSSB-20):** The value of capacitance connected across the series resistance of 2000 Ω with coil inductance 1 H of an M.I. voltmeter to eliminate the frequency error is around:
(a) 0.5 μF (b) 0.1 μF (c) 1 μF (d) 0.25 μF
**Ans: (d)** — C = L/r² = 1/(2000)² = 0.25 μF.
**Concept:** Frequency-error compensation — C = L/r² across the series multiplier.
**Twist:** r = 1000 Ω, L = 1 H → C = 1 μF. | r = 4000 Ω, L = 1 H → C ≈ 0.0625 μF.

**Q91 (HMWSSB-20):** A PMMC instrument can be used as a ballistic galvanometer by:
(a) eliminating the control springs (b) using control springs of large Moment of Inertia (c) using a low resistance shunt (d) using a high series resistance
**Ans: (a)** — Removing the controlling torque (springs) lets the coil swing undamped — ballistic (charge) measurement.
**Concept:** Ballistic galvanometer — no controlling torque, measures charge (∫i·dt).
**Twist:** Ballistic sensitivity requires long period → remove springs + light damping. | If damping retained → measures current, not charge.

**Q92 (TSSPDCL-22):** A 0–300 V voltmeter has an error of 2% on full scale deflection. If the true voltage is 30 V, the range of reading will be:
(a) 24 to 36 V (b) 22 to 40 V (c) 26.94 to 33.06 V (d) 29.94 to 30.06 V
**Ans: (a)** — Error = 2%×300 = 6 V; reading range = 30 ± 6 = 24 to 36 V.
**Concept:** Guaranteed-accuracy error is % of full-scale — constant absolute error across the scale.
**Twist:** True 150 V → 144 to 156 V. | Error 1% FSD → 30 ± 3 V.

**Q93 (TSSPDCL-22):** Two 300 V full-scale voltmeters V1 (100 kΩ/V) and V2 (150 kΩ/V) connected in series to measure 500 V:
(a) V1 and V2 will read 250 V each (b) V1 and V2 will read 0 V each (c) V1 will read 200 V and V2 will read 300 V (d) V1 will read 300 V and V2 will read 200 V each
**Ans: (c)** — Rm1 = 30 MΩ, Rm2 = 45 MΩ; V1 = 200 V, V2 = 300 V.
**Concept:** Series voltmeters divide by resistance (∝ sensitivity).
**Twist:** V1 = 120 kΩ/V, V2 = 60 kΩ/V, 500 V → V1 = 333.3 V, V2 = 166.7 V. | Equal sensitivity → 250 V each.

**Q94 (TSSPDCL-22):** By mistake voltmeter and ammeter are connected as shown (ammeter across supply, voltmeter in series with load):
(a) only ammeter will burn away (b) only voltmeter will burn away (c) both voltmeter and ammeter will burn away (d) none will burn away
**Ans: (a)** — The low-resistance ammeter across the supply draws a huge current and burns; the voltmeter in series limits current.
**Concept:** Correct connections — ammeter in series, voltmeter in parallel.
**Twist:** Voltmeter in parallel (correct) + ammeter in series (correct) → both safe. | Ammeter across low-resistance supply → burns.

**Q95 (TSNPDCL-22):** A moving coil instrument gives FSD of 10 mA when the potential difference across its terminals is 0.1 V. Determine the series resistance to convert it into a voltmeter measuring up to 20 V:
(a) 1990 Ω (b) 2000 Ω (c) 2010 Ω (d) 2020 Ω
**Ans: (a)** — Rm = 0.1/10m = 10 Ω; m = 200; Rse = (200−1)×10 = 1990 Ω.
**Concept:** Multiplier Rse = (m−1)Rm.
**Twist:** 50 V range, 10 mA/0.1 V meter → Rse = 4990 Ω. | 10 V range → 990 Ω.

**Q96 (TSNPDCL-22):** R1 = (100 ± 2%) Ω and R2 = (400 ± 5%) Ω. The maximum range of error of the series combination (R1 + R2) is:
(a) 13 Ω (b) 20 Ω (c) 22 Ω (d) 24 Ω
**Ans: (c)** — ΔR1 = 2, ΔR2 = 20; total 22 Ω.
**Concept:** Series error addition — absolute errors add.
**Twist:** Parallel → % errors add: 2%+5% of equivalent (80 Ω) = 5.6 Ω. | R1 ±1%, R2 ±2% → 1 + 8 = 9 Ω.

**Q97 (TSPSC-AEE-23):** An average-reading multi-meter reads 5 V when fed with a square wave symmetric about the time-axis. For the same input an rms-reading meter will read:
(a) 10 V (b) 5/√2 V (c) 5/√3 V (d) 5 V
**Ans: (d)** — Key marked (*); per solution: for a symmetric square wave the average and r.m.s. values are equal, so the r.m.s. meter reads 5 V.
**Concept:** Waveform response — square wave: r.m.s. = average (|avg| = peak).
**Twist:** Triangular wave → r.m.s. = 5/√3 ≈ 2.89 V. | Sine wave with avg-reading 5 V → r.m.s. = 1.11×5 = 5.55 V.

**Q98 (TSPSC-AEE-23):** An ammeter has range 0–10 A with internal resistance 0.1 Ω. To increase its range to 0–30 A, add a resistance of:
(a) 0.1 Ω in shunt with the meter (b) 0.05 Ω in series with the meter (c) 0.1 Ω in series with the meter (d) 0.05 Ω in shunt with the meter
**Ans: (d)** — m = 3; Rsh = 0.1/2 = 0.05 Ω in parallel (shunt).
**Concept:** Shunt for ammeter range extension — Rsh = Rm/(m−1), parallel.
**Twist:** 0–50 A from 0–10 A, Rm = 0.1 → Rsh = 0.025 Ω. | Series resistance would reduce range, never extend an ammeter.

**Q99 (TSSPDCL-AE-2023):** A PMMC meter (range 0–2.5 mA) with switch S opened swings to 1 mA and settles at 0.8 mA. The meter is:
(a) Under damped with a coil resistance of 0.5 kΩ (b) Under damped with a coil resistance of 0.25 kΩ (c) Critically damped with a coil resistance of 0.25 kΩ (d) Over damped with a coil resistance of 0.5 kΩ
**Ans: (a)** — Overshoot (1 mA then 0.8 mA) ⇒ under-damped; Rc = 2/0.8m − 2k = 0.5 kΩ.
**Concept:** Damping classification — overshoot ⇒ under-damped; meter resistance from steady current.
**Twist:** No overshoot, exact settle → critically damped. | Slow crawl to final → over-damped.

**Q100 (TSSPDCL-AE-2023):** A d.c. current superimposed with a.c. measured with a moving coil meter reads 20 A; a moving iron meter reads 25 A. The current can be expressed as:
(a) i = 20 + 25sin(ωt) (b) i = 20√2 + 15 sin(ωt) (c) i = 20√2 + 15√2 sin(ωt) (d) i = 20 + 15√2 sin(ωt)
**Ans: (d)** — MC reads d.c. = 20 A; MI reads √(20² + (Im/√2)²) = 25 ⇒ Im = 15√2 A.
**Concept:** MC = d.c. only; MI = r.m.s. of d.c. + a.c. = √(Idc² + Iac,rms²).
**Twist:** MI reads 26.9 A → Im = 18√2 A. | Pure a.c. (no d.c.) → MC reads 0.

**Q101 (TSPSC-AEE-23):** Which pair of 'Meter type – Major uses' is correct? I. Moving iron – indicator-type applications; II. Electrostatic – most widely used for d.c. current/voltage/resistance in low/medium impedance; III. Electrodynamometer – precise a.c. current/voltage at power frequencies.
(a) I, II and III (b) I and II only (c) I and III only (d) II and III only
**Ans: (c)** — II is wrong: electrostatic is used for very high voltages, not d.c. measurement in low/medium impedance.
**Concept:** Meter applications — MI for indicators, dynamometer for precise a.c., electrostatic for high voltage.
**Twist:** "Electrostatic for kV measurement" → correct. | "MI for precision" → false.

**Q102 (TSPSC-AEE-23):** Which statements are correct? I. PMMC meter is used for measurement of A.C. voltage only. II. Thermocouple is majorly used for measurement of Radio frequency A.C. signals. III. Rectifier is widely used for medium sensitivity service type voltage measurements in medium impedance circuits.
(a) II and III only (b) I and II only (c) I, II and III (d) I and III only
**Ans: (a)** — I is wrong: PMMC measures d.c. only.
**Concept:** PMMC = d.c.; thermocouple = r.f.; rectifier meter = medium-sensitivity a.c. voltmeter.
**Twist:** "PMMC used for a.c." → false. | "Rectifier for high sensitivity a.c." → marginal (moving iron/electrostatic).

**Q103 (TSPSC-AEE-23):** Find the multiplying power of a shunt of 200 Ω used with a galvanometer of 1600 Ω, and the shunt value to give a multiplying power of 80:
(a) 9, 20.2 Ω (b) 15, 18.5 Ω (c) 6, 52.5 Ω (d) 2, 10.2 Ω
**Ans: (a)** — m = 1 + Rm/Rsh = 1 + 1600/200 = 9; Rsh = 1600/79 ≈ 20.2 Ω.
**Concept:** Multiplying power m = 1 + Rm/Rsh; Rsh = Rm/(m−1).
**Twist:** Rsh = 100 Ω, Rm = 1600 Ω → m = 17. | m = 9, Rm = 1600 → Rsh = 200 Ω.

**Q104 (TSPSC-AEE-23):** The guaranteed accuracy of a 0–200 V voltmeter is 1 percent of full-scale. The instrument measures 40 V. The percentage limiting error is:
(a) 8 percent (b) 5 percent (c) 2 percent (d) 1 percent
**Ans: (b)** — LE = 1%×200 = 2 V; %LE = 2/40 × 100 = 5%.
**Concept:** % limiting error = (FSD error / true reading) × 100.
**Twist:** Measures 100 V → %LE = 2%. | 0–100 V meter, 1% FSD, at 25 V → 4%.

**Q105 (TSPSC-AEE-23):** A meter shows 118.35 V, the true voltage is 118.73 V. Determine the static error:
(a) 0.67 V (b) −0.38 V (c) 0.78 V (d) −0.07 V
**Ans: (b)** — Static error = Am − At = 118.35 − 118.73 = −0.38 V.
**Concept:** Static error = indicated − true (absolute error).
**Twist:** Meter 120.1 V, true 118.73 → +1.37 V. | Relative error = −0.38/118.73 = −0.32%.

**Q106 (TSPSC-AEE-23):** The manufacturer specified the inductance of an inductor as 5 mH ± 3 percent. Determine the limits within which the inductance is guaranteed:
(a) 4.5 to 5.5 mH (b) 3.85 to 5.15 mH (c) 4.85 to 5.15 mH (d) 3.5 to 5.8 mH
**Ans: (c)** — LE = 3%×5 = 0.15 mH; range = 5 ± 0.15 = 4.85 to 5.15 mH.
**Concept:** Specified ±% tolerance — absolute limits = value ± (%×value).
**Twist:** 10 mH ± 5% → 9.5 to 10.5 mH. | 5 mH ± 0.15 mH → 4.85 to 5.15 mH.

**Q107 (TSPSC-AEE-23):** A thermometer's calibration range is 130°C to 230°C, precision within ±0.35% of the instrument's range. The maximum static error is:
(a) ±0.35°C (b) ±0.15°C (c) ±0.01°C (d) ±0.05°C
**Ans: (a)** — Range = 100°C; error = 0.35%×100 = ±0.35°C.
**Concept:** % of span/range error — precision is % of full range (span).
**Twist:** Range 0–200°C, ±0.5% → ±1°C. | ±0.35% of reading at 150°C → ±0.525°C.

**Q108 (TSPSC-AEE-23):** Which statements are correct regarding standard deviation? I. The standard deviation of the mean is given by σm = σ/√(2n). II. For multiple sample data, the standard deviation of the standard deviation is σσ = σm/2.
(a) Only I (b) Both I and II (c) Only II (d) Neither I nor II
**Ans: (c)** — I is wrong (σm = σ/√n); per OHM key only II is correct.
**Concept:** Statistics of measurements — standard deviation of mean σm = σ/√n.
**Twist:** σm = σ/√n (correct form) → for σ = 4, n = 16 → σm = 1. | σ of σ = σ/√(2n).

**Q109 (TSGenco-24):** An alternating current is measured by a rectifier and hot wire ammeter; readings are 31 A and 33 A respectively. The form factor of the current wave is:
(a) 1.064 (b) 1.11 (c) 1.0 (d) 0.9393
**Ans: (a)** — Rectifier (avg) = 31 A; hot-wire (r.m.s.) = 33 A; FF = 33/31 = 1.064.
**Concept:** Form factor = r.m.s./average.
**Twist:** Rectifier 10 A, hot-wire 11.1 A → FF = 1.11 (sine). | Average 20, r.m.s. 25 → FF = 1.25 (triangular ~1.155/other).

**Q110 (TSGenco-24):** The maximum length of a machine language instruction for the 8086 microprocessor is:
(a) 2 bytes (b) 4 bytes (c) 6 bytes (d) 5 bytes
**Ans: (c)** — 8086 instructions can be up to 6 bytes long.
**Concept:** (Microprocessor, not measurements) — 8086 instruction length max 6 bytes.
**Twist:** 8085 → max 3 bytes. | 8086 MOV with memory+segment+offset → up to 6 bytes.

## Unit 2: Measurement of Power & Energy (64 Qs)

**Q1 (EPDCL-10):** Operating magnetic field flux density in an electrodynamometer instrument is typically about
(a) 1 Wb/m² (b) 0.5 Wb/m² (c) 0.05 Wb/m² (d) 0.005 Wb/m²
**Ans: (d)** — Flux density ≈ 0.005 Wb/m² (air-cored, no iron).
**Concept:** Electrodynamometer operating field flux density.
**Twist:** PMMC air-gap flux density ~0.5 Wb/m² (high, iron-cored) → electrodynamometer low because coils are air-cored to be linear.

**Q2 (EPDCL-10):** In a single-phase induction meter, to get true value of energy the shunt flux should lag the applied voltage by
(a) 0° (b) 45° (c) 90° (d) 180°
**Ans: (c)** — With Δ = 90°, error e = VI[sin(90−φ) − cosφ] = 0.
**Concept:** Energy-meter phase-angle error; shunt (pressure-coil) flux must lag V by exactly 90°.
**Twist:** If shunt coil is purely resistive (Δ = 0°), error e = VI[sin(−φ) − cosφ], large → wrong energy. Pressure coil must be inductive.

**Q3 (SSC-JE-10):** Laboratory wattmeters are
(a) Induction type (b) Moving iron type (c) Electrostatic type (d) Electro-dynamometer type
**Ans: (d)** — Electrodynamometer wattmeters are used as laboratory wattmeters (work on both AC & DC).
**Concept:** Choice of wattmeter for lab use.
**Twist:** Induction wattmeter is used in 3-φ AC only (no DC response) → electrodynamometer is preferred for lab since it reads AC and DC.

**Q4 (SSC-JE-11):** In two-wattmeter method on a balanced 3-φ load, if both wattmeters read the same, the power factor is
(a) 0.5 lagging (b) less than 0.5 lagging (c) unity (d) greater than 0.5 lagging
**Ans: (c)** — W1 = W2 ⇒ φ = 0° ⇒ cosφ = 1 (unity).
**Concept:** Two-wattmeter: tanφ = √3(W1−W2)/(W1+W2); W1=W2 → PF = 1.
**Twist:** W2 = 0 → PF = 0.5. W1 = −W2 → PF = 0. W1 > W2 (both +ve) → PF > 0.5.

**Q5 (SSC-JE-11):** For use in AC, the potential coil circuit of an electrodynamic wattmeter should be purely
(a) resistive (b) inductive (c) capacitive (d) reactive
**Ans: (a)** — High-resistance potential coil reduces phase (inductance) error.
**Concept:** Wattmeter pressure coil should be resistive (high R); energy-meter pressure coil should be inductive.
**Twist:** Energy meter pressure coil → inductive (lag ~90°) → correct integration. Wattmeter PC → resistive → low phase error.

**Q6 (SSC-JE-11):** Ratio of two wattmeter readings (balanced 3-φ) is 2:1. Power factor of the load is
(a) 0.866 lag (b) 0.866 lead (c) 0.866 lag or lead (d) none of the above
**Ans: (a)** — tanφ = √3(2−1)/(2+1) = 1/√3 ⇒ φ = 30° ⇒ PF = 0.866 lagging.
**Concept:** PF from two-wattmeter ratio, tanφ = √3(W1−W2)/(W1+W2).
**Twist:** If ratio 1:2 (W1 < W2) → φ = −30° → 0.866 leading. Equal readings → PF = 1.

**Q7 (SSC-JE-11):** Material for a heating element of a furnace working up to ~1500°C
(a) eureka (b) kanthal (c) platinum molybdenum carbon compound (d) nichrome
**Ans: (c)** — Platinum/molybdenum/carbon compound withstands ~1500°C.
**Concept:** Heating-element material selection by temperature.
**Twist:** Nichrome ~1100°C, kanthal ~1350°C → for 1500°C use Pt/Mo/C compound.

**Q8 (Transco-11):** In a dynamometer wattmeter, the moving coil is the
(a) current coil (b) low p.f. coil (c) potential coil (d) compensating coil
**Ans: (c)** — Moving coil = potential (pressure) coil; fixed coil = current coil.
**Concept:** Dynamometer wattmeter coil roles.
**Twist:** Fixed coil is current coil (series); in low-PF wattmeter an extra compensating coil cancels PC current error.

**Q9 (APSPDCL-12):** In two-wattmeter method, when power factor is 0.5
(a) readings equal & positive (b) readings equal & opposite (c) total power measured by only one wattmeter (d) readings unequal & positive
**Ans: (c)** — At PF = 0.5 (φ = 60°), W2 = 0, W1 measures total power.
**Concept:** Two-wattmeter table: φ=60° → W2 = 0.
**Twist:** PF = 1 → W1 = W2; PF = 0.866 → W1 = 2W2; PF = 0 → W1 = −W2.

**Q10 (APSPDCL-12):** Wattmeter measuring reactive power in 3-φ (400 V, 15 A) reads zero. Power factor of circuit is
(a) zero (b) 0.6 (c) 0.8 (d) unity
**Ans: (d)** — Q = √3 VI sinφ = 0 ⇒ sinφ = 0 ⇒ cosφ = 1.
**Concept:** Reactive-power measurement (Q = √3Vph Iph sinφ); Q=0 → PF=1.
**Twist:** If Q is maximum (not zero) → sinφ = 1 → PF = 0 (purely reactive load).

**Q11 (APSPDCL-12):** P = √3 VL IL cosφ in a 3-φ circuit, where φ is the angle between
(a) line voltage & line current (b) line voltage & phase current (c) phase voltage & line current (d) phase voltage & phase current
**Ans: (d)** — P = √3 VL IL cosφ = 3 Vph Iph cosφ, φ between phase V and phase I.
**Concept:** 3-φ power equation angle definition.
**Twist:** In two-wattmeter method each wattmeter uses VL IL cos(30 ∓ φ) — different angle reference.

**Q12 (APSPDCL-12):** No PF meter available; PF of a load is determined using
(a) a wattmeter (b) a voltmeter and ammeter (c) a voltmeter, ammeter and wattmeter (d) a kWh meter
**Ans: (c)** — cosφ = P/(√3 VL IL) needs V, I and P meters.
**Concept:** PF measurement from V, I, W.
**Twist:** With just a wattmeter alone PF can't be found (needs V, I). With a kWh meter alone also cannot.

**Q13 (HMWS-12):** Electrolytic meter is basically a/an
(a) dc ampere-hour meter (b) dc watt-hour meter (c) ac energy meter (d) ac ampere-hour meter
**Ans: (a)** — Electrolytic meter is a dc ampere-hour meter.
**Concept:** Electrolytic (coulomb) meter type.
**Twist:** It integrates current (ampere-hours), not power (has no voltage term) → not a true energy meter.

**Q14 (HMWS-12):** Instrument whose deflection θ ∝ I²(dM/dθ) is known as
(a) electrodynamometer (b) repulsion type (c) electrostatic type (d) attraction type
**Ans: (a)** — Td = I² dM/dθ is the electrodynamometer torque equation.
**Concept:** Deflection equation of electrodynamometer.
**Twist:** Moving-iron attraction/repulsion: Td ∝ I² (inductance change with flux path). Electrodynamometer has the dM/dθ term.

**Q15 (HMWS-12):** Wattmeter coils 0.01 Ω & 1000 Ω, load 20 A at 30 V. Connecting the voltage coil one way gives an error of
(a) 0.1% too high (b) 0.2% too high (c) 0.15% too high (d) zero
**Ans: (c)** — PC loss = V²/Rp = 30²/1000 = 0.9 W; true = 600 W; error = 0.9/600 = 0.15% high.
**Concept:** Wattmeter connection error (pressure-coil on load side adds PC loss to reading).
**Twist:** PC on supply side (load-side short) → current-coil drop error, reading differs → error sign/amount changes.

**Q16 (Transco-12):** Minimum number of wattmeters to measure 3-φ, 3-wire balanced/unbalanced power is
(a) 1 (b) 2 (c) 3 (d) 4
**Ans: (b)** — 3-φ 3-wire needs 2 wattmeters (Blondel).
**Concept:** Blondel's theorem.
**Twist:** 3-φ 4-wire unbalanced → 3 wattmeters; balanced 3-φ 4-wire → 1 wattmeter.

**Q17 (Transco-12):** Wattmeter (figure: CC in line, PC across Z2, Z1 & Z2 in series across supply) reads
(a) zero always (b) total power of Z1 & Z2 (c) power of Z1 (d) power of Z2
**Ans: (d)** — PC is across Z2, so wattmeter reads power consumed by Z2.
**Concept:** Wattmeter reads the power of the element across its potential coil.
**Twist:** If PC connected across the supply (Z1+Z2) → reads total power; PC across Z1 → reads Z1 power.

**Q18 (SSC-JC-12):** In phantom loading, energy consumption in calibration test of wattmeter is reduced because of
(a) no common point between the two coils (b) reduced loss in current & pressure coils (c) absence of load in the test set (d) separate application of low voltage supply across current coil
**Ans: (d)** — Rated current is injected at low voltage through the CC, so power is small.
**Concept:** Phantom loading principle.
**Twist:** Useful when meter rated current is large and actual-load power would be wasteful.

**Q19 (SSC-JE-12):** In two-wattmeter method on balanced 3-φ, if both wattmeters read equal, power factor is
(a) unity (b) 0.8 lagging (c) 0.8 leading (d) zero
**Ans: (a)** — W1 = W2 ⇒ φ = 0° ⇒ PF = 1.
**Concept:** Two-wattmeter: W1=W2 → PF = 1.
**Twist:** W2 = 0 → PF = 0.5; W1 = −W2 → PF = 0.

**Q20 (SSC-JE-12):** The household energy meter is a/an
(a) recording instrument (b) indicating instrument (c) integrating instrument (d) none of these
**Ans: (c)** — Energy meter integrates power over time (induction type).
**Concept:** Integrating vs indicating instrument.
**Twist:** Ammeter/voltmeter are indicating; chart recorders are recording; energy meter integrates.

**Q21 (SSC-JE-13):** Balanced 3-φ 3-wire star resistors; one resistor disconnected. Percentage reduction in load is
(a) 33.33 (b) 50 (c) 66.67 (d) 75
**Ans: (b)** — P = V²/R; one resistor open → V²/2R → power halves → 50% reduction.
**Concept:** Effect of an open phase in balanced star load.
**Twist:** If two resistors open (only one resistor on line-to-line) → P = V²/R same as star? Different loading → reduction changes.

**Q22 (SSC-JE-13):** Phasor diagram of V, IP (pressure coil current lagging V by β) and IC (lagging V by ψ); electrodynamic wattmeter reading is proportional to
(a) cos(β+ψ) (b) cosψ (c) cosβ·cosψ (d) cosβ·cos(β+ψ)
**Ans: (c)** — WM ∝ cosβ·cosψ (derived from Td ∝ I1 I2 cosψ and PC impedance angle β).
**Concept:** Wattmeter reading with inductive pressure coil.
**Twist:** If PC purely resistive (β = 0°) → reading ∝ cosψ (ideal).

**Q23 (SSC-JE-13):** To maximize driving torque in an induction-type instrument, flux of shunt and series coils should be
(a) in phase (b) in quadrature (c) displaced 45° (d) out of phase
**Ans: (b)** — Td ∝ Φ1m Φ2m sinθ, max when θ = 90° (quadrature).
**Concept:** Induction-instrument torque condition.
**Twist:** If the fluxes are in phase (θ=0) → torque zero.

**Q24 (SSC-JE-13):** Balanced 3-φ, line current 12 A; two-wattmeter: one reads 11 kW, other zero. Power factor is
(a) 0 (b) 0.5 (c) 0.866 (d) 1.0
**Ans: (b)** — W2 = 0 ⇒ φ = 60° ⇒ PF = 0.5.
**Concept:** Two-wattmeter: W2 = 0 → PF = 0.5.
**Twist:** W1 = −W2 → PF = 0; W1 = 2W2 → PF = 0.866; W1 = W2 → PF = 1.

**Q25 (EPDCL-14):** 5 A, 220 V energy meter (600 rev/kWh) makes 60 rev in 360 s at UPF. Error in energy recorded is
(a) 0.02 kWh (b) 0.05 kWh (c) 0.01 kWh (d) 0.1 kWh
**Ans: (c)** — Measured = 60/600 = 0.1 kWh; true = 220×5×360/3.6×10⁶ = 0.11 kWh; error = 0.01 kWh.
**Concept:** Energy-meter constant and error.
**Twist:** Meter reads fast (under-records 0.01 kWh per 0.1) → multiply by ratio for corrected energy.

**Q26 (APSPDCL-14):** In two-wattmeter method, one wattmeter reads negative. It may be concluded the pf is
(a) zero (b) 0.5 (c) less than 0.5 (d) greater than 0.5
**Ans: (c)** — Negative reading ⇒ φ > 60° ⇒ PF < 0.5.
**Concept:** Two-wattmeter sign of readings.
**Twist:** W2 = 0 → PF = 0.5; W1 = −W2 → PF = 0 (purely reactive).

**Q27 (ISRO-14):** 230 V, 50 Hz energy meter, load 20 A for 2 h at UPF, 1380 rev. Meter constant is
(a) 695 rev/kWh (b) 150 rev/kWh (c) 0.15 rev/kWh (d) 1/150 rev/kWh
**Ans: (b)** — Energy = 230×20×2/1000 = 9.2 kWh; K = 1380/9.2 = 150 rev/kWh.
**Concept:** Meter constant K = N/E.
**Twist:** If load is for 1 h, energy = 4.6 kWh → rev = 150×4.6 = 690 rev.

**Q28 (ISRO-14):** Two-wattmeter method on pure inductive balanced 3-φ load:
(a) both read same value opposite signs (b) both read zero (c) both read same value same sign (d) one reads zero, other non-zero
**Ans: (a)** — φ = 90°, W1 = −W2 (equal & opposite).
**Concept:** Two-wattmeter on purely reactive load.
**Twist:** Pure capacitive also gives equal & opposite readings; balanced resistive → equal positive.

**Q29 (SSC-JE-S1-14):** Least number of 1-φ wattmeters for total power of unbalanced load on 3-φ 4-wire system
(a) 1 (b) 2 (c) 3 (d) 4
**Ans: (c)** — Unbalanced 3-φ 4-wire → 3 wattmeters.
**Concept:** Blondel's theorem.
**Twist:** Balanced 3-φ 4-wire → 1 wattmeter; 3-wire (balanced/unbalanced) → 2 wattmeters.

**Q30 (SSC-JE-S2-14):** Two holes drilled in the energy-meter disc on a diameter are to
(a) increase ventilation (b) reduce disc weight (c) eliminate creeping on no-load (d) increase deflecting torque
**Ans: (c)** — Holes on the diameter prevent creeping (continuous rotation on no-load).
**Concept:** Creep prevention.
**Twist:** Creep occurs when only PC is energized; two opposite holes stop slow rotation.

**Q31 (SSC-JE-S2-14):** In moving iron instruments, the iron moves in a direction to cause
(a) coil inductance constant (b) mutual inductance minimum (c) minimum reluctance path (d) decrease in flux through it
**Ans: (c)** — MI works on minimum reluctance principle.
**Concept:** Moving-iron operating principle.
**Twist:** Attraction type: iron pulled in to increase flux (min reluctance); repulsion type works by repulsion between two vanes.

**Q32 (HMWS-15):** Minimum number of wattmeters to measure 3-φ power is
(a) 0 (b) 2 (c) 4 (d) 3
**Ans: (b)** — 2 wattmeters minimum for 3-φ power.
**Concept:** Minimum wattmeter count (Blondel).
**Twist:** 3-φ 4-wire unbalanced → 3; 3-φ 3-wire → 2.

**Q33 (HMWS-15):** In two-wattmeter method at unity power factor, W1 and W2 are such that
(a) W1 or W2 = 0 (b) W1 < W2 (c) W1 = W2 (d) W1 > W2
**Ans: (c)** — φ = 0° ⇒ W1 = W2 = (√3/2) VL IL.
**Concept:** Two-wattmeter at PF = 1.
**Twist:** PF = 0.866 → W1 = 2W2; PF = 0.5 → W2 = 0; PF = 0 → W1 = −W2.

**Q34 (HMWS-15):** Compensating winding in a dynamometer wattmeter neutralizes error due to
(a) voltage in pressure coil circuit (b) power loss in pressure coil circuit (c) current in current coil circuit (d) power loss in current coil circuit
**Ans: (b)** — Compensating winding cancels the power loss in the pressure coil circuit.
**Concept:** Compensating coil of wattmeter.
**Twist:** Without it, PC current adds to CC current causing over-registration; winding carries PC current in opposite direction.

**Q35 (TS Transco-15):** Electrodynamometer wattmeter (figure: CC in line I1, PC across other lines) in 3-φ balanced load; E, I are phase values, φ phase angle. Wattmeter reading is
(a) proportional to EI sinφ (b) proportional to EI cosφ (c) proportional to EI tanφ (d) zero
**Ans: (a)** — This connection measures reactive power Q = √3 VI sinφ ∝ EI sinφ.
**Concept:** Reactive-power measurement with a single wattmeter.
**Twist:** Same wattmeter reconnected normally (PC across line-neutral) → measures active power ∝ EI cosφ.

**Q36 (TSSPDCL-15):** 3-φ, 400 V balanced star load, 2.5 A; lower of two positive wattmeter readings is 707 W. Power factor is
(a) cos(π/4) (b) cos(π/6) (c) cos(π/8) (d) cos(π/12)
**Ans: (d)** — W2 = 1000 cos(30+φ) = 707 ⇒ 30+φ = 45° ⇒ φ = 15° = π/12.
**Concept:** Two-wattmeter with given lower reading.
**Twist:** If both readings equal → φ = 0° → PF = 1; if lower reading = 0 → PF = 0.5.

**Q37 (TSSPDCL-15):** Creep in a 1-φ energy meter occurs when ___ is energized, mainly due to ___ for friction.
(a) current-coil … over-compensation (b) pressure-coil … over-compensation (c) pressure-coil … under-compensation (d) current-coil … under-compensation
**Ans: (b)** — Creep: PC energized with no load; over-compensation drives disc for friction.
**Concept:** Creeping cause.
**Twist:** Remedy is two holes on the disc diameter (opposite sides) → eliminates slow rotation.

**Q38 (AP Transco-17):** Phantom loading for testing of energy meter is used
(a) to isolate current & potential circuits (b) to increase power loss during testing (c) for meters having low current ratings (d) to test meters having a large current rating for which loads may not be available
**Ans: (d)** — Phantom loading tests high-current meters without drawing real load.
**Concept:** Phantom loading purpose.
**Twist:** PC gets rated voltage at low current; CC gets rated current at low voltage → small test power.

**Q39 (AP Transco-17):** 200 V, 5 A dc energy meter tested at marked ratings; pressure circuit 8000 Ω, current coil 0.1 Ω; current circuit excited by 6 V battery. Power consumed with phantom loading is
(a) 2.5 W (b) 5 W (c) 32.5 W (d) 35 W
**Ans: (d)** — CC: 6×5 = 30 W; PC: 200²/8000 = 5 W; total = 35 W.
**Concept:** Phantom loading power calculation.
**Twist:** If battery were 12 V → CC power 60 W, total 65 W; if PC connected to 400 V → 20 W.

**Q40 (AP Transco-17):** Two-wattmeter readings 8 kW and 4 kW on balanced 3-φ load. Power factor is
(a) zero (b) 0.5 (c) between zero & 0.5 (d) between 0.5 & unity
**Ans: (d)** — tanφ = √3(8−4)/(8+4) = 1/√3 ⇒ φ = 30° ⇒ PF = 0.866 (0.5 < 0.866 < 1).
**Concept:** Two-wattmeter PF computation.
**Twist:** Readings 8 & −4 kW → tanφ = √3(8+4)/(8−4) = 3√3 ⇒ φ ≈ 79° ⇒ PF ≈ 0.19 (< 0.5).

**Q41 (AP Genco-17):** PC of 1-φ dynamometer wattmeter has 4840 Ω, load 220 V, PC on load side, meter reads 100 W. Approximate % error due to connection is
(a) 11% (b) 9% (c) 1.1% (d) 3%
**Ans: (a)** — PC loss = 220²/4840 = 10 W; true = 90 W; error = (100−90)/90 × 100 ≈ 11%.
**Concept:** Wattmeter connection (PC on load side) error.
**Twist:** PC on supply side → current-coil drop subtracted, reading tends lower → error sign flips.

**Q42 (AP Genco-17):** Energy-meter disc makes 60 rev in 6 min; constant 1200 rev/kWh. Power consumption is
(a) 1.2 kW (b) 1 kW (c) 600 W (d) 500 W
**Ans: (d)** — Energy = 60/1200 = 0.05 kWh in 0.1 h ⇒ P = 0.5 kW = 500 W.
**Concept:** Energy-meter constant → power.
**Twist:** If 60 rev in 6 min at 600 rev/kWh → P = 1 kW; if 30 rev in 6 min at 1200 rev/kWh → 250 W.

**Q43 (TSSPDCL-18):** CT, bar primary, secondary 20 (marked 200) turns; magnetizing mmf 100 A, core-loss 50 A; pure resistive burden, 5 A secondary. Turns to reduce for zero ratio error
(a) 0 (b) 10 (c) 15 (d) 5
**Ans: (b)** — Actual ratio = n + (Ie cosδ + Im sinδ)/Is = 200 + 50/5 = 210; reduce 10 turns (210−200).
**Concept:** CT turns compensation / ratio error.
**Twist:** If loss component larger (100 A) → actual ratio 220 → reduce 20 turns; reactive burden (δ≠0) adds Im term.

**Q44 (TS Transco-18):** Ammeter 0.1 Ω across secondary of 400/5 A CT. CT burden is
(a) 0.5 VA (b) 2.5 VA (c) 5.0 VA (d) 25 VA
**Ans: (b)** — Burden = I²R = 5² × 0.1 = 2.5 VA.
**Concept:** CT burden (I² × impedance).
**Twist:** If ammeter 0.2 Ω → 5 VA; if 1 Ω → 25 VA.

**Q45 (AP EPDCL-19):** Two-wattmeter readings equal and opposite when
(a) load is purely inductive (b) power factor is unity (c) load is balanced (d) phase angle between 60° & 90°
**Ans: (a)** — φ = 90° (pure inductive) gives W1 = −W2.
**Concept:** Two-wattmeter equal-opposite condition.
**Twist:** Pure capacitive also gives equal & opposite; unity PF gives equal & positive.

**Q46 (AP EPDCL-19):** Power of an n-phase unbalanced circuit can be measured with minimum of
(a) (n−2) wattmeters (b) (n−1) wattmeters (c) n wattmeters (d) (n+1) wattmeters
**Ans: (b)** — Blondel: n-phase, no neutral → n−1 wattmeters.
**Concept:** Blondel's theorem.
**Twist:** If neutral is available → n wattmeters.

**Q47 (AP EPDCL-19):** In 1-φ induction energy meter, maximum torque is achieved when angle between two fluxes is
(a) 180° (b) 0° (c) 45° (d) 90°
**Ans: (d)** — Td ∝ sin(angle), maximum at 90°.
**Concept:** Energy-meter torque-angle relation.
**Twist:** Angle 0° → torque zero (no rotation); 180° → torque zero (sin180 = 0).

**Q48 (AP SPDCL-19):** Two-wattmeter method; one wattmeter reads negative. Inference about pf
(a) unity pf (b) pf > √3/2 (c) pf < 0.5 (d) pf > 0.5
**Ans: (c)** — Negative reading ⇒ φ > 60° ⇒ PF < 0.5.
**Concept:** Negative wattmeter reading → PF < 0.5.
**Twist:** One reads zero → PF = 0.5; both positive equal → PF = 1.

**Q49 (AP SPDCL-19):** Statements: 1) dynamometer as ammeter has square-law scale; 2) as wattmeter has uniform scale.
(a) only 1 true (b) only 2 true (c) neither true (d) both true
**Ans: (d)** — EDM ammeter: Td ∝ I² → square law; EDM wattmeter: θ ∝ Pavg → uniform scale.
**Concept:** Dynamometer scale laws.
**Twist:** MI ammeter also square-law; but wattmeter linear in P.

**Q50 (AP Transco-19):** 1-φ, 240 V induction energy meter, constant 600 rev/kWh; load 10 A at pf 0.8 lag. Disc speed in rpm
(a) 57.6 (b) 38.4 (c) 19.2 (d) 9.6
**Ans: (c)** — P = 240×10×0.8/1000 = 1.92 kW; 1 kW → 10 rpm ⇒ 19.2 rpm.
**Concept:** Disc speed ∝ power (meter constant).
**Twist:** At pf 1, P = 2.4 kW → 24 rpm; at 0.5 pf → 12 rpm.

**Q51 (HMWSSB-20):** Instruments used as transfer instruments in standardization of AC potentiometers
(a) Thermocouple & Electrodynamometer type (b) Rectifier type only (c) Thermocouple type only (d) Electrodynamometer only
**Ans: (a)** — Both thermocouple and electrodynamometer serve as transfer instruments.
**Concept:** Transfer instruments (AC→DC transfer).
**Twist:** Transfer instrument must read same for AC (rms) and DC → thermocouple & EDM qualify.

**Q52 (HMWSSB-20):** Energy meter disc makes 600 rev per unit; with 1 kW load disc rotates at 10.2 rpm. Load on for 12 h; units recorded as error
(a) 0.48 kWh (b) 0.96 kWh (c) 0.12 kWh (d) 0.24 kWh
**Ans: (d)** — Error = 0.2 rpm = 12 rev/h; 144 rev in 12 h = 144/600 = 0.24 kWh.
**Concept:** Energy-meter speed error.
**Twist:** If disc rotates 9.8 rpm (slow) → error = 0.2 rpm slow → −0.24 kWh (under-record).

**Q53 (HMWSSB-20):** Two-wattmeter method: pf if (i) readings equal, and (ii) readings equal and opposite
(a) zero and one (b) one and zero (c) 0.5 and zero (d) one and 0.866 lagging
**Ans: (b)** — Equal → PF = 1; equal-opposite → PF = 0.
**Concept:** Two-wattmeter reading relations.
**Twist:** W1 = 2W2 → PF = 0.866; W2 = 0 → PF = 0.5.

**Q54 (HMWSSB-20):** CT must never be operated on open circuit because
(i) core flux increases enormously (ii) eddy & hysteresis losses increase to large value (iii) very low voltage induced in multi-turn secondary (iv) eddy & hysteresis losses decrease
(a) (i),(iii),(iv) (b) (ii),(iii) (c) (i),(ii) (d) (i),(iii)
**Ans: (c)** — Open CT: flux rises hugely; core losses rise → heating, danger.
**Concept:** CT secondary must never be open.
**Twist:** PT secondary short-circuit is dangerous (opposite) → PT must never be shorted.

**Q55 (HMWSSB-20):** VA rating of a Potential Transformer is about
(a) 15 VA (b) 100 kVA (c) 100 VA (d) 2 kVA
**Ans: (c)** — PT burden rating ~100 VA.
**Concept:** Instrument transformer VA ratings.
**Twist:** CT burden also low VA (a few VA); both are instrument transformers not power transformers.

**Q56 (HMWSSB-20):** The two pressure coils of a single-phase dynamometer PF meter are connected:
(a) one in series with non-inductive R, other in parallel with inductive choke (b) one in series with non-inductive R, other in series with inductive choke (c) one in series with non-inductive R, other in series with capacitance (d) one in series with non-inductive R, other in parallel with capacitance
**Ans: (b)** — One coil in series with R (current in phase with V), other in series with choke (current lagging V by 90°).
**Concept:** Dynamometer power-factor meter construction.
**Twist:** Currents in two coils must be displaced by ~90° → correct deflection varies with φ.

**Q57 (TSSPDCL-22):** Errors in an instrument transformer can be reduced by
(a) using high reluctance core (b) using small cross-sectional area (c) using low permeability material (d) using low reluctance core
**Ans: (d)** — Low-reluctance core → low magnetizing current & losses → reduced ratio/phase errors.
**Concept:** Reducing instrument-transformer errors.
**Twist:** Keeping burden low and using turns compensation also reduce ratio error.

**Q58 (TSSPDCL-22):** Two-wattmeters on balanced delta load read W1 = 12 kW, W2 = 15 kW. If the same load is reconnected in star, wattmeters will read
(a) W1 = 5 kW, W2 = 4 kW (b) W1 = 4 kW, W2 = 5 kW (c) W1 = 6.93, W2 = 8.66 kW (d) W1 = 8.66, W2 = 6.93 kW
**Ans: (b)** — Total Δ power = 27 kW; star power = 27/3 = 9 kW → W1+W2 = 9, ratio 12:15 = 4:5 → 4 & 5 kW.
**Concept:** Δ→star power reduction (PΔ = 3P_Y).
**Twist:** If star reconnected to 400 V line (same), each phase voltage drops by √3 → power 1/3.

**Q59 (TSNPDCL-22):** In induction-type wattmeters, correct combination:
(a) series magnet excited by load current (b) series magnet excited by line voltage (c) shunt magnet excited by load voltage (d) shunt magnet excited by line voltage
**Ans: (a,d)** — Series magnet carries load current; shunt magnet across supply (line) voltage.
**Concept:** Induction wattmeter magnet excitations.
**Twist:** Swap them → torque ∝ V×I still but phase angle wrong → large error; correct connection essential.

**Q60 (TSNPDCL-22):** v = 100sinωt + 40cos(3ωt+30°) + 50sin(5ωt+30°); i = 8sinωt + 6cos(5ωt−120°). 1-φ wattmeter reading
(a) 950 W (b) 1100 W (c) 550 W (d) 475 W
**Ans: (d)** — Only same-frequency terms count: W = (100×8/2)cos0° + (50×6/2)cos60° = 400 + 75 = 475 W.
**Concept:** Wattmeter responds only to components of same frequency.
**Twist:** If 3rd-harmonic voltage present but no 3rd-harmonic current → contributes nothing. Change 5th-harmonic phase → cos term changes.

**Q61 (TSNPDCL-22):** 200 V, 10 A EDM wattmeter, 200 divisions; PC fed 200√2 sin(100πt), CC carries 5√2 cos(100πt−60°). Wattmeter reads
(a) between 86th & 87th divisions (b) between 173rd & 174th divisions (c) exactly 100th division (d) exactly 200th division
**Ans: (a)** — W = 200×5×cos30° = 866 W; fsd = 2000 W → 10 W/div → 86.6 div.
**Concept:** Wattmeter division reading.
**Twist:** At 60° phase (V=200, I=5): W = 500 W → 50th division.

**Q62 (TSPSC-AEE-23):** Dynamometer wattmeter used to measure power of a room heater. Correct option:
(a) cannot comment on relative currents (b) fixed coil current same as moving coil (c) fixed coil current more than moving coil (d) fixed coil current lower than moving coil
**Ans: (c)** — Fixed (CC) carries load current; moving (PC) current is tiny → I_fixed >> I_moving.
**Concept:** Dynamometer wattmeter coil currents.
**Twist:** For a dynamometer ammeter, fixed & moving carry same current (series) → I fixed = I moving.

**Q63 (TSSPDCL-AE-2023):** 3-φ wattmeter, |W1/W2| = 1.5, PC of second wattmeter had to be reversed. Angle φ between phase V & I is
(a) φ = tan⁻¹(5/3) (b) φ = cos⁻¹(5/2√7) (c) φ = cos⁻¹(1/2√19) (d) φ = tan⁻¹(3/5)
**Ans: (c)** — W2 reversed ⇒ tanφ = √3(W1+W2)/(W1−W2) = √3(1.5+1)/(1.5−1) = 5√3 ⇒ cosφ = 1/(2√19).
**Concept:** Two-wattmeter with reversed PC.
**Twist:** Without reversal tanφ = √3(W1−W2)/(W1+W2) = √3(0.5/2.5) = √3/5 → smaller φ.

**Q64 (TSGenco-24):** Correct statements for two-wattmeter method:
(i) equal readings if load pf angle 0° (ii) one reading negative if pf angle > 60° (iii) only one wattmeter reads total power if pf angle 30°
(a) (i) & (ii) (b) (ii) & (iii) (c) (iii) & (i) (d) (i),(ii) & (iii)
**Ans: (a)** — (i) true (equal at 0°); (ii) true (negative beyond 60°); (iii) false — at 30° W1 = 2W2, not one wattmeter only.
**Concept:** Two-wattmeter reading rules.
**Twist:** "Only one wattmeter reads total" is true at φ = 60° (W2 = 0), not at 30°.

## Unit 3: Bridge Measurement of R, L & C (54 Qs)

**Q1 (EPDCL-10):** Frequency can be measured by using
(a) Maxwell's bridge (b) Schering bridge (c) Hay's bridge (d) Wein's bridge
**Ans: (d)** — Wein's bridge is the standard bridge for unknown-frequency measurement.
**Concept:** Wein bridge frequency balance: f = 1/(2π√(R1R2C1C2)).
**Twist:** "Which bridge measures capacitance/DF" → Schering. "Which for high-Q coil inductance" → Hay.

**Q2 (EPDCL-10):** Maxwell's bridge is used for measurement of inductance of
(a) low Q coils (b) medium Q coils (c) high Q coils (d) low and medium Q coils
**Ans: (b)** — Maxwell's bridge is for medium-Q inductive coils.
**Concept:** Maxwell inductance-capacitance bridge → medium Q (Q < 10).
**Twist:** high-Q coil → Hay's bridge. Low-Q coil → Anderson's bridge.

**Q3 (EPDCL-10):** Wheatstone bridge is widely used for precision measurement of
(a) frequency (b) inductance (c) capacitance (d) resistance
**Ans: (d)** — Wheatstone bridge is the standard method for medium resistance (1 Ω–100 kΩ).
**Concept:** Wheatstone balance: P/Q = R/S → P·S = Q·R.
**Twist:** low resistance (<1 Ω) → Kelvin double bridge. High resistance (>100 kΩ) → Megger / loss-of-charge.

**Q4 (EPDCL-10):** A 53 Hz reed type frequency meter is polarized with dc. The new range of frequency meter is
(a) 106 Hz (b) 26.5 Hz (c) 53 Hz (d) 10.6 Hz
**Ans: (a)** — With dc polarization the electromagnet is energized every half cycle, doubling the frequency range (53×2 = 106 Hz).
**Concept:** Reed-type frequency meter → polarization doubles the effective frequency.
**Twist:** If the question asks new range when polarized with dc → 2×. If a 50 Hz meter is used on dc → 100 Hz.

**Q5 (SSC-JE-11):** A lossy capacitor with loss angle 0.01 radian draws 0.5 A at 1000 V. Active power consumed is
(a) 5 W (b) 10 W (c) 2 W (d) 1 W
**Ans: (a)** — P = V·I·sinδ = 1000 × 0.5 × 0.01 ≈ 5 W.
**Concept:** Lossy capacitor power = V·I·sinδ (δ small → sinδ ≈ δ).
**Twist:** If loss angle given in degrees, convert δ to rad/using sin. If asked for dielectric loss in Schering terms → ωCV²tanδ.

**Q6 (SSC-JE-11):** Measurement of _____ is affected by the presence of thermo-emf in the measuring circuit.
(a) high resistance (b) low resistance (c) capacitance (d) inductance
**Ans: (b)** — Thermo-emf errors arise in low-resistance measurement; Kelvin double bridge uses reversing/dual switches to cancel them.
**Concept:** Thermo-emf affects low-resistance measurement (Kelvin double bridge).
**Twist:** "How to eliminate thermo-emf error" → reverse current direction (dual switch). "Which bridge avoids thermo-emf" → Kelvin double bridge.

**Q7 (APSPDCL-12):** Swamping resistance is used in moving coil instruments to reduce error due to
(a) thermal EMF (b) temperature (c) power taken by instrument (d) galvanometer sensitivity
**Ans: (b)** — Swamping resistance (manganin/constantan) added in series reduces temperature errors.
**Concept:** Swamping resistance → temperature-coefficient compensation (manganin/constantan).
**Twist:** Swamping resistance material → manganin or constantan. "Swamping resistance added to coil circuit" (Q13) → reduce temperature error (b).

**Q8 (APSPDCL-12):** The dielectric loss of a capacitor can be measured by
(a) Wein bridge (b) Owen bridge (c) Schering bridge (d) Maxwell bridge
**Ans: (c)** — Schering bridge measures capacitance, dissipation factor and dielectric loss.
**Concept:** Schering bridge → capacitance / loss angle / dissipation factor (DF).
**Twist:** High-voltage Schering → insulation/loss angle of cables & capacitors. Dielectric loss in capacitor → Schering.

**Q9 (HMWS-12):** Megger indicates infinity when test terminals are open-circuited because
(a) no current flows through the current coil (b) no current flows through the pressure coil (c) no current flows through any of the coils (d) none of the above
**Ans: (a)** — With terminals open, the current coil carries no current, so the coil torques produce an "infinity" deflection.
**Concept:** Megger: current coil + pressure coil opposed torques; open circuit → current-coil torque zero → infinity reading.
**Twist:** Short-circuited test terminals → huge current through current coil → zero (short) reading. Megger speed → 160 rpm (Q25).

**Q10 (HMWS-12):** The most common and best bridge method for precise measurement of inductance over a wide range is
(a) Wheatstone (b) Hay's (c) Anderson (d) Wein
**Ans: (c)** — Anderson's bridge is most accurate for inductance measurement over a wide range.
**Concept:** Anderson bridge → precise/wide-range inductance measurement (low Q).
**Twist:** Self-inductance of a coil → Anderson's (Q37). Mutual inductance → Heaviside-Campbell.

**Q11 (HMWS-12):** Which of the following bridges is frequency sensitive?
(a) Wheatstone (b) Maxwell (c) Anderson (d) Wein
**Ans: (d)** — Wein's bridge is frequency sensitive (used for frequency measurement).
**Concept:** Wein bridge → frequency measurement (frequency-sensitive bridge).
**Twist:** Bridge for frequency + capacitance (Q26) → Wein. Harmonic distortion analyzer → Wein (Q46).

**Q12 (HMWS-12):** Wagner's earthing device is used in ac bridges for
(a) shielding the bridge elements (b) eliminating the stray electrostatic field effects (c) eliminating the effect of the earth capacitance (d) eliminating the effect of inter-component capacitances
**Ans: (c)** — Wagner's earth eliminates stray/earth capacitance between bridge arms and ground.
**Concept:** Wagner's earthing device → eliminates earth-capacitance (stray) effects in AC bridges.
**Twist:** Same device for eliminating earth-capacitance effects in an A.C bridge network (Q22) → (b) eliminate effect of earth capacitances. Note: it does NOT shield elements or eliminate magnetic-field effects.

**Q13 (HMWS-12):** Swamping resistance is added to the coil circuit
(a) to increase the sensitivity (b) to reduce the temperature error (c) to reduce the error due to thermal emf (d) to reduce the power drawn by the instrument
**Ans: (b)** — Swamping resistance reduces temperature error (series manganin resistance).
**Concept:** Swamping resistance → temperature-error reduction.
**Twist:** Material used for swamping → manganin/constantan. Function is temperature compensation, NOT thermal-emf (that's reversing switch) or sensitivity.

**Q14 (HMWS-12):** For the measurement of insulation resistance of machines and cables, the following method is used
(a) Megger method (b) Carey Foster bridge method (c) Potentiometer method (d) Ammeter voltmeter method
**Ans: (a)** — Megger is used for high (insulation) resistance of machines and cables.
**Concept:** Megger → insulation/high resistance (>100 kΩ).
**Twist:** High resistance measured by → Megger, loss-of-charge, mega-ohm bridge. Low resistance → Kelvin double bridge.

**Q15 (Transco-12):** R1 and R4 are opposite arms of a Wheatstone bridge as are R3 and R2; source applied across R1 and R3. Under balance,
(a) R1 = R3R4/R2 (b) R1 = R2R3/R4 (c) R1 = R2R4/R3 (d) R1 = R2+R3+R4
**Ans: (b)** — Product of opposite arms equal: R1R4 = R2R3 → R1 = R2R3/R4.
**Concept:** Wheatstone balance: P·Q' = R·S (opposite-arm products equal); solve for unknown.
**Twist:** Given R1=50, R2=65, R3=100 with ±0.5% → Rx = 65×100/50 = 130 ± 1.5% (Q52 → 128.05–131.95). Rearranged balance for another arm.

**Q16 (Transco-12):** A dc potentiometer (2 V, 800 mm slide wire) balances a 1.18 V standard cell at 600 mm; a test cell balances at 680 mm. Its emf is
(a) 1.00 V (b) 1.34 V (c) 1.50 V (d) 1.70 V
**Ans: (b)** — Working current Iw = 1.18/600 = 1.967 mA/mm → V = 680 × 1.967e-3 = 1.34 V.
**Concept:** Slide-wire potentiometer: E ∝ balance length (linear).
**Twist:** If test balances shorter than standard → smaller emf. If slide wire fully 800 mm → 2 V full scale. Compare lengths ratio: 1.18×680/600.

**Q17 (SSC-JE-13):** To minimize errors due to lead contact resistances, low resistances used in electrical measurement are provided with
(a) guard rings (b) four terminals (c) thick insulation (d) metal shields
**Ans: (b)** — Low resistances use four terminals (2 current + 2 voltage) to eliminate lead-contact errors.
**Concept:** Kelvin 4-terminal measurement: current terminals 1–2, voltage terminals 3–4.
**Twist:** Guard terminal (high-resistance guard) → bypasses leakage current (Q42). Guard rings → for insulation/electrostatic shielding.

**Q18 (SSC-JE-13):** Ammeter with copper Rm, Rsh and manganin Rs, Rx. Condition for temperature-compensated performance is
(a) 1/Rm + 1/Rsh = 1/Rs + 1/Rx (b) Rm·Rs = Rsh·Rx (c) Rm+Rs = Rsh+Rx (d) Rm·Rsh = Rs·Rx
**Ans: (d)** — Cross-product condition Rm·Rsh = Rs·Rx makes the copper/manganin temperature effects cancel.
**Concept:** Temperature-compensation balance: equal relative temperature-coefficient ratios across arms.
**Twist:** Which material pair cancels temperature error → copper vs manganin (manganin has ~zero temp coeff). Swamping resistance instead of matching ratios → temperature error reduction.

**Q19 (EPDCL-14):** The bridge network commonly employed for measurement of very low resistance is
(a) Carey Foster's bridge (b) Wheatstone bridge (c) Kelvin's double bridge (d) Schering bridge
**Ans: (c)** — Kelvin double bridge measures micro-ohm to milli-ohm (low) resistance.
**Concept:** Kelvin double bridge → low resistance (micro-Ω–mΩ), 4-terminal.
**Twist:** Accurate measurement of very low resistances (Q38) → Kelvin double bridge. Very low resistance lead errors → four terminals.

**Q20 (EPDCL-14):** The bridge network employed for measurement of mutual inductance is
(a) Wein's bridge (b) Owen's bridge (c) Anderson's bridge (d) Heaviside Campbell bridge
**Ans: (d)** — Heaviside-Campbell bridge measures mutual inductance.
**Concept:** Heaviside-Campbell → mutual inductance; Owen → incremental inductance.
**Twist:** Self-inductance in terms of capacitance → Owen. Mutual inductance in terms of standard capacitance → Campbell. Mutual inductance question in statement list (Q53): Campbell measures self-inductance in terms of mutual inductance.

**Q21 (EPDCL-14):** Bridge arms ZAB = 100∠30°, ZBC = 100∠−30°, ZCD = 50∠−60°, unknown ZDA. Then ZDA =
(a) 50∠0° Ω (b) 100∠0° Ω (c) 50∠−120° Ω (d) 200∠60° Ω
**Ans: (a)** — Balance: ZAB·ZCD = ZBC·ZDA → ZDA = (100∠30° × 50∠−60°)/(100∠−30°) = 50∠0° Ω.
**Concept:** AC bridge balance: product of opposite impedances equal (magnitudes and angles).
**Twist:** Swap which two arms are known → recompute ZDA. Angles add on one side, subtract on other — check ∠ sum: 30 + (−60) = −30 → ZDA angle 0°.

**Q22 (EPDCL-14):** Wagner's earthing device is employed in A.C bridge network to
(a) shield the bridge elements (b) eliminate the effect of earth capacitances (c) eliminate the effect of stray magnetic field (d) eliminate the effect of stray electric fields
**Ans: (b)** — Wagner's earth eliminates earth-capacitance effects in AC bridges.
**Concept:** Wagner's earthing device → eliminate earth-capacitance effect.
**Twist:** Same device also stated as eliminating stray/earth capacitance (Q12) → (c). Not used for magnetic-field or shielding purposes.

**Q23 (APSPDCL-14):** The Hay's bridge is used for measuring
(a) the inductance of high-Q coils (b) the inductance of low-Q coils (c) the frequency of the source (d) the capacitance
**Ans: (a)** — Hay's bridge measures inductance of high-Q coils (Q > 10).
**Concept:** Hay bridge → high-Q inductance (resistance in series with standard capacitor).
**Twist:** High-quality-factor inductor (Q35) → Hay's. Statement list (Q53): Hay's for Q>10, so "Q less than 10" is false.

**Q24 (SSC-JE-S1-14):** Wheatstone bridge ratio arms 1000 Ω and 100 Ω; standard arm 4-decade boxes (1000, 100, 10, 1 Ω). Max and min unknown resistance determinable are
(a) 111100 Ω, 1 Ω (b) 11110 Ω, 10 Ω (c) 10000 Ω, 10 Ω (d) 111100 Ω, 10 Ω
**Ans: (d)** — Max standard = 11110 Ω → Rx(max) = 11110×1000/100 = 111100 Ω; min standard = 1 Ω → Rx(min) = 1×10 = 10 Ω.
**Concept:** Wheatstone range: Rx = standard × (1000/100) ratio = ×10; standard range 1–11110 Ω.
**Twist:** If ratio arm reversed (100/1000) → divide by 10 instead. If 5-decade boxes → larger range. Watch that the 4-decade max is 11110, not 10000.

**Q25 (SSC-JE-S1-14):** Speed of the megger is kept at
(a) 100 rpm (b) 120 rpm (c) 140 rpm (d) 160 rpm
**Ans: (d)** — Hand-driven megger generator is rotated at 160 rpm.
**Concept:** Megger drive speed = 160 rpm (hand generator producing 500–1000 V).
**Twist:** Megger output voltage order → 500–1000 V. If megger open-circuit → infinity (Q9). Megger test on cables → short galvanometer due to charging current.

**Q26 (SSC-JE-S1-14):** Which bridge is generally used for measurement of frequency and also capacitance?
(a) Hay's bridge (b) Owen's bridge (c) Schering bridge (d) Wein's bridge
**Ans: (d)** — Wein's bridge measures frequency (and is a frequency-selective bridge).
**Concept:** Wein bridge → frequency measurement.
**Twist:** "Bridge for frequency" (Q41, Q45, Q49) → Wien. "Capacitance measurement" strictly → Schering. Note the examiner pairs frequency with capacitance → Wien (source answer).

**Q27 (SSC-JE-S2-14):** The AC bridge used for measurement of dielectric loss of capacitor is
(a) Anderson bridge (b) Schering bridge (c) Wien bridge (d) Hay's bridge
**Ans: (b)** — Schering bridge measures dielectric loss (V²ωC·tanδ) of capacitors.
**Concept:** Schering bridge → dielectric loss, capacitance, dissipation factor.
**Twist:** Dielectric loss best measured (Q39) → Schering. High-voltage Schering → loss angle of capacitor (Q40).

**Q28 (SSC-JE-S2-14):** Resistance measured by ammeter-voltmeter; voltmeter reads 200 V (internal 2 kΩ), ammeter 2 A. Then R =
(a) 105.3 Ω (b) 100.0 Ω (c) 95.3 Ω (d) 90.3 Ω
**Ans: (a)** — Rtrue = 200/2 = 100 = Rmeas ∥ 2k → Rmeas = 105.3 Ω.
**Concept:** Voltmeter-in-parallel connection: measured value = R∥Rv, so true R is higher than V/I reading.
**Twist:** Ammeter-in-series (before voltmeter) connection → measured R = R + shunt error (R + Ra). If voltmeter internal resistance much larger than R → error negligible.

**Q29 (HMWS-15):** Schering bridge is used to
(a) measure mutual inductance (b) determine inductance (c) measure low resistance (d) determine dissipation factor of a capacitor
**Ans: (d)** — Schering bridge determines dissipation factor of a capacitor.
**Concept:** Schering bridge → dissipation factor / loss angle of capacitor.
**Twist:** DF/loss angle → Schering. Low resistance → Kelvin. Mutual inductance → Heaviside-Campbell.

**Q30 (TS Transco-15):** Oscillator independent of phase shift is
(a) Relaxation (b) Wein's bridge (c) Clapp (d) All of these
**Ans: (a)** — Relaxation oscillator works without any phase-shift network.
**Concept:** Relaxation oscillator → no phase-shift condition needed (independent of phase shift).
**Twist:** Wien-bridge oscillator → phase-shift-dependent, frequency = 1/(2πRC). Clapp is a phase-shift/tuned oscillator variant.

**Q31 (TSSPDCL-15):** For measurement of radio frequency ac signals _____ type meter is used.
(a) thermo-couple (b) electro-static (c) electro-dynamometer (d) rectifier
**Ans: (a)** — Thermocouple (true rms) meter is used for RF AC signals.
**Concept:** Thermocouple meter → RF/high-frequency AC (true RMS).
**Twist:** High-frequency current measurement → thermocouple. Electrostatic → kV DC/high voltage. Rectifier → line-frequency.

**Q32 (TSSPDCL-15):** In Maxwell's inductance-capacitance bridge, a resistance is in _____ with standard capacitor; in Hay's bridge a resistance is in _____ with standard capacitor.
(a) series ... parallel (b) series ... series (c) parallel ... parallel (d) parallel ... series
**Ans: (d)** — Maxwell: R4 in parallel with standard capacitor C4; Hay: R4 in series with C4.
**Concept:** Maxwell bridge → R ∥ C standard; Hay bridge → R series C standard.
**Twist:** Swap description ("Maxwell series, Hay parallel") is a common trap → false. Which is used for high-Q → Hay (R series C).

**Q33 (TSNPDCL-15):** Maxwell's bridge (figure) balance. Under balanced conditions Rx and Lx are
(a) Rx = R4R3/R2, Lx = R2L3/R4 (b) Rx = R2R3/R4, Lx = R2L3/R4 (c) Rx = R2R3/R4, Lx = R4L3/R2 (d) Rx = R4R2/R3, Lx = R4L3/R3
**Ans: (b)** — Balance: (Rx+jωLx)R4 = (R3+jωL3)R2 → Rx = R2R3/R4, Lx = R2L3/R4.
**Concept:** Maxwell bridge balance: equate real & imaginary parts of opposite-arm products.
**Twist:** Rearrange for another unknown arm. Note Lx expression has same ratio R2/R4 — both magnitudes scale together.

**Q34 (TSNPDCL-15):** Peterson coil is used for
(a) shunt compensation of lines (b) reduce fault currents (c) grounding of system neutral (d) connecting interconnected systems
**Ans: (c)** — Peterson coil (arc suppression coil) grounds the system neutral.
**Concept:** Peterson coil → neutral grounding / arc suppression (L = 1/(3ω²C)).
**Twist:** Peterson coil value → L = 1/(3ω²C). It's a power-systems topic appearing in bridge/metering unit.

**Q35 (HMWS-15):** The inductance of a high-quality factor inductor can be measured by a
(a) Hay's bridge (b) Wein's bridge (c) Maxwell's bridge (d) Schering bridge
**Ans: (a)** — Hay's bridge is for high-Q inductor measurement.
**Concept:** Hay bridge → high-Q inductance.
**Twist:** Medium-Q → Maxwell. Low-Q → Anderson. This is a favourite one-line swap question.

**Q36 (AP Transco-17):** When measuring insulation resistance of cables using dc source, the galvanometer used should be initially short-circuited because
(a) cables have low capacitance drawing high charging current (b) cables have low initial resistance (c) cables have high capacitance which draws high charging current (d) cables have low capacitance and initial resistance
**Ans: (c)** — Cables have high capacitance, drawing a high charging current that would damage/deflect the galvanometer, so short it initially.
**Concept:** Cable charging current (Ic ∝ C/ph) protection of galvanometer in insulation tests.
**Twist:** Megger on long cable → capacitance charges first, then insulation reading. Shorting galvanometer protects against charging-current surge.

**Q37 (AP Transco-17):** The self-inductance of a coil can be measured using
(a) Wein's bridge (b) Schering bridge (c) Anderson's bridge (d) Wheatstone bridge
**Ans: (c)** — Anderson's bridge is the more accurate method for self-inductance.
**Concept:** Anderson bridge → accurate self-inductance measurement.
**Twist:** Mutual inductance → Heaviside-Campbell. Incremental inductance → Owen. Inductance over wide range → Anderson (Q10).

**Q38 (AP Genco-17):** Accurate measurement of very low resistances is possible with
(a) Megger (b) Wheatstone bridge (c) Kelvin's double bridge (d) Wagner's earthing device
**Ans: (c)** — Kelvin double bridge measures micro-ohm to milli-ohm resistances accurately.
**Concept:** Kelvin double bridge → low resistance (micro-Ω–mΩ).
**Twist:** Low resistance lead errors → four terminals (Q17). Medium resistance → Wheatstone/Carey-Foster. High → Megger.

**Q39 (AP Genco-17):** Dielectric loss in a capacitor is best measured by
(a) Wein's bridge (b) Schering bridge (c) Anderson's bridge (d) Heaviside-Campbell Equal Ratio bridge
**Ans: (b)** — Schering bridge is the best for dielectric loss measurement.
**Concept:** Schering bridge → dielectric loss / dissipation factor.
**Twist:** Best bridge for dielectric loss (repeat) → Schering. Capacitor loss under high voltage → high-voltage Schering (Q40).

**Q40 (TS Transco-18):** High voltage Schering bridge is used for the measurement of
(a) resistance and inductance of a coil (b) frequency of ac source (c) loss angle of a capacitor (d) Q of a coil
**Ans: (c)** — High-voltage Schering bridge measures loss angle of a capacitor (insulation & capacitor properties).
**Concept:** HV Schering bridge → loss angle / insulation of capacitors.
**Twist:** Frequency → Wien. Q of coil → Hay. R,L of coil → Maxwell/Anderson.

**Q41 (APEPDCL-19):** Which of the following may be used for frequency measurement
(a) Schering bridge (b) Kelvin's bridge (c) Maxwell's bridge (d) Wien bridge
**Ans: (d)** — Wien bridge is used for frequency measurement.
**Concept:** Wien bridge → frequency (f = 1/(2π√(R1R2C1C2))).
**Twist:** Frequency questions (Q45, Q49) all → Wien. Don't pick Schering/Maxwell for frequency.

**Q42 (APEPDCL-19):** A guard terminal in measurement of high resistance is used to
(a) minimize the charging current in insulation capacitance (b) guard the resistance against any stray electrostatic field (c) guard the resistance against overloads (d) bypass the leakage current
**Ans: (d)** — Guard terminal bypasses (eliminates) leakage current in high-resistance measurement.
**Concept:** Guard terminal → bypass leakage current in high-resistance / insulation measurements.
**Twist:** Four-terminal low-resistance setup → eliminates lead-contact error. Guard rings → shield surface leakage paths.

**Q43 (APEPDCL-19):** A bridge circuit works at 2 kHz. Which of the following can be used as null detector?
(a) Amplifiers only (b) Vibration galvanometers and tunable amplifiers (c) headphones and tunable amplifiers (d) vibration galvanometers and headphones
**Ans: (c)** — At 2 kHz: headphones (250 Hz–4 kHz) and tunable amplifiers (10 Hz–100 kHz) are suitable null detectors.
**Concept:** Null-detector frequency ranges: headphones 250 Hz–4 kHz; vibration galvanometer 5 Hz–1 kHz; tunable amplifier 10 Hz–100 kHz.
**Twist:** If bridge at 100 Hz → vibration galvanometer (within 5 Hz–1 kHz). If at 50 kHz → tunable amplifier only.

**Q44 (APSPDCL-19):** Circuit: R arms 3 Ω & 11 Ω (top), 2 Ω & 4 Ω (bottom), 15 V. Which statement is NOT true?
(a) VPQ = 2 V (b) VRS = 15 V (c) The bridge is balanced (d) When load connected between P and Q, current flows from P to Q
**Ans: (c)** — 3×4 ≠ 11×2 → bridge unbalanced; VPQ = 2 V (KVL), VRS = 15 V, load current flows P→Q. So "bridge balanced" is false.
**Concept:** Wheatstone balance check: opposite-arm products must be equal (3×4 vs 2×11).
**Twist:** Change one arm (e.g., 3→5.5 Ω) so 11×2 = 5.5×4 → bridge balances, VPQ = 0. "Which statement is true" variant → VPQ = 2 V.

**Q45 (APSPDCL-19):** The bridge used to measure frequency is
(a) Schering bridge (b) Owen bridge (c) Hay bridge (d) Wien bridge
**Ans: (d)** — Wien bridge is used to measure frequency.
**Concept:** Wien bridge → frequency measurement.
**Twist:** Same content as Q41/Q49 → Wien. Capacitance/DF → Schering. High-Q inductance → Hay.

**Q46 (AP Transco-19):** Which bridge is best suited for use in Harmonic Distortion Analyzers?
(a) Heaviside (b) Kelvin's double bridge (c) Wein (d) Schering
**Ans: (c)** — Wein (Wien) bridge is used for tuning to specific frequencies in harmonic distortion analyzers.
**Concept:** Wien bridge → frequency-selective (tuning) applications.
**Twist:** Wein bridge as frequency-selective network → also in RC oscillators (balance at f = 1/(2πRC)). Harmonic analyzer needs tunable frequency → Wien.

**Q47 (HMWSSB-20):** Which of the following method is used to measure medium value of resistances?
(a) Loss of charge method (b) Potentiometer method (c) Kelvin double bridge method (d) Carey-foster slide wire bridge method
**Ans: (d)** — Carey-Foster slide-wire bridge measures medium-value resistances.
**Concept:** Carey-Foster bridge → medium-resistance measurement (modified Wheatstone).
**Twist:** Medium resistance (1 Ω–100 kΩ) also → Wheatstone/substitution/ammeter-voltmeter. Loss of charge & Megger → high resistance. Kelvin → low.

**Q48 (HMWSSB-20):** AC bridge: arm PQ R=250 Ω, QR R=500 Ω, SP C=0.2 μF, RS unknown. Source 200 V, 1 kHz, detector Q–S. Unknown parameter of arm RS is
(a) Capacitance of 0.3 μF (b) Capacitance of 0.4 μF (c) Capacitance of 0.1 μF (d) Capacitance of 0.2 μF
**Ans: (c)** — Balance: R1·(1/jωCX) = R2·(1/jωC) → CX = (R1/R2)·C = (250/500)×0.2 = 0.1 μF.
**Concept:** AC bridge balance for capacitor arms: CXR2 = CR1 → CX = R1·C/R2.
**Twist:** If the unknown arm is resistive instead → RX = R2·R3/R1-style product. Swap R1/R2 roles → CX = 0.4 μF (trap).

**Q49 (TSPSC-AEE-23):** Which bridge is used to measure frequency
(a) Anderson bridge (b) Maxwell's bridge (c) Schering bridge (d) Wien's bridge
**Ans: (d)** — Wien's bridge is used to determine unknown frequency.
**Concept:** Wien bridge → frequency measurement.
**Twist:** Frequency content repeats (Q41, Q45) → always Wien. Anderson/Maxwell → self-inductance; Schering → capacitance/DF.

**Q50 (TSPSC-AEE-23):** Which bridge can be used for measuring relative permeability?
(a) Anderson (b) Wheatstone (c) Kelvin (d) Schering
**Ans: (a)** — Relative permeability relates to coil inductance; Anderson measures coil inductance → related to permeability.
**Concept:** Anderson bridge → inductance → relative permeability (permittivity relates to dielectric/Schering).
**Twist:** Relative permittivity (dielectric) → Schering (capacitance). Permeability needs an inductance bridge → Anderson.

**Q51 (TSPSC-AEE-23):** Arrange in increasing order of their Q factor:
I. Maxwell's bridge II. Hay's bridge III. Anderson's Bridge
(a) II, III, I (b) III, I, II (c) I, II, III (d) I, III, II
**Ans: (b)** — Increasing Q: Anderson (low) < Maxwell (medium, Q<10) < Hay (high, Q>10) → III, I, II.
**Concept:** Q ordering: Anderson (low Q) → Maxwell (medium Q) → Hay (high Q).
**Twist:** Decreasing Q order → II, I, III. High-Q coil measurement → Hay; low-Q → Anderson.

**Q52 (TSGenco-24):** Wheatstone bridge: R1=50 Ω, R2=65 Ω, R3=100 Ω (each ±0.5%). Galvanometer zero. Upper & lower limits of Rx are
(a) 65.675, 64.325 (b) 65.65, 64.35 (c) 131.95, 128.05 (d) 131.30, 128.70
**Ans: (c)** — Rx = R2R3/R1 = 65×100/50 = 130 Ω; ±1.5% → limits 130±1.95 = 131.95, 128.05.
**Concept:** Wheatstone balance + error propagation (tolerances add: ±0.5×3 = ±1.5%).
**Twist:** If only R1 had tolerance ±0.5% and others exact → ±0.5%. If tolerances ±0.1% → ±0.3% spread. Same balance formula Rx = R2R3/R1.

**Q53 (TSGenco-24):** Identify the correct statements:
(i) Owen's bridge measures inductance in terms of capacitance.
(ii) Hay's bridge measures inductance of coils with Q < 10.
(iii) Campbell bridge measures mutual inductance in terms of standard capacitance.
(iv) Anderson bridge gives precise inductance measurement compared to other bridges.
(a) (i) and (ii) only (b) (ii) and (iii) only (c) (iii) and (iv) only (d) (i) and (iv) only
**Ans: (d)** — (i) correct (Owen → L via C); (iv) correct (Anderson → precise L). (ii) false (Hay → Q>10); (iii) false (Campbell measures self-inductance in terms of mutual inductance).
**Concept:** Bridge assignment table: Owen→L in terms of C; Hay→high Q; Campbell→self-L in terms of mutual L; Anderson→precise L.
**Twist:** "Campbell measures mutual inductance" (Q20) → true for Heaviside-Campbell. Mutual inductance in terms of standard capacitance → the correct one is actually Owen/Campbell table; exam expects this exact statement set.

**Q54 (TSGenco-24):** Balanced Maxwell bridge (figure). Values of RX and LX are
(a) 75 Ω, 75 mH (b) 75 Ω, 150 mH (c) 375 Ω, 75 mH (d) 37.5 Ω, 75 mH
**Ans: (c)** — Rx = 2000×750/4000 = 375 Ω; Lx = (750×2000×0.05e-6)/1 = 75 mH.
**Concept:** Maxwell bridge balance: Rx = R2R3/R4; Lx = R2R3C (C = 0.05 μF).
**Twist:** Change C to 0.1 μF → Lx = 150 mH (trap option b). Change R4 → different Rx. Same Maxwell formulas as Q33.

---
**Exam-map quick table (high-yield one-liners):**
- Frequency → Wien (Q1, 11, 26, 41, 45, 49)
- High-Q inductance → Hay (Q23, 35); Medium-Q → Maxwell (Q2); Low-Q → Anderson (Q10, 37)
- Low resistance → Kelvin double bridge (Q19, 38); Medium → Wheatstone/Carey-Foster (Q3, 47); High/insulation → Megger (Q14)
- Capacitance / dielectric loss / DF → Schering (Q8, 27, 29, 39, 40)
- Mutual inductance → Heaviside-Campbell (Q20); Self-inductance via C → Owen (Q53)
- Wagner's earth → eliminates earth-capacitance effects (Q12, 22)
- Swamping resistance → temperature-error reduction (Q7, 13)
- Megger: 160 rpm (Q25); open terminals → infinity (Q9)
- Wheatstone balance: R1R4 = R2R3 (Q15); error limits add tolerances (Q52)
- AC bridge balance: opposite impedance products equal (Q21, 33, 48)

## Unit 4: Electronic Measurements & Transducers (53 Qs)

**Q1 (EPDCL-10):** Time base generators used in CRO produces ___ waveforms.
(a) sine (b) square (c) sweep (d) pulse
**Ans: (c)** — In Y-t mode the sweep generator drives the x-plates; sweep signal is generated internally.
**Concept:** CRO time base = sweep generator (sawtooth).
**Twist:** X-Y mode (no sweep) → external signal drives x-input.

**Q2 (EPDCL-10):** CRO probe assembly is an application of
(a) multivibrator (b) attenuator (c) clipper (d) clamper
**Ans: (b)** — Probe is a compensated attenuator network (Rp–Cp shunting Ri–Ci).
**Concept:** CRO probe: Ri/(Ri+Rp) = Cp/(Cp+Ci) when Ri·Ci = Rp·Cp → attenuation frequency-independent.
**Twist:** 10:1 probe → input impedance raised ~10 MΩ, extends bandwidth; unbalanced probe → HF distortion.

**Q3 (APSPDCL-12):** Which of the following is an active transducer?
(a) Strain gauge (b) Selsyn (c) Photo voltaic cell (d) Photo emission cell
**Ans: (c)** — Photo voltaic cell generates its own emf (active); it is listed as active, photo-emissive as passive.
**Concept:** Active transducers self-generate output (thermocouple, piezoelectric, photovoltaic, moving-coil generator); passive need external excitation.
**Twist:** thermocouple → active; strain gauge / RTD / LVDT → passive.

**Q4 (APSPDCL-12):** ADC preferred for digital panel meters and multimeters
(a) Flash ADC (b) Servo ADC (c) Successive approximation ADC (d) Dual-slope ADC
**Ans: (d)** — Dual-slope is the slowest but most accurate ADC, ideal for DVM/DPM.
**Concept:** Dual-slope ADC: integrate Vx for fixed T, then integrate Vref to return to zero → cancels component drift.
**Twist:** fastest ADC → flash (n bits → 2ⁿ−1 comparators); high-speed acquisition → SAR.

**Q5 (HMWS-12):** Which material has the least thermoelectric power against copper?
(a) Constantan (b) Manganin (c) Nickel-chromium (d) Gold
**Ans: (b)** — Manganin (and constantan) have an almost constant (near-zero) thermal emf vs copper.
**Concept:** Thermoelectric power vs copper: Manganin/Constantan ≈ 0 → used in standard resistors / Cu pairs.
**Twist:** lowest thermal emf → Manganin (standard resistor wire); constantan is the −ve element of type T/type J thermocouples.

**Q6 (HMWS-12):** CRO cannot measure directly (without external aid)
(a) voltage (b) frequency (c) current (d) phase angle between two voltages
**Ans: (c)** — CRO measures voltage, frequency and phase directly; current only via a standard resistor.
**Concept:** CRO is a voltage-observing instrument (input impedance ~1 MΩ).
**Twist:** measure current → pass through known R and read V = IR drop.

**Q7 (HMWS-12):** Orifice is used to measure
(a) temperature (b) pressure (c) flow rate (d) velocity
**Ans: (c)** — Orifice meter is a differential-pressure flow meter.
**Concept:** Orifice → pressure drop ∝ (flow)², measure ΔP to get flow rate.
**Twist:** venturi / orifice plate → flow rate; pitot tube → velocity.

**Q8 (Transco-12):** Calibration pulse 1 kHz, 5 V p-p on ch-1 (4 div/cycle, 2 div height) fixes the erased scales; unknown signal (ch-2, 8 div period, 3 div height). Amplitude (p-p) and period of unknown?
(a) 5 V, 1 ms (b) 5 V, 2 ms (c) 7.5 V, 2 ms (d) 10 V, 1 ms
**Ans: (c)** — V/div = 5 V/2 div = 2.5 V/div → 3 div × 2.5 = 7.5 V; t/div = (1/1 kHz)/4 = 0.25 ms/div → 8 div × 0.25 = 2 ms.
**Concept:** CRO calibration: use known pulse to recover erased scales; amplitude = div × V/div, T = div × time/div.
**Twist:** cal pulse 2 V p-p → recompute V/div = 1 V/div, amplitude would halve.

**Q9 (Transco-12):** X-Y mode shows figure changing ellipse→circle→ellipse with major axis rotating slowly. Inference?
(a) signals not sinusoidal (b) amplitudes close but unequal (c) sinusoidal, frequencies very close but unequal (d) constant but small phase difference
**Ans: (d)** — Book solution: change of ellipse→circle→ellipse is due to phase difference only.
**Concept:** Lissajous: phase difference shifts the ellipse toward a circle (at 90°) and back.
**Twist:** if frequencies slightly differ → major axis rotates continuously (beating Lissajous), ratio of tangencies gives fy/fx.

**Q10 (Transco-12):** Q-meter: standard inductor + C=300 pF gives Q=120; adding lossless unknown Cx, variable C readjusted to 200 pF for same Q. Cx?
(a) 100 (b) 200 (c) 300 (d) 500
**Ans: (a)** — Q = 1/(ωC1R) = 1/(ω(C2+Cx)R) → C1 = C2 + Cx → Cx = 300 − 200 = 100 pF.
**Concept:** Q-meter: Q = XL/R = 1/(ωCR); unknown in parallel adds capacitance.
**Twist:** unknown is inductive (L) → ΔC gives L via f = 1/(2π√(LC)).

**Q11 (EPDCL-14):** Transducer employed for measurement of angular displacement
(a) LVDT (b) Thermocouple (c) Thermistor (d) Circular potentiometer
**Ans: (d)** — Circular potentiometer measures angular displacement; LVDT is linear.
**Concept:** Linear displacement → LVDT; angular displacement → circular/rotary potentiometer.
**Twist:** rotary displacement (RVDT) → rotary variable differential transformer.

**Q12 (EPDCL-14):** Thermistor is employed for measurement of
(a) Linear displacement (b) Acceleration (c) Pressure (d) Temperature
**Ans: (d)** — Thermistor has a negative temperature coefficient and is a temperature sensor.
**Concept:** Thermistor = NTC resistor, high sensitivity, non-linear.
**Twist:** thermistor in series with heating element → inrush current limiter; parallel combination → linearization.

**Q13 (EPDCL-14):** The "Gauge factor" of a strain gauge is given by
(a) (ΔL/L)/(ΔR/R) (b) (ΔR/R)/(ΔL/L) (c) ΔR/ΔL (d) ΔL/ΔR
**Ans: (b)** — Gf = (ΔR/R)/(ΔL/L) = (ΔR/R)/ε.
**Concept:** Gauge factor = fractional change in resistance per unit strain.
**Twist:** metal gauge Gf ≈ 2 (Gf = 1 + 2μ); semiconductor gauge Gf ≈ 100+.

**Q14 (EPDCL-14):** Lissajous pattern has 6 vertical maxima and 4 horizontal maxima; horizontal input 1000 Hz. Frequency of vertical input?
(a) 4000 Hz (b) 1500 Hz (c) 6000 Hz (d) 2000/3 Hz
**Ans: (d)** — fy/fx = (horizontal tangencies)/(vertical tangencies) = 4/6 → fy = 1000 × 4/6 = 2000/3 Hz.
**Concept:** Lissajous: fy/fx = H-tangencies / V-tangencies (cut count).
**Twist:** swap tangencies → fy = 1500 Hz; ratio = 4/6 = 2:3.

**Q15 (SSC-JE-S1-14):** In a 3½ digit voltmeter, the largest number that can be read is
(a) 0999 (b) 1999 (c) 5999 (d) 9999
**Ans: (b)** — Half digit (0 or 1) + 3 full digits (0–9) → 1999.
**Concept:** 3½ digit DVM: 0 to 1999 (2000 counts).
**Twist:** 4½ digit → 19999; resolution of 3½ digit = 1/2000th of range.

**Q16 (SSC-JE-S2-14):** Adding a precise amount of time between the trigger point and the beginning of the scope sweep is known as
(a) free running sweep (b) delayed sweep (c) triggered sweep (d) non-sawtooth sweep
**Ans: (b)** — This is the definition of delayed sweep.
**Concept:** Delayed sweep — inserts a calibrated delay after trigger to inspect a selected portion of the waveform.
**Twist:** triggered sweep → sweep starts on input signal itself; free-running → no trigger.

**Q17 (SSC-JE-S2-14):** In a CRO, a sinusoidal waveform is displayed. The value that can be made out by direct observation is
(a) RMS (b) average (c) form factor (d) peak-peak
**Ans: (d)** — Only the p-p (or peak) value is read directly off the graticule.
**Concept:** CRO displays instantaneous waveform; RMS/average must be computed (× k).
**Twist:** Vrms = Vp-p/(2√2) for sine; form factor = RMS/avg = 1.11.

**Q18 (SSC-JE-S2-14):** In a CRT, the focusing anode is located
(a) after accelerating anode (b) between pre-accelerating and accelerating anodes (c) before pre-accelerating anode (d) just after electron gun
**Ans: (b)** — Electron gun order: cathode → grid → pre-accelerating → focusing → accelerating.
**Concept:** CRT electron gun forms an electrostatic lens (focusing + accelerating anodes).
**Twist:** post-accelerating anode (between deflection plates & screen) → boosts final velocity.

**Q19 (SSC-JE-S1-14):** Order of minimum displacement measurable with capacitive transducers
(a) 1 cm (b) 1 mm (c) 1 μm (d) 10⁻¹² m
**Ans: (c)** — Capacitive transducers can resolve displacements down to ~1 μm.
**Concept:** Capacitive transducer: C ∝ A/d → d from capacitance change, high sensitivity.
**Twist:** capacitive also measures pressure/level; μm-class resolution.

**Q20 (HMWS-15):** y-input = 10 sin 100t, x-input = 10 cos 100t, equal gains. Lissajous pattern?
(a) Circle (b) Straight line (c) Ellipse (d) Sinusoidal signal
**Ans: (a)** — Equal amplitudes with 90° phase difference → circle.
**Concept:** Lissajous: equal amplitude + 90° → circle; 0°/180° → line; unequal amplitude + 90° → ellipse.
**Twist:** 10 sin100t on both inputs (0°) → straight line; 10 sin100t vs 20 cos100t → ellipse.

**Q21 (TS Genco-15):** Piezoelectric transducer is used to measure
(a) displacement (b) resistance (c) current (d) temperature
**Ans: (b)** — Book solution: piezoelectric transducer is used to measure resistance.
**Concept:** Piezoelectric: mechanical strain → charge (active); book lists "resistance".
**Twist:** piezoelectric is classically used for pressure/force/acceleration/vibration measurement (charge amplifier + high impedance load).

**Q22 (TS Transco-15):** The time base signal in a CRO is
(a) A square wave (b) A sawtooth signal (c) A triangular wave (d) A sinusoidal signal
**Ans: (b)** — Time base generator produces a sawtooth sweep.
**Concept:** Sawtooth: slow linear rise (sweep) + fast flyback (retrace, blanked).
**Twist:** beam blanked during retrace → invisible flyback; retrace travels right→left.

**Q23 (TSSPDCL-15):** Lissajous ellipse with major axis in quadrants 2 and 4. Phase difference?
(a) 270° (b) 210° (c) 180° (d) 300°
**Ans: (b)** — Major axis in Q2/Q4 ⇒ phase in (90°–270°); 210° lies in (180°–270°).
**Concept:** Phase bands: 0°→line, 0–90°→ellipse Q1/Q3, 90°→circle, 90–180° & 180–270°→ellipse Q2/Q4.
**Twist:** major axis Q1/Q3 (e.g. 45°) → phase 0–90°; 180° → straight line along Q2/Q4.

**Q24 (TSSPDCL-15):** In CRO, during retrace time the electron beam travels __ from __ of the screen.
(a) diagonally… top left to bottom right (b) vertically… top to bottom (c) horizontally… right to left (d) vertically… bottom to top
**Ans: (c)** — Retrace = fast horizontal flyback from right to left (beam blanked).
**Concept:** Sweep left→right, retrace right→left; blanking hides the retrace line.
**Twist:** if retrace not blanked → bright flyback line visible (poor brightness control).

**Q25 (TSSPDCL-15):** Poisson's ratio 1.8; neglecting piezo-resistive effects, gauge factor?
(a) 2.8 (b) 2.6 (c) 4.6 (d) 3.6
**Ans: (c)** — Gf = 1 + 2μ = 1 + 2(1.8) = 4.6.
**Concept:** Metal wire gauge factor Gf = 1 + 2μ (no piezo-resistive term).
**Twist:** μ = 0.3 (steel) → Gf = 1.6; typical metal gauge ~2.

**Q26 (TSNPDCL-15):** LVDT is used to measure
(a) strain (b) pressure (c) flow (d) displacement
**Ans: (d)** — LVDT measures linear displacement.
**Concept:** LVDT: one primary + two secondaries in series opposition; Eout ∝ core displacement.
**Twist:** angular displacement → RVDT/circular potentiometer; LVDT + bellows → pressure.

**Q27 (TSNPDCL-15):** Principle of thermocouple is based on
(a) Thomson effect (b) Peltier effect (c) Seebeck effect (d) Kelvin effect
**Ans: (c)** — Two dissimilar metals at two different temperatures produce emf (Seebeck).
**Concept:** Seebeck: hot junction → cold junction electron flow, detected by PMMC (DC).
**Twist:** Peltier → heating/cooling at junction (refrigeration); Thomson → emf along a single conductor with a gradient.

**Q28 (TSNPDCL-15):** A dummy strain gauge in a quarter-bridge strain gauge circuit is used to
(a) compensate for changes in temperature and lead wire resistance (b) produce more output voltage (c) increase sensitivity (d) compensate lead wire resistance only
**Ans: (a)** — Dummy gauge (unstressed, same material) cancels temperature & lead-wire effects.
**Concept:** Quarter bridge + dummy gauge → temperature compensation in adjacent arm.
**Twist:** dummy gauge mounted adjacent but unstressed → cancels thermal drift; active gauge alone → temp false output.

**Q29 (AP Genco-17):** Transducer with negative temperature coefficient of resistance
(a) Thermistor (b) Resistance Thermometer (c) Strain Gauge (d) Thermocouple
**Ans: (a)** — Thermistor has negative temperature coefficient.
**Concept:** Thermistor NTC; RTD (Pt) has positive temp coefficient.
**Twist:** RTD → positive coefficient (Pt100, R increases with T).

**Q30 (AP Genco-17):** Deflection sensitivity of a CRT (D = screen–plate distance, l = plate length, ld = plate gap, Ea = accelerating voltage) is
(a) 2Ea·l/(D·ld) (b) Dl/(2ld·Ea) (c) D·ld/(2l·Ea) (d) D·Ea/(2·l·ld)
**Ans: (b)** — S = deflection/unit voltage = D·l/(2·Ea·ld).
**Concept:** Electrostatic deflection sensitivity ∝ l·D, ∝ 1/(Ea·ld).
**Twist:** raising Ea → less sensitivity but sharper/brighter spot; longer plates → greater deflection but narrower angle.

**Q31 (TSSPDCL-18):** True RMS electronic voltmeter with thermocouples — statements: 1. two thermocouples overcome non-linear characteristic; 2. PMMC used for indication; 3. complex waveforms can be measured; 4. average actually measured, calibrated for RMS. Correct statements?
(a) 1, 3 (b) 1, 2 (c) 2, 4 (d) 2, 3
**Ans: (b)** — Two matched TCs (measuring + compensating) kill non-linearity; PMMC indicates.
**Concept:** True-RMS meter: thermocouple gives RMS-to-DC conversion (output ∝ true RMS).
**Twist:** statement 4 → that is an average-responding (rectifier) meter, not true RMS; true-RMS does measure complex waveforms.

**Q32 (TS Transco-18):** An aquadag is used in a CRO to collect
(a) Primary electrons (b) Secondary emission electrons (c) Both primary and secondary electrons (d) The frequency of the signal
**Ans: (b)** — Aquadag (graphite) coating collects secondary-emission electrons, keeps screen at steady potential.
**Concept:** Aquadag = internal conductive coating forming the return path / final anode.
**Twist:** aquadag also acts as post-accelerating anode & EM shielding; without it, screen charges up.

**Q33 (APEPDCL-19):** Lissajous pattern (figure): ratio of vertical to horizontal signal frequency?
(a) 1:5 (b) 3:2 (c) 2:3 (d) 5:1
**Ans: (b)** — fy/fx = horizontal cuts/vertical cuts = 6/4 = 3/2.
**Concept:** Lissajous frequency ratio = tangencies (cuts) count ratio.
**Twist:** if the figure has 4 horizontal & 6 vertical cuts → ratio 2:3.

**Q34 (APEPDCL-19):** Best example of a zero-order instrument
(a) Thermocouple (b) Mercury thermometer (c) Potential divider (d) Force-measuring spring scale
**Ans: (c)** — Potential divider has transfer function K·s⁰ (instantaneous, static response).
**Concept:** Zero-order: output proportional to input with no lag (static).
**Twist:** thermocouple & mercury thermometer → first-order (exponential lag); spring scale is also ~zero order but book picks potential divider.

**Q35 (APEPDCL-19):** The source of emission of electrons in a CRT is
(a) Post-accelerating anodes (b) PN junction diode (c) Barium and strontium oxide coated cathode (d) Accelerating anodes
**Ans: (c)** — Oxide-coated (Ba/Sr) cathode gives thermionic emission (low work function).
**Concept:** CRT electron gun: indirectly heated oxide-coated cathode emits electrons.
**Twist:** anode shapes/accelerates the beam; higher work function → needs more heat.

**Q36 (APEPDCL-19):** The input impedance of a CRO is nearly
(a) 1 MΩ (b) 0 Ω (c) 10 Ω (d) 100 Ω
**Ans: (a)** — ~1 MΩ (with few pF shunt) → negligible loading.
**Concept:** High input impedance so CRO doesn't load the circuit under test.
**Twist:** 10× probe → 10 MΩ input; higher Z at DC, falls with frequency.

**Q37 (APSPDCL-19):** Choose the odd one out
(a) Strain gauge (b) Thermistor (c) RTD (d) Thermocouple
**Ans: (a)** — Thermistor, RTD, thermocouple all measure temperature; strain gauge responds to force/strain.
**Concept:** Temperature sensors group vs strain (force) sensor.
**Twist:** RTD & thermistor are both resistive temp sensors; thermocouple is a generating (voltage) sensor.

**Q38 (APSPDCL-19):** LVDT is the abbreviation for
(a) Linear voltage displacement transducer (b) Linear variable differential transmitter (c) Linear variable differential transformer (d) Linear voltage displacement transformer
**Ans: (c)** — Linear Variable Differential Transformer.
**Concept:** LVDT: primary + 2 secondaries (series opposition); displacement → differential EMF.
**Twist:** RVDT → rotary version; LVDT output is AC, needs demodulator.

**Q39 (APSPDCL-19):** Sinusoidal waveform on CRO (8 cm for 2T, 5 cm p-p); knobs 100 μs/cm, 10 V/cm. Frequency and rms?
(a) 2.5 kHz, 17.7 V (b) 2.5 kHz, 25 V (c) 1.25 kHz, 25 V (d) 1.25 kHz, 17.7 V
**Ans: (a)** — T = 4 cm × 100 μs = 400 μs → f = 2.5 kHz; Vp-p = 5 cm × 10 = 50 V → Vrms = 50/(2√2) = 17.7 V.
**Concept:** f = 1/T; Vrms = Vp-p/(2√2) for sine.
**Twist:** if p-p = 5 cm → peak value = 25 V (trap for option b); non-sine needs form factor.

**Q40 (AP Transco-19):** A high-Q quartz crystal exhibits series resonance Ws and parallel resonance Wp. Then
(a) Ws ≪ Wp (b) Ws ≫ Wp (c) Ws very close to, but greater than Wp (d) Ws very close to, but less than Wp
**Ans: (d)** — fp is just above fs (Ws < Wp, extremely close); high Q → ultra-narrow gap.
**Concept:** Crystal equivalent: Ls, Cs (series) with Cp across → two resonances; fp > fs.
**Twist:** crystal as frequency-determining element in oscillators; Q up to 10⁵–10⁶.

**Q41 (HMWSSB-20):** Assertion (A): no loading problem in electronic voltmeter. Reason (R): input resistance of electronic voltmeter is small.
(a) A false, R true (b) A and R false (c) A and R true (d) A true, R false
**Ans: (d)** — Electronic voltmeter has very high input impedance (R true only if high, but R says small → false).
**Concept:** High input impedance → negligible loading; amplifier stage boosts sensitivity.
**Twist:** low input impedance meter → loading error (reading too low) on high-source-resistance circuits.

**Q42 (HMWSSB-20):** The 3½ digit DVM displays a maximum of ___ with resolution of ___ of the range.
(a) 999, 1/2000 (b) 1999, 1/2000th (c) 999, 1/1000th (d) 1999, 1/1000th
**Ans: (b)** — Max 1999; 2000 counts → resolution 1/2000th of range.
**Concept:** 3½ digit: half digit (0/1) + 3 digits → 2000 steps.
**Twist:** 4½ digit on 10 V range → max 19999, resolution 0.5 mV; on 100 V range → 19999 → 5 mV.

**Q43 (HMWSSB-20):** Match phase to Lissajous figure: (A) 0° (B) 150° (C) 90° → (P) circle (Q) straight line (R) ellipse.
(a) A-Q; B-R; C-P (b) A-P; B-R; C-Q (c) A-P; B-Q; C-R (d) A-Q; B-P; C-R
**Ans: (a)** — 0°→straight line (Q); 90°→circle (P); 150°→ellipse (R).
**Concept:** Phase→shape: 0/180° line, 90° circle, else ellipse.
**Twist:** 180° → straight line (reversed slope); unequal amplitudes + 90° → ellipse not circle.

**Q44 (HMWSSB-20):** CRT electrostatic & magnetic deflection sensitivities are proportional to ___ and ___ with accelerating voltage Va respectively.
(a) 1/Va and √Va (b) Va and Va (c) 1/Va and 1/√Va (d) Va and 1/√Va
**Ans: (c)** — Electrostatic S ∝ 1/Va; magnetic S ∝ 1/√Va (transit time increases as Va falls).
**Concept:** Higher Va → faster electrons → less deflection; magnetic has √ dependence (∝ transit time).
**Twist:** magnetic deflection gives larger deflection angles (TV tubes); electrostatic is faster (CRO) but limited angle.

**Q45 (TSNPDCL-22):** Periodic voltage waveform on CRO; a voltmeter reads 14 V. The meter can be
(a) Neither MC nor MI meter (b) Either MC or MI meter (c) MC meter only (d) MI meter only
**Ans: (a)** — For this waveform V²(rms) = 14 → Vrms = √14 ≈ 3.7 V, Vavg = −0.5 V; neither MI (RMS) nor MC (avg) reads 14 V.
**Concept:** MI reads true RMS; MC reads average; asymmetric waveform → no standard meter reads 14 V.
**Twist:** if reading equaled computed RMS → MI meter; if reading equaled average → MC meter.

**Q46 (TSPSC-AEE-23):** Two channels fed to CRO X-Y; ellipse with major axis along the Y-axis. Inference?
(a) periodic, same frequency, different phase and amplitude (b) same frequency and amplitude, different phase (c) same frequency and phase, different amplitude (d) same amplitude, different frequency
**Ans: (a)** — Ellipse with major axis on Y ⇒ same frequency, 90° phase, different amplitudes.
**Concept:** Lissajous ellipse: axis aligned along Y (or X) → 90° shift + unequal amplitudes.
**Twist:** major axis at 45° with equal amplitudes & 90° → circle; non-90° tilt → ellipse with tilted major axis.

**Q47 (TSSPDCL-AE-2023):** time/cm = 500 μs/cm, volts/cm = 5 V/cm; half-cycle = 2 div, p-p = 5 div. RMS value?
(a) 17.68 V (b) 8.84 V (c) 12.50 V (d) 7.96 V
**Ans: (b)** — Vp = 2.5 div × 5 = 12.5 V → Vrms = 12.5/√2 = 8.84 V.
**Concept:** Peak from p-p; rms = Vp/√2 for sine.
**Twist:** if half-cycle = 1 div → T = 1 ms → f = 1 kHz; rms uses peak (2.5 div) not p-p.

**Q48 (TSSPDCL-AE-2023):** A 4½ digit voltmeter displays 18.634 V on a 10 V range as
(a) 18.63 V (b) 018.63 V (c) 18.634 V (d) 18.630 V
**Ans: (c)** — 4½ digit (19999) on 10 V range can display all 5 digits: 18.634 V.
**Concept:** 4½ digit DVM → 5 display digits (half + 4 full).
**Twist:** on 100 V range (max 99.999) it reads 018.63 V (5-digit display, last digit dropped/rounded); 3½ digit would show 18.63.

**Q49 (TSSPDCL-AE-2023):** Dual-slope DVM: C = 0.2 μF, R = 100 kΩ; reference 5 V integrated for max 40 ms. Maximum output voltage?
(a) 0.1 V (b) 10 V (c) 1 V (d) 100 V
**Ans: (b)** — V0 = t·Vref/(RC) = (5 × 40×10⁻³)/(100×10³ × 0.2×10⁻⁶) = 0.2/0.02 = 10 V.
**Concept:** Dual-slope integration: V0 = Vref·T/(RC).
**Twist:** longer T or bigger Vref → higher V0; RC bigger → lower V0 (e.g. R=1 MΩ → 1 V).

**Q50 (TSPSC-AEE-23):** DVM range 0 to 9988 counts, full-scale 9.988 V. Resolution in volts?
(a) 10⁻⁴ V (b) 10⁻¹ V (c) 10⁻³ V (d) 10⁻² V
**Ans: (c)** — Resolution = FS/counts = 9.988/9988 = 1×10⁻³ V (1 mV).
**Concept:** Resolution = full-scale / number of counts.
**Twist:** counts = 9999 (full 4-digit) → resolution = 9.999/9999 ≈ 1 mV; higher counts → finer resolution.

**Q51 (TSPSC-AEE-23):** Arrange CRT parts in logical order from pins side: I. Heater, II. Grid, III. Focusing anode, IV. Accelerating anode.
(a) II, III, V, I, IV (b) I, V, II, III, IV (c) III, IV, V, I, II (d) V, I, II, IV, III
**Ans: (b)** — Heater → Cathode (V) → Grid → Focusing anode → Accelerating anode.
**Concept:** Electron gun from pins/base: heater, cathode, control grid, focusing, accelerating.
**Twist:** nearest the screen → post-accelerating anode (after deflection plates).

**Q52 (TSPSC-AEE-23):** Match Lissajous patterns to frequency ratios (I: 10 horizontal / 2 vertical cuts; II: 2/8; III: 4/6): 1. fv = (2/3)fh, 2. fv = 5fh, 3. fv = (1/4)fh.
(a) I-2, II-1, III-3 (b) I-1, II-2, III-3 (c) I-3, II-1, III-2 (d) I-2, II-3, III-1
**Ans: (d)** — I: 10/2 = 5 → fv = 5fh (2); II: 2/8 = 1/4 → (3); III: 4/6 = 2/3 → (1).
**Concept:** fy/fx = horizontal cuts / vertical cuts (tangencies).
**Twist:** pattern with equal loops 1:1 → circle/ellipse; vertical-rich pattern → fv < fh.

**Q53 (TSPSC-AEE-23):** Statements on CRO: I. deflection sensitivity = deflection per unit deflection voltage; II. graticule is a grid of lines for time/amplitude scale; III. isolation probe avoids loading effects of shielded probe.
(a) I and II only (b) II and III only (c) I and III only (d) I, II and III
**Ans: (d)** — All three statements are correct.
**Concept:** Deflection sensitivity, graticule, isolation/attenuator probes.
**Twist:** 10:1 compensated probe → less loading + higher bandwidth; isolation probe → removes ground-loop (common-mode) errors.

> Total: 281 questions annotated.

---

# 📋 FORMULA SUMMARY — Exam-Day Sheet (Measurements)

## 1. Basics of Measuring Instruments
- **PMMC: T = NBAI (d.c. only)** · moving iron works a.c./d.c.
- %error = (measured − true)/true ×100 · accuracy ≠ precision
- **Ammeter shunt: Rsh = Rm/(m−1)** · **Voltmeter multiplier: Rse = Rm(m−1)**

## 2. Power & Energy
- **P = VIcosφ** · two-wattmeter: **P = W1+W2, tanφ = √3(W1−W2)/(W1+W2)**
- W1=W2 → PF=1 · W1=0 → PF=0.5 · **CT secondary never open**

## 3. Bridges
- **Wheatstone: P/Q = R/S** · Kelvin double bridge → low resistance
- **Schering → capacitance/DF · Maxwell → inductance · Hay → high-Q coil · Wien → frequency**

## 4. Electronic Measurements
- **CRO: Y ∝ voltage, x = time · frequency = 1/T** · Lissajous: fy/fx = tangent ratio
- **Gauge factor = (ΔR/R)/ε ≈ 2 (metal)** · Q-meter: Q = XL/R
- Transducers: **active (thermocouple — self-generating) vs passive (RTD — needs excitation)**
