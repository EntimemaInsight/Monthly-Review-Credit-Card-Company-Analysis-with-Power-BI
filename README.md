# Monthly Review: Credit Card Company Analysis with Power BI

This repository contains a Power BI presentation project that provides a monthly review of a credit card company. The presentation includes revenue, collection, sales and collection vs. withdrawal analyses to provide insights and recommendations for the company's future strategy. The project includes the following components:

- A Power BI file that includes multiple visualizations and interactive dashboards.
- Monthly sample data files in Excel format, which contains the data used in the project.
- SQL query files that were used to retrieve the data.
- A README file that provides an overview of the project and instructions for using the Power BI file.

## Usage
The data used in this project is entirely fictional and intended solely for demonstration purposes. The data represents a sample of credit card sales data from a credit card company over the course of two years.

 
## Getting Started

To use the Power BI file, follow these steps:

1. Open the PBI_MonthlyReview.pbix file in Power BI desktop.
2. Interact with the visualizations and dashboards to explore the data and insights. 

## Project Structure

The project is organized as follows:

Monthly Review: Credit Card Company Analysis with Power BI

I. ExcelSources:

 1. ActiveClients.xlsx
 2. AverageNewGrantedLimit.xlsx
 3. CollectedAllBuckets.xlsx
 4. CollectedBucket1.xlsx
 5. ConversionRateAffiliates.xlsx
 6. ConversionRateOnline.xlsx
 7. DelinquencyRate.xlsx
 8. NewActivatedClients.xlsx
 9. OverdueClients.xlsx
10. ShareOfApprove.xlsx
11. TotalClients.xlsx
12. UtilisationRate.xlsx
13. АverageLimits.xlsx

II. MS SQL Server Queries

 1. Accruals_ES.sql
 2. Approved_ES.sql
 3. Closed_Cards_ES.sql
 4. Collected_Amounts_ES.sql
 5. Total_Clients_With_PI_ES.sql
 6. Withdrawal_Amounts_ES.sql

III. DAX Measures

 1. AVGCharges.dax
 2. DelinquencyRate %.dax
 3. Limit Utilisation Rate %.dax
 4. NetCashGenerated.dax
 5. PY.dax
 6. TotalRevenue.dax
 7. YTD.dax
 8. YoY Growth %.dax

IV. Images

 1. Main KPIs.jpg
 2. Additional KPIs.jpg
 3. Collected MDP by Buckets.jpg
 4. Overdue Dynamics.jpg
 5. Approved Clients.jpg
 6. Digital Channels.jpg
 7. Collected vs. Withdrawal Amounts.jpg
 8. CreditCardSalesMonthly.pbix

V. README.md

ExcelSources/: Folder containing the Excel sources used in the project.
MS SQL Server Queries/: Folder containing the MS SQL Server queries used to retrieve the data from the company's database.
DAX Measures/: Folder containing the DAX measures used in the project.
Images/: Folder containing the dashboards used in the project.
CreditCardSalesMonthly.pbix: Power BI file containing the visualizations and dashboards for the presentation.
README.md: This file, providing an overview of the project and instructions for use.

## Key Insights
Each month's review includes the following components/key insights:

1. Revenue Analysis: 
   This section includes visualizations and analyses of revenue by accruals. Key insights can be obtained into the impact of accruals on the overall revenue of the credit card company. For example, if the penalty interest accruals are high, this may indicate a high delinquency rate among customers and the need for improved collections processes. Similarly, if the collection costs accruals are high, this may indicate that the company is incurring high costs associated with collecting payments from customers and the need for streamlining the collections process. 

2. Collection Analysis: 
   The Collection Analysis section of the monthly review includes visualizations and analyses of the credit card company's collection processes. The section includes analyses of collection by bucket and overdue clients structure. By analyzing collection by bucket, key insights can be obtained into the company's collection processes and effectiveness. For example, the analysis may identify which buckets have the highest and lowest collection rates, enabling the company to focus on improving collections in the least effective areas. Similarly, analyzing overdue clients structure can provide insights into the effectiveness of the company's collections processes. For example, if the analysis identifies a high proportion of clients that are frequently overdue, this may indicate that the company needs to improve its collections processes and reduce the delinquency rate.

3. Sales Analysis: 
   The Sales Analysis section of the monthly review includes visualizations and analyses of the credit card company's sales performance, including insights into approved/new activated clients and digital channels.
   By analyzing approved clients, key insights can be obtained into the company's credit approval process and effectiveness. For example, the analysis may identify which customer segments have the highest and lowest approval rates, enabling the company to optimize its credit approval process. Similarly, analyzing new activated clients can provide insights into the effectiveness of the company's sales processes. For example, if the analysis identifies a high proportion of new clients who do not activate their cards, this may indicate that the company needs to improve its onboarding process.
   Analyzing digital channels, such as conversion rates by affiliates and online channels, can provide insights into the effectiveness of the company's digital marketing and sales strategies. For example, if the analysis identifies a low conversion rate for a particular affiliate or online channel, the company can optimize its marketing and sales strategies for that channel.   
   
4. Collected vs. Withdrawal Analysis:
   The Collected vs. Withdrawal Analysis section of the monthly review includes visualizations and analyses of the credit card company's cash flow, including insights into collected amount, withdrawal amount, and net cash generated. 
   By analyzing collected amounts, key insights can be obtained into the effectiveness of the company's collections processes. For example, the analysis may identify which payment methods or customer segments have the highest and lowest collection rates, enabling the company to optimize its collections processes.
   Similarly, analyzing withdrawal amounts can provide insights into the effectiveness of the company's credit extension processes. For example, if the analysis identifies a high proportion of clients who withdraw cash, this may indicate that the company needs to improve its credit extension processes and reduce the risk of defaults.
   Analyzing net cash generated can provide insights into the company's overall cash flow and profitability. For example, if the analysis identifies a negative net cash generated for a particular period, the company can take steps to improve its cash flow and profitability.
   

## Credits

This project was created by Aleksandar Dimitrov and is licensed under the MIT License. 
If you have any questions or comments, feel free to contact me at alexi.zein@gmail.com.
