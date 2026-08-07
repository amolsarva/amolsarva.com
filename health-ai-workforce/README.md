# Health Provider AI Workforce Sensitivity Model

This is a self-contained static website. It requires no build process, database, server-side application, or external JavaScript libraries.

## Publish

Upload the contents of this folder to the public/root directory of any static website host. Keep `index.html` at the root. Common options include Netlify Drop, Vercel static hosting, GitHub Pages, Cloudflare Pages, Amazon S3, or a conventional web server.

If the hosting service accepts a ZIP upload, upload the ZIP without changing its internal folder structure.

## Test locally

Open `index.html` in a modern browser. Scenario edits are stored in the visitor's browser using local storage. They are not sent to a server or shared across users.

## Files

- `index.html` — complete interactive model, styling, baseline data, calculations, research appendix, and citations.
- `data/workforce_model.csv` — baseline workforce assumptions.
- `data/primary_care_minutes.csv` — baseline physician-day assumptions.
- `data/summary_metrics.csv` — baseline summary metrics.

The application does not load the CSV files at runtime; they are included for transparency and downstream reuse. All runtime data is embedded in `index.html` so the tool remains portable.

## Important caveat

The workforce allocation is an illustrative benchmark model, not an actual Northwell HRIS census. Technical task exposure is not equivalent to job elimination.
