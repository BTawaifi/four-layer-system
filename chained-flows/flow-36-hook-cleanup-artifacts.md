# Flow 36: Hook Cleanup Artifacts

**Scenario:** Integrating a full chained flow combining domain expertise, operational constraints, state management, and the execution workflow.

## Components Used
1. **Context:** `@context-state-define-task-list`
   *Description:* Define and track a task list for multi-step processes with progress management
2. **Specialist:** `@specialist-ml-auditor`
   *Description:* Machine learning auditing expertise focusing on model integrity, reproducibility, and validation rigor
3. **Modifier:** `@modifier-conservative-mode`
   *Description:* Prioritizes proven, stable patterns and technologies over experimental approaches, emphasizing reliability and maintainability
4. **Workflow:** `@workflow-hook-cleanup-artifacts`
   *Description:* Post-action hook that identifies and proposes cleanup of temporary files, logs, and debug code

## Prompt Command
```
@context-state-define-task-list @specialist-ml-auditor @modifier-conservative-mode @workflow-hook-cleanup-artifacts
```

## Example Usage Prompt
> Please apply the `@context-state-define-task-list` rules to establish the working environment, act as a `@specialist-ml-auditor`, keep the responses `@modifier-conservative-mode`, and execute the `@workflow-hook-cleanup-artifacts` on the current module.
