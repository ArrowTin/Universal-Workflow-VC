# Universal Dynamic AI Vibe Coding Workflow

A reusable three-layer workflow for AI-assisted software engineering.

## Layers

- **Layer 1:** this workflow repository.
- **Layer 2:** generated project documentation in the project's repository.
- **Layer 3:** project code in the same repository as Layer 2.

The workflow repository is never the project output repository.

## Entry point

Use `WORKFLOW.md` as the first file the AI reads. It routes the AI to only the supporting rules needed for the current stage.

## Quick start

Provide the AI with the workflow URL and your project request. For a new project, the AI must ask for the separate Project Output Repository before generating documentation.

The generated project contains `AGENTS.md` plus only the relevant documents under `docs/`. General operating rules from Layer 1 are copied into project documentation so the project remains executable without the workflow repository.

## Development contract

After documentation approval, development follows the generated documentation. Phase and task state are logged from the start; every completed task is committed, material error fixes are committed separately, and each completed phase is pushed when Git access permits.
