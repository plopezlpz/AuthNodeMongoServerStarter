# Description
Boilerplate for authenticating users with JWTs

# Prerequisites
This server connects to a MongoDB running on localhost and creates a DB called `auth`: `mongodb://localhost:auth/auth`

# Quick Start
1. run `npm install`
2. create a file called `config.js` in the root directory of the project and place your secret key, e.g.:
        module.exports = {
          secret: 'mySecretKey'
        };
3. run `mongod` to start MongoDB in your computer
4. run `npm run dev` to start the node server in dev mode (will redeploy automatically when there are code changes).

