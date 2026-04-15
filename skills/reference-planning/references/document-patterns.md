# Document Patterns

Use these patterns when planning the repository layout.

## Recommended layers
- `source register`: one file per jurisdiction; log sources and metadata only.
- `entity reference`: one file per jurisdiction, product family, standard, or comparable unit; explain how it works.
- `pathway reference`: one file per pathway, product family, method, or comparable class; compare treatment across entities.
- `market analysis`: one file per analytical question; compare combinations and rank them.
- `strategy`: one file per decision subject; recommend, gate, and reject.
- `appendices`: glossary, citation index, gap log, QA, update policy.

## File allocation rules
- One jurisdiction per source file.
- One entity per entity-reference file.
- One pathway, product family, method, or topic per pathway file.
- One decision question per strategy file.
- One comparison question per market-analysis file.

## Folder README pattern
Every content folder should identify:
- what it contains;
- what decision it supports;
- how a reader should enter it;
- which upstream and downstream folders connect to it.

## Good planning questions
- What must a BD reader learn here?
- What must a legal or compliance reader validate here?
- What information must the next phase inherit from this file?
