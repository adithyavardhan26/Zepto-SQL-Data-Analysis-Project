# 🛒 Zepto Retail Data Analysis (SQL Project)

## 📌 Overview
This project focuses on **retail data analysis** using SQL.  
The dataset represents product details from Zepto (an online grocery delivery platform), including product category, pricing, discounts, stock status, and weight.  

The goal is to **explore, clean, and analyze** the data to generate actionable business insights such as revenue estimates, inventory categorization, and identifying best-value products.

---

## 📂 Project Workflow

### 1. Database Schema
- Created a `zepto` table with fields like `sku_id`, `category`, `name`, `mrp`, `discountPercent`, `discountedSellingPrice`, `availableQuantity`, `weightInGms`, and `outOfStock`.

### 2. Data Exploration
- Count of rows and null value detection.
- Listing unique product categories.
- Checking duplicate product names.
- Products in stock vs. out of stock.

### 3. Data Cleaning
- Removed invalid records (`mrp = 0` or `discountedSellingPrice = 0`).
- Standardized currency by converting values from **paise to rupees**.
- Verified cleaned dataset before analysis.

### 4. Data Analysis (Key Insights)
- **Top 10 Best-Value Products** → based on highest discount percentage.  
- **High MRP Out-of-Stock Products** → identifies potential lost sales opportunities.  
- **Estimated Revenue by Category** → calculated using selling price × available quantity.  
- **Products with High MRP & Low Discounts** → finds premium products.  
- **Top 5 Categories by Avg. Discount** → highlights customer attraction strategies.  
- **Price per Gram Analysis** → best value products by weight.  
- **Weight Categorization (Low, Medium, Bulk)** → helps in inventory classification.  
- **Total Inventory Weight per Category** → insights for logistics & supply chain.

---
