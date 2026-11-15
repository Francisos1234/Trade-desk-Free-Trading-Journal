# TradeDesk — Free Trading Journal

A free, private trading journal that runs entirely in your browser. One HTML file, no account, no server, no tracking.

**Live demo:** https://francisos1234.github.io/tradedesk/

> Built by **Francis Chizurumoke** with AI-assisted coding (ChatGPT and Claude). My contribution: product design, workflow and feature specification, and testing against my own trading records.

## Why I built it

Full-featured journaling platforms such as TradeZella offer broker sync, trade replay and AI review. I wanted a lightweight, free tool for the core journaling loop (log trades, review analytics, reflect), with data that never leaves my machine. TradeDesk is an independent project and is not affiliated with TradeZella.

## What it does

- **Analytics:** net P&L, win rate, profit factor, average R:R, expectancy, max drawdown, equity curve, and breakdowns by day of week, month, asset class, setup, session and direction
- **Display modes:** dollars, R-multiples, or both
- **Trade log:** add, view and delete trades with fees, tags and notes
- **Calendar:** daily and weekly P&L with a drill-down per day
- **Journal:** session notes with mood, mistakes and tags
- **Accounts:** multiple accounts (personal or prop firm) with filtering
- **Risk rules:** daily-loss, max-drawdown and trades-per-day rules
- **CSV import and export**
- **Light and dark themes** (your choice is remembered)

On first load it shows a clearly labelled demo: the 139-trade journal behind my [RR Calendar](https://francisos1234.github.io/trading-performance-journal/). That journal records R-multiples only, so the demo shows dollar P&L at a fixed $100 per 1R (3R outcome model). One click on **Clear demo data** removes it and keeps anything you add.

## Screenshots

| Analytics (light) | Analytics (dark) |
| --- | --- |
| ![Analytics, light theme](screenshots/analytics-light.png) | ![Analytics, dark theme](screenshots/analytics-dark.png) |

| Calendar | Trade log |
| --- | --- |
| ![P&L calendar](screenshots/calendar-light.png) | ![Trade log](screenshots/trade-log-light.png) |

## Privacy

All data is stored in your browser's `localStorage`. Nothing is uploaded, and there are no cookies, accounts or analytics. Use **Export CSV** to back up, since clearing browser data erases your journal.

## What it does not do

No automatic broker sync, trade replay, backtesting or AI review. Imported CSV columns must match the supported format.

## Notes

TradeDesk is a personal journaling tool. It is not financial advice, and nothing here is a forecast of future performance.

## Copyright

© 2026 Francis Chizurumoke. All rights reserved. This repository is public for viewing and evaluation only. See [LICENSE](LICENSE).
