# Superstore Sales Analysis – Power BI

## 📌 About This Project
This is my **first Power BI project**.

In this project, I analyzed Superstore sales data to understand **sales, profit, trends, regions, and product performance**.

I initially explored the data in **Excel**, but while working with **SQL**, I discovered several data quality issues such as **blank spaces, incorrect data types, and formatting problems** that were not clearly visible in Excel.

To fix this, I used **staging tables in SQL** to load the raw data, clean it step by step, and then created a final clean table.  
The cleaned data was then exported as a **CSV file** and loaded into Power BI for analysis and visualization.

---

## 🛠 Tools Used
- Excel (initial exploration and understanding of data)
- SQL (data cleaning using staging tables)
- Power BI Desktop
- DAX (for calculations like sales, profit, margin, and YoY growth)

---

## 📊 Dashboard Pages

### 1️⃣ Executive Dashboard
This page shows the **overall business performance**:
- Total Sales
- Total Profit
- Total Quantity
- Profit Margin
- Sales trend over time
- Year-over-Year (YoY) growth
- Sales contribution by customer segment

Slicers used:
- Region
- Date

---

### 2️⃣ Map Analysis
This page focuses on **geographic performance**:
- Sales distribution across U.S. states using a map
- Bubble size represents sales
- Sales by region
- Top states by sales

Slicers used:
- Region
- Date  
(All visuals respond to slicer selections.)

---

### 3️⃣ Product Detail Analysis
This page helps analyze **product-level performance**:
- Product-wise sales and profit
- Category and sub-category comparison
- Conditional formatting to highlight profit and loss
- Filters to analyze specific products

---

## ✨ Key Things I Implemented
- Explored data in **Excel** and identified limitations of formatting-only cleaning
- Used **SQL staging tables** to clean and prepare raw data
- Created a final clean table from the staging table
- Loaded clean data into Power BI using CSV
- Created a **separate Measures table** for DAX measures
- Used **Card visuals** instead of KPI visuals for better slicer behavior
- Applied **measure-level formatting** for consistency
- Used **Region and Date slicers across all pages**, including the map
- Verified filter interactions across visuals

---

## 📚 What I Learned From This Project
- Difference between data formatting in Excel and data cleaning in SQL
- Why staging tables are important for clean data
- How SQL and Power BI work together in a workflow
- How slicers affect visuals across pages
- How to design dashboards that answer business questions

---

## 🔮 Next Steps
- Build a second Power BI project with advanced features like tooltips
- Create an end-to-end project using a direct SQL connection
- Continue improving data cleaning and modeling skills

---

## 📂 Files in This Repository
- `Superstore_Sales_Analysis.pbix` – Power BI report file
- `screenshots/` – Dashboard screenshots
