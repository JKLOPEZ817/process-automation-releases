## MTC MoveMint v1.1.13

- Tally Report fetches SYSPRO stock lines by the exact sales order IDs selected in DMS. Paste the current DMS list, or use the SO Pick List Report or CM files for the selected DMS folder dates.
- The report saves in the current working-date folder. Existing Orders rows are preserved, and repeat runs skip orders already listed.
- The verified DMS batch contained 178 orders and 508 stock lines, including 12 type T orders and two orders entered on an earlier date.
- Download MTC_MoveMint.exe for manual installation. PROCESS_AUTOMATION.exe is provided for existing update clients.

The packaged Windows executable passed an offline startup check. The workbook update was tested with simulated stock lines. The packaged Tally Report was not run against live SYSPRO.
