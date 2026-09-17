# HAL Coach — PYQ Evidence & Weightage Analysis

> **Source of truth for every mark-allocation and topic-priority decision in this coach.**
> Do NOT invent weightage. Everything below comes from the collected papers in `../HAL/` plus the published HAL 2026 pattern.

## 1. The target exam

| Fact | Value | Source |
|---|---|---|
| Exam | HAL Management Trainee (Technical) / Design Trainee — Electrical | HAL Advert. HAL/HR/HC/TM/RECT-02/2026 |
| CBT | 160 Q, 160 marks, 2.5 hrs (150 min), online | published pattern |
| Sections | Part-I General Awareness **20** · Part-II English & Reasoning **40** · Part-III Electrical (discipline) **100** | published pattern |
| Language | English or Hindi (bilingual CBT) | published pattern |
| Setter note | Same paper-setter/agency family as BDL EE — so the collected BDL papers (below) are the behavioural template | user's guidance |

**Coaching corollary:** Part-III (100 Q, 62.5%) is a **breadth sampler over ~10 EE sub-areas**, not a deep exam. Part-II + Part-I (60 Q, 37.5%) are fast, bankable marks — never skip them.

## 2. Collected PYQs — how they were used

| Paper | File | Usable? | What it gives us |
|---|---|---|---|
| BDL EE 2022 (2021 cycle) | `BDL EE 2022.pdf` | Text layer = image-only | Format only: 150 MCQ, 2-hr slot, 4-option single-correct, answer-key + response log |
| BDL EE 2023 | `BDL EE 2023.pdf` | Full bilingual text + keys | Subject weightage + recurring micro-topics |
| BDL EE 2025 | `BDL EE 2025.pdf` | Full bilingual text + keys | Subject weightage + recurring micro-topics |

All three are 150-Q, 2-hour, bilingual EN/HI, with per-question answer key (memory-recreated papers — treat a few keys as provisional; when a drill answer contradicts well-known theory, trust theory and flag it).

## 3. Weightage — measured

Classified by question (2023 and 2025 combined, 300 questions; image-only diagram questions excluded from topic tallies).

### Technical areas (the ~100 Q in the real paper)

| # | Area | 2023 | 2025 | Combined | Share of tech | Priority |
|---|---|---|---|---|---|---|
| 1 | Power Systems & Protection | 11 | 11 | **22** | ~12% | ★★★ |
| 2 | Control Systems | 9 | 13 | **22** | ~12% | ★★★ |
| 3 | Machines | 12 | 9 | **21** | ~12% | ★★★ |
| 4 | Measurements & Instrumentation | 9 | 10 | **19** | ~11% | ★★★ |
| 5 | Power Electronics | 9 | 9 | **18** | ~10% | ★★★ |
| 6 | Circuits / Networks | 12 | 6 | **18** | ~10% | ★★★ |
| 7 | EM Fields & Materials | 9 | 8 | **17** | ~9% | ★★☆ |
| 8 | Signals & DSP | 8 | 8 | **16** | ~9% | ★★☆ |
| 9 | Digital Electronics | 6 | 7 | **13** | ~7% | ★★☆ |
| 10 | Analog Electronics | 5 | 5 | **10** | ~6% | ★★☆ |
| 11 | Utilization / Misc | 0 | 2 | **2** | ~1% | ★☆☆ |
| | **Tech total (classified)** | 90 | 88 | **178** | 100% | |

### Non-technical areas (the 60 Q in the real paper)

| # | Area | 2023 | 2025 | Combined | In HAL 2026 |
|---|---|---|---|---|---|
| 1 | Quantitative aptitude | 22 | 23 | **45** | folded into Reasoning block |
| 2 | Reasoning | 15 | 15 | **30** | Part-II |
| 3 | English | 15 | 15 | **30** | Part-II |
| 4 | GK / General awareness | 0 | 0 | **0** (absent from BDL proxy) | Part-I **20** |

**Overall split:** technical ≈ 195 vs non-technical ≈ 105 of 300 → **65 : 35**. HAL's real 100:60 split is 62.5 : 37.5 — same shape. Spend ~⅔ of every session on technical, ~⅓ on non-technical.

## 4. Recurring micro-topics (the highest-value 30 facts to drill)

Topic labels come straight from the papers; "hit" = how many times it recurred across 2023 + 2025.

### Machines (21 hits) — highest-hit examples
- Rotor current frequency `fr = s·f`; rotor EMF `E2s = s·E2` (2025 Q4, 2023)
- Squirrel-cage rotor skewing reduces **magnetic locking / cogging** (2023)
- Alternator speed–pole–frequency `f = PN/120` (2025: 4-pole 300 rpm → 10 Hz? `=4·300/120`)
- 20-pole 25 Hz alt. driven by 60 Hz motor → motor needs **48 poles** (2023)
- Lap vs wave winding: `A = P` vs `A = 2`; DC shunt torque ∝ `Ia` (2023, 2025)
- IM parts, synchronous machine excitation / hunting / damper winding

### Power Systems (22 hits)
- Primary/secondary **transmission vs distribution** vocabulary (2025 Q1)
- GMD = **Geometrical Mean Distance**; GMR = self (2025 Q3)
- Transmission-line max-power & voltage-regulator concepts (2025)
- Load curve: **area under load curve = energy / units generated** (2025)
- Faults, symmetrical components: negative-sequence = reverse phase sequence (2023)
- Protection vocab: relay sends signal to CB; recovery/restriking voltage across CB contacts after arc interruption (2025)
- CT/PT instrument transformers (2023, 2025)

### Control (22 hits)
- **Poles** = denominator of TF = 0 (2025 Q5)
- Lead/lag compensator TF shapes — `(1+0.5s)/(1+s)`: pole at `−1` nearer the origin than zero at `−2` → **lag** compensator (2025 Q25; reverse it → lead)
- Lead compensation un-cancelled pole raises system **order by 1** (2023)
- Characteristic eq `s²+2s+2=0` → ζ = 1/√2 ≈ 0.707 → **underdamped** (2025)
- Type-1 system → step(pos) error **0**, ramp error finite `1/Kv`, accel error **∞** (2025)
- Gain margin must be **positive** for stability (2023)
- Signal-flow graph: branch **arrow** = direction of transmission (2023)

### Measurements (19 hits)
- Schering bridge measures **capacitance** (loss/dissipation) (2023, 2025)
- Anderson bridge advantage over Maxwell: uses a **fixed capacitor** (2025 Q42)
- Wheatstone = resistance; Wien = frequency; Kelvin = low resistance (2023)
- CRO "heart" = **CRT** (2023)
- PMMC = DC only; integrating instruments measure **quantity (Ah)** (2025 Q23)
- Transducers: tacho-generator measures **speed**; piezoelectric → **force/pressure**; CT burden effect (2025)
- Ammeter shunt / multimeter battery conventions (2025)

### Power Electronics (18 hits)
- Snubber circuit limits **rate of rise of voltage (dv/dt)** across SCR (2025 Q33)
- Boost chopper `Vo = Vs/(1−D)` — 100 V in, D=0.8 → **500 V** (2025 Q92)
- Buck converter diode → use **synchronous rectifier (MOSFET) to cut conduction loss** (2023)
- IGBT = hybrid combining **MOSFET + BJT** advantages (2023)
- Single-phase full-bridge inverter fundamental RMS `V1 = (2√2/π)Vdc`; harmonic `4Vdc/(nπ)` peak (2025 Q18)
- SCR/GTO/MOSFET/GTO gate vs current turn-off facts (2023, 2025)

### Circuits (18 hits)
- Thevenin (find current in **one** branch) vs Superposition/Norton usage (2023 Q13)
- Two-port network parameter extractions recur (impedance/admittance/hybrid from terminal relations) (2025 Q86)
- Loop/mesh equation count `= b − n + 1`; node `= n − 1` (2025)
- Thevenin/Norton equivalence and conversion reflex

### EM Fields & Materials (17 hits)
- **Permeability μ = B/H**; ratio of flux density to field strength (2025 Q6)
- Biot–Savart ↔ **Coulomb's law** analogy (2023)
- MMF unit CGS = **Gilbert**; flux = Maxwell; flux density = Gauss; H = Oersted (2025 Q6)
- Maxwell's equations — which set is independent (2025)
- Dipole moment, force on charge, magnetic circuits

### Signals & DSP (16 hits)
- Laplace of `1` = `1/s`; of `δ(t)` = 1; unit step `1/s` (2023)
- Fourier of rectangular = **sinc** (2025 Q2)
- N-point DFT = **N²** complex multiplications (2025 Q66)
- Signals vocab: energy/power, periodic, step response

### Digital (13 hits)
- NOR = OR followed by **NOT** (2025); NAND/NOR universal → any combinational ckt (2023)
- Byte = 8 bits, ASCII = 7 bits (2025)
- SOP/POS, MUX/DEMUX usage (2025)

### Analog (10 hits)
- Ideal op-amp: infinite gain, infinite Zin, **zero Zout**, infinite BW (2023 Q6 NOT-question)
- Feedback amplifier effects (2023)
- Diode/BJT one-liner ratings

### Utilization (2) — illumination/traction one-liners (2025), low priority.

## 5. Question style (what to replicate in every drill)

1. **Definition / vocabulary** (~35%): "X is called —", "GMD stands for —", "A/an ___ provides a signal to the CB". Four short options.
2. **One-line concept** (~30%): "Frequency of rotor current is —", "Poles of TF = denominator zero gives —". Often the trap is the *inverse/opposite* option (s/f vs s·f).
3. **Quick numeric** (~25%): single formula, 30–60 s arithmetic (chopper D, `f=PN/120`, Laplace, DFT N²). No multi-step.
4. **Bilingual** EN + HI wording always mirrored.
5. **Trap style:** the wrong options are the *exact inverse*, the *1-φ vs 3-φ* version, or the *unit in a different system* (CGS MMF = Gilbert, not Oersted).

## 6. What this means for the 3-hour engine

- Do **not** teach 5-step derivations by default — HAL rewards *recall breadth*. Rapid sheet → trap → drill.
- Technical time splits roughly equally across ~7 ★★★ blocks (Power Systems, Control, Machines, Measurements, PE, Circuits) with quicker passes on ★★ EM/DSP/Digital/Analog.
- Reserve a firm ~30–35 min of every session for the non-technical bank (quant shortcuts, reasoning patterns, English, GK) — it is 37.5% of the paper and the fastest marks.
- Quote PYQ anchors ("this exact question appeared in BDL EE 2025 Q92") whenever a drill item matches a recurring micro-topic.
