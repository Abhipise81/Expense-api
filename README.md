# expense-api

A expense management node application to compliment with the [expense-app](https://github.com/Abhipise81/Expense-app) front end.

## Folder Structure and Explanation

```bash
.
├── server
|   ├── authStrategy
|   |   └── auth.js
|   ├── config
|   |   ├── index.js
|   |   └── server.js
|   ├── models
|   |   ├── administrator
|   |   |   └── user.js
|   |   ├── authetication
|   |   |   └── session.js
|   |   ├── core
|   |   |   ├── category.js
|   |   |   └── expense.js
|   |   └── index.js
|   ├── routes
|   |   ├── api
|   |   |   ├── administrator
|   |   |   |   └── user.js
|   |   |   └── authetication
|   |   |   |   ├── auth.js
|   |   |   |   └── signup.js
|   |   |   └── core
|   |   |       ├── category.js
|   |   |       └── expense.js
|   |   └── index.js
|   ├── utils
|   |   └── index.js
|   └── index.js
├── .gitignore
├── LICENCE
├── pakage-lock.json
├── package.json
└── README
```

## Project Explaination

**./Server**:- this folder contains all the APIs, Database Models, utils Functions and config information

**./Server/authStrategy**:- this folder contains authorization strategies plugins  which will be used at every request

**./server/config**:- this folder contains configuration info about modules, server and secret key.

**./server/models**:- this folder contains schema of modules (user, session, etc)

**./server/routes**:- this folder contains all the APIs

**./server/utils**:- this folder contains  functions required for application

**./server/index.js**:- this file is entry point for application everything is integrated here

**./.gitignore**:- this file is used t=for ignoring files and folders while making comments

**./package.json**:- this file contains project info , eslint config info (Standered Configuration), nodemon config, dependencies and dev dependencies

**./README.md**:- You are currently reading this file

## Technologies/Libraries Used

1. Javascript
2. Node Js
3. [Hapi Js](https://hapi.dev/api/?v=19.1.1#route-options)
4. jsonwebtoken
5. mongoose js
6. Mongo Db

Instructions
--------------
Please follow these instructions for running the application.

###### API
- [] install mongodb, node js , npm on your machine
- [] Clone expense-api repo
- [] Install all the dependancies and devedependancies uaing ```npm install``` or ```npm i```
- [] start the server using ```npm start```
