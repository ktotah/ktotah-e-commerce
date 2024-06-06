# E-commerce Back End
![License](https://img.shields.io/badge/License-MIT-blue.svg)

## Description
The E-commerce Back End project is a Node.js and Express.js-based application that serves as the backend for an e-commerce site. It uses Sequelize to interact with a MySQL database, allowing for the creation, retrieval, updating, and deletion of categories, products, and tags.

* **Motivation:** Developed to demonstrate the integration of a back-end server with a relational database using Sequelize, providing a practical example of managing e-commerce data.
* **Purpose:** To offer a robust backend solution for e-commerce platforms, facilitating efficient management of product information, categories, and tags.
* **Problem It Solves:** It streamlines the process of managing e-commerce data, reducing manual data handling and enhancing data integrity through relational database management.
* **What I Learned:** Through this project, I gained hands-on experience with Sequelize, MySQL, and creating RESTful APIs with Express.js.

## Table of Contents
* [Project Background](#project-background)
* [Installation](#installation)
* [Usage](#usage)
* [Video Demonstration](#video-demonstration)
* [License](#license)
* [Questions](#questions)

## Project Background
Initiated as a part of coursework for a Fullstack Coding Bootcamp, the E-commerce Back End project utilizes bootcamp-provided starter code to create a functional backend system for managing e-commerce data. This project demonstrates the application of Sequelize ORM for database interactions and Express.js for API routing.

## Installation 
To install and run the E-commerce Back End application locally:

1. Ensure Node.js and MySQL are installed on your machine.
2. Clone the repository to your local machine: `git clone https://github.com/ktotah/ktotah-e-commerce.git`.
3. Navigate to the project directory in your terminal.
4. Install the necessary dependencies by running: `npm install` in your terminal.
5. Create a `.env` file in the root directory and add your MySQL database credentials. You can easily do this by copying the code in the .env.EXAMPLE file and replacing `your_password_here` with your MySQL password.
6. Ensure that `require('dotenv').config();` is added at the top of your `server.js` file to load the environment variables.


## Usage 
After installation, follow these steps to use the application:

1. **Create the Database:** In your terminal, run:
    ```bash
    mysql -u root -p < db/schema.sql
    ```
2. **Seed the Database:** In your terminal, run:
    ```bash
    npm run seed
    ```
3. **Start the Server:** In your terminal, run:
    ```bash
    npm start
    ```
4. **Interact with the API:**
    - Use Insomnia or a similar tool to test the API routes. The server runs on `http://localhost:3001`.
    - Examples of API routes:
        - Get all categories: `GET http://localhost:3001/api/categories`
        - Get a single category by ID: `GET http://localhost:3001/api/categories/:id`
        - Create a new category: `POST http://localhost:3001/api/categories`
        - Update a category by ID: `PUT http://localhost:3001/api/categories/:id`
        - Delete a category by ID: `DELETE http://localhost:3001/api/categories/:id`


## Video Demonstration
A walkthrough video demonstrating the functionality of the application, including creating the schema, seeding the database, and starting the server, is available [here](INSERTLINK!!!!!).

## License
![License](https://img.shields.io/badge/License-MIT-blue.svg)

This project is licensed under the [MIT License](./LICENSE).
  
## Questions
For any questions or further information, please contact me.

* GitHub: [ktotah](https://github.com/ktotah)
* Email: [ket2137@columbia.edu](mailto:ket2137@columbia.edu)