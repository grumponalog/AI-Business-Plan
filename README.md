# Vinyl AI — Master Business Plan

Single-file, self-contained interactive business plan (HTML + inline CSS/JS). No build step, no dependencies. `index.html` is the entry point.

## Deploy to Vercel (static)
**Option A — CLI (fastest):**
```
cd vinyl-ai-plan-site
npx vercel          # preview deploy, follow prompts
npx vercel --prod   # promote to production URL
```
No framework or build settings needed — Vercel serves `index.html` directly.

**Option B — Dashboard:** push this folder to a Git repo, then in Vercel: Add New → Project → import the repo. Framework preset: **Other**. Build command: none. Output dir: `./`.

## Notes
- `.nojekyll` is only needed for GitHub Pages; harmless on Vercel.
- This site is **public** once deployed — anyone with the URL can read it (pricing + strategy included), by owner's decision.

_Internal — Vinyl Marketing · AI Business Development · June 2026_
