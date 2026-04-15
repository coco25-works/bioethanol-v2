# Agent Operating Model

## Team Objective
Use a multidisciplinary AI agent model so source gathering, legal extraction, comparative analysis, and strategic synthesis can operate as separate workstreams with explicit boundaries.

## Agents
### Program Orchestrator Agent
- Owns sequencing, scope control, phase gates, and issue escalation.

### EU-UK Legal Research Agent
- Owns EU-level, Germany, Netherlands, France, and UK source and country-reference files.

### Americas Legal Research Agent
- Owns US federal, California, and Brazil source and country-reference files.

### APAC Legal Research Agent
- Owns Japan, China, Indonesia, Malaysia, Thailand, and Singapore source and country-reference files.

### Citation and Evidence QA Agent
- Checks traceability, citation completeness, and unsupported claims.
- Has blocking authority before a file can progress to the next phase.

### Market Demand Agent
- Converts regulatory design into buyer demand, premium logic, and pathway pull.

### Supply Potential Agent
- Assesses feedstock availability, import dependence, and SE Asia export fit.

### Comparative Analysis Agent
- Owns matrices, rankings, and feedstock-to-market mapping outputs.

### Strategy Architect Agent
- Builds recommendation files after analysis is complete.
- Owns recommendation framing, commercial decision logic, and stop-condition design in the strategy layer.

### Editorial Integration Agent
- Enforces templates, writing consistency, cross-links, and navigation quality.

## Plan Review Function
During plan-audit and rewrite work, the Program Orchestrator Agent, Citation and Evidence QA Agent, and Editorial Integration Agent collectively act as a review function.

They own:
- identifying overlaps and contradictions across plan files;
- deciding whether a missing decision belongs in the overview, templates, or a specific phase plan;
- pushing missing strategy requirements upstream instead of allowing Phase 5 to compensate for them.

## Handoff Rules
- Source agents may log sources and extract rules; they must not write strategy conclusions.
- Analysis agents may only rely on validated source and country-reference files.
- Strategy outputs must cite upstream market-analysis and country-reference files.
- QA review happens at the end of every phase, not only at the end of the program.
- Shared gaps should be fixed at the highest reusable layer first: overview, repository structure, agent model, and templates before phase-specific duplication.
- If a strategy requirement depends on missing upstream inputs, the upstream phase plan must be expanded.

## Work Allocation Rule
Assign ownership by file, not by loose topic area. Every file should have one lead agent and one QA reviewer.

During the review-and-strengthening pass, every plan file should also have:
- one reviewer responsible for missing-decision detection;
- one reviewer responsible for checking commercial usefulness for BD-facing outputs.
