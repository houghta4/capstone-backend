# capstone-backend
backend of capstone 595 group 5

1. Download MySQL Installer https://dev.mysql.com/downloads/installer/
  - Select developer default
3. Replace your MySql username and password in application.properties. 
  - Mine is username: root password: root, so if you don't want to change anything you can copy that
  - ALTER USER 'root'@'localhost' IDENTIFIED BY 'root';
4. In MySQL Workbench, create a new script and run: CREATE DATABASE capstone;
  - This can be named anything you want as long as it matches the schema in application.properties. I have mine named capstone
