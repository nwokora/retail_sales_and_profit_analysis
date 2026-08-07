# 💹 Retail Sales & Profit Analysis
## 📌 Overview
This analysis explores sales performance, customer behaviour, product profitability, and regional and channel trends for a retail business from 1 January 2025 to 15 May 2026. Using transaction-level sales data, the project evaluates how revenue and profit are distributed across products, months, customers, regions, and sales channels to uncover the drivers of profitability and where losses occur.

## 🎯 Objective
The objective of this analysis is to evaluate overall sales performance, product profitability, customer behaviour, and regional and channel trends to identify the key drivers of revenue and profit, understand the impact of discounts on margins, and highlight opportunities to improve pricing, retention, and overall business performance.

## 📊 Analysis Questions
1. Revenue & Profit by Region  
2. Revenue & Profit by Category  
3. Products by Revenue & Profit  
4. Product-based & Transaction-based Gain & Loss
5. Top 3 Products by Quantity Sold
6. Monthly Revenue & Profit Trends
7. Online vs In-Store Revenue Performance
8. Impact of Discount on Profit
9. Customer Loyalty Rating

## 🛠️ Tools Used
Excel (Initial data preview and quick validation of row and column distributions)  
Excel (Data cleaning and preparation)  
Excel (Analysis visualization)

🔗 Data Source
Coca-Cola Stock Dataset (1962–2022) by Kalilur Rahman (Kaggle). Dataset Source

## 🧹 Data Cleaning and Preparation 
- Imported the dataset into Excel, ensuring all column headers were correctly placed in 
row one.  
- Converted the raw data range into an Excel table to enable structured references, easier 
filtering, and consistent validation.  
- Reviewed and standardized data types: formatted Unit_Price, Gross_Revenue, 
Discount_Amount, Net_Revenue, Cost_per_Unit, Total_Cost, and Profit as numbers 
formatting, and formatted Discount_Pct and Profit_Margin_Pct as percentages 
formatting.  
- Checked for missing values using filters across key columns and confirmed that no values 
were missing.  
- Checked for duplicate records using Order_ID with conditional formatting and confirmed 
that there were no duplicate orders.  
- Extracted Day, Month, and Year from the original Date column to support time-based 
analysis and trend reporting.  
- Sorted Product Name within each Category to make product-level analysis and validation 
easier.  
- Calculated overall summary metrics, including total Gross Revenue, total Net Revenue, 
and total Profit, to validate that the dataset aligns with expected business totals.  
- Gains and Losses columns were calculated to show how much of the business’s sales 
generated profit and how much resulted in losses.

## 📉 Analysis  
- **Revenue & Profit by Region** examines how sales and profitability are distributed across different regions. It helps identify which regions generate the most revenue and which convert sales into profit most efficiently
- **Revenue & Profit by Category** shows how much revenue and profit each product category contributes. It helps reveal which categories are the main drivers of performance and which ones contribute less to overall business results.
- **Products by Revenue & Profit** compares individual products based on how much revenue and profit they generate. It helps identify the best-performing products and shows that high sales volume does not always mean high profit.
- **Product-based & Transaction-based Gain & Loss** examines which products and individual transactions were profitable or loss-making. It shows the extent to which sales generated gain or loss, helping reveal margin weakness, pricing issues, or discount effects at both the product and transaction levels.
- **Top 3 Products by Quantity Sold** identifies the products with the highest sales volume. It helps show which items are most popular with customers and whether high volume also translates into strong revenue and profit.
- **Monthly Revenue & Profit Trends** tracks how sales and profit change over time from month to month. It helps reveal seasonality, peak performance periods, and months where profitability strengthens or weakens.
- **Online vs In-Store Revenue Performance** compares how revenue is generated across the two sales channels. It helps show which channel contributes more to sales and whether one channel performs better than the other in terms of revenue generation.
- **Impact of Discount on Profit** measures how different discount levels affect profitability. It helps show whether higher discounts improve sales enough to justify lower margins, or whether they reduce profit overall.
- **Customer Loyalty Rating** measures how frequently customers return to make repeat purchases. It helps classify customers by loyalty level and shows whether the business is mainly attracting one-time buyers or building long-term customer relationships.


## 🔭 Visualizations  
<img width="585" height="288" alt="Revenue   Profit by Category" src="https://github.com/user-attachments/assets/7163325a-8d29-41df-a22e-769438ed01b6" />
 
**Revenue & Profit by Category** shows how each product category contributes to business performance. Clothing was the best-performing category, contributing 46% ($136,291) of total revenue and 47% ($46,515) of total profit.

<img width="674" height="429" alt="Monthly Revenue   Profit Trends" src="https://github.com/user-attachments/assets/11a133a4-e5a3-40c9-a053-3a79602c89d6" />

**Monthly Revenue & Profit Trends** show how sales and profitability change from month to month, highlighting seasonality and peak performance periods. The analysis found that May 2025 recorded the highest revenue, October 2025 delivered the highest profit, and January was the strongest month overall in both revenue and profit for the year 2026.

<img width="649" height="277" alt="Impact of Discount on Profit" src="https://github.com/user-attachments/assets/78ab87a5-4ada-4bcd-b53b-3eed74c1bd99" />

**Impact of Discount on Profit** shows how different discount levels affect profitability. The analysis found that deeper discounts reduced margins sharply, with 15% and 20% discounts performing worst, while 10% was the only discount level to show a positive average profit margin.

<img width="874" height="235" alt="Product-based   Transaction-based Gain   Loss" src="https://github.com/user-attachments/assets/71729b97-8011-41ab-9c40-560f672e5358" />

**Product-based & Transaction-based Gain & Loss** shows the proportion of sales that generated profit compared with those that resulted in losses. The analysis found that 68% of sales were made at a gain, while 32% were made at a loss, indicating that the business is profitable overall but still has a significant share of loss-making transactions.

## 💡 Key Insights  
- **Strong but uneven profitability**: The business generated $294,348 in revenue and $99,064 in profit, with Clothing emerging as a key contributor, partly because it has the largest number of products in its category. However, performance varied by month, product, discount level, and region.

- **Growth and margin opportunities**: Over 60% of customers were one-time buyers, while deeper discounts and online sales weakened margins, highlighting opportunities to improve retention, pricing, discount control, and channel profitability.  
  **[See Insights](https://github.com/nwokora/retail_sales_and_profit_analysis/blob/main/insights.md)**

## 📂 Repository Layout  
- **📈 analysis charts** – Final analysis visuals (PNG)  
- **🗄️ dataset** – Raw dataset and cleaned CSV files  
- **📋 group tables** – Pandas aggregated tables in CSV files  
- **⚙️ process charts** – Technical work steps visual (PNG)  
- **📖 README.md** – Project overview  
- **🔎 Analysis Findings** – All metrics and findings from the analysis  
- **💡 insights.md** – All insights from analysis  
