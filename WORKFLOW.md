# UNIVERSAL DYNAMIC AI VIBE CODING WORKFLOW

**Version:** 1.4.0
**Status:** Canonical entry point

## 1. PURPOSE

This repository is **Layer 1**: a reusable workflow for turning a project idea into a persistent project documentation system and then building the project from that documentation.

It is not the project repository and must never be used as the project output repository.

## 2. THREE LAYERS

```text
LAYER 1 — WORKFLOW REPOSITORY
        ↓ interview + universal rules
LAYER 2 — PROJECT DOCUMENTATION
        ↓ approved project specification + copied operating rules
LAYER 3 — PROJECT IMPLEMENTATION
        ↓ code / tests / scripts / infrastructure
```

Layer 2 and Layer 3 live in the **same project repository**.

## 3. FIRST ACTION

When this workflow is loaded:

1. Read this file first.
2. Load only the supporting rules needed for the current stage from `core/`, `engineering/`, `governance/`, and `optimization/`.
3. Identify the workflow repository.
4. Ask for the **Project Output Repository** before generating project documentation for a new project.
5. Verify the Project Output Repository is different from the workflow repository.
6. Never write project output into the workflow repository.

Do not start coding merely because the workflow was loaded.

## 4. PROJECT FLOW

```text
READ WORKFLOW
→ LOAD RELEVANT RULES
→ DISCOVER PROJECT
→ INTERVIEW
→ PERSIST INTERVIEW STATE
→ SYNTHESIZE PROPOSAL
→ APPROVAL
→ GENERATE LAYER 2
→ INITIALIZE PHASE/TASK LOGS
→ DEVELOPMENT FROM DOCUMENTATION
→ TEST / VERIFY
→ COMMIT TASK
→ COMMIT MATERIAL FIX
→ PUSH COMPLETED PHASE
→ CHECKPOINT / LEARN
→ CONTINUE
```

## 5. INTERVIEW

Use progressive, conditional interview. Default language is **Bahasa Indonesia**; technical/domain terms remain in their original form. The developer may choose another language.

Persist material answers, decisions, assumptions, unknowns, and contradictions while interviewing. Do not rely on conversation history as the durable state.

Before approval, maintain the project proposal and interview state in the **project repository**, not this workflow repository.

## 6. LAYER 2 GENERATION

After proposal approval, generate only the documents relevant to the project under `docs/`, plus a root `AGENTS.md`.

Minimum entry structure:

```text
<project-repository>/
├── AGENTS.md
└── docs/
    ├── PROJECT.md
    ├── REQUIREMENTS.md
    ├── ARCHITECTURE.md
    ├── TASK-PLAN.md
    ├── PHASE-LOG.md
    ├── TASK-LOG.md
    └── operating/
        ├── EXECUTION.md
        ├── AGENTS.md
        ├── SKILLS.md
        ├── MODELS.md
        ├── MEMORY.md
        └── GIT.md
```

Add other project documents only when justified, such as API, database, security, testing, deployment, design system, or environment documentation.

### Operating rules copied from Layer 1

Layer 2 must contain a **derived, project-ready copy** of the general operating conditions from Layer 1 that are applicable to the project. This includes, when relevant:

- parallel/sequential execution;
- dynamic agent selection and switching;
- skill discovery, selection and lifecycle;
- model routing and switching;
- context and memory strategy;
- task orchestration;
- checkpoint and recovery;
- testing and verification;
- cost/token optimization;
- permissions and security;
- documentation synchronization;
- change control and learning;
- Git commit/push strategy.

Layer 2 must not require Layer 1 to be present at runtime.

`AGENTS.md` is the project entry point. It explains the purpose, reading order, relationships, precedence, and use of all generated documents.

## 7. LAYER 3 DEVELOPMENT

Once Layer 2 is generated and approved, implementation begins.

The AI must:

- read `AGENTS.md` first;
- follow the relevant `docs/` documents;
- treat approved documentation as the project source of truth;
- update documentation when material decisions or implementation changes alter it;
- never silently redefine approved scope or architecture.

## 8. PHASE / TASK TRACEABILITY

Before implementation:

- create the phase plan;
- create the initial task graph;
- initialize `PHASE-LOG.md` and `TASK-LOG.md`.

During implementation:

```text
TASK START
→ mark RUNNING
→ execute
→ test / verify
→ update TASK-LOG
→ commit task
→ mark DONE
```

For failures:

```text
ERROR
→ diagnose
→ fix
→ verify
→ log fix
→ separate fix commit
→ continue
```

At phase completion:

```text
all phase tasks DONE
→ verification
→ update PHASE-LOG
→ push phase
```

Use parallel execution only for independent tasks. Dependent or conflicting work remains sequential.

## 9. CONTINUITY

A new session, model, or agent must recover from durable project artifacts, not conversation memory alone:

```text
AGENTS.md
→ relevant docs
→ TASK-PLAN / PHASE-LOG / TASK-LOG
→ Git state
→ checkpoint / current context
→ continue
```

Model, agent, and skill changes are allowed when the required state is preserved.

## 10. SUPPORTING RULES

Use the modular documents instead of expanding this file unnecessarily:

- `core/PROJECT-BOOTSTRAP.md` — repository boundaries and project initialization.
- `core/INTERVIEW.md` — interview engine.
- `core/AGENTS.md` — agent strategy.
- `core/SKILLS.md` — skill strategy.
- `core/MODELS.md` — model routing.
- `core/MEMORY.md` — memory strategy.
- `core/TASKS.md` — task system.
- `core/ARTIFACTS.md` — durable artifacts.
- `core/CONTEXT.md` — context strategy.
- `core/TRACEABILITY.md` — traceability.
- `engineering/RECOVERY.md` — recovery.
- `engineering/TESTING.md` — testing.
- `engineering/SECURITY.md` — security.
- `engineering/RELEASE.md` — release.
- `governance/CHANGE-CONTROL.md` — controlled change.
- `governance/LEARNING.md` — learning.
- `governance/AUDIT.md` — audit.
- `optimization/SCHEDULING.md` — parallel/sequential scheduling.
- `optimization/TOKENS.md` — token strategy.
- `optimization/COST.md` — cost strategy.
- `optimization/CACHE.md` — cache strategy.

Load only what is relevant. Do not reproduce every rule in `WORKFLOW.md`.
