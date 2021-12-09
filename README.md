# group-06

IRMS System - React + Node.js Express: User Authentication with JWT
- Node Js – JWT Authentication & Authorization (Backend) with JSONWebToken & Sequelize
- React - JWT Authentication

Registration, Login, Logout

# Steps to run the IRMS project

1. First you need to have these prerequisites installed in your machines

    - XAMPP
    - VS Code
    - Postman
    - MySQL - > phpMyAdmin
    - Node

2. Next clone this repository to your local machines

3. Create the database called "irms_db" (no need to create the tables since they will be automatically created )

4. Change the "db.config.js" file in "node-js-jwt-auth" folder according to your MySQL Connection (username and password)

5. Then open the "node-js-jwt-auth" directory in command propmt and run "npm start" command

6. And also open the "react-jwt-auth" directory using an another command prompt and run "npm start"

7. After that you can connect to the IRMS web application. There you will be able to login and register to the system.
    Register -> Login

8. Using postman you can register some users with /signup API. Users are based on roles.
    - admin -> admin role -> userID as 3
    - internMgr -> intern manager role -> userID as 2
    - user -> user role -> userID as 1

9. Sample outputs are added on sample Outputs Folder.


