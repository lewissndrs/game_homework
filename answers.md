1. What is responsible for defining the routes of the games resource?
    -create_router.js

2. What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
    -The server is responsible for communicating directly with the database. The client assembles requests and user interaction.

3. What are the the responsibilities of server.js?
-Server.js is responsible for creating the express instance, setting ports and setting up the connection to the database.

4. What are the responsibilities of the gamesRouter?
    -The gamesRouter is responsible for defining routes relating to '/api/games'.

5. What process does the the client (front-end) use to communicate with the server?
    - the GameService sends an http request with a JSON payload to the server.

6. What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
    -an init options object.

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
- http://localhost:3000/api/games/

8. What are we using the MongoDB Driver for?
- in server.js, the driver is setting up the connection to the database and pulling through the data from the database.

9. Why do we need to use ObjectId?
    -ids in MongoDB are key object pairs, and the object itself is a unique object type.
