# Jessica Chen - E-Commerce Back End

## Columbia University Bootcamp - Object-Relational Mapping (ORM) Challenge: E-commerce Back End

> This repository contains my code for an e-commerce website backend to manage category, product and tag data using API endpoints.
> Link to Walkthrough Video: https://drive.google.com/file/d/1XUQ_faCVj8VyAXR5qZyRDVtz9XGVyG8v/view

## Table of Contents

- [General Info](#general-information)
- [Project Requirements](#project-requirements)
- [Installation](#installation)
- [Screenshots](#screenshots)
- [Source Code](#source-code)
- [Contact](#contact)

## General Information

This repository contains my code for an e-commerce website backend to manage category, product and tag data using API endpoints. The endpoints can be used to get, create, update and delete data.

## Project Requirements

User Story:

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

Acceptance Criteria:

```
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

## Installation

1. Clone the repository to your local drive.
2. Run `npm i` in order to install the npm package dependencies as specified in the package.json file.
3. Run `npm run seed` to seed the database.
4. Run `npm start` in the command line to use the application.

## Screenshots

![GET Request](./assets/GET%20Request.png)
![POST Request](./assets/POST%20Request.png)

## Source Code

Source Code Reference: https://github.com/coding-boot-camp/fantastic-umbrella

## Contact

Created by: Jessica Chen | jessicachen28@gmail.com
