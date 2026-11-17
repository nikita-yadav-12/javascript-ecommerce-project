# Amazon E-commerce Website

A frontend e-commerce project inspired by Amazon, built using HTML, CSS, and JavaScript. The project focuses on dynamically displaying products and implementing shopping cart functionality using JavaScript.

## Features

### Currently Implemented
- **Dynamic Product Listing:** Product information is stored in a JavaScript file as an array of objects rather than writing individual product HTML elements manually.
- **Product Information:** Displays product images, names, ratings, review counts, and prices.
- **Add to Cart:** Clicking the Add to Cart button adds the selected product to the cart array.
- **Cart Quantity Update:** The cart quantity displayed in the header updates whenever a product is added to the cart.
- **Dynamic HTML Generation:** JavaScript is used to generate the product elements and display them on the webpage.

### Work in Progress
The project is currently under development. Some of the functionality planned for future implementation includes:

- Displaying added products on a separate cart page.
- Implementing product quantity management.
- Updating product quantities and prices dynamically in the cart.
- Calculating the total order price.
- Implementing checkout functionality.
- Adding additional interactive features.

## Built With

- HTML5
- CSS3
- JavaScript (Vanilla JS)

## How It Works

Product information is maintained in a JavaScript file using an array of objects. Each object contains details such as the product ID, image, name, rating, price, and keywords.

JavaScript accesses this product data and dynamically generates the HTML for displaying products on the webpage.

When the user clicks the Add to Cart button, the selected product is added to a cart array. The cart quantity in the header is then updated to reflect the number of items added.

Currently, the cart functionality updates the cart array and its quantity indicator, but the added products are not yet displayed on the cart page.
