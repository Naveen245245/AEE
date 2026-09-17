# AP AEE — EXAM MASTER: Formulas + Derivations + Dot-Connections

**How to use (exam-day mindset):**
- You will NOT derive in the exam. You **recognize → plug → answer** (~100 s/question).
- Every formula has a **Derivation anchor** (the 20-second seed you rebuild from if you blank).
- **→ Dots** = cross-subject connections (the examiner's favourite habit).

---

## ⚡ 20-SECOND REBUILD KIT (if you remember NOTHING else)

| Topic | Recall this |
|---|---|
| Transformer EMF | **E = 4.44 f N Φm** (4.44 = 2π/√2) |
| Rectifier Vdc | 1-Φ full **(2Vm/π)cosα** · semi **(Vm/π)(1+cosα)** · 3-Φ full **(3√3/π)Vm·cosα** |
| Chopper Vo | buck **D·Vs** · boost **Vs/(1−D)** · buck-boost **−D·Vs/(1−D)** |
| DC machine | **E = PΦZN/60A** · **T = PΦZIa/2πA** · **N ∝ (V−IaRa)/Φ** |
| Induction motor | **Ns = 120f/P** · s = (Ns−N)/Ns · max T at **s = R2/X2** |
| Synchronous | **f = PN/120** · **P = (EV/Xs)·sinδ** |
| 3-Φ power | **P = √3·VL·IL·cosφ** |
| Per-unit | **Zpu = Z_act·MVAbase/kVbase²** |
| Faults | **LG: 3E/(Z1+Z2+Z0)** · **LL: √3E/(Z1+Z2)** · **3-Φ: E/Z1** |
| Closed loop | **CLTF = G/(1+GH)** |
| 2nd-order | **%MP = e^(−ζπ/√(1−ζ²)) ×100** |
| Op-amp | inv **−Rf/Ri** · non-inv **1+Rf/Ri** |
| ADC | flash **2ⁿ−1 comparators** · resolution **Vref/2ⁿ** |

---

## 1. NETWORKS / CIRCUITS

| Formula | Derivation anchor | → Dots |
|---|---|---|
| Thevenin: Vth, Rth · Norton: In = Vth/Rth | Open-circuit + deactivate sources | **→ Fault analysis: source behind Z** |
| Max power: RL = Rth, Pmax = Vth²/4Rth | dP/dRL = 0 | → Measurements (loading) |
| Star↔delta: RΔ = 3Rγ | Equal resistance between terminals | → 3-Φ machines/loads |
| RC: τ = RC · RL: τ = L/R | v(t) = V(1−e^(−t/τ)) | → IM/DC transient |
| Series resonance: ω0 = 1/√(LC), Q = ω0L/R | XL = XC | → Q-meter |
| P = VIcosφ, Q = VIsinφ, S = VI | Power triangle | → PS, PF correction |
| ABCD 2-port | V1 = AV2 − BI2 etc. | **→ Transmission lines** |

---

## 2. ELECTRICAL MACHINES (biggest marks)

### Transformers
| Formula | Derivation anchor | → Dots |
|---|---|---|
| **E = 4.44 f N Φm** | Faraday: E_rms = (2π/√2)fNΦm | → Sync gen, DC gen (same seed) |
| K = N2/N1 = V2/V1 = I1/I2 | Same flux links both windings | |
| R01 = R1 + K²R2 (to primary) | I2 referred: I2' = I2/K | → Equivalent ckt → per-unit |
| %R = I(R01cosφ ± X01sinφ)/V1 ×100 | Phasor drop on R01+jX01 | |
| **η max at x = √(Pi/Pcu)** | dη/dx = 0 → Pi = x²Pcu | |
| All-day η = energy out/in (24 h) | Energy-weighted | |
| Auto saving = (1 − 1/a)×100% | Copper ∝ I²; compare windings | |
| OC → Pi · SC → Pcu | No-load vs short-circuit | → Sequence networks |

### DC Machines
| Formula | Derivation anchor | → Dots |
|---|---|---|
| **E = PΦZN/60A** | Flux cut rate (Faraday) | Same EMF seed as transformer |
| **T = PΦZIa/2πA** | P = EIa = Tω, ω = 2πN/60 | |
| Eb = V − IaRa · **N ∝ Eb/Φ** | KVL on armature | → Drive speed control |
| Shunt: ~constant speed · Series: high T, runaway | T ∝ ΦIa | → PE chopper/rectifier drives |

### Induction Machines
| Formula | Derivation anchor | → Dots |
|---|---|---|
| **Ns = 120f/P** · s = (Ns−N)/Ns | Rotating field speed | → Sync freq f = PN/120 |
| Rotor freq = s·f | Slip rotates relative to field | |
| **T ∝ sR2/(R2²+s²X2²)** | Equivalent ckt, rotor copper loss | → PS (per-unit ckt) |
| **Max T at s = R2/X2** | dT/ds = 0 | |
| Starting torque ∝ R2 (up to a point) | s=1 in torque eq | |
| V/f control → constant flux | Φ ∝ V/f | → Inverter drives |

### Synchronous Machines
| Formula | Derivation anchor | → Dots |
|---|---|---|
| **f = PN/120** | Poles & rotor speed | Inverse of Ns |
| E = 4.44 f N Φ (per phase) | Faraday | Same EMF seed |
| **VR = (E − V)/V ×100** | Compare generated vs terminal | |
| **P = (EV/Xs)sinδ** | Phasor with synchronous reactance | → Power-angle (stability) |
| V-curves: under-excited lag, over-excited lead | Armature reaction | → PF correction |
| Hunting → damper winding | Oscillation damping | |

---

## 3. POWER SYSTEMS

| Formula | Derivation anchor | → Dots |
|---|---|---|
| ABCD medium π: A=D=1+YZ/2, B=Z, C=Y(1+YZ/4) | 2-port chain | **→ Networks ABCD** |
| Long line: A=cosh γl, B=Zc·sinh γl | Distributed ckt, γ = √(YZ) | |
| **Sag S = wL²/(8T)** | Parabola y = wx²/2T at mid | |
| String eff: η = V_str/(n·V_bottom) | Capacitance division: V2 = V1(1+k) | |
| L = 0.2 ln(GMD/GMR) mH/km | Flux linkage | → Machines leakage |
| C = 2πε0/ln(GMD/r) | Gauss | |
| Corona ∝ (V−Vd)²(f+25) | Ionization | |
| **Ferranti: Vr>Vs no-load → shunt reactor** | Charging current | |
| **Zc = √(L/C) · SIL = V²/Zc** | Lossless line | Overhead ≈400Ω, cable ≈50Ω |
| **Zpu_new = Zpu_old(V_old/V_new)²(MVA_new/MVA_old)** | Base change | → Machines |
| Symm comp: a = 1∠120° | Operator | |
| **LG: 3E/(Z1+Z2+Z0)** · LL: √3E/(Z1+Z2) · 3Φ: E/Z1 | Seq networks in series/parallel | **→ Thevenin from circuits** |
| SC MVA = base MVA/Zpu | 1/Z | |
| Swing: M(d²δ/dt²) = Pa, M = GH/180f | T = Jα on rotor | → Sync power-angle |
| NR Jacobian: (2N−Npv−2) | Unknowns | |
| ELD: IC1 = IC2 = λ | Lagrange | |
| **PSM = If/(CT ratio×PS)** | Relay pickup | |
| **IDMT t = 0.14·TMS/(PSM^0.02 − 1)** | IEC curve | |
| Breaking MVA = √3·VL·Ibr · **Making = 2.55×BC** | Asymmetry (1.8×√2) | |

---

## 4. POWER ELECTRONICS

| Formula | Derivation anchor | → Dots |
|---|---|---|
| **1-Φ full: (2Vm/π)cosα** | (1/π)∫Vm sinθ dθ over [α, α+π] | → DC drive N |
| **1-Φ semi: (Vm/π)(1+cosα)** | ∫ over [α, π] (FW diode) | |
| **3-Φ full: (3√3/π)Vm·cosα** | 6 windows of line-line, ∫ | Vm = peak phase |
| PIV: bridge Vm · mid-point 2Vm · 3-Φ √3Vm | Reverse max voltage | |
| I_rms per SCR (3-Φ) = Io/√3 | Conducts 120° = 1/3 | |
| Source L drop: ΔV = 3ωLs·Id/π (3-Φ) | Overlap angle | |
| Ripple freq: 1-Φ full 2f · 3-Φ full 6f | Pulse number p | |
| Buck D·Vs · Boost Vs/(1−D) · Buck-boost −DVs/(1−D) | **Inductor volt-sec balance** | → DC drive |
| **ΔIL = Vs·D/(f·L), max at D=0.5** | Volt-sec during on-time | freq↑ → ripple↓ |
| 1-Φ inverter: V1 peak 4Vs/π, rms (2√2/π)Vs | **Fourier of square wave** | → VSI/CSI |
| 3-Φ 180°: V_LL = Vs · 120°: V_LL = √3Vs/2 | Switching states | |
| Kill nth harmonic → width 2π/n | Fourier | |
| AC controller: Vo_rms = Vs√[(π−α+sin2α/2)/π] | ∫V² over window | |
| Cycloconverter: f_out < f_in | | |
| di/dt: L = V/(di/dt) · dv/dt: RC snubber | dV/dt = V/RC | |
| PD = (TJ − TA)/θJA | Thermal ckt | |

---

## 5. CONTROL SYSTEMS

| Formula | Derivation anchor | → Dots |
|---|---|---|
| **CLTF = G/(1+GH)** · char eq 1+GH=0 | Feedback summation | → Regulators |
| Mason: T = ΣPkΔk/Δ | SFG algebra | |
| **%MP = e^(−ζπ/√(1−ζ²))** · tp = π/ωd · ts = 4/(ζωn) | Step response envelope | ζ↔ Mr |
| Kp = lim G · Kv = lim sG · Ka = lim s²G | Error TF at s→0 | |
| **Routh: first column > 0** | Array | → Stability |
| GM = 1/|G| at −180° · PM = 180°+∠G at |G|=1 | Bode/Nyquist | → Drives stability |
| Nyquist: N = P − Z | Mapping | |
| Lead → ↑PM · Lag → ↓ess · PD ↑damping · PI ↓ess | Compensator design | |
| ẋ = Ax+Bu · y = Cx+Du | State equations | |
| **Controllability: rank[B AB A²B]=n · Observability: rank[C; CA; CA²]=n** | Grammians | |

---

## 6. ANALOG + DIGITAL + MEASUREMENTS + UTILIZATION

| Topic | Formula | Anchor / Dot |
|---|---|---|
| BJT | gm = Ic/Vt ≈ **40·Ic** | CE Av = −gm·Rc |
| JFET | gm0 = **2·Idss/|Vp|** | Id = Idss(1−Vgs/Vp)² |
| Op-amp | inv −Rf/Ri · non-inv 1+Rf/Ri | Virtual ground |
| Oscillator | **Barkhausen: |Aβ|=1, ∠0°** · RC f = 1/(2π√6·RC) | |
| 555 astable | T = 0.693(R1+2R2)C | |
| Power amps | B ηmax = 78.5% | |
| Number system | **2's comp = invert+1** · n-bit range | Hex = 4-bit groups |
| FF/counter | **JK J=K=1 toggle** · n FF → mod 2ⁿ | |
| ADC | **Flash 2ⁿ−1 comparators** · resolution **Vref/2ⁿ** · err ±LSB/2 | → Digital multimeter |
| PMMC | **T = NBAI (dc only)** | MI: ac/dc |
| Ammeter/Voltmeter | Rsh = Rm/(m−1) · Rse = Rm(m−1) | |
| Two-wattmeter | **tanφ = √3(W1−W2)/(W1+W2)** · P = W1+W2 | → 3-Φ power |
| Bridges | Kelvin=low R · Schering=C/DF · Maxwell=L · Hay=high-Q | |
| Strain gauge | GF = (ΔR/R)/ε ≈ 2 | |
| PF correction | **kVAR = P(tanφ1 − tanφ2)** | → Power triangle |

---

## 🧵 THE DOT MAP (cross-subject, all in one picture)

1. **Faraday seed:** E = 4.44fNΦm runs through **transformer → synchronous gen → DC gen**. One idea, three subjects.
2. **Thevenin → faults:** fault current = E behind **Z1** (Thevenin of the system).
3. **Transformer equivalent ckt → per-unit → sequence networks → faults** — one chain.
4. **P = Tω everywhere:** DC motor, IM, SM power-angle — torque/speed is one idea.
5. **Rectifier/chopper → DC drive speed:** Vdc → Eb = Vt−IaRa → N. Inverter → V/f → IM speed.
6. **ABCD 2-port (Networks) → transmission line (PS).**
7. **Power triangle (Circuits) → PF correction (Utilization) → two-wattmeter (Measurements).**
8. **Routh/Root-locus/Bode (Control) ↔ damping & stability of drives.**
9. **Resonance (Circuits) ↔ Q-meter (Measurements).**
10. **ADC/DAC (Digital) ↔ electronic instruments (Measurements).**
11. **Swing equation (PS) ↔ SM power-angle (Machines).**

---

## 🛠 DERIVATIONS YOU SHOULD OWN (so you never derive in the exam)

Pre-derived results — internalize the anchor line; if asked, write the result straight away:

1. **TF EMF:** E_rms = (2π/√2)·f·N·Φm = **4.44 f N Φm**.
2. **Max η:** Pcu at load = x²Pcu; set Pi = x²Pcu → **x = √(Pi/Pcu)**.
3. **1-Φ full rectifier:** (1/π)∫Vm sinθ = **(2Vm/π)cosα**.
4. **Boost:** Vs·D·T = Vo(1−D)T → **Vo = Vs/(1−D)**. Buck-boost similarly → **−DVs/(1−D)**.
5. **Inverter fundamental:** a1 = (4/π)Vs → V1,rms = (4Vs/π)/√2 = **(2√2/π)Vs**.
6. **DC EMF:** E = PΦZN/60A; **DC torque:** T = PΦZIa/2πA (from P = EIa = Tω).
7. **IM max-torque slip:** dT/ds = 0 → **s = R2/X2**.
8. **SM power:** P = (EV/Xs)sinδ.
9. **Sag:** S = wL²/(8T).
10. **String eff:** V2 = V1(1 + Cg/C); η = V_str/(n·V_bottom).
11. **LG fault:** Z0,Z1,Z2 in series → If = **3E/(Z1+Z2+Z0)**.
12. **Swing eq:** M(d²δ/dt²) = Pa with **M = GH/(180f)**.
13. **%MP:** at tp, envelope e^(−ζωnt) → **e^(−ζπ/√(1−ζ²))×100**.
14. **Two-wattmeter:** tanφ = √3(W1−W2)/(W1+W2).
15. **ADC:** Vstep = Vref/2ⁿ; **quant error = ±Vref/2^(n+1)**.
16. **Ripple:** ΔIL = Vs·D/(f·L) (on-time volt-sec).

---

**Final exam-day rule:** no negative marking → **attempt every question**. Recognition beats recall. The rebuild kit + dot map is all you need to hold in your head; everything else lives in the per-subject formula sheets at the end of each `pyq-notes/*.md` file.
