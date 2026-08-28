# ENGINEERING PRACTICES ADAPTATION GUIDANCE

**Purpose:** Guide Layer 2 generation for adapting engineering/ practices from Layer 1

## Overview

Layer 1 `engineering/` directory contains engineering practices that should be adapted to Layer 2 based on project complexity and requirements.

## Engineering Practices Mapping

### 1. ARCHITECTURE.md → docs/ARCHITECTURE.md (or integrated)

**When to adapt:** All non-trivial projects

**What to include:**
- Architecture decision framework
- Architectural principles
- Technology selection criteria
- Design pattern guidance

**Project-specific customization:**
- Define project-specific architectural principles
- Adapt decision framework to project needs
- Include technology choices and rationale

### 2. ENVIRONMENTS.md → docs/ENVIRONMENTS.md (or integrated)

**When to adapt:** Projects with multiple environments

**What to include:**
- Environment types (dev, staging, prod)
- Environment configuration management
- Environment-specific behavior
- Environment promotion process

**Project-specific customization:**
- Define project environment structure
- Set configuration management approach
- Define promotion criteria

### 3. RECOVERY.md → docs/operating/RECOVERY.md (or integrated)

**When to adapt:** Projects requiring robust recovery strategies

**What to include:**
- Recovery strategies
- Checkpoint guidelines
- Rollback procedures
- State recovery mechanisms

**Project-specific customization:**
- Define project-specific recovery scenarios
- Set checkpoint frequency
- Customize rollback procedures

### 4. RELEASE.md → docs/RELEASE.md (or integrated)

**When to adapt:** Projects with formal release processes

**What to include:**
- Release process
- Release criteria
- Version management
- Release communication

**Project-specific customization:**
- Define release workflow
- Set release quality gates
- Define version strategy

### 5. SECURITY.md → docs/SECURITY.md (or integrated)

**When to adapt:** All projects handling sensitive data or operations

**What to include:**
- Security principles
- Security practices
- Data protection requirements
- Access control guidelines

**Project-specific customization:**
- Define project-specific security requirements
- Adapt security practices to project context
- Include compliance requirements if applicable

### 6. TESTING.md → docs/TESTING.md (or integrated)

**When to adapt:** All projects requiring quality assurance

**What to include:**
- Testing strategy
- Test types and levels
- Test automation requirements
- Quality gates

**Project-specific customization:**
- Define test pyramid for project
- Set test coverage requirements
- Define quality gate criteria

## Adaptation Process

```text
ASSESS PROJECT COMPLEXITY
→ IDENTIFY RELEVANT ENGINEERING PRACTICES
→ CUSTOMIZE FOR PROJECT CONTEXT
→ INTEGRATE INTO LAYER 2 DOCUMENTS
→ ENSURE PRACTICAL IMPLEMENTATION
```

## Minimal Adaptation

For simple projects, minimal engineering practices adaptation:
- ARCHITECTURE.md → Integrated into ARCHITECTURE.md
- TESTING.md → Integrated into TASK-PLAN.md
- SECURITY.md → Only if handling sensitive data

## Best Practices

1. **Complexity-appropriate** - Adapt practices based on project complexity
2. **Practical implementation** - Ensure practices are actionable
3. **Integration** - Integrate into existing documentation where possible
4. **Project-specific** - Customize to project technology and domain
5. **Team capability** - Adapt to team skills and resources

## Project Complexity Guide

**Simple projects:**
- Basic architecture guidance
- Simple testing strategy
- Minimal security practices

**Medium projects:**
- Comprehensive architecture
- Full testing strategy
- Environment management
- Security practices

**Complex projects:**
- All engineering practices
- Detailed recovery strategies
- Formal release processes
- Comprehensive security