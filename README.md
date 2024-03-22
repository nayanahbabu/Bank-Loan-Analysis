# Bank Loan Analysis Project
This project focuses on analyzing the performance of loans provided by a bank throughout the year 2021. The analysis is conducted using MS SQL and Power BI tools.

## Data Source
The dataset used for this analysis is a flat file named financial_loan.csv. This file contains financial information related to loans and serves as the primary source for the analysis. The flat file is loaded into an MS SQL database named Bank Loan DB, and a table named dbo.bank_loan_data is created within this database to store the loan data.

## Tools Used
MS SQL Server Management Studio 19: Used for managing the SQL database, loading data, and running SQL queries.

Power BI Desktop: Utilized for creating visualizations and dashboards based on the loan data.

## Analysis Process
Data Preparation: The financial_loan.csv file is loaded into the Bank Loan DB, and a corresponding table is created to store the loan data.

SQL Queries: Various SQL queries are executed to analyze the loan data and derive insights. These queries are documented in the SQLQuery1.sql file and further detailed in the BANK LOAN REPORT QUERY DOCUMENT.docx document.

Visualization: The insights obtained from the SQL analysis are visualized using Power BI Desktop. The visualization dashboards are stored in the bank_loan.pbix file.

## Visualization Dashboards
The Power BI visualization dashboards consist of three main views:

1. Summary: Provides a high-level overview of the loan performance metrics.
2. Overview: Offers a comprehensive view of the key performance indicators (KPIs) and trends.
3. Details: Allows for a deeper dive into specific loan data and metrics.
   
Each dashboard prominently displays the top five KPIs to provide immediate insights to the viewer.

## Usage
To view the visualization dashboards and explore the loan analysis:

Ensure you have Power BI Desktop installed on your system.

Open the bank_loan.pbix file using Power BI Desktop.

Explore the different dashboards and visualizations to gain insights into the bank loan performance.

## Contributors
Nayana Harindra Babu

## License
This project is licensed under the MIT License.
