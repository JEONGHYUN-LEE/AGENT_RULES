# Planning Rule

Goal: design a concrete, reviewable implementation plan for the current task.

## Inputs
- `docs/task_goal.md`
- `docs/research.md`
- `docs/goal_research.md`

## Output
- `docs/plan.md`

Do not modify code.

## `docs/plan.md` must include

1. Goal
2. Non-goals
3. Relevant context
4. Design options considered
5. Chosen approach
6. Modification boundary
7. Files to read before modify
8. Constraints and invariants
9. Step-by-step implementation plan
10. Validation strategy
11. Risks and mitigations
12. Execution checklist

## Modification boundary
The plan must define which files are allowed to change.

Use this structure:

- Files allowed to change
- Files allowed for small edits only
- Tests allowed to change

If implementation seems to require changes outside this boundary, that must be reported during coding.

## Planning principles
- design decisions happen here
- keep scope bounded
- make the plan implementable without redesign
- avoid re-explaining the whole codebase; reference research instead