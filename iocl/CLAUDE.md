# IOCL — 3-Hour Rapid Exam Coach (Electrical, Technical)

This folder is a Claude Code project for IOCL Junior Engineer / Junior Engineering Assistant (Electrical) coaching — **technical/domain section only**.

## How to run (in this folder as your project)

| Type | What you get |
|---|---|
| `/iocl` | Full 3-hour coached session (recap → 5-Q diagnostic → 6 subject rounds → 25-Q technical mock → error review). Repeatable — each session cycles to less-covered topics. |
| `/iocl rapid` | ~30–45 min lightning round when time is short |
| `/iocl mock` | 25-Q timed technical mini-mock |
| `/iocl <topic>` e.g. `/iocl boost chopper` | Drill one micro-topic |
| `/iocl deep <topic>` | 5-step first-principles teaching for one topic |
| `/iocl setter-hunt` | Review the broken/ambiguous source questions |

## Engine files (loaded by the skill)
- Evidence + honesty rules: `iocl-coach/source-analysis.md` ← **read first**
- Session engine: `iocl-coach/00-master/master-orchestrator.md`
- Deep tutor: `iocl-coach/00-master/deep-method.md`
- Block rapid-sheets: `iocl-coach/01-machines` … `iocl-coach/06-measurements-analog-digital` (`meta-prompt.md` each)
- Drill bank: `practice_iocl.md` (300 Q, repaired — see its `## Repair Log`)

## Golden rules
- **Non-technical (aptitude / reasoning / English / GK) is OUT OF SCOPE.** There is no block for it and none in the mock.
- **Negative marking is UNVERIFIED.** Default rule: answer if you can eliminate two options; otherwise skip and mark for review. Never advise blind guessing.
- **The sources are coaching-institute question sets, not official IOCL papers, and they have no answer keys.** Never state official weightage or the exam duration/marks as fact.
- Technical is breadth — 18 flat topics, no skippable block. Facts + quick formulas, not derivations (unless `deep`).
- `[BROKEN SOURCE]` and `[AMBIGUOUS STEM]` questions are excluded from scored drills and the mock.
