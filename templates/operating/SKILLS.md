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

Skills must not silently expand permissions.

A skill may be replaced or supplemented by another skill when the task requires it.

The selected skill and relevant version/context should be recorded for material tasks when traceability is required.
