# Flow 42: Generate Documentation

**Scenario:** Integrating a full chained flow combining domain expertise, operational constraints, state management, and the execution workflow.

## Components Used
1. **Context:** `@context-progressive-context-loader`
   *Description:* Context for intelligent loading and management of large information contexts across Cursor IDE sessions
2. **Specialist:** `@specialist-qa-tester`
   *Description:* Meticulous quality assurance perspective focusing on bug detection, edge cases, and adversarial testing
3. **Modifier:** `@modifier-assume-best-practices`
   *Description:* Ensures AI assumes modern, best-practice environment with latest stable features, strict linting, and security/performance prioritization
4. **Workflow:** `@workflow-generate-documentation`
   *Description:* Generates technical documentation from source code in various formats including JSDoc, README, and OpenAPI specs

## Prompt Command
```
@context-progressive-context-loader @specialist-qa-tester @modifier-assume-best-practices @workflow-generate-documentation
```

## Example Usage Prompt
> Please apply the `@context-progressive-context-loader` rules to establish the working environment, act as a `@specialist-qa-tester`, keep the responses `@modifier-assume-best-practices`, and execute the `@workflow-generate-documentation` on the current module.
