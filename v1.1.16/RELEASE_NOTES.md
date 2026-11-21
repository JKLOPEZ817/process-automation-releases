## MTC MoveMint v1.1.16

- The Tally Report Orders sheet labels quantities as CS (cases), IB (inner boxes), or PCS (pieces) where applicable.
- Whole order units are preserved. Fractional quantities convert to whole cases, inner boxes, or pieces when the configured SYSPRO conversion represents both the order and backorder quantities accurately.
- When no whole-unit conversion fits, the report keeps the original quantity and lists the affected SKU in the console.
- Download MTC_MoveMint.exe for manual installation. PROCESS_AUTOMATION.exe is provided for existing update clients.

The packaged executable passed offline startup and the quantity conversions passed tests with simulated SYSPRO settings. Live SKU conversions were not verified.
