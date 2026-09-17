# HAL Coach — Block 02: POWER SYSTEMS (rapid sheet)
**Weightage: ~22 of 178 classified (2023+2025) → ★★★ (tied largest) | Engine slot: R1 (with Machines) | timebox ≈ 15–18 min**

Teach as Rapid Cards. Only `deep` for derivation.

---

## RAPID SHEET

### Transmission & Distribution vocabulary (definitional Qs are gold)
1. **Line feeding power on either side of the main transmission line = Secondary transmission** (PYQ 2025 Q1). Order: Generation → Primary transmission → Secondary transmission → Primary distribution → Secondary distribution. Trap: names are reversed in options.
2. **GMD = Geometrical Mean Distance** — the effective distance *between* phase conductors (PYQ 2025 Q3). **GMR = Geometrical Mean Radius** — of *one* stranded/bundled conductor (self). Trap: they swap the words. `L ∝ ln(GMD/GMR)`, `C ∝ 1/ln(GMD/r)`.
3. Bundling reduces line inductance & increases capacitance; increases SIL.

### Line & network performance
4. **ABCD constants:** `Vs = A·Vr + B·Ir`, `Is = C·Vr + D·Ir`; for a symmetric line **A = D**. Short line: `B = Z`. Trap: "A equals ___ for symmetrical line" → D.
5. **Nominal-π (medium line):** all shunt capacitance split half at each end; nominal-T lumped in middle.
6. **Ferranti effect:** lightly loaded / open-ended long line → receiving-end voltage **rises above** sending-end (capacitive charging). Trap: "voltage at open end of EHV line?" → higher.
7. **Regulation** `= (Vs − Vr)/Vr`; load power factor effect.
8. **Per-unit:** `Zpu = Z_Ω · Sbase / Vbase²`; base current `= Sbase/(√3·Vbase)`. Always convert to one common base when combining.
9. **Surge impedance loading** `SIL = V²/Zc`; power transfer `P = (Vs·Vr/X)·sinδ`.

### Power-flow & economics
10. **Area under the load curve = energy (kWh) generated/supplied** (PYQ 2025). Load factor `= avg load / max demand`; diversity factor `= Σ individual max / system max` (>1). Trap: which definition.
11. Tariff basics: demand charge + energy charge; power-factor (kVA) tariff penalises low pf.

### Faults & symmetrical components
12. **Negative-sequence components**: a balanced set with phase sequence **opposite** to the original (PYQ 2023). Positive = same sequence; zero = in phase.
13. Faults: **LLL (3-phase)** → only positive-sequence network → `If = Vth/(Z1 + Zf)`. **SLG → Z1+Z2+Z0**. **LL → Z1+Z2**. Sequence networks connect per fault type — state it before computing.
14. Symmetrical fault current is highest (usually) but SLG is most common on solidly-earthed systems.

### Protection & switchgear (definitional Qs — very common)
15. **A/an ___ provides the signal to the circuit breaker under fault → Relay** (PYQ 2025 Q1). Isolator = no-load disconnection only; CT steps current down for relays/meters.
16. **CT/PT (instrument transformers):** CT secondary ≈ 1 A/5 A, never open-circuited (kills secondary voltage); PT secondary ≈ 110/√3 V. Trap: "never open the ___ secondary" → CT.
17. **Distance (impedance) relay** protects transmission lines; **differential** protects transformers/generators/busbars; **Buchholz relay** = transformer internal (gas/incipient) faults only. Overcurrent: directional vs non.
18. **Restriking voltage** = appears across CB contacts *during* arc interruption; **recovery voltage** = after final arc extinction (PYQ 2025 Q58 style). Trap: swapping timing.
19. Circuit breakers: oil, **SF6** (best arc quenching, compact), vacuum (MV), air-blast. Arc quenching in vacuum/SF6 → dielectric recovery. MCB/MCCB/ELCB(RCD) roles; RCD detects earth leakage.
20. Fuse: operates on thermal effect of current; time-current characteristic.

### Generation & misc one-liners
21. Thermal → reheat improves η; hydro → cheap, quick start; nuclear → fission/chain reaction (control rods absorb neutrons); gas/CCGT.
22. Earthing: plate/pipe earth; earth-leakage; touch/step potential. Insulators: pin/suspension (HV, string efficiency), strain; corona on EHV lines.

---

## BLOCK TRAP TABLE (top 8)

| Trap | Example stem | Counter |
|---|---|---|
| GMD↔GMR swap | "GMD stands for?" | GMD = between conductors (Mutual is wrong-word trap); GMR = self |
| Vocab layer order | "feeds either side of main line?" | secondary transmission |
| CT secondary open | "which secondary never open?" | CT (not PT) |
| Relay vs isolator vs CB | "signals CB to trip?" | relay (low-power), CB breaks |
| Buchholz scope | "which device detects incipient transformer fault?" | Buchholz (gas); differential = electrical |
| Restriking vs recovery | "voltage after arc extinction?" | recovery; during = restriking |
| Sequence network for SLG | "SLG fault — which networks?" | +ve, −ve, zero in series |
| Symmetrical A=D | "parameter equal on both ends?" | A = D |

## MEMORY ANCHORS
- Layers: **G→PT→ST→PD→SD** (Primary/Secondary transmission before Primary/Secondary distribution).
- CT = Current Transform → **don't Open**; PT = Potential → don't short.
- Fault nets: SLG = three in series, LL = two in series, LLL = one alone, LLG = two parallel + one.
- **Ferranti = Far end floats higher.**

## DRILL RULES
- Definitional Rapid Cards first (they are the free marks here), then one numeric (regulation / per-unit / SIL).
- 8–10 Qs per R1 slot; wrong answers go to the session log and the mock.
