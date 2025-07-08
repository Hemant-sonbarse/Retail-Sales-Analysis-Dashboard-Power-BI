# 📊 Retail Sales Analysis Dashboard – Power BI

This Power BI project presents an interactive retail sales dashboard using fictional data from a company called **Electro Hub**. The goal is to analyze sales, profit, quantity sold, and promotional impacts across different time periods and customer segments.

---

## 🎯 Key Features

✅ KPI Cards: Total Sales, Total Profit, Quantity Sold  
✅ Top/Bottom Product Performance by Sales, Profit, and Quantity  
✅ Category & Segment Filtering via Slicers  
✅ Dual Date Range Comparison using DAX + Edit Interactions  
✅ Promotion-wise Discount and Profitability Insights  
✅ Detailed Order-Level Table with Dynamic Filters across Products, Customers, Promotions, and Dates  

---

## 🧠 Skills Highlighted

- **Data Modeling** (Star Schema: Fact & Dimension Tables, 1:M Relationships)  
- **DAX Measures** (`CALCULATE`, `USERELATIONSHIP`, `SUM`, `FILTER`, etc.)  
- **Custom Date Table** and Time Intelligence  
- **Slicers & Edit Interactions** for advanced filtering logic  
- **Interactive Visuals**: KPI Cards, Bar/Column Charts, Tables, and Slicers  
- **Power BI Formatting & UX Design** best practices  

---

## 📌 Requirements Implemented

1. **Overview Page** – Show key KPIs (Sales, Profit, Quantity)
2. **Top/Bottom Analysis** – Products by Sales, Profit, and Quantity
3. **Segment-wise Analysis** – Category, Subcategory, and Segment filters
4. **Date Range Comparison** – Compare KPIs across two custom date ranges
5. **Promotion-wise Insights** – Analyze discounts, profit, and performance
6. **Order-Level Detail Page** – Display all order info with slicers from dimensions
7. **Dynamic Filtering** – All slicers interact cleanly with the fact table

---

## 📁 Folder Structure

| Folder              | Description                                          |
|---------------------|------------------------------------------------------|
| `Data/`             | Raw data files (`.xlsx`, `.csv`) used in the model  |
| `PBIX_Files/`       | Final Power BI dashboard file                        |
| `DAX_Measures/`     | Custom DAX measures used across visuals              |
| `Screenshots/`      | Visual previews of report pages                      |
| `Final_Report/`     | Summary report (PDF) — optional                      |
| `README.md`         | Project documentation (this file)                   |
| `.gitignore`        | System file exclusions (if needed)                  |

---

## 🧠 DAX Measures Used

- `TotalSales_Measure`
- `ProfitComparison`
- `NetSales_By_Promotion`
- `Sales_Quantity_BetweenDates`

> All DAX measures are provided in the `DAX_Measures/` folder for reuse.
