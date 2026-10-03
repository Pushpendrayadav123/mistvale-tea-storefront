# Mistvale Tea Co. storefront

A responsive, single-page storefront prototype for Mistvale Tea Co. The page is implemented in [`index.html`](index.html); styles, product data, and browser-side behavior are embedded in that file. Product photography and the logo are in [`images/`](images/).

## Run locally

No build step, package manager, or server-side runtime is required. Open `index.html` in a modern browser, or serve this folder with any static HTTP server. For example:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Storefront features

- Eight sample teas with prices in Indian rupees, stock status, descriptions, and images.
- Product search, category filters, sorting, and product quick views.
- A shopping cart saved in browser `localStorage`, with stock and per-item quantity limits.
- Coupon entry (`WELCOME10`), cart totals, and a simulated pincode delivery estimate.
- FAQ, newsletter form feedback, responsive layout, and basic accessibility support such as keyboard focus styles and live status messages.

## Prototype limitations

This is a front-end preview, not a connected store. Product search and pincode checks are simulated in the page; cart contents stay in the current browser. Newsletter sign-ups are not submitted. Checkout points to the placeholder `mistvale.example` domain, and the contact/social links use example details. Connect real services and replace these placeholders before using the page as a live shop.

## Project files

```text
.
├── README.md
├── index.html
└── images/
    ├── product and gift-box images
    ├── Mistvale-Tea-logo.jpg
    └── mistvale-tea-garden-hero.png
```
