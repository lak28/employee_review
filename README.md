# employee_review

Below are the list of steps to start the appliaction
# Install dependencies for server
npm install

# Install dependencies for client
1. npm init
2. npm intall nodemon
3. npm install express
4. npm install express-session
5. npm install ejs
6. npm install passport
7. npm install passport-local
8. npm install mongoose
9. npm install connect-mongo

# Server runs on http://localhost:3000
Steps to work on the appliaction are written below
1 - First of all setup the application using the steps defined

2 - Once both the backend server and the frontend server start in the localhost:8000,you will first see the signin page

3- In the signin page enter the username and password of the user and press the signIn button(I have already created some users)

4- There a two types of login possible in signin page a employee login and an admin login. 
   For the employee login use the credentials:-
                                            username:-emp1
                                            password:-12345
   and for the admin login use the foloowing credentials:-
                                            username:-admin
                                            password:-12345

5- Once you click signin from admin login you will be navigated to a page which consistes of all the current employees, there you can assign the employees with tasks to review other employees or you can see all the reviews all employees got and even assign reviews to different employees and also can add new employee using sign up page

6- If you login using the employee login created by you then you will be navigated to the employee page where as an employee you can assign reviews to other employees as a task assigned by the admin and you can also see the reviews you got from other employees and the admin andd also add feedback towards your review by the admin

7-the views folder contains all the ejs files 

8-the routes folder contain the index.js file which will give the routes to the ejs file

9-the controller folder contain the user controller filewhich controlls the function to create and destroy session for user

10-the assests folder contain the css folder which has the styling for the ejs pages

11-the config contains the mongoose configuration and passport-local configuration

12-the model contains the database cariables to be saved

12-the server .js is the main file wgich contains all the dependencies and functions

other existing users created by me email -lakshyaarora4@gmail.com

Employee credential
 username:-emp1  
 password - 12345
 

very important admin credentials

 username:-admin
 password - 12345
 
 
 
