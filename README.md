# ORM E-Commerce Back End
This project is an exercise in the use object relational mapping. This is a mock backend for an e-commerce website. It serves data stored in a SQL database. Data is created, read, updated, and deleted by the use of the Sequelize node package and defined within the routes folder. This database contains three main tables housing the pertinent information. They are Category, Product, and Tag.


##
This is an example of a get request to the route "/api/categories" As the route suggests when called it will retreive the Category table data. This data is returned as JSON and appears as so.

["/api/categories" Example](./readme-images/ECcatall.png "An example of the route slash API slash categories")


##
This is an example of a get request to retreive a single category in the categories table.

["/api/categories/:id"](./readme-images/ECcatone.png "An example of the route slash API slash categories slash id value")

##
This is an example of a get request to the route "/api/products" As the route suggests when called it will retreive the Product table data.

["/api/products" Example](./readme-images/ECprodall.png "An example of the route slash API slash products")

##
This is an example of a get request to retreive a single product in the categories table.

["/api/products/:id"](./readme-images/ECprodone.png "An example of the route slash API slash products slash id value")

##
This is an example of a get request to the route "/api/tags" As the route suggests when called it will retreive the Tag table data.

["/api/tags" Example](./readme-images/ECtagall.png "An example of the route slash API slash tags")

##
This is an example of a get request to retreive a single product in the categories table.

["/api/tags/:id"](./readme-images/ECtagone.png "An example of the route slash API slash tags slash id value")

##
To use this, after cloning down the repository you will need to perform an "npm install" for it's dependencies, a mysql initialization of the database stored within the schema.sql file in the db folder, and a "node seeds" command to insert the data in the seeds folder. Make sure to, include the .env file with the database name, your username and password, the server needs to this communicate with SQL. With all that done a simple "npm start" will load the server and all routes can be accessed via an API tool like insomnia, the get requests can be done simply by browser.