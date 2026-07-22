# AP AEE (Electrical) — AI Tutor Meta-Prompts

A complete set of meta-prompts that turn any capable LLM (Claude, GPT-4+, Gemini 2.0+, local models with 32K+ context) into a **subject-matter tutor** for the **Andhra Pradesh Assistant Executive Engineer (Electrical)** exam.

## What's in the box

```
ap-aee-study/
├── README.md                              ← you are here
├── 00-master/
│   └── master-orchestrator.md            ← start here
├── 01-electric-circuits/
│   └── meta-prompt.md
├── 02-electrical-machines/
│   └── meta-prompt.md
├── 03-power-systems/
│   └── meta-prompt.md
├── 04-power-electronics/
│   └── meta-prompt.md
├── 05-control-systems/
│   └── meta-prompt.md
└── 06-utilization-measurements/
    └── meta-prompt.md
```

## How to use

### 1. Pick a subject folder
Open the file in the subject you want to study (e.g. `02-electrical-machines/meta-prompt.md`).

### 2. Copy the entire content of that `.md` file
The whole file is a self-contained system prompt. No external data needed.

### 3. Paste it into your LLM as a "System Prompt" / "Custom Instructions"
- **Claude**: Projects → Custom Instructions → paste
- **ChatGPT**: Custom GPT → Configure → Instructions → paste (or use a Custom GPT)
- **Gemini**: Gems → Instructions → paste
- **Local (Ollama, LM Studio)**: System prompt field
- **Cursor / Continue / Cline**: System prompt for the chat

### 4. Start asking
The tutor is now ready. Try:
- "Teach me transformer EMF equation from scratch"
- "Show me how the examiner twists 3-phase fault questions"
- "Give me 5 practice questions on induction motor starting torque"
- "Link Thevenin's theorem to fault analysis in power systems"

## What's inside each meta-prompt

Every subject file contains the **same 6-section structure** so the AI behaves consistently:

| Section | What it does |
|---|---|
| **1. Role Definition** | Who the AI is, what exam it's prepping you for, your target rank/band |
| **2. Knowledge Base** | Every formula, every variable, every examiner trick for that subject — your syllabus |
| **3. Teaching Methodology** | 5-step method: First-principles → Real-life analogy → Derivation → Examiner trick → Practice Q |
| **4. Output Format Rules** | How every answer must be structured (LaTeX math, tables, "trap" callouts) |
| **5. Cross-Subject Linkages** | How this subject's formulas connect to the other 5 (examiners love these) |
| **6. Examiner Tweak Catalog** | The 10-15 most common ways the AP AEE examiner "tweaks" questions in this subject |

## Why this works (the pedagogy)

The prompt enforces a **5-step learning loop** for every formula:

```
Step 1: DERIVE from first principles (e.g., F = ma → V = IR → P = VI)
Step 2: ANCHOR in real life (e.g., "V = IR is why your phone charger 
         is 5V/2A and not 50V/0.2A — same power, different current 
         means different wire thickness")
Step 3: SHOW the exam form (with all the variable substitutions)
Step 4: REVEAL the examiner tweak (the 3-4 common traps)
Step 5: PRACTICE with similar-tweaked questions
```

This is the loop the **top 1% rankers** use — they don't memorize, they **derive-and-connect**.

## The 1-week study plan (built into the master orchestrator)

| Day | Focus | Time |
|---|---|---|
| Day 1-2 | Electrical Machines (highest weightage) | 4-5 hr/day |
| Day 3 | Power Systems + Protection | 4-5 hr |
| Day 4 | Power Electronics + Control Systems | 4-5 hr |
| Day 5 | Electric Circuits | 3-4 hr |
| Day 6 | Utilization + Measurements + Electronics | 3-4 hr |
| Day 7 | Full mock test + formula revision | 6-8 hr |

## License

These prompts are yours to modify, remix, and include in your repo. The formula knowledge base draws on standard electrical-engineering pedagogy (Fitzgerald, Chapman, Hayt, Sadiku) plus 10+ years of competitive-exam question patterns.
