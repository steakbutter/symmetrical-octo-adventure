# Symmetrical Ecommerce Back End 

## Description

This is an Ecommerce back end application using sequelize. <br>
By seeding the data to the database using sequelize, this Ecommerce application is capable of adding, updating or deleting products. <br>
By executing the correct routes, I learned the importance of SQL and express in a real world common situation like an Ecommerce database. <br>
Github repository: https://github.com/steakbutter/symmetrical-octo-adventure <br>
Video Demo link: https://drive.google.com/file/d/1Dx1T_YYvFaDWK9_7qJ0Z9a3BD4rvtv5S/view?usp=sharing 

## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

Type 'npm install' in the terminal to install all dependencies inside the package.json file. <br>
Dependencies used in this project are: <br> 
- Express
- pg
- dotenv
- sequelize

## Usage

Create the database inside the terminal by going into the db folder and typing 'psql -U postgres'<br>
type in your password. <br>
type \i schema.sql to create the 'ecommerce_db' database <br>
type \q to exit psql <br><br>
Next we are going to use the seed script inside package.json file by typing "npm run seed" inside the terminal. <br>
This will seed and fill our database with the provided information inside the seed folder. <br><br>

Using the thunder client extension inside VS code, it is time to GET routes for all categories, all products and all tags <br><br>


 Next we are going to demonstrate GET routes for a single category, product and tag <br><br>
![GET ONE ROUTE](https://github.com/steakbutter/symmetrical-octo-adventure/assets/156126513/5eb87903-0971-467b-9e0e-4c5ead7da061) <br><br>


 Finally we are going to demonstrate how to create a new product, update the information of that new product and delete the new product. <br><br>
 


## Credits

https://sequelize.org/docs/v6/core-concepts/model-basics/ <br>
https://sequelize.org/docs/v6/core-concepts/validations-and-constraints/ <br>
https://sequelize.org/docs/v6/core-concepts/assocs/ <br>
## License

N/A.
