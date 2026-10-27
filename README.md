# HomeFlow

Responsive home setup planner covering Phase 0 electrical and safety through Phase 4 finishing touches.

## Deployment on Cloudflare Pages

Connect this repository to Cloudflare Pages. Build command: `npm run build`; output directory: `dist`; production branch: `main`.

## Development

Run `npm install` and `npm run dev`. The app is implemented in the standalone `index.html`; Vite is used for development and production packaging.

## Data

Tasks and budgets are stored in browser localStorage. Use JSON export/import to move data between browsers. There is no authentication or cross-device sync yet.
