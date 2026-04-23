# France Source Register

**Primary audience:** Commercial / BD team screening French biofuel opportunities
**Decision supported:** Which French regulations create demand for bio-based fuels and how the TIRUERT system works
**Coverage scope:** French transport fuel compliance system, TIRUERT, and implementation of EU directives
**Baseline date:** 2026-04-21
**Wave:** 1

## Why This Market Matters

France operates the TIRUERT (taux d'incorporation des biocarburants dans les carburants) system, a volumetric biofuel blending obligation under the Code de l'énergie. Unlike Germany's GHG-based quota, France mandates a minimum percentage of biofuel energy content in transport fuels. France has also taken a distinctive position on feedstock restrictions — notably capping or excluding palm-oil-based biodiesel under specific conditions — creating asymmetries that affect commercial access. The obligation is implemented by DGEC (Direction générale de l'énergie et du climat) with compliance data tracked by SDES (Service des données et des études statistiques).

### What this means for non-specialists
France is a real European market with demand, but it is narrower and more constrained than Germany or the Netherlands for imported supply. The key evidence concern is that French legal texts are in French; no official English translations exist for most instruments.

## Source-Stack Diagram

```text
                  FRANCE SOURCE STACK
┌─────────────────────────────────────────────────────┐
│ Primary law                                         │
│ Code de l'énergie / Code des douanes                │
└─────────────────────────────────────────────────────┘
                       ↓
┌─────────────────────────────────────────────────────┐
│ Implementing and interpretive layer                 │
│ Décret n° 2019-570 / Arrêtés / DGEC guidance       │
└─────────────────────────────────────────────────────┘
                       ↓
┌─────────────────────────────────────────────────────┐
│ Compliance and market-reference layer               │
│ DGEC reporting / SDES official statistics           │
└─────────────────────────────────────────────────────┘
```

## Primary Laws and Regulations

| Source title | Source type | Regulator / issuer | Date | Effective date | In-force status | Amendment or version status | Sunset / grandfathering / transition window | Jurisdictional level | Language | Official translation status | Citation location | Link | Topic tags | Asymmetry tags | Implementing dependency | Quoted rule text or extraction note | Relevance note | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Code de l'énergie (Energy Code) — contains TIRUERT obligation | Primary law | French Parliament | Ongoing (originally 2011) | Various | In force | Multiple amendments; TIRUERT obligation in L.641-1 et seq. | Obligation levels set annually by decree | National | FR | No official English translation | L.641-1 to L.641-6 (Title IV, Book VI — biocarburants) | [legifrance.gouv.fr](https://www.legifrance.gouv.fr/codes/texte_lc/LEGITEXT000006069577/) | blending mandate; volumetric obligation; biocarburants; TIRUERT | buyer_obligation_trigger; definition_boundary | DGEC implements; Décret and Arrêtés set annual levels | L.641-1 establishes the obligation for fuel distributors to incorporate biocarburants at a minimum rate | Core French demand mechanism; creates volumetric biofuel blending obligation | Confirmed |
| Code des douanes (Customs Code) — biofuel tax treatment | Primary law | French Parliament | Ongoing (originally 2009 reform) | Various | In force | Amended periodically for biofuel tax incentives | Tax treatment provisions subject to annual finance laws | National | FR | No official English translation | Articles related to taxe intérieure de consommation (TIC) and biofuel exemptions / reductions | [legifrance.gouv.fr](https://www.legifrance.gouv.fr/codes/texte_lc/LEGITEXT000006155078/) | tax treatment; fiscal incentives; energy taxation; TIC reduction | fiscal_asymmetry; value_capture | Customs administration (DGDDI) implements | Defines fiscal treatment of biofuels vs fossil fuels; TIC reductions for biofuel blend volumes | Fiscal incentive layer that shapes commercial economics | Confirmed |
| Décret n° 2019-570 — TIRUERT implementation | Decree (secondary law) | French Government (Premier ministre) | 2019-05-28 | 2019 | In force | Updated annually via new arrêtés setting obligation rates | Annual obligation rates set for upcoming compliance years | National | FR | No official English translation | TIRUERT obligation rates; compliance mechanics; penalty provisions | [legifrance.gouv.fr](https://www.legifrance.gouv.fr/) | blending mandate; obligation rate; compliance year; penalty mechanics | administrative_friction; timing_window | DGEC administers; fuel suppliers report | Sets the framework for annual TIRUERT obligation rates and reporting obligations for fuel suppliers | Key decree governing annual obligation levels | Confirmed |
| Arrêté du 13 décembre 2018 — biofuel counting methodology | Arrêté (ministerial order) | Ministry of Ecological Transition | 2018-12-13 | 2019 | In force | May be updated by subsequent arrêtés | N/A | National | FR | No official English translation | Counting methodology for biocarburants toward TIRUERT | [legifrance.gouv.fr](https://www.legifrance.gouv.fr/) | counting rules; methodology; biocarburants; pathway definitions | definition_boundary; chain_of_custody_model | DGEC implements | Defines how biocarburant volumes are counted toward the TIRUERT obligation, including energy content conversion factors | Technical methodology document for compliance calculation | Confirmed |
| Arrêté fixant le TIRUERT — annual obligation rate | Arrêté (ministerial order) | Ministry of Ecological Transition (via DGEC) | Annually (e.g., 2025 arrêté) | January 1 of applicable year | In force | Annual update | Applicable to single compliance year | National | FR | No official English translation | Annual TIRUERT rate (percentage of energy content) | [legifrance.gouv.fr](https://www.legifrance.gouv.fr/) | obligation rate; blending mandate; volumetric obligation | timing_window | DGEC publishes | Sets the specific TIRUERT percentage for the applicable compliance year (e.g., 9.1% for 2025 energy content) | Directly determines demand volume; changes annually | Confirmed |
| Arrêté palmier — palm oil restrictions in biocarburants | Arrêté (ministerial order) | Ministry of Ecological Transition | 2019-06-13 | 2019-07-01 | In force | Phased restrictions | Cap reduced to 0% of TIRUERT obligation from 2026 for HVO from palm oil | National | FR | No official English translation | Restrictions on palm-oil-based HVO counting toward TIRUERT | [legifrance.gouv.fr](https://www.legifrance.gouv.fr/) | feedstock restriction; palm oil; HVO; exclusion; counting rules | palm_oil_exclusion; market_access_asymmetry | DGEC implements | Caps counting of HVO produced from palm oil toward TIRUERT obligation; effectively excludes it from 2026 onward | Key feedstock restriction creating market asymmetry for palm-oil-based biodiesel | Confirmed |
| Biocarburants sustainability and GHG methodology | Primary law (implementing RED) | French Government | Various (original 2010; updated for RED II) | Various | In force | Updated to align with RED II/III sustainability criteria | N/A | National | FR | No official English translation | Sustainability criteria; GHG lifecycle calculation; double counting for waste | [legifrance.gouv.fr](https://www.legifrance.gouv.fr/) | certification; sustainability criteria; lifecycle GHG; double counting; waste or residue proof | certification_recognition; proof_asymmetry | Certifying schemes must be recognized by competent authority | Implements RED sustainability and GHG savings requirements at national level; defines double counting eligibility | Defines proof requirements and sustainability compliance for biofuel volumes counted toward TIRUERT | Confirmed |

## Official Guidance and Compliance References

| Source title | Source type | Regulator / issuer | Date | Effective date | In-force status | Amendment or version status | Sunset / grandfathering / transition window | Jurisdictional level | Language | Official translation status | Citation location | Link | Topic tags | Asymmetry tags | Implementing dependency | Quoted rule text or extraction note | Relevance note | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| DGEC — TIRUERT compliance guidance | Official guidance | DGEC (Direction générale de l'énergie et du climat) | Updated periodically | N/A | In force | Updated annually with new obligation rates | N/A | National | FR | No official English translation | Reporting procedures; obligation compliance; submission deadlines | [ecologie.gouv.fr](https://www.ecologie.gouv.fr/) | implementation or compliance mechanics; quota obligation; penalty mechanics | administrative_friction | DGEC is the implementing authority | Practical guidance on TIRUERT compliance, reporting obligations, and submission deadlines for fuel suppliers | Main implementation reference for obligated parties in France | Confirmed |
| DGEC — biofuel pathway and counting guidance | Official guidance | DGEC | Updated periodically | N/A | In force | Updated as pathway definitions evolve | N/A | National | FR | No official English translation | Pathway definitions; counting methodology; eligible biocarburants | [ecologie.gouv.fr](https://www.ecologie.gouv.fr/) | pathway definitions; counting rules; definition_boundary | definition_boundary | DGEC publishes | Guidance on which biocarburant pathways count toward TIRUERT and at what multipliers | Clarifies which products and routes are eligible for compliance counting | Confirmed |

## Official Data Sources

| Source title | Source type | Regulator / issuer | Date | Effective date | In-force status | Amendment or version status | Sunset / grandfathering / transition window | Jurisdictional level | Language | Official translation status | Citation location | Link | Topic tags | Asymmetry tags | Implementing dependency | Quoted rule text or extraction note | Relevance note | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| SDES — biocarburants statistics | Official data | SDES (Service des données et des études statistiques) | Annual | N/A | Active | Updated annually | N/A | National | FR | No official English translation | Annual biocarburant incorporation volumes; production; imports; TIRUERT compliance | [sdes.data.gouv.fr](https://sdes.data.gouv.fr/) | implementation or compliance mechanics; production volumes; import data | value_capture | SDES publishes annually | Volume of biocarburants incorporated, production data, import volumes, TIRUERT compliance rates | Market size and compliance data for France | Confirmed |
| SDES — chiffres clés de l'énergie | Official data | SDES | Annual | N/A | Active | Updated annually | N/A | National | FR | No official English translation | Key energy statistics for France; transport fuel breakdown | [sdes.data.gouv.fr](https://sdes.data.gouv.fr/) | transport fuel data; energy mix; consumption statistics | N/A | SDES publishes annually | Official energy statistics including transport fuel consumption breakdown | Reference data for market sizing | Confirmed |
| DGEC — annual TIRUERT compliance reporting | Official data | DGEC | Annual | N/A | Active | Updated annually | N/A | National | FR | No official English translation | Annual compliance data; obligation fulfillment rates | [ecologie.gouv.fr](https://www.ecologie.gouv.fr/) | implementation or compliance mechanics; obligation rate | N/A | DGEC publishes | Aggregated TIRUERT compliance data reported by obligated parties | Official compliance outcome data | Confirmed |

## Open Source Gaps

| Jurisdiction | Missing or uncertain source | Why it matters | Blocking level | Likely resolution path | Status |
|---|---|---|---|---|---|
| France | English translation of Code de l'énergie TIRUERT provisions | Language barrier for non-French-speaking BD team | Medium | Use unofficial translation; flag confidence limits; engage French legal counsel | Open |
| France | English translation of Décret n° 2019-570 | Need to verify exact obligation mechanics in English | Medium | Use unofficial translation; flag confidence limits | Open |
| France | English translation of palm oil restriction arrêté | Key asymmetry source; must understand exact scope and phasing | Medium | Obtain French-language full text; commission translation | Open |
| France | English translation of SDES biocarburants statistics | Market data behind language barrier | Low | Use browser translation; flag data confidence | Open |
| France | Official English versions of counting methodology arrêté | Technical counting rules only available in French | Medium | Obtain French text; engage technical translator | Open |

## Phase 2 Readiness

```text
Phase 2 readiness: Ready

Ready:
- core legal instruments logged (Code de l'énergie, Code des douanes, Décret n° 2019-570, key arrêtés)
- major guidance logged (DGEC compliance and pathway guidance)
- official data sources logged (SDES biocarburants statistics, DGEC compliance data)
- key asymmetry logged (palm oil exclusion / cap with phased timeline)
- no critical source gaps blocking Phase 2
- translation gaps flagged but not blocking (French-language sources with known content)
```

**Current status:** Ready for Phase 2. All primary instruments, implementing decrees, guidance, and data sources are identified. Translation gaps are flagged; French legal counsel should be engaged for high-confidence interpretation of TIRUERT obligation mechanics and palm oil exclusion scope.

## Related Files
- [01_eu_level.md](01_eu_level.md)
- [02_germany.md](02_germany.md)
- [03_netherlands.md](03_netherlands.md)
