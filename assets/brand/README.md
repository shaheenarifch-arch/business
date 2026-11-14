# BusinessBuy brand kit

Executive, premium corporate look. Use these files and values on every page so the site looks like one brand.

## Logo files

| File | Use it for |
|---|---|
| `businessbuy-logo.svg` | Full logo (B&B monogram + wordmark) on white or ivory backgrounds |
| `businessbuy-logo-white.svg` | Full logo on navy or dark backgrounds |
| `businessbuy-mark.svg` | Monogram only: social avatars, small spaces |
| `businessbuy-mark-512.png` | Monogram as PNG (512 px) for profiles, schema `logo`, email signatures |

Site favicons live in the site root (`/favicon.ico`, `/favicon-32x32.png`, `/apple-touch-icon.png`). The default share image is `/og-image.jpg`.

Keep clear space around the logo of at least half the monogram's width. Do not stretch, recolour or add effects.

## Colours

| Name | Hex | Use |
|---|---|---|
| Navy | `#0c1726` | Headings, header text, dark sections, buttons |
| Navy 2 | `#13233a` | Gradients, hover on dark |
| Ivory | `#f7f5f0` | Page background |
| Line | `#e4e0d6` | Borders, dividers |
| Text | `#1b2433` | Body text |
| Muted | `#5e6878` | Captions, small labels |
| Bronze | `#b08d57` | Thin accent rules, monogram frame and ampersand |

Rule: **never use yellow text.** Bronze is for lines, borders and the monogram only; body links use navy or the darker bronze `#987541`.

## Type

- Headings: serif (Lora / Georgia fallback)
- Body and UI: sans-serif (Inter / system fallback)

## Page template

Every page should carry the shared header: the `bb-top` contact bar, the `bb-hdr` header with the B&B logo and nav, the `bb-menu` mobile menu, the `<style id="bb-brand">` block and the `<script id="bb-menu-js">` script. Copy them from any existing guide, for example `blog/due-diligence-checklist-buying-business/index.html`.

Help: [Open Graph image guide](https://ogp.me/) · [Google logo structured data](https://developers.google.com/search/docs/appearance/structured-data/logo)
