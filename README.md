# FR Store — Starter Website

A polished, responsive English-language storefront starter for FR Store.

## Included
- Luxury-inspired storefront design and category filtering
- Search, sorting, bag/cart and checkout form
- Automatic customer pricing: Markaz cost + Rs. 350
- Demo admin dashboard with order list, customer delivery details, order status, sales and estimated gross profit
- Add products from the admin dashboard, including an optional image URL

## Run locally
Open `index.html` in a modern browser. No build step is required.

## Demo admin login
- Username: `admin`
- Password: `FRstore2026`

**Change/remove these demo credentials before sharing the site.**

## Important launch limitations
This is a front-end prototype. Products, carts and orders are stored in that browser's `localStorage`; they are not shared between devices and can be cleared by the browser. The demo admin login is not secure authentication. Do not use it to collect real customer orders or sensitive information.

For a real launch, connect a secure backend/database and authenticated admin access, server-side order storage, backups, privacy/terms pages, delivery workflow, and verified payment handling. Markaz products are not automatically synced; add products manually unless Markaz provides an authorized API/feed. Demo product names and costs are placeholders, not actual Markaz listings.

## Deploy
You can publish the static prototype with GitHub Pages after uploading these files to your repository. A production order-management system requires a backend in addition to GitHub Pages.
