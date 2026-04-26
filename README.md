# Amazon US Retail Operations & Profitability Analysis

<img width="1285" height="623" alt="Screenshot 2026-04-26 232942" src="https://github.com/user-attachments/assets/73e316b5-b97d-4682-a34a-898e8544e935" />

## 📌 Project Overview
This project examines the operational efficiency and financial health of a US-based retail giant. By analyzing over 5,000 orders across four years (2014-2017), I identified key growth opportunities, logistics bottlenecks, and the true cost of product returns.

## 🛠️ Technical Stack: Advanced Excel (Power Suite)
**Data Modeling (Power Pivot):** Built a Star Schema connecting four relational tables: Orders, Return, People and Shipping Cost.

**ETL & Data Transformation (Power Query):** Cleaned messy geographic data, standardized date formats, and merged shipping cost lookups into the main transaction table.

## 📈 Key Insights & KPIs
**Total Sales:** $2.29M | **Total Profit:** $286.4K

**Quantity Sold:** 37,873 units across **793 unique customers**.

**Regional Champion:** The West Region leads in both sales ($725K) and profitability.

**Product Performance:** **Technology (Phones & Accessories)** is the highest revenue generator, while **Office Supplies (Paper & Storage)** has the highest transaction frequency.

**Return Impact:** 296 orders were returned, with **Binders** and **Paper** seeing the highest return volume, indicating a need for better quality control or description accuracy in those categories.

## 📝 Technical Notes
**Date Handling:** To ensure financial accuracy, the KPIs in this dashboard align with the **Ship Date** as per the provided summary analysis. However, all time-of-day and seasonal growth insights utilize the **Order Date** to reflect when the customer transaction actually occurred.

## 💡 Strategic Recommendations
**Logistics Optimization:** Shipping costs in **Texas** and **Illinois** are significantly higher than the national average. Negotiating regional carrier contracts or utilizing local fulfillment centers could save an estimated 5-8% in operational costs.

**Return Reduction:** Investigate the high return volume in the "Standard Class" shipping mode, which accounts for the bulk of returned goods.

**Customer Retention:** Focus "Platinum" loyalty marketing on the top 10 customers (e.g., Christopher Conant, Sanjit Engle) who contribute a disproportionate amount of total annual revenue.
