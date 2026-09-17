# IOCL Coach — Block 01: ELECTRICAL MACHINES (rapid sheet)
**Coverage: 42 of 300 drill-bank questions → ★★★ (all blocks are ★★★ — the sources are flat, none can be skipped) | Engine slot: R1 | timebox ≈ 22 min**

Teach as Rapid Cards, not derivations. Only run 5-step deep mode on explicit `deep <topic>`. Anchors cite the institute sets, never "IOCL PYQ".

---

## RAPID SHEET (memorize the fact + the wrong option they plant)

### Transformers
1. **EMF eq:** `E = 4.44 f N Φm`. Trap: the constant — 4.44 (= 2π/√2) vs the form factor 1.11. Anchor: "equation of transformer EMF".
2. **OC test → LV side, rated V** → measures **iron/core loss** (constant). **SC test → HV side, rated I** → measures **full-load Cu loss**. Trap: reversing the sides.
3. **Max η** at load `x = √(Pi/Pcu)`, where `Pi = x²Pcu`. `η = xS·cosφ / (xS·cosφ + Pi + x²Pcu)`. Trap: using full-load Cu loss at part load — Cu loss scales as `x²`, iron loss does not.
4. **Efficiency from losses:** `η = Pout/(Pout + Ploss)`. If a stem gives η and Pout, `Ploss = Pout(1−η)/η`. Trap: computing losses as `Pout × η`.
5. **Core area / emf-per-turn:** `E/N = 4.44 f Bm A`. Trap: **units** — the answer falls out in m² and the options are in cm²; a 10⁴ factor. This is the single most common numeric trap in this block.
6. **Regulation** `= (Vnl − Vfl)/Vfl × 100`. Lagging pf → larger; leading → smaller (can go negative). Trap: dividing by `Vnl` instead of `Vfl`.
7. **Turns ratio** `K = N₂/N₁ = V₂/V₁ = I₁/I₂`. Current ratio is **inverse** of the voltage ratio. Trap: the option that uses the ratio the same way for V and I.
8. **Parallel operation:** same voltage ratio, same %Z, same polarity, same phase sequence, **same vector group**. Trap: Yd11 ∥ Yy0 → 30° phase difference → circulating current.
9. **Auto-transformer:** one winding; copper saved `≈ (1 − 1/a)×100%`; **no isolation**. Trap: "gives galvanic isolation".
10. **Magnetizing vs loss component:** `I₀` lags V by ~75°; `Im = I₀ sinφ₀` (magnetizing), `Iw = I₀ cosφ₀` (loss). Trap: swapping sin/cos.

### DC Machines
11. **EMF:** `E = PΦNZ/60A`. **Torque `T ∝ ΦIa`**. Parallel paths: **lap `A = P`**, **wave `A = 2`**. Trap: asking for a *shunt* motor's torque → "∝ Ia" since Φ is constant.
12. **Speed:** `N ∝ (V − IaRa)/Φ`. Field (flux) control → **above** base speed; armature voltage control → **below** base.
13. **Back-emf:** `Eb = V − IaRa`, and `Ia = IL − If` for a shunt motor. Trap: using line current instead of armature current.
14. **Series motor never run unloaded** → runaway. `Φ ∝ Ia`, so speed rises as load drops. Trap: "what happens if a DC series motor is uncoupled?" → over-speeds and destroys itself.
15. **Series motor speed ratio:** `N₂/N₁ = (I₁/I₂)` when flux ∝ current and Eb ≈ V. Torque `T ∝ Ia²`. Trap: applying the shunt-motor rule to a series motor.
16. **Starters:** 3-point = NVR (no-volt) coil + OLR + starting resistance; 4-point adds a separate NVR supply. Trap: "which release protects against supply failure?" → the NVR / no-volt coil, not the OLR.
17. **Swamping resistance** in the field circuit reduces temperature error in the ammeter-based measurement.

### 3-Phase Induction Motor
18. **Sync speed** `Ns = 120f/P`. **Slip** `s = (Ns − N)/Ns`. **Rotor frequency `fr = s·f`**. Trap: the option `fr = s/f`.
19. **Rotor EMF `E2s = s·E2`**; rotor Cu loss `= s·Pag`; mechanical power `= (1−s)·Pag`. Under load slip ≈ 2–6%.
20. **Torque** `T = 3V²sR₂ / [ωs(R₂² + (sX₂)²)]`. **`Tmax` occurs at `s_max = R₂/X₂` and is INDEPENDENT of R₂.** Adding rotor resistance shifts the slip at which peak torque occurs, but not the peak itself. Anchor: "slip at maximum torque" numerics.
21. **Max torque** `Tmax = 3V²/(2ωs X₂)`. Trap: presenting `Tmax` as proportional to `R₂`.
22. **Doubling rotor resistance doubles `s_max`.** Trap: halving it, or claiming `Tmax` changes.
23. **Starting torque** is proportional to `V²`. A 10% voltage dip cuts starting torque ~19%. Trap: linear scaling.
24. **Starting methods:** DOL = full current; **star-delta cuts line current AND torque to 1/3**; autotransformer at tap `x` → `x²` of both; rotor-resistance starting only for slip-ring.
25. **Skewed rotor slots** (squirrel cage) reduce **magnetic locking / cogging**. Trap: answers like "reduce eddy current loss".
26. **Cage vs slip-ring:** cage = rugged, cheap, low starting torque; slip-ring = external rotor R → high starting torque.

### Synchronous Machines
27. **Speed/frequency:** `f = PN/120`, i.e. `Ns = 120f/P`. Common values at 50 Hz: 2-pole 3000, 4-pole 1500, 6-pole 1000, 8-pole 750 rpm.
28. **EMF** `E = 4.44 f N Φ kw kp`; `kw ≈ 0.96`. **Power–angle** `P = (EV/Xs) sinδ`.
29. **Short-circuit current** `Isc = E/Xs` per phase (steady state, Ra neglected). Trap: forgetting to convert line kV to phase kV when Xs is given per phase.
30. **Fault current is limited by the synchronous reactance.** Sub-transient `Xd''` and transient `Xd'` limit the earlier (larger) sub-transient and transient currents — `Xd'' < Xd' < Xd`.
31. **Sync motor is not self-starting** (no average torque at standstill). Starts as an IM via the **damper / amortisseur winding**, which also damps **hunting**. Trap: "starting method" → damper winding.
32. **Slip of a synchronous machine = 0** always. Trap: asking for slip and offering a small non-zero option.
33. **V-curve:** armature current vs field current. **Over-excited → leading pf** (acts as a capacitor / synchronous condenser). Under-excited → lagging.
34. **Increasing excitation at constant active power → reactive output increases.** Trap: claiming P changes.

### Special / one-liners
35. Single-phase motors: split-phase (centrifugal switch), capacitor-start (high Tst), shaded-pole (tiny). **Double-revolving-field theory** explains why a single-phase IM produces no starting torque.
36. Universal motor runs on AC and DC; stepper → discrete steps; BLDC → trapezoidal back-EMF.

---

## BLOCK TRAP TABLE (top 8)

| Trap | Example stem | Counter |
|---|---|---|
| `fr = s/f` | "rotor current frequency is –" | `fr = s·f` (slip × supply f) |
| SC vs OC side | "OC test done on which side?" | OC–LV at rated V; SC–HV at rated I |
| Lap vs wave `A` | "parallel paths, lap wound, P=4?" | lap A=P=4; wave A=2 |
| `Tmax` & rotor R | "rotor R doubled — Tmax?" | `Tmax` unchanged; `s_max` doubles |
| Units m² vs cm² | "core area required?" | carry units to the end — 10⁴ factor |
| Series motor at no load | "DC series uncoupled" | over-speeds → damage |
| Sync machine slip | "slip of synchronous motor?" | exactly **0** |
| Over-excited pf | "sync motor over-excited?" | leading pf |

## MEMORY ANCHORS
- Transformer: **OC = iron (LV side), SC = copper (HV side)** — "Open the Low, Short the High".
- Rotor: **f and E both scale by `s`**; rotor Cu loss = `s × Pag`.
- DC wound: **Lap = Many paths (A = P), Wave = Two (A = 2)**.
- Sync: **over-excite → over-deliver VArs → leading pf**.
- Adding rotor R to an IM moves the **slip**, not the **peak**.

## DRILL RULES
1. Fire 2 Rapid-Card facts → 1 MCQ → verdict → next. 7–9 Qs per R1.
2. After each wrong MCQ, record the topic in the session log; re-test it in the mock.
3. Anchor phrasing: "Set 01 Q44 style" / "IOCL Jr Engg Topic 3 style" — **never** "IOCL PYQ".
4. Skip every `[BROKEN SOURCE]` / `[AMBIGUOUS STEM]` question from `practice_iocl.md`.
