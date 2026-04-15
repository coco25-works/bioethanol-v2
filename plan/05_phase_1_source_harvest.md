# Phase 1: Regulatory Source Harvest and Evidence Baseline

## Summary
Phase 1 builds the evidence backbone for the entire program. Its job is not to analyze markets or write strategy. Its job is to create a reliable, navigable, citation-ready source layer that downstream agents can trust.

This phase will produce:
- a structured source register by jurisdiction;
- a shared source-gap log;
- a consistent metadata model for every source;
- a frozen point-in-time baseline dated per file;
- wave-based completion, starting with the highest-value demand-center markets.

The output should already feel like an internal reference product, not a scratchpad. Even at the source stage, the files should read clearly, open with narrative framing, and include simple diagrams showing how each jurisdiction's source stack fits together.

## What Phase 1 Must Achieve
By the end of Phase 1, the team must be able to answer these questions without opening external notes:
- What are the primary legal instruments governing each market?
- Which official sources define eligibility, caps, thresholds, and demand mechanisms?
- Which sources are primary law versus guidance versus official data?
- Which source gaps remain unresolved?
- Which jurisdictions are ready for Phase 2 extraction, and which are blocked by missing authority or translation issues?

Phase 1 is complete only when the answer to those questions is visible inside the repository.

## Build Strategy
### Operating principle
Phase 1 is a source-harvest and source-validation phase only.

Allowed content:
- source identification;
- citation metadata;
- short relevance notes;
- source status and confidence;
- open issues and missing-source flags.

Not allowed content:
- strategic recommendations;
- commercial rankings;
- demand/supply conclusions beyond source descriptions;
- unsupported summaries of legal effect.

### Coverage order
Use two waves.

#### Wave 1: demand-center and anchor markets
- EU level
- Germany
- Netherlands
- France
- US federal
- California
- UK
- Japan

#### Wave 2: secondary and contextual markets
- Brazil
- Singapore
- China
- Indonesia
- Malaysia
- Thailand

The reason for this order is simple: Phase 2, 3, and 4 depend most heavily on the markets where regulation directly creates compliance demand and monetizable premiums.

## Folder and File Outputs
### Core outputs
- `01_source_register/README.md`
- `01_source_register/eu/eu_level.md`
- `01_source_register/eu/germany.md`
- `01_source_register/eu/netherlands.md`
- `01_source_register/eu/france.md`
- `01_source_register/americas/united_states_federal.md`
- `01_source_register/americas/california.md`
- `01_source_register/americas/brazil.md`
- `01_source_register/apac/japan.md`
- `01_source_register/apac/singapore.md`
- `01_source_register/apac/china.md`
- `01_source_register/apac/indonesia.md`
- `01_source_register/apac/malaysia.md`
- `01_source_register/apac/thailand.md`
- `06_appendices/source_gap_log.md`

### Optional helper files if needed
- `01_source_register/eu/README.md`
- `01_source_register/americas/README.md`
- `01_source_register/apac/README.md`

These regional `README` files are useful if the register becomes dense and the team needs a quick index by geography.

## Source Model
Every source entry must be classified into one of four authority levels:
1. Primary law
2. Official guidance
3. Official data
4. Secondary context

Every entry must also be tagged for topic relevance:
- feedstock eligibility
- restricted or capped pathways
- lifecycle GHG thresholds
- blending mandate
- quota obligation
- tradable credit system
- certification or proof requirement
- import or trade restriction
- maritime
- aviation
- implementation or compliance mechanics

Every entry must carry a status:
- confirmed
- needs translation check
- superseded
- secondary only
- missing

## File Design
Each jurisdiction file should read like a compact, high-trust intake brief.

### Required structure for each jurisdiction source file
1. Title
2. Last updated / baseline date
3. Why this market matters
4. Coverage scope
5. Source-stack diagram
6. Primary laws and regulations
7. Official guidance and compliance references
8. Official data sources
9. Source metadata table
10. Open source gaps
11. Readiness for Phase 2
12. Related files

### Narrative opening style
Use the writing-style guide here:
- open with why the market matters, not a dry list;
- explain what kind of source stack the reader is looking at;
- tell the team what this source file is for and how to use it.

Example opening pattern:
- Paragraph 1: what makes this market important in the global bio-based fuels landscape.
- Paragraph 2: what kind of regulatory architecture it uses.
- Paragraph 3: what this source file captures and what it does not yet attempt.

## Diagram Pattern
Every jurisdiction source file should include a simple ASCII source-stack diagram before the tables.

### Example: EU-level diagram
```text
                 EU-LEVEL SOURCE STACK
┌─────────────────────────────────────────────────────┐
│ Primary law                                         │
│ RED II / RED III / FuelEU Maritime                  │
└─────────────────────────────────────────────────────┘
                       ↓
┌─────────────────────────────────────────────────────┐
│ Implementing and interpretive layer                 │
│ Commission acts / official guidance / Q&A           │
└─────────────────────────────────────────────────────┘
                       ↓
┌─────────────────────────────────────────────────────┐
│ Compliance and market-reference layer               │
│ official databases / official statistics / reports  │
└─────────────────────────────────────────────────────┘
```

### Example: US federal + California diagram
```text
             US REGULATORY STACK FOR TRANSPORT FUELS
┌────────────────────────────┐       ┌────────────────────────────┐
│ Federal layer              │       │ State layer                │
│ Clean Air Act / RFS / EPA  │ ----> │ California LCFS / CARB     │
└────────────────────────────┘       └────────────────────────────┘
                ↓                                  ↓
┌──────────────────────────────────────────────────────────────────┐
│ Official guidance, pathway approvals, reporting, program data   │
└──────────────────────────────────────────────────────────────────┘
```

These do not need to be pretty. They need to orient the reader fast.

## Metadata Table Design
Use one standard table in every jurisdiction file.

| Field | Requirement |
|---|---|
| Source title | Full formal title |
| Source type | Primary law / guidance / data / secondary |
| Regulator / issuer | Exact authority |
| Date | Publication or adoption date |
| Citation location | Article / section / rule / chapter if known |
| Link | Official URL if available |
| Topic tags | Comma-separated issue tags |
| Relevance note | One-line note only |
| Status | Confirmed / needs translation check / superseded / secondary only / missing |

### Table rule
Do not place two large tables back-to-back without prose between them. Add a short transition paragraph explaining what the next section of sources contributes.

## Jurisdiction-by-Jurisdiction Expectations
### EU level
Must capture:
- RED II / RED III core instruments
- article-level anchors for definitions and sustainability criteria
- Annex IX feedstock treatment
- FuelEU Maritime
- official Commission guidance and implementing materials if used later

### Germany
Must capture:
- the core legal instruments behind the transport GHG quota regime
- any official compliance or implementation references needed to understand market treatment

### Netherlands
Must capture:
- core legal basis for the transport-energy compliance system
- official materials explaining HBE categories or equivalents

### France
Must capture:
- legal basis for TIRUERT and official implementation references
- any official treatment of excluded feedstocks if used later in analysis

### US federal
Must capture:
- Clean Air Act statutory anchor for RFS
- EPA rulemaking and official program pages used for pathway interpretation
- official RIN and program data sources where later analysis depends on them

### California
Must capture:
- LCFS legal anchor
- CARB compliance references
- official CI or program references if used later

### UK
Must capture:
- RTFO legal foundation
- official Department for Transport or administrator guidance
- development fuel references where relevant

### Japan
Must capture:
- legal or official-policy basis for transport or aviation-linked demand where the later analysis depends on it
- translation status must be explicit wherever the authoritative text is not in English

### Wave 2 jurisdictions
These can start thinner, but each file still needs:
- at least one primary-source anchor if available;
- a clear statement of what remains missing;
- a readiness assessment for whether Phase 2 can proceed.

## Readiness Scoring
At the end of each jurisdiction file, include a short readiness block.

```text
Phase 2 readiness: Ready / Partial / Blocked

Ready:
- core legal instruments logged
- major guidance logged
- no critical source gaps

Partial:
- main laws logged
- some guidance or citation gaps remain

Blocked:
- key legal anchor missing
- translation or access issue prevents safe extraction
```

This lets the orchestrator know where to send the next pass.

## Source Gap Log
The shared gap log should not be a dumping ground. It should be a management tool.

### Structure
1. Overview
2. High-priority blocking gaps
3. Translation-dependent gaps
4. Access or broken-link issues
5. Jurisdiction-specific open items
6. Deferred items for later phases

### Gap log fields
- jurisdiction
- missing or uncertain source
- why it matters
- blocking level: high / medium / low
- likely resolution path
- assigned agent
- status

### Priority logic
High:
- missing primary legal anchor for a key demand mechanism

Medium:
- primary law exists but guidance or official data is still missing

Low:
- useful context source missing but Phase 2 can still proceed safely

## Agent Operating Plan for Phase 1
### Program Orchestrator Agent
Owns:
- phase schedule
- wave coordination
- file assignment
- readiness scoreboard
- go/no-go decision for Phase 2 handoff

### EU-UK Legal Research Agent
Owns:
- EU level
- Germany
- Netherlands
- France
- UK

### Americas Legal Research Agent
Owns:
- US federal
- California
- Brazil

### APAC Legal Research Agent
Owns:
- Japan
- Singapore
- China
- Indonesia
- Malaysia
- Thailand

### Citation and Evidence QA Agent
Owns:
- authority-level checking
- citation completeness
- source status consistency
- blocking unsupported or ambiguous entries

### Editorial Integration Agent
Owns:
- template conformance
- narrative quality
- diagram inclusion
- link formatting
- consistent headings and field naming

## Workflow
```text
Plan file
   ↓
Jurisdiction assignment
   ↓
Initial source harvest
   ↓
Metadata normalization
   ↓
QA authority check
   ↓
Gap logging
   ↓
Readiness scoring
   ↓
Wave close review
```

## Implementation Steps
### Step 1. Create the folder-level navigation
- Add `README.md` in `01_source_register/`
- Optionally add regional `README.md` files if navigation needs it
- Explain wave structure and how to use the source register

### Step 2. Create all jurisdiction files immediately
- Even if some Wave 2 files start thin
- This prevents silent scope drift
- Every target market becomes visible from day one

### Step 3. Populate Wave 1 first
- Fill the high-priority demand-center markets to a higher standard
- Ensure article/section-level anchors wherever possible
- Confirm official guidance and official data layers

### Step 4. Populate Wave 2 to baseline
- Capture primary anchors and explicit limitations
- Do not overstate certainty if sources are thin or translation-dependent

### Step 5. Run QA review
- Check every file for baseline date
- Check every file for the source-stack diagram
- Check every file for consistent metadata columns
- Check every file for readiness scoring
- Check the shared gap log against all files

## Acceptance Criteria
Phase 1 is accepted only when all of the following are true:
- every target jurisdiction has a source-register file;
- every file has a narrative opening, a diagram, and a standardized metadata table;
- every Wave 1 market has primary legal anchors for the main demand mechanism;
- every unresolved issue is captured in the gap log;
- every file states a baseline date;
- every file ends with a readiness assessment;
- no file contains strategy recommendations or unsupported market conclusions.

## Important Interface and Template Additions
These are the concrete file-level conventions the implementer must follow:
- Add `Baseline date` near the top of every source file.
- Add `Wave` near the top of every source file.
- Add `Phase 2 readiness` near the bottom of every source file.
- Add one `Source stack` ASCII diagram per source file.
- Use one metadata table shape across all jurisdictions.
- Use identical status terms across all files.
- Use identical topic tags across all files.

## Risks and Failure Modes
### Risk: source register turns into analysis
Mitigation:
- relevance notes capped to one line
- no `implications` section in Phase 1 files

### Risk: Wave 2 gets neglected
Mitigation:
- create all jurisdiction files at the start
- use readiness scoring so incomplete markets stay visible

### Risk: non-English sources get treated as settled
Mitigation:
- explicit `needs translation check` status
- document whether the cited text is official translation or working translation

### Risk: inconsistent file quality across agents
Mitigation:
- strict template
- editorial review before QA signoff
- readiness scoring applied uniformly

## Test Cases and Scenarios
### Scenario 1: EU file is ready for Phase 2
Expected:
- RED II / RED III / FuelEU sources present
- official guidance section populated
- source-stack diagram present
- metadata complete
- readiness marked `Ready`

### Scenario 2: Japan file has incomplete English-language access
Expected:
- key source anchors logged
- translation dependency flagged
- gap log updated
- readiness marked `Partial` or `Blocked`, not forced to `Ready`

### Scenario 3: Brazil file has a primary law but little official guidance yet
Expected:
- primary source logged
- guidance section may be light
- file still usable if limitations are explicit
- readiness marked `Partial`

### Scenario 4: California file cites only summaries
Expected:
- QA fails the file
- no readiness approval until official legal anchors are added

## Assumptions
- Phase 1 remains a point-in-time baseline, not a continuously updated tracker.
- The baseline date is recorded using the actual compilation date per file.
- Official sources are preferred even if secondary summaries are easier to access.
- The reference set is written for an internal commercial/compliance audience, so clarity and navigability matter as much as completeness.
- The writing-style guide applies at Phase 1 too: narrative openings, diagrams before tables, and readable transitions are part of the deliverable, not optional polish.
