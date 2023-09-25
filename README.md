# Shopping Basket Cost Calculator

A Python program that calculates the total cost of a customer's shopping basket, including shipping.

- If a customer spends over $100, they get free shipping.
- If a customer spends less than $100, the shipping cost is $1.20 per kg of the basket's weight.

## Project Overview

This Python program helps you determine the total cost of a customer's shopping basket, considering the shipping cost. It works as follows:

1. Set the `customer_basket_cost`, `customer_basket_weight`, and `shipping_cost_per_kg` variables to match the customer's shopping basket and shipping rates.

2. The program calculates the total cost, taking into account the shipping cost based on the rules mentioned above.

3. It then prints the customer's total basket cost (including shipping).

## Example

In the provided code snippet:

```python
customer_basket_cost = 34
customer_basket_weight = 44
shipping_cost_per_kg = 1.20

# Calculate the total cost
if customer_basket_cost > 100:
    print(customer_basket_cost)
else:
    shipping_cost = customer_basket_weight * shipping_cost_per_kg
    customer_basket_cost += shipping_cost
    print("Total basket cost -> $", customer_basket_cost)

customer_basket_cost is set to $34.
customer_basket_weight is set to 44 kg.
shipping_cost_per_kg is set to $1.20 per kg.

The program calculates the total basket cost (including shipping) and prints it.

# Usage

1. Clone this repository to your local machine:

git clone https://github.com/onurcangnc/THM-Python-Project3.git

2. Open the project directory in your preferred code editor.

3. Modify the customer_basket_cost, customer_basket_weight, and shipping_cost_per_kg variables in the script to match your customer's shopping details.

4. Run the script

python shopping_basket_cost_calculator.py

The program will calculate and display the total basket cost.

Feel free to customize this project according to your needs.