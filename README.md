# US-Sales-Analytics-Dashboard

🛒 US Sales Analytics Dashboard (Power BI)
📌 Project Overview

This project presents a Power BI Sales Analytics Dashboard built on a retail dataset to analyze sales performance, customer behavior, product returns, and profitability.
The dashboard highlights KPIs, trends, customer segmentation, and regional insights, enabling decision-makers to identify growth opportunities and problem areas effectively.

👉 The dashboard consists of 5 interactive pages packed with visuals and actionable insights.

📊 Dataset Details

The dataset is composed of multiple relational tables:

Orders Table: Order ID, Date, Year, Ship Mode, Segment, Country, State, Region, Product ID, Sales, Quantity, Discount, Profit, Salesperson ID

Salesperson Table: Salesperson ID, Name

Sales Target Table: State, Year, Month, Target

Products Table: Category, Sub-Category, Product Name, Product ID

Customer Table: Customer ID, Customer Name

Return Table: Order ID, Returned

Region Heads Table: Person, Region

📈 Dashboard Pages & Features
🔹 Page 1 – Sales Overview

KPIs: Total Sales ($2.3M), Returned Sales, Net Sales ($2.12M), % Margin (12.5%)

Yearly Sales Trend (2018–2021)

Sales Growth % vs Previous Year across Regions, Segments, Categories

Target Achievement by State

Returned Products Analysis by Category & Region

🔹 Page 2 – What-If & Pareto Analysis

What-If Analysis: Predicted Profit based on user-defined Discount %

Comparison: Predicted vs Previous Profit by Segment

Pareto Analysis: Identifies contribution of customers to total sales

Example: Top 21% customers contribute 50% of sales

🔹 Page 3 – RFM Customer Segmentation

RFM Analysis: Based on Recency, Frequency, Monetary Value

Customers grouped into Low, Medium, High Valued segments

Visuals include:

Sales by Customer Segment

Customer Classification Pie Chart

RFM Score Distribution

Customer-level details: Sales, Purchase Frequency, Discount

🔹 Page 4 – Salesperson Performance

Top 5 Salespersons performance by State & City

Sales per salesperson with average discount offered

Drill-down filters: Region, State, Segment, City

🔹 Page 5 – Geo Analysis

US Map with Bubble Chart

State-wise sales to highlight high & low-performing regions

🚀 Key Insights

West Region – Home Office segment achieved 91.85% YoY growth.

Black Plastic Comb Bindings recorded the highest returns.

21% of customers drive 50% of revenue (Pareto Principle).

RFM analysis classified: 337 Medium, 321 High, and 135 Low Valued customers.

California & Texas dominated sales, while smaller states underperformed.

Sales performance varied widely, with a few salespersons driving most sales.

🛠 Tools & Technologies

Power BI Desktop – Data Modeling, DAX, Visualizations

Power Query – Data Cleaning & Transformation

DAX Measures – Advanced Calculations (KPIs, What-If, Pareto, RFM)

✨ This project showcases how business intelligence and analytics can transform raw sales data into actionable insights that fuel better decision-making.
