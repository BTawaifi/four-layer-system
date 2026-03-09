# Flow 7: Rename Files For Consistency

**Scenario:** Integrating a full chained flow combining domain expertise, operational constraints, state management, and the execution workflow.

## Components Used
1. **Context:** `@context-workflow-progress-tracker`
   *Description:* Comprehensive workflow progress tracking system combining initialization, commands, and usage patterns
2. **Specialist:** `@specialist-postgresql-admin`
   *Description:* PostgreSQL database administration expertise focusing on performance tuning, high availability, and data integrity
3. **Modifier:** `@modifier-output-format`
   *Description:* Formats all output in the specified structured format (json, csv, yaml, xml, markdown-table)
4. **Workflow:** `@workflow-rename-files-for-consistency`
   *Description:* Renames files for consistency and updates all code references to use the new filenames

## Prompt Command
```
@context-workflow-progress-tracker @specialist-postgresql-admin @modifier-output-format @workflow-rename-files-for-consistency
```

## Example Usage Prompt
> Please apply the `@context-workflow-progress-tracker` rules to establish the working environment, act as a `@specialist-postgresql-admin`, keep the responses `@modifier-output-format`, and execute the `@workflow-rename-files-for-consistency` on the current module.
