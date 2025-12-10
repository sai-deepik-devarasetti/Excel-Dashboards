Coffee Shop Sales Analysis – Excel BI Project
Overview

This repository contains an end-to-end Excel Business Intelligence project developed to analyze sales, customer footfall, product performance, and operational trends for a multi-location coffee shop chain. The dataset was sourced from the Maven Analytics Playground and processed using Excel’s advanced BI capabilities, including Power Query, Power Pivot, Data Modeling, DAX Measures, and interactive charts.

The final output is a fully interactive Excel dashboard designed for business decision-making.

Key Functionalities
Data Preparation

Performed data cleaning and shaping using Power Query.

Standardized field types, removed duplicates, fixed format inconsistencies, and prepared lookup dimensions.

Loaded all tables into the Excel Data Model for optimized performance.

Data Modeling

Built a relational data model using Power Pivot.

Created relationships across fact and dimension tables (e.g., Date, Product, Store, Orders).

Defined calculated columns and a structured model to support downstream analysis.

Measures (DAX)

Developed a suite of DAX Measures, including:

Total Sales

Total Footfall

Average Bill per Person

Average Orders per Person

Order Count

Product-Level Sales Measures

Size Distribution Percentages

Visualization & Dashboard

Created an interactive Excel dashboard including:

Line chart showing quantity ordered by hour

Pie chart representing category-level sales distribution

Donut chart showing size distribution of orders

Bar charts for:

Weekday performance

Store-level footfall and sales

Top product sales

Slicers for Month and Day dimensions enabling dynamic filtering

KPI cards showing Total Sales, Total Footfall, Average Bill per Person, and Average Orders per Person

Insights Generated

Coffee and Coffee Beans are the highest-revenue categories.

Weekdays show higher order volumes, with notable peaks from Monday to Friday.

Astoria and Hell’s Kitchen stores lead in both footfall and sales revenue.

Regular and Large sizes contribute the largest share of orders.

Evening hours show increased ordering behavior.

Tools and Technologies
Tool	Purpose
Microsoft Excel	Dashboarding and reporting
Power Query	Data cleaning and transformation
Power Pivot	Data modeling and relationships
DAX	Custom measures and KPIs
Excel Charts & Slicers	Visualization and interactivity
Dataset

This project uses the publicly available dataset from Maven Analytics Playground (Coffee Shop dataset). It includes tables for:

Transactions

Products

Store Locations

Date and Time fields

Customer footfall

Project Structure
Coffee-Shop-Sales-Analysis/
│── CoffeeShop_Dashboard.xlsx
│── README.md
│── dashboard.png
└── dataset_source.txt

How to Use

Download the Excel file from this repository.

Open it using Microsoft Excel (Office 365 or Excel 2019 recommended).

Use the slicers to filter the dashboard by Month and Day.

Review KPIs and charts to explore sales and operational insights.

Skills Demonstrated

Data Cleaning and Shaping

Power Query M Transformations

Data Modeling with Power Pivot

DAX Calculations

Business Analytics

Dashboard Design and Storytelling

Excel BI Workflow Development

Future Enhancements

Introduction of trend forecasting features.

Inclusion of external data sources (promotions, weather, customer segmentation).

Migration of the dashboard to Power BI for enhanced analytics capability.

Automation of refresh cycles using Power Automate.
