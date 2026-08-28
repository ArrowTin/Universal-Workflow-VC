# AGENT STRATEGY

`AGENTS.md` is the Layer 3 entry point.

## Startup

Every AI must:

1. read `AGENTS.md`;
2. identify the current phase/task;
3. synchronize the repository;
4. inspect task ownership;
5. read relevant documentation;
6. identify required skills;
7. retrieve relevant memory;
8. construct minimum sufficient context;
9. execute;
10. verify;
11. update state;
12. commit.

## Multi-AI coordination

The project repository may be used by multiple AI agents concurrently.

Before claiming work:

```text
SYNC
→ TASK-LOG
→ dependencies
→ affected files
→ ownership
→ CLAIM
```

An AI must not modify a conflicting task already owned by another AI.

Independent tasks may execute in parallel.

## Agent selection

Use specialist agents when useful:

* Architect
* UI/UX
* Frontend
* Backend
* Database
* Testing
* Security
* DevOps
* Review

Agent switching is allowed when beneficial.

Before switching, persist enough state for the next agent to continue independently.

## Conflict handling

If another AI changes the same area:

```text
STOP
→ SYNC
→ inspect changes
→ preserve work
→ resolve
→ verify
→ continue
```

Never silently overwrite another AI's work.

## Source of truth

Approved project documentation defines intended behavior.

Task/phase logs define execution state.

Git defines repository history.

Memory preserves reusable project knowledge.

Conversation history is not authoritative.
