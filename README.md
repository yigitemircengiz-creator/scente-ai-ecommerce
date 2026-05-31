# Scenté® — Fine Fragrance E-Commerce Website

A fully self-contained luxury perfume e-commerce website built with vanilla HTML, CSS, and JavaScript. No frameworks, no build tools, no server required — just open `index.html` in a browser.

---

## ✨ Features

### 🛍️ Shopping
- 10 curated fragrances across Unisex, Women, and Men categories
- 50ml / 100ml size selection with dynamic pricing
- Add to cart with instant visual feedback
- Discount codes: `SCENTE10`, `WELCOME15`, `VIP20`
- Full checkout flow — shipping address + card details + order confirmation with unique order code

### ❤️ Favorites
- Add/remove fragrances to a personal favorites list
- Heart icon on product card syncs instantly across all views
- Favorites panel with quick navigation to product

### 🔍 Product Detail
- Fragrance pyramid (Top / Heart / Base notes)
- Star rating system (saved per browser)
- "Customers also bought" suggestions
- Compare up to 2 fragrances side by side

### 👤 Account System
- Register / Login with email and password
- Profile page: order history, wishlist count, loyalty points
- Gold / Silver / Platinum membership tiers
- All data stored in `localStorage` — no backend needed

### 🤖 Scenté Assistant (AI Chatbot)
- Keyword-based chatbot with full product knowledge
- Answers in Turkish or English automatically
- Covers: fragrance recommendations, shipping, returns, stock, payment, gifting, discounts, layering tips
- Cart-aware: reads user's current cart for personalized responses

### 🎨 UX & Design
- Full-screen scroll-snap sections, one perfume per scene
- Unique background image per fragrance
- Animated intro (logo scale-in, tagline & button fade-up)
- Contact bar slides up on hover near bottom of screen
- Newsletter popup with discount code
- All assets embedded as base64 — truly single-file

---

## 📁 File Structure

```
scente-ai-ecommerce/
├── index.html    ← Entire app — completely self-contained (~7MB)
└── README.md
```

That's it. Upload both files to the same folder and open `index.html`. All images (bottle photos, backgrounds, logo) are embedded directly inside `index.html` as base64 data URLs. No external files, no CDN dependencies, no internet connection required after the initial font load.

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/yourusername/scente.git
cd scente

# Open directly in browser (no server needed)
open index.html
# or
start index.html
```

No npm, no build step, no dependencies.

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, backdrop-filter, animations) |
| Logic | Vanilla JavaScript (ES2020) |
| Storage | `localStorage` (cart, favorites, ratings, account) |
| Fonts | Google Fonts — Dancing Script, Playfair Display, Montserrat |
| Assets | Base64 embedded (PNG, JPG, WEBP, GIF) |

---

## 🏪 Discount Codes

| Code | Discount |
|------|----------|
| `SCENTE10` | 10% off |
| `WELCOME15` | 15% off |
| `VIP20` | 20% off |

---

## 📬 Contact

| Channel | Info |
|---------|------|
| Instagram | [@scente.official](https://instagram.com/scente.official) |
| Email | scente@gmail.com |
| Phone | 850 342 2234 |

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

*Built with elegance. Distilled from nature's purest essences.*
