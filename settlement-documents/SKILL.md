---
name: settlement-documents
description: Prepare Chinese frozen-food export settlement documents: client DDP invoices, Shipping Advice, COA, and GMO declarations. Use when a user asks to make, fill, or correct a shipment's 结汇文件.
---

# Frozen-food settlement documents

Preserve the existing Word templates, including stamps, signatures and layout. Update both visible Word text and each embedded Excel/OLE table; editing a preview image alone is incomplete.

Unless the user narrows scope, prepare DDP invoice, Shipping Advice, COA and GMO. Save editable DOCX files in `结汇\word原件` and matching PDFs in `结汇`.

## Sources

Use customer PO/sales contract for client address, DDP location, product specifications and pricing. Use settlement invoice/contract for invoice/order, quantities and total. Use the phytosanitary certificate for lots, product, weights and cartons. Use carton photo/production code for manufacture date, with best-before normally two years later. Use purchase contract for factory name; use ISF manufacturer block for factory address and FDA registration, cross-checking the name against the purchase contract. Use B/L and final carrier tracking for transport fields.

Read [field rules](references/field-rules.md) before filling documents.

## Method

1. Copy a comparable completed template; never overwrite the source template.
2. Inventory all visible fields and embedded OLE/Excel objects.
3. Fill Word text and embedded workbooks with identical data. Explicitly save and reopen each embedded workbook to confirm persistence.
4. Preserve seals/signatures. Do not rebuild documents unless the user asks.
5. Export PDFs, render every page, and correct stale previews, clipping, duplicate totals, missing units, shifted lines and lost stamps before delivery.

## Non-negotiable field rules

- List every phytosanitary-certificate lot in the COA/GMO description table. The carton code used for manufacture date is not a replacement for this field.
- COA dates use uppercase English month format such as `AUG/18/2026`, unless the template explicitly differs.
- DDP delivery location comes from the PO, not the port of discharge. Add PO product specifications under the invoice product name when present.
- Shipping Advice heavy line is directly above `TOTAL:`. The total row must contain net weight plus `KGS` and carton count plus `CTNS`, exactly once.
- If sources conflict, report the conflict rather than choosing silently.
