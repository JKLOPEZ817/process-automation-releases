## MTC MoveMint v1.1.28

- Orders displays On Hand, Allocated, and Stock Free next to Available for the order's warehouse.
- A red stock code means zero or negative On Hand. Amber indicates stock is on hand with no whole pieces available.
- Available excludes work-in-progress reservations from sales-order allocations to match SYSPRO Inventory Query. Stock Free follows the separate inventory export calculation.
- Download `MTC_MoveMint.exe` for manual installation. `PROCESS_AUTOMATION.exe` is the compatibility asset for existing update clients.

Verified with 32 tests, synthetic Excel stock balances and formatting, and an offline startup check. Live SYSPRO warehouse comparison and signed auto-update remain unverified.
