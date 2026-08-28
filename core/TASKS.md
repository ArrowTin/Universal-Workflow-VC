# TASK SYSTEM

Tasks are the atomic planning unit.

## Hierarchy

```text
Project → Epic → Feature → Task → Subtask
```

## Task quality

Every task needs:

- objective;
- acceptance criteria;
- dependencies;
- risk;
- required artifacts;
- test requirements;
- execution constraints.

## Task state

```text
PENDING
READY
RUNNING
BLOCKED
FAILED
VERIFYING
DONE
CANCELLED
```

## Scheduling rule

A task is READY only when its dependencies and required resources are satisfied.
