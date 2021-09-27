# go-fullstack

The app you will be working on is a simple online store.

- You will create an API to Create, Read, Update, and Delete (CRUD) items for sale.
- You will add authentication to your API to protect it.
- Integrate user file management to allow users to upload images.

## Goal

- create a simple web server with Express;

- create a REST API with Node, Express and MongoDB;

- set up an authentication system on an Express application;

- manage user files on an Express application.

## Clonez l'application front-end
create your working directory: you can name it go-fullstack
Once the directory is created, you will need to clone the code for the front-end application in a subdirectory called frontend. From your working directory, enter the command below:
```sh
git clone https://github.com/OpenClassrooms-Student-Center/go-fullstack-fr-frontend.git frontend
```
You can then proceed as follows:
```sh
cd frontend
npm install
ng serve
```
Now if you go to http: // localhost: 4200 you should see the interface.

The last step is to create a second subdirectory in your working directory, called the backend. This is where you will create the Express app.

## Installation

This project requires [Node.js](https://nodejs.org/) to run.

Install the dependencies and devDependencies and start the server.

```sh
cd backend
npm i
```

For front-end environments...Install Angular

```sh
npm install -g @angular/cli
```
## Plugins

| Plugin | install |from the folder:| Command |
| ------ | ------ |------ |------ |
| Nodemon | npm install -g nodemon |backend|nodemon server|
| Express | npm install --save express |backend||
| Body-parser | npm install --save body-parser |backend||

### Connect your API to your MongoDB cluster
| Plugin | install |from the folder:| Command |
| ------ | ------ |------ |------ |
| Mongoose | npm install --save mongoose |backend||

## Prepare the database for authentication :
### create unique validator
| Plugin | install |from the folder:| Command |
| ------ | ------ |------ |------ |
| Unique validator | npm install --save mongoose-unique-validator|backend||

### secure password storage
| Plugin | install |from the folder:| Command |
| ------ | ------ |------ |------ |
| bcrypt | npm install --save bcrypt|backend||

### tokens
| Plugin | install |from the folder:| Command |
| ------ | ------ |------ |------ |
| jsonwebtoken | npm install --save jsonwebtoken|backend||

### Accept incoming files with multer
| Plugin | install |from the folder:| Command |
| ------ | ------ |------ |------ |
| multer | npm install --save multer|backend||

# Development
to start your API (back-end): 
```sh
cd backend
nodemon server
```
to start your application(front-end): 
```sh
cd frontend
ng serve
```
