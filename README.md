# simple-Login-page-using-python-mysql
its just a simple project using python and mySQL. It will take login information and store it in table format on SQL.
..........................................................................................................................

Steps to follow after installing all the modules. Otherwise this application will not work properly.

->Create a database with this name, "student_database" ->create a table with this name, "student_register"

USE this code to create the table under the "student_database" database

create table student_register( f_name VARCHAR(50) NOT NULL, l_name VARCHAR(50) NOT NULL, email VARCHAR(100) NOT NULL, question VARCHAR(50) NOT NULL, answer VARCHAR(100) NOT NULL, password VARCHAR(50) NOT NULL, PRIMARY KEY ( email ) );
