# Phase 6: Final QA and Consolidation

## Summary
Phase 6 hardens the full repository into a trusted internal reference system. By this point the source, country, pathway, market-analysis, and strategy layers already exist. Phase 6 ensures they agree with each other, link correctly, use consistent terminology, and surface unresolved uncertainty instead of hiding it.

The purpose of this phase is to answer the trust question: "Can the team rely on this repository as a coherent decision-support system, or does it still behave like a collection of good but loosely connected drafts?"

Phase 6 must follow the writing-style guide even though it is a QA phase:
- explain what each appendix or README does before listing assets;
- use simple navigation diagrams before dense indexes;
- make caveats visible and readable;
- keep the tone practical, not bureaucratic.

## What Phase 6 Must Achieve
By the end of Phase 6, the team should be able to confirm:
- every file can be reached from a sensible entry path;
- every major claim is traceable to the prior phase below it;
- terminology is stable across the repository;
- unresolved source gaps or interpretive cautions are visible;
- recommendation labels and pathway terms mean the same thing everywhere;
- strategy files answer buyer, timing, gating, and stop-condition questions clearly and consistently;
- Wave 1 files make the material legal asymmetries visible rather than burying them inside general market summaries;
- glossary and acronym support are sufficient for a new internal reader.

Phase 6 is complete only when the repository behaves like one integrated system rather than multiple parallel workstreams.

## Build Strategy
### Operating principle
Phase 6 is a hardening phase. It does not create new market conclusions or strategy ideas. It validates, normalizes, and consolidates what already exists.

Allowed content:
- glossary and acronym build-out;
- citation indexing;
- cross-link cleanup;
- terminology normalization;
- appendix consolidation;
- interpretive caution notes;
- QA checklist and signoff artifacts.

Not allowed content:
- new unsupported claims;
- silent rewriting of analytical conclusions;
- new opportunity recommendations that bypass prior phases;
- hiding unresolved issues for the sake of polish.

### Work order
Use three passes in order.

#### Pass 1: traceability and evidence integrity
- verify linkages from strategy to analysis to pathway/country to source;
- confirm unresolved gaps are logged;
- confirm no unsupported claims remain.

#### Pass 2: navigation and usability
- finalize folder `README` files;
- ensure entry by market, pathway, or strategy question works cleanly;
- standardize related-file sections and appendix references.

#### Pass 3: terminology and presentation consistency
- normalize pathway names, jurisdiction names, and rating labels;
- finalize glossary and acronyms;
- check diagram presence and placement.

## Folder and File Outputs
### Core outputs
- `06_appendices/glossary.md`
- `06_appendices/acronyms.md`
- `06_appendices/legal_citation_index.md`
- `06_appendices/source_gap_log.md`
- `06_appendices/final_qa_checklist.md`

### Optional helper files if needed
- `06_appendices/interpretive_cautions.md`
- `06_appendices/navigation_map.md`

These optional files should be added if translation issues, authority conflicts, or repo-scale navigation complexity remain significant.

## Appendix and QA File Design
Each Phase 6 file should read like an operational support document for the whole repository.

### Required structure for `final_qa_checklist.md`
1. Title
2. Last updated
3. Purpose of the QA pass
4. Repository navigation diagram
5. Traceability checks
6. Consistency checks
7. Appendix completeness checks
8. Open issues
9. Signoff status
10. Related files

### Required structure for `legal_citation_index.md`
1. Title
2. Last updated
3. How to use this index
4. Jurisdiction-by-jurisdiction citation map
5. Cross-links to source-register files
6. Notes on translations or unofficial text where relevant
7. Related files

### Required structure for `glossary.md` and `acronyms.md`
1. Title
2. Last updated
3. How to use this file
4. Alphabetized entries
5. Cross-links to the main files where the term is especially important

## Diagram Pattern
Every major Phase 6 file should include a compact ASCII orientation diagram before long indexes or checklists.

### Example: repository navigation
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
APPENDICES AND INDEXES
```

### Example: traceability ladder
```text
STRATEGY CLAIM
     ↓
ANALYSIS SUPPORT
     ↓
PATHWAY / COUNTRY SUPPORT
     ↓
PRIMARY SOURCE TRAIL
```

These diagrams are there to make QA logic readable, not decorative.

## Section Expectations
### Traceability checks
This is the most important QA section. It should verify that:
- strategy claims map to analysis outputs;
- analysis claims map to country and pathway references;
- country and pathway claims map to source-register entries.

### Consistency checks
This section should verify:
- pathway naming consistency;
- jurisdiction naming consistency;
- recommendation-label consistency;
- rating vocabulary consistency;
- section-order consistency where templates require it.
- strategy usefulness checklist compliance.
- asymmetry vocabulary consistency across source, country, pathway, analysis, and strategy layers.

### Appendix completeness checks
This section should verify that every support document needed by a new reader actually exists and is discoverable.

### Open issues
If anything remains unresolved, list it explicitly. Phase 6 should reduce hidden ambiguity, not bury it.

## Agent Operating Plan for Phase 6
### Program Orchestrator Agent
Owns the closeout sequence, issue triage, and final readiness decision.

### Citation and Evidence QA Agent
Owns traceability validation and unsupported-claim blocking.

### Editorial Integration Agent
Owns navigation, terminology consistency, related-file sections, and appendix readability.

### Comparative Analysis Agent
Checks consistency between Phase 4 ranking language and Phase 5 recommendation language.

### Strategy Architect Agent
Checks that the strategy layer remains aligned with the final evidence and analysis set.

It must also confirm that the strategy layer remains commercially useful for BD readers rather than merely internally consistent.

### Regional Legal Research Agents
Support only where unresolved source conflicts, citation issues, or translation cautions still need expert review.

## Workflow
```text
All prior-phase files
        ↓
Traceability review
        ↓
Navigation review
        ↓
Terminology review
        ↓
Appendix consolidation
        ↓
Open-issue log
        ↓
Final QA signoff
```

## Implementation Steps
### Step 1. Finalize navigation layer
- add or refine top-level and folder `README` files;
- ensure file descriptions are accurate;
- verify cross-links across folders.

### Step 2. Run traceability review
- sample and then sweep strategy-to-source chains;
- confirm all evidence-base sections point to the right upstream files;
- surface any broken chains in the QA checklist.
- run the strategy usefulness checklist against the whole Phase 5 folder.
- run an asymmetry trace check for the Wave 1 markets so each highlighted delta resolves back to source and reference layers.

### Step 3. Normalize terminology
- lock the canonical spelling and naming for pathways, markets, acronyms, and labels;
- reflect that vocabulary in the glossary and acronyms files.

### Step 4. Consolidate appendices
- complete glossary, acronyms, citation index, and source-gap log;
- add interpretive cautions if unresolved source-confidence issues remain material.

### Step 5. Record signoff state
- mark what is complete;
- mark what remains partial;
- make the repository readiness status explicit.

## Acceptance Criteria
Phase 6 is accepted only when all of the following are true:
- every major folder has usable navigation support;
- glossary, acronyms, citation index, and source-gap log exist and are readable;
- every required traceability chain works;
- recommendation and rating vocabularies are consistent;
- the strategy usefulness checklist passes or any failures are explicitly logged;
- every Wave 1 market and pathway set shows at least one material asymmetry, one practical access friction, and one evidence-backed commercial effect;
- unresolved issues are listed explicitly rather than hidden;
- the repo can be entered by market, pathway, or strategy question without confusion.

## Important Interface and Template Additions
These conventions become mandatory in Phase 6:
- add `Last updated` to every appendix file;
- add one orientation diagram to every long appendix or QA file;
- standardize the format of `Related files` sections across the repository;
- make unresolved confidence or translation issues visible in appendices rather than buried in prose.
- add a cross-reference to the strategy usefulness checklist from the final QA checklist.
- add an asymmetry-check section to the final QA checklist for Wave 1 markets.

## Risks and Failure Modes
### Risk: QA becomes a cosmetic pass
Mitigation:
- prioritize traceability and contradiction checks ahead of formatting or polish.

### Risk: unresolved issues get silently dropped
Mitigation:
- maintain explicit open-issue sections and interpretive caution notes.

### Risk: appendix files become unreadable indexes
Mitigation:
- use diagrams, short openings, and section prose before dense lists.

### Risk: inconsistent labels survive into signoff
Mitigation:
- run a dedicated terminology pass across Phase 4 and Phase 5 outputs.

## Test Cases and Scenarios
### Scenario 1: strategy claim trace
Expected:
- a recommendation in Phase 5 can be followed back through Phase 4, Phase 3 or 2, and Phase 1 without ambiguity.

### Scenario 2: new reader navigation
Expected:
- a reader entering from a country question, pathway question, or strategy question can find the right file chain quickly.

### Scenario 3: translation caution
Expected:
- a market with translation-dependent authority is clearly flagged in appendices and not treated as fully settled.

### Scenario 4: inconsistent label detection
Expected:
- conflicting use of a rating or priority label is caught and normalized before signoff.

## Assumptions
- Phase 6 is a hardening phase, not a new research phase.
- The full repository already exists by the time this phase starts.
- The writing-style guide still applies to appendices and QA artifacts because readability remains part of quality.
