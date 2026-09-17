# IOCL Coach — Block 06: MEASUREMENTS, ANALOG & DIGITAL (rapid sheet)
**Coverage: 39 of 300 drill-bank questions → ★★★ (all blocks are ★★★ — the sources are flat, none can be skipped) | Engine slot: R6 | timebox ≈ 20 min**

Teach as Rapid Cards, not derivations. Only run 5-step deep mode on explicit `deep <topic>`. Anchors cite the institute sets, never "IOCL PYQ".

---

## RAPID SHEET (memorize the fact + the wrong option they plant)

### PART A — MEASUREMENTS & INSTRUMENTS

1. **Wheatstone bridge balance:** `R1/R2 = Rx/R3`, i.e. `R1·R3 = R2·Rx`. Solve for the unknown by cross-multiplying. **Sensitivity is maximum when all four arms are equal.** Trap: the arm-pairing — picking the wrong two arms to multiply.
2. **Kelvin double bridge** measures **very low resistance** (below ~1 Ω) because it eliminates contact and lead resistance. Trap: assigning it to high resistance (that is a Megger / loss-of-charge method).
3. **Schering bridge → capacitance** (and dissipation factor). **Maxwell bridge → inductance**. **Wien bridge → frequency**. **Anderson → inductance**. Trap: the bridge→quantity mapping — memorise it as a table, it is pure recall.
4. **Potentiometer constant** = voltage/length (V/cm or mV/cm). It is a **null** instrument, so it draws no current from the source at balance. Trap: options treating it as a deflection instrument.
5. **Galvanometer** is the **null detector** in a Wheatstone bridge, not the source.
6. **Energy meter "creeping"** = slow disc rotation at no load, caused by vibration/over-compensation; cured by drilling two holes in the disc. Trap: attributing creeping to the ammeter or voltmeter.
7. **Instrument transformers work on mutual induction.** CT steps down **current**; PT steps down **voltage**. Both also isolate the measuring circuit from the high-voltage line.
8. **CT burden** `S = I²R` VA at **rated secondary** current (typically 5 A or 1 A). Trap: using the primary current in the formula.
9. **CT ratio error** arises from the exciting current; a CT is compensated by reducing the turns ratio slightly.
10. **Systematic error** includes instrument defects, calibration error, and zero error. **Random error** is statistical. Trap: classifying an instrument defect as random.
11. **Accuracy vs precision:** accuracy = closeness to the true value; precision = repeatability. A precise instrument can be inaccurate.
12. **Error combination** `±(x% of reading + n digits)`: compute both, add them. For 2.000 V at ±(0.5% + 2 digits) with 1 mV resolution → `0.010 + 0.002 = 0.012 V`. Trap: applying the digit term as a percentage.
13. **Resolution** is the smallest detectable change (1 mV for a 3-decimal display). Trap: confusing resolution with accuracy.
14. **Loading effect:** a voltmeter must have **high** resistance (ideally infinite); an ammeter **low** (ideally zero). Trap: the reversed statement.
15. **CRO:** the **CRT** is the display core; the **time base** sets s/div, so total sweep = `divisions × timebase`. **Lissajous** figures give the frequency ratio from the number of loops/tangencies.
16. A **10:1 passive probe** raises the effective input resistance tenfold (1 MΩ scope → ~10 MΩ) and reduces capacitive loading. Trap: "attenuates the resistance".
17. **Oscilloscope phase measurement:** for a time difference `Δt` over period `T`, `φ = 360° × Δt/T`.

### PART B — ANALOG ELECTRONICS

18. **Inverting amp:** `Av = −Rf/Rin` (the negative sign matters). **Non-inverting:** `Av = 1 + Rf/R1`. Trap: dropping the "+1" — the most common slip in this block.
19. **Virtual short:** with negative feedback, the op-amp drives its inputs to the same potential. This is why the non-inverting gain has the +1.
20. **Ideal op-amp:** infinite gain, infinite input impedance, **zero output impedance**, infinite bandwidth, zero offset. Trap: reading the option set for the ONE property that is *not* ideal ("NOT true of an ideal op-amp").
21. **Integrator** `Vo = −(1/RC)∫Vi dt` with a **square-wave input gives a triangular output**. **Differentiator:** the reverse.
22. **Slew rate** `SR = dVo/dt|max = 2πf·Vm`. So `fmax = SR/(2πVm)`. Trap: forgetting the `2π` and using `SR/Vm`.
23. **Full-power bandwidth** is that `fmax` — above it the sine degrades into a **triangle**. Trap: "the output clips".
24. **Sallen-Key unity-gain LPF** `fc = 1/(2πRC)`. Roll-off **−40 dB/decade** for second-order. Gain at `fc` is `1/√2` = **−3 dB**.
25. **Gain in dB** `= 20 log₁₀(Vo/Vi)`. Half power = −3 dB; a decade = 20 dB; a factor of 2 ≈ 6 dB.
26. **CMRR** `= 20 log(A_d/A_cm)` — high CMRR is good. **Slew rate** and **CMRR** are the classic limitation parameters.
27. **Class-A amplifier** conducts for the full 360° and has the **lowest efficiency (≤ 25% with resistive load, 50% with transformer coupling)** but the best linearity. **Class-B** ≈ 78.5%. Trap: assigning the highest efficiency to Class-A.
28. **Q-point** must sit near the middle of the load line for maximum symmetrical swing. **Thermal runaway** in a BJT is countered by an **emitter resistor** (negative feedback).
29. **Transistor regions:** cutoff (both junctions reverse), active (EB forward, CB reverse), saturation (both forward). Trap: swapping active and saturation.

### PART C — DIGITAL ELECTRONICS

30. **ADC resolution** `= Vref/2ⁿ`. Quantization step (LSB) for 12 bits at 5 V = `5/4096 = 1.22 mV`. Trap: using `2ⁿ − 1` where `2ⁿ` is meant — read the stem.
31. **Quantization noise** (RMS) `= q/√12`, where `q` is the step size. Power `= q²/12`. SNR `≈ 6.02n + 1.76 dB`. Trap: the `√12` — not `√2`.
32. **DAC LSB** `= Vref/2ⁿ`; output `= LSB ×` (decimal input).
33. **Sample-and-hold droop** is the capacitor discharge during hold: `ΔV = I_leak·Δt/C`. Larger C → less droop but slower acquisition. Trap: claiming larger C speeds up acquisition.
34. **SAR ADC** takes `n` clock cycles for `n` bits; **flash ADC** is fastest but needs `2ⁿ − 1` comparators. Trap: attributing speed to SAR.
35. **Multiplexer** `2ⁿ` inputs → 1 output with `n` select lines. Trap: miscounting the select lines.
36. **Flip-flop max frequency:** `fmax = 1/(tsu + th + tpd)`. Trap: using only `tpd`.
37. **Counters:** a **mod-N** counter needs `⌈log₂N⌉` flip-flops. An `n`-bit ripple counter divides by `2ⁿ`.
38. **CMOS dynamic power** `P = α·C·V²·f`. Trap: the voltage is **squared**, and frequency is **linear**. This is where the classic numeric slip lives.
39. **CMOS static power** is ideally ~0 (only leakage). Trap: claiming CMOS burns power while static.
40. **Fan-out** = the number of gate inputs one output can drive. **Noise margin** = `VOH − VIH` (high) or `VIL − VOL` (low).
41. **K-map:** a group of `2ⁿ` adjacent 1s eliminates `n` variables; groups may wrap around the edges. Trap: allowing diagonal grouping, which is invalid.

---

## BLOCK TRAP TABLE (top 8)

| Trap | Example stem | Counter |
|---|---|---|
| Bridge → quantity | "Schering bridge measures?" | **capacitance** (Maxwell = L, Wien = f) |
| `Av` non-inverting | "non-inverting gain, Rf=39k, R1=1k" | `1 + Rf/R1 = 40`, not 39 |
| Slew rate `2π` | "max frequency from SR and Vm" | `f = SR/(2πVm)` |
| Quantization `√12` | "quantization noise RMS" | `q/√12` |
| CMOS power | "dynamic power vs V and f" | `αCV²f` — V **squared** |
| CT burden current | "CT VA burden" | use the **secondary** rated current |
| Class-A efficiency | "highest efficiency class?" | Class-**B** (78.5%); A is lowest |
| Error: digits vs % | "±(0.5% + 2 digits)" | add both; digits ≠ percentage |

## MEMORY ANCHORS
- **"Schering = Capacitance, Maxwell = inductance, Wien = frequency"** — SCMW.
- **Non-inverting always has the "+1"** ("non-inverting is never less than one").
- **`q/√12`** — "twelve angry quantizers".
- **CMOS: `αCV²f`** — "see squared eff".
- **Null instruments: Wheatstone, Kelvin, potentiometer, Schering** — they balance to zero.
- **Voltmeter high-Z, ammeter low-Z** ("volts high, amps low").

## DRILL RULES
1. Fire 2 Rapid-Card facts → 1 MCQ → verdict → next. 7–9 Qs per R6.
2. After each wrong MCQ, record the topic in the session log; re-test it in the mock.
3. Anchor phrasing: "Set 01 Q76 style" / "Set 02 Q62 style" — **never** "IOCL PYQ".
4. Skip every `[BROKEN SOURCE]` / `[AMBIGUOUS STEM]` question from `practice_iocl.md`.
