# Contact Management System

This project aims to develop a web-based contact management system that enables users to efficiently manage their contacts. The system will allow user registration and login, and will support operations such as adding, modifying, searching, viewing, and deleting contacts. The application will be built using the Java technology stack

## Getting Started

## Table of Contents
- [Prerequisites](#prerequisites)
- [Backend Setup](#backend-setup)
- [Frontend Setup](#frontend-setup)
- [Tech Stack](#tech-stack)
- [Additional Information](#additional-information)

## Prerequisites
Make sure you have the following installed on your machine:
- JAVA SDK 
- Node.js (version 14.0 or later)
- npm (Node Package Manager)
- SQL Server (or other preferred database)

## Backend Setup
### 1. Clone the repository:
```bash
git clone https://github.com/izzawaheed1/Contact-Management-System.git
cd Contact-Management-System/ContactApi backend
```

### How to use ?

```
As mentioned the project has two parts and both run on different server

Run backend code
Step-1 : Open your project in spring tool suite 4 IDE
file -> import -> maven->existing maven project-> click on next -> locate the folder [ContactApi backend] -> click to finish

NOTE: make sure your internet connection is on because maven download jar's required for project to be build.

Step-2 : Create an MySQL database with the name 'contact_api'.
You can change the database related settings - If you want the path of file to change settings is : ContactApi backend\src\main\resources\application.yml
```

### 2. Configure the database:

  ```
  CREATE DATABASE `contact_api`;
  ```

### 3. Run your application
```
right click on your project name -> Run As -> Spring boot App

If you don't see any errors that means you are good to go. The backend is started and tomcat is running the port 8080

Note: Make sure to do not turn of your backend otherwise your frontend will not work.
```


## Frontend Setup
### 1. Navigate to the frontend directory:
```bash
cd Contact-Management-System/contactapp frontend
```

### 2. Install dependencies:
```bash
npm install
npm i react-router-dom
npm i react-toastify
```


### 3. Running the Frontend
```bash
npm run dev
```
The frontend will be available at ` http://localhost:5173/contacts`.


# Tech Stack:
Following Tech Stack is being implemented:
- React for frontend
- Java Spring Boot Web Api Backend
- SQL Server Management Studio for database
- Redux for state management in React
- Serilog for Application logging (to be implemented)
- Spring data JPA and Hibernate
- Junit and Mockito
- Slf4j and Logback
- SonarQube for analyzing code quality (to be implemented)

## Additional Information
TBD
