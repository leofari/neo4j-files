# Current development handoff

Reviewed: 2026-11-09 — Middletown MacBook.

## Current state

The approved source/context backup is on https://github.com/leofari/neo4j-files (public). Start from `main`; fetch all remote branches before comparing with another Mac. Initial verified main before this documentation refresh: `a6e32c09b45d29b1c14294dab5c2b4e808aa1f7c`. Current commit: inspect `git rev-parse HEAD`.

Model newspaper dropoffs, parking nodes and walking/driving routes.

## Completed in this backup

- Preserved existing history and meaningful alternate versions without force-pushing or deleting branches.
- Added project context, source provenance and an additive AGENTS.md handoff-maintenance instruction.
- Kept Codex transcripts, credentials and private runtime data out of the upload.
- Verified source manifests and remote commit identities; application behavior was not newly regression-tested.

## Alternate versions

- `archive/middletown-2026-11-09-routing` @ `780b2ddc0ee5146c29c0b7363897faa47145282d`
- `archive/middletown-2026-11-09-parking-preparation` @ `01ae9a48ebe8099f8e0aa7a243256decf8ab4a0a`

## Next concrete step

Review assumptions, input-file dependencies and routing behavior. Decide later whether the software should become main after comparing the DC Mac.

## Constraints

Exclude bytecode/caches and review route/dropoff data for private details. Existing repository is PUBLIC: only source and public graph inputs may be uploaded there.

Original source working trees were not edited by the backup. Do not assume a working deployment or reproduce a private-data environment from the source snapshot alone.

## Update after development

Replace this current-state note with actual branch/commit, changes, checks and results, known issues, uncommitted work, decisions and next steps. Update PROJECT_CONTEXT.md when setup or architecture changes. State what remains unverified. Do not commit chat logs, credentials or unrelated personal data.
