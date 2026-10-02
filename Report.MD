# Logistics Operations <br> Analysis - Power BI

# TS Academy Data Analytics — Capstone Project

### Author: Stella Kabari Solomon <br> Role: Data Analyst <br> Tools Used: Power BI Desktop, Microsoft Excel <br> Dataset: 85K+ records

# Executive Summary
<h3> This repository contains my end-to-end Data Analytics Capstone Project completed as part of the TS Academy Data Analytics Certification. As the Data Analyst, I was responsible for transforming a complex logistics operations dataset into actionable business insights. The project covered the complete analytics workflow from data cleaning and transformation to data modeling, DAX development, visualization and business recommendations.</h3> 

<h3> Using Power BI as the primary analytics and visualization platform, I analyzed an 85K+ row logistics dataset to identify operational bottlenecks, evaluate revenue and cost drivers, assess fleet and driver performance, and uncover areas of supply chain inefficiency. The analysis revealed a logistics operation with a 65% gross profit margin, but also highlighted significant capacity utilization, service-level, fleet productivity and driver-retention challenges that could affect overall operational performance.</h3> 

# Business Challenges:
<h3> The logistics company had access to large volumes of operational data but lacked a consolidated analytical framework for understanding its key performance drives. For this purpose, the Management needed data-driven answers to critical questions such as:</h3> 

<h3> a. Which routes generate the most revenue, and what are the associated costs by lane? <br>
b. Which drivers are associated with higher delivery times and safety-related costs? <br>
c. Which customers generate the most revenue? <br>
d. Where are the largest operational inefficiencies occurring? <br>
e. How much potential revenue is being lost through underutilized capacity? <br>
f. How can management use data to improve fleet productivity and profitability? </h3> 
The objective was to transform fragmented operational data into structured and interactive insights that could support better business decision-making.</h3> 

# Key Focus
<br> The analysis identified several important operational performance indicators as follows: <br> KPI Result 
<h3> a. Realized Revenue - $298.62M  <br> b. Potential Capacity Revenue - $538M <br> c. Gross Profit Margin - 65% <br> d. SLA / On-Time Delivery Rate - 56% <br> e. Delayed Deliveries - 44% <br> f. Non-Productive Idle Hours - 598.79K <br> g. Driver Turnover Rate - 17.3% <br> h. Terminated Drivers - 26 of 150 </h3> 

# What the numbers indicate
<h3> Despite a strong 65% gross profit margin, the business has substantial room to improve operational efficiency. The gap between $298.62M in realized revenue and $538M in potential capacity revenue highlights significant unused revenue potential. Also, the 56% service level performance also indicates that nearly half of deliveries were delayed, creating a potential risk to customer satisfaction and operational reliability. Furthermore, 598.79K non productive idle hours represent substantial asset time that was not contributing directly to productive operations.</h3> 

# Data Overview And Preparation
<h3> The project utilized multiple interconnected datasets covering different areas of the logistics operation.</h3> 

# Datasets Used:
### Dataset Description
<h3> a. Drivers Driver demographics, employment history and license information <br>
b. Customers Customer accounts, contract types, and revenue potential <br>
c. Trucks Fleet equipment, acquisition information, and operational status <br>
d. Trailers Trailer inventory, types and status <br>
e. Facilities Terminal and warehouse locations and capacity <br>
f. Routes Origin-destination pairs, distances, and rate structures <br>
g. Loads Shipment details, revenue, and booking types <br>
h. Trips Actual trip performance, fuel consumption, and duration <br>
i. Fuel Purchases Fuel transactions, prices, and purchase locations <br>
j. Maintenance Records Service history, maintenance costs, and downtime <br>
k. Delivery Events Pickup and delivery activity <br>
l. Driver Monthly Metrics Aggregated driver performance and utilization metrics <br>
m. Truck Utilization Metrics Aggregated fleet utilization metrics <br>
n. Safety Incidents Driver and operational safety incidents <br>
o. Data Preparation & Cleaning <br>
q. Before analysis, the datasets underwent several preparation and transformation steps to ensure consistency and analytical reliability. </h3> 

# Key Preparation Steps
<h3> * Removed duplicate records <br>
* Standardized inconsistent data formats <br>
* Validated and corrected data types <br>
* Cleaned and segmented numerical fields <br>
* Identified and handled data inconsistencies <br>
* Created calculated columns <br>
* Established consistent naming conventions <br>
* Prepared datasets for relational modeling <br>
* Created aggregated operational metrics where required <br>
* The resulting datasets provided a clean and structured foundation for analysis, modeling, and dashboard development.</h3> 

# Data Modeling
<h3> A star schema was designed to support efficient analysis and cross-filtering across the logistics ecosystem. The model consisted of central fact tables supported by multiple dimension and operational tables.

## Core Tables
<h3> 1. Trips <br>
2. Loads <br>
3. Delivery Events <br>
4. Dimension & Supporting Tables <br>
5. Customers <br>
6. Trailers <br>
7. Trucks <br>
8. Drivers <br>
9. Routes <br>
10. Fuel Purchases <br>
11. Maintenance Records <br>
12. Driver Monthly Metrics <br>
13. Truck Utilization Metrics <br>
14. Safety Incidents </h3>
    
# DAX & Business Intelligence
<h3> Custom DAX measures were developed to create reusable business metrics and support interactive dashboard analysis:</h3>
<h3> * Anchor Metrics <br>
* Total Revenue <br>
* Operating Cost <br>
* Average Order Value <br>
* Conversion Rate <br>
* Total Miles <br>
* Fleet Trip MPG <br>
* Average Maintenance Downtime Hours <br>
* Average Fuel Cost </h3> 

# Additional measures were created to evaluate:
<h3> * Revenue performance <br>
* Route profitability <br>
* Fleet utilization <br>
* Delivery performance <br>
* Driver performance <br>
* Fuel efficiency <br>
* Maintenance impact <br>
* Capacity utilization <br>
* Safety performance <br>
* Customer contribution <br>
All these measures allowed management to move beyond descriptive reporting and explore the operational drivers behind business performance.</h3> 

# Power BI Dashboard
<h3> The final Power BI solution was designed to provide management with an interactive view of the company's logistics operations.

# Dashboard Areas
<h3> The analysis focused on;

* Executive Performance <br>
* Revenue & Profitability <br>
* Route & Lane Analysis <br>
* Customer Performance <br>
* Driver Performance <br>
* Fleet Utilization <br>
* Fuel Efficiency <br>
* Maintenance <br>
* Delivery & SLA Performance <br>
* Safety Metrics <br>
* Tools & Technologies </h3> 

# Tool - Purpose
<h3> a. Power BI - Data modeling, DAX, visualization and dashboard development <br> b. DAX - Business calculations and KPI development  <br> c. Power Query - Data cleaning and transformation  <br> d. Excel / CSV - Data sources and preliminary data inspection  <br> e. Data Modeling - Relational modeling and analytical architecture </h3> 

# Project Context
<h3> This project was completed as the Data Analytics Capstone Project for TS Academy Certification. It provided an opportunity to apply practical data analytics techniques to a complex business scenario, including data cleaning, Data transformation, Exploratory data analysis, Data modeling, DAX development, KPI development, Business intelligence, Dashboard design, Operational analysis and Data-driven recommendations.</h3> 

<h3> This project represents my ability to transform complex operational data into structured insights that can support business analysis and decision-making.
If you find this project useful, Feel free to explore the repository, review the dashboard, and connect with me to discuss data analytics, business intelligence, Power BI and data-driven decision-making. </h3> 

