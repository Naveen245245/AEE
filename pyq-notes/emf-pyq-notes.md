# EMF / Electromagnetics — PYQ Notes from Ohm Institute PDF

**Source:** [Study Material GTD PYQs] 2026 05 26 6 EMF PDF.pdf  
**Total Questions Analyzed:** ~470 across 4 units  
**Topics:** Vector Calculus, Electrostatics, Magnetostatics, Maxwell's Equations

---

## 📊 Formula/Concept vs. Question Count Analysis

| S.No | Formula / Concept | No. of Qs | Key Formula |
| :---: | :-------------------------------------------------------------- | :---: | :--- |
| 1 | **Vector Calculus** (Gradient, Divergence, Curl) | ~40 | ∇V, ∇·A, ∇×A, Stokes', Divergence theorem |
| 2 | **Electrostatics** (Coulomb, Gauss, Potential, Capacitance) | ~50 | F, E, V = Q/(4πεr), C = εA/d, D = εE |
| 3 | **Magnetostatics** (Biot-Savart, Ampere, Lorentz) | ~45 | dB = (μ₀/4π)(Idl×r̂/r²), F = q(E+v×B) |
| 4 | **Maxwell's Equations** (Time Varying Fields) | ~35 | ∇×E=-∂B/∂t, ∇×H=J+∂D/∂t |
| 5 | **Boundary Conditions** | ~15 | D₁n-D₂n=ρₛ, E₁t=E₂t, B₁n=B₂n, H₁t-H₂t=Jₛ |
| 6 | **EM Wave Propagation** | ~10 | c=1/√(μ₀ε₀), P = E×H, wave equation |
| 7 | **Coordinate Systems** (Cartesian, Cylindrical, Spherical) | ~15 | Conversions between coordinate systems |

---

## 📌 Quick Reference Card (Exam Day)

| Concept | Formula | Tip |
| :--- | :--- | :--- |
| **Gradient** | ∇V = ∂V/∂x î + ∂V/∂y ĵ + ∂V/∂z k̂ | Scalar → Vector |
| **Divergence** | ∇·A = ∂Ax/∂x + ∂Ay/∂y + ∂Az/∂z | Vector → Scalar |
| **Curl** | ∇×A = determinant | Vector → Vector |
| **Divergence Theorem** | ∮ A·dS = ∫ (∇·A) dv | Surface ↔ Volume |
| **Stokes Theorem** | ∮ A·dl = ∫ (∇×A)·dS | Line ↔ Surface |
| **Gauss Law** | ∮ D·dS = Qenc | D = εE |
| **Coulomb** | F = Q₁Q₂/(4πε₀r²) | |
| **Lorentz Force** | F = q(E + v×B) | On moving charge |
| **Faraday** | ∇×E = -∂B/∂t | e = -dΦ/dt |
| **Ampere-Maxwell** | ∇×H = J + ∂D/∂t | Displacement current |
| **Wave Eq** | ∇²E = μ₀ε₀∂²E/∂t² | v = 1/√(μ₀ε₀) |
| **Poynting** | P = E×H W/m² | Power flow density |

---

# 📝 FULL PYQ ANALYSIS — All EMF Questions (Concept through PYQ)

> Source: [Study Material GTD PYQs] 2026 05 26 6 EMF PDF.pdf (OHM Institute — GATE/ESE/AE/AEE)
> Every question: answer + options, the concept it teaches, and how the examiner twists it.

**Legend:** Q = question · Ans = correct option · Concept = new term/principle · Twist = examiner variation → new answer

## Unit 1: Coordinate Geometry & Vector Calculus (39 Qs)

## ONE MARK QUESTIONS

**Q1 (EC-GATE-94):** Fill-in: ∮_C A·dl = ∫_S ____ · dS. (Options not printed — fill-in type.)
(a) — (b) — (c) — (d) —
**Ans: (∇×A)** — Stoke's theorem converts the closed line integral of A into the surface integral of curl A over the open surface bounded by C.
**Concept:** Stokes theorem ∮A·dl = ∮∫(∇×A)·dS.
**Twist:** Ask for ∮E·dl in static field → 0 (since ∇×E=0). Ask the surface integral of B instead → use ∮B·dl = μ₀I (Ampere's law).

**Q2 (EE-GATE-02):** Given a vector field F, the divergence theorem states that:
(a) ∮_S F·dS = ∫_V ∇·F dv (b) ∮_S F·dS = ∫_V ∇×F dv (c) ∮_S F×dS = ∫_V ∇·F dv (d) ∮_S F×dS = ∫_V ∇×F dv
**Ans: (a)** — Divergence theorem equates the net outward flux of F through a closed surface to the volume integral of its divergence.
**Concept:** Divergence theorem ∮F·dS = ∫(∇·F)dV.
**Twist:** Ask flux of radial field r through a closed sphere → ∫3 dV = 3V. Ask flux of a constant field → 0.

**Q3 (EC-GATE-06):** ∮∫(∇×P)·dS, where P is a vector, is equal to:
(a) ∮P·dl (b) ∮(∇×∇×P)·dl (c) ∮(∇×P)·dl (d) ∫∫∫∇·P dv
**Ans: (a)** — By Stokes theorem the flux of curl P equals the circulation of P around the bounding loop.
**Concept:** Stokes theorem ∫∫(∇×P)·dS = ∮P·dl.
**Twist:** Ask ∫∫(∇×P)·dS with P irrotational (∇×P=0) → 0. Ask circulation of a gradient field → 0.

**Q4 (EC-GATE-06):** ∇×∇×P, where P is a vector, is equal to:
(a) P×∇×P − ∇P² (b) ∇²P + ∇(∇·P) (c) ∇²P + ∇×P (d) ∇(∇·P) − ∇²P
**Ans: (d)** — Vector identity: curl of curl = gradient of divergence minus vector Laplacian.
**Concept:** Vector identity ∇×(∇×P) = ∇(∇·P) − ∇²P.
**Twist:** If ∇·P=0 (solenoidal), then ∇×∇×P = −∇²P. Ask ∇·(∇×P) instead → always 0.

**Q5 (EE-GATE-07):** Divergence of V(x,y,z) = −(x cos xy + y)î + (y cos xy)ĵ + sin(z²+x²+y²)k̂ is:
(a) 2z cos z² (b) sin xy + 2x cos z² (c) x sin xy − cos z (d) None of these
**Ans: (a)** — ∂/∂x and ∂/∂y terms cancel (both give cosxy−xysinxy with opposite signs); ∂/∂z of the k-term = 2z cos(z²+x²+y²) → taken as 2z cos z² (key).
**Concept:** Divergence ∇·V = ∂Vx/∂x + ∂Vy/∂y + ∂Vz/∂z (product-rule partials).
**Twist:** Strictly the z-partial keeps x²+y² inside cos → answer "2z cos(z²+x²+y²)", so option (d) if examiner wants exactness. Change k-component to sin(z²) → answer 2z cos z² unambiguously.

**Q6 (EE-GATE-10):** Divergence of the three-dimensional radial vector field r is:
(a) 3 (b) 1/r (c) î+ĵ+k̂ (d) 3(î+ĵ+k̂)
**Ans: (a)** — ∇·r = ∂x/∂x + ∂y/∂y + ∂z/∂z = 3.
**Concept:** Divergence of position vector = 3 in 3-D.
**Twist:** In cylindrical r̂ → ∇·(ρâρ)=2. In spherical ∇·(r r̂)=3; ∇·(r²r̂)=4r.

**Q7 (EC-GATE-11):** Closed surface S surrounds volume V. If r is the position vector and n̂ the unit normal on S, ∫∫_S 5 r·n̂ dS is:
(a) 3V (b) 5V (c) 10V (d) 15V
**Ans: (d)** — 5∫∫ r·n̂ dS = 5∫∫∫ ∇·r dV = 5∫∫∫ 3 dV = 15V.
**Concept:** Divergence theorem applied to position vector (∇·r=3).
**Twist:** Replace r by constant vector c → flux = c·(net area vector), zero for closed surface. Ask ∫∫ r·n̂ dS over one open face (unit cube, z=1) → 1.

**Q8 (EC-GATE-13):** For a vector field A(r), the closed loop line integral ∮A·dl can be expressed as:
(a) ∫∫(∇×A)·dS over the closed surface bounded by the loop (b) ∫∫∫(∇·A)dv over the closed volume bounded by the loop (c) ∫∫∫(∇·A)dv over the open volume bounded by the loop (d) ∫∫(∇×A)·dS over the open surface bounded by the loop
**Ans: (d)** — Stokes theorem applies to the open surface spanning the closed loop.
**Concept:** Stokes theorem ∮A·dl = ∫∫(∇×A)·dS over open surface bounded by C.
**Twist:** If ∇×A=0 (conservative) → circulation = 0. Ask ∮B·dl = μ₀I (Ampere) — same form, different constant.

**Q9 (EC-GATE-13):** Divergence of the vector field A = xâx + yây + zâz is:
(a) 0 (b) 1/3 (c) 1 (d) 3
**Ans: (d)** — Each component contributes ∂x/∂x = ∂y/∂y = ∂z/∂z = 1 → total 3.
**Concept:** ∇·r = 3 (divergence of position vector).
**Twist:** A = 2x âx + y ây − 3z âz → divergence 2+1−3 = 0 (solenoidal). A = r² r̂ → 4r.

**Q10 (EE-GATE-13):** The curl of the gradient of the scalar field V = 2x²y + 3y²z + 4z²x is:
(a) 4xy âx + 6yz ây + 8zx âz (b) 4âx + 6ây + 8âz (c) (4xy+4z²)âx + (2x²+6yz)ây + (3y²+8zx)âz (d) 0
**Ans: (d)** — Curl of any gradient is identically zero (∇×∇V ≡ 0).
**Concept:** ∇×∇V = 0 always.
**Twist:** Instead compute ∇·∇V = ∇²V for the same V → 4y + 6z + 8x (not zero). Ask curl of a purely radial field r → also 0.

**Q11 (EE-GATE-15):** f = (1/r²)r̂, where r is distance from origin and r̂ the radial unit vector. Divergence of f over a sphere of radius R which includes the origin is:
(a) 0 (b) 2π (c) 4π (d) Rπ
**Ans: (c)** — Away from origin ∇·(r̂/r²)=0, but flux through the enclosing sphere ∮(1/R²)dS = 4π (origin singularity enclosed).
**Concept:** Dirac-type source at origin; divergence integral over a region containing the source = 4π (flux of r̂/r² = 4π).
**Twist:** Sphere not enclosing origin → 0 (divergence-free region). Replace with E = Q/(4πε₀r²)r̂ → total flux Q/ε₀ (Gauss's law).

**Q12 (EE-GATE-17):** Diagrammatic representations of vector fields X, Y, Z (field-line sketches: X radially spreading out, Y circulating around a point, Z uniform parallel lines). Which is true?
(a) ∇·X=0, ∇×Y≠0, ∇×Z=0 (b) ∇·X≠0, ∇×Y=0, ∇×Z≠0 (c) ∇·X≠0, ∇×Y≠0, ∇×Z=0 (d) ∇·X=0, ∇×Y=0, ∇×Z=0
**Ans: (c)** — X diverges from a source (∇·≠0), Y circulates (∇×≠0), Z is uniform/straight (both curl and divergence zero).
**Concept:** Geometric meaning: field lines spreading = divergence; closed loops = curl; parallel straight = both zero.
**Twist:** If X lines converge inward → still ∇·≠0 (sink, negative). If Y lines are parallel but curved slightly → curl ≠ 0.

**Q13 (EE-GATE-19):** If f = 2x³ + 3y² + 4z, the value of ∮_C grad f · dr over the closed contour C formed by segments (−3,−3,2)→(2,−3,2)→(2,6,2)→(2,6,−1) is _____.
(a) — (b) — (c) — (d) — (fill-in)
**Ans: (0)** — grad f is a conservative field, so its line integral over any closed path is zero.
**Concept:** Conservative field: ∮∇f·dr = 0 (path independent).
**Twist:** Ask ∫ grad f·dr between two named points → f(B) − f(A). Ask ∮ of a non-conservative F → depends on path (compute directly).

**Q14 (EC-GATE-20):** For a vector field A, which one is FALSE?
(a) ∇×A is another vector field (b) A is solenoidal if ∇·A=0 (c) A is irrotational if ∇²A=0 (d) ∇×(∇×A) = ∇(∇·A) − ∇²A
**Ans: (c)** — Irrotational means ∇×A=0, not ∇²A=0.
**Concept:** Irrotational ⇔ ∇×A=0; solenoidal ⇔ ∇·A=0.
**Twist:** A field with ∇²A=0 but ∇×A≠0 is not irrotational — e.g. A = y âx. Ask "conservative" synonym → ∇×A=0.

**Q15 (EC-GATE-21):** F(r) = −x î + y ĵ defined over a circular arc C (unit radius, 45° arc as in figure). The line integral ∫_C F(r)·dr is:
(a) 1/4 (b) 1/2 (c) 1/6 (d) 1/3
**Ans: (b)** — F·dr = −x dx + y dy = 2 sinθ cosθ dθ (R=1); ∫ over 45° arc = sin²θ = 1/2 (same for 0–45° or 45–90°).
**Concept:** Line integral over circular arc — parametrize x=Rcosθ, y=Rsinθ.
**Twist:** F = x î + y ĵ (both positive) → integrand −sinθcosθ+sinθcosθ = 0. Arc of 90° with F=−xî+yĵ → 1.

**Q16 (EC-GATE-21):** F = âx(4y − c₁z) + ây(4x + 2z) + âz(2y + z). If F is irrotational (conservative), then the constant c₁ (integer) is _____.
(a) — (b) — (c) — (d) — (fill-in)
**Ans: (0)** — ∇×F = 0 gives: ∂Fy/∂x−∂Fx/∂y = 4−4 = 0 (ok), ∂Fx/∂z−∂Fz/∂x = −c₁−0 → c₁=0.
**Concept:** Irrotational field ⇒ all three curl components vanish; set the mixed partials equal.
**Twist:** Make F = âx(4y−c₁z)+ây(4x−c₂z)+âz(2y+z) → solve c₁=0, c₂=0 by ∂Fy/∂z=∂Fz/∂y. Change a coefficient (e.g. az component 3y) → c₁ adjusts accordingly.

**Q17 (EC-GATE-22):** F(x,y) = x î + y ĵ. Contour C (in figure) is two horizontal lines connected at the ends by two semi-circular arcs of unit radius, traversed counter-clockwise. The closed path integral ∮_C F·(dx î + dy ĵ) is:
(a) 0 (b) 1 (c) 8+2π (d) −1
**Ans: (a)** — F = ∇(½(x²+y²)) is a gradient, so the closed-path integral is zero regardless of the path shape.
**Concept:** Conservative field ∮F·dr = 0 (F exact differential x dx + y dy).
**Twist:** F = −y î + x ĵ (rotational) → ∮ = 2×Area (Green). If the arcs close an area A and F = x î + 2y ĵ → ∮ = ∮(x dx + 2y dy) = ∫∫(0−0) + ... not exact → use Green's = area-dependent.

**Q18 (EC-GATE-23):** The rate of increase of f(x,y,z) = xyz in the direction v = (2,1,2) at point (0,2,1) is:
(a) 2/3 (b) 4/3 (c) 2 (d) 4
**Ans: (b)** — ∇f = (yz, xz, xy) = (2,0,0) at (0,2,1); unit direction v̂ = (2,1,2)/3 → ∇f·v̂ = (2·2)/3 = 4/3.
**Concept:** Directional derivative = ∇f · unit-direction vector.
**Twist:** Ask maximum rate of increase → |∇f| = 2 (along (2,0,0)). Use un-normalized v → mistakenly 4; examiner traps with v=(4,2,4) → still 4/3.

## TWO MARK QUESTIONS

**Q1 (EC-GATE-88):** Vector potential is a vector:
(a) whose curl is equal to the magnetic flux density (b) whose divergence is equal to the electric field intensity (c) whose divergence is equal to the electric potential (d) which is equal to the vector product E×H
**Ans: (a)** — Magnetic vector potential A satisfies B = ∇×A.
**Concept:** Vector potential B = ∇×A; gauge ∇·A=0 (Coulomb gauge).
**Twist:** Ask scalar potential relation E = −∇V. Ask the curl of the vector potential of a uniform B → A = ½B×r.

**Q2 (EC-GATE-93):** V = x²cos y î + x²e^z ĵ + z sin²y k̂ and S the surface of a unit cube with one corner at origin and edges parallel to the axes. ∫∫_S V·n̂ dS = _____.
(a) — (b) — (c) — (d) — (fill-in)
**Ans: (≈1.114)** — By divergence theorem: ∫∫∫(2x cos y + sin²y)dV over unit cube = sin 1 + 1/2 − (sin 2)/4 ≈ 1.114.
**Concept:** Divergence theorem converts a closed-surface flux into a volume integral of ∇·V.
**Twist:** If V has ∇·V = const, answer = const×volume. Ask flux only through the z=1 face → integrate Vz = z sin²y over that face.

**Q3 (EC-GATE-98):** Given irrotational F = (K₁xy + K₂z³)âx + (3x² − K₃z)ây + (3xz² − y)âz. Find ∇·F at (1,1,−2).
(a) — (b) — (c) — (d) — (fill-in)
**Ans: (−6)** — Curl=0 ⇒ K₁=6, K₂=1, K₃=1; ∇·F = 6y + 0 + 6xz = 6(1) + 6(1)(−2) = −6.
**Concept:** Irrotational (∇×F=0) fixes the constants; then compute divergence.
**Twist:** Ask the scalar potential V by integrating F → V = 3x²y + xz³ − yz. Ask ∇×F at a point after finding K's → 0.

**Q4 (EC-GATE-08):** Points P=(1,0) and Q=(0,1) in the xy-plane. Line integral 2∫_P^Q (x dx + y dy) along the semicircle with PQ as diameter:
(a) is −1 (b) is 0 (c) is 1 (d) depends on the direction (clockwise/anti-clockwise) of the semicircle
**Ans: (b)** — x dx + y dy = d(½r²) is exact, so the integral is ½(0²+1²) − ½(1²+0²) = 0, independent of path.
**Concept:** Exact differential ⇒ path-independent line integral (conservative field).
**Twist:** Replace integrand by x dy − y dx → equals 2×(semicircle area) = π (path dependent). Ask 2∫(x dx − y dy) → also 0 but opposite signs if misapplied.

**Q5 (EC-GATE-08):** The value of the integral of g(x,y) = 4x³ + 10y⁴ along the straight-line segment from (0,0) to (1,2) in the x-y plane is:
(a) 33 (b) 35 (c) 40 (d) 56
**Ans: (a)** — Parametrize y = 2x (0≤x≤1): ∫₀¹(4x³ + 10(2x)⁴)dx = [x⁴ + 32x⁵]₀¹ = 1 + 32 = 33.
**Concept:** Line integral of a scalar function along a path — substitute the curve equation.
**Twist:** Path (1,2)→(0,0) reversed → −33. Path y = x² (still (0,0)→(1,1)) → ∫(4x³+10x⁸)dx = 1 + 10/9 = 19/9.

**Q6 (EC-GATE-09):** If vector V is related to A through V = ∇×A (C and S_C are any closed contour and any surface with boundary C), which is true?
(a) ∮_C V·dl = ∫∫_SC A·dS (b) ∮_C A·dl = ∫∫_SC (∇×A)·dS (c) ∮_C (∇×V)·dl = ∫∫_SC (∇×A)·dS (d) ∮_C (∇×A)·dl = ∫∫_SC V·dS
**Ans: (b)** — This is exactly Stokes theorem applied to A.
**Concept:** Stokes theorem; V=∇×A implies ∇·V=0 (solenoidal).
**Twist:** Ask ∮_C V·dl → ∫∫(∇×V)·dS = ∫∫∇×(∇×A)·dS (not simply ∫∫A·dS). Ask which is divergence-free → V.

**Q7 (EE-GATE-09):** F(x,y) = (x²+xy)âx + (y²+xy)ây. Its line integral over the straight line from (x,y)=(0,2) to (2,0) evaluates to:
(a) −8 (b) 4 (c) 8 (d) 0
**Ans: (d)** — On y = 2−x, x²+xy = 2x and y²+xy = 4−2x, so ∫[(2x) − (4−2x)]dx from 0 to 2 = ∫(4x−4)dx = 0.
**Concept:** Direct line-integral evaluation along a straight path.
**Twist:** Path (0,0)→(2,0)→(2,2) (bent) → compute segment-wise (not 0). If F = (x²+xy)âx + (y²−xy)ây → path changes value.

**Q8 (EC-GATE-10):** A = xy âx + x² ây, then ∮_C A·dl over the closed rectangular path shown in figure (vertices around (1,1)–(2,·)) is:
(a) 0 (b) 3/2 (c) 1 (d) 1/3
**Ans: (b)** — Green's theorem: ∮ = ∫∫(∂(x²)/∂x − ∂(xy)/∂y)dA = ∫∫x dA = x̄·Area = (3/2)·1 = 3/2 for the shown region.
**Concept:** Green's theorem ∮(P dx+Q dy) = ∫∫(∂Q/∂x − ∂P/∂y)dA; here integrand reduces to ∫∫x dA (area × centroid x).
**Twist:** If the rectangle spans [1,2]×[1,3] → ∫∫x dA = 3 (watch the figure's y-range). Change A = x²y âx + xy² ây → ∮ = ∫∫(y²−x²)dA.

**Q9 (EC/EE-GATE-12):** Vector A radially outward from origin, A = k r^n with r² = x²+y²+z², k constant. The value of n for which ∇·A = 0 is:
(a) −2 (b) 2 (c) 1 (d) 0
**Ans: (a)** — In spherical ∇·(k r^n r̂) = k(n+2)r^(n−1) = 0 → n = −2.
**Concept:** ∇·(r^n r̂) = (n+2)r^(n−1); only r⁻² is divergence-free (like a point-charge field).
**Twist:** Ask ∇·A for n=0 → 2/r. Ask for a field rⁿ in cylindrical (2-D) → n = −1 for divergence-free.

**Q10 (EC-GATE-14):** F = z âx + x ây + y âz. If S is the portion of the sphere x²+y²+z²=1 for z≥0, then ∫∫_S (∇×F)·dS = _____.
(a) — (b) — (c) — (d) — (fill-in)
**Ans: (π)** — ∇×F = (1,1,1); by Stokes, ∫∫(∇×F)·dS = ∮F·dl around the unit circle z=0 → ∫₀^{2π}cos²θ dθ = π.
**Concept:** Stokes theorem with a constant-curl field; flux = line integral on boundary circle.
**Twist:** Hemisphere z≤0 → the boundary is traversed oppositely → −π. F = y âx + z ây + x âz → curl=(1,1,1) again → π.

**Q11 (EC-GATE-14):** A = (cos x)(sin y)âx + (sin x)(cos y)ây. The magnitude of curl of A is _____.
(a) — (b) — (c) — (d) — (fill-in)
**Ans: (0)** — ∂Ay/∂x − ∂Ax/∂y = cos x cos y − cos x cos y = 0, so |∇×A| = 0.
**Concept:** Curl in 2-D: ∇×A = (∂Ay/∂x − ∂Ax/∂y) k̂.
**Twist:** Swap components A = (sin x cos y)âx + (cos x sin y)ây → curl = −2sin x sin y. Ask ∇·A of the original → cos x sin y + sin x (−sin y) = 0 too (both divergence and curl zero).

**Q12 (EC-GATE-15):** P = x³y âx − x²y² ây − x²yz âz. Which statement is TRUE?
(a) P is solenoidal, but rotational (b) P is irrotational, but not solenoidal (c) P is neither irrotational nor solenoidal (d) P is both irrotational and solenoidal
**Ans: (a)** — ∇·P = 3x²y − 2x²y − x²y = 0 (solenoidal); ∇×P = (−x²z, 2xyz, −2xy²−x³) ≠ 0 (rotational).
**Concept:** Test solenoidal (∇·=0) and irrotational (∇×=0) independently.
**Twist:** Change az to −x²y²z² → ∇·P = 3x²y−2x²y−2x²yz² ≠ 0 (neither). Ask which of ∇·P, ∇×P vanish at a point → substitute coordinates.

**Q13 (EC-GATE-15):** D = 2ρ² âρ + z âz exists inside the cylindrical region enclosed by ρ=1, z=0, z=5. Surface integral ∮∫_S D·dS = _____.
(a) — (b) — (c) — (d) — (fill-in)
**Ans: (25π)** — ∇·D = 6ρ + 1; ∫∫∫(6ρ+1)dV = 2π·5·∫₀¹(6ρ²+ρ)dρ = 10π·2.5 = 25π.
**Concept:** Divergence theorem in cylindrical coordinates (1/ρ)∂(ρDρ)/∂ρ + ∂Dz/∂z.
**Twist:** If D = 2ρ âρ only → ∇·D = 4/ρ → integral = 2π·5·∫₀¹4dρ = 40π. Ask flux only through the top cap z=5 → π.

**Q14 (EC-GATE-16):** Region specified by (ρ,φ,z): 3≤ρ≤5, π/8≤φ≤π/4, 3≤z≤4.5 in cylindrical coordinates has volume _____.
(a) — (b) — (c) — (d) — (fill-in)
**Ans: (3π/2)** — dV = ρ dρ dφ dz; V = (4.5−3)·(π/8)·[(25−9)/2] = 1.5·π/8·8 = 3π/2.
**Concept:** Volume element in cylindrical coordinates dV = ρ dρ dφ dz.
**Twist:** Change z-range to 0–5 → V = 5π. Convert same region to spherical → use r²sinθ dr dθ dφ element.

**Q15 (EC-GATE-16):** ∫_C (x dy − y dx) counter-clockwise over the closed curve C bounding region R = union of a 2×3 rectangle and a semicircle of radius 1 (figure). The integral evaluates to:
(a) 12+π (b) 16+π (c) 8+π (d) 6+π/2
**Ans: (a)** — By Green: ∮(x dy − y dx) = ∫∫(1+1)dA = 2·Area = 2(6 + π/2) = 12 + π.
**Concept:** Green's theorem; ∮(x dy − y dx) = 2×enclosed area.
**Twist:** Integrand x dy + y dx → gradient, closed integral = 0. Semicircle of radius 2 → 2(6+2π) = 12+4π.

**Q16 (EE-GATE-16):** Line integral of F = 5xz î + (3x²+2y)ĵ + x²z k̂ along the path (0,0,0)→(1,1,1) parameterized by (t, t², t) is _____.
(a) — (b) — (c) — (d) — (fill-in)
**Ans: (53/12 ≈ 4.42)** — x=t, y=t², z=t: ∫₀¹[5t²·dt + (5t²)·2t dt + t³ dt] = ∫₀¹(5t²+10t³+t³)dt = 5/3 + 11/4 = 53/12.
**Concept:** Line integral via parametrization F·dr = P dx + Q dy + R dz.
**Twist:** Straight-line path (t,t,t) → ∫₀¹(5t² + 5t² + t²)dt = 11/3 (path dependence!). Same F with parameter (t²,t,t) → different value.

**Q17 (EE-GATE-19):** A = 2x î + 3y ĵ + 4z k̂ and u = x²+y²+z². div(uA) at (1,1,1) = _____.
(a) — (b) — (c) — (d) — (fill-in)
**Ans: (45)** — div(uA) = u(∇·A) + (∇u)·A = 3(9) + (2,2,2)·(2,3,4) = 27 + 18 = 45.
**Concept:** Product rule for divergence: ∇·(uA) = u∇·A + A·∇u.
**Twist:** div(A u) with scalar/vector swapped is the same product rule. At (1,0,0) → 3(9) + (2,0,0)·(2,3,4) = 27+4 = 31.

**Q18 (EC-GATE-20):** For the solid S shown in figure (tetrahedron with intercepts x=3, y=1, z=1), ∫∫∫_V x dx dy dz = _____ (rounded to two decimal places).
(a) — (b) — (c) — (d) — (fill-in)
**Ans: (0.375)** — ∫∫∫x dV = x̄·V = (0.75)·(3·1·1/6 = 0.5) = 0.375 (tetrahedron centroid at ¼ of each intercept).
**Concept:** Volume integral as centroid × volume; or integrate limits x:0→3(1−y−z).
**Twist:** ∫∫∫y dV → ȳ·V = (0.25)(0.5) = 0.125. ∫∫∫z dV → also 0.125; sum of x,y,z moments = 0.625.

**Q19 (EE-GATE-20):** F = âx(5y − k₁z) + ây(3z + k₂x) + âz(k₃y − 4x) is a conservative field. The values of k₁, k₂, k₃ are:
(a) k₁=3, k₂=3, k₃=7 (b) k₁=4, k₂=5, k₃=3 (c) k₁=3, k₂=8, k₃=5 (d) k₁=0, k₂=0, k₃=0
**Ans: (b)** — Curl=0 ⇒ ∂Fz/∂y−∂Fy/∂z = k₃−3 = 0, ∂Fx/∂z−∂Fz/∂x = −k₁+4 = 0, ∂Fy/∂x−∂Fx/∂y = k₂−5 = 0 → k₁=4, k₂=5, k₃=3.
**Concept:** Conservative ⇒ all mixed partials equal (∇×F=0).
**Twist:** Add a constant term to one component → constants unchanged. Ask the potential → integrate to get V = 5xy + 3yz − 4xz (+const).

**Q20 (EE-GATE-22):** E(x,y,z) = 2x²î + 5yĵ + 3zk̂. ∫∫∫_V (∇·E) dV where V is the unit cube 0≤x≤1, 0≤y≤1, 0≤z≤1 is:
(a) 3 (b) 8 (c) 10 (d) 5
**Ans: (c)** — ∇·E = 4x + 8; ∫₀¹∫₀¹∫₀¹(4x+8)dV = ∫₀¹(2+8)dx… = 10.
**Concept:** Volume integral of divergence = flux out (divergence theorem); here done directly.
**Twist:** Ask the net flux out of the cube of the same field → same 10 (divergence theorem). Change E = 2x²î+5yĵ+3z²k̂ → ∇·E = 4x+5+6z → integral = 2+5+3 = 10 again (coincidence varies by coefficients).

**Q21 (EC-GATE-23):** ∫_P^Q (z² dx + 3y² dy + 2xz dz) along the straight line joining P(1,1,2) and Q(2,3,1) is:
(a) 20 (b) 24 (c) 29 (d) −5
**Ans: (b)** — Parametrize x=1+t, y=1+2t, z=2−t (0≤t≤1): integrand = 6+18t+27t² → ∫₀¹ = 6+9+9 = 24.
**Concept:** Line integral along straight path via parametrization (dx=dt, dy=2dt, dz=−dt).
**Twist:** Not exact (∂(3y²)/∂x=0, ∂(z²)/∂y=0 mismatch) — check exactness trap: path reversal → −24. Same integrand over path (1,1,2)→(2,1,1)→(2,3,1) → different value (path dependent).

## Unit 2: Electrostatics (65 Qs)

Section A: ONE MARK QUESTIONS (Q1–Q27) · Section B: TWO MARK QUESTIONS (Q28–Q65)

## ONE MARK QUESTIONS

**Q1 (EE-GATE-92):** Which equation represents Gauss's law in a homogeneous isotropic medium?
(a) ∮D·dS = ∫ρv dv (b) ∇×H = D (c) ∇·J + ∂ρ/∂t = 0 (d) ∇·E = ρv/ε
**Ans: (d)** — In homogeneous isotropic medium D = εE, so point form ∇·E = ρv/ε.
**Concept:** Gauss's law — differential form ∇·D = ρv.
**Twist:** integral form ∮D·dS = Qenc → same law. General medium (anisotropic) → keep ∇·D = ρv.

**Q2 (EE-GATE-94):** In electrostatic field ∇×E = 0 — TRUE/FALSE
(a) TRUE (b) FALSE (c) — (d) —
**Ans: (TRUE)** — Electrostatic field is irrotational/conservative; VAB + VBA = 0 by Stokes.
**Concept:** Curl of electrostatic field = 0.
**Twist:** time-varying fields → ∇×E = −∂B/∂t ≠ 0 (Faraday) → FALSE.

**Q3 (EC-GATE-95):** Infinite plane at y = 6 m carries uniform surface charge density (1/6000π) μC/m². Associated electric field strength is
(a) 30î V/m (b) 3ĵ V/m (c) 30k̂ V/m (d) 60ĵ V/m
**Ans: (b)** — Sheet charge E = ρs/2εo = (1/6000π×10⁻⁶)/(2×(1/36π)×10⁻⁹) = 3 V/m along ±ĵ.
**Concept:** E = ρs/2εo (infinite sheet), independent of distance.
**Twist:** line charge E = ρl/2πεr → ∝ 1/r; point charge E = Q/4πεr² → ∝ 1/r².

**Q4 (EC-GATE-95):** E field at distant point P due to point charge +q at origin is 100 μV/m. If +q is enclosed by a perfectly conducting spherical sheet centred at origin, E at P outside becomes
(a) zero (b) 100 μV/m (c) −100 μV/m (d) 50 μV/m
**Ans: (b)** — Net charge enclosed is still +q (induced −q inside, +q on outer surface), so Gauss gives unchanged field.
**Concept:** Gauss's law + charge induction on conductor.
**Twist:** grounded shell → induced charges leak, field changes; off-centre charge → non-uniform surface charge.

**Q5 (EC-GATE-96):** Metal sphere radius 1 m, surface charge density 10 C/m², enclosed in a cube of 10 m side. Total outward electric displacement normal to cube surface is
(a) 40π C (b) 10π C (c) 5π C (d) None
**Ans: (a)** — ∮D·dS = Qenc = σ·4πr² = 10 × 4π(1)² = 40π C.
**Concept:** Gauss's law ∮D·dS = Qenc (surface shape irrelevant).
**Twist:** larger/smaller cube → same 40π C; sphere unenclosed → flux only part.

**Q6 (EE-GATE-96):** If v, w, q stand for voltage, energy, charge, then v can be expressed as
(a) v = dq/dw (b) v = dw/dq (c) dv = dw/dq (d) dv = dq/dw
**Ans: (c)** — Voltage = potential energy per unit charge, dv = dw/dq.
**Concept:** Potential as energy per unit charge.
**Twist:** W = ½CV² and Q = CV → combine to find C.

**Q7 (EE-GATE-98):** In a uniform electric field, field lines and equipotentials
(a) are parallel to one another (b) intersect at 45° (c) intersect at 30° (d) are orthogonal
**Ans: (d)** — Field lines are always normal to equipotential surfaces (no work moving along equipotential).
**Concept:** E ⟂ equipotential surface.
**Twist:** field stronger → lines closer together; E = −dV/dn.

**Q8 (EC-GATE-99):** Electric field on a plane given by potential V = 20(r⁻¹ + r⁻²), r from source. Field is due to
(a) a monopole (b) a dipole (c) both a monopole and dipole (d) a quadrupole
**Ans: (c)** — V ∝ 1/r (monopole) and V ∝ 1/r² (dipole) terms both present.
**Concept:** Multipole expansion: monopole ∝ 1/r, dipole ∝ 1/r².
**Twist:** only 1/r² term → dipole; only 1/r³ → quadrupole.

**Q9 (EE-GATE-04):** Parallel plate capacitor, 400 mm square plates, 14 mm gap with two dielectric layers εr=4 (6 mm) and εr=2 (8 mm); εo = 8.85×10⁻¹². Capacitance is
(a) 1298 pF (b) 944 pF (c) 354 pF (d) 257 pF
**Ans: (d)** — Two dielectrics in series; Ceq = εoA/(t1/εr1 + t2/εr2) = 257.4 pF ≈ 257 pF.
**Concept:** Series capacitors C = εoεrA/d.
**Twist:** dielectrics side-by-side (parallel) → C = εoA(εr1+εr2)/(2d) increases.

**Q10 (EE-GATE-05):** If E is the electric field intensity, ∇·(∇×E) is equal to
(a) E (b) ∇E (c) null vector (d) zero
**Ans: (d)** — Divergence of curl of any vector field is always zero.
**Concept:** Vector identity ∇·(∇×A) = 0.
**Twist:** curl of gradient ∇×(∇φ) = 0 → also used to test conservative fields.

**Q11 (EE-GATE-13):** Dielectric slab 500×500 mm² cross-section, 0.4 m long, E = 6âx + 8ây kV/mm, εr = 2, εo = 8.85×10⁻¹². Energy stored in dielectric (J)
(a) 8.85×10⁻¹¹ (b) 8.85×10⁻⁵ (c) 88.5 (d) 885
**Ans: (c)** — |E| = √(6²+8²) = 10 kV/mm = 10⁷ V/m; W = ½εoεrE²·V = 88.5 J.
**Concept:** Electrostatic energy W = ½εoεrE² × volume.
**Twist:** double E → W ×4 (energy ∝ E²); different εr → scale linearly.

**Q12 (EC-GATE-14):** Force on point charge +q kept distance d from surface of infinite grounded metal plate in medium of permittivity ε is
(a) 0 (b) q²/16πεd² away from plate (c) q²/16πεd² towards plate (d) q²/4πεd² towards plate
**Ans: (c)** — Method of images: image −q at 2d, F = q²/(4πε(2d)²) = q²/16πεd², attractive.
**Concept:** Method of images F = q²/16πεd².
**Twist:** dielectric interface (ε1≠ε2) → image magnitude scaled by (ε1−ε2)/(ε1+ε2).

**Q13 (EE-GATE-14):** Co = air parallel-plate capacitance. If half the gap is filled with dielectric εr (half-filled vertically, fig b), modified capacitance is
(a) Co(1+εr)/2 (b) (Co+εr) (c) Co εr/2 (d) Co(1+εr)
**Ans: (a)** — Half air + half dielectric in parallel: Ceq = ½Co + ½εrCo = Co(1+εr)/2.
**Concept:** Partial-fill dielectrics in parallel.
**Twist:** dielectric filling half the length (series) → C = 2εrCo/(1+εr).

**Q14 (EE-GATE-14):** Parallel plate capacitor with two dielectric materials (symmetric). If potential difference between one plate and nearest dielectric interface is 2 V, ratio ε1:ε2 is
(a) 1:4 (b) 2:3 (c) 3:2 (d) 4:1
**Ans: (c)** — Series (charge same): voltage across a dielectric ∝ 1/εr; ratio ε1/ε2 = V2/V1 = 6/4 = 3:2.
**Concept:** Series dielectrics, voltage divides inversely with capacitance.
**Twist:** given voltage drops 2 V and 6 V → ε1:ε2 = 3:2; swap V → 2:3.

**Q15 (EE-GATE-14):** Hollow metallic sphere radius r kept at potential 1 V. Total electric flux out of concentric spherical surface radius R (> r) is
(a) 4πεo r (b) 4πεo r² (c) 4πεo R (d) 4πεo R²
**Ans: (a)** — Flux = Qenc/εo; Q = CV = (4πεo r)(1) → flux = 4πεo r (independent of R).
**Concept:** Isolated sphere capacitance C = 4πεo r; Gauss flux = Qenc.
**Twist:** solid sphere at V → same C = 4πεo r; potential V0 → flux = 4πεo r V0.

**Q16 (EC-GATE-15):** In source-free region in vacuum, if electrostatic potential φ = 2x² + y² + Cz², constant C must be _____
(a) — (b) — (c) — (d) —
**Ans: (−3)** — Source-free ⇒ ∇·E = −∇²φ = 0 ⇒ −(4 + 2 + 2C) = 0 ⇒ C = −3.
**Concept:** Laplace's equation ∇²φ = 0 in charge-free region.
**Twist:** with charge ρ ⇒ Poisson ∇²φ = −ρ/εo; different coefficients → different C.

**Q17 (EE-GATE-15):** Match: P. Stokes theorem, Q. Gauss's theorem, R. Divergence theorem, S. Cauchy's Integral theorem
(a) P(2),Q(1),R(4),S(3) (b) P(4),Q(1),R(3),S(2) (c) P(4),Q(3),R(1),S(2) (d) P(3),Q(4),R(2),S(1)
**Ans: (b)** — Stokes ∮A·dl = ∬(∇×A)·dS (4); Gauss ∮D·dS = Q (1); Divergence ∭∇·A dv = ∮A·dS (3); Cauchy ∮f(z)dz = 0 (2).
**Concept:** Integral theorems of vector calculus.
**Twist:** Green's theorem → line/surface conversion; curl theorem for Ampere.

**Q18 (EC-GATE-16):** Concentric spherical shells radii 2 m, 4 m, 8 m carry surface densities 20 nC/m², −4 nC/m², ρs. ρs (nC/m²) so that D = 0 at radius 10 m
(a) — (b) — (c) — (d) —
**Ans: (−0.25)** — Qenc = 0 ⇒ 20·4π(2)² − 4·4π(4)² + ρs·4π(8)² = 0 ⇒ 320π − 256π + 256πρs = 0 ⇒ ρs = −0.25.
**Concept:** Gauss's law, flux ∝ σ·4πr² per shell.
**Twist:** D = 0 at other radius → different ρs; only 2 shells → simpler.

**Q19 (EE-GATE-16):** Potential of uniform ring charge in cylindrical coords φ = f(r,z). Magnitude of ∇×E is
(a) increases with r (b) is 0 (c) is 3 (d) decreases with z
**Ans: (b)** — Electrostatic field is conservative/irrotational ⇒ ∇×E = 0 everywhere.
**Concept:** ∇×E = 0 for any static charge distribution.
**Twist:** E = −∇φ always curl-free; curl-free also implies E derivable from scalar potential.

**Q20 (EE-GATE-16):** Parallel plate capacitor with two dielectrics side by side (regions A: εr=1, B: εr=4). If E in region A is 4 kV/cm, E in region B (kV/cm) is
(a) 1 (b) 2 (c) 4 (d) 16
**Ans: (c)** — Side-by-side dielectrics share same voltage ⇒ same E = V/d = 4 kV/cm.
**Concept:** Parallel dielectrics → equal voltage → equal E.
**Twist:** dielectrics stacked (series) → D continuous, E ∝ 1/εr ⇒ B = 1 kV/cm.

**Q21 (EE-GATE-16):** Two electrodes at same potential (cross-sectional view). Maximum electric field will be at point
(a) A (b) B (c) C (d) D
**Ans: (a)** — At A fields from both electrodes add; at C subtract; E strongest where field lines crowd (closest electrodes).
**Concept:** E is largest where flux lines concentrate / fields superpose.
**Twist:** sharpen electrode corners → further crowding → higher E; breakdown first at A.

**Q22 (EC-GATE-17):** Two conducting spheres radii a and b (b > a), far apart, joined by a long thin wire. For charge on structure, potential and surface field on S1 are Va, Ea and on S2 are Vb, Eb. Correct statement
(a) Va = Vb & Ea < Eb (b) Va > Vb & Ea > Eb (c) Va = Vb & Ea > Eb (d) Va > Vb & Ea = Eb
**Ans: (c)** — Wired ⇒ equal potential Va = Vb; surface E = V/r ⇒ smaller sphere (a) has larger E, Ea > Eb.
**Concept:** Connected conductors equalize potential; E ∝ 1/r for equal V.
**Twist:** Ea/Eb = rb/ra; charge mostly on smaller sphere (charge ∝ radius).

**Q23 (EE-GATE-17):** Solid sphere radius 5 cm of perfect electric conductor; one million electrons added. Electrons are distributed
(a) uniformly over the entire volume (b) uniformly over the outer surface (c) concentrated at the centre (d) along a line through the centre
**Ans: (b)** — Static charge resides on the outer surface of a conductor.
**Concept:** Excess charge on conductor surface, E inside = 0.
**Twist:** for isolated sphere → uniform surface density; shaped conductor → density ∝ curvature.

**Q24 (EE-GATE-18):** Positive charge 1 nC at (0,0,0.2) m; xy-plane is conducting ground; εo = 8.85×10⁻¹². z-component of E at (0,0,0.1) is
(a) 899.18 V/m (b) −899.18 V/m (c) 999.09 V/m (d) −999.09 V/m
**Ans: (d)** — Image −1 nC at (0,0,−0.2); E_z = −(1/4πεo)[1/(0.1)² + 1/(0.3)²]×10⁻⁹ = −999.09 V/m.
**Concept:** Method of images + superposition (E_z additive, pointing −z).
**Twist:** charge height h, point at z0 → distances (h−z0) and (h+z0); different values.

**Q25 (EC-GATE-19):** Electric flux ∮E·da through a quarter-cylinder of height H due to an infinitely long line charge along the axis with charge density Q is
(a) HQ/εo (b) HQ/4εo (c) 4H/Qεo (d) Hεo/4Q
**Ans: (b)** — Flux = Qenc/εo; quarter cylinder encloses (Q·H)/4 of line charge ⇒ HQ/4εo.
**Concept:** Gauss's law, enclosed charge fraction.
**Twist:** full cylinder → HQ/εo; half cylinder → HQ/2εo; double height → double flux.

**Q26 (EE-GATE-19):** Coaxial cylindrical capacitor (fig i) with εr1 = 2. When one-fourth portion is replaced by εr2 (fig ii), capacitance doubles. εr2 = _____
(a) — (b) — (c) — (d) —
**Ans: (10)** — C1+C2 in parallel: [3εr1+εr2]·π/(4ln(R/r)) = 2·[2πεr1/ln(R/r)] ⇒ 3(2)+εr2 = 16 ⇒ εr2 = 10.
**Concept:** Partial dielectrics in parallel (angular sectors of coaxial cap).
**Twist:** half replaced → εr2 = 6; quarter with different εr1 → recompute.

**Q27 (EE-GATE-2021):** 1 μC at origin; 10 μC moved from (0,10,0) to (5,5,5) then to (5,0,0). Total work done (mJ), round to 2 decimals; 1/4πεo = 9×10⁹
(a) — (b) — (c) — (d) —
**Ans: (9)** — Work = Q2(Vfinal−Vinitial) = 10⁻⁵×9×10⁹×10⁻⁶(1/5 − 1/10) = 9 mJ (path independent).
**Concept:** Work = Q·ΔV; E conservative.
**Twist:** move to same radius → W = 0; different final distance r → W ∝ (1/r1−1/r2).

## TWO MARK QUESTIONS

**Q28 (EC-GATE-89):** E field at far-off point P due to +q at origin O is 100 mV/m. Point charge now enclosed by a perfectly conducting hollow metal sphere centred at O. E at P is
(a) unchanged in magnitude and direction (b) unchanged in magnitude but reversed in direction (c) that due to a dipole (+q at O, −q induced) (d) zero
**Ans: (a)** — Net charge enclosed by any Gaussian surface outside is still +q (induced −q inner, +q outer), so field is 100 mV/m unchanged.
**Concept:** Gauss's law + induced charge on conducting shell.
**Twist:** grounded shell → outer +q drains → field zero; two-mark re-test of Q4.

**Q29 (EE-GATE-92):** Electrostatic potential φ = 2xy V in rectangular coordinates. Magnitude of E at x = 1 m, y = 1 m is _____ V/m
(a) — (b) — (c) — (d) —
**Ans: (√5)** — E = −∇φ = −(2y î + 2x ĵ); magnitude at (1,1) evaluated as √5 V/m per OHM key.
**Concept:** E = −∇V.
**Twist:** potential φ = x²y² → different gradient; φ = x²+y² → |E| = 2√(x²+y²).

**Q30 (EC-GATE-93):** Uniformly charged sphere radius R, charge density ρ. Ratio of magnitude of E at r = R/2 to E at r = 2R, i.e. E(R/2)/E(2R) is _____
(a) — (b) — (c) — (d) —
**Ans: (2)** — Inside: E1 = Qr/(4πεR³) at R/2 = Q/(8πεR²); outside: E2 = Q/(16πεR²); ratio = 2.
**Concept:** Gauss inside/outside uniformly charged sphere.
**Twist:** at r = R/3 vs 3R → ratio 4.5; inside E ∝ r, outside E ∝ 1/r².

**Q31 (EC-GATE-94):** Match A: ∇×H = J, B: ∮E·dl = −d/dt∮B·ds, C: ∇×J = −∂ρv/∂t with (1) Continuity, (2) Faraday, (3) Ampere, (4) Gauss, (5) Biot-Savart
(a) — (b) — (c) — (d) —
**Ans: (A→3, B→2, C→1)** — Ampere's law, Faraday's law, continuity equation respectively.
**Concept:** Maxwell's equations / fundamental laws matching.
**Twist:** ∇·D = ρv → Gauss; ∇·B = 0 → no isolated magnetic poles.

**Q32 (EE-GATE-97):** Capacitance of the arrangement (20 cm square plate, three dielectrics εr = 1, 2, 4 in 10 cm/20 cm/10 cm regions) is _____ pF
(a) — (b) — (c) — (d) —
**Ans: (4.72)** — C1,C2 in series then parallel with C3: Ceq = (2/3)C0 + 2C0 = (8/3)C0 = 4.72 pF.
**Concept:** Mixed series/parallel capacitor network.
**Twist:** reorder dielectric thicknesses → different equivalent C.

**Q33 (EE-GATE-97):** Capacitance of an isolated sphere of radius 10 cm in air is ___ pF
(a) — (b) — (c) — (d) —
**Ans: (11.11)** — C = 4πεoεrR = 4π(1/36π×10⁻⁹)(0.1) = 11.11 pF.
**Concept:** Isolated conducting sphere capacitance C = 4πεoR.
**Twist:** immersed in oil εr = 4 → 44.4 pF; radius doubled → 22.2 pF.

**Q34 (EE-GATE-01):** E (V/m) at point (1,1,0) due to point charge +1 μC at (−1,1,1), coordinates in metres
(a) 10⁻⁶/(20√5πεo)(2î−k̂) (b) 10⁻⁵/(20πεo)(2î−k̂) (c) −10⁻⁴/(20√5πεo)(2î−k̂) (d) −10⁻⁶/(20πεo)(2î−k̂)
**Ans: (a)** — r = (2,0,−1), |r| = √5; E = (q/4πεo r³)r = 10⁻⁶(2î−k̂)/(20√5πεo).
**Concept:** Coulomb's law in vector form E = q r̂/4πεo r².
**Twist:** charge at different location → different displacement vector; negative charge → reversed.

**Q35 (EE-GATE-01):** Potential V(x,y,z) = 50(x²+y²+z²) V. Magnitude and direction of E at (1,−1,1)
(a) 100; (i+j+k) (b) 100√3; (i+j+k) (c) 100√3; (−i−j−k)/√3 (d) 100√3; (−i+j−k)/√3
**Ans: (d)** — E = −∇V = −100(î−ĵ+k̂); |E| = 100√3, direction (−î+ĵ−k̂)/√3.
**Concept:** E = −∇V (potential gradient).
**Twist:** V = 50(x²−y²+z²) → different direction; E always points downhill in potential.

**Q36 (EC-GATE-03):** Parallel plate air capacitor, A = 10⁻⁴ m², d = 10⁻³ m, connected to 0.5 V, 3.6 GHz source. Magnitude of displacement current (εo = 1/36π×10⁻⁹)
(a) 10 mA (b) 100 mA (c) 10 A (d) 1.59 mA
**Ans: (a)** — Jd = ωεE = 2π×3.6×10⁹×(1/36π)×10⁻⁹×500 = 100 A/m²; id = Jd·A = 10⁻² A = 10 mA.
**Concept:** Displacement current Jd = ∂D/∂t = ωεE.
**Twist:** higher f → id ∝ f; larger plate area → id ∝ A.

**Q37 (EE-GATE-03):** Point charge +1 nC placed in space (ε = 8.85×10⁻¹² F/m). Potential difference VPQ between points P, Q at 40 mm and 20 mm from charge
(a) 0.22 kV (b) −225 V (c) −2.24 kV (d) 15 V
**Ans: (b)** — VPQ = VP − VQ = (q/4πεo)(1/0.04 − 1/0.02) = −225 V.
**Concept:** Potential of point charge V = q/4πεo r; V = −∫E·dl.
**Twist:** P closer than Q → positive VPQ; 10 nC → −2.25 kV.

**Q38 (EE-GATE-03):** Parallel plate capacitor, area 100 mm², spacing 0.1 mm, air (ε = 8.85×10⁻¹²), V = 100 V. Stored energy
(a) 8.85 pJ (b) 440 pJ (c) 22.1 nJ (d) 44.3 nJ
**Ans: (d)** — C = 8.85 pF; W = ½CV² = ½(8.85×10⁻¹²)(100)² = 44.25 nJ.
**Concept:** Energy W = ½CV².
**Twist:** with dielectric εr → C×εr, W×εr; V doubled → W×4.

**Q39 (EE-GATE-03):** Composite parallel plate capacitor, two dielectrics (εr=3, t1=0.5 mm) separated by conducting foil F, applied 100 V–0 V. Voltage of foil F is
(a) 52 V (b) 60 V (c) 67 V (d) 33 V
**Ans: (b)** — Voltage across C2 = C1/(C1+C2)×100; C1 = 6k, C2 = 4k ⇒ VF = 6/10×100 = 60 V.
**Concept:** Series capacitors → voltage divider by 1/C.
**Twist:** equal thickness & εr → 50 V; ratio 1:2 → 66.7 V.

**Q40 (EE-GATE-06):** Statements about equation ∇·J = −∂ρv/∂t: 1. point form of continuity; 2. divergence of J = decrease of charge per unit volume; 3. Maxwell's divergence equation; 4. conservation of charge
(a) only 2 & 4 true (b) 1, 2 & 3 true (c) 2, 3 & 4 true (d) 1, 2 & 4 true
**Ans: (d)** — Continuity equation expresses charge conservation (statements 1, 2, 4 true; it is not a Maxwell divergence equation).
**Concept:** Continuity equation ∇·J = −∂ρv/∂t.
**Twist:** steady current ∇·J = 0 → statement 3 only under special case.

**Q41 (EE-GATE-07):** Solid sphere (insulating), radius R, total charge Q uniformly distributed. Magnitude of E at distance r (0 < r < R) inside is
(a) Qr/4πεoR³ (b) 3Qr/4πεoR³ (c) Q/4πεo r² (d) QR/4πεo r³
**Ans: (a)** — Gaussian sphere at r encloses Qenc = Q r³/R³ ⇒ E = Qr/(4πεoR³).
**Concept:** Gauss's law inside uniform charge distribution (E ∝ r).
**Twist:** E outside = Q/4πεo r²; at surface Q/4πεoR²; hollow sphere inside → E = 0.

**Q42 (EE-GATE-08):** Q1 = 10 μC at (1,1,0) and Q2 = 20 μC at (−1,−1,0). Total electric flux passing through plane z = 20
(a) 7.5 μC (b) 13.5 μC (c) 15.0 μC (d) 22.5 μC
**Ans: (c)** — Both charges are below the plane; each contributes half its flux ⇒ 10/2 + 20/2 = 15 μC.
**Concept:** Flux through infinite plane = half the enclosed charge.
**Twist:** charge exactly on plane → ambiguous; plane between opposite charges → flux = Q1+Q2.

**Q43 (EE-GATE-08):** Capacitor, plates 500×500 mm², 6 mm apart, glass 4 mm (εr=8) + paper 2 mm (εr=2). Capacitance (εo = 8.85×10⁻¹²)
(a) 983.33 pF (b) 1475 pF (c) 6637.5 pF (d) 9956.25 pF
**Ans: (b)** — Series dielectrics: Ceq = CgCp/(Cg+Cp) = 500εo·250εo/750εo = 1475 pF.
**Concept:** Series combination of dielectric layers.
**Twist:** equal layers εr=8 & 2 with equal thickness → different value; parallel layout → sum.

**Q44 (EE-GATE-08):** Lossy capacitor Cr rated 5 kV, 50 Hz; Cp = 0.102 μF in parallel with Rp = 1.25 MΩ. Power loss and tanδ
(a) 10 W and 0.0002 (b) 10 W and 0.0025 (c) 20 W and 0.025 (d) 20 W and 0.04
**Ans: (c)** — P = V²/Rp = (5×10³)²/1.25×10⁶ = 20 W; tanδ = 1/(ωRpCp) = 0.025.
**Concept:** Power loss P = V²/Rp; dissipation factor tanδ = 1/ωRpCp.
**Twist:** series RC model → tanδ = ωRsCs; higher f → lower tanδ.

**Q45 (EE-GATE-11):** Capacitor with polymer dielectric εr=2.26, breakdown 50 kV/cm, plates 20×40 cm, εo = 8.85 pF/m. Maximum charge in capacitor
(a) 2 μC (b) 4 μC (c) 8 μC (d) 10 μC
**Ans: (c)** — Q = CV = εoεrA·(V/d) = εoεrA·Ebd = 8 μC.
**Concept:** Qmax = εoεrA·Ebreakdown.
**Twist:** larger plate area → more charge; thicker dielectric at same breakdown field → more Q.

**Q46 (EE-GATE-13):** C1=10 μF/10 V, C2=5 μF/5 V, C3=2 μF/2 V (C2,C3 in series, both parallel with C1). Max safe voltage and effective capacitance across terminals
(a) 2.8 and 36 (b) 7 and 119 (c) 2.8 and 32 (d) 7 and 80
**Ans: (*)** — Vmax = V2'+V3 = 4/5+2 = 2.8 V; Ceff = C1 + C2C3/(C2+C3) = 11.43 μF (no option matches; OHM marks *).
**Concept:** Series charge limiting + voltage rating; Ceff of series-parallel network.
**Twist:** different ratings → different safe voltage; correct pair (2.8 V, 11.43 μF).

**Q47 (EC-GATE-14):** One-dimensional E between points A and B (staircase: 0→20 kV/cm→40 kV/cm over 5 μm). ΨB − ΨA in volts
(a) — (b) — (c) — (d) —
**Ans: (−15)** — ΨB−ΨA = −∫E dx = −(area under E-x) = −15 V.
**Concept:** V = −∫E·dl (potential = −area under E curve).
**Twist:** reverse gradient → +15 V; different E levels → different area.

**Q48 (EC-GATE-14):** E = −(2y³−3yz²)x̂ −(6xy²−3xz²)ŷ + (6xyz)ẑ in a source-free region. Valid expression for electrostatic potential
(a) xy³−yz² (b) 2xy³−xyz² (c) y³+xyz² (d) 2xy³−3xyz²
**Ans: (d)** — Integrate E = −∇V: V = 2xy³ − 3xyz² (+const).
**Concept:** E = −∇V; potential integral of a conservative field.
**Twist:** change coefficients → verify ∇×E = 0 first; any curl-free E admits a scalar potential.

**Q49 (EE-GATE-14):** Perfectly conducting metal plate in xy-plane. Charge +32πεo² C at (0,0,2). Electric field vector E at (2,2,0) (N/C)
(a) 2√2 k̂ (b) −2k̂ (c) 2k̂ (d) −2√2 k̂
**Ans: (b)** — Image −Q at (0,0,−2); E = Q(r1⃗−r2⃗)/4πεo r³ = −2k̂.
**Concept:** Method of images over conducting plane.
**Twist:** observation point off-axis → nonzero x,y components; different plate → image distance changes.

**Q50 (EC-GATE-15):** Coaxial capacitor, inner 1 mm, outer 5 mm, C = 172 pF/m. If b/a ratio doubled, capacitance per unit length (pF/m) is
(a) — (b) — (c) — (d) —
**Ans: (120.22)** — C/L = 2πε/ln(b/a); C2 = 172·ln5/ln10 = 120.22 pF/m.
**Concept:** Coaxial capacitance C/L = 2πε/ln(b/a).
**Twist:** C ∝ 1/ln(b/a); halve b/a → C = 172·ln5/ln2.5.

**Q51 (EE-GATE-15):** Parallel plate partially filled with glass εr=4. Dielectric strengths: air 30 kV/cm, glass 300 kV/cm. Maximum voltage without breakdown (kV)
(a) — (b) — (c) — (d) —
**Ans: (18.75)** — Air (0.5 cm) limits at 30×0.5 = 15 kV; with 4C:15 split, Vmax = 15 + 3.75 = 18.75 kV.
**Concept:** Breakdown limited by weakest dielectric layer; series voltage division.
**Twist:** thicker air layer → higher limit; glass thinner → glass limits.

**Q52 (EE-GATE-15):** Two semi-infinite conducting sheets at right angles; +Q placed distance d from both. Net force = Q²K/4πεo d², where K is
(a) 0 (b) −1/4 î −1/4 ĵ (c) −1/8 î −1/8 ĵ (d) (1−2√2)/8√2 î + (1−2√2)/8√2 ĵ
**Ans: (d)** — Three image charges (two −Q, one +Q): F = (Q²/4πεod²)·[(1−2√2)/(8√2)](î+ĵ).
**Concept:** Method of images at a 90° conducting corner (3 images).
**Twist:** 60° corner → 5 images; infinite plane only → 1 image (K = −1/8).

**Q53 (EC-GATE-16):** Positive charge q at x=0 between infinite metal plates at x=−d and x=+d (yz-planes). +V applied to left plate, −V to right. Time for q to reach right plate is proportional to
(a) d/V (b) d/V (c) d/√V (d) d/V
**Ans: (c)** — E = 2V/d constant; t = √(2md/qE) ∝ d/√V.
**Concept:** Uniform acceleration in constant E; t ∝ √(md/qV).
**Twist:** higher V → shorter time (t ∝ 1/√V); heavier charge → longer.

**Q54 (EC-GATE-16):** Parallel plate capacitor (movable plates), energy E at separation d. Charged, isolated, plates moved to separation 2d. New stored energy
(a) 2E (b) √2E (c) E (d) E/2
**Ans: (a)** — Isolated ⇒ Q constant; C halves, W = Q²/2C doubles ⇒ E' = 2E.
**Concept:** W = Q²/2C with constant charge.
**Twist:** source still connected (V const) → C halves, W = ½CV² halves ⇒ E/2.

**Q55 (EC-GATE-16):** Current density J = 400 sinθ/(2π(r²+4)) âr A/m². Total current and average current density through spherical surface r = 0.8 m, π/12≤θ≤π/4, 0≤φ≤2π
(a) 15.09 A, 12.86 A/m² (b) 18.73 A, 13.65 A/m² (c) 12.86 A, 9.23 A/m² (d) 10.28 A, 7.56 A/m²
**Ans: (*)** — I = ∬J·dS = 14.3 A; Javg = I/A = 13.75 A/m² (no option matches; OHM marks *).
**Concept:** Current through a surface I = ∬J·dS; Javg = I/Area.
**Twist:** full sphere (0≤θ≤π) → larger I; different θ window → different fraction.

**Q56 (EE-GATE-16):** q at (0,0) and −2q at (6,0) on xy-plane. Equation of the zero equipotential curve
(a) x = −2 (b) y = 2 (c) x²+y² = 2 (d) (x+2)²+y² = 16
**Ans: (d)** — V = Kq/√(x²+y²) + K(−2q)/√((x−6)²+y²) = 0 ⇒ (x+2)²+y² = 16.
**Concept:** Zero-potential locus from superposition (equipotential circle).
**Twist:** charges q and −q → perpendicular bisector line; q and +2q same sign → no finite zero curve.

**Q57 (EC-GATE-17):** Electron moving at 10⁵ m/s in free space towards a stationary electron. Closest distance before repulsion diverts path = _ ×10⁻⁸ m (m = 9.11×10⁻³¹, e = −1.6×10⁻¹⁹, εo = 1/36π×10⁻⁹)
(a) — (b) — (c) — (d) —
**Ans: (5.06)** — ½mv² = Ke²/d ⇒ d = (9×10⁹×e²)/(½mv²) = 5.06×10⁻⁸ m.
**Concept:** Energy conservation KE → electrostatic PE at closest approach.
**Twist:** double v → d ÷4 (∝1/v²); charges ±e attractive → d from energy with opposite sign.

**Q58 (EE-GATE-17):** Thin soap bubble radius R=1 cm, thickness a=3.3 μm, at potential 1 V. Bursts into single spherical drop radius r (volume 4πR²a = 4/3πr³). Potential of drop (V)
(a) — (b) — (c) — (d) —
**Ans: (10.03)** — Charge conserved: Vdrop = Vbubble·(R/r); 4πR²a = 4/3πr³ ⇒ r = 9.97×10⁻⁴ m ⇒ Vdrop = 10.03 V.
**Concept:** Potential V = Q/4πεoR; volume conservation for charge.
**Twist:** thicker film (bigger a) → bigger drop → smaller V; V ∝ 1/r.

**Q59 (EE-GATE-18):** Air parallel-plate capacitance 60 pF. A dielectric slab of half the plate spacing, covering one plate, raises C to 86 pF. Relative permittivity (2 decimals)
(a) — (b) — (c) — (d) —
**Ans: (2.50)** — Ceq = 2C1εr/(εr+1); 86/60 = 2εr/(εr+1) ⇒ εr = 2.50.
**Concept:** Half-filled dielectric in series with air gap.
**Twist:** slab of thickness d/3 → different equation; εr given, find C.

**Q60 (EE-GATE-2020):** Static E in dielectric εr=2.25 (cylindrical): E = âr 2r + âφ 3/r + âz 6. Volume charge density in terms of εo
(a) 4εo (b) 5εo (c) 3εo (d) 9εo
**Ans: (d)** — ρv = ∇·(εoεrE) = 2.25εo·(1/r ∂(r·2r)/∂r + 0 + 0) = 2.25εo·4 = 9εo.
**Concept:** Gauss's law differential form ρv = ∇·D = ∇·(εoεrE).
**Twist:** εr = 1 → ρv = 4εo; different E components → different divergence.

**Q61 (EE-GATE-20):** D = âr 15 + âφ 2r − âz 3rz C/m². Total flux emanating from cylinder radius 3 m, height 5 m (base at origin)
(a) 108π (b) 54π (c) 90π (d) 180π
**Ans: (d)** — ∮D·dS = ∫∇·D dv; ∇·D = 15/r − 3r ⇒ Q = ∫(15−3r²)dr dφ dz = 180π C.
**Concept:** Divergence theorem / Gauss's law for flux.
**Twist:** different radius/height → different flux; taller cylinder → more flux.

**Q62 (EC-GATE-21):** D = ρcos²φ âρ + z²sin²φ âφ (cylindrical). Net flux leaving closed surface of cylinder ρ=3, 0≤z≤2 (2 decimals)
(a) — (b) — (c) — (d) —
**Ans: (56.52)** — Q = ∬Dρ dS over side surface = ∫ρ³cos²φ dφ dz = 9×π×2 = 18π = 56.52 C.
**Concept:** Flux through closed surface = surface integral of D (Gauss).
**Twist:** height 4 → 113.04; ρ=2 → flux ∝ ρ³.

**Q63 (EE-GATE-21):** Large parallel plate, gap fully filled with dielectric εr=5, charged to V, disconnected. Dielectric pulled out completely. Ratio of new field E2 to original E1
(a) — (b) — (c) — (d) —
**Ans: (5)** — Q constant ⇒ D constant; E = D/ε, removing dielectric multiplies E by εr ⇒ E2/E1 = 5.
**Concept:** D continuous at constant Q; E ∝ 1/εr.
**Twist:** half pulled out → two regions; source connected → V fixed, E2/E1 = 1.

**Q64 (EC-GATE-22):** D(x,y,z) = x³î + y³ĵ + xy²k̂ C/m². Electric charge enclosed in cube centred at origin, side 1 m (vertices ±0.5)
(a) — (b) — (c) — (d) —
**Ans: (0.5)** — Q = ∫∇·D dv; ∇·D = 3x²+3y² ⇒ Q = 3(x³/3)·(1)(1)×2 terms = 0.5 C.
**Concept:** Gauss's law Q = ∮D·dS = ∫∇·D dv (divergence theorem).
**Twist:** larger cube side 2 m → Q = 8×; D symmetric → only x,y terms contribute.

**Q65 (EE-GATE-22):** Two concentric conducting spherical shells radii r=c and r=d at potentials V1 and V2. Expression for V(r) between them (V depends only on r)
(a) V(r) = cd(V2−V1)/[(d−c)r] − (V1c+V2d−2V1d)/(d−c) (b) V(r) = cd(V1−V2)/[(d−c)r] + (V2d−V1c)/(d−c) (c) V(r) = cd(V1−V2)/[(d−c)r] − (V1c−V2c)/(d−c) (d) V(r) = cd(V2−V1)/[(d−c)r] − (V2c−V1c)/(d−c)
**Ans: (b)** — Laplace ∇²V=0 (ρv=0): V = −c1/r + c2; apply V(c)=V1, V(d)=V2 ⇒ cd(V1−V2)/[(d−c)r] + (V2d−V1c)/(d−c).
**Concept:** Laplace equation in spherical symmetry, potential 1/r form.
**Twist:** grounded outer (V2=0) → V = V1·[d(r−c)]/[r(d−c)]; different c,d → recompute constants.

## Unit 3: Magnetostatics (39 Qs)

## ONE MARK QUESTIONS

**Q1 (EE-GATE-93):** The line integral of the magnetic vector potential A around the boundary of a surface S represents
(a) Flux through the surface S (b) Flux density in the surface S (c) Magnetic density (d) Current density
**Ans: (a)** — ∮A·dl = ∬(∇×A)·ds = ∬B·ds = flux ψ through S (Stokes' theorem).
**Concept:** Stokes' theorem; A = magnetic vector potential, B = ∇×A.
**Twist:** Line integral of H·dl over closed path → μ0·I_enc (Ampere's law). ∮E·dl → −dφ/dt (Faraday).

**Q2 (EE-GATE-94):** "Static magnetic fields induce currents in closed conducting loops." True or False?
(a) True (b) False
**Ans: (b)** — Static B ⇒ flux φ = BA constant ⇒ e = −dφ/dt = 0, no induced current.
**Concept:** Faraday's law — only a time-varying flux induces emf/current.
**Twist:** Time-varying B → eddy currents induced → True. Loop moving in static B (motional emf) → current induced.

**Q3 (EE-GATE-96):** Energy stored in magnetic field of a solenoid (30 cm long, 3 cm diameter, 1000 turns, 10 A)?
(a) 0.015 J (b) 0.15 J (c) 0.5 J (d) 1.15 J
**Ans: (b)** — W = ½LI², L = μ0N²A/l → 0.15 J.
**Concept:** L = μ0N²A/l for solenoid; W = ½LI².
**Twist:** Double current → energy ×4. Iron core (μr) → energy ×μr.

**Q4 (EE-GATE-98):** Faraday's and Lenz's laws are summarized in which equation?
(a) e = iR (b) e = L·di/dt (c) e = −dψ/dt (d) None of these
**Ans: (c)** — e = −dψ/dt combines Faraday (dψ/dt) with Lenz's (−sign).
**Concept:** Faraday–Lenz law e = −dψ/dt.
**Twist:** Constant-L self induction → e = −L·di/dt. Lenz sign dropped (magnitude only) → e = +dψ/dt.

**Q5 (EE-GATE-99):** Two parallel wires distance d apart, equal current I in the same direction. Magnetic field on the line midway between them
(a) depends on I (b) is zero (c) depends on d (d) depends on permeability of the medium
**Ans: (b)** — Equal H = I/πd at midpoint, opposite directions, cancel.
**Concept:** B = μ0I/2πr for a long wire; superposition.
**Twist:** Opposite-direction currents → fields add → B = μ0I/πd. Unequal currents → net = μ0(I1−I2)/πd.

**Q6 (EE-GATE-99):** An electromagnetic field is radiated from
(a) a stationary point charge (b) a capacitor with a DC voltage (c) a conductor carrying DC current (d) an oscillating dipole
**Ans: (d)** — Radiation needs accelerated charge; an oscillating dipole is continuously accelerated.
**Concept:** Radiation from accelerated charge.
**Twist:** Stationary/DC charges → static fields, no radiation. Uniform-velocity charge → no radiation.

**Q7 (EE-GATE-00):** An electron (charge −e) with velocity u in electric field E and magnetic field B experiences force
(a) −eE (b) −eu×B (c) −e(u×E×B) (d) −e(E + u×B)
**Ans: (d)** — Lorentz force F = q(E + u×B) with q = −e.
**Concept:** Lorentz force F = q(E + v×B).
**Twist:** Proton (+e) → +e(E + u×B). Velocity parallel to B → magnetic term zero → F = −eE only.

**Q8 (EE-GATE-03):** Two conductors carry forward and return currents +I and −I; field H at point P equidistant (d) from both, along y
(a) I/πd ŷ (b) I/πd x̂ (c) I/2πd ŷ (d) I/2πd x̂
**Ans: (a)** — H = I/(2πd) + I/(2πd) = I/πd in +ŷ (both contributions add in y).
**Concept:** B = μ0I/2πr; superposition of fields.
**Twist:** Same-direction currents at P between them → cancel → H = 0. Unequal distances → H = (I/2π)(1/d1 − 1/d2).

**Q9 (EE-GATE-03):** Two infinite strips of width W carrying +I and −I (z-direction), separated by d, give inductance L H/m. If separation is reduced to d/2, the inductance per unit length becomes
(a) 2L H/m (b) L/4 H/m (c) L/2 H/m (d) 4L H/m
**Ans: (c)** — L' = μ0·d/w ∝ d, so halving d halves L.
**Concept:** Inductance of parallel strips L = μ0·d/w (per unit length).
**Twist:** Double strip width W → L halves. Double both W and d → L unchanged.

**Q10 (EE-GATE-04):** Inductance of a long solenoid (length 1000 mm, 3000 turns, 60 mm diameter)?
(a) 3.2 μH (b) 3.2 mH (c) 32.0 mH (d) 3.2 H
**Ans: (c)** — L = μ0N²A/l = 32.0 mH.
**Concept:** L = μ0N²A/l.
**Twist:** Double turns → L ×4. Iron core μr = 1000 → L ≈ 32 H.

**Q11 (EE-GATE-06):** Which statement holds for divergence of electric and magnetic flux densities?
(a) Both are zero (b) Zero for static but non-zero for time-varying densities (c) Zero for electric flux density (d) Zero for magnetic flux density
**Ans: (d)** — ∇·B = 0 always; ∇·D = ρv (not zero).
**Concept:** Gauss law for magnetism ∇·B = 0 (no magnetic monopoles).
**Twist:** ∇·D = ρv (non-zero in charge regions). Even for time-varying fields ∇·B = 0 still holds.

**Q12 (EC-GATE-09):** Two infinitely long 1 A wires — one in the y–z plane parallel to y-axis, the other in the x–y plane parallel to x-axis. Which B components are non-zero at the origin?
(a) x, y, z (b) x, y (c) y, z (d) x, z
**Ans: (d)** — Wire 1 gives H in −âx, wire 2 gives H in −âz → only x and z components.
**Concept:** Right-hand thumb rule for H around a long wire.
**Twist:** Wires reoriented (both in x-y plane) → different component mix. Currents reversed → signs flip, components unchanged.

**Q13 (EE-GATE-13):** B = 4x âx + 2ky ây + 8 âz mWb/m². The constant k must equal
(a) −2 (b) −0.5 (c) +0.5 (d) +2
**Ans: (a)** — ∇·B = 4 + 2k + 0 = 0 ⇒ k = −2.
**Concept:** ∇·B = 0 (solenoidal field).
**Twist:** If 8 became 8z → 4 + 2k + 8 = 0 → k = −6. For an E-field ∇·E = ρv/ε0 ≠ 0 → k not constrained by divergence.

**Q14 (EC-GATE-15):** For an infinitely long current-carrying conductor on the z-axis, which linear-scale plot shows Hφ vs r (outside conductor)?
(a) flat line (b) rising line (c) decaying hyperbola (Hφ ∝ 1/r) (d) rising then flat
**Ans: (c)** — Hφ = I/2πr outside, a rectangular hyperbola.
**Concept:** B = μ0I/2πr.
**Twist:** Inside conductor → Hφ ∝ r (linear rise). For a dipole at distance r → 1/r² decay.

**Q15 (EE-GATE-15):** One-turn rectangular loop (10 cm × 5 cm), R = 0.4 Ω, negligible L, in B(t) = 0.25 sin ωt (ω = 2π×50 rad/s), plane ⊥ field. Power absorbed (W)? [Numerical]
(a) — (b) — (c) — (d) —
**Ans: 0.1918 W** — Vrms = (A·B·ω)/√2 = 0.277 V, P = Vrms²/R = 0.1918 W.
**Concept:** Faraday's law; P = Vrms²/R.
**Twist:** Double B → power ×4. Double R → power halves. Loop plane ∥ B → flux zero → P = 0.

**Q16 (EE-GATE-15):** Circular turn radius 1 m revolves at 60 rpm about its x-axis diameter in H = 10⁷ ẑ A/m. Peak induced voltage Vturn (V)? [Numerical]
(a) — (b) — (c) — (d) —
**Ans: 248.05 V** — Vmax = μ0HAω = 4π×10⁻⁷·10⁷·π·2π = 8π³ = 248.05 V.
**Concept:** Vmax = BAω with B = μ0H.
**Twist:** Halve H → Vmax halves. Double speed (120 rpm) → ω doubles → Vmax doubles.

**Q17 (EE-GATE-15):** Two infinitely long wires at y = ±L/2 carry current I in +x. The B field at (0, L, 0) is
(a) −4μ0I/(3πL) ẑ (b) 4μ0I/(3πL) ẑ (c) 0 (d) −3μ0I/(4πL) ẑ
**Ans: (a)** — B = −(μ0I/2π)[1/(3L/2) + 1/(L/2)] ẑ = −4μ0I/(3πL) ẑ.
**Concept:** B = μ0I/2πr; superposition of two long wires.
**Twist:** Opposite currents → z-components cancel at point on axis → B = 0. Point at (0, L/2, 0) (midway) → B = −2μ0I/(πL) ẑ.

**Q18 (EC-GATE-16):** Particle of mass m, charge q enters region with B = B ẑ, v = vx x̂ + vz ẑ (all non-zero). Eventual trajectory?
(a) Helical motion in the ẑ direction (b) Circular motion in the xy plane (c) Linear motion in the ẑ direction (d) Linear motion in the x̂ direction
**Ans: (a)** — F = qvx x̂ × B ẑ = −qvxB ŷ → circular motion about ẑ; vz adds axial drift → helix.
**Concept:** Lorentz force F = qv×B.
**Twist:** vz = 0 → pure circle in xy plane → (b). v ∥ B only (vx = 0) → straight line in ẑ.

**Q19 (EE-GATE-16):** Soft-iron toroid (μr = 100) concentric with a long straight conductor carrying I. Ratio of B just inside to just outside the toroid? [Numerical]
(a) — (b) — (c) — (d) —
**Ans: 100** — B_in = μ0μrI/2πr, B_out = μ0I/2πr → ratio = μr = 100.
**Concept:** B = μ0μrH; H same on both sides at radius r.
**Twist:** Air (μr = 1) toroid → ratio 1. Compare H instead of B → H_in = H_out → ratio 1.

**Q20 (EE-GATE-17):** A solid iron cylinder is placed in a uniform B with axis parallel to the field. Field lines inside the cylinder will
(a) Bend closer to the cylinder axis (b) Bend farther away from the axis (c) Remain uniform as before (d) Cease to exist inside the cylinder
**Ans: (a)** — Iron offers low reluctance; flux concentrates toward the axis.
**Concept:** Magnetic boundary conditions / minimum-reluctance path.
**Twist:** Hollow (air) cylinder → lines bend away → (b). Sphere of iron → same flux-concentrating behaviour.

**Q21 (EE-GATE-21):** Which vector function represents a magnetic field B? (x̂, ŷ, ẑ unit vectors)
(a) 10x x̂ − 30z ŷ + 20y ẑ (b) 10z x̂ + 20y ŷ − 30z ẑ (c) 10y x̂ + 20x ŷ − 10z ẑ (d) 10x x̂ + 20y ŷ − 30z ẑ
**Ans: (d)** — ∇·B = 10 + 20 − 30 = 0 (solenoidal).
**Concept:** ∇·B = 0.
**Twist:** Others give non-zero divergence → not valid B. Valid B must also satisfy ∇×B = J (may be non-zero).

**Q22 (EE-GATE-22):** Long conducting cylinder radius b on the z-axis, J = Ja·r³ ẑ for r < b. Magnetic field intensity H inside (r < b)?
(a) (Ja/4)r⁴ (b) (Ja/3)r³ (c) (Ja/5)r⁴ (d) Ja·r³
**Ans: (c)** — ∮H·dl = ∫J·ds ⇒ H(2πr) = Ja·2π·r⁵/5 ⇒ H = Ja·r⁴/5.
**Concept:** Ampere's law with non-uniform current density.
**Twist:** Uniform J → H = Jr/2 (linear in r). J ∝ r → H = Ja·r²/3.

## TWO MARK QUESTIONS

**Q23 (EC-GATE-87):** Two long parallel wires, distance R apart, equal currents opposite in direction. At a general point P (distances d1, d2 from wires), the Z-component of
(a) magnetic vector potential = (μ0I/4π)ln(d2²/d1²) (b) magnetic induction = μ0I·d2/(4πd1) (c) magnetic induction is zero (d) magnetic vector potential = (μ0I/4π)·(d2²/d1²)
**Ans: (a)** — A = (μ0I/2π)[ln(2L/d1) − ln(2L/d2)] = (μ0I/4π)ln(d2²/d1²).
**Concept:** A = (μ0I/2π)ln r for a long wire; superposition of ±I wires.
**Twist:** Same-direction currents → A = (μ0I/4π)ln(d1·d2/4L²). B found from A by curl (B = ∇×A).

**Q24 (EC-GATE-93):** Long solenoid radius R, N turns/unit length, i(t) = I0 cos ωt. Magnitude of induced electric field at radius R/2 from the axis?
(a) (R/2)μ0NI0ω sin ωt (b) (R/4)μ0NI0ω cos ωt (c) (R/4)μ0NI0ω sin ωt (d) Rμ0NI0ω sin ωt
**Ans: (c)** — E·2πr = πr²·μ0N·d(i)/dt ⇒ E = (R/4)μ0NI0ω sin ωt at r = R/2.
**Concept:** Faraday in integral form ∮E·dl = −d(μ0H·ds)/dt.
**Twist:** At surface r = R → E = (R/2)μ0NI0ω sin ωt. For r > R (outside) → E ∝ 1/r (flux enclosed constant).

**Q25 (EE-GATE-07):** Inductor: 400 turns, iron core 16 cm² cross-section, air gap 1 mm, connected to 230 V, 50 Hz (neglect resistance, core loss, iron reluctance, leakage; μ0 = 4π×10⁻⁷). Current in the conductor?
(a) 18.08 A (b) 9.04 A (c) 4.56 A (d) 2.28 A
**Ans: (d)** — L = μ0N²A/l = 0.3217 H, XL = ωL = 101.1 Ω, I = 230/101.1 = 2.28 A.
**Concept:** Air-gap-dominated inductance L = μ0N²A/l; XL = ωL.
**Twist:** Applied DC → only winding R limits current. Double air gap → L halves → I doubles.

**Q26 (EE-GATE-07):** Average force on the core to reduce the air gap (same inductor as Q25)?
(a) 832.29 N (b) 1666.22 N (c) 3332.47 N (d) 6664.84 N
**Ans: (a)** — F = (½LI²)/d = 836 N ≈ 832.29 N (energy stored in air gap / gap length).
**Concept:** F = (1/2)B²A/μ0 = magnetic energy per unit gap.
**Twist:** Double current → force ×4. Double gap (same I) → force halves.

**Q27 (EE-GATE-08):** Coil of 300 turns on a non-magnetic core, mean circumference 300 mm, cross-section 300 mm². Inductance for a magnetizing current of 3 A (μ0 = 4π×10⁻⁷)?
(a) 37.68 μH (b) 113.04 μH (c) 3.768 μH (d) 1.1304 μH
**Ans: (b)** — L = μ0N²A/l = 4π×10⁻⁷·300²·300×10⁻⁶/300×10⁻³ = 113.04 μH.
**Concept:** L = μ0N²A/l.
**Twist:** Iron core μr = 1000 → L = 113 mH. Double turns → L ×4.

**Q28 (EE-GATE-08):** Which vector field does NOT satisfy the property of magnetic flux density?
(a) y²âx + z²ây + x²âz (b) z²âx + x²ây + y²âz (c) x²âx + y²ây + z²âz (d) y²z²âx + x²z²ây + x²y²âz
**Ans: (c)** — ∇·B = 2x + 2y + 2z ≠ 0.
**Concept:** ∇·B = 0 (magnetic flux density is solenoidal).
**Twist:** Option (a): ∇·B = 0 → valid B. Same test applied to an E-field in a charge-free region → ∇·E = 0.

**Q29 (EC-GATE-09):** In air, B = B0(x/(x²+y²) ŷ − y/(x²+y²) x̂). Which current distribution produces this field? [Hint: use cylindrical coordinates]
(a) J = (B0/μ0)ẑ/(x²+y²), r ≠ 0 (b) J = −(B0/μ0)ẑ/(x²+y²), r ≠ 0 (c) J = 0, r ≠ 0 (d) J = (B0/μ0)ẑ·2/(x²+y²)
**Ans: (c)** — In cylindrical coords B = (B0/ρ)âφ, and ∇×H = 0 for ρ ≠ 0 ⇒ J = 0.
**Concept:** Ampere in differential form J = ∇×H; curl of a 1/ρ azimuthal field is zero (ρ ≠ 0).
**Twist:** B = B0·ρ âφ → J = (2B0/μ0)ẑ (uniform current density). B = ρ/2 âφ → J = (1/μ0)ẑ.

**Q30 (EC-GATE-12):** Infinitely long uniform solid wire, radius a, uniform current density J. Magnetic field at distance r from the centre is proportional to
(a) r for r < a and 1/r² for r > a (b) 0 for r < a and 1/r for r > a (c) r for r < a and 1/r for r > a (d) 0 for r < a and 1/r² for r > a
**Ans: (c)** — H = Jr/2 inside (∝ r); H = Ja²/2r outside (∝ 1/r).
**Concept:** Ampere's law ∮H·dl = I_enc.
**Twist:** Surface (hollow) current → H = 0 inside, 1/r outside. J ∝ r → H ∝ r³ inside, 1/r outside.

**Q31 (EC-GATE-12):** A hole of radius b (b < a) is drilled along the solid wire of Q30 at distance d from its centre. Magnetic field inside the hole is
(a) uniform and depends only on d (b) uniform and depends only on b (c) uniform and depends on both b and d (d) non-uniform
**Ans: (a)** — Superpose a full cylinder (+J) and a negative cylinder (−J); inside hole H = Jd/2 — uniform, only d.
**Concept:** Superposition of two cylindrical current distributions.
**Twist:** Centred hole (d = 0) → B = 0 inside hole. Increase d → H in hole increases linearly.

**Q32 (EC-GATE-14):** Perfect-conducting half-space with surface current Ks = 2 x̂ A/m (n̂ = ŷ). Tangential H field in air just above the conductor?
(a) 2(x̂ + ẑ) A/m (b) 2 x̂ A/m (c) −2 ẑ A/m (d) 2 ẑ A/m
**Ans: (d)** — Boundary condition n̂×(H2 − H1) = Ks with H1 = 0 (perfect conductor) ⇒ H = 2 ẑ A/m.
**Concept:** Magnetic boundary condition n̂×(H2 − H1) = Ks; H = 0 inside perfect conductor.
**Twist:** Ks = 2 ŷ (n̂ = ẑ) → H = 2 x̂. Reverse current → H = −2 ẑ.

**Q33 (EE-GATE-14):** A wire on the x-axis carries 4 A in +x; another on the y-axis carries 2 A in +y. Magnetic field intensity H at (2, 1, 0) (μ0 free space; î, ĵ, k̂ unit vectors)?
(a) (3/2π) k̂ W/m² (b) (4/3π) î A/m (c) (3/2π) k̂ A/m (d) 0 A/m
**Ans: (c)** — H = (4/2π·1) k̂ − (2/2π·2) k̂ = (2/π − 1/2π) k̂ = (3/2π) k̂ A/m.
**Concept:** H = I/2πr with right-hand rule; superposition.
**Twist:** Point (1, 1, 0) → H = (4−2)/(2π) k̂ = (1/π) k̂. Reverse the y-wire current → H = (5/2π) k̂.

**Q34 (EE-GATE-17):** Regular hexagon loop of side 1 m, current I = 1 A, in vacuum. Magnitude of B (in μT) at the centre? [Numerical, 2 decimals]
(a) — (b) — (c) — (d) —
**Ans: 0.69 μT** — H per side = (I/4πρ)(cos 60° − cos 120°) with ρ = √3/2; total H = 6×0.0919 = 0.5513, B = μ0H = 0.6928 μT.
**Concept:** Finite straight wire formula H = (I/4πρ)(cos α2 − cos α1).
**Twist:** Circular loop radius 1 m → B = μ0I/2r = 0.628 μT. Equilateral triangle → 3 sides × same formula.

**Q35 (EC-GATE-19):** Identical parallel copper wires W1 (current I) and W2 (current 2I), opposite directions, separated 4r. Magnetic field B between the wires at distance r from W1?
(a) μ0I/6πr (b) 6μ0I/5πr (c) 5μ0I/6πr (d) μ0²I²/2πr²
**Ans: (c)** — B = μ0I/2πr + μ0·2I/(2π·3r) = μ0I/2πr(1 + 2/3) = 5μ0I/6πr.
**Concept:** Superposition of opposite currents (fields add between the wires).
**Twist:** Same-direction currents → fields subtract → μ0I/6πr. Point at 3r from W1 → B = μ0I/2πr − 2μ0I/2πr... (fields oppose).

**Q36 (EE-GATE-20):** Square loop of side 1 m placed 1 m from a long straight wire carrying I = 2 A. Mutual inductance (in nH, 2 decimals)? [Numerical]
(a) — (b) — (c) — (d) —
**Ans: 138.63 nH** — M = (1/I)∫B·ds = (μ0/4π)·∫ₓ₌₁² dx/x = μ0/4π·ln 2 → 138.63 nH.
**Concept:** Mutual inductance M = Nφ/I, with B = μ0I/2πx across loop face.
**Twist:** Loop moved to distance 2 m (x = 2→3) → M = (μ0/4π)ln(3/2) ≈ 40.5 nH. Loop ⊥ wire plane → flux zero → M = 0.

**Q37 (EE-GATE-21):** A 1 C point charge moving with uniform velocity 10 x̂ m/s enters region x ≥ 0 with B = (10y x̂ + 10x ŷ + 10 ẑ) T. Magnitude of force on the charge at x = 0⁺ (N)? [Numerical]
(a) — (b) — (c) — (d) —
**Ans: 100 N** — At x = 0⁺: v × B = 10 x̂ × (10y x̂ + 10 ẑ) = −100 ŷ, |F| = 100 N.
**Concept:** Lorentz force F = q(v × B) (electric part zero here).
**Twist:** Evaluate at x = 1 → B includes 10 ŷ term → v×B = 100(ẑ − ŷ)... |F| = 100√2 N. Double velocity → F doubles.

**Q38 (EE-GATE-21):** H = x² î + x²y² ĵ + x²y²z² k̂ A/m in a conducting region. Magnitude of current density (A/m²) at x = 1, y = 2, z = 1?
(a) 8 (b) 12 (c) 16 (d) 20
**Ans: (b)** — J = ∇×H = 2x²yz² î − 2xy²z² ĵ + 2xy² k̂; at (1,2,1) = 4î − 8ĵ + 8k̂, |J| = 12 A/m².
**Concept:** J = ∇×H (Ampere's law, differential form).
**Twist:** If H = x² î only → J = 0. If H = x²y ĵ only → J = −2xy k̂.

**Q39 (EE-GATE-23):** Infinite surface current density K = 5 âx A/m on the x–y plane. Magnitude of H (A/m) at point (1, 1, 1)? [Numerical, 2 decimals]
(a) — (b) — (c) — (d) —
**Ans: 2.5 A/m** — H = ½(K × n̂) = ½(5 x̂ × ẑ) = −2.5 ŷ, magnitude 2.5 A/m.
**Concept:** Field of a current sheet H = ½K × n̂.
**Twist:** K = 5 ŷ (n̂ = ẑ) → H = 2.5 x̂. Sheet on the y–z plane (n̂ = x̂), K = 5 ẑ → H = −2.5 ŷ.

## Unit 4: Time Varying Fields & Maxwell's Equations (18 Qs)

## ONE MARK QUESTIONS

**Q1 (EE-GATE-98):** The laws of electromagnetic induction (Faraday's and Lenz's law) are summarized in the following equation:
(a) e = iR (b) e = L·di/dt (c) e = −dψ/dt (d) none of these
**Ans: (c)** — e = −dψ/dt, the minus sign is Lenz's law (opposes the change producing it).
**Concept:** Faraday: emf = −dψ/dt = −N·dΦ/dt (Lenz's sign).
**Twist:** motional emf (conductor cutting flux) → e = Blv. Transformer emf (flux varies, coil fixed) → e = −N·dΦ/dt.

**Q2 (EC-GATE-98):** The Maxwell's equation ∇×H = J + ∂D/∂t is based on:
(a) Ampere's law (b) Gauss's law (c) Faraday's law (d) Coulomb's law
**Ans: (a)** — Ampere's law modified (generalised) for time-varying fields by adding displacement current ∂D/∂t.
**Concept:** Ampere-Maxwell: ∇×H = J + ∂D/∂t.
**Twist:** static form (∂D/∂t = 0) → ∇×H = J (Ampere's circuital law). Source-free region (J = 0) → ∇×H = ∂D/∂t.

**Q3 (EC-GATE-03):** The unit of ∇×H is:
(a) ampere (b) ampere/meter (c) ampere/meter² (d) ampere-meter
**Ans: (c)** — ∇×H = J (current density), so units are A/m².
**Concept:** curl of H equals current density J (A/m²); the added displacement current ∂D/∂t also has units A/m².
**Twist:** ∇×E = −∂B/∂t has units V/m². ∇·D = ρv has units C/m³.

**Q4 (EC-GATE-07):** If C is a closed curve enclosing a surface S, then the magnetic field intensity H, current density J and electric flux density D are related by:
(a) ∫∫S H·ds = ∮C (J + ∂D/∂t)·dl (b) ∮C H·dl = ∫∫S (J + ∂D/∂t)·dS (c) ∮C H·ds = ∫∫S (J + ∂D/∂t)·dl (d) ∮C H·dl = ∫∫S (J + ∂D/∂t)·dS
**Ans: (d)** — integral form of the Ampere-Maxwell law obtained from ∇×H = J + ∂D/∂t by Stokes' theorem.
**Concept:** ∮H·dl = ∫∫(J + ∂D/∂t)·dS.
**Twist:** static case → ∮H·dl = I_enc. Faraday's integral form ∮E·dl = −(d/dt)∫B·ds.

**Q5 (EC-GATE-08):** For static electric and magnetic fields in a homogeneous source-free medium, which represents the correct form of two Maxwell's equations?
(a) ∇·E = 0, ∇×B = 0 (b) ∇·E = 0, ∇·B = 0 (c) ∇×E = 0, ∇×B = 0 (d) ∇×E = 0, ∇·B = 0
**Ans: (d)** — source-free static: no curl of E (electrostatic, conservative) and zero divergence of B (no magnetic monopoles).
**Concept:** Maxwell source-free static: ∇×E = 0 and ∇·B = 0.
**Twist:** time-varying source-free → ∇×E = −∂B/∂t ≠ 0 (non-conservative).

**Q6 (EC-GATE-16):** Faraday's law of electromagnetic induction is mathematically described by which one of the following equations?
(a) ∇·B = 0 (b) ∇·D = ρv (c) ∇×E = −∂B/∂t (d) ∇×H = σE + ∂D/∂t
**Ans: (c)** — differential form of Faraday's law.
**Concept:** Faraday: ∇×E = −∂B/∂t (also = −μ·∂H/∂t).
**Twist:** integral form ∮E·dl = −dΦ/dt. Conductive medium form ∇×H = σE + ∂D/∂t.

**Q7 (EC-GATE-19):** Match List I (LHS) with List II (RHS) of Maxwell's equations. List I: 1. ∇·D, 2. ∇×E, 3. ∇·B, 4. ∇×H. List II: P. 0, Q. ρ, R. −∂B/∂t, S. J + ∂D/∂t:
(a) 1-P, 2-R, 3-Q, 4-S (b) 1-Q, 2-R, 3-P, 4-S (c) 1-Q, 2-S, 3-P, 4-R (d) 1-R, 2-Q, 3-S, 4-P
**Ans: (b)** — ∇·D = ρ; ∇×E = −∂B/∂t; ∇·B = 0; ∇×H = J + ∂D/∂t.
**Concept:** Maxwell's equations in differential form.
**Twist:** ∇·J = −∂ρv/∂t (continuity) as a 5th relation; integral forms equivalent via divergence/Stokes theorems.

## TWO MARK QUESTIONS

**Q1 (EC-GATE-87):** An electrostatic field is said to be conservative when:
(a) the divergence of the field is zero (b) the curl of the field is zero (c) the curl of the field equals −∂B/∂t (d) the Laplacian of the field equals με·∂²E/∂t²
**Ans: (b)** — conservative field ⇒ closed line integral ∮E·dl = 0 ⇒ ∇×E = 0.
**Concept:** conservative/electrostatic field ∇×E = 0 (path-independent work).
**Twist:** time-varying field → ∇×E = −∂B/∂t ≠ 0 (non-conservative).

**Q2 (EC-GATE-90):** Which of the following field equations indicates that free magnetic charges do not exist:
(a) H = (1/μ)∇×A (b) H = ∮(Idl×R)/4πR² (c) ∇·H = 0 (d) ∇×H = J
**Ans: (c)** — Gauss's law for magnetic fields: ∇·B = 0 (or ∇·H = 0 in homogeneous medium), flux lines always closed.
**Concept:** ∇·B = 0 — no free magnetic monopoles.
**Twist:** electric analogue ∇·D = ρv ≠ 0 — charges do exist. B = ∇×A ensures ∇·B = 0.

**Q3 (EC-GATE-93):** Match (A) ∇×H = J, (B) ∮C E·dl = −(d/dt)∫S B·ds, (C) ∇·J = −∂ρv/∂t with (1) Continuity equation, (2) Faraday's law, (3) Ampere's law, (4) Gauss's law, (5) Biot-Savart law:
(a) 1-A, 2-B, 3-C (b) A-3, B-2, C-1 (c) A-2, B-3, C-1 (d) A-3, B-1, C-2
**Ans: (b)** — ∇×H = J is Ampere's law; ∮E·dl = −(d/dt)∫B·ds is Faraday's law (emf = −dφ/dt); ∇·J = −∂ρv/∂t is point form of continuity equation.
**Concept:** identifying Maxwell/electromagnetic laws from their equations.
**Twist:** ∇×E = −∂B/∂t ↔ Faraday integral form ↔ emf = −dφ/dt; ∇·D = ρv ↔ Gauss's law.

**Q4 (EC-GATE-03):** If the electric field intensity is E = x·ux + y·uy + z·uz V/m, the potential difference between X(2,0,0) and Y(1,2,3) is:
(a) +1 V (b) −1 V (c) +5 V (d) +6 V
**Ans: (c)** — VXY = −∫E·dl = −½[(4−1) + (0−4) + (0−9)] = −½(−10) = +5 V.
**Concept:** V = −∫E·dl; electrostatic field is conservative so path-independent.
**Twist:** different end points X(0,0,0) & Y(1,1,1) → different value; E = −∇V so V can be recovered by integration.

**Q5 (EC-GATE-03):** Medium 1 (ε1 = 1.5εo) is left of x=0; Medium 2 (ε2 = 2.5εo) is right of x=0. If E1 = (2ux − 3uy + 1uz) V/m in medium 1, then E2 in medium 2 is:
(a) (2.0ux − 7.5uy + 2.5uz) V/m (b) (2.0ux − 7.5uy + 2.5uz) V/m (c) (1.2ux − 3.0uy + 1.0uz) V/m (d) (1.2ux − 2.0uy + 0.6uz) V/m
**Ans: (c)** — tangential E continuous (Ey, Ez unchanged); normal D continuous: Ex2 = (ε1/ε2)·Ex1 = (1.5/2.5)·2 = 1.2.
**Concept:** boundary conditions at a dielectric interface — Et continuous, Dn continuous.
**Twist:** with free surface charge at interface → Dn1 − Dn2 = ρs (normal component jumps). If ε1 = ε2, field continues unchanged.

**Q6 (EE-GATE-06):** With reference to ∇·J = −∂ρv/∂t: 1. point form of continuity equation; 2. divergence of current density equals decrease of charge per unit volume per unit time; 3. Maxwell's divergence equation; 4. represents conservation of charge. Select the correct answer:
(a) only 2 and 4 are true (b) 1, 2 and 3 are true (c) 2, 3 and 4 are true (d) 1, 2 and 4 are true
**Ans: (d)** — it is the continuity equation (conservation of charge), not one of Maxwell's divergence equations.
**Concept:** Continuity equation: ∇·J = −∂ρv/∂t.
**Twist:** integral form ∮J·ds = −dQ/dt (charge leaving a volume). Combined with ∇×H = J + ∂D/∂t gives ∇·(J + ∂D/∂t) = 0.

**Q7 (EC-GATE-06):** A medium is divided into Region I (εr1 = 3) and Region II (εr2 = 4) about the x = 0 plane. An EM wave with E1 = 4ax + 3ay + 5az is incident normally on the interface from Region I. The electric field E2 in Region II at the interface is (figure: two half-spaces x<0/x>0 at x=0 plane):
(a) E2 = E1 (b) 4ax + 0.75ay − 1.25az (c) 3ax + 3ay + 5az (d) −3ax + 3ay + 5az
**Ans: (c)** — tangential E continuous (Ey = 3, Ez = 5); normal D continuous: Ex2 = (ε1/ε2)·Ex1 = (3/4)·4 = 3.
**Concept:** boundary conditions: Et continuous, Dn continuous (ε1Ex1 = ε2Ex2).
**Twist:** normal component scales by ε ratio, tangential components unchanged; reverse direction (ε1=4, ε2=3) → Ex2 = (4/3)·4 = 5.33.

**Q8 (EC-GATE-11):** A current sheet J = 10uy A/m lies on the dielectric interface x = 0 between medium 1 (εr1 = 5, μr1 = 1, x < 0) and medium 2 (εr2 = 2, μr2 = 2, x > 0). If H1 = 3ux + 30uy A/m at x = 0−, the magnetic field H2 at x = 0+ is (figure: interface at x=0, current sheet J into page along y, regions marked):
(a) 1.5ux + 30uy − 10uz A/m (b) 3ux + 30uy − 10uz A/m (c) 3ux + 40uy A/m (d) 3ux + 30uy + 10uz A/m
**Ans: (a)** — normal B continuous: Hx2 = (μ1/μ2)Hx1 = (1/2)·3 = 1.5; tangential Hy continuous = 30; current sheet sets Hz2 = −10 (K = 10 A/m produces 10 A/m in −z at x = 0+).
**Concept:** boundary conditions with surface current — Bn continuous (μ1Hx1 = μ2Hx2), n̂×(H2−H1) = K.
**Twist:** if μ1 = μ2, Hx continuous (Hx2 = 3). Reversed sheet polarity K = −10uy → Hz2 = +10 (option d).

**Q9 (EE-GATE-16-S2):** A rotating conductor of 1 m length is placed in a radially outward (about z-axis) magnetic flux density B = 1 Tesla, parallel to and at 1 m distance from the z-axis (figure: rotating rod along radial B at radius 1 m). The speed in r.p.m. required to induce 1 V across it is ___.
**Ans: (9.4 to 9.7)** — Vemf = Blv → v = 1/(1·1) = 1 m/s; v = ωr → ω = 1/1 = 1 rad/s; N = 60ω/2π = 9.549 rpm.
**Concept:** motional emf e = Blv = B·l·ω·r (generator action).
**Twist:** v = rω so emf ∝ ω; larger B or l → smaller rpm for same emf. If conductor is at radius 2 m → ω = 0.5 rad/s → 4.77 rpm.

**Q10 (EE-GATE-16-S2):** The flux linkage λ and current i relation for an electromagnetic system is λ = i/g² (air-gap dependent). When i = 2 A and air gap length g = 10 cm, the magnitude of the mechanical force on the moving part, in N, is ___.
**Ans: (186 to 190 N)** — coenergy Wfld = ∫i dλ = λ³g²/3; fe = −∂Wfld/∂g = −(2/3)λ³g; with λ = √i/g → fe ≈ −188.5 N; magnitude ≈ 188.5 N.
**Concept:** energy method F = −∂Wfld/∂x (field energy of an electromagnetic actuator).
**Twist:** F ∝ i²/g³ → force ↑ sharply as gap ↓ (attractive, pulls armature to reduce gap); double i → force ×4.

**Q11 (EE-GATE-23) [MSQ]:** In the figure, E points along +x and B points along +z (both constant). A positive charge q is released from rest at the origin. Which statement(s) is/are true (figure: crossed E(x) and B(z) fields, charge at origin):
(a) The charge will move in the direction of z with constant velocity (b) The charge will always move on the y-z plane only (c) The trajectory of the charge will be a circle (d) The charge will progress in the direction of y
**Ans: (—)** — book marks as "Incorrect data".
**Concept:** Lorentz force F = q(E + v×B); charge in crossed E and B fields follows a cycloid and drifts in the E×B direction.
**Twist:** with only B present → circular motion (v⊥B); with E∥B → uniform acceleration along B plus circular motion (helix).

---

# 📋 FORMULA SUMMARY — Exam-Day Sheet (EMF)

## 1. Vector Calculus
- ∇f gradient (scalar→vector) · ∇·A divergence (→scalar) · ∇×A curl (→vector)
- Scalar projection = A·B/|B| · **Divergence thm: ∮A·dS = ∫∇·A dV · Stokes: ∮A·dl = ∫(∇×A)·dS**

## 2. Electrostatics
- Coulomb: F = q1q2/(4πεr²) · **E = Q/(4πεr²)** · Gauss: ∮D·dS = Q_enc · D = ε0εrE
- Potential: V = Q/(4πεr), E = −∇V · **C(parallel plate) = εA/d** · W = ½CV²
- Boundary: **Dn1 = Dn2, Et1 = Et2**

## 3. Magnetostatics
- **Biot-Savart long wire: B = μ0I/(2πr)** · Ampere: ∮B·dl = μ0I_enc · μ0 = 4π×10⁻⁷
- B = μ0μrH · F = IL×B · F = qv×B · L = NΦ/I · solenoid: B = μ0NI/l
- Boundary: **Bn1 = Bn2, Ht1 = Ht2**

## 4. Time Varying Fields & Maxwell
- **Faraday: emf = −dΦ/dt (∇×E = −∂B/∂t)** · Displacement current Jd = ∂D/∂t
- Maxwell: ∇×H = J + ∂D/∂t · ∇·D = ρ · ∇·B = 0
- **Poynting: S = E×H (W/m²)** · wave v = 1/√(με) · η = √(μ/ε) (free space ≈ 377 Ω)
- **Skin depth δ = 1/√(πfμσ)**
