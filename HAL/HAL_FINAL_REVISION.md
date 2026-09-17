# HAL — LAST-MINUTE REVISION SHEETS (one per subject)
**Exam: 160 Q / 2.5 h · Part-III EE 100 · Part-II Eng+Reason 40 · Part-I GA 20 · NO negative marking → never blank · ~55 s/Q**
Answers are the **bold** lines right under each question.

---

## 1. ELECTRICAL MACHINES

**Formulas**
- Transformer EMF `E = 4.44 f N Φm` · ratio `K = N2/N1 = V2/V1 = I1/I2`
- η `= x·S·cosφ / (x·S·cosφ + Pi + x²·Pcu)` ; **max η at x = √(Pi/Pcu)**
- OC test → **LV side**, rated V → gives **Pi** (iron). SC test → **HV side**, rated I → gives **Pcu** + Z01. (trap: reversed sides)
- %regulation `= (Vnl − Vfl)/Vfl` ; auto-tf saves copper `(1 − 1/a)×100%`
- DC: `E = PΦZN/60A` ; **lap A = P, wave A = 2** ; `T ∝ Φ·Ia` ; `N = (V − IaRa)/kΦ` ; **series motor NEVER no-load**
- IM: `Ns = 120f/P` ; slip `s = (Ns−N)/Ns` ; **rotor freq `fr = s·f`** ; rotor EMF `E2s = sE2` ; rotor Cu = `s·Pag`
- IM torque `T = 3V²·sR2 / [ωs(R2² + (sX2)²)]` ; **Tmax at s = R2/X2 (independent of R2)** ; T ∝ V²
- Star-delta start → **I and T both ÷3** ; skewing rotor slots → **reduces magnetic locking/cogging**
- Sync: `f = PN/120` ; `E = 4.44 f N Φ kw·kp` ; `P = (EV/Xs)·sinδ` ; sync motor needs **damper winding to start** (and damps hunting) ; **over-excited → leading pf**

**Formula Qs**
1. 4-pole 50 Hz IM at 1440 rpm → rotor freq? → Ns=1500, s=0.04 → **2 Hz**
2. 6-pole 50 Hz IM at 950 rpm → rotor freq? → Ns=1000, s=0.05 → **2.5 Hz**
3. 20-pole 25 Hz alternator driven by a 60 Hz motor → motor poles? → N=150 rpm → **48 poles**
4. DC shunt-motor torque ∝ ? → **Ia** (flux constant)
5. Add rotor resistance R2 → Tmax? → **unchanged**, only s_max shifts to 1
6. When is transformer η max? → **x = √(Pi/Pcu)**  (i.e. Pi = x²Pcu)
7. Star-delta starting torque as fraction of DOL? → **1/3**
8. 4-pole 50 Hz sync. machine speed? → **1500 rpm**

---

## 2. POWER SYSTEMS (Transmission · Distribution · Protection)

**Formulas**
- Flow: Generation → **Primary transmission → Secondary transmission → Primary dist. → Secondary dist.** (line feeding both sides of main line = **secondary transmission**)
- **GMD = Geometrical Mean Distance** (between conductors) ; **GMR = Geometric Mean Radius** (of one conductor) ; `L ∝ ln(GMD/GMR)`, `C ∝ 1/ln(GMD/r)`
- Line: `Vs = A·Vr + B·Ir`, `Is = C·Vr + D·Ir` ; symmetrical line → **A = D** ; short line B = Z
- **Ferranti**: open/lightly-loaded long line → receiving V **higher** than sending V
- %regulation `= (Vs − Vr)/Vr` ; **per-unit `Zpu = Z·Sbase/Vbase²`**
- SIL `= V²/Zc` ; area under **load curve = energy (kWh)** ; load factor = avg/max demand ; diversity factor = Σmax_i/System max (>1)
- Negative-sequence set = phase sequence **opposite** to original
- Faults: **SLG → Z1+Z2+Z0 (series)** · **LL → Z1+Z2 (series)** · **LLL → Z1** only ; `If = V/(Z1+Zf)`
- **Relay** sends the trip signal to the CB ; isolator = no-load only
- **CT secondary NEVER open** (≈1 A/5 A) ; PT secondary ≈ 110/√3 V
- **Buchholz** = transformer internal/incipient faults (gas) ; distance relay = lines ; differential = transformer/busbar/gen
- **Restriking voltage** = across CB contacts *during* arc extinction ; **recovery voltage** = *after* arc out
- SF6 = best arc quenching ; corona on EHV lines

**Formula Qs**
1. GMD full form? → **Geometrical Mean Distance**
2. Symmetrical transmission line: A = ? → **D**
3. Voltage at open far end of a long EHV line? → **rises (Ferranti)**
4. SLG fault — which sequence networks connect? → **Z1+Z2+Z0 in series**
5. Open the CT secondary → ? → **dangerous high voltage spike**
6. Area under the daily load curve = ? → **energy/units (kWh)**
7. Which device detects gas/incipient transformer fault? → **Buchholz relay**

---

## 3. POWER ELECTRONICS

**Formulas**
- SCR: **latching current > holding current** ; gate pulse starts conduction
- **Snubber (RC) limits dv/dt** ; **series inductor/anode reactor limits di/dt** (trap: swap)
- GTO = gate turn-OFF ; IGBT = **MOSFET gate + BJT conduction** hybrid
- **Buck `Vo = D·Vs`** ; **Boost `Vo = Vs/(1−D)`** ; Buck-boost `Vo = −D·Vs/(1−D)`
- Replace freewheel diode with MOSFET (synchronous rectifier) → cuts diode conduction loss
- 1-φ rectifiers (resistive): half-wave `Vdc = Vm/π` ; full-wave `Vdc = 2Vm/π` ; fully-controlled bridge `Vdc = (2Vm/π)cosα`
- Inverter: 1-φ full-bridge fundamental **peak = 4Vdc/π** ; **fundamental RMS V1 = (2√2/π)Vdc ≈ 0.9·Vdc** ; half-bridge ≈ half (0.45·Vdc)
- Cycloconverter: output f < supply f ; V/f control keeps IM flux constant

**Formula Qs**
1. Boost chopper 100 V, D=0.8 → ? → **Vs/(1−D) = 500 V**
2. Buck chopper 100 V, D=0.2 → ? → **20 V**
3. Snubber limits rate of rise of ? → **voltage (dv/dt)** across SCR
4. IGBT = combination of ? → **MOSFET + BJT advantages**
5. 1-φ full-bridge inverter fundamental RMS ≈ ? → **0.9 × Vdc**
6. SCR naturally turns off when anode current falls below ? → **holding current**

---

## 4. CONTROL SYSTEMS

**Formulas**
- **Poles = denominator = 0** ; zeros = numerator = 0
- Signal-flow graph: branch **arrow** = direction of transmission ; Mason: `T = ΣPkΔk/Δ`
- Closed loop `= G/(1+GH)` ; feedback **reduces sensitivity, increases bandwidth**
- Errors: `Kp=limG`, `Kv=lim sG`, `Ka=lim s²G` (s→0). **Type-0: pos err finite · Type-1: pos 0, ramp 1/Kv, accel ∞ · Type-2: pos 0, ramp 0, accel finite**
- Routh–Hurwitz: stable iff **all first-column > 0** ; **GM & PM must be positive**
- Damping from `s² + 2ζωns + ωn²`: `s²+2s+2` → ωn=√2, ζ=1/√2≈0.707 → **underdamped**
- Compensator: pole nearer origin than zero → **lag** (e.g. `(1+0.5s)/(1+s)`) ; zero nearer origin → **lead** ; uncancelled comp. pole/zero raises order **by 1**
- Controllers: PI kills steady-state error (adds type) ; PD adds damping/margin

**Formula Qs**
1. Type-1: position error & acceleration error? → **0 and ∞**
2. Characteristic `s²+2s+2=0` → damping? → **ζ≈0.707, underdamped**
3. `(1+0.5s)/(1+s)` is a ? → **lag compensator**
4. Denominator of TF = 0 gives ? → **poles**
5. System stable needs GM ? → **positive** (and PM positive)

---

## 5. CIRCUITS + MEASUREMENTS

**Formulas**
- **Thevenin** = best to find current in ONE branch ; Norton `IN = Vth/Rth` ; superposition: V-source→short, I-source→open (not for power)
- Mesh eqs `= b − n + 1` ; node eqs `= n − 1` ; **Pmax when RL = Rth** (`Pmax = Vth²/4Rth`) ; star→delta `RΔ = 3·RY`
- Series resonance `fr = 1/(2π√LC)` ; at resonance Z min (=R), I max, pf=1 ; Q = XL/R
- 3-φ `P = √3·VL·IL·cosφ` ; star `VL=√3·Vph` ; delta `IL=√3·Iph`
- Transients: `τ = RC` or `L/R` ; **cap = open ckt at DC steady state, inductor = short**
- Bridges: Wheatstone→R · Kelvin→**low R** · **Schering→capacitance** · Maxwell→L (var cap) · **Anderson→L (fixed cap)** · Wien→frequency
- **PMMC = DC only (average)** ; MI = AC+DC (RMS) ; electrodynamometer = AC+DC wattmeter ; integrating meters (kWh/Ah) = total quantity over time ; **CRO heart = CRT**
- Ammeter = low R, series ; voltmeter = high R, parallel ; **CT never open**
- Transducers: tacho→**speed** · piezo→force/pressure · **LVDT→displacement** · thermocouple/RTD→temperature

**Formula Qs**
1. Bridge for capacitance? → **Schering** (Maxwell = inductance)
2. Anderson over Maxwell advantage? → **uses a fixed capacitor**
3. DC-only (reads average) instrument? → **PMMC**
4. "Heart" of the CRO? → **CRT**
5. `RL` for maximum power transfer? → **RL = Rth**
6. Which instrument measures kWh (total quantity)? → **integrating (induction energy) meter**
7. Resonance frequency of LC? → **fr = 1/(2π√LC)**

---

## 6. ELECTRONICS · SIGNALS/DSP · EM/MATERIALS

**Formulas**
- Ideal op-amp: **∞ gain, ∞ Zin, 0 Zout, ∞ BW** (trap: "NOT a characteristic" → the finite one)
- Negative feedback: ↓ gain, ↑ bandwidth, ↓ distortion ; inverting `−Rf/Ri` ; non-inverting `1+Rf/R1`
- Zener = reverse-breakdown regulator ; BJT regions: active=amp, cut-off/saturation=switch ; FET = voltage-driven, high Zin
- **NOR = OR + NOT** ; **NAND & NOR universal** (any combinational ckt) ; byte = 8 bits, ASCII = 7 bits
- FF: SR invalid at S=R=1 ; **JK no invalid state (toggles)** ; D = data, T = toggle ; counters ÷ by 2ⁿ
- MUX: 2ⁿ inputs → n select ; ADC: n bits → 2ⁿ levels, step = Vref/2ⁿ
- Laplace: **δ(t)→1 · unit step 1→1/s · t→1/s² · e^−at→1/(s+a)**
- **FT of a rectangular pulse = sinc** ; DFT direct = **N²** mults, FFT = **N·log₂N** ; Nyquist `fs ≥ 2 fmax`
- **μ = B/H** (permeability) ; SI: MMF A-t, flux Wb, B Tesla ; **CGS: MMF = Gilbert, flux = Maxwell, B = Gauss, H = Oersted**
- Biot–Savart ↔ **Coulomb** analogy ; **hysteresis loss ∝ area of B–H loop** ; laminations + silicon steel cut eddy loss

**Formula Qs**
1. FT of a rectangle function? → **sinc**
2. Direct N-point DFT complex multiplications? → **N²**
3. Laplace of unit step u(t)? → **1/s**
4. "NOT a characteristic of ideal op-amp"? → **finite gain/BW** option
5. Combinational circuit using only one gate type → **NAND or NOR**
6. CGS unit of magnetomotive force? → **Gilbert** (Oersted = H)
7. Ratio of flux density B to field strength H? → **permeability μ**
8. Hysteresis loss depends on ? → **area of the B–H loop**

---

## 7. NON-TECH (Quant · Reasoning · English · GK) — ~37.5% of marks, bank fast

**Formulas/recipes**
- Avg speed (equal distances) `= 2ab/(a+b)` ; Boat: **down = u+v, up = u−v** ; boat `u=(down+up)/2`, stream `v=(down−up)/2`
- Time & work: A alone a days + B alone b days → together **ab/(a+b)** days (pipes: same, outlet = minus)
- Profit: SP = CP(1 ± p/100) ; **discount on Marked Price** ; successive discounts `a+b−ab/100` ; SP = MP(1−d/100)
- CI `A=P(1+r/100)^t` ; **CI−SI (2 yr) = P(r/100)²** ; SI = Prt/100
- **P&C:** `nPr = n!/(n−r)!`, `nCr = n!/[r!(n−r)!]` ; Probability = favourable/total (0–1)
- Partnership: profit ∝ **capital × time** ; Alligation: cross rule for mixtures
- H.C.F×L.C.M = **a×b** ; Ages/ratio → two linear equations ; weighted avg `Σwx/Σw`
- Mensuration: circle area `πr²`, `2πr` ; rect `lb` ; cube `a³`, cuboid `lbh`, cylinder `πr²h`, sphere `(4/3)πr³`
- **Clock angle `= |30H − 5.5M|`** (min ≤180°) ; hands coincide every **65⅝ min**
- Calendar: count **odd days** (leap=2, normal=1) ; % fraction table: 1/8=12.5, 1/6=16.67, 1/5=20, 1/4=25, 1/3=33.3, 1/2=50
- Trains/relative speed: crossing adds lengths ; opposite→add, same→subtract speeds
- Series: arithmetic/geometric/alternating/primes/squares ; Coding: letter-shift or reverse alphabet (A=Z)
- Family codes: decode operator first, then tree ; Syllogism: test extremes (all/some/no)
- English: one error per "improved" sentence ; P-Q-R-S → find opener (no pronoun back-ref) then flow
- GK/Defence: HAL = Tejas(LCA-MK1A), Sukhoi-30MKI, LCH **Prachand**, ALH Dhruv, HTT-40, GE-F414 pact ; PSUs HAL/BDL/BEL/MDL/GRSE

**Formula Qs**
1. Still-water 12, stream 4 → upstream? → **12−4 = 8**
2. CI−SI for 2 yr at 10% on ₹10,000? → **P(0.1)² = ₹100**
3. Two successive 10% discounts = single discount? → **10+10−1 = 19%**
4. Avg speed for 60 km/h & 40 km/h over equal distances? → **2·60·40/100 = 48 km/h**
5. A does a job in 6 d, B in 12 d → together? → **6·12/(6+12) = 4 days**
6. Clock angle at 3:00? → **|90 − 0| = 90°** (hands opposite) ; at 2:30 → **|60−165| = 105°**
7. `7C3`? → **7·6·5/6 = 35** ; `6P2`? → **30**

---

**Final 60 s ritual before the paper:** no negative marking → answer EVERY question · 55 s each, mark the uncertain ones and return · trust first instinct unless a unit/sign is off.
