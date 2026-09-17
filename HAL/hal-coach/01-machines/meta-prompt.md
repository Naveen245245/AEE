# HAL Coach — Block 01: ELECTRICAL MACHINES (rapid sheet)
**Weightage: ~21 of 178 classified tech questions (2023+2025) → ★★★ | Engine slot: R1 (with Power Systems) | timebox ≈ 15–18 min**

Teach as Rapid Cards, not derivations. Only run 5-step deep mode on explicit `deep <topic>`.

---

## RAPID SHEET (memorize the fact + the wrong option they plant)

### Transformers
1. **EMF eq:** `E = 4.44 f N Φm`. Trap: factor 4.44 (both 2φ √2 and form factor) vs 1.11. PYQ-anchor type: "equation of transformer EMF".
2. **OC test → LV side, rated V** → measures **iron/core loss**. **SC test → HV side, rated I** → measures **full-load Cu loss** + gives `Z01 = Vsc/Isc`. Trap: reversing the sides.
3. **Max η** at load `x = √(Pi/Pcu)`; at that point `Pi = x²Pcu`. η = `xS·cosφ / (xS·cosφ + Pi + x²Pcu)`.
4. **Regulation** `= (Vnl−Vfl)/Vfl`; lagging pf makes it larger (+IX sinφ), leading smaller. Vocab trap: "regulation of transformer".
5. **Parallel op conditions:** same voltage ratio, same %Z, same polarity, same phase sequence, **same vector group**. Trap: Yd11 ∥ Yy0 → 30° phase diff → circulating current (forbidden).
6. **Auto-transformer** — single winding; saves copper `≈ (1 − 1/a)×100%`; no isolation. One-liner use: reduced-voltage starting.

### DC Machines
7. **EMF:** `E = PΦZN/60A`. Torque `T ∝ ΦIa`. Parallel paths: **lap `A = P`**, **wave `A = 2`** (independent of poles). Trap: asking torque of *shunt* → "∝ Ia (armature current)" since Φ constant.
8. **Speed:** `N = (V − IaRa)/kΦ`. Field (flux) control → above base speed; armature (voltage) control → below base.
9. **Series motor never run unloaded** → runaway. Trap: "what happens if a DC series motor is uncoupled?" → over-speeds & destroys itself.
10. Starters: **3-point starter = NVR (no-volt) coil + OLR (overload) + starting R**; 4-point adds separate NVR supply. Trap: "which release protects against supply failure?" → NVR/no-volt coil.

### 3-phase Induction Motor
11. **Sync speed** `Ns = 120f/P`. **Slip** `s = (Ns−N)/Ns`. **Rotor-current frequency `fr = s·f`** (PYQ 2025 Q4). Trap: wrong option `fr = s/f`.
12. **Rotor EMF `E2s = s·E2`**; rotor-Cu loss = `s·Pag`; mech power `= (1−s)·Pag`. Slip in a machine under load ≈ 2–6%.
13. **Torque** `T = 3V²sR₂/[ωs(R₂² + (sX₂)²)]`. **`Tmax` at slip `= R₂/X₂` and is independent of R₂.** Rotor-R injection raises starting torque (wound rotor) but NOT Tmax. PYQ-anchor: "rotor resistance" numericals.
14. **Skewed rotor slots** (squirrel cage) reduce **magnetic locking / cogging** (PYQ 2023). Trap: answers like "reduce eddy loss".
15. **Starting:** DOL = full; **star-delta reduces line current AND torque to 1/3**; autotransformer at tap `x` → `x²` of both; rotor-R starter only for slip-ring. 
16. Slip-ring (wound) vs squirrel-cage: cage = rugged/cheap, low starting torque; slip-ring = external R → high Tst.

### Synchronous Machines
17. **Frequency:** `f = PN/120`. (PYQ type 2025: 4-pole, 300 rpm → 10 Hz; 2023: 20-pole 25 Hz alt. → 48-pole 60 Hz driver motor.)
18. EMF `E = 4.44 f N Φ kw kp`; **`kw` (winding) ≈ 0.96**; `kp` pitch factor. Power/angle `P = (EV/Xs) sinδ`.
19. **Sync motor not self-starting** (stator+dc rotor → no avg torque at 50 Hz). Starts as IM via **damper/amortisseur winding** (also damps **hunting**). Trap: "starting method" → damper/as cage.
20. **V-curve:** armature current vs field current. Over-excited → **leading pf** (acts capacitor / synchronous condenser for pf correction). Under-excited → lagging.

### Special / one-liners
21. Single-phase motors: split-phase (centrifugal switch), capacitor-start (high Tst), shaded-pole (tiny). Double-revolving field theory explains no self-start.
22. Universal motor runs on AC+DC; stepper → discrete steps; hysteresis/reluctance sync; BLDC = trapezoidal back-EMF.

---

## BLOCK TRAP TABLE (top 8)

| Trap | Example stem | Counter |
|---|---|---|
| `fr = s/f` | "rotor current frequency is –" | `fr = s·f` (slip × supply f) |
| SC vs OC side | "OC test done on which side?" | OC–LV rated V; SC–HV rated I |
| Lap vs wave `A` | "number of parallel paths, lap wound, P=4?" | lap A=P=4; wave A=2 |
| Tmax & rotor R | "add rotor R — Tmax?" | Tmax unchanged; s_max ↑ to 1 |
| Series no-load | "DC series uncoupled" | over-speed → damage |
| Parallel same group | "Yy0 with Dy11 parallel?" | no — 30° diff |
| f=PN/120 pole count | "alt 25 Hz 20 pole; driver 60 Hz poles?" | same rpm → 48 poles |
| Over-excited pf | "sync motor over-excited?" | leading pf |

## MEMORY ANCHORS
- **"E-PAPER"** for transformer: E=4.44 f N Φ; Parallel same vector group; All-day η for distribution; Pi from OC; E…; R… (adapt freely).
- Rotor: **f, E both × s**; resistance in torque eq `/s`; rotor-Cu = s×Pag.
- DC wound: **Lap = Many paths (A=P), Wave = Two (A=2).**
- Sync: **over-excite → over-deliver VArs → leading.**

## DRILL RULES
1. Fire 2 Rapid-Card facts → 1 MCQ → verdict → next. 8–10 Qs per R1.
2. After each wrong MCQ, record the topic in the session log; re-test it in the mock.
3. PYQ-anchor phrasing: "BDL EE 2025 Q4 style" / "BDL EE 2023 Q15 style".
