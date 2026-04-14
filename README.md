# Laon-Data-Analysis-Excel-dashboard-
This repository contains an Excel-based dashboard for analyzing loan repayment data. The project uses pivot tables and charts to visualize key metrics like loan status, repayment trends, and borrower demographics from the provided dataset

Dataset Overview
The dataset includes 500 loan records from September 2016, with columns such as LoanID, LoanStatus (PAIDOFF, COLLECTION, COLLECTIONPAIDOFF), Principal (mostly 1000), Terms (7-30 days), EffectiveDate, DueDate, Age (19-51), Education (High School or Below, college, Bechalor, Master or Above), and Gender. Total principal outstanding is around 471,600 across all records.

Key Insights
Loan statuses: 60% PAIDOFF (300 loans), 20% COLLECTION (100), 20% COLLECTIONPAIDOFF (100).

Gender split: 77 female (15.4%), 423 male (84.6%).

Education distribution: High School or Below (209 loans), college (220), Bechalor (67), Master or Above (4).

Average principal per loan: 943.2.

Dashboard Features
The Excel file has three sheets: Data (raw records), Pivot table (summaries by status, education, gender, dates), and Dashboard (visuals like pie charts for status, bar charts for principal by education, and timelines for paid-off dates). Use slicers for interactive filtering by date, gender, or education.

Technologies Used
Microsoft Excel (PivotTables, Charts, Slicers).

Suitable for data analysis portfolios; extendable to Power BI or Python (Pandas/Matplotlib) for advanced viz
