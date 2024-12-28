# Super-Market-Billing
Project Overview
This project is a Supermarket Billing System that allows for the management of products and the processing of customer orders. The system is designed to enable administrators to create, modify, delete, and display products. Customers can place orders, generate invoices, and calculate the total price of their purchases with discounts.

Features
For Admin:
Create Product: Allows the admin to create a new product with details like Product No, Name, Price, and Discount.
Display All Products: View the list of all available products with their details.
Modify Product: Modify the details of an existing product.
Delete Product: Delete a product from the inventory.
View Product Menu: View a list of all products with prices.
For Customers:
Place Order: Customers can order products by selecting the product number and entering the quantity. The system will generate a bill with product details and apply discounts.
Additional Features:
Invoice Generation: After placing an order, an invoice is generated with the total amount, showing product details, prices, and the discounted amount.
Technologies Used:
C++
File Handling (using fstream to read and write data to files)
Windows API (windows.h for cursor movement using gotoxy)
Standard C++ Libraries (<iostream>, <fstream>, <stdio.h>, <cstdlib>, etc.)
Setup Instructions
Prerequisites:
A C++ compiler that supports conio.h and windows.h.
Windows operating system for proper usage of gotoxy (Windows-specific functionality).
Usage:
Upon running the program, the user will be presented with a Main Menu.
The user can choose between Customer and Administrator options:
Customer: Allows the customer to place an order.
Administrator: Provides access to product management features (create, modify, delete, view).
The program also generates invoices for the customer's purchases and displays the total amount with applied discounts.
Code Structure:
product class: Represents a product with attributes like product number, name, price, quantity, tax, and discount. This class also contains methods to create and display product details.
Main Functions: Includes various functions for writing to the file, displaying products, modifying records, placing orders, and generating invoices.
Sample Output
Admin Menu:
1. CREATE PRODUCT
2. DISPLAY ALL PRODUCTS
3. QUERY
4. MODIFY PRODUCT
5. DELETE PRODUCT
6. VIEW PRODUCT MENU
7. BACK TO MAIN MENU
Customer Order (Invoice Example):
Product No | Product Name | Quantity | Price | Amount | Discounted Amount
----------------------------------------------------------------------
101        | Milk         | 2        | 50    | 100    | 90
102        | Cereal       | 1        | 120   | 120    | 108

TOTAL = 198
License:
This project is open-source and available under the MIT License.
