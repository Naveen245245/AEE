# AP AEE — MATH PREREQUISITES: ONE-PAGE SUMMARY
> 5-Column Framework: Derivation → Real Life → Exam Form → Examiner Tweaks → Practice

---

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **1. Trigonometry** | sin²θ+cos²θ=1 from Pythagorean theorem on unit circle | PF = cosφ (lagging angle), AC sine waves, ωt in radians | sin 30°=0.5, cos 60°=0.5, tan 45°=1, √3/2≈0.866 | sin(30°+60°)=sin90°≠sin30°+sin60°, degrees vs radians, tan 90°=∞ | cosφ=0.8 → φ=36.87°, tanφ=4/3 → sinφ=4/5 |
| **2. Complex (j)** | j=√(-1), j²=-1, polar ↔ rectangular conversion | Impedance Z=R+jX, Inductor Z=jωL, Capacitor Z=1/jωC, Symmetrical components (a=1∠120°) | z=a+jb=r∠θ, r=√(a²+b²), θ=tan⁻¹(b/a), 1+j=√2∠45° | 1/j=-j (not +j), a+a²+1=0 always, polar addition→rectangular first | (3+j4)=5∠53.13°, Z₁×Z₂ in polar, j²+j⁴+j⁶=-1 |
| **3. Phasors** | V=V∠φ=RMS value, peak=V_m/√2, conversion to time domain | AC circuit analysis, generator E=V∠δ, resonance at XL=XC, power S=V×I* | V=I×Z, KVL/KCL in phasor form, tip-to-tail addition | \|V₁+V₂\|≠\|V₁\|+\|V₂\|, 230V=RMS not peak, current lags by -90° in inductor | V=230∠30° (RMS), Z=4+j3Ω→\|Z\|=5Ω |
| **4. Derivatives** | dy/dx=lim(Δx→0)[f(x+Δx)-f(x)]/Δx, rate of change | Capacitor: i=C×dv/dt, Inductor: v=L×di/dt, Faraday: e=-dΦ/dt | d/dt[sin(ωt)]=ωcos(ωt), d/dt[tⁿ]=ntⁿ⁻¹, d/dt[e^(at)]=ae^(at) | ω in rad/s (not deg/s), chain rule f(g(t))→f'(g)×g', d/dt[constant]=0 | dv/dt of 325sin(314t), i=C×dv/dt for capacitor |
| **5. Integration** | ∫f(x)dx=F(x)+C, area under curve, inverse of derivative | Average=∫f/T, RMS=√[∫f²/T], Energy=∫Pdt, capacitor ½CV², inductor ½LI² | ∫tⁿdt=tⁿ⁺¹/(n+1)+C, ∫sin(ωt)dt=-cos(ωt)/ω+C, V_rms=V_m/√2 | Average vs RMS (different formulas), constant C for indefinite, ln\|x\| not ln(x) | ∫(2t+3)dt, RMS derivation, half-cycle avg=2V_m/π |
| **6. Logarithms** | logₐ(b)=x means a^x=b, inverse of exponentiation | Bode plots: dB=20log\|G\|, decade=×10→20dB, cascaded gains add in dB | dB_power=10log₁₀(ratio), dB_voltage=20log₁₀(ratio), 6dB=×2 | log(xy)≠log(x)×log(y), 20dB≠×20 (it's ×10), power vs voltage dB | 40dB=×100, 3dB≈√2, -6dB=×0.5 |
| **7. Matrices** | [A][I]=[V], solve via [I]=[A]⁻¹[V] or Cramer's rule | Mesh/nodal analysis, two-port Z/Y/ABCD params, symmetrical components transform | \|A\|=ad-bc (2×2), A⁻¹=(1/\|A\|)×[d -b; -c a], multiplication row×col | AB≠BA (not commutative), \|A\|=0→no inverse, add same-sized only | Determinant [3 4;2 5]=7, solve 2 eqns, inverse |
| **8. Physics** | F=ma, P=W/t, P=VI, P=T×ω (torque×angular velocity) | Motor torque, heating P=I²R, energy in L/C, high V→low I→less loss | P=VI=I²R=V²/R, ω=2πN/60 rad/s, 1HP≈746W, E=½CV², E=½LI² | Weight(kg)→actually mass, HP vs W conversion, ω vs N (rad/s vs RPM) | 5kW×2h=10kWh, 150Nm@1000RPM=15.7kW |

---

## 🔑 HIGH-YIELD FORMULAS (Memorize)

```
| Concept | Formula | Topic |
|---------|---------|-------|
| sin²θ+cos²θ | = 1 | Trig |
| j² | = -1 | Complex |
| V_rms | = V_m/√2 | Phasor |
| d/dt[sin(ωt)] | = ωcos(ωt) | Derivative |
| ∫tⁿdt | = tⁿ⁺¹/(n+1)+C | Integration |
| dB (power) | = 10log₁₀(ratio) | Log |
| dB (voltage) | = 20log₁₀(ratio) | Log |
| \|A\| (2×2) | = ad-bc | Matrix |
| P=VI=I²R | = V²/R | Physics |
| ω | = 2πN/60 rad/s | Physics |
```

## ⚠️ EXAMINER TWEAK QUICK REFERENCE

| Trap | Counter |
|------|---------|
| sin(30°+60°)≠sin30°+sin60° | Use formulas, not numeric addition |
| 1/j = -j (not +j) | Remember: multiply top and bottom by j |
| Average ≠ RMS | Average=∫f/T, RMS=√[∫f²/T] |
| 20dB = ×10 (not ×20) | 20dB means ratio of 10 |
| AB ≠ BA (matrices) | Matrix mult is NOT commutative |
| ω in rad/s (not deg) | Always convert degrees to radians |
| \|V₁+V₂\| ≠ \|V₁\|+\|V₂\| | Must use phasor addition |
| Half voltage = -6dB, Half power = -3dB | Different formulas! |

---

## 📊 MARKS WEIGHTAGE

| Topic | Direct Marks | Indirect (in other subjects) |
|-------|-------------|----------------------------|
| Trigonometry + Phasors | 3-5 | ~15 (circuits, machines) |
| Complex Numbers | 2-4 | ~10 (impedance, faults) |
| Calculus | 2-3 | ~15 (control, transients) |
| Logarithms | 1-2 | ~5 (Bode plots) |
| Matrices | 2-4 | ~5 (mesh analysis) |
| Physics | 3-5 | ~10 (machines, power) |
| **TOTAL** | **10-15 direct** | **~66 indirect** |

---

> **Remember:** 70-80% of the exam depends on these math skills. Master them once, apply them everywhere!
