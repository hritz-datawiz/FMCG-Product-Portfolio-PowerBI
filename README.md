Global Superstore – Power BI Analytics Project
📌 Project Overview

This project presents an end-to-end business intelligence analysis of the Global Superstore dataset using Microsoft Power BI. The objective is to analyze sales, profit, margin drivers, discount impact, and category performance and translate raw transactional data into actionable business insights.

The project is structured across three analytical report pages, each answering a distinct business question:

Overall business performance and geography

Sales & profitability deep dive

Margin change driver analysis

This repository is intended as a portfolio project demonstrating data modeling, DAX, and storytelling skills in Power BI.

🗂 Dataset Information

Dataset: Global Superstore (Kaggle)

Time Period: FY2010–2015

Grain: Order line level

Key Dimensions:

Order Date (Fiscal Year & Quarter)

Category / Sub-category / Product

Country & Region

Customer

Key Measures:

Sales

Profit

Profit Margin

Discount

Shipping Cost

🛠 Tools & Skills Used

Power BI Desktop

Power Query – Data cleaning & transformations

Data Modeling – Star schema

DAX – Time intelligence, ranking, cumulative metrics

Data Visualization & Storytelling

📊 Report Pages Breakdown
1️⃣ Global Business Overview
🎯 Objective

To understand overall business performance, profitability trends over time, and geographical distribution of sales & profit.

🔑 Key KPIs

Total Sales: 13M

Total Products: 3,711

Total Profit: 1.47M

Overall Profit Margin: 11.61%

Shipping Cost per Sale: 10.70%

📈 Visuals & Insights

Quarterly Sales & Profit Margin Trend

Identifies seasonality and margin fluctuations across fiscal years.

Category-wise Performance Table

Furniture shows lowest margin (6.94%), while Technology leads (~14%).

Geographical Distribution (Map Visual)

Bubble size represents sales, color indicates profitability.

Highlights high-revenue but low-margin regions.

📌 Business Insight: Revenue growth does not always translate to higher margins, especially in Furniture.

2️⃣ GSD – Sales & Profitability Analysis
🎯 Objective

To deep dive into subcategory performance, identify profit leaks, and evaluate discount-driven sales.

🔑 KPIs

Total Orders: 51K

Average Order Value (AOV): 246.5

Sales from Discounted Orders: 372K

Discount Margin Impact: 126.34%

% SKUs with Negative Margin: 18.19%

📊 Key Visuals
🔹 Pareto – Top Subcategories by Sales

Demonstrates the 80/20 rule where a few subcategories drive majority of sales.

Used running total % DAX to calculate contribution.

🔹 Negative Margin Subcategories

Ranks subcategories with negative profit margins.

Helps identify where discounts, shipping, or pricing erode profitability.

🔹 BCG Matrix (Sales vs Profit Margin)

X-axis: Total Sales

Y-axis: Profit Margin

Bubble size: Sales contribution

Quadrant Interpretation:

⭐ Stars: High sales, high margin (ideal)

🐄 Cash Cows: High sales, low growth

❓ Question Marks: Low sales, high margin

🐶 Dogs: Low sales, low margin

📌 Business Insight: Some high-sales subcategories fall below average margin, signaling pricing or cost issues.

3️⃣ GSD – Margin Change Driver Analysis
🎯 Objective

To explain why margins changed between two selected quarters using a Waterfall analysis.

🧮 Methodology

User selects Start Quarter and End Quarter

Margin change is decomposed into business drivers:

Furniture Impact

Office Supplies Impact

Technology Impact

Discount Impact

Shipping Impact

Customer Mix Effect

📉 Waterfall Chart

Start Margin → Individual Driver Impacts → Final Margin

Clearly distinguishes positive vs negative contributors.

📌 Business Insight:

Technology positively drives margin

Furniture and Shipping often dilute margin

Customer mix plays a critical balancing role

🧠 Key Learnings

High sales ≠ High profitability

Discounts can significantly distort margin if not controlled

Technology category is the strongest margin contributor

Furniture requires cost & pricing optimization

Driver-based analysis is critical for leadership decision-making

🚀 How to Use This Report

Open the .pbix file in Power BI Desktop

Use slicers (Year, Quarter, Category) to interact with visuals

Navigate pages.

Happy Using !
