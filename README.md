# 📊 Power BI Project: Financial Performance Dashboard

## 🔍 Overview

This Power BI project analyzes a company's **financial performance** across multiple dimensions including **country, product category, time period**, and **segment**. It uses a rich dataset with key financial metrics such as **Sales**, **Profit**, **Cost of Goods Sold (COGS)**, and **Discounts** to deliver actionable insights.

---

## 🎯 Objectives

* Understand and track financial KPIs over time.
* Identify top-performing products, regions, and segments.
* Analyze profit margins and discount strategies.
* Provide stakeholders with an interactive, dynamic reporting tool.

---

## 🛠️ Tools & Technologies

* **Power BI** for data modeling, DAX measures, and interactive dashboard creation.
* **DAX** for custom measures (e.g., Total Sales, Profit Margin, Discount %, etc.).
* **Power Query** for data transformation and cleaning.
* **Excel** (as the data source).

---

## 📁 Dataset Columns

* `Segment`, `Country`, `Product`, `Discount Band`
* `Units Sold`, `Manufacturing Price`, `Sale Price`
* `Gross Sales`, `Discounts`, `Sales`, `COGS`, `Profit`
* `Date`, `Month Number`, `Month Name`, `Year`

---

## 📌 Key Features

* **Executive Summary Dashboard** with KPIs, trend lines, and filterable cards.
* **Product Performance Analysis** with bar charts and profit contribution.
* **Country & Regional Insights** using maps and regional drilldowns.
* **Discount & Profitability Page** highlighting discount strategies vs. net profit.

---

## 🧠 DAX Measures Used

* `Total Sales`
* `Total Profit`
* `Total COGS`
* `Total Discounts`
* `Profit Margin = DIVIDE([Total Profit], [Total Sales])`
* `Discount % = DIVIDE([Total Discounts], [Gross Sales])`
* `Top Country by Sales`
* `Sales Trend`, etc.

---

## 📸 Dashboard Screenshots

> Includes visual mock-ups and real screenshots for all 4 pages:

1. Executive Summary
2. Product Performance
3. Country & Regional Insights
4. Discount & Profitability Analysis

---

## 📈 Outcome

A highly interactive Power BI dashboard that enables stakeholders to **explore financial metrics**, **track trends**, and **make data-driven decisions** with ease.

---

## 📎 Project Files

* `.pbix` Power BI file
* Project presentation in `.pptx` and `.pdf`
* Dashboard images used in mock-ups and reports

---

## ✅ How to Run

1. Open the Power BI file (.pbix)
2. Load the Excel dataset (or use preloaded data)
3. Refresh the data and explore visuals
4. Use slicers to interact with products, countries, or time ranges
