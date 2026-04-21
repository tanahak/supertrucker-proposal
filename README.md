# SuperTrucker × APL Cargo — Founding Partnership Proposal

A founding partnership proposal from **Carso Cybernetics** to **APL Cargo** for the SuperTrucker fleet AI platform.

Single-file HTML site, deployed to GitHub Pages at https://apl.supertrucker.ai

## Structure

- `index.html` — the full proposal (inline CSS + JS, no build step)
- `images/` — logos and hero image
- `CNAME` — GitHub Pages custom-domain configuration

## Local preview

```
python3 -m http.server 8765
```

Then open http://localhost:8765/

## Deployment

Pushed to the `main` branch on GitHub. GitHub Pages serves the repo root. DNS CNAME record points `apl.supertrucker.ai` → `<username>.github.io`.

## Reusing this template

If the partnership pivots to a different carrier, edit the content in `index.html` (the site is structured for easy find-and-replace of carrier name), then change the subdomain in `CNAME` and update the DNS record.
