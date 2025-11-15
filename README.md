# 📊 Power BI Sales Analysis Dashboard
*(Sales Person Performance · Category Insights · Geo Trends · Forecasting)*

## 🎯 Project Objective
The main objective of this Power BI project is to analyze sales performance across different **Sales Representatives**, **Teams**, **Product Categories**, and **Geographic Regions**.  
The interactive dashboard transforms raw sales data into actionable insights that help identify top performers, prioritize key accounts, understand category trends, and forecast future revenue.

## 📁 Files Included (suggested)
- `sales-data.xlsx` — Raw & cleaned data tables (people, products, locations, sales)  
- `PowerBI_Report.pbix` — Power BI Desktop file with all pages and measures   
- `dashboard-thumbnail.png` — Project thumbnail for GitHub

## 📂 Dataset Used
**[Call Center Records](https://github.com/Bindukankatala/Sales-data-analysis-power-bi/blob/main/AC-sales-data-blank.xlsx)**

**[Call Center Records](https://github.com/Bindukankatala/Sales-data-analysis-power-bi/blob/main/Power%20BI%20Excel%20Data%20extra.xlsx)**


## ❓ Key Questions (KPIs) Answered
The dashboard was built to answer the following business questions:

### Sales Representative Analysis
1. Who are the top-performing sales representatives?  
2. How much revenue did each person generate?  
3. How many boxes did each salesperson sell?  
4. What is the average amount earned per box?

### Category & Team Insights
5. Which product categories contribute the most revenue?  
6. Which team (Delish, Juicies, Yummies, Special) performs best?

### Geographic & Trend Analysis
7. Which countries generate the highest sales?  
8. How is sales performance distributed region-wise?  
9. What are the monthly and yearly sales trends and forecasts?

## ⚙️ Process Overview

### 1. Data Loading & Modeling
- Data loaded from Excel into Power BI Desktop.
- Cleaned and verified data types; removed duplicates / fixed date formats.
- Built relationships: `sales ↔ people`, `sales ↔ products`, `sales ↔ locations`.
- Created date hierarchy: **Year → Quarter → Month**.

### 2. DAX Measures
Common measures used:
- `Total Amount`
- `Total Boxes`
- `Amount Per Box` (Total Amount / Total Boxes)
- Time-intelligence measures (Month-to-date, YTD, rolling totals)
- Forecast-related measures (used by built-in Power BI forecasting visuals)

### 3. Report & Visual Design
- Used slicers for **Team**, **Geo**, and **Sales Person** for interactive filtering.
- Visual elements include tables, bar charts, column charts, line charts with forecasting, and KPI cards.
- Clean layout with emphasis on readability and quick decision-making.
- 
## 📊 Dashboard
![Call Center Dashboard](https://github.com/Bindukankatala/Sales-data-analysis-power-bi/blob/main/Sales%20Person%20Analysis%20Dashboard.png)
*(The dashboard visualizessales performance by geography, team, and individual salespersons.)*

![Call Center Dashboard](https://github.com/Bindukankatala/Sales-data-analysis-power-bi/blob/main/Sales%20Performance%20Dashboard.png)
*(The dashboard visualizessales overall sales performance by salesperson, product category, and geographic region.)*

![Call Center Dashboard](https://github.com/Bindukankatala/Sales-data-analysis-power-bi/blob/main/Sales%20and%20Trend%20Forecast%20Dashboard.png)
*(The dashboard visualizes customer and sales trends over time with future forecasts.)*

## 📄 Report Pages

### Page 1 — Sales Person Analysis
- Visuals: Sales person table (photo, total amount, total boxes, amount/box), Amount by Geo bar chart, Amount by Team horizontal bars.
- Purpose: Compare performance across salespersons, teams, and geographies.

### Page 2 — Sales Performance Report
- Visuals: Detailed table with photos, Category Performance bar chart, Amount by Geo chart, Team slicer.
- Purpose: Single-screen deep-dive of all core KPIs for leadership reviews.

### Page 3 — Sales & Trend Forecast Report
- Visuals: Line chart of total customers over time, line chart of total amount with forecast cone.
- Purpose: Detect seasonality, identify growth patterns, and forecast near-term revenue.

## 💡 Key Insights
- **Top Salespersons**: A small set of reps generate the majority of revenue — great candidates for cross-training and retention.
- **Category Performance**: “Bars” category leads revenue; other categories show seasonal peaks.
- **Team Performance**: Teams like *Yummies* & *Delish* drive the highest revenue; useful for workload balancing.
- **Geo Distribution**: New Zealand, India, UK, USA show strong revenue—no obvious underperforming region.
- **Forecast**: Revenue and customer count projections trend upward indicating expansion opportunities.
- **Operational**: Use slicers and drill-through to identify underperforming reps for targeted training.

## 🚀 Final Conclusion
This Power BI dashboard provides a 360° view of sales performance and helps stakeholders:
1. Recognize and reward top-performing sales reps.  
2. Rebalance team assignments and staffing where necessary.  
3. Prioritize product categories for promotions and inventory planning.  
4. Use forecasts for short-term hiring or promotional campaigns.
