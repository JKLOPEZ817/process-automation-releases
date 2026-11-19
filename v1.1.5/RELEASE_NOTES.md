## MTC MoveMint v1.1.5

- The desktop app now displays the MTC MoveMint name.
- Tally Orders asks the operator for SYSPRO credentials with hidden password entry and includes SKU details once per sales order. Operators can skip the Orders query and still generate the other sheets.
- Loadsheet titles retain the full route and salesperson suffix. Repeated product and customer column headings are hidden while detail rows are preserved.
- The licensing dashboard supports temporary device approvals and displays recent app launches and process selections reported by v1.1.5 clients.

Requires Windows and Excel for workbook automation. Orders enrichment requires access to SYSPRO and a template with an Orders sheet.

Validated the Windows build and tested Loadsheet formatting in Excel with synthetic data. The Orders query was tested with a mocked connection.
