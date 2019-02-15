# graphql-react-api
A GraphQL API 

# Startup (Frontend)
1) change directory to frontend folder
2) run "npm install"
3) run "npm start"

> note: GraphQL backend powered by MongoDB Atlas (personal database), you must create your own database
  in order for the full application to work

# Backend Setup

1) In graphql-react-api folder(root directory), run "npm install"

2) Create an account on [MongoDB Atlas] (https://www.mongodb.com/cloud/atlas)

3) Follow instructions on MongoDB to create a cluster

3) Create a MongoDB User with Admin privileges

4) Click Security tab and add your IP address to whitelist

4) edit nodemon.json file with correct environment variables 
(       "MONGO_USER": "YOUR_USER_NAME_HERE"
        "MONGO_PASSWORD": "YOUR_PASSWORD_HERE",
        "MONGO_DB": "NAME_OF_DATABASE_HERE" )

5) run npm start to start server on port 8000


