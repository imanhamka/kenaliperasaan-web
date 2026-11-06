# Mari Kenal Perasaan

### Penguasaan Pengurusan Emosi Melalui Integrasi Gamifikasi Berasaskan Kecerdasan Buatan dalam Kalangan Kanak-kanak Autisme

Projek oleh pelajar **Universiti Islam Antarabangsa Malaysia (UIAM)**.

---

## Tujuan

Aplikasi web gamifikasi untuk membantu kanak-kanak autisme mengenal dan memahami emosi asas. Kanak-kanak menonton klip video, kemudian memilih perasaan yang betul — latihan pengecaman emosi secara interaktif dan berulang.

## Cara Main

1. Tekan **Mula Main**.
2. Tonton klip video pendek.
3. Pilih emosi yang betul daripada 4 kad: **Gembira**, **Sedih**, **Marah**, **Takut**.
4. Jawapan betul → loceng + confetti sebagai ganjaran positif.
5. 8 pusingan setiap sesi. Habis → skrin **Tahniah!** + **Main Lagi**.

## Ciri

- Antara muka mesra kanak-kanak — warna lembut, fon besar, kawalan mudah.
- Maklum balas segera (audio + visual) untuk pengukuhan positif.
- **PWA** — boleh "Add to Home Screen" dan main sepenuhnya **offline** tanpa internet.
- Ringan — tiada pendaftaran, tiada pengumpulan data peribadi.

## Teknikal

- Statik tulen: satu `index.html` (HTML + CSS + JavaScript terkandung dalam).
- `videos/` — 8 klip emosi (mp4).
- `fonts/` — Fredoka (woff2).
- `icons/` — ikon PWA.
- `manifest.webmanifest`, `service-worker.js` — sokongan PWA + cache offline.
- `_headers` — kawalan cache Cloudflare Pages.

## Hos

Live: https://kenaliperasaan.pages.dev (Cloudflare Pages)

Auto-deploy: setiap `git push` ke `main` akan mengemas kini laman secara automatik melalui GitHub Actions.
