## MTC MoveMint v1.1.19

- Orders shows Available Qty in whole pieces using each SKU's SYSPRO conversion and the balance for the order's warehouse. Stock codes in column C are red when no stock is available. If a piece conversion is unavailable, the piece count stays blank and the original balance is in the collapsed detail columns.
- After you enter sales order IDs, choose **Y** to fill Salesperson Summary, S.O. to Rectify, and All Transactions from SYSPRO. For status-8 orders, the totals use the DMS **With Back Orders** calculation.
- Choose **N** or press Enter to use the working day's Pick List export, including `pickSO_PICKLIST_REPORT.xls`. If there are no matching export rows, the three sheets stay blank.
- Download `MTC_MoveMint.exe` for manual installation. `PROCESS_AUTOMATION.exe` is the compatibility asset for existing update clients.

Verified with synthetic sales orders and inventory balances and a copy of the macro-enabled Tally Report. Live SYSPRO quantities and signed auto-update were outside this validation.
