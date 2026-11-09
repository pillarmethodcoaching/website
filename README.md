# Pillar Method Coaching website

Astro site for pillarmethodcoaching.com, published to GitHub Pages by GitHub Actions (see .github/workflows/deploy.yml).

- Links, price and offer facts: `src/config.ts` (source of truth is Mitch's Business/status.md).
- Apply form: set `APPLY_URL` in `src/config.ts` once the Tally form exists.
- Email list: set `KIT_FORM_ACTION` in `src/config.ts` once the Kit form exists.
- Local: `npm install`, then `npm run dev`.
