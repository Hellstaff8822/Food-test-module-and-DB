# Food Test Module and DB 🍽️

## Description

This project is designed for **learning** how to work with databases, API requests, Webpack, JSON-server, and MAMP. It provides a simple food-related interface that interacts with a mock database.

This is a learning project where I have gained experience in:

* Setting up and configuring Webpack 📦
* Working with JSON-server for mock APIs 🌐
* Using MAMP for local PHP development 🐘
* Managing dependencies with npm 📦
* Making API requests and handling responses 🔄
* Structuring JavaScript code for better maintainability 🏗️

## Technologies

* HTML, CSS, JavaScript – *front-end structure and styling* 🎨
* Webpack – module bundler 📦
* JSON-server – mock database API 🌐
* MAMP – local PHP server 🐘
* Node.js & npm – package management 📦

## Installation

### Prerequisites

Ensure you have the following installed on your system:

* Node.js 🟢
* MAMP 🐘
* npm (comes with Node.js) 📦

### Installing Webpack

Install Webpack and Webpack CLI globally:

![Install Webpack globally](img/README/webpack-install-code.png)

Or install Webpack locally in the project:

![Install Webpack locally](img/README/local-install-webpack.png)

### Steps

1.  Clone the repository:

    ![Clone the repository](img/README/git-clone.png)

2.  Navigate to the project directory:

    ![Navigate to the project directory](img/README/cd.png)

3.  Install dependencies:

    ![Install dependencies](img/README/npm-install.png)

## Running the Project

### Start Webpack Development Server

![Start Webpack Development Server](img/README/webpack-npx.png)

This will start Webpack in watch mode to automatically rebuild changes.

### Start Webpack on a Specific Port (default 8080 or set your own)

![Start Webpack on a Specific Port](img/README/webpack-npx.png)

### Start JSON-server (default port 4000 or set your own)

![Start JSON-server](img/README/json-server-wach.png)

This will create a mock API at `http://localhost:4000`.

### Start MAMP (for PHP Server)

1.  Open MAMP and start the Apache server.
2.  Move the project folder to the MAMP `htdocs` directory.
3.  Access `http://localhost/Food-test-module-and-DB-main/server.php`.

## API Endpoints

* Get all food items:

    ![Get all food items](img/README/GET.png)

* Add a new food item:

    ![Add a new food item](img/README/POST.png)

* Update a food item:

    ![Update a food item](img/README/PUT.png)

* Delete a food item:

    ![Delete a food item](img/README/DELETE.png)

## Common Issues & Fixes

### JSON-server not starting

* Error: `Error: listen EADDRINUSE: address already in use 4000`
* Solution: run:

    ![Kill port](img/README/kill-port.png)

    and restart the server.

### Webpack not bundling

* Solution: ensure Webpack is installed, and try:

    ![npm run build](img/README/npm-build.png)

## Future Improvements 🚀

* Integrate a real database (e.g., MongoDB, MySQL) 🗄️
* Add authentication 🔐
* Improve the user interface with a front-end framework (React, Vue) ⚛️
* Implement sorting and filtering for food items 🔍
* Enhance error handling and API validation ⚠️
* Optimize Webpack configuration for better performance ⚡

Now you can run the project and experiment with databases, API requests, and Webpack! 🎉
