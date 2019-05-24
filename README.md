![CF](http://i.imgur.com/7v5ASc8.png) LAB - 09
=================================================

## API Server

### Author: Jagdeep Singh

### Links and Resources
* [submission PR](https://github.com/401-advanced-javascript-js/lab-09-api-server/pull/2)
* [travis](https://www.travis-ci.com/401-advanced-javascript-js/lab-09-api-server)
* [back-end](http://api-server-js.herokuapp.com/api/v1/)
<!-- * [front-end](http://xyz.com) (when applicable) -->

#### Documentation
* [api docs](http://api-server-js.herokuapp.com/api/v1/api-docs/)
* [jsdoc](https://401-advanced-javascript-js.github.io/lab-09-api-server/)

### Setup
#### `.env` requirements
* `PORT` - Port Number
* `MONGODB_URI` - URL to the running mongo instance/db

#### Running the app
* `npm start`

  Endpoint: `/api/v1/categories`
    * returns all categories

  Endpoint: `/api/v1/categories/:id`
    * returns category with passed id

  Endpoint: `/api/v1/players`
    * returns all players

  Endpoint: `/api/v1/players/:id`
    * returns player with passed id

  Endpoint: `/api/v1/teams`
    * returns all teams

  Endpoint: `/api/v1/teams/:id`
    * returns team with passed id
  

#### Tests
* How do you run tests?

  `npm test`

#### UML
![UML of Data Flow](./assets/uml.jpeg)