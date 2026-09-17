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

<table>
  <colgroup>
    <col width="4%">
    <col width="60%">
    <col width="4%">
    <col width="11%">
    <col width="14%">
    <col width="7%">
  </colgroup>
  <thead>
    <tr>
      <th>S.No</th>
      <th>Formula / Concept</th>
      <th>No. of Qs</th>
      <th>What They GIVE in the Question</th>
      <th>What They ASK in the Question</th>
      <th>Mapped Question Numbers</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>1</strong></td>
      <td><strong>AC-DC Converters (Rectifiers)</strong> <br> 1-Φ Half wave: <code>V_o = V_m/(2π)(1 + cosα)</code> <br> 1-Φ Full wave: <code>V_o = (2V_m/π)cosα</code> <br> 1-Φ Semi: <code>V_o = (V_m/π)(1 + cosα)</code> <br> 3-Φ Full: <code>V_o = (3√3V_m/π)cosα</code> <br> <code>PIV = V_m</code> (Bridge), <code>PIV = 2V_m</code> (Mid-point) <br> <code>I_rms(thyristor) = I_o/√3</code> (3-Φ full)</td>
      <td><strong>~25</strong></td>
      <td>Supply voltage, Firing angle (α), Load (R, RL, RLE), Source inductance.</td>
      <td><strong>Average output voltage</strong>, <strong>RMS output voltage</strong>, <strong>PIV</strong> of diode/SCR, <strong>RMS current</strong> through SCR, <strong>Displacement power factor</strong>, <strong>Effect of source inductance</strong>.</td>
      <td>Q1-Q67</td>
    </tr>
    <tr>
      <td><strong>2</strong></td>
      <td><strong>DC-DC Converters (Choppers)</strong> <br> Step-down (Buck): <code>V_o = D V_s</code> <br> Step-up (Boost): <code>V_o = V_s / (1-D)</code> <br> Buck-Boost: <code>V_o = -D V_s / (1-D)</code> <br> <code>ΔI_L = (V_s D T) / L</code> <br> <code>ΔV_C = (I_o D T) / C</code> <br> Ripple factor: <code>√(1/D - 1)</code></td>
      <td><strong>~18</strong></td>
      <td>Input voltage (V_s), Duty cycle (D), Switching frequency, L, C, Load.</td>
      <td><strong>Average output voltage</strong>, <strong>Ripple current/voltage</strong>, <strong>Duty cycle for desired output</strong>, <strong>Chopper type/quadrant</strong>.</td>
      <td>Q1-Q34</td>
    </tr>
    <tr>
      <td><strong>3</strong></td>
      <td><strong>DC-AC Converters (Inverters)</strong> <br> 1-Φ Full bridge fundamental: <code>V_o1 = (4V_s/π)sin(ωt)</code> <br> RMS fundamental: <code>V_o1_rms = (2√2/π)V_s</code> <br> 3-Φ Line voltage (180° mode): <code>V_LL = V_s</code> (peak) <br> Harmonic elimination: Pulse width for nth harmonic = <code>2π/n</code> <br> THD definition</td>
      <td><strong>~12</strong></td>
      <td>DC input voltage, Modulation index, Switching frequency, Load (R, RL, RLC).</td>
      <td><strong>Fundamental output voltage</strong>, <strong>Harmonic elimination</strong>, <strong>THD</strong>, <strong>Conduction mode (120°/180°)</strong>, <strong>VSI vs CSI</strong>.</td>
      <td>Q1-Q31</td>
    </tr>
    <tr>
      <td><strong>4</strong></td>
      <td><strong>AC-AC Converters</strong> <br> AC Voltage Controller: <code>V_o_rms = V_s √[(π-α + sin2α/2)/π]</code> <br> Cycloconverter: Output frequency &lt; Input frequency (Step-down)</td>
      <td><strong>~6</strong></td>
      <td>Input voltage, Firing angle, Load, Output frequency.</td>
      <td><strong>RMS output voltage</strong>, <strong>Input power factor</strong>, <strong>Output frequency</strong>, <strong>Cycloconverter type</strong>.</td>
      <td>Q1-Q12</td>
    </tr>
    <tr>
      <td><strong>5</strong></td>
      <td><strong>Power Semiconductor Devices</strong> <br> <code>di/dt = V/L</code> <br> <code>dV/dt = V/(RC)</code> <br> <code>I_c = C_j (dV/dt)</code> <br> <code>P_D = (T_J - T_A)/θ_JA</code> <br> <code>I_rms = I_p × √(D)</code> (various waveforms)</td>
      <td><strong>~16</strong></td>
      <td>Device ratings, Snubber circuit values, Temperature, Gate pulse.</td>
      <td><strong>di/dt protection</strong> (L value), <strong>dV/dt protection</strong> (C/R value), <strong>Latching/Holding current</strong>, <strong>Power dissipation</strong>, <strong>Device identification</strong>.</td>
      <td>Q1-Q50</td>
    </tr>
    <tr>
      <td><strong>6</strong></td>
      <td><strong>Electric Drives (DC &amp; AC)</strong> <br> <code>P = T × ω</code> <br> <code>E_b = V_t - I_a R_a</code> <br> <code>N ∝ E_b / φ</code> <br> <code>THD = √(I_h²) / I_1</code></td>
      <td><strong>~14</strong></td>
      <td>Motor ratings, Converter output, Torque, Speed.</td>
      <td><strong>Motor speed</strong> with converter, <strong>Back EMF</strong>, <strong>Torque</strong>, <strong>Harmonics</strong>, <strong>Drive quadrant operation</strong>.</td>
      <td>Q1-Q28</td>
    </tr>
    <tr>
      <td><strong>7</strong></td>
      <td><strong>Commutation &amp; Protection</strong> <br> <code>L = V_s / (di/dt)</code> <br> <code>R = 0.5√(L/C)</code> (for resistance switching) <br> <code>V = i√(L/C)</code> (voltage across CB)</td>
      <td><strong>~8</strong></td>
      <td>Snubber values, Source inductance, Current.</td>
      <td><strong>Snubber component values</strong>, <strong>Voltage across breaker</strong>, <strong>Commutation circuit</strong> analysis.</td>
      <td>Q3, Q21, Q27, Q28, Q30, Q31, Q36, Q45, Q80, Q87, Q90, Q93, Q101</td>
    </tr>
    <tr>
      <td><strong>8</strong></td>
      <td><strong>Power Factor &amp; Harmonics</strong> <br> <code>IPF = (DF) / √(1 + THD²)</code> <br> <code>DF = cosφ₁</code> <br> <code>THD = √(1/DF² - 1)</code></td>
      <td><strong>~6</strong></td>
      <td>Input power factor, Displacement factor, THD.</td>
      <td><strong>Input power factor</strong>, <strong>Displacement factor</strong>, <strong>Total Harmonic Distortion</strong>.</td>
      <td>Q14, Q16, Q23, Q59, Q63, Q65</td>
    </tr>
  </tbody>
</table>

**🔗 The Bridge — GIVEN/ASKED → Formula:**
> **GIVEN picks the formula family** (1-Φ vs 3-Φ, full vs semi, R vs RL) · **ASKED picks the formula** (V_o, PIV, I_rms, PF…).

| GIVEN (circuit) | ASKED (quantity) | Formula |
| :--- | :--- | :--- |
| 1-Φ full bridge | Avg output V_o | (2Vm/π)cosα |
| 1-Φ semi · R load α>90° | Avg output V_o | (Vm/π)(1+cosα) |
| 3-Φ full | Avg output V_o | (3√3/π)Vm·cosα |
| 3-Φ half-wave | Avg output V_o | (3√3/2π)Vm·cosα |
| 3-Φ semi | Avg output V_o | (3√3/2π)Vm(1+cosα) |
| Any rectifier | PIV | Vm (bridge) / 2Vm (mid-pt) |
| 3-Φ full | I_rms per SCR | I_o/√3 (conducts 120°) |
| With source Ls | Output drop ΔV | 3ωLs·Id/π (3-Φ) · 2ωLs·Id/π (1-Φ) |
| Any | Displacement PF | cosα |

---

## 🧭 The 5-Question Decision Flowchart

| Step | Question to Ask | If YES → | If NO → |
| :---: | :-------------------------------------------------------------- | :--- | :--- |
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
| :---: | :-------------------------------------------------------------- | :---: | :--- |
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
| **3-Φ Full Converter** | `V_o = (3√3V_m/π)cosα` | 6-pulse output |
| **3-Φ Half-Wave** | `V_o = (3√3/2π)Vm·cosα` | 3-pulse |
| **3-Φ Semi-Converter** | `V_o = (3√3/2π)Vm(1+cosα)` | 3-pulse |
| **R-load boundary** | 3-Φ continuous only α≤60° · 1-Φ only α≤90° | beyond → (Vm/π)(1+cosα) |
| **Source inductance** | `ΔV = 3ωLs·Id/π` (3-Φ) | output falls |
| **RLE + freewheel diode** | `V_o = (Vm/π)(1+cosα)` | PF↑, no reverse current |
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

# 📝 FULL PYQ ANALYSIS — All 222 Questions (Concept through PYQ)

> Source: Study_Material__GTD_PYQs_2026_05_26_7_Power_Electronics_.pdf (OHM Institute — GENCO/TRANSCO/DISCOMs/TSPSC/APPSC)
> Every question: answer + options, the concept it teaches, and how the examiner twists it.

**Legend:** Q = question · Ans = correct option · Concept = new term/principle · Twist = examiner variation → new answer

## Unit 1: Basics of Power Semiconductor Devices (50 Qs)

**Q1 (EPDCL-10):** The terms anode and cathode are not applicable to
(a) SCR (b) Diode (c) Triac (d) GTO
**Ans: (c)** — Triac uses MT1/MT2 terminals, not anode/cathode.
**Concept:** Terminal naming: SCR/GTO have anode-cathode-gate; Diode has anode-cathode; Triac has MT1-MT2-gate.
**Twist:** ask where anode/cathode DO apply → SCR, GTO, Diode. ask the triac's main-terminal name → MT1/MT2.

**Q2 (EPDCL-10):** The rectifier-mode operation of triac can be overcome by increasing
(a) anode current (b) gate current (c) holding current (d) latching current
**Ans: (b)** — insufficient gate current lets a triac fire only in one quadrant (rectifier mode); raising gate current restores bidirectional firing.
**Concept:** Triac gate sensitivity / quadrant-firing limitation.
**Twist:** cause of rectifier-mode → gate current too low for the negative-MT2 quadrant. constant negative gate current fires III but not I → increase gate current.

**Q3 (EPDCL-10):** The equivalent capacitance of the depletion layer of a reverse-biased junction of an SCR is 30 pF, fired with a dv/dt of 150 V/μs. The capacitive current flowing through the junction is
(a) 4.0 mA (b) 4.5 mA (c) 5.0 mA (d) 5.5 mA
**Ans: (b)** — Ic = Cj·dv/dt = 30e-12 × 150e6 = 4.5 mA.
**Concept:** Capacitive current through junction capacitance Ic = Cj·(dV/dt).
**Twist:** dv/dt doubled to 300 V/μs → 9 mA. Cj doubled to 60 pF → 9 mA.

**Q4 (EPDCL-10):** JFET is
(a) voltage-controlled device (b) current controlled device (c) resistance-controlled device (d) conductance-controlled device
**Ans: (a)** — JFET is a voltage-controlled device (VGS controls ID).
**Concept:** JFET = voltage-controlled; also works as a voltage-variable resistor.
**Twist:** ask BJT → current-controlled. ask which device behaves as a voltage-variable resistor → JFET (see Q15).

**Q5 (APGenco-12):** The latching current of T1 is 1 mA. The minimum width of gate pulse required to turn on the SCR is — figure: SCR T1 in series with RL and 0.2H, 200 V DC supply
(a) 2 μs (b) 1 μs (c) 0.5 μs (d) 1.5 μs
**Ans: (b)** — pulse width = L·Ilat/Vdc = 0.2 × 1e-3 / 200 = 1 μs.
**Concept:** Minimum gate-pulse width = L·Ilatching/Vdc (anode current must reach latching value in an inductive circuit).
**Twist:** L doubled to 0.4 H → 2 μs. Vdc halved to 100 V → 2 μs.

**Q6 (Transco-12):** A thyristor (SCR) turns off when the
(a) Gate pulse is removed (b) Gate pulse is applied (c) Thyristor current is below holding value (d) Anode voltage is made negative
**Ans: (c)** — turn-off needs anode current below holding current (and/or reverse bias).
**Concept:** Holding current = turn-off condition; gate loses control once latched.
**Twist:** ask what turns SCR on → latching current + forward bias + gate pulse (Q7). ask the current that must fall below for turn-off → holding current (Q32).

**Q7 (Transco-12):** Turn-on of a thyristor (SCR) takes place when
(a) Anode-cathode voltage is positive (b) Anode-cathode voltage is negative (c) Positive current is applied to gate (d) Anode-cathode positive AND positive gate pulse
**Ans: (d)** — needs forward bias plus a suitable positive gate current.
**Concept:** SCR turn-on conditions (forward bias + gate pulse).
**Twist:** forward-biased but no gate → no turn-on unless breakover/overvoltage. gate applied while reverse-biased → no turn-on.

**Q8 (Transco-12):** A triac is a device which acts as a
(a) Diode in forward and thyristor in reverse (b) Thyristor in both directions (c) Diode in both directions (d) Thyristor in forward and diode in reverse
**Ans: (b)** — triac = two thyristors in antiparallel, conducts in both directions.
**Concept:** Triac = two SCRs in antiparallel (back-to-back), bidirectional.
**Twist:** ask functional equivalence → two antiparallel thyristors (Q34, Q39). ask conduction capability → bidirectional current with bidirectional voltage blocking.

**Q9 (Transco-12):** A GTO
(a) Requires a special turn-off circuit like the commutation circuit of an SCR (b) Can be turned off by removing the gate pulse (c) Can be turned off by giving a negative pulse to the gate (d) Can be turned off by giving a positive gate pulse to the gate
**Ans: (c)** — GTO is turned off by a negative gate current.
**Concept:** GTO gate-assisted turn-off (unlike SCR).
**Twist:** ask SCR turn-off → cannot be gated off, needs commutation. ask self-commutating devices → GTO/IGBT/MOSFET (Q13).

**Q10 (Transco-12):** Which power device of the following is NOT a current-triggered device?
(a) Thyristor (b) GTO (c) Triac (d) MOSFET
**Ans: (d)** — MOSFET is voltage-triggered; the rest are current-triggered.
**Concept:** Current-triggered (SCR, GTO, triac, BJT) vs voltage-triggered (MOSFET, IGBT, JFET).
**Twist:** ask which IS current-triggered → thyristor/GTO/triac. ask IGBT → voltage-controlled (Q26, Q49).

**Q11 (Transco-12):** The number of p-n junctions in a thyristor is
(a) 1 (b) 2 (c) 3 (d) 4
**Ans: (c)** — SCR is a 3-junction, 4-layer (PNPN), 3-terminal device.
**Concept:** SCR structure: 4 layers → 3 junctions.
**Twist:** ask number of layers → 4. ask number of terminals → 3.

**Q12 (Transco-12):** The purpose of a snubber circuit across an SCR is to
(a) Eliminate dv/dt (b) Increase dv/dt (c) Reduce dv/dt (d) Keep transient over-voltage at a constant value
**Ans: (c)** — snubber protects against dv/dt (and di/dt) by reducing dv/dt.
**Concept:** RC snubber = dv/dt limiting.
**Twist:** di/dt protection → series inductor. general purpose → reduce electrical stresses (Q23, Q36).

**Q13 (EPDCL-14):** The main advantage of IGBT over SCR in power electronics
(a) Reduced weight (b) Self-commutating capability (c) Very high reliability (d) Self-cooling property
**Ans: (b)** — IGBT is self-commutating; SCR needs external commutation.
**Concept:** Self-commutating (gate-controlled turn-off) devices.
**Twist:** IGBT vs BJT advantage → high input impedance (MOS gate). MOSFET vs BJT advantage → no minority-carrier storage, faster (Q50).

**Q14 (APSPDCL-14):** Ten thyristors are used in a string to withstand a dc voltage of 15 kV. The worst-case steady-state voltage across a thyristor is 1800 V. The derating factor is
(a) 33.3% (b) 15.5% (c) 23.3% (d) 16.66%
**Ans: (d)** — ηstring = 15000/(10×1800) = 0.833; DRF = 1 − 0.833 = 16.66%.
**Concept:** String derating factor DRF = 1 − Vstring/(N·VSCR).
**Twist:** ask string efficiency directly → 83.3%. N=12 → η=0.694, DRF=30.5%.

**Q15 (APSPDCL-14):** The device which is used as a voltage-variable resistor
(a) BJT (b) JFET (c) SCR (d) PN-diode
**Ans: (b)** — JFET's drain-source resistance is controlled by VGS.
**Concept:** JFET as voltage-variable resistor (linear/ohmic region).
**Twist:** ask which device is voltage-controlled → JFET/MOSFET/IGBT. BJT → current-controlled, no VVR action.

**Q16 (ISRO-14):** A waveform shown as input is applied across the primary of a pulse transformer of 1:1 turns ratio. The output on the secondary will be as shown in figure — (figure: rectangular input pulse; output options are waveform sketches)
(a) rectangular pulse (b) triangular (c) DC level (d) differentiated spikes (+ve spike on rising edge, −ve spike on falling edge)
**Ans: (d)** — pulse transformer acts as a differentiator: +ve spike on rising edge, −ve spike on falling edge, zero on flat portion.
**Concept:** Pulse transformer = differentiator.
**Twist:** turns ratio 2:1 → output amplitude halves. a square wave through a transformer gives spikes (not a level).

**Q17 (ISRO-14):** An SCR triggered by a current pulse applied to gate-cathode can be turned OFF
(a) by applying a pulse to cathode (b) by applying a pulse to the anode (c) by applying another pulse of opposite polarity to gate-cathode (d) by reversing the polarity of the anode and cathode voltage
**Ans: (d)** — after latching, the gate loses control; turn-off needs anode-cathode reversal (or current < holding).
**Concept:** SCR gate cannot turn the device off.
**Twist:** ask GTO turn-off → negative gate pulse (Q9). ask current-based SCR turn-off → anode current below holding (Q6).

**Q18 (HMWS-15):** An IGBT has
(a) low input impedance and high conduction losses (b) low input impedance and low conduction losses (c) high input impedance and high conduction losses (d) high input impedance and low conduction losses
**Ans: (d)** — high input impedance (SiO2 MOS gate) + low conduction loss (minority-carrier injection like BJT).
**Concept:** IGBT = MOS gate + BJT-like conduction (hybrid).
**Twist:** BJT → low input impedance. MOSFET (high voltage) → higher conduction loss than IGBT (Q22). IGBT turn-off slower than MOSFET (Q49).

**Q19 (HMWS-15):** Which of the following devices has the lowest maximum switching frequency?
(a) GTO (b) IGBT (c) SCR (d) MOSFET
**Ans: (c)** — SCR has the lowest switching frequency; MOSFET the highest.
**Concept:** Switching-frequency ranking (MOSFET ≫ IGBT > GTO > SCR/Triac).
**Twist:** ask highest switching frequency → MOSFET. ask where triac sits → low (Q47).

**Q20 (TSGenco-15):** SCR is more utilized as compared to Triac because it is
(a) more capable in regard to control (b) more efficient (c) available with higher ratings (d) comparatively cheaper
**Ans: (a, c)** — better controllability and available at higher ratings.
**Concept:** SCR vs Triac trade-offs.
**Twist:** ask high-power-line usage → higher ratings & better control. triac advantage → cheaper for low-power AC switching.

**Q21 (TSNPDCL-15):** Figure shows a thyristor controlling power in a load resistance RL. Supply 240 V DC; di/dt limit of the SCR is 50 A/μs. The minimum value of L used for di/dt protection, in μH, is — figure: SCR with Rs=5Ω, Cs, series L, VS=240V, RL
(a) 2.4 (b) 120 (c) 1.2 (d) 4.8
**Ans: (d)** — L = Vdc/(di/dt) = 240/50 = 4.8 μH.
**Concept:** di/dt limiting with series inductor L = Vs/(di/dt)max.
**Twist:** Vs=120 V → 2.4 μH. limit 100 A/μs → 2.4 μH.

**Q22 (TSNPDCL-15):** Consider statements: (1) IGBT has low input impedance compared to PMOSFET (2) IGBT and PMOSFET are both voltage-controlled (3) IGBT can be designed for higher voltages than PMOSFET (4) IGBT converters are costlier and bigger than BJT converters. Correct statements are:
(a) 1 & 2 (b) 2 & 3 (c) 3 & 4 (d) 1 & 4
**Ans: (b)** — 2 and 3 are correct (both voltage-controlled; IGBT for higher voltages).
**Concept:** IGBT vs PMOSFET comparison.
**Twist:** why IGBT at higher voltage → smaller on-state drop increase (conductivity modulation). statement 1 wrong → IGBT has HIGH input impedance (Q18).

**Q23 (APTransco-17):** A snubber circuit is connected to a power semiconductor device to reduce the
(a) turn-on time (b) turn-off time (c) electrical stresses (d) thermal resistance
**Ans: (c)** — snubbers reduce dv/dt and di/dt (electrical stresses).
**Concept:** Snubber purpose = stress limiting.
**Twist:** RC snubber specifically → dv/dt. series-L snubber → di/dt (Q21, Q27).

**Q24 (APTransco-17):** Which phenomenon is present in thyristors but absent in BJT, MOSFET and IGBT?
(a) forward conduction (b) latching (c) forward blocking (d) reverse breakdown
**Ans: (b)** — latching is unique to the 4-layer thyristor structure.
**Concept:** Latching phenomenon (stays on after gate removal).
**Twist:** ask the current needed to latch → latching current (Q37). power BJT can suffer secondary breakdown, not latching.

**Q25 (APTransco-17):** RC triggering is preferred over resistance triggering because
(a) it provides triggering at a precise instant (b) it gives a longer-duration gate pulse (c) it enables triggering at a larger firing angle (d) it protects the SCR against high dv/dt
**Ans: (c)** — resistance triggering only gives 0–90°; RC triggering extends to 0–180°.
**Concept:** Triggering-circuit firing-angle range.
**Twist:** range of resistance triggering → 0–90°. add a diode across R in RC circuit → restricts range near 0–180°.

**Q26 (TSSPDCL-18):** Consider the statements: (1) BJT is current-controlled, IGBT voltage-controlled (2) BJT and IGBT have low input impedance, PMOSFET higher (3) IGBT available at higher voltage ratings than PMOSFET (4) IGBT and PMOSFET have different substrate structures. Correct statements are:
(a) 1, 2 (b) 1, 3, 4 (c) 3, 4 (d) 2, 3, 4
**Ans: (b)** — statements 1, 3, 4 correct.
**Concept:** BJT vs IGBT vs PMOSFET characteristics.
**Twist:** statement 2 wrong → IGBT, like MOSFET, has HIGH input impedance (Q18). ask which has low input impedance → BJT.

**Q27 (TSSPDCL-18):** For the circuit shown, di/dt(max) and dV/dt(max) when switch S is closed at t=0 — figure: 240 V source, 10Ω, 0.2μF, 12μH, 2Ω
(a) 10 A/μs, 100 V/μs (b) 20 A/μs, 200 V/μs (c) 20√2 A/μs, 200√2 V/μs (d) 10 A/μs, 200 V/μs
**Ans: (b)** — di/dt = V/L = 240/12e-6 = 20 A/μs; dV/dt = R·di/dt = 10×20 = 200 V/μs.
**Concept:** di/dt and dv/dt stress at turn-on.
**Twist:** L=24 μH → 10 A/μs. R=20Ω → 400 V/μs.

**Q28 (APEPDCL-19):** The main reason for connecting a pulse transformer at the output stage of a thyristor triggering circuit is to
(a) avoid spurious triggering due to noise (b) amplify the power of the triggering pulse (c) provide electrical isolation (d) reduce the turn-on time of the thyristors
**Ans: (c)** — isolation between high-power and low-power (control) circuits.
**Concept:** Pulse-transformer purpose in gate drive.
**Twist:** ask opto-coupler purpose → isolation too (Q31). ask noise immunity → use twisted/shielded leads or pulse transformer.

**Q29 (APEPDCL-19):** θJA of a power transistor is 2.5 °C/W. TJ = 25 °C. PD(max) at 150 °C is
(a) 150 W (b) 100 W (c) 75 W (d) 50 W
**Ans: (d)** — PD = ΔT/θJA = (150−25)/2.5 = 50 W.
**Concept:** Thermal resistance PD = (Tj − Ta)/θJA.
**Twist:** θJA=5 → 25 W. Tjmax=175 °C → 60 W.

**Q30 (APEPDCL-19):** In a commutation circuit employed to turn off an SCR, satisfactory turn-off is obtained when
(a) circuit time constant < device turn-off time (b) circuit turn-off time < device turn-off time (c) circuit turn-off time > device turn-off time (d) circuit time constant > device turn-off time
**Ans: (c)** — circuit turn-off time must exceed the device turn-off time so J2 regains reverse blocking.
**Concept:** Commutation requirement t(circuit) > tq(device).
**Twist:** if not met, J2 fails to regain reverse bias → SCR re-fires. ask quantity measured → device turn-off time tq.

**Q31 (APEPDCL-19):** Opto-couplers are connected to the transistor base drive circuit because — I amplification of base drive, II fast switching, III isolation between control and base drive, IV protection of base drive
(a) (II) and (IV) (b) (I) and (III) (c) (II) and (III) (d) (I) and (IV)
**Ans: (c)** — opto-couplers give isolation (III) and fast switching (II).
**Concept:** Opto-isolation in gate/base drive.
**Twist:** ask what it does NOT provide → power amplification. compare with pulse transformer → both give isolation (Q28).

**Q32 (APTransco-19):** For an SCR, during turn-on and turn-off, the quantities responsible, respectively, are
(a) gate voltage and gate current (b) holding current and latching current (c) latching current and holding current (d) forward breakover and reverse breakover voltage
**Ans: (c)** — latching current governs turn-on; holding current governs turn-off.
**Concept:** Latching vs holding current.
**Twist:** which is larger → latching current (≥ holding). ask the level below which SCR turns off → holding current (Q6).

**Q33 (APSPDCL-19):** The gate triggering circuit shown has Ig(min) = 100 mA, Vg(min) = 2 V. The Vtrig should be — figure: Vtrig with two 30Ω resistors feeding the gate-cathode
(a) 7 V (b) 9 V (c) 12 V (d) 7.5 V
**Ans: (a)** — Thevenin: Vth = Vtrig/2, Rth = 15Ω; Vth = 15×0.1 + 2 = 3.5 V → Vtrig = 7 V.
**Concept:** Gate-triggering circuit design via Thevenin's theorem.
**Twist:** both resistors 20Ω → Vtrig solves from Vth=10·0.1+2=3 → Vtrig=6 V. Ig(min)=200 mA → Vth=5 → Vtrig=10 V.

**Q34 (APPSC-20):** A semiconductor device TRIAC contains:
(a) two SCRs connected in reverse parallel (b) two BJTs connected in series (c) two SCRs connected in series (d) two SCRs connected in parallel
**Ans: (a)** — triac = two SCRs in antiparallel (reverse parallel).
**Concept:** Triac internal construction.
**Twist:** functional equivalence → two antiparallel thyristors (Q8, Q39). ask bidirectional device pair → reverse-parallel SCRs.

**Q35 (TSSPDCL-22):** If the amplitude of the gate pulse applied to the thyristor is increased then
(a) both delay and rise time increase (b) delay increases, rise time decreases (c) delay decreases, rise time increases (d) delay decreases, rise time remains unaffected
**Ans: (d)** — larger gate pulse shortens delay time; rise time is independent of gate amplitude.
**Concept:** Effect of gate amplitude on turn-on time (td ↓, tr unchanged).
**Twist:** ask what shortens delay time → larger gate current/temperature. higher temperature → both td and tr reduce.

**Q36 (TSPSC-AEE-23):** Which of the following is the function of an R–C snubber circuit connected in parallel to an SCR?
(a) limiting di/dt through the SCR (b) triggering the SCR (c) preventing over-voltages across the SCR (d) forced commutation of the SCR
**Ans: (c)** — RC snubber limits dv/dt, preventing over-voltages.
**Concept:** RC snubber function (dv/dt/overvoltage).
**Twist:** di/dt limiting → series inductor (Q21). ask generic snubber goal → reduce electrical stresses (Q23).

**Q37 (TSPSC-AEE-23):** The minimum value of anode current in an SCR that is required to sustain conduction with zero gate current is called
(a) fundamental current (b) latching current (c) holding current (d) base current
**Ans: (b)** — per official solution, this is latching current (minimum current to sustain conduction once gate pulse is removed at turn-on).
**Concept:** Latching current definition.
**Twist:** conventionally the current below which an already-conducting SCR turns off is holding current → that answer for that phrasing (Q32). which is smaller → holding current.

**Q38 (TSPSC-AEE-23):** Match devices to characteristics — A Schottky diode, B SCR, C IGBT, D BJT with 1 current-controlled turn-on/off, 2 majority-carrier device, 3 voltage-controlled turn-on/off, 4 four-layer structure
(a) A-2, B-1, C-3, D-4 (b) A-1, B-2, C-3, D-4 (c) A-2, B-4, C-3, D-1 (d) A-4, B-2, C-1, D-3
**Ans: (c)** — Schottky→majority carrier, SCR→4-layer, IGBT→voltage-controlled, BJT→current-controlled.
**Concept:** Device-to-characteristic mapping.
**Twist:** ask which is current-controlled → BJT. Schottky majority-carrier → very fast switching, no reverse recovery. SCR 4-layer → latching (Q24).

**Q39 (TSPSC-AEE-23):** Statements about triac: A bidirectional current-carrying AND bidirectional voltage-blocking; B functionally equivalent to two antiparallel thyristors; C can be turned on with both positive and negative gate currents.
(a) A, B and C (b) A and B only (c) A and C only (d) B and C only
**Ans: (a)** — all three statements are correct.
**Concept:** Triac characteristics (bidirectional + both gate polarities).
**Twist:** ask how many turn-on quadrants → 4 (modes I–IV with MT2+/− and gate+/−). gate sensitivity is not equal in all quadrants → that's why triacs show rectifier-mode (Q2).

**Q40 (TSPSC-AEE-23):** Which among the following is an example of a voltage-bidirectional two-quadrant switch?
(a) SCR (b) BJT (c) Diode (d) MOSFET
**Ans: (a)** — SCR blocks both forward and reverse voltage, conducts one direction.
**Concept:** Switch quadrant classification (voltage-bidirectional = SCR).
**Twist:** ask the current-bidirectional two-quadrant switch → diode. ask four-quadrant switch → none of the listed (needs bidirectional + bidirectional).

**Q41 (TSSPDCL-AE-2023):** If IC, VGS and VCE represent collector current, gate-emitter voltage and collector-emitter voltage of an IGBT, the transfer characteristic is a plot of
(a) VCE vs IC (b) VGE vs IC (c) IC vs VCE (d) IC vs VGE
**Ans: (d)** — transfer characteristic plots output (IC) against input (VGE).
**Concept:** IGBT transfer characteristic (IC–VGE).
**Twist:** output characteristic → IC vs VCE (c). MOSFET transfer characteristic → ID vs VGS.

**Q42 (TSPSC-AEE-23):** Consider a series resonant inverter using two unidirectional thyristor switches. Arrange the modes in correct order (first to last) — figure: Vs feeding T1/T2, L1=L2=L, C, R, with output io/Vo(t); modes I (T2 on, reverse resonant current), II (T1,T2 both off), III (T1 fired, resonant pulse through T1 and load)
(a) II, III, I (b) III, II, I (c) II, I, III (d) I, III, II
**Ans: (b)** — order: T1 conduction (III) → both off (II) → T2 conduction (I).
**Concept:** Series-resonant inverter operating sequence.
**Twist:** ask the natural-commutation (both-off) interval → mode II. if asked which device conducts first → T1.

**Q43 (TSPSC-AEE-23):** Arrange the given thyristors in increasing order of maximum voltage ratings — I phase-controlled SCRs, II bidirectional thyristors (triacs), III MTOs, IV IGCTs
(a) I, IV, II, III (b) I, II, III, IV (c) II, III, IV, I (d) I, III, II, IV
**Ans: (a)** — increasing: phase-controlled SCR → IGCT → bidirectional thyristor → MTO.
**Concept:** Voltage-rating ranking of thyristor family.
**Twist:** ask highest voltage rating → MTOs. ask device for very high power line-commutated use → phase-controlled SCRs/IGCTs.

**Q44 (TSPSC-AEE-23):** Identify the symbol for Insulated-Gate Bipolar Transistor (IGBT) — figure: four transistor symbols (G/D/S, G/C/E, B/C/E, etc.)
(a) symbol (a) (b) symbol (b) (c) symbol (c) (d) symbol (d)
**Ans: (b)** — IGBT symbol has gate G, collector C and emitter E.
**Concept:** IGBT symbol recognition.
**Twist:** symbol with G and S/D → MOSFET. symbol with B, C, E → BJT. symbol with G, A, K → SCR/thyristor.

**Q45 (TSPSC-AEE-23):** Identify the correct control-characteristic statement related to different thyristors — I phase-controlled SCR: turn-on with pulse, turn-off with natural commutation; II GTO: turn-on positive pulse, turn-off negative pulse; III SITH: turned on by positive gate-drive voltage, turned off with negative gate voltage
(a) II and III only (b) I and II only (c) I, II and III (d) I and III only
**Ans: (c)** — all three statements correct.
**Concept:** Gate-control characteristics of SCR, GTO, SITH.
**Twist:** ask GTO turn-off → negative gate pulse (Q9). SITH is a voltage-controlled thyristor → turned off with negative gate voltage.

**Q46 (TSPSC-AEE-23):** Identify the characteristics of Triode for Alternating Current (TRIAC) — figure: four IA vs VAK/VAB V-I characteristic graphs
(a) curve (a) (b) curve (b) (c) curve (c) (d) curve (d)
**Ans: (d)** — triac V-I characteristic is symmetric about the origin, conducting in both quadrants I and III.
**Concept:** Triac static V-I characteristic (bidirectional).
**Twist:** SCR V-I → latching/breakover only in quadrant I. diac → symmetric but no gate terminal.

**Q47 (TSPSC-AEE-23):** Identify the correct switching-frequency statement related to different thyristors — I bidirectional thyristor: low switching frequency; II SITH: high switching frequency; III TRIAC: high switching frequency; IV GTO: medium switching frequency
(a) I, II and III (b) I and IV (c) I, II and IV (d) II, III and IV
**Ans: (c)** — I, II, IV correct; III wrong (triac switching frequency is low).
**Concept:** Switching-frequency ranking of thyristor family.
**Twist:** ask which thyristor has high switching frequency → SITH. triac sits with the slow, line-commutated devices (Q19).

**Q48 (TSPSC-AEE-23):** Match the waveforms to their RMS currents — figure: current pulses of width To at period T with peak Ip; formulas 1 Ip√(To/T), 2 Ip√(To/2T), 3 Ip√(To/3T), 4 Ip/√2
(a) I-4, II-3, III-2, IV-1 (b) I-4, II-3, III-1, IV-2 (c) I-2, II-3, III-1, IV-4 (d) I-1, II-3, III-4, IV-2
**Ans: (b)** — pulse-waveform RMS matching as per official key.
**Concept:** RMS value of pulse waveforms (Irms = Ip√(duty cycle)).
**Twist:** ask average value instead → duty cycle × Ip. duty cycle 50% square wave → Ip/√2.

**Q49 (TSGenco-24):** Identify the wrong statements — i IGBT is a voltage-controlled device; ii Power MOSFET is a current-controlled device; iii Turn-OFF time of IGBT is less than that of power MOSFET; iv IGBT has high input impedance
(a) i and ii only (b) ii and iii only (c) iii and iv only (d) iv and i only
**Ans: (b)** — wrong: ii (MOSFET is voltage-controlled) and iii (IGBT turn-off time is MORE, not less, than MOSFET).
**Concept:** IGBT vs power MOSFET.
**Twist:** why IGBT turns off slower → stored minority carriers. MOSFET majority-carrier → very fast (Q18).

**Q50 (TSGenco-24):** MOSFETs are connected in parallel very easily because
(a) conductivity modulation is absent (b) its on-state voltage drop is very low (c) its gate-drive circuits are simple (d) it has a positive temperature coefficient of on-state resistance
**Ans: (d)** — positive temp coefficient of RDS(on) gives natural current sharing.
**Concept:** MOSFET parallel operation (positive TC prevents current hogging).
**Twist:** BJT → negative temp coefficient → current hogging/thermal runaway, needs derating. ask which device lacks conductivity modulation → MOSFET (majority carrier).

## Unit 2: AC to DC Converters — Rectifiers (67 Qs)

**Q1 (EPDCL-10):** Peak inverse voltage of each diode in a bridge rectifier is
(a) 4Vm (b) 2Vm (c) Vm (d) Vm/π
**Ans: (c)** — PIV of a (single-phase) bridge diode equals the source peak voltage Vm.
**Concept:** PIV of 1-Φ bridge rectifier = Vm.
**Twist:** 3-Φ bridge → PIV = √3·Vm (peak line-line). Center-tap/mid-point rectifier → PIV = 2Vm.

**Q2 (EPDCL-10):** Half-wave rectifier, v = 100 sin 377t, R = 100 Ω, α = 45°. Average output voltage is
(a) 12.7 V (b) 22.7 V (c) 21.7 V (d) 27.1 V
**Ans: (d)** — Vo = (Vm/2π)(1+cosα) = (100/2π)(1+cos45°) = 27.17 V.
**Concept:** Vdc = (Vm/2π)(1+cosα) for half-wave SCR with R load.
**Twist:** α=0° → Vm/π. α=90° → Vm/2π (half).

**Q3 (EPDCL-10):** In a single-phase full converter, for continuous conduction, each pair of SCRs conducts for
(a) π−α (b) π (c) α (d) π+α
**Ans: (b)** — T1T2 conducts α→(π+α); each pair conducts π rad.
**Concept:** per-SCR-pair conduction in 1-Φ full converter = π rad (180°).
**Twist:** semi-converter pair conducts (π−α). Discontinuous conduction → each pair conducts < π.

**Q4 (EPDCL-10):** A single-phase full converter can operate in
(a) 4 quadrants (b) 3 quadrants (c) 2 quadrants (d) 1 quadrant
**Ans: (c)** — 1-Φ full converter gives 2-quadrant operation (forward motoring + reverse regenerative braking).
**Concept:** full converter = 2-quadrant; dual converter = 4-quadrant.
**Twist:** semi/half-wave converter → 1-quadrant. Two full converters back-to-back → 4-quadrant.

**Q5 (APGenco-12):** A 1-Φ fully controlled rectifier has average output 200 V at α = 0. Its output at α = 30° is approx.
(a) 200 V (b) 160 V (c) 173 V (d) 183 V
**Ans: (c)** — Vo = (2Vm/π)cosα = 200·cos30° = 173.2 V.
**Concept:** Vdc = (2Vm/π)cosα for 1-Φ full converter (cosinusoidal, not linear).
**Twist:** α=60° → 100 V. α=90° → 0 V (rectifier/inverter boundary).

**Q6 (Transco-12):** A free-wheeling diode in a phase-controlled converter
(a) Decreases the possibility of discontinuous conduction (b) Increases the possibility of discontinuous conduction (c) Reduces the power factor and causes over voltage (d) Causes over voltages
**Ans: (a)** — FWD preserves continuity of inductive load current.
**Concept:** FWD maintains load-current continuity and improves IPF.
**Twist:** without FWD at low load current → discontinuous conduction. With FWD, negative output is clamped → higher IPF.

**Q7 (Transco-12):** The ripple content of load current of a converter feeding RL load is decided by
(a) Load resistance alone (b) Load inductance alone (c) Both load resistance and load inductance (d) Neither
**Ans: (c)** — ripple depends on R, L (time constant) and firing angle.
**Concept:** load-current ripple governed by τ = L/R.
**Twist:** large L/R → smooth current (ripple↓). Small L/R → large ripple.

**Q8 (Transco-12):** In a thyristorised converter, a freewheeling diode is used to
(a) Add to the conduction current of the thyristor (b) Oppose the thyristor conduction (c) Conduct current during the off period of the thyristor (d) Protect the thyristor by providing a shunt path
**Ans: (c)** — FWD conducts during the thyristor's off period (half-wave rectifier).
**Concept:** FWD provides a path for load current when the thyristor is off.
**Twist:** R load → FWD needless. Inductive load without FWD → discontinuous conduction, higher ripple.

**Q9 (EPDCL-14):** In a 2-pulse bridge converter with free-wheeling diode, the width of the diode current pulse over one cycle (α is firing angle) is
(a) π+α (b) π−α (c) π (d) 2α
**Ans: (d)** — FWD conducts 0→α and π→(π+α); total 2α.
**Concept:** FWD conduction width in 1-Φ full converter = 2α.
**Twist:** semi-converter FWD conducts (π−α) per half cycle. α=0 → FWD never conducts.

**Q10 (APSPDCL-14):** Technique to improve input power factor in ac-to-dc converters (controlled rectifiers) with self-commutating switches
(a) firing angle control (b) ac applied voltage control (c) symmetrical angle control (d) dual control
**Ans: (c)** — symmetric angle control improves IPF when self-commutating switches (e.g., GTOs) are used.
**Concept:** symmetric angle control → IPF improvement.
**Twist:** plain phase control (α) → DPF = cosα, poor IPF. PWM with self-commutation → near-unity IPF.

**Q11 (ISRO-14):** The ripple factor of a full-wave rectifier circuit compared to that of a half-wave rectifier circuit without filter is
(a) half of that for a half wave rectifier (b) less than half that for a half-wave rectifier (c) equal to that of a half wave rectifier (d) more than half that for a half-wave rectifier circuit
**Ans: (b)** — RF(HWR)=1.21, RF(FWR)=0.48 < 1.21/2 = 0.605.
**Concept:** ripple factor HWR = 1.21, FWR = 0.48; more pulses → more filtering.
**Twist:** 3-Φ bridge (6-pulse) RF ≈ 0.04 → far smaller. m-pulse rectifier RF = 1/(m²−1)^(1/2)·… small.

**Q12 (HMWS-15):** A single-phase full converter with R-L load is triggered at 30°. Each device conducts for
(a) 120° (b) 150° (c) 30° (d) 180°
**Ans: (d)** — each SCR conducts 180° (π) under continuous conduction.
**Concept:** per-device conduction in 1-Φ full converter = 180°.
**Twist:** semi-converter with FWD → device conducts (180°−α). Discontinuous conduction → less.

**Q13 (HMWS-15):** The converters which operate only in two quadrants are
(a) dual converter and semi-converters (b) half-wave and semi converters (c) full wave and semi converters (d) half-wave and full-wave converters
**Ans: (d)** — full-wave (1-Φ & 3-Φ) and 3-Φ half-wave converters give 2-quadrant operation.
**Concept:** quadrant map: full/half-wave = 2Q; semi = 1Q; dual = 4Q.
**Twist:** semi-converter → 1-quadrant only. Dual converter → 4-quadrant.

**Q14 (HMWS-15):** Choose the correct statement
(a) If displacement factor increases/decreases, input p.f. remains constant (b) If THD increases, input p.f. decreases (c) If displacement factor increases, input p.f. decreases (d) If THD increases, input p.f. increases
**Ans: (b)** — IPF = DPF/√(1+THD²); higher THD → lower IPF.
**Concept:** IPF = DPF/√(1+THD²).
**Twist:** DPF=1, THD=0 → IPF=1. DPF=1, THD=75% → IPF=0.8.

**Q15 (HMWS-15):** A circulating current mode dual converter has the following properties
(a) size is less and efficiency is low (b) size is more and efficiency is low (c) size is less and efficiency is high (d) size is more and efficiency is high
**Ans: (b)** — interconnecting reactor increases size and losses.
**Concept:** circulating-current mode needs an interconnecting reactor → larger, lossier.
**Twist:** non-circulating (circulating-current-free) mode → smaller size, higher efficiency.

**Q16 (TSGenco-15):** When firing angle α of a 1-Φ fully controlled rectifier feeding constant dc current into a load is 30°, the displacement power factor of the rectifier is
(a) 1 (b) 0.5 (c) 1/√3 (d) √3/2
**Ans: (d)** — DPF = cosα = cos30° = √3/2.
**Concept:** DPF = cosα for line-commutated converter (fundamental current lags by α).
**Twist:** α=0° → DPF = 1. α=60° → DPF = 0.5.

**Q17 (TSGenco-15):** A 3-Φ fully controlled converter feeds a DC load at a constant current of 150 A. RMS current through each thyristor
(a) 50 A (b) 100 A (c) 150√2/3 A (d) 150/3 A
**Ans: (d)** — per key, I_Trms = Io/3 = 150/3 A.
**Concept:** device current in 3-Φ full converter (key: Io/3).
**Twist:** standard RMS for each SCR of a 3-Φ bridge = Io/√3 ≈ 86.6 A (key prints Io/3 = 50 A). Average device current = Io/3.

**Q18 (TSTransco-15):** Three-pulse converter has a freewheeling diode across its load. The operating range of the converter is
(a) 0° ≤ α ≤ 150° (b) 60° ≤ α ≤ 120° (c) 30° ≤ α ≤ 150° (d) 180° ≤ α ≤ 360°
**Ans: (a)** — α measured from the phase crossover (30°); cannot exceed 180° → range 0°–150°.
**Concept:** 3-pulse (3-Φ half-wave) converter control range with FWD.
**Twist:** 1-Φ half-wave → 0°–180°. 3-Φ full converter → 0°–180°.

**Q19 (TSTransco-15):** A four-quadrant operation requires two full converters connected in
(a) Series (b) Parallel (c) Back-to-back (d) Series Cascade
**Ans: (c)** — two full converters in anti-parallel (back-to-back) form a dual converter.
**Concept:** dual converter = back-to-back connection → 4-quadrant operation.
**Twist:** a single full converter → 2-quadrant only. Same full converters in series (cascade) → higher voltage, still 2Q.

**Q20 (TSTransco-15):** In a dual converter, the circulating current
(a) allows smooth reversal of load current but increases the response time (b) does not allow smooth reversal but reduces response time (c) allows smooth reversal of load current with improved speed of response (d) flows only if there is no interconnecting inductor
**Ans: (c)** — circulating-current mode gives smooth, fast load-current reversal.
**Concept:** circulating-current mode dual converter → smooth reversal + fast response.
**Twist:** non-circulating mode → no circulating current but needs controlled gating (dead time / α-limiting); response slower.

**Q21 (TSSPDCL-15):** A separately excited dc motor in first quadrant fed from 3-Φ semi-converter; if the freewheeling diode is open-circuited, the motor
(a) can be operated in first quadrant (b) can be operated in first & second quadrants (c) can be operated in first & fourth quadrants (d) cannot be operated
**Ans: (c)** — without the FWD the semi-converter can invert, enabling 1st & 4th quadrant operation.
**Concept:** removing FWD lets a semi-converter operate in inversion → 2-quadrant capability.
**Twist:** with FWD → 1-quadrant only. Full converter (inherently no FWD) → 2-quadrant (1Q & 4Q).

**Q22 (TSSPDCL-15):** If the time period of output voltage of a 1-Φ bridge rectifier is 25/3 ms, the supply frequency is
(a) 30 Hz (b) 50 Hz (c) 25 Hz (d) 60 Hz
**Ans: (d)** — fo = 2fi; To = 25/3 ms → fo = 120 Hz → fi = 60 Hz (Ti = 16.67 ms).
**Concept:** 1-Φ bridge output ripple frequency = 2× supply frequency.
**Twist:** 3-Φ bridge → 6× supply frequency. Half-wave → 1× supply frequency.

**Q23 (TSSPDCL-15):** Active input power of a 1-Φ semi-converter with R-L load is 200 W at firing angle π/3. Neglecting output-current harmonics, the reactive input power is
(a) 100√3 (b) 200√3 (c) 100/√3 (d) 200/√3
**Ans: (d)** — φ1 = α/2 = π/6; Q = P·tan(π/6) = 200/√3 VAR.
**Concept:** semi-converter fundamental displacement angle = α/2; Q = P·tanφ1.
**Twist:** full converter → φ1 = α → Q = 200·tan60° = 200√3 VAR. Half-wave → φ1 = α/2, same as semi.

**Q24 (TSNPDCL-15):** A separately excited DC motor is energised from a 440 V, 50 Hz, 3-Φ full converter. Input voltage to the motor at α = 45° is
(a) 420 V (b) 297 V (c) 390 V (d) 260 V
**Ans: (a)** — Vt = (3Vml/π)cosα = (3×440√2/π)×(1/√2) = 3×440/π = 420 V.
**Concept:** Vdc = (3√3/π)Vm·cosα = (3Vml/π)cosα for 3-Φ full converter.
**Twist:** α=0° → 3×440√2/π ≈ 594 V. α=90° → 0 V.

**Q25 (TSNPDCL-15):** In the diode rectifier shown (200 sin 100t source, series L = 1 H), the PMMC meter reads
(a) 1 A (b) 1.414 A (c) 2 A (d) 2.814 A
**Ans: (c)** — PMMC reads average; for diode + pure L, I0 = Vm/(ωL) = 200/100 = 2 A.
**Concept:** diode with pure inductance: average current = Vm/(ωL).
**Twist:** L = 2 H → 1 A. Same source with R load → average = Vm/(πR).

**Q26 (APTransco-17):** In a 3-Φ converter during commutation, when one SCR in one phase is turned on to turn off an SCR in another phase, results in
(a) voltage notching (b) harmonic distortion (c) voltage sag (d) voltage swell
**Ans: (a)** — abrupt source-current change during commutation produces voltage notches.
**Concept:** commutation → voltage notching in the supply waveform.
**Twist:** higher source inductance → deeper/wider notches (increased overlap).

**Q27 (APGenco-17):** Average load voltage across a resistive load of a 1-Φ bridge converter with two SCRs and two diodes (semi-converter), at firing delay α, supplied at 200 V, 50 Hz, is
(a) (200/2π)cosα (b) (2×200/π)cosα (c) (2×200/π)(1+cosα) (d) (200/2π)(1+sinα)
**Ans: (c)** — semi-converter Vo = (Vm/π)(1+cosα); key marks (c) (2×200/π)(1+cosα).
**Concept:** 1-Φ semi-converter Vdc = (Vm/π)(1+cosα).
**Twist:** correct numeric = (200√2/π)(1+cosα) ≈ 90(1+cosα). Full converter → (2Vm/π)cosα = (400√2/π)cosα.

**Q28 (TSSPDCL-18):** 1-Φ full-converter SCR bridge with FWD feeds an RLE load (Vs = 230√2 sin314t, R = 0.5 Ω, L = 3 mH, E = 120 V); load current constant 8 A. Firing angle delay is
(a) 30° (b) 36.8° (c) 60° (d) 53.2°
**Ans: (*)** — (Vm/π)(1+cosα) = Vo = RIo + E = 124 V → α = 78.6°, not in the options (bonus).
**Concept:** FWD full converter → Vo = (Vm/π)(1+cosα); load equation Vo = RIo + E.
**Twist:** if E = 0 → Vo = RIo = 4 V → very small α. If full-converter formula (2Vm/π)cosα used → different α.

**Q29 (APEPDCL-19):** The effect of source inductance on the performance of single-phase and three-phase full converters is to ___
(a) increase the load voltage (b) reduce ripple in the load current (c) make the discontinuous current as continuous (d) reduce the output voltage
**Ans: (d)** — commutation overlap reduces output voltage.
**Concept:** source inductance → ΔV = 2ωLs·Io/π (1-Φ), 3ωLs·Io/π (3-Φ).
**Twist:** 1-Φ full: ΔV = 2ωLs·Id/π. 3-Φ full: ΔV = 3ωLs·Id/π (larger, depends on line Ls).

**Q30 (APEPDCL-19):** A 1-Φ full-wave diode-bridge rectifier supplied from 200 V, 50 Hz; load = 100 Ω resistor. PIV of each diode is
(a) 400/π V (b) 200 V (c) 200√2 V (d) 400√2/π V
**Ans: (c)** — PIV = Vml = 200√2 V.
**Concept:** PIV of a bridge diode = peak source voltage = √2·Vrms.
**Twist:** center-tap rectifier → PIV = 2Vm. 3-Φ bridge → PIV = √3·Vm.

**Q31 (APEPDCL-19):** A 1-Φ diode bridge rectifier supplies a highly inductive load (ripple-free current). The AC supply side current waveform will be
(a) triangular (b) sinusoidal (c) constant DC (d) square
**Ans: (d)** — input current alternates ±Io → square wave.
**Concept:** current-stiff (highly inductive) load → square-wave input current.
**Twist:** R load → sinusoidal input current. Capacitor-filtered load → peaky/discontinuous input current.

**Q32 (APEPDCL-19):** A thyristor half-wave rectifier supplies a resistive load; source voltage 2Vs·cos(ωt). If α = 60°, the average load voltage is
(a) 2Vs/π (b) 3√2Vs/4π (c) 3Vs/4π (d) 2Vs/4π
**Ans: (b)** — Vo = (Vm/2π)(1+cosα) with Vm = 2Vs; key → 3√2Vs/4π.
**Concept:** half-wave SCR: Vo = (Vm/2π)(1+cosα).
**Twist:** α=0° → (2Vs/2π)(2) = 2Vs/π. Direct arithmetic with peak 2Vs and α=60° gives 3Vs/2π (key prints the √2 form).

**Q33 (APEPDCL-19):** Converter shown (single-phase bridge T1–T4, R = 10 Ω, E = 220 V, source 220√2 sinωt); firing angles T1,T2 = π/6, T3,T4 = 5π/6. Average voltage across the RE-load is
(a) 220(√2−1) V (b) 220 V (c) 70√6 V (d) 220√2 V
**Ans: (b)** — source at α = 30° (≈155 V) is below E = 220 V, so SCRs never conduct; output = back-emf E = 220 V.
**Concept:** SCR fires only if vs(α) > E at the firing instant.
**Twist:** E lowered so vs(α) > E → converter conducts, Vo = (Vm/π)(1+cosα). E > Vm → never conducts.

**Q34 (APEPDCL-19):** Valve power rating of a converter circuit is given by the product of
(a) maximum voltage and maximum current (b) average voltage and average current (c) peak inverse voltage and r.m.s. current (d) peak inverse voltage and average current
**Ans: (d)** — valve rating = PIV × I_avg.
**Concept:** device "valve" power rating = PIV × average current.
**Twist:** device thermal rating uses rms current; forward/blocking rating uses PIV × I_avg.

**Q35 (APTransco-19):** A 1-Φ mid-point full-wave SCR converter with maximum mid-point voltage Vmax develops average output voltage across a resistive load at firing delay angles 0 and π/2 rad respectively as
(a) 2Vmax/π, Vmax/π (b) Vmax/π, Vmax/2π (c) Vmax/2π, Vmax/π (d) Vmax/π, −Vmax/2π
**Ans: (a)** — Vo = (Vm/π)(1+cosα): α=0 → 2Vmax/π; α=π/2 → Vmax/π.
**Concept:** 2-pulse mid-point (center-tap) R-load converter: Vo = (Vm/π)(1+cosα).
**Twist:** full converter → (2Vm/π)cosα: α=0 → 2Vmax/π, α=π/2 → 0.

**Q36 (APTransco-19):** A 240 V, 50 Hz 1-Φ half-wave SCR converter supplies a resistance load at firing delay π/3. RMS load voltage
(a) (240/2)√(5/6 − 3/4π) (b) (240/2)√(5/6 + 3/4π) (c) (240/2)√(5/12 − 3/4π) (d) (240/2)√(5/12 − 3/2π)
**Ans: (*)** — Vor = (Vm/2)·√[(π−α)/π + sin2α/(2π)] = 152.2 V; none of the options → bonus.
**Concept:** RMS of phase-controlled half-wave (R load): Vor = (Vm/2)·√[(π−α)/π + (sin2α)/(2π)].
**Twist:** α=0° → Vor = Vm/2. α=π/2 → Vor = Vm/(2√2).

**Q37 (APTransco-19):** A 1-Φ half-wave SCR converter with commutating diode supplies an R-L load at an average load voltage of 150 V at firing delay 60°. The supply voltage to the converter is
(a) 50√2π (b) 100π (c) 200π (d) 150√2π
**Ans: (c)** — Vo = (Vm/2π)(1+cos60°) = 150 → Vm = 300π/1.5 = 200π V.
**Concept:** Vo = (Vm/2π)(1+cosα); back-solve for supply peak Vm.
**Twist:** α=0° → Vm = 300π V. With full-converter law (2Vm/π)cosα → different Vm.

**Q38 (APTransco-19):** Conducting pairs of SCRs in a bridge-type 3-Φ ac-dc converter (S1,S3,S5 in top-half; S4,S6,S2 in bottom-half), R load, are
(a) (S6,S1),(S1,S2),(S2,S3),(S3,S4),(S4,S5),(S5,S6) (b) (S1,S4),(S4,S3),(S3,S6),(S6,S5),(S5,S2),(S2,S1) (c) (S1,S2),(S2,S3),(S3,S4),(S4,S5),(S5,S6),(S6,S1) (d) (S1,S5),(S5,S2),(S2,S6),(S6,S3),(S3,S4),(S4,S1)
**Ans: (a, c)** — key accepts both; devices trigger in numbered order with adjacent pairs conducting.
**Concept:** 3-Φ bridge conducting-pair sequence; commutation every 60°.
**Twist:** with S1 top-R, S3 top-Y, S5 top-B and 2,4,6 bottom in physical order → natural pairs (S6,S1),(S1,S2),…(option a).

**Q39 (APTransco-19):** Sequence of triggering of SCRs in a 3-Φ bridge-type converter (S1,S2,S3 top-half; S4,S5,S6 bottom-half), R load, is
(a) S1,S2,S3,S4,S5,S6 (b) S1,S6,S2,S4,S3,S5 (c) S1,S4,S3,S6,S5,S2 (d) S1,S3,S4,S6,S2,S5
**Ans: (b)** — standard order 1,2,3,4,5,6 maps to S1,S6,S2,S4,S3,S5.
**Concept:** 3-Φ bridge gating sequence derived from numbering map.
**Twist:** if SCRs are numbered S1..S6 in standard bridge positions, sequence becomes S1,S6,S2,S4,S3,S5 (as above); with top 1,3,5 / bottom 4,6,2 → S1,S6,S2,S4,S3,S5.

**Q40 (APSPDCL-19):** The phasor diagram (fundamental Van & Ia, angle > 90°) represents the ac side of a 3-Φ controlled bridge rectifier. The mode of operation is
(a) Rectifier (b) Inverter (c) Bridge Idle (d) Amplifier
**Ans: (b)** — fundamental-current lag > 90° → inversion.
**Concept:** |φ1| > 90° → converter operates as inverter.
**Twist:** angle < 90° → rectifier mode. angle = 90° → zero average power.

**Q41 (APSPDCL-19):** A 3-Φ fully controlled rectifier fed from 200 V, 3-Φ, 50 Hz supply is fired at α = 45°. Average output voltage is
(a) 100√2/π V (b) 200√2/π V (c) 300/π V (d) 600/π V
**Ans: (d)** — Vo = (3Vml/π)cos45° = (3×200√2/π)×(1/√2) = 600/π V.
**Concept:** Vdc = (3√3/π)Vm_phase·cosα = (3Vml/π)cosα for 3-Φ full converter.
**Twist:** α=0° → 600√2/π V. α=90° → 0 V. (If 200 V were phase rms, Vo = 600√3/π.)

**Q42 (APPSC-20):** In a three-phase full controlled converter using six SCRs, commutation occurs every ___
(a) 60° (b) 90° (c) 45° (d) 180°
**Ans: (a)** — 6-pulse converter → commutation every 60°.
**Concept:** 6-pulse bridge commutation interval = 60° (one SCR change per 60°).
**Twist:** 3-Φ half-wave (3-pulse) → every 120°. 1-Φ full (2-pulse) → every 180°.

**Q43 (TSSPDCL-22):** In a two-pulse fully controlled bridge converter with freewheeling diode, the width of the freewheeling diode current pulse is (α firing angle); RL load, continuous conduction.
(a) π−α (b) π+α (c) 2π (d) 2α
**Ans: (d)** — FWD conducts 0→α and π→(π+α); total 2α.
**Concept:** FWD conduction width in a 2-pulse full converter = 2α.
**Twist:** semi-converter FWD conducts (π−α). α=0 → FWD current = 0.

**Q44 (TSSPDCL-22):** A half-wave thyristor converter supplies a pure inductive load. If the triggering angle is 100°, the extinction angle will be
(a) 260° (b) 240° (c) 200° (d) 120°
**Ans: (a)** — inductor releases energy 180°–260°; β = 360° − α = 260°.
**Concept:** pure-L half-wave: β = 2π − α; conduction angle = π (160° here).
**Twist:** α=60° → β = 300°. α=120° → β = 240°.

**Q45 (TSSPDCL-22):** A single-phase bridge rectifier is preferred over the full-wave center-tap rectifier because its
(a) ripple percentage is lower (b) power factor is higher (c) ratio of ripple frequency to line frequency is higher (d) peak inverse voltage across the diode is lower
**Ans: (d)** — bridge PIV = Vm vs center-tap 2Vm.
**Concept:** PIV: bridge = Vm; center-tap (mid-point) = 2Vm.
**Twist:** both are 2-pulse → same ripple frequency (2f), so (c) is false. 3-Φ bridge → PIV = √3·Vm.

**Q46 (TSSPDCL-22):** A fully controlled thyristor converter (1-Φ) fed from a single-phase AC source gives Vdc = 300 V at α = 0°. Output voltage at α = 60° (continuous conduction)?
(a) 150 V (b) 300 V (c) 210 V (d) 100π V
**Ans: (a)** — Vo = (2Vm/π)cosα = 300·cos60° = 150 V.
**Concept:** Vdc = (2Vm/π)cosα for 1-Φ full converter.
**Twist:** α=30° → 300×0.866 = 260 V. α=90° → 0 V.

**Q47 (TSSPDCL-22):** A single SCR is inserted between a 200 sin(314t) source and an R = 10 Ω load. If the firing angle is 120°, the average load current is
(a) 15/π A (b) 5/π A (c) −15/π A (d) −5/π A
**Ans: (b)** — Vo = (Vm/2π)(1+cos120°) = (200/2π)(1/2) = 50/π; Io = Vo/R = 5/π A.
**Concept:** Vo = (Vm/2π)(1+cosα); Io = Vo/R (R load).
**Twist:** α=90° → Vo = 100/π, Io = 10/π A. α=180° → Io = 0.

**Q48 (TSSPDCL-22):** The average output voltage of a dc–dc converter can be controlled by
(a) Amplitude modulation (b) Pulse width modulation (c) Frequency modulation (d) Both pulse width modulation and frequency modulation
**Ans: (d)** — PWM and frequency modulation both control dc-dc output.
**Concept:** dc-dc converter output control via duty ratio (PWM) and switching frequency (FM).
**Twist:** fixed-frequency PWM → variable duty D. FM → Vary frequency at fixed on-time.

**Q49 (TSNPDCL-22):** Controlled thyristor supplying a load; input/output waveforms given; α = 45°, β = 235°. Conducting period in the 1st half cycle and non-conduction period in the 2nd half cycle of input current are
(a) 45° and 125° (b) 135° and 55° (c) 45° and 55° (d) 135° and 125°
**Ans: (d)** — conducts α→π = 135° in 1st half; in 2nd half conducts β→2π = 125°.
**Concept:** conduction interval = (π−α) first half, (2π−β) second half for controlled rectifier with extinction angle β.
**Twist:** α=60°, β=300° → 120° and 60°. α=0, β=180° (diode-like) → 180° and 180°.

**Q50 (TSNPDCL-22):** If the output of a 1-Φ semi-converter is twice the output of a 1-Φ full converter for the same firing angle, find the input displacement factor of the semi-converter
(a) 2/√3 (b) 1/√3 (c) 1/3 (d) 2/3
**Ans: (d)** — (Vm/π)(1+cosα) = 2·(2Vm/π)cosα → cosα = 1/3; IDF = cos(α/2); key → 2/3.
**Concept:** semi Vo = (Vm/π)(1+cosα); full Vo = (2Vm/π)cosα; IDF = cos(α/2).
**Twist:** correct IDF = √((1+cosα)/2) = √(2/3) ≈ 0.816 (key prints 2/3). Equal outputs → (1+cosα)=2cosα → α=0 → IDF=1.

**Q51 (TSPSC-AEE-23):** Statements about a phase-controlled 1-Φ full-bridge SCR converter: A. avg dc output varies linearly with firing angle; B. input power factor depends on firing angle; C. cannot operate with α > 90°. True statement(s):
(a) A only (b) A and B only (c) B and C only (d) B only
**Ans: (d)** — B true; A false (Vo = (2Vm/π)cosα, cosinusoidal, not linear); C false (α>90° gives inverter mode).
**Concept:** Vo = (2Vm/π)cosα; PF ≈ 0.9cosα; α>90° → inversion.
**Twist:** for semi-converter Vo = (Vm/π)(1+cosα) → also not linear in α. R-load → α max 180°.

**Q52 (TSPSC-AEE-23):** In a 1-Φ SCR full converter with continuous conduction at firing angle α, the angle duration of conduction for each pair of SCRs (in radians) is
(a) α (b) π−α (c) π+α (d) π
**Ans: (d)** — each SCR pair conducts for π rad.
**Concept:** 1-Φ full converter pair conduction = π rad (independent of α under continuous conduction).
**Twist:** discontinuous conduction → pair conducts (π−α)·k less. Semi-converter pair → (π−α).

**Q53 (TSPSC-AEE-23):** The low-order ripple frequency of the output voltage of a 3-Φ fully controlled bridge converter, if ac input supply frequency is f, is
(a) 6f (b) f (c) 2f (d) 3f
**Ans: (a)** — 6-pulse output → dominant ripple at 6f.
**Concept:** m-pulse converter → lowest output ripple frequency = m·f.
**Twist:** 1-Φ full (2-pulse) → 2f. 3-Φ half-wave (3-pulse) → 3f.

**Q54 (TSPSC-AEE-23):** An ideal diode in series with a pure inductance is supplied from an ideal AC voltage source. The duration (radians) the diode conducts is
(a) π/4 (b) 2π (c) π (d) π/2
**Ans: (b)** — diode + pure L conducts for 2π (current persists after voltage reversal).
**Concept:** pure-L half-wave: conduction angle = 2π (current never reaches zero).
**Twist:** R load → conduction = π. RL load → conduction between π and 2π depending on τ.

**Q55 (TSPSC-AEE-23):** Effect of AC-side source inductance in an SCR phase-controlled rectifier with α < π/2 and R-L load, compared to zero source impedance:
(a) Average output voltage may increase or decrease (b) increases (c) decreases (d) remains unchanged
**Ans: (c)** — Vo = (2Vm/π)cosα − (2ωLs/π)Io → decreased by source inductance.
**Concept:** source inductance causes overlap; drops output by 2ωLs·Io/π (1-Φ).
**Twist:** 3-Φ full → ΔV = 3ωLs·Io/π. As Ls↑ (more overlap) → lower Vo, increased commutation angle.

**Q56 (TSPSC-AEE-23):** A 3-Φ diode bridge rectifier from a 400 V, 50 Hz supply delivers to a 50 Ω resistive load. Peak value of the instantaneous load voltage is
(a) 400/√3 V (b) 400√2 V (c) 400 V (d) 400√(2/3) V
**Ans: (b)** — Vml = 400√2 V (peak line voltage).
**Concept:** peak load voltage of a 3-Φ bridge = peak line voltage = √2·VL.
**Twist:** average dc output = (3√3/π)Vm_phase = (3/π)·400√2 ≈ 540 V. Peak load current = 400√2/50 A.

**Q57 (TSPSC-AEE-23):** A single-phase diode bridge rectifier supplies a highly inductive load (ripple-free current). The input current at the ac side will be
(a) Square wave (b) Purely sinusoidal (c) Pure DC (d) Triangular wave
**Ans: (a)** — input current alternates ±Io → square wave.
**Concept:** current-stiff (ripple-free) load → square-wave input current.
**Twist:** R load → sinusoidal input current. Capacitor-filtered → peaky, distorted input.

**Q58 (TSSPDCL-AE-2023):** A 3-Φ semi-converter is operated with a firing angle of 30°. Its input displacement factor is
(a) (2+√3)/2 (b) (2−√3)/4 (c) (2−√3)/2 (d) (2+√3)/4
**Ans: (a)** — IDF = cos(α/2) = cos15° (key → (a)).
**Concept:** 3-Φ semi-converter IDF = cos(α/2).
**Twist:** α=60° → cos30° = √3/2 ≈ 0.866. α=0° → IDF = 1. (Note cos15° = (√6+√2)/4 ≈ 0.966; printed options approximate.)

**Q59 (TSSPDCL-AE-2023):** Input power factor and displacement factor of an ac-to-dc converter are 0.8 and 1.0. Input total harmonic distortion is
(a) 50% (b) 20% (c) 75% (d) 56.25%
**Ans: (c)** — DF = IPF/DPF = 0.8; %THD = √(1/0.8² − 1)×100 = 75%.
**Concept:** IPF = DPF/√(1+THD²) → THD = √(1/DF² − 1).
**Twist:** IPF=0.707, DPF=1 → THD = 100%. IPF=0.9, DPF=1 → THD ≈ 48.4%.

**Q60 (TSSPDCL-AE-2023):** Identify the angle at which the average dc voltage equals the instantaneous output voltage of a 1-Φ full-wave rectifier (Vdc = 2Vm/π).
(a) α = π + sin⁻¹(2/π) (b) α = π/2 + sin⁻¹(2/π) (c) α = π/2 − sin⁻¹(2/π) (d) α = 3π/2 + sin⁻¹(2/π)
**Ans: (a)** — set Vm|sinα| = 2Vm/π → sinα = 2/π; intersection at α = π + sin⁻¹(2/π).
**Concept:** Vdc = 2Vm/π for full-wave R load; equal to instantaneous at |sinα| = 2/π.
**Twist:** half-wave → Vdc = Vm/π → sinα = 1/π. 1-Φ full converter → Vdc = (2Vm/π)cosα → intersection changes.

**Q61 (TSPSC-AEE-23):** Which single-phase converter provides operation in all four-quadrant drives?
(a) Single-phase semi converter drives (b) Single-phase dual converter drives (c) Single-phase full converter drives (d) Single-phase half-wave converter drives
**Ans: (b)** — dual converter → all four quadrants.
**Concept:** dual converter (two back-to-back converters) = 4-quadrant.
**Twist:** full converter → 2-quadrant (1Q & 4Q). semi/half-wave → 1-quadrant.

**Q62 (TSPSC-AEE-23):** The average armature voltage Va = (Vm/2π)(1+cosα) is given by which single-phase converter?
(a) Single-phase full converter drives (b) Single-phase half-wave converter drives (c) Single-phase semi converter drives (d) Single-phase dual converter drives
**Ans: (b)** — half-wave converter gives Va = (Vm/2π)(1+cosα).
**Concept:** half-wave SCR: Va = (Vm/2π)(1+cosα).
**Twist:** (Vm/π)(1+cosα) → semi-converter. (2Vm/π)cosα → full converter.

**Q63 (TSPSC-AEE-23):** Statements: I. If φ is the angle between fundamental input current and voltage, φ is the displacement angle and DF = cosφ. II. Harmonic factor of input current HF = √[(Is²−Is1²)/Is1²]. Correct statement(s):
(a) Only II (b) Neither I nor II (c) Only I (d) Both I and II
**Ans: (c)** — only I; statement II is incorrect as written.
**Concept:** DF = cosφ; HF = Isn/Is1 (n>1) — or rms form √(Is²−Is1²)/Is1.
**Twist:** square-wave input (DF=1) → THD ≈ 48.4%. IPF = DF/√(1+THD²) ties the two.

**Q64 (TSPSC-AEE-23):** Expression of armature voltage for a three-phase half-wave converter:
(a) Va = (3Vm/π)(1+cosα) (b) Va = (3√3Vm/π)cosα (c) Va = (3√3Vm/2π)cosα (d) Va = (3√3Vm/2π)(1+cosα)
**Ans: (c)** — 3-Φ half-wave (3-pulse): Va = (3√3Vm/2π)cosα.
**Concept:** 3-pulse converter Vdc = (3√3/2π)Vm·cosα.
**Twist:** 3-Φ full converter → (3√3/π)Vm·cosα (twice, watch the √3). 1-Φ full → (2Vm/π)cosα.

**Q65 (TSGenco-24):** A 1-Φ full-bridge diode rectifier with a large output filter capacitance feeds a resistive load. The input current is
(a) Purely sinusoidal and in-phase with the voltage (b) Purely sinusoidal with power factor less than one (c) Peaky and distorted with power factor less than one (d) Peaky and distorted but with power factor equal to one
**Ans: (c)** — capacitor filter → pulsed/peaky input current, PF < 1.
**Concept:** capacitor-filtered rectifier → conduction angle short, peaky input current, low PF.
**Twist:** without capacitor, R load → sinusoidal input current, PF ≈ 1. Inductive (current-stiff) load → square input current.

**Q66 (TSGenco-24):** A 120 V battery is charged through a 7 Ω resistor via a 1-Φ half-wave uncontrolled rectifier (single diode) fed by a 240 V(peak), 50 Hz supply. PIV of the diode and circuit turn-off time are respectively
(a) 360 V, 6.66 ms (b) 240 V, 13.33 ms (c) 360 V, 13.33 ms (d) 120 V, 6.66 ms
**Ans: (c)** — PIV = E + Vm = 120 + 240 = 360 V; turn-off = (π+2θ)/ω, θ = sin⁻¹(E/Vm) = 30° → 240° = 13.33 ms.
**Concept:** battery-charging half-wave rectifier: PIV = E + Vm; turn-off interval = (π+2θ)/ω.
**Twist:** E = Vm → θ = 90° → turn-off 360° (20 ms, never turns off). E = 0 → θ = 0 → turn-off = π → 10 ms.

**Q67 (TSGenco-24):** 228 V, 40 A SEP DC motor, 1500 rpm, Ra = 0.2 Ω, driven by a 3-Φ fully controlled rectifier; rated torque & speed at α = 0°. Load is linear with zero torque at zero speed. Angle α to reduce the speed to half the rated speed is
(a) 60° (b) 26° (c) 30° (d) 80°
**Ans: (a)** — halving speed ⇒ halve Vt; Vt = (3Vml/π)cosα → cosα = 1/2 → α = 60°.
**Concept:** Vt = (3√3/π)Vm·cosα; N ∝ Vt (constant flux), and linear load ⇒ Ia ∝ N.
**Twist:** reduce to 1/3 speed → cosα = 1/3 → α ≈ 70.5°. Full speed (α=0) → Vt = 3Vml/π ≈ 594·(√2 relation).

## Unit 3: DC to DC Converters — Choppers (34 Qs)

**Q1 (EPDCL-10):** The maximum DC voltage rating (VRDC) of a power diode is useful for selecting ____ diodes in a DC-DC chopper.
(a) Feedback (b) Free Wheeling (c) Series (d) Zener
**Ans: (a)** — Feedback diodes are used in choppers, commutation circuits and inverters.
**Concept:** VRDC rating selects the feedback/freewheeling diode in a chopper.
**Twist:** ask about the diode that clamps inductive load current → still feedback diode. Diode across a switch for snubbing → series/feedback roles differ.

**Q2 (EPDCL-10):** In dc choppers, per unit ripple is maximum when duty cycle is
(a) 0.2 (b) 0.5 (c) 0.7 (d) 0.9
**Ans: (b)** — ΔIL = (Vdc/L)·D(1−D)·T is maximum at D = 0.5.
**Concept:** Ripple current ΔIL = Vs·D(1−D)/(f·L), max at D = 0.5.
**Twist:** ask ripple at D = 0.8 vs D = 0.5 → peak at 0.5. Frequency doubled, D constant → ripple HALVES (ΔIL ∝ 1/f).

**Q3 (EPDCL-10):** A load commutated chopper circuit has
(a) One thyristor (b) Two thyristor (c) Four thyristor (d) Six thyristor
**Ans: (c)** — Load commutated chopper uses four thyristors (T1–T4 with commutation capacitor).
**Concept:** Load/current commutated chopper (class-C type) — 4-thyristor bridge with capacitor.
**Twist:** voltage commutated chopper → 2 thyristors; Morgan/Jones current-commutated → also 4-thyristor topology.

**Q4 (APGenco-12):** A 200 V dc-dc converter is turned ON for 30 μs and OFF for 10 μs. Output voltage?
(a) 200 V (b) 150 V (c) 175 V (d) 120 V
**Ans: (b)** — Vo = Vdc·Ton/(Ton+Toff) = 200×30/40 = 150 V.
**Concept:** Buck (step-down) chopper: Vo = D·Vs with D = Ton/T.
**Twist:** ask D → D = 30/40 = 0.75. ON 10 μs, OFF 30 μs → Vo = 50 V.

**Q5 (Transco-12):** In d.c. choppers, for periodic time T, output voltage is controlled by frequency modulation by varying
(a) T, keeping ton constant (b) ton, keeping T constant (c) T, keeping toff constant (d) toff, keeping T constant
**Ans: (a, c)** — Frequency modulation varies T while holding either ton or toff constant.
**Concept:** FM control: D = ton/T changed by varying T (ton fixed) or varying T with toff fixed.
**Twist:** PWM control = vary ton keeping T constant → (b). Vary toff keeping T constant → (d).

**Q6 (EPDCL-14):** Which configuration is used for both motoring and regenerative braking?
(a) First quadrant chopper (b) Second quadrant chopper (c) Two quadrant chopper (d) Four quadrant chopper
**Ans: (c)** — Type C two-quadrant chopper gives forward motoring + forward regenerative braking.
**Concept:** Quadrant operation; type C → Q1+Q2 (motoring + regen braking).
**Twist:** type D → forward motoring + reverse regenerative braking (Q1+Q4); single-quadrant type A cannot brake.

**Q7 (APSPDCL-14):** Effective input resistance seen by the source in the chopper circuit (10 Ω load, D = 0.2 from figure)
(a) 10 Ω (b) 50 Ω (c) 20 Ω (d) 5 Ω
**Ans: (b)** — Rin = Vdc/Is = R/D = 10/0.2 = 50 Ω.
**Concept:** Chopper input resistance Rin = R/D — source sees a boosted resistance.
**Twist:** D = 0.5 → Rin = 20 Ω (option c); D = 0.5 with R = 20 Ω → Rin = 40 Ω.

**Q8 (HMWS-15):** If the duty cycle of a d.c. chopper is α, ripple factor is given by
(a) 1/α (b) α/(1−α) (c) α (d) (1−α)/α
**Ans: (d)** — RF = √((Vrms/Vdc)²−1) = √(1/α − 1) = √((1−α)/α) (key: d).
**Concept:** Ripple factor = √(FF²−1); FF = Vrms/Vdc = 1/√D for a chopper.
**Twist:** ask form factor → 1/√α. Ripple factor strictly decreases as α increases.

**Q9 (HMWS-15):** Forced commutation is necessary in ____ circuits
(a) Inverter grade SCR (b) MOSFET Based (c) Converter grade SCR (d) GTO Based
**Ans: (a)** — Inverter-grade SCRs with forced commutation are used in chopper circuits.
**Concept:** Converter-grade SCR (line commutated, for rectifiers) vs inverter-grade SCR (forced commutation, for choppers/inverters).
**Twist:** converter-grade SCR in rectifier → line commutation; GTO switchable off by gate → no forced commutation needed.

**Q10 (TSGenco-15):** In a thyristor DC chopper, which type of commutation results in best performance?
(a) Voltage commutation (b) Current commutation (c) Load commutation (d) Supply commutation
**Ans: (a, b)** — Voltage and current commutation are the methods used in practice.
**Concept:** Voltage & current commutation of thyristor choppers (voltage stress ≈ 2Vs).
**Twist:** load commutation → resonant/class-A circuits only; supply (line) commutation works on AC, not DC chopper.

**Q11 (TSTransco-15):** A dc chopper feeds an RL load from constant voltage mains; duty ratio progressively increased. Per-unit current ripple?
(a) increase progressively (b) decrease progressively (c) decrease to min at α=0.5 then increase (d) increase to max at α=0.5 then decrease
**Ans: (d)** — Ripple rises to a maximum at D = 0.5, then falls.
**Concept:** ΔIL ∝ D(1−D) — maximum at D = 0.5.
**Twist:** note ripple factor γ = √((1−D)/D) alone decreases with D — the "per-unit ripple current" (D(1−D)) peaks at 0.5.

**Q12 (TSNPDCL-15):** Circuit with 2 choppers (Ch1, Ch2, D2) feeding a load. This chopper drive is:
(a) one quadrant drive (b) two quadrant drive (c) 3 quadrant drive (d) 4 quadrant drive
**Ans: (b)** — Type D chopper gives two-quadrant operation.
**Concept:** Type D chopper (two choppers + two diodes, Q1+Q4) → two-quadrant.
**Twist:** type C (same part count) → Q1+Q2; a true 4-quadrant needs type E/dual arrangement.

**Q13 (TSNPDCL-15):** Simple chopper, Vs = 200 V, R = 10 Ω, duty cycle 0.49. Average and rms currents?
(a) 9.8, 14 (b) 14, 9.8 (c) 20, 28.28 (d) 14, 18.2
**Ans: (a)** — Io(avg) = D·Vs/R = 9.8 A; Io(rms) = (Vs/R)√D = 14 A.
**Concept:** Resistive-load chopper: Io = D·Vs/R, Irms = (Vs/R)·√D.
**Twist:** D = 0.25 → avg 5 A, rms 10 A; average source current = D·Vs/R same as load avg.

**Q14 (APTransco-17):** In a boost chopper (Vs, V0, L), when the conducting switch is opened, the rate of change of inductive current is
(a) Vs/L (b) 0 (c) (Vs−V0)/L (d) (Vs+V0)/L
**Ans: (c)** — During switch OFF, L·di/dt = Vs − V0 → di/dt = (Vs−V0)/L.
**Concept:** Boost, OFF interval: inductor sees (Vs − V0), V0 > Vs so di/dt is negative.
**Twist:** switch ON → di/dt = Vs/L (option a); in a buck, ON interval gives (Vs−V0)/L.

**Q15 (APGenco-17):** In a dc-dc converter, the switch duty ratio is defined as
(a) turn-off time / time period (b) sawtooth voltage / control voltage (c) control voltage / peak value of sawtooth voltage (d) control voltage / sawtooth voltage
**Ans: (c)** — D = ton/T = vcontrol/V̂st.
**Concept:** PWM duty ratio D = Vcontrol/V̂saw (constant-f switching).
**Twist:** ask off-fraction → toff/T = 1−D (option a); raise Vcontrol → higher D.

**Q16 (APGenco-17):** Four-quadrant dc motor drive with two phase-controlled converters — converter 1 operating in I and IV quadrants has current/voltage:
(a) Ia−,Va+ / Ia+,Va− (b) Ia+,Va+ / Ia+,Va− (c) Ia−,Va+ / Ia−,Va− (d) Ia+,Va+ / Ia−,Va−
**Ans: (b)** — Quadrant I: +Va, +Ia; Quadrant IV: −Va, +Ia (current direction unchanged).
**Concept:** Dual-converter (2 phase-controlled bridges) quadrant sign convention.
**Twist:** converter 2 operating in II and III → Ia−,Va+ and Ia−,Va− (option c).

**Q17 (TSSPDCL-18):** Circuit with Ch1, Ch2, D2, L, FWD and back-EMF E is a
(a) second quadrant or type B (b) two quadrant type A or type C (c) first quadrant or type A (d) two quadrant type B or type D
**Ans: (b)** — Type C chopper = two-quadrant type A.
**Concept:** Type C chopper (2 choppers + 2 diodes, Q1+Q2, motoring + regen braking).
**Twist:** Ch1 + FWD only → type A (first quadrant); Ch2 + FWD + reversed E → type B (second quadrant).

**Q18 (APEPDCL-19):** In DC chopper, per-unit ripple is maximum when duty cycle α is
(a) 0.5 (b) 0.2 (c) 1.0 (d) 0.7
**Ans: (a)** — ΔIL = (Vdc/L)·D(1−D)·T, maximum at D = 0.5.
**Concept:** Same as Q2 — ripple peak at D = 0.5.
**Twist:** at D = 0.2 vs 0.5 → peak at 0.5; frequency doubled, D fixed → ripple halves.

**Q19 (APTransco-19):** Order of connection of L, C, D, MOSFET (left to right) in a boost converter
(a) L-series, Switch-series, C-parallel, D-parallel (b) Switch-series, L-series, V-parallel, D-parallel (c) L-series, Switch-parallel, D-series, C-parallel (d) Switch-series, L-parallel, C-parallel, D-series
**Ans: (c)** — Boost: L series with supply, switch across (parallel), D series, C parallel across output.
**Concept:** Boost topology: input L in series, switch in parallel, diode in series, output C in parallel.
**Twist:** buck → switch series, D parallel, L series, C parallel; buck-boost → switch series, D parallel, then inverted L–C.

**Q20 (APTransco-19):** Buck converter, L = 400 μH, di/dt = 7.5×10⁴ A/s when MOSFET triggered, Vs = 50 V. Output voltage?
(a) 15 V (b) 20 V (c) 25 V (d) 30 V
**Ans: (b)** — L·di/dt = Vs − Vo → 30 = 50 − Vo → Vo = 20 V.
**Concept:** Buck, ON interval: L·di/dt = Vs − Vo.
**Twist:** di/dt given during OFF → L·di/dt = −Vo → Vo = L·di/dt; different L (e.g. 200 μH) → Vo = 35 V.

**Q21 (TSSPDCL-22):** Resonant circuit, C = 10 µF, L = 1 mH, Vo = 100 V (switch closes at t=0). Peak current through the diode?
(a) 100 A (b) 50 A (c) 10 A (d) 20 A
**Ans: (c)** — Ipeak = Vo√(C/L) = 100√(10µ/1m) = 10 A.
**Concept:** ½CV² = ½LI² → Ipeak = V√(C/L) (capacitor→inductor energy transfer).
**Twist:** Vo doubled → peak doubles to 20 A; C quadrupled → peak doubles (×√C).

**Q22 (TSSPDCL-22):** Step-up chopper, Vdc = 200 V, Vo = 500 V, switch conduction time 150 µs. Pulse width of the output voltage?
(a) 250 µs (b) 150 µs (c) 100 µs (d) 110 µs
**Ans: (c)** — D = 1−Vdc/Vo = 0.6, T = Ton/D = 250 µs; pulse width = T−Ton = 100 µs.
**Concept:** Boost: Vo = Vdc/(1−D); output pulse width = off time = T−Ton.
**Twist:** ask total period → 250 µs; ask D → 0.6.

**Q23 (TSPSC-AEE-23):** Step-up chopper gives Vo = 100 V from Vs = 60 V (continuous source current). Duty ratio of the switch?
(a) 1/3 (b) 0.6 (c) 0.4 (d) 2/3
**Ans: (c)** — 1−D = Vs/Vo = 0.6 → D = 0.4.
**Concept:** Boost: D = 1 − Vs/Vo.
**Twist:** Vo = 150 V → D = 0.6; if it were a buck: D = Vo/Vs.

**Q24 (TSPSC-AEE-23):** Buck converter, 10 kHz, D = 0.6, L = 10 mH, Vs = 50 V; initial iL = 0. Energy stored in the inductor at the end of 10 complete switching cycles?
(a) 0.008 J (b) 0.005 J (c) 0.001 J (d) 0.01 J
**Ans: (b)** — Ramp up (50 V/L·DT = 0.3 A) minus ramp down (0.2 A) gives net +0.1 A/cycle → i10 = 1 A; E = ½·10m·1² = 5 mJ.
**Concept:** Inductor current grows by (2D−1)(Vs/L)T per cycle; energy = ½Li².
**Twist:** ask current after 10 cycles → 1 A; energy after 5 cycles → ½L(0.5)² = 1.25 mJ.

**Q25 (TSSPDCL-AE-2023):** Ripple voltage across the capacitor in a Buck-boost converter, 'f' switching frequency, α duty ratio:
(a) (1−α)/f² (b) (1−α)/f (c) α/f² (d) α/f
**Ans: (d)** — ΔVC = ΔQ/C = Io·D·T/C ∝ α/f.
**Concept:** Capacitor ripple ΔVC ∝ D/(f·C) (charge balance over ON interval).
**Twist:** frequency doubled, D constant → ripple HALVES (ΔVC ∝ 1/f); doubling Io → ripple doubles.

**Q26 (TSSPDCL-AE-2023):** In chopper-fed dc drives, correct quadrant combination:
(a) Type D operates in I and II (b) Type C operates in II and III (c) Type D operates in I and IV (d) Type C operates in I and IV
**Ans: (c)** — Type D operates in quadrants I and IV.
**Concept:** Type C → Q1+Q2 (motoring + forward braking); Type D → Q1+Q4 (motoring + reverse braking).
**Twist:** four-quadrant drive needs two type C/D or type E; Type B alone → second quadrant only.

**Q27 (TSPSC-AEE-23):** Average output voltage of Buck regulator:
(a) Va = KVs (b) Va = −KVs/(1−K) (c) Va = (1−K)Vs (d) Va = Vs/(1−K)
**Ans: (a)** — Buck: Va = D·Vs.
**Concept:** Buck Vo = D·Vs; Boost Vo = Vs/(1−D); Buck-boost Vo = −D·Vs/(1−D).
**Twist:** boost → (d); buck-boost → (b) with negative output.

**Q28 (TSPSC-AEE-23):** Identify the ripple factor expression:
(a) Vrms/Vdc (b) (Vrms/Vdc)² (c) √(Vrms²−Vdc²) (d) √((Vrms/Vdc)²−1)
**Ans: (d)** — RF = √((Vrms/Vdc)²−1).
**Concept:** RF = √(FF²−1), where form factor FF = Vrms/Vdc.
**Twist:** ask form factor → (a); for pure DC RF = 0; RF relates to harmonics content.

**Q29 (TSPSC-AEE-23):** Increasing order of the four quadrants of D.C. drives — I. Reverse motoring, II. Forward braking, III. Forward motoring, IV. Reverse braking:
(a) IV, III, II, I (b) II, III, IV, I (c) I, II, III, IV (d) III, II, I, IV
**Ans: (d)** — Standard cycle: III (fw motoring) → II (fw braking) → I (rev motoring) → IV (rev braking).
**Concept:** Four-quadrant map: QI +V,+I; QII +V,−I; QIII −V,−I; QIV −V,+I.
**Twist:** reverse braking = QIV; forward motoring = QI; reverse motoring = QIII.

**Q30 (TSPSC-AEE-23):** DC converter, R = 20 Ω, Vs = 280 V, switch ON-drop Vd = 2 V, D = 0.5. Average output voltage?
(a) 139 V (b) 280 V (c) 140 V (d) 278 V
**Ans: (a)** — Effective Vin = 280−2 = 278 V; Va = D·Vin = 0.5×278 = 139 V.
**Concept:** Buck output accounting for switch drop: Vo = D(Vs − Vd).
**Twist:** neglect Vd → 140 V (option c); average load current → 139/20 = 6.95 A.

**Q31 (TSPSC-AEE-23):** Forward motoring operation comes under which quadrant?
(a) Quadrant I (b) Quadrant II (c) Quadrant IV (d) Quadrant III
**Ans: (a)** — Forward motoring = Quadrant I (+V, +I).
**Concept:** Quadrant definitions: QI fw motoring, QII fw braking, QIII rev motoring, QIV rev braking.
**Twist:** reverse braking → QIV; reverse motoring → QIII; forward braking → QII.

**Q32 (TSPSC-AEE-23):** Correct pairs for switching regulators — I. Buck: Is = KIa; II. Boost: Is = Ia(1−K); III. Buck-boost: Is = IaK/(1−K):
(a) I, II and III (b) I and II (c) I and II (d) II and III
**Ans: (c)** — Per key; note solution gives Boost Is = Ia/(1−K), so II is FALSE — true set is I & III (option list has a typo: (b) and (c) are identical).
**Concept:** Source current: Buck Is = D·Ia; Boost Is = Ia/(1−D); Buck-boost Is = Ia·D/(1−D).
**Twist:** as D→1 boost source current grows (1/(1−D)); ask only buck-boost pair → III.

**Q33 (TSGenco-24):** True statements for dc-dc switch-mode converters: (i) duty ratio inversely proportional to control signal amplitude (constant-f PWM); (ii) switching frequency = frequency of the repetitive (sawtooth) waveform; (iii) integral of inductor voltage over one period > 0; (iv) average capacitor current in periodic steady state = 0:
(a) (i) and (ii) only (b) (ii) and (iii) only (b) (ii) and (iv) only (d) (iii) and (iv) only
**Ans: (c)** — (ii) and (iv) are true; (i) false (D ∝ Vcontrol), (iii) false (volt-second balance → integral = 0).
**Concept:** PWM modulation (D = Vc/V̂st), inductor volt-second balance, capacitor charge balance.
**Twist:** (i) corrected → duty ratio proportional to control signal; (iii) corrected → integral equals zero.

**Q34 (TSGenco-24):** Buck-boost converter at 10 kHz, current at edge of continuous conduction, Vs = 100 V, Vo = 500 V, L = 100 μH. On-time and peak inductor current:
(a) 83.3 μs, 0.48 A (b) 250 μs, 0.48 A (c) 250 μs, 83.3 A (d) 250 μs, 83.88 A
**Ans: (d)** — Equating ramp slopes 100·DT/L = 500(1−D)T/L → D = 5/6, Ton = 83.3 μs; Ip = (100/L)·DT ≈ 83.88 A (key: d).
**Concept:** Volt-second balance + triangular current at boundary conduction; Ip = (Vs/L)·Ton.
**Twist:** note Ton computes to 83.3 μs (option a) but that option's current is wrong — the key takes (d); frequency doubled → Ton halves to ~41.7 μs.

## Unit 4: DC to AC Converters — Inverters (31 Qs)

**Q1 (APGenco-12):** In single pulse modulation used in PWM inverters, pulse width needed to eliminate the third harmonic.
(a) 60° (b) 90° (c) 110° (d) 120°
**Ans: (d)** — single-pulse PWM eliminates nth harmonic when pulse width 2d = 2π/n; for n=3, width = 120°.
**Concept:** Harmonic elimination by single pulse modulation: width 2π/n.
**Twist:** ask 5th harmonic → 72°; ask 7th harmonic → 2π/7 ≈ 51.4°; ask 3rd with width 120° → 120°.

**Q2 (APSPDCL-12):** Single-phase bridge output is a quasi-square wave (fig: ±V steps, each 120° wide); which harmonics are absent?
(a) 5th and 7th (b) 3rd, 5th, 7th (c) 3rd, 9th, 15th (d) 3rd, 7th
**Ans: (c)** — a 120°-wide pulse output is free of all triplen (multiples-of-3) harmonics: 3rd, 9th, 15th.
**Concept:** 120° quasi-square waveform → triplen harmonics absent.
**Twist:** 180° square wave (no zero interval) → only odd harmonics, triplen NOT eliminated; pulse width 2π/n → that nth harmonic eliminated.

**Q3 (Transco-12):** An inverter converts…
(a) dc to dc (b) ac to dc (c) dc to ac at constant frequency (d) dc to ac at variable frequency
**Ans: (d)** — inverter converts dc power to ac power at required (variable) voltage and frequency.
**Concept:** Inverter = dc → variable-frequency ac (rectifier does the reverse).
**Twist:** ask rectifier → ac to dc; ask cycloconverter → ac to ac; "constant frequency" option is a distractor.

**Q4 (EPDCL-14):** A PWM switching scheme is used with a three-phase inverter to…
(a) Reduce THD with modest filtering (b) Minimize load on dc side (c) Increase life of batteries (d) Reduce low-order harmonics and increase high-order harmonics
**Ans: (d)** — PWM eliminates low-order harmonics by pulse-width selection; more pulses/cycle pushes energy into higher-order harmonics.
**Concept:** PWM shifts harmonic content from low to high order.
**Twist:** ask "why is THD lowered" → harmonics sit at high order, removed by small filter (that is the (a) reason in Q6); ask about pulse count → higher count → higher-order harmonics.

**Q5 (APSPDCL-14):** Multiple-pulse equal-width PWM, carrier 15 kHz, fundamental 500 Hz. Number of pulses per half cycle.
(a) 5 (b) 10 (c) 12 (d) 15
**Ans: (d)** — N = fc/(2f) = 15000/(2×500) = 15.
**Concept:** pulses per half-cycle = fc/(2f).
**Twist:** carrier 10 kHz @ 500 Hz → N = 10; ask pulses per full cycle → fc/f = 30.

**Q6 (ISRO-14):** PWM switching scheme used with three-phase inverters to…
(a) reduce low-order harmonics and increase high-order harmonics (b) minimize load on dc side (c) increase life of batteries (d) reduce THD with modest filtering
**Ans: (a)** — same PWM harmonic-shift principle as Q4.
**Concept:** PWM → low-order harmonics removed, THD reduced with modest filtering.
**Twist:** ask "effect on THD" → reduced with modest filtering (option d); ask battery life / dc loading → irrelevant distractors.

**Q7 (TSGenco-15):** A single-phase VSI square-wave feeds pure inductive load. Load current waveform?
(a) Sinusoidal (b) Rectangular (c) Trapezoidal (d) Triangular
**Ans: (d)** — integral of the square voltage across pure L is triangular, mean zero.
**Concept:** VSI + pure L load → triangular current.
**Twist:** pure R load → square (rectangular) current; R–L load → exponentially rounded/trapezoidal waveform.

**Q8 (TSGenco-15):** A VSI is normally employed when…
(a) source L large, load L small (b) source L small, load L large (c) both inductances small (d) both inductances large
**Ans: (b)** — VSI wants a stiff (low-impedance) source and a current-stiff (high-L) load.
**Concept:** VSI suitability — small source inductance, large load inductance.
**Twist:** CSI is suitable when source L large and load L small (reverse).

**Q9 (TSTransco-15):** A VSI will have better performance if its…
(a) load L small, source L large (b) both L small (c) both L large (d) load L large, source L small
**Ans: (d)** — same principle as Q8: large load inductance, small source inductance.
**Concept:** VSI performance — low source impedance, high-impedance/current-stiff load.
**Twist:** ask about CSI → load L small, source L large.

**Q10 (TSSPDCL-15):** 3-φ VSI, 180° conduction, star resistive load, Vdc = 100 V. Peak-to-peak output line voltage?
(a) 200/3 V (b) 200 V (c) 400/3 V (d) 200√3 V
**Ans: (b)** — line voltage quasi-square with magnitude ±Vdc, so peak-to-peak = 2Vdc = 200 V.
**Concept:** 180° conduction: V_LL peak = Vdc (six-step line waveform).
**Twist:** ask peak phase voltage (star, 180°) → 2Vdc/3 ≈ 66.7 V; 120° conduction also peaks line at Vdc → peak-to-peak still 2Vdc.

**Q11 (TSNPDCL-15):** Fundamental component of single-phase full-bridge inverter output (Vs = dc input)?
(a) (Vs/π) sinωt (b) (2Vs/π) sinωt (c) (4Vs/3π) sinωt (d) (4Vs/π) sinωt
**Ans: (d)** — full-bridge fundamental peak = 4Vdc/π.
**Concept:** full-bridge: v₀ = Σ (4Vdc/nπ) sin(nωt), n odd; fundamental = 4Vdc/π.
**Twist:** ask half-bridge → 2Vdc/π; ask RMS fundamental → (2√2/π)Vdc ≈ 0.9 Vdc.

**Q12 (TSNPDCL-15):** Full-bridge inverter, Vs = 220 V DC, T = 1 ms, resistive load. RMS value of fundamental load voltage?
(a) 110√2 (b) 280√2 (c) 160√2 (d) 140√2
**Ans: (d)** — V1rms = (2√2/π)Vdc = (2√2/π)×220 = 140√2 V.
**Concept:** 1-Φ bridge fundamental V1rms = (2√2/π)Vs ≈ 0.9 Vs.
**Twist:** Vs = 110 V → 70√2 V; Vs = 230 V → (2√2/π)×230 V; ask peak fundamental → ×√2.

**Q13 (APGenco-17):** 3-φ MOSFET bridge inverter, switches numbered 1,2,3 top and 4,5,6 bottom. Triggering sequence giving balanced output?
(a) 1,2,3,4,5,6 (b) 1,5,3,4,2,6 (c) 1,6,2,4,3,5 (d) 1,4,2,5,3,6
**Ans: (c)** — with standard numbering, balanced gating sequence is 1,6,2,4,3,5 (180° conduction).
**Concept:** 3-φ VSI 180° gating sequence = 1,6,2,4,3,5 (three switches on per step).
**Twist:** 120° conduction mode → 1,2,3,4,5,6 (two switches on per step); reorder switch numbers → re-map sequence.

**Q14 (TSSPDCL-18):** Statements on inverters: 1 line-commutated can act as isolated ac source; 2 force-commutated give adjustable independent V & f; 3 thyristor inverters need no extra commutation circuitry; 4 IGBT/MOSFET inverters more reliable, cheaper, less complex. Correct ones?
(a) 1,3 (b) 1,3,4 (c) 2,4 (d) 1,4
**Ans: (c)** — line-commutated needs the ac grid (not isolated) and thyristors DO need commutation circuits; so only 2 and 4 hold.
**Concept:** line-commutated vs force-commutated; self-commutated (IGBT/MOSFET) vs thyristor.
**Twist:** ask which are FALSE → 1 and 3; ask "isolated ac source" device → force-commutated inverter.

**Q15 (TSTransco-18):** Output frequency of a single-phase PWM converter is regulated by…
(a) increasing sine amplitude (b) varying sine frequency (c) varying triangular frequency (d) triangular amplitude
**Ans: (b)** — in sinusoidal PWM, output frequency follows the modulating sine wave frequency.
**Concept:** SPWM — fundamental frequency = frequency of the sine (modulating) signal.
**Twist:** vary triangular-wave frequency → changes carrier/switching frequency, not fundamental; vary sine amplitude → changes output voltage (modulation index).

**Q16 (APEPDCL-19):** In voltage source inverters…
(a) both V and I independent of Z (b) V depends on Z, I doesn't (c) both V and I depend on Z (d) V does not depend on Z, I depends on Z
**Ans: (d)** — VSI: stiff output voltage independent of load; only load current varies with Z.
**Concept:** VSI — V fixed by dc link, I = V/Z (load-dependent).
**Twist:** CSI → I independent of load, V depends on Z (dual).

**Q17 (APEPDCL-19):** 1-φ VSI feeds pure inductive load with square-wave source. Nature of load current?
(a) Triangular (b) Sinusoidal (c) Trapezoidal (d) Square-wave
**Ans: (a)** — square V across pure L integrates to triangular current.
**Concept:** VSI + pure L → triangular current (same as Q7).
**Twist:** pure R load → square current; R–L load → trapezoidal/exponential.

**Q18 (APTransco-19):** Single-phase full-bridge (S1–S4 with feedback diodes D1–D4) driving R–L load. Conducting devices in intervals t0–t1, t1–t2, t2–t3, t3–t4?
(a) S1,S4 / D2,D3 / S2,S3 / D1,D4 (b) D1,D4 / S1,S4 / D2,D3 / S2,S3 (c) D2,D3 / S2,S3 / D1,D4 / S1,S4 (d) S2,S3 / D1,D4 / S1,S4 / D2,D3
**Ans: (b)** — start (+v, −i) → feedback D1,D4; then (+v,+i) → S1,S4; then (−v,+i) → D2,D3; then (−v,−i) → S2,S3.
**Concept:** diode conduction during freewheeling when output voltage and current oppose.
**Twist:** swap load power factor → diode/switch intervals shift; ask only first interval → D1,D4.

**Q19 (APSPDCL-19):** Firing sequence of a 3-φ bridge: 1,5,6 / 2,6,1 / 3,1,2 / 4,2,3 / 5,3,4 / 6,4,5, each 60°. Conduction mode?
(a) 120° (b) 180° (c) 90° (d) 240°
**Ans: (b)** — three switches conduct in each 60° interval → 180° conduction.
**Concept:** 180° mode — 3 switches on at a time; 120° mode — 2 switches on.
**Twist:** if two switches per interval (e.g., 1,6 / 1,2 / 2,3 …) → 120° mode.

**Q20 (APPSC-20):** Harmonics in three-phase inverters may be reduced with the help of…
(a) both passive and active filters (b) passive filters (c) active filters (d) neither
**Ans: (a)** — harmonic reduction uses both passive (LC) and active filters.
**Concept:** inverter harmonic filtering — passive + active combination.
**Twist:** ask about PWM alone → reduces low-order harmonics but not total elimination; single filter type → incomplete.

**Q21 (APPSC-20):** In a three-phase bridge inverter, gating signals for the three phases have a phase difference of…
(a) 120° (b) 60° (c) 90° (d) 180°
**Ans: (a)** — phase gating signals are 120° apart (balanced three-phase).
**Concept:** 3-φ inverter gating phase shift = 120°.
**Twist:** switching steps are every 60° (in 180° mode) — don't confuse; single-phase two legs → 180° between legs.

**Q22 (TSSPDCL-22):** In single-pulse modulation, if pulse width is 72°, which harmonic is eliminated?
(a) Fifth (b) Third (c) Seventh (d) Eleventh
**Ans: (a)** — n = 360°/72° = 5th harmonic removed (2d = 2π/n).
**Concept:** single-pulse elimination: n = 360°/pulse-width.
**Twist:** pulse width 120° → 3rd eliminated; 51.4° → 7th; 32.7° → 11th.

**Q23 (TSSPDCL-22):** A current source inverter is obtained by inserting a large…
(a) capacitance in parallel with dc supply (b) inductance in parallel with dc supply (c) capacitance in series with dc supply (d) inductance in series with dc supply
**Ans: (d)** — a large series inductance makes the dc source current-stiff.
**Concept:** CSI = dc link with large series inductance (current stiff).
**Twist:** VSI = large capacitance in parallel across dc supply (voltage stiff).

**Q24 (TSSPDCL-22):** A PWM signal can be generated by…
(a) an unstable multivibrator (b) integrating a PPM signal (c) a monostable multivibrator (d) differentiating a PPM signal
**Ans: (c)** — monostable (one-shot) multivibrator generates PWM.
**Concept:** PWM generation by monostable multivibrator (pulse width ∝ timing).
**Twist:** ask PPM generation → differentiate a PWM signal; integrating PPM → PWM (distractor).

**Q25 (TSNPDCL-22):** 3-φ IM fed by 3-φ inverter with fundamental and odd harmonics (no triplen). Slip at the 5th harmonic component?
(a) exactly 0.2 (b) exactly 1.0 (c) greater than 1.00 (d) between 0.5 and 1.0
**Ans: (c)** — 5th harmonic is negative-sequence → slip = (n+1)/n = 1.2 > 1.
**Concept:** harmonic slip for negative-sequence harmonic > 1; 5th is the lowest harmonic present (triplens absent).
**Twist:** ask 7th harmonic (positive sequence) → slip = (7−1)/7 = 6/7 ≈ 0.857; ask 11th → 10/11.

**Q26 (TSPSC-AEE-23):** 3-φ bridge inverter in square-wave mode — output voltage waveforms contain…
(a) even and odd but no triplen (b) only triplen (c) only odd-order (d) only even-order
**Ans: (c)** — square-wave output has odd symmetry → only odd harmonics.
**Concept:** 3-φ square-wave line output = odd harmonics only (no even, no triplen).
**Twist:** ask line-to-line waveform → triplen absent too; ask phase-to-neutral (with neutral) → triplen may appear.

**Q27 (TSPSC-AEE-23):** Statements on 3-φ VSI: A need voltage-bidirectional two-quadrant devices; B PWM reduces harmonic frequency content; C in 180° mode a new switch gates every 60°. Which true?
(a) C only (b) A and B only (c) B and C only (d) A only
**Ans: (c)** — VSI switches are unipolar voltage + current-bidirectional (statement A wrong); B and C correct.
**Concept:** VSI switch requirement — unipolar voltage, bidirectional current; 180° mode steps every 60°.
**Twist:** statement A rephrased "current-bidirectional, unipolar" → then true; ask CSI → bidirectional voltage, unidirectional current.

**Q28 (TSPSC-AEE-23):** A VSI is most suitable where…
(a) both source and load inductances small (b) source L large, load L small (c) source L small, load L large (d) both inductances large
**Ans: (c)** — VSI best with low-impedance (small-L) source and high-L load (same as Q8/Q9).
**Concept:** VSI suitability — small source inductance, large load inductance.
**Twist:** ask CSI → large source inductance, small load inductance.

**Q29 (TSSPDCL-AE-2023):** Five equal pulses per half cycle, each π/15 rad wide, Vdc = 100 V. RMS output voltage?
(a) 57.7 V (b) 70.7 V (c) 86.6 V (d) 50.0 V
**Ans: (a)** — total conduction angle per cycle = 2×(5×π/15) = 2π/3 → duty 1/3 → Vrms = Vdc/√3 = 100/√3 = 57.7 V.
**Concept:** multipulse PWM rms output = Vdc√(duty-cycle), duty = total ON angle / 2π.
**Twist:** single pulse π/15 wide → Vrms = Vdc/√(15) ≈ 25.8 V; pulses wider (total 2π/3 per half → duty 2/3) → Vrms = 100√(2/3) ≈ 81.6 V.

**Q30 (—):** Inverter performance parameters: I. HFn = Von/V01 for n > 1; II. THD = (1/V01)·√(Σ V²on), n = 2,3,…
(a) Neither I nor II (b) Only II (c) Only I (d) Both I and II
**Ans: (d)** — both harmonic factor (per individual harmonic) and THD definitions are correct.
**Concept:** HFn = Von/V01 (individual harmonic measure); THD = (1/V01)√(ΣVon²) (waveform closeness).
**Twist:** THD including the fundamental term → incorrect; HF defined for n = 1 → incorrect (only n > 1).

**Q31 (TSGenco-24):** Full-bridge inverter feeds series R–L–C load, R = 3 Ω, XL = 6 Ω, XC = 10 Ω, Vdc = 400 V, f0 = 50 Hz, SCR switches. Turn-off mechanism?
(a) Forced commutation (b) Load commutation (c) External pulse commutation (d) Line commutation
**Ans: (b)** — XC > XL → leading pf, so SCRs turn off naturally by the load (load commutation).
**Concept:** load (natural) commutation when load pf is leading (capacitive).
**Twist:** if XL > XC (lagging/inductive load) → forced commutation required; line commutation needs an ac source — not applicable to standalone inverter.

## Unit 5: AC to AC Converters (12 Qs)

**Q1 (APSPDCL-12):** Output waveform (conducting α to π+α each half-cycle, resistive load) is obtained from?
(a) Controlled rectifier (b) AC chopper (c) DC chopper (d) DIAC-TRIAC phase control circuit
**Ans: (d)** — The symmetric phase-controlled waveform is produced by a TRIAC / AC voltage regulator.
**Concept:** AC voltage controller (TRIAC phase control) — symmetric conduction in both half-cycles.
**Twist:** ask single-direction output (only one half-cycle conducts) → half-controlled rectifier/SCR. Ask on-off bursts → AC chopper (integral cycle control).

**Q2 (HMWS-15):** In which of the following can both frequency and voltage be controlled?
(a) Inverter, cycloconverter and AC voltage controller (b) Cycloconverter and AC voltage controller (c) Inverter and cycloconverter (d) Inverter and AC voltage controller
**Ans: (c)** — Inverter and cycloconverter control both V and f; AC voltage controller controls voltage only.
**Concept:** Inverter and cycloconverter = variable V & f; AC voltage controller = variable V, fixed f.
**Twist:** ask "controls only voltage" → AC voltage controller. Ask "fixed-frequency variable-voltage only" → AC voltage controller.

**Q3 (HMWS-15):** Firing angle of a 1-φ AC voltage controller is zero, resistive load. Input current wave shape is?
(a) AC sine wave (b) constant DC wave (c) DC sine wave (d) AC square wave
**Ans: (a)** — At α = 0 the full input sine wave passes unclipped.
**Concept:** AC voltage controller: at α = 0 (fully on) output/input is a pure sine wave.
**Twist:** firing angle > 0 → chopped sine wave (part of half-cycle missing). Inductive (RL) load → continuous, near-sinusoidal current with phase delay.

**Q4 (HMWS-15):** Output frequency of a 1-φ cycloconverter is 12 Hz. Input frequency is?
(a) 30 Hz (b) 60 Hz (c) 40 Hz (d) 50 Hz
**Ans: (b)** — 60 Hz = 5 × 12 Hz (integral-multiple relation per given solution).
**Concept:** Cycloconverter output frequency is an integral sub-multiple/ratio of input frequency.
**Twist:** real cycloconverters are step-down only (f_out < f_in), so asking "input 50 Hz, output 25 Hz" → feasible; "output > input" → not naturally possible (needs forced commutation).

**Q5 (TSSPDCL-15):** To get minimum harmonic distortion in a 3-φ to 3-φ cycloconverter, the number of SCRs required is?
(a) 12 (b) 18 (c) 36 (d) 72
**Ans: (c)** — 36 SCRs (6 per phase group) reduce THD in the output.
**Concept:** Cycloconverter SCR count: 3φ-to-1φ = 12 SCRs; 3φ-to-3φ = 36 SCRs (more devices → lower harmonic distortion).
**Twist:** ask 3φ-to-1φ cycloconverter → 12 SCRs. Ask for the simplest configuration → fewer SCRs but higher THD.

**Q6 (TSSPDCL-15):** Input to 1-φ full-wave AC voltage controller is v = 282.8 sin(314t). Resistive load, output 162 V. Input power factor is?
(a) 0.573 (b) 0.900 (c) 0.810 (d) 0.656
**Ans: (c)** — IPF = Vor/Vs = 162/200 = 0.81.
**Concept:** AC voltage controller: input power factor = Vor/Vs (resistive load, sinusoidal source).
**Twist:** give α directly → compute Vor first then IPF = Vor/Vs. Inductive load → IPF worse, not simply Vor/Vs.

**Q7 (TSSPDCL-15):** Input current of an AC voltage controller is sinusoidal. Type of load is ____ and firing angle (rad) is ____.
(a) capacitive...zero (b) capacitive...π/2 (c) inductive...π (d) resistive...2π
**Ans: (d)** — Resistive load with firing angle 0 or 2π gives a pure sinusoidal input current.
**Concept:** AC voltage controller — input current is sinusoidal only for resistive load at α = 0 (or 2π).
**Twist:** ask "inductive load" → current is non-sinusoidal/continuous, never pure sine. Ask "minimum α for control" → α = 0 gives no control.

**Q8 (TSNPDCL-15):** Statements: (a) Step-up cycloconverters require forced commutation. (b) Step-down cycloconverters operate on line commutation. (c) Step-up or step-down cycloconverters can be load commutated for any type of load. Correct statements?
(a) (a) only (b) (a), (c) (c) (a), (b) (d) (c) only
**Ans: (c)** — (a) and (b) are true; load commutation is not valid for any type of load.
**Concept:** Cycloconverter commutation: step-up = forced commutation; step-down = line/natural commutation.
**Twist:** ask "step-down cycloconverter requires" → natural/line commutation. Ask "which commutation works for all loads" → forced commutation (not load commutation).

**Q9 (TSNPDCL-15):** Single-phase voltage controller, 220 V, 50 Hz, load 10 Ω, with 9 cycles ON and 7 cycles OFF. RMS output voltage and input power factor are?
(a) 170 V, 0.7 (b) 171 V, 0.78 (c) 165 V, 0.75 (d) 180 V, 0.6
**Ans: (c)** — Vor = Vs·√(n/(n+m)) = 220·√(9/16) = 165 V; IPF = √(n/(n+m)) = 3/4 = 0.75.
**Concept:** On-off (integral cycle) control: Vor = Vs√(n/(n+m)), input power factor = √(n/(n+m)).
**Twist:** change n and m (e.g., 6 on / 4 off) → Vor = 220√(6/10) ≈ 170 V, IPF = 0.775. Ask "which control has less harmonic distortion" → integral cycle control over phase control.

**Q10 (APTransco-17):** A TRIAC in a 1-φ circuit at V volts with firing delay angle α feeding a resistive load R. Power loss in the load is?
(a) 2V²sin2α/(πR) (b) (V²/πR)[cos2α/2] (c) (V²/πR)[π−α+sin2α/2] (d) (V²/πR)[π+α−sin2α/2]
**Ans: (c)** — Po = Vor²/R = (V²/πR)[(π−α) + (sin2α)/2].
**Concept:** AC voltage controller output power: Po = (Vm²/2πR)[(π−α) + (sin2α)/2].
**Twist:** ask RMS output voltage instead → Vor = (Vm/√(2π))√[(π−α)+(sin2α)/2]. α = π (fully off) → zero power.

**Q11 (APEPDCL-19):** Thyristor-based 1-φ voltage regulator (figure: Vs sin(ωt) through thyristor to R) with firing angle α = 90°. RMS output voltage is?
(a) 2Vs/π (b) Vs/2 (c) Vs/π (d) Vs/√2
**Ans: (d)** — Vor = (Vm/√(2π))√[(π−α)+sin2α/2]; α = 90° (sin2α = 0) → Vs/√2.
**Concept:** AC voltage controller RMS output: Vor = (Vm/√(2π))√[(π−α)+(sin2α)/2].
**Twist:** α = 0 → Vor = Vs (full conduction). α = π → Vor = 0. Ask α = 60° → Vor = Vs√[(π−π/3+sin120°/2)/π] ≈ 0.84Vs.

**Q12 (APTransco-19):** A power electronic controller gives symmetric output from π/6 to π and 7π/6 to 2π across a resistive load over a cycle. The circuit contains?
(a) a diode (b) two diodes in anti-parallel (c) a TRIAC (d) an SCR
**Ans: (c)** — Symmetric conduction in both half-cycles (α = 30°) requires a TRIAC (or AC voltage regulator).
**Concept:** TRIAC / AC voltage controller gives symmetric phase-controlled conduction in both half-cycles.
**Twist:** conduction only in one half-cycle (α to π) → diode/SCR (half-wave). Anti-parallel diodes conduct without control → full sine, not phase-shifted.

## Unit 6: Electric Drives (28 Qs)

**Q1 (APSPDCL-12):** Chopper (SCR at 1 kHz, TON = 0.5 ms) feeding a 200 V, 1000 rpm, 10 A dc motor; neglect Ra, Tm constant. Find motor speed.
(a) 1000 rpm (b) 500 rpm (c) 1500 rpm (d) 750 rpm
**Ans: (b)** — D = 0.5 → Vt = 100 V → motor runs at half rated speed (500 rpm).
**Concept:** Chopper-fed DC drive: Vt = D·Vdc; N ∝ Vt (constant flux).
**Twist:** D = 1 → 1000 rpm (full speed). D increased → speed rises linearly.

**Q2 (APSPDCL-12):** Converter feeding a DC machine (figure: Va, Eb, armature current shown). Identify mode of operation.
(a) Motoring (b) Regenerating (c) Plugging (d) Rheostatic braking
**Ans: (c)** — Armature current flows away from machine → plugging.
**Concept:** Drive quadrants — plugging = current reversal against driving voltage.
**Twist:** Current into machine with V > Eb → motoring. Braking with energy to source (current out, Eb > V) → regenerative.

**Q3 (Transco-12):** Preferred thyristor method for speed control of AC drive.
(a) Phase control (b) Integral cycle control (c) Single pulse PWM control (d) Sinusoidal PWM control
**Ans: (a)** — PWM needs fast switching; thyristors suit phase control.
**Concept:** Phase control (firing angle) for thyristor AC drives.
**Twist:** Ask for IGBT/GTO drive → PWM control. Ask voltage magnitude only → integral cycle control.

**Q4 (EPDCL-14):** 440 V, 3-φ, 10-pole, 50 Hz synchronous motor delivering T = 50/π N·m. Power delivered?
(a) 50 W (b) 500 W (c) 1000 W (d) 2000 W
**Ans: (c)** — ωs = 20π rad/s; P = (50/π)(20π) = 1000 W.
**Concept:** P = T·ω; synchronous speed ωs = 4πf/P.
**Twist:** Ask torque for given P → T = P/ω. Change poles to 4 → ωs = 50π rad/s → P = 2500 W.

**Q5 (TSSPDCL-15):** 3-φ, 2-pole, 60 Hz synchronous motor speed-controlled by step-down 3-φ cycloconverter. Maximum possible motor speed?
(a) 1200 rpm (b) 3000 rpm (c) 1000 rpm (d) 3600 rpm
**Ans: (a)** — Ns = 3600 rpm; cycloconverter steps frequency (speed) down by integral multiples → 1200 rpm.
**Concept:** Cycloconverter output frequency is a submultiple of supply frequency; N = Ns/harmonic.
**Twist:** Ask speeds possible → 3600, 1800, 1200, 900… . Step-up (inverter mode) not possible → no speed above 3600 rpm.

**Q6 (TSTransco-15):** Chopper-controlled rotor resistance of wound-rotor IM: 2 Ω fixed, +4 Ω during OFF (4 ms), f = 200 Hz. Average rotor resistance?
(a) 26/5 Ω (b) 24/5 Ω (c) 18/5 Ω (d) 16/5 Ω
**Ans: (a)** — T = 5 ms, Ton = 1 ms; Ravg = (2×1 + 6×4)/5 = 26/5 Ω.
**Concept:** Chopper-chopped rotor resistance: Ravg = (Ron·Ton + Roff·Toff)/T.
**Twist:** Swap Toff → Ton values → different Ravg. Change frequency → T changes → Ravg changes.

**Q7 (TSGenco-15):** Self-controlled synchronous motor fed from variable-frequency inverter — correct statement?
(a) rotor poles invariably have damper windings (b) there are stability problems (c) rotor speed decides stator frequency (d) stator frequency decides rotor speed
**Ans: (d)** — Stator supply frequency is adjusted so synchronous speed tracks rotor speed; rotor never pulls out of step.
**Concept:** Self-controlled synchronous drive: frequency locked to rotor (no damper windings/hunting).
**Twist:** Ask "damper winding needed?" → No, hunting eliminated. Ask open/closed-loop drive → externally controlled requires damper windings.

**Q8 (HMWS-15):** 3-φ, 50 Hz IM controlled by VSI. Frequency of rotor current due to 5th harmonic?
(a) exactly 250 Hz (b) less than 250 Hz (c) more than 250 Hz (d) equal to 50 Hz
**Ans: (c)** — For the 5th harmonic slip > 1; f_rotor = s·f_harmonic > 250 Hz.
**Concept:** Rotor current frequency = s·f; harmonic slips are > 1.
**Twist:** Ask fundamental rotor frequency → s·50 (small). Ask 7th harmonic → even higher frequency.

**Q9 (APTransco-17):** In an adjustable-speed AC drive, which quantity reduces above rated speed?
(a) developed torque (b) stator frequency (c) reduced starting torque (d) stator current
**Ans: (a)** — Above base speed → field-flux (constant-power) control → torque ∝ 1/speed.
**Concept:** Constant-power region: T ∝ 1/N above base speed.
**Twist:** Ask below base speed → constant torque, constant flux (V/f). Ask which control → field/voltage weakening.

**Q10 (APGenco-17):** 3-φ inverter-fed IM drive, THD = 4%, peak fundamental load current = 4 A. RMS net harmonic current?
(a) 0.08 A (b) 0.08√2 A (c) 0.16 A (d) 0.16√2 A
**Ans: (b)** — I1 = 4/√2 A; √(I²−I1²) = 0.04×4/√2 = 0.08√2 A.
**Concept:** THD = √(I²−I1²)/I1; peak → rms fundamental conversion.
**Twist:** Ask rms fundamental → 2.83 A. Change THD to 8% → 0.16√2 A.

**Q11 (TSTransco-18):** Single-phase half-wave converter + freewheel diode SEP DC drive runs at 1000 rpm at α = 45°. Replaced by single-phase semi-converter → speed?
(a) 2000 rpm (b) 1500 rpm (c) 1000 rpm (d) 500 rpm
**Ans: (a)** — Semi-converter output doubles (Vm/π vs Vm/2π) → speed doubles to 2000 rpm.
**Concept:** N ∝ Vt; half-wave Vt = (Vm/2π)(1+cosα), semi Vt = (Vm/π)(1+cosα).
**Twist:** Full-converter instead → Vt = (2Vm/π)cosα → speed changes. Ask with α = 0 → max voltage.

**Q12 (TSTransco-18):** 3-φ full-wave controlled rectifier feeding SEP DC motor: Tc = 150 N·m, ω = 75 rad/s, Ia = 50 A. Back emf?
(a) 200 V (b) 225 V (c) 250 V (d) 275 V
**Ans: (b)** — Power balance T·ω = Eb·Ia → Eb = 150×75/50 = 225 V.
**Concept:** Electromagnetic power balance: Eb·Ia = T·ω.
**Twist:** Ask torque → T = Eb·Ia/ω. Change Ia → Eb changes inversely.

**Q13 (APTransco-19):** SEP DC motor, single-phase SCR full-converter at 200 V AC, 40 A at α = 45°, Ra = 0.25 Ω. Back emf?
(a) (200/π − 10) V (b) (200/π + 10) V (c) (400/π − 10) V (d) (400/π + 10) V
**Ans: (c)** — Vt = (2Vm/π)cosα = 400/π V; Eb = 400/π − 40×0.25 = 400/π − 10 V.
**Concept:** Full-converter Vt = (2Vm/π)cosα; Eb = Vt − Ia·Ra.
**Twist:** Semi-converter → Vt = (Vm/π)(1+cosα) → different Eb. α = 0 → Eb = 400/π − 10 (max).

**Q14 (APTransco-19):** Adjustable-speed DC drive via AC–DC converter, armature voltage control up to base speed — what happens?
(a) torque increases linearly with speed (b) torque decreases linearly with speed (c) torque remains constant (d) power remains constant
**Ans: (c)** — Up to base speed (armature voltage control, constant flux) torque stays constant.
**Concept:** Constant-torque region below base speed; Vt control ∝ speed.
**Twist:** Above base speed → field weakening → constant power. Ask rated torque limit → depends on Ia rating.

**Q15 (APSPDCL-19):** Circuit (R1, R2 per phase, 3-φ supply, ACVR) on rotor side of 3-φ slip-ring IM. Effective rotor resistance/phase at α = 180°?
(a) R2 (b) R1 + R2 (c) R1 (d) R1 || R2
**Ans: (c)** — At α = 180° ACVR never fires → R2 disconnected → effective resistance = R1.
**Concept:** ACVR (AC voltage regulator) -controlled rotor resistance; α = 180° = fully OFF.
**Twist:** α = 0° → R2 fully in circuit → R1 + R2. Intermediate α → average resistance between R1 and R1+R2.

**Q16 (APEPDCL-19):** Synchronous motor fed from VSI — which controls are possible? I) voltage control II) V/f control III) current control IV) frequency control
(a) I, II and IV (b) I and II (c) III and IV (d) I, III and IV
**Ans: (a)** — VSI gives voltage, frequency and combined V/f control; not current control.
**Concept:** VSI → voltage + frequency (V/f) control; CSI → current control.
**Twist:** Ask with CSI → current control (III). Ask V/f only → I and II.

**Q17 (APEPDCL-19):** Drive a DC shunt motor at different speeds in both directions and brake in both directions — which converter?
(a) Dual converter (b) Half-controlled thyristor bridge (c) Full-controlled thyristor bridge (d) Diode bridge
**Ans: (a)** — Both-direction drive + braking needs four-quadrant operation → dual converter.
**Concept:** Four-quadrant DC drive → dual converter.
**Twist:** Two-quadrant (one direction + braking) → single full converter with armature/field reversal. Three-quadrant → dual converter without one quadrant.

**Q18 (TSNPDCL-15):** SEP DC motor, 3-φ semi-converter from 3-φ 440 V 50 Hz, Ra = 1 Ω, Kt = 2 N·m/A, α = 45°, torque 50 N·m. Back emf?
(a) 460 V (b) 482 V (c) 420 V (d) 333 V
**Ans: (b)** — Ia = 50/2 = 25 A; Vt = (3Vml/2π)(1+cos45°) = 507.16 V; Eb = 507.16 − 25×1 ≈ 482 V.
**Concept:** 3-φ semi-converter Vt = (3Vml/2π)(1+cosα); T = Kt·Ia; Eb = Vt − Ia·Ra.
**Twist:** α = 0° → Vt = 3Vml/π → higher Eb. Ask Ia from given Eb → Ia = (Vt − Eb)/Ra.

**Q19 (TSPSC-AEE023):** 200 V, 1000 rpm, 100 A SEP DC motor (Ra = 0.1 Ω) fed by step-down chopper from 300 V. Duty cycle for rated torque at 500 rpm?
(a) 0.35 (b) 0.25 (c) 0.84 (d) 0.5
**Ans: (a)** — Eb1 = 190 V; Eb2 = (500/1000)190 = 95 V; Vt = 95 + 10 = 105 V; D = 105/300 = 0.35.
**Concept:** N ∝ Eb/φ; Eb = Vt − Ia·Ra; chopper Vt = D·Vs.
**Twist:** Ask speed at given D → reverse the steps. Change source to 250 V → D = 0.42.

**Q20 (TSPSC-AEE023):** Constant V/f-controlled IM from VVVF VSI, operated below base speed — true of torque–speed characteristics?
(a) starting torque decreases with f, max torque decreases (b) starting torque increases with ↓f, max torque unchanged (c) starting torque decreases with ↓f, max torque unchanged (d) starting torque increases with ↓f, max torque decreases
**Ans: (b)** — Below base speed, V/f = const → flux constant → max torque unchanged; starting torque rises as f decreases.
**Concept:** V/f control → constant flux, constant maximum torque below base speed.
**Twist:** Above base speed (V constant) → flux falls → max torque decreases (constant power). Ask at very low f → I²R drop issue (voltage boost).

**Q21 (TSPSC-AEE023):** Multi-loop closed-loop control of DC/AC drives with speed and current feedback — correct statement?
(a) output of current control gives speed reference (b) speed loop is faster than current loop (c) both loops have equal bandwidth (d) current loop is faster than speed loop
**Ans: (d)** — Inner current loop must be faster than outer speed loop.
**Concept:** Cascaded (inner current / outer speed) control loops.
**Twist:** Ask outer loop output → it feeds the current reference. Ask which loop limits torque → current loop.

**Q22 (TSPSC-AEE023):** Quadrant-I motoring: T(motor) = 0.1N − 10 Nm, T(load) = 0.25N − 75 Nm. Steady-state speed?
(a) 666.3 rpm (b) 433.3 rpm (c) 0 rpm (d) 700 rpm
**Ans: (b)** — Tm = TL → 0.1N − 10 = 0.25N − 75 → N = 65/0.15 = 433.3 rpm.
**Concept:** Steady-state operating point at Tm = TL (N ∝ intersection of curves).
**Twist:** Change load slope/intercept → different speed. Ask stability → check (dTm/dN < dTL/dN).

**Q23 (TSPSC-AEE023):** 3-φ full-controlled converter (6 SCRs) feeding SEP DC motor, must also operate in quadrant III — suitable method?
(a) freewheeling diode across armature + α adjustment (b) adjust α only (c) adjust α followed by armature connection reversal (d) operate with α > π/2
**Ans: (c)** — Quadrant III needs both V and I negative → adjust α plus interchange armature terminals.
**Concept:** Full converter + armature reversal → four-quadrant operation (Q-III negative torque reverse rotation).
**Twist:** Quadrant II (reverse braking) → field reversal. Ask Q-IV → field reversal with rectifier.

**Q24 (TSPSC-AEE023):** Which armature voltage control method is used when the supply is DC?
(a) Static Ward–Leonard (b) Ward–Leonard (c) transformers with taps + uncontrolled rectifier bridge (d) chopper control
**Ans: (d)** — DC supply → chopper gives smooth armature voltage control.
**Concept:** Armature voltage control from DC bus → DC–DC chopper.
**Twist:** AC supply → Ward–Leonard (static or rotary). Ask efficiency of chopper → high (only one switch).

**Q25 (TSPSC-AEE023):** Slip power recovery scheme — operating speed relative to synchronous speed when power is injected into the rotor from an external source?
(a) speed reduces to zero (b) speed above synchronous (c) speed equal to synchronous (d) speed always below synchronous
**Ans: (b)** — External power injection into rotor → super-synchronous operation.
**Concept:** Rotor power injection → above synchronous speed; extraction → sub-synchronous.
**Twist:** Ask slip-energy recovery (Kramer/Scherbius) → sub-synchronous. Ask with rotor power fed back → above synchronous.

**Q26 (TSPSC-AEE-23):** Statements on stepper motor control — I) convert digital info to mechanical motion II) synchronous machines operated as stepping motors III) two types: VR and PM steppers.
(a) Only I and II (b) I, II and III (c) Only II and III (d) Only I and III
**Ans: (b)** — All three statements are correct.
**Concept:** Stepper motor types: variable reluctance, permanent magnet, hybrid; digital-to-motion conversion.
**Twist:** Ask missing third type → hybrid. Ask step angle formula → 360/(steps/rev) or rotor poles.

**Q27 (TSPSC-AEE023):** Which is a type of AC drive? I) Induction motor drives II) Synchronous motor drives
(a) Only II (b) Both I and II (c) Neither (d) Only I
**Ans: (b)** — Both induction and synchronous motor drives are AC drives.
**Concept:** AC drive classification: induction and synchronous motor drives.
**Twist:** Ask specific synchronous drive type → inverter-fed/cycloconverter-fed. Ask DC drive → separately excited/shunt.

**Q28 (TSPSC-AEE023):** Statements on AC drives — I) require advanced control of voltage, frequency and current II) synchronous motors are constant-speed and controllable by voltage/frequency/current.
(a) Only I (b) Only II (c) Both I and II (d) Neither I nor II
**Ans: (c)** — Both statements are correct.
**Concept:** AC drive control of V, f, I; synchronous motor speed control.
**Twist:** Ask what a VSI controls → voltage & frequency. Ask thyristor limitation → phase control only (slow switching).

> Total: 222 questions annotated.

---

# 📋 FORMULA SUMMARY — Exam-Day Sheet (All PE Units)

## 1. Power Semiconductor Devices
| Concept | Formula |
| :--- | :--- |
| di/dt protection | L = V/(di/dt) (series L) |
| dv/dt protection | dV/dt = V/(RC) · C = Ic/(dV/dt) (RC snubber) |
| Capacitive current | Ic = Cj·(dV/dt) |
| Power dissipation | PD = (TJ − TA)/θJA |
| Derating factor | DF = (V_actual − V_ideal)/V_actual ×100 |
| Latching vs holding | Latching > Holding |
| SCR turn-ON | forward bias **AND** gate pulse |
| RMS of a pulse train | Irms = Ip·√D |

## 2. Rectifiers (AC → DC)
| Converter | Vdc | Note |
| :--- | :--- | :--- |
| 1-Φ half-wave | (Vm/2π)(1+cosα) | |
| 1-Φ full (continuous/RL) | (2Vm/π)cosα | R load α>90° → (Vm/π)(1+cosα) |
| 1-Φ semi | (Vm/π)(1+cosα) | with freewheel diode |
| 3-Φ half-wave (3-pulse) | (3√3/2π)Vm·cosα | |
| 3-Φ full (6-pulse) | **(3√3/π)Vm·cosα** | Vm = peak **phase** voltage |
| 3-Φ semi | (3√3/2π)Vm(1+cosα) | |
| Source-inductance drop | ΔV = 3ωLs·Id/π (3-Φ) · 2ωLs·Id/π (1-Φ) | Vdc falls |
| PIV | bridge Vm · mid-point 2Vm · 3-Φ bridge √3Vm | |
| I_rms per SCR (3-Φ) | Io/√3 | each SCR conducts 120° |
| Ripple frequency | 1-Φ full = 2f · 3-Φ full = 6f | |
| Displacement PF | cosα | |

## 3. Choppers (DC → DC)
| Type | Vo | Note |
| :--- | :--- | :--- |
| Buck (step-down) | D·Vs | |
| Boost (step-up) | Vs/(1−D) | |
| Buck-boost | −D·Vs/(1−D) | inverts polarity |
| Ripple current | ΔIL = Vs·D/(f·L) | **max at D = 0.5** |
| Ripple voltage | ΔVC = Io·D/(f·C) | |
| Freq doubled | ripple ∝ 1/f → **halves** | |

## 4. Inverters (DC → AC)
| Concept | Formula |
| :--- | :--- |
| 1-Φ bridge fundamental (peak) | V1 = 4Vs/π |
| 1-Φ bridge fundamental (RMS) | V1rms = (2√2/π)Vs |
| 3-Φ 180° mode line peak | Vs |
| 3-Φ 120° mode line peak | √3Vs/2 |
| Harmonic elimination | kill nth harmonic → pulse width 2π/n |
| VSI vs CSI | VSI low-Z source · CSI high-Z source |

## 5. AC → AC
| Concept | Formula |
| :--- | :--- |
| AC voltage controller | Vo(rms) = Vs√[(π−α+sin2α/2)/π] |
| Cycloconverter | f_out < f_in (step-down only) |

## 6. Electric Drives
| Concept | Formula |
| :--- | :--- |
| Power | P = T·ω |
| Back EMF | Eb = Vt − Ia·Ra |
| Speed | N ∝ Eb/φ |
| V/f control | below base speed → constant torque · above → constant power |
| THD | THD = √(ΣIh²)/I1 |

## Device Quick Facts
- **Voltage-controlled:** MOSFET, IGBT · **Current-triggered:** SCR, GTO, Triac
- **Self-commutating (gate turn-off):** GTO, IGBT, MOSFET · **Line-commutated:** SCR
- **Bidirectional:** Triac (MT1/MT2) · **No gate:** Diode
