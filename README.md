# Authentication App

> A complete authentication system which can be used as a starter code for creating any new
> application. It has login, logout, register, forget password, email verification(for added security), and access control.

## Technologies Used

1.  NodeJS
2.  Express
3.  EJS
4.  MongoDB
5.  Mongoose
6.  PassportJS
7.  JWT
8.  Nodemailer

## Installation

##### Clone the latest Repository

`git clone https://github.com/agarwalshashankjan/Authentication.git`

##### Into the project directory

`cd authentication`

##### Installing NPM dependencies

`npm install`

##### Installing dotEnv and Mongoose dependencies

`npm install mongoose dotenv`

##### Then simply start your app

`npm start`

#### Check the console for this, if it says connected, the configuration is complete, otherwise resolve the errors:

```Server running on PORT 2000
Successfully connected to MongoDB
```

#### The Server should now be running at http://localhost:2000/

### You can always change the defaults in .env file (PORT, ENV, and mongoose connection)

## Folder Structure

Authentication <br>
├── assets <br>
│ --- ├── secure-icon.png <br>
│ --- └── css <br>
│ -------- └── bootstrap.min.css <br>
├── config <br>
│ --- ├── checkAuth.js <br>
│ --- ├── key.js <br>
│ --- └── passport.js <br>
├── config <br>
│ --- └──authController.js
├── models <br>
│ --- └── User.js <br>
├── node_modules <br>
├── routes <br>
│ --- ├── auth.js <br>
│ --- └── index.js <br>
├── views <br>
│ --- ├── dash.ejs <br>
│ --- ├── forgot.ejs <br>
│ --- ├── layout.ejs <br>
│ --- ├── login.ejs <br>
│ --- ├── messages.ejs <br>
│ --- ├── register.ejs <br>
│ --- ├── reset.ejs <br>
│ --- └── welcome.ejs <br>
├── .gitignore <br>
├── .env <br>
├── package.json <br>
├── package-lock.json <br>
├── README.md <br>
└── server.js <br>
