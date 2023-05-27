# Online Store Management System

This is a simple command-line based Online Store Management System implemented in C. It allows users to manage products, add products to a shopping cart, view the cart, generate bills, and save order details. The system supports two types of users: **Admin** and **Customer**.

## Features

The Online Store Management System provides the following features:

### Admin Features

1. Add a new product to the store
2. Delete an existing product from the store
3. Display the list of products in the store

### Customer Features

1. Display the list of products in the store
2. Sort and display products by price
3. Add a product to the shopping cart
4. View the contents of the shopping cart
5. Print a bill for the items in the cart
6. Save order details and clear the cart
7. View order history

## Getting Started

To compile and run the Online Store Management System, follow these steps:

1. Clone the repository or download the source code files.
2. Navigate to the project directory in your terminal.
3. Compile the code using the following command:

   ```
   gh repo clone lokesh10111/Online-Store-Management-System
   ```

4. Run the compiled executable:

   ```
   ./store management
   ```

## Usage

### Admin Mode

When running the program, you will be prompted to choose between **Admin** and **Customer** modes. To access the admin features, choose **Admin** and enter the admin password when prompted.

Once in admin mode, you can choose from the following options:

1. Add Product: Enter the details of a new product to add it to the store.
2. Delete Product: Enter the name of a product to remove it from the store.
3. Display Products: View the list of products currently in the store.
4. Exit: Exit the program.

### Customer Mode

To access the customer features, choose **Customer** when prompted. You will be asked to enter your name.

Once in customer mode, you can choose from the following options:

1. Display Products: View the list of products in the store.
2. Sort and Display Products: Sort the products by price and display them.
3. Buy Product: Enter the name of a product to add it to your shopping cart.
4. View Cart: View the contents of your shopping cart.
5. Print Bill: Generate a bill for the items in your cart.
6. Save Order Details: Save the details of your order and clear the cart.
7. View Order History: View the history of your past orders.
8. Exit: Exit the program.

## File Management

The system uses two files for data storage: **products.txt** and **cart.txt**. The **products.txt** file stores the product information, and the **cart.txt** file stores the items in the shopping cart. Additionally, each customer has a separate order file named **[username]_order.txt** to store their order history.

## Dependencies

This program does not have any external dependencies. It uses standard C libraries such as `stdio.h`, `stdlib.h`, `string.h`, and `time.h`.

## Contributing

Contributions to the Online Store Management System are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code according to your needs.
