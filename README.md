# Zepto Inventory, Pricing & Revenue Analysis (SQL Project)

## Project Overview

This project analyzes Zepto's product inventory dataset using SQL to uncover insights related to pricing strategies, discounts, inventory management, and revenue opportunities.

The objective is to perform data exploration, data cleaning, and business analysis on real-world retail inventory data while demonstrating practical SQL skills commonly required for Data Analyst roles.

---

## Project Objectives

* Explore and understand the dataset structure.
* Clean and validate inventory data.
* Analyze pricing and discount strategies.
* Identify inventory-related business opportunities.
* Estimate category-wise revenue potential.
* Generate actionable business insights using SQL.

---

## Dataset Information

The dataset contains product-level inventory information from Zepto, including:

| Column Name            | Description                        |
| ---------------------- | ---------------------------------- |
| sku_id                 | Unique product identifier          |
| name                   | Product name                       |
| category               | Product category                   |
| mrp                    | Maximum Retail Price               |
| discountPercent        | Discount percentage offered        |
| discountedSellingPrice | Final selling price after discount |
| weightInGms            | Product weight in grams            |
| availableQuantity      | Available inventory quantity       |
| outOfStock             | Product stock status               |
| quantity               | Quantity description               |

---

## Tools & Technologies Used

* MySQL
* SQL
* GitHub

---

## SQL Skills Demonstrated


### Data Analysis

* GROUP BY
* HAVING
* CASE Statements
* Aggregate Functions

### Business Analytics

* Revenue Estimation
* Discount Analysis
* Inventory Analysis
* Product Segmentation

---

## Data Exploration

The following exploratory analyses were performed:

### Total Records

Calculated the total number of products available in the dataset.

### Sample Data Inspection

Reviewed sample records to understand the structure and contents of the dataset.

### Missing Value Analysis

Checked important columns for null or missing values.

### Product Category Analysis

Identified all unique product categories.

### Stock Availability Analysis

Compared products that are currently in stock versus out of stock.

### Duplicate Product Detection

Identified products appearing multiple times under different SKUs.

---


---

## Business Questions Solved

### 1. Top 10 Best-Value Products

Identified products offering the highest discount percentages.

### 2. High-Value Out-of-Stock Products

Found premium products that are currently unavailable and may result in lost sales opportunities.

### 3. Estimated Revenue by Category

Calculated potential revenue using:

Revenue = Discounted Selling Price × Available Quantity

### 4. Premium Products with Low Discounts

Identified products with:

* MRP greater than ₹500
* Discount less than 10%

### 5. Categories with Highest Average Discounts

Ranked categories based on average discount percentage.

### 6. Best Value Products by Price per Gram

Calculated price efficiency for products weighing at least 100 grams.

### 7. Product Weight Segmentation

Grouped products into:

* Low Weight (<1000g)
* Medium Weight (1000g–4999g)
* Bulk Products (≥5000g)

### 8. Total Inventory Weight by Category

Measured inventory volume available across product categories.

---


## Key Insights

After analyzing the dataset, several meaningful insights were discovered:

* Certain product categories consistently offered higher discounts than others.
* Premium products that were out of stock represented potential revenue loss.
* A small number of categories contributed a significant portion of total inventory value.
* Bulk products generally provided better value when measured using price per gram.
* Several high-priced products had very low discounts despite premium positioning.
* Inventory weight was concentrated in a limited number of categories, indicating inventory imbalance.

---

## Business Impact

This analysis can help:

### Inventory Management Teams

* Monitor stock shortages.
* Improve replenishment planning.

### Pricing Teams

* Evaluate discount effectiveness.
* Optimize pricing strategies.

### Category Managers

* Identify high-performing categories.
* Improve product assortment decisions.

### Revenue Teams

* Estimate potential category-level revenue.
* Identify revenue leakage due to stock-outs.

### Operations Teams

* Track inventory distribution across categories.

---


---

## Author

**Mohd Adnan Amir**


### Connect With Me

* LinkedIn: www.linkedin.com/in/mohdadnanamir


If you have suggestions or feedback regarding this project, feel free to connect.
