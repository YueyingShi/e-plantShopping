# Paradise Nursery 🌿

**Paradise Nursery – Where Green Meets Serenity** is a React shopping cart application for browsing and buying houseplants. Users can explore plants by category, add them to a cart, adjust quantities, and review their order.

## Features

- Landing page with a **Get Started** call to action.
- Product catalog grouped by category (Air Purifying, Aromatic, Insect Repellent, Medicinal, and Low Maintenance plants).
- **Add to Cart** button that disables and shows "Added" once an item is in the cart.
- Live cart badge showing the total number of items on the cart icon.
- Cart page to increase/decrease quantity, delete items, and view the total amount.
- **Continue Shopping** and **Checkout** actions.

## Tech Stack

- **React 18** (functional components + hooks)
- **Redux Toolkit** + **React Redux** for cart state management
- **Vite** for development and build tooling

## Getting Started

```bash
npm install       # install dependencies
npm run dev       # start the development server
npm run build     # create a production build
npm run preview   # preview the production build
```

The dev server prints a local URL (for example `http://localhost:5173`) — open it in your browser.

## Project Structure

```
src/
  App.jsx          # Landing page and view switching
  ProductList.jsx  # Plant catalog and navbar
  CartItem.jsx     # Cart view and item controls
  CartSlice.jsx    # Redux slice for cart state
  store.js         # Redux store configuration
```
