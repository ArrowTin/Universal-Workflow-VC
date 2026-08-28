# MEMORY STRATEGY

Memory preserves information that helps future project execution.

## Distinction

```text
Documentation = intended project truth
Memory        = accumulated project knowledge
State         = current execution position
```

Do not use conversation history as the only memory source.

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

## Updating

When implementation creates material new knowledge:

```text
Discover
→ evaluate future value
→ persist
→ reference from relevant documentation/state
```

Memory must remain consistent with approved project documentation. If a conflict exists, follow the project's defined source-of-truth precedence and record the resulting decision.
