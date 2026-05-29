# 🤖 Hermes - Bursa Trading Intelligence Dashboard

A real-time trading dashboard for Bursa Malaysia and US stock markets, powered by an AI trading assistant called **Hermes**.

## What is this?

This dashboard tracks:
- 📊 **Bursa Malaysia** stocks — semiconductors, tech, financials, energy
- 🇺🇸 **US Paper Trading** — NVDA, QCOM, AMD, TSM positions
- 📈 **Serenity's AI Supply Chain Picks** — tracking Twitter/X influencer stock calls (XFAB, SIVE, AAXI, etc.)
- 💱 **Macro data** — USD/MYR, Oil, CPO, SOX futures
- 📰 **Market news** — auto-aggregated from 25+ RSS feeds

## How I built it

1. **AI Agent (Hermes)** — A Python-based trading intelligence bot running on my Mac mini, using:
   - Futu/Moomoo API for live market data and paper trading
   - Google Sheets as a data backend
   - 90+ keyword groups for sector scanning
   - Technical analysis (RSI, MACD, Bollinger, Ichimoku)
   - Cron jobs for automated market briefings (8:30 AM & 8:30 PM daily)

2. **Dashboard** — A single-file HTML dashboard with:
   - Dark theme, real-time data display
   - Portfolio tracker with P&L
   - Sector watchlists
   - Serenity's stock picks tracker

3. **Hosting** — GitHub Pages (free, permanent URL)

## Tools Used

- **Python** — Futu API, yfinance, technical analysis
- **Google Sheets API** — Data storage
- **GitHub Pages** — Free hosting
- **Telegram Bot** — Daily market alerts

## Links

- 🌐 **Dashboard:** [Open Dashboard](https://yin2306.github.io/hermes-bursa-dashboard/)
- 📊 **Google Sheet:** [Bursa Data](https://docs.google.com/spreadsheets/d/1qJne2RkHcQKiS5ydL3ijclK9XvcQLcVBZ_cy4sGSjbY)

## Disclaimer

This is a paper trading project for educational purposes only. No real money is used. Always do your own research before making investment decisions.
