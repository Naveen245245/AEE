# HAL Coach — Block 03: POWER ELECTRONICS + CONTROL SYSTEMS (rapid sheet)
**Weightage: PE ~18 + Control ~22 = 40 of 178 classified (2023+2025) → ★★★★ (biggest combined) | Engine slot: R2 | timebox ≈ 20 min**

Teach as Rapid Cards. Only `deep` for derivation.

---

## PART A — POWER ELECTRONICS & DRIVES

### Devices (definitional Qs recur every paper)
1. **SCR (thyristor):** latching current = min anode current to *stay ON* after gate removed; holding current = min to *stay conducting*. If anode current < holding → turns OFF. Trap: latching vs holding (latching > holding).
2. **Snubber circuit limits rate of rise of voltage (dv/dt)** across the SCR — prevents false turn-on (PYQ 2025 Q33). Trap: "di/dt" — that is limited by a **series inductor/anode reactor**, not the RC snubber.
3. **Turn-off:** SCR is a half-controlled device — turned OFF by current going below holding (natural/line commutation); **GTO = gate turn-off**; IGBT/MOSFET/BJT gate/base-controlled ON & OFF.
4. **IGBT = hybrid combining MOSFET (gate drive) + BJT (conduction) advantages** (PYQ 2023). Trap: "IGBT combines FET + thyristor?" → wrong.
5. Ratings ladder (rough voltage): MOSFET low-V high-freq fast; IGBT medium-V high-freq; thyristor high-V low-freq. Power BJT is current-driven (needs base current).

### Converters (numeric Qs recur)
6. **Buck (step-down):** `Vo = D·Vs`. **Boost (step-up):** `Vo = Vs/(1 − D)` (PYQ 2025 Q92: 100 V in, D=0.8 → **500 V**). Trap: mixing the two formulas.
7. Buck-boost: `Vo = −D·Vs/(1 − D)`. Chopper in traction = DC-DC speed control of DC motor.
8. In converters, **replacing the freewheeling diode with a MOSFET (synchronous rectification) cuts diode conduction loss** (PYQ 2023 — buck converter Q).
9. Single-phase rectifiers (assume ideal, resistive): half-wave uncontrolled `Vdc = Vm/π`; full-wave bridge uncontrolled `Vdc = 2Vm/π` (≈0.9 Vs). Fully-controlled bridge `Vdc = (2Vm/π)·cosα` in continuous conduction. Trap: half vs full-wave factor and "which quadrant".
10. **Inverter:** 1-φ full-bridge square-wave fundamental peak `= 4Vdc/π`; **fundamental RMS `V1 = (2√2/π)·Vdc ≈ 0.9·Vdc`** (PYQ 2025 Q18 style). Harmonics present at 3rd, 5th… → PWM/filtering to reduce. Multi-level reduces THD.
11. Single-phase half-bridge: fundamental RMS `≈ 0.45 Vdc` (half of full-bridge's 0.9). Trap: half vs full bridge voltage halving.
12. Cycloconverter: output frequency < supply frequency (direct AC-AC).

### Drives one-liners
13. V/f control keeps air-gap flux constant below base speed; IM torque ∝ V². Chopper-fed DC drive: speed ∝ average armature voltage.

## PART B — CONTROL SYSTEMS

### TF / modeling (definitional — every paper)
14. **Poles = denominator of transfer function = 0; zeros = numerator = 0** (PYQ 2025 Q5). Trap: numerator/denominator swap.
15. **Signal-flow graph: the branch (arrow) shows direction of transmission between nodes** (PYQ 2023 Q10). Mason's gain formula: `T = Σ PkΔk/Δ`. Number of state variables = order of system.
16. Closed-loop TF `= G/(1 + GH)`; negative feedback **reduces sensitivity** and **increases bandwidth**; characteristic eq = `1 + GH = 0`.

### Stability & response (recurring numeric + concept)
17. Characteristic eq `s² + 2s + 2 = 0` → `ωn=√2`, `2ζωn=2` → **ζ = 1/√2 ≈ 0.707 → underdamped** (PYQ 2025 Q19 style). Rules: ζ>1 overdamped, ζ=1 critically damped, 0<ζ<1 underdamped, ζ=0 undamped (oscillatory).
18. **Routh–Hurwitz:** system stable iff all first-column entries of the Routh array > 0 and no sign change. Routh can count RHP poles.
19. **Gain margin must be positive for stability** (PYQ 2023 Q34). GM = 1/G at −180° (or 0 dB crossing logic on Bode); PM = margin at gain crossover. GM>1(0 dB+) & PM>0 → stable. Trap: "GM negative means stable" → false.
20. Nyquist: encirclements `N = P − Z`; closed-loop poles in RHP if Z≠0. Non-minimum-phase = RHP zero.

### Errors & compensators (high-yield, subtle)
21. **Type number = number of integrators (poles at origin) in the open-loop TF.**
   - Type-0: `Kp = K` finite → step error finite.
   - **Type-1: step error = 0 (Kp=∞), ramp error = 1/Kv (finite), acceleration error = ∞ (Ka=0)** (PYQ 2025 Q34/Q78). Trap options: "position & acceleration errors of Type-1 are ___" → **0 and ∞**.
22. Error constants: `Kp = lim G(s)`, `Kv = lim s·G(s)`, `Ka = lim s²·G(s)` as s→0.
23. **Compensators:** lead (zero nearer origin; phase lead at crossover, faster response, higher BW); **lag (pole nearer origin; e.g. `(1+0.5s)/(1+s)` is lag** — PYQ 2025 Q25), reduces steady-state error, lowers BW. Un-cancelled compensator pole/zero raises system order by 1 (PYQ 2023). Trap: identify pole vs zero nearer origin.
24. Controllers: P raises Kv, reduces but not removes offset; PI removes steady-state error (adds type); PD adds damping/stability margin (adds a zero).

---

## BLOCK TRAP TABLE (top 8)

| Trap | Example stem | Counter |
|---|---|---|
| dv/dt vs di/dt | "snubber limits rate of rise of __?" | dv/dt (RC); di/dt needs series L |
| Buck vs boost formula | "100 V, D=0.8 → ?" | boost = 500 V; buck = 80 V |
| Lead vs lag pole/zero | "(1+0.5s)/(1+s) is a __?" | lag (pole nearer origin) |
| Type-1 errors | "pos & accel errors?" | 0 and ∞ |
| Zeros vs poles | "denominator=0 gives __?" | poles |
| Half vs full bridge | "1-φ bridge fundamental RMS?" | 0.9·Vdc full; 0.45 half |
| ζ values | "s²+2s+2 → damping?" | ζ≈0.707 underdamped |
| IGBT parents | "IGBT = ?+? advantages" | MOSFET gate + BJT conduction |

## MEMORY ANCHORS
- **D-cubed:** boost `Vo = Vs/(1−D)`; buck `Vo = D·Vs` — "**D on top = it drops (buck)**".
- Snubber **S**tops **V**oltage spikes → **dv/dt**.
- Lead/Lag: **L**ead has zero **L**eft-ish / nearer origin zero; pole nearer origin = **L**ag (both start with the shape you keep).
- Type number 0/1/2 → errors: (finite/∞/∞), (0/finite/∞), (0/0/finite).

## DRILL RULES
- Alternate PE numeric (chopper/inverter) with Control concept (error/compensator/stability) — these are the two most-tested "quick numeric" areas in the whole paper.
- 8–10 Qs per R2; PYQ-anchor e.g. "BDL EE 2025 Q92 / Q25 / Q34 style".
