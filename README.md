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
7. Online vs In-store Revenue Performance
8. Impact of Discount on Profit
9. Customer Loyalty Rating

## 🛠️ Tools Used
Excel (Initial data preview and quick validation of rows & columns distributions)  
Excel (Data cleaning and preparation)  
Excel (Analysis visualization)

🔗 Data Source
Coca-Cola Stock Dataset (1962–2022) by Kalilur Rahman (Kaggle). Dataset Source

DATA CLEANING AND PREPARATION STEPS 
- Imported the dataset into Excel, ensuring all column headers were correctly placed in 
row 1.  
- Converted the raw data range into an Excel table to enable structured references, easier 
filtering, and consistent validation.  
- Reviewed and standardized data types: formatted Unit_Price, Gross_Revenue, 
Discount_Amount, Net_Revenue, Cost_per_Unit, Total_Cost, and Profit as numbers 
formatting, and formatted Discount_Pct and Profit_Margin_Pct as percentages 
formatting.  
- Checked for missing values using filters across key columns and confirmed that no values 
were missing.  
➢ Checked for duplicate records using Order_ID with conditional formatting and confirmed 
that there were no duplicate orders.  
➢ Extracted Day, Month, and Year from the original Date column to support time-based 
analysis and trend reporting.  
➢ Sorted Product Name within each Category to make product-level analysis and validation 
easier.  
➢ Calculated overall summary metrics, including total Gross Revenue, total Net Revenue, 
and total Profit, to validate that the dataset aligns with expected business totals.  
➢ Gains and Losses columns were calculated to show how much of the business’s sales 
generated profit and how much resulted in losses.

🧹 Data Cleaning and Preparation
Standardized column data types for consistency and analysis.
Checked for duplicates (none were found.)
Checked for missing values (none were found.)
Renamed Open, High, Low, and Close with a Price prefix for clarity.
Created key measures such as Average Close Price, Average Daily Volatility, Total Trading Days, and related metrics.
📉 Analysis
Volume of KO Traded – This analysis shows the total trading activity of KO over the selected period, helping to indicate overall market interest and liquidity. The result showed a total volume of 140 billion shares traded over 60 years.
Total Trading Days – This analysis shows the total trading days covered in the dataset, spanning ~15,000 trading days over the full period under review.
Close > Open (%) – This metric shows the percentage of trading days when the closing price was higher than the opening price, reflecting how often KO ended the day positively. KO closed higher than it opened on 48% of trading days.
Average Daily Volatility – This metric measures the average amount KO’s price moved each day. 1.74 Avg Daily Volatility shows a moderate and relatively stable stock over the period.
Average Volume by Year Analysis – This analysis examines how KO’s trading volume changed over 60 years, from 1962 to 2022. The average annual volume rose from 1,371,885.71 shares in 1962 to 16,810,583.01 shares in 2022. The highest average volume occurred in 2008, reaching 25,264,216.60 shares.
Average Volume by Month Analysis –This analysis examines how KO’s trading volume varies across the months of the year. The result shows monthly volumes are nearly even, with only about ±5% variation across all 12 months.
Average Close Price by Year – This analysis examines KO’s average closing price over time to highlight the stock’s growth trend across the study period. The price rose from 0.04 in 1962 to 60.86 in 2022, an increase of about 152,050%.
Average Closing Price by Quarter – This analysis examines KO’s average closing price across each quarter, helping to reveal short-term performance trends within the year.
Average Closing Price by Month – This analysis examines KO’s average closing price across each month, helping to identify recurring seasonal patterns and short-term price trends.
🔭 Visualizations
Screenshot 2026-05-26 093541
1962-2022 KO Market Performance Summary highlights KO’s long-term trading behaviour, liquidity, and price stability over the 60 years. The KPIs capture total trading volume, the number of trading days analyzed, the percentage of days the stock closed above its opening price, and the average daily volatility. Together, they provide a concise view of KO’s market activity and show how consistently the stock has performed over time.

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
