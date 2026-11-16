# <Project name>

## Relevant references

Use [agent-workflow/PROJECT.md](agent-workflow/PROJECT.md) for architecture, commands, and constraints. Read relevant sections and verify dated facts against current source. Correct affected stale entries without a separate onboarding phase.

The [workflow core](agent-workflow/CORE.md) is an optional reference for complex work, recovery, or an explicitly requested workflow. Load only what helps; routine tasks need no workflow records or handbook validation.

## Engineering and verification

<Two or three sentences: invariants agents must preserve, the canonical schema or config, and the package manager.>

<Which targeted checks to run while iterating, and the broad gate to run before committing.>

## Operations

<Where deployment, backup and rollback runbooks live. Never commit secrets, databases or uploads.>
