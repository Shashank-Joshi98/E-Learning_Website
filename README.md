# E-Learning_Website
## Here I have Created a simple E-Learning Website using Node js Server as Backend
### Objectives achieved :
- Teachers can add new Courses from Teachers Page
- Students have to register themselves first then or (**use Default Login provied below**) after that they can add or remove courses 
- Students can subscribe Courses and also remove Courses they don't want 
- **Default Login is :** 
    - > **user :  shank**
    - > **password:  1234**
- With the above login you can enter into System and can add or remove courses 

# Node-Modules used :
  - express
  - body-parser
  - express-session
  - lodash
  - pug
  
### There is views folder for all the pug files that I have created . 
#### I have implemented this project as MVC(Model View Architecture) - I have also created controllers modules for 
#### handling request from students and Teachers

## Concepts Covered :
- Basic Javascripts
- How to effeciently write Code in PUG files
- How to render Pug Files and Send data from the server to pug files and handle it by writing code inside Pug Files
- Use of lodash to filter the arrays
- Use of express to create and handle server requests 
--Promises concept used to read Server Files for Courses and render them to Clients
## Steps to Start using Website:
 - Download the Zip file and extract the Project
 - In vscode inside the Directory of project type command to install all the required modules 
     - Command to install all the modules : **npm install**
 - Now in the terminal start the server by 
     - Command : **nodemon server.js**
 - server.js is a file to start the server at the port 3000
 - Now open Browser type **"localhost:3000"**
