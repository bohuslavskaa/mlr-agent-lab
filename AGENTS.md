# AGENTS.md — Working Rules for AI Agents

## Guidelines & Rules
- Read `README.md` and `PLAN.md` before starting any task; keep project decisions inside the repository.
- Try all available tools before asking the user to perform a technical step manually.
- Use an isolated Python environment (via `uv`); record installed packages, versions, and exact commands.
- Run meaningful checks and tests before claiming a task is done.
- Do not weaken or modify a test to make it pass; explain any disagreement or failure first.
- Never publish secrets, API keys, or private data; ask permission before publishing anything.
- Start each new task with: "Make a folder `<task>/` for this task."
- When a session becomes long or fills up, save progress in `PLAN.md`, run `/clear`, and resume work using these project files.
