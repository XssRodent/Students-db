# Build a Student Database: Part 1

This project is part of the FreeCodeCamp Relational Database Certification course. It aims to create and manage a student database using PostgreSQL. The database stores information about students, their majors, and the courses they are enrolled in, demonstrating a practical example of relational database management.

## Project Overview

The objective of this project is to:

- Create a PostgreSQL database named `students`.
- Populate the database with tables for students, majors, and courses.
- Use a shell script to insert data into the tables from CSV files.
- Implement logic to handle relationships between students, their majors, and their courses.

## Database Schema

The project utilizes the following tables:

1. **`students` Table**:
   - Contains information about students, such as their ID, name, and major.

2. **`majors` Table**:
   - Lists the available majors, with each major having a unique ID.

3. **`courses` Table**:
   - Lists the courses offered, with each course having a unique ID.

4. **`majors_courses` Table**:
   - Acts as a junction table to associate majors with courses, demonstrating many-to-many relationships.
