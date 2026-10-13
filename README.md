# PIECECRAFT — Puzzles & Creative Challenges

**Every piece has a place.**

PIECECRAFT is a puzzle-storefront concept for curious minds, creative thinkers, families, and puzzle enthusiasts. The store concept brings together jigsaw puzzles, 3D builds, brain teasers, educational puzzles, accessories, and gift ideas in a premium lavender-and-cream visual identity.

## Brand direction

PIECECRAFT is designed to feel creative, thoughtful, and polished rather than generic. Its visual language combines puzzle-piece motifs, deep purple, lavender, warm cream, and clean editorial typography.

## Collections

- **Jigsaw Puzzles:** landscapes, art-inspired designs, maps, and themed puzzles
- **3D Puzzles:** architectural models and build-and-display challenges
- **Brain Teasers:** wooden logic puzzles and hands-on problem-solving
- **Accessories:** sorting trays, storage mats, and puzzle-care concepts
- **Kids & Educational:** approachable puzzle activities
- **Gifts & Bundles:** gift-ready puzzle concepts

## Storefront features

- Responsive desktop and mobile layout
- 12-item JSON product catalog
- Individual local image assets for products
- Search by name, category, or description
- Category filtering and price/name sorting
- Product detail dialog
- Shopping bag with quantity controls and subtotal
- Favorites/saved products
- Cart and favorites persistence through browser local storage when available
- Newsletter demo interaction
- Customer support links in the footer
- Local logo, hero image, and product photos
- Static structure designed for GitHub Pages

> **Important:** This is a frontend demonstration. Product prices are illustrative market-style estimates, not live offers or verified prices for the exact pictured products. The images are visual concept assets and do not verify a specific retail SKU. Checkout, payments, shipping calculations, stock, customer accounts, and email delivery are not connected.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- JSON
- GitHub Pages (planned deployment)

## Project structure

```text
piececraft-puzzles/
├── index.html
├── README.md
├── CHANGELOG.md
├── css/
│   └── styles.css
├── js/
│   └── app.js
└── assets/
    ├── data/
    │   └── products.json
    ├── logo/
    │   └── piececraft-logo.jpg
    └── images/
        ├── hero/
        │   └── puzzle-table.jpg
        └── products/
            └── 12 individually generated square product photographs (900 × 900 px)
```

## Run locally

Because the catalog is loaded using `fetch()`, run the project with a local web server instead of opening `index.html` directly via `file://`.

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Upload all project files to the root of the `piececraft-puzzles` repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`.
5. Save and wait for GitHub Pages to publish.

The site URL generally follows `https://YOUR-USERNAME.github.io/piececraft-puzzles/`. Replace `YOUR-USERNAME` with the repository owner's GitHub username.

## Customer support

**PIECECRAFT — Puzzles & Creative Challenges**

- Email: `support@piececraft.example`
- Phone: `+1 (800) 555-0142` (demo number)
- Hours shown in the demo: Monday–Friday, 9 AM–5 PM Eastern Time

**These are placeholders, not live support channels.** The `.example` domain is reserved for documentation, and the phone number is fictional. Replace both with official contact details before launching commercially.

## V2 image improvements

V2 replaces the V1 catalog imagery with separate, locally stored image assets matched to the displayed products. Product tiles use a 4:3 frame and contain-fit rendering so the full image remains visible without forcing a square crop. Images are stored without card controls, prices, labels, or wishlist icons.

## Quality checklist

- [x] Logo included locally
- [x] Hero image included locally
- [x] 12 individually generated square product photographs (900 × 900 px) included
- [x] Product catalog validates as JSON
- [x] Every product points to its own local, square image file
- [x] Search, filter, and sort controls implemented
- [x] Product details dialog implemented
- [x] Cart quantity and subtotal logic implemented
- [x] Favorites and browser persistence implemented
- [x] Responsive layout and mobile breakpoints included
- [x] Support links included in footer
- [x] Local references and ZIP integrity checked
- [ ] Replace placeholder support contacts
- [ ] Confirm actual SKUs, prices, specifications, and availability
- [ ] Connect payment and order processing for a commercial launch

## Image quality — V3

V3 replaces the earlier image crops with individually exported 900 × 900 product photographs. Product files are square, the white collage dividers are excluded from the crops, and the storefront renders each image edge-to-edge in its own image tile. The hero uses a separate wide lifestyle photograph. Product visuals are generated concept imagery and do not represent verified retail SKUs.

## Project status

**Status: In development.** This package is a functional static frontend demo. A real commercial launch requires confirmed product data, live support information, and any required commerce integrations.

## License

No open-source license has been selected. All rights not expressly granted remain reserved. Review rights for any third-party assets before commercial use.

---

**PIECECRAFT — Every piece has a place.**

© 2026 PIECECRAFT Puzzles & Creative Challenges. All rights reserved.
