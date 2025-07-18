# 📊 BikeGear Solutions Sales Optimization Case Study

## Project Summary

This case study explores how data-driven analysis using **Microsoft Excel** was used to help **BikeGear Solutions**, a global retailer of bike accessories, unlock insights across regions, age demographics, and product categories. The analysis supported smarter marketing, inventory planning, and customer engagement strategies.

As a **Business Analyst**, I performed a comprehensive analysis on historical sales data, delivering actionable insights and an interactive dashboard that aligns with strategic business needs.

---

## 🧰 Tools & Technologies
- Microsoft Excel (Pivot Tables, Slicers, Charts, IFs, SUMIFs, Formulas)
- Data Cleaning & Structuring
- Descriptive Analytics
- Dashboard Design & Visual Reporting

---

## 🧩 Dataset Overview

The dataset covered sales transactions with the following attributes:

- **Demographics**: `Customer_Age`, `Customer_Gender`
- **Geography**: `Country`, `State`
- **Product Info**: `Product_Category`, `Sub_Category`, `Product`
- **Sales Metrics**: `Order_Quantity`, `Unit_Cost`, `Unit_Price`, `Revenue`, `Profit`, `Cost`
- **Time Dimensions**: `Date`, `Month`, `Year`

---

## 🧭 Project Workflow

| Step | Activity |
|------|----------|
| ✅ Step 1 | Data Collection & Cleaning |
| ✅ Step 2 | Exploratory Data Analysis (EDA) |
| ✅ Step 3 | Data Modelling & Segmentation |
| ✅ Step 4 | Dashboard Design & Visualization |
| ✅ Step 5 | Recommendations & Insights Presentation |

---

## 🔧 Data Processing Breakdown

### 🧹 Data Cleaning

To ensure accurate analysis, I performed the following data cleaning steps in Excel:

- **Removed blanks and duplicates** in key columns (e.g., Product, Revenue, Country)
- **Standardized text cases** using `PROPER()`, `UPPER()`, and `TRIM()` functions
- **Handled missing values** using default placeholders or calculated averages where necessary
- **Converted date formats** using `TEXT()`, `DATEVALUE()`, and ensured correct mapping to Year, Month, and Day columns
- **Verified numeric data types** for cost, profit, and revenue calculations

### 🧩 Data Modelling & Structuring

- **Segmented Age Groups**:  
  Used Excel formula logic to group ages into:
  - `< 25` → Youth  
  - `25–35` → Young Adult  
  - `> 35` → Adult

- **Calculated KPIs**:
  - Revenue: `=Order_Quantity * Unit_Price`
  - Cost: `=Order_Quantity * Unit_Cost`
  - Profit: `=Revenue - Cost`

- **Created helper columns** for time analysis (e.g., Month Name, Year, Quarter) to enable trend analysis over time

- **Categorized Products** by subcategory for detailed sales breakdown

- **Structured data** into clean tables to enable dynamic pivoting and dashboard use

### 📊 Data Visualization & Dashboard Creation

Built a fully interactive Excel dashboard that includes:

- **Pivot Charts** for revenue, profit, and order quantity by:
  - Region (Country, State)
  - Age Group and Gender
  - Product Category and Sub-Category
  - Monthly/Seasonal Trends

- **Slicers & Timelines** to allow end users to filter and explore the data dynamically

- **KPI Summary Cards** for:
  - Total Revenue
  - Total Profit
  - Total Units Sold
  - Top Age Group and Region

- **Color-coded insights** to highlight top-performing categories and low-yield areas

---

## 📈 Business Questions Answered

- **Which regions generate the most revenue?**
- **Which age groups and gender are the top buyers?**
- **What product subcategories perform best in terms of profit and volume?**
- **What are the seasonal trends in sales volume and profit?**

---

## 📌 Key Performance Indicators (KPIs)

- Total Revenue
- Total Profit
- Total Order Quantity
- Top 3 Regions by Profit
- Top Age Group by Revenue
- Best-Selling Product Sub-Category

---

## 📊 Dashboard

Explore the **interactive Excel dashboard** used to uncover trends and segment data:

📎 [Download Dashboard Excel File](./BikeGear_Solutions_sales_data.xlsx)

---

## 💡 Key Insights & Recommendations

### 📍 Insights

- 🇺🇸 **United States** was the most profitable market, followed by Canada.
- 🧑‍💼 **Adults (36+)** accounted for the highest revenue share.
- 🚴 **Bike Racks** and **Protective Gear** were the most popular and profitable subcategories.
- 📆 Sales **peaked during Spring and Summer months**, aligning with the cycling season.

### ✅ Recommendations

1. **Regional Marketing Focus**  
   Prioritise marketing campaigns in the U.S. and Canada while exploring ways to grow underperforming regions like Australia.

2. **Demographic Targeting**  
   Tailor marketing messages for the "Adult" segment (36+), with gender-specific promotions where applicable.

3. **Product Strategy**  
   Increase stock levels and marketing for high-performing subcategories like Bike Racks. Consider phasing out low-performing ones.

4. **Seasonal Planning**  
   Boost inventory before Q2 and Q3 to align with peak seasonal demand. Plan promotions in advance for spring launches.

---

## 🧠 Learning Outcomes

- Gained practical Excel experience in real-world sales analysis
- Strengthened skills in data storytelling and KPI visualization
- Applied business analysis methods to support marketing and inventory strategy

---
