# React-Seed-Auth0 With Redux

This is a fully functional basic React app seed. It comes with Redux and Passport/Auth0 already set up, and uses Node, Express, Massive, and SQL for the back end.

## To Use This Seed

1. Clone this seed
2. In the terminal, navigate to the project folder and run 'npm i'
3. Create a 'config.js' file in the server folder (It is already ignored).

#### Should look something like this
```javascript
module.exports = {
  secret: "werlhkh4345^%#%lijlskdjre45hlkhjsir3$%^",
  auth0:{
    clientID: "Auth0 client ID goes here",
    clientSecret: "Auth0 client secret goes here"
  },
  connectionString: "Your DB connection string goes here", 
  port: 3000
};
```

4. Use npm start while building the front end
5. Navigate to the project folder and run nodemon to connect to your back end
