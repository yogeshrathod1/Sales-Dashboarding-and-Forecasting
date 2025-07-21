# Sales Dashboarding and Forecasting

### Objective
To create an interactive and insightful dashboard for Royal Store’s sales data, facilitating strategic decision-making and future sales forecasting.

### Dataset
The dataset is an Excel file containing sales data for 2019 and 2020, with approximately 6,000 rows and the following columns:

Order ID, Order Date, Customer ID, Customer Name
Segment (Consumer, Corporate, Home Office)
Country, City, State
Product ID, Category, Sub-Category, Product Name
Sales, Quantity, Profit, Returns
Payment Mode (Card, COD, Online)
Average Delivery Date
### Technologies/Tools

Power BI for data visualization and dashboard creation
Excel for initial EDA and data cleaning
DAX for custom metric calculations

### Process
#### Data Exploration and Cleaning:

Performed exploratory data analysis (EDA) in Excel.
Imported data into Power BI, handled outliers, missing values, and inconsistencies.
Created a custom metric for average delivery time using DAX.

### Dashboard Development:

Designed a simple and intuitive dashboard with KPIs, slicers, and interactive visuals.
Incorporated time-series forecasting for future sales trends.

### Challenges

Gained an understanding of the business context and problem statement by conducting research on sales trends and retail performance.

### Key Insights

KPI Summary:

Average Shipping Days: 4
Total Quantity Sold: 22K
Total Profit: $175K
Total Sales: $1.57M

### Segment-wise Sales:

Consumer: 48%, Corporate: 33%, Home Office: 19%

### Payment Mode Breakdown:

COD: 43%, Online: 35%, Cards: 22%

### Top Sub-Categories by Sales:

Phones: $0.20M, Chairs: $0.18M, Binders: $0.17M

### Regional Performance:

Highest profit: West USA; Lowest profit: South USA
Best-performing states: California, New York, Texas
Least-performing state: District of Columbia

### Trends and Anomalies:

Identified a sharp decline in profits in April 2020 despite good sales.
Sales and profit trends in 2019 and 2020 were similar, with notable growth in December 2020.

### Forecasting Results:

Predicted 5,304 orders per day from Dec 31, 2020, to Jan 14, 2021.
Forecast bounds: 1,294 (lower) to 9,313 (upper) orders per day.

### Visualizations
KPI Cards: Display key metrics like sales, profit, quantity, and average shipping days.
Donut Charts: Show sales breakdown by segment and payment mode.
Line Charts: Compare monthly sales and profit trends for 2019 and 2020.
Column Charts: Display sales by category, sub-category, and shipping mode.
Map Visualization: Highlights sales and profit by state.
Forecasting Chart: Uses a time-series model to predict future sales, with state-level slicers.

### Conclusion
This project provides valuable insights into Royal Store’s sales performance, highlights regional trends, and identifies anomalies. The sales forecast supports strategic planning, while the dashboard offers a comprehensive view of the business.
