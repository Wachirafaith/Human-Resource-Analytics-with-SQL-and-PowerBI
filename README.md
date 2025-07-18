# Human Resource Analytics with SQL and PowerBI

## Project Overview

This project involves cleaning and analyzing a Human Resource dataset using SQL followed by creating an interactive dashboard in Power BI. The objective was to extract meaningful HR insights such as employee demographics, turnover trends etc

## Data and Tools used

- **Data** - HR Data with over 22000 rows from the year 2000 to 2020.

- **Data Cleaning and Analysis** - MySQL Workbench

- **Data Visualization** - PowerBI

## Analysis Questions

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across different departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by city and state?
10. How has the company's employee count changed over time based on hire and term dates?
11. What is the tenure distribution for each department?

## Power BI Dashboard

An interactive dashboard was created in Power BI based on the SQL query outputs

Dashboard preview

![page1](https://github.com/user-attachments/assets/dd254fbc-2010-4ce5-bd84-367c3242979f)
![page2](https://github.com/user-attachments/assets/a17675c5-610c-4dca-92e3-415e3fd7e786)



## Key Insights

- There are more male employees
- White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
- The youngest employee is 20 years old and the oldest is 57 years old
- 5 age groups were created (18-24, 25-34, 35-44, 45-54, 55-64). A large number of employees were between 25-34 followed by 35-44 while the smallest group was 55-64.
- A large number of employees work at the headquarters versus remotely.
- The average length of employment for terminated employees is around 7 years.
- The gender distribution across departments is fairly balanced but there are generally more male than female employees.
- The Marketing department has the highest turnover rate followed by Training. The least turn over rate are in the Research and development, Support and Legal departments.
- A large number of employees come from the state of Ohio.
- The net change in employees has increased over the years.
- The average tenure for each department is about 8 years with Legal and Auditing having the highest and Services, Sales and Marketing having the lowest.

## Limitations

- Some records had negative ages and these were excluded during querying. Ages used were 18 years and above.
- Some termdates were far into the future and were not included in the analysis. The only term dates used were those less than or equal to the current date.

## Conclusion

This project demonstrates how SQL and Power BI can be combined for end-to-end HR analytics. It highlights the importance of using data to inform strategic HR decisions around hiring, retention and workforce planning.










