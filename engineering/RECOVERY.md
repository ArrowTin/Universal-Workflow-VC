# RECOVERY POLICY

Recovery:

```text
Detect → Classify → Root Cause → Change Strategy → Retry → Verify → Escalate
```

Do not repeat a failed strategy indefinitely.

Escalation:

```text
Cheap → Medium → Strong → Specialist → Human
```

For production failures, prefer safe stop/rollback over speculative repair.
