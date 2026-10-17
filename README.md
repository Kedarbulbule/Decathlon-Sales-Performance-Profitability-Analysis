
# 🏆 Decathlon Sales Performance & Profitability Analysis

An interactive Business Intelligence Dashboard built in **Microsoft Excel** to analyze Decathlon's sales, profitability, store performance, and customer behavior using Power Query, Power Pivot, Pivot Tables, Pivot Charts, and dynamic Slicers.

---

## 📌 Project Overview

This project transforms raw retail transaction data into an interactive dashboard that enables business users to monitor key performance indicators, analyze sales trends, evaluate store performance, and understand customer purchasing behavior.

The dashboard is divided into three analytical modules:

- Executive Business Overview
- Store & Sales Performance
- Customer & Sales Analysis

---

# 🎯 Business Objective

The objective of this project is to provide management with a centralized dashboard that helps answer questions such as:

- How is the business performing overall?
- Which stores generate the highest revenue and profit?
- Which product categories perform best?
- Which promotions drive sales?
- How do customers behave across different segments?
- Which payment methods and sales channels are most preferred?

---

# 📊 Dataset

**Source:**

https://www.kaggle.com/datasets/anushka29/decathalon-data

# 🏗️ Star Schema Data Model

To improve reporting performance and simplify analysis, the dataset was transformed into a **Star Schema** using Power Pivot.

The model consists of one central fact table connected to multiple dimension tables through one-to-many relationships.

### Fact Table

**Fact_Sales**

Stores transactional sales data including:

- Order ID
- Date Key
- Customer ID
- Product ID
- Store ID
- Salesperson ID
- Promotion ID
- Quantity
- Sales Amount
- Profit
- Sales Channel
- Payment Method
- Customer Rating
- Return Information

---

### Dimension Tables

#### 📅 Dim_Date

Contains calendar information.

- Date
- Day
- Month
- Quarter
- Year
- YearMonth

---

#### 👤 Dim_Customer

Contains customer attributes.

- Customer Name
- Gender
- Age
- Age Group
- City
- State
- Membership Type
- Customer Segment

---

#### 🛍️ Dim_Product

Contains product information.

- Product Name
- Product Category
- Brand
- Sport Type

---

#### 🏬 Dim_Store

Contains store details.

- Store Name

---

#### 🎯 Dim_Promotion

Contains promotion campaigns.

- Promotion Campaign

---

#### 👨‍💼 Dim_Salesperson

Contains salesperson information.

- Salesperson Name

---

## Model Relationships

- Dim_Date → Fact_Sales
- Dim_Customer → Fact_Sales
- Dim_Product → Fact_Sales
- Dim_Store → Fact_Sales
- Dim_Promotion → Fact_Sales
- Dim_Salesperson → Fact_Sales

All relationships follow a **One-to-Many (1:*)** relationship, where each dimension table filters the central Fact_Sales table.

This schema improves:

- Query Performance
- Data Consistency
- Scalability
- Easy Slice & Dice Analysis
- Faster Pivot Table Calculations

---

### Data Model Preview

> 

![Star Schema](I<img width="2760" height="1214" alt="Screenshot 2026-07-31 141734" src="https://github.com/user-attachments/assets/f72d6ee3-5fd2-4ca2-a954-0827e025ce01" />
)

---

# 🛠 Tools & Technologies

- Microsoft Excel
- Power Query
- Power Pivot
- Pivot Tables
- Pivot Charts

---

# 📈 Dashboard 1 — Executive Business Overview

Provides a high-level summary of business performance.

### KPIs

- Total Revenue
- Total Profit
- Total Orders
- Quantity Sold
- Average Order Value
- Average Customer Rating

### Visualizations

- Monthly Revenue Trend
- Revenue by Promotion
- Revenue Share by Sales Channel
- Profit by Product Category
- Revenue by Product Category
- Revenue Distribution by State

### Key Insights

- Total Revenue reached **₹36.71 Cr**.
- Total Profit recorded **₹11.27 Cr**.
- Around **30,000 orders** were processed.
- Nearly **90.83K units** were sold.
- **Cycling** generated the highest revenue.
- **Cycling** also contributed the highest profit.
- Revenue is distributed almost equally across **Store**, **Website**, and **Mobile App** sales channels.
- Maharashtra generated the highest revenue among all states.
- Winter Sports Fest generated the highest promotional revenue.

---

# 🏪 Dashboard 2 — Store & Sales Performance

Analyzes operational performance across stores and salespersons.

### KPIs

- Revenue
- Profit
- Orders
- Quantity Sold
- Average Order Value
- Customer Rating

### Visualizations

- Revenue by Store
- Profit by Store
- Revenue by Salesperson
- Revenue by Time Slot
- Order Share by Time Slot
- Revenue Share by Payment Method

### Key Insights

- Decathlon Mumbai generated the highest revenue.
- Decathlon Mumbai also recorded the highest profit.
- Karan Sharma was the top-performing salesperson by revenue.
- Afternoon generated the highest revenue.
- Afternoon also contributed the largest share of orders.
- Revenue is fairly balanced across all payment methods.

---

# 👥 Dashboard 3 — Customer & Sales Analysis

Provides customer segmentation and behavioral insights.

### Visualizations

- Average Customer Rating by Delivery Speed
- Revenue by Membership Type
- Return Reasons
- Revenue Share by Gender
- Revenue Share by Age Group
- Order Share by Customer Segment

### Key Insights

- Basic Membership customers generated the highest revenue.
- Adult customers contributed nearly **69%** of revenue.
- Revenue contribution from Male and Female customers is almost equal.
- Returning customers account for the largest share of orders.
- Wrong Item Delivered is the most common return reason.
- Customer ratings remain consistent across delivery speeds.

---

# 💡 Business Recommendations

- Increase inventory for Cycling products to meet demand.
- Replicate operational strategies from the Mumbai store across other locations.
- Schedule staffing during Afternoon hours to handle peak demand.
- Expand the Basic Membership program to encourage upgrades.
- Improve logistics and quality control to reduce Wrong Item Delivered returns.
- Continue investing in high-performing promotions such as Winter Sports Fest.
- Encourage customers to shift toward premium memberships through loyalty campaigns.

---

# 📁 Repository Structure

```
Decathlon-Sales-Performance-Profitability-Analysis
│
├── Dashboard.xlsx
├── Report
├── README.md

```

---

# 📷 Dashboard Preview

### Executive Business Overview

*(<img width="2798" height="1060" alt="Screenshot 2026-08-03 210341" src="https://github.com/user-attachments/assets/88bfa5bf-deaf-421b-9ab1-e35d07a8a1b5" />)*

### Store & Sales Performance

*(<img width="2794" height="1030" alt="Screenshot 2026-08-03 211959" src="https://github.com/user-attachments/assets/8a6a9ac7-a86b-4de1-9a4a-6f5a88cc346f" />
)*

### Customer & Sales Analysis

*(<img width="2792" height="1054" alt="Screenshot 2026-08-03 212233" src="https://github.com/user-attachments/assets/84f483a0-7dee-49d6-bea3-08cd43d996e9" />)*

---

# 📚 Skills Demonstrated

- Business Intelligence
- Data Cleaning
- Data Modeling
- ETL
- Dashboard Design
- KPI Development
- Data Visualization
- Power Query
- Power Pivot
- Pivot Tables
- Pivot Charts
- Business Storytelling

---

# ⭐ Project Highlights

✔ Interactive Dashboard

✔ Dynamic Slicers

✔ Drill-down Analysis

✔ Executive KPI Dashboard

✔ Store Performance Analysis

✔ Customer Insights

✔ Revenue & Profit Analysis

✔ Promotion Analysis

✔ Geographic Analysis

---

# 📬 Connect With Me

### LinkedIn

www.linkedin.com/in/kedar-bulbule




---

## ⭐ If you found this project useful, consider giving this repository a Star.
