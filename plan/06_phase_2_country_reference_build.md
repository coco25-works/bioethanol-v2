# Phase 2: Country Reference Build

## Summary
Phase 2 converts the validated Phase 1 source baseline into jurisdiction-level reference files the team can actually use. This is the phase where raw sources become clear, structured market-reference documents, but it still stops short of comparative ranking and strategy recommendations.

Each country-reference file should answer a practical question: "How does this market work for bio-based fuels, what pathways does it reward or constrain, and what would a Southeast Asia-based producer need to understand before treating it as a target market?"

Phase 2 must follow the writing-style guide directly:
- narrative openings before tables;
- diagrams before detailed data;
- insight-rich prose instead of transcription;
- deliberate transitions between sections;
- a readable reference tone rather than a legal memo voice.

## What Phase 2 Must Achieve
By the end of Phase 2, a reader should be able to open any jurisdiction file and understand:
- the regulatory structure of the market;
- which fuels and feedstocks are in scope;
- which pathways are eligible, restricted, capped, or conditional;
- what mechanism creates demand or compliance value;
- who the obligated or incentive-driven buyers are;
- which buyer or counterparty classes matter commercially;
- what certification and traceability gates matter;
- what import, local-preference, or trade constraints matter;
- what timing rules, transition windows, or grandfathering treatment matter;
- what administrative or implementation friction affects practical access;
- who actually captures the compliance value, certificate value, or premium under the regime;
- which small legal differences should be compared against other Wave 1 markets;
- how relevant the market is to a Southeast Asia-based producer.

Phase 2 is complete only when these answers are presented clearly, consistently, and with traceability back to Phase 1 sources.

## Build Strategy
### Operating principle
Phase 2 is a structured interpretation phase. It may explain legal effect and market mechanics, but it may not yet rank markets globally or recommend final strategy plays.

Allowed content:
- synthesis of legal and official guidance sources;
- explanation of demand mechanisms;
- explanation of pathway treatment;
- explanation of certification and compliance structure;
- concise SE Asia relevance notes;
- worked examples where they clarify a market mechanism.

Not allowed content:
- global market ranking;
- commercial opportunity scoring;
- investment recommendations;
- claims unsupported by Phase 1 sources.

### Coverage order
Use the same two-wave order from Phase 1.

#### Wave 1
- EU level
- Germany
- Netherlands
- France
- US federal
- California
- UK
- Japan

#### Wave 2
- Brazil
- Singapore
- China
- Indonesia
- Malaysia
- Thailand

Only jurisdictions marked `Ready` or strong `Partial` at the end of Phase 1 should be drafted first. `Blocked` jurisdictions may get thin reference shells with explicit limitations, but not confident interpretations.

## Folder and File Outputs
### Core outputs
- `02_country_reference/README.md`
- `02_country_reference/eu/eu_level.md`
- `02_country_reference/eu/germany.md`
- `02_country_reference/eu/netherlands.md`
- `02_country_reference/eu/france.md`
- `02_country_reference/americas/united_states_federal.md`
- `02_country_reference/americas/california.md`
- `02_country_reference/americas/brazil.md`
- `02_country_reference/apac/japan.md`
- `02_country_reference/apac/singapore.md`
- `02_country_reference/apac/china.md`
- `02_country_reference/apac/indonesia.md`
- `02_country_reference/apac/malaysia.md`
- `02_country_reference/apac/thailand.md`

### Optional helper files if needed
- regional `README.md` files mirroring the source-register structure;
- one shared note in appendices for interpretive cautions if multiple markets carry translation or source-confidence limits.

## Country Reference File Design
Each jurisdiction file should read like a compact market operating manual.

### Required structure
See `04_file_templates.md` for the canonical section list. Key sections:

1. Title
2. Last updated
3. Why this market matters
4. Market architecture diagram
5. Market overview
6. In-scope fuel pathways
7. Governing regulatory framework
8. Eligible pathways
9. Restricted / capped / conditional pathways
10. Demand mechanism
11. Obligated parties / buyer classes — who must comply under the regime (legal obligation)
12. Buyer / counterparty classes — commercial actors a BD team would encounter (obligated suppliers, refiners, blenders, traders, aggregators, aviation or maritime buyers, compliance-value intermediaries)
13. Certification and chain-of-custody requirements
14. Import / trade / local-preference considerations
15. Temporal rules and transition windows
16. Implementation and administrative friction
17. Supply-side context
18. Southeast Asia relevance
19. Value-capture mechanics
20. Priority legal asymmetries for cross-market comparison
21. Commercial decision criteria
22. What would change this conclusion
23. Worked example
24. Key source references
25. Related files

### Narrative opening style
Open with why the market matters, what kind of compliance logic it uses, and how the team should read the file.

Example opening pattern:
- Paragraph 1: why the market matters globally.
- Paragraph 2: what kind of regulatory logic drives it, such as volumetric mandates, GHG-intensity systems, or tradable credits.
- Paragraph 3: what the file helps the team understand, especially from an SE Asia producer perspective.

## Diagram Pattern
Every country-reference file should include a market-architecture diagram near the top.

### Example: EU file
```text
                  EU MARKET ARCHITECTURE
┌──────────────────────────────────────────────────┐
│ EU directives and regulations                    │
│ RED / FuelEU Maritime / other EU-level rules     │
└──────────────────────────────────────────────────┘
                       ↓
┌──────────────────────────────────────────────────┐
│ Member-state implementation                      │
│ quotas / tax systems / compliance credit systems │
└──────────────────────────────────────────────────┘
                       ↓
┌──────────────────────────────────────────────────┐
│ Buyer and market effect                          │
│ obligated suppliers / port demand / premiums     │
└──────────────────────────────────────────────────┘
```

### Example: California file
```text
                CALIFORNIA LCFS MARKET LOGIC
┌───────────────────────────────────────────────┐
│ Legal framework                               │
│ LCFS regulation / CARB implementation         │
└───────────────────────────────────────────────┘
                     ↓
┌───────────────────────────────────────────────┐
│ Carbon intensity scoring                      │
│ pathway CI values / credits / deficits        │
└───────────────────────────────────────────────┘
                     ↓
┌───────────────────────────────────────────────┐
│ Buyer pull                                    │
│ obligated fuel suppliers seek low-CI fuels    │
└───────────────────────────────────────────────┘
```

## Section Expectations
### Governing regulatory framework
Explain the legal stack in prose before listing instruments. This section should make clear what type of system the market uses and how the rules relate to each other.

### Eligible pathways
Describe what the regime clearly rewards or counts toward compliance. Tie every important conclusion to Phase 1 sources.

### Restricted / capped / conditional pathways
Use this section to avoid overstatement. If a pathway is not banned but limited by caps, excluded feedstock treatment, or sustainability conditions, say so precisely.

### Demand mechanism
This is the center of the file. Explain how the market creates demand:
- blending obligation;
- quota or target;
- tradable credits;
- tax penalty;
- carbon-intensity compliance;
- maritime or aviation obligation.

### Obligated parties / buyer classes
State who must act under the regime, or who captures value from acting under it.

### Buyer / counterparty classes
State which commercial actors a BD team would likely encounter in the market:
- obligated fuel suppliers;
- refiners and blenders;
- traders and aggregators;
- aviation or maritime buyers where relevant;
- certificate-driven or compliance-value buyers.

### Certification and chain-of-custody requirements
Explain the practical gatekeepers. This section should not yet become a full certification deep dive, but it must identify what proof systems and documentation matter.

### Import / trade / local-preference considerations
Clarify whether imported material can realistically access the regime, and under what conditions.

### Temporal rules and transition windows
Capture the small timing details that can create or destroy opportunity:
- effective dates;
- phase-ins;
- transition windows;
- grandfathering;
- sunset treatment.

### Implementation and administrative friction
Explain the practical barriers that can make a nominally open market hard to access:
- registry access;
- importer registration;
- audit burden;
- documentary failure consequences;
- verifier or administrator controls.

### Supply-side context
Provide concise context on local production base, feedstock advantage, or import dependence where it matters for interpreting the market.

### Southeast Asia relevance
End the core analytical sections with a short practical lens:
- Is this a realistic target market?
- For which pathways?
- Under which constraints?

This should remain descriptive, not strategic.

### Value-capture mechanics
State who likely captures the market value created by the regime:
- producer;
- trader or aggregator;
- obligated supplier;
- credit or certificate holder;
- intermediary with documentary or registry control.

### Priority legal asymmetries for cross-market comparison
Use this section to surface the small differences that should be compared against other Wave 1 markets.

For every major asymmetry, state:
- the rule difference;
- the comparable market;
- the commercial effect;
- the proof or capability implication.

### Commercial decision criteria
List the conditions a commercial team would use to decide whether the market merits deeper pursuit:
- clear buyer pull;
- pathway access;
- proof burden;
- import openness;
- plausible fit for SE Asia-origin material.

### What would change this conclusion
State what regulatory, market, or evidence change would materially alter the market interpretation.

## Worked Example Requirement
Every major Wave 1 file should include one worked example showing how the market logic functions in practice.

Examples:
- EU: how an Annex IX pathway interacts with member-state compliance systems.
- US federal: how a pathway category leads to a RIN type and why that matters.
- California: how lower carbon intensity changes credit economics.
- UK: how development fuel treatment changes value.
- Japan: how an official threshold or mandate affects pathway fit.

The example structure:
1. Set the scenario.
2. Show the rule or classification logic.
3. Walk through the practical outcome.
4. State what the example reveals.

## Tables and Comparison Elements
Each country file may include small tables, but they should be subordinate to the prose.

Preferred tables:
- key instruments table;
- pathway treatment summary;
- buyer/compliance actor table;
- certification gate table.

Rule:
- no stacked tables without transition prose;
- no tables that merely restate headings;
- each table must support a practical reading task.

## Agent Operating Plan for Phase 2
### Program Orchestrator Agent
Owns phase sequencing, readiness gating, and escalation on blocked jurisdictions.

### Regional Legal Research Agents
Own country-reference drafting for their jurisdictions, using Phase 1 files as the exclusive evidence base unless QA approves a justified add-on source.

### Citation and Evidence QA Agent
Checks every legal claim against the source register and blocks unsupported assertions.

### Editorial Integration Agent
Checks narrative quality, diagram presence, section ordering, consistent terminology, and cross-links to Phase 1 source files.

### Market Demand Agent
Supports drafting of the demand-mechanism and buyer sections for Wave 1 files where the legal architecture is complex.

## Workflow
```text
Phase 1 source file
   ↓
Readiness review
   ↓
Country-reference draft
   ↓
Evidence trace check
   ↓
Editorial review
   ↓
Worked example check
   ↓
Wave close review
```

## Implementation Steps
### Step 1. Create folder-level navigation
- Add `README.md` in `02_country_reference/`
- Explain how these files differ from source-register files
- Explain how to move from a country file into pathway or strategy files later

### Step 2. Draft Wave 1 first
- Start with the highest-value, best-sourced markets
- Keep the same section order across files
- Include diagrams and one worked example per major file
- In every Wave 1 file, require at least one `similar regime, different outcome` asymmetry and one `nominally eligible, practically hard` issue

### Step 3. Draft Wave 2 using explicit confidence limits
- If a jurisdiction is still source-thin, say so plainly
- Avoid pretending confidence where the Phase 1 baseline remains partial

### Step 4. Run cross-file terminology review
- Standardize `eligible`, `restricted`, `capped`, and `conditional`
- Standardize pathway names across all markets
- Standardize how buyer classes are described

### Step 5. Run QA and completeness review
- confirm every major legal point resolves back to a Phase 1 source;
- confirm diagrams and worked examples are present where required;
- confirm SE Asia relevance is present but not overextended into strategy.
- confirm buyer / counterparty classes are explicit enough for downstream strategy work.
- confirm commercial decision criteria are present without turning the file into a recommendation memo.
- confirm timing rules, administrative friction, value-capture mechanics, and priority legal asymmetries are explicit in every Wave 1 file.

## Acceptance Criteria
Phase 2 is accepted only when all of the following are true:
- every target jurisdiction has a country-reference file;
- every Wave 1 file reads as a usable market reference, not just a list of sources;
- every file includes a narrative opening and a market-architecture diagram;
- every major Wave 1 file includes one worked example;
- all pathway-treatment claims trace back to Phase 1;
- all files include a concise SE Asia relevance section;
- all files include buyer / counterparty classes and commercial decision criteria;
- every Wave 1 file includes temporal rules, implementation friction, value-capture mechanics, and a priority legal asymmetry section;
- no file includes global rankings or final strategy recommendations.

## Important Interface and Template Additions
These conventions become mandatory in Phase 2:
- Add `Last updated` near the top of every country-reference file.
- Add one `Market architecture` ASCII diagram per file.
- Add one `Worked example` section in every major Wave 1 file.
- Add a `Related files` section linking back to the corresponding Phase 1 source file.
- Add `Buyer / counterparty classes`, `Commercial decision criteria`, and `What would change this conclusion` to every country-reference file.
- Add `Temporal rules and transition windows`, `Implementation and administrative friction`, `Value-capture mechanics`, and `Priority legal asymmetries for cross-market comparison` to every country-reference file.
- Use the same section ordering across jurisdictions unless a specific market has a documented reason to differ.

## Risks and Failure Modes
### Risk: files become mini legal memos
Mitigation:
- keep openings narrative and practical;
- emphasize market mechanics, not exhaustive quotation.

### Risk: files drift into strategy
Mitigation:
- keep SE Asia relevance descriptive;
- hold rankings and recommendations for later phases.

### Risk: inconsistency across jurisdictions
Mitigation:
- one shared template;
- editorial review before QA signoff;
- cross-file terminology pass.

### Risk: source-thin markets get overstated
Mitigation:
- inherit readiness limits from Phase 1;
- state uncertainty directly;
- use thinner files where needed.

## Test Cases and Scenarios
### Scenario 1: EU file
Expected:
- explains EU-level rules and member-state effect clearly;
- distinguishes Annex IX treatment from local implementation;
- includes a worked example;
- keeps strategic conclusions out.

### Scenario 2: California file
Expected:
- explains LCFS mechanics in plain language;
- identifies buyer pull via carbon-intensity logic;
- includes one practical worked example;
- cites Phase 1 legal anchors.

### Scenario 3: Japan file with translation constraints
Expected:
- explains the market carefully;
- flags confidence limits where authority is translation-dependent;
- avoids overclaiming.

### Scenario 4: Thailand or Malaysia file with lighter evidence base
Expected:
- still usable as a concise reference;
- explicit about limitations;
- no forced depth beyond evidence quality.

## Assumptions
- Phase 2 remains jurisdiction-by-jurisdiction, not comparative.
- Phase 1 is the governing evidence baseline for Phase 2 drafting.
- The writing-style guide applies fully here: diagrams before tables, narrative openings, insight after structured data, and readable transitions are required.
- Wave 1 files are expected to be materially richer than Wave 2 files at first pass.
