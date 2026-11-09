# Development handoff — Newspaper routing / Neo4j graph

Last reviewed: 2026-11-09, Middletown MacBook.

## Starting point

/Users/leofarina/Desktop/School/newspaper

Status: Related GitHub project with unique local source. The backup plan was approved on 2026-11-09. This file describes the staged version; Git refs and the external verification report establish publication status.

## What is known

parking_lots.csv is byte-identical to neo4j-files/main (blob af2621e721926cc59385ecec9cea7832c9cd44e9). GitHub currently contains that one CSV; local graph.py, routing.py, main.py and data.py add routing software and local data. Sessions reference the earlier Desktop/newspaper path, now likely Desktop/School/newspaper. This establishes association, not shared Git ancestry.

## Verification

File hashes and selected version differences inspected. Application tests: not run during backup discovery. Remote histories must be fetched and audited again immediately before any push.

## Next action

Review assumptions, input-file dependencies and routing behavior. Decide later whether the software should become main after comparing the DC Mac.

## Preservation

Reuse leofari/neo4j-files; preserve current remote main. Import the local software on archive/middletown-2026-11-09 initially because primary chronology is ambiguous. No automatic merge.

## After the next development session

Replace this current-state note with the actual branch/commit, concise changes, checks run and results, remaining defects, uncommitted work, decisions and next steps. Record limitations honestly. Update PROJECT_CONTEXT.md and existing project progress docs where relevant. Do not paste chat logs, credentials, job records or personal source documents.
