# Spiritual Light — Artist Gallery Template

A complete single-file art gallery website with shopping cart, buyer checkout form, light & dark mode, and gradient design. No build tools, no frameworks — pure HTML, CSS and JavaScript.

## What's included

```
spiritual-light-gallery/
├── index.html          # The entire website (HTML + CSS + JS in one file)
├── images/             # 6 demo artworks (PNG)
└── README.md
```

## How it works

Open `index.html` in any browser — that's it. No installation, no build step, no server needed.

Or drag the whole folder onto [Netlify Drop](https://app.netlify.com/drop) to put it online instantly.

## Features

- **Fully responsive** — desktop, tablet, mobile
- **Light & dark mode** — automatic via `prefers-color-scheme`
- **Shopping cart** — add items, change quantity, remove (saved in browser)
- **Checkout form** — buyer details: name, email, phone, address (with validation)
- **Dual purchase** — direct "Buy" button per item + cart checkout
- **Gradient design** — indigo & antique gold palette, editorial typography

## Customize

| What | Where in index.html |
|---|---|
| Product name | `<h3>` inside each `.card` |
| Description | `<p>` inside each `.card` |
| Price | `data-price` attribute on `.card` + `<span class="price">` |
| Image | `src` of `<img>` + `data-image` attribute |
| Payhip link (direct buy) | `data-payhip` attribute on `.card` |
| Cart checkout link | `PAYHIP_CHECKOUT_LINK` in the `<script>` at the bottom |
| Colors | CSS variables in `:root` at the top of `<style>` |

### Quick start for sellers

1. Replace the demo images in `images/` with your own (keep the filenames or update the `src`)
2. Edit each card's name, description, price
3. Add your Payhip product links to `data-payhip` attributes
4. Optionally set `PAYHIP_CHECKOUT_LINK` for the cart's final payment step
5. Upload the folder to GitHub Pages, Netlify, or any static host

## Demo images

The 6 included PNG images are AI-generated spiritual artworks (3000×4000 px) — use them as placeholders or replace with your own.

## License

Personal and commercial use.
