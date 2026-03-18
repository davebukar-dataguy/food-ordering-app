# Food Ordering App

A simple **Python application** that allows users to order food items (Pizza, Burger, Noodles), choose quantities, and view a receipt for their order. This project demonstrates basic Python programming, user input handling, and simple cart management.

---

## Project Overview

The Food Ordering App simulates a small food vendor's ordering system. Users can:

* View a menu of available food items
* Select items and specify quantities
* Add multiple items to a shopping cart
* View the final receipt with total prices

The app uses Python functions to capture user input, calculate totals, and display the cart in a clean, organized format.

---

## Menu Items

| Item    | Price (USD) |
| ------- | ----------- |
| Pizza   | 26.00       |
| Burger  | 22.00       |
| Noodles | 15.00       |

> Users can order multiple items in different quantities.

---

## Features

* Display a menu with item names and prices
* Capture valid user choices with input validation
* Allow users to order multiple items and quantities
* Calculate total prices for each item and overall order
* Display a formatted receipt at checkout
* Handle invalid inputs and edge cases gracefully
* Includes unit testing using `unittest` and `mock`

---

## Files in this Project

* `food_ordering_app.ipynb` – Jupyter Notebook version of the project (interactive)
* `food_ordering_app.py` – Python script version that can be run from the terminal
* `README.md` – Project overview and documentation

---

## Installation & Running

1. **Clone the repository:**

```bash
git clone https://github.com/YourUsername/food-ordering-app.git
cd food-ordering-app
```

2. **Run the Python script:**

```bash
python food_ordering_app.py
```

---

## Example Usage

```
Welcome to the Food Ordering App!

Menu:
1. Pizza - 26.00
2. Burger - 22.00
3. Noodles - 15.00
4. Exit Menu

Enter your choice (1-4): 1
Enter quantity to buy: 2

Enter your choice (1-4): 4

Checking out...
Your order details:
Item 1: Quantity - 2, Total Price - 52.0
Total Order Price: 52.0
Thank you for ordering!
```

---

## Testing

This project includes unit tests for:

* User input validation
* Quantity handling
* Order placement
* Checkout functionality

Run tests directly within the notebook or integrate into your Python workflow.

---

## Future Improvements

* Add a graphical user interface (GUI)
* Store orders in a database
* Add more menu items dynamically
* Implement payment simulation

---

## Author

**David Abukar**
Data Analyst | Python | SQL | Excel

---
