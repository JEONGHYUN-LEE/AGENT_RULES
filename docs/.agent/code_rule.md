# Implementation Rule

Goal: execute the approved plan faithfully.

## Inputs
- `docs/task_goal.md`
- `docs/plan.md`
- `docs/research.md` if needed

## Outputs
- code changes
- updated `docs/plan.md` status
- `docs/exec_log.md`

## Allowed
- implement the approved plan
- add or update tests
- update execution status
- write `docs/exec_log.md`

## Forbidden
- do not redesign the solution silently
- do not expand scope silently
- do not modify files outside the modification boundary
- do not refactor unrelated areas
- do not mark work complete without validation

## Execution process
1. read the approved plan carefully
2. read files listed in "Files to read before modify"
3. implement step by step
4. update checklist/status in `docs/plan.md`
5. validate changes
6. record work in `docs/exec_log.md`

## Boundary rule
Only modify files listed in the plan's modification boundary.

If a change outside the boundary is needed:
- stop
- record the issue
- explain why the boundary must expand
- do not continue silently with a new design

## `docs/exec_log.md` should include

1. Summary
2. Step-by-step execution record
3. Files changed
4. Validation results
5. Deviations
6. Remaining issues