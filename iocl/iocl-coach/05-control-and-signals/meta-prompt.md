# IOCL Coach — Block 05: CONTROL SYSTEMS & SIGNALS (rapid sheet)
**Coverage: 55 of 300 drill-bank questions → ★★★ (all blocks are ★★★ — the sources are flat, none can be skipped) | Engine slot: R5 | timebox ≈ 22 min**

Teach as Rapid Cards, not derivations. Only run 5-step deep mode on explicit `deep <topic>`. Anchors cite the institute sets, never "IOCL PYQ".

---

## RAPID SHEET (memorize the fact + the wrong option they plant)

### Transfer functions & time response
1. **Closed-loop** `T(s) = G/(1 + GH)` for **negative** feedback; `G/(1 − GH)` for positive. Trap: the missing minus sign — the single most common slip.
2. **Characteristic equation** is `1 + GH = 0`. Its roots are the closed-loop poles and determine stability.
3. **First-order step response:** `τ` = time constant; reaches **63.2%** at `t = τ`, **95%** at `3τ`, and is taken as settled at `4τ`–`5τ`.
4. **Second order:** `ωn` sets speed; `ζ` sets overshoot. `ωd = ωn√(1−ζ²)` is the damped frequency.
5. **Peak overshoot** `%Mp = e^{−πζ/√(1−ζ²)} × 100`. `ζ = 0.5 → 16.3%`; `ζ = 0.707 → 4.3%`; `ζ = 1 → 0%` (critically damped). Trap: options that halve the percentage or forget the π.
6. **Settling time (2% band)** `ts = 4/(ζωn)`; (5% band) `ts = 3/(ζωn)`. **Rise time** `tr ≈ 1.8/ωn`.
7. **Damping classes:** `ζ = 0` undamped · `0 < ζ < 1` underdamped (oscillatory) · `ζ = 1` critically damped · `ζ > 1` overdamped. Only `ζ = 0` gives sustained oscillation.

### Steady-state error — the system-type table
8. **Error constants:** `Kp = lim_{s→0} G(s)`, `Kv = lim_{s→0} sG(s)`, `Ka = lim_{s→0} s²G(s)`.
9. **`e_ss` table** (unity feedback):

| Type | Step | Ramp | Parabolic |
|---|---|---|---|
| 0 | `1/(1+Kp)` | ∞ | ∞ |
| 1 | **0** | `1/Kv` | ∞ |
| 2 | **0** | **0** | `1/Ka` |

Trap: the "infinite" cells — the setter loves offering `1/Kv` for a Type-0 ramp input, which is 0.
10. **Number of integrations in `G(s)` = the system type.** A `1/s` factor is Type 1.
11. **Final value theorem** `lim_{t→∞} f(t) = lim_{s→0} sF(s)`. Trap: the stem says "steady-state **value**" (the output) where you expect "steady-state **error**" — read which one is asked.

### Stability
12. **Routh:** the system is stable iff **every element of the first column is positive**. The number of **sign changes** = the number of RHP poles. Trap: "all coefficients positive" is *necessary* but **not sufficient**.
13. **Necessary condition:** all coefficients of the characteristic polynomial present and of the same sign. A missing term → at least one RHP pole.
14. **Nyquist:** `Z = N + P`, where `Z` = closed-loop RHP poles, `N` = clockwise encirclements of `−1 + j0`, `P` = open-loop RHP poles. **Stable iff `Z = 0`.** Trap: the sign convention — `Z = N + P`, so `N = Z − P`.
15. **Margins:** gain margin is measured where the phase crosses **−180°**; phase margin where the gain crosses **0 dB**. Trap: swapping the two crossover conditions.
16. **Stable iff GM > 1 (0 dB) and PM > 0°.**
17. **Root locus:** **starts at the open-loop poles** (`K → 0`) and **ends at the open-loop zeros or infinity** (`K → ∞`). Number of branches = number of poles. Trap: starting at zeros.
18. **Root locus on the real axis** exists to the left of an **odd** number of poles + zeros. Asymptote angles `= (2q+1)180°/(P − Z)`; centroid `= (Σpoles − Σzeros)/(P − Z)`.
19. A point on the root locus satisfies the **angle condition**; the **magnitude condition** gives K there.

### Compensators & controllers
20. **Lead:** `(Ts+1)/(αTs+1)` with `α < 1` — adds **positive phase**, increases bandwidth, speeds up the response, improves transient behaviour. Trap: `α > 1`, which is the lag form.
21. **Lag:** `(Ts+1)/(βTs+1)` with `β > 1` — reduces steady-state error, reduces bandwidth, slows the response.
22. **Pole/zero nearer the origin decides:** nearer-origin **zero → lead**; nearer-origin **pole → lag**. Trap: judging by the coefficient instead of the location.
23. **Max phase lead** `φmax = sin⁻¹((1−α)/(1+α))`, occurring at `ω = 1/(T√α)`.
24. **PID** `Gc(s) = Kp(1 + 1/(sTi) + sTd)`, with `Ki = Kp/Ti` and `Kd = Kp·Td`. Trap: inverting Ti and Td in the expression.
25. **Effect of each term:** P reduces rise time, I eliminates steady-state error, D reduces overshoot and adds damping. Trap: claiming D removes steady-state error.
26. **PI** improves steady-state error; **PD** improves transient response; **PID** does both.

### Signals & systems
27. **Causality:** output depends only on present and past inputs. **Memoryless** is a separate property. Trap: equating causal with memoryless.
28. **LTI stability (BIBO):** all poles in the **left half-plane** (continuous) or **inside the unit circle** (`|z| < 1`, discrete).
29. **Laplace pairs:** `u(t) → 1/s` · `δ(t) → 1` · `e^{−at}u(t) → 1/(s+a)` · `t·u(t) → 1/s²` · `sin(ωt) → ω/(s²+ω²)`.
30. **ROC:** for a right-sided (causal) signal, ROC is `Re(s) >` the rightmost pole. Trap: `Re(s) < −2`, which would be the anti-causal case.
31. **Z-transform:** `aⁿu[n] → 1/(1 − az⁻¹)`, ROC `|z| > |a|`. Note `1/(1−0.5z⁻¹) = z/(z−0.5)` — the **same** transform in two forms. Trap: the stem offers both and one looks "different".
32. **Sampling theorem:** `fs ≥ 2·fmax`. `2fmax` is the **Nyquist rate**; `1/(2fmax)` is the **Nyquist interval**.
33. **Aliasing:** if `fs < 2fmax`, the apparent frequency is `f_alias = |f − n·fs|` for the integer `n` that brings it into `[0, fs/2]`. Trap: reporting the folded value without taking the modulus.
34. **Fourier symmetry:** **half-wave** symmetry → **only odd harmonics**, no DC. **Even** symmetry → cosine terms only. **Odd** symmetry → sine terms only. Trap: the option offering even harmonics for a half-wave-symmetric waveform.
35. **Parseval:** energy in time = energy in frequency. Trap: claiming it applies to power signals without qualification.
36. **Convolution in time = multiplication in frequency**; cascaded LTI systems convolve their impulse responses.
37. **Ideal reconstruction filter** is a low-pass with cutoff at `fs/2`, so the original can be recovered exactly when `fs ≥ 2fmax`.
38. **FIR filters** are always stable and can be exactly linear-phase (symmetric coefficients); **IIR** needs fewer coefficients but may be unstable. Trap: attributing guaranteed stability to IIR.

---

## BLOCK TRAP TABLE (top 8)

| Trap | Example stem | Counter |
|---|---|---|
| Sign of feedback | "closed-loop TF" | negative feedback → `G/(1+GH)` |
| Type-0 ramp error | "Type-0 system, ramp input, e_ss?" | **∞**, not `1/Kv` |
| Routh sufficiency | "all coefficients positive → stable?" | necessary, **not** sufficient — check column 1 |
| Nyquist sign | "Z given N and P?" | `Z = N + P` |
| GM/PM crossover | "gain margin measured where?" | phase = −180° (PM at 0 dB) |
| Lead vs lag | "`(Ts+1)/(αTs+1)`, α<1?" | **lead** (zero nearer origin) |
| ROC direction | "ROC of a causal signal?" | **right** of the rightmost pole |
| Aliasing | "fs < 2fmax — apparent frequency?" | `|f − n·fs|` |

## MEMORY ANCHORS
- **CLTF: `G/(1+GH)`** — "one plus, for negative."
- Error table: **"Type 1 kills step and ramp; Type 2 kills all three."**
- **Routh: sign changes = RHP poles.** All-positive coefficients is a *necessary* check only.
- **Lead = zero nearer the origin** ("lead the way with a zero").
- **Nyquist: `Z = N + P`** — "Zed equals En plus Pee."
- Sampling: **Nyquist rate = 2fmax; Nyquist interval = 1/(2fmax)**.

## DRILL RULES
1. Fire 2 Rapid-Card facts → 1 MCQ → verdict → next. 7–9 Qs per R5.
2. After each wrong MCQ, record the topic in the session log; re-test it in the mock.
3. Anchor phrasing: "Set 02 Q53 style" / "IOCL Jr Engg Topic 14 style" — **never** "IOCL PYQ".
4. Skip every `[BROKEN SOURCE]` / `[AMBIGUOUS STEM]` question from `practice_iocl.md`.
