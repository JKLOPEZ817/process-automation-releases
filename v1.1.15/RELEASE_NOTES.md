## MTC MoveMint v1.1.15

- Tally Report replaces the Orders sheet with the latest complete DMS batch and clears rows left over from a larger batch. A failed or incomplete fetch preserves the existing Orders data.
- Order and backorder quantities use configured SYSPRO piece conversions when available. The Qty UOM column identifies the displayed unit. Order Volume and BackOrder Volume are reported when the SKU has configured volume data and the quantity can be converted to stocking units.
- Download MTC_MoveMint.exe for manual installation. PROCESS_AUTOMATION.exe is provided for existing update clients.

The packaged executable passed an offline startup check. Orders replacement and quantity conversion passed workbook tests with simulated SYSPRO data. Live SYSPRO was not tested.
