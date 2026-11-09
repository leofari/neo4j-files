# Newspaper routing / Neo4j graph

Last reviewed: 2026-11-09, Middletown MacBook.

## Purpose

Model newspaper dropoffs, parking nodes and walking/driving routes.

## Architecture

Python graph/data/routing modules with CSV graph inputs and Neo4j-related preparation scripts.

## Canonical repository and backup state

https://github.com/leofari/neo4j-files — **public**. Reuse this repository; do not create another copy on the second Mac. Primary branch: `main`.

The approved Middletown source/context backup was pushed and verified. Its initial verified primary tip before this documentation refresh was `a6e32c09b45d29b1c14294dab5c2b4e808aa1f7c`. Use `git rev-parse HEAD` for the current tip. Existing Git history and remote branches were preserved.

## Version evidence

parking_lots.csv is byte-identical to neo4j-files/main (blob af2621e721926cc59385ecec9cea7832c9cd44e9). GitHub currently contains that one CSV; local graph.py, routing.py, main.py and data.py add routing software and local data. Sessions reference the earlier Desktop/newspaper path, now likely Desktop/School/newspaper. This establishes association, not shared Git ancestry.

## Preserved alternate versions

- `archive/middletown-2026-11-09-routing` @ `780b2ddc0ee5146c29c0b7363897faa47145282d`
- `archive/middletown-2026-11-09-parking-preparation` @ `01ae9a48ebe8099f8e0aa7a243256decf8ab4a0a`

Archive branches preserve historical/alternate states and are not automatically merged. Non-Git snapshot roots do not imply shared chronological Git ancestry. Before developing on another Mac, fetch all branches and inspect the archive provenance and manifests.

## Setup and checks

Read README.md, existing AI instructions, dependency declarations and lockfiles before installing or running. Exact package scripts inspected during discovery appear below where available. Machine-specific paths in the original scripts are known portability constraints, not a guarantee that those paths exist on another Mac. Do not replace private data/credentials with guesses.

Backup checks verified Git ancestry, remote branch hashes, captured source-file bytes, source exclusions, and secret-scan findings. Application regression/integration tests were not run during backup. The sanitized quote-builder JavaScript/Python passed syntax checks. No application submission, mail sending, deployment or vault modification was performed as a backup test.

## Next development step

Review assumptions, input-file dependencies and routing behavior. Decide later whether the software should become main after comparing the DC Mac.

## Private state and deliberate exclusions

Exclude bytecode/caches and review route/dropoff data for private details. Existing repository is PUBLIC: only source and public graph inputs may be uploaded there.

Complete Codex transcripts stay in the separate local history ZIP and must never enter this repository. Original private inputs remain on the source Mac. The eight unconfirmed coursework/tutorial candidates are outside this approved backup set.

## Handoff maintenance

At the start of development, read PROJECT_CONTEXT.md, HANDOFF.md and AGENTS.md plus applicable nested instructions. After each meaningful session, update HANDOFF.md with actual branch/commit, changes, checks/results, outstanding issues, uncommitted work and next steps. Update this context when architecture, setup, dependencies, data contracts or decisions change. Keep existing README/CLAUDE.md/progress documents consistent. Do not paste transcripts or credentials.
