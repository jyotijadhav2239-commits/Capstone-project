# E-Book Store WebApp

A web application for browsing, purchasing, and downloading e-books online. This project is developed as a capstone project for the Diploma in Computer Engineering.

## Features

### User Features
- Browse e-books by category
- View book details
- Add to cart
- Make secure payments (dummy)
- Download purchased e-books
- Write and view reviews
- Login and Register

### Admin Features
- Add, update, delete books
- Manage categories
- Manage orders
- Manage users

## Tech Stack
- Frontend: HTML, CSS, JSP
- Backend: Java (Servlet/JSP)
- Database: MySQL
- Server: Apache Tomcat 9+
- IDE: IntelliJ IDEA

## Installation Guide

### 1. System Requirements
- Java JDK 8+
- IntelliJ IDEA / Eclipse
- Apache Tomcat 9+
- MySQL Server + MySQL Workbench

### 2. Download or Clone the Project
git clone https://github.com/your-username/ebook-store-webapp.git

Or download ZIP and extract.

### 3. Database Setup
1. Open MySQL Workbench
2. Create database:
   CREATE DATABASE ebook_app;
3. Import SQL file if available
4. Update database connection inside DBConnect.java:

   DriverManager.getConnection(
   "jdbc:mysql://localhost:3306/ebook_app",
   "root",
   "your_password");

### 4. Configure Tomcat
- Add Apache Tomcat in IntelliJ settings
- Add project artifact (WAR exploded)
- Run Tomcat server

### 5. Run the Application
Open browser and type:

http://localhost:8080/EbookStore/

## Folder Structure

/EbookStore  
   /src  
      /com.DB  
      /com.user  
      /com.admin  
   /web  
      index.jsp  
      login.jsp  
      register.jsp  
   /WEB-INF  
      web.xml  

## Team Members
- Jyoti Madhukar Jadhav
- Shital Rajabhau Jadhav
- Gayatri Madhav More
- Mayuri Laxman Narsale

## Guide
Mr. M. A. Zahed  
Lecturer, Computer Engineering  
Government Polytechnic Jintur

## License
This project is for educational purposes only.
