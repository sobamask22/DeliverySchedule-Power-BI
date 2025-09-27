# Project Title: Delivery Schedule Dashboard


## Project Overview:
The company stores stock in their warehouse and distribute it to franchisees across the UK. All stock is ordered from external suppliers and stored in the warehouse. Pallets are then assembled to complete franchisee orders, which are delivered by company drivers to the stores throughout the week.

The Delivery Schedule Dashboard is a dynamic reporting solution designed to provide clear and interactive insights into stock deliveries. It offers visibility into products, delivery times, purchase costs, and more, enabling the logistics manager and managing director to monitor performance and make data driven purchases.

### Business Problem:
The company lacked a delivery schedule and management system, making it very difficult to track purchase orders and delivery timelines. Relying on memory and emails to track and backlog orders was inefficient, limited accuracy, and slowed decision making.

### Goal:
This project collects raw data in Microsoft Excel and transforms it into actionable insights through visualizations and data modeling in Power BI. The dashboard summarizes key metrics and allows stakeholders to monitor deliveries, purchase costs, and order activity to improve planning and purchasing decisions.

## Data Structure Overview:
### The delivery Schedule's data model is showed below. It highlights:
- The main fact table with its columns and data types
- Relationships to supporting tables
Data was cleaned and prepared using Microsoft Excel, Python scripts, and Power Query before analysis. 

<img width="1201" height="619" alt="image" src="https://github.com/user-attachments/assets/9fe98617-c894-4ce5-98ca-9a8b75d47fc6" />


## Executive Summary:
Key Performance Indicators (KPIs) track total purchase costs and their monthly distribution through a simple line graph. A map visual identifies supplier locations, with interactive tooltips showing total orders and purchase costs per country.

### Highlights:
- Month-over-Month (MoM) Purchase Cost Growth: +0.07%
- MoM Orders Growth: +0.05%

During the summer, a dip in sales caused a temporary slowdown in warehouse activity. As demand recovered, franchisees increased orders, prompting higher purchase volumes to replinish warehouse stock.

<img width="1281" height="718" alt="image" src="https://github.com/user-attachments/assets/5ab6719e-3898-4c14-ad73-c9ae4588b43b" />


## Recommendations:
### Supplier Page:
- Displays Minster insights using a slicer filter
  
- The pie chart shows the share of total purchase cost by product
  
- The bar chart highlights monthly pallet orders by product
  
- The table provides detailed information for further analysis


### Category Page:
- Focuses on the category chilled products
  
- KPI cards summarize purchase costs, total orders, & late/on-time deliveries
  
- The line and bar chart tracks monthly trends using orders and purchase costs


## Tech Stack:
The dashboard was built using the following tools:

- Microsoft Excel: Initial data collection, drop-down lists for Products, Country, Category, etc, and calculated columns for “Order Late?” and "Number of Days Over?”
  
- Python: Data cleaning and extraction of unique tables into separate CSV files for analysis
  
- Power BI Desktop: Main platform for data visualization and reporting

- Power Query: Data transformation and preparation

- DAX (Data Analysis Expressions): Creation of KPIs and dynamic filters

- Data Modeling: Establishing relationships between tables for accurate filtering


## Personal Note:
- This was a simple visualization project based on data collected during my role as a Logistics Assistant.
  
- At the time, I was new to the role and saw Excel as an efficient way to store and organize delivery data.
  
- As I gathered more data, I gradually added new features to improve analysis.
  
- The dataset covers a short time period, so the report is limited in historical depth but demonstrates core reporting capabilities.

