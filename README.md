## Login-Authentication
1. Description:
   > A full-stack authentication application that will implement Login, Registration, and Logout functionalities.
2. Technologies Used:
   > HTML, CSS, JavaScript, MERN (MongoDB, Express, React, Node.js)


## Procedure
1. Setting up Environment:
#### Front-End
   - Creat a folder of any name `Login-Authentication` and open it on VS Code.
   - Check your path and run these commands to create an App using React.
     
```cmd
npm init vite
```
   - Give your Project name as `client` click enter and select `React` and then select `JavaScript`.
   - You've created an app called `client`
   - Check your path and install npm package manager inside client app.
```cmd
npm install  
```
```cmd
npm install bootstrap axios react-router-dom
```
   - Now if you execute the following command it'll provde a link where you can host your application.
```cmd
npm run dev
```
   - In your `Login-Authentication` path, run the following command.
```cmd
npm init -y
```
#### Back-End
- Create a folder inside `Login-Authentication` with the name `server`
- Inside `server` run the following commands.
```cmd
npm init -y
```
```cmd
npm install express mongoose cors nodemon bcrypt
```
- Make sure to do these changes :
  > In `package.json` inside `server`, be sure add this in `"scripts":`
  
```json
"start": "nodemon index.js"
```
- In the terminal run this command inside `server`, to check if it's working. 
```cmd
npm start
```
- Your environment has been successfully set up.
  
2. Setting up MongoDB:
   - Install MongoDB: [Clickhere](https://www.mongodb.com/try/download/community)
   - Open MongoDB, Click on `Connect`.
   - Go to `Databases` and click on `Create Database`.
   - Give your Datbase Name as `employee` and Collection Name as `register`.
   - Click on Create Database.
 

## Demo-Video 




https://github.com/K-Pragna/Login-Authentication/assets/158297257/64d3670f-08ae-452c-a93b-683b78c4de6d

