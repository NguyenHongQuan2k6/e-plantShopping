# Paradise Nursery Shopping Application

**Paradise Nursery** is an online plant shop built with **React** and **Redux Toolkit**. It lets customers browse houseplants, add them to a shopping cart, and manage the cart before checkout.

## Features

- **Landing page** with the company name, a background image, a short "About Us" section, and a **Get Started** button.
- **Product listing page** with plants grouped into categories (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, Low Maintenance). Each plant shows a thumbnail, name, description, and price.
- **Add to Cart** buttons that add the plant to the cart, disable themselves once the plant is added, and update the cart icon count.
- **Navigation bar** with links to Home, Plants, and Cart, shown on both the product listing and the cart page.
- **Shopping cart page** showing each plant's thumbnail, name, unit price, quantity, and subtotal, plus the total cart amount.
- Buttons to **increase**, **decrease**, and **delete** items, a **Continue Shopping** button, and a **Checkout** button (Coming Soon).

## Tech Stack

- React 18 + Vite
- Redux Toolkit / React Redux (`CartSlice.jsx`, `store.js`)

## Getting Started

```bash
npm install
npm run dev
```
