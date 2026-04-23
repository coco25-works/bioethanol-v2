# Phase 5: Strategy Output Build

## Summary
Phase 5 converts the validated evidence, reference, and comparative analysis layers into standalone strategy documents. This is the first phase where the program moves from explanation to recommendation.

The purpose of this phase is to answer the executive and commercial question: "Given the regulatory demand structure, pathway treatment, supply potential, and Southeast Asia context established in earlier phases, what should a Southeast Asia-based producer actually prioritize, avoid, build capabilities for, and pursue in global markets?"

Phase 5 must use the writing-style guide as a hard standard:
- open each file with the decision tension, not a generic summary;
- use diagrams to clarify strategic logic before tables;
- explain why a recommendation exists, not just what the recommendation is;
- keep recommendations evidence-backed and readable for decision-makers;
- close with practical implications and boundaries, not vague optimism.

## What Phase 5 Must Achieve
By the end of Phase 5, the team should be able to answer:
- which pathway-market combinations deserve near-term focus;
- which combinations are attractive only under specific proof, certification, or partnership conditions;
- which markets are worth monitoring but not prioritizing;
- which producer archetypes should pursue which pathways;
- what commercial model is most plausible for each opportunity type;
- what gating capabilities must exist before pursuing the opportunity;
- which apparent opportunities should be treated as low priority or no-go.
- who the likely buyer is;
- why the timing works now;
- what specific legal asymmetry creates the opportunity;
- whether the opportunity is durable or mainly a transition-window opening;
- what stronger alternative is better if this one is not.

Phase 5 is complete only when these answers are expressed as modular strategy outputs that can be read independently while remaining fully traceable to Phase 2, Phase 3, and Phase 4.

## Build Strategy
### Operating principle
Phase 5 is the recommendation phase. It may recommend pathway priorities, market-entry logic, producer-specific plays, and capability-building actions. It must not invent recommendations that are not clearly supported by the evidence and comparative analysis from prior phases.

Allowed content:
- prioritized opportunity recommendations;
- pathway strategy recommendations;
- market-entry logic by destination market;
- producer-type strategy recommendations;
- certification, capability, and partnership requirements;
- explicit low-priority and no-go guidance.

Not allowed content:
- recommendations unsupported by earlier phases;
- generic strategy language disconnected from specific market mechanics;
- investor-style valuation claims without evidentiary support;
- operational implementation details that belong in a later execution plan.

### Coverage order
Use two waves aligned to decision urgency.

#### Wave 1: core executive and opportunity outputs
- executive strategy summary
- SE Asia producer opportunity map
- pathway strategy files
- key risk and no-go outputs

#### Wave 2: market-entry and producer-type outputs
- market-entry strategy files
- producer-type strategy files
- partnerships and offtake model files
- capability and certification requirement files

Wave 1 should be completed first because it establishes the main strategic position before the more detailed operating variants are drafted.

## Folder and File Outputs
### Core outputs
- `05_strategy_outputs/README.md`
- `05_strategy_outputs/01_executive_strategy_summary.md`
- `05_strategy_outputs/02_se_asia_producer_opportunity_map.md`
- `05_strategy_outputs/pathway_strategy/01_biodiesel_and_hvo_strategy.md`
- `05_strategy_outputs/pathway_strategy/02_bioethanol_strategy.md`
- `05_strategy_outputs/pathway_strategy/03_biomethanol_strategy.md`
- `05_strategy_outputs/pathway_strategy/04_biogas_rng_strategy.md`
- `05_strategy_outputs/market_entry_strategy/01_eu_market_entry.md`
- `05_strategy_outputs/market_entry_strategy/03_us_market_entry.md`
- `05_strategy_outputs/market_entry_strategy/02_uk_market_entry.md`
- `05_strategy_outputs/market_entry_strategy/04_japan_market_entry.md`
- `05_strategy_outputs/market_entry_strategy/05_singapore_hub_strategy.md`
- `05_strategy_outputs/producer_type_strategy/02_plantation_linked_producer.md`
- `05_strategy_outputs/producer_type_strategy/01_waste_aggregator.md`
- `05_strategy_outputs/producer_type_strategy/04_novel_feedstock_developer.md`
- `05_strategy_outputs/producer_type_strategy/03_gas_and_effluent_operator.md`
- `05_strategy_outputs/partnerships/01_target_counterparties.md`
- `05_strategy_outputs/partnerships/04_certification_requirements.md`
- `05_strategy_outputs/partnerships/03_jv_and_tolling_models.md`
- `05_strategy_outputs/partnerships/02_offtake_model_options.md`
- `05_strategy_outputs/risk_and_no_go/01_key_risks.md`
- `05_strategy_outputs/risk_and_no_go/03_low_priority_markets.md`
- `05_strategy_outputs/risk_and_no_go/02_no_go_conditions.md`

### Optional helper files if needed
- `05_strategy_outputs/strategy_method.md`
- `05_strategy_outputs/strategy_assumptions.md`
- `05_strategy_outputs/opportunity_screening_framework.md`
- `05_strategy_outputs/pathway_market_priority_matrix.md`
- `05_strategy_outputs/capability_build_roadmap.md`

## Strategy File Design
Each strategy file should read like a decision memo built on a visible evidence base.

### Required structure
See `04_file_templates.md` for the canonical section list. Key sections:

1. Title
2. Last updated
3. Strategic objective
4. Strategy logic diagram
5. Recommendation summary
6. Why now
7. Why demand exists
8. Legal asymmetry creating the opportunity
9. Buyer / counterparty logic
10. Why Southeast Asia can compete
11. Recommended entry model or strategic posture
12. Commercial decision criteria
13. Gating requirements
14. Opportunity durability and collapse triggers
15. Better alternatives / competing routes
16. Risks and no-go conditions
17. What would change this conclusion
18. Evidence confidence
19. Evidence base
20. Related files

### Narrative opening style
Open with the core decision tension, what the file recommends, and under what conditions the recommendation holds.

Example opening pattern:
- Paragraph 1: what strategic question this file answers.
- Paragraph 2: what makes the decision difficult, such as proof burdens, route economics, buyer concentration, or policy complexity.
- Paragraph 3: what the recommendation is and how the reader should use it.

## Diagram Pattern
Every strategy file should include an ASCII strategy-logic diagram near the top.

### Example: pathway strategy logic
```text
         PATHWAY STRATEGY DECISION LOGIC
┌──────────────────────────────────────────┐
│ Regulation-linked demand                 │
│ where value is created                   │
└──────────────────────────────────────────┘
                    +
┌──────────────────────────────────────────┐
│ SE Asia supply fit                       │
│ feedstock access / route feasibility     │
└──────────────────────────────────────────┘
                    +
┌──────────────────────────────────────────┐
│ Access requirements                      │
│ certification / proof / partnerships     │
└──────────────────────────────────────────┘
                    ↓
┌──────────────────────────────────────────┐
│ Strategic recommendation                 │
│ prioritize / monitor / avoid             │
└──────────────────────────────────────────┘
```

### Example: market-entry strategy logic
```text
           MARKET ENTRY STRATEGY LOGIC
┌──────────────────────────────────────┐
│ Destination market demand            │
│ compliance pull and buyer need       │
└──────────────────────────────────────┘
                 +
┌──────────────────────────────────────┐
│ Access burden                        │
│ certifications / approvals / proof   │
└──────────────────────────────────────┘
                 +
┌──────────────────────────────────────┐
│ Commercial route                     │
│ export / pre-treatment / JV / offtake│
└──────────────────────────────────────┘
                 ↓
┌──────────────────────────────────────┐
│ Recommended market posture           │
│ enter now / build first / watch      │
└──────────────────────────────────────┘
```

The diagram should clarify the recommendation logic before any ranking table appears.

## Section Expectations
### Recommendation summary
This section should state the strategic answer directly. Do not bury the conclusion in the rest of the file.

It should use clear labels such as:
- prioritize now;
- build capabilities first;
- pursue selectively;
- monitor;
- avoid.

### Why now
State the timing logic explicitly:
- policy tightening;
- buyer scarcity;
- pathway pull emerging faster than supply;
- certification or capability timing windows.

### Why demand exists
Tie the recommendation to regulation-linked demand established in earlier phases. This section should make clear that the strategy is grounded in actual market pull, not broad decarbonization rhetoric.

### Buyer / counterparty logic
State who would actually buy, contract, aggregate, or monetize the opportunity:
- obligated suppliers;
- refiners;
- traders;
- airlines;
- shipping-linked buyers;
- compliance-value intermediaries.

### Legal asymmetry creating the opportunity
State the exact rule difference that makes the recommendation attractive relative to similar markets.

This should explain whether the opportunity is created by:
- pathway definition;
- buyer-obligation design;
- certification recognition;
- chain-of-custody treatment;
- timing window;
- administrative access;
- value-capture mechanics.

### Why Southeast Asia can compete
Explain the structural fit:
- feedstock availability;
- route suitability;
- proof feasibility;
- relative position versus local incumbents or other exporting regions.

### Recommended entry model or strategic posture
This is the first phase where the program may recommend:
- feedstock export;
- pre-treatment and export;
- certification-led aggregation;
- tolling or JV arrangements;
- selective market development;
- capability-building before market pursuit.

The recommendation must remain high-level enough to stay strategic rather than operational.

### Commercial decision criteria
State the explicit screening criteria that justify the recommendation:
- buyer access;
- pathway access;
- proof burden;
- route feasibility;
- market timing;
- margin or premium logic where analysis supports it.

### Gating requirements
State what must be true before the recommendation is actionable:
- certification;
- chain-of-custody systems;
- lifecycle GHG documentation;
- feedstock proof integrity;
- buyer access;
- technical conversion capability;
- partnership prerequisites.

### Opportunity durability and collapse triggers
State whether the opportunity is likely durable, transitional, or dependent on a narrow implementation feature.

For each major recommendation, say what would collapse the opportunity:
- rule amendment;
- expiry of a transition window;
- loss of certification recognition;
- tighter proof enforcement;
- buyer-design change;
- value-capture shift to another actor.

### Better alternatives / competing routes
If another market-pathway combination is stronger, say so directly. Phase 5 should help the team avoid spending time on second-best opportunities when the evidence points elsewhere.

### Risks and no-go conditions
Do not treat strategy files as pure upside documents. Each one must clearly say:
- what could break the thesis;
- what conditions make the opportunity unattractive;
- when the team should not proceed.

### What would change this conclusion
State what new evidence, regulatory shift, or capability change would alter the recommendation label.

## Output Types and Their Jobs
### Executive strategy summary
This is the entry point for senior stakeholders. It should state the portfolio view clearly and concisely:
- top opportunity themes;
- top risks;
- pathways to prioritize;
- markets to prioritize;
- capabilities to build.

### SE Asia producer opportunity map
This file should act as the center of gravity for the strategy folder.

It should organize opportunities by:
- pathway;
- destination market;
- producer archetype;
- readiness level.
- buyer class;
- recommendation label.

### Pathway strategy files
These files should answer whether a given pathway is strategically attractive from a Southeast Asia base and under what conditions.

### Market-entry strategy files
These files should answer how the team should think about a specific destination market:
- enter directly;
- partner first;
- build proof infrastructure first;
- monitor but defer.

### Producer-type strategy files
These files should translate the global opportunity map into plays for different producer archetypes.

### Partnership files
These files should explain what types of commercial relationships are likely required without naming specific deals unless the evidence base supports general counterparty categories.

### Risk and no-go files
These files should protect the strategy layer from optimism bias and clearly frame what not to chase.

## Recommendation Logic
Every recommendation must be explicitly derived from:
- Phase 2 country mechanics;
- Phase 3 pathway treatment;
- Phase 4 comparative demand and supply analysis.
- buyer / counterparty logic captured upstream;
- disqualifier conditions captured upstream.

### Required recommendation dimensions
- demand strength;
- pathway fit;
- supply fit;
- proof burden;
- access complexity;
- strategic control;
- downside risk.
- buyer concentration;
- timing;
- better-alternative risk.

### Recommendation output style
Use compact priority labels and explain them in prose first.

Example labels:
- `Priority 1`
- `Priority 2`
- `Selective`
- `Monitor`
- `No-go`

Rules:
- recommendation labels must mean the same thing across files;
- the logic behind the label must be stated;
- no recommendation can rely on hidden assumptions.
- each label must have explicit decision criteria and stop conditions.

## Worked Example Requirement
Every Wave 1 file should include one worked example or strategy scenario.

Examples:
- executive summary: why a smaller but proof-accessible market outranks a larger but protected market.
- opportunity map: how one residue stream can support different strategy postures depending on destination and conversion route.
- pathway strategy: why a pathway with strong demand may still require a capability-building phase first.
- risk file: how a missing certification capability turns a plausible export route into a no-go.

The example structure:
1. Set the scenario.
2. Show the relevant strategic dimensions.
3. Walk through the recommendation outcome.
4. State what the example reveals.

## Agent Operating Plan for Phase 5
### Program Orchestrator Agent
Owns sequencing, recommendation-label lock, and phase-close review.

### Strategy Architect Agent
Owns the core recommendation logic and drafting of the main strategy files.

### Market Demand Agent
Supports the demand rationale behind strategic prioritization.

### Supply Potential Agent
Supports the supply-fit and producer-feasibility logic behind the recommendations.

### Comparative Analysis Agent
Ensures the strategy layer is consistent with the ranking and comparison logic established in Phase 4.

### Citation and Evidence QA Agent
Checks that every recommendation is traceable and that no unsupported leap appears in the strategy files.

### Editorial Integration Agent
Checks narrative clarity, diagram presence, consistency of labels, and usability for executive readers.

## Workflow
```text
Phase 4 analysis outputs
        ↓
Recommendation framework lock
        ↓
Wave 1 strategy files
        ↓
Evidence trace check
        ↓
Wave 2 strategy files
        ↓
Cross-file recommendation review
        ↓
Editorial review
        ↓
Phase close review
```

## Implementation Steps
### Step 1. Create folder-level navigation
- Add `README.md` in `05_strategy_outputs/`
- Explain how strategy files differ from reference and analysis files
- Explain how decision-makers should enter the folder

### Step 2. Lock recommendation framework
- Define the priority labels once
- Define the recommendation dimensions once
- Define the meaning of `no-go` once
- Define how legal asymmetry and opportunity durability will be stated across all strategy files

### Step 3. Draft Wave 1 files
- Start with the executive summary and opportunity map
- Draft pathway strategy files next
- Draft risk and no-go outputs in parallel to balance the opportunity framing
- Draft the opportunity-screening framework and capability-build roadmap before finalizing recommendation labels

### Step 4. Draft Wave 2 files
- build market-entry files using the established recommendation labels;
- build producer-type files using the same logic;
- build partnerships and capability files as enabling layers, not standalone opinions.

### Step 5. Run cross-file coherence review
- confirm that the same opportunity is not labeled differently across files without explanation;
- confirm that all recommendations map back to earlier phases;
- confirm that downside cases are treated as rigorously as upside cases.
- confirm that buyer logic, timing logic, and better-alternative logic are explicit in every major recommendation file.

## Acceptance Criteria
Phase 5 is accepted only when all of the following are true:
- every planned strategy file exists and follows the common structure;
- every Wave 1 file includes a narrative opening, a strategy-logic diagram, and one worked example;
- recommendation labels are explicit and used consistently;
- every recommendation cites the relevant prior-phase evidence;
- every major recommendation file includes `Why now`, `Buyer / counterparty logic`, `Commercial decision criteria`, `Better alternatives / competing routes`, and `What would change this conclusion`;
- every major recommendation file includes `Legal asymmetry creating the opportunity` and `Opportunity durability and collapse triggers`;
- risk, low-priority, and no-go outputs are present and substantive;
- no file drifts into execution-level detail beyond the strategic layer.

## Important Interface and Template Additions
These conventions become mandatory in Phase 5:
- Add `Last updated` near the top of every strategy file.
- Add one `Strategy logic` ASCII diagram per file.
- Add one `Worked example or strategy scenario` section in every Wave 1 file.
- Add an `Evidence base` section pointing back to the relevant country, pathway, and market-analysis files.
- Add `Why now`, `Buyer / counterparty logic`, `Commercial decision criteria`, `Better alternatives / competing routes`, `What would change this conclusion`, and `Evidence confidence` to every strategy file.
- Add `Legal asymmetry creating the opportunity` and `Opportunity durability and collapse triggers` to every strategy file.
- Use one shared recommendation vocabulary across all strategy outputs.

## Risks and Failure Modes
### Risk: strategy becomes generic
Mitigation:
- tie every recommendation to specific market mechanics and pathway evidence;
- avoid broad decarbonization language that could apply anywhere.

### Risk: opportunity bias overwhelms downside analysis
Mitigation:
- draft risk and no-go files in parallel with opportunity files;
- require explicit stop conditions in every strategy file.

### Risk: contradictory labels across files
Mitigation:
- lock the recommendation framework early;
- run a dedicated cross-file coherence review.

### Risk: strategy overreaches beyond evidence
Mitigation:
- require traceability to earlier phases;
- let QA block unsupported recommendations.

## Test Cases and Scenarios
### Scenario 1: executive strategy summary
Expected:
- clearly states top priorities and top risks;
- remains evidence-backed rather than promotional;
- points to deeper files without repeating them.

### Scenario 2: biomethanol strategy
Expected:
- explains where demand exists and where route classification matters;
- distinguishes between technically plausible and strategically prioritized plays;
- states gating conditions clearly.

### Scenario 3: EU market-entry strategy
Expected:
- explains whether the market should be approached directly or via enabling steps first;
- ties the posture to proof, pathway, and demand conditions;
- avoids pretending all EU sub-markets work the same way.

### Scenario 4: gas and effluent operator strategy
Expected:
- translates the global opportunity map into a producer-specific view;
- explains when the pathway is attractive and when it is not;
- includes risk and no-go conditions.

## Assumptions
- Phase 5 is the first prescriptive layer of the program.
- Phase 2, Phase 3, and Phase 4 are the governing evidence and analytical base for every recommendation.
- The writing-style guide applies fully here: diagrams before dense content, narrative framing of recommendations, and worked examples are required.
- The main audience is a mixed executive, commercial, and project-development team that needs actionable prioritization without losing evidentiary traceability.
