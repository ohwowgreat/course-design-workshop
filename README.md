# Course Design in an Age of Algorithmic Attention

Workshop companion site for the BNDS Insights 2026 miniworkshop, adapted for use at other schools.

## What's here

- `index.html` — Workshop hub page
- `hook-or-skip.html` — Media Studies live demo
- `le-chatelier.html` — Chemistry live demo
- `prompt-builder.html` — Drag-and-drop prompt builder

All files are single-page HTML with inline CSS and JavaScript. No build step.

## Deploy to Cloudflare Pages

### Option A — Connect GitHub (recommended)

1. Go to [Cloudflare Dashboard](https://dash.cloudflare.com/) → **Workers & Pages** → **Create** → **Pages**
2. Connect your GitHub account and select this repo
3. Framework preset: **None**
4. Build command: (leave empty)
5. Build output directory: `/` (root)
6. Click **Save and Deploy**

Cloudflare Pages will auto-deploy on every push to `main`.

### Option B — Wrangler CLI

```bash
npm install -g wrangler
wrangler login
wrangler pages deploy .
```

---

## Deploy to Vercel

1. Push this folder to a GitHub repo
2. Import the repo into Vercel
3. Framework Preset: **Other**
4. Build Command: (leave empty)
5. Output Directory: (leave empty, root)
6. Deploy

Vercel will serve `index.html` automatically.

## Local preview

Open `index.html` directly in a browser, or run:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Facilitator

Doğan · BNDS, Beijing
