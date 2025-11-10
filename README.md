
# 📊 E-Commerce Sales Dashboard (Power BI)

## 🔍 Overview
This **E-Commerce Dashboard** provides a comprehensive overview of sales performance, customer trends, and order analytics across various continents and payment methods.  
It helps business leaders **track KPIs**, identify **growth opportunities**, and **optimize marketing and inventory decisions** through data-driven insights.

---

## ⚙️ Tools & Technologies
- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query for ETL  
- Excel / CSV data sources  
- Interactive slicers and filters  

---

## 🎯 Key Objectives
1. Track **monthly sales trends** and **Average Order Value (AOV)**  
2. Compare **orders and customer metrics** vs. previous months  
3. Analyze **payment method preferences** and **geographical distribution**  
4. Monitor **product performance** (Orders, Sales, and AOV Growth)  
5. Provide **interactive filters** by category and month  

---

## 🧠 Business Insights
- **Europe (32%)** and **North America (19%)** contribute the highest sales volume  
- **Credit Card** is the most preferred payment method (~35%)  
- **Laptop and Smartphone** categories drive the majority of revenue  
- **February** shows a minor decline in customers (-4.1%) compared to January  
- Data highlights opportunities for **targeted promotions** in **low-performing continents** like Africa and South America  

---

## 📈 Dashboard Features

| Feature | Description |
|----------|-------------|
| **KPI Cards** | Displays key metrics like Customers, Orders, Sales, and AOV with comparison to previous months |
| **Sales by Month** | Visualizes monthly sales trends for year-over-year comparison |
| **Sales by Payment Method** | Pie chart showing the percentage share of payment modes |
| **Sales by Continent** | Visual distribution of sales contribution by region |
| **Product Performance Table** | Detailed product-level insights with mini trend charts and growth metrics |
| **Interactive Filters** | Dynamic slicers for selecting category and month views |

---

## 🗂️ Data Model Overview
- **Fact Table:** `Sales_Data`  
- **Dimension Tables:** `Products`, `Customers`, `Dates`, `Regions`, `PaymentMethods`  
- Relationships defined on `Customer_ID`, `Product_ID`, and `DateKey`  
- DAX measures created for:  
  - `Total Sales`  
  - `Total Orders`  
  - `Average Order Value`  
  - `Month-over-Month Growth`  

---

## 📷 Dashboard Preview
https://github.com/chavdajaymeen-create/Jaymeen-Chavda-Dashboards/blob/main/Ecommerce%20Dashboard.jpeg
