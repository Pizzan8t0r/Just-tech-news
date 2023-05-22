# Just Tech News—a tech news website where users can post, upvote, and comment on links to news articles.
As developers in an ever-changing field, success relies on keeping up-to-date with modern practices and tools.


## 
This project is centered around object-relational mapping (ORM), a technique that allows developers to convert data between incompatible type systems using object-oriented programming principles. This application works with Sequelize, an ORM library that creates a virtual object database that can be used within your code while managing a relational database. This allows you to set up and completely manage objects using JavaScript, while Sequelize translates your code into database schema and queries using SQL.
The goal is to get a web server up and running using Sequelize, so that I can create database tables.

## 
Orm is a third party library that acts as an interpreter that generates the Sql query for you. When you request data the ORM translates that data into an object which is returned to your server by using your preferred coding language. 
ORM’s are able to cut down on coding time as well as recode potential for error when programming, ensuring that SQL queries are optimized.  Object relational mapping will map keys into a table in a DBMS, the keys become the headers and the values become the data inside the table. It makes interfacing with data a seamless experience in web applications.
![Screenshot 2023-05-21 at 23 14 59 (2)](https://github.com/Pizzan8t0r/Just-tech-news/assets/131811220/528cd013-02fa-4d4f-a19f-38032c1cbc56)


##  Skills applied into this project. 

* Configure the Sequelize ORM in a Node.js application.
* Create models for categories, products, and tags in a relational database and a through table that will connect the product and tag models.
* Define and implement CRUD methods, using Sequelize to interact with your models in each API endpoint through proper RESTful commands (GET, POST, PUT, DELETE).
* Create and implement Sequelize associations to join tables.
* Use environment variables to protect sensitive data, such as your MySQL username and password.

##  Steps I took to make this application happen: 

* Implement the Sequelize ORM in a Node.js application.
* Define models that use datatype validations.
* Implement CRUD methods using Sequelize.
* Implement Sequelize associations to join one or more tables.
* Configure Heroku for deployment of an application using Sequelize & MySQL.
* Use the bcrypt package to hash password information and use environment variables to protect sensitive data.
* Set up the application to use Sequelize to manage SQL data.
* Used environment variables to protect the sensitive data.
* Created a user table using Sequelize models.
* Created all of the server endpoints using RESTful API standards to work with the user model’s data.

Sequelize, is an object-relational mapping (ORM) library, to simplify your MySQL queries, add password hashing so that users can create secure passwords, it’s a promise-based Node.js ORM for Postgres, MySQL, MariaDB, SQLite, and Microsoft SQL Server. It features solid transaction support, relations, eager and lazy loading, and read replication. It sits between the server's API endpoints and the SQL database to translate and normalize data between JavaScript and SQL,  using JavaScript to model the database structure, and Sequelize will handle all of the SQL queries.
The biggest benefit that an ORM like Sequelize offers is sparing us from spending a lot of time writing SQL to define our tables and queries. Instead, we can use object-oriented concepts to model database tables using JavaScript classes. This lets us add validators and custom rules to the SQL data where SQL sometimes falls short.
![Screenshot 2023-05-21 at 23 15 16 (2)](https://github.com/Pizzan8t0r/Just-tech-news/assets/131811220/08534b88-f575-4a1b-9f56-650c9cbf8e48)

Sequelize goes a step further by taking object-oriented JavaScript concepts and applying them to how we set up the SQL tables. This is done by using Sequelize's model class where, essentially, we create our own JavaScript class and define the columns, data types, and any other rules we need the data to adhere to.
This class will serve as a layer between the API and the database and will handle all transactions of data between the two. As we'll see, it'll provide a lot more flexibility and functionality that we would otherwise have to create on our own.
![Screenshot 2023-05-21 at 23 15 07 (2)](https://github.com/Pizzan8t0r/Just-tech-news/assets/131811220/56c1cb15-801b-4153-9739-2be9ae4a8787)
Sequelize's offerings are twofold. For us, the developers, we get to use object-oriented principles to model and manipulate the data. This makes our lives easier as these actions and concepts are more geared toward a language like JavaScript. This is the side we get to interface with.
The other side of this is that after we interface with Sequelize, the library interprets our request to it and goes ahead to convey the request to the database and return to us with a response. This means we don't have to directly work with the SQL database, for the most part.
