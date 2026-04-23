# Versioning Rules

**Last updated:** 2026-04-21  
**Purpose:** Define how the repository is versioned during updates.

### Why This File Matters
Without clear versioning rules, different people may work on different versions without knowing it. This file prevents that confusion.

## Versioning Approach
- Major versions (v1.0, v2.0) are created when a complete refresh cycle is done across all layers.
- Minor versions (v1.1, v1.2) are created when material updates are made to specific layers.
- Patch updates (corrections, formatting) do not require a version bump.

## Version Number Rules

| Change type | Version bump | Example |
|---|---|---|
| Complete refresh across all layers | Major (v1.0 → v2.0) | Annual comprehensive review |
| Material update to one or more layers with downstream impact | Minor (v1.0 → v1.1) | RED III transposition update |
| Correction or clarification without substantive change | No bump | Typo fix, link update |

## Change Classification

| Classification | Definition | Required action |
|---|---|---|
| Source only | Source register updated; no downstream impact yet | Log in change log; monitor for downstream impact |
| Analysis affecting | Source or reference change that affects market analysis or rankings | Update affected analysis files; log in change log |
| Strategy affecting | Analysis change that affects recommendation labels or strategy conclusions | Update affected strategy files; run strategy usefulness checklist; log in change log |

## What Triggers a Strategy Review
- Any change that affects buyer logic, timing, or stop conditions in an upstream file
- Any change that alters the legal asymmetry underlying a strategy recommendation
- Any change that affects the credit/premium value structure in a target market

## Version Release Process
1. Complete upstream updates following the evidence-first chain
2. Run QA checks (traceability, consistency)
3. Update change log with version entry
4. Update "Last updated" dates in affected files
5. Review strategy usefulness checklist for any affected strategy files

## Related Files
- [update_policy.md](update_policy.md)
- [change_log.md](change_log.md)
- [final_qa_checklist.md](final_qa_checklist.md)
