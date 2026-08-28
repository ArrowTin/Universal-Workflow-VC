# QUICKSTART

1. Give the AI the `WORKFLOW.md` URL.
2. AI reads `WORKFLOW.md` first.
3. AI asks for the separate **Project Output Repository** for a new project.
4. AI interviews the developer and persists project state in that repository.
5. After proposal approval, AI generates `AGENTS.md` and relevant `docs/` files.
6. AI copies the applicable Layer 1 operating rules into `docs/operating/`.
7. AI initializes phase/task logs and begins development from the documentation.
8. Every task is committed; material error fixes are separately committed; every completed phase is pushed when possible.

For resume, AI reads `AGENTS.md`, relevant docs, task/phase logs, Git state, and checkpoints before continuing.
