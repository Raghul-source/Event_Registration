pre-requirement:
1.jupyter notebook
2. MySQL server

procedure to run:
1.Clone this repository:

2.Install the required packages:

mysql-connector-python==8.0.33

3.Create a new database in MySQL:


CREATE DATABASE event;
USE event;

create table Registration(
	ID int not null auto_increment,
    First_name varchar(50) not null,
    Last_name varchar(50),
    DOB date not null,
    Phone_Number varchar(15) not null,
    Address varchar(200),
    primary key(ID)
    );

4)Update the db_config.py file with your MySQL login data.

5) Run the backend script CRUD.iynb

