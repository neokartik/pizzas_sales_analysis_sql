# Pizza Sales Analysis Project

This project analyzes pizza sales data to uncover insights about customer preferences, popular pizza categories, and revenue trends. The dataset consists of four CSV files detailing orders, pizza types, and their pricing information.

---

## Table of Contents
- [Introduction](#introduction)
- [Dataset Description](dataset-description)
- [Setup Instructions](setup-instructions)
- [SQL Queries and Analysis](sql-queries-and-analysis)
- [Results and Insights](results-and-insights)
  
---

## Introduction

In this project, we use a relational database approach to analyze pizza sales data. The objective is to perform data cleaning, join operations, and aggregations to extract valuable insights about sales performance.

---

## Dataset Description

### 1. `order_details.csv`
Details about each pizza ordered:
- **`order_details_id`**: Unique identifier for the order detail.
- **`order_id`**: Reference to the `order_id` in the `orders` table.
- **`pizza_id`**: Identifier for the pizza in the `pizzas` table.
- **`quantity`**: Number of pizzas ordered.

### 2. `orders.csv`
Details about customer orders:
- **`order_id`**: Unique identifier for each order.
- **`date`**: Date when the order was placed.

### 3. `pizza_type.csv`
Details about pizza types:
- **`pizza_type_id`**: Unique identifier for the type of pizza.
- **`name`**: Name of the pizza.
- **`category`**: Category of the pizza (e.g., Chicken, Classic, Veggie).

### 4. `pizzas.csv`
Details about specific pizzas:
- **`pizza_id`**: Unique identifier for each pizza.
- **`pizza_type_id`**: Reference to the `pizza_type_id` in the `pizza_type` table.
- **`size`**: Size of the pizza (Small, Medium, Large).
- **`price`**: Price of the pizza based on its size.


