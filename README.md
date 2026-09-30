# Library Management System - Java + JDBC
Educational web app using Java Servlets, JSP, JDBC and MySQL.

Requirements: JDK 17+, Maven, MySQL 8+, Tomcat 10.1+.

Setup:
1. Run database/schema.sql in MySQL.
2. Edit MySQL username/password in DBConnection.java.
3. Run `mvn clean package`.
4. Deploy target/library-management.war to Tomcat.
5. Open http://localhost:8080/library-management/

Features: registration, login, book search, borrow, return, due dates, borrowing history, JDBC DAO architecture.
