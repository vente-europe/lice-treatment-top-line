# Nitolic - EU Topline Dashboard

> TopLine multi-marketplace comparison dashboard for Nitolic brand across European markets.

---

## Project Type

**TopLine Dashboard** — simpler format, multi-marketplace comparison.
- Template: `Fruit Flies - Other/index.html`
- One `index.html` in project root — no build step

## Folder Structure

```
Nitolic - EU Topline/
  CLAUDE.md         # This file
  .gitignore        # Protects sensitive files
  index.html        # Dashboard (built from Fruit Flies - Other template)
  x-ray/            # All marketplace X-Ray CSVs (flat folder)
```

## Data Convention

- **No sales-units files** — X-Ray is 30D, multiply by 12 for all dashboard output (charts + tables must show 12M)
- Currency: EUR (base). Convert GBP → EUR x 1.195 (ECB Mar 2026)
- Each marketplace = one X-Ray CSV in `x-ray/`

## Tech Stack

- HTML + vanilla JS
- Chart.js 4.4.0 + chartjs-plugin-datalabels 2.2.0 (CDN)

## Status

- [x] X-Ray CSVs loaded into `x-ray/` (DE, UK, FR, ES, IT)
- [x] Dashboard built
- [x] Git repo initialized
- [ ] Connected to GitHub remote

## Self-Update Rule

Update this file after every bug fix, new pattern, or structural change.
