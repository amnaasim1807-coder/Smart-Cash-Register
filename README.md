# Smart Cash Register

A lightweight C command-line application that acts as an optimized cash register, determining the absolute minimum number of coins required to give a user their change. 

## 🎓 Academic Credit
This project was developed as a solution to the **"Cash" problem set** in **Harvard University's CS50x: Introduction to Computer Science** course. All credit for the underlying problem definition, framework, and custom library headers (`<cs50.h>`) belongs to the CS50 course staff.

## 🚀 Features
* **Greedy Algorithm:** Automatically optimizes coin distribution using quarters (25¢), dimes (10¢), nickels (5¢), and pennies (1¢).
* **Input Validation:** Robust error handling that rejects negative values, non-numeric strings, or empty inputs.

## 🛠️ How It Works
1. Prompts the user for the amount of change owed (in cents).
2. Uses integer division and modular arithmetic helper functions to break down the total.
3. Outputs the absolute minimum count of coins needed to satisfy the amount.
