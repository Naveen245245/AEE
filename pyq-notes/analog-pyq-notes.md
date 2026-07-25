# Analog Electronics — PYQ Notes from Ohm Institute PDF

**Source:** Study_Material__GTD_PYQs_2026_05_26_5_Analog_Circuits_PD.pdf  
**Total Questions Analyzed:** ~425 across 4 units  
**Topics:** Diodes → BJT/JFET/MOSFET → Op-Amp → Oscillators & Multivibrators

---

## 📊 Formula/Concept vs. Question Count Analysis

| S.No | Formula / Concept | No. of Qs | Key Formula |
| :---: | :--- | :---: | :--- |
| 1 | **Diode Circuits** (Rectifiers, Clippers, Clampers) | ~100 | V_dc=2V_m/π, r_d=V_T/I_D, PIV=V_m(bridge) |
| 2 | **BJT** (Biasing, Amplifiers, CE/CB/CC) | ~90 | I_C=βI_B, g_m=I_C/V_T, A_V=-g_mR_C |
| 3 | **JFET & MOSFET** (Characteristics, Biasing) | ~60 | I_D=I_DSS(1-V_GS/V_p)², voltage-controlled |
| 4 | **Op-Amp** (Inverting, Non-inv, Integrator, Diff) | ~80 | V_out = -(R_f/R_in)V_in, virt. short |
| 5 | **Oscillators** (Barkhausen, RC, LC, Crystal) | ~30 | Aβ=1, ∠Aβ=0° at oscillation freq |
| 6 | **Power Amplifiers** (Class A, B, AB, C) | ~25 | η_max(A)=25%, η_max(B)=78.5% |
| 7 | **Multivibrators** (555 Timer, Astable, Mono) | ~20 | T=1.1RC(mono), f=1.44/(R₁+2R₂)C |
| 8 | **Feedback Amplifiers** | ~20 | A_f = A/(1+Aβ), negative/positive feedback |

---

## 📌 Quick Reference Card (Exam Day)

| Concept | Formula | Tip |
| :--- | :--- | :--- |
| **Si/Ge knee** | Si=0.7V, Ge=0.3V | Forward voltage |
| **r_d (dynamic)** | r_d = 26mV/I_D(mA) | From diode equation |
| **HWR V_dc** | V_m/π | Ripple=1.21 |
| **FWR V_dc** | 2V_m/π | Ripple=0.48, PIV=2V_m(CT), V_m(bridge) |
| **Filter cap ripple** | V_r = I_load/(2fC) | For FWR |
| **BJT CE gain** | A_V = -g_mR_C | g_m = I_C/V_T |
| **JFET type** | Voltage-controlled | B_junction reverse biased |
| **Ideal Op-Amp** | Z_in=∞, Z_out=0, A=∞ | Virtual short: V+=V- |
| **Inverting** | V_out/V_in = -R_f/R_in | |
| **Non-inverting** | V_out/V_in = 1+R_f/R_in | |
| **Barkhausen** | Aβ=1, ∠Aβ=0 | Oscillation condition |
| **Class B η_max** | π/4 = 78.5% | Push-pull, crossover distortion |
| **555 Mono T** | T = 1.1 RC | Single pulse |
| **555 Astable f** | f = 1.44/(R₁+2R₂)C | Square wave |

---

# 📝 EMBEDDED PYQs — Ohm Institute PDF

> Source: Study_Material__GTD_PYQs_2026_05_26_5_Analog_Circuits_PD.pdf  
> ~425 PYQs across 4 units. Selected representative Qs below.

---

## Topic 1: Diode Circuits & Applications

**Q1 (EPDCL-10):** Ideal diode is characterized as:
(a) Infinite R &emsp; (b) Zero R &emsp; (c) 10MΩ &emsp; (d) 1kΩ  
**Answer: (b)** — Ideal diode: R=0 (forward), R=∞ (reverse)

**Q2 (EPDCL-10):** Knee voltage of silicon diode:
(a) 1.0V &emsp; (b) 0.7V &emsp; (c) 0.7mV &emsp; (d) 0.3V  
**Answer: (b) 0.7V**

**Q4 (AP Genco-12):** Dynamic resistance of Ge diode at 1mA forward bias:
**Solution:** r_d = V_T/I_D = 26mV/1mA = **26Ω. Answer: (d)**

**Q9 (SSC-JE-S1-14):** Cut-in voltages of Si and Ge:
(a) Si=0.6V, Ge=0.2V &emsp; (b) Si=0.7V, Ge=0.3V  
(c) Si=0.3V, Ge=0.7V &emsp; (d) Si=0.2V, Ge=0.6V  
**Answer: (b)**

**Q12 (HMWS-15):** Device using Hall effect measures:
(a) Magnetic flux &emsp; (b) Magnetic flux density  
(c) Electric charge &emsp; (d) Electric flux density  
**Answer: (b)** — Hall effect: V_H = (R_H)(I×B)/d → measures B

**Q13 (SSC-JE-S1-14):** Bridge rectifier advantage over center-tap FWR:
(a) Higher current &emsp; (b) Lower PIV requirement  
(c) Lower ripple &emsp; (d) Higher efficiency  
**Answer: (b)** — Bridge PIV=Vm, center-tap PIV=2Vm

**Q14 (APSPDCL-12):** FWR ripple voltage with C=100μF filter, I_load=50mA:
**Solution:** V_r = I_load/(2fC) = 0.05/(2×50×100×10⁻⁶) = 0.05/0.01 = **5V**

**Q17 (HMWS-15):** Zener diode operates in:
(a) Forward bias &emsp; (b) Reverse breakdown region  
(c) Cutoff &emsp; (d) Saturation  
**Answer: (b)**

---

## Topic 2: BJT, JFET & MOSFET

**Q1 (EPDCL-10):** Voltage gain of BJT CE amplifier:
(a) A_V = -g_mR_C &emsp; (b) A_V = g_mR_E  
(c) A_V = R_C/r_π &emsp; (d) A_V = βR_C/R_in  
**Answer: (a)** — CE gain = -gmR_C

**Q2 (EPDCL-10):** JFET is a:
(a) Voltage-controlled device &emsp; (b) Current-controlled device  
(c) Resistance-controlled &emsp; (d) Conductance-controlled  
**Answer: (a)**

**Q3 (AP Genco-12):** Thermal runaway not possible in FET because as T↑:
(a) Mobility↑ &emsp; (b) Mobility↓ → I_D↓ → P_D↓  
(c) Drain current↑ &emsp; (d) Transconductance↑  
**Answer: (b)** — Negative temp coefficient → self-limiting

**Q5 (APSPDCL-12):** Pinch-off voltage of JFET = 5V. Cut-off voltage = ?
(a) 5V &emsp; (b) 2.5V &emsp; (c) 5.0V &emsp; (d) 0.5V  
**Answer: (a)** — For JFET, V_GS(off) = V_p (magnitude same)

**Q7 (HMWS-12):** In RC coupled CE amplifier:
(a) Coupling cap affects HF, bypass cap affects LF  
(b) Both affect LF &emsp; (c) Both affect HF  
(d) Coupling cap affects LF, bypass cap affects HF  
**Answer: (d)** — Coupling caps cause LF roll-off, bypass caps affect HF

**Q9 (TRANSCO-AE-12):** NMOS, V_th=1V, find V_ab in given circuit:
Biased with V_GS > V_th, MOSFET in saturation. V_ab = V_DS = depends on circuit values.
**For ideal NMOS with gate and drain tied:** V_ab = V_GS. When V_GS > V_th, MOSFET ON.

**Q13 (TSSPDCL-15):** MOSFET is a:
**Answer:** Voltage-controlled device (like JFET)

---

## Topic 3: Op-Amp

**Q1 (EPDCL-10):** Ideal Op-Amp has:
(a) Infinite Z_in &emsp; (b) Infinite Z_out &emsp; (c) Small gain &emsp; (d) Small bandwidth  
**Answer: (a)** — Z_in=∞, Z_out=0, A_OL=∞

**Q3 (APSPDCL-12):** Inverting amplifier, R_in=1kΩ, R_f=10kΩ, V_in=2V. V_out = ?
**Answer:** V_out = -(R_f/R_in)V_in = -(10/1)×2 = **-20V**

**Q5 (HMWS-12):** Op-Amp integrator output for DC input:
(a) Ramp &emsp; (b) Constant &emsp; (c) Zero &emsp; (d) Exponential  
**Answer: (a)** — For constant DC input, integrator gives linear ramp: V_out = -(1/RC)∫V_in·dt

**Q8 (TRANSCO-AE-12):** Op-Amp as voltage follower. Purpose:
(a) High input impedance buffer &emsp; (b) Voltage amplification  
(c) Current amplification &emsp; (d) Phase inversion  
**Answer: (a)** — Unity gain buffer, Z_in≈∞, Z_out≈0

**Q13 (TSNPDCL-15):** Differential amplifier CMRR definition:
(a) A_d/A_c &emsp; (b) A_c/A_d &emsp; (c) A_d×A_c &emsp; (d) A_d + A_c  
**Answer: (a)** — CMRR = A_dm/A_cm (higher is better)

**Q15 (TSSPDCL-18):** Op-Amp comparator: If V+ > V-, output:
(a) +V_sat &emsp; (b) -V_sat &emsp; (c) 0 &emsp; (d) Midpoint  
**Answer: (a)** — Comparator saturates to positive rail

**Q20 (APEPDCL-19):** Summing amplifier: R_1=R_2=R_f=10kΩ, V1=1V, V2=2V. V_out = ?
**Answer:** V_out = -R_f(V1/R1+V2/R2) = -10k(1/10k+2/10k) = **-3V**

---

## Topic 4: Oscillators, Multivibrators & Power Amplifiers

**Q1 (SSC-JE-10):** An oscillator uses:
(a) Positive feedback &emsp; (b) Negative feedback  
(c) Both &emsp; (d) No feedback  
**Answer: (a)**

**Q2 (EPDCL-10):** Pulse generator is:
(a) Astable MV &emsp; (b) Monostable MV &emsp; (c) Bistable MV &emsp; (d) Schmitt trigger  
**Answer: (a)** — Astable multivibrator generates continuous square wave

**Q3 (APSPDCL-12):** Class B amplifier η for V_CC=24V, peak-to-peak output=6V:
(a) 4% &emsp; (b) 48% &emsp; (c) 19.5% &emsp; (d) 39.2%  
**Solution:** η = (π/4)×(V_pp/2)/V_CC = 0.785×3/24 = **9.8%** — Not matching given options exactly; theoretical max for class B = 78.5%

**Q5 (APSPDCL-12):** 555 monostable: T=100ms, R=100kΩ. Find C:
**Solution:** T = 1.1RC → C = 0.1/(1.1×100×10³) = 0.1/110000 = **0.91 μF ≈ 0.9 μF. Answer: (b)**

**Q7 (EPDCL-14):** Barkhausen criterion:
(a) Aβ = 1 &emsp; (b) A = β &emsp; (c) Aβ = -1 &emsp; (d) Aβ = 0  
**Answer: (c) A·β = 1 with 0° phase shift** (or A·β = -1 for 180° shift per stage in some texts — key point: |Aβ|=1)

**Q8 (SSPDCL-14):** Max conversion efficiency of Class B push-pull:
(a) 78.5% &emsp; (b) 50% &emsp; (c) 25% &emsp; (d) 100%  
**Answer: (a) π/4 = 78.5%**

**Q9 (APSPDCL-12):** Voltage to frequency converter is:
(a) Bistable &emsp; (b) Astable &emsp; (c) Monostable &emsp; (d) Schmitt trigger  
**Answer: (d) — Actually:** VCOs use astable principle. In context: Schmitt trigger used in VCOs for wave shaping.

**Q13 (TSNPDCL-15):** PLL free running frequency:
f_r = 1/(3R_T × C_T) × 10⁴ (for 565 PLL typical)

---

> **Total embedded PYQs: 28 (selected from ~425 Analog Electronics questions)**

---

> **Last Updated:** July 25, 2026 — Embedded PYQs from Ohm PDF
> **Use alongside:** AP_AEE_STUDY_NOTES.md Section S12 for concept review
