# Backup provenance — proposed import

Device: Middletown MacBook
Discovery date: 2026-11-09 (America/New_York)
Repository: https://github.com/leofari/neo4j-files

## Original source locations

- `/Users/leofarina/Desktop/School/newspaper`
- `/Users/leofarina/Documents/Codex/2026-09-30/referenced-chatgpt-conversation-this-is-an/work`

## Version evidence

parking_lots.csv is byte-identical to neo4j-files/main (blob af2621e721926cc59385ecec9cea7832c9cd44e9). GitHub currently contains that one CSV; local graph.py, routing.py, main.py and data.py add routing software and local data. Sessions reference the earlier Desktop/newspaper path, now likely Desktop/School/newspaper. This establishes association, not shared Git ancestry.

## Proposed preservation

Reuse leofari/neo4j-files; preserve current remote main. Import the local software on archive/middletown-2026-11-09 initially because primary chronology is ambiguous. No automatic merge.


## Captured source identity

Existing remote main baseline `806bf5462152d5b64a06440d679d9e091da53b0b`. Primary application source was retained; unique local versions are preserved on archive branches.

Original working directories were read only. Source history is preserved where it existed and passed audit. Archive snapshots with no original Git metadata must not be treated as evidence of shared Git ancestry. Conversation transcripts are excluded.

## Initial remote verification

Initial approved main verified at `a6e32c09b45d29b1c14294dab5c2b4e808aa1f7c` on 2026-11-09. 2 preservation branches were verified. A following documentation-only commit finalizes current handoff context; consult current Git refs for its hash.
