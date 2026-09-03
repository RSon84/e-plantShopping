# Paradise Nursery

Paradise Nursery is a responsive plant-shopping web app built with React, Redux Toolkit, and Vite. Users can browse plants by category, add products to a cart, adjust quantities, remove items, and view the total cost of their order.

## Features

- Landing page with an introduction to Paradise Nursery
- Plant catalog organized into five categories
- Product cards with images, descriptions, and prices
- Add-to-cart functionality with visual feedback
- Live cart item count in the navigation bar
- Increase, decrease, and remove cart items
- Automatically calculated item totals and order total
- Continue-shopping navigation

> **Note:** Checkout is currently a placeholder and does not process payments.

Open the local URL shown in the terminal, usually `http://localhost:5173`.


## How the Cart Works

Redux Toolkit stores the cart items and their quantities. Adding a plant dispatches an `addItem` action. Quantity controls dispatch `updateQuantity`, while deleting an item dispatches `removeItem`. The cart total is recalculated from the current Redux state whenever the cart renders.

## Repository Location

[github.com/RSon84/e-plantShopping](https://github.com/RSon84/e-plantShopping)
