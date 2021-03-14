<<<<<<< HEAD
# Employee Manager Day 10

__Install__. 
To start install the project node_modules by running ```npm install```

__Development__. 
Start the server so the client can access the api ```npm run server```.  Make sure your are in the employee-manager directory when you run this command. To view any edits you make run ```snowpack dev``` from the employee-manager root folder. The project should run on localhost:3000

__Production__. 
When your read to deploy to Netlify you first must build a deployment build of the client site. To do this run ```snowpack build```. This will create a new folder called www inside the employee manager folder. This folder contains the optimized production bundle. Once you have this folder created commit your changes to git and visit your Heroku app an test your project. 

__Data Reset__. 
There is an api route /api/departments/reset that will copy the original data back to the employee.json file. You can run this command locally from the browser by running ```http://localhost:5000/api/departments/reset```

=======
Employee-manager

This Application contains a reigister and login form, when creating a new user in the registration form it is validatted on the client side then on the server, if validation is good the new user data include a unique id is inputted into a .json file. When logging in the information is validated again on the client side and then the server, after validation it looks for the information in the .json of user data. When the user is logged in a session is created and the authorized user will be able to acess a dashboard.


Installing
- npm install, to install all dependancies
- npm start , to start the server

Live Working demo
https://employee-manager-application.herokuapp.com/

 


 
  
>>>>>>> e1c65f518e31d9007c06bb9a61c28d70756468eb
