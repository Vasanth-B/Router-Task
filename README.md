# BOWIES II - React Shopping Cart

## Project Overview
This is a simple e-commerce project built using React. It utilizes the Fake Store API to fetch product data and implements a shopping cart functionality. Users can view products, add them to a cart, adjust quantities, and proceed to checkout with a dynamic total price calculation.

## Demo : [Click Here!!!]()

## Features
- **Product Listing:** Displays a list of products fetched from the Fake Store API.
  
- **Product Details:** Clicking on a product leads to a detailed view of the product.
  
- **Shopping Cart:** Users can add and remove items from the cart, and adjust the quantity of each item.
  
- **Cart Total:** The total price is dynamically calculated, including a 10% discount.
  
- **Responsive Design:** The layout adjusts based on screen size for a mobile-friendly experience.
  
- **Routing:** The app includes navigation between the product list and the cart using react-router-dom.
  
## Tech Stack

- **React:** Component-based library for building user interfaces.
  
- **React Router:** For managing navigation between pages.
  
- **Tailwind CSS:** Utility-first CSS framework for styling the application.
  
- **Fake Store API:** Provides product data for this project.
  
- **Context API:** Manages the state of the shopping cart.

  ## Key Components

- **Navbar.jsx:** Provides navigation links to the product page and the cart, with a cart item count displayed.

- **Products.jsx:** Displays a list of products fetched from the Fake Store API. Each product card contains an image, title, description, price, and buttons to add/remove from the cart.

- **Cart.jsx:** Shows items that have been added to the cart. Users can increase or decrease the quantity of each item, and the total price is dynamically updated with a 10% discount applied.

- **ProductDetails.jsx:** Displays detailed information about a specific product when the user clicks on a product in the product list.
  
## Cart Functionality

1. **Add to Cart:** Adds the product to the cart and stores it in the global state managed by the Context API.
   
2. **Remove from Cart:** Removes the product from the cart.
   
3. **Quantity Adjustment:** Users can increase or decrease the quantity of items in the cart, and the total price will adjust accordingly.
   
4. **Discount:** A 10% discount is applied to the total price in the cart.

## File Structure

1. **src**
   
   - **assests**
        
     - fonts
       
   - **components**
     
     - Navbar.jsx
     - Products.jsx
     - Cart.jsx
     - ProductDetails.jsx

    - **context**
      - CartContext.jsx
        
    - **services**
      - ApiService.jsx
        
    - **App.js**
      
    - **index.css**
      
    - **README.md**
  
    - **main.jsx**
 


      

   



