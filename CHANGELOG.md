# Changelog

## Unreleased

- Renames the app to Cofferly after product-name collisions with previous AirWallet and Atlas Wallet names.
- Preserves automatic legacy data import for previous Atlas Wallet, TallyNest, and original AirWallet installs.
- Updates all references in code, docs, build scripts, installer, tests, screenshots, and GitHub workflows.

## 0.1.0

- Renames AirWallet to TallyNest to avoid confusion with an existing payment platform.
- Imports existing AirWallet data automatically on first launch.
- Initial TallyNest desktop app.
- Adds two default child wallets.
- Tracks deposits, deductions, and running balances.
- Adds parent PIN unlock with first-run PIN `1234`.
- Adds child wallet renaming and adding custom child wallets.
- Adds printable ledger export for one wallet or both wallets.
- Adds Windows portable packaging script.
- Adds Inno Setup installer script.
- Adds GitHub Actions release workflow.
- Updates GitHub Actions and Rust dependencies after first Dependabot scan.
