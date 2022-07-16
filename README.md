# e-commerce_backEnd
## Description
This is an application for an e-commerce backend.
This backend uses MYSQL2, Express, Sequelize and dotenv.

## Installation
npm init
npm install

## Usage
create db from schema.sql
npm run seed
npm start

## Acceptance Criteria
GIVEN a functional Express.js API <br />
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file <br />
THEN I am able to connect to a database using Sequelize <br />
WHEN I enter schema and seed commands <br />
THEN a development database is created and is seeded with test data <br />
WHEN I enter the command to invoke the application <br />
THEN my server is started and the Sequelize models are synced to the MySQL database <br />
WHEN I open API GET routes in Insomnia for categories, products, or tags <br />
THEN the data for each of these routes is displayed in a formatted JSON <br />
WHEN I test API POST, PUT, and DELETE routes in Insomnia <br />
THEN I am able to successfully create, update, and delete data in my database <br />
