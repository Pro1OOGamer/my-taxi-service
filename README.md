# my-taxi-service

## List of content
- [Description](#description)
- [Stack of technologies](#stack-of-technologies)
- [Installing](#installing)
- [Getting started](#getting-started)
- [Authors](#authors)

## Description
Hi to all! This is my implementation of the taxi service, the purpose of this project was to test the capabilities of Java Web in interaction with the MySQL database, as well as to acquire practical skills in working with GitHub and publishing the project in public access. <hr>
The project structure is based on 3-Tier architecture:
1. Data Tier - MySQL DB and DAO's.
2. Application Tier - business logic in Java services.
3. Presentation Tier - Servlet Controllers and JSP pages.

## Stack of technologies
- Java 11
- Servlet 4.0.1
- SQL
- MySQL 8.0.22
- JDBC
- Maven 4.0.0
- Tomcat 9.0.50
- JSTL 1.2
- JSP
- HTML

## Installing
1. Download project from this repository and add to IDE as Maven project;
2. Add project to your IDE as Maven project;
3. Install and configure Tomcat 9.0.50, with other versions, the work will not be correct;
4. Install and configure MySQL;
5. In the ConnectionUtil class, replace the USERNAME and PASSWORD fields with the corresponding data from your DB
6. Make sure all dependencies from pom.xml are loaded;
7. Run init_db.sql in database;
8. Finally run it!

## Getting started
First, you must register (create a driver) and log in. Unregistered users do not have access to our service. After logging in, you have the opportunity to receive all information about drivers, car models and manufacturers. You can also create the aforementioned options yourself at your discretion and taste, as well as assign individual drivers to your cars.

## Authors
[Ivan Kharchenko](https://github.com/Pro1OOGamer)
