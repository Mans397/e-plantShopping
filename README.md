# e-plantShopping

**Paradise Nursery** – an online plant shop built with React, Vite and Redux Toolkit.

## Overview
e-plantShopping is a shopping cart application for Paradise Nursery, an online store offering a variety of house plants.

### Features
- Landing page with a background image, company description (About Us) and a **Get Started** button
- Navigation bar with links to the home page, plant listing page and shopping cart (with a live item counter)
- Product listing grouped into categories (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, Low Maintenance) – each plant card shows image, name, description, price and an **Add to Cart** button
- Shopping cart page with thumbnail, unit price, subtotal per plant, **+ / −** quantity buttons, **Delete** button and total cart amount
- **Continue Shopping** and **Checkout** buttons
- Global state management with Redux Toolkit (`CartSlice.jsx`, `store.js`)

## Run locally
```bash
npm install
npm run dev
```

## Deploy (GitHub Pages)
```bash
npm run deploy
```
