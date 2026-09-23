# Crypto Portfolio Tracker

A clean, formula-driven portfolio tracker for crypto investors — **no macros, no accounts, no subscriptions**. It works in Excel, WPS Office, and Google Sheets (import the `.xlsx`).

Your trades stay on your machine. No API keys, no cloud sync, nothing phones home.

## Free Community Edition

Download **[`Crypto_Portfolio_Tracker_Community.xlsx`](Crypto_Portfolio_Tracker_Community.xlsx)** and start logging trades in under a minute.

- **Trade Log** — date / BUY-SELL / coin / exchange / qty / price / fee, with dropdowns and auto-computed totals
- **Holdings** — live position per coin: qty held, average buy price (fees included), cost basis, current value, P&L in USD and %, green/red conditional formatting
- **Reference Lists** — rename any row to track the coin you hold; dropdowns update everywhere
- 32 trade rows, 8 coin slots (drag-fill for more — formulas and dropdowns copy)
- Works with Excel 2016+, WPS Office, Google Sheets

Data flow: you type trades once → `SUMIFS` aggregation keeps Holdings current → paste live prices from CoinGecko or your exchange, P&L recalculates instantly.

## Pro Edition — $9 (one-time)

| | Community (free) | Pro ($9) |
|---|---|---|
| Trade Log rows | 32 | 64 |
| Coin slots | 8 | 16 |
| Holdings aggregation | ✓ | ✓ |
| **Dashboard** (KPI cards, allocation pie chart, P&L bar chart) | — | ✓ |
| **Integrity Checks** sheet (self-verifying math, PASS/FAIL at a glance) | — | ✓ |
| PDF quick-start guide | — | ✓ |

### How to buy

1. Email **assassinationss@163.com** with subject **`Tracker`**
2. You'll get payment instructions back (USDT on TRC20, ~$9 — no gas surprises)
3. Send the transaction ID; the tracker (`xlsx` + PDF guide) is emailed back as attachments once the payment confirms on-chain

**30-day refund guarantee.** If it doesn't work for your setup, email the same address and the payment is returned in full. No questions asked.

## Why a spreadsheet?

- Trading apps show you *their* numbers. A spreadsheet shows you yours — every fee, every lot, auditable.
- Portfolio apps get acquihired and shut down. A file on your disk doesn't.
- Excel formulas are inspectable. If you want to see how "average buy price" is computed, click the cell.

## FAQ

**Is my data uploaded anywhere?** No. The file contains formulas only — there is no network code because there is no code.

**Does it auto-fetch prices?** No, by design. You paste current prices when you want a P&L refresh (30 seconds with CoinGecko open in the next tab). Auto-fetch means API keys and a dependency that breaks.

**Google Sheets?** Import the `.xlsx`; dropdowns and formulas carry over.

## License

The Community Edition is released under [CC BY 4.0](LICENSE) — use it freely, share it, keep attribution. The Pro edition build is a paid product (personal-use license).

---

Questions or feedback: **assassinationss@163.com**
