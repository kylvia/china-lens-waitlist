# China Lens — Waitlist

Landing page for the China Lens Chrome extension.

**Live**: https://kylvia.github.io/china-lens-waitlist/

## What this is

A waitlist page to validate demand for a Chrome extension that surfaces mainland China data (A-share quotes, northbound capital flow, AI-translated earnings, regulator filings) inside TradingView and Yahoo Finance.

## To collect emails

1. Sign up at [formspree.io](https://formspree.io) (free tier: 50 submissions/month).
2. Create a new form; copy the endpoint URL (looks like `https://formspree.io/f/xxxxx`).
3. In `index.html`, replace `REPLACE_WITH_FORMSPREE_ID` with the form ID.
4. Commit and push.

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
