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
The Power BI report is structured into multiple dedicated analytical views:
1. **Sales & Revenue Report:** High-level executive overview tracking Revenue, COGS, and Margin with Year-over-Year (YoY) variance.
2. **Margin Report:** Detailed profitability breakdown across product categories, gender, and geographic continents.
3. **Detail Report:** Granular breakdown tables with interactive filters by Country, Brand, and Top N products.
4. **KPI & Window Functions:** Advanced time-intelligence calculations, YTD/QTD, 3-month rolling averages, and window rankings.
5. **Customer Lifespan & Retention:** Cohort and lifecycle tracking analyzing new vs. loyal customer contribution over time.

---

## 💡 Advanced DAX & Calculations
Examples of complex measures implemented in this solution:
* **Time Intelligence:** Dynamic previous year and moving averages.
* **Ranking & Window Functions:** Utilizing advanced DAX patterns for running totals, rank, and contribution percentages.
* **Matrix Visual Formatting:** Dynamic measure switching and conditional formatting layers.

---

## 📸 Report Preview & Galleries

### 1. Main Dashboards & Model
| Sales Overview | Margin Breakdown |
| :---: | :---: |
| ![Sales Report](sales_report.jpg) | ![Margin Report](margin_report.jpg) |

| Data Model Schema | Customer Lifespan |
| :---: | :---: |
| ![Data Model](data_model.jpg) | ![Customer Lifespan](customer_lifespan.jpg) |

### 2. Advanced Analytics & Tables
| Detail Report | Window RT Report |
| :---: | :---: |
| ![Detail Report](detail_report.jpg) | ![Window RT Report](window_rt_report.jpg) |

| Advanced DAX Matrix Calculation | Advanced Time Intelligence Matrix |
| :---: | :---: |
| ![Advanced DAX](advanced_dax_matrix_calculation.jpg) | ![Advanced Time Intelligence](advanced_time_intelligence_matrix.jpg) |

| Pareto Analytics | Yearly & Quarterly Report |
| :---: | :---: |
| ![Pareto Analytics](Pareto_Analytics.jpg) | ![Yearly Quarterly Report](yearly_quarterly_report.jpg) |

| Previous 6 Months Trend | Previous 6 Months Over Selection |
| :---: | :---: |
| ![Prev 6 Months Trend](prev_6months_trend.jpg) | ![Prev 6 Months Selection](prev_6months_over_selection.jpg) |

| Window Trolling 6M |
| :---: |
| ![Window Trolling](window_trolling_6M.jpg) |

---

## 🛠️ Tools & Technologies
* **Power BI Desktop:** Data modeling, Power Query transformations, and interactive UI design.
* **DAX:** Custom measure creation and performance optimization.
* **Git & GitHub:** Version control and professional portfolio presentation.
