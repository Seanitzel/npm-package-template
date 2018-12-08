# New NPM Package Template

### Thinking about building your own npm package? 
### This is where you start!

This template saves you all the head-ache of configuring a work environment for a new library...

Things have gotten way too complicated these days...
We get an idea, and wish to start writing code, but then find ourselves spending hours over hours on just setting up babel, webpack, testing and other packages we'll need to use...

#### Just clone this repo, update *packgae.json* and *webpack.config.js* with your new-awesome-package details and start writing code!

##### It comes pre-configured with:
* Babel - for transpiling.
* Webpack - for bundling.
* Mocha & Chai - for testing.
* Jsdoc - for docs generating.

npm scripts:
```
// Build
npm run build

// run tests
npm run test 

// generate docs
npm run docs
``` 

* Jsdoc uses the conf.json file, update it with your details and desired configuration too as you like. it now uses the 'cosmo' template from ink-docstrap.
