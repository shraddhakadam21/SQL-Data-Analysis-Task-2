# SQL Data Analysis Internship – Task 2
## Student Management Database: Course Performance Analysis

### Project Overview
As part of my Data Analysis Internship, I extended my existing Student Management Database by creating Courses and Enrollments tables. I used MySQL to analyze course performance, calculate average grades, identify top-performing students, and count students who failed.

### Tools Used
- MySQL
- MySQL Workbench
- SQL

### Database Tables

**1. Students**
Existing table containing student details from Task 1.

**2. Courses**
- `id` – Primary key with auto-increment
- `name` – Course name

**3. Enrollments**
- `student_id` – Foreign key referencing Students
- `course_id` – Foreign key referencing Courses
- `grade` – Numeric course score

A composite primary key on `student_id` and `course_id` prevents duplicate enrollments for the same student and course.

### Tasks Completed
1. Created the Courses table.
2. Created the Enrollments table with foreign key relationships.
3. Inserted sample courses and enrollment records.
4. Listed students enrolled in each course using INNER JOIN.
5. Calculated average grades per course using AVG(), GROUP BY, and ROUND().
6. Identified the top three students using aggregate functions, ORDER BY, and LIMIT.
7. Counted failed enrollment records and distinct students with scores below 40.

### SQL Concepts Practiced
- Relational database design
- Primary keys and composite primary keys
- Foreign keys and table relationships
- INNER JOIN
- Aggregate functions: AVG(), COUNT(), and SUM()
- GROUP BY and ORDER BY
- WHERE conditions
- DISTINCT
- ROUND() and LIMIT

### Key Learnings
This project strengthened my understanding of relational database relationships, joining multiple tables, aggregating data, ranking students, and analyzing performance across courses.

### How to Run
1. Open MySQL Workbench and connect to your MySQL server.
2. Select the StudentManagement database.
3. Open `StudentManagement_Task2.sql`.
4. Execute the table creation and data insertion statements in the correct order.
5. Run the analysis queries and review the results.

### Note
The sample enrollment scores used in this project are fictional and intended for learning purposes.
