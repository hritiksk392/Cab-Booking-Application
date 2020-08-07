# Cab-Booking-Application
## Overview
A java based application which provides a interface for the user to login/signup to book a ride.
This application provides the user to register into the database using his/her details and maintain their account. It facilitates the user to book a cab for their desired location and the closest driver will be assigned to them. Every account/ID also has a wallet linked to it which can be used for booking rides and the user can add money to the wallet whenever required.

![Home](/home.png)

## Database
We hold 2 databases for the application namely **user** and **driver**. The 'user' database will hold the user personal information like their wallet amount and passwords. The 'driver' database will hold driver personal details and information regarding to his vehicle and current location ('Location_Name', 'Distance from reference' , 'Direction').
To link database to the netbeans JAVA project file , the project has to be linked to 'mysql-connector-java-5.1.48-bin.jar' before accessing the phpmyadmin database.
We have used "XAMPP" web server to locally host our relational database.
For accesing the information in the database the queries are written in SQL, can be found in the source code ('src directory')
You have to create your own XAMPP web server with pre-defined attributes to replicate the database and run the application.

## Important Files
* The source code of the application can be found under the 'src directory'.
* The .jar and .exe file can be found under distribution folder which is the 'dist' directory.
* The mysql to JAVA connector .jar file is present in the home directory itself.

## Team Members
* Hritik Singh Kushwah (https://github.com/hritiksk392)
* Smiket Barodia (https://github.com/Smket99)
* Shubham Asopa (https://github.com/sammyasopa)
