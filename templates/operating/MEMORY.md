# MEMORY STRATEGY

Memory preserves information that helps future project execution.

## Distinction

```text
Documentation = intended project truth
Memory        = accumulated project knowledge
State         = current execution position
```

Do not use conversation history as the only memory source.

## Memory storage mechanism

### Recommended storage approach

For most projects, use a simple text-based memory system:

```text
.devin/memory/
├── decisions.md          # Architectural and technical decisions
├── discoveries.md       # Implementation discoveries and learnings
├── failures.md          # Recurring failures and their solutions
├── patterns.md          # Project-specific patterns and conventions
├── environment.md       # Environment constraints and setup notes
└── lessons.md           # Lessons learned during development
```

### Alternative approaches

Projects may use alternative memory mechanisms:
- Project wiki or knowledge base
- Database-backed memory system
- External documentation system
- Project-specific memory tools

Choose the simplest approach that meets project needs.

## Memory setup instructions

### Initial project setup

During Layer 2 generation, determine memory needs:

```text
ASSESS PROJECT COMPLEXITY
→ IDENTIFY KNOWLEDGE-INTENSIVE AREAS
→ CHOOSE STORAGE MECHANISM
→ CREATE MEMORY STORAGE STRUCTURE
→ DOCUMENT IN MEMORY.md
→ INITIALIZE EMPTY MEMORY FILES
```

### Minimal initial memory

Most projects start with empty memory files. Populate memory as implementation progresses and knowledge accumulates.

## Retrieval

For each task:

1. identify what previous knowledge may affect the task;
2. retrieve only relevant memory;
3. use it as context;
4. avoid loading unrelated history.

## Persistence

Persist information when it has future operational value, such as:

* decisions;
* implementation discoveries;
* recurring failures;
* successful fixes;
* lessons;
* environment constraints;
* important task state;
* project-specific patterns.

Do not persist:

* secrets;
* credentials;
* unnecessary personal data;
* irrelevant conversation.

## Memory file format

For text-based memory, use structured markdown:

```markdown
# MEMORY TYPE

## [Date] - Entry Title

**Context:** Task/Area where this was learned
**Discovery/Decision:** What was learned or decided
**Impact:** How this affects future work
**Related:** Links to relevant documentation/tasks

---
```

## Updating

When implementation creates material new knowledge:

```text
Discover
→ evaluate future value
→ persist
→ reference from relevant documentation/state
```

Memory must remain consistent with approved project documentation. If a conflict exists, follow the project's defined source-of-truth precedence and record the resulting decision.
