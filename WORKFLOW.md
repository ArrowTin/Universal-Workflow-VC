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
* skill discovery and loading (including project-local skills setup);
* memory retrieval and persistence (including memory storage mechanism);
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

### Comprehensive Layer 2 generation

Layer 2 generation must adapt and integrate all relevant Layer 1 modular components:

**Core Concepts (from core/):**
- AGENTS.md → Agent system and multi-AI coordination
- TASKS.md → Task system, state management, traceability
- SKILLS.md → Skill system and lifecycle
- MEMORY.md → Memory classes and gatekeeper rules
- ARTIFACTS.md → Artifact system and versioning
- CONTEXT.md → Context engineering and priority
- CONTRACTS.md → Contract system and boundaries
- PRINCIPLES.md → Core principles adherence
- PROJECT-BOOTSTRAP.md → Bootstrap requirements

**Engineering Practices (from engineering/):**
- ARCHITECTURE.md → Architecture practices
- ENVIRONMENTS.md → Environment management
- RECOVERY.md → Recovery and checkpoint strategies
- RELEASE.md → Release practices
- SECURITY.md → Security practices
- TESTING.md → Testing practices

**Governance Rules (from governance/):**
- AUDIT.md → Audit trail requirements
- CHANGE-CONTROL.md → Change control process
- LEARNING.md → Learning and improvement
- PERMISSIONS.md → Permission management

**Optimization Guidelines (from optimization/):**
- CACHE.md → Caching strategies
- COST.md → Cost optimization
- TOKENS.md → Token optimization

Each Layer 2 document should adapt only the relevant components from Layer 1 based on project needs.

### Layer 2 adaptation guidance

For detailed guidance on adapting Layer 1 components to Layer 2, refer to:

- `templates/guidance/CORE-ADAPTATION.md` - Core concepts adaptation
- `templates/guidance/ENGINEERING-ADAPTATION.md` - Engineering practices adaptation
- `templates/guidance/GOVERNANCE-ADAPTATION.md` - Governance rules adaptation
- `templates/guidance/OPTIMIZATION-ADAPTATION.md` - Optimization guidelines adaptation

These guidance documents provide:
- Mapping between Layer 1 and Layer 2
- When to adapt each component
- What to include in adaptations
- Project-specific customization guidelines
- Minimal vs comprehensive adaptation options
- Best practices for integration

### Skills and memory setup

During Layer 2 generation:

**Skills:**
- Assess project complexity and repetitive patterns
- Determine if project-local skills are needed
- Most projects start with NO project-local skills
- If needed, create `.devin/skills/` structure
- Document skill approach in `docs/operating/SKILLS.md`
- Populate skills incrementally during implementation

**Memory:**
- Assess knowledge-intensive areas
- Choose appropriate memory storage mechanism
- Create memory storage structure (e.g., `.devin/memory/`)
- Document memory approach in `docs/operating/MEMORY.md`
- Initialize empty memory files
- Populate memory as implementation progresses

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
templates/guidance/
```

### Layer 2 generation resources

When generating Layer 2 documentation, use the following resources:

- `templates/operating/` - Operating rules templates
- `templates/guidance/` - Adaptation guidance for all Layer 1 components
- `templates/` - Document templates for various artifacts

Do not duplicate specialized rules unnecessarily.
