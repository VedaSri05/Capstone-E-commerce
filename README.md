# Capstone E-Commerce

A feature-rich e-commerce web application that allows users to browse products, add them to their cart, and view their selections in a dedicated cart page. The application utilizes modern JavaScript features and local storage to manage user interactions.

## Project Structure

- `cart.html`: The HTML file for displaying the shopping cart.
- `cart.js`: JavaScript file handling the cart functionality and logic.
- `createHorizontalProductCard.js`: Script for creating horizontal product cards for display.
- `createProductCard.js`: Script for creating vertical product cards for display.
- `index.html`: The main HTML file where products are listed.
- `index.js`: JavaScript file handling product listing, filtering, and cart management.
- `style.css`: CSS file for styling the application and enhancing user experience.

## Features
- Displays a list of products fetched from a local database (`db/products.js`).
- Users can filter products based on their ratings.
- Users can add products to their cart and are redirected to the cart page upon clicking the cart button.
- The application saves the cart state in the browser's local storage for persistence.

## Technologies Used
- **HTML**: For structuring the product listing and cart layout.
- **CSS**: For styling the application and improving user experience.
- **JavaScript**: For implementing product filtering, adding to the cart, and managing local storage.
- **Local Storage**: For persisting the cart data across page refreshes.
