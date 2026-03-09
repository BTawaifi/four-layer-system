# Flow 12: Compare Code

**Scenario:** Integrating a full chained flow combining domain expertise, operational constraints, state management, and the execution workflow.

## Components Used
1. **Context:** `@context-set-ground-truth`
   *Description:* Establishes absolute source of truth files that take precedence over other information in the session
2. **Specialist:** `@specialist-database-administrator`
   *Description:* Database administration expertise focusing on schema design, query optimization, data modeling, and database performance
3. **Modifier:** `@modifier-explain-like-im-five`
   *Description:* Ensures all technical concepts are explained using simple, non-technical analogies for non-programmers
4. **Workflow:** `@workflow-compare-code`
   *Description:* Compares two versions of code and provides detailed analysis of changes and differences

## Prompt Command
```
@context-set-ground-truth @specialist-database-administrator @modifier-explain-like-im-five @workflow-compare-code
```

## Example Usage Prompt
> Please apply the `@context-set-ground-truth` rules to establish the working environment, act as a `@specialist-database-administrator`, keep the responses `@modifier-explain-like-im-five`, and execute the `@workflow-compare-code` on the current module.
