# u00f8

Personal site of u00f8 (U+00F8, the slashed o), ASCII / textmode artist. Hand-written static HTML
and one stylesheet. No JavaScript, no images, no build step, no dependencies.

Open `index.html` directly, or serve the folder:

    python3 -m http.server 8000

Fonts are self-hosted in `fonts/`:

- IBM Plex Mono (SIL Open Font License 1.1) — body text
- PxPlus IBM XGA-AI 12x20 by VileR, The Ultimate Oldschool PC Font Pack
  (CC BY-SA 4.0, https://int10h.org/oldschool-pc-fonts/) — mark, rules, works.
  Bitmap font: render only at 20px, 40px or 60px.
  Works need a row count divisible by 6 to stay on the 24px text grid.

Deploy: upload the folder as-is to any static host.
