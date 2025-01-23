# CLI Clothing Store

This is a command-line interface (CLI) application for managing a clothing store database I created. The application is built with Python and SQLite and allows users to interact with the store's database to view products, create accounts, add items to a cart, and confirm orders.

## Features

- View available products with details such as price and stock.
- Create and manage customer accounts.
- Add items to a cart and adjust quantities.
- Confirm orders, process payments, and track deliveries.

## How It Works

1. **View Products**: Browse all available products in the store's inventory.
2. **Create Account**: New users can create an account, while existing users can log in using their Customer ID.
3. **Add to Cart**: Select products and specify quantities to add to your shopping cart.
4. **Confirm Order**: Finalize your order, view the total price, and track your order status.

## Database Schema

Ensure your SQLite database has the following tables:

- **Product**: Stores product details like `Product_ID`, `Name`, `Price`, and `Stock`.
- **Customer**: Stores customer information such as `Customer_ID`, `First_name`, `Last_name`, `Email`, etc.
- **Cart**: Tracks items in a customer's cart.
- **Order**: Records customer orders with details like `Order_ID`, `Customer_ID`, and `Total_price`.
- **Payment**: Handles payment details and statuses.
- **Delivery**: Tracks delivery status for orders.
