# Manjahi ArchArt Design, Construction & Consultancy

Website for **Manjahi ArchArt Design, Construction & Consultancy** — a Nairobi-based architectural practice specialising in bespoke residential design, construction management, and urban consultancy.

## Pages

| File | Purpose |
|------|---------|
| `JoeMbur.html` | Homepage |
| `Aboutus.html` | About the practice |
| `Ourservices.html` | Services overview |
| `ContactUs.html` | Contact form + FAQ |
| `Readmore.html` | Project portfolio |

## Stack

- HTML5
- [Bootstrap 5.0.2](https://getbootstrap.com/) (CDN)
- [Bootstrap Icons 1.3.0](https://icons.getbootstrap.com/) (CDN)
- [Google Fonts](https://fonts.google.com/) — Playfair Display + Inter
- Vanilla CSS (`style.css`)

No build tool or framework — open any HTML file directly in a browser or use the VS Code Live Server extension (configured on port 5501).

## Project Structure

```
joe.web/
├── img/               Static image assets
├── style.css          Custom styles & design tokens
├── favicon.svg        Brand favicon
├── JoeMbur.html
├── Aboutus.html
├── Ourservices.html
├── ContactUs.html
└── Readmore.html
```

## Design Tokens

Defined as CSS custom properties in `style.css`:

| Token | Value | Role |
|-------|-------|------|
| `--color-dark` | `#212529` | Backgrounds, navbar, footer |
| `--color-gold` | `#ffc107` | Accent, highlights, borders |
| `--color-blue` | `#0d6efd` | Primary buttons, newsletter |
| `--color-light` | `#f8f9fa` | Text on dark backgrounds |
| `--font-heading` | Playfair Display | All headings |
| `--font-body` | Inter | Body copy |

## Local Development

1. Clone or download the repository
2. Open in VS Code
3. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension
4. Right-click `JoeMbur.html` → **Open with Live Server** (runs on port 5501)

## Next Steps (Priority 3)

- [ ] Wire up contact form via [Formspree](https://formspree.io) or similar
- [ ] Shared navbar via JS fetch partial (reduce copy-paste across pages)
- [ ] Add real phone, email, and social media links
- [ ] Image optimisation (compress `img/` assets for web)
- [ ] `npm` + package.json for future tooling (autoprefixer, minification)

---

Built by [Scythe Developers Media](https://github.com)
