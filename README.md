# Pewlett Hackard Analysis

## Overview Of Analysis

This analysis involved creating database designs, table management, and SQL statements to explore company data and help find answers to retirement questions. Postgres and PgAdmin were used for SQL analysis.

## Results
- The number of retirement-age employees for the company is 90,398.
- Majority of the types of employees that will be retiring soon are Senior Engineers and Senior Staff.
- The number of employees who are eligible to participate in the mentorship program is 1549.
- All the employees who are eligible to participate in the mentorship program are Senior Engineers

![image](Resources/image.png)

## Summary
In all the analysis answered questions regarding who was eligible for retirement and how many. Employees that are eligible for retirement include 29414 Senior Engineers, 28254 Senior Staff, 14222 Engineers, 12243 Staff, 4502 Technique Leaders, 1761 Assistant Engineers, and 2 Managers (as we can see in the image of the table from the results section. Since the number of retirement ready engineers is 29414 and there are 1549 participants, there are enough qualified retirement-ready employees to mentor the next generation. Additional queries that can provide more insight includes finding out why there are significantly less managers who are retirement ready as well as playing with the birth date constraints within our queries to see if a more even distribution of retirement-ready employees can be obtained.
