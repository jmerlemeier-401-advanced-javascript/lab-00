# LAB - 00

## 401 JS Deployment

### Author: Julie Erlemeier

### Links and Resources
* [Travis](https://www.travis-ci.com/jmerlemeier-401-advanced-javascript/lab-00)
* [Heroku](https://deployment-00.herokuapp.com/)

#### Documentation
* [jsdoc](https://github.com/codefellows/code-401-JS-prework/tree/master/deployment-workshop)
* [How To Video](https://www.youtube.com/watch?v=s8tQd4akmb8&feature=youtu.be)

### Modules
#### `pol.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
The isAlive() method returns a boolean based on the arg sent in.

### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns true or false
* Endpoint: `/docs`
  * Renders Developer Documentation
  
#### Tests
* Unit Tests: `npm run test`
* Lint Tests: `npm run lint`
* Assertions Made
  * Assert that isAlive() properly returns a boolean
* Assertions Remaining
  * ... Things I want to tests, but didn't yet.
