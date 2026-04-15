---
name: evidence-traceability-qa
description: Validate evidence chains, consistency, and update impact across layered reference repositories. Use when Codex needs to check that strategy claims trace back to analysis and sources, terminology is consistent, recommendation labels are coherent, unresolved issues are visible, or update propagation follows the evidence-first workflow.
---

# Evidence Traceability QA

Use this skill for repository hardening, final QA, and maintenance checks.

## Workflow
1. Pick the claim, label, or file being checked.
2. Trace it down through the layer below it.
3. Confirm terminology and label consistency across parallel files.
4. Log unresolved issues explicitly.
5. Confirm update propagation order for any changed input.

## Core Rules
- Strategy must trace back to analysis, then to the relevant reference layer, then to source.
- QA should catch contradictions, not just missing citations.
- Uncertainty should be surfaced, not polished away.
- Strategy usefulness is part of QA, not an optional extra.

## Use These References
- Read [references/traceability-checks.md](references/traceability-checks.md) for evidence-ladder checks.
- Read [references/consistency-checks.md](references/consistency-checks.md) for label and terminology review.
- Read [references/update-impact-checks.md](references/update-impact-checks.md) for refresh and propagation checks.

## Output Expectations
- Make the document system safer to trust.
- Catch broken evidence chains and inconsistent strategy logic.
- Preserve the evidence-first design during updates.
