# IOCL Coach — Block 02: POWER SYSTEMS & PROTECTION (rapid sheet)
**Coverage: 42 of 300 drill-bank questions → ★★★ (all blocks are ★★★ — the sources are flat, none can be skipped) | Engine slot: R2 | timebox ≈ 22 min**

Teach as Rapid Cards, not derivations. Only run 5-step deep mode on explicit `deep <topic>`. Anchors cite the institute sets, never "IOCL PYQ".

---

## RAPID SHEET (memorize the fact + the wrong option they plant)

### Per-unit & load flow
1. **Per-unit** `Zpu = Zactual × MVAbase / kVbase²`. Traps: old→new base change is `Znew = Zold (MVAb / MVAb_old)(kVb_old / kVb)²` — the **voltage term is squared**, the MVA term is not.
2. **Why per-unit:** eliminates transformer ratios, makes impedances comparable across voltage levels, keeps values in a narrow band. Trap: the option claiming it "reduces losses" or "improves pf".
3. **Base impedance** `Zbase = kVbase²/MVAbase`; `Ibase = MVAbase/(√3 × kVbase)`.
4. **Bus types:** slack (V, δ known) · PV/generator (P, V known) · PQ/load (P, Q known). **Slack bus is the only one with both magnitude and angle fixed.** Trap: swapping PV and PQ knowns.
5. **PV → PQ conversion:** when a generator's reactive limit is violated, fix Q at the limit and convert the bus to PQ. Trap: "retain it as PV" or "increase generator voltage".
6. **Gauss-Seidel** is simple but **linear convergence**; **Newton-Raphson** uses the Jacobian and gives **quadratic convergence**. Trap: attributing quadratic convergence to Gauss-Seidel.
7. **Number of equations:** `2n − 1 − (number of PV buses)` for the Newton-Raphson power-flow mismatch set. Trap: plain `2n`.

### Faults & symmetrical components
8. **Three-phase fault:** `If = V/(Z₁ + Zf)` — only positive sequence. Trap: including Z₂ and Z₀.
9. **Single line-to-ground:** `If = 3E/(Z₁ + Z₂ + Z₀)`. The three sequence networks are in **series**. Trap: using `E/(Z₁+Z₂+Z₀)` and forgetting the 3.
10. **Line-to-line:** `If = √3 E/(Z₁ + Z₂)`. **Double line-to-ground:** sequence networks in **parallel**.
11. **Symmetrical components:** `I₀ = (Ia+Ib+Ic)/3`, `I₁ = (Ia + aIb + a²Ic)/3`, `I₂ = (Ia + a²Ib + aIc)/3`, with `a = 1∠120°` and `1 + a + a² = 0`. Trap: the a-operator applied to the wrong phase.
12. **In a 3-φ fault** only I₁ exists → I₀ = I₂ = 0. In an **LL fault** I₀ = 0 and I₂ = −I₁.
13. **Fault current is limited by the synchronous reactance** in steady state; by `Xd''` sub-transient and `Xd'` transient immediately after. `Xd'' < Xd' < Xd`. Trap: claiming armature resistance or field resistance limits it.
14. **Per-unit fault current** `Ipu = 1/Xpu` for a bolted 3-φ fault on a generator at rated V. Trap: dividing by √3.

### Stability
15. **Power–angle** `P = (EV/Xs) sinδ`. **Max at δ = 90°.** Trap: options putting the maximum at 180° or 45°.
16. **Steady-state stability limit** is `δ = 90°`; the system is stable while `δ` is below the critical clearing angle. Trap: comparing δ to `δmax` vs comparing areas.
17. **Equal area criterion:** stable iff `A_accelerating ≤ A_decelerating`. **Critical clearing angle** is where the two areas are equal. Trap: naming it "critical" for the angle where `δmax` is reached.
18. **Inertia:** `E_stored = H × S_rated` (MJ). `H` is in MJ/MVA and is numerically the **inertia constant in seconds**. Trap: multiplying H by MVA in kVA without converting.
19. **Swing equation** `M d²δ/dt² = Pm − Pe`. Increasing `H` slows the rotor excursion — more inertia, more stability.
20. **Ferranti effect:** on a **lightly loaded / open** long line, the receiving-end voltage **exceeds** the sending-end. Cause: line charging capacitance. Trap: attributing it to line resistance or to heavy loading.
21. **Surge impedance** `Zc = √(L/C)`, typically 400 Ω for overhead lines; **SIL** `= V²/Zc`.

### Transmission & distribution
22. **Voltage regulation** `%VR = (Vs − Vr)/Vr × 100`. Trap: dividing by `Vs`.
23. **Line impedance is total, not per km.** `Z = (r + jx) × length`. Trap: reporting the per-km value, or forgetting to multiply both parts.
24. **Corona loss** rises with voltage, conductor diameter (up to a point), and frequency; **reduces** with increased conductor spacing. Trap: "increases with spacing".
25. **Skin effect** raises effective AC resistance; it increases with frequency and conductor size. Trap: "skin effect reduces resistance".
26. **Load factor** `= average load / maximum demand`. **Diversity factor** `= sum of individual maxima / maximum demand` (≥ 1). Traps: inverting one of them, or confusing load factor with demand factor.
27. **Load curve area = energy consumed.** `Max demand = average load / load factor`.

### Protection
28. **Distance relay** reach `= (setting %) × Z_line`. Zone-1 ≈ 80% of the line (no intentional time delay). Trap: applying the 80% to the relay reach in ohms instead of the line length.
29. **CT/PT** step down current/voltage for measurement and protection, working on **mutual induction**. Trap: attributing them to Lenz's law.
30. **CT secondary must never be open-circuited** under load (dangerous voltage); **PT secondary must never be short-circuited**. Trap: swapping the two rules.
31. **CT burden** `S = I²R` in VA at rated secondary current. Trap: using the primary current.
32. **Symmetrical-component-based relays:** negative-sequence relays detect unbalanced faults; zero-sequence relays detect ground faults.
33. **Circuit breaker arc extinction:** recovery voltage appears **after** the arc is extinguished; **restriking voltage** appears **during**. Trap: swapping the two terms.

### Generation, renewables & utilization
34. **Thermal efficiency ranking:** combined-cycle gas turbine > coal-fired steam > simple-cycle gas turbine. Trap: ranking simple-cycle GT above CCGT.
35. **Renewable capacity/energy:** capacity factor `= actual energy / (rated power × time)` — solar PV in India typically 15–20%, wind 20–30%. Trap: confusing capacity factor with efficiency.
36. **Illumination:** luminous flux in **lumen**; illuminance in **lux = lumen/m²**; luminous intensity in **candela**. Trap: swapping lux and lumen.

---

## BLOCK TRAP TABLE (top 8)

| Trap | Example stem | Counter |
|---|---|---|
| Base-change exponent | "convert Zpu to a new base" | MVA ratio to the 1, **kV ratio squared** |
| SLG missing the 3 | "single line-to-ground fault current" | `If = 3E/(Z₁+Z₂+Z₀)` |
| Per-unit fault current | "3-φ fault, Xpu = 1.2" | `Ipu = 1/Xpu`; no √3 |
| Stability at δ = 90° | "max power transfer angle" | 90°, not 180° |
| Ferranti direction | "lightly loaded long line — Vr?" | Vr **>** Vs (charging capacitance) |
| Division base in %VR | "voltage regulation" | divide by **Vr** |
| CT/PT secondary rules | "CT secondary open?" | CT never open; PT never short |
| CCGT efficiency | "highest thermal efficiency plant" | **combined cycle** |

## MEMORY ANCHORS
- **SLG = series (Z₁+Z₂+Z₀, and ×3); LLG = parallel.** "Series for ground, parallel for double-ground."
- **Slack has everything; PV has V; PQ has neither.**
- **`Xd'' < Xd' < Xd`** — double-prime is the smallest, so it lets the biggest current through.
- Per-unit base change: **"MVA to the one, kV to the two."**
- **Ferranti = far end too high** (light load).

## DRILL RULES
1. Fire 2 Rapid-Card facts → 1 MCQ → verdict → next. 7–9 Qs per R2.
2. After each wrong MCQ, record the topic in the session log; re-test it in the mock.
3. Anchor phrasing: "Set 02 Q48 style" / "IOCL Jr Engg Topic 9 style" — **never** "IOCL PYQ".
4. Skip every `[BROKEN SOURCE]` / `[AMBIGUOUS STEM]` question from `practice_iocl.md`.
