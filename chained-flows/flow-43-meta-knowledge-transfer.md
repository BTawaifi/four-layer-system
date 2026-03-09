# Flow 43: Meta Knowledge Transfer

**Scenario:** Integrating a full chained flow combining domain expertise, operational constraints, state management, and the execution workflow.

## Components Used
1. **Context:** `@context-filter-apply-lens`
   *Description:* Generic lens filter that applies any specialist or modifier as an ongoing perspective throughout the session
2. **Specialist:** `@specialist-data-scientist`
   *Description:* Data science expertise focusing on statistical analysis, exploratory data analysis, modeling, and data-driven insights
3. **Modifier:** `@modifier-output-format`
   *Description:* Formats all output in the specified structured format (json, csv, yaml, xml, markdown-table)
4. **Workflow:** `@workflow-meta-workflow-knowledge-transfer`
   *Description:* Facilitates cross-domain knowledge transfer by simulating collaborative problem-solving between specialists

## Prompt Command
```
@context-filter-apply-lens @specialist-data-scientist @modifier-output-format @workflow-meta-workflow-knowledge-transfer
```

## Example Usage Prompt
> Please apply the `@context-filter-apply-lens` rules to establish the working environment, act as a `@specialist-data-scientist`, keep the responses `@modifier-output-format`, and execute the `@workflow-meta-workflow-knowledge-transfer` on the current module.
