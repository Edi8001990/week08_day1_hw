

### Questions

1. What is responsible for defining the routes of the `games` resource?
Publish:
1. Games:data-loaded
Subscribe:
1. GameView:game-delete-clicked
2. GameView:game-submitted


2. What are the the responsibilities of server.js?
-- Make a connection with database and establishing Hostname


3. What are the responsibilities of the `gamesRouter`?
CRUD?

4. What process does the the client (front-end) use to communicate with the server?
-- Sending GET request to the server and getting reply from the server

5. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs
6. Which of the games API routes does the front-end application consume (i.e. make requests to)?
7. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?

## Extension

Why do we need to use [`ObjectId`](https://mongodb.github.io/node-mongodb-native/api-bson-generated/objectid.html) from the MongoDB driver?
