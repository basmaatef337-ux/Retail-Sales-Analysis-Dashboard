
# 🛒 Retail Sales Dashboard | Power BI Project

## 📊 Project Overview

This project presents a **Retail Sales Analysis Dashboard** developed using **Power BI** to analyze customer purchasing behavior and sales performance.

The goal of this project is to demonstrate:

- Data cleaning and preparation
- Data modeling using Star Schema
- Building interactive dashboards
- Extracting business insights from sales data

The dashboard enables decision-makers to quickly understand sales trends, customer demographics, and product demand.

---

# 📁 Dataset Description

The dataset represents retail transactions and includes the following variables:

| Column | Description |
|------|-------------|
Customer ID | Unique identifier for each customer |
Age | Customer age |
Gender | Male / Female |
Product Category | Product classification |
Price per Unit | Price of a single item |
Quantity | Number of purchased items |
Total Amount | Total purchase value |
Date | Transaction date |

---

# 🧠 Business Questions

This analysis aims to answer several key business questions:

1️⃣ What is the overall sales performance?

2️⃣ How do sales change over time?

3️⃣ Which product categories attract the most customers?

4️⃣ Are there differences in purchasing behavior between genders?

5️⃣ What is the average quantity purchased per transaction?

---

# 🏗 Data Model

The data model follows a **Star Schema** design.

### Fact Table

**retail_sales_dataset**

Contains transactional data such as:

- Customer ID
- Date
- Quantity
- Price per Unit
- Total Amount
- Product Category
- Gender

### Dimension Tables

**Product Dimension**
- Product Category

**Gender Dimension**
- Gender

**Sales Dimension**
- Quantity
- Price per Unit
- Total Amount

This model improves query performance and analytical efficiency in Power BI.

📚 Reference  
Microsoft Power BI Documentation  
https://learn.microsoft.com/en-us/power-bi/

---

# 📊 Dashboard KPIs

The dashboard includes several key performance indicators:

| KPI | Value |
|----|------|
Total Customers | 1000 |
Total Sales | 456K |
Average Price | 179.89 |
Average Quantity | 2.51 |
Average Customer Age | 41.39 |

These metrics provide a quick overview of the retail business performance.

---

# 📈 Sales Trend Analysis

The monthly sales chart highlights fluctuations in retail sales performance.

Key observations:

- **Highest sales:** May (~53K)
- **Lowest sales:** September (~24K)
- Sales increase again towards the end of the year.

This pattern suggests **seasonal purchasing behavior**.

---

# 🛍 Product Category Analysis

Customer distribution across product categories:

| Category | Customers |
|--------|-----------|
Clothing | 351 |
Electronics | 342 |
Beauty | 307 |

Clothing appears to attract the largest number of customers.

---

# 👥 Gender Sales Analysis

Sales distribution by gender:

- Male: **51%**
- Female: **49%**

The results indicate that purchasing behavior is **balanced between genders**.

---

# 📊 Key Insights

✔ Retail sales show **seasonal variation across months**

✔ Clothing products attract the **largest customer segment**

✔ Male and female purchasing behavior is **nearly identical**

✔ Average customer buys **around 2–3 items per transaction**

---

# ⚙ Tools Used

- Power BI
- Data Modeling
- Data Visualization
- DAX


---

# 📷 Dashboard Preview

![Retail Dashboard](RetailSalesDashboard.png)

![Data Model](RetailSalesModel.png)

