# Object-Relational-Mapping-ORM-E-Commerce-Back-End

Building an E-Commerce application back end by editing starter code then using a working Express.js API to use Sequelize and testing with Postman.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
## How to run application

In the terminal run "npm i" to install all requirements, then "npm run seed" to fill in the table data, finally "npm start" to start the application.

The following animation shows installing, seeding, and starting the application in the terminal:

![In the terminal, the user runs "npm i," "npm run seed," and "npm start.".](./Assets/Install-seed-start-app.gif)

## How to test application

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Postman:

![In Postman, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/Get-all-Categories-Products-Tags.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Postman:

![In Insomnia Core, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/Get-1-Category-Product-and-Tag-attempts.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Postman:

![In Insomnia Core, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/Post-Put-and-Delete-attempts.gif)