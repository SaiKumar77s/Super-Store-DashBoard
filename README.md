
# Superstore-Sales-Dashboard
-- 📊 Interactive Sales Dashboard Using Power BI

---

## 🎯 Project Objective

The objective of this project is to build a fully interactive Sales Performance Dashboard using Power BI to analyze Superstore sales data.

This dashboard helps the business to:

- Monitor overall sales performance  
- Track profit and profit margin  
- Identify top-performing products  
- Analyze monthly sales trends  
- Support data-driven business decisions  

---

## 📂 Dataset Information

## Dataset Used
- <a href="https://github.com/SaiKumar77s/Super-Store-DashBoard/blob/main/Superstore.csv.csv">Superstore Dataset</a>

The dataset contains:

- Order Date  
- Customer Details  
- Product Category & Sub-Category  
- Sales  
- Quantity  
- Discount  
- Profit  
- Shipping Mode  

### Key Metrics Created:

- Total Sales  
- Total Profit  
- Total Quantity  
- Profit Margin %  

---

## ❓ Business Problem

Build an interactive dashboard to answer:

> How is the business performing in terms of sales, profit, and product performance?

---

## 🛠️ Project Workflow

### 1️⃣ Data Cleaning (Power Query)

- Checked for missing values  
- Converted Order Date to Date format  
- Created Year and Month columns  
- Verified numeric data types  

---

### 2️⃣ Data Modeling

- Single dataset model  
- Created calculated measures using DAX  
- Ensured proper aggregation logic  

---

### 3️⃣ DAX Measures Created


Total Sales = SUM('Sample - Superstore'[Sales])

Total Profit = SUM('Sample - Superstore'[Profit])

Total Quantity = SUM('Sample - Superstore'[Quantity])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
---

### 4️⃣ Dashboard Components

The dashboard includes:

KPI Cards (Sales, Profit, Quantity, Profit Margin)

Sales by Category (Bar Chart)

Monthly Sales Trend (Line Chart)

Top 10 Products by Sales

Interactive Filters (Year, Category)

## Key Insights

Technology category generates the highest sales and profit.

Sales increase significantly during year-end months.

A small number of products contribute to major revenue.

Higher discounts reduce overall profit margin.

### 📁 Project Structure

superstore-sales-dashboard/
│
├── data/
│ └── Sample - Superstore.csv
│
├── dashboard/
│ └── superstore_dashboard.pbix
│
├── images/
│ └── dashboard_screenshot.png
│
└── README.md

### ⚙️ Tools Used

Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

### 📈 Dashboard Features

Fully interactive visuals

Cross-filtering enabled

Dynamic slicers

Real-time KPI updates

Business insight text boxes

## DashBoard
<img width="1683" height="1464" alt="image" src="https://github.com/user-attachments/assets/def9de22-6569-4e5c-b12e-8f1c89238a39" />


### ✅ Final Conclusion

This interactive Power BI dashboard enables business stakeholders to:

Monitor key performance indicators

Identify profitable product categories

Detect seasonal sales patterns

Make strategic decisions based on data

This project demonstrates practical Business Intelligence skills using Power BI.

### 🔮 Future Improvements

Add customer segmentation analysis

Implement forecast visuals

Connect to live SQL database

Deploy to Power BI Service for sharing
