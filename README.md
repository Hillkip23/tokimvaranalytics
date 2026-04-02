# Tokim Analytics Website

Institutional-Grade Risk Analytics. Research-Driven.

## Deployment to Vercel

### Option 1 — Vercel CLI (recommended)
```bash
npm i -g vercel
cd tokim-site
vercel
# Follow prompts — set project name to: tokimvaranalytics
# URL will be: tokimvaranalytics.vercel.app
```

### Option 2 — Vercel Dashboard
1. Go to vercel.com → New Project
2. Import from GitHub (push this folder first) or drag-drop the folder
3. Set project name: `tokimvaranalytics`
4. Framework: Other (Static)
5. Deploy

### Option 3 — GitHub + Vercel auto-deploy
```bash
git init
git add .
git commit -m "Initial Tokim Analytics site"
gh repo create tokimvaranalytics --public
git push origin main
# Connect repo in Vercel dashboard — auto-deploys on every push
```

## Structure
```
tokim-site/
├── index.html      ← Single-page site (all JS/CSS inline)
├── vercel.json     ← Vercel deployment config
└── README.md
```

## Features
- Hero with animated stats from actual research
- Interactive Chart.js charts: backtest rates, regime analysis, SHAP attribution
- Full results tables: SPX primary + cross-asset + VRP
- Services section (4 tiers)
- Mechanism section explaining GARCH-EVT vs RND
- Paper CTA
- Contact form
- Fully responsive

## Customisation
- Update email in contact section (search: hcheruiyot@uncc.edu)
- Update LinkedIn URL (search: linkedin.com/in/hillary-cheruiyot)
- When SSRN paper is live, add the actual PDF link
- When Kenya site is ready, add navigation link to it

## Kenya site (Phase 2)
Will be a separate deployment at tokimanalytics-ke.vercel.app
focused on NSE analytics, CBK regulatory context, and East African market data.
