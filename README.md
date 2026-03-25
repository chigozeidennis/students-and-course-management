# Student Management System - Advanced SQL Analytics Project

## Project Overview

This project is a Student Management System database designed using SQL to manage students, instructors, courses, and enrollments efficiently. It demonstrates database design, table relationships, and data organization using structured queries.


 Objective

The goal of this project is to
	•	Design a relational database from scratch,Establish relationships between multiple tables,Ensure data integrity using primary and foreign keys,Practice real-world database structuring

 Tools & Technologies
	•	SQL (MySQL)
	•	Database Design Concepts
	•	Relational Database Management System (RDBMS)

Database Structure

1. Students Table

Stores student personal information:
	•	id (Primary Key)
	•	first_name
	•	last_name
	•	email (Unique)
	•	date_of_birth
	•	gender

2. Instructors Table

Contains instructor details:
	•	instructor_id (Primary Key)
	•	instructor_name
	•	email (Unique)

3. Courses Table

Stores course information and links instructors:
	•	course_id (Primary Key)
	•	course_name
	•	instructor_id (Foreign Key)

4. Enrollments Table

Tracks which students are enrolled in which courses:
	•	enrollment_id (Primary Key)
	•	(Expected fields: student_id, course_id, etc.)

 Relationships
	•	One instructor can teach multiple courses
	•	Each course is assigned to one instructor
	•	Students can enroll in multiple courses
	•	Courses can have multiple students

 Key Features
	•	Use of Primary Keys to uniquely identify records
	•	Use of Foreign Keys to maintain relationships
	•	Ensures data consistency and integrity
	•	Structured for scalability and real-world use

 Learning Outcomes

Through this project, I learned:
	•	How to design a relational database schema
	•	How to create and link multiple tables
	•	The importance of normalization
	•	Writing structured and readable SQL queries



### Conclusion

This project demonstrates my ability to design and implement a structured database system using SQL. It reflects foundational skills required for data analysis, including data organization, relationship mapping, and database management
