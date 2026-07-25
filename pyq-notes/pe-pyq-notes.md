# Power Electronics – Formula/Concept vs. Question Count Analysis

**Source:** Study Material – GTD PYQs 2026 (Power Electronics)  
**Total Questions Analyzed:** 130+ (Pages 1-32)

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
| **1** | **AC-DC Converters (Rectifiers)** <br> 1-Φ Half wave: `V_o = V_m/(2π)(1 + cosα)` <br> 1-Φ Full wave: `V_o = (2V_m/π)cosα` <br> 1-Φ Semi: `V_o = (V_m/π)(1 + cosα)` <br> 3-Φ Full: `V_o = (3V_m/π)cosα` <br> `PIV = V_m` (Bridge), `PIV = 2V_m` (Mid-point) <br> `I_rms(thyristor) = I_o/√3` (3-Φ full) | **~25** | Supply voltage, Firing angle (α), Load (R, RL, RLE), Source inductance. | **Average output voltage** , **RMS output voltage** , **PIV** of diode/SCR, **RMS current** through SCR, **Displacement power factor** , **Effect of source inductance**. | Q1-Q67 |
| **2** | **DC-DC Converters (Choppers)** <br> Step-down (Buck): `V_o = D V_s` <br> Step-up (Boost): `V_o = V_s / (1-D)` <br> Buck-Boost: `V_o = -D V_s / (1-D)` <br> `ΔI_L = (V_s D T) / L` <br> `ΔV_C = (I_o D T) / C` <br> Ripple factor: `√(1/D - 1)` | **~18** | Input voltage (V_s), Duty cycle (D), Switching frequency, L, C, Load. | **Average output voltage** , **Ripple current/voltage** , **Duty cycle for desired output** , **Chopper type/quadrant**. | Q1-Q34 |
| **3** | **DC-AC Converters (Inverters)** <br> 1-Φ Full bridge fundamental: `V_o1 = (4V_s/π)sin(ωt)` <br> RMS fundamental: `V_o1_rms = (2√2/π)V_s` <br> 3-Φ Line voltage (180° mode): `V_LL = V_s` (peak) <br> Harmonic elimination: Pulse width for nth harmonic = `2π/n` <br> THD definition | **~12** | DC input voltage, Modulation index, Switching frequency, Load (R, RL, RLC). | **Fundamental output voltage** , **Harmonic elimination** , **THD** , **Conduction mode (120°/180°)** , **VSI vs CSI**. | Q1-Q31 |
| **4** | **AC-AC Converters** <br> AC Voltage Controller: `V_o_rms = V_s √[(π-α + sin2α/2)/π]` <br> Cycloconverter: Output frequency < Input frequency (Step-down) | **~6** | Input voltage, Firing angle, Load, Output frequency. | **RMS output voltage** , **Input power factor** , **Output frequency** , **Cycloconverter type**. | Q1-Q12 |
| **5** | **Power Semiconductor Devices** <br> `di/dt = V/L` <br> `dV/dt = V/(RC)` <br> `I_c = C_j (dV/dt)` <br> `P_D = (T_J - T_A)/θ_JA` <br> `I_rms = I_p × √(D)` (various waveforms) | **~16** | Device ratings, Snubber circuit values, Temperature, Gate pulse. | **di/dt protection** (L value), **dV/dt protection** (C/R value), **Latching/Holding current** , **Power dissipation** , **Device identification**. | Q1-Q50 |
| **6** | **Electric Drives (DC & AC)** <br> `P = T × ω` <br> `E_b = V_t - I_a R_a` <br> `N ∝ E_b / φ` <br> `THD = √(I_h²) / I_1` | **~14** | Motor ratings, Converter output, Torque, Speed. | **Motor speed** with converter, **Back EMF** , **Torque** , **Harmonics** , **Drive quadrant operation**. | Q1-Q28 |
| **7** | **Commutation & Protection** <br> `L = V_s / (di/dt)` <br> `R = 0.5√(L/C)` (for resistance switching) <br> `V = i√(L/C)` (voltage across CB) | **~8** | Snubber values, Source inductance, Current. | **Snubber component values** , **Voltage across breaker** , **Commutation circuit** analysis. | Q3, Q21, Q27, Q28, Q30, Q31, Q36, Q45, Q80, Q87, Q90, Q93, Q101 |
| **8** | **Power Factor & Harmonics** <br> `IPF = (DF) / √(1 + THD²)` <br> `DF = cosφ₁` <br> `THD = √(1/DF² - 1)` | **~6** | Input power factor, Displacement factor, THD. | **Input power factor** , **Displacement factor** , **Total Harmonic Distortion**. | Q14, Q16, Q23, Q59, Q63, Q65 |

---

## 🧭 The 5-Question Decision Flowchart

| Step | Question to Ask | If YES → | If NO → |
| :---: | :--- | :--- | :--- |
| **1** | **Is the conversion AC → DC?** | Use **Rectifier** formulas (α, V_o, PIV) | Go to Step 2 |
| **2** | **Is the conversion DC → DC?** | Use **Chopper** formulas (D, V_o, ripple) | Go to Step 3 |
| **3** | **Is the conversion DC → AC?** | Use **Inverter** formulas (fundamental, harmonics, THD) | Go to Step 4 |
| **4** | **Is the conversion AC → AC?** | Use **AC Voltage Controller** or **Cycloconverter** formulas | Go to Step 5 |
| **5** | **Is it about a device or drive?** | Use **Device** (di/dt, dV/dt, latching) or **Drive** (motor speed, torque) formulas | It's a **theory/definition** question. |

---

## 🔑 How to Identify the Topic from the Question

| Keywords in Question | Topic | Go-to Formula |
| :--- | :--- | :--- |
| "Firing angle", "average output voltage", "rectifier", "PIV" | **AC-DC Converter** | V_o = (2V_m/π)cosα |
| "Duty cycle", "chopper", "buck", "boost" | **DC-DC Converter** | V_o = D V_s / (1-D) |
| "Inverter", "fundamental component", "harmonics", "PWM" | **DC-AC Converter** | V_o1 = (4V_s/π)sinωt |
| "AC voltage controller", "cycloconverter", "output frequency" | **AC-AC Converter** | V_o_rms = V_s √[(π-α + sin2α/2)/π] |
| "SCR", "GTO", "IGBT", "MOSFET", "di/dt", "snubber" | **Power Devices** | di/dt = V/L, dV/dt = V/(RC) |
| "Motor", "drive", "speed", "torque" | **Electric Drives** | P = Tω, N ∝ E_b/φ |

---

## 📝 The Ultimate "What Happens When..." Cheat-Sheet

| Change Made | Converter | Effect |
| :--- | :--- | :--- |
| **↑ Firing angle (α)** | Rectifier | ↓ V_o, ↓ Power factor |
| **↑ Duty cycle (D)** | Buck Chopper | ↑ V_o |
| **↑ Duty cycle (D)** | Boost Chopper | ↑ V_o (non-linear) |
| **↑ Switching frequency** | Chopper/Inverter | ↓ Ripple, ↓ THD, ↑ Losses |
| **↑ Load current** | Any | ↑ Losses, ↓ Efficiency |
| **↑ Source inductance** | Rectifier | ↓ V_o (commutation overlap) |
| **↑ Modulation index** | Inverter | ↑ Fundamental voltage |
| **↑ DC link voltage** | Inverter | ↑ Output voltage |

---

## 🎯 Top 10 Concepts to Score >90%

| Rank | Concept | Weightage | Key Formulas |
| :---: | :--- | :---: | :--- |
| **1** | **AC-DC Converters** | ~20% | V_o, PIV, I_rms, α |
| **2** | **DC-DC Converters** | ~15% | V_o = DV_s, V_s/(1-D), ripple |
| **3** | **Power Devices (SCR, IGBT, etc.)** | ~12% | di/dt, dV/dt, latching/holding |
| **4** | **DC-AC Converters** | ~10% | Fundamental voltage, THD |
| **5** | **Electric Drives** | ~10% | P = Tω, N ∝ E_b/φ |
| **6** | **AC-AC Converters** | ~5% | V_o_rms |
| **7** | **Commutation & Protection** | ~6% | Snubber values |
| **8** | **Power Factor & Harmonics** | ~5% | IPF, THD |
| **9** | **Dual Converters** | ~4% | Four-quadrant operation |
| **10** | **PWM Techniques** | ~4% | Harmonic elimination |

---

## 📌 Quick Reference Card (Exam Day)

| Converter | Formula | Quick Tip |
| :--- | :--- | :--- |
| **1-Φ Full Bridge** | `V_o = (2V_m/π)cosα` | Continuous conduction |
| **1-Φ Semi Converter** | `V_o = (V_m/π)(1+cosα)` | Discontinuous for α > 0 |
| **3-Φ Full Converter** | `V_o = (3V_m/π)cosα` | 6-pulse output |
| **Buck Chopper** | `V_o = D V_s` | Step-down only |
| **Boost Chopper** | `V_o = V_s/(1-D)` | Step-up only |
| **Buck-Boost** | `V_o = -D V_s/(1-D)` | Inverts polarity |
| **1-Φ Inverter Fundamental** | `V_o1 = (4V_s/π)sinωt` | Square wave output |
| **3-Φ Inverter Line V (180°)** | `V_LL = V_s` (peak) | Quasi-square wave |
| **AC Voltage Controller** | `V_o_rms = V_s √[(π-α + sin2α/2)/π]` | Resistive load |
| **SCR di/dt protection** | `L = V_s/(di/dt)` | Choose L ≥ this value |
| **SCR dV/dt protection** | `C = I_c/(dV/dt)` | Snubber capacitor |
| **Latching Current** | Minimum anode current to turn on | Gate pulse must be wide enough |

---

# 📝 EMBEDDED PYQs — Ohm Institute PDF (GENCO/TRANSCO/DISCOMs)

> Source: Study_Material__GTD_PYQs_2026_05_26_7_Power_Electronics_.pdf  
> Contains ~482 PYQs across 6 units. Selected representative Qs below.

---

## Topic 1: Power Semiconductor Devices (SCR, IGBT, MOSFET, GTO, TRIAC)

**Q1 (EPDCL-10):** The terms "anode and cathode" are NOT applicable to:
(a) SCR &emsp; (b) Diode &emsp; (c) Triac &emsp; (d) GTO  
**Answer: (c)** — Triac uses MT1/MT2 terminals

**Q3 (EPDCL-10):** Depletion capacitance of SCR = 30 pF, dv/dt = 150 V/μs. Capacitive current?
(a) 4.0 mA &emsp; (b) 4.5 mA &emsp; (c) 5.0 mA &emsp; (d) 5.5 mA  
**Solution:** `Ic = C × dv/dt = 30×10⁻¹² × 150×10⁶ = 4.5×10⁻³ = 4.5 mA`  
**Answer: (b)**

**Q5 (APGenco-12):** Latching current of SCR T1 = 1 mA, RL in series with 0.2H, source 200V. Minimum gate pulse width?
(a) 2 μs &emsp; (b) 1 μs &emsp; (c) 0.5 μs &emsp; (d) 1.5 μs  
**Solution:** `τ = L/R = 0.2/200 = 1 ms`. For RL circuit: `i(t) = V/R(1-e^(-t/τ))`.  
At t where i = 1 mA: `0.001 = 200/R(1-e^(-t/0.001))`. For large R: `t = L×I_lat/V = 0.2×0.001/200 = 1×10⁻⁶ = 1 μs`  
**Answer: (b) 1 μs**

**Q7 (Transco-12):** SCR turns ON when:
(a) Anode-cathode voltage positive  
(b) Anode-cathode voltage negative  
(c) Positive current applied to gate  
(d) Anode positive AND positive gate pulse  
**Answer: (d)** — Both conditions must be satisfied

**Q12 (Transco-12):** Purpose of snubber circuit across SCR:
(a) Eliminate dv/dt &emsp; (b) Increase dv/dt  
(c) Reduce dv/dt &emsp; (d) Keep transient overvoltage constant  
**Answer: (c)** — Snubber (RC) limits dv/dt across SCR

**Q13 (EPDCL-14):** Main advantage of IGBT over SCR:
(a) Reduced weight &emsp; (b) Self-commutating capability  
(c) Very high reliability &emsp; (d) Self-cooling  
**Answer: (b)** — IGBT can be turned off by gate signal; SCR requires commutation

**Q14 (APSPDCL-14):** 10 thyristors in string, total 15 kV. Worst-case steady state = 1800 V per thyristor. Derating factor?
(a) 33.3% &emsp; (b) 15.5% &emsp; (c) 23.3% &emsp; (d) 16.66%  
**Solution:** Ideal V per thyristor = 15000/10 = 1500V. Actual rating used = 1800V.  
DF = (1800-1500)/1800 × 100 = 300/1800 × 100 = **16.66%**  
**Answer: (d)**

**Q21 (TSNPDCL-15):** 240V DC supply, SCR di/dt limit = 50 A/μs. Minimum L for di/dt protection?
(a) 2.4 μH &emsp; (b) 120 μH &emsp; (c) 1.2 μH &emsp; (d) 4.8 μH  
**Solution:** `L = V/(di/dt) = 240/(50×10⁶) = 4.8×10⁻⁶ H = 4.8 μH`  
**Answer: (d)**

**Q29 (APEPDCL-19):** θ_JA = 2.5°C/W, TJ = 25°C. P_D(max) at 150°C?
(a) 150 W &emsp; (b) 100 W &emsp; (c) 75 W &emsp; (d) 50 W  
**Solution:** `P_D = (TJ_max - TA)/θ_JA = (150-25)/2.5 = 125/2.5 = 50 W`  
**Answer: (d)**

---

## Topic 2: AC-DC Converters (Rectifiers)

**Q1 (EPDCL-10):** PIV of each diode in bridge rectifier:
(a) Vm &emsp; (b) 2Vm &emsp; (c) Vm/2 &emsp; (d) Vm/√2  
**Answer: (a)** — Bridge rectifier PIV = Vm (half of center-tap)

**Q7 (APGenco-12):** 1-φ fully controlled bridge, α = 60°, Vs = 230V (RMS). Average output voltage?
(a) 103.5 V &emsp; (b) 207 V &emsp; (c) 0 V &emsp; (d) 155.7 V  
**Solution:** `Vm = 230√2 = 325.27V`, `Vdc = (2Vm/π)cosα = (2×325.27/π)×cos60° = 207×0.5 = 103.5V`  
**Answer: (a) 103.5 V**

**Q15 (APSPDCL-14):** 1-φ full converter, Vs=230V, α=45°, continuous conduction. Average output voltage?
`Vdc = (2Vm/π)cosα = (2×230√2/π)×0.707 = (207)×0.707 = 146.4 V`

**Q22 (TSNPDCL-15):** 3-φ fully controlled bridge converter, α=30°, supply=415V (L-L). Vdc?
**Solution:** `Vdc = (3Vm/π)cosα` where Vm = peak phase voltage  
`Vm = 415√2/√3 = 338.8V`, `Vdc = (3×338.8/π)×cos30° = (323.5)×0.866 = 280.2 V`

**Q35 (APGenco-17):** In a 1-φ full converter, output voltage waveform has ___ pulses per cycle:
(a) 1 &emsp; (b) 2 &emsp; (c) 4 &emsp; (d) 6  
**Answer: (b)** — 2 pulses for 1-φ full converter

---

## Topic 3: DC-DC Converters (Choppers)

**Q1 (EPDCL-10):** In step-down chopper, output voltage can be controlled by varying:
(a) Duty cycle &emsp; (b) Frequency &emsp; (c) Both &emsp; (d) Load  
**Answer: (a)** — Vdc = D×Vs

**Q3 (APGenco-12):** Step-down chopper, Vs = 200V, D = 0.4, load R = 5Ω. Find output power.
**Solution:** `Vdc = D×Vs = 0.4×200 = 80V`, `P = Vdc²/R = 6400/5 = 1280 W`

**Q8 (TSTransco-15):** Boost chopper, Vs = 12V, D = 0.6. Output voltage?
(a) 30V &emsp; (b) 20V &emsp; (c) 15V &emsp; (d) 7.2V  
**Solution:** `Vo = Vs/(1-D) = 12/(1-0.6) = 12/0.4 = 30V`  
**Answer: (a)**

**Q15 (TSNPDCL-15):** Buck-boost chopper, Vs=24V, D=0.25. Output?
(a) 6V &emsp; (b) -6V &emsp; (c) -8V &emsp; (d) 8V  
**Solution:** `Vo = -D×Vs/(1-D) = -0.25×24/0.75 = -8V`  
**Answer: (c)**

**Q24 (APTransco-17):** Chopper frequency doubled, keeping D same. Effect on ripple?
Ripple ΔIL = VsDT/L → unchanged if D and T constants adjust. But ripple frequency doubles → easier to filter.

---

## Topic 4: DC-AC Converters (Inverters)

**Q1 (EPDCL-10):** For 1-φ full bridge inverter, Vs=200V. Fundamental RMS output?
**Solution:** `V₁(rms) = (2√2/π)×Vs = (2×1.414/3.14)×200 = 180 V`

**Q3 (APGenco-12):** In 3-φ inverter, 180° conduction mode. Line voltage peak =?
(a) Vs &emsp; (b) Vs/2 &emsp; (c) Vs/√3 &emsp; (d) Vs√3  
**Answer: (a)** — In 180° mode, peak line voltage = Vs

**Q7 (APSPDCL-12):** The output waveform with half-cycle symmetry, fundamental eliminated when pulse width =:
`Eliminate nth harmonic when pulse width = 2π/n`

**Q17 (APGenco-17):** PWM inverter advantages over square wave:
(a) Lower THD &emsp; (b) Higher fundamental &emsp; (c) Simpler control &emsp; (d) Lower cost  
**Answer: (a)** — PWM significantly reduces harmonic content

**Q31 (APEPDCL-19):** VSI vs CSI — VSI has ___ impedance source:
(a) Low &emsp; (b) High &emsp; (c) Zero &emsp; (d) Infinite  
**Answer: (a)** — VSI = voltage source (low impedance)

---

## Topic 5: AC-AC Converters

**Q1 (EPDCL-10):** 1-φ AC voltage controller, RL load. The output is controlled by varying:
(a) Firing angle α &emsp; (b) Duty cycle &emsp; (c) Frequency &emsp; (d) Supply voltage  
**Answer: (a)**

**Q4 (APSPDCL-14):** 1-φ AC voltage controller, Vs=230V(rms), R load, α=90°. Vrms output?
**Solution:** `Vo(rms) = Vs√[(π-α+sin2α/2)/π] = 230√[(π-π/2+0)/π] = 230√(0.5) = 162.6 V`

**Q7 (TSNPDCL-15):** Cycloconverter: Output frequency compared to input?
(a) Always lower &emsp; (b) Always higher &emsp; (c) Same &emsp; (d) Any  
**Answer: (a)** — Step-down cycloconverter: f_out < f_in

---

## Topic 6: Electric Drives

**Q1 (EPDCL-10):** An electric drive has ___ main components:
(a) 2 &emsp; (b) 3 &emsp; (c) 4 &emsp; (d) 5  
**Answer: (b)** — Source, power converter, motor + load

**Q9 (TSNPDCL-15):** For constant torque application (below base speed), V/f control maintains:
(a) T ∝ V²/f² &emsp; (b) T = constant &emsp; (c) P = constant &emsp; (d) T ∝ f  
**Answer: (a)** — With V/f constant, flux constant → torque constant

**Q17 (APGenco-17):** In regenerative braking of DC motor fed by chopper:
(a) Power flows from motor to source &emsp; (b) Motor draws current  
(c) Chopper acts as rectifier &emsp; (d) Speed decreases slowly  
**Answer: (a)** — Regeneration returns energy to source

---

> **Total embedded PYQs: 28 (selected from ~482 Power Electronics questions)**

---