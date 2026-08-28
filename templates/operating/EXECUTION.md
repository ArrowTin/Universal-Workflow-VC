# EXECUTION

This document is the project-specific execution policy derived from Layer 1.

## Work scheduling

Run independent tasks in parallel when they do not share conflicting files, state, dependencies, or resources. Run dependent or conflicting tasks sequentially.

## Task lifecycle

`PENDING → READY → RUNNING → VERIFYING → DONE`.

Blocked or failed tasks must record the reason and recovery action.

## Continuity

Persist state in project artifacts. A new model, agent, or session must recover from `AGENTS.md`, relevant documentation, logs, Git state, and checkpoints.
