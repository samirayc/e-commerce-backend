<div align="center">

# E-Commerce Backend

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js Badge](https://img.shields.io/badge/Node.js-393?logo=nodedotjs&logoColor=fff&style=flat)](https://nodejs.org/en)
[![Nodemon Badge](https://img.shields.io/badge/Nodemon-76D04B?logo=nodemon&logoColor=fff&style=flat)](https://nodemon.io/)
[![MySQL Badge](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=fff&style=flat)](https://www.npmjs.com/package/mysql2)
[![Sequelize Badge](https://img.shields.io/badge/Sequelize-52B0E7?logo=sequelize&logoColor=fff&style=flat)](https://sequelize.org/docs/v6/)
[![.ENV Badge](https://img.shields.io/badge/.ENV-ECD53F?logo=dotenv&logoColor=000&style=flat)](https://www.npmjs.com/package/dotenv)
[![Insomnia Badge](https://img.shields.io/badge/Insomnia-4000BF?logo=insomnia&logoColor=fff&style=flat)](https://insomnia.rest/)

</div>

## Description

For this application, given the starter code of a working Express.js API E-Commerce website, Sequelized was configured to use and interact with a MySQL database. The MySQL database includes tables for products, categories, tags, and product tags, in which requests and updates can be made through Sequelize queries.

## Table of Contents

* [Demo](#demo)
* [Installation](#installation)
* [Usage](#usage)
* [Technologies](#technologies)
* [Contact](#contact)

## Demo
View the full demo [here](https://drive.google.com/file/d/1UVmbFmFccEQw7S9XmtWLoUxceDBQDelg/view?usp=sharing)!

Example functionality:

GET all tags:

![GET all tags](public/images/GET-all-tags.png)

Create new tag:

![Create new tag](public/images/CREATE-tag.png)

Update tag:

![Update tag](public/images/UPDATE-tag.png)

Search id of tag to show that tag name was updated:

![Updated tag by id](public/images/UPDATED-tag-by-id.png)

Delete tag by id:

![Delete tag by id](public/images/DELETE-tag-by-id.png)

Check that tag was deleted:

![Check that tag was deleted](public/images/DELETE-after.png)

## Installation

* Clone repository to use this application on your local machine.
* Must have Node.js and MySQL installed to run the application. 
* Install necessary dependencies by navigating to the root directory and running `npm i`
* Create a file in the root directory titled `.env` and include database name and personal MySQL username and password.

## Usage

* Open MySQL using command `mysql -u root -p` and enter your MySQL password.
* Run `source db/schema.sql` to create database
* Seed database with `npm run seed`
* Start server with `npm start` command or, to start server with Nodemon, run `npm run watch`.
* Use [Insomnia](https://insomnia.rest/download) to interact through different routes.
* Having issues? Watch the [demo](https://drive.google.com/file/d/1aIqbkg0Giwn762jbxnFUW1A0CiEM5oGD/view?usp=sharing) to see the application in use. 

## Technologies

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Express.js](https://expressjs.com/)
* [Node.js](https://nodejs.org/en/)
* [Nodemon](https://www.npmjs.com/package/nodemon)
* [MySQL](https://www.mysql.com/)
* [dotenv](https://www.npmjs.com/package/dotenv)
* [Sequelize](https://sequelize.org/)

## Contact

Hi, my name is Samira Chetta! If you have any questions about this application or if you wish to contribute, I can be reached via email at samirachetta@gmail.com. Feel free to check out my other projects on my [github](https://github.com/samirayc)!

