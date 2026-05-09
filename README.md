# Retail Sales Performance Analysis (Power BI)

## 📊 Project Overview
This Power BI dashboard provides a strategic analysis of a $7.08M retail operation. The goal was to transform raw sales, product, and return data into actionable business insights regarding profitability and operational efficiency.

## 📷 Dashboard Preview
![Executive Summary](02-Sales_Overview.png)

## 🛠️ Step-by-Step Transformation
Using Power BI and DAX, I followed these steps to build a reliable analysis:

1. **Data Modeling:** I imported raw CSV and Excel files, creating relationships between sales, products, and geography to build a solid data foundation.
2. **Data Cleaning:** I audited the datasets to ensure currency consistency and handled missing values in the regional categories.
3. **KPI Logic (DAX):** I wrote custom DAX measures to calculate:
   * **Profit Margin %:** To see which products were actually making money after costs.
   * **Return Rate Analysis:** To pinpoint "problem products" that were being returned too often.
   * **Year-over-Year (YoY) Growth:** To compare current performance against previous periods.
4. **Interactive Design:** I built an Executive Summary view that allows management to filter by region or product category to see instant results.

## 💡 What the Data Told Me
* **Profit vs. Volume:** Some high-selling products had surprisingly low margins due to high return rates.
* **Regional Performance:** Identified specific geographic zones where sales were high, but shipping costs and returns were significantly hurting the net profit.
* **Actionable Insight:** Recommended a review of the return policy for the "Electronics" category, which showed the highest rate of revenue loss.
