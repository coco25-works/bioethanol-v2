# Update Policy

**Last updated:** 2026-04-21  
**Purpose:** Define how the repository is kept current without breaking traceability or letting recommendations age silently.

### Why This File Matters
Regulatory change can make a strategy recommendation obsolete without warning. This policy ensures updates follow the evidence-first chain so strategy files never drift from the underlying rules.

## Update Workflow Diagram

```text
UPDATE PROPAGATION ORDER
┌──────────────────────────────────────┐
│ 1. Source register                   │
│ Detect and log regulatory change     │
└──────────────────────────────────────┘
               ↓
┌──────────────────────────────────────┐
│ 2. Country reference                 │
│ Update market mechanics if affected  │
└──────────────────────────────────────┘
               ↓
┌──────────────────────────────────────┐
│ 3. Pathway reference                 │
│ Update pathway treatment if affected │
└──────────────────────────────────────┘
               ↓
┌──────────────────────────────────────┐
│ 4. Market analysis                   │
│ Update rankings if affected          │
└──────────────────────────────────────┘
               ↓
┌──────────────────────────────────────┐
│ 5. Strategy outputs                  │
│ Review recommendation labels         │
└──────────────────────────────────────┘
               ↓
┌──────────────────────────────────────┐
│ 6. Change log + version update       │
│ Record what changed and why          │
└──────────────────────────────────────┘
```

## Update Triggers

An immediate review is triggered by:
- New law or regulation affecting any in-scope market
- Amendment affecting eligibility, caps, or buyer obligations
- Official guidance that changes interpretation of existing rules
- Certification-rule changes affecting scheme recognition
- Trade restrictions or fraud-enforcement changes
- Major compliance-market shifts that would alter analysis or strategy conclusions
- Changes in buyer eligibility, buyer concentration, or route access
- Changes to definitions, threshold methods, registry access, transferability, or transition windows

## Refresh Cadence

| Layer | Review frequency | Trigger for immediate review |
|---|---|---|
| Source register (Wave 1 jurisdictions) | Quarterly + event-driven | Any trigger above |
| Source register (Wave 2 jurisdictions) | Semiannual or material-change | Any trigger above |
| Country reference | After source register update | Source register change affecting market mechanics |
| Pathway reference | After country reference update | Country reference change affecting pathway treatment |
| Market analysis | After pathway/country update | Reference change affecting rankings |
| Strategy outputs | Only after analysis layer changes | Analysis change affecting recommendation labels |
| Watchlists | Quarterly review | New regulatory development |

## File-Update Order (Critical Rule)
Updates MUST follow the evidence-first chain:
1. Source register (log the new evidence)
2. Country reference (update market interpretation)
3. Pathway reference (update pathway treatment)
4. Market analysis (update comparisons and rankings)
5. Strategy outputs (review and update recommendation labels)
6. Change log and version update (record the propagation)

**Never update strategy without updating upstream layers first.**

## Ownership Model

| Layer | Owner | QA reviewer |
|---|---|---|
| Source register (EU) | EU-UK Legal Research agent | Citation and Evidence QA agent |
| Source register (Americas) | Americas Legal Research agent | Citation and Evidence QA agent |
| Source register (APAC) | APAC Legal Research agent | Citation and Evidence QA agent |
| Country reference | Regional agents | Citation and Evidence QA agent |
| Pathway reference | Comparative Analysis agent | Citation and Evidence QA agent |
| Market analysis | Comparative Analysis agent | Citation and Evidence QA agent |
| Strategy outputs | Strategy Architect agent | Citation and Evidence QA agent |
| Change log | Editorial Integration agent | Program Orchestrator agent |

## Related Files
- [05_regulatory_watchlist.md](05_regulatory_watchlist.md)
- [06_pathway_watchlist.md](06_pathway_watchlist.md)
- [07_change_log.md](07_change_log.md)
- [09_versioning_rules.md](09_versioning_rules.md)
