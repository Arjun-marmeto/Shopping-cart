PSEUDOCODE

START
1. Initialize Product Data
    - Define products with id, name, image, price, and quantity
2. Initialize Cart
    - Create an empty cart array to store cart items
3. Define Functions
    - addToCart(product): Add or update product quantity in cart
    - removeFromCart(productId): Remove product from cart
    - getTotalPrice(): Calculate and return total price of items in cart
    - getAveragePrice(): Calculate and return average price of items in cart
    - filterProducts(minPrice): Filter products based on minimum price
    - sortCart(order): Sort cart items based on price (ascending/descending)
    - clearCart(): Empty the cart and display a message
4. Handle UI Interactions
    - On Add to Cart button click: Add product to cart
    - On Remove from Cart button click: Remove product from cart
    - On Clear Cart button click: Clear the cart
    - On Sort button click: Sort cart items
    - On Filter button click: Filter products based on price
    - On Go to Checkout button click: Redirect to cart page
5. On Page Load
    - Load and display products
    - Update cart UI
END
