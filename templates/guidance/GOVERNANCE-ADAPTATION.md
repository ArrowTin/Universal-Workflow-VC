# GOVERNANCE RULES ADAPTATION GUIDANCE

**Purpose:** Guide Layer 2 generation for adapting governance/ rules from Layer 1

## Overview

Layer 1 `governance/` directory contains governance rules that should be adapted to Layer 2 based on project scale, team size, and regulatory requirements.

## Governance Rules Mapping

### 1. AUDIT.md → docs/operating/AUDIT.md (or integrated)

**When to adapt:** Projects requiring audit trails or compliance

**What to include:**
- Audit trail requirements
- Events to audit
- Audit data retention
- Audit access controls

**Project-specific customization:**
- Define project-specific audit events
- Set retention policies
- Define access requirements

### 2. CHANGE-CONTROL.md → docs/operating/CHANGE-CONTROL.md (or integrated)

**When to adapt:** Projects with formal change management needs

**What to include:**
- Change control process
- Change approval requirements
- Change impact analysis
- Change rollback procedures

**Project-specific customization:**
- Define change categories
- Set approval thresholds
- Customize impact analysis criteria

### 3. LEARNING.md → docs/operating/LEARNING.md (or integrated)

**When to adapt:** Projects focused on continuous improvement

**What to include:**
- Learning capture process
- Lessons learned documentation
- Improvement identification
- Learning application

**Project-specific customization:**
- Define learning triggers
- Set improvement priorities
- Customize learning capture format

### 4. PERMISSIONS.md → docs/operating/PERMISSIONS.md (or integrated)

**When to adapt:** Projects with access control requirements

**What to include:**
- Permission model
- Role definitions
- Permission assignment process
- Permission review process

**Project-specific customization:**
- Define project-specific roles
- Set permission granularity
- Define review frequency

## Adaptation Process

```text
ASSESS GOVERNANCE NEEDS
→ CONSIDER REGULATORY REQUIREMENTS
→ EVALUATE TEAM SIZE AND STRUCTURE
→ SELECT RELEVANT GOVERNANCE RULES
→ CUSTOMIZE FOR PROJECT CONTEXT
→ INTEGRATE INTO LAYER 2 DOCUMENTS
```

## Minimal Adaptation

For simple projects, minimal governance rules adaptation:
- CHANGE-CONTROL.md → Integrated into existing change processes
- Only add other governance rules if specifically required

## Scale-Based Adaptation

**Small projects (1-3 team members):**
- Minimal change control
- Basic permissions if needed
- No formal audit unless required

**Medium projects (4-10 team members):**
- Formal change control
- Defined permissions
- Basic learning capture

**Large projects (10+ team members):**
- All governance rules
- Formal audit trails
- Comprehensive permissions
- Structured learning process

**Regulated projects:**
- Full audit requirements
- Strict change control
- Formal permissions
- Documented compliance

## Best Practices

1. **Scale-appropriate** - Adapt governance to project and team size
2. **Regulatory awareness** - Consider compliance requirements
3. **Practical enforcement** - Ensure rules can be practically enforced
4. **Team capability** - Match governance to team maturity
5. **Overhead balance** - Balance governance value with overhead

## Integration Approaches

**Option 1: Separate governance documents**
- Create docs/operating/AUDIT.md, etc.
- Best for complex or regulated projects

**Option 2: Integrated into existing documents**
- Add governance sections to relevant docs
- Best for simple to medium projects

**Option 3: Combined governance document**
- Create docs/GOVERNANCE.md covering all aspects
- Best when multiple governance aspects are needed