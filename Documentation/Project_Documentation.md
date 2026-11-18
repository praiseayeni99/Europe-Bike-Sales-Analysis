
# Europe Bike Sales Analysis – Project Documentation

##  Project Overview

This project involves analysing the Europe Bike Store Sales dataset to evaluate the company's financial performance, product sales, customer purchasing patterns, and geographical sales distribution.

Microsoft Excel was used for data cleaning and preparation, while Microsoft Power BI was used to develop an interactive dashboard, calculate key performance indicators (KPIs), and generate business insights.

The project focuses on transforming raw sales data into meaningful information that supports business decision-making and identifies opportunities to improve revenue and profitability.

##  Dataset Source

The dataset used for this project was obtained from Kaggle.

- **Dataset Name:** Europe Bike Store Sales
- **Source:** Kaggle
- **Dataset Provider:** PrepInsta Prime
- **Dataset Link:** [Europe Bike Store Sales – Kaggle](https://www.kaggle.com/datasets/prepinstaprime/europe-bike-store-sales)

The dataset contains bike sales transaction records, including customer demographics, product details, order quantities, revenue, cost, and profit.

##  Project Objectives

The main objectives of this analysis were to:

- Evaluate overall revenue and net profit performance.
- Analyse monthly revenue and net profit trends.
- Identify high-performing product categories and subcategories.
- Compare sales and profitability across countries.
- Examine customer purchasing patterns.
- Develop an interactive Power BI dashboard.
- Generate actionable business insights and recommendations.

##  Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning and preparation |
| Microsoft Power BI | Dashboard development and data visualisation |
| DAX | KPI calculations and financial performance measures |

##  Data Preparation (Microsoft Excel)

Microsoft Excel was used to clean and prepare the dataset before 
developing the Power BI dashboard.

The following data preparation steps were performed:

###  Duplicate Removal
- Checked the dataset for duplicate records.
- Removed duplicate records to improve data quality and avoid 
  potential duplication in the analysis.

### Age Group Classification
- Used the Excel IF function to create two additional columns:
  - **Age Category:** Classified customers into different age categories.
  - **Age Bracket:** Grouped customers into defined age brackets.
- This classification made it easier to analyse customer 
  demographics and purchasing patterns.

###  Final Dataset
After completing the data preparation steps, the cleaned dataset 
was ready for use in Power BI for further analysis and dashboard 
development.

## Revenue and Net Profit Analysis

Revenue and net profit were analysed in Power BI using measures to evaluate the financial performance of the business.

The analysis included:
- Total Revenue
- Total Net Profit
- Profit Margin (%)
- Monthly Net Profit (MoM)
- Net Profit Year-to-Date (YTD)
- Selected Reporting Period

These measures supported the dashboard KPIs, financial performance comparisons, and business insights.
### Time-Based Financial Performance Measures

The following DAX measures were created in Power BI to evaluate financial performance over time:

| Measure | Description |
|---|---|
| **Revenue YTD** | Calculates cumulative revenue from the beginning of the year up to the selected reporting period. |
| **Net Profit YTD** | Calculates cumulative net profit from the beginning of the year up to the selected reporting period. |
| **Revenue Growth MoM (%)** | Measures the percentage increase or decrease in revenue compared with the previous month. |
| **Profit Growth MoM (%)** | Measures the percentage increase or decrease in net profit compared with the previous month. |

### Additional Dashboard Measures

| Measure | Description |
|---|---|
| **Net Profit MoM** | Calculates the month-over-month change in net profit. |
| **Selected Reporting Period** | Dynamically displays the reporting period selected by the user. |

These measures support monthly performance comparisons, year-to-date reporting, and dynamic financial analysis within the Power BI dashboard.

## Product Performance Analysis

Product performance was analysed in Power BI to identify the product categories and subcategories generating the highest revenue and net profit.

### Product Category Performance

- **Bikes:** Generated the highest revenue of $61.78 million and net profit of $20.52 million.
- **Accessories:** Generated $15.12 million in revenue and $8.86 million in net profit.
- **Clothing:** Generated $8.37 million in revenue and $2.84 million in net profit.

### Product Subcategory Performance

- **Road Bikes:** Recorded the highest revenue of $33.36 million and net profit of $10.08 million.
- **Mountain Bikes:** Generated $21.12 million in revenue and $8.16 million in net profit.
- **Touring Bikes:** Generated $7.30 million in revenue.
- **Helmets:** Generated $5.74 million in revenue.

### Key Observation

Bikes were the leading product category in both revenue and net profit, with Road Bikes and Mountain Bikes making the largest contributions among the subcategories.


## Geographical Analysis

Geographical performance was analysed in Power BI to compare revenue and net profit across different countries.

### Revenue by Country

- **United States:** Generated $28.0 million in revenue.
- **Australia:** Generated $21.3 million in revenue.
- **United Kingdom:** Generated $10.6 million in revenue.

### Net Profit by Country

- **United States:** Recorded $11.1 million in net profit.
- **Australia:** Recorded $6.8 million in net profit.
- **United Kingdom:** Recorded $4.4 million in net profit.

### Key Observation

The United States recorded the highest revenue and net profit, followed by Australia and the United Kingdom among the countries highlighted.


## Business Insights and Recommendations

The analysis revealed several important findings about the business's revenue, net profit, product performance, and geographical performance.

### Key Business Insights

1. **Monthly Performance:** December recorded the highest revenue ($9.09 million) and net profit ($3.41 million), while August recorded the lowest revenue ($5.71 million).
2. **Product Performance:** Bikes contributed the highest revenue and net profit among the product categories.
3. **Subcategory Performance:** Road Bikes and Mountain Bikes were the leading subcategories in revenue and net profit.
4. **Geographical Performance:** The United States recorded the highest revenue ($28.0 million) and net profit ($11.1 million), followed by Australia.

### Business Recommendations

- **Monitor financial performance:** Track revenue, net profit, and profit margin together.
- **Investigate monthly trends:** Examine December's strong performance and weaker July–August results.
- **Prioritise leading products:** Maintain strong-performing Bikes, Road Bikes, and Mountain Bikes.
- **Improve profitability:** Compare product margins to guide pricing, costs, and inventory decisions.
- **Strengthen leading markets:** Investigate growth opportunities in the United States and Australia.
- **Support data-driven decisions:** Use consistent reporting periods and validated financial calculations.


## Conclusion

The Europe Bike Sales Analysis provided insights into the business's overall revenue, net profit, product performance, monthly sales trends, and geographical performance.

Using Microsoft Excel and Power BI, the dataset was prepared, analysed, and presented through interactive dashboards and financial performance measures.

The analysis highlighted the importance of monitoring financial performance, understanding product contributions, identifying monthly trends, and evaluating country-level performance to support informed business decisions.
