mysql> create database group5;
Query OK, 1 row affected (0.01 sec)

mysql> use group5;
Database changed
mysql> create table user
        -> (
        -> id int,
        -> age int,
        -> gender varchar(8),
        -> username varchar(30),
        -> emergency_contact varchar(30),
        -> phone_num int(20),
        -> email varchar(50),
        -> address varchar(50)
        -> )
        -> ;