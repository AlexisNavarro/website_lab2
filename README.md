# lab2_secure_web
## Purpose
For this project I will be creating a website that uses MySQL as the database, PHP for the backend to allow the user to store and retrieve information to, and HTML which is the front end that will display the information that the back end has sent for the user to read 

To be able to run this website you will also need to have a localhost installed in your computer in which I used AMMPS since it comes with PHP and MYSQl, another alternative can be XAMMPS.

## Setting up MySQL

To be able to run this website you will need to set up your database in MySQL to be able to contain two tables which these tables will be the User and Admin tables. To access MySQL in this project I used the MySQL that comes from phpmyadmin in AMMPS. Within these tables you want to have:
1. first name
2. last name
3. username
4. password
5. creation date
6. last log in

both of these tables will need to use VARCHAR(255), the large size is just to avoid any length issues with the hashing of the password that will be done later.

Now that the database is set up, use the INSERT statment in MySQl to insert a user and admin account to the tables to be able to access the log in functions within the website.

When connecting to the database please look at the [config.php](https://github.com/AlexisNavarro/lab2_secure_web/blob/main/config.php) file which will be handling the connection to a specific database, if you are using a localhost such as I am, keep the config file the same. 

##Registering and accessing an account


