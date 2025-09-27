# Project Title: Delivery Schedule Dashboard


## Project Overview:
Fireaway Pizza store all stock in their warehouse, and distribute to franchisees across the UK every week by deliveries. All stock is ordered to the warehouse, pallets are built to fufil orders, and they are delivered by company drivers 6 days a week to various routes.

The delivery schedule dashboard is a dynamic reporting solution that was designed to deliver insights on stock deliveries to the warehouse. It provides a clear interactive overview of stock delivery times, order status, categories, and country of shipping to enable the manager and managing director to monitor performances and make future purchase orders.

### Business Problem:
The company had an absence of a devlivery schedule and inventory management system making it very difficult to monitor, purchase orders and track delivery timelines. Using memory and emails to track these was very inefficient because it limits accuracy and slows decision making.

### Goal:
The  projects starts by collecting raw data using Microsoft Excel, and transforms it into actionable insights through visualizations and data modelling in Power BI. The dashboard enables the stakeholders and logistics manager to view key metrics and make data-driven decisions.


## Data Structure Overview:
The delivery Schedule's data structure is showed below. A simple diagram showing the columns and data types of the main fact table, the unique fact sheets and how they relate to each other. Prior to beginning the analysis, the data was checked and cleaned using Microft Excel, Python scripts and Power Query.

<img width="1201" height="619" alt="image" src="https://github.com/user-attachments/assets/9fe98617-c894-4ce5-98ca-9a8b75d47fc6" />


## Executive Summary:
Key Performance Indicators show the total purchase cost and shows how the cost was distributed monthly using a simpe line graph. It also uses a map feature to show the location of the stock is purchased from. There are also tooltips included so when the map is hovered above, you can see the sum of orders and the total purchase cost.

The schedule shows the Month over Month (MoM) purchase cost growth of 0.07%, and the (MoM) individual orders growth of 0.05%. Due to a drop in sales in the business during the summer, there was a quiet period in warehouse sales. However, as business slowly picked up again, there was a gradual increase in items ordered from the warehouse. To prevent items running out of stock in the warehouse, there was a rise in purchase orders to compensate.

<img width="1281" height="718" alt="image" src="https://github.com/user-attachments/assets/5ab6719e-3898-4c14-ad73-c9ae4588b43b" />

## Recommendations:

## Tech Stack:
The dashboard was built using the following tools and technologies:

Microsoft Excel- Microsoft Excel was used to collect the data initially. Creating dropdown lists for Products, Country of Shipping, Category and more using unique function. It made it so those data can have a value everytime. Calculations were added to determine "Order Late?" and "Days Over?" to add further clarity into the Purchase Orders

Python- Pthon was used to clean data and extract unique tables from the general dataset into separate CSV files for analysis

Power BI Desktop- The main visualization platform used to publish the report

Power Query- Used within Power BI for the data transformation and cleaning

DAX (Data Analysis Expression)- Used to create calculated measures for KPIs and dynamic filters

Data Modelling- Used within Power BI to establish relationships between tables for accurate filtering


## Personal Review:
