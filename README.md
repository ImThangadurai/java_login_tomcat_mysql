# Registration and Login Example with Spring MVC 4, Spring Security, Spring Data JPA, XML Configuration, Maven, JSP, and MySQL.

## Guide
https://hellokoding.com/registration-and-login-example-with-spring-xml-configuration-maven-jsp-and-mysql/

This java program is used to check login register user to mysql database and logout. Used for K8 orchestration.

## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Stack
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL

## Steps to build the image
1. git clone https://github.com/muralindia/java_login_tomcat_mysql.git
2. cd java_login_tomcat_mysql
3. Install jdk and set java_home and path
4. mvn package    (ensure maven is installed, else apt-get install -y maven and then mvn package)
5. The above successful execution will create folder target with files containing account-1.0-SNAPSHOT.war, etc.
6. Run docker build command,
  $ docker build -t java_login_tomcat_mysql:1.0 .
7. This will build the java application image which is used for K8 orchestration frontend testing.
8. Similarly, https://github.com/muralindia/Docker-Files/tree/master/mysql-dockerfile another docker image can be built to store the application user register data in mysql database.
 
 

  
