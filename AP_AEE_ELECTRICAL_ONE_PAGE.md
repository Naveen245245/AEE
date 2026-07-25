---
title: AP AEE Electrical - Core Formulas One-Page Sheet
description: All essential electrical engineering formulas for AP AEE exam preparation
exam: AP AEE Electrical
marks: 70 marks
lastUpdated: 2026-07-22
---

# AP AEE Electrical — Core Formulas One-Page Sheet
> 5-Column Framework: Derivation → Real Life → Exam Form → Examiner Tweaks → Practice

---

## 1. TRANSFORMER

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **EMF Equation** | Faraday e=N·dΦ/dt; integrate sine flux Φ=Φmsin(ωt) → E_rms=4.44fNΦm | Pole TX near your house — 11kV/415V, 50Hz determines core size | E=4.44·f·N·Φm =4.44·f·N·Bm·A | 60Hz TX on 50Hz → Φ↑20%, saturation; N halves → Φ doubles | Given V,f,N find Φm or Bm |
| **Turns Ratio** | Same flux through both windings → E∝N; Pᵢₙ=Pₒᵤₜ → V·I constant | Step-down: 11kV/415V → current ×26.5 on secondary side | K=N₂/N₁=V₂/V₁=I₁/I₂; a=N₁/N₂ (inverse) | K>1 step-up, K<1 step-down; don't confuse a and K | Find I₁ given I₂ and V ratio |
| **OC Test** | Apply rated V on LV side (secondary open); Pₒ measures iron loss (hysteresis+eddy) | Every TX manufacturer certifies core quality via OC test | Pᵢ=Pₒ; R₀=V₁²/P₀; X₀=√[(V₁/I₀)²−R₀²] | Always on LV side (safe low V); shunt branch, constant with load | From OC data find R₀,X₀ |
| **SC Test** | Short secondary, apply reduced V on HV side till rated I flows; Pₛc = Cu loss | Certifies winding resistance and % impedance voltage | Pcu=Pₛc; R₀₁=Pₛc/Iₛc²; Z₀₁=Vₛc/Iₛc; X₀₁=√(Z₀₁²−R₀₁²) | HV side (lower rated current); series branch, ∝ I² | From SC data find R₀₁,X₀₁,Z₀₁ |
| **Efficiency** | η=Output/(Output+Losses); losses=const Pᵢ + variable x²Pcu | Dist TX max η at ~75% load (day peak vs night light load) | η=(x·S·cosφ)/(x·S·cosφ+Pᵢ+x²Pcu); max η at x=√(Pᵢ/Pcu) | x²Pcu=Pᵢ at max η (not xPcu); half-load η often lower | Find η at 50%,100% load; x for max η |
| **Voltage Reg.** | Internal R+jX causes I(Rcosφ±jXsinφ) drop under load | Lights dim when motor starts — that's regulation in action | %Reg=(Vₙₗ−V𝒻ₗ)/V𝒻ₗ×100; lagging +IX sinφ; leading −IX sinφ | Leading pf → negative regulation; unity pf → IR only | %Reg at 0.8 lag vs lead vs unity |
| **Auto-TX** | Single continuous winding; power transferred by conduction + induction jointly | 400/220kV grid auto-TX saves 45% material; NO isolation | Savings=(1−1/a)×100%; kVAₐᵤₜₒ=kVAₜ×(a/(a−1)) | No isolation ⇒ unsafe for distribution; savings max when a≈1 | Savings for 2:1 ratio |
| **Parallel** | Two TXs share load; must match V, seq, polarity, Z% for equal sharing | Synchroscope must read zero before closing paralleling breaker | 5 conditions: same polarity, sequence, V (±5%), Z% (±10%), vector group | Polarity fail: ΔV=2Vₚₕ→20-25×I_rated; seq fail: ΔV=√3Vₚₕ→14-18× | Find I_circ given mismatch type |
| **3-φ TX** | 3 single-phase on common core; each limb one phase; Y/Δ per side | Dyn11: Δ traps triplen harmonics; Y gives neutral for 240V loads | Dy11: LV leads HV 30°; V-V open Δ=57.7% of Δ-Δ capacity | Line V ratio ≠ turns ratio for Yd (√3 factor); vector group must match | Find LV line V given connection and ratio |

---

## 2. DC MACHINES

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **EMF Equation** | Each conductor cuts Φ once per rev; rate = P·Φ·N/60; Z conductors / A parallel paths = E | Hydro generator (Srisailam): speed determines output voltage | E=(P·Φ·N·Z)/(60·A); Lap: A=P; Wave: A=2 | Lap vs wave confusion; multiplex lap: A=mP | Given P,Φ,N,Z,A find E |
| **Torque** | Power=Torque×ω; Eₐ·Iₐ = T·ω; ω=2πN/60 → T=Φ·Z·Iₐ·P/(2π·A) | Series motor (high starting T ∝ I²) — used in traction, cranes, hoists | T=(P·Φ·Z·Iₐ)/(2π·A) N-m; Tₐ=0.159·Φ·Z·(P/A)·Iₐ | Shunt T∝Iₐ; Series T∝Iₐ²; shaft T = armature T − friction loss | Find T given P,Φ,Z,Iₐ,A |
| **Speed** | N=(V−IₐRₐ)/(kΦ); k=PZ/(60A); back EMF Eₐ=V−IₐRₐ | Shunt motor: near-constant speed (3-5% drop on load); Series: speed ∝ 1/Iₐ | N=(V−IₐRₐ)/(kΦ); field weakening → N↑; shunt N ∝ V/Φ | Series motor NO-LOAD → ω→∞ (destructive); must always be coupled to load | Find N given V,Rₐ,Iₐ,Φ |
| **Starters** | At standstill Eₐ=0 → Iₐ=V/Rₐ (10-20× rated); external R limits current | 3-point: NVR coil (no-volt release) + OLR; 4-point for series motors | Iₛₜₐᵣₜ=V/Rₐ; with Rₛ: Iₐ=V/(Rₐ+Rₛ); graded steps for smooth start | 4-point has separate NVR circuit; 3-point: NVR coil in series with shunt field | Design Rₛ for given I₁,I₂ limits |
| **Commutation** | Brushes short-circuit coils under commutation; interpoles neutralize armature flux | Interpoles: same polarity as next main pole ahead (generator) | Interpole winding in series with armature; compensating winding in pole faces | Interpoles reduce reactance voltage; compensating winding for heavy loads | Why interpoles? What polarity? |

---

## 3. INDUCTION MOTOR

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **Sync Speed** | Rotating magnetic field from 3-φ currents 120° apart; 1 rev per P/2 cycles | 50Hz: 2-pole→3000, 4-pole→1500, 6-pole→1000 rpm (standard speeds) | Nₛ=120f/P rpm; ωₛ=2πNₛ/60 rad/s | Same for sync & induction; given N find P (must be even) | Nₛ for 4-pole at 50Hz |
| **Slip** | Rotor lags behind rotating field; s=(Nₛ−N)/Nₛ | Normal: s=2-5% (N≈1440 for 4-pole); s=1 at start; s=0 at sync | s=(Nₛ−N)/Nₛ; fᵣ=s·f; N=Nₛ(1−s) | sR₂ vs R₂/s opposite: E₂ₛ=sE₂ but R₂'=R₂/s | Find N given Nₛ and s |
| **Torque Eq.** | F=BIL on rotor conductors; I₂=sE₂/Z₂; T= (3/ωₛ)·[V²·(R₂/s)]/[(R₂/s)²+X₂²] | T ∝ V²: 10% voltage dip → 19% torque loss; critical for starting | T=(3V²/ωₛ)·sR₂/[R₂²+(sX₂)²]; Tₘₐₓ=3V²/(2ωₛX₂) at s=R₂/X₂ | Tₘₐₓ independent of R₂; sₘₐₓ ∝ R₂; adding rotor R boosts Tₛₜ until R₂=X₂ | Find Tₘₐₓ, sₘₐₓ given parameters |
| **Starting** | DOL: 6-8× I_rated; Star-Delta: V per winding = 1/√3×V_L → I=1/3, T=1/3 | DOL ≤5HP; S-D for cage motors; rotor resistance for wound-rotor | S-D: Iₛₜ=33%, Tₛₜ=33% of DOL; Auto-TX (80% tap): Iₛₜ=0.64, Tₛₜ=0.64 | S-D reduces BOTH I and T by 1/3 (not usable for high-inertia loads) | Compare Iₛₜ,Tₛₜ: DOL vs S-D vs Auto-TX |
| **Power Flow** | Pₐᵢᵣ=P𝒾ₙ−stator losses; rotor Cu=s·Pₐᵢᵣ; mech=(1−s)·Pₐᵢᵣ | Rotor Cu = s×airgap — major heat at high slip; slip-ring motors dissipate via external R | Pᵣₒₜₒᵣ:Pₐᵢᵣ:Pₘₑ𝒸ₕ = s:1:(1−s); T=Pₐᵢᵣ/ωₛ | Pᵣₒₜₒᵣ = sPₐᵢᵣ (lost as heat); Pₘₑ𝒸ₕ = (1−s)Pₐᵢᵣ | Given P𝒾ₙ,s, find Pₒᵤₜ, η |

---

## 4. SYNCHRONOUS MACHINE

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **EMF Equation** | Same Faraday as TX + winding factors k_w (distribution) and k_p (pitch) | Turbo-alternators (Vijayawada thermal): 21kV, 3000rpm, 2-pole | E=4.44·f·N·Φ·k_w·k_p; k_w≈0.955; kₚ=cos(α/2) | Don't forget winding factors; salient pole: X_d≠X_q | Find E given f,N,Φ,k_w |
| **Frequency** | f = (P·N)/120; mechanical N rpm x P/2 pole pairs = electrical Hz | Hydro: N=150, P=40→50Hz; Thermal: N=3000, P=2→50Hz | f=P·N/120; N=120f/P; given f and N → find even P | P must be even integer; N in RPM not rad/s | f=50Hz, N=250 → P=? |
| **Power Angle** | P=(EV/Xₛ)·sinδ; δ = angle between induced EMF E and terminal V | Max power at δ=90°; beyond → pole slipping, generator trips off-grid | P=(EV/Xₛ)sinδ; salient: + (V²/2)(1/X_q−1/X_d)sin2δ | δ>90° → unstable; salient pole has extra reluctance torque term | Find P at given δ; max power |
| **V-Curves** | Vary field I_f → armature I_a traces V-shape at constant load | Over-excited sync motor runs as capacitor — used for pf correction (synchronous condenser) | Over-excited: leading pf; under-excited: lagging pf; min I_a at unity pf | Leading/lagging pf for given excitation; motor vs gen V-curve opposite direction | Given I_f change → new pf |
| **Voltage Reg.** | E (no-load) vs V (load); E from OCC, drop = I·Xₛ in phasor diagram | EMF method uses unsaturated Xₛ (from OCC + SCC); gives pessimistic reg | %VR=(E−V)/V×100; E=√[(Vcosφ+IRₐ)²+(Vsinφ±IXₛ)²] | Sign: lagging +IXₛ, leading −IXₛ; SCR = 1/Xₛ(pu); saturated vs unsaturated | Find %VR given pf, V, I, Xₛ |

---

## 5. TRANSMISSION LINES

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **Per Unit** | Normalize impedance: Z_pu = Z_actual / Z_base; Z_base = V_base²/S_base | Compare TX impedance across voltage levels: 10% is 10% anywhere | Z_pu=Z_actual·S_base/V_base²; base change: Z_pu_new = Z_pu_old·(MVA_new/MVA_old)·(kV_old/kV_new)² | Base change formula — most common PYQ; match MVA and kV correctly | Base change: given Z_pu_old find Z_pu_new |
| **Short Line** | (<80km): Neglect shunt C; V_S=V_R+I(R+jX) | Low-voltage distribution lines; simple IR+IX drop | V_S=V_R+I(R+jX); %Reg=(V_S−V_R)/V_R×100; A=D=1, B=Z, C=0 | Only R+X, no C; valid only for very short lines | Given V_R,I,Z find V_S |
| **Medium Line** | (80-250km): Lumped shunt C at ends (π) or middle (T) | Sub-transmission (66kV, 132kV); used for regional power transfer | π-model: A=D=1+YZ/2, B=Z, C=Y(1+YZ/4); T-model: A=D=1+YZ/2, B=Z(1+YZ/4), C=Y | Don't confuse π vs T formulas; AD−BC=1 always | Find A,B,C,D for given Z,Y |
| **Long Line** | (>250km): Distributed parameters; hyperbolic solutions cosh(γl), sinh(γl) | 400kV EHV lines (APTransco); surge impedance ~280Ω, SIL ~570MW | A=D=cosh(γl), B=Z₀sinh(γl), C=sinh(γl)/Z₀; γ=√(zy); Z₀=√(z/y) | Ferranti effect: V_R>V_S at no-load (shunt C charging); shunt reactors needed | Find SIL given V and Z₀ |
| **Line Parameters** | L=2×10⁻⁷·ln(D/r') H/m; C=2πε₀/ln(D/r) F/m; R=ρ/A | Bundle conductors reduce corona at EHV; skin effect ↑R_ac at 50Hz | Z₀=√(L/C); SIL=V²/Z₀; R_ac > R_dc; skin depth δ=√(2ρωμ) | Skin effect: only in AC, not DC; GMD method for unsymmetrical spacing | Find L and C given conductor geometry |
| **Corona/Insulators** | Ionization of air around conductor at high E-field; audible + visual + radio interference | Corona: more in humid weather, rain; string efficiency worse with more discs | P_corona ∝ f·V², reduced by bundling; η_string=V/(n·V_n) | String efficiency ← disc nearest conductor has max voltage drop | Find string eff. given voltage distribution |

---

## 6. FAULT ANALYSIS

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **Sym Components** | Unbalanced 3-φ → 3 balanced sets: +ve (120° fwd), −ve (120° rev), 0-seq (in phase) | Every digital fault recorder identifies fault type from sym components | a=1∠120°; a+a²+1=0; I₀=(Iₐ+I_b+I_c)/3; I₁=(Iₐ+aI_b+a²I_c)/3; I₂=(Iₐ+a²I_b+aI_c)/3 | Only L-G uses Z₀; L-L uses Z₁+Z₂ only (no zero seq); 3-φ uses Z₁ only | Given Iₐ,I_b,I_c find I₁,I₂,I₀ |
| **3-φ Fault** | Balanced → only +ve seq network; I_f = V_prefault / Z₁ | Strongest fault (highest current); used to rate circuit breakers | I_f=V/Z₁; SC MVA = MVA_base/Z_pu = √3·V_L·I_f | Most severe but less common; pre-fault V usually 1.0 pu (sometimes 1.05) | Find I_f and SC MVA given Z₁ |
| **L-G Fault** | All 3 seq networks in series: I_f = 3V/(Z₁+Z₂+Z₀+3Z_f) | Most common fault type (80% of all faults); Z₀ depends on grounding | I_f=3V/(Z₁+Z₂+Z₀); L-L: I_f=√3·V/(Z₁+Z₂); DLG: I_f=3V/(Z₁+Z₂∥Z₀) | L-L no Z₀; ungrounded system → Z₀=∞ → zero L-G fault current | Find I_f for SLG vs L-L vs 3-φ |

---

## 7. POWER SYSTEM STABILITY

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **Swing Eq.** | Rotor acceleration = (P_m−P_e)/M; 2nd-order ODE for δ(t) | After a 3-φ fault, generator rotor accelerates; must clear fault before δ exceeds critical angle | (2H/ωₛ)·d²δ/dt² = Pₘ−Pₑ; Pₑ=(EV/X)sinδ | H in MJ/MVA or seconds? Both valid, watch units | Given H, find acceleration at given Pₘ−Pₑ |
| **Critical Clearing** | Equal area criterion: accelerating A₁ = decelerating A₂ for stability | Fast breakers (3-5 cycles) improve stability; 400kV lines clear in <100ms | cosδ_cc = [(π−2δ₀)sinδ₀−cosδ₀]/(π−2δ₀) for 3-φ fault clearing | If A₁>A₂: system loses synchronism; clearing angle > δ_cc is unstable | Find δ_cc given Pₘ and P_max |
| **Stability Limits** | Steady-state: δ<90° (P<EV/X); transient: depends on fault clearance | Series capacitors reduce X → increases P_max; PSS adds damping | P_max=EV/X (steady); P_synch = (EV/X)cosδ (synchronizing coefficient) | Transient limit < steady limit; improving: fast breakers, series C, fast valving | Compare steady vs transient limits |
| **Bus Matrices** | Y_bus from line admittances: Y_ii=sum, Y_ij=-y_ij; Z_bus=Y_bus⁻¹ | Load flow uses Y_bus; Z_kk for fault current at bus k | Y_bus·V=I; Z_kk=fault impedance; passive: symmetric Y_bus | Mutual coupling adds off-diag terms; phase-shift TX breaks symmetry | Build Y_bus for 3-bus system |
| **Equipment Protection** | Buchholz: gas-actuated; Diff: %bias; Distance: Z=V/I; Auto-reclose | Each TX: Buchholz+differential+REF; each line: Z1/Z2/Z3+AR | Z1=80%(instant), Z2=120%(0.3s), Z3=150%(0.8s); I_op>k·I_bias | Inrush has 2nd harmonic → restraint; CVT transient distorts distance | Identify protection for given equipment |

---

## 8. POWER ELECTRONICS

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **SCR** | 4-layer PNPN device; latching after gate trigger; gate loses control | Used in HVDC, large rectifiers; dv/dt false trigger → RC snubber protection | V_GT, I_GT for triggering; I_H = holding current (I_L > I_H always); dv/dt snubber | Once ON gate has no control; turn-off needs anode current < I_H | Identify SCR characteristics |
| **1-φ Rectifier** | Integrate input over conduction angle α to π to get average V_dc | Phase-controlled rectifier: from 0° (max V) to 180° (0V); >90°=inverter | Full: V_dc=V_m(1+cosα)/π; Fully controlled: V_dc=2V_m·cosα/π | 1-φ vs 3-φ formula confusion; α>90° → V_dc negative (inverter) | Find V_dc at α=30°,60° |
| **3-φ Rectifier** | 6 SCRs fire in sequence; each pair conducts 60°; integrate line-to-line V over 60° | Front-end of every VFD: 415V AC in → ~560V DC link | V_dc=1.35·V_LL·cosα; V_dc=2.34·V_Ph·cosα (diode α=0) | V_m in formula = peak line V (not phase V); α>90° → inverter mode | DC link V for 415V input |
| **Chopper (Buck)** | Switch with duty D = T_on/T; Vₒ = (1/T)·∫₀ᵀˢ Vₛ dt = D·Vₛ | Buck converter in every SMPS, LED driver, DC motor speed control | Vₒ=D·Vₛ; Iₒ=Iₛ/D; ripple max at D=0.5 | Buck = step-down; Boost = step-up; don't invert formulas | Vₒ for D=0.6 given Vₛ=100V |
| **Chopper (Boost)** | When switch off, inductor current diverts to load through diode; Vₒ = Vₛ/(1−D) | Used in battery boost, PV MPPT, regenerative braking | Vₒ=Vₛ/(1−D); at D=0.5 → Vₒ=2Vₛ | D→1: Vₒ→∞ (practical limit); polarity non-inverting | Vₒ for D=0.4 given Vₛ=50V |
| **Inverter** | DC → AC; square wave (six-step) or PWM; fundamental V₁=(4Vₛ/π)·sin(ωt) | Solar inverters, VFDs use SPWM/SVPWM; SVPWM gives 15% more output | V₁(fund)=4Vₛ/π; SPWM: V₁=m·V_DC/√3 (3-φ); SVPWM: V₁,mₐₓ=V_DC/√3 | Square wave THD≈48%; PWM: m>1 = overmodulation | Find fundamental V for square wave |
| **Device Table** | SCR=latched, MOSFET=voltage-controlled, IGBT=high power+speed | VFD=I GBT (20-50kHz); HVDC=SCR; SMPS=MOSFET | SCR up to 6kV/5kA; IGBT up to 6.5kV/3.6kA; MOSFET up to 500V | SCR = latching; IGBT = continuous gate; SCR turn-off needs commutation | Match device to application |
| **SCR Triggering** | RC phase shift or UJT relaxation oscillator for gate pulse; alpha set by RC time constant | UJT oscillator is standard: stable, synchronized firing; digital triggering in modern systems | UJT: f=1/(RC·ln(1/(1-η))); R-trigger: 0-90°; RC-trigger: 0-180° | R trigger: temp unstable; UJT: most stable and linear | Choose SCR triggering method |
| **AC/DC Drives** | DC: vary alpha or duty cycle → vary V_dc → vary speed; AC: V/f control for constant flux | DC drives in traction; VFDs in factories; Indian Railways uses VFD-fed 3-phase IM | DC: N=(alpha·V_s−I_aR_a)/kΦ; V/f: V1/f1=V_rat/f_rat; vector: I_q=T, I_d=flux | Below 10Hz: need voltage boost; regen braking: DC link rises | V/f curve for 50Hz motor at 25Hz |

---

## 9. CONTROL SYSTEMS

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **CLTF** | Negative feedback: output compared to reference; error drives the system | AVR (auto voltage regulator) in generators; temperature PID in furnaces | CLTF=G/(1+GH); unity: T=G/(1+G); char. eq: 1+GH=0 | Positive feedback: T=G/(1−GH); sign error flips whole answer | Find CLTF given G, H |
| **Routh-Hurwitz** | Build array from char. polynomial; stability if all 1st column > 0 | Every control system design checks Routh before implementation | All 1st-column >0 → stable; sign changes = #RHP poles | Zero in 1st column: ε substitution; row of zeros: auxiliary polynomial | Test stability of given char. eq. |
| **Steady-State Error** | e_ss = lim_{s→0} s·E(s) by final value theorem; depends on system Type | Type 1: zero step error, finite ramp error; servo motor position control | Type 0: 1/(1+Kₚ); Type 1: 1/K_v; Type 2: 1/Kₐ; Kₚ=lim G(s); K_v=lim sG(s); Kₐ=lim s²G(s) | Type N: zero error for inputs of order < N; ∞ for > N | Find e_ss for step, ramp given G(s) |
| **2nd Order** | ζ=damping ratio; ωₙ=natural freq; step response from poles = −ζωₙ±jωₙ√(1−ζ²) | Servo: ζ≈0.7 (good balance); ζ<0.5 → oscillatory; ζ>1 → slow | tₛ=4/(ζωₙ) at 2%; Mₚ=exp(−ζπ/√(1−ζ²)); ω_d=ωₙ√(1−ζ²); tₚ=π/ω_d | Settling ∝ 1/(ζωₙ) not 1/ωₙ; Mₚ only valid for ζ<1 | Find tₛ, Mₚ given ζ, ωₙ |
| **Bode Plot** | Magnitude: 20log₁₀|G| dB; Phase: ∠G; slopes: −20dB/dec per pole | GM>6dB, PM>30° for robust stability; 45° PM typical target | GM = −|G|(dB) at ω_phase; PM = 180°+∠G at ω_gain; ω_gc: |G|=1 (0dB) | GM at ω_pc, PM at ω_gc (reverse is wrong) | Find GM, PM from Bode |
| **Nyquist** | Plot G(jω) for ω=−∞ to +∞; encirclements of −1 = P−Z | Used for systems with delays, RHP poles (Bode can't handle) | N encirclements of −1 = P_OL − Z_CL (RHP); stable if N = −P | Direction (CW vs CCW) matters; min-phase: stable if no encirclements | Determine stability from Nyquist |
| **PID** | P reduces rise time; I eliminates error; D adds damping | 95% of industrial loops are PI or PID; Ziegler-Nichols for tuning | G_c(s)=Kₚ+Kᵢ/s+K_d·s; Kₚ(proportional), Kᵢ(integral), K_d(derivative) | D amplifies noise — rarely used alone; I causes windup | Design PID for given response |

---

## 10. CIRCUITS

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **Thevenin/Norton** | Any linear 2-terminal circuit = V_th in series with R_th (Thevenin) or I_N∥R_N (Norton) | Power grid appears to your phone charger as a Thevenin source (230V + series Z) | V_th = V_oc; R_th = V_th/I_sc; I_N = I_sc; V_th = I_N·R_th | Dependent sources: ZERO independent sources but KEEP dependent sources | Find V_th, R_th for given circuit |
| **Max Power** | P=I²R_L; dP/dR_L=0 → R_L=R_th; at this point η=50% | Audio amps: max power (50% η); Power systems: high η (low losses) | DC: R_L=R_th → P_max=V_th²/(4R_th); AC: Z_L=Z_th* | AC needs complex conjugate (reactance opposite sign); not just magnitude | Find R_L for max power transfer |
| **Resonance** | At ω₀: X_L=X_C; Z=R (series min) or max (parallel); stored energy cycles between L and C | Radio tuning (series), induction heating (parallel tank), filter design | f₀=1/(2π√LC); Q_series=ω₀L/R=1/(ω₀RC); Q_parallel=R/(ω₀L); BW=f₀/Q | Series: Z_min, I_max; Parallel: Z_max, I_min — opposite! | Find f₀, Q for series/parallel RLC |
| **Transients** | RC/RL: τ=RC or L/R; 63% in 1τ, 99% in 5τ; RLC: 2nd order, 3 damping types | Camera flash (RC), car turn signal (RLC-like), snubber design | VC(t)=V(1−e⁻ᵗ/ʳ) RC charge; IL(t)=I(1−e⁻ᵗ/ʳ) RL charge; RLC: solve s²+(R/L)s+1/LC=0 | Over vs under vs critically damped; initial conditions matter | Find VC(t) given RC, V, t |
| **2-Port** | Z, Y, h, ABCD parameters; AD−BC=1 for reciprocal; A=D for symmetric | T-line ABCD params; transistor h-params; cascade uses ABCD | Z₁₁=V₁/I₁|I₂=₀; AD−BC=1; A=D (symmetric); Z₁₁=A/C | Don't confuse Z vs Y vs h; h₂₁=forward current gain (short output) | Find Z params for given network |
| **Coupled Ckts** | M = k√(L₁L₂); dot convention: current into dot → + voltage at other dot | Transformer model; series aiding (L₁+L₂+2M) vs opposing (L₁+L₂−2M) | M=k√(L₁L₂), 0≤k≤1; aiding: L_eq=L₁+L₂+2M; opposing: L_eq=L₁+L₂−2M | Dot polarity determines sign of M; k=1 for ideal transformer | Find L_eq for given L₁,L₂,M |
| **Millman/Recip.** | Millman: Veq = Σ(V_i/R_i) / Σ(1/R_i); Reciprocity: V in A→I in B = same V in B→I in A | Millman: multiple parallel sources; Reciprocity: bilateral networks only (not diodes) | Veq=(V₁/R₁+V₂/R₂)/(1/R₁+1/R₂); Reciprocity: linear bilateral only | Reciprocity fails for non-bilateral (amplifiers); Millman = weighted average | Find Veq for 3 parallel branches |
| **Star-Delta** | Δ→Y: R_a = R_AB·R_CA/(R_AB+R_BC+R_CA); Y→Δ: R_AB=R_a+R_b+R_aR_b/R_c | Used in 3-φ conversions, transformer winding analysis, bridge networks | Balanced: R_Y=R_Δ/3; unbalanced: use product/sum formulas | Δ→Y: product of adjacent / sum of all three; Y→Δ: sum + product/opposite | Convert Δ (10,20,30) to Y |

---

## 11. THREE PHASE POWER

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **Power Formula** | P=3·V_Ph·I_Ph·cosφ; sub Y: V_Ph=V_L/√3, I_Ph=I_L; Δ: V_Ph=V_L, I_Ph=I_L/√3; both → √3·V_L·I_L·cosφ | Every 3-φ motor nameplate shows rated kW at specified V, I, pf; use this formula | P=√3·V_L·I_L·cosφ; Q=√3·V_L·I_L·sinφ; S=√3·V_L·I_L | Same formula for Y and Δ (line values); don't forget √3 | Find P given 415V, 10A, 0.8pf |
| **Two-Wattmeter** | Two wattmeters measure P=W₁+W₂; tanφ = √3(W₁−W₂)/(W₁+W₂); if W₁=W₂ → pf=1 | Every industrial panel has 2-wattmeter energy meter; pf<0.5 → one reads negative | W₁=V_L·I_L·cos(30°−φ); W₂=V_L·I_L·cos(30°+φ); tanφ=√3(W₁−W₂)/(W₁+W₂) | φ>60° → one wattmeter negative; need to reverse leads for reading | Find pf given W₁=5kW, W₂=3kW |

---

## 12. MEASUREMENTS & INSTRUMENTS

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **PMMC** | T = G·I (deflecting); dc only; linear scale; most accurate | Lab voltmeters/ammeters — PMMC for DC, rectifier type for AC | T=B·A·N·I=G·I; T_c=K·θ; range: shunt Rₛₕ=Rₘ/(m−1); multiplier: Rₛ=(V−IₘRₘ)/Iₘ | PMMC=DC only unless rectifier; moving iron = AC+DC (non-linear) | Find shunt R for 10× range |
| **Bridges** | Wheatstone: balanced when R₁/R₂=R₃/R₄ (galvanometer zero) | Wheatstone = 1Ω−1MΩ; Kelvin = <1Ω; Maxwell = L (Q<10); Schering = C+loss | R_x=R₂·R₃/R₁ (Wheatstone); L_x=R₂R₃C₁ (Maxwell); f=1/(2π√RC) (Wien) | Each bridge for specific measurement range; Kelvin eliminates lead resistance | Identify correct bridge for measurement |
| **CT/PT** | CT: primary in series; NEVER open secondary (lethal kV); PT: across line | CT: 2000/5A for large currents; PT: 33kV/110V for HV metering | CT: Iₚ/Iₛ=Nₛ/Nₚ; PT: Vₚ/Vₛ=Nₚ/Nₛ; CT burden = secondary Z | CT open secondary → core saturates → kV on secondary → lethal | CT ratio for 200A to 5A |
| **CRO** | Voltage = height × V/div; time = width × time/div; Lissajous for phase/freq | Lissajous: sinφ = y₁/y₂; frequency ratio = horizontal/vertical tangencies | f=1/T; Lissajous phase = sin⁻¹(y₁/y₂); freq ratio = H_tang/V_tang | Lissajous: ellipse = phase shift; circle = 90°; line = 0° or 180° | Find phase from Lissajous pattern |

---

## 13. WAVEFORM PARAMETERS

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **Sine RMS/Avg** | RMS = √[∫f²/T] = a/√2; Avg = ∫|f|/T = 2a/π (full-wave); FF = RMS/Avg = 1.11 | Your 230V AC mains: RMS=230V, peak=325V, avg (rectified)=207V | RMS=a/√2≈0.707a; ARV=2a/π≈0.637a; FF=π/(2√2)≈1.11; CF=√2≈1.414 | RMS ≠ average; half-wave: RMS=a/2, avg=a/π, FF=1.57 | Find RMS, avg given peak=325V |
| **Other Waveforms** | Square: RMS=a (same as DC); Triangle: RMS=a/√3; Pulse: RMS=a√D | SMPS output: pulse waveform, duty D determines DC equivalent | Half-wave: RMS=a/2, FF=1.57; Triangle: RMS=a/√3; Square: FF=1.0; Pulse: RMS=a√D, FF=1/√D | Half-wave FF > full-wave (more peaks = less efficient); as D→0, FF→∞ | Find RMS, FF for triangle wave |

---

## 14. MAGNETIC CIRCUITS

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **Reluctance/Flux** | Magnetic Ohm's law: Φ=F/ℛ; F=NI (mmf); ℛ=l/(μ₀μᵣA) | B = Φ/A; μᵣ of iron ≈ 2000-6000 (much higher than air) | Φ=B·A; B=μ₀μᵣH; ℛ=l/(μ₀μᵣA); F=NI=Φ·ℛ; M=k√(L₁L₂) | Air gap → high ℛ → dominates total reluctance; BH curve non-linear | Calculate ℛ for iron+air gap |
| **Core Losses** | Hysteresis ∝ f·Bₘ^1.6; Eddy current ∝ f²·Bₘ²·t² (t=lamination thickness) | Transformer core: 0.35mm Si-steel laminations; 5% Si reduces eddy loss; >5% brittle | P_h∝fBₘ^1.6; P_e∝f²Bₘ²t²; Steinmetz: P_h=K_h·f·Bₘ^n; B lags H | Eddy loss ∝ f² (not f); laminations reduce t→ reduce eddy loss | Compare losses at 50Hz vs 60Hz |

---

## 15. ANALOG ELECTRONICS

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **Diode** | PN junction: I=Is(e^(V/V_T)−1); V_T≈26mV at 300K; Si: 0.7V, Ge: 0.3V | Rectifier diodes in power supplies; Zener diode for voltage reference | Si knee=0.7V; r_d=26mV/I_D (dynamic); I=Is(e^(V/ηV_T)−1) | Dynamic resistance = slope of V-I at Q-point; not static resistance | Find r_d given I_D=10mA |
| **BJT** | I_C=βI_B; I_E=(β+1)I_B; CE: high gain; CB: low Z_in; CC: buffer (Z_in high, Z_out low) | 3 configurations: CE (general amp), CB (HF), CC (buffer); β=50-300 typical | CE: A_v=−βR_C/r_π; r_π=β/g_m; g_m=I_C/V_T; R_in=βr_e | CE inverts (negative gain); CC gain≈1; CB gain ≈ g_mR_C | Find A_v for CE amp given β,R_C |
| **Op-Amp** | Ideal: A_v=∞, R_in=∞, R_out=0; V+=V- (virtual short); no input current | 741 op-amp; in audio, instrumentation, filters; golden rule: V+=V- | Inverting: V_out=−(R_f/R_in)V_in; Non-inv: V_out=(1+R_f/R_in)V_in; Integrator: V_out=−(1/RC)∫V_in dt; Diff: V_out=−RC·dV_in/dt | Virtual short ≠ short circuit (no current); CMRR = A_d/A_cm (∞ ideal) | Find V_out for inverting amp |

---

## 16. DIGITAL CIRCUITS

| Topic | STEP 1: Derivation | STEP 2: Real Life | STEP 3: Exam Form | STEP 4: Examiner Tweaks | STEP 5: Practice |
|-------|-------------------|-------------------|-------------------|----------------------|-----------------|
| **Gates/Boolean** | AND, OR, NOT → NAND/NOR are universal; De Morgan: (AB)'=A'+B' | All digital circuits built from NAND gates; Boolean simplifies logic | A·Ā=0, A+Ā=1, A+AB=A, A+ĀB=A+B; (A·B)'=A'+B'; (A+B)'=A'·B' | De Morgan: complement flips AND↔OR and complements; memorize both | Simplify A+AB+A'B |
| **Flip-Flops** | SR: basic latch (S=R=1 invalid); JK: like SR but toggle; D: data; T: toggle | Counters (divide-by-n), shift registers, state machines | SR→invalid at 11; JK→toggles at 11; D→Q=D at clock; T→toggles | SR has invalid state; JK needs both J and K known; T=JK with J=K=1 | JK input for toggle mode |
| **ADC/DAC** | Flash: fastest, 2ⁿ−1 comparators; SAR: n cycles; R-2R: most common DAC | Flash ADC in high-speed (oscilloscopes); SAR in microcontrollers | Resolution=V_fs/(2ⁿ−1); R-2R: V_out=D·V_ref/2ⁿ; Conv_time_SAR=n·T_clock | Flash has 2ⁿ−1 comparators (not 2ⁿ); SAR uses n clock cycles | Resolution for 8-bit ADC at 5V |
| **8085** | 8-bit µP; 16-bit addr→64KB; 8-bit data; 40-pin; +5V; TRAP=highest priority | Still taught for fundamentals; modern: ARM, RISC-V in practical systems | 16 addr lines; 8 data lines; TRAP>RST7.5>6.5>5.5>INTR; 74 instructions | Address (16) ≠ data (8) lines; TRAP is non-maskable | How much memory? 64KB |

---

## QUICK MEMORY TRICKS (PYQ Patterns)

| Subject | Common Trap | Counter Strategy |
|---------|-------------|-----------------|
| **Transformer** | DC on primary → burns out; SC test side confusion; efficiency half-load vs full-load | DC = no back EMF → high current; OC=LV, SC=HV; compute x²Pcu separately |
| **DC Machines** | Series motor no-load → overspeed (must be loaded); Lap A=P, Wave A=2 | Series motor flux ∝ Iₐ → at no-load Iₐ≈0 → Φ≈0 → N→∞ |
| **Induction Motor** | s_max=R₂/X₂ independent of R₁; Star-Delta: 1/3 I, 1/3 T (not 1/√3) | T∝V² → (1/√3)²=1/3; T_max independent of rotor resistance |
| **Fault Analysis** | 3-φ uses Z₁ only; L-L uses Z₁+Z₂ (no Z₀); L-G uses all three | L-L has no ground path → zero sequence not involved |
| **PE** | Semi vs full converter; 1-φ vs 3-φ formula; α>90° = inverter mode | Semi: Vd=Vd_full·(1+cosα)/2; 3-φ: Vd=1.35V_Lcosα |
| **Control** | Positive vs negative feedback sign; settling time 4/(ζωₙ) not 4/ωₙ; Type vs order | Positive: 1−GH; Type = #integrators; Order = pole count |
| **Measurements** | CT secondary NEVER open; voltmeter/ammeter connection; wattmeter potential/current coil | CT open → saturates → lethal kV; ammeter series, voltmeter parallel |

---

## MARKS DISTRIBUTION

| Subject | Marks | Topics to Master |
|---------|-------|-----------------|
| **Electrical Machines** | ~25 | Transformer (10), DC (5), IM (5), Sync (5) |
| **Power Systems** | ~15 | Transmission + Per-Unit (5), Fault (5), Protection (3), Stability (2) |
| **Power Electronics + Control** | ~16 | PE (8), Control (8) |
| **Electric Circuits** | ~10 | Theorems (4), Resonance (3), Transients (3) |
| **Utilization + Measurements + Electronics** | ~4-8 | Traction/Heating (2), Bridges/Instruments (2), Op-Amp/8085 (1-2) |
| **TOTAL** | **70** | |

---

## PYQ QUESTION → FORMULA MAPPING

| # | PYQ Pattern | Formula |
|---|-------------|---------|
| 1 | Given N,f find P | P=120f/N |
| 2 | TX max η load | x=√(Pi/Pcu) |
| 3 | Auto-TX kVA rating | kVA_auto=kVA_tw×(a/(a−1)) |
| 4 | DC speed | N=(V−IaRa)/(KΦ) |
| 5 | TX voltage regulation | %R=(IRcosφ±IXsinφ)/V×100 |
| 6 | Base change per-unit | Zpu_new=Zpu_old×(MVA_new/MVA_old)×(kV_old/kV_new)² |
| 7 | tanφ from wattmeters | tanφ=√3(W₁−W₂)/(W₁+W₂) |
| 8 | 3-φ fault current | If=V/Z₁ |
| 9 | L-G fault current | If=3V/(Z₀+Z₁+Z₂) |
| 10 | Chopper buck | V₀=D×Vs |
| 11 | Chopper boost | V₀=Vs/(1−D) |
| 12 | Settling time (2%) | ts=4/(ζωₙ) |
| 13 | Peak overshoot | Mp=exp(−ζπ/√(1−ζ²)) |
| 14 | Routh-Hurwitz stability | All 1st-column > 0 → stable |
| 15 | Eddy current loss @ different f | Pe ∝ f² (Bm const) |
| 16 | Hysteresis loss @ different f | Ph ∝ f (Bm const) |
| 17 | Surge impedance | Z₀=√(L/C) |
| 18 | Lap vs wave A | Lap: A=P; Wave: A=2 |
| 19 | Diode knee voltage | Si: 0.7V; Ge: 0.3V |
| 20 | Sine form factor | FF=π/(2√2)≈1.11 |
| 21 | TX oil function | Insulation + cooling |
| 22 | Lamination Si <5% | Reduce eddy loss; >5% → brittle |
| 23 | String efficiency | Max drop across disc nearest conductor |
| 24 | CT secondary | NEVER open → lethal high voltage |
| 25 | SCR latching vs holding | IL > IH always; below IH → turns off |
| 26 | Buchholz relay | Gas actuated device — detects transformer internal faults |
| 27 | Core purpose in TX | Reduce reluctance of magnetic circuit |
| 28 | IM slip from rpm | s=(Ns−N)/Ns; Ns=120f/P |
| 29 | Sync motor excitation vs pf | Over-excited → leading pf; Under-excited → lagging pf |
| 30 | Generator poles from f,N | P=120f/N (even integer) |
| 31 | Short circuit MVA | SC MVA = S_base / Z_pu |
| 32 | Power angle for max P | δ=90° for cylindrical rotor |
| 33 | Rectifier DC at α=0 | 1-φ: 0.9V_s; 3-φ: 1.35V_LL |
| 34 | 2nd order damping ratio | ζ from denominator s²+2ζωₙs+ωₙ² |
| 35 | Thevenin max power | Pmax=Vth²/(4Rth) when RL=Rth |
| 36 | Series vs parallel resonance | Series: Z_min; Parallel: Z_max |
| 37 | DC generator EMF | E=PΦNZ/(60A) |
| 38 | Induction motor max torque | T_max=3V²/(2ωₛX₂), independent of R₂ |
| 39 | Star-Delta starting | 1/3 current, 1/3 torque of DOL |
| 40 | CT ratio calculation | Iₚ/Iₛ=Nₛ/Nₚ |
| 41 | Buchholz relay function | Gas actuated — detects transformer internal faults |
| 42 | Bus impedance for faults | I_fault at bus k = 1/Z_kk(pu) |
| 43 | Distance relay Zone 1 reach | 80% of line (instantaneous) |
| 44 | SCR gate triggering | UJT oscillator: stable, synchronized pulses |
| 45 | DC drive speed control | N = (αV_s − I_aR_a)/kΦ |
| 46 | V/f control for IM | V₁/f₁ = V_rat/f_rat (constant flux region) |
| 47 | Single phase IM starting | Split: T_st=1-1.5×; Cap-start: T_st=2-3×; Shaded: 0.3-0.5× |
| 48 | GTO vs SCR turn-off | GTO: negative gate pulse; SCR: commutation circuit |
| 49 | Barkhausen criterion | |Aβ|=1 and ∠Aβ=0° for sustained oscillation |
| 50 | Negative feedback effect | Decreases gain, increases bandwidth |
| 51 | 8085 address lines | 16 lines → 64 KB memory |
| 52 | DMM 3½ digit max count | ±1999 (½ means first digit max 1) |
| 53 | Q-meter principle | Series resonance: Q = V_C/V_in |
| 54 | KCL/KVL | KCL: ΣI=0 at node; KVL: ΣV=0 around loop |
| 55 | Spot vs seam welding | Spot=stationary tips; Seam=roller electrodes |
| 56 | AC transient worst case | Switching at voltage zero → max DC offset |
| 57 | Multiplexer | 2ⁿ inputs, n select lines |
| 58 | JK flip-flop with J=K=1 | Toggle mode (divide-by-2) |

---

## 📚 QUICK REFERENCE LINKS

| Topic | Article |
|-------|---------|
| Transformer | [CircuitGlobe: Transformer](https://circuitglobe.com/electrical-transformer.html) |
| DC Machine | [CircuitGlobe: DC Machine](https://circuitglobe.com/what-is-a-dc-machine.html) |
| Induction Motor | [CircuitGlobe: Induction Motor](https://circuitglobe.com/equivalent-circuit-of-an-induction-motor.html) |
| Synchronous Machine | [CircuitGlobe: Sync Machine](https://circuitglobe.com/synchronous-machine.html) |
| Star Delta Starter | [CircuitGlobe: Star Delta Starter](https://circuitglobe.com/star-delta-starter.html) |
| Auto Transformer | [CircuitGlobe: Auto TX](https://circuitglobe.com/what-is-an-auto-transformer.html) |
| Thevenin's Theorem | [CircuitGlobe: Thevenin](https://circuitglobe.com/what-is-thevenins-theorem.html) |
| Reciprocity Theorem | [CircuitGlobe: Reciprocity](https://circuitglobe.com/what-is-reciprocity-theorem.html) |
| Two Wattmeter Method | [CircuitGlobe: 2-Wattmeter](https://circuitglobe.com/two-wattmeter-method-of-power-measurement.html) |
| Eddy Current Loss | [CircuitGlobe: Eddy Current Loss](https://circuitglobe.com/what-is-eddy-current-loss.html) |
| Electrical Earthing | [CircuitGlobe: Earthing](https://circuitglobe.com/electrical-earthing.html) |
| Excitation System | [CircuitGlobe: Excitation](https://circuitglobe.com/excitation-system.html) |
| Schering Bridge | [CircuitGlobe: Schering Bridge](https://circuitglobe.com/schering-bridge.html) |
| Kelvin Bridge | [CircuitGlobe: Kelvin Bridge](https://circuitglobe.com/kelvin-bridge.html) |
| Star to Delta Conversion | [CircuitGlobe: Star-Delta](https://circuitglobe.com/star-to-delta-and-delta-to-star-conversion.html) |
| Power in AC Circuit | [CircuitGlobe: AC Power](https://circuitglobe.com/power-in-ac-circuit.html) |
| Active, Reactive, Apparent Power | [CircuitGlobe: Power Triangle](https://circuitglobe.com/what-is-active-reactive-and-apparent-power.html) |
| RLC Series Circuit | [CircuitGlobe: RLC Series](https://circuitglobe.com/what-is-rlc-series-circuit.html) |
| Parallel Resonance | [CircuitGlobe: Parallel Resonance](https://circuitglobe.com/what-is-parallel-resonance.html) |
| Types of Faults | [CircuitGlobe: Faults](https://circuitglobe.com/types-of-faults-in-power-system.html) |
| Relay | [CircuitGlobe: Relay](https://circuitglobe.com/relay.html) |
| Types of Circuit Breaker | [CircuitGlobe: CB Types](https://circuitglobe.com/types-of-circuit-breaker.html) |
| Classification of TL | [CircuitGlobe: TL Classification](https://circuitglobe.com/classification-of-transmission-lines.html) |
| Sequence Impedance | [CircuitGlobe: Sequence Imp](https://circuitglobe.com/sequence-impedance.html) |
| Sequence Networks | [CircuitGlobe: Seq Networks](https://circuitglobe.com/sequence-networks.html) |
| Power Factor Correction | [CircuitGlobe: PF Correction](https://circuitglobe.com/power-factor-correction.html) |
| Steady State Stability | [CircuitGlobe: Stability](https://circuitglobe.com/steady-state-stability-in-power-system.html) |

---

> **Last Updated:** July 2026 | Good luck with your exam!
