# S1 Group — Sanskaar Nair

Personal site for Sanskaar Nair, founder of S1 Group (Dubai).

A single self-contained `index.html` — no build step, no dependencies. The portrait
and résumé PDF are embedded as data URIs, so the whole site is one file plus fonts
loaded from Google Fonts.

## Deploying on Vercel

Import the repo at [vercel.com/new](https://vercel.com/new) and deploy with the
defaults:

- **Framework preset:** Other
- **Build command:** none
- **Output directory:** leave empty (serves the repo root)

`vercel.json` sets security headers and keeps `index.html` revalidating so updates
go live immediately after a push.

To deploy from the terminal instead:

```bash
npx vercel --prod
```

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
