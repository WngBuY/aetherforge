# AetherForge

**Crypto strategy research & tooling for independent traders and quants.**

AetherForge is an independent, self-funded **early-stage project** based in Japan.
It provides research and tooling — **not financial advice**, and it never executes
trades or holds funds. The site is currently a landing page with an **early-access
waitlist**.

Live site: **https://aetherforge.bond** · Contact: **contact@aetherforge.bond**

## What it does

- **Backtesting** — test strategies on historical data with transparent fees, slippage, and assumptions (with limitations stated).
- **Signal monitoring** — track indicators and strategy states on a dashboard, with alerts. Informational only.
- **Risk reports** — drawdown, volatility, exposure, and scenario breakdowns.
- **Data pipelines** — curated, reproducible market & on-chain data feeding research and backtests.
- **Strategy research subscriptions** — follow research strategies and get notified on state changes. No auto-trading, no custody.

## Pages

```
index.html                            Homepage
research.html                         Research notes index
research-data-pipelines.html          Note: reproducible market-data pipeline principles
research-backtest-failure-modes.html  Note: six backtest failure modes & our controls
waitlist.html                         Early-access waitlist (email-based)
disclaimer.html                       Risk Disclaimer / Not Financial Advice
privacy.html                          Privacy Policy
terms.html                            Terms of Service (governed by the laws of Japan)
contact.html                          Contact + project identity
style.css                             Shared styles
sitemap.xml / robots.txt              SEO basics
CNAME                                 Custom domain (aetherforge.bond)
```

No build step and no dependencies — plain static HTML/CSS, hosted on **GitHub Pages**.

## Run locally

```bash
python -m http.server 8000   # then open http://localhost:8000
```

## Deploy

Push to the `main` branch; GitHub Pages serves it at the custom domain `aetherforge.bond`.

## Important

AetherForge is for **research and educational purposes only** and is **not
financial, investment, or trading advice**. Crypto assets are high-risk. See
[Risk Disclaimer](disclaimer.html).
