## MTC MoveMint v1.1.20

- Orders displays available stock as full cases and loose pieces for the order's warehouse. Zero availability and shortages highlight the stock code in red. Total pieces remain available in the collapsed columns.
- Tally Report finds the newest Pick List export automatically and accepts common Excel heading variations. Choose **N** and skip the SYSPRO sign-in to populate the three summary tabs from the export while preserving existing Orders.
- An inventory query failure preserves existing Orders. Workbook reruns preserve notes beside the generated columns, and the app reports when an open Excel workbook prevents saving.
- Download `MTC_MoveMint.exe` for manual installation. `PROCESS_AUTOMATION.exe` is the compatibility asset for existing update clients.

Verified with six regression tests, synthetic Excel data, and an offline startup check. Live SYSPRO and signed auto-update remain unverified. Server totals for status 8 use the DMS With Back Orders calculation.
