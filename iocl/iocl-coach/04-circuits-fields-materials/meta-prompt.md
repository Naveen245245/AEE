# IOCL Coach — Block 04: CIRCUITS, FIELDS & MATERIALS (rapid sheet)
**Coverage: 63 of 300 drill-bank questions — the largest block → ★★★ (all blocks are ★★★; the sources are flat) | Engine slot: R4 | timebox ≈ 25 min**

Teach as Rapid Cards, not derivations. Only run 5-step deep mode on explicit `deep <topic>`. Anchors cite the institute sets, never "IOCL PYQ".

---

## RAPID SHEET (memorize the fact + the wrong option they plant)

### Network theorems & analysis
1. **KCL** is conservation of **charge**; **KVL** is conservation of **energy**. Trap: swapping them. Independent KCL equations for `n` nodes = `n − 1`.
2. **Thevenin resistance:** zero the sources — **voltage sources → short, current sources → open**; keep resistors. `Rth` is measured looking into the load terminals. Trap: reversing the source treatment.
3. **Thevenin voltage:** remove the load, find the open-terminal voltage. Thevenin ≡ a series `Vth + Rth`.
4. **Norton:** `In = Vth/Rth`, `Rn = Rth`. Source conversion is `V = IR` both ways. Trap: `In = Vth × Rth`.
5. **Maximum power transfer (DC):** `RL = Rth`, `Pmax = Vth²/(4Rth)`, efficiency = **50%**. Trap: options giving 100% efficiency or `RL = 2Rth`.
6. **Maximum power transfer (AC):** `ZL = Zth*` — the **complex conjugate**. Trap: `ZL = Zth`, which only maximises for a purely resistive source.
7. **Superposition:** applies to **linear** circuits only; sum the individual source contributions. It is not valid for power (which is nonlinear in current).
8. **Reciprocity** requires a **linear, passive, bilateral, time-invariant** network. Trap: granting reciprocity to a network containing a dependent source.
9. **Delta→Star:** `Ra = (R1R2)/(R1+R2+R3)`; each star arm = product of the two adjacent delta arms ÷ sum of all three. Star→Delta: `R1 = (RaRb + RbRc + RcRa)/Rc`.

### Resonance & transients
10. **Series resonance:** `XL = XC`, `f₀ = 1/(2π√(LC))`. `Z = R` (minimum), current **maximum**, pf = unity. Trap: claiming impedance is maximum in series resonance.
11. **Parallel resonance:** impedance is **maximum** (ideal), current minimum. Trap: applying the series behaviour.
12. **Quality factor (series):** `Q = ω₀L/R = 1/(ω₀CR) = (1/R)√(L/C)`. At resonance, `VL = VC = Q·V` — the component voltages can greatly exceed the supply. Trap: "VL and VC are zero at resonance".
13. **Bandwidth:** `BW = f₀/Q = R/(2πL)`. Higher Q → narrower band. Trap: `BW = Q·f₀`.
14. **RL time constant** `τ = L/R`; **RC time constant** `τ = RC`. Trap: inverting them (`R/L`, `1/RC`).
15. **RC charging:** `v(t) = V(1 − e^{−t/τ})`; discharge `v(t) = V₀e^{−t/τ}`. After one `τ` the capacitor reaches **63.2%**; after `5τ` it is ~99.3% (practical steady state).

### RMS, average & power
16. **Sine:** `Vrms = Vm/√2`, `Vavg = 2Vm/π`. **Form factor** `= Vrms/Vavg = π/(2√2) ≈ 1.11`. **Peak factor** `= Vm/Vrms = √2 ≈ 1.414`.
17. **Triangular / sawtooth:** `Vrms = Vm/√3`, form factor `= 2/√3 ≈ 1.155`.
18. **Square wave:** `Vrms = Vm` (form factor 1.0).
19. **Power** `P = VI cosφ` (1-φ); **three-phase** `P = √3 VL IL cosφ`, `Q = √3 VL IL sinφ`, `S = √3 VL IL`. Trap: using `√3` for a per-phase quantity or dropping it for a total.
20. **Power factor** `= cosφ = P/S = R/|Z|`. Trap: the option giving `sinφ`, or the impedance angle in degrees where a pf is asked.
21. **Star (Y):** `Vph = VL/√3`, `Iph = IL`. **Delta (Δ):** `Vph = VL`, `Iph = IL/√3`. Trap: applying the star relation to a delta load.
22. **Star↔Delta impedance:** `ZΔ = 3 ZY`. Trap: `ZΔ = ZY/3` (the inverse).

### Electrostatics
23. **Coulomb / point charge:** `E = Q/(4πε₀r²)` → falls as `1/r²`. **Potential** `V = Q/(4πε₀r)` → falls as `1/r`. Trap: swapping the exponents.
24. **Infinite line charge:** `E = λ/(2πε₀r)` → falls as `1/r`. **Parallel-plate:** `E = σ/ε₀` (**uniform**, independent of distance).
25. **Gauss's law:** `∮E·dA = Qenc/ε₀`; differential form `∇·E = ρ/ε₀`. Trap: "flux depends on the size of the surface" — it depends only on the enclosed charge.
26. **`∇ × E = 0`** — the electrostatic field is **conservative / irrotational**. Trap: options giving `μ₀J` (that is Ampère's law for B).
27. **`∇ · B = 0` always** — no magnetic monopoles.
28. **Parallel-plate capacitance** `C = ε₀εr A/d`. Doubling the area **doubles** C; doubling the separation **halves** C. Trap: the direction of each.
29. **Capacitors in series** add as reciprocals (like resistors in parallel); **in parallel** they add directly. Trap: treating them like resistors.
30. **Energy** `W = ½CV² = ½QV = Q²/(2C)`. Trap: forgetting the ½ — the most common slip in the block.
31. **Charge sharing** between two capacitors conserves **charge**, not energy: `Vf = (C1V1 + C2V2)/(C1 + C2)`. **Half the energy is lost** when an uncharged capacitor is connected across a charged one.
32. **Dielectric inserted, battery disconnected:** Q constant, C rises by εr, V falls by εr. **Battery connected:** V constant, Q rises by εr. Trap: mixing the two cases.

### Magnetism & materials
33. **Faraday:** `e = −N dΦ/dt`; the **negative sign is Lenz's law** (opposition to change). Trap: reading the sign as a magnitude.
34. **B at the centre of a circular loop** `= μ₀I/2a`. **On the axis of a long solenoid** `= μ₀nI`. **Long straight conductor** `= μ₀I/2πr`. Trap: `μ₀I/2πa` offered for the loop.
35. **Force between two parallel conductors** `F/L = μ₀I₁I₂/(2πd)`. **Same direction → attractive; opposite → repulsive.** Trap: reversing the rule.
36. **Force on a conductor** `F = BIL sinθ`; on a moving charge `F = qvB sinθ`; on a coil in a field, torque `τ = NIAB sinθ`.
37. **Solenoid inductance** `L = μ₀μrN²A/l` — proportional to `N²`. Trap: linear in N.
38. **Magnetic circuit:** `MMF = NI = ΦR`, reluctance `R = l/(μ₀μrA)`. **Air gap dominates** the reluctance because `μr = 1`. Trap: ignoring the air gap's contribution.
39. **Flux linkage** `λ = NΦ` (weber-turns). Trap: reporting `Φ` when `λ` is asked, or vice versa.
40. **Reluctance** is to magnetic circuits what resistance is to electric; **permeance** is its reciprocal.
41. **`B = μ₀μr H`**, so `μr = B/(μ₀H)`. Trap: forgetting `μ₀`.
42. **Hysteresis loss** `∝ f·Bmax^n` (n ≈ 1.6); reduced by **laminated / grain-oriented silicon steel**. **Eddy loss** `∝ f²B²t²`; reduced by **laminations** and increased resistivity. Trap: swapping which loss the lamination fixes — laminations address **eddy**, not hysteresis.
43. **Skin effect** raises AC resistance with frequency and conductor size; **proximity effect** is the neighbouring-conductor version.
44. **Materials:** copper for conductors (low ρ), silicon steel for cores (high μ, low hysteresis), mica/XLPE for insulation (high resistivity, high breakdown strength). **Superconductors** have exactly zero DC resistance below the critical temperature.

---

## BLOCK TRAP TABLE (top 8)

| Trap | Example stem | Counter |
|---|---|---|
| Source zeroing reversed | "Thevenin Rth: sources?" | V → short, I → open |
| Series vs parallel resonance | "impedance at resonance?" | series → **min** (=R); parallel → **max** |
| `1/r` vs `1/r²` | "E due to a point charge?" | E ∝ 1/r²; V ∝ 1/r |
| Missing the ½ | "energy stored in a capacitor" | `½CV²` |
| Loop vs straight-conductor B | "B at the centre of a loop" | `μ₀I/2a`, not `μ₀I/2πa` |
| Force direction | "currents in opposite directions?" | **repulsive** |
| Star vs delta conversion | "3 identical ZY → ZΔ?" | `ZΔ = 3ZY` |
| Lamination purpose | "why laminate the core?" | **eddy** loss, not hysteresis |

## MEMORY ANCHORS
- **Thevenin: short the V, open the I.**
- **Series resonates low (min Z); parallel resonates high (max Z).**
- **E goes as r², V goes as r** — one power apart.
- **Capacitors are backwards to resistors** (series like R-parallel).
- **Same-direction currents attract** — "like currents like each other".
- **Laminations stop eddies; alloying stops hysteresis.**

## DRILL RULES
1. Fire 2 Rapid-Card facts → 1 MCQ → verdict → next. 8–10 Qs per R4 (largest block).
2. After each wrong MCQ, record the topic in the session log; re-test it in the mock.
3. Anchor phrasing: "Set 01 Q16 style" / "Set 03 Q20 style" — **never** "IOCL PYQ".
4. Skip every `[BROKEN SOURCE]` / `[AMBIGUOUS STEM]` question from `practice_iocl.md`.
