# ISF field rules

Use these rules with the closest approved ISF example. The example controls exact presentation when it differs from general conventions.

| ISF area | Value rule |
|---|---|
| SCAC CODE & MBL# | `<MBL SCAC>/<full MBL>`; preserve prefixes shown in the user's source, e.g. `CMDU/CMDUQGD3389390`. |
| SCAC CODE & HBL# | `<HBL SCAC>/<HBL>`; this field is not an AMS-number field unless the template or approved example explicitly makes it one. |
| Seller | Current seller/exporter name and address. Preserve the approved spelling and address format when unchanged. |
| Consolidator | Use the party and address supported by the current shipment or the unchanged approved reference. Do not add a source note. |
| Manufacturer | Manufacturer name, physical address, and FDA registration number when supported. |
| Container stuffing location | Physical loading location. In this user's established forms it commonly repeats the manufacturer and FDA number; verify against the shipment documents. |
| Buyer / Ship to / Consignee | Use the corresponding current party. Do not assume these are identical unless supported by the current documents or unchanged approved reference. |
| Importer / IRS / Bond / Surety / Forwarding agent / HTS | Preserve approved values only when known to apply; otherwise leave blank. |
| Vessel & voyage | Match the standard style, commonly `<VESSEL> V.<VOYAGE>`. |
| Port of loading / unloading | Match the destination shown in the standard ISF rather than automatically copying port-of-discharge terminology from a B/L. |
| Container | `<CONTAINER>/<SEAL>`. |
| Container type | Match the standard, commonly `40'RH`, without adding `1 X` unless the example uses it. |
| Departure / arrival | Use shipment-specific carrier dates. Match the example format, commonly `MMM.DD.YYYY`, with no time or ETD/ETA labels. |
| Quantity | In the established examples, enter gross weight in kilograms, e.g. `21794.000KGS`; do not substitute net weight or carton count. |
| Commodity description | One line per commodity as `<DESCRIPTION>/<CARTONS>CTNS`. |
| Line below commodities | Enter the carrier booking/MBL reference without the SCAC prefix when that is how the approved example is completed, e.g. `QGD3389390`. Do not add transshipment or status notes. |
| Country of origin | One `CHINA` entry per populated commodity row when China is supported as origin. |
| Containerized | Preserve the approved example's selected value and appearance; verify visually because PDF radio-button state can be misleading. |

## Common failure patterns

- Adding operational notes into the commodity table.
- Filling net weight when the standard uses gross weight.
- Adding time and `(ETD)` / `(ETA)` to date-only fields.
- Omitting the FDA registration number from manufacturer or stuffing location.
- Writing the AMS number into the HBL field merely because both are supplied.
- Adding PO number to the part-number field when the standard leaves that field blank.
- Changing common party formatting instead of retaining the approved reference values.
- Appending `_DRAFT` or removing the `#` from `PO#` in the filename.
