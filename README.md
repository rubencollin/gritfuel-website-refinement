# gritfuel.works — website refinement brief

Static handoff package for the same-day refresh of [gritfuel.works](https://gritfuel.works) on **Monday 20 April 2026**. Prepared for **Taffy & Fidel**.

## Start here

→ **[`developer-brief.html`](developer-brief.html)** — the brief.
Section-by-section walk: current site copy on the left, new copy on the right, plus the new statement band and rendered plan cards.

## Structure

```
website-refinement/
├── developer-brief.html      ← the handoff (start here)
├── refinement-spec.html      verified live-site copy capture (source of truth)
├── index.html                landing page for this folder
├── icons-preview.html        14-icon preview gallery
├── imagery-preview.html      illustration previews
├── concepts/                 statement-bg.html (3 variants — V2 lime is the picked one)
├── mockups/                  a-minimal · b-full · c-editorial
├── assets/
│   ├── icons/                28 SVG files (14 icons × light + -inv variants)
│   ├── icons-png/            PNG fallbacks
│   ├── illustrations/        step03-compound · dashboard-cluster · growth-dashboard
│   ├── statement-bg/         statement-bg-v1/v2/v3 (V2 lime is the chosen one)
│   └── viewer/               per-asset HTML viewers with download buttons
└── README.md                 this file
```

## Deadline

| Milestone        | When                            |
|------------------|---------------------------------|
| Dev handoff      | **Mon 20 April 2026 · AM** (today) |
| Go-live          | **Mon 20 April 2026 · COB** (today) |

Same-day ship. Anything that can't go today gets bumped to a follow-up patch.

## Running locally

No build step — pure static HTML + CSS.

```bash
cd website-refinement
python3 -m http.server 8000
# open http://localhost:8000/developer-brief.html
```

Or just open `developer-brief.html` directly in a browser.

## Publishing to GitHub Pages (recommended)

1. Push this folder to a public repo.
2. On github.com → **Settings → Pages**.
3. Source: **Deploy from a branch** · Branch: `main` · Folder: `/` (or `/website-refinement` if pushed alongside other folders).
4. Save. Live URL appears within ~60 seconds at:
   `https://<your-username>.github.io/<repo-name>/developer-brief.html`

Share that URL with Taffy & Fidel. Asset viewers and download buttons all work from the published URL.

## Version

v3 — 20 April 2026 — prepared by Ruben + Claude.
