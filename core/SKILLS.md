# SKILL SYSTEM

Skills are modular capabilities.

## Lifecycle

```text
Discover → Select → Load → Execute → Unload
```

## Skill registry fields

```yaml
skill_id:
name:
version:
capabilities:
compatible_agents:
compatible_models:
supported_project_types:
required_tools:
permission_scope:
cost:
quality_score:
success_rate:
```

Skills must not silently expand permissions.
