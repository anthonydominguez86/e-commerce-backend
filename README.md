# The Assignment: E-commerce Backend

* GIVEN a functional Express.js API

* WHEN I add my database name, MySQL username, and MySQL password to an environment variable file

* THEN I am able to connect to a database using Sequelize

* WHEN I enter schema and seed commands

* THEN a development database is created and is seeded with test data

* WHEN I enter the command to invoke the application

* THEN my server is started and the Sequelize models are synced to the MySQL database

* WHEN I open API GET routes in Insomnia Core for categories, products, or tags

* THEN the data for each of these routes is displayed in a formatted JSON

* WHEN I test API POST, PUT, and DELETE routes in Insomnia Core

* THEN I am able to successfully create, update, and delete data in my database

The assignment is a complete backend of an E-commerce website that handles the products, prices, and if it was live potential sales of items. To initialize this application the user must open the terminal and npm install or npm i this will import node modules, dotenv, express, mysql2, and sequelize. These are all listed on the dependencies in the package.json file. It will also create a package-lock.json. After this installation copy the contents of the file named schema.sql located in the db folder in the MySQL workbench to create the database needed for the application to function. Next the user will have to create the .env file filling out the DB_USER, DB_PW, and using the DB_NAME = ecommerce_db. Once this is completed use the command npm run seeds this will access all of the data in the seeds folder and insert it into the database ecommerce_db this is live in MySQL workbench. Now we can run the npm start or npm run watch either one will start the server the second command will do it using nodemon. Then you should have a prompt returned that the server is now listening on 3001. Next open the Postman application or Insomnia as listed above so one can can utilize the POST, PUT, and DELETE routes based on the addresses localhost:3001/api/products, localhost:3001/api/tags, and localhost:3001/api/categories. 

# Lessons:
This assignment was unlike any other because we were given a large amount of starter code and were tasked to refactor or complete what was not completed. I think this would be a great representation of a real world scenario of fixing broken code or updating old code that we would encounter on the job. It taught me to really look at the code I was given to understand its functioning and finish what was started. The first step was update the models with sets of given values as numbers, strings, or decimals then move onto the routes and relationships for the products, categories, and tags. This assignment showed so much of the backend side of the full stack and how it can become very complex very quickly. The big lesson I took from this assignment is staying organized and writing clean easy to follow code so others programmers can see how it functions. 

# Takeaways: 
Takeaways are the best parts of these assignments they are all very difficult because we are practicing code that we have barely just started learning. These homeworks allow us to get the practice and experience of using this new code and making it work either from starter code or starting from a clean slate and writing it all ourselves. Every assignment takes me deeper down a rabbit hole that I have to figure out what is going on. This particular assignment was a very deep rabbit hole but with the comments provided  I was able to figure out what was happening and make it work. This is the biggest takeaway from this assignment was actually figuring out how it all functions and actually works.

# Screenshots:

<img width="1440" alt="E-commerce 1" src="https://user-images.githubusercontent.com/73844796/111808002-f408cc80-88a9-11eb-87fe-0c56a7608156.png">

<img width="1440" alt="E-commerce 3" src="https://user-images.githubusercontent.com/73844796/111808746-accf0b80-88aa-11eb-854d-034cb2201132.png">

<img width="1440" alt="E-commerce 4" src="https://user-images.githubusercontent.com/73844796/111808843-c07a7200-88aa-11eb-98ef-396f1c47c6a2.png">

<img width="1440" alt="E-commerce 5" src="https://user-images.githubusercontent.com/73844796/111808895-cec88e00-88aa-11eb-8a94-e7542aa80ff6.png">

More Screenshots available in the assets folder 

# Video Walkthrough:


* https://drive.google.com/file/d/1T-Jn6DlHpZge_yvpi0eaUClufl8Ats7i/view?usp=sharing - Video 1 

* https://drive.google.com/file/d/1Q_Mjq4FXa_QZeQSQKJtETHC6aBD5lyJb/view?usp=sharing - Video 2 