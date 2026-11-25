# MySQL-Assignment-2-Querying-Data

Distinct Values & Aliases (DISTINCT, AS)

Retrieving unique salary values from employees (DISTINCT)
Renaming columns such as age to Employee_Age and salary to Employee_Salary (AS)

Filtering (WHERE, LIKE):

Filtering employees by salary (> 50000) and hire date (< '2016-01-01')
Finding missing designations and updating them (such as filling with 'Data Scientist')
Pattern matching designations with 'Analyst' (LIKE)

Sorting & Limiting (ORDER BY, LIMIT)

Sorting employees by department_id ascending and salary descending
Limiting results to the first 5 employees hired in 2018

Aggregations, Grouping & HAVING (SUM, MIN, MAX, AVG, COUNT, GROUP BY, HAVING):

Calculating total salary for the Finance department (including a subquery option without a JOIN)
Finding minimum employee age (MIN) and maximum salary per location (MAX with GROUP BY)
Finding average salary for designations containing 'Analyst' (AVG and GROUP BY)
Finding departments with fewer than 3 employees (COUNT with LEFT JOIN, GROUP BY, and HAVING)
Finding locations where female employees (gender = 'F') have an average age below 30 (AVG with GROUP BY and HAVING < 30, returning 3 locations)

Joins (INNER JOIN, LEFT JOIN, RIGHT JOIN)

Listing employee names, designations, and assigned department names
Listing all departments with employee counts, including 0 for departments with no employees
Displaying all locations with assigned employee names (NULL where none exist)
