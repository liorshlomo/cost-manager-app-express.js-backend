# cost-manager-app-express.js-backend

The Cost Manager App is a web application that allows you to keep track of your daily expenses. 
The app lets you add, edit and view your expenses, create reports and see your expenses history.


This code defines the Mongoose schema and models for three MongoDB collections: Cost, Report, and User. 
It also defines a router for an Express app that implements a POST endpoint for adding new costs to the Cost collection in the database.
The costmanager.js file creates a connection to a MongoDB database hosted on MongoDB Atlas and exports the Mongoose library as a module.
The costmongconn.js, reportmongconn.js, and usermongconn.js files each define a Mongoose schema for a MongoDB collection and create a Mongoose model from the schema. 
The Cost model represents the cost collection, the Report model represents the report collection, and the User model represents the user collection.

The addcost.js file defines an Express router that implements a POST endpoint for adding new costs to the Cost collection in the MongoDB database. 
It uses the Cost model to perform CRUD operations on the cost collection. It also imports the User and Report models to perform validation 
and update the report collection, respectively.

## Usage
The app has four main features:

1. Add a new cost
2. Edit an existing cost
3. View your expenses history
4. Generate reports

## Dependencies
The following dependencies are used in this project:

- express: for building the server-side of the app.
- mongoose: for connecting to and interacting with the MongoDB database



