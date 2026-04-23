# Source Register

## What This Folder Contains
This folder holds the legal and regulatory evidence base for the whole repository.

Each file answers one practical question:

**What are the official sources behind the market analysis and strategy in this project, and are they strong enough to trust?**

These files do not make recommendations. They log and verify the foundation that everything else is built on.

## How To Use This Folder
- Enter by jurisdiction under `eu/`, `americas/`, or `apac/`.
- Each file opens with why the market matters and a source-stack diagram.
- The metadata table is the core of each file — it lists every official source with full verification detail.
- Use the Phase 2 readiness score at the bottom to know which jurisdictions are ready for the next phase.
- Use `../06_appendices/source_gap_log.md` to track unresolved source gaps.

### In plain English
This is the folder a reviewer or new team member opens when they want to check:
- are the legal sources real,
- are they current,
- and are there gaps that should worry us?

If the sources look solid here, the country references and strategy built on top of them can be trusted.

## Wave Structure

### Wave 1 (demand-center and anchor markets)
EU level, Germany, Netherlands, France, US federal, California, UK, Japan

These markets are the commercial core of the strategy. Their source registers are the most important and the most detailed.

### Wave 2 (secondary and contextual markets)
Brazil, Singapore, China, Indonesia, Malaysia, Thailand

Wave 2 jurisdictions receive full source registration at a thinner evidence standard. They are context and benchmark markets, not the main targets.

## Most Important Files
- [eu/eu_level.md](eu/eu_level.md) — EU-level directives and regulations
- [americas/united_states_federal.md](americas/united_states_federal.md) — US federal RFS and Clean Air Act
- [americas/california.md](americas/california.md) — California LCFS
- [eu/germany.md](eu/germany.md) — German THG-Quote regime
- [apac/japan.md](apac/japan.md) — Japan transport fuel policy

## How To Read The Readiness Score
Each file ends with a Phase 2 readiness block:

- **Ready**: the sources are strong enough for the country-reference team to build on.
- **Partial**: the main laws are logged, but some gaps or translation issues remain. The team can proceed cautiously.
- **Blocked**: a key legal anchor is missing or inaccessible. The team should not build on this file until the gap is resolved.

## Upstream References
- [plan/05_phase_1_source_harvest.md](../../plan/05_phase_1_source_harvest.md) — Phase 1 plan
- [plan/04_file_templates.md](../../plan/04_file_templates.md) — canonical file templates

## Downstream Folders
- [02_country_reference/](../02_country_reference/) — jurisdiction reference files (Phase 2)
- [06_appendices/source_gap_log.md](../06_appendices/source_gap_log.md) — shared source gap log
