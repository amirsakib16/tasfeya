# Draft of Tasfeya

A static multi-page site: `index.html` (dashboard) plus `hr.html`, `acc.html`, `ofad.html`, `canva.html`, `msx.html`, `adobe.html`.
Shared styling is in `css/style.css`, behavior (dark/light mode, animations, dropdown) in `js/main.js`.

## Run locally
Open `index.html` in a browser, or run `npx serve .`

## Deploy to Vercel
**Option A: Vercel CLI**
1. `npm i -g vercel`
2. From this folder run `vercel` and accept the defaults (Framework Preset: Other, no build command, output directory `.`).
3. Run `vercel --prod` to publish.

**Option B: GitHub**
1. Push this folder to a GitHub repository.
2. On vercel.com choose Add New > Project and import the repository.
3. Leave Framework Preset as "Other", leave Build Command empty, and click Deploy.

`vercel.json` adds basic security headers and caching for the CSS and JS files.
