[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# shopping-backend

This project demonstrates ability using Sequelize as an ORM to interface with a MySQL database in order to create a backend database and API for an e-commerce site. It has functionality to track products, categories of products, and tags for defining and sorting the products. This backend technology could easily be implemented with a front end to creat a full stack e-commerce site/tracker.

In this project, I learned how to use an ORM to simplify the use of a SQL (MySQL) database in creating a practical API. All the queries are handled through JavaScript by Sequelize. I solidified my knowledge of SQL databases and how to implement them in the setting of modern web applications. I also practiced clean code with a logical file structure, solid naming conventions, and good readability. My biggest challenge was making sure to get the through table written correctly and functioning properly.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [Questions](#questions)

## Installation

The application is strictly back-end software, so the user will need to run `npm i` to install all of the required packages and dependencies, and then either plug it into their own front end or use something like Insomnia to test the routes and database functionality. After everything is installed and the database has been created on the local machine with mysql, be sure to execute `npm start` to start the server before testing routes and functionality.

## Usage
##### [Back to Table of Contents](#table-of-contents)

The first thing the user will need to do to use/test the code is execute `npm i` to install all dependencies. Then they will have to create the database in mysql on the local machine using `mysql -u root -p` and then execute `source db/schema.sql`. After the database has been created, the user will need to enter their credentials into the .env file, and if they want to use the seed data that is provided with the application, run `npm run seed`. Finally, to start the app database, the user will need to execute `npm start` to start the server and then run the routes in a test environment like Insomnia or plug in the API to their own front end.

## Credits
##### [Back to Table of Contents](#table-of-contents)

For this project, I mainly referenced the documentation for [Node.js](https://nodejs.org/api/) and [Express.js](https://www.npmjs.com/package/express), as well as [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm), [Sequelize](https://sequelize.org/docs/v6/category/core-concepts/), and [mysql2](https://www.npmjs.com/package/mysql2).

## Questions
##### [Back to Table of Contents](#table-of-contents)

You can view my other projects on GitHub: [cynogriffin](https://github.com/cynogriffin)

If you have any questions or comments, please feel free to contact me via email at griffinc6@gmail.com.

Connect with me on [LinkedIn](https://www.linkedin.com/in/cody-griffin-0a74b1222/) and catch me on my develper blog [The Cozy Coding Corner](https://cynogriffin.hashnode.dev/)!

---
Copyright &copy; 2022 Cody Griffin. All rights reserved.

Licensed under the [GPL v3 License](https://www.gnu.org/licenses/gpl-3.0).  