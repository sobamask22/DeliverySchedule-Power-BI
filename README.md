# Project Title: Delivery Schedule Dashboard

Insights Deep Dive:

Recommendations:

# Project Overview:
Fireaway Pizza store all stock in their warehouse and distribute to franchise stores every week by deliveries. All stock is ordered to the warehouse, the pallets are built per order, and delivered by company drivers and vehicles 6 days a week to various locations across the UK.

The delivery schedule dashboard is a dynamic reporting solution that was designed to deliver insights on stock deliveries to the warehouse. It provides a clear interactive overview of stock delivery times, order status, categories, and country of shipping to enable the manager and managing director to monitor performances and make future decisions.

### Business Problem:
The business had an absence of a devlivery schedule and inventory management system making it very difficult to monitor purchase orders and track delivery timelines. Using memory and emails to track these was very inefficient because it limits accuracy and slows decision making for future purchase orders.

### Goal:
The dashboard collects raw data using Microsoft Excel, and transforms it into actionable insights through visualizations and data modelling in Power BI. The dashboard enables the stakeholders and logistics manager to view key metrics and make data-driven decisions with confidence.

### Insights are given on the following key areas:
Trend Analysis:

Category Comparison:

Regional Comparisons:

# Data Structure Overview:
The delivery Schedule's data structure is showed below. A simple diagram showing the columns of the main fact table, the unique fact sheets derived from it and how they relate to each other.

<img width="1010" height="694" alt="image" src="https://github.com/user-attachments/assets/4a463db1-a16a-4d62-ae75-5de9fcf5da5f" />

Prior to beginning the analysis, the data was checked and cleaned using python scripts to ensure a smooth accurate result. 

# Executive Summary:
## Overview of report:
The delivery schedule shows the total purchase cost and breaks it down into the months recorded using a simpe line graph. It also uses a map feature to show where the stock is purchased from. There are also tooltips included so when the map is hovered above, you can see the amount of orders from each country and the total purchase cost.

The schedule also shows the Month over Month (MoM) purchase cost growth of 0.07%, and the (MoM) individual orders growth of 0.05%. Due to a drop in sales of warehouse stock between April and June there was a surplus in some items meaning less stock was ordered. However, as business slowly picked up again, there was a gradual increase in items ordered into the warehouse to potentially preventing items running out of stock.

<img width="1281" height="718" alt="image" src="https://github.com/user-attachments/assets/5ab6719e-3898-4c14-ad73-c9ae4588b43b" />


# Tech Stack:
The dashboard was built using the following tools and technologies:
Microsoft Excel:

Python- Used to extract unique tables from general dataset into separate CSV files for analysis

Power BI Desktop- Main visualization platform used to publish the report

Power Query- Used within Power BI for the data transformation and cleaning

DAX (Data Analysis Expression)- Used to create calculated measures for KPIs and dynamic filters

Data Modelling- Used to establish relationships between tables for accurate filtering
