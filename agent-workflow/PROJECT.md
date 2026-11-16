# Project profile template

Replace placeholders with facts observed in the target repository. Keep this profile small; link detailed subsystem guidance and verify it when used.

Create the actual profile at `agent-workflow/PROJECT.md` when the root `AGENTS.md` requests onboarding. Mark unresolved facts as unknown with the source or decision needed; do not leave template placeholders as if setup were complete. Update an existing local profile selectively instead of discarding valid project-specific instructions.

## Identity and boundaries

- Project/workspace: REPLACE
- Repository identity evidence (manifest names, entry paths, or other stable local identifiers): REPLACE
- Profile status and last source verification date: REPLACE
- Relevant repository roots and subsystem owners: REPLACE
- Runtime/toolchain constraints, with source files: REPLACE
- Applicable local policy and required review: REPLACE
- Commands that mutate production/shared resources: REPLACE

## Source and command map

| Purpose | Source or exact command | Working directory | Side effects | Required for |
|---|---|---|---|---|
| Application entry | REPLACE | REPLACE | REPLACE | REPLACE |
| Focused test | REPLACE | REPLACE | REPLACE | REPLACE |
| Integration test | REPLACE | REPLACE | REPLACE | REPLACE |
| Required final gates | REPLACE | REPLACE | REPLACE | REPLACE |
| Lint/type/build | REPLACE | REPLACE | REPLACE | REPLACE |
| Local run | REPLACE | REPLACE | REPLACE | REPLACE |

Do not infer commands from another project's stack. Mark commands as defined, executed, or environment-blocked accurately.

## Invariants worth preserving

List only consequential constraints that are not obvious from the immediate code. For each, record the authoritative source and when it must be rechecked. Examples might concern tenancy, backward compatibility, units, localization, deployment order, or state transitions; they are not universally required.

## Task state and evidence

- Ignored task directory: REPLACE
- Evidence retention/sharing policy: REPLACE
- Concurrent writer ownership: REPLACE
- Mandatory CI/release gates and whether reuse is allowed: REPLACE
- Known coverage gaps: REPLACE

## Instruction reconciliation

Document any authorized replacement of older process rules. Preserve engineering requirements and current user constraints. Record the last source verification date and relevant invalidation triggers.
