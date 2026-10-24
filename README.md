Full version: themes.formchime.com

# Astro Extension Kit Lite

A free, one-page landing site for a browser extension: hero with store install buttons, browser-window product mock, latest-release strip, "how it works", and a plain-language **permissions explainer** for store review. Astro 7 + Tailwind 4, zero framework JS, light/dark, Lighthouse 100.

**MIT licensed** — use it for anything.

## Want the rest?
The full **[Astro Extension Kit](https://themes.formchime.com/themes/extension-kit/)** adds pricing, docs (Content Collections), changelog, a store-ready privacy policy, a post-install onboarding page, and English / 日本語 / 繁體中文.

## Use
```bash
nvm use && npm install && npm run dev
```
Edit `src/site.config.ts` (name, version, store links, permissions) and `src/i18n/ui.ts` (copy). Recolor via `--signal` in `src/styles/global.css`. Build with `npm run build`, deploy `dist/` to Cloudflare Pages, Netlify or Vercel (Node 22).

## Before you go live
Replace the demo user count and rating (`users`, `rating` in `src/site.config.ts`), the changelog entry and store URLs with your real values.
