# MongoDb/Express.js/Node.js Starter Boilerplate

> Use this boilerplate to create a MERN application (R is for React, but compatible with any view library that can make HTTP requests)

## FEATURES

- Set up to use Mongoose as ORM for MongoDb
- Uses Joi for schema validation
- Example model files and routes included

## SETUP INSTRUCTIONS

1. Run `npm install` to install Node dependencies and generate `node_modules`
2. Create a `.env` file in the root directory. Add variables for _PORT_ and _CONNECTION_STRING_
3. Set each equal to respective values. Generate a connection string from the MongoDb website.
4. Run `npm start` and verify that the console is logging "Connected to MongoDb..."
5. Make sure to import any routes into `index.js` and create a unique URL for those routes

```
PORT=9001
CONNECTION_STRING="mongodb+srv://<username>:<password>@<cluster name>.nm4by.mongodb.net/<database name>?retryWrites=true&w=majority"
```
