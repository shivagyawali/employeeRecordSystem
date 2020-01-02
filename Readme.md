1.Install xampp and move your project to xampp->htdocs 

2.Open Xampp and create Database name as demo

3.Upload users.sql in mysql database

4.create employee table (copy pase below code)
CREATE TABLE employees (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    address VARCHAR(255) NOT NULL,
    salary INT(10) NOT NULL
);

username:admin
password:admin123
now your done 
