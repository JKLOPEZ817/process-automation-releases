## MTC MoveMint v1.1.23

- In Tally Report, **R** lists status-8 sales orders by SYSPRO Requested Ship Date. The lookup uses the selected DMS branches and Booking salesperson codes. Press Enter at each filter prompt to use the defaults, then use all listed orders or paste the S.O. IDs to include.
- Orders uses **Ready To Print w/ BackOrder** values. Salesperson Summary, S.O. to Rectify, and All Transactions use plain **Ready To Print**. When using an export for those three tabs, confirm that DMS generated it in plain Ready To Print mode.
- After a successful SYSPRO login, you can save it securely for your Windows account. On a later run, press Enter to reuse it, **N** to enter a different login, **F** to forget it, or **S** to skip SYSPRO.
- Download `MTC_MoveMint.exe` for manual installation. `PROCESS_AUTOMATION.exe` is the compatibility asset for existing update clients.

Verified with 24 tests, a synthetic Excel report, Windows credential protection, and an offline startup check. Live DMS and SYSPRO comparison and signed auto-update remain unverified.
