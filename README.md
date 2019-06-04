# Simple React Starter Kit

## Getting started

#### Basic commands
1. Clone repository
`git clone https://github.com/martapa/react-starter.git`
2. Go into the folder
`cd react-starter`
3. Install all dependencies
`npm install`
4. Bundle files
`npm run-script build`
5. Run your app
`npm start`
App will automatically open in your browser [http://localhost:8080/](http://localhost:8080/).

#### Some extras
To start over and clean your project.
`npm run clean`

To test the app.
`npm test`

To start server without ESLint
`npm run-script start-server`

To run ESLint
`npm run-script lint`

## Folder structure

* __package.json__ -list of node dependencies needed.
* __src/index.html__ -file where jsx code is loaded in the `<div id=”root”>`. Id is important because it point to id from index.js file.
* __src/index.js__ -file that corresponds to html file. It tells that App component has to be loaded into html with `id="root"`.
* __src/App.js__ -main App component that will hold all other components.
* __dist__ -this folder will be created after running `npm build`. It stores bundled files.
* __src/App.test.js__ -simple App component test.
* __src/setupTests.js__ -file with Enzyme configuration.
* __.babelrc__ -babel configuration file.
* __.webpack.config.js__ -simple webpack configuration file.
* **src/__tests__** -folder with future Jest or Enzyme tests.


## More info

* This starter uses ESLint to ensure code consitency [https://eslint.org/docs/user-guide/getting-started](https://eslint.org/docs/user-guide/getting-started).
