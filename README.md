# Bingo-Sales-Data-Analysis-Project

## Overview
This project involves analyzing retail sales data collected monthly from February to May. The analysis includes data cleaning, transformation, and visualization using Excel, SQL Server, SSIS, and Power BI.

## Data Sources
- **Sales**: Contains transaction data.
- **Products**: Contains product information.
- **Reps**: Contains sales representative information.
- **Stores**: Contains store information.


## Tasks and Solutions

### Excel
1- **Data Cleaning**: Using Power Query
1- **Data Lookups**: Added new sheets with lookups for each ID with related information.
2- **Calculations**: Uning Pivot Tables
- Top 20 Products by Sales.
- Top 10 Reps by Order Count.
- Top & Worst 10 Brands by Value.
- Rank Months in Each Store.
- Rank Reps in Each Store.
- Rank Products in Each Brand.


## SQL Server and SSIS
1- **Star Schema**: Created a star schema for the data.
2- **ETL Pipelines**: Developed ETL pipelines using SSIS to populate the cleaned data into the Data Warehouse (DWH).
![Screenshot 2023-12-14 003352](https://github.com/user-attachments/assets/30f3ded1-cfcd-405e-a285-11ef2ec63f40)
![Screenshot 2023-12-13 205949](https://github.com/user-attachments/assets/92d27a37-8bab-470c-99f3-a80ad57cf94b)


## Power BI
- **Dashboard**: Connected to the DWH and created a descriptive analysis dashboard, focusing on design and usability. [here](https://app.powerbi.com/view?r=eyJrIjoiMjI5NTZkNWUtMmJjMy00ZThkLThhNzQtMDAxMDRmOTE2OTEzIiwidCI6ImQxZjQ1MDM5LTJhNDQtNDAwNy1hZDViLTM3NjEyNWI0N2Q1YiJ9)


## Presentation
- **Process Explanation**: Provided a brief presentation explaining the thought process and work during the task.


## Deliverables
- Cleaned Excel Workbook.
- Backup file from the DWH.
- SSIS solution folder.
- Power BI Dashboard file.
- Presentation file (including snapshots of the star schema and SSIS pipelines).
