homework


### Questions

1. What is responsible for defining the routes of the `games` resource?

A. createRouter in the server/helpers/createroutes.js

2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?

A. The client is responsable for collectiong user input from the new game form also displaying the data from the database. it also holds all the logic that takes place when createing editing and deleting a game
The server side is responsable for creating the database, getting data from the database and editing the database with the user input.

3. What are the the responsibilities of server.js?

A. Server.js creates the database, retrieves all the games and creates an array of game objects held in the gamesCollection variable.It also creates the router and sets the inital urls ie(/api/games)


4. What are the responsibilities of the `gamesRouter`?

A. The games router takes the collection of games and creates the router links.

5. What process does the the client (front-end) use to communicate with the server?

A. the client uses a form to interact with the database, on submit it calls several functions with interact with the database.

6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs

A. the fetch method has an optional second perameter, it's a init object that allows you to control diffrent settings eg.method,header,body and mode.

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?

A. router.post('/'),router.delete('/:id'),router.put('/:id'),router.get('/:id'),router.get('/')

8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?

A. the mongo db driver allows working with databases. examples are conecting to db instances, read and write data, access return values using asynchronous javascript.

Extention
A. we use ['ObjectId'] as An ObjectID creates an integer field to use as a unique identifier for rows in a database.


