# Post-it

Automatic posting to Facebook groups for Israeli real estate agents.

Bilingual landing page (Hebrew / English) for [@PostItBot](https://t.me/PostItBot) — the smart Telegram bot that posts your properties to dozens of Facebook groups with unique AI-generated text for each group, photos, and smart scheduling.

## Stack

- Static HTML / CSS / vanilla JavaScript (no frameworks, no build step)
- `i18n.js` — runtime Hebrew/English toggle with `localStorage` persistence
- Deployed on Vercel

## Local development

```bash
python3 -m http.server 8765
open http://localhost:8765
```

## Deploy

```bash
vercel --prod
```
