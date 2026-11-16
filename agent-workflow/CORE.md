# Agent workflow reference

This handbook is optional guidance for complex work, within the host's instruction hierarchy and the user's current authorization. It does not add approval gates or require a task-record format.

- Establish the requested outcome from the conversation and current source. Infer routine implementation details; ask when a missing decision materially affects correctness, scope, or authorization.
- Read what the task needs, including relevant callers and tests. Verify uncertain facts and distinguish observations from assumptions. Historical test and release results need current verification when relied on.
- Preserve unrelated work and make a coherent, maintainable change. Complete the authorized task rather than stopping at a proposal or first implementation.
- Use available tools economically. Batch independent reads, keep dependent actions sequential, and inspect failures and truncated output. Use one agent unless delegation is authorized.
- Run checks that establish the requested behavior and applicable project gates. Repeat them when relevant inputs change or new concerns warrant it. Report what passed and any material gaps.
- For interruption-prone work, retain a concise checkpoint of scope, changes, evidence, and next steps. Routine tasks need no persisted workflow records.

## Optional references

> The lite version ships without the modules below; they are part of the full kit (see README).

Use [PROJECT.md](PROJECT.md) for local commands and constraints. Consult a module when its detail helps:

| Need | Reference |
|---|---|
| Context recovery or large outputs | [Context](modules/context.md) |
| Complex implementation or debugging | [Execution](modules/execution.md) |
| Verification strategy | [Verification](modules/verification.md) |
| Authorized delegation | [Delegation](modules/delegation.md) |
| Usage or efficiency investigation | [Measurement](modules/measurement.md) |
| Incident, UI, migration, refactor, or research procedures | [Workflow adaptations](modules/workflows.md) |
| Explicit workflow installation or adaptation | [Adoption](modules/adoption.md) |

Modules and templates are supporting material, not mandatory startup steps. Apply only the parts relevant to the task; their procedures do not create additional permission requirements. Run the handbook validator when modifying the package's structure or templates, not as an application completion gate.
