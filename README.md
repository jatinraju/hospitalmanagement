# Java Assignment(Hospital Management Staff) By Jatin Raju

## About:
	Hospital Management Staff is a Backend project have multiple Rest Api's. You can Add, fetch and update the existing data by calling api.

## Technologies and Frameworks:
	Java
	SpringBoot
	MySQL
	Postman

## How to Use:
	- Import the project in eclipse or sts.
	- update your project using alt+f5 key.
	- import the database file (database.sql) in MySQL WORKBENCH
	- you have to set your own root credentials for MySQL database connectivity in application.properties 	file. 
	- run the main class file.
	- open the postman and sent the request to localhost 7070 (port number mention in 	application.properties file under src/main/resource folder).
	- call the api's with following url:
		/admin/add: adding patient in database
		/admin/getAll: getting the list of admitted patient
		/admin/dishcarge: update the status of patient to 'discharge'.

## Note: 
if you are sending request to admin url's then you should also send username & password with the request. without username and password it will not authenticate you.(default username: 'jatin' & password: 'raju'). you can change the username and password in the main file before running the project.

if you want to signup then do the following step:
	- send the request to /public/signup/ with json object of user class.
	- user class has id and password properties.

## Database Schema:
	Database have two tables 'patient' and 'user'.
	patient table contains all the properties mention in document and user table has id,password & role 	properties.

## Files Attached:
	- zip file of project.
	- database images.
	- postman collection file.
	
	
