# Goal Research Rule

Goal: deepen understanding of the code paths relevant to the current task.

## Inputs
- `docs/task_goal.md`
- `docs/research.md`

## Output
- `docs/goal_research.md`

## Allowed
- inspect goal-relevant modules in depth
- trace exact execution flow related to the goal
- identify constraints, invariants, dependencies, and risks
- refine earlier research if it turns out incomplete or wrong
- update `docs/goal_research.md`

## Forbidden
- do not create the implementation plan yet
- do not modify code
- do not repeat broad repository explanations unless directly relevant

## `docs/goal_research.md` should include

1. Goal interpretation
2. Relevant modules and files
3. Current behavior
4. Goal-relevant execution flow
5. Constraints and invariants
6. Hidden dependencies and side effects
7. Edge cases and risks
8. Open questions
9. Evidence

## Standards
- start from `docs/research.md`, do not replace it
- go deep only where the goal requires it
- prefer concrete flow tracing over high-level summary