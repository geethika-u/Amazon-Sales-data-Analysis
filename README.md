# Amazon-Sales-data-Analysis
Amazon sales data analysis using Power BI

# citation: https://www.kaggle.com/datasets/litonislam/amazon-sales-analysis-cleaned-data/data

# Amazon Sales Performance Analysis & Customer Insights Dashboard (Power BI)

---

## ✅ TASK 1: Sales & Profitability Analysis Dashboard

### 🎯 Objective
Analyze overall business performance, sales trends, discount impact, and profitability.

---

### 🔎 Key Business Questions

1. What is the total revenue and total profit?
2. Which product categories generate the most profit?
3. How do discounts impact revenue and profit?
4. What are the monthly sales trends?

---

### 📊 Recommended Visualizations

#### 🔹 KPI Cards
- Total Revenue  
- Total Profit  
- Profit Margin  
- Total Orders (Distinct `order_id`)  

---

#### 🔹 Sales Trend (Line Chart)
- **Axis** → Month-Year  
- **Values** → Total Revenue & Total Profit  

---

#### 🔹 Category Performance (Clustered Column Chart)
- **Axis** → `product_category`  
- **Values** → Total Revenue & Total Profit  

---

#### 🔹 Discount Impact (Scatter Plot)
- **X-axis** → `discount_percent`  
- **Y-axis** → `profit`  
- **Size** → `quantity_sold`  
- **Legend** → `product_category`  

**Insight Goal:** Identify if higher discounts reduce profit margin.

---

#### 🔹 Payment Method Distribution (Donut Chart)
- **Legend** → `payment_method`  
- **Values** → Total Revenue  

---

### 📈 Expected Insights

- High discounts may increase revenue but reduce profit margin.
- Some categories generate high revenue but low profit.
- Certain regions may show higher average ratings.
- Payment method trends may correlate with region.

---

## ✅ TASK 2: Customer & Product Performance Analysis

### 🎯 Objective
Analyze customer behavior, ratings, and product performance to improve business strategy.

---

### 🔎 Key Business Questions

1. Which products have the highest ratings?
2. Do higher-rated products generate more revenue?
3. Which categories receive the most reviews?
4. What is the relationship between reviews and profit?

---

### 📊 Recommended Visualizations

#### 🔹 Rating vs Revenue (Scatter Plot)
- **X-axis** → `rating`  
- **Y-axis** → `total_revenue`  
- **Size** → `review_count`  
- **Legend** → `product_category`  

**Goal:** See if better-rated products drive higher sales.

---

#### 🔹 Top 10 Products (Bar Chart)
- **Axis** → `product_id`  
- **Values** → Total Revenue  
- **Filter** → Top 10 by revenue  

---

#### 🔹 Review Distribution (Column Chart)
- **Axis** → `product_category`  
- **Values** → Total Reviews  

---

#### 🔹 Regional Rating Analysis (Matrix)
- **Rows** → `customer_region`  
- **Columns** → `product_category`  
- **Values** → Average Rating  

---

#### 🔹 Profit by Rating (Line or Area Chart)
- **Axis** → `rating`  
- **Values** → Total Profit  

