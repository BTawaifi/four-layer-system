# Flow 47: Hook Cleanup Artifacts

**Scenario:** Integrating a full chained flow combining domain expertise, operational constraints, state management, and the execution workflow.

## Components Used
1. **Context:** `@context-state-set-primary-goal`
   *Description:* Establishes the primary goal for the entire session and ensures all suggestions align with achieving that objective
2. **Specialist:** `@specialist-gcp-architect`
   *Description:* Google Cloud Platform architecture specialist focusing on GCP services, Kubernetes, and cloud-native solutions
3. **Modifier:** `@modifier-no-new-dependencies`
   *Description:* Ensures solutions use only existing dependencies and standard library, prohibiting introduction of new third-party packages
4. **Workflow:** `@workflow-hook-cleanup-artifacts`
   *Description:* Post-action hook that identifies and proposes cleanup of temporary files, logs, and debug code

## Prompt Command
```
@context-state-set-primary-goal @specialist-gcp-architect @modifier-no-new-dependencies @workflow-hook-cleanup-artifacts
```

## Example Usage Prompt
> Please apply the `@context-state-set-primary-goal` rules to establish the working environment, act as a `@specialist-gcp-architect`, keep the responses `@modifier-no-new-dependencies`, and execute the `@workflow-hook-cleanup-artifacts` on the current module.
