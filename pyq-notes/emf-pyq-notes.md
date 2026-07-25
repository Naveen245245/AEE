# EMF / Electromagnetics — PYQ Notes from Ohm Institute PDF

**Source:** [Study Material GTD PYQs] 2026 05 26 6 EMF PDF.pdf  
**Total Questions Analyzed:** ~470 across 4 units  
**Topics:** Vector Calculus, Electrostatics, Magnetostatics, Maxwell's Equations

---

## 📊 Formula/Concept vs. Question Count Analysis

| S.No | Formula / Concept | No. of Qs | Key Formula |
| :---: | :--- | :---: | :--- |
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

# 📝 EMBEDDED PYQs — Ohm Institute PDF

> Source: [Study Material GTD PYQs] 2026 05 26 6 EMF PDF.pdf  
> ~470 PYQs across 4 units. Selected representative Qs below.

---

## Topic 1: Vector Calculus & Coordinate Geometry

**Q1 (EE-GATE-94):** Stokes theorem states: `∮_C A·dl = ∫_S (∇×A)·dS`

**Q2 (EE-GATE-02):** Divergence theorem states: `∮_S F·dS = ∫_V (∇·F)·dv`

**Q3 (TSSPDCL-2022):** The scalar projection of vector (6î+2ĵ-3k̂) along (3î-4ĵ):
**Solution:** Scalar projection = (A·B)/|B| = (18-8+0)/5 = 10/5 = **2. Answer: (a)**

**Q4 (TSNPDCL-2022):** Spherical coordinates of P(1, √3, 2√3):
**Solution:** r = √(1+3+12) = √16 = 4. θ = cos⁻¹(z/r) = cos⁻¹(2√3/4) = cos⁻¹(0.866) = 30°. φ = tan⁻¹(y/x) = tan⁻¹(√3/1) = 60°.  
**Answer: (b) P(4, 60°, 30°)** — Wait, that's (r, φ, θ) format. Given options: (b) P(4, 60°, 30°) ✓

---

## Topic 2: Electrostatics

**Q1 (EE-GATE-96):** If v,w,q are voltage, energy, charge, then v = ?
(a) dq/dw &emsp; (b) dw/dq &emsp; (c) dv = dq/dw &emsp; (d) dv = dw/dq  
**Answer: (b) v = dw/dq** — By definition, voltage = energy per unit charge

**Q2 (EC-GATE-95):** Point charge +q at origin. E at P = 100 μV/m. Now charge enclosed in conducting sphere. New E at P?
(a) 0 &emsp; (b) 100 &emsp; (c) -100 &emsp; (d) 50  
**Solution:** Conducting sphere shields internal charge. Field outside = 0.  
**Answer: (a) 0**

**Q3 (EC-GATE-95):** Surface charge density = 1/6000π μC/m². Electric field strength?
(a) 30î V/m &emsp; (b) 3ĵ V/m &emsp; (c) 60ĵ V/m &emsp; (d) 30ĵ V/m  
**Solution:** E = ρₛ/(2ε₀) for infinite sheet = (10⁻⁶/(6000π))/(2×8.85×10⁻¹²) ≈ 30 V/m. Direction depends on sheet orientation.  
**Answer: (a) 30î V/m** (assuming sheet in yz-plane)

**Q4 (EC-GATE-96):** Metal sphere r=1m, ρₛ=10C/m² enclosed in 10m cube. ∮ D·dS over cube?
**Solution:** Gauss law: ∮ D·dS = Qenc = ρₛ × 4πr² = 10 × 4π = **40π C. Answer: (a)**

**Q5 (TSNPDCL-2022):** Electric field 1000V/m in εr=7 medium, hits air at 45° to normal. E in air?
**Solution:** Tangential E continuous: E₁sin45° = E₂sinθ₂. Normal D continuous: ε₁E₁cos45° = ε₀E₂cosθ₂.  
E₂(tan) = 1000×0.707 = 707 V/m. D₂(normal) = 7ε₀×1000×0.707 = 4950ε₀. E₂(normal) = 4950 V/m.  
E₂ = √(707²+4950²) = **5000 V/m. Answer: (a)**

**Capacitance of parallel plate:** C = ε₀εrA/d. For 100cm² area, 1mm gap, εr=2:  
C = 8.85×10⁻¹²×2×0.01/0.001 = **177 pF**

---

## Topic 3: Magnetostatics

**Q1 (EE-GATE-93):** Line integral of vector potential A around boundary of S represents:
(a) Flux through S &emsp; (b) Flux density &emsp; (c) Magnetic density &emsp; (d) Current density  
**Answer: (a)** — ∮ A·dl = ∫ B·dS = Φ (by Stokes theorem)

**Q3 (EE-GATE-99):** Two parallel wires, same direction current I, distance d apart. B-field midway?
**Solution:** B₁ into page = μ₀I/(2π(d/2)) = μ₀I/πd. B₂ out of page = same magnitude.  
Net B = **0. Answer: (b)**

**Q5 (EE-GATE-00):** Electron with velocity u in E and B fields. Force = ?
**Answer: (d) -e(E + u×B)** — Lorentz force, negative charge

**Q12 (TSPSC-AEE-23):** Coaxial cable inner=0.8mm, outer=4mm, μr=50. Self-inductance/m?
**Solution:** L = μ₀μr/(2π)×ln(r₂/r₁) = 4π×10⁻⁷×50/(2π)×ln(4/0.8)  
= 10⁻⁵×ln(5) = 10⁻⁵×1.609 = **16.1 μH/m. Answer: (b)**

**Force between parallel conductors:** F/l = μ₀I₁I₂/(2πd). I₁=I₂=100A, d=1m.  
F/l = 4π×10⁻⁷×10000/(2π×1) = **0.002 N/m** (attractive if same direction)

---

## Topic 4: Time Varying Fields & Maxwell's Equations

**Q1 (EE-GATE-98):** Faraday's and Lenz's law summarized as:
(a) e = iR &emsp; (b) e = L di/dt &emsp; (c) e = -dψ/dt &emsp; (d) None  
**Answer: (c) e = -dψ/dt** — Negative sign = Lenz's law

**Q2 (EC-GATE-98):** Maxwell's equation ∇×H = J + ∂D/∂t is based on:
(a) Ampere's law &emsp; (b) Gauss's law &emsp; (c) Faraday's law &emsp; (d) Coulomb's law  
**Answer: (a)** — Modified Ampere's law with displacement current

**Q3 (EC-GATE-07):** For a closed curve C enclosing surface S, the relation is:
**Answer:** `∮_C H·dl = ∫_S (J + ∂D/∂t)·dS` — Ampere's circuit law in integral form

**Q4 (EE-GATE-99):** An EM field is radiated from:
(a) Stationary point charge &emsp; (b) Capacitor with DC  
(c) Conductor with DC &emsp; (d) Oscillating dipole  
**Answer: (d)** — Only time-varying sources radiate EM waves

**Displacement current:** Jd = ∂D/∂t. In capacitor with AC, Jd exists between plates, enabling continuous current.

**EM wave in free space:** ∇²E = μ₀ε₀∂²E/∂t². Solution: E = E₀sin(ωt-βz).  
Velocity c = 1/√(μ₀ε₀) = 3×10⁸ m/s. Intrinsic impedance η₀ = √(μ₀/ε₀) = 377Ω.

**Poynting theorem:** P = E×H W/m². Average power (for plane wave): Pav = E₀²/(2η₀)

---

## 🎯 Top Concepts Score >90%

| Rank | Concept | Weightage | Key Formulas |
| :---: | :--- | :---: | :--- |
| 1 | **Vector Calculus Theorems** | ~10% | Divergence theorem, Stokes theorem |
| 2 | **Gauss Law Applications** | ~12% | ∮D·dS=Qenc, spheres, cubes |
| 3 | **Coulomb & Electric Field** | ~10% | E = Q/(4πε₀r²), force calculations |
| 4 | **Capacitance** | ~8% | C = εA/d, energy = ½CV² |
| 5 | **Lorentz Force** | ~8% | F = q(E+v×B), motion in fields |
| 6 | **Ampere's Law** | ~10% | ∮H·dl=Ienc, coaxial cable |
| 7 | **Faraday's Law** | ~8% | e = -dΦ/dt, motional EMF |
| 8 | **Maxwell's Equations** | ~12% | Four equations, physical meaning |
| 9 | **EM Wave Propagation** | ~6% | Wave equation, velocity, Poynting |
| 10 | **Coordinate Systems** | ~5% | Cartesian, Cylindrical, Spherical |

---

> **Last Updated:** July 25, 2026 — Embedded PYQs from Ohm PDF
> **Use alongside:** AP_AEE_STUDY_NOTES.md Section S11 for concept review
