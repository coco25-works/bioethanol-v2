# Global Bio-Based Fuels Research Program

This repository is the planning and capability foundation for a global bio-based fuels reference and strategy program. It is designed to support evidence-first research on regulatory demand, supply potential, and market-entry strategy across biodiesel, bioethanol, biomethanol, biogas/RNG, renewable diesel/HVO, and adjacent pathways where policy relevance matters.

The current repository state is deliberate: it contains the execution framework, writing system, and reusable skills needed to build the research corpus, but it does not yet contain the completed country, pathway, analysis, or strategy deliverables.

## Current State

This repo currently contains:
- a full phased implementation plan
- a reusable local skill suite for planning, writing, analysis, diagrams, source harvest, and QA
- a project handoff document with learnings and next-person instructions

This repo does not yet contain:
- populated source-register files
- completed country or pathway references
- completed market-analysis outputs
- completed strategy deliverables

## What This Repository Is For

The end-state is a layered document system for a commercial and business-development audience that needs to answer questions like:
- Which regulations create demand in each target market?
- Which fuels and feedstocks are eligible, capped, restricted, or conditional?
- Which buyer classes are actually pulled into the market by regulation?
- Where is supply structurally short, and where could a Southeast Asia-based producer compete?
- What certifications, proof burdens, and chain-of-custody requirements gate access?
- Which opportunities should be pursued, monitored, or rejected?

The repository is structured so those answers are built in sequence rather than guessed downstream.

```text
SOURCE REGISTER
      ↓
COUNTRY REFERENCES
      ↓
PATHWAY REFERENCES
      ↓
MARKET ANALYSIS
      ↓
STRATEGY OUTPUTS
      ↓
QA / UPDATE OPERATIONS
```

## Repository Map

### `plan/`
The implementation specification for the whole program.

Start here:
- [plan/README.md](plan/README.md)
- [plan/00_overview.md](plan/00_overview.md)
- [plan/02_phased_execution.md](plan/02_phased_execution.md)
- [plan/05_phase_1_source_harvest.md](plan/05_phase_1_source_harvest.md)
- [plan/13_strategy_usefulness_checklist.md](plan/13_strategy_usefulness_checklist.md)

### `skills/`
Reusable local skills that support repeatable work across this project and others.

Included skills:
- `reference-planning`
- `reference-writing-style`
- `strategy-writing`
- `diagram-drawing`
- `source-harvest`
- `market-analysis`
- `evidence-traceability-qa`

### `project.md`
The detailed handoff document. It explains what has already been built, what was learned while shaping the system, what the next person should read first, and what should be executed next.

## Program Structure

The repository is planned as a seven-phase build:

1. Program design
2. Source harvest
3. Country reference build
4. Biofuel reference build
5. Market analysis build
6. Strategy output build
7. QA, consolidation, and update operations

The operating rule is strict:
- evidence first
- analysis second
- strategy last

That sequencing is what keeps strategy outputs useful instead of speculative.

## Guiding Principles

- Use primary law first for legal meaning.
- Use official guidance for implementation detail.
- Use official data first for market facts and compliance context.
- Separate legal fact, agency interpretation, market observation, and strategy inference.
- Use `eligible`, `restricted`, `capped`, and `conditional` instead of collapsing everything into `allowed` or `banned`.
- Make buyer logic, decision criteria, disqualifiers, and stop conditions explicit before making recommendations.
- Treat diagrams as part of the information system, not decoration.
- Keep every recommendation traceable back to analysis, references, and sources.

## How To Start

If you are picking this repository up for execution, use this reading order:

1. [project.md](project.md)
2. [plan/README.md](plan/README.md)
3. [plan/00_overview.md](plan/00_overview.md)
4. [plan/02_phased_execution.md](plan/02_phased_execution.md)
5. [plan/04_file_templates.md](plan/04_file_templates.md)
6. [plan/12_plan_review_matrix.md](plan/12_plan_review_matrix.md)
7. [plan/13_strategy_usefulness_checklist.md](plan/13_strategy_usefulness_checklist.md)

Then begin actual execution in this order:

1. Create the target content folders and file shells defined in the repository structure plan.
2. Execute Phase 1 source harvest before drafting references.
3. Build country and pathway references only after the source register is materially complete.
4. Build market analysis on top of validated references.
5. Build strategy outputs only after the analysis layer is ready.

## Skill Suite

The local skills are part of the operating model for this repo.

Use them like this:
- `reference-planning` for structure, phasing, and file decomposition
- `reference-writing-style` for readable reference, analysis, and strategy prose
- `strategy-writing` for recommendation logic, buyer logic, and no-go framing
- `diagram-drawing` for one-off diagrams and connected diagram series
- `source-harvest` for authority-first source logging and gap handling
- `market-analysis` for comparison logic, ranking, and disqualifier framing
- `evidence-traceability-qa` for traceability checks, consistency review, and maintenance discipline

## Immediate Next Deliverables

The next real outputs to create are:
- `01_source_register/README.md`
- one source-register file per target jurisdiction
- `06_appendices/source_gap_log.md`

Until those exist, this repo should be understood as ready for execution, not as completed research.

## Why The Strategy Layer Matters

This project is not just a legal-reference exercise. The planning system has been strengthened so the eventual strategy outputs are commercially useful, not just technically correct.

That means the final strategy layer is expected to include:
- buyer and counterparty logic
- timing and `Why now`
- market-pathway prioritization
- gating requirements
- better alternatives
- disqualifier logic
- stop conditions
- evidence confidence

The key checkpoint for that is [plan/13_strategy_usefulness_checklist.md](plan/13_strategy_usefulness_checklist.md).

## Key Files

- [project.md](project.md)
- [plan/README.md](plan/README.md)
- [plan/05_phase_1_source_harvest.md](plan/05_phase_1_source_harvest.md)
- [plan/09_phase_5_strategy_output_build.md](plan/09_phase_5_strategy_output_build.md)
- [plan/13_strategy_usefulness_checklist.md](plan/13_strategy_usefulness_checklist.md)

## Status

This repository is complete as a planning and capability foundation.

It is not yet complete as a populated research and strategy deliverable set.
