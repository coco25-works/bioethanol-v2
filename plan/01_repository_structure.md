# Repository Structure Plan

## Structure Goal
Organize the repository so a reader can enter the material from three directions:
- by jurisdiction;
- by fuel pathway;
- by strategy question.

The same structure must also make it easy to find legal asymmetries across similar-looking markets, especially in the Wave 1 markets where the deepest cross-market delta work happens first.

For the primary commercial / BD audience, the strategy route must answer five questions quickly:
- which market;
- which pathway;
- which buyer class;
- under what gating conditions;
- and under what stop conditions.

For asymmetry-focused work, the repository must also answer:
- what exact rule difference creates the opportunity;
- whether the difference is legal, administrative, proof-related, or temporal;
- who captures the value created by that difference.

## Target Layout
```text
/plan
/00_program_requirements          ← content distributed across plan files (00_overview.md, 04_file_templates.md, 01_repository_structure.md)
/01_source_register
  /eu
  /americas
  /apac
/02_country_reference
  /eu
  /americas
  /apac
/03_biofuel_reference
/04_market_analysis
/05_strategy_outputs
  /pathway_strategy
  /market_entry_strategy
  /producer_type_strategy
  /partnerships
  /risk_and_no_go
/06_appendices
```

## File Allocation Rules
### Source register
- One file per jurisdiction.
- Purpose: log sources, not conclusions.

### Country reference
- One file per jurisdiction.
- Purpose: explain the market's regulatory logic and access conditions.

### Biofuel reference
- One file per major fuel or feedstock topic.
- Purpose: compare pathway treatment across jurisdictions.

### Market analysis
- One file per analytical question.
- Purpose: compare markets, demand mechanisms, and supply fit.
- Include dedicated outputs for legal-asymmetry comparison where small rule differences materially change opportunity.

### Strategy outputs
- One file per strategy subject.
- Purpose: produce recommendation-ready outputs without mixing them into legal reference files.
- Strategy files must be discoverable by market-entry question and by decision type, not only by pathway family.

## Naming Standard
- Use lowercase snake-case style with words separated by underscores.
- Use explicit jurisdiction or topic names.
- Avoid generic names like `notes.md` or `summary.md`.

## Folder READMEs
Each top-level content folder should include a `README.md` that does four jobs:
1. explains what the folder contains;
2. tells the reader how to use it;
3. links to the most important files;
4. points to related folders.

Each `README.md` should also identify:
5. the main decision the folder supports;
6. the best entry points for BD readers;
7. the upstream folders the reader should consult when more evidence detail is needed.
