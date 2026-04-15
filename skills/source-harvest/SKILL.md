---
name: source-harvest
description: Build evidence-first source registers for regulatory and market-reference projects. Use when Codex needs to collect primary law, official guidance, official data, and secondary context into jurisdiction files with source metadata, status flags, authority levels, translation cautions, readiness scoring, and gap logs.
---

# Source Harvest

Use this skill when the output is a source register or evidence log, not an interpretation memo.

## Workflow
1. Find the highest-authority sources first.
2. Classify each source by authority type.
3. Capture consistent metadata.
4. Flag translation and supersession risks.
5. Log open gaps instead of guessing.
6. Record readiness for the next phase.

## Core Rules
- Primary law first.
- Guidance explains implementation but does not override statute.
- Official data is for targets, quotas, and program facts.
- Secondary context should never carry core legal meaning.

## Use These References
- Read [references/source-metadata-schema.md](references/source-metadata-schema.md) for required fields.
- Read [references/authority-hierarchy.md](references/authority-hierarchy.md) for source classification.
- Read [references/gap-log-patterns.md](references/gap-log-patterns.md) for missing-source handling.

## Output Expectations
- Produce source files another agent can safely use.
- Surface uncertainty early.
- Do not drift into recommendation language.
