# Mari Kenal Perasaan

Permainan web untuk kanak-kanak belajar kenal emosi. Tonton klip video, pilih perasaan yang betul (Gembira / Sedih / Marah / Takut). 8 pusingan, loceng + confetti bila betul.

Statik tulen (HTML + CSS + JS inline), tiada backend. PWA — boleh "Add to Home Screen" dan main offline.

## Hos
Live: https://kenaliperasaan.pages.dev (Cloudflare Pages)

## Struktur
- `index.html` — seluruh app (CSS + JS inline)
- `videos/` — 8 klip emosi (mp4)
- `fonts/` — Fredoka (woff2)
- `icons/` — ikon PWA
- `manifest.webmanifest`, `service-worker.js` — sokongan PWA offline
- `_headers` — kawalan cache Cloudflare Pages
