# Jobly Backend

This is the Express backend that supports [Jobly](https://github.com/hannahanela/react-jobly). This code was provided with complete features to expedite the React build. If you'd like to view my own work in Express, please visit [my express-jobly repository](https://github.com/hannahanela/express-jobly).

## Developer Environment Setup

This app uses a PostgreSQL database. You'll need Node 18 and PostgreSQL 12 or later.

To install dependencies:

`npm install`

jobly.sql is provided to create and seed the database.

`psql -f jobly.sql jobly`

### To start the server:

`node server.js -p 3001`

If you need to see something in your browser, you can use [http://localhost:3001/jobs](http://localhost:3001/jobs).

### To run tests:

`jest -i`
