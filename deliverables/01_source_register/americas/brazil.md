# Brazil Source Register

**Primary audience:** Commercial / BD team assessing Brazilian biofuel context
**Decision supported:** What is the regulatory basis for bio-based fuels in Brazil and how does it affect competitive dynamics
**Coverage scope:** Brazilian biofuel legislation, RenovaBio, and relevant fuel policy
**Baseline date:** 2026-04-21
**Wave:** 2

## Why This Market Matters
Brazil is the world's second-largest biofuel producer after the US. Its RenovaBio program creates a CBIO (crédito de descarbonização) credit system that functions similarly to tradable compliance credits in other markets. Brazil's dominance in sugarcane ethanol and soybean biodiesel means it is a competitive reference model and a price-setter for conventional biofuel globally. Understanding Brazilian policy matters for assessing competitive positioning and feedstock flows.

### What this means for non-specialists
Brazil is a competitor and benchmark market, not a primary export target. The key evidence concern is that Brazilian legal texts are in Portuguese; no official English translations exist.

## Source-Stack Diagram

```text
                  BRAZIL SOURCE STACK
┌─────────────────────────────────────────────────────┐
│ Primary law and policy                              │
│ RenovaBio (Decree 9.045/2017) / ANP regulations    │
└─────────────────────────────────────────────────────┘
                       ↓
┌─────────────────────────────────────────────────────┐
│ Implementation layer                                │
│ ANP guidance / CBIO program / CNPE resolutions      │
└─────────────────────────────────────────────────────┘
                       ↓
┌─────────────────────────────────────────────────────┐
│ Data and compliance layer                           │
│ ANP reporting / CBIO data / UNICA statistics        │
└─────────────────────────────────────────────────────┘
```

## Primary Laws and Regulations

| Source title | Source type | Regulator / issuer | Date | Effective date | In-force status | Amendment or version status | Sunset / grandfathering / transition window | Jurisdictional level | Language | Official translation status | Citation location | Link | Topic tags | Asymmetry tags | Implementing dependency | Quoted rule text or extraction note | Relevance note | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| RenovaBio (Law 13.576/2017) | Primary law | Brazilian Congress | 2017-12-26 | 2018-01-01 | In force | Original | Program through 2030 (CBIO targets) | National | PT | No official English translation | Art. 1-2 purpose; Art. 3 definitions; Art. 5 CBIO | Planalto (BR) | blending mandate; quota obligation; tradable credit system; pathway definitions | buyer_obligation_trigger; value_capture | ANP implements; CNPE sets targets | Creates national biofuel policy framework and CBIO credit system | Core Brazilian biofuel demand mechanism | Confirmed |
| Decree 9.045/2017 (RenovaBio regulation) | Primary law | Brazilian Federal Government | 2017-05-11 | 2017-05-11 | In force (amended) | Amended multiple times | Annual CBIO targets | National | PT | No official English translation | CBIO issuance rules; obligated parties | Planalto (BR) | quota obligation; tradable credit system; blending mandate | buyer_obligation_trigger; value_capture | ANP implements | Defines RenovaBio implementation, CBIO issuance, obligated parties | Implementation detail for CBIO program | Confirmed |
| CNPE Resolution 11/2019 (Biodiesel blending mandate) | Primary law | Conselho Nacional de Política Energética | 2019 | 2019 | In force | Amended — B13 to B15 phased increase | B15 from 2023; planned increase to B20 | National | PT | No official English translation | Blending percentage | ANP (BR) | blending mandate; pathway definitions; quota obligation | timing_window | ANP monitors compliance | Sets biodiesel blending at B15 (15% palm/soybean blend) | Domestic biodiesel demand driver | Confirmed |
| ANP Resolution 807/2020 (Fuel quality specifications) | Implementing rule | Agência Nacional do Petróleo | 2020 | 2020 | In force | Amended | N/A | National | PT | No official English translation | Fuel specifications | ANP (BR) | blending mandate; pathway definitions | definition_boundary | Fuel producers | Sets fuel quality specs including biodiesel and ethanol blending | Technical fuel quality standard | Confirmed |
| RenovaBio CBIO program documentation | Official guidance | ANP | Updated annually | N/A | Active | Annual CBIO target updates | Annual | National | PT | No official English translation | CBIO issuance and trading rules | ANP (BR) | tradable credit system; implementation or compliance mechanics | value_capture | ANP operates CBIO platform | Details CBIO issuance, trading, and compliance | Practical implementation reference | Confirmed |

## Official Guidance and Compliance References

| Source title | Source type | Regulator / issuer | Date | In-force status | Link | Topic tags | Status |
|---|---|---|---|---|---|---|---|
| ANP RenovaBio program page | Official guidance | ANP | Updated regularly | Active | ANP website (PT) | implementation or compliance mechanics | Confirmed |
| CNPE resolutions on biofuel mandates | Official guidance | CNPE | Various | Active | Planalto (PT) | blending mandate; quota obligation | Confirmed |

## Official Data Sources

| Source title | Source type | Regulator / issuer | Date | In-force status | Link | Topic tags | Status |
|---|---|---|---|---|---|---|---|
| ANP annual biofuel statistics | Official data | ANP | Annual | Active | ANP (PT) | implementation or compliance mechanics | Confirmed |
| CBIO market data | Official data | ANP | Updated regularly | Active | ANP (PT) | tradable credit system; value_capture | Confirmed |
| UNICA sugarcane industry data | Secondary context | UNICA (industry association) | Updated regularly | Active | UNICA (EN/PT) | N/A | Secondary only |

## Open Source Gaps

| Jurisdiction | Missing or uncertain source | Why it matters | Blocking level | Likely resolution path | Status |
|---|---|---|---|---|---|
| Brazil | English translations of RenovaBio law and decrees | Language barrier for non-Portuguese speakers | Medium | Use unofficial translations; content is well-documented internationally | Open |
| Brazil | CBIO pricing data accessibility | Needed for value comparison with EU/US credit markets | Medium | ANP publishes data but in Portuguese | Open |
| Brazil | B20 mandate implementation timeline | Planned increase from B15 to B20 — timing affects domestic soybean demand | Low | Monitor CNPE resolutions | Open |

## Phase 2 Readiness

```text
Phase 2 readiness: Ready

Ready:
- core legal instruments logged (RenovaBio, CNPE blending mandates, ANP implementing rules)
- major guidance logged (ANP program documentation)
- official data sources logged (ANP statistics, CBIO data)
- translation gaps flagged but not blocking
```

**Current status:** Ready for Phase 2. Brazil is primarily a competitor/reference rather than a target market.

## Related Files
- [../americas/united_states_federal.md](../americas/united_states_federal.md)
