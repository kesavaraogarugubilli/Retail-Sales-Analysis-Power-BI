# 📊 Retail Sales & Profitability Analysis — Power BI

## 📌 Project Overview

This project presents an interactive **Retail Sales & Profitability Dashboard** built using **Microsoft Power BI** to analyze sales performance, profitability, customer behavior, product performance, regional trends, and sales channels.

The project uses a **25,000-record retail sales dataset** containing transactional information such as order dates, regions, cities, product categories, customer segments, sales channels, payment methods, quantities, sales, costs, discounts, and profits.

The primary objective of this project is to transform raw transactional data into a **business-focused analytical dashboard** that enables stakeholders to monitor KPIs, identify trends, compare performance, and make data-driven decisions.

---

## 🎯 Business Objectives

The dashboard was developed to answer key business questions such as:

- How are total sales and profit performing?
- Which regions and cities generate the highest revenue?
- Which product categories contribute the most to sales and profit?
- Which products are the most profitable?
- How do different customer segments perform?
- Which sales channel generates better results?
- How do sales and profit change over time?
- What impact do discounts have on profitability?
- Which areas of the business require improvement?

---

## 📁 Dataset

**Dataset:** Retail Sales Dataset  
**Records:** 25,000  
**Columns:** 15

### Dataset Columns

| Column | Description |
|---|---|
| 'Order_ID' | Unique order identifier |
| 'Order_Date' | Date of the transaction |
| 'Region' | Geographical region |
| 'City' | Customer/order city |
| 'Category' | Product category |
| 'Product' | Product name |
| 'Customer_Segment' | Customer classification |
| 'Sales_Channel' | Online or Offline sales |
| 'Payment_Method' | Payment method used |
| 'Quantity' | Number of units purchased |
| 'Unit_Price' | Price per unit |
| 'Discount' | Discount applied to the order |
| 'Sales' | Total sales/revenue |
| 'Cost' | Product/order cost |
| 'Profit' | Profit generated from the transaction |

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Cleaning & Transformation**
- **Data Visualization**
- **Business Intelligence**

---

## 🔄 Project Workflow

### 1️⃣ Data Collection

Imported the retail sales CSV dataset containing **25,000 transactional records** into Power BI.

### 2️⃣ Data Cleaning & Transformation

Performed data preparation using **Power Query**, including:

- Checking data types
- Checking for missing/null values
- Checking duplicate records
- Validating numerical columns
- Converting 'Order_Date' into the appropriate date format
- Preparing fields for analysis
- Ensuring consistency across categorical fields

### 3️⃣ Data Modeling

Structured the dataset to support efficient reporting and analysis.

Created appropriate analytical structures and relationships where required.

### 4️⃣ DAX Measures

Created DAX measures to calculate important business KPIs such as:

- Total Sales
- Total Profit
- Total Cost
- Total Quantity
- Total Orders
- Average Order Value
- Profit Margin

---

## 📊 DAX Measures

The following DAX measures were created to calculate the key business KPIs.

### Total Sales

Total Sales = SUM(Retail_Sales[Sales])


### Total Profit

Total Profit = SUM(Retail_Sales[Profit])


### Total Cost

Total Cost = SUM(Retail_Sales[Cost])


### Total Quantity

Total Quantity = SUM(Retail_Sales[Quantity])


### Total Orders

Total Orders = DISTINCTCOUNT(Retail_Sales[Order_ID])


### Profit Margin

Profit Margin =
DIVIDE([Total Profit], [Total Sales], 0)

### Average Order Value

Average Order Value =
DIVIDE([Total Sales], [Total Orders], 0)


---

## 📊 Dashboard Features

The Power BI dashboard provides an interactive overview of retail performance through multiple analytical sections.

### 🔹 KPI Cards

Key performance indicators include:

- 💰 Total Sales
- 📈 Total Profit
- 📦 Total Orders
- 🛒 Total Quantity
- 💹 Profit Margin
- 🧾 Average Order Value
- 📦 YoY Growth
- 

### 🔹 Sales Trend Analysis

Analyzes sales and profit performance over time to identify:

- Growth trends
- Declining periods
- Seasonal patterns
- Revenue fluctuations
- Profitability trends

### 🔹 Regional Analysis

Compares performance across different regions and cities to identify:

- High-performing regions
- Underperforming regions
- Revenue distribution
- Regional profitability

### 🔹 Product & Category Analysis

Analyzes:

- Category-wise sales
- Category-wise profit
- Top-performing products
- Low-performing products
- Quantity sold
- Product profitability

### 🔹 Customer Segment Analysis

Compares different customer segments to understand their contribution to:

- Sales
- Profit
- Orders
- Overall business performance

### 🔹 Sales Channel Analysis

Evaluates **Online vs Offline** performance to determine which channel contributes more to overall business performance.

### 🔹 Payment Method Analysis

Examines the distribution of transactions across different payment methods.

### 🔹 Interactive Filters

Users can dynamically filter the dashboard based on:

- Date
- Region
- City
- Category
- Product
- Customer Segment
- Sales Channel
- Payment Method

---

## 💡 Key Business Insights

The dashboard enables identification of important business patterns, including:

- Revenue and profitability vary across geographical regions.
- Product categories contribute differently to overall sales and profit.
- Customer segments demonstrate different purchasing behaviors.
- Online and offline channels can be compared to evaluate channel effectiveness.
- High sales volume does not necessarily indicate high profitability.
- Discount levels can influence overall profit margins.
- Monitoring both revenue and profit provides a better understanding of business performance than revenue alone.
- Time-based analysis helps identify changes in sales and profitability trends.

---

## 📈 Skills Demonstrated

### Power BI

- Dashboard Development
- Interactive Reports
- KPI Design
- Drill-down Analysis
- Slicers & Filters
- Data Visualization

### DAX

- Aggregations
- 'SUM'
- 'DIVIDE'
- 'DISTINCTCOUNT'
- Calculated Measures
- Profitability Metrics

### Power Query

- Data Cleaning
- Data Transformation
- Data Type Management
- Data Validation

### Business Analytics

- Sales Analysis
- Profitability Analysis
- Customer Segmentation
- Regional Analysis
- Product Performance
- Channel Analysis
- KPI Monitoring

---

## 🖼️ Dashboard Preview

Screenshots of the Power BI dashboard below.

### Sales & Profit Analysis

<img width="1535" height="857" alt="Screenshot 2026-09-04 200525" src="https://github.com/user-attachments/assets/3d9e2cf5-5a89-4f03-9599-09720e21e3b0" />


### Product & Regional Analysis

![Product and Regional Analysis](<img width="1541" height="856" alt="Screenshot 2026-09-04 200619" src="https://github.com/user-attachments/assets/8522f9e1-9da9-45da-b5dc-5f83da8aff16" />



---

## 📂 Project Structure

Retail-Sales-Analysis-Power-BI/
│
├── Dataset/
│   └── PowerBI_Retail_Sales_25000.csv
│
├── Dashboard/
│   └── Retail_Sales_Dashboard.pbix
│
├── Screenshots/
│   ├── dashboard_overview.png
│   ├── sales_analysis.png
│   └── product_analysis.png
│
└── README.md

---

🚀 Project Outcome

This project demonstrates how raw transactional retail data can be transformed into an **interactive Business Intelligence solution** using Power BI.

The dashboard provides management with a centralized view of:

- Sales
- Profitability
- Customers
- Products
- Regions
- Sales Channels

This helps identify performance trends, understand business performance, and support data-driven decision-making.

---

## 👨‍💻 About the Project

This project was developed as part of my journey toward becoming a **Data Analyst**, with a focus on developing practical skills in:

- Power BI
- DAX
- Power Query
- Data Cleaning
- Data Modeling
- Data Visualization
- Business Analytics

The project emphasizes not only building visually appealing dashboards but also using data to answer meaningful **business questions and generate actionable insights**.

---

## ⭐ Future Improvements

Potential improvements for future versions include:

- Adding a dedicated Date/Calendar table
- Implementing advanced time-intelligence DAX
- Adding Year-over-Year analysis
- Adding Month-over-Month analysis
- Creating a dedicated profitability analysis page
- Adding sales forecasting
- Implementing drill-through pages
- Adding tooltip pages
- Improving mobile dashboard layout
- Publishing the report through Power BI Service
- Implementing Row-Level Security (RLS)

---

📌 Conclusion

The **Retail Sales & Profitability Analysis Dashboard** demonstrates an end-to-end Power BI workflow, starting from raw data preparation and transformation through DAX-based analysis and interactive dashboard development.

It showcases my ability to convert a large dataset into **clear, interactive, and business-oriented insights** using modern data analytics and Business Intelligence techniques.

---

📜 License

This project is licensed under the **MIT License**.
