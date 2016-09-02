# What

This is a starter template for Front-End related projects. It contains a handful of modules and tasks to help you build quickly. Use it for a React or AngularJS project or when you just want to mess around. It includes a dev server (browsersync) as well as all the build tools you'll need to get started.

Enjoy.

## Usage

- Clone this repo
- `rm -rf .git` to remove my .git folder
- `git init` to reinitialize your own git project
- Build something cool


## Build Tools

I'm using Gulp to handle most things and NPM for testing, deployment and linting. For these to work, make sure you globally install the following:

- [Mocha](https://mochajs.org/)
- [Surge](http://surge.sh/)
- [ESLint](http://eslint.org/)

## Gulp & NPM Tasks

- **`gulp start`**: This is the primary task that will fire up the server and allow you to start building
- `gulp server`: This will start a Browsersync server with live-reload
- `gulp sass`: This will compile your SASS
- `gulp browserify`: This will transpile your JS from ES6 to ES5 (and handle `import`'s)
- `gulp watch`: This will start a watcher for files


- `npm run test`: This will launch Mocha in your terminal and run any tests
- `npm run deploy`: This will deploy your application to Surge.sh for you
- `npm run lint`: This will run ESLint on your `/src/js` folder
