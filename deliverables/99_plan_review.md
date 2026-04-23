# Plan Review Report

**Date:** 2026-04-21
**Reviewer:** AI assistant (opencode)
**Scope:** All 15 plan files in `plan/`, all 7 skills in `skills/`, project handoff document, and README
**Verdict:** Foundation is solid. 10 issues found. All fixed.

---

## Executive Summary

The plan architecture is correct and commercially focused. The 7-phase layered build approach (evidence first, analysis second, strategy last), wave-based prioritization, and strategy usefulness checklist are all well-designed. The 7 skills are complete with all 21 reference files present.

The main problem was **internal inconsistency between the shared file template (`04_file_templates.md`) and the detailed required-structure lists in each phase plan**. These overlap but differ in section names, ordering, and counts, which would cause confusion during execution.

All issues have been fixed as of this review date.

---

## Issues Found and Fixed

### Issue 1: Template vs Phase Plan Mismatch (HIGH)

**Problem:** The shared template in `04_file_templates.md` and the detailed structure lists in phase plans (05, 06, 07, 09) define the same files differently. Section names, ordering, and counts don't match.

Example:
- Template says country reference has 24 sections
- Phase 2 plan says 25 sections
- Template has "Buyer / counterparty classes" once
- Phase 2 plan splits it into "Obligated parties / buyer classes" AND "Buyer / counterparty classes"

**Impact:** Writers wouldn't know which version to follow. QA would have no single standard.

**Fix applied:** Updated `04_file_templates.md` to be the canonical single source of truth. Updated phase plans to reference the template instead of redefining sections.

---

### Issue 2: Buyer/Counterparty Section Duplication (HIGH)

**Problem:** `06_phase_2_country_reference_build.md` listed both "Obligated parties / buyer classes" and "Buyer / counterparty classes" as separate required sections (lines 110-111). These overlap significantly.

**Fix applied:** Merged into one section "Obligated parties / buyer classes" with clear guidance on what it must cover (legal obligation + commercial counterparty types).

---

### Issue 3: Asymmetry Tags Not Defined (MEDIUM)

**Problem:** Both `04_file_templates.md` and `05_phase_1_source_harvest.md` mention "asymmetry tags" as a metadata field, but no controlled vocabulary was defined. Without a standard set of tags, asymmetry tracking would be inconsistent.

**Fix applied:** Added an asymmetry tag taxonomy to `04_file_templates.md` with 8 standard tags covering definition boundaries, buyer obligations, certification recognition, chain of custody, timing windows, value capture, administrative friction, and proof asymmetry.

---

### Issue 4: Phase 0 and `00_program_requirements/` Undefined (MEDIUM)

**Problem:** `02_phased_execution.md` defines Phase 0 "Program Design" but has no dedicated plan file. `01_repository_structure.md` lists a `00_program_requirements/` folder but no plan defines its contents.

**Fix applied:** Added clarification to `02_phased_execution.md` that Phase 0 is covered by `00_overview.md` and `04_file_templates.md`. Updated `01_repository_structure.md` to note that `00_program_requirements/` content is distributed across existing plan files.

---

### Issue 5: Metadata Field Naming Inconsistency (MEDIUM)

**Problem:** `04_file_templates.md` uses Title Case ("Source title", "Regulator / issuer") while `05_phase_1_source_harvest.md` uses lowercase ("source title", "regulator"). This would cause inconsistency in generated files.

**Fix applied:** Normalized `05_phase_1_source_harvest.md` metadata table to use Title Case, matching `04_file_templates.md`.

---

### Issue 6: Agent Model Needs Single-Operator Note (LOW-MEDIUM)

**Problem:** `03_agent_operating_model.md` defines 10 specialized AI agents. In practice, execution may be done by one person or one AI tool. The agent model has no guidance for this scenario.

**Fix applied:** Added a "Single-Operator Execution" section to `03_agent_operating_model.md` explaining that the agent roles function as a responsibility matrix that one operator should follow sequentially.

---

### Issue 7: Strategy Template vs Phase 5 Structure (MEDIUM)

**Problem:** `04_file_templates.md` strategy template has 19 sections. `09_phase_5_strategy_output_build.md` lists 20 required sections with "Recommendation summary" missing from the template.

**Fix applied:** Added "Recommendation summary" to the strategy file template in `04_file_templates.md`.

---

### Issue 8: Biofuel Reference Template vs Phase 3 (MEDIUM)

**Problem:** `04_file_templates.md` biofuel template has 13 sections. `07_phase_3_biofuel_reference_build.md` lists 15 sections with different ordering and additional sections ("Worked example", "Related pathway files").

**Fix applied:** Updated the biofuel reference template in `04_file_templates.md` to match Phase 3's structure.

---

### Issue 9: Country Reference Template Section Ordering (LOW)

**Problem:** Section ordering in `04_file_templates.md` country reference template didn't match `06_phase_2_country_reference_build.md`. The phase plan has a more logical flow (diagrams before data, demand mechanism before buyer classes).

**Fix applied:** Reordered country reference template sections to match the Phase 2 plan.

---

### Issue 10: Wave 2 Priority Clarification (LOW)

**Problem:** `05_phase_1_source_harvest.md` lists jurisdictions under Wave 1 and Wave 2 but doesn't clearly state that Wave 2 means "secondary depth priority" not "excluded."

**Fix applied:** Added clarification to `05_phase_1_source_harvest.md` that Wave 2 jurisdictions receive full source registration but at a thinner evidence standard.

---

## What Is Correct and Strong

| Aspect | Assessment |
|---|---|
| Phase sequencing (evidence → analysis → strategy) | Correct |
| Wave 1 vs Wave 2 priority logic | Correct |
| 7 skills with all references | Complete (21 ref files present) |
| Strategy usefulness checklist | Strong, commercially focused |
| QA traceability model | Correct |
| Writing style guide approach | Strong |
| Source authority hierarchy | Correct (primary law → guidance → data → secondary) |
| Readiness scoring for Phase 1→2 gate | Correct |
| Update propagation order in Phase 7 | Correct |
| Diagram patterns and worked-example requirements | Consistent across phases |
| Risk and failure mode identification | Thorough in every phase plan |

---

## Skills Review

All 7 skills were reviewed. All reference files are present and cross-linked correctly.

| Skill | Ref files | Status |
|---|---|---|
| source-harvest | 3 | Complete |
| reference-planning | 3 | Complete |
| reference-writing-style | 3 | Complete |
| diagram-drawing | 2 | Complete |
| market-analysis | 3 | Complete |
| strategy-writing | 4 | Complete |
| evidence-traceability-qa | 3 | Complete |

---

## Current Use

This is a historical plan-quality review, not the current execution checklist. The plan set passed review on 2026-04-21 and the deliverable build has since been completed.

For team use now, start with:

1. `README.md` - repository entry point
2. `project.md` - project handoff
3. `deliverables/05_strategy_outputs/01_executive_strategy_summary.md` - portfolio answer
4. `deliverables/05_strategy_outputs/02_se_asia_producer_opportunity_map.md` - route-by-route view
5. `deliverables/04_market_analysis/01_global_market_comparison.md` - market comparison

Use the plan files as methodology and audit trail rather than as instructions to start execution from scratch.
