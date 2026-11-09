# Newspaper routing / Neo4j graph

Prepared 2026-11-09 from Middletown source inspection. Prepared from the approved Middletown backup plan; consult Git refs and the local verification report for publication status.

## Purpose

Model newspaper dropoffs, parking nodes and walking/driving routes.

## Architecture and entry points

Python graph/data/routing modules with CSV graph inputs and Neo4j-related preparation scripts.

## Repository and version identity

Canonical destination: https://github.com/leofari/neo4j-files (public).

Preferred source/version: /Users/leofarina/Desktop/School/newspaper.

Related GitHub project with unique local source.

parking_lots.csv is byte-identical to neo4j-files/main (blob af2621e721926cc59385ecec9cea7832c9cd44e9). GitHub currently contains that one CSV; local graph.py, routing.py, main.py and data.py add routing software and local data. Sessions reference the earlier Desktop/newspaper path, now likely Desktop/School/newspaper. This establishes association, not shared Git ancestry.

## Setup and validation

Read the selected version's README, dependency lockfiles and existing AI instructions first. Restore the declared environment; do not infer commands or credentials from another project. Consult package.json scripts, pyproject.toml or existing test documentation for exact commands. No application tests were run in this backup discovery; passing file/archive integrity checks does not establish that the application works.

Machine-specific paths must be documented as configurable inputs. Never run deployment, mail sending, application submission, vault modification, or paid API calls as a backup check.

## Current constraints and next work

Review assumptions, input-file dependencies and routing behavior. Decide later whether the software should become main after comparing the DC Mac.

Reuse leofari/neo4j-files; preserve current remote main. Import the local software on archive/middletown-2026-11-09 initially because primary chronology is ambiguous. No automatic merge.

## Private state and excluded material

Exclude bytecode/caches and review route/dropoff data for private details. Existing repository is PUBLIC: only source and public graph inputs may be uploaded there.

Conversation transcripts are stored only in the separate local history archive. Do not add them to this repository.

## Maintaining this context

After meaningful development, update this file when architecture, setup, dependencies, behavior, decisions or constraints change. Update HANDOFF.md at the end of every development session, including interrupted work. Keep facts concise and distinguish verified behavior from plans and assumptions. See AGENTS.md.
