# File Template Plan

This file is the **canonical source** for all file structures used across the program. Phase plans reference this file for section requirements. If a phase plan lists different sections, this file takes precedence.

## Asymmetry Tag Taxonomy

Use these controlled tags in source-register metadata and cross-market comparison sections. Tags identify the type of subtle legal or implementation difference that creates commercial opportunity across similar markets.

| Tag | Meaning |
|---|---|
| `definition_boundary` | The legal definition of a fuel, feedstock, or pathway differs between markets |
| `buyer_obligation_trigger` | The point at which a buyer becomes obligated differs (e.g., volumetric vs GHG-based) |
| `certification_recognition` | One market accepts a certification another market does not |
| `chain_of_custody_model` | Mass balance, segregation, or book-and-claim treatment differs |
| `timing_window` | A transition period, grandfathering clause, or phase-in creates a time-limited opening |
| `value_capture` | The actor who monetizes the credit, certificate, or premium differs between markets |
| `administrative_friction` | Registry access, importer registration, audit burden, or documentary controls differ |
| `proof_asymmetry` | The proof burden or documentation standard for the same pathway differs between markets |

## Source Register File Template
Use for: `01_source_register/<region>/<jurisdiction>.md`

Required sections:
- Title
- Primary audience
- Decision supported
- Coverage scope
- Baseline date
- Wave (1 or 2)
- Why this market matters
- Source-stack diagram
- Primary laws and regulations
- Official guidance and compliance references
- Official data sources
- Source metadata table:
  - Source title
  - Source type
  - Regulator / issuer
  - Date
  - Effective date
  - In-force status
  - Amendment or version status
  - Sunset / grandfathering / transition window
  - Jurisdictional level
  - Language
  - Official translation status
  - Citation location
  - Link
  - Topic tags
  - Asymmetry tags (use controlled vocabulary above)
  - Implementing dependency
  - Quoted rule text or extraction note
  - Relevance note
  - Status
- Open source gaps
- Phase 2 readiness (Ready / Partial / Blocked)
- Related files

## Country Reference File Template
Use for: `02_country_reference/<region>/<jurisdiction>.md`

Required sections (in this order):
1. Title
2. Last updated
3. Primary audience
4. Decision supported
5. Why this market matters
6. Market architecture diagram
7. Market overview
8. In-scope fuel pathways
9. Governing regulatory framework
10. Eligible pathways
11. Restricted / capped / conditional pathways
12. Demand mechanism
13. Obligated parties / buyer classes — who must comply under the regime (legal obligation)
14. Buyer / counterparty classes — commercial actors a BD team would encounter (obligated suppliers, refiners, blenders, traders, aggregators, aviation or maritime buyers, compliance-value intermediaries)
15. Certification and chain-of-custody requirements
16. Import / trade / local-preference considerations
17. Temporal rules and transition windows
18. Implementation and administrative friction
19. Supply-side context
20. Southeast Asia relevance
21. Value-capture mechanics
22. Priority legal asymmetries for cross-market comparison
23. Commercial decision criteria
24. What would change this conclusion
25. Worked example (required for Wave 1 files)
26. Key source references
27. Related files

## Biofuel Reference File Template
Use for: `03_biofuel_reference/*.md`

Required sections (in this order):
1. Title
2. Last updated
3. Primary audience
4. Decision supported
5. Why this pathway matters
6. Pathway landscape diagram
7. Feedstock and conversion route scope
8. Regulatory demand by market
9. Eligibility and restrictions by market
10. Certification and traceability requirements
11. Route competitiveness and proof burden
12. Cross-market asymmetry map
13. Southeast Asia supply implications
14. Worked example (required for Wave 1 files)
15. Key source trail
16. Related country files
17. Related pathway files

## Market Analysis File Template
Use for: `04_market_analysis/*.md`

Required sections (in this order):
1. Title
2. Last updated
3. Primary audience
4. Decision supported
5. Analytical question
6. Analytical framework diagram
7. Market comparison view
8. Regulatory asymmetry view
9. Key findings
10. Demand-side implications
11. Supply-side implications
12. SE Asia producer implications
13. Commercial attractiveness dimensions
14. Disqualifier conditions
15. Worked example or scenario (required for Wave 1 files)
16. Supporting references
17. Related files

## Strategy File Template
Use for: `05_strategy_outputs/**/*.md`

Required sections (in this order):
1. Title
2. Last updated
3. Primary audience
4. Decision supported
5. Strategic objective
6. Strategy logic diagram
7. Recommendation summary — state the answer directly using labels (Priority 1 / Priority 2 / Selective / Monitor / No-go)
8. Why now
9. Why demand exists
10. Legal asymmetry creating the opportunity
11. Buyer / counterparty logic
12. Why SE Asia can compete
13. Recommended entry model or strategic posture
14. Commercial decision criteria
15. Gating requirements
16. Opportunity durability and collapse triggers
17. Better alternatives / competing routes
18. Risks and no-go conditions
19. What would change this conclusion
20. Evidence confidence
21. Evidence base
22. Related files
