# Contoso-PowerBi-Portfolio-Project
Advanced Power Sales &amp; Customer Analytics Using a Galaxy Schema And Dax Time Intellegence

# 📊 Contoso Sales & Business Intelligence Portfolio Project

An enterprise-level end-to-end Business Intelligence solution built using **Power BI**, featuring advanced **DAX modeling**, complex calculations, and a robust star schema data architecture based on the Contoso dataset.

---

## 🚀 Project Overview
This project delivers comprehensive sales, margin, and customer analytics designed to empower executive decision-making. It tracks key performance indicators (KPIs) over time, evaluates customer lifetime value (CLV), and analyzes regional and categorical performance drivers.

---

## 🏗️ Data Architecture & Modeling
* **Star & Galaxy Schema Design:** The data model is optimized for analytical performance, featuring a central fact table (`fact_sales`) connected to clean, conformed dimension tables:
  * `dim_customer` (Customer demographics, geography, and lifecycle segmentation)
  * `dim_product` (Product hierarchies and attributes)
  * `dim_store` (Store details and metrics)
  * `dim_date` (Time-intelligence tables)
* **Relationships:** Enforced proper one-to-many (`1:*`) relationships with correct filter propagation directions to ensure accurate aggregations.

---

## 📈 Key Features & Report Pages
1. **Sales & Revenue Report:** High-level executive overview tracking Revenue, COGS, and Margin with Year-over-Year (YoY) variance.
2. **Margin Report:** Detailed profitability breakdown across product categories, gender, and geographic continents.
3. **Detail Report:** Granular breakdown tables with interactive filters by Country, Brand, and Top N products.
4. **KPI & Window Functions:** Advanced time-intelligence calculations, YTD/QTD, 3-month rolling averages, and window rankings.
5. **Customer Lifespan & Retention:** Cohort and lifecycle tracking analyzing new vs. loyal customer contribution over time.

---

## 💡 Advanced DAX & Calculations
* **Time Intelligence:** Dynamic previous year and moving averages.
* **Ranking & Window Functions:** Utilizing advanced DAX patterns for running totals, rank, and contribution percentages.
* **Matrix Visual Formatting:** Dynamic measure switching and conditional formatting layers.

---

## 📸 Report Previews & Visuals

### 1. Sales & Margin Dashboards
**Sales Overview Report:**
![Sales Report](https://github.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/blob/main/ScreenShot/sales_report.jpg.png)

**Margin Breakdown Report:**
![Margin Report](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8Fmargin_report.jpg)

### 2. Data Model & Customers
**Data Model Schema:**
![Data Model](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8Fdata_model.jpg)

**Customer Lifespan & Retention:**
![Customer Lifespan](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8Fcustomer_lifespan.jpg)

### 3. Advanced Analytics & Tables
**Detail Report:**
![Detail Report](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8Fdetail_report.jpg)

**Window RT Report:**
![Window RT Report](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8Fwindow_rt_report.jpg)

**Advanced DAX Matrix Calculation:**
![Advanced DAX](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8Fadvanced_dax_matrix_calculation.jpg)

**Advanced Time Intelligence Matrix:**
![Advanced Time Intelligence](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8Fadvanced_time_intelligence_matrix.png)

**Pareto Analytics:**
![Pareto Analytics](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8FPareto_Analytics.jpg)

**Yearly & Quarterly Report:**
![Yearly Quarterly Report](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8Fyearly_quartly_report.jpg)

**Previous 6 Months Trend:**
![Prev 6 Months Trend](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8Fprev_6months_trend.jpg)

**Previous 6 Months Over Selection:**
![Prev 6 Months Selection](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8Fprev_6months_over_selection.jpg)

**Window Trolling 6M:**
![Window Trolling](https://raw.githubusercontent.com/MOHAMMEDD77/Contoso-PowerBi-Portfolio-Project/refs/heads/main/%E2%80%8F%E2%80%8Fwindow_trolling_6M.JPG)

---

## 🛠️ Tools & Technologies
* **Power BI Desktop:** Data modeling, Power Query transformations, and interactive UI design.
* **DAX:** Custom measure creation and performance optimization.
* **Git & GitHub:** Version control and professional portfolio presentation.
