# Monthly Review: Credit Card Company Analysis with Power BI

This repository contains a Power BI presentation project that provides a monthly review of credit card sales data from a credit card company. The presentation includes revenue, collection, sales and withdrawal vs. collection analyses to provide insights and recommendations for the company's future strategy. The project includes the following components:

- A Power BI file that includes multiple visualizations and interactive dashboards.
- Monthly sample data files in Excel format, which contains the data used in the project.
- SQL query files that were used to retrieve the data.
- A README file that provides an overview of the project and instructions for using the Power BI file.
 
## Getting Started

To use the Power BI file, follow these steps:

1. Open the PBI_MonthlyReview.pbix file in Power BI desktop.
2. Refresh the data in the file by connecting to your own data source or updating the existing connection to the included sample data files.
3. Interact with the visualizations and dashboards to explore the data and insights. 

## Project Structure

The project is organized as follows:

Monthly Review: Credit Card Sales Analysis with Power BI and SQL Queries/
├── Sample Data/
│   ├── ActiveClients.xlsx
│   ├── AverageNewGrantedLimit.xlsx
│   ├── CollectedAllBuckets.xlsx
│   ├── CollectedBucket1.xlsx
│   ├── ConversionRateAffiliates.xlsx
│   ├── ConversionRateOnline.xlsx
│   ├── DelinquencyRate.xlsx
│   ├── NewActivatedClients.xlsx
│   ├── OverdueClients.xlsx
│   ├── ShareOfApprove.xlsx
│   ├── TotalClients.xlsx
│   ├── UtilisationRate.xlsx
│   └── АverageLimits.xlsx
├── MS SQL Server Queries/
│   ├── Accruals_ES.sql
│   ├── Approved_ES.sql
│   ├── Closed_Cards_ES.sql
│   ├── Collected_Amounts_ES.sql
│   ├── Total_Clients_With_PI_ES.sql
│   └── Withdrawal_Amounts_ES.sql
├── DAX Measures/
│   ├── AVGCharges.dax
│   ├── DelinquencyRate %.dax
│   ├── Limit Utilisation Rate %.dax
│   ├── NetCashGenerated.dax
│   ├── PY.dax
│   ├── TotalRevenue.dax
│   ├── YTD.dax
│   └── YoY Growth %.dax
├── Images/
│   ├── Main KPIs.jpg
│   ├── Additional KPIs.jpg
│   ├── Collected MDP by Buckets.jpg
│   ├── Overdue Dynamics.jpg
│   ├── Approved Clients.jpg
│   ├── Digital Channels.jpg
│   └── Collected vs. Withdrawal Amounts.jpg
├── CreditCardSalesMonthly.pbix
└── README.md

ExcelSources/: Folder containing the Excel sources used in the project.
MS SQL Server Queries/: Folder containing the MS SQL Server queries used to retrieve the data from the company's database.
DAX Measures/: Folder containing the DAX measures used in the project.
Images/: Folder containing the dashboards used in the project.
CreditCardSalesMonthly.pbix: Power BI file containing the visualizations and dashboards for the presentation.
README.md: This file, providing an overview of the project and instructions for use.

## Data Source
The data used in this project is entirely fictional and intended solely for demonstration purposes. The data represents a sample of credit card sales data from a credit card company over the course of two years.

## Monthly Review
Each month's review includes the following components:

1. Revenue Analysis: This section includes visualizations and analyses of revenue by accruals. Key insights can be obtained into the impact of accruals on the overall revenue of the credit card company. For example, if the penalty interest accruals are high, this may indicate a high delinquency rate among customers and the need for improved collections processes. Similarly, if the collection costs accruals are high, this may indicate that the company is incurring high costs associated with collecting payments from customers and the need for streamlining the collections process. 

2. Collection Analysis: This section includes visualizations and analyses of collections by region, payment type, and customer segment. Key insights from this section may include identifying regions with the highest and lowest collections, payment types that are most and least popular, and customer segments that have the highest and lowest collections.

3. Sales Analysis: This section includes visualizations and analyses of sales by product type, region, and customer segment. Key insights from this section may include identifying the most popular product types, regions with the highest and lowest sales, and customer segments that make the most and least purchases.
 
 
