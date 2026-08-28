# QUICKSTART

## 1. Save the workflow

Fork or copy this repository into GitHub.

## 2. Give the workflow URL to your AI

Example:

> Gunakan workflow ini untuk project saya:
> https://github.com/ArrowTin/Universal-Workflow-VC/blob/main/WORKFLOW.md
>
> Saya ingin membangun SaaS dashboard analytics.

## 3. Expected AI behavior

The AI must:

1. read `WORKFLOW.md`;
2. validate it;
3. inspect the current project if one exists;
4. start progressive project interview;
5. avoid coding before project documentation is approved;
6. generate only necessary documentation;
7. build a task graph;
8. select agents/skills/models dynamically;
9. execute with minimum sufficient context;
10. test and verify;
11. checkpoint state;
12. keep documentation synchronized.

## 4. If the platform cannot read URLs

Use one of these fallbacks:

- attach `WORKFLOW.md`;
- paste its contents;
- copy the workflow repository into the project repository.

## 5. Resume

Later, simply say:

> Lanjutkan project.

The AI must load the workflow version, project docs, checkpoint, Git state, task state, environment state and relevant context before continuing.
