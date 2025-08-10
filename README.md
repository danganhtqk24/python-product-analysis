# Product Analysis using Python
## Overview
In this project, I will build a programme that helps a company gain insights into which of their products generate the best sales and profits by analyzing a list of products represented as dictionaries.
Each product contains the following keys: name, price, and sales. Assume that all product names are in title case and have no duplicate values. 
## Functions explanation
(a) ``most_expensive(products: list[dict], k: int = 3) -> list[dict]:`` This function takes a list of products and returns a list of the top k most expensive products, sorted by price in descending order.

(b) ``bestsellers(products: list[dict], k: int = 3) -> list[dict]:`` This function takes a list of products and returns a list of the top k best-selling products (i.e., those with the highest sales values), sorted by sales in descending order.

(c) ``most_profitable(products: list[dict], k: int = 3) -> list[dict]:`` This function takes a list of products, calculates the profit (i.e., price times sales) earned by each product, and returns a list of the top k most profitable products (i.e., those with the highest profits), sorted by the profit value in descending order. 

(d) ``print_tops(products: list[dict], k: int = 3) -> None:`` This void function takes a list of products, and prints the top k most expensive, best-selling, and most profitable products. It utilizes the above three functions, developed in part (a) to (c), to retrieve the required products.
