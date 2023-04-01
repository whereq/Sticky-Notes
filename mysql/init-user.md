 ```
 CREATE DATABASE whereq;
 CREATE USER 'user'@'localhost' IDENTIFIED BY 'user1@3';
 CREATE USER 'user'@'%' IDENTIFIED BY 'user1@3';

 GRANT ALL PRIVILEGES ON whereq.* TO 'user'@'%' WITH GRANT OPTION;
 FLUSH PRIVILEGES;
 ```
