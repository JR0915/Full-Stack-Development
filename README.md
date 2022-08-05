# Student-Database-Management-System-using-JAVA-Spring-Boot
In this project, I have worked on a Database Management System of Student , Result & Course for Students using Spring Boot Web Platform.

# Environment
- Intellij IDE
- Java 18
- Spring Boot
- Mysql

# Testing
**URL** **:** (www.google.com)

# Student Management System
This system have following classes:

1. StudentController.java
2. Student.java 
3. StudentRepository.java

## StudentController.java
This java class contains methods like GET , POST , PUT , DELETE ...
 - **@GetMapping :** This method is use for get the list of all Students and get pertucular Student by its id.
   - **/liststudents , /student/{id}**
     - show Students all data and with Specific ID
 - **@PostMapping :** This method is use for add the new Student details.
   - **/student** 
     - Delete student with Specific ID.
 - **@PutMaping :** This method is use for update Student information.
   - **/update/{id}**
     - Update With Specific ID
 - **@DeleteMaping :** This method is use for delete Student information.
   - **/delete/{id}**
     - Delete With Specific ID 
  
## Student.java
This class have variables like id,name and address where **id** is the **primary key**,also it have **constructors**, **getters** and **setters**.

## StudentRepository.java
This is basically a **Interface**.

# Postman
We can check GET,PUT,POST,DELETE mapping using postman api platform.

It can also check using VS code.We have to install **Thuder Client** for it.

# MySQL Server
We will store our Student, Course and Result related information in this by creating our DataBase.

# How to use this project in IntelliJ IDEA ?
1. First follow this step for installing Spring Boot in your IDE.<br/><br/>
   File menu -> Settings -> Plugins -> Search Spring Initializr and Assistant and then click on Install.<br/><br/>
2. You can Download the Zip file of code by clicking on the top of the page named Code -> Download Zip and then open it into your IDE .<br/><br/>
3. You can use this project by another way in your IDE by following steps:<br/><br/>
   File menu -> New -> Project From Version Control -> Version Control: Git -> Enter the url: https://github.com/Jay20IT043/studentmgmtsystem -> Choose Directory ->    Clone
