Personal Encyclopedia
=====================
Software in Java to help maintain your data and notes and provide search option to manage your data in effective manner.  

The Prgramming Language used is **Java** .

For handling data it uses **MySQL** database.

##MySQL database 

Name of the database used is **personalenc** .
### Tables used by this System  ###

    Data
    
### Structure of Table with their description 

####Data table -
It stores your content 

| S.NO.         | Column Name   | Data Type | Size | Key | NULL |
| ------------- |:-------------:|:---------:|:----:|:---:|:----:|
| 1      | id | Integer | 7 | Primary Key | YES |
| 2      | title     |   Varchar |  60 || YES |
| 3 | content      |    Varchar | 4000 |  | YES |
| 4 | tag    | Varchar |  200| | YES | 

##Set up this project in your System 

Open all the files in this repositry in your ide, i used Netbean IDE here.

Username and Password used by me are "root" and "netbean". So, edit this line of code according to your mysql username and password  

    String databasepass="netbean";
    String databaseuser="root";

