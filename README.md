# FUTURE_DS_01 – Business Sales Performance Analytics

## Future Interns – Data Science & Analytics Internship | Task 1

### 📊 Project Overview

This project was completed as part of the Future Interns Data Science & Analytics Internship.

The objective of Task 1 was to analyze business sales data and identify revenue trends, top-selling products, high-value categories, and regional sales performance.

The analysis was designed to simulate a real-world business analytics scenario where data is transformed into meaningful insights that can support business decision-making.

---

## 🎯 Objectives

The main objectives of this project were to:

- Analyze overall business sales and profitability
- Identify monthly sales performance and trends
- Determine the highest-performing product categories
- Analyze sales performance across regions
- Identify the top-selling products
- Calculate and monitor key business KPIs
- Build an interactive Power BI dashboard
- Generate actionable business insights and recommendations

---

## 🛠️ Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Visual Studio Code**
- **Pandas**
- **Power BI**
- **GitHub**

---

## 📁 Dataset

The project uses the **Superstore Sales Dataset**, containing business transaction information such as:

- Order Date
- Product Name
- Category
- Region
- Customer Segment
- Sales
- Profit
- Quantity
- Discount

The dataset was prepared and analyzed before being visualized in Power BI.

---

## 🔍 Data Preparation & Analysis

The data preparation and exploratory analysis included:

- Loading the sales dataset into Python
- Reviewing the dataset structure using `df.info()`
- Checking for missing values
- Reviewing sales, profit, and order metrics
- Preparing the dataset for visualization
- Creating business performance KPIs
- Building interactive Power BI visualizations

---

## 📈 Key Performance Indicators

The dashboard includes the following KPIs:

| KPI | Result |
|---|---:|
| Total Sales | $2,30M |
| Total Profit | $286,40K |
| Total Orders | 5,009 |
| Average Order Value | $458,61 |
| Profit Margin | 12,5% |

---

## 📊 Dashboard Features

The Power BI dashboard contains:

### Monthly Sales Performance
A monthly view of sales performance used to identify stronger and weaker sales periods.

### Sales by Category
Comparison of sales performance across:

- Technology
- Furniture
- Office Supplies

### Profit by Category
Comparison of profitability across the three major product categories.

### Sales Contribution by Region
Analysis of sales contribution from:

- West
- East
- Central
- South

### Top 10 Products by Sales
Identification of the products contributing the highest sales values.

### Interactive Filters
The dashboard includes filters for:

- Year
- Region
- Category
- Customer Segment

These filters allow users to explore the data interactively.

---

## 💡 Key Findings

### Category Performance

Technology generated the highest sales at approximately **$836K**, followed by Furniture at approximately **$742K** and Office Supplies at approximately **$719K**.

Technology was also the most profitable category, generating approximately **$145K** in profit.

### Regional Performance

The **West region** generated the largest share of sales at approximately **31,56%**, followed by the **East region at 29,55%**.

The Central region contributed approximately **21,82%**, while the South region contributed approximately **17,05%**.

### Profitability

The business generated approximately **$286.40K in total profit** from approximately **$2,30M in sales**, resulting in an overall profit margin of approximately **12,5%**.

### Product Performance

The Top 10 Products analysis identifies the products contributing the highest individual sales values and provides a basis for prioritizing high-performing products.

---

## 💼 Business Recommendations

Based on the analysis, the following recommendations can be considered:

1. **Prioritize Technology**
   
   Technology is the strongest-performing category in both sales and profit. The business should continue supporting this category through inventory availability, marketing, and product expansion.

2. **Investigate Furniture Profitability**
   
   Furniture generates strong sales but significantly lower profit than Technology and Office Supplies. The business should investigate pricing, discounts, product costs, and margins within this category.

3. **Strengthen Regional Performance**
   
   The West and East regions generate the largest shares of sales. Successful strategies from these regions could be evaluated and adapted for lower-performing regions.

4. **Develop the South Region**
   
   The South region contributes the smallest share of sales. Further analysis could identify opportunities to improve product availability, marketing, customer targeting, or regional sales strategies.

5. **Focus on High-Performing Products**
   
   High-performing products should be monitored closely to maintain stock availability and identify opportunities for cross-selling or promotional strategies.

6. **Monitor Profitability Alongside Sales**
   
   Sales volume should not be the only performance measure. Management should monitor profit margins by product, category, and region to ensure revenue growth translates into sustainable profitability.

---

## 📌 Dashboard

The final Power BI dashboard provides an interactive overview of business sales performance and allows users to filter results by year, region, category, and customer segment.

---

## 📂 Project Structure

```text
FUTURE_DS_01/
│
├── README.md
│
├── data/
│   └── superstore_sales.csv
│
├── notebooks/
│   └── sales_analysis.ipynb
│
├── dashboard/
│   └── Task_1_Sales_Performance.pbix
│
├── report/
│   └── Key_Insights_and_Recommendations.pdf
│
└── images/
    └── dashboard.png
