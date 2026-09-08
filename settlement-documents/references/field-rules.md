# Settlement-document field rules

## Cross-checks

- Match the purchase-contract factory name against ISF manufacturer/container-stuffing entity. Stop if they differ materially.
- Copy FDA registration only from ISF manufacturer data, never a Chinese plant-registration number or carton code.
- Match net/gross weight, cartons, container and seal across all documents.
- Use final B/L or carrier tracking identifiers; never retain template values.

## COA

- Description table: product, net weight, cartons and every lot from phytosanitary certificate.
- Carton table: product, manufacture date from carton photo/code, best-before +2 years, verified factory name/address and ISF FDA number.

## Shipping Advice and GMO

- Update HBL, MBL, container, seal, carrier, vessel/voyage, ports, ETD/ETA, product, net weight, cartons and lots.
- Reopen the saved DOCX and embedded workbook. Inspect PDF separately because embedded-object previews can be stale.
- After row edits, check the total-row line and units; legacy formulas and merged cells can shift these.

## Client DDP invoice

- Add PO product specifications beneath product name.
- Keep total equal to contract/settlement invoice. Do not substitute customs price.
- Use PO DDP city/address.
