# Shoe Inventory Management System

This project is a simple inventory management system to manage information about shoes.

## Table of Contents

- Description
- How to use
- Functions

## Description

This project allows you to manage information about shoes such as their country of origin, product code, product name, cost, and quantity.

## How to Use

To use this project, you can simply download the source code from the repository and run it in a Python environment. When you run the code, you will be prompted to enter commands such as "1" to view all the products, "2" to add a new product, "3" to search for a product by its code, "4" to restock a product, "5" to view the value per item of all the products, and "6" to view the product with the highest quantity.

## Functions

Here are the functions available in this project:

- `read_shoes_data()`: This function reads all the data from the text file.
- `update_file()`: This function updates the inventory file with the current data.
- `capture_shoes()`: This function captures new information about a product and adds it to the inventory.
- `view_all()`: This function prints out all the products in the inventory.
- `re_stock()`: This function restocks the product with the lowest quantity in the inventory.
- `seach_shoe(item_c)`: This function searches for a product in the inventory by its code.
- `value_per_item()`: This function prints out the value per item of all the products in the inventory.
- `highest_qty()`: This function prints out the product with the highest quantity in the inventory.