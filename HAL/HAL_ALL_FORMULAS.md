# HAL — COMPLETE FORMULA UNIVERSE (every formula in BDL EE 2023 + 2025, question-by-question)

> **Exhaustive scan, no formula question missed.** Source: the two text-extractable papers. `23:Q#` = BDL EE 2023 · `25:Q#` = BDL EE 2025.
> ⚠️ **2022 is a pure image scan — zero text survived → no formula can be attributed to it.**
> 2023: 60 formula-bearing Qs (28 tech · 21 maths · 11 reasoning) + 8 image-blank · 2025: 82 formula-bearing Qs (44 tech · 24 maths · 14 reasoning) + 9 image-blank.
> Format: subject → formula (exact form) → Qs that used it → trap.

---

## MACHINES

| Formula | Used in | Trap / notes |
|---|---|---|
| DC EMF `E = PΦZN/60A` · lap `A = P`, wave `A = 2` | 23:Q4 | lap → parallel paths = **poles** |
| DC torque `T = k·Φ·Ia` | 23:Q69 | full statement ∝ Φ **AND** Ia |
| `f = PN/120` · same shaft ⇒ `P₁f₂ = P₂f₁` | 23:Q3, 25:Q75 | 20p/25Hz←60Hz→**48 poles**; 4p/300rpm→**10 Hz** |
| Slip `s = (Ns−N)/Ns`, `N = Ns(1−s)`; rotor-R control changes **slip** | 23:Q28 | squirrel cage cannot rotor-R |
| **Rotor current freq `fr = s·f`** | 25:Q4 | trap option: `s/f` |
| DC shunt ↑speed above rated → **field weakening** (R in series with **field winding**) | 25:Q55 | armature R lowers speed |
| Lap armature R: path = Z/A conductors; `R_total = Z·r/A²` | 25:Q70 | A=2, Z=100, r=2 Ω → **50 Ω** |
| Coil-span factor `Kp = cos(ε/2)`, ε = 180°−span | 25:Q93 | span 60°el → **0.5** (full pitch = 1) |

## POWER SYSTEMS & PROTECTION

| Formula | Used in | Trap / notes |
|---|---|---|
| `Z₀ = √(Z/Y)` characteristic impedance | 23:Q59 | Z=16, Y=9 S → **1.33 Ω** |
| Fault nets: **SLG = Z1+Z2+Z0 in series** (I₁=I₂=I₀) · **LLG parallel** (V₁=V₂=V₀) · LL series | 23:Q19 | parallel nets ⇒ equal sequence **voltages** |
| `P = EV/X`; **series compensation** `Xeff = XL−XC` ↑Pmax | 23:Q29, 25:Q24 | shunt comp doesn't cut line X |
| PF `= P/S = kW/kVA = cosφ` | 23:Q60 | active ÷ apparent |
| Resistive ckt → `PF = R/|Z| = 1` (φ=0) | 25:Q73 | |
| Load curve: **energy = area under curve = ∫P dt** | 25:Q10 | = units generated |
| Load factor `= avg/max` ⇒ `Max demand = avg/LF` | 25:Q49 | 1.25 kW / 0.0625 = **20 kW** |

## POWER ELECTRONICS & DRIVES

| Formula | Used in | Trap / notes |
|---|---|---|
| Single-pulse PWM: kill **nth** harmonic when width `= 360°/n` | 23:Q45 | 5th → **72°** (120° kills 3rd) |
| SCR surge (I²t equal heating): `I_one-cycle = I_half-cycle/√2` | 25:Q13 | 3000/√2 = **2121 A** (trap ×√2) |
| 1-φ full-bridge inverter: `V1rms = (2√2/π)Vdc ≈ 0.9Vdc`, `V1pk = 4Vdc/π`; `I₁ = V₁/|Z|`, `|Z|=√(R²+(XL−Xc)²)` | 25:Q18 | V1pk 292.9 V ÷ 10 Ω → **29.29 A** (book's answer) |
| Type-A (step-down) chopper with device drop: `V₀ = α·(Vs − Von)` | 25:Q40 | 0.5×(220−1) = **109.5 V** |
| 3-φ semi-converter: α ≤ 60° → output continuous → **FWD conducts 0°** | 25:Q51 | |
| Multiple-pulse PWM: spacing `180°/p`; `δ = (Ar/Ac)·(180°/p)` | 25:Q82 | (1/2)·36° = **18°** |
| **Boost (step-up) chopper `V₀ = Vs/(1−α)`** | 25:Q92 | 100/0.2 = **500 V** (trap 400) |

## CONTROL · SIGNALS/DSP · LAPLACE/FT · STATE-SPACE

| Formula | Used in | Trap / notes |
|---|---|---|
| `MMF = N·I` (amp-turns) | 23:Q2 | = **product** of I×N |
| ∫u(t)dt = ramp; **∫∫u(t)dt = t²/2 = parabola** | 23:Q26, 25:Q14 | double integral ≠ ramp |
| BIBO stable ⇔ `∫|h(t)|dt < ∞` | 23:Q35 | differentiability not enough |
| `ℒ⁻¹{1/(s−a)} = e^{at}` | 23:Q41 | ROC s>a |
| Lead comp `Gc = K(s+z)/(s+p)`; **uncancelled pole → order ↑ by 1** | 23:Q53 | not +2 |
| STM `Φ(t) = e^{At}` → **free (zero-input) response** | 23:Q61 | not forced |
| GM **> 0 dB** for stability (min-phase) | 23:Q73 | |
| `ℒ{1} = 1/s` | 23:Q85 | constant ↔ 1/s |
| FT of real signal → **conjugate symmetry** `X(−ω)=X*(ω)` | 23:Q93 | not even/odd |
| **Poles = denominator = 0**; zeros = numerator | 25:Q5 | trap: swap |
| Marginal stability (jω poles, ζ=0) → **sustained oscillation** | 25:Q19 | |
| Compensator `(1+aTs)/(1+Ts)`: a<1 → **lag** ⇒ `(1+0.5s)/(1+s)` = lag | 25:Q27 | a=0.5 |
| Error type: **Type-1 → position err 0, accel err ∞** | 25:Q34 | Kp=∞, Ka=0 |
| Lead max phase `φm = sin⁻¹[(a−1)/(a+1)]` | 25:Q36 | a=3 → **30°** |
| Bandwidth: `tr ≈ 0.35/BW` → BW↑ ⇒ **faster** | 25:Q62 | |
| 2nd order `s²+2ζωn s+ωn²`: `s²+2s+2` → ζ=0.707 **underdamped** | 25:Q65 | |
| `s²+4.8s+36` → `ωn=6`, `ζ=4.8/12 = 0.4` | 25:Q89 | |
| **Direct N-point DFT = N²** complex mults (FFT = N·log₂N) | 25:Q96 | trap: FFT answer |
| **FT of rectangular pulse = sinc** | 25:Q2 | trap: star/exp/log |
| Difference-eq recursion (`y(n)=x(n)−x(n−1)+2y(n−1)−y(n−2)`) | 25:Q8 | theory y(2)=**1**; official key says 0 ⚠️ setter slip |
| Energy signal ⇒ average power = **0** (`E` finite) | 25:Q66 | |

## CIRCUITS · NETWORKS · EM FIELDS/UNITS

| Formula | Used in | Trap / notes |
|---|---|---|
| Coulomb `F = (1/4πε₀)q₁q₂/r²` | 23:Q5 | inverse-square |
| KVL series: `Vs = V1+V2+V3` | 23:Q37 | 5.2+8.5+12.3 = **26 V** |
| `E = F/q` (field = force/charge) | 23:Q40 | |
| `τ = RC` | 23:Q33 | traps R/C, 1/RC |
| `D = Q/A = εE`, unit **C/m²** | 23:Q55 | |
| Parallel equal R: `Req = R/N` | 23:Q62 | 100×100 Ω → **1 Ω** |
| Lorentz `F = qE + qv×B` | 23:Q74, 25:Q68 | 2 C × 1 V/m = **2 N** |
| Mesh eqs `L = B − J + 1` | 23:Q77, 25:Q17 | 10−7+1 = **4** (not B−1) |
| Biot–Savart `dB ∝ (I dl sinθ)/r²` ⇒ H ∝ **1/r²** | 23:Q96 | inverse-square |
| Toroid `H = NI/(2πr)` — **r in metres** | 25:Q31 | 40·3.25/2π·0.2 = **103.45 A/m** |
| Magnetic dipole in uniform field: **torque `τ=mB sinθ`, net force = 0** | 25:Q11 | no ∇B → no force |
| Dipole moment `p = q·d` (convert cm→m) | 25:Q44 | 2×0.02 = **0.04 C·m** |
| `μ = B/H` (permeability) | 25:Q50 | ratio of flux density to field strength |
| Maxwell: 2 curl eqs + continuity make divergence eqs derivable | 25:Q71 | official key = both sets ⚠️ theory: curl pair is independent core |
| Two-port: from `I = Y·V`, `Z = Y⁻¹`, `Z12 = −Y12/ΔY` | 25:Q86 | Y=[[2,1],[2,3]], Δ=4 → **−0.25 Ω** |
| Polarization loss `PLF = cos²ψ` | 25:Q64 | circular↔linear: theory −3 dB (50%); official key 0% ⚠️ |

## MEASUREMENTS · ELECTRONICS · UTILIZATION (numeric/memorized)

| Formula / value | Used in | Notes |
|---|---|---|
| Ammeter shunt `Rsh = Im·Rm/(I − Im)` | 25:Q56 | 1 mA,100 Ω →100 mA ⇒ 100/99 = **1.01 Ω** |
| PMMC typical power ~ **25–200 µW** | 25:Q38 | memorized range |
| % ripple `= Vripple_rms/Vdc × 100` | 25:Q69 | 0.75/15 = **5%** |
| 35 SWG copper fuse wire → **≈ 5 A** | 25:Q97 | memorized |
| **1 byte = 8 bits** ; **ASCII = 7 bits** | 25:Q12, 25:Q20 | |

## MATHS / APTITUDE (2023 → Q50, Q101–120)

| Formula / method | Q | Trap / notes |
|---|---|---|
| Constrained combos `C(7,5)·C(6,5)·C(2,1)` | Q50 | = **252** |
| Remainder % → base (salary × 25% = 750) | Q101 | → **3000** |
| SI→CI: `CI₂ = SI + P(r/100)²` | Q102 | 51.25 |
| `CP = SP/(1+p/100)` | Q103 | 220/1.1 = 200 |
| Time–work rates add | Q104 | C alone = 1/8−1/24 → **12 d** |
| `sinX+sinY = 2 sin½(X+Y) cos½(X−Y)` | Q105 | = **cos A** |
| Percent-multiplier −6% ⇒ ×0.94 | Q106 | decimal trap |
| Average = Σ/n | Q107 | 77 |
| `CI = P[(1+r/100)ⁿ−1]` back-solve | Q108 | P = **16000** |
| Weighted avg = Σfx/Σf | Q109 | = 5 |
| Cube-cut: side = HCF; count = volume ratio | Q110 | HCF(6,42,54)=6 → 63 |
| MP chain: cash 0.9×1.25c, credit 0.95×1.25c | Q111 | c = **360** |
| Boats 2-eq (diff of times) | Q112 | stream = **8/3** |
| Fraction: present = 1 − absent | Q113 | 23/30 |
| Ratio + constant: (5k+12)/(8k+12) = 3/4 | Q114 | → **15** |
| Decimal simplify | Q115 | 0.10/0.05 = 2 |
| Boats downstream = b+c; D = vt | Q116 | 18×0.2 = **3.6 km** |
| Avg speed = total D/total T | Q117 | 90/9 = 10 |
| 8–15–17 triplet → tan A | Q118 | 8/15 |
| Scientific notation mantissa ∈[1,10) | Q119 | 9.123×10⁻⁶ |
| Ages 2 linear eqs | Q120 | S = 12 |

## MATHS / APTITUDE (2025 → new items)

| Formula / method | Q | Trap / notes |
|---|---|---|
| Binomial mean `μ = np` | Q28 | trap n−p |
| Linear eq `2y+9=4` | Q30 | y = −2.5 |
| DE `dx/dy = cos(x+y)`, v=x+y → `tan((x+y)/2) = y + c` | Q67 | |
| Standard normal = **N(0,1)** | Q81 | μ=0, σ²=1 |
| Series: differences = consecutive squares (11²…15²) | Q104 | ? = **666** |
| BODMAS with `of` + braces | Q107 | a = **48** |
| Ladder: `cos60° = base/hyp` | Q110 | 10.5/0.5 = **21 m** |
| Successive change: `(1−.25)(1+.30) = 0.975` | Q115 | **2.5% decrease** |
| Time–work pairs: isolate one `1/P = [1/10+1/15−1/12]/2` | Q117 | **24 d** |
| 2-digit linear eqs `x−y=18`, `3x−4y=18` | Q119 | sum = **90** |
| CI equal installments (PV at half-yearly rate 5%) | Q121 | ≈ **8200** |
| Averages leave/join (sum method) | Q127 | avg = **14** |
| Wire: square perimeter = circle `2πr` | Q128 | area = **154 cm²** |
| Boats `v/u = (Tu+Td)/(Tu−Td)` | Q129, Q147 | 13:5 ; 7:1 |
| Pair incomes → individual | Q130 | **4000** |
| `SI = Prt/100` → recompute at new rate | Q134 | **1584** |
| Identity `(p²−q²)² = 16pq` (p=cotθ+cosθ, q=cotθ−cosθ) | Q138 | |
| Meeting time `T = √(t₁·t₂)` | Q140 | t₁=54,t₂=24 → T=36; total **60 min** |
| Population chain multipliers ×1.1×0.95×1.2 | Q141 | **12540** |
| Income/expense/savings ratio | Q142 | **2:2:1** |
| `CP = SP/(1+gain%)` then re-sell | Q144 | gain = **10%** |
| Pass/fail threshold `0.30M+40 = 310+30` | Q148 | M = **1000** |
| Decimal division | Q150 | as printed self-inconsistent ⚠️ key 0.125 |

## REASONING (2023)

| Pattern / rule | Q | Notes |
|---|---|---|
| Letter series by alphabet positions, growing gaps +1,+1,+2,+2,+3,+3 | Q122 | → **T** |
| Direction vectors (net E-W / N-S) | Q123 | → 8 km E |
| Rank: `from right = N − posL + 1` | Q126 | 24−9+1 = **16** |
| Letter-shift coding (wrap alphabet) | Q127 | MYTHIC+2 → FOG = **HQI** |
| Letter analogy decreasing odd gaps +7,+5,+3 | Q128 | CDE → **JIH** |
| Pair-shift analogy (CD→GH = +4) | Q129 | TU−4 → **PQ** |
| Alpha-numeric split series (+3,+4,+5,+6) | Q130 | → **XU** |
| Number series ×2 | Q131 | **48** |
| Wrong term: product of previous two | Q132 | 118 (should be 108) |
| Word-code common-word/common-code | Q133 | gives→**wo** |
| DS: 90° turn logic | Q134 | either I or II |
| Seating / blood-relation / odd-one-out / modal syllogism | Q121/124/125/135 | pattern-based |

## REASONING (2025)

| Pattern / rule | Q | Notes |
|---|---|---|
| Analogy superordinate (Linen:Cloth :: Gold:**Metal**) | Q102 | kind-of relation |
| Ranking from comparatives + extrema anchors | Q108 | J>D>I>G>H → **I** 3rd |
| Word-code mapping (common-word) | Q109 | → ci gi ta |
| Circular seating **outward** (right/left inverted) | Q113, Q139 | |
| Syllogism (class / prescriptive → neither) | Q114, Q132 | |
| Alphabet growing blocks AB|DEF|HIJK|?|STUVWX | Q118 | → **MNOPQ** |
| Symbolic blood relation `*`−`÷`+ (÷ = son) | Q123 | P = **son** of U |
| Age ordering | Q135 | → Tina |
| Coding data-sufficiency (colour) | Q136 | I alone |
| Letter odd-one-out: `+1 … −1` envelope | Q137 | **KLOR** breaks |
| Direction: facing-each-other endpoint | Q143 | Mala → **Northwest** |
| Animal–home (Cow:Byre :: Rabbit:**Hutch**) | Q149 | |

---

## Repeats across BOTH years = near-guaranteed topics
`L = B−J+1` · series compensation `P=EV/X` · `f = PN/120` · ∫∫u(t) = parabola · GM (0 dB at (−1,j0)) · rotor slip/freq family · 3-φ power/concept constants · boat-stream time-ratio method.

## Setter inconsistencies to watch (know theory, don't fight it)
- 25:Q8 difference-eq → theory y(2)=1, official key 0.
- 25:Q64 polarization circular↔linear → theory −3 dB, official key 0%.
- 25:Q150 decimal division → printed numbers give no option; official key 0.125.
- 25:Q18 inverter current → official uses peak fundamental (292.9 V) ÷ 10 Ω = 29.29 A.
