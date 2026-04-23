# Phase 7: Update Operations and Maintenance

## Summary
Phase 7 turns the completed repository into a maintainable internal system. Its job is to define how the team monitors regulatory change, refreshes the evidence base, propagates updates through the layered document stack, and prevents strategy files from drifting away from the underlying rules.

The purpose of this phase is to answer the operations question: "Once the initial build is complete, how do we keep the repository current without breaking traceability, duplicating work, or letting recommendations age silently?"

Phase 7 should follow the same writing-style principles as the earlier phases:
- explain the update logic before listing procedures;
- use simple diagrams before rule-heavy sections;
- make maintenance workflows easy to follow;
- write for the team that will operate the system, not just audit it.

## What Phase 7 Must Achieve
By the end of Phase 7, the team should be able to answer:
- which markets and pathways need active monitoring;
- what kinds of regulatory or market changes trigger immediate review;
- what the refresh cadence is for high-, medium-, and lower-volatility files;
- in what order files must be updated so evidence leads strategy;
- how versioning and change logging work;
- how to issue periodic update briefs without rebuilding the entire repository.
- when a strategy recommendation must be re-labeled because buyer logic, timing, or access conditions changed.
- when a previously attractive Wave 1 asymmetry has narrowed, disappeared, or shifted to a different actor.

Phase 7 is complete only when the repository has a reusable maintenance model that preserves the evidence-first design from earlier phases.

## Build Strategy
### Operating principle
Phase 7 is an operational maintenance phase. It creates rules for updating the repository, not new substantive market conclusions.

Allowed content:
- update policy;
- watchlists;
- change-log conventions;
- versioning rules;
- refresh cadence;
- trigger-based update workflows;
- periodic briefing templates.

Not allowed content:
- silent substantive changes without change-log treatment;
- direct edits to strategy logic without upstream evidence review;
- maintenance rules that bypass the source-first workflow.

### Work order
Use three layers.

#### Layer 1: monitoring scope
- define which jurisdictions and pathways need active watch status;
- define volatility tiers;
- define trigger conditions.

#### Layer 2: update process
- define update order from source register through strategy outputs;
- define who owns each step;
- define how changes are logged and versioned.

#### Layer 3: recurring outputs
- define periodic update briefs;
- define watchlist reviews;
- define repository refresh checkpoints.

## Folder and File Outputs
### Core outputs
- `06_appendices/08_update_policy.md`
- `06_appendices/05_regulatory_watchlist.md`
- `06_appendices/06_pathway_watchlist.md`
- `06_appendices/07_change_log.md`
- `06_appendices/09_versioning_rules.md`

### Optional helper files if needed
- `06_appendices/quarterly_update_brief_template.md`
- `06_appendices/refresh_playbook.md`

These helper files should be added if the team expects formal recurring reviews or handoffs between different operators.

## Operations File Design
Each Phase 7 file should read like a maintenance playbook.

### Required structure for `08_update_policy.md`
1. Title
2. Last updated
3. Why updates matter
4. Update workflow diagram
5. Update triggers
6. Refresh cadence
7. File-update order
8. Ownership model
9. Related files

### Required structure for `05_regulatory_watchlist.md` and `06_pathway_watchlist.md`
1. Title
2. Last updated
3. How to use the watchlist
4. Tiered monitoring table
5. Trigger types
6. Priority notes
7. Related files

### Required structure for `07_change_log.md`
1. Title
2. Last updated
3. How changes are recorded
4. Version entries by date
5. Impacted folders/files
6. Whether downstream files were updated
7. Open follow-up actions

## Diagram Pattern
Every major Phase 7 file should include a compact ASCII operations diagram before detailed rules.

### Example: update propagation order
```text
SOURCE REGISTER
      ↓
COUNTRY REFERENCE
      ↓
BIOFUEL REFERENCE
      ↓
MARKET ANALYSIS
      ↓
STRATEGY OUTPUTS
      ↓
CHANGE LOG / VERSION UPDATE
```

### Example: monitoring tiers
```text
HIGH VOLATILITY
EU / US / California / UK / Japan
        ↓
QUARTERLY OR EVENT-DRIVEN REVIEW

MEDIUM VOLATILITY
Singapore / Brazil
        ↓
SEMIANNUAL OR EVENT-DRIVEN REVIEW

CONTEXT WATCH
China / Indonesia / Malaysia / Thailand
        ↓
PERIODIC REVIEW OR MATERIAL-CHANGE REVIEW
```

These diagrams should make update logic obvious before the team reads the policy details.

## Section Expectations
### Update triggers
This section should define what causes an immediate review, such as:
- new law or regulation;
- amendment affecting eligibility, caps, or buyer obligations;
- official guidance that changes interpretation;
- certification-rule changes;
- trade restrictions or fraud-enforcement changes;
- major compliance-market shifts that would alter analysis or strategy conclusions.
- changes in buyer eligibility, buyer concentration, or route access that would alter a strategy recommendation.
- changes to definitions, threshold methods, registry access, transferability, or transition windows that would alter an asymmetry-based opportunity.

### Refresh cadence
This section should define how often different parts of the repository are reviewed even when no major trigger appears.

Recommended baseline:
- high-volatility jurisdictions: quarterly plus event-driven;
- core pathway files: quarterly;
- contextual jurisdictions: semiannual or material-change review;
- strategy files: only after upstream evidence or analysis changes materially.
- strategy usefulness checklist review: at every quarterly strategy refresh.
- Wave 1 asymmetry review: at every quarterly refresh even if headline market size or demand rankings appear unchanged.

### File-update order
This is the most important process rule in Phase 7. Updates must follow the evidence-first chain:
1. source register
2. country reference
3. pathway reference
4. market analysis
5. strategy outputs
6. change log and version update

This prevents strategy drift.

### Ownership model
The policy must assign update ownership clearly:
- regional agents monitor jurisdictional changes;
- pathway and analysis agents update comparative layers;
- strategy agent updates recommendations only after upstream changes are complete;
- QA signs off before a change is considered closed.

## Agent Operating Plan for Phase 7
### Program Orchestrator Agent
Owns maintenance cadence, escalation, and release coordination.

### EU-UK Legal Research Agent
Owns monitoring and source-first updates for EU, Germany, Netherlands, France, and UK.

### Americas Legal Research Agent
Owns monitoring and source-first updates for US federal, California, and Brazil.

### APAC Legal Research Agent
Owns monitoring and source-first updates for Japan, Singapore, China, Indonesia, Malaysia, and Thailand.

### Comparative Analysis Agent
Owns updates that affect cross-market rankings or feedstock-to-market mapping.

### Strategy Architect Agent
Owns downstream strategic refreshes after upstream updates are validated.

### Citation and Evidence QA Agent
Owns update traceability and blocks downstream refreshes if upstream files are incomplete.

### Editorial Integration Agent
Owns change-log hygiene, version consistency, and maintenance-file readability.

## Workflow
```text
Trigger detected
      ↓
Watchlist review
      ↓
Source-register update
      ↓
Downstream impact check
      ↓
Country / pathway / analysis update
      ↓
Strategy impact review
      ↓
Change log entry
      ↓
Version release note
```

## Implementation Steps
### Step 1. Define watch tiers
- classify jurisdictions and pathways by volatility and strategic importance;
- record the review cadence for each.

### Step 2. Define trigger model
- list material-change events that require immediate review;
- distinguish them from routine refresh events.
- include a dedicated list of asymmetry-collapse triggers for Wave 1 markets.

### Step 3. Lock update order
- formalize the source-first propagation sequence;
- document who can update which layer and when QA is required.

### Step 4. Build maintenance artifacts
- complete update policy, watchlists, change log, and versioning rules;
- add a quarterly brief template or refresh playbook if the team needs recurring reporting.

### Step 5. Simulate one refresh cycle
- run a dry-run scenario through the documented process;
- confirm that the workflow is usable and does not skip evidence layers.
- confirm that the dry run also tests whether recommendation labels or stop conditions changed.

## Acceptance Criteria
Phase 7 is accepted only when all of the following are true:
- every market and pathway has a monitoring status or review cadence;
- update triggers are explicit;
- source-first propagation order is documented and usable;
- change logging and versioning rules are clear;
- strategy files cannot be refreshed independently of upstream evidence changes;
- strategy labels, buyer logic, and stop conditions are part of the refresh review, not optional narrative clean-up;
- Wave 1 asymmetry changes are explicitly checked during refresh rather than assumed to be captured indirectly;
- the team could run a quarterly or event-driven update cycle without redesigning the workflow.

## Important Interface and Template Additions
These conventions become mandatory in Phase 7:
- add `Last updated` to every operations file;
- add one workflow or monitoring diagram to every long operations file;
- use consistent change-log entry fields across updates;
- mark whether a change is `source only`, `analysis affecting`, or `strategy affecting`.
- mark whether a change affects buyer logic, timing, or stop conditions.

## Risks and Failure Modes
### Risk: updates happen out of order
Mitigation:
- document the evidence-first propagation chain clearly;
- let QA block downstream refreshes when upstream layers are stale.

### Risk: watchlists become stale themselves
Mitigation:
- assign explicit cadence and ownership for watchlist review.

### Risk: strategy files drift from evidence
Mitigation:
- require upstream completion before strategic refresh;
- track downstream impact explicitly in the change log.

### Risk: change logging becomes too lightweight
Mitigation:
- standardize fields and require impact notes for downstream files.

## Test Cases and Scenarios
### Scenario 1: new EU amendment
Expected:
- source register updates first;
- impacted country, pathway, analysis, and strategy files are identified in order;
- change log records the propagation.

### Scenario 2: certification-rule change
Expected:
- pathway and strategy effects are reviewed only after the relevant evidence layer is updated;
- the certifications file and affected opportunity files are flagged clearly.

### Scenario 3: contextual market update
Expected:
- a lower-volatility market can be refreshed on a lighter cadence without disrupting the whole repo;
- any downstream impact is still recorded.

### Scenario 4: quarterly review cycle
Expected:
- the team can follow the playbook without inventing new steps;
- the resulting brief or log makes clear what changed and what did not.

## Assumptions
- Phase 7 is a standing operating phase rather than a one-time deliverable.
- The repository is already fully built and hardened by the time this phase starts.
- The writing-style guide still applies because update operations must be readable by the people maintaining the system.
