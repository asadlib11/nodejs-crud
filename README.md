A Node js REST Backend with CRUD functionality.

This project is a crud backend server uses REST api for performing crud functionality.
This project is created using Node.js, Express.js and Mongoose for MongoDB

Server.js:
This is the backend server where you install your express js middleware and use bodyparser to parse requests of different content type. Then you configure database, connect to it, define the routes.
After that you start the server.

Routes in Server.js will call controller and controller will then call methods on specific routes where different methods for schemas are defined.