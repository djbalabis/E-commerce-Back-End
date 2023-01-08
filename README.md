# E-commerce-Back-End

## Description
This application serves as the backend of an e-commerce site, which uses a functional Express.js API and uses Sequelize to interact with a MySQL database.

When the user adds their database name, MySQL username, and MySQL password to a ".env" (environmental variable file), the user is able to connect to a database using Sequelize. When entering schema and seed commands, a development database is created and is seeded with test data. When the application is invoked, the server is started and Sequelize models are synced to the MySQL database, with API GET routes for categories, products, and tags display a formatted JSON using Insomnia. When testing API POST, PUT, and DELETE routes in Insomnia, users can create, update, and delete data in the database.

MySQL2 and Sequelize packages connect the Express.js API to a MySQL database. The dotenv package uses environmental variables to store sensitive data, such as the user's MySQL username, password, and database name. On server start, the application syncs Sequelize models of Category, Product, Tag, and ProductTag to a MySQL database and includes associations between these models.

## Built With
* JavaScript
* Express.js
* Sequelize
* Mysql2
* dotenv

## Installation
1. Clone the Git repository and run as an integrated terminal.
2. run "npm install"

## Usage
Clone the repository, navigate to the project folder in your CLI and use the npm run seed to seed data to the database and test CRUD routes.

## Mock-up

The following images show the web application's appearance and functionality:

![This is a screenshot of the E-commerce Back End!](./images/Back%20End%201.png)
![This is a screenshot of the E-commerce Back End!](./images/Back%20End%202.png)
![This is a screenshot of the E-commerce Back End!](./images/Back%20End%203.png)
![This is a screenshot of the E-commerce Back End!](./images/Back%20End%204.png)
![This is a screenshot of the E-commerce Back End!](./images/Back%20End%205.png)

## Demonstration
https://photos.app.goo.gl/RHMEp4uLwzWTiFt79