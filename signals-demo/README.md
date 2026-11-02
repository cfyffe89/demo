# Demo data for Signals Data Sources (static, synthetic)
Served as raw GitHub files, so a tenant can reach them without a running server. All values are synthetic demo data; supplier names are fictional.
| Data Source type | URL to configure | Key |
|---|---|---|
| External List | `https://raw.githubusercontent.com/cfyffe89/demo/main/signals-demo/project-codes.json` | `code` |
| External Data Source (containers) | `https://raw.githubusercontent.com/cfyffe89/demo/main/signals-demo/containers` (Signals appends `/<barcode>`) | barcode, for example `V-0048213` |
| External Chemical Source (reagents) | `https://raw.githubusercontent.com/cfyffe89/demo/main/signals-demo/reagents/{id}` | reagent ID, for example `RGT-000124` |
Each file name is the key with no extension. Read-only: POST and PUT from Row Options do not work on this host.
