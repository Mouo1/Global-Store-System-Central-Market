# Global Store System (Central Market) - Data Management & Analysis Solution Project

## Project Overview
The **Global Store System (Central Market)**, is a comprehensive solution for managing and analyzing sales data, customer information, product catalog details, and order processing for a centralized market. This system is designed to streamline operations, support targeted marketing, enhance customer relationship management (CRM), and provide insightful analysis for data-driven decision-making.

The project is structured to fulfill key business requirements through a **data pipeline** involving an OLTP database schema, ETL processing with SSIS, data warehousing, and final analysis through SSAS, SSRS, and Power BI visualizations.

### Key Objectives
- Accurate sales tracking and order management
- Comprehensive customer information management
- Centralized and organized product catalog
- Efficient inventory and order processing management
- Robust analytical capabilities for sales, customer segmentation, and product performance

## Project Phases

### 1. Database Design and Implementation

#### Entity Relationship Diagram (ERD)
A detailed **ERD** was created to design and normalize the database to meet the various requirements for **Sales**, **Customers**, **Products**, and **Orders** schemas. The ERD outlines all entities, relationships, and primary/foreign keys necessary to organize and maintain data integrity.

#### OLTP Schema Creation
The **OLTP** schema was implemented in SQL Server. Key SQL queries and stored procedures were developed to support essential data handling and rule enforcement.
- **Sales**: Tracks transactions, including customer info, product details, quantities, prices, and timestamps.
- **Customers**: Manages customer profiles, contact info, demographics, and segmentation criteria.
- **Products**: Stores product catalog details and supports inventory management.
- **Orders**: Tracks order status, processing efficiency, and analytics.


### 2. Data Warehousing and ETL Processing

To consolidate transactional data for analytical purposes, an **ETL (Extract, Transform, Load)** process was implemented using **SSIS (SQL Server Integration Services)**:
- **ETL Processing**: Data from the OLTP database is cleansed, transformed, and loaded into a **centralized data warehouse**.
- **Data Warehouse Design**: The warehouse schema was optimized for OLAP (Online Analytical Processing) to support complex queries and analytics.


### 3. Analysis and Reporting

With data centralized in the warehouse, analysis and reporting were achieved through **SSAS (SQL Server Analysis Services)** and **SSRS (SQL Server Reporting Services)**:

### 4. Visualization

The final step involved creating interactive dashboards using **Power BI**:
- **Power BI Dashboard**: A comprehensive Power BI dashboard visualizes key metrics, including Sales , Products, Customers, and orders. This dashboard enables decision-makers to monitor and explore data visually.

## Links

### project presentation

For a detailed overview of this project, including visuals and workflows, you will find it in the [project presentation](https://www.canva.com/design/DAGRM45MfHo/uDlO_CXXwXb9-XSFldsf-A/view?utm_content=DAGRM45MfHo&utm_campaign=designshare&utm_medium=link&utm_source=editor).

