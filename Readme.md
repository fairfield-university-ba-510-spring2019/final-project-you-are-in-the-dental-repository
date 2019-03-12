# You are in the Dental Repository Final Project
Our Final Project shows steps required to demonstrate ETL (Extract, Transform and Load) process. We developed a DataWarehouse from a source data (.csv format) supplied by Dr. Huntley. The data contains information about semesters, courses and instructors at Fairfield University. 

## 1. Create ERD
First step is to create ERD from sourse data to related to the Database design.

## 2. Transfer sourse data (.csv) to SQL
To transfer sourse data to SQL, we used sqlite3 to move to all csv files into CourseData.db. The source data was tranferred into three separate tables import_courses, import_CourseCatalogs and import_course_meetings.

## 3. Create Database Tables
Next step was to create tables within CourseData.db. We created tables in CourseData.db as per our ERD. Each table included its own Primary Key, Surrogate Keys and Foreign Keys if neccessary. 

## 4. Insert Data in CourseData.db Tables
Once we had tables created in the CourseData.db It was time to insert data into the tables. We extracted relational data from the imported source tables and inserted in to database tables. JOIN function was required to extract data from two different sourse tables to insert in to one database table.

## 5. Test Database
We created a test notebook to run queries to test Domain, Entity and Relational integrity of the database. 
