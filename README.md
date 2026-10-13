# Krums Storefront

A responsive storefront for Krums cookie brittle, built around the line “All snacks leave krums.” and the final warm-cream, cookie-brown, and crumb-red brand.

## Run locally

Open `index.html` directly, or from this directory run:

```powershell
python -m http.server 4173
```

Then visit `http://localhost:4173`.

## Pages

- `index.html` — home
- `shop.html` — shop
- `product.html` — flavor detail (`?flavor=chocolate-chip` or `?flavor=peanut-butter-chocolate`)
- `where-to-buy.html` — where to buy
- `contact.html` — contact

## Commerce

Product data lives in `script.js`. The `commerce.checkout()` adapter is the integration point for a hosted checkout provider. The cart UI persists in `localStorage`.

Flavors on sale are Chocolate Chip and Peanut Butter Chocolate Chip. A third flavor slot is shown as coming soon.
