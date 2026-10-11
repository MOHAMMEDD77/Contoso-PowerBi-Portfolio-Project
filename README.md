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
  * `dim_product` & `product_name` (Product hierarchies and attributes)
  * `dim_store` (Store details and metrics)
  * `dim_date` & `prevouse_date` (Time-intelligence tables)
* **Relationships:** Enforced proper one-to-many (`1:*`) relationships with correct filter propagation directions to ensure accurate aggregations.

---

## 📈 Key Features & Report Pages
The Power BI report is structured into multiple dedicated analytical views:
1. **Sales & Revenue Report:** High-level executive overview tracking Revenue, COGS, and Margin with Year-over-Year (YoY) variance[cite: 5].
2. **Margin Report:** Detailed profitability breakdown across product categories, gender, and geographic continents[cite: 4].
3. **KPI Calculations:** Advanced measures including YTD, QTD, 3-Month Rolling Averages, and PY comparisons[cite: 9].
4. **Ranking & Contribution:** ABC/XYZ and Contributory ranking metrics measuring product and brand share[cite: 8].
5. **Customer Lifespan & Retention:** Cohort and lifecycle tracking analysing new vs. loyal customer contribution over time[cite: 7].
6. **Quarterly Revenue Distribution:** Multi-year breakdown highlighting quarterly performance shifts[cite: 6].

---

## 💡 Advanced DAX & Calculations
Examples of complex measures implemented in this solution:
* **Time Intelligence:** Dynamic previous year and moving averages.
* **Ranking & Window Functions:** Utilizing advanced DAX/SQL patterns for running totals and ranking dynamics[cite: 10].
* **Matrix Visual Formatting:** Dynamic measure switching and conditional formatting layers.

---

## 📸 Report Preview
| Sales Overview | Margin Breakdown |
| :---: | :---: |
| ![Sales Report](sales_report.jpg) | ![Margin Report](margin_report.jpg) |

| Data Model Schema | Customer Lifespan |
| :---: | :---: |
| ![Data Model](data_model.jpg) | ![Customer Lifespan](customer_lifespan.jpg) |

---

## 🛠️ Tools & Technologies
* **Power BI Desktop:** Data modeling, Power Query transformations, and interactive UI design.
* **DAX:** Custom measure creation and performance optimization.
* **Git & GitHub:** Version control and professional portfolio presentation.
