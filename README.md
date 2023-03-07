# SSH Mysql Commands

## Mysql Commands (To create db, create user and  grant all privileges to user) 

01. CREATE DATABASE dbname;

02. CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';

03. USE mysql;

04. select user from user;

05. GRANT ALL PRIVILEGES ON `dbname`.* TO `username`@`localhost`;

06. FLUSH PRIVILEGES;

07. SHOW GRANTS FOR 'username'@'localhost';

08. Import db command: mysql -u username -p dbname < filename.sql

09. Export db command: mysqldump -u username -p dbname > filename.sql

10. Next Steps To Change db user password

11. mysql -u root password

12. Enter password

13. ALTER USER 'username'@'localhost' IDENTIFIED BY 'newpassword';

14. FLUSH PRIVILEGES;
