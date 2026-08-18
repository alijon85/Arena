# Arena

Desktop accounting and inventory software built for small retail shops, designed around real shop owners' request for something simple.

## Features

- **Inventory** (انبار) — track products and stock levels
- **Store** (فروشگاه) — record sales and purchases
- **Deposits** (واریزی‌ها) — log incoming payments
- **Withdrawals** (برداشت‌ها) — record withdrawals
- **Ledger accounts** (حساب‌های دفتری) — a digital ledger for auditing and tracking
- **Settings** — font size/family, icon size, and password-protected access, all configurable from within the app
- Persian (Jalali) calendar support throughout, matching how the shops using it actually track dates

## Tech Stack

- **Language:** Python
- **UI:** PyQt5
- **Storage:** SQLite (local, per-install)
- **Calendar:** [persiantools](https://pypi.org/project/persiantools/) for Jalali date handling

## Installation

```bash
git clone https://github.com/Alidl81/Arena.git
cd Arena
pip install -r requirements.txt
python ArenaSport.py
```

A packaged Windows installer is also available under `Arena Setup/`.

## Usage

Launch the app, set an access password on first run from Settings, then use the Inventory, Store, Deposits, Withdrawals, and Ledger tabs to manage day-to-day shop accounting. All data is stored locally in SQLite.

## Project Status

Stable and in real-world use by several small retail shops. Not under active feature development.

## Notes

`*.db` files are intentionally excluded from version control — they hold real shop data on an actual install, not sample data.

## License

No license file is currently included; treat as all-rights-reserved unless stated otherwise by the author.
