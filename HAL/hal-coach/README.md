# HAL 3-Hour Rapid Coach

Turn any LLM into a **final-sprint coach** for the HAL MT/Design-Trainee (Electrical) CBT and same-setter defense-PSU EE papers. Built from the collected BDL EE 2022/23/25 PYQs in `../HAL/` + the published HAL-2026 pattern.

## Files

```
hal-coach/
├── README.md                     ← you are here
├── pyq-analysis.md               ← weightage evidence (read first)
├── 00-master/master-orchestrator.md  ← the 3-hour session engine
├── 01-machines/meta-prompt.md
├── 02-power-systems/meta-prompt.md
├── 03-power-electronics-and-control/meta-prompt.md
├── 04-circuits-and-measurements/meta-prompt.md
├── 05-electronics-signals-fields/meta-prompt.md
└── 06-non-technical/meta-prompt.md
```

## Quick start (Claude Code)

Open `/Users/naveenvp/Desktop/AEE/HAL` as the project and type:

- **`hal`** → full 3-hour coached session (paper recap → 5-Q diagnostic → priority drill rounds → mixed mock → error review)
- **`hal rapid`** → ~30-45 min lightning round if time is short
- **`hal mock`** → straight to a 25-Q timed mini-mock
- **`hal boost chopper`** → drill one micro-topic
- **`hal deep induction motor`** → 5-step derivation mode for one topic

## In any other LLM
Paste `pyq-analysis.md` + `00-master/master-orchestrator.md` + the block you want as your system prompt, then say "start HAL".

## Exam facts to remember
160 Q / 160 marks / 2.5 h · Part-III Electrical 100 · Part-II English+Reasoning 40 · Part-I GA 20 · no negative marking → **never leave a blank**.
