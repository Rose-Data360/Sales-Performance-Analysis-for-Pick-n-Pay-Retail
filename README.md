# SALES PERFORMANCE ANALYSIS
## Leveraging PowerBI's Analytics for Sales Performance Analysis for Pick n'Pay Retail

![Screenshot 2025-06-19 001629](https://github.com/user-attachments/assets/85cb671d-a5ae-41b8-87e1-fefddcb44a64)

 Disclaimer⚠️: The datasets, slides, and reports do not contain any proprietary, confidential, or sensitive information from the listed companies, institutions, or individuals. All the content is dummy and aimed to demonstrate my capabilities of utilising Power BI to examine a healthcare dataset.

 # INTRODUCTION
 The goal of this project is to leverage Power BI's sophisticated analytics tools to examine sales performance across a number of product categories at Pick 'n Pay, the industry leader in electronics, home goods, and personal care products. By looking at important indicators, including as revenue, market potential, and sales patterns, and to show growth or decline, include graphic comparisons with prior years.  By highlighting top performing cities, channels, and clients, the analysis seeks to offer actionable insights that will facilitate data-driven strategic decision-making. 

 

![Screenshot 2025-06-18 185650](https://github.com/user-attachments/assets/ececf404-cc3b-4c61-b929-cd905516f78c)

# PROBLEM STATEMENT
Pick 'n Pay Retail aims to enhance its understanding of sales performance across various products by analyzing key metrics, including total sales, profit margins, and order trends.The main challenge is to compare year-over-year performance, identify top-performing products and cities, and track customer preferences effectively.Effective decision-making about consumer behaviour, product performance, and geographical patterns is hampered by a lack of comprehensive understanding of these trends. Pick 'n Pay Retail can address underperforming cities, learn more about customer behaviour, product performance, regional trends, and direct future investments in important product categories by carefully examining these metrics. This will help the company make better, quicker business decisions across channels and regions.

# AIM OF THE PROJECT
- Give an overview of year-over-year sales performance, emphasising top-performing products and cities, and track customer preferences
- Analyze sales trends to identify high-performing and underperforming cities.
- Use Power BI to visualise sales KPIs and trends and give decision makers with actionable information
- Make suggestions for improving company profitability based on your insights

# MODELLING
The Pick ‘n Pay data model follows a star schema structure, with the Order Fact table (Order ID, Customer ID, Product ID, Channel, Order Quantity ,Order Date, Profit, Reginal ID, Currency Code), at the center, linking to key dimension tables (Customer-Dm, Product-Dm, Location-Dm, and Calendar-Dm) via primary keys. This design enables efficient filtering and analysis of sales data by customer, product, location, and time, providing powerful insights such as year-over-year trends, regional performance, and product-level profitability.



![Screenshot 2025-06-19 230404](https://github.com/user-attachments/assets/6be0a340-cd0b-46a9-b211-d9ea630d5e97)

# VISUALIZATION
- KPI'S
- Bar Chart
- Line Chart

# DATA ANALYSIS

KPI'S

This visualization compares Pick 'n Pick Retail's monthly sales trends to the prior year (PY) and displays key performance indicators (KPIs) for total sales, total profit, total product, and order quantity. We had $188 million in total sales, which was 21.8% more than the previous year.It then made $70 million in profit, which is 22% more than the previous year and indicates that we are not just selling more but also operating more profitably. Despite the fact that 82,000 individual goods were sold, this indicates that there was significant product mobility.
Since we are now monitoring 14 essential products, it is simple to concentrate on the top-selling items.


![Screenshot 2025-06-20 071657](https://github.com/user-attachments/assets/00f8ac73-1eb0-45b2-9233-a1120e953646)

Bar Chart

This bar graph presents a comparison of revenue across three different sales channels. Wholesale shows the highest performance with 0.1 billion (bn), making it the most dominant channel among the three. Distributor: Second highest, but noticeably longer than Export, indicating a moderate contribution to the overall sales or revenue. Export performs the lowest.
 Showing sales under 0.05 billion.
