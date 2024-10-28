# HR Analytics

This project is a Power BI case study designed to create an interactive report for Atlas Labs, a fictitious tech company, focusing on employee performance metrics and attrition factors. The project provides the Atlas Labs HR team with key insights into employee performance ratings and aims to highlight factors impacting employee turnover.

Using a Kimball modeling approach with a snowflake schema, the data model consists of one fact table and multiple dimension tables:

Fact Table: The central table, Performance Ratings, captures employee performance reviews, providing essential data for HR performance management. It includes 11 columns and supports multiple review records per employee.

Dimension Tables: Five dimension tables add context to the fact table, answering the “who, what, when, where, and why” of the data:
Employee
EducationLevel
RatingLevel
SatisfiedLevel
Date (future addition, detailing year, quarter, month, and day)

This report development project is a demonstration of data modeling in Power BI, with a focus on creating a structured, insightful dashboard for employee monitoring and decision-making.
