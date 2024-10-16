# HR-Dashboard-MySQL-PowerBI

![image](https://user-images.githubusercontent.com/56026296/229609893-b7b1f261-5941-45af-8322-1ccb2535d36b.png)

## Data Used

**Data** - HR Data with over 22000 rows from the year 2000 to 2020.

**Data Cleaning & Analysis** - MySQL Workbench

**Data Visualization** - PowerBI

## Questions

1. What is the gender distribution among the company's employees?
2. What is the racial/ethnic composition of the workforce?
3. How is the age of employees distributed across the company?
4. What is the number of employees working at headquarters compared to remote locations?
5. What is the average tenure of employees who have left the company?
6. How does gender distribution vary by department and job title?
7. What are the most common job titles within the company?
8. Which department experiences the highest employee turnover?
9. How are employees distributed across different states?
10. How has the number of employees changed over time based on hiring and termination dates?
11. What is the tenure distribution within each department?

## Summary of Findings
- The workforce is predominantly male.
- The majority of employees identify as White, with Native Hawaiian and American Indian being the least represented.
- Employees range in age from 20 to 57 years old.
- Employees are grouped into five age categories (18-24, 25-34, 35-44, 45-54, 55-64), with the 25-34 age group being the largest, followed by the 35-44 age group. The 55-64 age group is the smallest.
- More employees work at the headquarters compared to remote locations.
- The average employment duration for terminated employees is approximately 7 years.
- Gender distribution across departments is relatively balanced, though there are generally more male employees.
- The Marketing department has the highest turnover rate, followed by the Training department. The lowest turnover rates are in the Research and Development, Support, and Legal departments.
- Ohio has the highest number of employees.
- The overall employee count has increased over the years.
- The average tenure across departments is about 8 years, with the highest tenures in the Legal and Auditing departments, and the lowest in the Services, Sales, and Marketing departments.


## Limitations

- Records with negative ages (967 in total) were excluded from the analysis. Only ages 18 and above were considered.
- Future termination dates (1599 records) were excluded from the analysis. Only termination dates up to the current date were used.
