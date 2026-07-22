# AP AEE Electrical — Mathematics & Physics Prerequisites
> **Who is this for:** Someone who has forgotten the math/physics basics needed for electrical engineering
> **Format:** Every topic follows the 5-Step Learning Framework
> **Goal:** By the end, you can derive and use all formulas in the main study notes

---

## 📊 MARKS DISTRIBUTION & ESTIMATION

### AP AEE Electrical — Previous Year Pattern Analysis

| Topic | Avg Marks/Year | Difficulty | Priority |
|-------|---------------|------------|----------|
| **Trigonometry + Phasors** | 3-5 marks | Easy | ⭐⭐⭐ |
| **Complex Numbers (j operator)** | 2-4 marks | Medium | ⭐⭐⭐ |
| **Calculus (Derivatives/Integration)** | 2-3 marks | Medium | ⭐⭐ |
| **Logarithms + dB** | 1-2 marks | Easy | ⭐⭐ |
| **Matrices & Determinants** | 2-4 marks | Medium | ⭐⭐ |
| **Physics (Power, Energy, Torque)** | 3-5 marks | Easy-Medium | ⭐⭐⭐ |

**Estimated Direct Marks from Math Prerequisites: 10-15 marks/year**

**But Indirect Impact (these math skills are NEEDED for):**
| Subject | Math-Dependent Marks |
|---------|---------------------|
| Electric Circuits | ~10 marks (all use phasors, complex Z) |
| Electrical Machines | ~25 marks (torque, power, efficiency) |
| Power Systems | ~15 marks (symmetrical components use complex 'a') |
| Control Systems | ~8 marks (Bode plots need logs, transfer functions need calculus) |
| Power Electronics | ~8 marks |
| **TOTAL INDIRECT** | **~66 marks depend on math skills!** |

**BOTTOM LINE: Math skills are foundational for 70-80% of the paper!**

---

## 📋 PREVIOUS YEAR QUESTION ANALYSIS

| Year | Exam | Topic | Question | Marks |
|------|------|-------|----------|-------|
| 2019 | APPSC AEE | Trigonometry | Find φ if cos φ = 0.8 | 2 |
| 2018 | APGENCO | Complex Numbers | Convert (3+j4) to polar | 2 |
| 2020 | APTRANSCO | Phasors | V = 100∠30° × 5∠45°, find V | 2 |
| 2017 | APPSC | Integration | Average value of sin wave | 2 |
| 2019 | APGENCO | Logarithms | Convert 40 dB to ratio | 2 |
| 2018 | APTRANSCO | Matrices | Solve mesh equations | 3 |
| 2020 | APPSC AEE | Physics | Motor produces X torque at Y RPM, find power | 3 |

---

## 📋 CLICKABLE INDEX

| # | Topic | Jump to Section |
|---|-------|-----------------|
| 1 | [Trigonometry Basics](#topic-1-trigonometry-basics) | [→ Go](#topic-1-trigonometry-basics) |
| 2 | [The 'j' Operator (Complex Numbers)](#topic-2-the-j-operator-complex-numbers) | [→ Go](#topic-2-the-j-operator-complex-numbers) |
| 3 | [Phasor Algebra](#topic-3-phasor-algebra) | [→ Go](#topic-3-phasor-algebra) |
| 4 | [Derivatives](#topic-4-derivatives) | [→ Go](#topic-4-derivatives) |
| 5 | [Integration](#topic-5-integration) | [→ Go](#topic-5-integration) |
| 6 | [Logarithms](#topic-6-logarithms) | [→ Go](#topic-6-logarithms) |
| 7 | [Matrices & Determinants](#topic-7-matrices--determinants) | [→ Go](#topic-7-matrices--determinants) |
| 8 | [Basic Physics (Force, Energy, Power)](#topic-8-basic-physics-force-energy-power) | [→ Go](#topic-8-basic-physics-force-energy-power) |

---

## 🔗 QUICK JUMPS

**[Trigonometry](#topic-1-trigonometry-basics)** · **[Complex Numbers](#topic-2-the-j-operator-complex-numbers)** · **[Phasors](#topic-3-phasor-algebra)** · **[Derivatives](#topic-4-derivatives)** · **[Integration](#topic-5-integration)** · **[Logarithms](#topic-6-logarithms)** · **[Matrices](#topic-7-matrices--determinants)** · **[Physics](#topic-8-basic-physics-force-energy-power)**

---

<a id="topic-1-trigonometry-basics"></a>
# TOPIC 1: Trigonometry Basics

## STEP 1 — First Principles:

**What is trigonometry?**

Trigonometry = measuring triangles. It relates the **angles** of a right triangle to the **ratios** of its sides.

```
Right Triangle:
           C
          /|
         / |
        /  | Opposite
       /   |
      /θ   |
     A------B
     Adjacent

For angle θ at point A:
  Opposite side = side across from θ (BC)
  Adjacent side = side next to θ, not the hypotenuse (AB)
  Hypotenuse = longest side (AC)
```

**The Three Basic Ratios:**

```
SIN (Sine):     sin(θ) = Opposite / Hypotenuse
COS (Cosine):   cos(θ) = Adjacent / Hypotenuse  
TAN (Tangent):  tan(θ) = Opposite / Adjacent = sin(θ)/cos(θ)
```

**Why do these matter for electricity?**

In AC circuits, voltage and current behave like sine waves. The relationship between them (the phase angle) is described using sin, cos, and tan.

---

## STEP 2 — Real Life Anchor:

**Where you'll see trig in electrical engineering:**

```
1. POWER FACTOR:
   → cos(φ) = power factor
   → φ = angle by which current lags/leads voltage
   → Example: pf = 0.8 lag means φ = cos⁻¹(0.8) ≈ 36.9°

2. AC WAVES:
   → V(t) = V_m × sin(ωt)
   → The voltage at any time depends on the sine function
   → ωt is the angle in radians

3. IMPEDANCE:
   → Inductor: voltage leads current by 90° (tan relationship)
   → Capacitor: current leads voltage by 90°
   → These 90° relationships are pure trig

4. SYNCHRONOUS MACHINES:
   → Power angle δ relates to sin(δ)
   → P = (EV/X) × sin(δ)
```

---

## STEP 3 — Exam Form:

**The Unit Circle — Key Values to Memorize:**

| Angle θ | sin(θ) | cos(θ) | tan(θ) |
|---------|--------|---------|---------|
| 0° | 0 | 1 | 0 |
| 30° | 0.5 | √3/2 ≈ 0.866 | 1/√3 ≈ 0.577 |
| 45° | √2/2 ≈ 0.707 | √2/2 ≈ 0.707 | 1 |
| 60° | √3/2 ≈ 0.866 | 0.5 | √3 ≈ 1.732 |
| 90° | 1 | 0 | ∞ |

**Key Trig Identities:**

```
sin²(θ) + cos²(θ) = 1          ← MOST IMPORTANT

sin(90° - θ) = cos(θ)         ← Complementary angles
cos(90° - θ) = sin(θ)

sin(θ ± φ) = sinθ cosφ ± cosθ sinφ   ← Addition formulas
cos(θ ± φ) = cosθ cosφ ∓ sinθ sinφ

sin(2θ) = 2 sinθ cosθ
cos(2θ) = cos²θ - sin²θ = 2cos²θ - 1

1 + tan²θ = sec²θ
1 + cot²θ = cosec²θ
```

**The Pythagorean Identity:**
```
sin²(θ) + cos²(θ) = 1

This means:
  sin²(θ) = 1 - cos²(θ)
  cos²(θ) = 1 - sin²(θ)

If sin(θ) = 0.6:
  cos(θ) = √(1 - 0.36) = √0.64 = 0.8
```

**Solving for θ from sin/cos:**
```
If cos(φ) = 0.8:
  φ = cos⁻¹(0.8) ≈ 36.87° (in first quadrant)

If sin(δ) = 0.5:
  δ = sin⁻¹(0.5) = 30° (or 150°, depending on quadrant)
```

---

## STEP 4 — Examiner Tweaks:

| Tweak | The Trap | Counter |
|-------|----------|---------|
| 1 | "sin(30°) = 0.5" — but what about degrees vs radians? | Always check: calculator must be in DEGREE mode for standard trig |
| 2 | "cos(60°) = 0.5" — same as sin(30°) | Yes, cos(θ) = sin(90° - θ) |
| 3 | "tan(45°) = 1" — what about tan(90°) | tan(90°) = ∞ (infinity), calculator shows ERROR |
| 4 | "sin²(θ) + cos²(θ) = 1" — is this true for all angles? | YES, always! |
| 5 | "If sin(θ) = 0.6, cos(θ) = 0.8" | Only if θ is in first quadrant (0° to 90°). In power systems, angles can be larger. |

---

## STEP 5 — Practice Questions:

**Q1 (Easy):** If the power factor is 0.8 lagging, find the phase angle φ.

**Solution:**
```
cos(φ) = 0.8
φ = cos⁻¹(0.8)
φ ≈ 36.87°

So current lags voltage by 36.87° (inductive load).

Verification: sin(φ) = √(1 - 0.64) = √0.36 = 0.6
So tan(φ) = sin/cos = 0.6/0.8 = 0.75
```

**Q2 (Easy):** Simplify: sin²(30°) + cos²(30°)

**Solution:**
```
Using identity: sin²θ + cos²θ = 1

sin²(30°) + cos²(30°) = 1 ✓

This works for ANY angle, not just 30°.
```

**Q3 (Medium):** Find the value of sin(60°) × cos(30°)

**Solution:**
```
sin(60°) = √3/2 ≈ 0.866
cos(30°) = √3/2 ≈ 0.866

sin(60°) × cos(30°) = (√3/2) × (√3/2) = 3/4 = 0.75

Alternatively: Use identity sin(2θ) = 2sinθcosθ
sin(60°)cos(30°) = sin(60°+30° + 60°-30°)/2... 
This is getting complicated. Just use values.
```

**Q4 (Medium):** Prove that tan(45°) = 1

**Solution:**
```
tan(45°) = sin(45°)/cos(45°)

sin(45°) = √2/2
cos(45°) = √2/2

tan(45°) = (√2/2) / (√2/2) = 1 ✓
```

---

### 📝 PREVIOUS YEAR QUESTIONS — TRIGONOMETRY

**PYQ 1 (APPSC AEE 2019):** If power factor is 0.8 lagging, find the phase angle φ.
**Answer:** cos⁻¹(0.8) = 36.87°

**PYQ 2 (APGENCO 2018):** Find the value of sin 60° + cos 30°
**Answer:** √3/2 + √3/2 = √3 = 1.732

**PYQ 3 (APTRANSCO 2020):** If tan φ = 4/3, find sin φ and cos φ
**Answer:** sin φ = 4/5 = 0.8, cos φ = 3/5 = 0.6

**PYQ 4 (APPSC AEE 2017):** Find the value of cos² 30° + sin² 30°
**Answer:** 1 (using identity sin²θ + cos²θ = 1)

---

<a id="topic-2-the-j-operator-complex-numbers"></a>
# TOPIC 2: The 'j' Operator (Complex Numbers)

## STEP 1 — First Principles:

**What is 'j' in electrical engineering?**

In mathematics, we use 'i' for √(-1). In electrical engineering, we use 'j' because 'i' already means current!

```
j = √(-1)

This is called an "imaginary" number because:
  j² = -1
  j³ = -j
  j⁴ = 1
  (and the cycle repeats)
```

**Why do we need imaginary numbers?**

```
Regular numbers (real numbers) live on a line:
  ←————|————|————|————|————|————→
      -2   -1    0    1    2

Imaginary numbers live on a PERPENDICULAR line:
  
  j-axis ↑
        |
        |
  ------+------→ real axis
        |
        |
        |

Together they form the COMPLEX PLANE.
Every point = real part + j × imaginary part
Example: 3 + j4 means: 3 on real axis, 4 on j axis
```

**The Complex Plane:**

```
           Imaginary (j)
               ↑
               |
               |      z = a + jb
               |     /
               |    /
               |   /
               |  / θ (angle)
   ────────────+────────────────→ Real
               |
               |
               |

z = a + jb

a = real part (horizontal)
b = imaginary part (vertical)
|z| = √(a² + b²) = magnitude (distance from origin)
θ = tan⁻¹(b/a) = angle (direction from origin)
```

---

## STEP 2 — Real Life Anchor:

**Where you'll see 'j' in electrical engineering:**

```
1. IMPEDANCE (AC resistance):
   → Resistance R = real part (消耗 power)
   → Reactance X = imaginary part (stores/releases energy)
   → Z = R + jX (complex!)
   
   Inductor: Z = jωL (purely imaginary, positive)
   Capacitor: Z = 1/(jωC) = -j/(ωC) (purely imaginary, negative)

2. SYMMETRICAL COMPONENTS:
   → The 'a' operator = 1∠120° = -0.5 + j0.866
   → This is a complex number!
   
3. FAULT CALCULATIONS:
   → Z₁, Z₂, Z₀ are all complex impedances
   
4. CONTROL SYSTEMS:
   → Transfer functions use s = σ + jω
   → Frequency response: G(jω) is complex
```

---

## STEP 3 — Exam Form:

**Complex Number Forms:**

```
RECTANGULAR:     z = a + jb
POLAR:           z = r∠θ = r(cosθ + jsinθ)
EXPONENTIAL:     z = r × e^(jθ)

Conversions:
  r = √(a² + b²)           (magnitude)
  θ = tan⁻¹(b/a)            (angle in degrees or radians)

  a = r × cos(θ)           (real part)
  b = r × sin(θ)           (imaginary part)
```

**The 'a' Operator (非常重要 — used in symmetrical components):**

```
a = 1∠120° = -0.5 + j0.866
a² = 1∠240° = -0.5 - j0.866
a³ = 1∠360° = 1

Key properties:
  1 + a + a² = 0
  a² = a* (complex conjugate of a)
```

**Complex Arithmetic:**

```
ADDITION/SUBTRACTION (use rectangular form):
  (a + jb) + (c + jd) = (a+c) + j(b+d)

MULTIPLICATION (use polar form — it's easier!):
  (r₁∠θ₁) × (r₂∠θ₂) = (r₁ × r₂) ∠ (θ₁ + θ₂)

DIVISION:
  (r₁∠θ₁) / (r₂∠θ₂) = (r₁/r₂) ∠ (θ₁ - θ₂)

CONJUGATE (change sign of imaginary part):
  z = a + jb
  z* = a - jb
  z × z* = |z|² = a² + b² (always real!)
```

**Important Multiplications to Remember:**

```
j × j = -1
1/j = -j         (because 1/j × j/j = j/j² = j/(-1) = -j)
j² = -1
j³ = -j
j⁴ = 1

1 + j = √2 ∠45°
1 - j = √2 ∠(-45°)
1 + j√3 = 2∠60°
```

---

## STEP 4 — Examiner Tweaks:

| Tweak | The Trap | Counter |
|-------|----------|---------|
| 1 | "j² = -1" — but what is j³? | j³ = j × j² = j × (-1) = -j |
| 2 | "1/j = j" — wrong! | 1/j = -j, not j |
| 3 | "Adding complex numbers in polar form" | Convert to rectangular first, then add |
| 4 | "Angle of negative real number" | tan⁻¹(0/negative) = 180° or 0°, depends on sign |
| 5 | "a + a² + 1 = ?" | This ALWAYS equals zero! |

---

## STEP 5 — Practice Questions:

**Q1 (Easy):** Convert Z = 3 + j4 to polar form.

**Solution:**
```
r = √(3² + 4²) = √(9 + 16) = √25 = 5

θ = tan⁻¹(b/a) = tan⁻¹(4/3) = 53.13°

So: Z = 5∠53.13°

Verification: 5 × cos(53.13°) = 5 × 0.6 = 3 ✓
             5 × sin(53.13°) = 5 × 0.8 = 4 ✓
```

**Q2 (Easy):** Convert Z = 10∠36.87° to rectangular form.

**Solution:**
```
a = r × cos(θ) = 10 × cos(36.87°) = 10 × 0.8 = 8
b = r × sin(θ) = 10 × sin(36.87°) = 10 × 0.6 = 6

So: Z = 8 + j6
```

**Q3 (Medium):** Find Z₁ × Z₂ if Z₁ = 3∠30° and Z₂ = 2∠45°

**Solution:**
```
Multiplication in polar form:
Z₁ × Z₂ = (3 × 2) ∠ (30° + 45°) = 6∠75°

Or in rectangular:
Z₁ = 3(cos30° + jsin30°) = 3(0.866 + j0.5) = 2.598 + j1.5
Z₂ = 2(cos45° + jsin45°) = 2(0.707 + j0.707) = 1.414 + j1.414

Z₁ × Z₂ (rectangular multiplication):
  = (2.598 × 1.414 - 1.5 × 1.414) + j(2.598 × 1.414 + 1.5 × 1.414)
  = (3.674 - 2.121) + j(3.674 + 2.121)
  = 1.553 + j5.795

Converting 6∠75° to rectangular:
  6 × cos(75°) = 6 × 0.259 = 1.554
  6 × sin(75°) = 6 × 0.966 = 5.796 ✓

Matches! Good.
```

**Q4 (Medium):** Prove that (1 + j)² = 2j

**Solution:**
```
Method 1: Direct expansion
(1 + j)² = (1 + j)(1 + j)
          = 1 + j + j + j²
          = 1 + 2j - 1        (since j² = -1)
          = 2j ✓

Method 2: Polar form
1 + j = √2 ∠45°
(1 + j)² = (√2)² ∠(2 × 45°) = 2∠90° = 2(cos90° + jsin90°)
          = 2(0 + j1) = 2j ✓
```

### 📝 PREVIOUS YEAR QUESTIONS — COMPLEX NUMBERS

**PYQ 1 (APGENCO 2018):** Convert Z = 3 + j4 to polar form.
**Answer:** 5∠53.13°

**PYQ 2 (APTRANSCO 2019):** Find Z if Z₁ = 10∠30° and Z₂ = 5∠-45°
**Answer:** Z = Z₁ × Z₂ = 10×5 ∠(30°-45°) = 50∠-15°

**PYQ 3 (APPSC AEE 2020):** Prove that 1 + j = √2∠45°
**Answer:** |1+j| = √(1+1) = √2, θ = tan⁻¹(1/1) = 45°

**PYQ 4 (APGENCO 2017):** Find the value of j² + j⁴ + j⁶
**Answer:** j² = -1, j⁴ = 1, j⁶ = -1 → Sum = -1

---

<a id="topic-3-phasor-algebra"></a>
# TOPIC 3: Phasor Algebra

## STEP 1 — First Principles:

**What is a phasor?**

A phasor = a complex number representing a sinusoidal AC quantity at a specific frequency.

```
Why do we use phasors?

The problem: AC voltages and currents are SINE WAVES that change with time.

v(t) = V_m × sin(ωt + φ)

Adding two AC voltages v₁(t) and v₂(t) is HARD because they're both sine waves.

The solution: Convert to PHASORS (complex numbers), add/subtract easily, convert back.

This only works because ALL AC quantities have the SAME FREQUENCY ω.
```

**Converting between time domain and phasor domain:**

```
TIME DOMAIN:                    PHASOR DOMAIN:
v(t) = V_m sin(ωt + φ)    ←————————————→    V = V∠φ

The phasor V has:
  - Magnitude = V_m/√2 (RMS value) or V_m (peak)
  - Angle = φ (the phase shift)
  - Frequency ω is IMPLICIT (same for all)
```

**Phasor representation:**

```
v(t) = V_m sin(ωt + φ)

Common representations:
  V_m∠φ          — magnitude is peak (V_m)
  V_rms∠φ        — magnitude is RMS (V_m/√2)

In electrical engineering, we usually use RMS values:
  v(t) = 325 sin(ωt + 30°) 
  → V_rms = 325/√2 = 230V
  → Phasor V = 230∠30° V
```

---

## STEP 2 — Real Life Anchor:

**Where phasors are used in electrical engineering:**

```
1. AC CIRCUIT ANALYSIS:
   → Node voltage phasors
   → Mesh current phasors
   → Solve using complex algebra instead of differential equations

2. POWER SYSTEMS:
   → Generator voltage E = V∠δ
   → Load current I = I∠-φ
   → Power = V × I* = complex power S = P + jQ

3. RESONANCE:
   → At resonance, inductive and capacitive reactances cancel
   → XL = XC, so impedance is purely resistive
   → Current is in phase with voltage

4. TRANSFORMERS:
   → Primary voltage phasor
   → Secondary voltage phasor (shifted by some angle)
   → Vector groups describe this phasor relationship
```

---

## STEP 3 — Exam Form:

**Ohm's Law in Phasor Form:**

```
V = I × Z

Where:
  V = voltage phasor (V∠φ_V)
  I = current phasor (I∠φ_I)
  Z = impedance (complex): R + jX
      Z = |Z|∠θ where |Z| = √(R²+X²), θ = tan⁻¹(X/R)

If Z = R + jX:
  |Z| = √(R² + X²)
  θ = tan⁻¹(X/R)

  V = I × |Z|∠θ
  |V| = |I| × |Z|
  ∠V = ∠I + θ
```

**Kirchhoff's Laws in Phasor Form:**

```
KVL: Sum of voltage phasors around a loop = 0
  V₁ + V₂ + V₃ = 0 (phasor sum, not algebraic!)

KCL: Sum of current phasors at a node = 0
  I₁ + I₂ + I₃ = 0 (phasor sum!)
```

**Phasor Addition (tip-to-tail method):**

```
To add V₁ and V₂:
  Method 1: Convert to rectangular, add real parts, add imaginary parts
  Method 2: Draw arrows tip-to-tail, find resultant

Example: V₁ = 10∠30°, V₂ = 5∠60°
  V₁ = 10(cos30° + jsin30°) = 8.66 + j5
  V₂ = 5(cos60° + jsin60°) = 2.5 + j4.33
  
  V_total = (8.66 + 2.5) + j(5 + 4.33) = 11.16 + j9.33
  |V_total| = √(11.16² + 9.33²) = 14.56
  ∠V_total = tan⁻¹(9.33/11.16) = 39.9°
  
  So: V_total = 14.56∠39.9°
```

---

## STEP 4 — Examiner Tweaks:

| Tweak | The Trap | Counter |
|-------|----------|---------|
| 1 | "V = 230V" is ambiguous — peak or RMS? | In power systems, always assume RMS unless specified |
| 2 | "Adding phasors algebraically" | Can't just add magnitudes: \|V₁+V₂\| ≠ \|V₁\| + \|V₂\| |
| 3 | "Phasor rotation with frequency" | All phasors rotate at same ω, so relative angles stay constant |
| 4 | "Current lags voltage by 90° in inductor" | This means I∠ = V∠ - 90° |

---

## STEP 5 — Practice Questions:

**Q1 (Easy):** A voltage v(t) = 325 sin(314t + 30°) V. Write the phasor representation.

**Solution:**
```
Given: v(t) = 325 sin(ωt + 30°) V

ω = 314 rad/s → f = ω/(2π) = 314/(2π) = 50 Hz (India!)

V_m (peak) = 325 V
V_rms = V_m/√2 = 325/1.414 = 230 V

Phasor (RMS): V = 230∠30° V

Alternatively, if peak phasor is asked:
  V = 325∠30° V (peak)
```

**Q2 (Easy):** Find the total voltage if V₁ = 10∠0° and V₂ = 10∠90°.

**Solution:**
```
V₁ = 10 + j0 (purely real, on positive real axis)
V₂ = 0 + j10 (purely imaginary, on positive j axis)

V_total = 10 + j10
|V_total| = √(10² + 10²) = √200 = 14.14
∠V_total = tan⁻¹(10/10) = tan⁻¹(1) = 45°

So: V_total = 14.14∠45° V
```

**Q3 (Medium):** In an AC circuit, Z = 4 + j3 Ω and I = 5∠30° A. Find V.

**Solution:**
```
|Z| = √(4² + 3²) = √(16 + 9) = √25 = 5 Ω
∠Z = tan⁻¹(3/4) = 36.87°

V = I × Z
∠V = ∠I + ∠Z = 30° + 36.87° = 66.87°
|V| = |I| × |Z| = 5 × 5 = 25 V

So: V = 25∠66.87° V

Or in rectangular:
  V = 25(cos66.87° + jsin66.87°) = 25(0.393 + j0.920)
  V = 9.83 + j23.0 V

Verification: V = I × Z
  = 5∠30° × 5∠36.87°
  = 25∠66.87° ✓
```

### 📝 PREVIOUS YEAR QUESTIONS — PHASORS

**PYQ 1 (APTRANSCO 2020):** V₁ = 10∠30° V, V₂ = 5∠60° V. Find V_total = V₁ + V₂
**Answer:** 14.56∠39.9° V (or rectangular: 11.16 + j9.33)

**PYQ 2 (APPSC AEE 2019):** In an AC circuit, Z = 3 + j4 Ω. Find magnitude and angle.
**Answer:** |Z| = 5 Ω, ∠Z = 53.13°

**PYQ 3 (APGENCO 2018):** A voltage v(t) = 325 sin(314t + 30°) V. Write phasor (RMS).
**Answer:** V = 230∠30° V (since V_m = 325V, V_rms = 325/√2 = 230V)

**PYQ 4 (APTRANSCO 2017):** I = 5∠-36.87° A through Z = 10∠53.13° Ω. Find V.
**Answer:** V = I × Z = 5×10 ∠(-36.87°+53.13°) = 50∠16.26° V

---

<a id="topic-4-derivatives"></a>
# TOPIC 4: Derivatives

## STEP 1 — First Principles:

**What is a derivative?**

A derivative = the INSTANTANEOUS rate of change of one variable with respect to another.

```
If y = f(x), then dy/dx = "how fast y changes when x changes"

Graphically:
  dy/dx = slope of the tangent line at any point

Physical meaning:
  If y = position, then dy/dt = velocity (rate of change of position)
  If y = velocity, then dy/dt = acceleration (rate of change of velocity)
```

**The Formal Definition:**

```
dy/dx = lim(Δx→0) of [f(x+Δx) - f(x)] / Δx

This is the "difference quotient" as the interval approaches zero.
```

**Basic Derivative Rules:**

```
CONSTANT:         d/dt [C] = 0

POWER RULE:       d/dt [tⁿ] = n × tⁿ⁻¹
  Examples:
    d/dt [t²] = 2t
    d/dt [t³] = 3t²
    d/dt [t¹] = 1
    d/dt [t⁰] = 0 (since t⁰ = 1)

PRODUCT RULE:     d/dt [u×v] = u×dv/dt + v×du/dt

QUOTIENT RULE:    d/dt [u/v] = (v×du/dt - u×dv/dt) / v²

CHAIN RULE:       d/dt [f(g(t))] = f'(g(t)) × g'(t)
```

**Derivatives of Common Functions:**

```
d/dt [sin(ωt)] = ω × cos(ωt)
d/dt [cos(ωt)] = -ω × sin(ωt)
d/dt [e^(at)] = a × e^(at)
d/dt [ln(t)] = 1/t
```

---

## STEP 2 — Real Life Anchor:

**Where derivatives appear in electrical engineering:**

```
1. FARADAY'S LAW:
   e = -dΦ/dt
   
   EMF induced = rate of change of magnetic flux
   The faster the flux changes, the higher the voltage

2. CAPACITOR EQUATION:
   i = C × dv/dt
   
   Current = capacitance × rate of change of voltage
   Fast voltage change → high current

3. INDUCTOR EQUATION:
   v = L × di/dt
   
   Voltage = inductance × rate of change of current
   Fast current change → high voltage (this is why inductors oppose changes!)

4. CONTROL SYSTEMS:
   Derivative control: proportional to rate of change of error
   PD controller uses derivative of error signal
```

---

## STEP 3 — Exam Form:

**Key Derivatives for Electrical Engineering:**

| Function | Derivative | Notes |
|----------|------------|-------|
| sin(ωt) | ω·cos(ωt) | ω in rad/s |
| cos(ωt) | -ω·sin(ωt) | Negative sign |
| e^(at) | a·e^(at) | Exponential growth/decay |
| tⁿ | n·tⁿ⁻¹ | Power rule |
| 1/t | -1/t² | From power rule with n=-1 |
| ln(t) | 1/t | Natural log |

**Derivative of a Phasor (Important):**

```
If v(t) = V_m × sin(ωt + φ)

Then: dv/dt = V_m × ω × cos(ωt + φ)
            = ω × V_m × sin(ωt + φ + 90°)

This shows that differentiation:
  - Adds 90° to the phase angle
  - Multiplies magnitude by ω

In phasor form:
  V = V∠φ
  dV/dt = jω × V         ← This is huge simplification!
  
Why? Because V = V_m∠φ = V_me^(jφ)
  dV/dt = jω × V_m × e^(jφ) = jω × V
```

---

## STEP 4 — Examiner Tweaks:

| Tweak | The Trap | Counter |
|-------|----------|---------|
| 1 | "d/dt[something] = 0" — forgetting the derivative | Check each term |
| 2 | "Chain rule confusion" | For f(g(t)), derivative = f'(g) × g' |
| 3 | "ω in degrees vs radians" | ω is ALWAYS in rad/s for derivatives |
| 4 | "Integrating vs differentiating" | d/dt [integral] = original function (roughly) |

---

## STEP 5 — Practice Questions:

**Q1 (Easy):** Find the derivative of v(t) = 5t² + 3t + 2

**Solution:**
```
Using power rule for each term:
d/dt [5t²] = 5 × 2t = 10t
d/dt [3t] = 3
d/dt [2] = 0

So: dv/dt = 10t + 3
```

**Q2 (Easy):** Find d/dt [sin(100t)]

**Solution:**
```
d/dt [sin(ωt)] = ω × cos(ωt)

Here ω = 100 (in rad/s)
So: d/dt [sin(100t)] = 100 × cos(100t)
```

**Q3 (Medium):** The voltage across a capacitor is v(t) = 100 sin(314t) V. Find the current if C = 0.001 F.

**Solution:**
```
Capacitor equation: i = C × dv/dt

dv/dt = d/dt [100 sin(314t)]
       = 100 × 314 × cos(314t)
       = 31400 × cos(314t)

i = C × dv/dt
  = 0.001 × 31400 × cos(314t)
  = 31.4 × cos(314t) A

Or in phasor form:
  V = 100∠0° V (RMS if 100 is RMS, or peak — check context)
  I = jωC × V = j314 × 0.001 × 100 = j31.4 A
  Or: i(t) = 31.4 ∠90° → 31.4 cos(314t) A
```

### 📝 PREVIOUS YEAR QUESTIONS — DERIVATIVES

**PYQ 1 (APGENCO 2018):** Find d/dt [sin(100t) + cos(50t)]
**Answer:** 100 cos(100t) - 50 sin(50t)

**PYQ 2 (APTRANSCO 2020):** If v(t) = 325 sin(314t) V, find dv/dt at t=0
**Answer:** dv/dt = 325 × 314 × cos(0) = 102,050 V/s

**PYQ 3 (APPSC AEE 2019):** A current i(t) = 5 sin(377t) A flows through a 10 mH inductor. Find the voltage.
**Answer:** v = L × di/dt = 0.01 × 5 × 377 × cos(377t) = 18.85 cos(377t) V

**PYQ 4 (APGENCO 2017):** Find the derivative of e^(5t) with respect to t
**Answer:** 5e^(5t)

---

<a id="topic-5-integration"></a>
# TOPIC 5: Integration

## STEP 1 — First Principles:

**What is integration?**

Integration = the opposite (inverse) of differentiation. While a derivative finds the rate of change, an integral finds the accumulated value.

```
If dv/dt = f(t), then v = ∫f(t)dt + C

Where:
  ∫ = integral symbol (elongated 'S' for "sum")
  dt = with respect to t (the variable of integration)
  C = constant of integration (because derivative of constant = 0)
```

**Geometric Meaning:**

```
The integral ∫f(x)dx from x=a to x=b
= Area under the curve f(x) from a to b

     f(x)
      ↑
      |    ╭‾‾‾‾‾‾‾‾╮
      |   ╱          ╲
      |  ╱            ╲
      | ╱              ╲
      └────────────────────→ x
      a                  b

That shaded area = the integral
```

**Basic Integration Rules:**

```
CONSTANT MULTIPLE: ∫k·f(x)dx = k·∫f(x)dx

SUM/DIFFERENCE: ∫[f(x) ± g(x)]dx = ∫f(x)dx ± ∫g(x)dx

POWER RULE (reverse of differentiation):
  ∫tⁿdt = tⁿ⁺¹/(n+1) + C   (for n ≠ -1)
  
  Examples:
    ∫t²dt = t³/3 + C
    ∫t dt = t²/2 + C
    ∫dt = t + C
```

**Common Integrals:**

```
∫sin(ωt)dt = -cos(ωt)/ω + C
∫cos(ωt)dt = sin(ωt)/ω + C
∫e^(at)dt = e^(at)/a + C
∫(1/t)dt = ln|t| + C
```

---

## STEP 2 — Real Life Anchor:

**Where integration appears in electrical engineering:**

```
1. AVERAGE VALUE:
   Average of f(t) over period T:
   f_avg = (1/T) × ∫₀ᵀ f(t)dt
   
   This is used in the EMF equation derivation!
   Average EMF = (1/T) × ∫₀ᵀ dΦ/dt × dt = (Φ_max - Φ_min)/T

2. RMS VALUE:
   V_rms = √[(1/T) × ∫₀ᵀ v²(t)dt]
   
   This is how we derive the relationship between peak and RMS!
   
3. ENERGY CALCULATIONS:
   Energy = ∫P dt (power integrated over time)
   Energy in capacitor = ∫v·i dt = ½CV²
   Energy in inductor = ½LI²

4. TRANSIENT RESPONSE:
   RC circuit: v(t) = V(1 - e^(-t/RC))
   This comes from integrating the differential equation
```

---

## STEP 3 — Exam Form:

**Definite vs Indefinite Integrals:**

```
INDEFINITE: ∫f(x)dx = F(x) + C
  → Gives a family of functions (plus constant C)

DEFINITE: ∫ₐᵇ f(x)dx = F(b) - F(a)
  → Gives a NUMBER (the area)
  → No constant needed
```

**Integration by Parts (for products):**

```
∫u·dv = u·v - ∫v·du

This comes from: d(uv) = u·dv + v·du
Rearranging: u·dv = d(uv) - v·du
Integrating: ∫u·dv = uv - ∫v·du

Example:
  ∫x·sin(x)dx
  Let u = x, dv = sin(x)dx
  Then du = dx, v = -cos(x)
  = x·(-cos(x)) - ∫(-cos(x))dx
  = -x·cos(x) + sin(x) + C
```

---

## STEP 4 — Examiner Tweaks:

| Tweak | The Trap | Counter |
|-------|----------|---------|
| 1 | "Integration constant C" | Always include +C for indefinite integrals |
| 2 | "∫1/x dx = ln(x)" — wrong! | It's ln\|x\| (need absolute value for domain) |
| 3 | "Integration limits" | Definite integrals: evaluate at upper minus lower |
| 4 | "Average vs RMS" | Average = ∫f/T; RMS = √(∫f²/T) — different! |

---

## STEP 5 — Practice Questions:

**Q1 (Easy):** Find ∫(3t² + 2t + 1)dt

**Solution:**
```
∫3t²dt = 3 × t³/3 = t³
∫2t dt = 2 × t²/2 = t²
∫1 dt = t

So: ∫(3t² + 2t + 1)dt = t³ + t² + t + C
```

**Q2 (Medium):** Find the average value of v(t) = 10 sin(ωt) over one complete cycle.

**Solution:**
```
v_avg = (1/T) × ∫₀ᵀ v(t)dt

Over one period T = 2π/ω:
v_avg = (ω/2π) × ∫₀^(2π/ω) 10 sin(ωt) dt
       = (ω/2π) × 10 × [-cos(ωt)/ω]₀^(2π/ω)
       = (10/2π) × [-cos(2π) + cos(0)]
       = (10/2π) × [-1 + 1]
       = (10/2π) × 0
       = 0

This makes sense: sin wave over full cycle has equal positive and negative areas
→ Average = 0!

But over HALF cycle (0 to π/ω):
v_avg = (ω/π) × ∫₀^(π/ω) 10 sin(ωt) dt
       = (10/π) × [-cos(π) + cos(0)]
       = (10/π) × [1 + 1]
       = 20/π ≈ 6.37 V
```

**Q3 (Medium):** Derive the RMS value of a sine wave.

**Solution:**
```
For v(t) = V_m sin(ωt):

V_rms = √[(1/T) × ∫₀ᵀ v²(t)dt]
       = √[(1/T) × ∫₀ᵀ V_m² sin²(ωt)dt]
       = V_m × √[(1/T) × ∫₀ᵀ (1 - cos(2ωt))/2 dt]
       = V_m × √[(1/T) × (1/2) × ∫₀ᵀ (1 - cos(2ωt))dt]

Over period T = 2π/ω:
∫₀^(2π/ω) 1·dt = 2π/ω
∫₀^(2π/ω) cos(2ωt)dt = [sin(2ωt)/(2ω)]₀^(2π/ω) = 0

So: V_rms = V_m × √[(1/T) × (1/2) × (2π/ω)]
       = V_m × √[1/(2T) × (2π/ω)]
       = V_m × √[π/(ωT)]

But ωT = ω × (2π/ω) = 2π, so:
       = V_m × √[π/(2π)]
       = V_m × √(1/2)
       = V_m / √2
       = V_m × 0.707

Therefore: V_rms = V_m/√2 ≈ 0.707 × V_m
```

### 📝 PREVIOUS YEAR QUESTIONS — INTEGRATION

**PYQ 1 (APPSC AEE 2019):** Find the average value of sin(ωt) over one complete cycle.
**Answer:** 0 (equal positive and negative areas cancel)

**PYQ 2 (APGENCO 2018):** Find ∫(2t + 3)dt
**Answer:** t² + 3t + C

**PYQ 3 (APTRANSCO 2020):** Find the average value of v(t) = 100 sin(ωt) from 0 to π/ω (half cycle)
**Answer:** (2/π) × 100 ≈ 63.7 V

**PYQ 4 (APGENCO 2017):** Evaluate ∫₀² x² dx
**Answer:** [x³/3]₀² = 8/3

---

<a id="topic-6-logarithms"></a>
# TOPIC 6: Logarithms

## STEP 1 — First Principles:

**What is a logarithm?**

A logarithm is the INVERSE of exponentiation.

```
If:  a^x = b
Then: logₐ(b) = x

Read as: "log base a of b equals x"

This means: "a raised to what power gives b?"
```

**The Two Important Bases:**

```
BASE 10 (common log):
  log₁₀(x) = y  means  10^y = x
  Often written as just: log(x)

BASE e (natural log):
  ln(x) = y  means  e^y = x
  Where e ≈ 2.71828 (Euler's number)
  ln is used in engineering because it simplifies calculus
```

**Key Logarithm Properties:**

```
log(ab) = log(a) + log(b)
log(a/b) = log(a) - log(b)
log(a^n) = n × log(a)

ln(e^x) = x
e^(ln x) = x

log₁₀(10) = 1
ln(e) = 1
log(1) = 0
ln(1) = 0
```

---

## STEP 2 — Real Life Anchor:

**Where logs appear in electrical engineering:**

```
1. BODE PLOTS:
   → Gain in dB = 20 × log₁₀|G(jω)|
   → Every "decade" (10× frequency) = 20 dB change for first-order systems
   
   Example: If |G| = 100 at ω = 1
   In dB: 20 × log₁₀(100) = 20 × 2 = 40 dB
   
2. DECIBEL CALCULATIONS:
   → Power gain in dB = 10 × log₁₀(P_out/P_in)
   → Voltage gain in dB = 20 × log₁₀(V_out/V_in)
   → (The 20 vs 10 is because power ∝ V²)

3. TIME CONSTANTS:
   → e^(-t/τ) decay
   → ln(e^(-t/τ)) = -t/τ
   → Used to find time constant from measurements

4. TRANSMISSION LINE EQUATIONS:
   → Propagation constant γ = √(ZY)
   → ln(e^γx) form appears in long line equations
```

---

## STEP 3 — Exam Form:

**dB (Decibel) Calculations:**

```
dB = 20 × log₁₀(Gain)   for voltage/current
dB = 10 × log₁₀(Gain)   for power

Common values to memorize:

| Ratio | 20×log₁₀(ratio) | 10×log₁₀(ratio) |
|-------|------------------|------------------|
| 1     | 0 dB             | 0 dB             |
| 2     | 6 dB             | 3 dB             |
| 10    | 20 dB             | 10 dB            |
| √2    | 3 dB             | 1.5 dB           |
| 0.1   | -20 dB            | -10 dB           |
| 0.5   | -6 dB            | -3 dB            |
```

**Working with dB:**

```
Adding dB = multiplying ratios:
  6 dB + 6 dB = 12 dB  (ratio: 2 × 2 = 4)
  
Subtracting dB = dividing ratios:
  20 dB - 6 dB = 14 dB  (ratio: 10 / 2 = 5)

Converting ratio from dB:
  Ratio = 10^(dB/20) for voltage
  Ratio = 10^(dB/10) for power
```

---

## STEP 4 — Examiner Tweaks:

| Tweak | The Trap | Counter |
|-------|----------|---------|
| 1 | "log(xy) = log(x) × log(y)" — wrong! | log(xy) = log(x) + log(y) |
| 2 | "20 dB = ×20" | No! 20 dB = ×10 |
| 3 | "dB for power vs voltage" | Use 10 for power, 20 for voltage/current |
| 4 | "log of negative" | Not defined for real numbers (need complex log) |

---

## STEP 5 — Practice Questions:

**Q1 (Easy):** Convert a voltage gain of 100 to dB.

**Solution:**
```
dB = 20 × log₁₀(100)
    = 20 × 2
    = 40 dB
```

**Q2 (Easy):** What voltage ratio does 40 dB represent?

**Solution:**
```
Ratio = 10^(dB/20)
      = 10^(40/20)
      = 10^2
      = 100

So 40 dB = ×100 voltage gain ✓
```

**Q3 (Medium):** Two amplifiers are cascaded. Amp 1 has 20 dB gain, Amp 2 has 10 dB gain. What is the total gain in dB and as a ratio?

**Solution:**
```
Total gain in dB = 20 + 10 = 30 dB

As ratio:
  Amp 1 ratio = 10^(20/20) = 10
  Amp 2 ratio = 10^(10/20) = 10^0.5 = √10 ≈ 3.16

Total ratio = 10 × 3.16 = 31.6

Check: 10^(30/20) = 10^1.5 = 31.6 ✓
```

### 📝 PREVIOUS YEAR QUESTIONS — LOGARITHMS

**PYQ 1 (APGENCO 2019):** Convert 40 dB to voltage ratio.
**Answer:** 10^(40/20) = 10² = 100

**PYQ 2 (APTRANSCO 2020):** Express 20 dB + 10 dB as a single power ratio.
**Answer:** Combined dB = 30 dB → ratio = 10^(30/10) = 1000

**PYQ 3 (APPSC AEE 2018):** What is 3 dB equivalent to in voltage ratio?
**Answer:** 10^(3/20) ≈ 1.41 (approximately √2)

**PYQ 4 (APGENCO 2017):** If the gain of an amplifier is reduced to half, how many dB change?
**Answer:** 20 × log₁₀(0.5) = -6 dB

---

<a id="topic-7-matrices--determinants"></a>
# TOPIC 7: Matrices & Determinants

## STEP 1 — First Principles:

**What is a matrix?**

A matrix = a rectangular array of numbers arranged in rows and columns.

```
     ┌         ┐
     │ a  b  c │   ← Row 1
A =  │         │   
     │ d  e  f │   ← Row 2
     │         │
     │ g  h  i │   ← Row 3
     └         ┘
       ↑  ↑  ↑
       Col1 Col2 Col3

This is a 3×3 matrix (3 rows, 3 columns).
```

**Why matrices in electrical engineering?**

```
When solving circuit equations with multiple loops:
  Mesh 1: 10I₁ - 4I₂ = 12
  Mesh 2: -4I₁ + 16I₂ = -8
  
This can be written as:
  ┌      ┐ ┌  ┐   ┌   ┐
  │10  -4│ │I₁│ = │ 12│
  │ -4 16│ │I₂│   │ -8│
  └      ┘ └  ┘   └   ┘

  Or: [R] × [I] = [V]

We can solve for [I] = [R]⁻¹ × [V]
```

---

## STEP 2 — Real Life Anchor:

**Where matrices appear in electrical engineering:**

```
1. MESH/NODAL ANALYSIS:
   → System of simultaneous equations → matrix form
   → Solve using matrix inversion or Cramer's rule

2. TWO-PORT NETWORKS:
   → Z-parameters, Y-parameters, ABCD parameters
   → All as 2×2 matrices
   → Cascading: [A_total] = [A₁] × [A₂]

3. SYMMETRICAL COMPONENTS:
   → The transformation matrix:
   [1    1    1  ]
   [1    a   a² ]  (for converting to symmetrical components)
   [1   a²   a  ]

4. POWER SYSTEM ANALYSIS:
   → Y-bus, Z-bus matrices
   → Load flow studies
   → Fault analysis
```

---

## STEP 3 — Exam Form:

**2×2 Matrix Operations:**

```
ADDITION: [A] + [B] = element-by-element addition

MULTIPLICATION by scalar k:
  k × [A] = every element multiplied by k

MATRIX MULTIPLICATION:
  ┌      ┐   ┌      ┐   ┌                            ┐
  │a  b  │   │e  f  │   │(ae+bg)  (af+bh)          │
  │      │ × │      │ = │                            │
  │c  d  │   │g  h  │   │(ce+dg)  (cf+dh)          │
  └      ┘   └      ┘   └                            ┘
  
  Note: Row 1 of A × Column 1 of B = element (1,1)
        Row 1 of A × Column 2 of B = element (1,2)
```

**Determinant of 2×2:**

```
|A| = ad - bc

For matrix ┌    ┐
           │a  b│
           │c  d│
           └    ┘
           
Determinant = a×d - b×c
```

**Inverse of 2×2:**

```
If |A| ≠ 0, then A⁻¹ exists:

A⁻¹ = (1/|A|) × ┌     ┐
                 │ d  -b│
                 │-c   a│
                 └     ┘

So for solving [R][I] = [V]:
  [I] = [R]⁻¹ × [V]
```

---

## STEP 4 — Examiner Tweaks:

| Tweak | The Trap | Counter |
|-------|----------|---------|
| 1 | "Matrix multiplication: AB = BA" | NO! Matrix multiplication is NOT commutative |
| 2 | "Determinant of 2×2" | Remember: ad - bc, not ad + bc |
| 3 | "Inverse of singular matrix" | If \|A\| = 0, inverse doesn't exist |
| 4 | "Matrix addition" | Can only add same-sized matrices |

---

## STEP 5 — Practice Questions:

**Q1 (Easy):** Find the determinant of A = ┌    ┐
                                            │3  4│
                                            │2  5│

**Solution:**
```
|A| = (3)(5) - (4)(2) = 15 - 8 = 7
```

**Q2 (Easy):** Solve the system:
  2I₁ + 3I₂ = 12
  4I₁ + 1I₂ = 5

**Solution:**
```
Matrix form: [R][I] = [V]
  ┌      ┐ ┌  ┐   ┌  ┐
  │2   3 │ │I₁│ = │12│
  │4   1 │ │I₂│   │ 5│
  └      ┘ └  ┘   └  ┘

|R| = (2)(1) - (3)(4) = 2 - 12 = -10

Using Cramer's rule:
I₁ = |12  3| / |R| = (12×1 - 3×5) / (-10) = (12-15)/(-10) = -3/(-10) = 0.3
     | 5  1|

I₂ = |2  12| / |R| = (2×5 - 12×4) / (-10) = (10-48)/(-10) = -38/(-10) = 3.8
     |4   5|

Check:
  2(0.3) + 3(3.8) = 0.6 + 11.4 = 12 ✓
  4(0.3) + 1(3.8) = 1.2 + 3.8 = 5 ✓
```

**Q3 (Medium):** Multiply: ┌    ┐ × ┌    ┐
                           │1  2│   │5  6│
                           │3  4│   │7  8│

**Solution:**
```
Row 1 × Col 1: 1×5 + 2×7 = 5 + 14 = 19
Row 1 × Col 2: 1×6 + 2×8 = 6 + 16 = 22
Row 2 × Col 1: 3×5 + 4×7 = 15 + 28 = 43
Row 2 × Col 2: 3×6 + 4×8 = 18 + 32 = 50

Result: ┌      ┐
         │19  22│
         │43  50│
         └      ┘
```

### 📝 PREVIOUS YEAR QUESTIONS — MATRICES

**PYQ 1 (APTRANSCO 2018):** Find the determinant of A = [3 2; 4 5]
**Answer:** |A| = (3)(5) - (2)(4) = 15 - 8 = 7

**PYQ 2 (APPSC AEE 2019):** Solve using matrices: 2I₁ + 3I₂ = 13, 1I₁ + 4I₂ = 12
**Answer:** I₁ = 3.2 A, I₂ = 2.2 A

**PYQ 3 (APGENCO 2018):** Find the inverse of [4 2; 3 2]
**Answer:** |A| = 8-6 = 2; A⁻¹ = (1/2)[2 -2; -3 4] = [1 -1; -1.5 2]

**PYQ 4 (APTRANSCO 2020):** Multiply: [2 1] × [3 4; 5 6]
**Answer:** [2×3+1×5, 2×4+1×6] = [11, 14]

---

<a id="topic-8-basic-physics-force-energy-power"></a>
# TOPIC 8: Basic Physics (Force, Energy, Power)

## STEP 1 — First Principles:

**Force:**

```
Force (F) = mass (m) × acceleration (a)
Unit: Newton (N) = kg × m/s²

Earth's gravity: g ≈ 9.8 m/s²
Weight = m × g (in Newtons, not kilograms!)
```

**Energy:**

```
Energy = ability to do work
Work (W) = Force × distance × cos(θ)
Unit: Joule (J) = N × m

Types of energy:
  → Kinetic: KE = ½mv²
  → Potential: PE = mgh (gravitational)
  → Electrical: PE = Q × V = V × I × t
```

**Power:**

```
Power = rate of doing work = Energy/time
Unit: Watt (W) = Joule/second

Electrical Power:
  P = V × I (volts × amps)
  P = I²R (current squared × resistance)
  P = V²/R (voltage squared divided by resistance)
  
These are all equivalent (Ohm's law: V = IR)
```

---

## STEP 2 — Real Life Anchor:

**Where physics basics appear in electrical engineering:**

```
1. MOTOR TORQUE:
   → Torque T = Force × radius
   → T = F × r (Nm)
   → In DC motor: T ∝ Φ × I_a
   → Power = Torque × angular velocity
   → P = T × ω (watts)

2. ENERGY IN INDUCTOR/CAPACITOR:
   → Inductor: E = ½LI² (joules)
   → Capacitor: E = ½CV² (joules)
   → These store energy in magnetic/electric fields

3. HEATING:
   → P = I²R (Joule's law)
   → Higher current → more heat
   → This is why power lines use high voltage (lower current = less loss)

4. MECHANICAL TO ELECTRICAL CONVERSION:
   → Generator: Mechanical power in = Electrical power out + losses
   → Efficiency = P_out/P_in
```

---

## STEP 3 — Exam Form:

**Key Equations:**

| Quantity | Formula | Units |
|----------|---------|-------|
| Force | F = ma | N |
| Work | W = F × d | J |
| Kinetic Energy | KE = ½mv² | J |
| Potential Energy | PE = mgh | J |
| Power (mechanical) | P = W/t = F×v | W |
| Power (electrical) | P = V × I = I²R = V²/R | W |
| Torque | T = F × r | N-m |
| Angular velocity | ω = 2πN/60 | rad/s |

**Conversions:**

```
1 HP ≈ 746 W (horsepower)
1 kW = 1000 W
1 MW = 10⁶ W
1 GW = 10⁹ W

Angular velocity: ω (rad/s) = 2π × f = 2π × N/60 (where N is RPM)
```

---

## STEP 4 — Examiner Tweaks:

| Tweak | The Trap | Counter |
|-------|----------|---------|
| 1 | "Weight in kg" | Weight is a FORCE, measured in Newtons. kg is MASS |
| 2 | "Confusing power units" | HP vs W vs kW — convert properly |
| 3 | "ω vs N" | ω (rad/s) = 2π × N/60 where N is RPM |

---

## STEP 5 — Practice Questions:

**Q1 (Easy):** A 2 kW heater operates for 1 hour. How much energy does it consume?

**Solution:**
```
P = 2 kW = 2000 W
t = 1 hour = 3600 seconds

Energy = P × t = 2000 × 3600 = 7,200,000 J
       = 7.2 MJ

Or in kWh: E = 2 kW × 1 h = 2 kWh
```

**Q2 (Easy):** Convert 5 HP to watts.

**Solution:**
```
1 HP ≈ 746 W
5 HP ≈ 5 × 746 = 3730 W ≈ 3.73 kW
```

**Q3 (Medium):** A motor produces 100 N-m torque at 1500 RPM. Find the mechanical power output.

**Solution:**
```
Given: T = 100 N-m, N = 1500 RPM

Step 1: Convert RPM to rad/s
ω = 2π × N/60 = 2π × 1500/60 = 2π × 25 = 50π rad/s ≈ 157 rad/s

Step 2: Calculate power
P = T × ω = 100 × 157 = 15,700 W ≈ 15.7 kW

Alternatively in HP:
P_HP = P_W / 746 = 15700/746 ≈ 21 HP
```

### 📝 PREVIOUS YEAR QUESTIONS — PHYSICS

**PYQ 1 (APPSC AEE 2019):** A 5 kW motor runs for 2 hours. Find energy consumed.
**Answer:** E = 5 × 2 = 10 kWh

**PYQ 2 (APGENCO 2018):** Convert 10 HP to watts.
**Answer:** 10 × 746 = 7460 W

**PYQ 3 (APTRANSCO 2020):** A motor produces 150 N-m torque at 1000 RPM. Find power in kW.
**Answer:** ω = 2π×1000/60 = 104.7 rad/s; P = 150×104.7 = 15,705 W ≈ 15.7 kW

**PYQ 4 (APPSC AEE 2017):** If an electric heater draws 10 A at 230 V for 3 hours, find energy consumed.
**Answer:** P = 230×10 = 2300 W = 2.3 kW; E = 2.3 × 3 = 6.9 kWh

---

# 📋 MATH PREREQUISITES — QUICK REFERENCE CARD

```
┌─────────────────────────────────────────────────────────────────┐
│           MATH PREREQUISITES — ONE-PAGE SUMMARY                   │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  TRIGONOMETRY:                                                  │
│  sin²θ + cos²θ = 1                                             │
│  cos(θ) = sin(90°-θ)                                          │
│  Key values: sin30°=0.5, sin60°=0.866, cos45°=0.707           │
│                                                                 │
│  COMPLEX NUMBERS (j = √-1):                                    │
│  z = a + jb = r∠θ, r = √(a²+b²), θ = tan⁻¹(b/a)             │
│  j² = -1, 1/j = -j                                             │
│  a = 1∠120° = -0.5 + j0.866, 1+a+a² = 0                     │
│                                                                 │
│  PHASORS:                                                       │
│  V = I × Z, V = V_m∠φ (RMS), V_m = √2 × V_rms              │
│                                                                 │
│  DERIVATIVES:                                                  │
│  d/dt[sin(ωt)] = ωcos(ωt), d/dt[tⁿ] = ntⁿ⁻¹                  │
│  d/dt[e^(at)] = ae^(at)                                        │
│                                                                 │
│  INTEGRALS:                                                     │
│  ∫tⁿdt = tⁿ⁺¹/(n+1) + C                                      │
│  ∫sin(ωt)dt = -cos(ωt)/ω + C                                  │
│  Average = (1/T)∫₀ᵀ f(t)dt                                     │
│  RMS = √[(1/T)∫₀ᵀ f²(t)dt]                                    │
│  For sine: V_rms = V_m/√2                                     │
│                                                                 │
│  LOGARITHMS:                                                    │
│  log(ab) = log(a) + log(b)                                    │
│  dB_voltage = 20×log₁₀(ratio), dB_power = 10×log₁₀(ratio) │
│                                                                 │
│  MATRICES:                                                      │
│  |A| = ad - bc (2×2 determinant)                               │
│  A⁻¹ = (1/|A|) × [d  -b; -c   a]                             │
│                                                                 │
│  PHYSICS:                                                       │
│  P = VI = I²R = V²/R                                           │
│  P = T × ω (power = torque × angular velocity)               │
│  ω = 2πN/60 rad/s (N in RPM)                                 │
│  1 HP ≈ 746 W                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

# ❓ WEAK AREAS (Fill in as you discover them)

```
1. _________________________________________________________________
2. _________________________________________________________________
3. _________________________________________________________________
4. _________________________________________________________________
```

---

> **How to use this document:**
> 1. Read through each topic before tackling the corresponding formula in the main notes
> 2. If a formula derivation confuses you, come back here
> 3. Mark topics you find easy with ✓, topics you struggle with with ✗
> 4. Focus your revision on the ✗ marked topics
> 5. Use the Quick Reference Card for last-minute review
