# Pewlett-Hackard Analysis
Using SQL.
## Overview of Pewlett-Hackard Analysis
We are doing employee research for ""Pewlett-Hackard", a large company looking to the future as many employees will be retiring soon. They want information on the number of employees retiring per department to plan for retirement packages, filling positions, and offering mentorship programs. We will be retrieving data from CSV files to create a database with SQL to perform analysis. Specifically, we are asked to determine the number of employees retiring per title and which employees are eligible to participate in a mentorship program. 
## Pewlett-Hackard Results
**Number of Retiring Employees by Title:**
  - The chart below lists the number of employees eligible for retirement per title. There are more senior engineers ready for retirement than any other category. Only two managers will need to be replaced. 
  - Before filtering to remove duplicate employees from the retirement_titles table there were 133,776 employee entrees. In the unique_titles table we filtered to show only the most recent title for each employee and only employees still with the company. There were then 72,458 entrees, meaning there are a total of 72,458 employees eligible for retirement.

![retiring_per_department.png](https://raw.githubusercontent.com/LaurenDebes/Pewlett-Hackard-Analysis/main/retiring_per_department.png)

**Employees Eligible for the Mentorship Program:**
  - There are a total of just 1,549 employees meeting the conditions for the mentorship program. 
  - When compared to the number eligible for retirement, the number eligible for the mentorship program is only 2% of the positions needing to be filled following the "silver tsunami".
 
## Summary
A total of 72,458 roles will need to be filled. Excluding those eligible for retirement, these are the current numbers in each of the departments and the code used to find the totals:

![other_totals_table.png](https://raw.githubusercontent.com/LaurenDebes/Pewlett-Hackard-Analysis/main/other_totals_table.png)
![other_totals.png](https://raw.githubusercontent.com/LaurenDebes/Pewlett-Hackard-Analysis/main/other_totals.png)

There are a total of 240,124 employees, so 32% of the employees at the company will be eligible for retirement. 
There are definitely enough retirement-ready employees ready to mentor the next generation. The youngest person at the company was born in February of 1965, making them 57 years old. They will be eligible for retirement soon as well. For the mentorship program, if only using current employees, the age range would need to extend from just those born in 1965 to those born between February 25th of 1961 to the end of 1965. That would make 72,486 employees eligible as mentees.

![summary2.png](https://raw.githubusercontent.com/LaurenDebes/Pewlett-Hackard-Analysis/main/summary2.png)
