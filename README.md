# Elevate Lab SQL Internship – Task 4  
## College Event Management System – Aggregate Functions and Grouping

This task is part of the Elevate Lab SQL Developer Internship and focuses on using aggregate functions and grouping techniques in SQL. The goal is to summarize and analyze data using functions like `COUNT`, `SUM`, `AVG`, and `MAX`, along with `GROUP BY` and `HAVING` clauses.

---

## Objective

To extract meaningful summaries from tabular data using SQL aggregate functions and to apply grouping and filtering logic for analyzing records in the College Event Management System database.

---

## Database Used

**Database Name:** `CollegeEventDB`  
This schema is built to simulate the backend structure of managing a college fest, including modules such as student registrations, event planning, team participation, and result management.

---

## Tables Involved

- `Student`  
- `Organizer`  
- `Venue`  
- `Event`  
- `Team`  
- `Participation`  
- `Result`

---

## Tasks Performed

- Used `COUNT(*)`, `AVG()`, `MAX()`, `SUM()`, and `ROUND()` for data summarization
- Grouped data using `GROUP BY` based on fields like department, event, venue, and organizer
- Filtered grouped results using the `HAVING` clause
- Calculated total students per department and total events per organizer
- Counted teams per event and results declared per event
- Retrieved distinct departments and calculated average values across numeric fields
- Grouped and filtered data to identify venues with maximum capacity and departments with more than one student

---

## Concepts Demonstrated

- Use of SQL aggregate functions:
  - `COUNT()`, `SUM()`, `AVG()`, `MAX()`, `MIN()`
- Categorizing data using `GROUP BY`
- Filtering grouped results using `HAVING`
- Applying aggregate logic with conditions using `WHERE`
- Formatting numeric output using `ROUND()`
- Counting distinct values using `COUNT(DISTINCT ...)`

---

## Execution Instructions

1. Open MySQL Workbench or your preferred SQL editor.
2. Ensure that the `CollegeEventDB` schema and all required tables have been created and populated.
3. Run the `task4.sql` script to execute the queries.
4. Review the result sets for each query to confirm their correctness and interpretation.

---

## Files Included

| File Name   | Description                                       |
|-------------|---------------------------------------------------|
| `task4.sql` | SQL script containing all aggregate queries        |
| `README.md` | Documentation file for Task 4                     |
