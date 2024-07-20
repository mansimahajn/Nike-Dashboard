# Nike Power BI Dashboard
## Overview
This project involves the creation of an interactive Power BI dashboard to analyze Nike sales data. The dashboard is designed to provide valuable insights into sales performance, trends, and product analysis, supporting data-driven decision-making. By leveraging Power BI's advanced features, the project aims to deliver a comprehensive and intuitive visualization of key business metrics.

## Key Features
**1. Interactive Visualizations:**

The dashboard features engaging and interactive charts and graphs that allow users to drill down into specific data points for deeper analysis.
Various types of visualizations such as bar charts, line charts, pie charts, and heat maps are used to represent the data effectively.


**2. Date Table Creation:**

A custom date table is created to facilitate time-based analysis.
Detailed columns for day, day number, month, month number, and year are included to enable precise time series analysis.

Calender = CALENDAR(
    DATE(YEAR(MIN(Virat_Kohli[date])), 1, 1),
    DATE(YEAR(MAX(Virat_Kohli[date])), 12, 31)
)
day = FORMAT(Calender[Date], "ddd")
day_no = DAY(Calender[Date])
month = FORMAT(Calender[Date], "mmm")
month_no = MONTH(Calender[Date])
year = YEAR(Calender[Date])

**3. Sales Analysis:**

The dashboard provides a comprehensive analysis of sales performance, including total revenue, average order value, and total units sold.
Key performance indicators (KPIs) are highlighted to give a quick overview of the business performance.


**4. Product Insights:**

Detailed insights into top-performing products are presented, including best-selling products and categories.
Comparative analysis of different products and their contribution to overall sales is included to support strategic planning.

## Insights

**Sales Performance:**

Analyze overall sales trends and performance, including total sales, revenue growth, and sales volume.
Identify peak sales periods and seasonal trends to optimize inventory and marketing strategies.

**Product Analysis:**

Identify top-selling products and categories to understand consumer preferences and demand.
Evaluate the performance of different product lines and identify opportunities for product development and promotions.

**Monthly and Yearly Trends:**

Track sales trends over different time periods to identify long-term patterns and anomalies.
Compare monthly and yearly performance to set realistic sales targets and measure progress.

## Conclusion
This project demonstrates the effective use of Power BI for sales data visualization and analysis. By providing a detailed view of sales performance, product analysis, and trends, the dashboard supports data-driven business decisions. It showcases how businesses can leverage data visualization tools to gain actionable insights and improve strategic planning.
