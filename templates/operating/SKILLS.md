# SKILL STRATEGY

Skills are modular capabilities used by Layer 3.

## Runtime lifecycle

```text
Discover
→ Select
→ Load
→ Execute
→ Verify
→ Unload
```

## Selection

For each task:

1. identify the required capability;
2. locate the corresponding skill;
3. check compatibility and constraints;
4. load only the required skill;
5. execute its procedure;
6. verify the result.

Prefer the smallest sufficient skill set.

## When to create skills

Create project-local skills when:

1. **Repetitive complex operations** - The same complex task appears multiple times
2. **Cross-project capability** - A capability will be useful across multiple projects
3. **Domain-specific expertise** - Specialized knowledge that requires specific guidance
4. **Tool orchestration** - Complex multi-step workflows with specific tools
5. **Standardization need** - Need to enforce consistent patterns

Do NOT create skills for:
- Simple one-off operations
- Trivial tasks
- Basic tool usage
- Generic coding patterns

## Skill setup instructions

### Initial project setup

During Layer 2 generation, determine if the project requires project-local skills:

```text
ANALYZE PROJECT COMPLEXITY
→ IDENTIFY REPETITIVE PATTERNS
→ ASSESS DOMAIN-SPECIFIC NEEDS
→ CREATE .devin/skills/ IF NEEDED
→ GENERATE INITIAL SKILLS
→ DOCUMENT IN SKILLS.md
```

### Skill directory structure

If project-local skills are needed, create:

```text
.devin/skills/
├── skill-name-1/
│   └── SKILL.md
├── skill-name-2/
│   └── SKILL.md
└── ...
```

Each skill MUST have a `SKILL.md` file with standardized format.

### Minimal initial skills

Most projects start with NO project-local skills. Use built-in skills first. Create project-local skills only when clear need emerges during implementation.

## Skill registry

When project-local skills exist, this document must identify their location and purpose.

A skill definition should provide:

```text
name
purpose
when to use
inputs
procedure
constraints
required tools
verification
related documentation
```

## Skill discovery process

Before execution:

```text
CHECK TASK REQUIREMENTS
→ SCAN .devin/skills/ FOR RELEVANT SKILLS
→ CHECK BUILT-IN SKILLS
→ SELECT SMALLEST SUFFICIENT SET
→ LOAD SKILLS
→ EXECUTE
```

Skills must not silently expand permissions.

A skill may be replaced or supplemented by another skill when the task requires it.

The selected skill and relevant version/context should be recorded for material tasks when traceability is required.
