# Phase 4: Market Analysis Build

## Summary
Phase 4 converts the validated country and pathway reference layers into comparative market analysis. This is the first phase where the program explicitly compares markets, ranks pathway relevance, and maps supply potential against regulation-linked demand.

The purpose of this phase is to answer the portfolio question: "Across the major global markets, where is real demand created by regulation, which pathways attract the strongest pull, where are supply shortages or import openings likely to exist, and how does Southeast Asia fit into that global picture?"

Phase 4 must follow the writing-style guide as a hard standard:
- open with what the analysis is trying to show and why it matters;
- use diagrams before dense tables or matrices;
- explain analytical logic before presenting rankings;
- use prose to interpret patterns, not just display them;
- keep outputs readable for commercial and strategy users without losing evidentiary discipline.

## What Phase 4 Must Achieve
By the end of Phase 4, the team should be able to answer:
- which markets create the strongest regulation-linked demand by pathway;
- which mechanisms drive value, such as mandates, credits, quotas, or carbon-intensity systems;
- which pathways are advantaged, capped, or structurally disadvantaged in each major market;
- where domestic supply is likely insufficient or constrained;
- where imports or external advanced feedstocks are likely to matter;
- how Southeast Asia-origin pathways map onto those demand centers;
- which small legal differences create outsized opportunity or disqualifier effects across otherwise similar markets;
- which opportunities are created by timing windows, proof recognition, administrative design, or value-capture asymmetry rather than headline demand size;
- which markets deserve priority attention in the final strategy phase.
- which combinations should be disqualified even if top-line demand looks strong.

Phase 4 is complete only when these answers are expressed through a consistent analytical framework and every conclusion can be traced back to Phase 2 and Phase 3 files.

## Build Strategy
### Operating principle
Phase 4 is a comparative analysis phase. It may rank, compare, and interpret market opportunity structure, but it must stop short of prescribing specific go-to-market actions or partnership models. Those belong in Phase 5.

Allowed content:
- comparative demand analysis across markets;
- supply-potential analysis by region and pathway;
- market ranking logic;
- feedstock-to-market mapping;
- identification of high-priority and lower-priority market types;
- analytical interpretation of where Southeast Asia-origin supply is likely to fit.

Not allowed content:
- named counterparty recommendations;
- final entry-model decisions;
- investment sequencing recommendations;
- unsupported scoring that is not grounded in Phase 2 and Phase 3 evidence.

### Coverage order
Use two waves aligned to decision value.

#### Wave 1: highest-value comparative outputs
- global market comparison
- demand mechanisms by market
- supply potential by region
- feedstock-to-market mapping
- high-priority opportunity ranking

#### Wave 2: focused market analyses
- EU demand analysis
- US demand analysis
- UK demand analysis
- Japan demand analysis
- Southeast Asia supply-base analysis

Wave 1 should be completed first because it creates the core analytical model that the focused market files and Phase 5 strategy files will rely on.

## Folder and File Outputs
### Core outputs
- `04_market_analysis/README.md`
- `04_market_analysis/global_market_comparison.md`
- `04_market_analysis/demand_mechanisms_by_market.md`
- `04_market_analysis/supply_potential_by_region.md`
- `04_market_analysis/feedstock_to_market_mapping.md`
- `04_market_analysis/regulatory_asymmetry_matrix.md`
- `04_market_analysis/high_priority_opportunity_ranking.md`
- `04_market_analysis/wave_1_micro_opportunity_log.md`
- `04_market_analysis/eu_demand_analysis.md`
- `04_market_analysis/us_demand_analysis.md`
- `04_market_analysis/uk_demand_analysis.md`
- `04_market_analysis/japan_demand_analysis.md`
- `04_market_analysis/southeast_asia_supply_base.md`

### Optional helper files if needed
- one methodology file explaining the ranking framework if the main outputs become too dense;
- one assumptions log if scoring inputs or analytical thresholds need explicit documentation.

## Market Analysis File Design
Each analysis file should read like a decision-support document, not a data dump.

### Required structure
1. Title
2. Last updated
3. Analytical question
4. Analytical framework diagram
5. Market comparison view
6. Regulatory asymmetry view
7. Key findings
8. Demand-side implications
9. Supply-side implications
10. Southeast Asia producer implications
11. Commercial attractiveness dimensions
12. Disqualifier conditions
13. Worked example or scenario
14. Supporting references
15. Related files

### Narrative opening style
Open with the decision problem, what the comparison is measuring, and how the reader should interpret the output.

Example opening pattern:
- Paragraph 1: what market question this file is answering.
- Paragraph 2: which dimensions matter most, such as regulatory pull, pathway fit, proof burden, or import openness.
- Paragraph 3: what the file helps the team compare and what it does not yet decide.

## Diagram Pattern
Every market-analysis file should include an ASCII analysis diagram near the top.

### Example: overall market comparison
```text
         GLOBAL MARKET ATTRACTIVENESS LOGIC
┌────────────────────────────────────────────┐
│ Regulation-linked demand                   │
│ mandates / quotas / credits / CI systems   │
└────────────────────────────────────────────┘
                     +
┌────────────────────────────────────────────┐
│ Pathway fit                                │
│ eligibility / caps / proof burden          │
└────────────────────────────────────────────┘
                     +
┌────────────────────────────────────────────┐
│ Supply gap or import openness              │
│ local scarcity / import need / trade fit   │
└────────────────────────────────────────────┘
                     ↓
┌────────────────────────────────────────────┐
│ Comparative market priority                │
│ high / medium / low analytical priority    │
└────────────────────────────────────────────┘
```

### Example: feedstock-to-market mapping
```text
          FEEDSTOCK TO MARKET FIT LOGIC
┌─────────────────────────────────────┐
│ SE Asia feedstock class             │
│ UCO / POME / residues / gases       │
└─────────────────────────────────────┘
                ↓
┌─────────────────────────────────────┐
│ Pathway conversion options          │
│ FAME / HVO / RNG / methanol / etc.  │
└─────────────────────────────────────┘
                ↓
┌─────────────────────────────────────┐
│ Destination market pull             │
│ EU / US / UK / Japan / Singapore    │
└─────────────────────────────────────┘
```

These diagrams should explain the analytical lens before rankings or matrices appear.

## Section Expectations
### Market comparison view
This is the heart of the file. Explain what dimensions are being compared and why they matter.

Typical dimensions:
- strength of regulation-linked demand;
- pathway openness;
- proof and certification burden;
- buyer pull intensity;
- domestic supply gap;
- import openness;
- relevance to Southeast Asia-origin supply.

### Key findings
State the main patterns directly and clearly. This section should not hide the conclusion in tables.

### Regulatory asymmetry view
Use this section to isolate the small legal differences that create materially different outcomes across similar markets.

Typical asymmetry dimensions:
- legal definition boundary;
- buyer-obligation trigger point;
- certification recognition;
- chain-of-custody model;
- default versus actual GHG treatment;
- import eligibility or importer access;
- registry, audit, or documentary friction;
- value-capture mechanics;
- timing windows, grandfathering, or sunset treatment.

### Demand-side implications
Explain what creates value in each market:
- compliance obligations;
- scarcity of compliant molecules;
- premium pathways;
- timing of future demand expansion.

### Supply-side implications
Explain what constrains supply:
- domestic feedstock shortages;
- caps on favored feedstocks;
- proof bottlenecks;
- infrastructure or route dependence;
- import reliance or import resistance.

### Southeast Asia producer implications
Translate the comparison into a practical analytical lens:
- which pathway-market matches look structurally plausible;
- which markets are technically attractive but administratively difficult;
- which markets look large but are poor fits for SE Asia-origin supply.

This section remains analytical. It should not yet become a strategy recommendation.

### Commercial attractiveness dimensions
State the dimensions that make the combination attractive or unattractive for a BD team:
- buyer pull;
- pathway access;
- proof burden;
- supply fit;
- likely commercial control or dependence on intermediaries.

### Disqualifier conditions
State what would make a market-pathway combination unattractive even if nominal demand is high:
- protected local supply;
- excessive proof burdens;
- low buyer access;
- route mismatch;
- unresolved policy ambiguity.

## Ranking Logic
Phase 4 may rank, but the ranking method must be explicit.

### Required ranking dimensions
- regulation-linked demand strength;
- pathway eligibility quality;
- proof and certification burden;
- likely buyer pull intensity;
- supply scarcity or import opening;
- fit for Southeast Asia-origin supply.

### Ranking output style
Use high / medium / low analytical ratings or a compact score framework, but explain the meaning in prose first.

Rules:
- the scoring model must be stable across files;
- no hidden weighting;
- if judgment is qualitative, say so directly;
- every score or label must be defensible from prior phases.
- every high-priority label must have a corresponding disqualifier test.

## Worked Example Requirement
Every Wave 1 file should include one worked example or scenario.

Examples:
- global comparison: why two markets with similar climate ambitions produce very different commercial pull for the same pathway.
- demand-mechanism file: how a credit system can outperform a simple blending mandate for a waste-based pathway.
- supply-potential file: how a market can be large but still unattractive due to local feedstock protection.
- feedstock-to-market mapping: how a single SE Asia residue stream routes differently depending on pathway conversion and proof burden.
- opportunity ranking: how a pathway can rank below a larger market because access barriers overwhelm nominal demand size.

The example structure:
1. Set the scenario.
2. Show the relevant analytical dimensions.
3. Walk through the comparative outcome.
4. State what the example reveals.

## File-Specific Expectations
### Global market comparison
This file should synthesize the overall picture and act as the entry point for commercial readers.

It should include:
- a market comparison matrix;
- narrative explanation of the strongest demand centers;
- explanation of why some markets are strategically important despite smaller size.

### Demand mechanisms by market
This file should explain how different regulatory designs create very different commercial behavior.

It should compare:
- volumetric mandates;
- carbon-intensity systems;
- tradable credit markets;
- tax-driven systems;
- aviation and maritime demand mechanisms.

### Supply potential by region
This file should compare regional supply bases and their likely relevance to global demand centers.

Regions should include:
- Southeast Asia;
- Europe where relevant;
- North America where relevant;
- Brazil and other notable origin points where relevant to the covered pathways.

### Feedstock-to-market mapping
This file should map real SE Asia-origin feedstock classes to plausible pathway and destination combinations.

### High-priority opportunity ranking
This file should rank combinations of market and pathway, not just markets in isolation.

### Regulatory asymmetry matrix
This file should compare the Wave 1 markets directly on the legal and implementation differences that can create outsized opportunity.

At minimum, compare:
- EU level versus key member-state implementation;
- US federal versus California;
- UK versus EU implementations;
- Japan versus other Wave 1 destination markets where pathway treatment looks similar on the surface.

For every asymmetry, state:
- the rule difference;
- the affected pathway or buyer class;
- the commercial effect;
- the proof or capability requirement;
- whether the asymmetry is durable or likely temporary.

### Wave 1 micro-opportunity log
This file should capture short, high-value opportunity notes created by subtle legal or implementation differences in Wave 1 markets.

Each entry should state:
- market;
- pathway or feedstock;
- asymmetry type;
- why the difference matters commercially;
- what proof or capability is required;
- what rule change would collapse the opportunity.

### Focused market analyses
The EU, US, UK, Japan, and Southeast Asia focused files should unpack why the broader comparison looks the way it does for those specific areas.

## Agent Operating Plan for Phase 4
### Program Orchestrator Agent
Owns sequencing, ranking-framework lock, and dependencies into Phase 5.

### Comparative Analysis Agent
Owns analytical model design, comparison matrices, and cross-file consistency in scoring language.

### Market Demand Agent
Owns demand-side interpretation and ensures the analysis reflects actual regulatory pull rather than abstract policy ambition.

### Supply Potential Agent
Owns supply-side interpretation, import-openness analysis, and Southeast Asia fit logic.

### Strategy Architect Agent
Participates as a downstream consumer during this phase to ensure outputs are usable in Phase 5, but does not yet write recommendations.

### Citation and Evidence QA Agent
Checks that rankings, comparisons, and statements are anchored in Phase 2 and Phase 3.

### Editorial Integration Agent
Checks narrative structure, diagram presence, transition quality, and table readability.

## Workflow
```text
Phase 2 country files
        +
Phase 3 pathway files
        ↓
Analytical framework lock
        ↓
Wave 1 comparison files
        ↓
Evidence trace check
        ↓
Wave 2 focused analyses
        ↓
Ranking coherence review
        ↓
Editorial review
        ↓
Phase close review
```

## Implementation Steps
### Step 1. Create folder-level navigation
- Add `README.md` in `04_market_analysis/`
- Explain how these files differ from country and pathway files
- Explain how the folder should be used before entering Phase 5 strategy outputs

### Step 2. Lock the analytical framework
- Define comparison dimensions once
- Define the rating language once
- Define how qualitative judgment will be stated
- Define the asymmetry dimensions once so every Wave 1 comparison uses the same legal-delta logic

### Step 3. Draft Wave 1 files
- Start with the shared comparative outputs
- Use consistent dimensions and tables across files
- Include one diagram and one worked example in every Wave 1 file
- Draft `regulatory_asymmetry_matrix.md` and `wave_1_micro_opportunity_log.md` before finalizing the opportunity ranking

### Step 4. Draft Wave 2 focused files
- Use the Wave 1 framework to explain why the highest-priority markets look the way they do
- Keep these files explanatory, not repetitive

### Step 5. Run ranking and coherence review
- confirm that the same market-pathway combination is not treated inconsistently across files;
- confirm that all rating labels have evidence behind them;
- confirm that the Southeast Asia lens stays analytical rather than prescriptive.

## Acceptance Criteria
Phase 4 is accepted only when all of the following are true:
- every planned analysis file exists and follows the common structure;
- every Wave 1 file includes a narrative opening, an analysis diagram, and one worked example;
- ranking logic is explicit and reused consistently;
- every comparative claim resolves back to Phase 2 or Phase 3 files;
- every Wave 1 file includes commercial attractiveness dimensions and disqualifier conditions;
- the asymmetry matrix and Wave 1 micro-opportunity log both exist and use stable comparison dimensions;
- market-pathway comparisons are made at the combination level where needed, not only at the country level;
- no file includes named counterparties or specific entry-model recommendations.

## Important Interface and Template Additions
These conventions become mandatory in Phase 4:
- Add `Last updated` near the top of every market-analysis file.
- Add one `Analytical framework` ASCII diagram per file.
- Add one `Worked example or scenario` section in every Wave 1 file.
- Add a `Supporting references` section pointing back to relevant country and pathway files.
- Add `Commercial attractiveness dimensions` and `Disqualifier conditions` to every market-analysis file.
- Add `Regulatory asymmetry view` to every market-analysis file.
- Use a shared rating vocabulary across all analysis outputs.

## Risks and Failure Modes
### Risk: rankings look arbitrary
Mitigation:
- make the dimensions explicit;
- explain the analytical logic before showing results;
- keep the scoring model stable.

### Risk: files duplicate pathway references
Mitigation:
- use pathway files for treatment detail;
- use market-analysis files for comparison and interpretation.

### Risk: analysis drifts into strategy too early
Mitigation:
- stop at implications and priority structure;
- defer named actions and go-to-market models to Phase 5.

### Risk: large tables overwhelm readers
Mitigation:
- put diagrams and prose first;
- use matrices only where comparison value is high;
- follow each matrix with interpretation.

## Test Cases and Scenarios
### Scenario 1: global market comparison
Expected:
- shows why EU, US, UK, and Japan differ in commercial pull;
- distinguishes large markets from accessible markets;
- points readers to deeper files without repeating them.

### Scenario 2: demand mechanisms by market
Expected:
- explains why different compliance designs create different premiums;
- makes the logic readable for non-legal users;
- remains grounded in the reference layers.

### Scenario 3: feedstock-to-market mapping
Expected:
- maps SE Asia-origin materials to plausible destination markets;
- explains why some seemingly attractive routes fail on proof or policy grounds;
- avoids turning into a recommendation memo.

### Scenario 4: high-priority opportunity ranking
Expected:
- ranks combinations, not just markets;
- uses explicit dimensions;
- provides analytical priority without jumping to execution advice.

## Assumptions
- Phase 4 is the first ranking phase, but it remains evidence-backed analysis rather than strategy.
- Phase 2 and Phase 3 are the governing reference layers for this phase.
- The writing-style guide applies fully here: diagrams before dense data, narrative interpretation of matrices, and worked examples are required.
- The main audience at this phase is a mixed commercial, compliance, and strategy team that needs decision support without losing traceability.
