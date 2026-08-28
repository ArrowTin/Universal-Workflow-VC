# PROJECT BOOTSTRAP

Layer 1 and the Project Output Repository must always be separate.

Before generating project documentation:

1. identify Layer 1 repository;
2. ask for the Project Output Repository;
3. verify repository separation;
4. persist interview state in the Project Output Repository;
5. after proposal approval, generate Layer 2;
6. initialize Layer 3 execution state in the same repository.

Layer 2 must be self-contained for runtime use.

It must derive the applicable operating rules from Layer 1 without requiring Layer 1 to remain available during implementation.

The generated project must provide a clear runtime path:

```text
AGENTS.md
→ project documentation
→ operating rules
→ skills
→ memory
→ task/phase state
→ implementation
```

Do not generate unnecessary documents. Generate only artifacts required by the project and workflow.
