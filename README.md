# Blinkit-Power-BI-Dashboard
**Blinkit Power BI Dashboard: Visualizing Quick-Commerce Operations for Data-Driven Decisions**

**1-Short Description**
This project involves building an interactive Power BI dashboard for Blinkit, India's leading quick-commerce platform, to monitor key metrics like sales, inventory, customer feedback, and marketing performance. By consolidating large volumes of operational data, the dashboard enables stakeholders to identify trends, optimize efficiency, and improve customer satisfaction through real-time visualizations and insights. It serves as a template for similar e-commerce analytics, showcasing my skills in data visualization and business intelligence.

**2-Tech Stack**

**Power BI**: For dashboard creation, data modeling, visualizations (e.g., line charts, bar charts, gauges, KPIs), and interactive features like filters and drill-downs.
Data Sources/Integration: Excel/CSV for mock data import (or SQL/Database connectors if used in production).

**DAX (Data Analysis Expressions)**: For custom calculations, KPIs, and metrics like revenue trends and turnover ratios.

**Power Query:** For data cleaning, transformation, and ETL processes.

**GitHub:** For version control and hosting the project repository (including .pbix files, datasets, and documentation).

**3-Data Source**

**Primary Data**: Synthesized dataset based on Blinkit's operational metrics, including sales revenue ($2.5M current year vs. $2.21M previous), inventory levels (e.g., stock available: 61M units, damaged: 5.99%), customer counts (659 new/2128 total), marketing impressions (912M), and feedback sentiments (1.2M positive). Data was extracted and structured from PDF documents via OCR for simulation purposes.

**Format**: CSV/Excel files imported into Power BI, with mock historical data for trends (e.g., monthly sales, delivery completions).

**Handling**: Cleaned using Power Query to remove duplicates/repetitions from OCR errors, then modeled with relationships for categories like regions, products, and time periods. No real-time API integration; static data for demo.

**4-Features and Highlights**

Interactive Visualizations: Line charts for delivery trends over time, donut charts for completion rates, and bar charts for regional revenue contributions—allowing drill-down by time, region, or category.

KPIs and Metrics: Real-time cards showing average order value, inventory turnover ratio (e.g., 5.33%), customer retention, and ROI analysis, calculated via DAX for actionable insights.

Customer & Feedback Analysis: Gauge charts for retention rates, tables for top customers by revenue, and word clouds/sentiment breakdowns (e.g., 1.2M positive feedbacks) to identify trends and improve engagement.

Marketing & Inventory Optimization: Funnel charts for campaign ROI, pie charts for acquisition channels, heatmaps for low-stock alerts, and stacked bars for spend by region—helping prevent stockouts and allocate budgets effectively.

Sales Overview: Column charts for revenue by product, line charts for monthly trends (e.g., $2.52M/2.21M for 2024 vs. 2023), enabling forecasting and upselling strategies.

Dynamic Filtering & Exports: Slicers for time periods/regions, with export to PDF/Excel for sharing reports.

Business Impact: Demonstrates 13.81% growth in key metrics; provides a scalable framework for e-commerce analytics, reducing decision-making time by centralizing data.

**5-Screenshots and Explanations**

This section showcases key pages from the Blinkit Power BI Dashboard, with screenshots and explanations of their features, metrics, and business implications.

**Overview Page**

![image alt](https://github.com/ankitapandey4000/Blinkit-Power-BI-Dashboard/blob/main/Overview.jpg)

This page provides a high-level summary of business performance, featuring a line chart for total deliveries over time (e.g., trends showing peaks in current year deliveries at 2.5M vs. previous year's 2.2M), a donut chart for delivery completion rates, and a bar chart for revenue by regions (highlighting growth of 32.50% to $2.2M current year from $1.68M previous). It helps stakeholders quickly identify operational trends and resource allocation needs, enabling proactive decisions like scaling during high-demand periods.

**Sales Overview Page**

 ![image alt](https://github.com/ankitapandey4000/Blinkit-Power-BI-Dashboard/blob/main/Sales%20Overview.jpg)

Focused on revenue and order metrics, this page includes a column chart for revenue by product category (e.g., $2.52M in 2024 vs. $2.21M in 2023), a line chart for monthly sales trends, and a KPI card for average order value. It allows users to track growth (13.81% implied from data) and set targets, supporting strategies like promotions for underperforming categories to boost overall revenue.

**Customer Page**

![image alt](https://github.com/ankitapandey4000/Blinkit-Power-BI-Dashboard/blob/main/Customer.jpg)

This page analyzes customer behavior with a gauge chart for retention rates, a table ranking top customers by revenue (e.g., new customers at 659 out of 2128 total), and a word cloud or sentiment analysis for feedback trends. It reveals acquisition patterns (e.g., by month/year) and helps design loyalty programs, improving retention and targeting similar demographics for expansion.

**Inventory Page**

![image alt](https://github.com/ankitapandey4000/Blinkit-Power-BI-Dashboard/blob/main/Inventory.jpg)

Dedicated to stock management, it shows a bar chart for stock levels by category (e.g., available stock at 61M units, 54.41M available percentage), a KPI card for turnover rate (5.33%), and a heatmap/table for low-stock/damaged alerts (5.99% damaged). Monthly breakdowns of received, sold, and closing stock (e.g., up to 100M received) prevent stockouts, optimizing costs and ensuring demand fulfillment.

**Marketing Page**

![image alt](https://github.com/ankitapandey4000/Blinkit-Power-BI-Dashboard/blob/main/Marketing.jpg)

This page evaluates campaign performance via a bar or funnel chart for ROI (e.g., impressions at 912M, conversions at 90.71K), a pie chart for customer acquisition by channel, and a stacked bar for spend by region (current year 744.3K vs. previous 775.75K). It identifies effective channels and adjusts budgets, maximizing ROI and driving targeted growth.

**Feedback Page**

![image alt](https://github.com/ankitapandey4000/Blinkit-Power-BI-Dashboard/blob/main/Feedbacks.jpg)

Centered on customer sentiment, it includes charts for feedback volume (2.5M current vs. 2.21M previous), a breakdown by sentiment (e.g., 1.2M positive, new vs. regular at 1.11M/2128), and lists of individual feedbacks (repeated mentions like "Aedi Bains" possibly indicating sample data). It pinpoints improvement areas, enhancing product quality and customer satisfaction through actionable insights.



