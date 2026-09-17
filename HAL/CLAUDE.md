# HAL — 3-Hour Rapid Exam Coach (Electrical)

This folder is a Claude Code project for rapid HAL/defense-PSU EE exam coaching. The exam: **160 Q / 2.5 h, no negative marking** (Part-III Electrical 100 · Part-II English+Reasoning 40 · Part-I GA 20). Coached on the collected BDL EE 2022/23/25 PYQs here (same setter family).

## How to run (in this folder as your project)

| Type | What you get |
|---|---|
| `/hal` | Full 3-hour coached session (recap → 5-Q diagnostic → priority drill → mixed mock → error review). Repeatable — each session cycles to new topics. |
| `/hal rapid` | ~30–45 min lightning round when time is short |
| `/hal mock` | 25-Q timed mini-mock |
| `/hal <topic>` e.g. `/hal boost chopper` | Drill one micro-topic |
| `/hal deep <topic>` | 5-step derivation teaching for one topic |

## Engine files (loaded by the skill)
- Evidence/weightage: `hal-coach/pyq-analysis.md`
- Session engine: `hal-coach/00-master/master-orchestrator.md`
- Block rapid-sheets: `hal-coach/01-machines` … `hal-coach/06-non-technical` (`meta-prompt.md` each)

## Golden rules
- **Never leave a question blank** (no negative marking).
- ~55 s/question; technical 100 Q is breadth — facts + quick formulas, not derivations.
- Non-technical = 37.5% of marks: never skip the quant/reasoning/English/GK block.
