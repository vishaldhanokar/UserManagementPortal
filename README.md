# Usermangement
This is a simple JSP web application for performing CRUD (Create, Read, Update, Delete) operations on user data.

Features
The application allows users to perform the following actions:

View a list of all users in the system
Add a new user
Edit an existing user
Delete a user

Requirements
• Java 8 or later
• Apache Tomcat 8.5 or later
• MySQL 5.7 or later
• MySQL Connector/J 8.0.25 or later
• Eclipse IDE (or any other Java IDE)

Installation
1. Clone this repository to your local machine.
2. Import the project into Eclipse or your preferred IDE.
3. Set up a MySQL database and create a table named users with the following columns:
  • id (INT, primary key, auto-increment)
  • name (VARCHAR)
  • email (VARCHAR)
  • country (VARCHAR)
4. Build and run the project on Apache Tomcat.

Usage
Once the application is running, you can access it by navigating to http://localhost:8080/usermanagement in your web browser.

The home page will display a list of all users in the system. To add a new user, click the "Add User" button and fill out the form. To edit or delete an existing user, click the corresponding buttons next to the user's name in the table.
