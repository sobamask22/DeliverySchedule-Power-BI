# Project Title: Delivery Schedule Dashboard

## Project Overview:
The Delivery Schedule Dashboard is a dynamic reporting solution designed to provide clear and interactive insights into stock deliveries. It offers visibility into products, quantities, delivery times, purchase costs, supplier performance and more. This enables the logistics manager and managing director to monitor operational performance and make data driven purchases. The company has one warehouse where all stock is received from external suppliers. Key processes include:

- **Inbound Stock:** Goods are ordered from third-party suppliers and stored in the warehouse
  
- **Order Assembly:** Pallets are assembled to fulfill franchisee orders
  
- **Outbound Delivery:** Company drivers distribute stock to franchisee stores across the UK throughout the week

### Business Problem:
The company lacked a centralized management system for delivery schedules and purchase orders, making it difficult to keep track. Operations were heavily reliant on memory and email threads, leading to:

- **Inefficient workflows:** Uncertainty around what had been ordered made it difficult to retrieve information when requested by the logistics manager or managing director. This created delays and confusion in day to day operations
  
- **Inaccurate or Limited data:** The warehouse has limited storage capacity, making it essential to know what stock is in transit, its quantity, and expected arrival dates. Without reliable data, the warehouse manager struggled to plan effectively and allocate space
  
- **Slower decision making:** Purchase decisions were often delayed due to a lack of visibility into incoming stock. Overstocking posed a serious risk by consuming warehouse space and disrupting inventory flow. This issue is critical for chilled and frozen items, which could spoil and result in financial losses

### Solution:
This Power BI solution transforms raw delivery data from Microsoft Excel into actionable insights. Through robust data modeling and interactive visualizations, the dashboard enables stakeholders to:

- Track delivery schedules and order activity
  
- Monitor purchase costs and supplier performance

- Track price changes and quantity ordered over time
  
- Improve planning, purchasing decisions, and overall operational efficiency


## Data Structure Overview:
### The delivery Schedule's data model is showed below. It highlights:
- The main fact table with its columns and data types
  
- Relationships to supporting tables

Data was cleaned and prepared using Microsoft Excel, Python scripts, and Power Query before analysis. 

<img width="1201" height="619" alt="image" src="https://github.com/user-attachments/assets/9fe98617-c894-4ce5-98ca-9a8b75d47fc6" />


## Executive Summary:
### Overview Page
This report visualizes key metrics to support strategic decision making across supply chain operations.

- **Purchase Cost Trends:** A line graph tracks total purchase costs and their monthly distribution, enabling quick identification of seasonal fluctuations and spending patterns

- **Order Distribution by Category:** The pie chart illustrates how the total purchase orders are split across different categories. This visual breakdown helps identify which categories are more popular than others

- **Supplier Distribution:** An interactive map highlights supplier locations, with tooltips displaying total orders and purchase costs per country, offering geographic insights into sourcing

- **Top 10 items by purchase cost:** The table is filtered to display the top 10 items ranked by highest total purchase cost. Metrics shown are total purchase cost, total individual orders and quantity in pallets
  
- **Kpi Cards Overview:**
  - Total Purchase Cost: £4.54M worth of items delivered into the warehouse
  
  - Total Orders: 563 individual purchase orders processed
  
  - Delivery Performance: 89.2% of orders arrived on time, while 10.8% were delayed

<img width="1148" height="652" alt="image" src="https://github.com/user-attachments/assets/c313ea6d-d111-4e72-8770-2de006364e37" />

### Supplier Page:

- Displays Minster insights using a slicer filter
- The pie chart shows the share of total purchase cost by product
- The bar chart highlights monthly pallet orders by product
- The table provides detailed information for further analysis

### Category Page:

- Focuses on the category chilled products
- KPI cards summarize purchase costs, total orders, & late/on-time deliveries
- The line and bar chart tracks monthly trends using orders and purchase costs

### Highlights
- Month-over-Month Purchase Cost Growth: +0.07%
  
- Month-over-Month Orders Growth: +0.05%
  
During the summer period, a dip in company sales led to reduced warehouse orders. As demand rebounded, franchisees responded with increased order volumes, driving a corresponding rise in purchase activity to replenish stock levels and restore operational momentum.

## Tech Stack:
The dashboard was built using the following tools:

- Microsoft Excel: Used for initial data collection
- Python: Data cleaning and extraction of unique tables into separate CSV files for analysis
- Power BI Desktop: Main platform for data visualization and reporting
- Power Query: Data transformation and preparation
- DAX (Data Analysis Expressions): Creation of KPIs and dynamic filters
- Data Modeling: Establishing relationships between tables for accurate filtering


## Personal Note:
- This project began as a simple visualization exercise, built from delivery data I collected during my time as a Logistics Assistant
- At the time, I was new to the role and used Microsoft Excel as a practical tool to store and organize delivery records
- As I gained experience and accumulated more data, I gradually introduced new features to enhance analysis and reporting
- While the dataset spans a short time period, the dashboard effectively demonstrates core reporting capabilities
