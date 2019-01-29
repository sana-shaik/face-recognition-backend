## Added Packages

To initialize npm into the folder. Create Package.json

## `npm init` 

Added nodemon package as dev dependency

## `npm install --save-dev nodemon`

Added express for the server and body-parser to read json files json.parse()

## `npm install express`
## `npm install body-parser`

body-parser is a middleware component so you have to use below.

## `app.use(bodyParser.json())`

Added bcrypt-nodejs for Storing Passwords

## `npm install bcrypt-nodejs`

Added CORS to allow Access control 

## `npm install cors`

cors is also a middle ware component so you have to use below.

## `app.use(cors());

Added script in package.json with 
## "start" : "nodemon server.js"

To run the Application

## `npm start`