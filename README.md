# Java Assignment (Hospital Management Staff) By Jatin Raju
## Table of Contents

- About
- Technologies and Frameworks
- How to Use
- Note
- Database Schema
- Files Attached


## About :
Hospital Management Staff is a Backend project have multiple Rest Api's. You can Add, fetch and update the existing data by calling api.

## Technologies and Frameworks:
- Java
- SpringBoot
- MySQL
- Postman

## How to Use:
- Import the project in eclipse or sts(spring tool suit).
- update your project using alt+f5 key.
- create the database 'hospitalmng' (MySQL).
- you have to set your own root credentials for MySQL database connectivity in application.properties 
file under src/main/resource folder). 
- run the main class file.
- open the postman and sent the request to localhost 7070 (port number mentioned in application.properties 
file.
- call the api's with following url:
	/admin/add: adding patient in database
	/admin/getAll: getting the list of admitted patient
	/admin/dishcarge: update the status of patient to 'discharge'.
- you can also import the 'postman collection' in your postman.

## Note: 
if you are sending request to admin url's then you should also send username & password with the request. without username and password it will not authenticate you.(default username: 'jatin' & password: 'raju'). 
you can change the username and password in the main file before running the project.
**(or)**
if you want to signup then do the following steps:
- send the request to /public/signup/ with json object of user class.
- user class has id and password properties.

## Database Schema:
Database have two tables 'patient' and 'user'. Patient table contains all the properties mention in document (name, age, room, doctor name, admit date, expenses, status(admitted, discharged)) 
and User table has id, password & role properties.

## Files Attached:
- zip file of project.
- database images.
- postman collection file.

	
