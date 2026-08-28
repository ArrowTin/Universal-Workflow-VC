# AGENT SYSTEM

Agents are temporary execution roles, not necessarily permanent services.

## Orchestrator

Owns planning, routing, scheduling, monitoring, verification, recovery and integration.

## Specialist agents

Examples:

- Architect
- UI/UX
- Frontend
- Backend
- Database
- Testing
- Security
- DevOps
- Review
- SEO
- Accessibility

Instantiate only roles justified by project/task needs.

## Agent contract

An agent must:

1. read its task;
2. retrieve minimum sufficient context;
3. obey permissions;
4. produce expected artifacts;
5. run required verification;
6. report evidence;
7. checkpoint meaningful state.

## Multi-AI coordination

Multiple AI agents may work concurrently in the same project repository.

Before claiming work:

```text
SYNC/PULL LATEST
→ READ TASK STATE
→ INSPECT DEPENDENCIES
→ INSPECT AFFECTED FILES/AREAS
→ CONFIRM NO CONFLICTING OWNER
→ CLAIM
```

An AI must not modify a conflicting task already owned by another AI.

Independent tasks may execute in parallel.

## Conflict handling

If another AI changes the same area:

```text
STOP
→ SYNC
→ INSPECT CHANGES
→ PRESERVE WORK
→ RESOLVE
→ VERIFY
→ CONTINUE
```

Never silently overwrite another AI's work.
