# PowerBI-project
🌟 Background
- Your role in this project: a BI Developer for Northwind Traders, a global import and export company that specializes in supplying high-quality gourmet food products to restaurants, cafes, and specialty food retailers around the world. 
- Task: build **a top-level KPI dashboard** for the executive team so that they can **quickly understand the company's performance** in key areas **Sales trends, Product performance, Key customers, Shipping costs**

🌟 Data overview
  - Include 7 files: Categories, Customers, Employees, Order_details, Orders, Products, Shippers 
  - Total 830 orders, time range from Jul 2013 - Jun 2015. Each order has 3 types of date: Ordered date, Required date, Shipped date. Some orders are seen with null Shipped date.

🌟 Dashboard structure

This Dashboard is built **for high-level positions to get quick understand of company performance**, so my approach is building **1-page report**. It will include
1. **Overview**: Key KPI card to get current performance & YoY. Metrics: Sales, Shipping cost, No of orders, No of customers
2. **Details of key areas** 
  - Sales trends: track sales over time by line chart and Top 5 Employees by sales in Tooltip
  - Shipping costs: track shipping cost per order over time by line chart and Shipping company overview in Tooltip
  - Product performance: through sale by Category and top 5 Product's sale performance
  - Key customers: top 5 Customers by Sales
3. **Slicers**
  - Time aka Year, Month
  - Sales calculated by: Ordered date, Shipped date
  - Order status: Complete, Incomplete; in which Incomplete order is order with null Shipped date.
  - Month status: Complete, Incomplete; in which Incomplete month is month including incomplete order.
  - Other slicers based on the raw data: Product category, Customer Name, Employee Name, Shipping Company

🌟 About Me

Hi there! I'm Thu Nguyen Hoai, self-taught Data Analyst in Hochiminh, Vietnam. This github is created to upload my projects while learning data analysis.
