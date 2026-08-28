# RELEASE POLICY

Build once and promote the same artifact where feasible.

Release record:

```yaml
release_id:
artifact_id:
commit_sha:
source_environment:
target_environment:
test_results:
security_results:
approval:
deployment_status:
rollback_plan:
```

Production releases require an explicit rollback strategy.
