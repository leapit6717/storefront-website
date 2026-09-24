# Blush and Luxe Boutique

## Website Purpose

Blush and Luxe Boutique is an e-commerce website created by Leah Semaj Pittman for the SDC260 course. The store offers designer-inspired handbags, jewelry, sunglasses, wallets, beauty products, shoes, fragrance, and feminine accessories.

Customers can browse ten products, view product descriptions and prices, add products to a shopping cart, adjust quantities, remove products, apply a coupon, and complete a demonstration checkout.

## Website Pages

* `index.html` - Store homepage
* `shop.html` - Product catalog containing ten products
* `product-details.html` - Featured product information
* `cart.html` - Interactive shopping cart
* `checkout.html` - Shipping, payment, coupon, and checkout form
* `order-confirmation.html` - Completed order information
* `about-contact.html` - Store information and contact form
* `styles.css` - Website colors, layout, forms, cart, and responsive design
* `script.js` - Products, cart, inventory, form validation, coupon, and checkout functions
* `images` - Folder containing the ten product images

## Products

The store currently displays the following ten products:

1. Blush Designer Handbag
2. Gold Charm Bracelet
3. Rose Gold Sunglasses
4. Burgundy Luxe Wallet
5. Pink Beauty Bag
6. Pearl Drop Earrings
7. Blush High Heels
8. Blush Luxe Perfume
9. Blush Satin Scarf
10. Jeweled Hair Clip

## Brand Colors

* Deep Burgundy: `#4A102A`
* Rose Pink: `#B83268`
* Blush Pink: `#FCE7F3`
* Soft Cream: `#FFF1E6`
* White: `#FFFFFF`

## Product Display Features

* Uses a JavaScript loop to display ten products
* Displays each product’s name, image, description, category, price, and available stock
* Uses a responsive product layout
* Displays products correctly on desktop, tablet, and mobile screens
* Provides descriptive alternative text for product images

## Shopping Cart Features

* Allows products to be added to the shopping cart
* Displays product names, prices, quantities, and item totals
* Calculates and displays the current cart total
* Allows customers to increase or decrease product quantities
* Allows individual products to be removed
* Includes a button to clear the entire shopping cart
* Includes a button that navigates to the checkout page
* Saves the shopping cart through browser refreshes using local storage
* Displays immediate confirmation when a product is added
* Displays the number of products currently in the cart

## Inventory Features

* Reduces the available stock when a product is added to the cart
* Increases the available stock when a product is removed
* Updates inventory when the quantity is changed
* Prevents customers from adding products with zero available stock
* Disables the Add to Cart button when a product sells out
* Displays an “Out of Stock” message and tooltip

## Contact and Checkout Features

* Validates the required contact form fields
* Validates the customer’s shipping information
* Validates demonstration payment information
* Displays the products from the shopping cart in the order summary
* Calculates the order subtotal automatically
* Checks whether a coupon code exists
* Applies a 20 percent discount with coupon code `BLUSH20`
* Prevents checkout when the shopping cart is empty
* Creates a demonstration order number
* Displays purchased products and the final total on the order confirmation page

## Feature Roadmap

### Phase 1 - Initial Setup

* Created the basic website structure
* Created the store homepage
* Created the GitHub repository
* Created an external stylesheet

### Phase 2 - Core Features

* Added the main website content
* Added navigation to every page
* Added product images and descriptions
* Created the cart and checkout pages
* Created the contact form

### Phase 3 - Design and Usability

* Applied the boutique color palette
* Made the website responsive
* Added accessible image descriptions
* Added JavaScript product display
* Added contact and checkout form validation
* Added coupon validation and discount calculations

### Phase 4 - Shopping Cart and Inventory

* Created a functional shopping cart
* Added quantity adjustment controls
* Added individual product removal
* Added a Clear Entire Cart button
* Added browser storage for the cart and inventory
* Added inventory tracking
* Added out-of-stock protection
* Connected the cart to checkout
* Added order confirmation logic
* Tested the shopping, cart, coupon, checkout, and confirmation process

## Coupon Code

Use the following coupon code during the demonstration checkout:

`BLUSH20`

This coupon applies a 20 percent discount to the order total.

## Viewing the Website

Open `index.html` in a web browser to begin viewing the website. Use the navigation menu to visit the shop, shopping cart, checkout, contact, and other pages.

## Project Author

Leah Semaj Pittman
SDC260 Website Project
September 2026
