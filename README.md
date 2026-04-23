# Global Bio-Based Fuels Research and Strategy Program

This repository is a complete, populated research and strategy system for global bio-based fuels. It covers regulatory demand, supply potential, legal asymmetries, and market-entry strategy across biodiesel, bioethanol, biomethanol, biogas/RNG, renewable diesel/HVO, and adjacent pathways.

The deliverables have been rewritten for mixed-team readability so they work for BD, compliance, operations, finance, leadership, and expert reviewers.

## Current State

This repo is **complete**. It contains:
- a full phased implementation plan (`plan/`)
- a reusable skill suite (`skills/`)
- populated source registers for 13 jurisdictions (`deliverables/01_source_register/`)
- country reference files for 13 jurisdictions (`deliverables/02_country_reference/`)
- pathway reference files for 9 biofuel pathways (`deliverables/03_biofuel_reference/`)
- market analysis files including rankings, mapping, and asymmetry comparisons (`deliverables/04_market_analysis/`)
- strategy outputs including executive summary, pathway strategies, market-entry strategies, and risk/no-go files (`deliverables/05_strategy_outputs/`)
- QA, glossary, acronyms, watchlists, and update operations (`deliverables/06_appendices/`)
- a plan review report (`deliverables/plan-review.md`)
- readability rewrite across all files for mixed-team use

## What This Repository Is For

The repository answers questions like:
- Which regulations create demand in each target market?
- Which fuels and feedstocks are eligible, capped, restricted, or conditional?
- Which buyer classes are actually pulled into the market by regulation?
- Where is supply structurally short, and where could a Southeast Asia-based producer compete?
- What certifications, proof burdens, and chain-of-custody requirements gate access?
- Where do small legal differences create outsized access, timing, or premium opportunities?
- Which opportunities should be pursued, monitored, or rejected?

## How The Repository Is Built

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
APPENDICES AND INDEXES
```

Each layer builds on the layer below it. Strategy traces back to analysis, analysis traces back to reference, and reference traces back to source.

## Repository Map

### `plan/`
The implementation specification for the whole program. 15 files covering scope, structure, phasing, templates, and QA.

### `skills/`
7 reusable local skills with 21 reference files for planning, writing, analysis, diagrams, source harvest, and QA.

### `deliverables/`
All the research and strategy outputs. See `deliverables/` for the complete deliverable set.

### `project.md`
The handoff document explaining what was built and what was learned.

## Program Structure

The repository was built as a seven-phase program:

1. Program design (done)
2. Source harvest (done)
3. Country reference build (done)
4. Biofuel reference build (done)
5. Market analysis build (done)
6. Strategy output build (done)
7. QA, consolidation, and update operations (done)

All seven phases are built and the final consistency and status-reconciliation pass is complete.

## Core Finding

**Waste-based HVO/FAME from Southeast Asia to Germany and the Netherlands is the strongest near-term opportunity.** Feedstock waste documentation and ISCC/RSB certification are the critical enablers.

## How To Start Reading

If you are new to this project:

1. Start with `deliverables/START_HERE.md`
2. Then read `deliverables/summary_report_20_page.md`
3. Then read `deliverables/05_strategy_outputs/executive_strategy_summary.md`
4. Then read `deliverables/05_strategy_outputs/se_asia_producer_opportunity_map.md`
5. Then read `deliverables/04_market_analysis/global_market_comparison.md`
6. Then read the country reference files for your market of interest
7. Then read the pathway reference files for your pathway of interest

## Status

This repository is complete as both a populated research deliverable set and a readable mixed-team decision-support system.

## Key Files

- [deliverables/START_HERE.md](deliverables/START_HERE.md)
- [deliverables/summary_report_20_page.md](deliverables/summary_report_20_page.md)
- [deliverables/05_strategy_outputs/executive_strategy_summary.md](deliverables/05_strategy_outputs/executive_strategy_summary.md)
- [deliverables/05_strategy_outputs/se_asia_producer_opportunity_map.md](deliverables/05_strategy_outputs/se_asia_producer_opportunity_map.md)
- [deliverables/04_market_analysis/global_market_comparison.md](deliverables/04_market_analysis/global_market_comparison.md)
- [deliverables/06_appendices/phase_status.md](deliverables/06_appendices/phase_status.md) — build and rewrite phase tracker
- [deliverables/06_appendices/writing_standard.md](deliverables/06_appendices/writing_standard.md) — readability standard
