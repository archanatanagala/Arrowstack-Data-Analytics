# ARROWSTACK DATA ANALYTICS INTERNSHIP

# SALES PERFORMANCE DASHBOARD USING POWER BI

## 1. Project Overview

The Sales Performance Dashboard is a data analytics project developed using Microsoft Power BI. The purpose of this project is to analyze e-commerce sales performance, understand customer purchasing behavior, identify high-performing product categories, and evaluate marketing lead conversion.

The dashboard presents key performance indicators (KPIs), interactive charts, and slicers to help users explore sales and marketing data and make data-driven decisions.

## 2. Project Objectives

* Analyze overall e-commerce sales performance.
* Calculate total revenue, average order value, and total orders.
* Identify product categories contributing to revenue.
* Analyze revenue across customer states.
* Understand payment method distribution.
* Examine marketing leads and closed deals.
* Calculate and display the marketing lead conversion rate.
* Build an interactive and user-friendly Power BI dashboard.

## 3. Tools and Technologies

* Microsoft Power BI Desktop
* Power Query Editor
* DAX (Data Analysis Expressions)
* Microsoft Excel / CSV datasets
* Data visualization and exploratory data analysis

## 4. Datasets Used

### A. Brazilian E-Commerce Public Dataset by Olist

Source:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

This dataset contains information about e-commerce orders, order items, customers, products, and payment records.

Tables used include:

* Orders
* Order Items
* Customers
* Products
* Order Payments

### B. Marketing Funnel by Olist

Source:
https://www.kaggle.com/datasets/olistbr/marketing-funnel-olist

This dataset contains information about marketing qualified leads and closed deals.

The e-commerce dataset and marketing funnel dataset are analyzed separately because a verified relationship between marketing leads and e-commerce orders has not been established.

## 5. Project Methodology

### Step 1: Data Import

Imported the relevant Olist CSV datasets into Microsoft Power BI Desktop.

### Step 2: Data Cleaning

Used Power Query Editor to inspect data quality, review missing values, check data types, and identify duplicate keys.

Missing product categories and marketing lead origins were replaced with "Unknown".

Valid repeated order item and payment records were retained because multiple records per order can be legitimate.

### Step 3: Data Modeling

Created relationships between relevant sales tables using their corresponding keys, including order ID, customer ID, and product ID.

Connected Marketing Qualified Leads and Closed Deals using mql_id.

### Step 4: DAX Measures

Created measures for the key performance indicators:

* Total Revenue
* Average Order Value
* Total Orders
* Total Leads
* Converted Leads
* Conversion Rate

### Step 5: Dashboard Development

Created KPI cards, charts, and slicers to make the report interactive and easier to understand.

### Step 6: Validation

Checked selected data quality results, duplicate keys, data types, relationships, KPI cards, charts, and slicer interactions.

## 6. Key Performance Indicators

### Total Revenue

Calculated by summing order item prices. Freight charges are excluded from this measure.

### Average Order Value

Calculated by dividing total revenue by the distinct number of orders.

### Total Orders

Calculated as the distinct count of order IDs.

### Total Leads

Calculated as the distinct count of marketing qualified lead IDs.

### Converted Leads

Calculated as the distinct count of lead IDs in the closed deals dataset.

### Conversion Rate

Calculated by dividing converted leads by total leads.

Note: The conversion rate represents marketing funnel conversion based on the available marketing data. It should not be interpreted as the percentage of marketing leads that became e-commerce orders.

## 7. Dashboard Visualizations

The dashboard includes the following visualizations:

1. KPI cards for key sales and marketing metrics.
2. Monthly Revenue Trend to examine revenue over time.
3. Sales by Product Category to compare category performance.
4. Revenue by Customer State to analyze regional sales.
5. Payment Method Analysis to understand payment distribution.
6. Marketing Funnel Analysis to examine leads, closed deals, and conversion rate.

## 8. Interactive Filters

The dashboard includes the following slicers:

* Order Date
* Product Category
* Customer State
* Payment Method

These slicers allow users to explore the relevant sales data based on their selections.

Marketing funnel visuals remain separate from sales filters unless a valid relationship is established.

## 9. Business Applications

This dashboard can help businesses:

* Monitor sales performance.
* Compare product category revenue.
* Identify states contributing to sales.
* Understand customer payment preferences.
* Track marketing lead conversion.
* Support data-driven business decisions.

## 10. Expected Learning Outcomes

Through this project, I gained practical experience in:

* Importing datasets into Power BI.
* Cleaning data using Power Query.
* Understanding data relationships and data modeling.
* Creating DAX measures.
* Developing KPI cards and interactive charts.
* Testing slicers and report interactions.
* Presenting data in a clear dashboard format.
* Maintaining data validation documentation.

## 11. Project Deliverables

* Power BI dashboard file (.pbix).
* README documentation.
* Data validation log.
* Dashboard screenshot.

## 12. Conclusion

The Sales Performance Dashboard demonstrates the use of Microsoft Power BI for e-commerce sales analysis and marketing funnel reporting. It combines key performance indicators, charts, and interactive filters to present business data in an accessible format.

The project provides practical experience in data cleaning, data modeling, DAX calculations, visualization, and validation. By keeping sales and marketing funnel results separate where a verified connection is unavailable, the dashboard avoids unsupported conclusions and promotes reliable analysis.

## 13. Author

Name: T Archana

Project: Sales Performance Dashboard

Internship: Arrowstack Data Analytics Internship

Domain: Data Analytics

Tools: Microsoft Power BI, Power Query, DAX
