# Student-Management-System-using-JDBC-and-Mysql

* STEPS:

1. First download MySQL
2. Download Eclipse IDE for java programming
3. Download Java Database Connector Jar file using below link
    https://repo1.maven.org/maven2/mysql/mysql-connector-java/8.0.11/mysql-connector-java-8.0.11.jar
    
* Steps For MySQL:

4. Open MySQL command line client.
5. Create a database using below query - 
    create database studentRecords;
    use studentRecords;
6. Create table students using following querry -
    create table students (
      sid int not null auto_increment,
      sname varchar(50) not null,
      scity varchar(20),
      sphone varchar(12),
      primary key(sid)
      );
7. For display table attributes run the bellow querry -
    desc students;
    
* Steps for Eclipse :

8. Open Ecpise
9. Click on File
10. Click on  New 
11. Then click on Java Project
12. In the field of project name enter StudentManagementJDBC
13. Click on Finish - select Dont't create -> Here you will see that our project is create in the left side under Package Explorer
14. Click on a small arrow in front of StudentManagementJDBC
15. You will a src file then Right click on that - click on New - Package 
16. Then Enter Package name as Start
17. Right Click on Start - Select class - Enter class name as Start
18. Similler way create another package name of - com.student.manage
19. Similler way create the class of name Student, CP and studentDao in the com.student.manage package
20. Right click on src - select Build Path - Configure Build Path
21. Select Libraries - click on ModulePath - Add external JARs - select mysql-connector-java - 8.0.11 (Jar file you have downloaded in step 3) - open - Apply and close
21. Then copy the content from attached files and paste in the respective file of eclipse.
23. Run the program.

* To Check the database

24. In the MySQL command line client run below query -
      select * from students;
