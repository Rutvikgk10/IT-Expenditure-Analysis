# IT-Expenditure-Analysis
📌 Project Overview

This project focuses on analyzing IT expenditure across different business areas, regions, and cost categories using Power BI. The objective is to build an interactive dashboard that provides visibility into Actual vs Forecast vs Planned IT costs, helping organizations monitor budget alignment and identify areas of overspending or underutilization.

The dashboard transforms raw financial data into actionable business insights to support strategic budgeting and operational accountability.

🎯 Business Objective

Organizations often struggle to track IT spending efficiently across departments and regions. This project aims to:

Analyze how IT costs are distributed across regions and business units

Compare Actual, Forecasted, and Planned IT expenditures

Identify cost drivers such as Internal Labor and Shared Services

Detect budget variances and financial inefficiencies

Support better financial decision-making

🗂 Dataset Description

The dataset consists of two sheets:

Data – Contains actual IT expenditure data

Future Data – Contains forecasted and planned expenditure data

Key Fields:

Region

IT Area

Business Unit

Cost Element Group

Actual

Plan

Forecast

Date (Month-based values such as Jan, Feb, etc.)

🧹 Data Preparation

The following data transformation steps were performed in Power BI:

Loaded both sheets into Power Query

Standardized column names

Converted month text values into proper Date format

Replaced null values with zero to avoid calculation errors

Appended both sheets into a single unified dataset

Created a separate Date Table

Established proper relationships using a star schema model

This ensured accurate time-based analysis and efficient data modeling.

🧮 Data Modeling & DAX Measures

To support dynamic analysis, the following DAX measures were created:

Total Actual

Total Plan

Total Forecast

Actual vs Plan Variance

Variance Percentage

These measures allow dynamic filtering by region, department, or month.

📈 Dashboard Structure

The Power BI report consists of three main pages:

1️⃣ Executive Overview

KPI Cards (Total Actual, Plan, Forecast, Variance %)

Monthly Spend Comparison (Actual vs Plan)

Cost Distribution by Cost Element Group

Interactive slicers (Region, IT Area, Business Unit, Month)

2️⃣ Regional & Department Analysis

Region-wise IT Spend comparison

Variance matrix with conditional formatting

Forecast vs Plan comparison by IT Area

3️⃣ Cost Driver Analysis

Tree map for cost element contribution

Stacked column chart for monthly cost composition

Line chart for IT spending trend analysis

🔍 Key Insights

Certain regions show consistent overspending against planned budgets

Shared Services and Internal Labor are major cost drivers

Some business units underutilize allocated budgets

Forecast deviations indicate potential planning inaccuracies

These insights support cost optimization and improved budgeting strategies.

💡 Business Recommendations

Implement monthly variance monitoring

Review high-variance regions quarterly

Optimize shared services contracts

Improve forecasting accuracy using historical trends

Introduce accountability reporting for departments

🛠 Tools & Technologies Used

Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

Excel (Data Source)

📊 Key Features

Interactive filtering and drill-down capabilities

Clean star schema data model

Conditional formatting for variance visibility

Professional corporate dashboard layout

Scalable and reusable data model

🚀 Outcome

This project demonstrates how financial data can be transformed into a decision-support system using Power BI. The dashboard provides transparency, highlights inefficiencies, and enables data-driven budgeting decisions.

📂 Repository Structure
IT-Expenditure-Analysis/
│
├── IT Expenditure.pbix
├── Dataset.xlsx
└── README.md

👤 Author

Rutvik Kajrekar
Business Analytics
