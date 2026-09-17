# IOCL Coach — Block 03: POWER ELECTRONICS & DRIVES (rapid sheet)
**Coverage: 43 of 300 drill-bank questions → ★★★ (all blocks are ★★★ — the sources are flat, none can be skipped) | Engine slot: R3 | timebox ≈ 20 min**

Teach as Rapid Cards, not derivations. Only run 5-step deep mode on explicit `deep <topic>`. Anchors cite the institute sets, never "IOCL PYQ".

---

## RAPID SHEET (memorize the fact + the wrong option they plant)

### Rectifiers — the phase-count trap zone
1. **1-φ half-wave uncontrolled:** `Vdc = Vm/π`. Ripple frequency = `f`.
2. **1-φ full-wave (bridge) uncontrolled:** `Vdc = 2Vm/π`. Ripple frequency = `2f`.
3. **1-φ fully-controlled (bridge):** `Vdc = (2Vm/π) cosα`. Ripple `2f`. Trap: the half-controlled version below.
4. **1-φ half-controlled bridge:** `Vdc = (Vm/π)(1 + cosα)`. Trap: **this is the most-swapped formula in the block** — the `(1+cosα)` form belongs to the *half*-controlled bridge, not the fully-controlled one.
5. **3-φ half-wave:** `Vdc = (3√3 Vm)/(2π)`. **3-φ full-wave bridge:** `Vdc = (3√3 Vm)/π` — exactly double. Ripple `6f`. Trap: using the 1-φ factor on a 3-φ stem.
6. **3-φ bridge in terms of line voltage:** `Vdc = (3√3 VmL)/π` where `VmL` is the line (not phase) maximum. Trap: mixing RMS and peak, line and phase.
7. **Ripple factor** of a full-wave rectifier ≈ **0.482**; half-wave ≈ **1.21**. Trap: swapping them.
8. **PIV** of a bridge diode = `Vm`; of a centre-tap full-wave = `2Vm`. Trap: swapping.
9. **Capacitor filter:** raises average DC toward `Vm` and reduces ripple; ripple `∝ 1/(f R C)`. Trap: "the capacitor increases the DC output beyond Vm".
10. **Displacement power factor** of a phase-controlled converter `= cosα` (for a fully-controlled bridge with a smooth current). Trap: options giving `cos(α/2)`, which belongs to a **half-controlled** converter.

### Choppers / DC-DC
11. **Buck:** `Vo = D·Vs`. **Boost:** `Vo = Vs/(1−D)`. **Buck-boost:** `Vo = Vs·D/(1−D)`. Trap: the topology swap — buck steps **down**, boost steps **up**.
12. **Duty cycle** `D = Ton/T`. Trap: giving the answer as a percentage when the options are fractions, or using `Ton/(Ton+Toff)` incorrectly when the stem quotes a switching **frequency** — `T = 1/f`.
13. **Buck inductor ripple** `ΔIL = (Vs − Vo)·D·T / L = Vo(1−D)T/L`. Ripple **decreases** with larger L and higher f. Trap: claiming ripple is independent of switching frequency.
14. **Boundary / critical inductance** `Lcrit = Vo(1−D)/(2·f·Io)`. Conduction becomes discontinuous below it. Trap: "CCM at all loads".
15. **Boost converter output is always ≥ input**; it cannot step down regardless of D. Trap: an option giving `Vo < Vs` for a boost.
16. **Cuk / buck-boost** both invert polarity. Trap: claiming the output is the same polarity as the input.

### Inverters
17. **1-φ full-bridge square-wave output:** fundamental peak `V₁ = 4Vs/(π√2)` RMS, or peak `4Vs/π`. Trap: dropping the 4/π factor.
18. **Harmonics of a square-wave inverter:** only **odd** harmonics, amplitude `∝ 1/n`. **THD of a square wave = 48.3%.** Trap: giving 0% or 100%.
19. **SPWM** pushes the dominant harmonics to around the **switching frequency** and its sidebands, and lowers THD vs square wave. Trap: "SPWM eliminates all harmonics".
20. **Number of pulses:** a 3-φ bridge gives **6 pulses** per cycle → lowest harmonic order `6 ± 1` = 5th and 7th. Trap: offering the 3rd harmonic, which cancels in a balanced 3-φ bridge.
21. **Space-vector PWM** gives a wider linear modulation range and lower THD than sinusoidal PWM.
22. **Dead time** in an H-bridge prevents **shoot-through** (both switches of a leg conducting). Trap: "prevents harmonics".
23. **Multilevel (NPC) inverters** reduce THD, reduce device voltage stress; the cost is **capacitor voltage balancing**. Trap: "eliminates the balancing requirement".
24. **Current-source inverter (CSI)** has a stiff DC **current** and needs a large series inductor; the VSI has a stiff DC **voltage** with a parallel capacitor. Trap: swapping which needs which.

### Devices & losses
25. **IGBT = MOSFET input + BJT output** — high input impedance with low conduction loss. Its main limitation is a **tail current at turn-off**, which caps switching frequency below a MOSFET's. Trap: "IGBT switches faster than a MOSFET".
26. **MOSFET** is majority-carrier → fast, but `Rds(on)` rises steeply with voltage rating. Best for **high frequency, low voltage**.
27. **Thyristor (SCR):** latches on, turned off only by **commutation** (current below holding current). Not a self-commutated device.
28. **Switching loss** `P ≈ ½·V·I·(ton + toff)·f` — **proportional to switching frequency**. Trap: claiming it is independent of f.
29. **Conduction loss** ∝ `I²·R` or `V·I`; it does **not** scale with frequency.
30. **Snubber (RC across a thyristor)** limits `dv/dt` and reduces turn-off stress. Trap: "increases di/dt withstand".
31. **Thermal runaway:** as temperature rises, leakage current rises, which raises dissipation, which raises temperature further. Trap: describing it as self-limiting.
32. **Safe operating area (SOA)** shrinks as temperature rises and as switching frequency rises.
33. **Diode reverse recovery** causes a current spike and EMI at turn-off; a **fast-recovery** diode reduces it.
34. **Synchronous rectification** replaces a diode with a MOSFET to cut conduction loss in low-voltage converters.

---

## BLOCK TRAP TABLE (top 8)

| Trap | Example stem | Counter |
|---|---|---|
| Half- vs fully-controlled | "1-φ controlled rectifier Vdc" | half-controlled: `(Vm/π)(1+cosα)`; fully: `(2Vm/π)cosα` |
| 1-φ vs 3-φ factor | "3-φ bridge Vdc" | 3-φ bridge = `(3√3Vm)/π` — double the half-wave |
| Buck vs boost | "Vo for D = 0.3" | buck `D·Vs`; boost `Vs/(1−D)` → **boost can never step down** |
| Ripple ∝ f | "increase switching frequency → ripple?" | ripple **falls** with higher f |
| PIV bridge vs centre-tap | "peak inverse voltage" | bridge `Vm`; centre-tap `2Vm` |
| Square-wave THD | "THD of a square wave" | **48.3%**, odd harmonics only |
| Switching loss vs f | "loss vs switching frequency" | switching loss **∝ f**; conduction loss is not |
| IGBT speed | "which switches faster?" | **MOSFET**; IGBT has tail current |

## MEMORY ANCHORS
- **Buck goes down, boost goes up.** "Buck = Below."
- **`(1+cosα)` → half-controlled.** "One cosine for the half."
- **3-φ is double the 1-φ half-wave.** Bridge ripple order = `2×` phase count → 6-pulse.
- **Switching loss lives on f; conduction loss lives on I².**
- **IGBT = MOS gate + BJT body; MOSFET = fast, low-voltage.**

## DRILL RULES
1. Fire 2 Rapid-Card facts → 1 MCQ → verdict → next. 7–9 Qs per R3.
2. After each wrong MCQ, record the topic in the session log; re-test it in the mock.
3. Anchor phrasing: "Set 03 Q89 style" / "IOCL Jr Engg Topic 5 style" — **never** "IOCL PYQ".
4. Skip every `[BROKEN SOURCE]` / `[AMBIGUOUS STEM]` question from `practice_iocl.md`.
