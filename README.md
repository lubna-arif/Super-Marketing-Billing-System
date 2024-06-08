# Super-Marketing-Billing-System
The Super Market System is a C++ program designed for efficient management of products in a supermarket. It utilizes object-oriented programming principles to define a "Product" class and implements various functionalities to add, modify, delete, and display product records.

Header Files Included:

#include<iostream>
#include<fstream>
#include<string>
#include<iomanip>
#include"SuperMarketBilling.h"
Product Class:
The "Product" class represents supermarket products, containing private member variables for product number, name, price, quantity, tax, and discount. It provides getter and setter methods for accessing and modifying these variables, along with a method to calculate the total price after considering tax and discount.

File Handling:
The program employs file handling to read product records from the "products.txt" file and write updated records back to it. Functions like "readProductsFromFile" and "writeProductsToFile" manage the reading and writing of product details, respectively.

Functionality:
The program offers the following functionalities through a menu-driven interface:
a) Add Product: Allows users to input product details and adds a new product to the array.
b) Modify Product: Enables users to update product details based on the entered product number.
c) Delete Product: Lets users remove a product from the array by entering its product number.
d) Display All Products: Shows all product records present in the array, including details.
e) Exit: Writes updated product records to the file and exits the program.

These functionalities streamline product management operations, enhancing efficiency and organization within the supermarket system.
