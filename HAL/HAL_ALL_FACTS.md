# HAL — COMPLETE CONCEPT/FACT INVENTORY (every non-numeric question in BDL EE 2023 + 2025)

> **Pairs with `HAL_ALL_FORMULAS.md`.** Together they cover EVERY question type. Numerics live in the formulas file; this file holds every *conceptual/factual/definitional* question.
> `23:Q#` = BDL EE 2023 · `25:Q#` = BDL EE 2025. ⚠️ **2022 = image scan, no text → nothing verifiable.** Each row: fact (answer) → wrong-option trap the setter planted.
> **Totals: 2023 = 100 facts (84 technical · 1 maths · 15 reasoning) · 2025 = 85 facts (69 technical · 2 maths · 14 reasoning). Combined = 185.**

---

## 1. MEASUREMENTS & INSTRUMENTS (2023)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q8 | A manual **potentiometer has 3 terminals** | 4 terminals |
| Q12 | **Creeping** (slow no-load disc rotation) occurs in the **energy meter** | ammeter/hot-wire/voltmeter |
| Q14 | CRO: the metal cylinder with a small aperture at **negative potential** wrt cathode = **control grid** | accelerating anodes (positive) |
| Q21 | An instrument *defect* is a **systematic** error | random/gross |
| Q36 | **Galvanometer** is the null detector in a Wheatstone bridge | source |
| Q44 | A digital multimeter measures **AC/DC V & I + resistance + conductance** | only one quantity |
| Q51 | S/H sample-capture time (key: **aperture time**; standard term: acquisition time) ⚠️ | acquisition |
| Q58 | A DC potentiometer is **NOT** used to measure **temperature** | power (it can) |
| Q63 | **Schering bridge** measures **capacitance** | Wien= f, Maxwell= L |
| Q95 | Instrument transformers (CT/PT) work on **mutual induction** | Lenz |
| Q98 | **CRT** = "heart of the CRO" | sweep generator/trigger |

## 2. POWER ELECTRONICS & DEVICES (2023)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q7 | Cut buck-converter diode loss → connect a **low-R switch in PARALLEL with the diode** | series switch |
| Q17 | **IGBT = MOSFET + BJT** advantages (hybrid) | MOSFET+diode |
| Q18 | In sinusoidal PWM the **carrier is a triangular wave** | square |
| Q75 | A **thyristor (SCR) has 3 PN junctions** | 2 (diode) |
| Q81 | In **120° mode**, each SCR conducts **120°** per cycle | 60° |
| Q89 | D/A output is **proportional** to the digital value | exactly equal |
| Q97 | A DC–DC converter = **chopper** | cyclo-converter |
| Q99 | GTO = **Gate Turn-Off** thyristor | gain variants |
| Q100 | MOSFETs have **high input impedance** (so "low" is the NOT-true answer) | high (true) |

## 3. CONTROL & SIGNALS & SYSTEMS (2023)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q6 | Positive feedback = **regenerative** feedback | degenerative = negative |
| Q9 | **Schmitt trigger = inverting comparator + positive feedback** | integrator |
| Q10 | Node with only incoming branches = **sink node** | source |
| Q24 | LTI obeys **all** of associative/commutative/distributive | picking one |
| Q26 | ∫∫ unit step = **parabola** | ramp |
| Q34 | Non-minimum phase TF = **zero(s) in the right half-plane** | zero count |
| Q35 | BIBO stable ⇔ impulse response **absolutely integrable** | differentiable |
| Q52 | Transfer function = ratio of **Laplace** transforms (O/p ÷ I/p, zero ICs) | Z/Fourier |
| Q53 | Lead comp. uncancelled pole → **order ↑ by 1** | +2/+3 |
| Q61 | State transition matrix `Φ=e^{At}` = **free (zero-input)** response | impulse response |
| Q65 | SFG: the **arrow** shows transmission direction | line |
| Q73 | **Positive** gain margin → stable | — |
| Q76 | Nyquist through (−1, j0) ⇒ GM = **0 dB** | ∞ |
| Q80 | **Zero-state** = due to input; **zero-input** = due to initial states | reversed |
| Q86 | **Lead**: zero to the RIGHT of pole (zero nearer origin). **Lag**: pole to the right of zero | reversed |
| Q93 | FT of real signal → **conjugate symmetry** | even/odd |

## 4. POWER SYSTEMS / PROTECTION / OPERATION (2023)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q1 | **Relay** signals the CB to trip under fault | CT feeds relay, not CB |
| Q19 | Equal sequence **voltages** at fault ⇒ **double-line-to-ground** | SLG has equal sequence *currents* |
| Q22 | HVDC = **bulk power, very long distance** | harmonics/reactive |
| Q25 | **Z-bus** is a **dense** matrix (Y-bus sparse) | sparse |
| Q29 | Series compensation cuts **line transfer reactance** | shunt comp |
| Q39 | **Disc (suspension)** insulators used on **132 kV** | pin/shackle (low V) |
| Q47 | **HT cables: up to 11 kV** | 33/66/132 |
| Q48 | Load flow: **Gauss–Seidel = linear** conv.; **Newton–Raphson = quadratic** | reversed |
| Q56 | Parallel alternators: match **voltage, phase sequence, frequency** (none is untrue) | — |
| Q67 | Set with phase sequence **opposite** to original = **negative-sequence** comps | positive |
| Q71 | **Breather** arrests moisture entering the transformer | cooling-oil filter |
| Q83 | System **frequency ↔ active power** (voltage ↔ reactive) | reactive |

## 5. MACHINES (2023)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q4 | **Lap** winding: parallel paths = **poles** | wave = 2 |
| Q15 | 3-φ slip-ring IM has **3 slip rings** | 2 |
| Q28 | Wound-rotor IM speed changed by changing **slip (rotor resistance)** | pole changing |
| Q49 | EMF by changing current in a **neighbouring** coil = **mutual induction** | self |
| Q64 | **Salient pole**: air gap least at pole **centre**, grows away | uniform |
| Q68 | IM **frame = closed-grain cast iron** | silicon steel (core) |
| Q69 | DC shunt torque ∝ **Φ × Ia** | Ia only |
| Q88 | **Cylindrical rotor**: uniform air gap, high-speed (turbo) alternator | low-speed/projecting |
| Q91 | Squirrel-cage rotor slots **skewed** → reduces **magnetic locking/hum & cogging** | eddy/windage |
| Q94 | Wound-rotor: **"slip rings/brushes absent" is NOT true** | others true |

## 6. NETWORKS · CIRCUITS · EM · DIGITAL · ELECTRONICS · MISC (2023)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q2 | MMF = **N·I** (product, ampere-turns) | sum |
| Q5 | Force between charges = **Coulomb's law** | Faraday/Ohm/Ampere |
| Q13 | Find current in **one/added branch** → **Thevenin** | Norton (also works; classic key = Thevenin) |
| Q20 | NOT true of combinational circuits: "**harder to design**" (they're memory-less, simple) | memory-less (true) |
| Q27 | **Half-adder = XOR + AND** | NAND combos |
| Q30 | Ideal **voltage** source has **zero** internal resistance | infinite (current source) |
| Q31 | Four-terminal network = **two-port** | single-port |
| Q32 | Any combinational ckt using only **NAND and NOR** (universal) | XOR |
| Q33 | RC time constant = **RC** | R/C etc. |
| Q37 | Series drops add (KVL) | — |
| Q40 | E = **force per unit test charge** | sum/product |
| Q42 | **Mesh** = loop containing no other loop | — |
| Q43 | Superposition: response = **sum** of individual responses | product |
| Q46 | Biot–Savart (magnetic) ↔ **Coulomb's law** (electric) | Ampere/Lorentz |
| Q54 | Clamper **adds a DC level** | subtracts |
| Q55 | Flux density unit = **C/m²** | N/m, C/kg |
| Q57 | Biot–Savart **NOT used** for: **electric field intensity** | MRI/solenoid (applications) |
| Q60 | Active ÷ apparent power = **power factor** | form/load factor |
| Q74 | Lorentz **F = qE + qv×B** | mis-arranged terms |
| Q77 | Mesh eqs `L = B − N + 1` | — |
| Q82 | **Common-base** amplifier output resistance = **very high** | low |
| Q84 | Which is a binary number → **only one option uses digits 0/1** | 21/23/14 |
| Q85 | `ℒ{1} = 1/s` | 1, 1/s² |
| Q87 | Insulator between capacitor plates = **dielectric** | conductor |
| Q92 | V₁/V₂ = **voltage transfer ratio** | current transfer ratio |
| Q96 | Biot–Savart: H ∝ **1/r²** | directly ∝ |
| Q41 | `ℒ⁻¹{1/(s−a)} = e^{at}` | 1/tⁿ |

## 7. REASONING (2023)

| Q | Pattern | Solution |
|---|---|---|
| Q121 | 2-row linear seating, face-to-face | extreme-end pair = **Abarna & Karan** |
| Q122 | Letter series, gaps +1,+1,+2,+2,+3,+3 | K,L,M,O,Q,**T**,W |
| Q123 | Direction walk | net **8 km East** |
| Q124 | Blood-relation chain | wife's grandfather's only child's only granddaughter = **daughter** |
| Q125 | Odd-one-out | **Capital** (hut/house/shed are dwellings) |
| Q126 | Rank logic | earlier from right = **16th** (24−9+1) |
| Q127 | Coding letter-shift +2 | MYTHIC→OAVJKE; FOG→**HQI** |
| Q128 | Letter analogy decreasing gaps +7,+5,+3 | CDE → **JIH** |
| Q129 | Letter-pair analogy +4 | TU−4 → **PQ** |
| Q130 | Split series: letters +3,+4,+5,+6 both columns | FC,IF,MJ,RO → **XU** |
| Q131 | Number series ×2 | 6,12,24,**48**,96 |
| Q132 | Wrong term: multiply previous two | 2,3,6,18,**108**,1944 → wrong **118** |
| Q133 | Word-code mapping | "gives" → **wo** |
| Q134 | Data sufficiency (direction turns) | **Either I or II** alone |
| Q135 | Syllogism (prescriptive) | **Neither** conclusion follows |

---

# 2025 INVENTORY

## 1. MEASUREMENTS & INSTRUMENTS (2025)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q23 | Instrument measuring total electricity over time = **integrating** (kWh meter) | indicating/recording |
| Q26 | Control-spring material in instruments = **Phosphor bronze** | German silver |
| Q32 | **Tacho-generator** measures **speed** | displacement/acceleration |
| Q38 | PMMC power consumption ≈ **25–200 µW** | mW figures |
| Q42 | Anderson bridge advantage: **fixed standard capacitor, easy low-Q balance** (wording varies: "uses a fixed capacitor") | capacitance clause |
| Q47 | Multimeter **without battery** unsuitable for **resistance** (ohmmeter needs battery) | V/I readings |
| Q54 | **Schering bridge** = capacitance (and loss angle) | |
| Q79 | Piezoelectric transducer uses **quartz crystal** | gold crystal |
| Q84 | Single-frequency AC-bridge detector = **tuned detector** | vibration galvanometer |
| Q6 | CGS unit of mmf = **Gilbert** | Oersted=H, Gauss=B, Maxwell=Φ |

## 2. POWER ELECTRONICS & UTILIZATION (2025)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q33 | **Snubber** limits rate of rise of **dv/dt across SCR** | di/dt |
| Q39 | Half-wave rectifier can **saturate the transformer core** (DC component) | FWR bridges |
| Q41 | Thyristor turn-on methods = **all** (gate, voltage, dv/dt) | single method |
| Q51 | 3-φ semi-converter α ≤ 60° → **FWD conducts 0°** (continuous conduction) | 60° |
| Q57 | **AC voltage controllers** used in **electric heating** (and lighting) | generation |
| Q59 | Diesel/gas/steam generator speed controlled by **speed governor** | relay |
| Q46 | Pendant holder = for **hanging the bulb** | fixing |

## 3. CONTROL & SIGNALS & SYSTEMS (2025)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q5 | Denominator of TF = 0 ⇒ **poles** | zeros |
| Q19 | Marginally stable ⇒ **sustained oscillation** (poles on jω) | damped types |
| Q22 | OLTF zero with positive real part = **non-minimum phase** | minimum |
| Q25 | Lead comp: statements 1&2 true (improves relative stability, speeds transient); NOT steady-state error | include stmt 3 |
| Q27 | `(1+0.5s)/(1+s)` (a=0.5<1) = **lag network** | lead |
| Q34 | Type-1: position error **0**, acceleration error **∞** | reversed |
| Q61 | MIMO analysis → **state-space** | root locus (SISO) |
| Q62 | Very large bandwidth ⇒ response **faster** | sluggish |
| Q65 | `s²+2s+2` → ζ=0.707 ⇒ **underdamped** | critically/over |
| Q77 | Lead comp property (by elimination): **maximizes velocity constant** ⚠️ (textbook: ↑BW, faster transient) | overshoot/BW-down |
| Q78 | Type-0: velocity error **∞**, acceleration error **∞** | finite |
| Q2 | FT of rectangle = **sinc** | exp/log |
| Q14 | Double ∫ unit step = **parabola** | ramp |
| Q60 | Fourier series = **frequency-domain** representation | time-domain only |
| Q66 | Energy signals → average power **zero** | infinite |
| Q94 | `f(x) = f(x+p)` ⇒ **periodic** signal | even/odd |
| Q96 | N-point DFT = **N²** complex mults | N log N (FFT) |
| Q4 | Rotor current freq `fr = s·f` | s/f |

## 4. POWER SYSTEMS / PROTECTION / SWITCHGEAR (2025)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q1 | Feeds both sides of main line = **secondary transmission** | distribution |
| Q3 | GMD = **Geometrical Mean Distance** | mutual/maintenance |
| Q10 | Area under load curve = **units (energy) generated** | avg load |
| Q21 | Fault NOT in an alternator = **rotor-bar faults** (IM feature) | stator/field |
| Q24 | ↑ transmission Pmax → **series capacitors** | series inductors |
| Q29 | SC currents caused by **all** fault types | single type |
| Q43 | Off-load disconnection for maintenance = **isolator** | CB (on-load) |
| Q58 | Voltage across CB **after** arc = **recovery voltage** | restriking (during) |
| Q72 | **Distance protection** protects **transmission lines** | gens/transformers |
| Q83 | Substation receiving end mainly **star-delta** (step-down) | star-star |
| Q85 | IM **shaft = carbon steel** | cast iron |

## 5. MACHINES & TRANSFORMERS (2025)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q16 | IM **no-load test** ≈ transformer **open-circuit** test | SC = locked rotor |
| Q55 | DC shunt above-rated speed → **field rheostat** (weakening) | armature R |
| Q87 | **Potier triangle** separates leakage reactance from armature-reaction MMF | losses |

## 6. NETWORKS · EM · DIGITAL · ELECTRONICS · MISC (2025)

| Q | Fact (answer) | Trap |
|---|---|---|
| Q11 | Magnetic needle in uniform field → **torque, no net force** | force |
| Q12 | **Byte = 8 bits** | 4/16 |
| Q15 | AC frequency = **cycles/second** | electrons/sec |
| Q20 | ASCII = **7 bits** (extended 8) | 8 |
| Q35 | Properties change with direction = **unilateral** circuit | non-linear |
| Q37 | Canonical Boolean forms = **SOP and POS** | OR/XOR |
| Q50 | μ = **B/H** | reluctance |
| Q52 | Magnetic field **inside ideal conductor = zero** | infinite |
| Q71 | Maxwell independent set ⚠️ key: **both curl & divergence**; standard: 2 curl + continuity | |
| Q73 | Purely resistive ckt → PF = **unity** | lag/lead |
| Q74 | Transients present when circuit has **both L and C** ⚠️ key; standard: L *or* C (RL/RC/RLC) | |
| Q76 | Function with >1 output = **multi-output function** | |
| Q80 | Buffer for impedance matching = **common-collector** (emitter follower) | CB |
| Q88 | Flash ADC = **parallel-comparator** ADC | counter |
| Q95 | Sinusoidal oscillator = **positive feedback** | negative |
| Q98 | Routes one input → one of 2ⁿ outputs = **demultiplexer** | multiplexer |
| Q99 | NOR = **OR + NOT** | NAND |
| Q100 | **Common-base** input resistance = **very low** | high |
| Q64 | CP↔linear polarization: key 0% ⚠️ standard PLF = 50% (−3 dB) | |

## 7. REASONING (2025)

| Q | Pattern | Solution |
|---|---|---|
| Q102 | Word-class analogy (kind-of) | Linen:Cloth :: Gold:**Metal** |
| Q108 | Ranking from comparatives | J > D > I(59) > G > H → 3rd = **I** |
| Q109 | Word-code mapping | ci=federer, gi=plays, ta=cricket → "federer plays cricket" = **ci gi ta** |
| Q113 | Circular seating (outward; R/L inverted) | right of G = **F** |
| Q114 | Syllogism (habitat classes) | **only II** follows |
| Q118 | Alphabet groups 2→3→4→5→6 letters | AB|DEF|HIJK|**MNOPQ**|STUVWX |
| Q123 | Symbolic blood relation (`÷` = son) | **P = son of U** |
| Q132 | Statement–conclusions (prescriptive) | **Neither** follows |
| Q135 | Age ordering | youngest = **Tina** |
| Q136 | Data sufficiency (colour coding) | **I alone** sufficient |
| Q137 | Letter odd-one-out (consecutive + reverse pair) | **KLOR** breaks rule |
| Q139 | Seating DS (6 around circle) | **both together** |
| Q143 | Direction, facing each other | Mala looks **Northwest** |
| Q149 | Animal–home analogy | Cow:Byre :: Rabbit:**Hutch** (Pig:Pen defensible, key=C) ⚠️ |

## 2025 MATHS-CONCEPT

| Q | Fact | |
|---|---|---|
| Q28 | Binomial **mean = np** | trap 1−p |
| Q81 | Standard normal = **N(0,1)** | N(1,0) |

---

## CROSS-YEAR REPEATS (asked in BOTH 2023 & 2025 ⇒ near-certain)
FT rect → **sinc** · rotor freq `fr=s·f` · ∫∫step → **parabola** · GM/error-type concepts · **Schering = capacitance** · **series compensation** · lead/lag zero-pole geometry · DFT **N²** · slip/rotor families · instrument-class vocabulary.

## Setter answers that contradict standard theory (know theory, don't fight key)
25:Q64 pol. mismatch (key 0% vs 50%) · 25:Q71 Maxwell (key both vs curl+continuity) · 25:Q74 transients "both L&C" (restrictive) · 25:Q77 lead "maximizes Kv" (imprecise) · 25:Q149 Pig:Pen defensible · 23:Q51 aperture-vs-acquisition · 23:Q13 Thevenin-vs-Norton.

