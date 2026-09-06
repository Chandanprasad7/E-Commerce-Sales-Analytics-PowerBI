## 🧮 Key DAX Measures

Some of the important DAX measures used in this project include:

```DAX
Total Revenue =
SUM('sales_customer'[net_sales])
```

```DAX
Total Profit =
SUM('sales_customer'[profit])
```

```DAX
Total Orders =
DISTINCTCOUNT('sales_customer'[order_id])
```

```DAX
Total Customers =
DISTINCTCOUNT('sales_customer'[customer_id])
```

```DAX
AOV =
DIVIDE(
    [Total Revenue],
    [Total Orders]
)
```

```DAX
Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Revenue]
)
```

```DAX
Return Rate % =
DIVIDE(
    [Returned Orders],
    [Total Orders]
)
```

```DAX
Cancellation Rate % =
DIVIDE(
    [Cancelled Orders],
    [Total Orders]
)
```

```DAX
YoY Growth % =
DIVIDE(
    [Total Revenue] - [Previous Year Revenue],
    [Previous Year Revenue]
)
```

---

## 📊 Dashboard Preview

### 1. Executive Overview

![Executive Overview](01-executive-overview.png)

### 2. Product Analysis

![Product Analysis](02-product-analysis.png)

### 3. Customer Analysis

![Customer Analysis](03-customer-analysis.png)

### 4. Sales & Profit Analysis

![Sales Profit Analysis](04-sales-profit-analysis.png)

### 5. Delivery, Returns & Customer Experience

![Delivery Returns Analysis](05-delivery-returns-analysis.png)

### 6. Marketing & Payment Analysis

![Marketing Payment Analysis](06-marketing-payment-analysis.png)

---

## 🗂 Data Model

The project uses a relational Power BI data model connecting sales transactions, customers, products, order items, and a dedicated Date table.

The model enables analysis across sales, profitability, customer behavior, product performance, marketing, delivery, and returns.

![Power BI Data Model](data-model.png)

---

## 💡 Key Business Insights

- Analyzed more than **138K orders** and approximately **25K customers**.
- Generated approximately **177M in revenue** and **76M in profit**.
- Overall profit margin is approximately **43%**.
- Organic Search generated the highest revenue among marketing channels.
- Credit Card generated the highest revenue among payment methods.
- Repeat customers represent the majority of the customer base.
- Product category, customer segment, region, marketing channel, payment method, delivery performance, and returns can be analyzed using interactive filters.
- The dashboard covers business performance across **2021–2025**.

---

## 📁 Repository Contents

- `01-executive-overview.png`
- `02-product-analysis.png`
- `03-customer-analysis.png`
- `04-sales-profit-analysis.png`
- `05-delivery-returns-analysis.png`
- `06-marketing-payment-analysis.png`
- `data-model.png`
- `E-Commerce-Sales-Dashboard.pbix`
- `README.md`

---

## 🎯 Project Objective

The objective of this project is to demonstrate practical skills in:

- Power BI
- DAX
- Power Query
- Data Modeling
- Data Visualization
- KPI Reporting
- Business Analysis
- Customer Analysis
- Product Analysis
- Sales & Profitability Analysis
- Marketing Analysis

---

## 👤 Author

**Chandan Prasad**

GitHub: [Chandanprasad7](https://github.com/Chandanprasad7)
