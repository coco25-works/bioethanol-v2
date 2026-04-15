# Plan Review Matrix

This file records the main review findings across the `plan/` set and the rewrite actions required to make the plans more comprehensive, consistent, and commercially useful.

## Review Matrix
| File | Intended role | Main strengths | Main gaps before rewrite | Required revision | Severity | Owner |
|---|---|---|---|---|---|---|
| `00_overview.md` | Set purpose and governing rules | Clear objective and layered model | Audience and commercial decision use were implicit | Make commercial / BD audience explicit and add buyer logic, stop-condition, and evidence-confidence principles | High | Program Orchestrator Agent |
| `01_repository_structure.md` | Define repository architecture | Clear market / pathway / strategy entry model | Strategy folder was not explicitly optimized for BD search behavior | Add BD entry-path requirement and README decision-support role | Medium | Editorial Integration Agent |
| `03_agent_operating_model.md` | Define ownership and handoffs | Strong phase ownership model | No explicit review function and no rule for fixing shared gaps at the highest reusable layer | Add plan-review function and upstream-first rewrite rule | Medium | Program Orchestrator Agent |
| `04_file_templates.md` | Set shared file requirements | Strong baseline templates | Missing shared commercial decision fields across all layers | Add audience, decision, buyer logic, decision criteria, disqualifiers, and evidence confidence fields | High | Editorial Integration Agent |
| `05_phase_1_source_harvest.md` | Source baseline plan | Strong evidence-first foundation | Needs to be interpreted through the strengthened shared templates rather than expanded independently | Enforce through template and QA updates | Low | Citation and Evidence QA Agent |
| `06_phase_2_country_reference_build.md` | Jurisdiction-level reference layer | Good market mechanics structure | Buyer classes existed but were not explicit enough for downstream BD use; no commercial decision criteria field | Add buyer / counterparty classes, commercial decision criteria, and what-would-change sections | High | Regional Legal Research Agents |
| `07_phase_3_biofuel_reference_build.md` | Pathway synthesis layer | Strong legal and pathway comparison logic | Commercial route competitiveness and proof burden were not explicit enough | Add route competitiveness and proof-burden section plus shared language | High | Comparative Analysis Agent |
| `08_phase_4_market_analysis_build.md` | Comparative demand and supply layer | Good ranking and comparison scaffolding | Rankings lacked an explicit disqualifier layer for BD triage | Add commercial attractiveness dimensions and disqualifier conditions | High | Comparative Analysis Agent |
| `09_phase_5_strategy_output_build.md` | Strategy layer | Strong modular strategy structure | Needed deeper buyer logic, timing logic, screening criteria, better-alternative logic, and evidence-confidence framing | Expand required strategy-file structure and add strategy-method support files | Critical | Strategy Architect Agent |
| `10_phase_6_final_qa_and_consolidation.md` | Hardening and final QA | Strong traceability and navigation framing | Did not explicitly test commercial usefulness of the strategy layer | Add strategy usefulness checklist review to QA criteria | Medium | Citation and Evidence QA Agent |
| `11_phase_7_update_operations.md` | Maintenance and refresh operations | Strong source-first update model | Did not explicitly refresh buyer logic, timing logic, or stop conditions | Add strategy-refresh triggers and checklist review in maintenance cycle | Medium | Program Orchestrator Agent |

## Cross-Plan Findings
### Strengths
- The repository structure is already coherent and scalable.
- The phase sequence correctly builds from evidence to interpretation to recommendation.
- The plan set already treats traceability seriously, which makes the strategy layer defensible.

### Gaps addressed by this review
- Commercial / BD audience was not explicit enough in the foundation files.
- Shared templates did not require decision-support fields across all layers.
- Strategy usefulness depended too much on implied upstream information.
- The strategy phase needed deeper buyer, timing, alternative-route, and stop-condition logic.
- QA and maintenance phases did not explicitly test whether strategy outputs remained useful, only whether they remained internally consistent.

## Review Outcome
The current plan set remains the correct foundation. The required action is targeted strengthening, not a structural restart.
