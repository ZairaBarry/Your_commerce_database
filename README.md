# Your_commerce_database

## Description

This application  is  the back end for an e-commerce site.It takes a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## Installation

In order the app to run you need to install the MySQL2 and Sequelize packages to connect to a MySQL database.
Ypu will also need to use dotenv.package to use store sensitive data.

## Usage

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

![Screenshot of Insomnia](/assets/Screenshot%20.jpg)


link to the walkthrough video-  https://drive.google.com/file/d/1VIz93opZwK1DKqJiBd7j4PQOUHrH9An1/view

## TESTS
In order to run the application run the command node server.js and test routes in Insomnia or Postman.

## License
This application is licensed under MIT