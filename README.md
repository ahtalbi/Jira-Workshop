# Thimdrine

Showcase website for Thimdrine, a women's cooperative of 25 members in the Nador region (Rif, Morocco). The cooperative harvests, processes and packages thyme honey, extra virgin olive oil and prickly pear jam by hand. Until now it sold only at local markets and over WhatsApp.

The president, Mme Fadma, asked for a website to present the cooperative, show its products and receive order requests. This project covers the design phase (backlog, zoning, wireframes, mockups, style guide) and the integration in plain HTML5 and CSS3.

Individual project, 5 days, YouCode Nador.

## Links

- Live site: https://0xm3d.github.io/Thimdrine/
- Repository: https://github.com/0xm3d/Thimdrine
- Figma mockups: https://www.figma.com/design/XBAdiP16iN1ybJuXUmwoFW/Thimdrine-Project?node-id=0-1&t=4G0yMHZGAPo4VULE-1
- Backlog (GitHub Projects): https://github.com/users/0xm3d/projects/1

## Pages

All four pages share the same header (logo and navigation) and footer (address, phone, email, opening hours, sitemap).

| Page | Live URL | Content |
|---|---|---|
| Home | https://0xm3d.github.io/Thimdrine/ | Hero banner, short presentation of the cooperative, 3 signature products, call to action to Contact |
| Our products | https://0xm3d.github.io/Thimdrine/products.html | 6 product cards (image, name, description, price) laid out with Flexbox |
| About | https://0xm3d.github.io/Thimdrine/about.html | The cooperative's story as a timeline from 2015 to 2026 |
| Contact | https://0xm3d.github.io/Thimdrine/contact.html | Order request form with native HTML validation |

## Products

| Product | Size | Price |
|---|---|---|
| Thyme honey | 500 g | 180 DH |
| Thyme honey | 1 kg | 340 DH |
| Extra virgin olive oil | 1 L | 90 DH |
| Extra virgin olive oil | 5 L | 420 DH |
| Prickly pear jam | 350 g | 45 DH |
| Prickly pear jam | 700 g | 85 DH |

## Contact form

Fields: full name, email, phone number, product (dropdown with the 6 products), quantity, message, and a consent checkbox. Validation relies only on native HTML attributes (`required`, `type`, `pattern`, `min`), with no JavaScript.

## Design system

The style guide was made in Figma and is declared as CSS variables in `:root`.

| Color | Hex | Variable | Use |
|---|---|---|---|
| Rif (thyme) | `#264653` | `--rif-color` | Buttons, links |
| Honey | `#D99A2B` | `--honey-color` | Call-to-action, accents |
| Fig | `#7A2946` | `--fig-color` | Prices, kicker text, focus ring |
| Linen | `#F7F0E3` | `--linen-color` | Page background |
| Earth | `#241E1A` | `--earth-color` | Main text |
| Clay | `#B85C38` | `--clay-color` | Headings, footer |
| Sand | `#E8D8BF` | `--sand-color` | Alternate sections |
| Soft earth | `#5A4F46` | `--earth-soft-color` | Secondary text |
| White | `#FFFFFF` | `--white-color` | Cards, header |

**Typography**

- Lora (weights 600, 700) for headings: H1 52px, H2 32px, H3 20px. On mobile: H1 34px, H2 28px.
- Source Sans 3 (weights 400, 600, 700) for text: 17px body with a 1.6 line height, 20px lead text, 15px small text.

**Buttons:** Primary, Outline and Honey variants, with a keyboard focus ring (3px Fig outline using `:focus-visible`).

**Spacing scale:** 8px, 16px, 24px, 40px, 64px.

## Technical constraints

- HTML5 and CSS3 only: no framework, no JavaScript, no copied template
- Semantic markup, one `h1` per page, an `alt` attribute on every image
- Layout with Flexbox, responsive with at least one media query
- Conventional Commits, at least one commit per finished task
- Deployed on GitHub Pages

## Project structure

```text
Thimdrine/
├── index.html
├── products.html
├── about.html
├── contact.html
├── assets/
│   └── style.css
├── images/
└── README.md
```

## Technologies

- HTML5 (semantic elements)
- CSS3 (custom properties, Flexbox, media queries)
- Figma (zoning, wireframes, mockups, style guide)
- GitHub Projects (backlog), GitHub Pages (hosting)

## Run locally

```bash
git clone https://github.com/0xm3d/Thimdrine.git
cd Thimdrine
```

Open `index.html` in a browser.

## Author

Mohamed Bouhadi, YouCode Nador.
