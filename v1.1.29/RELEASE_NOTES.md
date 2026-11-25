## MTC MoveMint v1.1.29

- Tally stock codes with positive **Stock Free** no longer turn yellow when **Available Total PCS** is zero or negative. The existing red warning for zero or negative **On Hand** still applies.
- Refresh closes the saved Tally workbook at its exact path. If it has unsaved edits, Tally asks you to save them before trying again.
- Each successful Tally save prints total calls and the total amount in PHP in the terminal.
- Download `MTC_MoveMint.exe` for manual installation. `PROCESS_AUTOMATION.exe` is the compatibility asset for existing update clients.

Verified with 36 automated tests and a synthetic macro-enabled workbook in Microsoft Excel.
