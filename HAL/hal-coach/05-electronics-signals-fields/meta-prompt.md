# HAL Coach — Block 05: ELECTRONICS + SIGNALS/DSP + EM FIELDS/MATERIALS (rapid sheet)
**Weightage: Analog 10 + Digital 13 + Signals/DSP 16 + EM/Materials 17 = 56 of 178 classified (2023+2025) → ★★☆ but wide | Engine slot: R4 | timebox ≈ 15–20 min (compressed one-liners)**

This is a *breadth block*: drill facts, not derivations. Move fast — one fact, one trap, one MCQ.

---

## PART A — ANALOG ELECTRONICS (~10 hits)

1. **Ideal op-amp characteristics:** infinite open-loop gain, infinite input impedance, **zero output impedance**, infinite bandwidth, zero offset. Trap (PYQ 2023 Q6): "Which is NOT a characteristic?" → a *finite* gain / *finite* BW option is the planted wrong-answer-to-pick.
2. Negative feedback: **reduces gain, increases bandwidth, reduces distortion/noise, stabilises gain**. Trap: "feedback increases ___?" → not gain (reduces it).
3. Inverting amp gain `= −Rf/Ri`; non-inverting `= 1 + Rf/R1`; voltage follower = buffer (unity gain, high Zin). Op-amp comparator → output saturates.
4. Diode: conducts forward (>0.7 V Si); **Zener operates in reverse breakdown** → voltage regulator. **Ripple factor: half-wave 1.21, full-wave 0.483** (lower → smoother); a capacitor filter charges to near peak and smooths.
5. BJT regions: **active (amplifier), cutoff, saturation (switch)**; CE = most used amplifier. FET/MOSFET: **voltage-controlled, very high input impedance**; BJT current-controlled.

## PART B — DIGITAL ELECTRONICS (~13 hits)

6. Gate vocabulary: **NOR = OR + NOT** (PYQ 2025 Q12); NAND = AND + NOT; De Morgan's laws. **NAND and NOR are universal gates → any combinational circuit using only NAND (or only NOR)** (PYQ 2023 Q32).
7. Number/data: **byte = 8 bits; ASCII = 7-bit** code (PYQ 2025 Q98/Q99 style); hex nibble = 4 bits. 2's complement = standard for signed numbers.
8. Flip-flops: **SR (invalid when S=R=1), JK (no invalid state — toggles), D (data), T (toggle)**. Edge-triggered vs level. Counters divide by 2ⁿ (mod-N).
9. MUX: 2ⁿ data inputs need n select lines (8:1 → 3 select). DEMUX opposite. SOP (sum of minterms) / POS forms (PYQ 2025).
10. Memory: RAM volatile / ROM non-volatile; registers; A/D converter — `n` bits → `2ⁿ` levels; step/quantization `= Vref/2ⁿ`.

## PART C — SIGNALS, SYSTEMS & DSP (~16 hits)

11. **Laplace transforms (PYQ 2023 Q41):** `ℒ{δ(t)} = 1`, `ℒ{u(t)} = 1/s`, `ℒ{1} = 1/s`, `ℒ{e^(−at)} = 1/(s+a)`, `ℒ{t} = 1/s²`. Trap: give the *time-shift* option instead of `1/s`.
12. **Fourier transform of a rectangular (rectangle) function = a sinc function** (PYQ 2025 Q2). Trap options: star/exponential/log.
13. **Direct N-point DFT = N² complex multiplications; FFT = (N/2)log₂N ≈ N log₂N** (PYQ 2025 Q66). Trap: DFT "N" vs "N²".
14. Energy vs power signals; periodic signal has discrete spectrum. **Sampling: fs ≥ 2·fmax (Nyquist)**; below → aliasing. z-transform ↔ digital TF; ROC.
15. LTI system: fully described by its **impulse response**; output = input convolved with h(t). Linear = superposition holds; time-invariant = shift-invariant.

## PART D — EM FIELDS, MAGNETIC CIRCUITS & MATERIALS (~17 hits)

16. **Permeability `μ = B/H`** = ratio of flux density (B, T) to field strength (H, A/m) (PYQ 2025 Q6). `B = μ₀μr·H`; relative permeability `μr` (air = 1). Trap: give "reluctance" or "susceptibility".
17. **CGS unit of magnetomotive force = Gilbert** (PYQ 2025 Q6); flux = **Maxwell**; flux density = **Gauss**; magnetizing force = **Oersted**. SI: MMF = Ampere-turn, flux = Weber, B = Tesla. Trap: Oersted (that's H).
18. **Biot–Savart's law (magnetic field from a current element) is analogous to Coulomb's law in electrostatics** (PYQ 2023 Q2). Also: Ampere's circuital law ↔ Gauss's law (closed-path vs closed-surface).
19. Maxwell's equations (integral): **Gauss for E (∮E·dA = Q/ε₀), Gauss for B (∮B·dA = 0), Faraday (∮E·dl = −dΦ/dt), Ampere–Maxwell (∮B·dl = μ₀I + μ₀ε₀ dΦe/dt)**. Trap: "which set is independent" (Gauss-law divergence equations come from curl equations + continuity in the time-varying case).
20. Force on a charge: `F = q(E + v×B)`; magnetic force does **no work** (⊥ to motion). Electric dipole moment `p = q·d`.
21. Materials: ferromagnets (Fe/Ni/Co) have high μr & hysteresis; **hysteresis loss ∝ area of the B-H loop**; silicon steel + laminations reduce eddy-current loss in transformer cores. Hard magnets = wide loop (high coercivity, permanent); soft = narrow loop. Trap: loop-area question.

---

## BLOCK TRAP TABLE (top 8)

| Trap | Example stem | Counter |
|---|---|---|
| NOT-op-amp phrasing | "NOT a characteristic of ideal op-amp?" | the finite-gain option |
| NAND/NOR universality | "combinational ckt with only ___?" | NAND or NOR |
| DFT count | "N-point DFT multiplications?" | N² (FFT: N·log₂N) |
| μ = B/H | "ratio of B to H is?" | permeability μ |
| CGS MMF unit | "CGS unit of MMF?" | Gilbert (Oersted = H) |
| ℒ{δ(t)} vs ℒ{u(t)} | "Laplace of unit step?" | 1/s (impulse = 1) |
| Rectangle Fourier | "FT of rectangular pulse?" | sinc |
| Biot–Savart analog | "analogous electrostatic law?" | Coulomb's |

## MEMORY ANCHORS
- **"NO."** = NOR = OR + **N**ot; NAND/NOR universal.
- **Gilbert = MMF; Weber = flux; Gauss = B; Oersted = H** (CGS set).
- `ℒ`: **step 1/s, ramp 1/s², ramp is 'step over s'**, impulse 1.
- Hysteresis loss ∝ **loop area**; eddy loss cut by **laminations/silicon steel**.

## DRILL RULES
- This block is a fire-hose: 6 Rapid Cards in a row, then 6-8 fast MCQs. Do NOT slow down for derivations.
- If time is short in a session, R4 is the first block to compress (lowest single-area marks per minute).
