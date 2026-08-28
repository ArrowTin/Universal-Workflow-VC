# TASK SYSTEM

Tasks are the atomic execution and coordination unit.

## Hierarchy

```text
Project → Epic → Feature → Task → Subtask
```

## Required fields

Every executable task must define:

* objective;
* acceptance criteria;
* dependencies;
* risk;
* required artifacts;
* test requirements;
* execution constraints;
* owner;
* scope;
* affected files/areas;
* parallel-safety.

## Task state

```text
PENDING
READY
CLAIMED
RUNNING
BLOCKED
FAILED
VERIFYING
DONE
CANCELLED
```

## Ownership

Only one AI may actively own a conflicting task.

Independent tasks may have different owners and execute concurrently.

Before claiming:

```text
SYNC/PULL LATEST
→ inspect TASK-LOG
→ inspect dependencies
→ inspect affected files/areas
→ confirm no conflicting owner
→ CLAIM
```

## Parallel safety

A task is parallel-safe only when concurrent execution cannot create unsafe conflicts through:

* shared files;
* shared state;
* dependency ordering;
* API/contracts;
* database/schema changes;
* generated artifacts;
* configuration;
* environment resources.

When uncertain, treat the task as **not parallel-safe**.

## Completion

A task is complete only after:

```text
implementation
→ verification
→ TASK-LOG update
→ commit reference
→ DONE
```

---

# core/TRACEABILITY.md

# EXECUTION TRACEABILITY

Initialize before coding:

* `docs/TASK-PLAN.md`
* `docs/PHASE-LOG.md`
* `docs/TASK-LOG.md`

Maintain:

```text
Requirement
→ Phase
→ Task
→ Owner / AI
→ Skill
→ Model
→ Artifact
→ Test
→ Commit
→ Phase Push
```

Every task must have a durable owner and status.

Every completed task should map to a commit.

Material fixes should use separate commits.

Every completed phase should be pushed when Git access permits.

Record failed, blocked, conflicting, or unavailable Git operations explicitly.

Never fabricate completion.

## Multi-AI coordination

The task log is the shared coordination state.

Before work:

```text
SYNC
→ READ TASK STATE
→ CLAIM
→ WORK
```

After work:

```text
VERIFY
→ UPDATE TASK STATE
→ COMMIT
```

When concurrent changes are detected:

```text
STOP
→ SYNC
→ INSPECT
→ RESOLVE SAFELY
→ REVERIFY
→ COMMIT
```

---

# optimization/SCHEDULING.md

# RESOURCE SCHEDULING

The scheduler determines whether work should execute sequentially or in parallel.

## Parallel execution

Parallelize only when tasks are demonstrably independent.

Check:

* file overlap;
* dependency graph;
* shared state;
* API/contracts;
* database/schema;
* generated artifacts;
* configuration;
* environment resources;
* ordering requirements.

```text
Independent + isolated
→ PARALLEL

Dependent / conflicting / uncertain
→ SEQUENTIAL
```

When uncertainty exists, serialize the work.

## Shared repository rule

All AI agents working on the same repository must synchronize before beginning a task.

```text
PULL / SYNC
→ READ CURRENT STATE
→ CHECK OWNERSHIP
→ CHECK SCOPE
→ CLAIM
→ EXECUTE
```

After concurrent work changes the repository, agents must synchronize again before integration or commit.

## Scheduling objective

Maximize safe throughput, not raw concurrency.

Prefer fewer safe parallel tasks over unsafe concurrency that creates merge conflicts or invalid intermediate states.
