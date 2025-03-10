# SQL Data Warehouse using Medallion Architecture

## Project Description

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights.

## Data Architecture

The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
![data_architecture](https://github.com/user-attachments/assets/d7e665cf-6d83-41d1-9f17-ef7768f4dc10)
<ul>
<li>Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.</li>
<li>Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.</li>
<li>Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.</li>
</ul>

## Data Flow

![data_flow](https://github.com/user-attachments/assets/2592be80-3c9b-4d3b-9383-17ea91b43a4a)

## Stages

<ol>
<li>
Building Bronze Layer
<ul>
<li>Analyze Source Systems</li>
<li>Create DDL for Tables</li>
<li>Develop SQL Load Scripts</li>
<li>Create Stored Procedure</li>
</ul>
</li>
<li>
Building Silver Layer
<ul>
<li>Create DDL for Tables</li>
<li>Clean & Load crm_cust_info</li>
<li>Clean & Load crm_prd_info</li>
<li>Clean & Load crm_sales_details</li>
<li>Clean & Load erp_cust_az12</li>
<li>Clean & Load erp_loc_a101</li>
<li>Clean & Load erp_px_cat_g1v2</li>
<li>Create Stored Procedure</li>
</ul>
</li>
<li>
Building Gold Layer
<ul>
<li>Explore the Business Objects</li>
<li>Create Dimension Customers</li>
<li>Create Dimension Products</li>
<li>Create Fact Sales</li>
<li>Build The Star Schema Model</li>
</ul>
</li>
</ol>

## Data Integration

![data_integration](https://github.com/user-attachments/assets/6adfaf49-6bae-4b63-bac0-9423297b9ffe)

## Data Model

![data_model](https://github.com/user-attachments/assets/5d97e736-ed26-4da6-b615-06f4b88eea29)




