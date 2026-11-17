# Sales Performance Analysis using Power BI
## Project Overview

This project analyzes sales performance data to identify trends in customer behavior, sales performance, shipping activity, regional performance, product demand, and target achievement. The project combines data preparation, report development, DAX calculations, KPI monitoring, and business intelligence reporting to support data-driven decision making.

Dataset Information

<img width="658" height="260" alt="image" src="https://github.com/user-attachments/assets/ac0107a6-fced-4dc7-8062-5c5fdf620d8c" />



## Business Questions

The reporting solution was developed to answer the following questions:

What is the total number of orders per segment?
What is the average number of orders per region?
What is the average sales value per region?
What are the total sales by category?
Which states generate the highest sales?
During which year and quarter were the most products sold?
How much does each customer segment contribute to total sales?
Which category sold the most units each year?
What are the most frequently used shipping methods?
Which state has the most customers?
What is the average quantity sold per state?
How do categories and sub-categories perform in terms of cost, quantity, and sales?
Is the business meeting its sales and quantity targets?

## Data Preparation
Before building reports, the dataset was reviewed and prepared for analysis.

Activities included:

Dataset inspection
Data transformation
Data cleaning
Removal of unnecessary columns
Ship Date
Country
Data type validation
Data loading into Power BI
Data quality assessment

## Additional Validation
The Sales Amount field was investigated using the Interquartile Range (IQR) method to identify potential outliers. A dedicated outlier classification field was created using DAX to enable comparisons between reports with and without suspected outliers.

## Report Development

A series of analytical reports were developed to evaluate:
Sales Performance
Sales by category
Sales by state
Sales by region
Sales contribution by segment

## Customer Analysis
Orders per segment
Customer distribution by state

## Product Performance
Units sold by category
Quantity sold by category and sub-category
Shipping Analysis
Shipping mode usage by year

## Target Analysis
Sales target achievement
Quantity target achievement
Performance against business thresholds

## Regional Analysis
Sales performance by region
Order distribution by region

# Key Findings
## Customer Segments

Consumer customers generated the highest number of orders, while segment contribution analysis revealed differences in sales contribution across customer groups.

## Regional Performance

Western and Eastern regions consistently appeared among the strongest-performing regions across multiple metrics.

## Product Categories

Technology generated the highest overall sales compared with Furniture and Office Supplies.

## Shipping Trends

Standard Class was consistently the most frequently used shipping mode across reporting periods.

## State Performance

Sales and customer concentration varied substantially across states, with several states contributing disproportionately to overall performance.

## Business Targets

The target-monitoring reports provided visibility into performance relative to minimum and target thresholds, enabling performance evaluation across reporting periods.

## Challenges and Limitations
## Sales Outliers

Potential outliers were identified within the Sales Amount field using the IQR method.

Because the dataset did not provide sufficient business context to determine whether these observations represented genuine business activity or data anomalies, no records were removed.

Instead, an outlier filter was implemented to support transparent analysis under different assumptions.

## Cost Interpretation

Limited business context was available regarding product pricing structures and cost calculations.

Additional stakeholder consultation would be required before making significant modifications to cost-related data or conclusions.

# Skills Demonstrated
## Business Intelligence
Power BI
KPI Development
Dashboard and Report Design
Business Reporting

## Data Preparation
Data Cleaning
Data Transformation
Data Validation
Outlier Analysis

### Data Modelling
DAX
Calculated Columns
Measures

## Analytics
Trend Analysis
Customer Analysis
Sales Analysis
Target Analysis
Performance Monitoring

## Deliverables
Interactive Power BI Reports
Executive Reporting Pages
KPI Performance Reports
Business Recommendations
Downloadable PDF Report

## Project Outcome

The project transformed transactional sales data into a comprehensive business intelligence reporting solution that enables stakeholders to monitor sales performance, customer behavior, shipping activity, product demand, and organizational performance against established targets. The resulting reports provide decision-makers with accessible and actionable insights to support strategic planning and operational improvement.
