To create the banking_system database and switch to it in MariaDB, you can use the following SQL commands:
1.	Create the banking_system database:
CREATE DATABASE banking_system; 
2.	Switch to the banking_system database:
USE banking_system; 
After executing these commands, you'll have the banking_system database created and selected, and you can proceed to create the tables accounts and user within this database using the commands provided in the previous response.

Here are the SQL commands to create the tables accounts and user in the banking_system database:
1.	Create the accounts table:
CREATE TABLE accounts ( account_number BIGINT(20) NOT NULL PRIMARY KEY, full_name VARCHAR(255) NOT NULL, email VARCHAR(255) NOT NULL UNIQUE, balance DECIMAL(10,2) NOT NULL, security_pin VARCHAR(20) ); 
2.	Create the user table:
CREATE TABLE user ( full_name VARCHAR(255) NOT NULL, email VARCHAR(255) NOT NULL PRIMARY KEY, password VARCHAR(255) NOT NULL ); 
These commands will create the tables with the specified fields and constraints in the banking_system database. Also include MYSQL Connector jar.
