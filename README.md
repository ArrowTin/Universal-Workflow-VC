# Universal Dynamic Agentic AI Vibe Coding Workflow

A reusable, project-agnostic operating procedure for AI-assisted software engineering.

## What this is

This repository is a **workflow/documentation system**, not an application framework.

Its purpose is to let a developer give an AI Vibe Coding agent one workflow reference and have the agent:

1. load and validate the workflow;
2. discover the project;
3. conduct a progressive interview;
4. synthesize requirements and architecture;
5. generate project documentation;
6. obtain approval;
7. create a task graph;
8. dynamically select agents, skills, models and context;
9. implement and test;
10. verify independently where risk requires it;
11. integrate, release and deploy;
12. checkpoint state;
13. recover from failures;
14. detect documentation drift;
15. preserve continuity across sessions and model changes.

## Quick start

Use:

`https://github.com/ArrowTin/Universal-Workflow-VC/blob/main/WORKFLOW.md`

Then tell your coding AI:

> Use this workflow for my project: <WORKFLOW_URL>.  
> I want to build: <PROJECT_DESCRIPTION>.

The AI must enter **Project Discovery & Interview Mode** before coding.

## Design principles

- Intent > Prompt
- Specification > Guessing
- Context > Model
- Artifact > Conversation
- Contract > Assumption
- Task > Chat
- Policy > Autonomy
- Verification > Self-assessment
- Reuse > Modify > Create
- Cache > Recompute
- Minimum Sufficient Context > Full Context
- Parallel when safe
- Sequential when necessary
- Cheap model when sufficient
- Strong model when necessary
- Build once > Rebuild
- Promote > Recreate
- Checkpoint > Memoryless execution
- Documentation > Implicit knowledge
- Evaluated learning > Blind learning

## Repository map

- `WORKFLOW.md` — canonical entry point and operational protocol.
- `QUICKSTART.md` — minimal invocation instructions.
- `core/` — universal workflow rules.
- `engineering/` — architecture, testing, security, environment, release and recovery.
- `optimization/` — token, cost, cache and scheduling rules.
- `governance/` — permissions, audit and change control.
- `templates/` — generated project-document templates.
- `schemas/` — machine-readable task/artifact/checkpoint/release shapes.
- `examples/` — example generated project documentation.

## Version

Current workflow version: `1.0.0`.
