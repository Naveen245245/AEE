---
title: AP AEE Electrical - Core Formulas One-Page Sheet
description: All essential electrical engineering formulas for AP AEE exam preparation
exam: AP AEE Electrical
marks: 70 marks
lastUpdated: 2026-07-19
---

# AP AEE Electrical — Core Formulas One-Page Sheet
> All essential formulas with question-pattern mapping. Paste on your wall!

---

## 1. TRANSFORMER

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| EMF Equation | E = 4.44 × f × N × Φm | **Very High freq** — given V, f, N find Φm or vice-versa |
| Turns Ratio | K = N₂/N₁ = V₂/V₁ = I₁/I₂ | K>1 step-up, K<1 step-down |
| EMF per turn | E_turn = V₁/N₁ = 4.44 × f × Φm | Direct: given V and N find turns |
| Equivalent circuit | R₀ = V₁/I₀cosφ₀, X₀ = V₁/I₀sinφ₀ | OC test → R₀, X₀ (shunt branch) on LV side |
| Series params | R₀₁ = P_sc / I_sc², X₀₁ = Z₀₁ × sinφ_sc | SC test → referred to HV side |
| Efficiency | η = (x·S·cosφ) / (x·S·cosφ + Pi + x²Pcu) | x = load fraction |
| Max η condition | Pi = x²Pcu → **x = √(Pi/Pcu)** | PYQ: given Pi, Pcu find load at max η |
| Voltage Reg | %R = (IR cosφ ± IX sinφ) / V × 100 | Lagging +, Leading − ; leading pf → reg can be negative |
| Auto-transformer | Savings = (1 − 1/a) × 100%, a = V₁/V₂ | **High freq** — K>1 step-down saves more |
| Auto-transformer rating | kVA_auto = kVA_tw × (a/(a−1)) | For 2:1 tw as auto → 3× kVA rating |
| Inductive fraction | Fraction transferred inductively = (V₁−V₂)/V₁ = (a−1)/a | |
| Hysteresis loss | Ph ∝ f | Eddy current loss Pe ∝ f² — **PYQ freq: very high** |
| Copper loss scaling | Pcu_actual = x² × Pcu_fl | Half-load copper loss = Pcu_fl/4 |
| Back-to-back test | Total input = 2Pi + Pcu | Used for heat run (Sumpner's test) |
| All-day efficiency | η_all-day = Output energy / Input energy (24h cycle) | Distribution transformers |
| Parallel operation | Conditions: Same polarity, vector group, turns ratio, %Z | Load ∝ kVA rating if equal puZ |
| Scott connection | Main: K; Teaser: 2K/√3 | 3-phase to 2-phase conversion |
| 3-φ transformer | Delta side: V_L = V_Ph; Y side: V_L = √3 × V_Ph | Y-Δ: line voltage ratio = a×√3 |
| Delta-Delta one phase out | Output = 57.7% of rated (√3/3 × 100%) | |
| Auto power transfer | Both conduction AND induction | Not just one |

## 2. DC MACHINES

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| EMF | E = (P × Φ × N × Z) / (60 × A) | **Very High freq** — given P, Φ, N, Z, A find E |
| Torque | T = (P × Φ × Z × Ia) / (2π × A) | Shunt: T ∝ Ia; Series: T ∝ Ia² |
| Speed | N = (V − Ia×Ra) / (K×Φ) | N ∝ V/Φ for shunt |
| Back EMF | Eb = V − Ia×Ra | Given V, Ra, Ia find Eb |
| Armature paths | **Lap: A = P; Wave: A = 2** | Lap: Ia/path = Ia/P; Wave: Ia/path = Ia/2 |
| Starting current | Ia_start = V / Ra | Very high — needs starter |
| Swinburne's test | Constant loss = Input at no-load | η at any load from this |
| Max efficiency | Fixed loss = Variable loss → Pi = Pcu | |
| Compounding | Over: V rises; Flat: V constant; Under: V falls slightly; Differential: V falls sharply | |
| Critical field resistance | Slope of OCC at origin | Self-excited generator builds voltage if Rf < Rcrit |
| Armature reaction | Distorts flux (demagnetizing at leading pole tip) | Effect increases with load |
| Commutator function | Converts AC in armature to DC externally | Mechanical rectifier |
| Interpoles | Same polarity as main pole AHEAD in rotation (generator) | Improves commutation |
| Hopkinson's test | Efficiency = 1 − (losses/input) using two identical machines | |
| Plugging | Armature reversed; braking torque = 2 × running torque | |
| Dynamic braking | Armature connected to resistor; T ∝ speed | |
| DC motor selection | Series: traction (high starting T); Shunt: constant speed; Compound: moderate starting | |

---

## 3. INDUCTION MOTOR

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| Sync Speed | Ns = 120f / P | India: 50 Hz; 4-pole → 1500 rpm |
| Slip | s = (Ns − N) / Ns | Always 0 < s < 1 |
| Rotor EMF freq | fr = s × f | |
| Torque (approx) | T ∝ s·R₂ / (R₂² + s²X₂²) | |
| Max torque condition | **s_max = R₂ / (X₁+X₂)** — Independent of R₁ | |
| Starting torque (DOL) | 100% V, Ts ∝ V² | |
| Star-Delta start | 1/√3 V, 1/3 torque, 1/3 current | |
| Rotating field | Synchronous, at Ns | |
| Rotor copper loss | Pcu₂ = s × P₂ | Air-gap power P₂ = (1−s)×Pag |
| Efficiency | η ≈ 1 − (losses/input) | |

---

## 4. SYNCHRONOUS MACHINE

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| EMF | E = 4.44 × f × N × Φ × Kw | Same form as transformer |
| Frequency | **f = P × N / 120** | Given N and f find P |
| Voltage Reg | %VR = (E − V)/V × 100 | Lagging pf: positive; Leading pf: negative |
| Short-circuit ratio | SCR = 1 / Xs_pu | Given Xs pu, SCR = 1/Xs |
| Power angle | **P = (EV/Xs) sin δ** | For round-rotor; for salient: P = (EV/Xd)sinδ + (EV/2)(1/Xq − 1/Xd)sin2δ |
| Potier method | Air-gap line − OCC = leakage drop = Ia×Xa | |
| V-curves | Over-excited → leading pf; Under-excited → lagging pf | Synchronous motor used for pf correction |
| Damper bars | Provide starting torque (induction motor action) | |
| Hunting | Super-synchronous speed → damper bars act as induction generator | |
| Synchronizing | Equal voltage, same phase sequence, same frequency | |
| Brushless exciter | Rotating rectifier — no slip rings | |

---

## 5. TRANSMISSION LINES

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| Per Unit | Z_base = V² / S | Z_pu = Z_actual / Z_base |
| Base change | **Z_pu_new = Z_pu_old × (MVA_new/MVA_old) × (kV_old/kV_new)²** | Very High freq |
| Short line | VS = VR + IZ | Only series impedance |
| Medium T-equivalent | A = D = 1 + YZ/2; B = Z(1+YZ/4); C = Y | |
| Medium π-equivalent | A = D = 1 + YZ/2; B = Z; C = Y(1+YZ/4) | |
| Surge impedance | **Z₀ = √(L/C)** | |
| Surge impedance loading | **SIL = V²_LL / Z₀** | MW loading at unity pf |
| Ferranti effect | No-load: VS < VR (receiving end voltage rises) | Due to line capacitance |
| Voltage regulation | %R = (IR cosφ ± IX sinφ) / VR × 100 | Positive for lagging |
| ABCD: Short line | A = D = 1; B = Z; C = 0 | |
| ABCD: Medium T | A = D = 1 + YZ/2; B = Z; C = Y | |
| ABCD: Medium π | A = D = 1 + YZ/2; B = Z; C = Y(1+YZ/4) | |
| Power flow | P = (EV/X) sin δ | |
| Line inductance | L = 2×10⁻⁷ × ln(D/r') H/km | Self GMD method |
| Capacitance | C = 2πε₀ / ln(D/r) F/km | |
| Skin effect | R_ac > R_dc; more at high freq, small diameter | |
| Proximity effect | Increases effective reactance | |
| Sag equation | Parabola approximation: Sag = w×x²/(2T) | |
| Corona loss | P ∝ f², V², 1/r | More in humid weather |
| String efficiency | η_string = (applied voltage / n discs) / (disc puncture voltage) × 100 | |
| Bundled conductors | Reduce corona, increase capacitance |
| Long line (exact) | A=D=cosh(γl); B=Z₀ sinh(γl); C=sinh(γl)/Z₀ | >250 km; hyperbolic |
| Propagation constant | γ = √(zy) per km | γ = α + jβ |
| Cable capacitance | C = 2πε₀εr / ln(r₂/r₁) F/m | r₁=cond, r₂=sheath radius |
| Cable grading | Capacitance/intersheath grading | Reduces stress at conductor |
| Dielectric loss | P = V² × ω × C × tanδ | Cable insulation test | |

---

## 6. FAULT ANALYSIS

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| Sym comp operator | a = 1∠120° = −½ + j√3/2; **a + a² + 1 = 0** | |
| Sequence currents | I₀ = (Ia+Ib+Ic)/3; I₁ = (Ia+aIb+a²Ic)/3; I₂ = (Ia+a²Ib+aIc)/3 | |
| 3-φ Fault | **If = V / Z₁** | Use Z₁ only |
| L-G Fault | **If = 3V / (Z₀ + Z₁ + Z₂)** | All three sequences |
| L-L Fault | **If = j√3 V / (Z₁ + Z₂)** → If = 1.732V/(Z₁+Z₂) | No Z₀ |
| L-L-G Fault | If = 3V / (Z₀ + 2Z₁) | |
| Sequence networks | Positive: Thevenin; Negative: Z₂ ≈ Z₁; Zero: 3× grounded path | |
| Zero-seq not in LL | Zero-seq only when neutral path exists | |
| Short-circuit MVA | **SC MVA = MVA_base / Z_pu** | |
| Rating basis | Circuit breaker rated at LLLG (worst case) | |

---

## 7. POWER SYSTEM STABILITY

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| Swing equation | (2H/f) × d²δ/dt² = P_a = P_m − P_e | |
| Inertia constant | **H (MJ/MVA) = KE stored / MVA rating** | Given MVA, H → MJ; 100 MVA, H=4 → 400 MJ |
| Angular acceleration | α = (360 × f / P) × (P_m − P_e) elec deg/s² | |
| Equal area criterion | Area A₁ = Area A₂ for critical fault clearing | Critical clearing angle |
| Critical clearing angle | δ_cc = cos⁻¹[...P_m, P_max, δ₀] | |
| Synchronizing power | **P_synch = (EV/X) cos δ** | Derivative of power angle curve |
| Transient stability limit | Always < steady-state limit | |
| Improving stability | Series capacitors (increase X), fast breakers, high-speed relaying | |
| Two groups not swinging | M_eq = M1M2/(M1+M2) | |

## 7B. NEUTRAL EARTHING & INSULATORS

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| Solid grounding | Z0 approx 0 -> high SLG fault | Most common for HV systems |
| Resistance grounding | Z0 = Zgen,0 + 3Rn | Limits SLG fault; used in generators |
| Ungrounded system | Z0 = inf -> no SLG path | Zero-seq current only capacitive |
| Peterson coil (ASC) | L tuned to cancel line C | Arc suppression for SLG in EHV |
| String efficiency | eta = V / (n x Vn) x 100% | Worse for more discs without grading |
| Improve string eff. | Longer cross-arms, grading rings, static shielding | Uniform voltage distribution |
| **PF correction** | **Qc = P(tanphi1 - tanphi2)** | Given P and desired pf improvement |
| Capacitor bank | Star or delta (LV: delta) | With discharge resistors (1-3 min) |

---


## 8. POWER ELECTRONICS

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| 1-φ Semi-converter | **Vdc = Vm(1+cosα) / π** | Continuous R-L load |
| 1-φ Full converter | **Vdc = 2Vm cosα / π** | Continuous current |
| Ripple factor | γ = √(Irms²−Idc²) / Idc | |
| 3-φ fully controlled | **Vdc = (3Vm cosα) / π** | For α < 90° (rectifier) |
| 3-φ diode bridge | Vdc = (3√3 × √2 × V_Ph) / π ≈ 2.34 V_Ph | |
| Chopper Buck | **V₀ = D × Vs** | D = T_on/T; step down |
| Chopper Boost | **V₀ = Vs / (1−D)** | Step up |
| Chopper ripple max | At D = 0.5 | |
| Inverter fundamental | **V₁ = 4Vs / (nπ)** | Square wave, n = number of pulses |
| Chopper duty ratio | D = control voltage / sawtooth amplitude | |
| PIV (1-φ bridge) | PIV = Vm (each device) | |
| PIV (center-tap) | PIV = 2Vm | |
| Displacement pf | cos(α) for fully controlled rectifier | |
| Commutation overlap | Reduces output voltage; Vdc_comp = Vdc − (3ωL_s/π)×Idc | |
| SCR turn-on methods | Gate pulse (normal), forward VBO, dv/dt, light, temp | dv/dt false trigger → RC snubber |
| SCR commutation (Class A) | Resonant LC forces current to zero | For DC circuits (natural for AC) |
| SCR commutation (Class B) | Auxiliary SCR + LC reverse biases main | Inverter circuits |
| SCR commutation (Class D) | AC line voltage reverses → natural turn-off | Phase-controlled rectifiers |
| Cycloconverter | AC → AC (no DC link); fo < fi | Output freq < 1/3 of input freq |
| SVPWM (Space Vector) | V1,max = Vdc/√3 (15% > SPWM) | Modern VFDs; better DC bus utilization | |

---

## 9. CONTROL SYSTEMS

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| CLTF | **G_cl = G / (1+GH)** | Unity feedback |
| Characteristic eq | 1 + GH = 0 | Apply Routh-Hurwitz |
| Routh-Hurwitz | All first-column elements > 0 → stable | **Very High freq** |
| Error constants | Kp = lim G(s); **Kv = lim sG(s)**; Ka = lim s²G(s) | |
| Type 0 system | Step → ess = 1/(1+Kp) | |
| Type 1 system | Ramp → ess = 1/Kv | |
| Type 2 system | Parabolic → ess = 1/Ka | |
| 2nd order natural freq | ωn from denominator s² + 2ζωn s + ωn² | **Very High freq** |
| Damping ratio | **ζ = b / (2√k)** where denominator = s² + 2ζωns + ωn² | |
| Damped frequency | ωd = ωn × √(1−ζ²) | |
| Peak time | **Tp = π / (ωn×√(1−ζ²))** | |
| Settling time (2%) | **ts = 4 / (ζωn)** | |
| Settling time (5%) | ts = 4 / (ζωn) × 0.75 (actually 3/ζωn) | Check: 5% uses 3/ζωn |
| Overshoot | **Mp = exp(−ζπ/√(1−ζ²))** | In %: 100 × exp(...) |
| GM / PM | GM > 6 dB, PM > 30° good margins | |
| Resonant peak | **Mr = 1 / (2ζ√(1−ζ²))** | |
| Resonant frequency | ωr = ωn√(1−2ζ²) | |
| Bode: 20 log G(s) | Integral: −20 dB/dec; Double integral: −40 dB/dec | |
| Polar plot | Encirclement of −1+j0 = P − Z | Nyquist stability |
| Root locus | Branch from poles, go to zeros; asymptotes at infinity | |
| Angle of departure | 180° − Σangles from other poles + Σangles to zeros | |
| Mason's gain formula | T = (1/Δ) × Σ(Pk × Δk) | Δ = 1 − ΣLi + ΣLiLj − ... |
| State-space (A matrix) | ẋ = Ax + Bu, y = Cx + Du | Stable if eigenvalues of A in LHP |
| Controllability | rank[B, AB, A²B, ..., A^(n−1)B] = n | Full rank = all states controllable |
| Observability | rank[C, CA, CA², ..., CA^(n−1)] = n | Full rank = all states observable |
| Lag compensator | Gc(s) = (1+sT)/(1+sαT), α>1 | Pole < zero; reduces error, lowers BW |
| Lead compensator | Gc(s) = (1+sT)/(1+sαT), α<1 | Zero < pole; increases BW, faster |
| PID controller | u = Kp·e + Ki·∫e·dt + Kd·de/dt | P: speed; I: eliminate error; D: damp |

---

## 10. CIRCUITS

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| Thevenin | **Vth = Voc (open-circuit); Rth = Vth / Isc** | |
| Norton | IN = Isc; RN = Vth / Isc | |
| Max power (DC) | RL = Rth → Pmax = Vth²/(4Rth) | |
| Max power (AC) | ZL = Zth* (conjugate match) | |
| Resonance | **f₀ = 1 / (2π√LC)** | |
| Series Q-factor | **Q = ω₀L / R = 1/(ω₀CR)** | |
| Parallel Q-factor | Q = R / (ω₀L) = ω₀RC | |
| Bandwidth | BW = f₀ / Q | |
| At resonance | Z is minimum (series) or maximum (parallel) | |
| Transformer equivalent | All params referred to one side | |
| Dependent sources | Must keep in Thevenin/Norton calculations | |
| Millman's theorem | Veq = sum(Vi/Ri)/sum(1/Ri) | Parallel branches with different sources |
| Reciprocity theorem | V in branch A → I in branch B; same V in B → same I in A | Linear bilateral networks only |
| Dot convention (coupled) | M = k√(L1L2); dot = same polarity | k = coupling coefficient (0 to 1) |

---

## 11. THREE PHASE POWER

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| Total power | **P = √3 × V_L × I_L × cosφ** | Same for Y and Δ |
| Two wattmeter | W₁ = V_L I_L cos(30°−φ); W₂ = V_L I_L cos(30°+φ) | |
| Power factor | **tanφ = √3(W₁−W₂)/(W₁+W₂)** | **Very High freq** |
| W₁+W₂ = total P | When φ < 60°, both positive | |
| Reactive power | Q = √3 × V_L × I_L × sinφ | |
| For balanced Y | I_L = I_Ph; V_L = √3 × V_Ph | |
| For balanced Δ | V_L = V_Ph; I_L = √3 × I_Ph | |

---

## 12. MEASUREMENTS & INSTRUMENTS

| Topic | Formula | Memory / PYQ Pattern |
|-------|---------|----------------------|
| PMMC torque | T ∝ I (deflecting); T_c = K × θ (controlling) | |
| Moving iron | T ∝ I² (average squared current) | Works for AC and DC |
| Shunt (ammeter) | **R_sh = Rm / (m−1)**, m = multiplying factor = I/Im | **Very High freq** |
| Series multiplier | **Rs = (V − Vm) / Im** for voltmeter | **High freq** |
| Multiplier for DC | R = (V − Im×Rm)/Im | |
| Kelvin double bridge | For low resistance measurement | |
| Wheatstone bridge | R₁/R₂ = R₃/R₄ | Balance condition |
| Maxwell bridge | Lx = R₂R₃C₁; Rx = R₂R₃/R₁ | For inductance measurement |
| Schering bridge | C₄ = C₁R₃/R₄; used for capacitor dissipation | |
| Two-wattmeter method | W₁ = √3 V_L I_L cos(30°−φ); W₂ = √3 V_L I_L cos(30°+φ) | |
| tanφ from wattmeters | tanφ = √3(W₁−W₂)/(W₁+W₂) | **Very High freq** |
| Energy meter | K = revs per kWh | |
| CT ratio error | ε% = (K − Np/Ns)/K × 100% | |
| Current transformer | **Never open-circuit secondary** — dangerous high voltage | |
| Megger | Measures insulation resistance; has hand-cranked DC generator | |
| Power factor meter | Electrodynamic type; works with 3-phase, 2-coil meter | |
| CRO (oscilloscope) | V/div, time/div, trigger | Voltage, period, phase measurement |
| Lissajous figures | For phase & freq measurement | Cycles count = freq ratio |
| Sec (Specific Energy Cons.) | SEC = Energy(Wh) / (tonnes x km) | Electric: 50-80; Diesel: 250-400 Wh/t-km |
| Illumination: Inverse Square | E propto 1/d² | Point source illuminance |
| Illumination: Lambert's Law | E propto cosθ | θ = angle of incidence |
| Op-Amp integrator | Vout = -(1/RC) x integral(Vin)dt | Output proportional to area under Vin |
| Op-Amp differentiator | Vout = -RC x dVin/dt | Sensitive to noise |
| Op-Amp summing amp | Vout = -Rf(V1/R1 + V2/R2 + ...) | Analog adder |

---

## 13. WAVEFORM PARAMETERS

| Topic | Formula | Memory |
|-------|---------|--------|
| Sine RMS | a/√2 = 0.707a | |
| Sine average | 2a/π = 0.637a | |
| Sine form factor | FF = Vrms/Vavg = (π/(2√2)) ≈ 1.11 | |
| Sine crest factor | CF = Vpeak/Vrms = √2 ≈ 1.414 | |
| Half-wave RMS | a/2 = 0.5a | |
| Half-wave FF | π/2 ≈ 1.57 | |
| Square wave RMS | a (same as DC) | FF = 1.0 |
| Triangular RMS | a/√3 | FF = 1.15 |

---

## 14. MAGNETIC CIRCUITS

| Topic | Formula | Memory |
|-------|---------|--------|
| Reluctance | **ℛ = l / (μ₀μr A)** | |
| Ohm's law (magnetic) | Φ = F / ℛ, F = NI (mmf) | |
| Flux density | **B = Φ / A = μ₀μr H** | |
| Flux | Φ = B × A | |
| Hysteresis lag | B lags H | |
| Eddy current loss | **Pe ∝ f² Bm² t²** (t = lamination thickness) | Reduced by laminations |
| Steinmetz law | Pi/hyst = Kh × f × Bm^1.6 × V | |
| Lamination | Thickness 0.35mm or 0.5mm for steel sheets | |
| Mutual inductance | **M = k√(L₁L₂)** | k = coupling coefficient (0 ≤ k ≤ 1) |
| Induced EMF | **e = N × dΦ/dt** (Faraday) | e = M × dI₁/dt for mutual |

---

## 15. ANALOG ELECTRONICS

| Topic | Formula | Memory |
|-------|---------|--------|
| Diode dynamic resistance | **rd = 26mV / Id** (at room temp) | Ge: 26mV; Si: 26mV |
| Knee voltage | Si: 0.7V; Ge: 0.3V | |
| CE amplifier | Av = −β Rc / (rπ + (β+1)Re) ≈ −Rc/Re | |
| Common-emitter current gain | α = β/(β+1); β = α/(1−α) | |
| FET transconductance | gm = Idss × (1−Vgs/Vp)² × (2/|Vp|) | |
| Op-amp inverting | Av = −Rf/R₁ | |
| Op-amp non-inverting | Av = 1 + Rf/R₁ | |
| Op-amp CMRR | CMRR = Ad/Acm | |
| Differential gain | Ad = R₂/R₁ (instrumentation amp) | |
| Instrumentation amp | Vout = (1+2R₁/Rgain) × (V₂−V₁) | |
| Slew rate | SR = dV/dt max; units V/μs | |
| Virtual short | V+ ≈ V− in negative feedback | |
| Virtual ground | At virtual short with one input at ground | |
| 3-terminal regulator | 78XX series — output stable despite input variation | |

---

## 16. DIGITAL CIRCUITS

| Topic | Formula | Memory |
|-------|---------|--------|
| Mod-n counter | n = 2^n_flip-flops | |
| Flash ADC | Comparators = 2^n − 1 for n-bit | |
| Successive approx | Conversion time = n × Tclock | |
| R-2R ladder | Vout = Vref × (binary/2^n) | |
| Gray to binary | XOR each bit with left neighbor | |
| 2's complement | For subtraction, add the 2's complement | |
| Multiplexer | 2^n data inputs, n select lines | |
| De Morgan's laws | (A·B)' = A' + B'; (A+B)' = A' · B' | NAND/NOR are universal gates |
| SR Flip-flop | Set-Reset; S=R=1 invalid | Basic latch |
| JK Flip-flop | Toggles when J=K=1 | No invalid state like SR |
| D Flip-flop | Q = D at clock edge | Data latch, shift registers |
| T Flip-flop | Toggles on each clock | Divide-by-2 counter |
| Schmitt trigger | Comparator with hysteresis | Noise rejection, wave shaping |
| Boolean identities | A + AB = A; A(A+B) = A; A + A'B = A + B | Simplification rules |

---

## QUICK MEMORY TRICKS (from PYQ patterns)

```
TRANSFORMER TRAPS:
- DC supply on primary → burns out (no counter-EMF, high current)
- Efficiency at half-load, 0.8pf lagging: compute Pi + 0.25×Pcu + copper(friction)
- Auto-transformer: conducts both by induction AND conduction
- Scott connection: teaser ratio = 2K/√3 (not K/√3)

DC MACHINE TRAPS:
- Lap wound: brushes = number of poles (P); Wave wound: brushes = 2 always
- Wave: A=2 always; Lap: A=P
- Series motor: NEVER run without load — overspeeds dangerously
- Swinburne's: constant loss = no-load input; armature copper = I²Ra
- Generator builds voltage: residual flux needed, Rf < critical resistance

INDUCTION MOTOR TRAPS:
- s_max = R₂/X₂ is independent of R1 — PYQ trick
- DOL: 6-8× starting current, full torque
- Star-delta: 1/√3 voltage, 1/3 current, 1/3 torque

FAULT ANALYSIS TRICKS:
- L-L fault: no zero-sequence → Z₀ not in denominator
- L-G: most common in practice
- 3-φ fault: most severe but rare; use Z₁ only
- SCR = 1/Xs(pu) → given Xs pu, SCR = 1/Xs

POWER ELECTRONICS TRICKS:
- Semi-converter: has freewheeling diode; full converter: no freewheeling diode
- For R-L load continuous current: average output = Vm(1+cosα)/π
- Chopper ripple MAX at D = 0.5
- Boost: Vout > Vin

CONTROL SYSTEMS TRICKS:
- Stable: all first-column terms of Routh array positive
- Unstable: any first-column element ≤ 0
- Mp = exp(−ζπ/√(1−ζ²)) — check ζ<1 (underdamped only)
- ts (2%) = 4/(ζωn), ts (5%) = 3/(ζωn)

MEASUREMENTS TRICKS:
- Voltmeter: always connected in parallel
- Ammeter: always connected in series
- Wattmeter: two coils — current coil in series, pressure coil in parallel
- Two wattmeter method: if pf > 0.5 (φ < 60°), both wattmeters read positive
```

---

## MARKS DISTRIBUTION

```
Machines (25): Transformer 10, DC 5, IM 5, Sync 5
Power Systems (15): Transmission 5, Fault 5, Protection 3, Stability 2
Electronics + Control (16): PE 8, Control 8
Circuits (10): Theorems 4, Resonance 3, Transients 3
Utilization (4): Traction 2, Measurements 2
```

---

## PYQ QUESTION → FORMULA MAPPING (Top 20)

| # | PYQ Question Pattern | Formula to Use |
|---|----------------------|---------------|
| 1 | Given N, f find P (poles) | P = 120f/N |
| 2 | Transformer max η load | x = √(Pi/Pcu) |
| 3 | Auto-transformer kVA rating | kVA_auto = kVA_tw × (a/(a−1)) |
| 4 | DC machine speed N | N = (V−IaRa)/(KΦ) |
| 5 | Voltage regulation transformer | %R = (IRcosφ±IXsinφ)/V×100 |
| 6 | Base change per unit | Zpu_new = Zpu_old × (MVA_new/MVA_old) × (kV_old/kV_new)² |
| 7 | tanφ from two wattmeters | tanφ = √3(W₁−W₂)/(W₁+W₂) |
| 8 | Fault current 3-φ | If = V/Z₁ |
| 9 | Fault current L-G | If = 3V/(Z₀+Z₁+Z₂) |
| 10 | Chopper Vout (buck) | V₀ = D×Vs |
| 11 | Chopper Vout (boost) | V₀ = Vs/(1−D) |
| 12 | Settling time | ts = 4/(ζωn) for 2% |
| 13 | Peak overshoot | Mp = exp(−ζπ/√(1−ζ²)) |
| 14 | Routh-Hurwitz stability | All first-column elements > 0 |
| 15 | Eddy current loss at different f | Pe ∝ f² (Bm constant) |
| 16 | Hysteresis loss at different f | Ph ∝ f (Bm constant) |
| 17 | Surge impedance | Z₀ = √(L/C) |
| 18 | DC machine lap/wave A | Lap: A=P; Wave: A=2 |
| 19 | Semiconductor device knee voltage | Si: 0.7V; Ge: 0.3V |
| 20 | Form factor sine wave | FF = π/(2√2) ≈ 1.11 |
| 21 | Transformer oil function | Insulation + cooling |
| 22 | Stepped core reason | Reduce iron material & iron loss |
| 23 | Lamination Si content <5% | Reduce eddy loss; >5% makes brittle |
| 24 | LV winding near core (concentric) | Reduces insulation requirement |
| 25 | String efficiency/voltage distribution | Max drop across disc nearest conductor |
| 26 | Corona undesirable effects | Power loss, radio interference, harmonics |
| 27 | Distribution TX max efficiency | At 50-70% of full load (not 100%) |
| 28 | Skin effect exists in | AC only; not in DC |
| 29 | CT secondary never open | Lethal high voltage; core saturation |
| 30 | SCR latching vs holding | IL > IH always; below IH → turns off |

---

> **Last Updated:** July 2026 | Good luck with your exam!
