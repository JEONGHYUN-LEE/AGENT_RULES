# Planning Rule

Goal: Deepen understanding of the task from research, then design a concrete, reviewable implementation plan in one pass.

## Inputs
- `docs/task_goal.md`
- `docs/research.md`

## Output
- `docs/plan.md`

Do not modify code.

## Process
1. **Goal analysis** (from research): interpret goal, identify relevant modules/files, current behavior, execution flow, constraints, invariants, dependencies, edge cases, risks. Go deep only where the goal requires; prefer concrete flow over high-level summary.
2. **Plan design**: decide approach, modification boundary, steps, validation, mitigations.

## `docs/plan.md` must include

1. Goal (and non-goals)
2. Relevant context (from goal analysis; reference research, avoid re-explaining codebase)
3. Design options considered → chosen approach
4. **Modification boundary**: files allowed to change / small edits only / tests. Report if implementation would exceed this.
5. Files to read before modify
6. Constraints and invariants
7. Step-by-step implementation plan
8. Validation strategy
9. Risks and mitigations
10. Execution checklist

- Keep scope bounded; make the plan implementable without redesign.
