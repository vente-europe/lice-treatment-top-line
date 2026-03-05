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

- **No sales-units files** — use X-Ray 30d data x 12 for annual projection
- Currency conversion to USD: EUR x 1.085, GBP x 1.295
- Each marketplace = one X-Ray CSV in `x-ray/`

## Tech Stack

- HTML + vanilla JS
- Chart.js 4.4.0 + chartjs-plugin-datalabels 2.2.0 (CDN)

## Status

- [ ] X-Ray CSVs loaded into `x-ray/`
- [ ] Dashboard built
- [ ] Git repo initialized
- [ ] Connected to GitHub remote

## Self-Update Rule

Update this file after every bug fix, new pattern, or structural change.
