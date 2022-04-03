# Gettin Techie
[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

## Description 
Welcome to the Gettin' Techie blog! Here you will be able to read about new applications, how to debug existing codebases, learn about new advancements and technologies, and find tutorials from fellow developers. It was built using Express, Express-Session, MySQL2, Sequelize, Handlebars, Bcrypt, and Dotenv. You can find the fully deplyed site [here.](https://gettin-techy.herokuapp.com/)
 
## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Questions](#questions)

## Installation 
If you would like to install the codebase: 
First clone the repository from GitHub and then install Node. Install express, dotenv, mysql2, sequelize, bcrypt, connect-session-sequelize, express-handlebars, express-session, and nodemon by running `npm i` in your command line.

You will then need to create a .env file within the root folder. The file will need to include: DB_USER=(your username), DB_PW=(your password), and DB_NAME=gettintechy_db

To set up the database run `npm start`. If you are making changes you may want to change force: false to force: true in server.js.

If you need to update any code and would like to have the server running and update during the changes run nodemon `npm run watch`

## Usage 
Run `npm start` in your command line and open http://localhost:3001/ or visit the deployed site [here.](https://gettin-techy.herokuapp.com/)

The main homepage should look similar to:
![Image of website](https://ngranzow.github.io/gettin-techy/assets/images/Gettin-Techie.png)

## License 
To read the ISC license click [here](https://opensource.org/licenses/ISC)

## Contributing 
Please read the [installation](#installation) section.

## Questions
If you have any questions please contact email me [here](mailto:nate.granzow@gmail.com). You can also view more of my projects [here](https://github.com/ngranzow/).