# 💹 Retail Sales & Profit Analysis
## 📌 Overview
This analysis explores sales performance, customer behaviour, product profitability, and regional and channel trends for a retail business over the period from 1 January 2025 to 15 May 2026. Using transaction-level sales data, the project evaluates how revenue and profit are distributed across products, months, customers, regions, and sales channels to uncover what drives profitability and where losses occur.

## 🎯 Objective
The objective of this analysis is to evaluate overall sales performance, product profitability, customer behaviour, and regional and channel trends in order to identify the key drivers of revenue and profit, understand the impact of discounts on margins, and highlight opportunities to improve pricing, retention, and business performance.

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
Excel (Initial data preview and quick validation of rows & columns distributions)  
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
<img width="651" height="289" alt="Revenue   Profit by Category" src="https://github.com/user-attachments/assets/387a9eba-bd26-4070-bd99-1626c31b5127" />    

Revenue & Profit by Category shows how each product category contributes to business performance. Clothing was the best-performing category, contributing 46% ($136,291) of total revenue and 47% ($46,515) of total profit.

image
Average Volume Traded by Year shows that KO’s trading activity increased substantially over time, rising from 1,371,885.71 in 1962 to 16,810,583.01. The peak in 2008 at 25,264,216.60 suggests unusually strong market participation during that year.

Screenshot 2026-05-25 095000
Average Close Price by Year highlights KO’s remarkable long-term price growth, rising from 0.04 in 1962 to a peak of 60.86 in 2022. This steady increase reflects the stock’s enduring strength and long-term value expansion.

💡 Key Insights
Over the 60 years analysed, KO demonstrated exceptional long-term resilience and value creation. The stock rose from 0.04 to 60.86, representing a growth of about 152,050%, while maintaining an average daily volatility of just 1.74%. This combination of strong appreciation and relatively modest volatility suggests a stock that has delivered substantial returns without excessive instability.

KO also demonstrated consistently strong market participation. About 140 billion shares were traded over the period. The stock closed above its open on roughly 48% of trading days, and monthly volume remained highly stable, varying by only about ±5%.

In practical terms, these metrics suggest that KO has enjoyed broad global acceptance, likely supported by the enduring strength of its beverage brands and its reputation as a stable, highly liquid stock. The consistency in volume, modest volatility, and strong long-term appreciation all indicate a stock that has been attractive to both short-term traders and long-term investors. See Insights Here

📂 Repository Layout
📈 analysis charts – Final analysis visuals (PNG)
🗄️ dataset – Raw dataset and cleaned CSV files
📋 group tables – Pandas aggregated tables in CSV files
⚙️ process charts – Technical work steps visual (PNG)
📖 README.md – Project overview
🔎 Analysis Findings – All metrics and findings from the analysis
💡 insights.md – All insights from analysis
