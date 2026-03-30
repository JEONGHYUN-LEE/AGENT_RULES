---
description: 승인된 계획에 따라 코드를 구현합니다. Teams 환경에서는 서브에이전트를 활용할 수 있습니다
---

Read the agent constitution from `.claude/rules/agent-constitution.md`, the code rule from `.claude/rules/code-rule.md`, `docs/task_goal.md`, `docs/plan.md`, and all .md files under `docs/knowledge/` if needed (use index/README there to locate).

First perform internal analysis of the approved plan and the target files.
Do not modify code yet.

Read the files listed in "Files to read before modify".
Then implement the approved plan step by step.

Only modify files inside the modification boundary.
If changes outside the boundary are required, stop and report instead of continuing silently.

Update `docs/plan.md` status as you work.
Write `docs/exec_log.md`.
Validate changes before marking work complete.

## Teams: Subagent Delegation

복잡하거나 대규모 구현의 경우, 다음 서브에이전트에 위임할 수 있습니다:

- **researcher** agent: 구현 중 코드베이스의 특정 부분을 깊이 조사해야 할 때
- **planner** agent: 구현 도중 하위 계획이 필요할 때
- **coder** agent: 독립적인 모듈/파일을 병렬로 구현할 때 (worktree 격리)

After the above is complete, perform the close steps: read and follow the instructions in the `/my-close` command.
