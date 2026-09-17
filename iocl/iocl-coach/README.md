# IOCL 3-Hour Rapid Coach (Electrical — Technical)

Turn any LLM into a **final-sprint coach** for the IOCL Junior Engineer / Junior Engineering Assistant (Electrical) CBT — **technical section only**.

> ### ⚠️ Read this before trusting anything this coach says about the exam
> The four source papers in `../` are **coaching-institute question sets**, not official IOCL past papers, and **none of them contains an answer key**. Public sources also **conflict** on the exam pattern (150 Q/150 min/−0.25 vs 100 Q/100 min/none). This coach therefore:
> - never states official weightage,
> - never states the duration, marks, or negative marking as fact,
> - never advises blind guessing.
>
> See `source-analysis.md` §1–§2 for the evidence.

## Files

```
iocl-coach/
├── README.md                  ← you are here
├── source-analysis.md         ← evidence + honesty rules (read FIRST)
├── 00-master/
│   ├── master-orchestrator.md ← the session engine
│   └── deep-method.md         ← 5-step tutor, loaded only on `deep`
├── 01-machines/meta-prompt.md
├── 02-power-systems/meta-prompt.md
├── 03-power-electronics/meta-prompt.md
├── 04-circuits-fields-materials/meta-prompt.md
├── 05-control-and-signals/meta-prompt.md
└── 06-measurements-analog-digital/meta-prompt.md
```

Supporting files one level up: `../CLAUDE.md` (project entry), `../.claude/skills/iocl/SKILL.md` (slash router), `../.analysis/*.txt` (frozen PDF extracts — the audit trail), `../practice_iocl.md` (the 300-question drill bank).

**There is no non-technical block.** Aptitude, reasoning, English, and GK are out of scope by the user's decision.

## Quick start (Claude Code)

Open `../` (the `iocl/` folder) as your project, then:

| Command | What you get |
|---|---|
| `/iocl` | Full 3-hour session: diagnostic → 6 rounds → 25-Q technical mock → error review |
| `/iocl session 2` | New session cycling to less-covered topics (repeatable) |
| `/iocl rapid` | ~30–45 min lightning round |
| `/iocl mock` | 25-Q timed technical mini-mock |
| `/iocl <topic>` | Drill one micro-topic, e.g. `/iocl boost chopper` |
| `/iocl deep <topic>` | 5-step first-principles teaching |
| `/iocl setter-hunt` | Review the broken/ambiguous source questions |

## In any other LLM

Load `source-analysis.md`, then `00-master/master-orchestrator.md`, then the block file(s) for the subjects you want to drill. Paste them as system context. Invoke by saying "start IOCL" / "drill me on machines".

## The six blocks

Sized to the **drill bank** (300 questions), since no reliable exam weightage exists. The sources are unusually flat — no subject above ~15% — so **every block is ★★★ and none can be skipped**.

| Block | Covers | Drill-bank Qs | Engine slot |
|---|---|---|---|
| `01-machines` | Transformer, DC, induction, synchronous, drives | 42 | R1 · 22 min |
| `02-power-systems` | Load flow, faults, protection, stability, T&D | 42 | R2 · 22 min |
| `03-power-electronics` | Rectifiers, choppers, inverters, PWM, devices | 43 | R3 · 20 min |
| `04-circuits-fields-materials` | Network theory, EM fields, materials | 63 | R4 · 25 min |
| `05-control-and-signals` | Control, LTI, Laplace/Z, sampling | 55 | R5 · 22 min |
| `06-measurements-analog-digital` | Bridges, CT/CRO, op-amps, ADC/DAC, logic | 39 | R6 · 20 min |

## Exam facts to remember

- **Technical only** — no aptitude/reasoning/English/GK in this coach.
- Duration, marks, and negative marking: **unconfirmed** — check the official IOCL notification.
- **Guessing rule:** answer if you can eliminate two options; otherwise skip and mark for review.
- Broad recall paper: ~40% single-concept, ~35% one-formula numeric, ~20% discriminator. No multi-step derivations.
- The drill bank carries `[KEY-FIXED]` / `[BROKEN SOURCE]` / `[AMBIGUOUS STEM]` / `[UNVERIFIED]` markers — see `practice_iocl.md` → `## Repair Log`.
