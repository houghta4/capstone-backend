# capstone-backend
backend of capstone 595 group 5

1. Download MySQL Installer https://dev.mysql.com/downloads/installer/
  - On the site click on the download link for your operating system 
  - Click "No thanks, just start my download." at the bottom 
  - After pulling up the installer 
  - Select developer default and press next/execute untill its down downloading
  - Once done, it should open up automatically 
2. Replace your MySql username and password in application.properties. 
  - Mine is username: root password: root, so if you don't want to change anything you can copy that
  - ALTER USER 'root'@'localhost' IDENTIFIED BY 'root';
3. Download JDK 19 https://www.oracle.com/java/technologies/javase/jdk19-archive-downloads.html
  - Follow the installer
  
4. Download any java IDE: https://www.jetbrains.com/idea/download/#section=windows
  - We used Intellij. Get tge community edition and follow installer steps
  - Once installed, Use this github repo by pressing Clone VCS and pasting the code link in their. 
  - ***Make sure you configue your SDK is 19 in File-> Project Structure -> Project  
  - click on CapstoneApplication in src-> java -> Capstone Application
  
5. In MySQL Workbench, create a new script and run: CREATE DATABASE capstone;
  - This can be named anything you want as long as it matches the schema in application.properties. I have mine named capstone

6. In Your Java IDE in src/main/java/com/capstone595/capstone/CapstoneApplication.java, Press the play button to the right of line 7 and click run 

7. Your database should be up and running, Try creating an account and loging in. It sould save your User
