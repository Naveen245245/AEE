---
name: electrical-diagrams
description: Draw electrical circuits, transformer equivalents, and waveforms using ASCII art and Mermaid
metadata:
  type: skill
---

# Electrical Diagrams Skill

Use this skill when explaining electrical concepts that need visual diagrams.

## ASCII Art (Simple, works everywhere)

Best for: Transformer equivalent circuits, simple circuits, connection diagrams

### Transformer Equivalent Circuit (referred to primary)

```
        PRIMARY                    SECONDARY
    ────────|↦|─────────────────|↦|───────
            │                    │
           R₁                   R₂'
          X₁                    X₂'
            │                    │
    ────────┼────────────────────┼───────
            │         ┌───┐      │
            └─────────| R₀ ├──────┘
                     │ X₀ │
                     └───┘
```

### Open Circuit Test (LV side test)

```
    ─────────────────────────────────
         AC Source    Voltmeter   Ammeter
             |           |           |
             |           |           |
           (N₁)       (V₁)        (I₀)
             |           |           |
             └───────────┴───────────┘
                    [OC]

    Measured: V₁, I₀, P₀ (iron losses)
```

### Short Circuit Test (HV side test)

```
    ─────────────────────────────────
         AC Source    Voltmeter   Ammeter
             |           |           |
             |           |           |
           (N₁)       (Vsc)       (Isc)
             │           │           │
             └───────||───────||─────┘
                      SHORT
                    [SC]

    Measured: Vsc, Isc, Psc (copper losses)
```

### Star (Y) Connection

```
           Phase A
              │
              │
         ┌────●────┐
        ╱     │     ╲
       ╱      │      ╲
    Phase   Neutral   Phase
    B              C
     │             │
     └──────●──────┘
           (Neutral point)
```

### Delta (Δ) Connection

```
       Phase A ◄───────► Phase B
          │               ▲
          │              ╱
          ▼             ╱
       Phase C ────────►
```

### DC Machine

```
    ┌──────────────────────────────────────┐
    │          ARMATURE (rotor)            │
    │   ┌────────────────────────────┐    │
    │   │  Conductors on surface    │    │
    │   │  (carrying current out)   │    │
    │   └────────────────────────────┘    │
    │                                      │
    │   ←── Rotation (mechanical input)  │
    │                                      │
    │  N    S    N    S    N    S        │
    │  ↑ Poles on stator (field) ↑        │
    └──────────────────────────────────────┘
              │
              │ Commutator + Brushes
              ▼
         DC Output
```

### Three Phase Transformer Connections

```
STAR (Y):                        DELTA (Δ):
       Phase A                        Phase A
          │                              │
          │                        ┌─────┼─────┐
     ┌────●────┐                   │     │     │
    ╱     │     ╲                  │     │     │
   ╱      │      ╲             ◄──┼─────┼─────┼──►
Phase   Neutral   Phase           │     │     │
B              C                   └─────┼─────┘
 │             │                        Phase B
 └──────●──────┘
       (Neutral point)
```

### Inductor & Capacitor Reactance vs Frequency

```
  X_L = ωL                    X_C = 1/(ωC)

  X_L                          X_C
   │                            │
   │                           │←──Infinite at ω=0
   │                            │
   │                            │
  ─┼──────────────→            ─┼──────────────→
   │ ω=0                       │ ω→∞
   │                           │
```

### RLC Series Resonance

```
      ──────/\/\/\/\────o────o─────
                      L       C
                     ───     ───
      Source               │
   V ~                      └──── Resonance frequency ω = 1/√(LC)
```

---

## Mermaid Diagrams (Complex, interactive)

Use `mermaid` code blocks for:
- Block diagrams
- Flowcharts
- Control system diagrams

### Example: Transformer Equivalent Circuit

```mermaid
graph LR
    subgraph Primary
        V1["V₁<br/>Primary Voltage"]
        R1["R₁"]
        X1["X₁"]
    end
    
    subgraph "Magnetizing Branch"
        R0["R₀<br/>Core Loss"]
        X0["X₀<br/>Magnetizing"]
    end
    
    subgraph Secondary
        R2["R₂'"]
        X2["X₂'"]
        V2["V₂'<br/>Secondary Voltage"]
    end
    
    V1 --> R1 --> X1
    X1 --> V2
    X1 --> R0
    R0 --> X0
    X0 --> V2
    R1 -.-> R2
    X1 -.-> X2
```

### Example: Block Diagram (Closed Loop Control)

```mermaid
graph LR
    subgraph "Forward Path"
        E[Error] --> G["G(s)<br/>Plant"]
        G --> H["H(s)<br/>Feedback"]
    end
    
    subgraph "Feedback Path"
        H --> SF[Sum]
    end
    
    Ref[Reference] --> SF
    SF --> E
    H --> F[Feedback Signal]
```

### Example: DC Motor Control

```mermaid
graph LR
    subgraph "DC Motor Circuit"
        V["V<br/>Supply"] --> Ra["Rₐ<br/>Armature"]
        Ra --> La["Lₐ"]
        La --> Ea["Eₐ<br/>Back EMF"]
    end
    
    subgraph "Field Circuit"
        V --> Rf["R_f"]
        Rf --> If["I_f<br/>Field"]
    end
```

---

## Waveform Drawing (ASCII)

### Sinusoidal AC Wave

```
  V
   ↑
 325│            ****           ****
   │          **    **       **    **
   │         *        **    **        *
   │        *           ****           *
   │       *                            
   │      *                              
    ─────┼──────────────────────────────→ t
   -325│      **            **
       │        ****    ****
       │            ****
```

### Three Phase Waveforms

```
  Phase A:    /\    /\    /\    /\    /\
            /    \/    \/    \/    \/    \
  Phase B:      /\    /\    /\    /\    /\
              /    \/    \/    \/    \/    \
  Phase C:        /\    /\    /\    /\    /\
                /    \/    \/    \/    \/    \
                    ↑
              120° apart
```

### Full Wave Rectifier Output

```
  Vdc
   ↑
  Vm│████   ████   ████   ████   ████
   │   ██ ██   ██ ██   ██ ██   ██
   │    ████     ████     ████
  0├──────────────────────────────────→ t
   │
   └─ Ripple voltage
```

---

## Tips for Creating Diagrams

1. **Keep it simple** - ASCII art works best for simple circuits
2. **Use alignment** - spaces matter for ASCII art
3. **Label clearly** - add component values when relevant
4. **Mermaid for complex** - use for block diagrams and flowcharts
5. **Match the viewer's renderer** - not all markdown viewers support Mermaid
