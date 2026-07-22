# AE Electrical Exam Preparation - Andhra Pradesh

**Context:** 1-week intensive preparation for AP AEE Electrical exam. This folder has a complete study system at `../ap-aee-study/` with subject-specific meta-prompts (skills).

---

## Your Study System

The folder `/Users/naveenvp/Desktop/AEE/ap-aee-study/` contains **6 subject skills** (meta-prompts):

| Subject | Location | Marks |
|---------|----------|-------|
| Electric Circuits | `01-electric-circuits/meta-prompt.md` | ~10 |
| Electrical Machines | `02-electrical-machines/meta-prompt.md` | ~25 |
| Power Systems | `03-power-systems/meta-prompt.md` | ~15 |
| Power Electronics | `04-power-electronics/meta-prompt.md` | ~8 |
| Control Systems | `05-control-systems/meta-prompt.md` | ~8 |
| Utilization & Measurements | `06-utilization-measurements/meta-prompt.md` | ~4-8 |

**Master Orchestrator:** `00-master/master-orchestrator.md` — overall coach that coordinates all 6 subjects.

---

## How to Use These Skills

When you ask me questions:
1. **"Teach me [formula/topic]"** → I'll use the 5-step method from the meta-prompt
2. **"Start Day 1"** → I'll run the Day 1 plan from the master orchestrator
3. **"Give me practice questions on [topic]"** → I'll generate exam-style questions with examiner tweaks
4. **"Deep dive on [subject]"** → I'll load that subject's meta-prompt for detailed coverage

---

## Quick Formula Reference (High-Yield)

### Priority Order: Machines (25) → Power Systems (15) → Power Electronics (8) → Control (8) → Circuits (10) → Utilization (4-8)

### Transformers
- EMF: `E = 4.44 f N Φm`
- Ratio: `K = N₂/N₁ = V₂/V₁ = I₁/I₂`
- Efficiency: `η = (x·S·cosφ) / (x·S·cosφ + Pi + x²Pcu)`
- Max η when: `Pi = x²Pcu` → `x = √(Pi/Pcu)`
- Regulation: `%R = (Vnl - Vfl)/Vfl × 100`
- Auto-transformer savings: `(1 - 1/a) × 100%`

### DC Machines
- EMF: `E = (PΦNZ)/(60A)`
- Torque: `T = (PΦZI)/(2πA)`
- Speed: `N ∝ V/Φ`

### Induction Motor
- Slip: `s = (Ns - N)/Ns`
- Torque: `T ∝ (V²·s·R₂) / (R₂² + s²X₂²)`
- Max torque at: `s = R₂/X₂`
- Starting torque: `Ts = (3V²R₂) / (ωs[(R₁+R₂)² + (X₁+X₂)²])`

### Synchronous Machine
- Frequency: `f = PN/120`
- Voltage regulation: `%VR = (E - V)/V × 100`
- Power: `P = (EV/Xs)sinδ`

### Power Systems
- Transmission: `VS = VR + IZ`
- Per-unit: `Zpu = Zactual × (MVAbase / kVbase²)`
- Symmetrical components: `I₀ = (Ia+Ib+Ic)/3`, `I₁ = (Ia+aIb+a²Ic)/3`, `I₂ = (Ia+a²Ib+aIc)/3`
- Fault current: `If = V/(Z₁+Zf)` (3-φ)
- Stability: `δcc = cos⁻¹[...]`

### Power Electronics
- Rectifier DC: `Vdc = (Vm/π)(1+cosα)` (1-φ fully controlled)
- Chopper: `V₀ = D×Vs` (step-down)
- Inverter: fundamental `V₁ = (4Vs)/(nπ)`

### Control Systems
- CLTF: `G/(1+GH)`
- Error constants: `Kp = lim G(s)`, `Kv = lim sG(s)`, `Ka = lim s²G(s)`
- Routh-Hurwitz: all first-column > 0
- Nyquist: encirclements = P-Z
- GM/PM from Bode

---

## 1-Week Plan

| Day | Focus |
|-----|-------|
| Day 1-2 | Electrical Machines (~25 marks) |
| Day 3 | Power Systems + Protection (~15 marks) |
| Day 4 | Power Electronics + Control Systems (~16 marks) |
| Day 5 | Electric Circuits (~10 marks) |
| Day 6 | Utilization + Measurements + Electronics |
| Day 7 | Full mock + revision |

---

## My Capabilities for Your Prep

When you ask me to teach, I will:
1. **Derive from first principles** — you should be able to re-derive in exam
2. **Give real-life anchors** — Indian grid context (400 kV, 50 Hz, APTransco)
3. **Show exam form** — LaTeX with units
4. **Predict examiner tweaks** — the 3-4 common traps
5. **Generate practice questions** — with full solutions
6. **Link cross-subject** — examiners combine topics

**Start command:** Say **"Start AP AEE prep"** or **"Begin Day [1-7]"** and I'll run the coaching session.

**Example questions to ask:**
- "Teach me transformer EMF equation from scratch"
- "Show me how the examiner twists 3-phase fault questions"
- "Give me 5 practice questions on induction motor starting torque"
- "Link Thevenin's theorem to fault analysis in power systems"
