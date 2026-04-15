# Phase 3: Biofuel Reference Build

## Summary
Phase 3 converts the jurisdiction-by-jurisdiction reference layer into pathway-centered reference files. This is the first phase where the team can read across markets by fuel family instead of by country.

The purpose of this phase is not to rank markets or recommend deals. Its purpose is to answer a different operational question: "For a given pathway or feedstock class, where does regulatory demand exist, how is the pathway treated across major markets, what proof and certification gates apply, and where does Southeast Asian supply fit?"

Phase 3 must use the writing-style guide as a hard standard:
- open with narrative framing instead of definitions alone;
- use diagrams before tables;
- explain what the patterns mean, not just what the tables list;
- include transitions between markets and pathway sub-sections;
- keep the tone practical and reference-oriented.

## What Phase 3 Must Achieve
By the end of Phase 3, the team should be able to open any pathway file and understand:
- what the pathway covers and what it excludes;
- which feedstocks and conversion routes fall inside the pathway;
- which major markets reward the pathway and under what conditions;
- where the pathway is capped, restricted, disadvantaged, or subject to proof burdens;
- what certifications, documentation, and chain-of-custody conditions matter;
- how the pathway fits or does not fit Southeast Asia-origin supply;
- which route configurations and buyer types matter most commercially;
- which country files to consult for jurisdiction-level detail.

Phase 3 is complete only when those answers are available for every in-scope pathway in a way that is comparable across markets and traceable back to Phase 2 country files.

## Build Strategy
### Operating principle
Phase 3 is a pathway-synthesis phase. It may compare treatment across jurisdictions and explain where demand exists, but it may not yet produce global rankings or prescriptive strategy.

Allowed content:
- cross-market synthesis of pathway treatment;
- explanation of feedstock and conversion-route boundaries;
- explanation of market demand by pathway;
- explanation of proof, certification, and documentation burdens;
- concise Southeast Asia supply-fit interpretation;
- worked examples that clarify pathway classification or market access.

Not allowed content:
- market-attractiveness ranking;
- final opportunity scoring;
- counterparty or entry-model recommendations;
- unsupported pathway claims that are not grounded in Phase 2 files.

### Coverage order
Use two waves aligned to complexity and downstream relevance.

#### Wave 1: core opportunity pathways
- biodiesel and FAME
- renewable diesel and HVO
- bioethanol
- biomethanol
- biogas and RNG
- certifications and chain of custody

#### Wave 2: enabling and special-topic files
- SAF-linked pathways
- waste oils and residues
- lignocellulosic feedstocks

Wave 1 files should be completed first because they anchor the most important cross-market comparisons for later demand analysis and strategy.

## Folder and File Outputs
### Core outputs
- `03_biofuel_reference/README.md`
- `03_biofuel_reference/biodiesel_and_fame.md`
- `03_biofuel_reference/renewable_diesel_hvo.md`
- `03_biofuel_reference/bioethanol.md`
- `03_biofuel_reference/biomethanol.md`
- `03_biofuel_reference/biogas_and_rng.md`
- `03_biofuel_reference/certifications_and_chain_of_custody.md`
- `03_biofuel_reference/saf_linked_pathways.md`
- `03_biofuel_reference/waste_oils_and_residues.md`
- `03_biofuel_reference/lignocellulosic_feedstocks.md`

### Optional helper files if needed
- one short methodology note in this folder if the team needs an explicit explanation of how pathway grouping decisions were made;
- one visual index file if the number of pathway and feedstock cross-links becomes difficult to navigate.

## Pathway File Design
Each pathway file should read like a cross-market operating map for that pathway.

### Required structure
1. Title
2. Last updated
3. Why this pathway matters
4. Pathway landscape diagram
5. Feedstock and conversion-route scope
6. Regulatory demand by market
7. Eligibility and restrictions by market
8. Certification and traceability requirements
9. Route competitiveness and proof burden
10. Southeast Asia supply implications
11. Worked example
12. Key source trail
13. Related country files
14. Related pathway files

### Narrative opening style
Open with why the pathway matters globally, where the pathway is creating the most confusion or opportunity, and how the team should use the file.

Example opening pattern:
- Paragraph 1: why the pathway matters in global compliance or low-carbon fuel markets.
- Paragraph 2: what makes the pathway difficult, such as classification ambiguity, proof burdens, or sharply different treatment across jurisdictions.
- Paragraph 3: what the file covers and how it connects to country-reference files.

## Diagram Pattern
Every pathway file should include an ASCII pathway-landscape diagram near the top.

### Example: biodiesel and HVO pathway family
```text
            LIPID-BASED FUEL PATHWAY LANDSCAPE
┌──────────────────────────────┐
│ Feedstocks                   │
│ vegetable oils / UCO / fats  │
└──────────────────────────────┘
               ↓
┌──────────────────────────────┐
│ Conversion routes            │
│ FAME transesterification     │
│ HVO hydrotreatment           │
└──────────────────────────────┘
               ↓
┌──────────────────────────────┐
│ Market treatment             │
│ eligibility / caps / credits │
└──────────────────────────────┘
```

### Example: biogas and RNG
```text
              BIOGAS TO RNG MARKET LOGIC
┌─────────────────────────────────────┐
│ Organic wastes and gas generation   │
│ manure / landfill / POME / residues │
└─────────────────────────────────────┘
                  ↓
┌─────────────────────────────────────┐
│ Upgrading and transport use         │
│ biogas → RNG / CNG / LNG pathways   │
└─────────────────────────────────────┘
                  ↓
┌─────────────────────────────────────┐
│ Credit and demand outcomes          │
│ RFS / LCFS / local gas markets      │
└─────────────────────────────────────┘
```

The diagram should explain pathway logic before any comparison tables appear.

## Section Expectations
### Feedstock and conversion-route scope
Define the pathway carefully. This is where the file should explain what is in and out of scope and what distinctions matter commercially and legally.

Examples:
- biodiesel/FAME versus renewable diesel/HVO;
- raw biogas versus upgraded RNG;
- bioethanol from food crops versus lignocellulosic routes;
- biomethanol from biogenic feedstock versus RFNBO-related e-methanol interfaces.

This section should avoid vague umbrella terminology.

### Regulatory demand by market
Explain where the pathway creates real compliance pull and through what mechanism:
- volumetric blending;
- tradable credit systems;
- GHG-intensity programs;
- aviation or maritime quotas;
- tax-driven incentives or penalties.

This section should cross-link directly to Phase 2 country files instead of redoing country-level detail.

### Eligibility and restrictions by market
Present the pathway's market treatment precisely:
- clearly eligible;
- eligible only under conditions;
- capped or limited;
- disadvantaged versus alternative pathways;
- not currently central to the regime.

Avoid flattening nuanced treatment into binary labels unless the underlying country file justifies that conclusion.

### Certification and traceability requirements
Explain the recurring practical proof burdens for the pathway:
- sustainability certification;
- chain of custody;
- waste or residue proof;
- lifecycle GHG documentation;
- pathway-approval or CI documentation where relevant.

This section should point to the dedicated certifications file where the same issue recurs.

### Route competitiveness and proof burden
Explain the commercial tradeoffs that affect pathway usefulness:
- which route configurations are most attractive;
- where proof burdens materially reduce attractiveness;
- where documentation complexity changes the viable buyer class;
- what route assumptions downstream strategy files are allowed to make.

### Southeast Asia supply implications
This section should answer:
- what kinds of SE Asia-origin material fit this pathway;
- what proof burdens would matter most;
- whether the pathway structurally favors export, local use, or both.

It should remain analytical and descriptive, not yet strategic.

## Worked Example Requirement
Every Wave 1 pathway file should include one worked example.

Examples:
- biodiesel/FAME: how the same lipid feedstock can be treated differently depending on FAME output, waste classification, or local caps.
- HVO: how feedstock origin and certification alter market eligibility.
- bioethanol: how conventional versus advanced routes change regulatory treatment.
- biomethanol: how maritime demand or low-carbon fuel rules make route and classification matter.
- biogas/RNG: how upgrading and end use change regulatory value.
- certifications: how a missing proof document can break market access even when the fuel is otherwise eligible.

The example structure:
1. Set the scenario.
2. Show the classification or compliance issue.
3. Walk through the market consequences.
4. State what the example reveals.

## Comparison Tools
Pathway files should use compact comparison elements, but always under narrative control.

Preferred tables:
- market-by-market pathway treatment table;
- feedstock inclusion and exclusion table;
- proof-burden summary table;
- pathway-to-country reference map.

Preferred visual patterns:
- pathway spectrum diagrams;
- conversion-route maps;
- market-treatment ladders from strongly rewarded to conditionally accepted.

Rule:
- no dense matrix should appear without a short paragraph telling the reader how to read it;
- tables must support comparison, not replace explanation.

## Special File Expectations
### Certifications and chain of custody
This file is not jurisdiction-specific. It should explain recurring proof systems as a cross-market gating layer and act as a bridge between country and pathway files.

It should include:
- what certification systems solve for;
- where they are mandatory in practice versus merely expected;
- how mass balance, segregation, and related proof models affect access;
- why documentary integrity can matter as much as feedstock chemistry.

### Waste oils and residues
This file should focus on feedstock-class treatment rather than finished-fuel chemistry. It should explain why some waste classes attract premiums, where fraud concerns create limits, and how these issues map onto major destination markets.

### Lignocellulosic feedstocks
This file should clarify the boundary between conventional and advanced pathways and explain why the same crop family can be treated differently depending on which part of the plant is used and how it is processed.

### SAF-linked pathways
This file should stay connected to the core pathway set and avoid becoming a full standalone SAF market report. Its job is to explain where aviation demand changes the relevance of bioethanol, lipids, wastes, gases, or biomethanol-adjacent pathways.

## Agent Operating Plan for Phase 3
### Program Orchestrator Agent
Owns sequencing, wave management, and dependency checks between Phase 2 and Phase 3.

### Comparative Analysis Agent
Owns the cross-market synthesis logic in pathway files and helps standardize comparison language.

### Market Demand Agent
Owns the `Regulatory demand by market` sections and ensures pathway-level demand descriptions stay grounded in country mechanisms.

### Supply Potential Agent
Owns the `Southeast Asia supply implications` sections and ensures feedstock-fit logic is technically coherent.

### Regional Legal Research Agents
Support pathway drafting where classification or market-treatment questions require jurisdiction-specific clarification.

### Citation and Evidence QA Agent
Checks that pathway-level claims resolve back to Phase 2 country files and do not introduce unsupported cross-market assertions.

### Editorial Integration Agent
Checks narrative quality, diagram quality, terminology consistency, and cross-links across pathway files.

## Workflow
```text
Phase 2 country files
   ↓
Pathway grouping decision
   ↓
Pathway-reference draft
   ↓
Cross-market comparison pass
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
- Add `README.md` in `03_biofuel_reference/`
- Explain the difference between country files and pathway files
- Explain how to move from a pathway file into country files and later into market-analysis files

### Step 2. Draft Wave 1 pathway files
- Start with the pathway families most likely to anchor downstream market analysis
- Use the same section order across files
- Include one diagram and one worked example in every Wave 1 file

### Step 3. Draft enabling and special-topic files
- Build the certifications file early enough that other pathway files can reference it consistently
- Build feedstock-class files where they reduce repetition across major pathway files

### Step 4. Run cross-file terminology review
- standardize pathway names;
- standardize feedstock class labels;
- standardize language around `eligible`, `restricted`, `capped`, and `conditional`;
- standardize how proof burdens are described.
- standardize the language used for route attractiveness and buyer fit.

### Step 5. Run QA and coherence review
- confirm every pathway claim resolves back to country files;
- confirm the same market is not described inconsistently across pathway files;
- confirm the Southeast Asia lens remains analytical, not prescriptive.

## Acceptance Criteria
Phase 3 is accepted only when all of the following are true:
- every in-scope pathway has a dedicated file;
- every Wave 1 file includes a narrative opening, a pathway diagram, and one worked example;
- every file explains both market demand and pathway treatment, not just definitions;
- every Wave 1 file explains route competitiveness and proof burden clearly enough for downstream strategy use;
- every pathway file links back to the relevant country-reference files;
- recurring certification issues are handled consistently across files;
- no file includes market rankings or entry recommendations.

## Important Interface and Template Additions
These conventions become mandatory in Phase 3:
- Add `Last updated` near the top of every pathway file.
- Add one `Pathway landscape` ASCII diagram per file.
- Add one `Worked example` section in every Wave 1 file.
- Add a `Related country files` section and a `Related pathway files` section.
- Add `Route competitiveness and proof burden` to every pathway file.
- Use a shared comparison vocabulary across all pathway files.

## Risks and Failure Modes
### Risk: pathway files duplicate country files
Mitigation:
- keep jurisdiction detail in Phase 2 files;
- use Phase 3 files for synthesis and comparison only.

### Risk: pathway definitions get fuzzy
Mitigation:
- define feedstock and conversion boundaries explicitly;
- use worked examples to show edge cases.

### Risk: files drift into strategic recommendations
Mitigation:
- keep Southeast Asia discussion descriptive;
- hold opportunity ranking and go-to-market choices for later phases.

### Risk: cross-market statements become overconfident
Mitigation:
- require every comparative claim to map back to one or more country files;
- escalate unclear treatment to QA instead of smoothing over it.

## Test Cases and Scenarios
### Scenario 1: biodiesel and FAME file
Expected:
- distinguishes lipid feedstocks from finished-fuel pathway treatment;
- explains where FAME remains important and where it is disadvantaged;
- points to country files for local caps and implementation details.

### Scenario 2: biogas and RNG file
Expected:
- distinguishes raw biogas from transport-grade RNG;
- explains why end use changes regulatory value;
- shows where the pathway has the strongest compliance pull.

### Scenario 3: biomethanol file
Expected:
- clarifies route distinctions and why maritime-linked demand matters;
- avoids collapsing bio-methanol and e-methanol into a single unsupported category;
- points to country files for exact legal treatment.

### Scenario 4: certifications and chain of custody file
Expected:
- acts as a cross-market proof guide;
- explains recurring access barriers without becoming a full audit manual;
- is reusable by all other pathway files.

## Assumptions
- Phase 3 remains pathway-centered and cross-market, not yet market-ranked.
- Phase 2 is the governing interpretive base for Phase 3 drafting.
- The writing-style guide applies fully here: diagrams before tables, narrative hooks, prose between comparison elements, and insight after structured data are required.
- Wave 1 pathway files are expected to be materially richer than Wave 2 special-topic files on first pass.
