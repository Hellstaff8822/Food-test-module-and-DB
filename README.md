Food Test Module and DB

Description

This project is designed for learning how to work with databases, API requests, Webpack, JSON-server, and MAMP. It provides a simple food-related interface that interacts with a mock database.

This is a learning project where I have gained experience in:

Setting up and configuring Webpack

Working with JSON-server for mock APIs

Using MAMP for local PHP development

Managing dependencies with npm

Making API requests and handling responses

Structuring JavaScript code for better maintainability

Technologies Used

HTML, CSS, JavaScript – Front-end structure and styling

Webpack – Module bundler

JSON-server – Mock database API

MAMP – Local PHP server

Node.js & npm – Package management

Installation

Prerequisites

Ensure you have the following installed on your system:

Node.js

MAMP

npm (comes with Node.js)

Installing Webpack

Install Webpack and Webpack CLI globally:

npm install -g webpack webpack-cli

Alternatively, install Webpack locally in the project:

npm install --save-dev webpack webpack-cli

Steps

Clone the repository:

git clone <repository_url>
cd Food-test-module-and-DB-main

Install dependencies:

npm install

Running the Project

Start Webpack Development Server

npx webpack --watch --mode development

This will start Webpack in watch mode to automatically rebuild changes.

Start Webpack on a Specific Port (default 8080 or set your own)

npx webpack serve --port 8080

Start JSON-server (default port 4000 or set your own)

npx json-server --watch db.json --port 4000

This will create a mock API at http://localhost:4000.

Start MAMP (for PHP Server)

Open MAMP and start the Apache server.

Move the project folder to the MAMP htdocs directory.

Access http://localhost/Food-test-module-and-DB-main/server.php.

API Endpoints

Get all food items

GET http://localhost:4000/foods

Add a new food item

POST http://localhost:4000/foods
Content-Type: application/json
{
  "name": "Pizza",
  "price": 10.99
}

Update a food item

PUT http://localhost:4000/foods/1
Content-Type: application/json
{
  "name": "Burger",
  "price": 8.99
}

Delete a food item

DELETE http://localhost:4000/foods/1

Common Issues & Fixes

JSON-server not starting

Error: Error: listen EADDRINUSE: address already in use 4000
Solution: Run:

npx kill-port 4000

and restart the server.

Webpack not bundling

Solution: Ensure Webpack is installed and try:

npm run build

Future Improvements

Integrate a real database (e.g., MongoDB, MySQL)

Add authentication

Improve UI with a front-end framework (React, Vue)

Implement sorting and filtering for food items

Enhance error handling and API validation

Optimize Webpack configuration for better performance

Now you can run the project and experiment with databases, API requests, and Webpack! 🚀
