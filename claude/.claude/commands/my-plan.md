---
description: task_goal과 knowledge를 바탕으로 구현 계획(docs/plan.md)을 수립합니다
---

Read the agent constitution from `.claude/rules/agent-constitution.md`, the plan rule from `.claude/rules/plan-rule.md`, `docs/task_goal.md`, and all .md files under `docs/knowledge/` (use index/README there to locate).

First perform internal analysis (do not write `docs/plan.md` yet):
- Goal interpretation, non-goals
- Relevant modules, execution flow, constraints, invariants, dependencies, edge cases, risks
- Plausible design options, tradeoffs, chosen approach
- Modification boundary, files to read before modify
- Implementation steps, validation strategy, risks

After the analysis is complete, produce `docs/plan.md`.

Do not modify code. Make the plan concrete, reviewable, and bounded.
