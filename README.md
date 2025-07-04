# Visual-Analytics-of-Loan-Behavior-and-Credit-Metrics
by Ishan

This Power BI dashboard was built to explore and analyze trends in a bank’s loan portfolio. It presents an interactive overview of loan status, borrower demographics, repayment behavior, and credit risk. The dashboard is designed for clarity, ease of use, and real-time data exploration, suitable for business analysts, interns, or decision-makers.

Objective
The goal of this dashboard is to provide a visual understanding of how factors such as income, debt-to-income ratio (DTI), verification status, loan purpose, and geographic location influence loan approval, repayment, and defaults. It highlights correlations and patterns using intuitive visual storytelling.

Dataset
The dataset consists of approximately 1,000 records from a bank loan dataset in CSV format. It includes key attributes such as:

Loan ID, status, issue date, and loan amount

Borrower annual income, interest rate, and DTI

Loan grade and sub-grade

Verification status, home ownership, and state

Purpose of the loan and total payments

Dashboard Features

KPI Cards: Highlighting total loans issued, total funded amount, payments received, average interest rate, and average DTI.

Time-Series Charts: Year-wise breakdown of loan statuses to analyze how loan performance changes over time.

Demographic Filters: Slicers for state, grade, purpose, and home ownership help explore specific borrower segments.

Risk Analysis: Visualization of DTI distribution and interest rates across credit grades to assess borrower risk profiles.

Loan Purpose Analysis: Breakdown of why borrowers apply for loans and how purpose correlates with approval or default.

Tools Used
Built entirely using Power BI Web on macOS, the dashboard leverages Power BI's online capabilities for real-time report design. DAX functions were used to create calculated metrics such as percentage-based KPIs and formatted values. The design includes a balance of visuals: bar charts, donut charts, KPI tiles, scatter plots, and tree maps.

Key Findings

Verified borrowers are less likely to default compared to unverified ones

DTI tends to rise in defaulted loans, indicating higher risk

Interest rates increase as credit grade decreases, reflecting risk-based pricing

Certain U.S. states show a higher concentration of charge-offs, suggesting regional credit challenges

Usage
This report was created as part of a data/analyst-focused internship portfolio. The original file is in .pbix format and is viewable using Power BI Desktop on Windows. The report can also be published and accessed via the Power BI Service for Mac users.

Personal Note
This project reflects an applied understanding of business intelligence, data storytelling, and dashboard design. It demonstrates the ability to convert raw financial data into actionable insights using modern BI tools.
