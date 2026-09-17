# Analog Electronics — PYQ Notes from Ohm Institute PDF

**Source:** Study_Material__GTD_PYQs_2026_05_26_5_Analog_Circuits_PD.pdf  
**Total Questions Analyzed:** ~425 across 4 units  
**Topics:** Diodes → BJT/JFET/MOSFET → Op-Amp → Oscillators & Multivibrators

---

## 📊 Formula/Concept vs. Question Count Analysis

| S.No | Formula / Concept | No. of Qs | Key Formula |
| :---: | :-------------------------------------------------------------- | :---: | :--- |
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

# 📝 FULL PYQ ANALYSIS — All 174 Analog Questions (Concept through PYQ)

> Source: Study_Material__GTD_PYQs_2026_05_26_5_Analog_Circuits_PD.pdf (OHM Institute)
> Every question: answer + options, the concept it teaches, and how the examiner twists it.

**Legend:** Q = question · Ans = correct option · Concept = new term/principle · Twist = examiner variation → new answer

## Unit 1: Diode Circuits & Applications (37 Qs)

**Q1 (EPDCL-10):** Ideal diode is characterized as
(a) infinite resistance (b) zero resistance (c) 10 MΩ (d) 1 kΩ
**Ans: (b)** — ideal diode ON is a short → zero resistance; note solution flags "insufficient data" because if OFF it is infinite resistance (a).
**Concept:** ideal diode: Vγ=0, Rf=0 when ON / Rr=∞ when OFF.
**Twist:** silicon diode → Vγ=0.7 V, cut-in ~0.7 V. Real diode → Rf small but nonzero.

**Q2 (EPDCL-10):** The knee voltage of silicon diode is
(a) 1.0 V (b) 0.7 V (c) 0.7 mV (d) 0.3 V
**Ans: (b)** — knee/cut-in voltage of Si ≈ 0.7 V.
**Concept:** knee voltage = cut-in voltage where forward current rises sharply.
**Twist:** germanium diode → ~0.3 V (d). GaAs → ~1.2 V.

**Q3 (AP Genco-12):** The diode used in a clipping circuit has Rf = 25 Ω and Rr = 1 MΩ. The external resistor R is
(a) 50 kΩ (b) 5 kΩ (c) 1/25 MΩ (d) 25 MΩ
**Ans: (b)** — R = √(Rf·Rr) = √(25 × 10⁶) = 5 kΩ.
**Concept:** clipper: external R = geometric mean of forward and reverse resistances (slope-matching, equal clipping levels).
**Twist:** Rf=100 Ω, Rr=100 kΩ → R = √10⁷ = 3.16 kΩ. If Rr ignored (infinite) → R → ∞, not recommended.

**Q4 (AP Genco-12):** The dynamic resistance of a p-n junction germanium diode at room temperature with current of 1 mA under forward biasing is
(a) 100 Ω (b) 12 mΩ (c) 13 Ω (d) 26 Ω
**Ans: (d)** — Rd = ηVT/ID = (1)(26 mV)/(1 mA) = 26 Ω.
**Concept:** dynamic resistance rd = ηVT/ID (Ge: η=1, VT=26 mV at 300 K).
**Twist:** silicon diode (η=2), ID=1 mA → rd = 52 Ω. Same Ge at ID=2 mA → 13 Ω (d).

**Q5 (APSPDCL-12):** The ripple voltage of a FWR with a 100 μF filter capacitor connected to a load of 50 mA is
(a) 2.4 V (b) 1.2 V (c) 4.4 V (d) 6.6 V
**Ans: (—)** — solution: data insufficient (time period T not given); Vr = Vm/(2fRC) = (Im·T)/(2C) needs T/f.
**Concept:** ripple of FWR + C-filter: Vr = Vm/(2fRC) = Im/(2fC); f=2fin.
**Twist:** if f=50 Hz (India), Im=50 mA, C=100 μF → Vr = 50m/(2×100×100μ)=2.5 V ≈ (a). If 100 Hz → 1.25 V ≈ (b).

**Q6 (HMWS-12):** A diode whose terminal characteristics are related as iD = IS(e^{V/VT}), is biased at ID = 2 mA. Its dynamic resistance is
(a) 25 Ω (b) 12.5 Ω (c) 50 Ω (d) 100 Ω
**Ans: (b)** — rD = ηVT/id = (1)(25 mV)/(2 mA) = 12.5 Ω (η=1 from exponent form).
**Concept:** rd = ηVT/ID; exponential law slope gives dV/dI = VT/ID (η=1).
**Twist:** Si with η=2, ID=2 mA → 25 Ω (a). ID=1 mA → 25 mV/1 mA = 25 Ω (Si η=2 → 50 Ω).

**Q7 (TRANSCO-AE-12):** Assume D1 and D2 in figure are ideal diodes. The value of current Is is (circuit: 1 mA DC source feeding parallel branches each 2 kΩ with D1, D2)
(a) 0 mA (b) 0.5 mA (c) 1 mA (d) 2 mA
**Ans: (a)** — current picks the low-resistance path; D1 ON, D2 OFF (reverse-biased), so Is = 0.
**Concept:** ideal diode as a switch / current chooses low-impedance path.
**Twist:** reverse D2 polarity → both ON path equal → Is = 0.5 mA (b). Remove D2 branch → Is = 1 mA (c).

**Q8 (TRANSCO-AE-12):** A voltage signal 10 sin ωt is applied to the circuit with ideal diodes (fig: ~Vi → 10 kΩ → node with D1 to +4 V, D2 to −4 V, 10 kΩ to output). The maximum and minimum values of the output waveform are respectively
(a) +10 V & –10 V (b) +4V & –4V (c) +7V & –4V (d) +4V & –7V
**Ans: (d)** — at Vin=+10 V: D1 OFF, D2 ON → V0=+4 V; at Vin=−10 V: D1 ON → V0 = −4 + 10k·(−6/20k) = −7 V.
**Concept:** clipper/clamper hybrid — diode clamps output to ±reference rails.
**Twist:** swap 4 V to 5 V refs → +5 V, −? V. Change to series resistor 20 kΩ → V0 min = −5.5 V.

**Q9 (EPDCL-14):** The cut-in voltage for silicon and germanium diodes respectively are
(a) 0.6 V, 0.2 V (b) 0.7 V, 0.3 V (c) 0.3 V, 0.7 V (d) 0.2 V, 0.6 V
**Ans: (b)** — Si ≈ 0.7 V, Ge ≈ 0.3 V (solution also accepts (a) 0.6/0.2).
**Concept:** cut-in (knee) voltage: Si 0.7 V, Ge 0.3 V.
**Twist:** GaAs → 1.2 V. Cut-in vs forward drop: Si forward ≈ 0.7 V, Ge ≈ 0.3 V.

**Q10 (APSPDCL-14):** Normally which of the following has a negative temperature coefficient?
(a) Platinum (b) Thermistors (c) Copper (d) Nickel
**Ans: (b)** — thermistors have NTC (resistance ↓ as temperature ↑).
**Concept:** NTC thermistor vs PTC metals (Pt, Cu, Ni).
**Twist:** copper/platinum (metals) → PTC (positive TC). For an ntc thermistor in series with a lamp, surge limiting.

**Q11 (ISRO-14):** The concentration of minority carriers in an extrinsic semiconductor under equilibrium is
(a) Directly proportional to the doping concentration (b) Inversely proportional to the doping concentration (c) Directly proportional to the intrinsic concentration (d) Inversely proportional to the intrinsic concentration
**Ans: (b)** — np = ni²/ND (N-type) and pn = ni²/NA (P-type) → ∝ 1/doping.
**Concept:** mass-action law np = ni²; minority carriers fall as doping rises.
**Twist:** doubling ND → minority concentration halves. Minority ∝ ni² so rises fast with temperature.

**Q12 (HMWS-15):** Device employing the Hall effect is used to measure _____.
(a) Magnetic flux (b) Magnetic flux density (c) Electric charge (d) Electric flux density
**Ans: (b)** — Hall voltage ∝ B; used to measure magnetic flux density (and carrier type).
**Concept:** Hall effect: VH = BI/(qnt) — measures B and identifies carrier type.
**Twist:** also used to find carrier concentration & mobility. Measure → P/N-type (see Q30).

**Q13 (SSC-JE-S1-14):** As compared to full-wave rectifier using two diodes, the four-diode bridge rectifier has the dominant advantage of:
(a) Higher current carrying capacity (b) Lower peak inverse voltage requirement (c) Lower ripple factor (d) Higher efficiency
**Ans: (b)** — PIV of bridge = Vm; PIV of two-diode FWR = 2Vm.
**Concept:** PIV of bridge rectifier = Vm; center-tap PIV = 2Vm.
**Twist:** 230 V rms, Vm=325 V → bridge PIV 325 V, CT PIV 650 V. Bridge needs transformer no tap (smaller, cheaper).

**Q14 (SSC-JE-S1-14):** Which semiconductor device behaves like two SCR's?
(a) MOSFET (b) JFET (c) UJT (d) Triac
**Ans: (d)** — Triac is an antiparallel combination of two SCRs.
**Concept:** triac = 2 SCRs anti-parallel → bidirectional AC switch.
**Twist:** DIAC = 2 diodes antiparallel (trigger device). Two SCRs separately → anti-parallel SCR module.

**Q15 (SSC-JE-S1-14):** The current in reverse biased P-N junction diode may be:
(a) few micro or nano amperes (b) few milli amperes (c) between 0.2 A and 2 A (d) between 2A and 5A
**Ans: (a)** — reverse current is due to minority carriers, µA/nA order.
**Concept:** reverse saturation current IS = minority-carrier drift current.
**Twist:** temperature ↑ → IS roughly doubles per 10 °C. At breakdown, reverse current becomes large.

**Q16 (SSC-JE-S2-14):** An AC supply of 230 V is applied to half-wave rectifier through transformer of turns ratio 10:1 (fig). Determine the peak inverse voltage across the diode.
(a) 37.6 V (b) 32.5 V (c) 23.0 V (d) 14.54 V
**Ans: (b)** — V2 = 230/10 = 23 V; PIV(HWR) = Vm = √2×23 = 32.5 V.
**Concept:** HWR PIV = Vm (peak secondary voltage).
**Twist:** FWR center-tap PIV = 2Vm = 65 V. Full bridge PIV = Vm = 32.5 V. Load added → PIV unchanged for ideal diode.

**Q17 (SSC-JE-S2-14):** The potential barrier existing across P-N junction
(a) Prevents flow of minority carriers (b) Prevents flow of majority carriers (c) Prevents total recombination of holes and electrons (d) Prevents neutralization of acceptor and donor ions
**Ans: (c)** — barrier stops the flow of majority carriers so total recombination is prevented.
**Concept:** built-in potential barrier opposes majority-carrier diffusion.
**Twist:** forward bias lowers barrier (majority flow); reverse bias raises it (minority drift).

**Q18 (SSC-JE-13):** In electronic circuits, for blocking the DC component of voltage signal, a/an _____ is connected in series with the voltage source.
(a) capacitor (b) diode (c) resistor (d) inductor
**Ans: (a)** — a series capacitor blocks DC (coupling capacitor).
**Concept:** capacitor blocks DC, passes AC; used as coupling/dc-blocking element.
**Twist:** inductor passes DC, blocks AC (choke). Resistor passes both, just attenuates.

**Q19 (SSC-JE-13):** For n-type semiconductor, the doping material is
(a) tetravalent (b) pentavalent (c) trivalent (d) bivalent
**Ans: (b)** — n-type doping uses pentavalent donors (P, As, Sb).
**Concept:** donor (pentavalent) → n-type; acceptor (trivalent) → p-type.
**Twist:** trivalent → p-type. Si/Ga(Ge) are tetravalent host atoms.

**Q20 (SSC-JE-13):** In a semiconductor, the resistivity
(a) depends on temperature (b) depends on voltage (c) depends on current through it (d) none of the above
**Ans: (a)** — semiconductor is NTC, so resistivity depends on temperature.
**Concept:** semiconductor resistivity ↓ with temperature (NTC); metals ↑ (PTC).
**Twist:** metals (Cu) resistivity ↑ with T. Doping ↑ → resistivity ↓ at fixed T.

**Q21 (SSC-JE-12):** In the figure, D is an ideal diode. If the rms value of the input voltage is 50 V, then the rms current through 100 Ω is (fig: ~Vi, series D, 100 Ω)
(a) 0.25 A (b) 0.5 A (c) 0.5√2 A (d) 0.5/√2 A
**Ans: (d)** — Vm = 50√2; Irms = Vm/(2R) = 50√2/(2×100) = 0.5/√2 A.
**Concept:** HWR Irms = Im/2 = Vm/(2R); Im = Vm/R.
**Twist:** FWR → Irms = Vm/(√2 R) = 0.5 A (b). Si diode drop 0.7 V → subtract from Vm.

**Q22 (SSC-JE-12):** Which of the following material is a semiconductor?
(a) Selenium (b) Bismuth (c) Silica (d) Chromium
**Ans: (c)** — Silica (silicon compound) selected as semiconductor (per key; note Selenium is also a semiconductor — examiner trap).
**Concept:** group IV elemental semiconductors (Si, Ge).
**Twist:** Silicon & Germanium are true semiconductors; Silica (SiO2) is an insulator, Selenium is a photoconductor.

**Q23 ({—}):** The output frequencies of bridge rectifier and half wave rectifier respectively are (fin is input frequency)
(a) 2fin and fin (b) 2fin and 2fin (c) fin and 2fin (d) fin and fin/2
**Ans: (a)** — bridge (FWR) output ripple = 2fin; HWR = fin.
**Concept:** FWR ripple frequency = 2fin; HWR = fin.
**Twist:** three-phase bridge → 6fin. With C filter, ripple freq still 2fin but amplitude smaller.

**Q24 (TSSPDCL-18):** Assuming the diodes in the circuit to be ideal, i and V in the circuit are respectively (fig: 9 V via 10 kΩ, node A; 5 V via 10 kΩ, node B; diode between; V across)
(a) 0 A, 2 V (b) 0.2 mA, 0 V (c) 0 A, –2 V (d) 0.2 mA, 2 V
**Ans: (c)** — VA=2.5 V, VB=4.5 V, VAB=−2 V → diode reverse biased → i=0 A, V=−2 V.
**Concept:** ideal diode OFF when anode < cathode (reverse); node-voltage division.
**Twist:** raise 5 V to 7 V → VA=3.5 V > 4.5? no → still OFF. Raise 9 V to 3 V → diode ON, i≈0.2 mA.

**Q25 (TSSPDCL-18):** The diode circuit shown has R = 30 kΩ, VDD = 10 V, VS = 5V and diode drop VD = 0.7 V. Then V0 will be (fig: +VDD→R→node with D3,D4 to VS; D1,D2 series to ground giving V0)
(a) 2.1 V (b) 2.9 V (c) 3.6 V (d) 6.4 V
**Ans: (a)** — three forward-biased diode drops: V0 = 3 × 0.7 = 2.1 V.
**Concept:** series diode stack clamps voltage to n×VD.
**Twist:** 2 diodes → 1.4 V. Si 0.7 each, Ge 0.3 each → 0.9 V. Reverse a diode → it blocks, V0 = VS.

**Q26 (TSTransco-18):** The input voltage to a full wave bridge rectifier is v(t) = 200 sin(ωt) V. The peak inverse voltage of the diodes is
(a) 200 V (b) √2 × 200 V (c) √2 × 100 V (d) 400 V
**Ans: (a)** — PIV of bridge rectifier = Vm = 200 V.
**Concept:** bridge PIV = Vm; center-tap PIV = 2Vm.
**Twist:** center-tap with same Vm → 400 V (d). HWR → 200 V too.

**Q27 (TSTransco-18):** As the temperature is increased, the voltage across a semiconductor diode carrying a constant current
(a) increases (b) decreases (c) remains constant (d) may increase or decrease depending upon the doping levels in the junction.
**Ans: (b)** — resistance falls with T; at constant current, voltage drop decreases (~−2 mV/°C).
**Concept:** diode forward drop has NTC ≈ −2.5 mV/°C at constant current.
**Twist:** with constant voltage instead → current increases. IS doubles per 10 °C → V shifts.

**Q28 (APEPDCL-19):** A Ge transistor has ICO = 0.01 mA at 25°C. If βdc remains unchanged, the leakage current at 100°C is _____.
(a) 8.1 mA (b) 1.81 mA (c) 0.81 mA (d) 18.1 mA
**Ans: (b)** — ICO doubles per 10 °C: 0.01 × 2^7.5 = 0.01 × 181 = 1.81 mA.
**Concept:** leakage current doubles every 10 °C (rule of thumb).
**Twist:** 25→125 °C (Δ=100 °C) → 0.01 × 2¹⁰ = 10.24 mA. Si has much lower ICO than Ge.

**Q29 (APSPDCL-19):** Dynamic resistance of a germanium PN junction diode at a forward current of 2 mA is
(a) 26 Ω (b) 52 Ω (c) 6.5 Ω (d) 13 Ω
**Ans: (d)** — Rd = VT/ID = 26 mV/2 mA = 13 Ω (Ge, η=1).
**Concept:** rd = ηVT/ID; Ge η=1, Si η=2.
**Twist:** Si (η=2) at 2 mA → 26 Ω (a). Ge at 1 mA → 26 Ω (a).

**Q30 ({—}):** Which of the following statements are correct?
(A) In semiconductors diffusion current is independent of any applied electric field
(B) Hall effect is used to determine whether a semiconductor is P-type or N-type
(C) In a forward biased P-N junction diode, the current enters as hole current and leaves as electron current
(D) The barrier capacitance of PN junction diode is constant and independent of the reverse bias voltage
(a) C, D and A (b) A, B and D (c) A, B and C (d) B, C and D
**Ans: (c)** — A, B, C true; D false (barrier/junction capacitance ∝ 1/√Vreverse).
**Concept:** diffusion current (concentration gradient) independent of E-field; junction capacitance varies with reverse bias.
**Twist:** barrier (depletion) capacitance ↓ as reverse bias ↑. Diffusion capacitance large in forward bias.

**Q31 (TSSPDCL-2022):** The 6 V Zener Diode shown has zero resistance and knee current of 5 mA. Then what is the minimum value of resistance R, so that the voltage across the diode does not fall below 6 V (fig: 8.5 V → 100 Ω → zener 6 V → R)
(a) 1000 ohm (b) 600 ohm (c) 450 ohm (d) 300 ohm
**Ans: (d)** — Is = (8.5−6)/100 = 25 mA; I = Is − Iz = 25−5 = 20 mA; R = 6/20 mA = 300 Ω.
**Concept:** zener regulator: current balance Is = Iz + IL; Vz holds load voltage constant.
**Twist:** Iz(min)=0 (ideal zener) → R = 6/25 = 240 Ω. Change source to 12 V → Is = 60 mA → R = 6/55 ≈ 109 Ω.

**Q32 (TSNPDCL-22):** A device having characteristics very similar to an ideal voltage source is
(a) GTO (b) Zener diode (c) IGBT (d) FET
**Ans: (b)** — zener maintains near-constant V across it (regulator → acts like voltage source).
**Concept:** zener breakdown region: V constant regardless of current → voltage-source-like.
**Twist:** ideal current source → BJT in active region (constant IC). Zener with series R = practical voltage source.

**Q33 (TSNPDCL-22):** Refer to the circuit diagram and assume that the diodes are ideal. Determine the impedance offered by the circuit across the terminals A and B (fig: A→D1→10 kΩ→B; A→D2→10 kΩ→B; V=4 sin ωt)
(a) 5kΩ (b) 20 kΩ (c) 10 kΩ (d) 0.2 kΩ
**Ans: (c)** — at any instant only D1 or D2 conducts, so impedance = single 10 kΩ path.
**Concept:** antiparallel ideal diodes → only one conducting per half-cycle → Z = R.
**Twist:** remove the two 10 kΩ resistors → impedance = 0 (short in each half). Series both diodes same polarity → both OFF → infinite.

**Q34 (TSSPDCL-AE-2023):** Identify the correct statements from the following.
i. Clamper circuit is also called as d.c. restorer.
ii. The positive clamping circuit shifts the original signal in a vertical downward direction.
iii. The clamping circuit changes the r.m.s. value of the waveform.
iv. The clamping circuit changes the average value of the waveform.
(a) i and ii (b) ii and iii (c) iii and iv (d) iv and i
**Ans: (d)** — i true (dc restorer) and iv true (clamping shifts dc level/average); ii wrong (positive clamp shifts upward); iii wrong (RMS unchanged).
**Concept:** clamper shifts dc level (average) without changing RMS/shape; positive clamp pushes signal up.
**Twist:** negative clamp shifts downward. Clamper vs clipper: clipper removes peaks, clamper only shifts level.

**Q35 (TSPSC-AEE-23):** A diode circuit with an LC load is shown with the capacitor having an initial voltage; VC(t=0) = −Vco = Vo = 300 V, C = 30 μF and L = 120 μH. If switch S1 is closed at t = 0, determine the peak current through the diode (fig: S1, D1, L, C in series loop)
(a) 100 A (b) 150 A (c) 300 A (d) 50 A
**Ans: (b)** — im = Vco × √(C/L) = 300 × √(30/120) = 300 × 0.5 = 150 A.
**Concept:** LC resonant discharge: i(t) = Vco√(C/L)·sin(ω₀t); peak at √(C/L).
**Twist:** C=120 μF, L=30 μH → √4 = 2 → 600 A. Double Vco → 300 A (c). It is like an impulse commutator / snubber resonance.

**Q36 (TSPSC-AEE-23):** What is the correct logical order of a semi-conductor material according to its knee voltage (increasing order)? I. GaAs  II. Ge  III. Si
(a) I, II, III (b) II, I, III (c) II, III, I (d) III, I, II
**Ans: (c)** — knee: Ge (0.3 V) < Si (0.7 V) < GaAs (1.2 V).
**Concept:** bandgap order: Ge 0.66 eV < Si 1.1 eV < GaAs 1.42 eV → knee voltage rises with bandgap.
**Twist:** for forward drop with current, same order holds. Germanium highest leakage, GaAs lowest.

**Q37 (TSPGCL-24):** Find the current iD flowing through the diode and voltage VAB in the circuit shown. Assume diode is ideal (fig: 10 V via 4 Ω to node A; iD; A→4 Ω→B; B: 1 Ω to 2 A source to ground)
(a) 0 A, 5 V (b) 1 A, 5 V (c) 1 A, 3 V (d) 3 A, 5 V
**Ans: (c)** — source transform: 10 V/4 Ω → 2.5 A ∥ 4 Ω; combine with 2 A source → 3 A in (4∥4)∥... → I=3/3=1 A; VAB = 1×1 + 2 = 3 V.
**Concept:** source transformation + superposition/parallel current combination; ideal diode short.
**Twist:** 2 A source removed → I = 10/8 = 1.25 A, VAB = 2.5 V. Reverse diode → iD=0, VAB = voltage divider.

## Unit 2: BJT, JFET & MOSFET (59 Qs)

Source: /tmp/analog_full.txt (lines 223-588 questions; solutions 1441-1825).
Answers follow the OHM solutions key; numbers restart per unit so matching is by topic/content.

---

**Q1 (EPDCL-10):** Voltage gain of BJT amplifier is
(a) AI·RL (b) AI·(RL/RI) (c) AI·(RI/RL) (d) AI·RI
**Ans: (b)** — Av = V0/Vi = (I0·RL)/(Ii·RI) = AI·(RL/RI).
**Concept:** Av = AI·(RL/RI) (BJT amplifier gain in terms of current gain).
**Twist:** RL = RI → Av = AI. If AI = 50, RL/RI = 2 → Av = 100.

**Q2 (EPDCL-10):** JFET is
(a) voltage controlled device (b) current controlled device (c) resistance controlled device (d) conductance controlled device
**Ans: (a)** — FET/JFET output current is controlled by gate-source voltage; BJT is current controlled.
**Concept:** FET = voltage-controlled device (VGS controls ID).
**Twist:** BJT is current-controlled; op-amp also voltage-controlled.

**Q3 (APGenco-12):** Thermal runaway is not possible in FET because as temperature of FET increases
(a) Mobility increases (b) Mobility decreases (c) Drain current decreases (d) Transconductance increases
**Ans: (b)** — as temperature rises, carrier mobility falls → drain current reduces → self-limiting, no thermal runaway.
**Concept:** FET negative temperature coefficient prevents thermal runaway.
**Twist:** In BJT, leakage ICBO doubles every ~10°C → thermal runaway unless stabilized by emitter resistance. In MOSFET, ID falls with temperature → self-protecting.

**Q4 (APSPDCL-12):** For the BJT in figure (VCC=+20V, RB=430kΩ, RC=2kΩ, RE=1kΩ), VBE=0.7V, β=100, find IB.
(a) 36.35 µA (b) 19.3 mA (c) 38.6 mA (d) 57 µA
**Ans: (a)** — KVL: 20 = IB·430k + 0.7 + IE·1k = IB(430k + (β+1)1k) → IB = 19.3/531k = 36.35 µA.
**Concept:** DC biasing with emitter resistor — IB = (VCC−VBE)/(RB + (β+1)RE).
**Twist:** RE removed → IB = 19.3/430k = 44.9 µA. VCC doubled → IB ≈ 73 µA.

**Q5 (APSPDCL-12):** Transconductance at bias voltage of 0 V for the JFET with IDSS = 9 mA and VP = −3 V is
(a) 6 mV (b) 6 mS (c) 27 S (d) 3 mS
**Ans: (b)** — gm0 = 2·IDSS/|VP| = 2×9/3 = 6 mS.
**Concept:** gm0 = 2·IDSS/|VP| (max transconductance at VGS = 0).
**Twist:** At VGS = −1.5 V → gm = gm0(1−VGS/VP) = 6×(1−1.5/3) = 3 mS. If IDSS = 4 mA, VP = −2 V → gm0 = 4 mS.

**Q6 (HMWS-12):** The pinch-off voltage of a JFET is 5.0 V. Its cut-off voltage is
(a) (5.0)² V (b) 2.5 V (c) 5.0 V (d) (0.5)³/² V
**Ans: (c)** — pinch-off voltage ≡ cut-off voltage (same magnitude).
**Concept:** JFET: VP (pinch-off) = VGS(off) (cut-off), equal magnitude.
**Twist:** VGS(off) = −4 V → pinch-off = 4 V. At VGS = 0, ID = IDSS.

**Q7 (HMWS-12):** In an RC coupled common emitter amplifier, which of the following is true?
(a) coupling capacitor affects HF response and bypass capacitor affects LF response (b) both coupling and bypass capacitors affect LF response only (c) both affect HF response only (d) coupling affects LF and bypass affects HF
**Ans: (b)** — coupling and bypass capacitors limit the LOW-frequency response; parasitic/junction capacitances limit HF.
**Concept:** RC coupling frequency response — f_L set by coupling/bypass caps, f_H by transistor capacitance.
**Twist:** Larger coupling capacitor → lower f_L. HF limit set by Miller capacitance of CE stage (Cµ·(1+Av)).

**Q8 (HMWS-12):** The current gain of a bipolar transistor drops at high frequencies because of
(a) transistor capacitances (b) high current effects in the base (c) parasitic inductive elements (d) early effect
**Ans: (a)** — internal/transistor capacitances (Cπ, Cµ) roll off current gain at high frequency.
**Concept:** fβ / fT gain-bandwidth — transistor capacitances limit HF current gain.
**Twist:** fT = β0·fβ. Above fβ gain falls at 20 dB/decade. Typical BJT fT ~ 100-300 MHz.

**Q9 (TRANSCO-AE-12):** Assume n-channel MOSFET in figure is ideal and its threshold voltage is 1 V; the voltage Vab between nodes a and b is (VGS=2V, drain via 2kΩ from a, 10 V source, gate 2 V, source 0 V).
(a) 5 V (b) 2 V (c) 1 V (d) 0 V
**Ans: (d)** — VGS = 2 V > Vth = 1 V; VDS > VDS(sat) → saturation, MOSFET acts as short, so Vab = 0 V.
**Concept:** MOSFET as switch — saturation = low-resistance ON state (Vab ≈ 0).
**Twist:** VGS = 0.5 V < Vth → cut-off, MOSFET OFF → Vab = divider output (≠ 0). If Vth = 3 V, device cut-off → Vab non-zero.

**Q10 (EPDCL-14):** In a FET
(a) rd = µ×gm (b) rd = gm/µ (c) µ = rd×gm (d) µ = rd/gm
**Ans: (c)** — amplification factor µ = gm·rd.
**Concept:** FET parameter relation µ = gm·rd.
**Twist:** gm = 5 mS, rd = 100 kΩ → µ = 500. CS gain = −gm(rd||RD) ≤ µ.

**Q11 (EPDCL-14):** Which transistor amplifier configuration is called emitter follower?
(a) CB (b) CE (c) CC (d) Cascode
**Ans: (c)** — common collector is the emitter follower.
**Concept:** CC/emitter follower — Av ≈ 1, high Zi, low Zo.
**Twist:** MOSFET analog = common-drain source follower. CC = voltage buffer (Q35).

**Q12 (APSPDCL-14):** Find differential-mode gain of amplifier in figure (hie = 2.8 kΩ, hfe = 100; diff pair with 4.7 kΩ collectors, 100 Ω emitter resistors, 6.8 kΩ tail, ±15 V).
(a) 162 (b) 254 (c) 197 (d) 210
**Ans: (a)** — Ad ≈ hfe·RC/hie = 100×4.7/2.8 ≈ 167.8 ≈ 162 (nearest option).
**Concept:** Differential amplifier — Ad = hfe·RC/hie (no degeneration ideal).
**Twist:** Emitter degeneration 100 Ω reduces Ad. Common-mode gain → CMRR = Ad/Ac; tail current source makes Ac → 0, CMRR very high.

**Q13 (HMWS-15):** On the drain characteristic curve of a JFET for VGS = 0, the pinch-off voltage is
(a) above the breakdown region (b) between the ohmic area and the constant-current area (c) between constant-current and breakdown region (d) below the ohmic area
**Ans: (b)** — pinch-off point sits between ohmic (triode) and constant-current (saturation) regions.
**Concept:** JFET drain characteristics — ohmic / constant-current / breakdown regions.
**Twist:** Analogous MOSFET edge of saturation: VDS = VGS − Vth. More negative VGS → pinch-off at lower VDS.

**Q14 (HMWS-15):** In a BJT, when both junctions are forward biased then the operating mode is
(a) reverse active (b) forward active (c) saturation (d) cut-off
**Ans: (c)** — both junctions F.B. = saturation.
**Concept:** BJT mode table — F.B./R.B. = active; F.B./F.B. = saturation; R.B./F.B. = inverse active; R.B./R.B. = cut-off.
**Twist:** E-B R.B., B-C F.B. → inverse active. Both R.B. → cut-off. In saturation VCE(sat) ≈ 0.2 V.

**Q15 (TGenco-15):** Two identical FETs, each with gm and rd, are connected in parallel. The composite FET has
(a) gm/2 and 2rd (b) gm/2 and rd/2 (c) 2gm and rd/2 (d) 2gm and 2rd
**Ans: (c)** — current sources add (2gm); rd's in parallel (rd/2).
**Concept:** Parallel FETs — gm doubles, rd halves.
**Twist:** FETs in series → gm halves, rd doubles. Parallel BJTs double effective gm.

**Q16 (TSTransco-15):** For the n-channel MOSFET and its transfer curve in figure (Vth = 1 V, VG = 3 V, VS = 1 V), the threshold voltage is
(a) 1 V and device in active region (b) −1 V and device in saturation (c) 1 V and device in saturation region (d) −1 V and device in active region
**Ans: (c)** — Vth = 1 V (n-channel, +ve); VGS = 2 V > Vth and VDS ≥ VGS − Vth → saturation. (Solution key lists (a),(c); content supports (c).)
**Concept:** n-MOSFET threshold voltage + region check (VDS ≥ VGS − Vth → saturation).
**Twist:** If Vth = 2 V and VGS = 1.5 V → cut-off, ID ≈ 0. If VDS < VGS − Vth → triode/ohmic region.

**Q17 (TSTransco-15):** The voltage gain of a common-source JFET amplifier depends on its
(a) input impedance (b) amplification factor (c) dynamic drain resistance (d) drain load resistance
**Ans: (c), (d)** — Av = −gm(rd || RD), depends on dynamic drain resistance and drain load.
**Concept:** Av = −gm(rd || RD) (CS FET amplifier).
**Twist:** RD ≪ rd → Av ≈ −gm·RD. CD (source follower): Av = gm·RD/(1+gm·RD) < 1.

**Q18 (TSSPDCL-15):** Calculate collector current of a silicon BJT when dc current gain = 100, base current = 20 µA and reverse saturation current of CB junction = 500 nA.
(a) 2.051 mA (b) 2 mA (c) 1.949 mA (d) 0.051 mA
**Ans: (a)** — IC = β·IB + (1+β)·ICBO = 100×20µ + 101×0.5µ = 2.051 mA.
**Concept:** IC = βIB + (1+β)ICBO (leakage-inclusive collector current).
**Twist:** ICBO = 0 → IC = 2 mA. ICBO doubled → IC ≈ 2.101 mA.

**Q19 (TSNPDCL-15):** In the circuit in figure, if β = 30 and input voltage Vi = +5 V, the transistor would be operating in (+12 V, 2 kΩ collector, 20 kΩ from Vi, 100 kΩ to −10 V)
(a) cut-off (b) breakdown (c) active (d) saturation
**Ans: (c)** — assume active: KCL @ VB → IB = 0.108 mA, IC = 3.24 mA, VC = 5.52 V > VB = 0.7 V → forward active (verified).
**Concept:** Region verification — VC > VB > VE ⇒ active.
**Twist:** Vi raised to 7 V → VC drops toward VB → saturation. Vi < 0.7 V → cut-off.

**Q20 (SSC-JE-S1-14):** A BJT is said to be operating in the saturation region if
(a) both junctions are reverse biased (b) E-B junction reverse and B-C forward (c) E-B forward and B-C reverse (d) both junctions are forward biased
**Ans: (d)** — saturation = both junctions forward biased.
**Concept:** BJT saturation — both junctions F.B.
**Twist:** E-B F.B., B-C R.B. → forward active. Both R.B. → cut-off.

**Q21 (SSC-JE-S1-14):** The Ebers-Moll model is applicable to
(a) BJT (b) NMOS transistor (c) UJT (d) JFET
**Ans: (a)** — Ebers-Moll large-signal model is for the BJT.
**Concept:** Ebers-Moll transport model (BJT).
**Twist:** MOSFET large-signal model uses square-law / SPICE level-1. Early effect models BJT base-width modulation.

**Q22 (SSC-JE-S2-14):** In a CE transistor, VCC = 12 V and zero-signal collector current is 1 mA. Determine the operating point when collector load RC = 6 kΩ.
(a) 6 V, 1 mA (b) 6 V, 2 mA (c) 12 V, 1 mA (d) 12 V, 2 mA
**Ans: (a)** — VCE = VCC − IC·RC = 12 − 1m×6k = 6 V; IC = 1 mA → Q(6 V, 1 mA).
**Concept:** Q-point: VCE = VCC − IC·RC; DC load line.
**Twist:** RC = 4 kΩ, IC = 1 mA → VCE = 8 V. Load-line endpoints: IC(sat) = VCC/RC, VCE(off) = VCC.

**Q23 (SSC-JE-13):** The switching transistor in figure carries in the collector an rms current of 8 mA. If the frequency of the rectangular pulse train Vi is 50 Hz, the on-time of the transistor is (VCC=10 V, 500 Ω, VCE = 5 V)
(a) 20 ms (b) 6.4 ms (c) 12.8 ms (d) 16 ms
**Ans: (—)** — source key: "Insufficient data". Standard calc: Ipk = (10−5)/500 = 10 mA, D = (8/10)² = 0.64, t_on = 0.64×20 ms = 12.8 ms → (c).
**Concept:** RMS of rectangular pulse: Irms = Ipk·√D.
**Twist:** If Ipk = 8 mA at D = 0.25 → t_on = 5 ms. Frequency 100 Hz → T = 10 ms, t_on halves.

**Q24 (SSC-JE-13):** If the transistor with VCE = 5 V, VBE = 0.7 V has β = 45, the value of R is (24 V, R to base, 8 kΩ collector, 230 Ω emitter)
(a) 85.64 kΩ (b) 63.14 kΩ (c) 72.15 kΩ (d) 91.18 kΩ
**Ans: (a)** — VCB = VCE − VBE = 4.3 V; IE = 2.35 mA; R = VCB(β+1)/IE = 4.3×46/2.358m ≈ 83.88 kΩ ≈ 85.64 kΩ.
**Concept:** Emitter-bias design — R = (VCB)(β+1)/IE.
**Twist:** VCE = 8 V → VCB = 7.3 V → larger R. Emitter resistor removed → R = (VCC−VBE)/IB.

**Q25 (SSC-JE-13):** The input resistance of a FET is of the order of
(a) 100 Ω (b) 10 kΩ (c) 1 MΩ (d) 100 MΩ
**Ans: (d)** — FET input resistance ≈ 100 MΩ (reverse-biased gate junction).
**Concept:** FET input impedance — very high (MΩ range).
**Twist:** MOSFET gate input resistance ~10¹⁴ Ω (insulated gate). BJT input ~ kΩ (forward-biased base).

**Q26 (SSC-JE-12):** FETs are
(a) none of these (b) unipolar devices (c) bipolar devices (d) either unipolar or bipolar
**Ans: (b)** — conduction by majority carriers only → unipolar.
**Concept:** Unipolar devices (FET/MOSFET) vs bipolar (BJT).
**Twist:** BJT is bipolar (both electrons and holes). MOSFET is unipolar.

**Q27 (SSC-JE-11):** A transistor operating in common emitter mode in the figure (+20 V, 5 kΩ, 310 kΩ to +10 V, VBE = 0.6 V, β = 125). The voltage VCE is
(a) 10.5 V (b) 1.5 V (c) 1.05 V (d) 0.5 V
**Ans: (c)** — IB = (10−0.6)/310k = 0.03 mA, IC = 3.8 mA, VCE = 20 − 5k×3.8m = 1.05 V.
**Concept:** Q-point computation — VCE = VCC − IC·RC.
**Twist:** VCC = 10 V → VCE = 10 − 19 = −9 V (impossible) → saturation. RC = 2 kΩ → VCE = 12.4 V.

**Q28 (SSC-JE-10):** A FET is essentially a
(a) current driven device (b) voltage driven device (c) power drive source (d) solar device
**Ans: (b)** — output current controlled by gate-source voltage → voltage driven.
**Concept:** FET = voltage-driven device (ID depends on VGS, VDS).
**Twist:** BJT = current-driven. At high frequency MOSFET gate needs drive current (charge).

**Q29 (SSC-JE-10):** An oscillator uses
(a) positive feedback (b) negative feedback (c) both positive and negative feedback (d) no feedback
**Ans: (a)** — oscillators use positive feedback.
**Concept:** Barkhausen criterion — Aβ = 1, ∠Aβ = 0° (positive feedback).
**Twist:** Amplifiers use negative feedback for stability; oscillation start requires Aβ > 1.

**Q30 (SSC-JE-10):** For active region operation of an NPN transistor
(a) emitter is positive with respect to base (b) emitter is −ve with respect to base (c) emitter at same voltage as base (d) base at same voltage as collector
**Ans: (b)** — active NPN: base is positive w.r.t emitter → emitter negative w.r.t base (VB > VE, VC > VB).
**Concept:** NPN active — E-B F.B. (VB > VE), B-C R.B. (VC > VB).
**Twist:** PNP active — emitter positive w.r.t base. If VB > VC → saturation.

**Q31 (APTransco-17):** Which diode exhibits negative resistance characteristic?
(a) LED (b) Zener (c) Tunnel diode (d) PN diode
**Ans: (c)** — tunnel diode has a negative resistance region.
**Concept:** Tunnel diode — NDR region in forward characteristic.
**Twist:** Tunnel diode used in high-speed oscillators. UJT also shows negative resistance (voltage).

**Q32 (APGenco-17):** The cascade amplifier is a multistage configuration of
(a) CE-CC (b) CE-CB (c) CC-CB (d) CB-CC
**Ans: (a)** — cascade = CE + CC; cascode = CE + CB.
**Concept:** Cascade (CE-CC) vs Cascode (CE-CB).
**Twist:** Cascode (CE-CB) → higher bandwidth, reduced Miller effect (Q45). Darlington = CC-CC.

**Q33 (APGenco-17):** While biasing a JFET, if drain and source are interchanged, then
(a) device will work normally (b) device will get damaged (c) device will work, but drain current value will be affected (d) device will not operate at all
**Ans: (a)** — JFET is symmetric; D and S are interchangeable (key also lists (c) for practical devices). Not damaged.
**Concept:** JFET symmetry — drain/source interchangeable.
**Twist:** Practical JFETs may have slight asymmetry → small change in ID (option c). MOSFET body-diode prevents D/S interchange (damage).

**Q34 (TSSPDCL-18):** The rise time tr in a BJT is the time during which collector current rises from
(a) 0.1 ICS to 0.8 ICS (b) 0.2 ICS to 0.9 ICS (c) 0.1 ICS to ICS (d) 0.1 ICS to 0.9 ICS
**Ans: (d)** — rise time = 10% to 90% of saturated ICS.
**Concept:** Rise time tr (10–90%) of BJT switching.
**Twist:** Fall time tf also 10–90%. tr ≈ 0.35/BW. Total turn-on = t_d + t_r.

**Q35 (TSTransco-18):** BJT amplifier configuration which acts as buffer is
(a) common emitter (b) common base (c) common collector (d) cascade amplifier
**Ans: (c)** — CC has Av ≈ 1, high Zi, low Zo → buffer.
**Concept:** CC / emitter follower = voltage buffer (impedance matching).
**Twist:** CB = current buffer (Ai ≈ 1). MOSFET CD (source follower) = voltage buffer.

**Q36 (APEPDCL-19):** The condition that must be satisfied in a tuned collector oscillator for oscillations to build up and sustain is
(a) hfe/hie ≤ (RC + hoe·L)/M (b) hfe/hie > (RC + hoe·L)/M (c) hfe = (RC + hoe·L)/M (d) hfe = M/(RC + hoe·L)
**Ans: (b)** — practically hfe/hie > (RC + hoe·L)/M for startup; equality sustains.
**Concept:** Tuned-collector oscillator — loop gain > 1 to start, Aβ = 1 to sustain.
**Twist:** At sustain exactly Aβ = 1 (equality). Larger mutual inductance M → easier to sustain.

**Q37 (APEPDCL-19):** The gate-to-source voltage VGS applied to a FET is −3 V, IDSS = 10 mA and VP = −6 V. Then its drain current is
(a) 6 mA (b) 2.5 mA (c) 5 mA (d) 4 mA
**Ans: (b)** — ID = IDSS(1−VGS/VP)² = 10(1−3/6)² = 2.5 mA.
**Concept:** Shockley equation ID = IDSS(1−VGS/VP)².
**Twist:** VGS = 0 → ID = IDSS = 10 mA. VGS = VP = −6 V → ID = 0 (cut-off). VP = −4 V, VGS = −3 V → ID = 10(1−0.75)² = 0.625 mA.

**Q38 (APEPDCL-19):** The current gain of a CB amplifier is approximately
(a) 1 + hfe (b) hfe (c) ∞ (d) 1
**Ans: (d)** — CB current gain α ≈ 1 (slightly less than 1).
**Concept:** CB current gain Ai ≈ α ≈ 1.
**Twist:** CE gain = β (large). CC gain = 1 + β. β = α/(1−α).

**Q39 (APEPDCL-19):** As RL → ∞, the magnitude of the gain of the CS amplifier approaches
(a) ∞ (b) unity (c) 0 (d) µ
**Ans: (d)** — A = −gm(RL || rd); as RL → ∞ → |A| → gm·rd = µ.
**Concept:** CS gain bound — Av(max) = µ (amplification factor).
**Twist:** RL = rd → |A| = gm·rd/2 = µ/2. For CE, Av = −hfe·RL/hie grows with RL but is limited by output resistance.

**Q40 (APSPDCL-19):** In a FET, drain current changes from 8.0 mA to 7.5 mA when VGS changes from 0 to −0.25 V at constant VDS. The transconductance will be
(a) 6 mS (b) 4 mS (c) 1 mS (d) 2 mS
**Ans: (d)** — gm = ΔID/ΔVGS = (8−7.5)mA / 0.25 V = 2 mS.
**Concept:** gm = ΔID/ΔVGS.
**Twist:** ΔID = 0.5 mA over 0.5 V → gm = 1 mS. ΔID = 1 mA over 0.5 V → gm = 2 mS.

**Q41 (HMWS-20):** The value of IE (emitter current) for a transistor with αdc = 0.97, ICBO = 10 µA and IB = 50 µA is
(a) 3 mA (b) 15 mA (c) 2.5 mA (d) 2 mA
**Ans: (d)** — β = 0.97/0.03 = 32.33; IE = (1+β)IB + (1+β)ICBO = 33.33×(50+10)µ = 2 mA.
**Concept:** IE = (1+β)IB + (1+β)ICBO.
**Twist:** ICBO = 0 → IE = 33.33×50µ = 1.67 mA. IB = 100 µA → IE ≈ 3.33 mA.

**Q42 (HMWS-20):** Identify the expression for ID (drain current) in a JFET: IDSS = saturation drain current with gate shorted to source, VGS = gate-source voltage, VP = pinch-off voltage
(a) IDSS(1−VGS/VP) (b) IDSS(1−VGS/VP)² (c) IDSS(1+VGS/VP) (d) IDSS(1+VGS/VP)²
**Ans: (b)** — Shockley equation ID = IDSS(1−VGS/VP)².
**Concept:** Shockley square-law equation (JFET).
**Twist:** Slightly forward VGS (positive) raises ID, but gate must stay reverse-biased (IG ≈ 0). At VGS = VP, ID = 0.

**Q43 (HMWS-20):** The stability factor (S) of a fixed bias circuit of a transistor of β = 4 is
(a) 5 (b) 1/5 (c) 3 (d) 1/3
**Ans: (a)** — S = β + 1 = 5.
**Concept:** Fixed-bias stability factor S = β+1 (poorest stability).
**Twist:** Voltage-divider bias → S ≈ 1+RB/RE (small, best). Self (emitter) bias → S = (1+β)/(1+β·RE/(RB+RE)).

**Q44 (TSSPDCL-2022):** What is the current gain of a transistor in the CC mode, given a current gain of 0.98 in the CB mode?
(a) 100 (b) 98 (c) 50 (d) 49
**Ans: (c)** — β = α/(1−α) = 0.98/0.02 = 49; CC gain = 1+β = 50.
**Concept:** CC current gain Ai = 1+β.
**Twist:** α = 0.99 → β = 99, CC gain = 100. α = 0.95 → β = 19, CC gain = 20.

**Q45 (TSNPDCL-22):** Indicate the correct combination and sequence of a cascode amplifier.
(a) common base followed by common emitter (b) common gate followed by common source (c) common emitter followed by common collector (d) common source followed by common gate
**Ans: (d)** — cascode = CS followed by CG (or CE followed by CB).
**Concept:** Cascode — CS-CG (CE-CB) reduces Miller effect, high bandwidth.
**Twist:** Cascade = CE-CC (Q32). In BJT cascode CE then CB → input capacitance reduced → higher f_T performance.

**Q46 (TSNPDCL-22):** On the BJT characteristic curve (IC vs VCE, line AB from IC-axis to VCE-axis crossing IB1, IB2, IB3 curves), the straight-line AB represents
(a) unity gain line (b) active region (c) saturation line (d) DC load line
**Ans: (d)** — straight line AB is the DC load line.
**Concept:** DC load line — locus of Q-point, slope −1/RC.
**Twist:** AC load line has different slope −1/RC' where RC' = RC||RL. Endpoints: IC(sat) = VCC/RC, VCE(off) = VCC.

**Q47 (TSNPDCL-22):** In a base drive circuit of a BJT, the choice of opto-coupler using photodiode and BJT depends on (A) current transfer ratio (B) voltage transfer ratio (C) breakdown voltage between opto-coupler and transistor terminals (D) propagation delay for turn-on/off
(a) (A) and (B) (b) (B) and (C) (c) (D) and (B) (d) (C) and (D)
**Ans: (d)** — breakdown voltage (isolation rating) and propagation delay matter.
**Concept:** Opto-coupler selection — isolation breakdown voltage + propagation delay for switching.
**Twist:** For high-voltage switching the isolation rating (C) is critical; for fast PWM, propagation delay (D). CTR (A) applies to phototransistor optocouplers, not photodiode-based.

**Q48 (TSPSC-AEE-23):** Q1 and Q2 are perfectly matched BJTs. Assuming β infinite and forward bias diode drop 0.7 V, find Iout (+5 V, Q1, Q2, 1 kΩ, −5 V).
(a) 5.7 mA (b) 0 mA (c) 3.6 mA (d) 4.3 mA
**Ans: (c)** — Vx = 5 − 0.7 − 0.7 = 3.6 V; IC1 = IC2 = 3.6 V/1 kΩ = 3.6 mA.
**Concept:** Matched BJT pair / current mirror — equal currents.
**Twist:** Single 0.7 V drop → I = (5−0.7)/1k = 4.3 mA. Two diode drops → 3.6 mA. This is a current source whose value tracks (VCC−2VBE)/R.

**Q49 (TSPSC-AEE-23):** What is the small-signal gain of the circuit in figure (+5 V, 10 kΩ, 5 kΩ, gm = ∞, CS amplifier with 1 kΩ source resistor)
(a) −5 (b) 4 (c) 5 (d) −4
**Ans: (a)** — with gm → ∞, Vgs → 0, gain = −RD/RS = −5 k/1 k = −5.
**Concept:** CS amplifier with large gm → degenerate gain Av = −RD/RS.
**Twist:** RD = 5 k, RS = 2 k → gain = −2.5. Finite gm → Av = −gm·RD/(1+gm·RS), magnitude < 5.

**Q50 (TSPSC-AEE-23):** For the two circuits to be equivalent (drawn gm·Vgs source vs resistor R in parallel with Vgs), R should be equal to
(a) 1/(2gm) (b) 0 (c) infinity (d) 1/gm
**Ans: (d)** — R = 1/gm for the gm·Vgs source to be equivalent.
**Concept:** Source transformation of dependent source → R = 1/gm.
**Twist:** gm = 5 mS → R = 200 Ω. Two such sources in parallel → R = 1/(2gm).

**Q51 (TSPSC-AEE-23):** A bipolar junction transistor is
(a) a field-controlled device (b) a voltage-controlled device (c) a current-controlled device (d) a charge-controlled device
**Ans: (c)** — BJT is current-controlled.
**Concept:** BJT = current-controlled; FET/MOSFET = voltage-controlled.
**Twist:** MOSFET = voltage-controlled (Q2, Q28). In switching, BJT is treated as charge-controlled (stored base charge).

**Q52 (TSPSC-AEE-23):** A MOSFET biased in common-drain configuration is best suited for designing a
(a) transconductance amplifier (b) current buffer (c) voltage buffer (d) transresistance amplifier
**Ans: (c)** — common-drain (source follower) has Av ≈ 1, high Zi, low Zo → voltage buffer.
**Concept:** Common-drain = source follower = voltage buffer.
**Twist:** Common-gate/base = current buffer. Common-source = transconductance amplifier.

**Q53 (TSSPDCL-AE-2023):** A transistor with α = 0.96 is placed in CB configuration with load RL. If emitter-base junction resistance is 80 Ω and voltage gain is 60, RL is
(a) 5 kΩ (b) 4.8 kΩ (c) 4 kΩ (d) 4.6 kΩ
**Ans: (—)** — computed RL = 200 Ω; none of the options match (solution key: "Options not matched, correct answer is 200 Ω").
**Concept:** CB voltage gain Av = α·RL/ri → RL = Av·ri/α.
**Twist:** Using ideal α≈1 approximation Av ≈ RL/ri → RL ≈ 60×80 = 4.8 kΩ (option b, if ri = 80 and α=1). Precise calc gives 200 Ω.

**Q54 (TSPSC-AEE-23):** Identify the correct one(s) related to CE emitter-bias configuration:
I. Input impedance Zi = RB||βre
II. Output impedance Zo = RC
III. Voltage amplification Av ≈ −RC/RE
(a) I and II (b) I, II and III (c) II and III (d) I and II
**Ans: (c)** — II and III correct; I is wrong because with emitter resistor Zi = RB||[β(re + RE)].
**Concept:** CE emitter-bias — Av ≈ −RC/RE, Zi = RB||[β(re+RE)].
**Twist:** If RE is bypassed by CE capacitor → Av = −gm·RC (large gain, unstable). Emitter bias trades gain for bias stability.

**Q55 (TSPSC-AEE-23):** Determine VGS from the given circuit (48 V, 4 kΩ, IDSS = 10 mA, Va = −24 V, gate via 2 MΩ, source at +8 V).
(a) −24 V (b) 0 V (c) 48 V (d) −8 V
**Ans: (d)** — IG ≈ 0 (JFET high input resistance) → gate at 0 V, source at +8 V → VGS = −8 V.
**Concept:** JFET self-bias — VGS = VG − VS = −VS (gate grounded through RG).
**Twist:** Source at +4 V → VGS = −4 V. Gate divider sets VG = +5 V with VS = 8 V → VGS = −3 V.

**Q56 (TSPSC-AEE-23):** Identify the correct pair of term: expression related to FET amplifiers:
I. Shockley equation: ID = IDSS(1 − VGS/VP)²
II. Transconductance: gm = ΔID/ΔVGS
III. Voltage gain: Av = −gmRD
(a) I and III only (b) I, II and III (c) II and III only (d) I and II only
**Ans: (b)** — all three are correct.
**Concept:** FET amplifier relations — Shockley, gm, Av = −gmRD.
**Twist:** RD replaced by (RL||rd) → Av = −gm(RL||rd). With source degeneration RS → Av = −gmRD/(1+gmRS).

**Q57 (TSPSC-AEE-23):** In the circuit (+15 V, 4 kΩ, 720 kΩ, β = 50, emitter network), determine VE1, VE2, VE3 for IE = 1.75, 2.5, 3.75 mA respectively, and arrange in increasing order.
(a) VE3, VE1, VE2 (b) VE1, VE2, VE3 (c) VE2, VE1, VE3 (d) VE3, VE2, VE1
**Ans: (b)** — VE = IE·RE; larger IE → larger VE, so increasing order is VE1, VE2, VE3.
**Concept:** Emitter voltage VE = IE·RE (emitter-bias).
**Twist:** RE = 2 kΩ → VE = 3.5, 5.0, 7.5 V. If RE differs per stage, ordering can change.

**Q58 (TSPSC-AEE-23):** Determine the collector current from the circuit where VCC = 350 V, RC = 15 Ω, VCE = 2 V.
(a) 40 A (b) 23.2 A (c) 32.4 A (d) 16.4 A
**Ans: (b)** — IC = (VCC − VCE)/RC = (350−2)/15 = 23.2 A.
**Concept:** Collector current IC = (VCC − VCE)/RC.
**Twist:** VCE = 5 V → IC = 23 A. RC = 10 Ω → IC = 34.8 A (power BJT switching).

**Q59 (TSPSC-AEE-23):** Determine the base-emitter current (IB) for the fixed bias configuration with VCC = +13 V, RB = 300 kΩ, RC = 3.8 kΩ (silicon BJT).
(a) 0.041 µA (b) 15.28 µA (c) 41 µA (d) 24.58 µA
**Ans: (c)** — KVL: 13 − 300k·IB − 0.7 = 0 → IB = 12.3/300k = 41 µA.
**Concept:** Fixed bias IB = (VCC − VBE)/RB.
**Twist:** RB = 600 kΩ → IB = 20.5 µA. VCC = 15 V → IB = 47.7 µA.

## Unit 3: Op-Amp (49 Qs)

Ideal op-amp, inverting/non-inverting, CMRR, slew rate, comparators, filters, 555/multivibrators, oscillators. Numbering restarts per unit; answers matched by content from the solutions section.

---

**Q1 (EPDCL-10):** Ideal operational amplifier has
(a) Infinite input resistance (b) Infinite output resistance (c) Small gain (d) Small bandwidth
**Ans: (a)** — Ideal op-amp has infinite input resistance, zero output resistance, infinite gain and infinite bandwidth.
**Concept:** Ideal op-amp: Ri = ∞, Ro = 0, Av = ∞, BW = ∞.
**Twist:** "Which is NOT ideal" → infinite output resistance (Ro must be 0). Practical 741: Ri ≈ 2 MΩ, Ro ≈ 75 Ω.

**Q2 (APGenco-12):** Differential amplifier, Ad = 20,000, CMRR = 80 dB. Common-mode gain Ac is
(a) 1 (b) 1/2 (c) 2 (d) 250
**Ans: (c)** — 80 = 20log(Ad/Ac) → Ac = 20,000/10⁴ = 2.
**Concept:** CMRR = Ad/Ac; in dB = 20log(Ad/Ac).
**Twist:** CMRR = 60 dB → Ac = 20. CMRR given as ratio 10⁴ → Ac = 2 directly (no log).

**Q3 (APGenco-12):** Amplifier input power 2 µW, power gain 60 dB. Output power is
(a) 2 milliwatts (b) 6 microwatts (c) 2 watts (d) 120 microwatts
**Ans: (c)** — 60 dB = 10log(Po/Pi) → Po = 2 µW × 10⁶ = 2 W.
**Concept:** Power gain (dB) = 10log(Po/Pi); 60 dB = factor 10⁶.
**Twist:** Voltage gain 60 dB → factor 10³ (20log scale). Power gain 30 dB → ×1000.

**Q4 (APGenco-12):** Voltage gains with and without feedback are 20 and 100. Percentage negative feedback?
(a) 40% (b) 80% (c) 4% (d) 8%
**Ans: (c)** — 20 = 100/(1+100β) → β = 0.04 = 4%.
**Concept:** Closed-loop gain Af = A/(1 + Aβ).
**Twist:** Af = 50, A = 100 → β = 1%. Af = 50, A = 500 → β = 1.8%.

**Q5 (APGenco-12):** Differential configuration, open-loop gain 100,000, differential input 2 µV, supply ±12 V. Output voltage?
(a) +12 V (b) −12 V (c) 0 V (d) 2 µV
**Ans: (—)** — V0 = Ad·Vd = 2×10⁻⁶ × 10⁵ = 0.2 V (no option matches; book marks it *).
**Concept:** Open-loop operation V0 = Ad·Vd; saturates at ±VCC only if computed value exceeds rails.
**Twist:** Vd = 200 µV → V0 = 20 V, saturates at +12 V. Vd = 2 µV, Ad = 10⁶ → 2 V.

**Q6 (APSPDCL-12):** The ideal operational amplifier has
(a) Ri = ∞, R0 = ∞ (b) Ri = 0, R0 = ∞ (c) Ri = ∞, R0 = 0 (d) Ri = 0, R0 = 0
**Ans: (c)** — Ideal: infinite input resistance, zero output resistance.
**Concept:** Ideal op-amp: Ri = ∞, Ro = 0.
**Twist:** Ideal voltage source has Ro = 0 too; ideal current source has Ro = ∞ (opposite).

**Q7 (APSPDCL-12):** In LM741, LM stands for
(a) Motorola (b) RCA (c) Texas instruments (d) National semiconductor
**Ans: (d)** — LM is National Semiconductor's prefix for linear ICs.
**Concept:** IC manufacturer codes: LM = National, MC = Motorola, CA = RCA, SN = TI, µA = Fairchild.
**Twist:** CA741 → RCA. SN72741 → Texas Instruments. µA741 → Fairchild.

**Q8 (APSPDCL-12):** Voltage follower output is a triangular wave (figure: ±3 V, period 0.5 µs) for an 8 Vpp square input at 2 MHz. Slew rate of op-amp?
(a) 6 µs (b) 12 V/µs (c) 14 V/µs (d) 14 µs
**Ans: (—)** — Slew rate = slope of triangle = 6 V / 0.25 µs = 24 V/µs (no option matches; book marks *).
**Concept:** Slew rate = maximum dVo/dt = slope of the output ramp.
**Twist:** Triangle ±5 V rising in 0.5 µs → SR = 20 V/µs. If triangle is 8 Vpp with T = 1 µs → SR = 32 V/µs.

**Q9 (HMWS-12):** Ideal op-amp, V1 sinωt and V2 sinωt fed via capacitors C to inverting input with C feedback. V0?
(a) zero (b) (V1 − V2) sinωt (c) −(V1 + V2) sinωt (d) (V1 + V2) sinωt
**Ans: (c)** — Virtual ground summing of currents: V0 = −(V1 + V2) sinωt.
**Concept:** Inverting adder/summer (capacitor-coupled inputs), virtual ground.
**Twist:** Second input to non-inverting (+) terminal → V0 = (V2 − V1) sinωt. DC inputs V1, V2 → V0 = −(V1+V2).

**Q10 (EPDCL-14):** Which is NOT an ideal op-amp characteristic?
(a) Infinite voltage gain (b) Infinite output resistance (c) Infinite input resistance (d) Infinite bandwidth
**Ans: (b)** — Ideal op-amp has ZERO output resistance, not infinite.
**Concept:** Ideal op-amp: Ro = 0, Ri = ∞, Av = ∞, BW = ∞.
**Twist:** "Infinite CMRR" → yes, ideal. "Finite bandwidth" → not ideal (BW must be ∞).

**Q11 (APSPDCL-14):** Op-amp slew rate 3 V/µs. Max closed-loop gain when input changes by 0.4 V in 12 µs?
(a) 120 (b) 90 (c) 300 (d) 100
**Ans: (b)** — SR = ACL·(ΔVi/Δt) → 3 = ACL(0.4/12) → ACL = 90.
**Concept:** Slew rate = ACL × rate of change of input.
**Twist:** Input 0.2 V in 10 µs, SR = 2 V/µs → ACL = 100. SR = 5 V/µs, dVi/dt = 0.1 V/µs → ACL = 50.

**Q12 (ISRO-14):** Op-amp integrator (R1 input, C1 feedback), square-wave input. Output waveform?
(a) Square wave (b) Sine wave (c) Triangle wave (d) Saw tooth wave
**Ans: (c)** — V0 = −(1/R1C1)∫Vin dt; integral of square wave = triangle.
**Concept:** Integrator: V0 = −(1/RC)∫Vin dt.
**Twist:** Sine input → cosine (90° lag). DC input → output ramps until saturation.

**Q13 (ISRO-14):** Inverting op-amp, the two input terminals are at same potential because
(a) inputs are directly shorted internally (b) input impedance is infinity and CMRR is infinity (c) open-loop gain is infinity (d) slew rate is very high
**Ans: (c)** — Virtual short follows from infinite open-loop gain + negative feedback.
**Concept:** Virtual ground / virtual short (V+ ≈ V−).
**Twist:** Non-inverting terminal grounded → inverting terminal is a virtual ground at 0 V. With finite gain A, V− = V0/A ≈ small.

**Q14 (HMWS-15):** An ideal op-amp slew rate is
(a) Infinitely fast (b) Slow (c) Fast (d) Very slow
**Ans: (a)** — Ideal op-amp responds instantly; SR = ∞.
**Concept:** Slew rate = max dVo/dt; infinite for ideal.
**Twist:** Practical 741 ≈ 0.5 V/µs; high-speed LM318 ≈ 50 V/µs.

**Q15 (TSTransco-15):** CMRR of a differential amplifier (Ad = differential gain, Ac = common-mode gain)?
(a) Ad/Ac (b) (Ad − Ac)/Ad (c) 20 log10(Ad/Ac) (d) 20 log10(Ac/Ad)
**Ans: (a)** — CMRR = Ad/Ac.
**Concept:** CMRR = Ad/Ac; in dB: 20log(Ad/Ac).
**Twist:** Ad = 10⁵, Ac = 10 → CMRR = 10⁴ (80 dB). Ideal CMRR = ∞.

**Q16 (APGenco-12):** Which circuit is used as amplitude comparator?
(a) Bistable (b) Monostable (c) Astable (d) Schmitt trigger
**Ans: (d)** — Schmitt trigger compares input against threshold levels (comparator with hysteresis).
**Concept:** Schmitt trigger as amplitude comparator.
**Twist:** Plain comparator (no hysteresis) → zero-crossing detector. Two thresholds (UTP/LTP) give noise immunity.

**Q17 (SSC-JE-13):** Circuit (Vi → inverting input, R1–R2 positive-feedback divider to non-inverting) represents a
(a) monostable multivibrator (b) astable multivibrator (c) Schmitt trigger (d) bistable multivibrator
**Ans: (c)** — Positive feedback to the + input makes a Schmitt trigger.
**Concept:** Schmitt trigger = comparator with positive feedback (hysteresis).
**Twist:** Swap feedback to − input → inverting amplifier (no hysteresis). Add RC to the + path → astable multivibrator.

**Q18 (SSC-JE-12):** A sine wave fed into a Schmitt trigger gives output
(a) saw-tooth wave (b) amplified sine wave (c) triangular wave (d) square wave
**Ans: (d)** — Output switches between ±Vsat whenever input crosses thresholds → square wave.
**Concept:** Schmitt trigger saturates → square-wave output.
**Twist:** Triangular input → square wave. Sine into plain comparator → square wave with 50% duty.

**Q19 (APGenco-17):** An ideal Op-Amp is an ideal
(a) voltage controlled current source (b) voltage-controlled voltage source (c) current controlled current source (d) current controlled voltage source
**Ans: (b)** — Output voltage is controlled by the differential input voltage.
**Concept:** Op-amp = voltage-controlled voltage source (VCVS).
**Twist:** BJT = current-controlled device. Transconductance amplifier = VCCS.

**Q20 (APGenco-17):** 100 pF capacitor has max charging current 150 µA. Slew rate?
(a) 1.5 V/µs (b) 1.05 V/µs (c) 0.15 mV/s (d) 10.5 mV/s
**Ans: (a)** — i = C dv/dt → dv/dt = 150 µA / 100 pF = 1.5 V/µs.
**Concept:** Slew rate = I/C (charging of the internal compensation capacitor).
**Twist:** C = 50 pF, I = 100 µA → SR = 2 V/µs. Larger charging current → higher slew rate.

**Q21 (TSSPDCL-18):** Highest frequency of a 20 Vpp triangular wave reproducible by an op-amp with slew rate 10 V/µs?
(a) 50 kHz (b) 150 kHz (c) 250 kHz (d) 350 kHz
**Ans: (c)** — Slope = 20 V/(T/2) = 10 V/µs → T = 4 µs → f = 250 kHz.
**Concept:** Slew-rate limit on triangular wave: slope = 4A/T.
**Twist:** 10 Vpp, SR = 10 V/µs → f = 500 kHz. SR = 5 V/µs, 20 Vpp → f = 125 kHz.

**Q22 (TSSPDCL-18):** Differentiator circuit (C1 input, Rf feedback), square-wave input. Output waveform (figure options)?
(a) — (b) spikes (c) — (d) —
**Ans: (b)** — V0 = −RfC1 dVi/dt; square wave → narrow spikes at edges.
**Concept:** Differentiator: V0 = −RC dVi/dt.
**Twist:** Triangular input → square wave. Sawtooth input → rectangular pulses.

**Q23 (TSSPDCL-18):** Non-inverting amp, Vs = 10 sin 2000t, Rf = 20 kΩ, R1 = 5 kΩ, supply ±15 V. Peak output voltages?
(a) 50 V, −50 V (b) 15 V, −15 V (c) 40 V, −40 V (d) 2.5 V, −2.5 V
**Ans: (b)** — Gain = 1 + 20/5 = 5 → 50 sin 2000t, but clipped at ±Vsat = ±15 V.
**Concept:** Non-inverting: Av = 1 + Rf/R1; output clamps at supply rails.
**Twist:** Supply ±20 V → peaks ±20 V. Rf = 4k, R1 = 1k, Vs = 3 sin → gain 5 → ±15 V (clipped).

**Q24 (TSTransco-18):** Frequency of Colpitts oscillator?
(a) f = 1/(2π√(L·C1C2/(C1+C2))) (b) f = 1/(2π√(L(C1+C2))) (c) f = 1/(2π√((L1+L2)C)) (d) f = 1/(2π√((L1+L2+2M)C))
**Ans: (a)** — Ceq = C1C2/(C1+C2); f = 1/(2π√(LCeq)).
**Concept:** Colpitts oscillator (two capacitors + one inductor).
**Twist:** Hartley uses two inductors → f = 1/(2π√((L1+L2)C)) (option c). Coupled coils add 2M term.

**Q25 (TSTransco-18):** Type of feedback in Wien bridge oscillator?
(a) negative feedback only (b) positive feedback only (c) no feedback (d) both negative and positive
**Ans: (d)** — Positive feedback (lead-lag network) sustains oscillation; negative feedback stabilizes amplitude/gain.
**Concept:** Wien bridge uses both positive and negative feedback.
**Twist:** Minimum gain required = 3 (from negative-feedback branch). Barkhausen condition Aβ = 1.

**Q26 (TSTransco-18):** Ideal op-amp voltage follower, Vin = 5 sinωt mV. Vout?
(a) 5 sinωt (b) −5 sinωt (c) 10 sinωt (d) 2.5 sinωt
**Ans: (a)** — Unity-gain buffer: Vout = Vin = 5 sinωt.
**Concept:** Voltage follower / unity-gain buffer (Av = 1, high Zin, low Zout).
**Twist:** Non-inverting with Rf = R1 → Av = 2 → 10 sinωt. Inverting buffer (Rf = R1) → −5 sinωt.

**Q27 (APEPDCL-19):** IC 741 slew rate 0.5 V/µs, max undistorted output 5 V. Max frequency without distortion?
(a) 100 kHz (b) 159.2 kHz (c) 1.592 kHz (d) 15.92 kHz
**Ans: (d)** — fmax = SR/(2πVm) = 0.5/(2π×5×10⁻⁶) = 15.92 kHz.
**Concept:** Slew-rate limited full-power bandwidth: fmax = SR/(2πVm).
**Twist:** Vm = 1 V → fmax = 79.6 kHz. SR = 1 V/µs, Vm = 5 V → 31.8 kHz.

**Q28 (—):** Ratio V2/V1 for the network (V1 via 10k/5k divider to + input; 2k/7k non-inverting feedback)?
(a) 3.5 (b) 5 (c) 3 (d) 1.5
**Ans: (d)** — V+ = V1(5/15) = V1/3; V2 = (V1/3)(1 + 7/2) = 1.5 V1.
**Concept:** Non-inverting gain with input attenuator: V2 = (divider ratio)·(1 + Rf/Ri)·V1.
**Twist:** V1 straight to + input → gain = 1 + 7/2 = 4.5. Divider 10k/10k → ratio = 2.25.

**Q29 (—):** All statements about Wien bridge oscillator are correct EXCEPT:
(a) Frequency f0 can be varied in the ratio of 3:1 (b) f = 1/(2πRC) (c) minimum amplifier gain 3 (d) it employs lead-lag network
**Ans: (a)** — Wien bridge f can be varied over a wider range; the 3:1 claim is false (the exception).
**Concept:** Wien bridge: f = 1/(2πRC), gain ≥ 3, lead-lag feedback network.
**Twist:** "Which is correct?" → (b). Gain below 3 → oscillations decay (no sustained oscillation).

**Q30 (TSSPDCL-2022):** Ideal op-amp, inverting, 1k/2k resistors, Vin = −5 V. Vout?
(a) +10 V (b) +15 V (c) −10 V (d) −15 V
**Ans: (d)** — Virtual ground: I = (0−(−5))/1k = 5 mA; Vout = −5 − 5×2 = −15 V.
**Concept:** Inverting amplifier via virtual-ground node analysis.
**Twist:** Vin = +5 V → Vout = +15 V (option b). Rf = 3k → −20 V (clips at −15 V).

**Q31 (TSSPDCL-2022):** Ideal op-amp, inputs 5 mV and 9 mV through 2.5k and 3k, feedback 7k. Vout?
(a) −14 mV (b) 14 mV (c) −35 mV (d) 35 mV
**Ans: (c)** — Summing: I = 5/2.5 + 9/3 = 5 µA → Vout = −7k × 5 µA = −35 mV.
**Concept:** Inverting summing amplifier (virtual ground).
**Twist:** Non-inverting summing → +35 mV. Rf = 14 k → −70 mV.

**Q32 (TSNPDCL-22):** Type of feedback usually employed in an oscillator?
(a) Negative feedback (b) Positive feedback (c) Open loop feedback (d) Imaginary feedback
**Ans: (b)** — Oscillators use positive feedback satisfying Aβ = 1.
**Concept:** Oscillator = positive feedback (Barkhausen criterion).
**Twist:** Amplifiers use negative feedback (for stability). Aβ > 1 → growing/distorted oscillations.

**Q33 (TSPSC-AEE-23):** Terminals X and Y for the circuit to be in negative feedback (1k, 1k, 2k, 1k, 2V)?
(a) never in negative feedback (b) X negative, Y positive (c) X positive, Y negative (d) any terminal
**Ans: (c)** — Loop-gain sign must be negative: Y (feedback return) = − input, X = + input.
**Concept:** Negative feedback requires feedback to oppose the input (loop gain negative).
**Twist:** Swap X/Y → positive feedback (latches/saturates). Remove inverting stage → never negative.

**Q34 (TSPSC-AEE-23):** Same circuit under negative feedback, find Vo (2V input)?
(a) −4 V (b) 1 V (c) 2 V (d) 3 V
**Ans: (a)** — Virtual short VX = VY + node analysis → Vo = −4 V.
**Concept:** Virtual short in negative feedback; superposition/node equations.
**Twist:** Input 2V → 1V gives Vo = −2 V. Change feedback ratio (1k/2k) → different Vo.

**Q35 (TSPSC-AEE-23):** Find current IX (3k, 3k, 6k, 3k, 4V source)?
(a) −0.33 mA (b) 0.33 mA (c) 0.67 mA (d) −0.67 mA
**Ans: (d)** — Node at virtual ground: IX = (−2 − 0)/3k = −0.67 mA.
**Concept:** Virtual ground + KCL at op-amp input node.
**Twist:** Source 4V → 2V → IX = −0.33 mA. Reverse source polarity → +0.67 mA.

**Q36 (TSPSC-AEE-23):** Ideal op-amp, find Vout (1V source, 1k resistors)?
(a) −2 V (b) 0 V (c) 1 V (d) −1 V
**Ans: (—)** — Vout = 0 − 0.5 = −0.5 V (book marks *; options don't match).
**Concept:** Inverting stage with input divider; KVL/node analysis.
**Twist:** Source 2 V → Vout = −1 V (option d). Rf = 2k → −1 V.

**Q37 (TSPSC-AEE-23):** Type of filter (1k, 1k, 1k, 1pF)?
(a) Band-stop filter (b) Low-pass filter (c) High-pass filter (d) Band-pass filter
**Ans: (c)** — At ω=0 cap open → Vout = 0; at ω=∞ cap short → Vin passes → high-pass.
**Concept:** Active high-pass filter (capacitor blocks DC).
**Twist:** Feedback cap + input R only → low-pass. Band-pass needs both RC pairs.

**Q38 (TSPSC-AEE-23):** Polarity of op-amp inputs for negative feedback (CE-transistor in loop, 1 mA, 1V)?
(a) never negative feedback (b) A positive, B negative (c) A negative, B positive (d) always negative feedback
**Ans: (b)** — Loop gain must be negative; CE stage gives −gain, so A = + input, B = − input.
**Concept:** Loop-gain sign analysis for negative feedback (inverting stages).
**Twist:** Replace CE with CC (gain +) → A negative, B positive. Odd number of inversions → positive feedback.

**Q39 (TSPSC-AEE-23):** What filter is realized (1k, 1k, 1k, 1pF)?
(a) All-pass filter (b) Low-pass filter (c) High-pass filter (d) Band-pass filter
**Ans: (a)** — Vin passes at ω=0 (Vout=Vin) and at ω=∞ (Vout=−Vin); |gain| constant → all-pass.
**Concept:** All-pass filter / phase shifter (constant magnitude, varying phase).
**Twist:** If magnitudes differ (gain ≠ 1) → band-reject behaviour. Second cap → true band-reject.

**Q40 (TSPSC-AEE-23):** Time period of oscillation of Vout (relaxation/astable, R3, C, R1, R2)?
(a) (R2/R1)·2R3C·ln(1 + 2R2/R1) (b) 2R3C·ln(1 + 2R1/R2) (c) (R2/R1)·2R3C·ln(1 + 2R1/R2) (d) (R1/R2)·2R3C·ln(1 + 2R1/R2)
**Ans: (b)** — T = 2R3C·ln((1+β)/(1−β)) = 2R3C·ln(1 + 2R1/R2), with β = R1/(R1+R2).
**Concept:** Relaxation (astable) oscillator period: Schmitt trigger + RC.
**Twist:** R1 = R2 → β = 1/2 → T = 2R3C·ln3. β → 0 → T → 0.

**Q41 (TSSPDCL-AE-2023):** Value of V2 (two-stage op-amp, +0.5 V, −0.6 V, 1k/2k/3k resistors)?
(a) −2.8 V (b) 2.8 V (c) −1.8 V (d) 0.8 V
**Ans: (a)** — V1 = −(3k/1k)(−0.6) = +1.8 V; V2 = −(2k/1k)(0.5) − (2k/2k)(1.8) = −2.8 V.
**Concept:** Cascade of inverting stages; superposition.
**Twist:** Reverse source polarities → +2.8 V. −0.6 V → −0.3 V gives V1 = +0.9 V, V2 = −1.9 V.

**Q42 (TSPSC-AEE-23):** Non-inverting amplifier, V1 = 5 V, Rf = 1500 kΩ, R1 = 300 kΩ. Output?
(a) 5 V (b) 16 V (c) 30 V (d) 3 V
**Ans: (c)** — V0 = 5(1 + 1500/300) = 5 × 6 = 30 V.
**Concept:** Non-inverting: Av = 1 + Rf/R1.
**Twist:** Inverting with same resistors → −25 V. Rf = R1 = 300k → 10 V.

**Q43 (TSPSC-AEE-23):** Basic op-amp connection (inverting, R1/Rf): I: Rf = R1 → voltage gain exactly 1 (unity). II: Rf a multiple of R1 → constant magnitude gain. Correct?
(a) Both I and II (b) Only I (c) Neither I nor II (d) Only II
**Ans: (a)** — Inverting gain Av = −Rf/R1: unity magnitude when equal; constant magnitude when ratio fixed.
**Concept:** Inverting amplifier gain Av = −Rf/R1.
**Twist:** Non-inverting with Rf = R1 → gain 2 (not 1). Unity gain non-inverting → use voltage follower (buffer).

**Q44 (TSPSC-AEE-23):** Inverting amp, Rf = 360 kΩ, R1 = 4 kΩ, sinusoidal input 12 mV (±15 V supply). Output?
(a) −1.08 V (b) −24 V (c) 12 V (d) 15 V
**Ans: (a)** — V0 = −(360/4)(12 mV) = −1.08 V.
**Concept:** Inverting: Av = −Rf/R1.
**Twist:** Input 1 V → −90 V, clipped at −15 V. Rf = 360k, R1 = 12k, 12 mV → −0.36 V.

**Q45 (TSPSC-AEE-23):** Expression of a differentiator?
(a) v0(t) = −(1/RC)∫v1(t)dt (b) v0(t) = −RC∫v1(t)dt (c) v0(t) = −(1/RC)dv1(t)/dt (d) v0(t) = −RC·dv1(t)/dt
**Ans: (d)** — Differentiator: v0 = −RC·dv1/dt.
**Concept:** Differentiator: V0 = −RC·dVi/dt.
**Twist:** Integrator is option (a): v0 = −(1/RC)∫v1 dt. Square in → spikes; triangle in → square.

**Q46 (TSPSC-AEE-23):** Match filters — I low-pass, II band-pass, III high-pass — with responses 1, 2, 3?
(a) I-1, II-3, III-2 (b) I-2, II-1, III-3 (c) I-2, II-3, III-1 (d) I-1, II-2, III-3
**Ans: (c)** — I (low-pass) → 2, II (band-pass) → 3, III (high-pass) → 1.
**Concept:** Filter magnitude responses vs frequency and impedance-angle plots.
**Twist:** Band-stop response → notch (falls then rises). Swap component type changes low↔high roles.

**Q47 (TSPSC-AEE-23):** CMRR of op-amp with differential gain Ad and common-mode gain Ac?
(a) Ad + Ac (b) Ad/Ac (c) (1 + Ad)/Ac (d) Ac/Ad
**Ans: (b)** — CMRR = Ad/Ac.
**Concept:** CMRR = Ad/Ac (figure of merit for common-mode rejection).
**Twist:** In dB: 20log(Ad/Ac). High CMRR → better suppression of common-mode noise on both inputs.

**Q48 (TSPSC-AEE-23):** Current drawn from a dual ±24 V supply if the IC dissipates 2000 mW?
(a) 40 mA (b) 83.34 A (c) 41.67 mA (d) 166.67 mA
**Ans: (c)** — I = P/V = 2000 mW / 48 V = 41.67 mA (total dual-rail voltage).
**Concept:** Power dissipation P = V·I across the dual supply rails.
**Twist:** ±12 V supply, 2000 mW → 83.3 mA. 1000 mW at ±24 V → 20.8 mA.

**Q49 (TSGenco-24):** Circuit (diode D in feedback loop, R, op-amp, Vi) can be used as a
(a) full-wave rectifier (b) voltage to frequency converter (c) logarithmic amplifier (d) frequency to voltage converter
**Ans: (c)** — Diode (or transistor) in feedback gives V0 ∝ ln(Vi).
**Concept:** Logarithmic amplifier (log amp with diode in feedback).
**Twist:** Replace diode with linear R → inverting amplifier. Reverse diode direction → |V0| log for negative inputs (precision rectifier).

---
*(Total: 49 questions. Solutions source: OHM Institute OP-AMP unit; answers marked (—) are cases where the printed options do not match the computed answer.)*

## Unit 4: Miscellaneous — Oscillators, 555, Regulators (29 Qs)

Oscillators, 555 timer, regulators, power amplifiers, waveform generators, RC circuits. 29 questions.

---

**Q1 (SSC-JE-10):** An oscillator uses:
(a) Positive feedback (b) Negative feedback (c) Both positive and negative feedback (d) No feedback
**Ans: (a)** — Oscillators employ positive (regenerative) feedback to sustain the output signal.
**Concept:** Positive feedback — a fraction of output is fed back in phase to reinforce the input.
**Twist:** Circuit asking for stability → negative feedback. Amplitude stabilization of an oscillator → non-linear element / AGC (AVC).

**Q2 (EPDCL-10):** Pulse generator is:
(a) Astable multivibrator (b) Monostable multivibrator (c) Bistable multivibrator (d) Schmitt trigger
**Ans: (b)** — Monostable MV produces one output pulse per trigger; astable is the square-wave generator.
**Concept:** Monostable (one-shot) MV — one quasi-stable state, outputs a single pulse.
**Twist:** Square-wave generator → astable MV. Storing binary information → bistable MV (flip-flop).

**Q3 (APSPDCL-12):** The efficiency of a class B amplifier for a supply VCC = 24 V with peak-to-peak output of 6 V is:
(a) 4% (b) 48% (c) 19.5% (d) 39.2%
**Ans: (c)** — η = (π/4)·(Vm/VCC)·100 = (π/4)(6/24)·100 ≈ 19.6% ≈ 19.5%.
**Concept:** Class B efficiency η = (π/4)(Vm/VCC); maximum π/4 = 78.5% when Vm = VCC.
**Twist:** Ideal condition Vm = VCC → 78.5%. Half the Vm → half the efficiency (~9.8%).

**Q4 (APSPDCL-12):** The timing resistor is 10 kΩ and timing capacitor 200 pF for a 565 PLL. The free-running frequency is:
(a) 500 kHz (b) 350 kHz (c) 250 kHz (d) 150 kHz
**Ans: (d)** — f0 = 0.3/(RT·CT) = 0.3/(10×10³ × 200×10⁻¹²) = 150 kHz.
**Concept:** PLL 565 free-running (centre) frequency f0 = 0.3/(RT·CT).
**Twist:** CT doubled (400 pF) → f0 = 75 kHz. RT made 20 kΩ → f0 = 75 kHz.

**Q5 (APSPDCL-12):** In a monostable multivibrator using 555 timer, time delay is 100 ms, timing resistor is 100 kΩ. The timing capacitor is:
(a) 9 mF (b) 0.9 µF (c) 9 F (d) 1.8 µF
**Ans: (b)** — T = 1.1 RC → C = 100 ms/(1.1 × 100 kΩ) = 0.9 µF.
**Concept:** 555 monostable pulse width T ≈ 1.1 RC.
**Twist:** T = 1000 ms with R = 120 kΩ → C = 7.5 µF. Astable uses T = 0.693(R1+2R2)C.

**Q6 (HMWS-12):** Consider the two statements — 1. Astable MV can generate a square wave. 2. Bistable MV can store binary information.
(a) only Statement 1 is correct (b) only Statement 2 is correct (c) both are correct (d) both are incorrect
**Ans: (c)** — Both statements are true.
**Concept:** Astable = free-running square-wave oscillator; Bistable = flip-flop/latch (stores binary state).
**Twist:** "One-shot / pulse delay" → monostable. "Two stable states, no oscillation" → bistable.

**Q7 (EPDCL-14):** The Barkhausen criterion is:
(a) A = β (b) A = –β (c) Aβ = 1 (d) Aβ = –1
**Ans: (c)** — Oscillation requires |Aβ| = 1 with ∠Aβ = 0° (or 360°).
**Concept:** Barkhausen: loop gain |Aβ| = 1 and total loop phase shift 0° (or 360°).
**Twist:** Start-up condition |Aβ| > 1 (oscillation grows). |Aβ| < 1 → damped (no sustained oscillation).

**Q8 (EPDCL-14):** The maximum conversion efficiency of a class B push-pull amplifier is:
(a) 10π (b) 15π (c) 20π (d) 25π
**Ans: (d)** — ηmax = π/4 = 78.5% (= 25π %).
**Concept:** Class B push-pull max conversion efficiency = π/4 (78.5%).
**Twist:** Class A direct-coupled → 25%; transformer-coupled class A → 50%; class C (tuned) → up to ~85–99%.

**Q9 (EPDCL-14):** Which is a voltage-to-frequency convertor multivibrator?
(a) Bistable (b) Astable (c) Monostable (d) Schmitt trigger
**Ans: (b)** — Astable MV is a voltage-to-frequency converter.
**Concept:** Astable = V→F converter; Monostable = V→time converter.
**Twist:** "Voltage-to-time" → monostable (pulse width ∝ control voltage). "Frequency-to-voltage" → 565 PLL discriminator.

**Q10 (EPDCL-14):** The bandwidth of a low-pass RC circuit is 1 kHz. What is the rise time of output for a step input?
(a) 0.35 ms (b) 3.5 ms (c) 0.35 s (d) 1 ms
**Ans: (a)** — tr = 0.35/BW = 0.35/1000 = 0.35 ms.
**Concept:** Rise time tr ≈ 0.35/BW (equivalently tr = 2.2 RC).
**Twist:** BW = 10 kHz → tr = 0.035 ms. Given R & C directly → tr = 2.2 RC.

**Q11 (APSPDCL-14):** For the 555 timer astable circuit (VCC, RA = 7.2 kΩ from supply to pin 7, RB = 3.6 kΩ pin 7→pin 6, C = 0.1 µF pin 6–2 to ground, output pin 3), find the output frequency:
(a) 100 kHz (b) 1000 Hz (c) 1500 Hz (d) 2000 Hz
**Ans: (b)** — T = 0.693(RA + 2RB)C = 0.693(7.2k + 7.2k)(0.1µ) ≈ 1 ms → f = 1000 Hz.
**Concept:** 555 astable: T = 0.693(RA+2RB)C; f = 1/T.
**Twist:** RA = RB → duty cycle D = (RA+RB)/(RA+2RB) = 2/3. Increase C to 0.2 µF → f = 500 Hz.

**Q12 (ISRO-14):** A comparator circuit is used to:
(a) Mark the instant when an arbitrary waveform attains some reference level (b) Mark the instant when the input voltage becomes constant (c) Switch ON and OFF a circuit alternately at a particular rate (d) Switch OFF a circuit when output becomes zero
**Ans: (a)** — A comparator changes state when the input crosses a reference level.
**Concept:** Comparator — detects crossing of a reference voltage (open-loop op-amp).
**Twist:** Comparator + positive feedback → Schmitt trigger (adds hysteresis, noise immunity).

**Q13 (TGenco-15):** Two non-inverting amplifiers, one unity gain and one gain twenty, made with identical op-amps. Compared to the unity-gain amplifier, the amplifier with gain twenty has:
(a) less negative feedback (b) greater input impedance (c) less bandwidth (d) more bandwidth
**Ans: (a), (c)** — Higher closed-loop gain → smaller feedback fraction β (=1/Af) → less negative feedback; gain–bandwidth product is constant → less bandwidth.
**Concept:** GBW product: Af·BW = constant; non-inverting β = 1/Af.
**Twist:** Gain 10 (GBW fixed) → BW = GBW/10. Unity-gain buffer → maximum bandwidth.

**Q14 (TSTransco-15):** An amplifier has a voltage gain of 120. To reduce distortion, 10% negative feedback is employed. The gain with feedback is:
(a) 141 (b) 92.3 (c) 9.23 (d) 1.41
**Ans: (c)** — Af = A/(1+Aβ) = 120/(1+120×0.1) = 120/13 = 9.23.
**Concept:** Negative feedback: Af = A/(1+Aβ); distortion reduced by factor (1+Aβ).
**Twist:** β = 1% → Af = 120/2.2 ≈ 54.5. β = 5% → Af = 120/7 = 17.1.

**Q15 (TSTransco-15):** The AC bypassing of RE by CF in a common-emitter configuration:
(a) increases AC signal across emitter-base junction (b) decreases AC signal across emitter-base junction (c) decreases voltage amplification (d) stabilizes the Q-point
**Ans: (a)** — The bypass capacitor shorts RE at signal frequency, removing AC negative feedback (degeneration) and increasing the signal across VBE → higher voltage gain.
**Concept:** Emitter bypass capacitor — eliminates AC negative feedback, boosts AC voltage gain.
**Twist:** CF open/removed → gain falls (unbypassed, negative feedback active). CF for DC only → Q-point stabilized with RE, high AC gain.

**Q16 (TSSPDCL-15):** An astable multivibrator has:
(a) two quasi-stable states (b) one quasi-stable state (c) two stable states (d) no-stable state
**Ans: (a)** — Astable: 2 quasi-stable, 0 stable states.
**Concept:** MV state table — Astable (0 stable, 2 quasi); Monostable (1 stable, 1 quasi); Bistable (2 stable, 0 quasi).
**Twist:** Bistable → two stable states (binary storage). Monostable → one quasi-stable state.

**Q17 (TSNPDCL-15):** The op-amp circuit (input through series C then R1 to inverting input, R2 feedback to inverting input, non-inverting grounded) is a:
(a) low-pass filter with f3dB = 1/(R1+R2)C rad/s (b) high-pass filter with f3dB = 1/(R1C) rad/s (c) low-pass filter with f3dB = 1/(R1C) rad/s (d) high-pass filter with f3dB = 1/(R1+R2)C rad/s
**Ans: (b)** — H(s) = −R2/(R1 + 1/sC); magnitude rises from 0 to R2/R1 → high-pass with ω3dB = 1/(R1C).
**Concept:** Active high-pass (differentiator-type): ω3dB = 1/R1C; f3dB = 1/(2πR1C) Hz.
**Twist:** C in feedback with R to ground (input through R) → low-pass/integrator. Both C and R1 present → band-pass (R1 sets low cutoff).

**Q18 (APEPDCL-19):** f1 is the lower half-power frequency of a single-stage amplifier. The lower half-power frequency of an n-stage amplifier is:
(a) f1·√(1 − 2^(−1/n)) (b) f1/√(2^(1/n) − 1) (c) f1·√(2^(1/n) − 1) (d) f1/√(1 − 2^(−1/n))
**Ans: (b)** — fL(n) = f1/√(2^(1/n) − 1).
**Concept:** Cascading n identical stages sharpens the band edge: lower cutoff rises by (2^(1/n)−1)^(−1/2); upper cutoff fH(n) = f2·√(2^(1/n)−1).
**Twist:** n = 2 → fL = f1/√(√2−1) ≈ 1.55·f1. n = 3 → fL = f1/√(2^(1/3)−1) ≈ 1.96·f1.

**Q19 (APEPDCL-19):** The given feedback amplifier topology (CE stage with VCC, bias network R1/R2, collector load R3, feedback resistor from collector to base, Vs/Vi/V0 terminals) is:
(a) current shunt (b) current series (c) voltage series (d) voltage shunt
**Ans: (d)** — Output voltage sampled at collector and fed back in parallel (shunt) to the base input → voltage-shunt (shunt–shunt).
**Concept:** Feedback topology by output sampling (voltage/current) × input mixing (series/shunt).
**Twist:** Feedback to emitter (unbypassed RE) → current series (series–series). Output from emitter follower fed to input → voltage series (series–shunt).

**Q20 (APEPDCL-19):** The frequency of oscillations of a symmetric astable multivibrator, given R = 10 kΩ and C = 10 nF, is:
(a) 28 kHz (b) 7 kHz (c) 14 kHz (d) 3.5 kHz
**Ans: (b)** — f = 1/(1.38 RC) = 1/(1.38 × 10 kΩ × 10 nF) ≈ 7.2 kHz ≈ 7 kHz.
**Concept:** Symmetric (two-transistor) astable MV period T = 1.38 RC.
**Twist:** R doubled (20 kΩ) → f ≈ 3.6 kHz. Unsymmetric (different RC per side) → T = 0.69(R1C1 + R2C2).

**Q21 (APEPDCL-19):** The β-network of a Wien bridge oscillator uses R = 10 kΩ; C varies from 0.001 µF to 0.1 µF. The ratio of maximum to minimum frequency is:
(a) 150 (b) 100 (c) 10 (d) 50
**Ans: (b)** — f = 1/(2πRC) so f ∝ 1/C → fmax/fmin = Cmax/Cmin = 0.1/0.001 = 100.
**Concept:** Wien bridge oscillator frequency f = 1/(2πRC).
**Twist:** R varied 1 kΩ–100 kΩ → ratio 100. Vary both R and C → ratio multiplies.

**Q22 (APSPDCL-19):** A monostable multivibrator using a 555 timer has a time delay of 1000 ms and timing resistor 120 kΩ. The timing capacitor is:
(a) 7.5 µF (b) 9 µF (c) 12 µF (d) 2.5 µF
**Ans: (a)** — C = T/(1.1 R) = 1000 ms/(1.1 × 120 kΩ) = 7.5 µF.
**Concept:** 555 monostable pulse width T ≈ 1.1 RC.
**Twist:** T = 100 ms, R = 100 kΩ → 0.9 µF. Astable → 0.693(R1+2R2)C.

**Q23 (—):** The theoretical maximum efficiency of a transformer-coupled class-A power amplifier is:
(a) 25% (b) 50% (c) 78.5% (d) 92%
**Ans: (b)** — Transformer coupling lets the collector swing ~2VCC, raising class-A maximum efficiency to 50%.
**Concept:** Class-A efficiency: direct-coupled 25%, transformer-coupled 50%.
**Twist:** Direct-coupled class A → 25%. Class B push-pull → 78.5%.

**Q24 (—):** In which feedback topology do both input and output impedances decrease with the introduction of feedback?
(a) Voltage series (b) Current series (c) Voltage shunt (d) Current shunt
**Ans: (a)** — per OHM key. (Textbook result: series mixing raises Zin and voltage sampling lowers Zout, so BOTH decrease only for voltage-shunt (c); some keys/versions list voltage series — verify in exam.)
**Concept:** Series mixing → Zin ↑; Shunt mixing → Zin ↓. Voltage sampling → Zout ↓; Current sampling → Zout ↑.
**Twist:** Only Zout decreases (Zin increases) → voltage-series (series–shunt). Only Zin decreases (Zout increases) → current-shunt (shunt–series).

**Q25 (TSSPDCL-2022):** The voltage gain of an amplifier without feedback and with negative feedback are 100 and 50. Determine the negative feedback factor β:
(a) 0.04 (b) 0.01 (c) 0.05 (d) –0.01
**Ans: (b)** — 50 = 100/(1+100β) → 1+100β = 2 → β = 0.01.
**Concept:** Af = A/(1+Aβ); feedback factor β is positive for negative feedback.
**Twist:** Af = 20 with A = 100 → β = 0.04. Distortion reduction factor = (1+Aβ) = 2 here.

**Q26 (TSNPDCL-2022):** Match the oscillators with their examples — (A) Tuned circuit, (B) Negative resistance, (C) RC, (D) Crystal; (i) Wien bridge, (ii) Colpitts, (iii) Tunnel diode, (iv) Hartley, (v) Piezo-electric.
(a) (A)-(iv); (B)-(i); (C)-(iii); (D)-(v) (b) (A)-(ii); (B)-(v); (C)-(i); (D)-(iv) (c) (A)-(iv); (B)-(iii); (C)-(i); (D)-(v) (d) (A)-(ii); (B)-(iii); (C)-(iv); (D)-(v)
**Ans: (c)** — Tuned→Hartley(iv); Negative resistance→Tunnel diode(iii); RC→Wien bridge(i); Crystal→Piezo-electric(v).
**Concept:** Oscillator classification: LC tuned (Hartley/Colpitts), negative resistance (tunnel diode), RC (Wien/phase-shift), crystal (piezoelectric, highest stability).
**Twist:** Colpitts = 2C + 1L (capacitor tap); Hartley = 2L + 1C (inductor tap). Crystal → best frequency stability.

**Q27 (TSPSC-AEE-23):** Find the type of feedback in the circuit (1 kΩ from Vin to inverting input, 1 kΩ feedback to inverting input, Vout at output, non-inverting grounded/input).
(a) Shunt–shunt (b) Series–series (c) Series–shunt (d) Shunt–series
**Ans: (c)** — Output voltage is sampled (voltage/shunt sampling at output) and mixed in series at the input → series–shunt (voltage-series) feedback.
**Concept:** Inverting op-amp amp → voltage-shunt (shunt-shunt); non-inverting amp → series-shunt (voltage-series).
**Twist:** Feedback taken from emitter (current sensing) → series–series (current-series). Feedback to inverting node → shunt–shunt (voltage-shunt).

**Q28 (TSSPDCL-AE-2023):** Pick the wrong statement:
(a) Oscillator circuits employ positive feedback (b) The feedback network of a Hartley oscillator contains two inductors and one capacitor (c) The feedback network of a Colpitts oscillator contains two inductors and two capacitors (d) The minimum gain of the amplifier must be 3 in case of a Wien-bridge oscillator
**Ans: (c)** — Colpitts uses two capacitors and ONE inductor (the reverse of the statement).
**Concept:** Colpitts = 2C + 1L (voltage divider on capacitor); Hartley = 2L + 1C; Wien bridge requires gain ≥ 3.
**Twist:** Minimum gain for Wien bridge = 3; for phase-shift oscillator = 29.

**Q29 (TSSPDCL-AE-2023):** From the following statements — P: Schmitt trigger accepts a slow-changing input and produces a rapid (oscillation-free) transition at the output. Q: 555 IC timer can be used as a free-running oscillator.
(a) P and Q are not correct (b) P is correct and Q is not correct (c) P is not correct and Q is correct (d) P and Q are correct
**Ans: (d)** — Both statements are correct.
**Concept:** Schmitt trigger (positive feedback/hysteresis) sharpens slow signals; 555 in astable mode = free-running oscillator.
**Twist:** Schmitt trigger → adds hysteresis → noise immunity. 555 in monostable mode → NOT free-running (one-shot).

> Total: 174 questions annotated.

---

# 📋 FORMULA SUMMARY — Exam-Day Sheet (Analog)

## 1. Diode Circuits
- Ideal diode: Vγ = 0 · **Si ≈ 0.7 V · Ge ≈ 0.3 V**
- PIV: **bridge = Vm · center-tap = 2Vm**
- Zener: V constant in breakdown (regulator) · clipper vs clamper

## 2. BJT, JFET & MOSFET
- **gm(BJT) = Ic/Vt ≈ 40·Ic** · **gm0(JFET) = 2·Idss/|Vp|**
- JFET: Id = Idss(1 − Vgs/Vp)² · MOSFET saturation: Id = ½Kn(Vgs−Vt)²
- CE amp: **Av = −gm·Rc** · CC follower: Av ≈ 1, high Zin

## 3. Op-Amp
- **Inverting: Av = −Rf/Ri** · **Non-inverting: Av = 1 + Rf/Ri**
- Buffer: Av = 1, Zi = ∞, Zo = 0 · CMRR = Ad/Ac · slew rate = dVo/dt

## 4. Miscellaneous
- **Barkhausen: |Aβ| = 1, ∠Aβ = 0° (360°)**
- RC phase-shift: f = 1/(2π√6·RC) · Wien: f = 1/(2πRC) · Crystal: best stability
- 555 astable: T = 0.693(R1+2R2)C
- Power amps ηmax: **A = 25% · B = 78.5%** · C > 78.5%
