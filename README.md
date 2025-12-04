

 # 🛒 Grocery Sales Dashboard — README
📌 Overview



This Power BI dashboard provides a comprehensive analysis of grocery sales, tracking sales performance over time, shipment distribution across countries, and contributions made by individual sales representatives. It helps identify sales patterns, shipment volume, and top performers with clear visual insights.

🔗 Data Source
1) Local Excel File

Source: grocery_sales_data.xlsx

Connection Type: Import

Fields Used:

Date

Amount

Country

Sales_Person

Boxes_Shipped

Data Preparation

Cleaned in Power Query

Removed duplicates

Fixed data types (Date/Number/Text)

Ensured consistency in country & sales person names

🧩 Data Model

Fact Columns: Amount, Boxes_Shipped

Dimension Columns: Date, Country, Sales_Person

Transformations:

Aggregated totals for amount & shipment

Standardized date hierarchy

Created category-wise breakdowns

📏 Measures Used
Total Amount = SUM(Amount)
Total Boxes Shipped = SUM(Boxes_Shipped)
Amount by Sales Person = SUM(Amount)
Boxes by Country = SUM(Boxes_Shipped)

📊 Dashboard Visuals
1) Amount by Date (Line Chart)

Shows daily sales trends throughout the year.

2) Amount by Sales Person (Bar/Line Chart)

Displays contribution of each sales representative with increase/decrease indicators.

3) Boxes Shipped by Country (Pie Chart)

Country-wise shipment share across Australia, Canada, UK, India, USA, and New Zealand.

4) Boxes Shipped by Sales Person (Donut Chart)

Highlights how many boxes each representative shipped.

5) Total Boxes Shipped (Card Visual)

Shows the overall shipment volume: 177K boxes.

🌱 Key Insights

Total boxes shipped: 177K

Balanced shipment distribution among multiple countries

Sales performance varies significantly by reps

Date-wise line chart reveals demand fluctuations.

Show what the dashboard looks like.---  ![Dashboard Preview](https://github.com/Sonu6290/Grocery-Sales-Data/blob/main/Grocery%20Sales%20Data.png)

