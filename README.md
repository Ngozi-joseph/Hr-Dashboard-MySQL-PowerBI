# Hr-Dashboard-MySQL-PowerBI

<img width="1426" alt="Screenshot 2024-03-25 at 09 20 57" src="https://github.com/Ngozi-joseph/Hr-Dashboard-MySQL-PowerBI/assets/161621333/42be60fe-6f89-4ff7-a7aa-231faaf3af0f">

## Table of Contents
* [Project Overview](#project-overview)
* [Data Sources](#data-sources)
* [Tools](#tools)
* [Questions](#questions)
* [Results](#questions)
* [Limitations](#limitations)

### Project Overview 

Exploring HR Employee Data Reports through analysis and visualisations. This project provides insights and charts based on the collective figures from the Employee records.


### Data Sources
The Human Resources table is stored in a csv file with over 22000 rows from the year 2000 to 2020. The dataset includes columns such as 'hire_date', 'emp_id' and 'gender'.

### Tools

- Excel
    - Data Collection of Report
- MySQL Workbench
    - Data cleaning
    - Analysis
- PowerBI
    - Data visualisation
    - Creating HR Reports

### Questions

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. What is the tenure distribution for each department?

### Results

- The average tenure for each department is about 8 years with the Sales department having the longest retention (above average) of 9 years, whilst the HR and Legal department having the lowest of 7 years.
- There are more male employees.
- 75% of employees work at the headquarters versus the 25% that work remotely.
- Most employees are located in Ohio.
- White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
- The youngest employee is 20 years old and the oldest is 57 years old.
  
### Limitations
- Some records had negative ages and these were excluded during querying and so there fore ages used were 18 years and above.
- Some termdates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current date.
