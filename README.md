**Online-LMS**

📘 Online Learning Management System (LMS)

This project is a simple Online Learning Management System built using Java Servlets, JSP, and MySQL.
It allows educators and students to interact in an online platform:

Educators can register, log in, and create courses.

Students can register, log in, and enroll in courses to track their learning.

🚀 Features

User registration & login (for both students and educators)

Course creation and management (by educators)

Course enrollment (by students)

Simple and clean database schema (Students, Courses, Enrollments)

🛠️ Tech Stack

Java 11

JSP & Servlets

MySQL (database)

Apache Tomcat (server)

Maven (project build & dependency management)

📂 Project Structure

lms_schema.sql → Database schema (tables for students, courses, enrollments)

pom.xml → Maven configuration (dependencies, Tomcat setup)

src/ → Java source code (Servlets, JSPs, etc.)

webapp/ → JSP pages and frontend resources

⚙️ Prerequisites

Make sure you have installed:

Java 11+

Apache Maven

MySQL

Apache Tomcat 8/9

🗄️ Database Setup

Open MySQL and create the database:

source lms_schema.sql;


This will create the students, courses, and enrollments tables.

Update your database username/password in the project (if required).

▶️ Running the Application

Package the project using Maven:

mvn clean install


Deploy to Tomcat using the Maven plugin or copy the WAR file to Tomcat’s webapps folder.

Start Tomcat server.

Open your browser and go to:

http://localhost:8080/user-web-app/

📌 Future Improvements

Add admin dashboard

Course progress tracking

Assignment & grading system

Better UI with Bootstrap/React
