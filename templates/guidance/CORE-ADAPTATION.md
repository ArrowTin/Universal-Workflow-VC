# CORE CONCEPTS ADAPTATION GUIDANCE

**Purpose:** Guide Layer 2 generation for adapting core/ concepts from Layer 1

## Overview

Layer 1 `core/` directory contains fundamental concepts that must be adapted to Layer 2 for proper project execution. Not all concepts apply to every project - adapt only what's relevant.

## Core Concepts Mapping

### 1. AGENTS.md → docs/operating/AGENTS.md

**When to adapt:** All projects with multi-AI coordination potential

**What to include:**
- Agent system overview
- Orchestrator role
- Specialist agent roles relevant to project
- Agent contract requirements
- Multi-AI coordination rules
- Conflict handling procedures

**Project-specific customization:**
- Add project-relevant specialist agent roles
- Customize agent selection criteria
- Adapt conflict handling to project needs

### 2. TASKS.md → docs/TASK-PLAN.md + docs/TASK-LOG.md

**When to adapt:** All projects requiring structured implementation

**What to include:**
- Task hierarchy structure
- Required task fields
- Task state definitions
- Ownership rules
- Parallel safety criteria
- Completion requirements
- Traceability requirements

**Project-specific customization:**
- Define project-specific task hierarchy
- Customize task fields for project needs
- Add project-specific task types
- Adapt parallel safety criteria

### 3. SKILLS.md → docs/operating/SKILLS.md

**When to adapt:** Projects with repetitive complex operations

**What to include:**
- Skill lifecycle
- Skill registry structure
- Skill discovery process
- When to create project-local skills

**Project-specific customization:**
- Identify project-specific skill needs
- Define skill creation criteria
- Custom skill registry fields if needed

### 4. MEMORY.md → docs/operating/MEMORY.md

**When to adapt:** All projects with knowledge retention needs

**What to include:**
- Memory classes relevant to project
- Memory gatekeeper rules
- Memory storage mechanism
- Memory retrieval process

**Project-specific customization:**
- Select relevant memory classes
- Define project-specific memory categories
- Choose appropriate storage mechanism

### 5. ARTIFACTS.md → docs/ (integrated into relevant docs)

**When to adapt:** Projects with formal engineering practices

**What to include:**
- Artifact types relevant to project
- Artifact versioning requirements
- Artifact preference over conversation

**Project-specific customization:**
- Define project-specific artifact types
- Set versioning requirements
- Integrate into existing documentation

### 6. CONTEXT.md → docs/operating/CONTEXT.md (if needed)

**When to adapt:** Complex projects with large context needs

**What to include:**
- Context lifecycle
- Context priority order
- Context versioning requirements

**Project-specific customization:**
- Define project-specific context priorities
- Set context versioning policies

### 7. CONTRACTS.md → docs/CONTRACTS.md (if needed)

**When to adapt:** Projects with multiple workstreams/integrations

**What to include:**
- Contract system overview
- Contract structure requirements
- Contract change process

**Project-specific customization:**
- Define project-specific contract types
- Set contract change policies

### 8. PRINCIPLES.md → docs/PRINCIPLES.md (if needed)

**When to adapt:** Projects requiring explicit principle adherence

**What to include:**
- Relevant core principles
- Principle adaptation guidance
- Principle violation handling

**Project-specific customization:**
- Select most relevant principles
- Add project-specific principles
- Define principle enforcement

### 9. PROJECT-BOOTSTRAP.md → docs/PROJECT.md (integrated)

**When to adapt:** All projects

**What to include:**
- Repository separation requirements
- Layer 2 self-contained requirements
- Runtime path definition

**Project-specific customization:**
- Define project-specific runtime path
- Integrate into project documentation

## Adaptation Process

```text
ANALYZE PROJECT NEEDS
→ SELECT RELEVANT CORE CONCEPTS
→ CUSTOMIZE FOR PROJECT CONTEXT
→ INTEGRATE INTO LAYER 2 DOCUMENTS
→ VERIFY COMPLETENESS
```

## Minimal Adaptation

For simple projects, minimal core concepts adaptation:
- TASKS.md → TASK-PLAN.md + TASK-LOG.md (always needed)
- SKILLS.md → SKILLS.md (if skills needed)
- MEMORY.md → MEMORY.md (if memory needed)
- AGENTS.md → AGENTS.md (if multi-AI coordination)

## Best Practices

1. **Relevance over completeness** - Adapt only what the project needs
2. **Project context** - Customize for specific project requirements
3. **Integration** - Integrate concepts into existing documentation rather than creating many separate files
4. **Clarity** - Make adapted concepts clear and actionable for Layer 3
5. **Independence** - Ensure Layer 2 can operate without Layer 1 access