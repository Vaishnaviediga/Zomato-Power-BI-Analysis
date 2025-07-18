

 🍽️ Zomato Data Analytics Dashboard (Power BI Project)

1. Introduction

This project is a comprehensive Power BI dashboard built using Zomato's restaurant data. It covers restaurant analysis, customer behavior, pricing insights, and booking trends — all visualized interactively for business stakeholders.

2. Project Objectives

 🎯 Objectives
- Derive financial metrics using fiscal calendar (April–March)
- Segment restaurants based on price & rating buckets
- Track weekly, monthly, and quarterly performance
- Integrate multiple tables to build a connected data model
- Visualize top cuisines, cities, online booking trends, and KPIs

3. Tools Used

 🛠️ Tools & Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (ETL)


4. Data Model and DAX**

 📊 Data Modeling & Key DAX Calculations

Financial Quarter (Starting April)
DAX
FM = "FM" & IF(MONTH(Main[Date]) >= 4,
               ROUNDUP((MONTH(Main[Date]) - 3) / 3, 0),
               ROUNDUP((MONTH(Main[Date]) + 9) / 3, 0))
 Additional Calculations:

* Week Number
* Weekday Name
* Year-Month Label
* Price Buckets
* Rating Buckets


5. Insights Summary

 💡 Key Insights
- North Indian cuisine dominates, though initially filtered out in Top N logic
- Online delivery services are more commonly offered than table booking
- Cities like Mumbai and Delhi NCR lead in restaurant count
- Price bucket segmentation highlights consumer affordability trends




🙋‍♀️ ABOUT ME

Hi! I'm Vaishnavi, a data analytics professional skilled in Excel, Power BI, and SQL. This project is part of my learning portfolio to demonstrate real-world analytics capabilities.



