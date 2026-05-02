# BrightLearn-Sql-Fundamentals-Select-Filtering
A beginner-friendly SQL project covering SELECT statements, filtering with WHERE, sorting, and basic query building using an employees dataset.
## 📚 Overview

This exercise introduces the core concepts of SQL used by data analysts and data scientists to retrieve and filter data from a database.

### Key Topics Covered:
- SELECT statements (all columns and specific columns)
- DISTINCT (removing duplicates)
- ORDER BY (sorting results)
- LIMIT (restricting number of rows)
- WHERE clause (filtering data)
- Logical operators: AND, OR, NOT, IN


## 🗂 Dataset

The exercise is based on a single table:

### `employees`

| id | first_name | last_name | department | salary | hire_date | city |
|----|------------|-----------|------------|--------|------------|--------|
| 1  | Alice      | Green     | IT         | 70000  | 2020-01-10 | Johannesburg |
| 2  | Brian      | Lee       | HR         | 45000  | 2019-03-22 | Cape Town |
| 3  | Cathy      | Zulu      | Finance    | 65000  | 2018-07-18 | Durban |
| 4  | David      | Mokoena   | Marketing  | 50000  | 2021-11-05 | Pretoria |
| 5  | Eva        | Naidoo    | IT         | 72000  | 2017-09-30 | Johannesburg |


## 🧠 Learning Objectives

By completing this exercise, I practiced how to:
- Retrieve data using SQL queries
- Filter datasets based on conditions
- Sort and limit query results
- Predict query outputs before execution

## 📝 Exercise Breakdown

### 🔹 Section 1: Selecting & Sorting
1. Retrieve all columns from the employees table  
2. Find unique departments  
3. Retrieve first and last names ordered by salary (descending)  
4. Retrieve the top 3 highest-paid employees  

### 🔹 Section 2: Filtering with WHERE
5. Employees in the IT department  
6. Employees in Finance with salary > 60000  
7. Employees in HR or Marketing  
8. Employees not in IT  
9. Employees in IT, HR, or Finance (using IN)  
10. Employees in IT with salary > 65000 and city Johannesburg  


## 💻 Example Query

```sql
SELECT first_name, last_name
FROM employees
ORDER BY salary DESC;
