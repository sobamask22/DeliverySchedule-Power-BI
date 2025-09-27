# Project Title: Delivery Schedule Dashboard


## Project Overview:
Fireaway Pizza stores all stock in the warehouse, and distribute to franchisees across the UK every week. All stock is ordered to the warehouse, pallets are built by warehouse staff to fufil orders from francisees, and they are delivered by company drivers to various routes throughout the week.

The delivery schedule dashboard is a dynamic reporting solution that was designed to deliver insights on stock deliveries to the warehouse. It provides a clear interactive overview of products, stock delivery times, order status, categories, and country of shipping to enable the manager and managing director to monitor performances and make future purchase orders.

### Business Problem:
The company had an absence of a devlivery schedule and inventory management system making it very difficult to monitor purchase orders and track delivery timelines. Using memory and emails to track these, it was very inefficient because it limits accuracy and slows decision making.

### Goal:
The projects starts by collecting raw data using Microsoft Excel, and transforms it into actionable insights through visualizations and data modelling in Power BI. The dashboard enables the stakeholders and logistics manager to view key metrics and make data-driven decisions. It is aimed to collect accurate data.


## Data Structure Overview:
The delivery Schedule's data structure is showed below. A simple diagram showing the columns and data types of the main fact table, the unique fact sheets and how they relate. Prior to beginning the analysis, the data was checked and cleaned using Microft Excel, Python scripts and Power Query.

<img width="1201" height="619" alt="image" src="https://github.com/user-attachments/assets/9fe98617-c894-4ce5-98ca-9a8b75d47fc6" />


## Executive Summary:
Key Performance Indicators show the total purchase cost and shows how the cost was distributed monthly using a simpe line graph. It also uses a map feature to show the location the stock is purchased from. There are also tooltips included so when the map is hovered above, you can see the sum of orders and the total purchase cost per country.

The schedule shows the Month over Month (MoM) purchase cost growth of 0.07%, and the (MoM) individual orders growth of 0.05%. Due to a drop in sales in the business during the summer, there was a quiet period in warehouse. However, as business slowly picked up again, there was a gradual increase in items ordered from the warehouse from franchisees. To prevent items running out of stock in the warehouse, there was a rise in purchase orders to compensate diminished stock.

<img width="1281" height="718" alt="image" src="https://github.com/user-attachments/assets/5ab6719e-3898-4c14-ad73-c9ae4588b43b" />


## Recommendations:
- Supplier Page:
Shows information on the page based on the supplier slicer. The dashboard showed information about the supplier Minster Foods. They supply most of the toppings at very good quality. The pie chart shows how the total purchase cost split across the items sources from minster. The bar graph is used to shows the number of pallets ordered by each ofproducts across each month. The table visualizes information that may be needed for analysis. 

- Category Page:
The category Page shows the page on chilled products. It uses KPI cards to show the sum of purchase costs for all chilled products, the number of orders and which ones were late or on time. This can be very useful when considering storage spaces and orders. The line and bar chart shows the monthly performance on the products by orders and purchase cost.

## Tech Stack:
The dashboard was built using the following tools and technologies:

Microsoft Excel- Microsoft Excel was used to collect the data initially. Creating dropdown lists for Products, Country of Shipping, Category and more using unique function. It made it so those data can have a value everytime. Calculations were added to determine "Order Late?" and "Days Over?" to add further clarity into the Purchase Orders

Python- Pthon was used to clean data and extract unique tables from the general dataset into separate CSV files for analysis

Power BI Desktop- The main visualization platform used to publish the report

Power Query- Used within Power BI for the data transformation and cleaning

DAX (Data Analysis Expression)- Used to create calculated measures for KPIs and dynamic filters

Data Modelling- Used within Power BI to establish relationships between tables for accurate filtering


Personal Note:
