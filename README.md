Here's a revised version of the documentation for the "BOWIES II - React Shopping Cart" project:

---

# BOWIES II - React Shopping Cart

## Overview

**BOWIES II** is a streamlined e-commerce app built with React, offering users a seamless shopping experience. Using the Fake Store API, the app dynamically displays products, enabling users to view details, add items to their cart, adjust quantities, and proceed to checkout with real-time price calculations and a 10% discount on the cart total. This project features a responsive design, ensuring a smooth experience on both desktop and mobile devices.

### Live Demo: [View Here](https://router-app-react-task.netlify.app/)

---

## Key Features

- **Product Listing:** Displays products fetched from the Fake Store API, each with essential details and an "Add to Cart" option.
  
- **Product Details:** A detailed product view is available for each item when clicked, showing a larger image, description, and price.

- **Shopping Cart Functionality:** Users can add items to the cart, adjust quantities, remove items, and view a live total price with an automatic 10% discount.

- **Responsive Design:** The layout is optimized for all screen sizes, providing a mobile-friendly experience.
  
- **Page Navigation:** The app includes smooth navigation between product listings, product details, and the cart page, using `react-router-dom`.

---

## Technology Stack

- **React:** A component-based framework for building interactive UIs.
  
- **React Router:** Manages page navigation and routing for a single-page application experience.
  
- **Tailwind CSS:** A utility-first CSS framework that facilitates quick and responsive styling.
  
- **Fake Store API:** Supplies product data, eliminating the need for a custom backend.
  
- **Context API:** Provides a global state for managing the shopping cart across the app.

---

## Core Components

- **Navbar.jsx:** A navigation bar with links to the product list and cart, displaying the current number of items in the cart.

- **Products.jsx:** Lists all available products from the Fake Store API, with each card showing the product image, title, price, and a button to add/remove items from the cart.

- **Cart.jsx:** Displays selected cart items, allowing users to adjust quantities, remove items, and view the dynamically updated total (with a 10% discount applied).

- **ProductDetails.jsx:** Shows comprehensive information about a specific product, accessible when a product card is clicked.

---

## Shopping Cart Functionality

1. **Add to Cart:** Adds the selected product to the cart and updates the global cart state managed by Context API.
   
2. **Remove from Cart:** Removes a specific product from the cart and recalculates the total.
   
3. **Adjust Quantity:** Users can increase or decrease the quantity of each product in the cart, with real-time price adjustments.
   
4. **Discount Application:** The total cart price reflects a 10% discount automatically, providing a more engaging checkout experience.

---

## File Structure

```
src
├── assets
│   └── fonts           // Font assets for styling
├── components
│   ├── Navbar.jsx      // Top navigation bar
│   ├── Products.jsx    // Main product listing
│   ├── Cart.jsx        // Shopping cart page
│   └── ProductDetails.jsx // Detailed product view
├── context
│   └── CartContext.jsx // Context API for managing cart state
├── services
│   └── ApiService.jsx  // Service for API calls to Fake Store
├── App.js              // Main application component
├── index.css           // Global CSS styling
├── README.md           // Project documentation
└── main.jsx            // App entry point
```

---
