# investor-dashboard

Public host for the investor pipeline dashboard. Contains only `index.html` and an
**encrypted** data blob (`data.enc.json`, AES-256-GCM). The decryption key lives in the
dashboard link's URL fragment (`#k=...`) and is never stored here, so this public repo
exposes no client data. Source data + tooling live privately in `investor-pipeline` and
`yossi-claude-brain`.
