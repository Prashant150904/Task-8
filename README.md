# Simple Sales Dashboard

## 📌 Overview
A Power BI dashboard analyzing sales performance by product, region, and month using the `Superstore_Sales.csv` dataset. Built for **Task 8** to demonstrate data cleaning, visualization, and actionable insights.

---

## 🛠️ Tools & Technologies
- **Power BI**: Dashboard creation and visualization.

## 📋 Steps to Build the Dashboard

### 1. Data Import & Cleaning
- Import `Superstore_Sales.csv` via **Get Data > Text/CSV**.
- Convert `Order Date` to "Month-Year":
  - In Power Query:  
    `Month-Year = FORMAT([Order Date], "MMM-YYYY")`.

### 2. Visualizations
- **Line Chart**:  
  - *Axis*: `Month-Year` (sorted chronologically).  
  - *Values*: Sum of `Sales`.  
- **Bar Chart (Sales by Region)**:  
  - *Axis*: `Region`.  
  - *Values*: Sum of `Sales`.  
  - **Color Gradient**: Darker shades for higher sales   
- **Donut Chart (Sales by Category)**:  
  - *Legend*: `Category`.  
  - *Values*: Sum of `Sales`.  
- **Slicer**: Added for `Region` to filter visuals dynamically.

### 3. Dashboard Design
- **Layout**:  
  - Line chart at the top.  
  - Bar and donut charts side-by-side below.  
  - Slicer on the right.  
- **Color Scheme**:  
  - Blue for sales metrics.  
  - Contrasting colors for categories.  

---






