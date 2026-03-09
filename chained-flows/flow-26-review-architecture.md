# Flow 26: Review Architecture

**Scenario:** Integrating a full chained flow combining domain expertise, operational constraints, state management, and the execution workflow.

## Components Used
1. **Context:** `@context-state-set-primary-goal`
   *Description:* Establishes the primary goal for the entire session and ensures all suggestions align with achieving that objective
2. **Specialist:** `@specialist-aws-architect`
   *Description:* AWS cloud architecture expertise focusing on scalable, secure, and cost-optimized AWS solutions
3. **Modifier:** `@modifier-backward-compatible`
   *Description:* Ensures all code changes maintain full backward compatibility with existing API, function signatures, and observable behavior
4. **Workflow:** `@workflow-review-architecture`
   *Description:* Architectural review workflow that evaluates design quality, scalability, maintainability, and security

## Prompt Command
```
@context-state-set-primary-goal @specialist-aws-architect @modifier-backward-compatible @workflow-review-architecture
```

## Example Usage Prompt
> Please apply the `@context-state-set-primary-goal` rules to establish the working environment, act as a `@specialist-aws-architect`, keep the responses `@modifier-backward-compatible`, and execute the `@workflow-review-architecture` on the current module.
