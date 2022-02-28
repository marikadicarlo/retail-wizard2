# retail-wizard2

[Walkthrough Videos](https://drive.google.com/drive/folders/1IZDMgrhbS4oWKBEOIASOgr-PEjFQQwjW)


# Description
This is the back end for an e-commerce site, Retail Wizard. This application takes a working Express.js API and configures it to use Sequelize to interact with a MySQL database.

## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria
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

## Table of Contents
- [Installation](#Installation)
- [Links](#Links)
- [Questions](#Questions)

## Installation

Use `cd` and `git clone` https://github.com/marikadicarlo/retail-wizard2.git 

Run `npm init`, and make sure the `package.json` is updated with "start": "node server.js"

Run `npm install express sequelize mysql2` to install dependencies. To use the application locally, run `node server.js`.

## Links
[Link to the GitHub Repository](https://marikadicarlo.github.io/retail-wizard2/)


## Questions
Contact me with any questions at <mdicarlo19@yahoo.com> or [visit my GitHub page](https://github.com/marikadicarlo)