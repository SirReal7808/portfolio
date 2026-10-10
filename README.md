# Mert Lafcı — Portfolio

Single-page bilingual (EN / TR) personal site for **Mert Lafcı**: solo developer & app creator. One self-contained `index.html` — no build step, no framework.

## What’s on the page

- Hero with brand-first name and vibe-coding vision
- **My Apps** — Meridyen Terapi Asistanı (App Store + Google Play)
- Upcoming Hi-Fi & audio tools teaser (player, EQ, tuner)
- Contact — email, LinkedIn, GitHub
- Language toggle (EN default, TR available; choice saved in `localStorage`)

## Open locally

**Option A — open the file**

```bash
open index.html
# or double-click index.html in your file manager
```

**Option B — tiny static server**

```bash
# Python
python3 -m http.server 43127

# or Node (if you have npx)
npx --yes serve -l 43127
```

Then visit [http://127.0.0.1:43127](http://127.0.0.1:43127).

Fonts load from Google Fonts (Fraunces + DM Sans); everything else is inline in `index.html`.
