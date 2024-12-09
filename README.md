# Python Challenge 1: Interactive Food Truck Ordering System

**Author:** Peyton Lambourne  

---

## Overview

This project presents a command-line interactive ordering system for a diverse food truck menu. Customers can select items from various categories, specify quantities, and receive a formatted receipt including the total cost of their order. Throughout this challenge, input validation, dictionary lookups, user guidance, and Python control structures (including match-case statements) are demonstrated.

---

## Features

- **User-Friendly Menu Navigation:**  
  Customers can easily browse through a structured, multi-tiered menu. Categories like Snacks, Meals, Drinks, and Desserts are presented, followed by their corresponding items and prices.

- **Dynamic Ordering Process:**  
  The program continuously prompts users for their selections until they decide to stop. Each chosen item (and its price and quantity) is recorded in a dedicated order list.

- **Input Validation and Error Handling:**  
  The program checks user inputs at every step. Users are alerted if they provide invalid numbers or menu selections. If an invalid quantity is entered, it defaults to 1 and notifies the user.

- **Flexible Control Flow With Match-Case:**  
  Once the user finishes selecting items, a match-case statement handles whether they want to continue or end the ordering process.

- **Formatted Receipt and Totals:**  
  The final step prints out each ordered item, price, and quantity in a neat, aligned table. Using list comprehension, the total cost of the order is calculated and displayed to the user.

---

## Assignment Requirements

**Order System (54 points):**
- An initialized order list.
- Prompting for `menu_selection` and validating it as a number.
- Conversion of `menu_selection` to an integer.
- Checking `menu_selection` against `menu_items` keys and handling errors.
- Extracting the item name and price from `menu_items`.
- Prompting for item quantity with a default of 1 if invalid input is provided.
- Appending item details (name, price, quantity) to `order_list`.
- Using a match-case statement (y/n) to decide whether to keep ordering or complete the order.

**Order Receipt (46 points):**
- A for loop to iterate through `order_list`.
- Assigning dictionary values (item name, price, quantity) to variables.
- Calculating and adding spacing for a neatly formatted receipt.
- Printing out each item line, including name, price, and quantity, aligned properly.
- Using list comprehension to compute the total cost and printing it.
