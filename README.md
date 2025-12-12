# Car-Sales-Dashboard

1. Project Title / Headline
🚗 AutoVelocity: Global Car Sales Insights Dashboard A dynamic, interactive data visualization tool built to explore automotive market data—focusing on sales volume, revenue trends, car model attributes, and regional performance.

2. Short Description / Purpose
The AutoVelocity Dashboard is a comprehensive analytical tool that consolidates critical sales data into a single view. It allows sales managers and executives to monitor performance across different car models, regions, and time periods. The dashboard is designed to replace manual reporting, offering instant visibility into "Units Sold," "Total Revenue," and "Average Transaction Price," empowering stakeholders to make data-driven decisions on inventory and marketing strategies.

3. Tech Stack
The dashboard was built using the following tools and technologies:
📊 Power BI Desktop: The primary engine used for report authoring, visualization, and layout design.
📂 Power Query (M): Used for ETL (Extract, Transform, Load) processes to clean raw sales logs, handle missing values, and standardize vehicle model names.
🧠 DAX (Data Analysis Expressions): Utilized for creating time-intelligence measures (e.g., Year-over-Year growth), aggregate totals, and dynamic KPI logic.
📝 Data Modeling: A Star Schema design connecting a central Sales fact table with dimension tables such as Products (Car Models), Customers, and Calendar.
🎨 Custom Theming: Utilizes a custom JSON theme (CY25SU11.json) and specific background imagery (Car_Sales_Background...jpg) to create a cohesive, branded user interface.

4. Data Source
Source: Internal Sales CRM / ERP System (Simulated).
Structure: The data model aggregates transactional records containing details on individual vehicle sales, including dates, sale prices, customer demographics, and vehicle specifications (Model, Color, Body Type).

5. Features / Highlights
• Business Problem Automotive dealerships often struggle with fragmented data. Sales figures are buried in spreadsheets, making it difficult to answer simple questions quickly: Which models are underperforming? Is revenue trending up or down compared to last month? Which region has the highest demand for SUVs?

• Goal of the Dashboard To create a "Single Source of Truth" that:
Monitors Health: Instantly visualizes top-line revenue and unit sales.
Identifies Trends: Spots seasonal buying patterns and popular vehicle attributes.
Optimizes Strategy: Helps inventory managers stock the right cars at the right time.

• Walkthrough of Key Visuals
Executive KPI Cards (Top Ribbon): Immediate snapshots of critical metrics:
Total Revenue: The sum of all sales.
Units Sold: Total count of vehicles delivered.
Avg. Price: The average selling price per unit, helpful for tracking discounting trends.

• Sales Trend Analysis (Line Chart): A continuous time-series visual showing revenue or units sold over months/years. This helps identify peak seasons (e.g., end-of-year sales events) or slow periods.
 Top Selling Models (Bar Chart): A ranked horizontal bar chart displaying the best-performing car models.
 Insight: Quickly separates the "Cash Cows" (e.g., best-selling SUVs) from slow-moving inventory.
 Sales by Body Style (Donut/Pie Chart): A segmentation visual breaking down sales by category (SUV, Sedan, Hatchback, Truck).
 Insight: Helps understand consumer preference shifts (e.g., the market shift from Sedans to SUVs).
 Regional Performance (Map or Column Chart): (If geospatial data is present) Visualizes sales density by state or city, highlighting high-performing dealer locations versus those needing support.

• Business Impact & Insights
Inventory Optimization: Dealers can reduce holding costs by stocking more of the high-turnover models identified in the "Top Selling" visuals.
Revenue Forecasting: Historical trend lines allow finance teams to predict upcoming quarterly revenue with greater accuracy.
Marketing Focus: Insights into "Who buys what" (e.g., Sedan vs. SUV trends) allow for targeted ad spend.

6. Screenshots / Demos
Show what the dashboard looks like.
Example : [Dashboard Preview] :(https://github.com/monisha23102000/Car-Sales-Dashboard/blob/main/Car_Sales_Dashboard_Overview.png)
