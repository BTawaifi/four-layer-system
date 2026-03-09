# Flow 46: Api Development

**Scenario:** Integrating a full chained flow combining domain expertise, operational constraints, state management, and the execution workflow.

## Components Used
1. **Context:** `@context-set-ground-truth`
   *Description:* Establishes absolute source of truth files that take precedence over other information in the session
2. **Specialist:** `@specialist-ml-auditor`
   *Description:* Machine learning auditing expertise focusing on model integrity, reproducibility, and validation rigor
3. **Modifier:** `@modifier-concise-output`
   *Description:* Ensures responses are as concise as possible, omitting conversational filler and unnecessary explanations
4. **Workflow:** `@workflow-api-development`
   *Description:* Comprehensive API development workflow covering design, implementation, documentation, and testing of REST and GraphQL APIs

## Prompt Command
```
@context-set-ground-truth @specialist-ml-auditor @modifier-concise-output @workflow-api-development
```

## Example Usage Prompt
> Please apply the `@context-set-ground-truth` rules to establish the working environment, act as a `@specialist-ml-auditor`, keep the responses `@modifier-concise-output`, and execute the `@workflow-api-development` on the current module.
