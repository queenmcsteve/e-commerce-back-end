# Ecommerce Backend

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description:

This project is the backend for an e-commerce site, using Express.js and Sequelize to interact with a MySQL database.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Table of contents:

- [Installation](#installation)
- [Usage](#usage)
- [Demonstration](#demonstration)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

# Installation Instructions

Install dependencies (mysql2, express, sequelize, dotenv) using `npm i`, connect to MySQL and run db/schema.sql to create database. Then from terminal, run `node seeds/index.js` or `npm run seed` to seed data. Finally, run `node server.js` or `npm start` to start the server.

# Usage

See the demo video to see database queries using Insomnia.

# Demonstration

As this is a command line program, there are no screenshots of the program itself. Please watch the following demo video to see the program in action.

[Demonstration Video](https://watch.screencastify.com/v/LxSVKuURzqtTbWjHcoVO)

# Contributing

Feel free to clone or fork.

# Contact

If you have any questions you can reach me via:

- Github: [queenmcsteve](https://github.com/queenmcsteve)
- Email: [queen.mcsteve.666@gmail.com](mailto:queen.mcsteve.666@gmail.com)

# License

[This project is licensed under the terms of the MIT license.](https://opensource.org/licenses/MIT)
