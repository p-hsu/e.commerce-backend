# E.commerce BACKEND [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

****

## Project overview

This application is the backend that manages an internet retail company's product database built with Sequalize and Express.js - this application is a practice in ***O****bject-***R**elational **M***apping*.

### Project Status:

*ONGOING*

#### Issues to debug:

Running into error in Insomnia when trying to update 'Tag' database:

```
{
  "generatedMessage": false,
  "code": "ERR_ASSERTION",
  "expected": true,
  "operator": "=="
}
```

****

## MVP

### Project-build Aspects:

The following components are used to build the code for this project:

1. JavaScript >  Node.js > npm:
    - mysql2
    - Sequelize
    - Express.js
    - dotenv
2. MySQL Workbench
3. Insomnia Core


### Functionality:

* using Sequelize Model to build database tables:
    - 'Category', 'Product', 'Tag', 'ProductTag'
    - 'ProductTag' table used for relating 'Product' and 'Tag' table only
* using Express.js to perform RESTful CRUD operations
    - CREATE, READ, UPDATE, DELETE from all three database tables (please refer to the [walkthrough video](#Application-Walkthrough)

### Process:

* source starter code provided by the bootcamp program (please see [Credit](#Credit) section)
* `npm init` ran to create package.json file
* required packages installed as dependencies
* using MySQL Workbench for model data to sync and populate to
* using Insomnia Core to test `GET`, `POST`, and `DELETE` routes

****

## Installation

1. Clone this repository onto local workspace
2. Open Terminal (MacOS) or Git Bash (Windows) and change location to where you want the cloned directory
3. Type `git clone` and paste copied respository
4. Directory should include the following:
![Directory Structure:](./assets/images/dir-struc.png)

## Usage

***IMPORTANT >>>
    - rename `.env.EXAMPLE` to `.env`
    - change "//YOUR SQL PASSWORD HERE//" to your own sql password***

Copy and past the schema located in the `db` directory into your MySQL workbench

RUN WITH CLI:

- FIRST >>     `npm init`
- SECOND >>    `npm run seed`
- THIRD >>     `npm start`  

## Application Screenshots

## Application Walkthrough


****

## License

## Credit

* Full-stack Bootcamp Program @ [Washington University, Saint Louis](https://bootcamp.tlcenter.wustl.edu/) through [© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand](https://www.trilogyed.com/)
* [Sequalize documentation](https://sequelize.org/master/manual/)
* [Express.js APU documentaion](https://expressjs.com/en/5x/api.html)