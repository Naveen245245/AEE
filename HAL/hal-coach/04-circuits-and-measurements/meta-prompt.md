# HAL Coach — Block 04: CIRCUITS/NETWORKS + ELECTRICAL MEASUREMENTS (rapid sheet)
**Weightage: Circuits ~18 + Measurements ~19 = 37 of 178 classified (2023+2025) → ★★★ | Engine slot: R3 | timebox ≈ 20 min**

Teach as Rapid Cards. Only `deep` for derivation.

---

## PART A — CIRCUITS / NETWORKS

### Theorems & methods (which-tool questions recur)
1. **Thevenin**: replace a 2-terminal network by `Vth` + `Rth`; **most useful to find the current in ONE branch / an added branch** (PYQ 2023 Q13). Norton: current source `IN = Vth/Rth` in parallel with `Rth`. Convert reflex: Vth ↔ Norton `IN·Rth`.
2. **Superposition**: analyse one source at a time; others replaced by their internal impedance — **voltage source → short, current source → open**. Trap: "apply to power (P∝I²)" → power is non-linear, superposition invalid for power.
3. Equation counts: mesh `= b − n + 1`; node `= n − 1` (reference node). Trap: "+1/-1" off-by-one options.
4. **Maximum power transfer**: `RL = Rth` → `Pmax = Vth²/4Rth`.
5. Star↔Delta (balanced): `RΔ = 3·RY`. Trap: dividing vs multiplying by 3.

### AC & resonance
6. Series resonance `fr = 1/(2π√(LC))`; at resonance `XL = XC`, circuit is **resistive, min impedance (=R), max current**, pf = 1. Q = `XL/R = 1/(R)·√(L/C)`. Parallel resonance → max impedance, min line current.
7. AC powers: `P = VIcosφ`, `Q = VIsinφ`, `S = VI`; pf = cosφ. **Power in a pure inductor/capacitor is zero (reactive only).**
8. 3-φ: `P = √3·VL·IL·cosφ`; **star: `VL = √3·Vph`, `IL = Iph`; delta: `IL = √3·Iph`, `VL = Vph`**. Two-wattmeter method: `P = W1 + W2`; when pf < 0.5 one reads negative. Trap: converting before substituting.

### Transients & 2-port
9. Time constants: **RC → τ = RC; RL → τ = L/R**; ~5τ to reach steady state. Capacitor: open-circuit at DC steady state; inductor: short-circuit at DC steady state. Trap: "inductor in DC steady state acts as ___" → short.
10. Two-port parameters: **Z (open-circuit impedance)**, Y (short-circuit admittance), h (hybrid), ABCD (chain). `Z11 = V1/I1` with `I2 = 0`; reciprocal network `Z12 = Z21`. Extraction style recurs (PYQ 2025 Q86).
11. Initial/final conditions + source transformation + KVL/KCL basics always in the options.

## PART B — MEASUREMENTS & INSTRUMENTATION

### Bridges (map-to-quantity — guaranteed Qs)
12. **Bridge ↔ quantity:** Wheatstone = resistance; **Kelvin double = low resistance**; **Schering = capacitance (and its loss/dissipation factor)** (PYQ 2023+2025); **Anderson = inductance using a fixed standard capacitor**; Maxwell = inductance using a *variable* capacitor; Wien = frequency; Hay = high-Q inductance. Trap: options mix Schering/Maxwell/Wien.
13. **Anderson bridge's advantage over Maxwell: uses a FIXED capacitor instead of a variable standard capacitor** (PYQ 2025 Q42). Also suited to low-Q coils.
14. Null detector for AC bridges = **vibration galvanometer / tuned detector**; Wheatstone DC → sensitive galvanometer.

### Instruments (construction-vocabulary Qs recur)
15. **PMMC (permanent-magnet moving coil): DC only, measures the average/mean**; polarities matter. For AC it needs a rectifier. **Moving-iron (MI): works AC & DC, reads RMS**. Trap: "which works on AC only / DC only".
16. **Electrodynamometer** = AC+DC, used as **wattmeter** (no iron → accurate); induction type = energy meter (kWh). 
17. **Integrating instruments measure the total quantity of electricity/energy delivered over time** (PYQ 2025 Q23: kWh meter, Ah meter). Trap: "recording" vs "integrating".
18. **Heart of the CRO = the CRT (cathode-ray tube)** (PYQ 2023 Q14). X-plates = time base; Lissajous figures → frequency/phase comparison.
19. **Ammeter: low resistance, in series. Voltmeter: high resistance, in parallel.** Shunt extends ammeter range (`Rsh = Rm/(m−1)`); multiplier extends voltmeter. Never connect ammeter across supply.
20. **Transducers:** tacho-generator → **speed** (PYQ 2025 Q32); piezoelectric → force/pressure (needs charge amplifier); **LVDT → displacement**; thermocouple → temperature; RTD (Pt100) → temperature (resistance varies); strain gauge → strain/force. Trap: assign the wrong measurand.
21. **CT: never open-circuit the secondary** (huge flux/voltage spike); PT: never short. Burden = load on secondary; ratio/phase errors.
22. Potentiometer measures **emf at null (zero current)** — most accurate; megger = insulation resistance (generator + ohmmeter). Multimeter internal battery powers resistance ranges.

---

## BLOCK TRAP TABLE (top 8)

| Trap | Example stem | Counter |
|---|---|---|
| Bridge → wrong quantity | "bridge for capacitance?" | Schering (Maxwell = L) |
| Anderson vs Maxwell | "advantage of Anderson?" | fixed capacitor |
| PMMC vs MI | "DC-only instrument?" | PMMC (MI reads both) |
| Integrating definition | "measures total quantity over time?" | kWh/Ah integrating |
| CRO heart | "heart of CRO?" | CRT |
| Star/delta ratio | "VL vs Vph in delta?" | VL = Vph |
| CT/PT fault | "never open __ secondary?" | CT |
| Rth for Pmax | "Pmax condition?" | RL = Rth |

## MEMORY ANCHORS
- **Bridges: "Weird Kelvin Scared Anderson Maxwien"** — Wheatstone R · Kelvin low-R · Schering C · Anderson L (fixed cap) · Maxwell L (var cap) · Wien f.
- **"A-meter A-short-A-series (Ammeter is low-R series); V-meter high-R parallel."**
- CRO → **CRT**; integrating = **kWh/Ah**; transducer → measurand pairs (tacho=speed, piezo=force, LVDT=position).
- Resonance: **series = min-Z/max-I; parallel = max-Z/min-I**.

## DRILL RULES
- Bridge-mapping + instrument-vocab Rapid Cards are the free marks; follow with 2 quick numerics (Pmax, resonance f, 3-φ power).
- 8–10 Qs per R3; PYQ-anchor e.g. "BDL EE 2025 Q42 / Q23 / Q32 style".
