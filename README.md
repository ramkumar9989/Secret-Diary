# Secret-Diary

### Secret Diary Project

Is an application where it allows a user to write down anything in their diary.

### Settting up the database ###

1. Create a MySQL database with any name.

2.
  * Table Name: users
  * Column1: `id` type int with size (11) [auto increment]
  * Column2: `email` type text 
  * Column3: `password` type text
  * Column4: `diary` type text with default value as NULL

  to add the above table and columns into the database simply run this sql query:

  

  CREATE TABLE IF NOT EXISTS `users` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `email` text NOT NULL,
  `password` text NOT NULL,
  `diary` text ,
  PRIMARY KEY (`id`)
  ) ENGINE=InnoDB AUTO_INCREMENT=12 DEFAULT CHARSET=latin1;



3. Update the connection to the database in the connection.php

  $link = mysqli_connect("127.0.0.1 or localhost", "my_user", "my_password", "my_db");
  
  
  ###creator's information

This diary was created by Ram kumar Vakamudi

This diary was created based on the literature survey of different websites  

This project is created based on the  [Bootstrap](http://getbootstrap.com/) framework
