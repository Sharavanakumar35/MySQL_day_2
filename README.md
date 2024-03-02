# Guvi Online Learning Platform Database

This repository contains the SQL schema for the database of Guvi, an online learning platform. The database schema is designed to manage information about students, tasks, mentors, batches, courses, and marks.

## ER Diagram

An Entity-Relationship (ER) diagram has been created using MySQL Workbench to visualize the structure of the database. The ER diagram illustrates the relationships between different entities in the database.

Click [here](https://github.com/Sharavanakumar35/MySQL_day_2/blob/main/guvi_zenclass_DB.mwb) to download ER Diagram

## Tables

The database consists of the following tables:

1. **students**: Contains information about the students enrolled in the platform.
2. **tasks**: Stores details about the tasks assigned to students.
3. **mentors**: Contains information about the mentors associated with the platform.
4. **batches**: Stores information about the batches of students, each associated with a mentor and a course.
5. **courses**: Contains details about the courses offered on the platform.
6. **marks**: Stores the marks obtained by students for each task.

## Usage

To use this database schema, you can:

1. Execute the SQL script in your MySQL environment to create the tables and establish the necessary relationships.
2. Populate the tables with sample data as per your requirements.
3. Query the database to retrieve information about students, tasks, mentors, batches, courses, and marks.

## Tools Used

- MySQL Workbench: Used to design the database schema and create the ER diagram.
