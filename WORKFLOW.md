# UNIVERSAL DYNAMIC AI VIBE CODING WORKFLOW

**Version:** 1.6.0
**Status:** Canonical entry point

## 1. PURPOSE

This repository is **Layer 1**: a reusable workflow for transforming a project idea into a persistent project knowledge system and implementing the project from that system.

It is never the project output repository.

## 2. THREE LAYERS

```text
LAYER 1 — WORKFLOW REPOSITORY
        ↓
interview + universal operating rules
        ↓
LAYER 2 — PROJECT REPOSITORY
        ↓
project documentation + derived operating rules
        ↓
LAYER 3 — PROJECT IMPLEMENTATION
        ↓
code / tests / scripts / infrastructure
```

Layer 2 and Layer 3 use the **same project repository**.

## 3. FIRST ACTION

When loaded:

1. Read `WORKFLOW.md` first.
2. Load only supporting rules required for the current stage.
3. Identify the workflow repository.
4. Ask for the **Project Output Repository**.
5. Verify it is different from the workflow repository.
6. Never write project output into Layer 1.

Do not begin implementation during discovery.

## 4. PROJECT FLOW

```text
READ WORKFLOW
→ LOAD RELEVANT RULES
→ DISCOVER PROJECT
→ INTERVIEW
→ PERSIST STATE
→ SYNTHESIZE PROPOSAL
→ APPROVAL
→ GENERATE LAYER 2
→ INITIALIZE PHASE/TASK STATE
→ PLAN PARALLEL WORK
→ IMPLEMENT LAYER 3
→ SYNC REPOSITORY
→ CLAIM TASK
→ EXECUTE
→ VERIFY
→ UPDATE STATE
→ COMMIT
→ PUSH COMPLETED PHASE
→ LEARN / CONTINUE
```

## 5. INTERVIEW

Use a progressive and conditional interview.

Default interview language is **Bahasa Indonesia**. Technical and domain terms remain in their original form. The developer may choose another language.

Persist material:

* answers;
* decisions;
* assumptions;
* unknowns;
* contradictions;
* requirements;
* constraints;
* project state.

The conversation is not the durable project state.

All project artifacts must be written to the Project Output Repository, never Layer 1.

## 6. LAYER 2 GENERATION

After proposal approval, generate only documents justified by the project under `docs/`, plus root `AGENTS.md`.

Layer 2 and Layer 3 use the same repository.

`AGENTS.md` is the Layer 3 entry point and must explain:

* documentation reading order;
* source-of-truth precedence;
* current phase/task;
* task ownership;
* parallel execution rules;
* skill discovery and loading;
* memory retrieval and persistence;
* model/agent switching;
* repository synchronization;
* Git strategy;
* verification and recovery.

### Derived operating rules

Layer 2 must contain the applicable project-ready operating rules derived from Layer 1, including:

* parallel/sequential execution;
* multi-AI coordination;
* task ownership;
* repository synchronization;
* dynamic agents;
* skills;
* memory;
* model routing/switching;
* context strategy;
* checkpoint/recovery;
* testing/verification;
* Git;
* documentation synchronization;
* change control;
* cost/token optimization.

Do not blindly copy Layer 1. Generate only applicable rules.

Layer 2 must operate independently from Layer 1.

## 7. LAYER 3 RUNTIME

After Layer 2 generation, AI must follow the generated project documentation.

Before every task:

```text
READ AGENTS.md
→ IDENTIFY PHASE/TASK
→ SYNC/PULL LATEST REPOSITORY
→ CHECK TASK OWNERSHIP
→ CHECK DEPENDENCIES / FILE SCOPE
→ CLAIM TASK
→ LOAD RELEVANT DOCS / SKILLS / MEMORY
→ EXECUTE
→ VERIFY
→ UPDATE LOG / STATE
→ SYNC IF REQUIRED
→ COMMIT
```

Approved documentation is the project source of truth.

## 8. MULTI-AI EXECUTION

Multiple AI agents may work concurrently in the same project repository.

Parallel execution is allowed only for tasks proven independent.

Before starting a task, every AI must synchronize with the latest repository state.

An AI must not:

* overwrite another AI's newer changes;
* reset/discard another AI's work;
* force-push shared history;
* modify an actively owned conflicting task;
* assume the repository state is current without synchronization.

If ownership or scope is unclear:

```text
STOP
→ inspect state
→ coordinate
→ continue only after ownership is clear
```

Independent tasks may run in parallel.

Tasks sharing files, state, contracts, dependencies, or ordering constraints must be serialized or explicitly coordinated.

## 9. TASK / PHASE TRACEABILITY

Before implementation:

* create the phase plan;
* create the initial task graph;
* identify dependencies;
* identify parallel-safe tasks;
* initialize `PHASE-LOG.md`;
* initialize `TASK-LOG.md`.

Each task records at minimum:

```text
Task ID
Phase
Status
Owner
Scope
Files / Areas
Dependencies
Parallel-Safe
Started
Completed
Commit
Verification
```

## 10. GIT

Git is both a persistence mechanism and a coordination boundary.

Default:

* synchronize before every task;
* each completed task produces a commit;
* material fixes use separate commits;
* task/phase logs reference commits;
* completed phases are pushed;
* resolve upstream changes before committing;
* never overwrite another AI's work.

Phase completion:

```text
ALL TASKS DONE
→ FINAL SYNC
→ VERIFY
→ UPDATE PHASE LOG
→ COMMIT
→ PUSH
```

## 11. CONTINUITY

A new AI, model, or session must recover from:

```text
AGENTS.md
→ relevant docs
→ TASK-PLAN
→ PHASE-LOG
→ TASK-LOG
→ relevant skills
→ relevant memory
→ Git state
→ current task
```

Conversation history is supplementary.

## 12. MODULAR RULES

`WORKFLOW.md` is the entry point, not the complete rulebook.

Load specialized rules from:

```text
core/
engineering/
governance/
optimization/
```

Do not duplicate specialized rules unnecessarily.
