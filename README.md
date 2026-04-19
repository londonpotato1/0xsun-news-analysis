# 0xSun News Trading Analysis Dashboard

Event-driven crypto trading strategy dashboard — derived from [@0xSunNFT's April 2026 retrospective](https://x.com/0xSunNFT/status/2045760821188551055) on news-based trading.

**Live:** https://londonpotato1.github.io/0xsun-news-analysis/

## Contents
- Thesis decomposition (방향성 × 변동성, Speed vs Interpretation edges)
- 6 verified case studies (KelpDAO hack, Covenant AI/TAO exit, ARC funding surge, RAVE investigation, etc.)
- Stack × strategy mapping
- Module build plan (signal_hub, kol_watcher, exchange_notice_diff, …)
- Source universe (KOL whitelist, exchange notice URLs, on-chain APIs)
- Strategy playbook (event type × position recipe)
- Execution roadmap

Single-file HTML, no build step. Tailwind loaded via CDN.

## Local preview
```bash
open index.html
```
