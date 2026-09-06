# 🛒 E-Commerce Sales Analytics Dashboard

## 📌 Project Overview

This project is an interactive **E-Commerce Sales Analytics Dashboard** developed using **Microsoft Power BI**.

The dashboard analyzes **138K+ orders, 25K customers, and 177M in revenue** from **January 2021 to December 2025**.

The objective of this project is to transform raw e-commerce data into meaningful business insights related to sales performance, profitability, products, customers, marketing, payments, delivery performance, and returns.

---

## 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Cleaning & Transformation
- Excel / CSV
- Data Visualization

---

## 📊 Dashboard Pages

The project contains **6 interactive dashboard pages**:

1. Executive Overview
2. Product Analysis
3. Customer Analysis
4. Sales & Profit Analysis
5. Delivery, Returns & Customer Experience
6. Marketing & Payment Analysis

---

# 1️⃣ Executive Overview

Provides a high-level overview of overall e-commerce business performance.

### Key KPIs

- Total Revenue: **177M**
- Total Orders: **138K**
- Total Profit: **76M**
- Total Customers: **25K**
- Average Order Value: **1.28K**
- Profit Margin: **43.0%**

### Analysis

- Revenue trend by year
- Revenue by sales channel
- Profit by region
- Orders by status
- Country, year, region, customer segment and marketing channel filters

![Executive Overview](01-executive-overview.png)

---

# 2️⃣ Product Analysis

Analyzes product, category and brand performance.

### Analysis

- Top 10 products by revenue
- Revenue by product category
- Profit by category
- Revenue contribution by category
- Revenue by brand
- Product revenue vs profit analysis

![Product Analysis](02-product-analysis.png)

---

# 3️⃣ Customer Analysis

Provides insights into customer demographics, customer value and purchasing behavior.

### Key KPIs

- Total Customers: **25K**
- Repeat Customers: **24K**
- Average Customer Lifetime Value: **8.97K**
- Revenue per Customer: **7.11K**
- New Customers in Last 2 Years: **787**

### Analysis

- Top 10 customers by revenue
- Customers by age group
- Revenue by customer segment
- Revenue by gender
- Customers by country
- New vs repeat customers

![Customer Analysis](03-customer-analysis.png)

---

# 4️⃣ Sales & Profit Analysis

Analyzes revenue, gross sales, discounts, profitability and year-over-year performance.

### Key KPIs

- Gross Sales: **190M**
- Total Revenue: **177M**
- Total Discount: **33M**
- Total Profit: **76M**
- Profit Margin: **43.0%**
- Latest YoY Growth: **-1.1%**

### Analysis

- Revenue and profit trend by month
- Gross sales vs revenue by month
- Year-over-year revenue growth

![Sales & Profit Analysis](04-sales-profit-analysis.png)

---

# 5️⃣ Delivery, Returns & Customer Experience

Analyzes operational performance and customer experience.

### Key KPIs

- Cancellation Rate: **6.1%**
- Average Delivery Days: **4.56**
- Average Customer Rating: **3.68**
- Returned Orders: **9K**
- Return Rate: **6.9%**

### Analysis

- Orders by delivery status
- Average delivery days by shipping method
- Returned orders by return reason
- Return rate by product category
- Orders by customer rating
- Orders by review sentiment
- Average delivery days by warehouse

![Delivery Returns Analysis](05-delivery-returns-analysis.png)

---

# 6️⃣ Marketing & Payment Analysis

Analyzes marketing channel effectiveness, campaign performance, payment preferences and coupon usage.

### Analysis

- Revenue by marketing channel
- Orders by marketing channel
- Revenue by campaign
- Orders by payment method
- Revenue by payment method
- Coupon vs non-coupon orders

### Key Findings

- **Organic Search** generated the highest marketing-channel revenue at approximately **36M**.
- **Credit Card** was the leading payment method, generating approximately **53M** in revenue.
- Approximately **80% of orders were non-coupon orders**.
- Default Campaign generated approximately **29M** among assigned campaign values.

![Marketing & Payment Analysis](06-marketing-payment-analysis.png)

---

## 🧮 Key DAX Measures

### Total Revenue

```DAX
Total Revenue =
SUM('sales_customer'[net_sales])

## 📊 Dashboard Preview

### 1. Executive Overview
![Executive Overview](01-executive-overview.png)

### 2. Product Analysis
![Product Analysis](02-product-analysis.png)

### 3. Customer Analysis
![Customer Analysis](03-customer-analysis.png)

### 4. Sales & Profit Analysis
![Sales & Profit Analysis](04-sales-profit-analysis.png)

### 5. Delivery, Returns & Customer Experience
![Delivery Returns Analysis](05-delivery-returns-analysis.png)

### 6. Marketing & Payment Analysis
![Marketing Payment Analysis](06-marketing-payment-analysis.png)

---

## 🗂 Data Model

The project uses a relational Power BI data model connecting sales transactions, customers, products, order items, and a dedicated Date table.

![Power BI Data Model](data-model.png)

## 📈 Key DAX Measures

- Total Revenue
- Total Profit
- Gross Sales
- Average Order Value
- Profit Margin %
- YoY Growth %
- Return Rate %
- Cancellation Rate %
- Average Customer Lifetime Value
- Revenue per Customer
- Repeat Customers

## 💡 Key Business Insights

- The dashboard analyzes more than 138K orders and approximately 25K customers.
- Total revenue is approximately 177M with profit of approximately 76M.
- Organic Search generated the highest marketing-channel revenue.
- Credit Card was the highest-performing payment method by revenue.
- Repeat customers represent a major share of the customer base.
- Product, customer, marketing, delivery, return, and profitability performance can be analyzed using interactive filters.

