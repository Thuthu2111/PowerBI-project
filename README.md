# Northwind Traders Dashboard (Power BI)
A data-driven Dashboard to get update of key business factors for executive decision-making

🌟 Technical highlights
  - Report design: create 1-page dasboard with clean layout, all key areas coverage and dynamic slicers
  - DAX: develope custom measures (ex: Shipping cost per Order, Sales, No orders, YoY difference & percentage, etc)
  - Interactive visuals: provide friendly-user report with Slicers, Tooltips, Conditional formating
  - Advanced filtering: allow flexibility in viewing data (ex: Sales calculated by Order date/Shipped date, Order status, Month status)

📊 Key insights

🌟 Background
  - Role: **BI Developer** for Northwind Traders, a global import and export company in gourmet food products.
  - Task: build **an executive KPI dashboard** to provide **quick insights of company performance** in key areas 
    + Sales trends
    + Product performance
    + Key customers
    + Shipping costs

🌟 Data overview
  - The datasets include 7 files: Categories, Customers, Employees, Order_details, Orders, Products, Shippers 
  - Key facts:
    + Total 830 orders from Jul 2013 - Jun 2015
    + Each order has 3 types of date: Ordered date, Required date, Shipped date. 
    + Some orders are seen with null Shipped date (Incomplete).

🌟 Dashboard structure: A 1-page Dashboard for executive to get quick business update
  1. **Overview**
  - KPI cards: Sales, Shipping cost, No of orders, No of customers (with YoY change)
  2. **Sales trend** 
  - Line chart tracks sales over time
  - Tooltip: Top 5 Employees by sales
  3. **Shipping cost**
  - Line chart tracks shipping cost per order over time
  - Tooltip: Shipping company overview
  4. **Product**
  - Bar chart: Sales by Product Category
  - Table of top 5 Product's performance (with YoY change)
  5. **Key customers**
  - Table of top 5 Customers by Sales (with YoY change)
  6. **Slicers**
  - Time: Year, Month
  - Sales calculated by: Ordered date, Shipped date
  - Order status: Complete, Incomplete (Incomplete= Order with null Shipped date).
  - Month status: Complete, Incomplete (Incomplete= Month with incomplete order).
  - Others: Product category, Customer Name, Employee Name, Shipping Company

🌟 About Me

Hi there! I'm Thu Nguyen Hoai, self-taught Data Analyst in Hochiminh, Vietnam. This github is created to upload my projects while learning data analysis.
