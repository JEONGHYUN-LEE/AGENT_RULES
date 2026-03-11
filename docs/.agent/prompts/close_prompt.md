Read `docs/.agent/rules/agent_constitution.md`, `docs/research.md`, `docs/plan.md`, and `docs/exec_log.md`.

Update `docs/research.md` with any changes or new information learned during this task.

Ensure `docs/commits` exists; create it if not. Create a folder inside it named: current time in KST (e.g. `YYYY-MM-DD_HH-mm-ss`) then an underscore and a very short summary of the task (e.g. `docs/commits/2025-03-10_14-30-00_add-login-api`). Derive the summary from the task goal or plan; keep it brief (a few words). Time zone must be KST (Asia/Seoul). When you need the current time, do not guess.
Use Python to get the current Korea Standard Time (KST, Asia/Seoul).
Example:
```python
from datetime import datetime
from zoneinfo import ZoneInfo

now_kst = datetime.now(ZoneInfo("Asia/Seoul"))
print(now_kst.strftime("%Y-%m-%d %H:%M:%S %Z"))
```

Move `docs/plan.md` and `docs/exec_log.md` and `docs/task_goal.md` into that timestamp folder.

Recreate `docs/task_goal.md` in the `docs/` folder. The recreated file must begin with the heading `# Task Goal` (and may include additional content as needed).

Do not modify code. Perform only the above steps.
