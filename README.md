# Financial-Analysis
# 🚀 Data Analytics Project: Comprehensive Business Insights  

## Overview  
This repository showcases a financial analysis extracted to derive meaningful insights into a company's day-to-day activities. The project involves analyzing a relational database comprising **10 interconnected tables** using **Power Query**, **Data Modeling**, **DAX**, and **Power BI** for visualization.  

## 📚 Database Design  
The database was designed to capture key aspects of business operations, facilitating a comprehensive analysis. Below is an overview of the datasets used:  

- **AccountHolder**: Information on individuals or entities holding accounts within the organization.  
- **Account**: Details of financial accounts, including types and associated balances.  
- **Customers**: Demographic and segmentation data about the organization's customers.  
- **DepartmentGroup**: Hierarchical categorization of departments across the organization.  
- **FactTable**: A central table holding transactional and aggregated data for analysis.  
- **Finance**: Financial metrics such as income, expenditure, and profit details.  
- **Organization**: Structural details of the organization, including divisions and regions.  
- **Product Cost**: Information on the costs associated with products.  
- **Products**: Details of the organization's products, including categories and pricing.  
- **Returns**: Data related to product returns, including reasons and volumes.  

## 🔗 Data Modeling  
A **galaxy schema** (or fact constellation schema) was employed to support complex queries and analyses across multiple business processes.  

### Key Aspects of the Schema Design  
- **Three fact tables**: `FactTable`, `Finance`, and `Returns` are connected via a shared **Date table**, enabling cohesive time-based analysis.  
- **Shared dimension tables**: `Products` and `Customers` are used by multiple fact tables to provide a unified view of key attributes across datasets.  
- **Granularity**: Ensured accurate granularity for transactional data across all fact tables.  
- **Normalization**: Dimension tables were normalized to reduce redundancy and improve data integrity.  
- **Advanced DAX**: Calculated columns and measures were implemented to derive insights efficiently.  

## 🛠 Tools and Technologies  
- **Power Query**: Used for cleaning, transforming, and preparing raw data.  
- **Data Modeling**: Applied to define relationships and optimize the database structure using the galaxy schema approach.  
- **DAX (Data Analysis Expressions)**: Utilized for creating dynamic calculations and aggregations.  
- **Power BI**: Leveraged to build interactive dashboards and visualize insights effectively.  

## 📈 Key Findings  
This project delivered valuable insights into various aspects of the business:  

- **Operational Efficiency**: Identified bottlenecks in inventory management and order processing.  
- **Revenue Trends**: Highlighted top-performing products and seasonal sales patterns.  
- **Customer Behavior**: Provided segmentation insights, improving targeted marketing efforts.  
- **Financial Insights**: Revealed cost-to-revenue ratios and areas for expense optimization.  
- **Return Analysis**: Analyzed trends in product returns, leading to actionable recommendations for quality improvement.  

## 🤝 Collaboration  
This repository is open for exploration, feedback, and contributions. Dive into the Power BI dashboards and data models to uncover more insights!  
