# Student Performance Database

A beginner SQL project: a small database of student records with queries to analyse their performance.

## Tools Used
- SQL (SQLite syntax)
- SQLite Online (browser-based SQL IDE)

## Table Structure

**students**

| Column | Type | Description |
|---|---|---|
| student_id | INTEGER (Primary Key) | Unique ID for each student |
| name | VARCHAR(50) | Student name |
| department | VARCHAR(30) | EEE, CSE or BBA |
| semester | INTEGER | Current semester |
| math | INTEGER | Math marks |
| physics | INTEGER | Physics marks |
| programming | INTEGER | Programming marks |

## Queries Included
1. List all EEE students
2. Students scoring above 80 in programming, sorted highest first
3. Average mark per student
4. Department-wise student count and average programming mark
5. Grade assignment (A/B/C/Fail) using `CASE`
6. Top scorer in each subject (handles ties)

## How to Run
1. Open any online SQL IDE (e.g. SQLite Online).
2. Copy the contents of `student_performance.sql`.
3. Paste it into the editor and click **Run**.

## What I Learned
- Creating tables with primary keys and constraints
- Inserting and querying data
- Filtering, sorting, and aggregation (`WHERE`, `ORDER BY`, `GROUP BY`)
- Using `CASE` and subqueries

## Next Steps
- Split marks into a separate table and practise `JOIN`s
- Export to CSV and build a small Python data pipeline
