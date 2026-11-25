# Tiny Treasures — Baby Products Store

A responsive baby-products storefront built with HTML, CSS and vanilla JavaScript.

## Pages
- Home, Shop, Product details, Basket, Checkout
- About, Contact, Login, Register and Profile

## Run locally
1. Extract the ZIP.
2. Open the `tiny-treasures` folder in VS Code.
3. Install the **Live Server** extension if you do not already have it.
4. Right-click `index.html` and choose **Open with Live Server**.

The product catalogue is loaded from `data/products.json`, so use a local server rather than opening the HTML file directly.

## Configure WhatsApp ordering
1. Open `js/config.js`.
2. Replace `2348012345678` with your store's WhatsApp number in international format.
   - Example format: `2348012345678`
   - Do not include `+`, spaces, or the leading zero.
3. Save and test checkout. It opens WhatsApp with the basket and customer delivery details.

## Before going live
- The 30 catalogue entries, prices and image links are sample content. Update `data/products.json` with your actual products, stock, prices and properly licensed product photos.
- Checkout sends an order request through WhatsApp. It does not collect card payments or automatically calculate delivery fees.
- Login/register/profile are demo-only and use browser localStorage. Passwords are not securely protected. Do not use this demo authentication for real customers. A production store needs a secure backend, database, HTTPS and a proper authentication/payment provider.
- Add your business policies, delivery timelines, returns policy and privacy notice before accepting real orders.

## Main files
- `data/products.json` — product catalogue
- `js/config.js` — store name and WhatsApp number
- `js/app.js` — shared layout, currency formatting and basket helpers
- `css/style.css` — responsive styling
