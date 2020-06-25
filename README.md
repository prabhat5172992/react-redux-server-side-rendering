# react-redux-server-side-rendering

If you are running on mac and package.json giving error then make this change.

````json
"dev:server": "nodemon --watch build --exec \"node build/bundle.js\" ",

Also if package json give compatiblity issue then copy this file.
```json
{
  "name": "react-ssr",
  "author": "Prabhat Ranjan",
  "version": "1.0.0",
  "description": "Server side rendering project",
  "main": "index.js",
  "scripts": {
    "dev": "npm-run-all --parallel dev:*",
    "dev:server": "nodemon --watch build --exec node build/bundle.js",
    "dev:build-server": "webpack --config webpack.server.js --watch",
    "dev:build-client": "webpack --config webpack.client.js --watch"
  },
  "license": "ISC",
  "dependencies": {
    "axios": "0.16.2",
    "babel-cli": "6.26.0",
    "babel-core": "6.26.0",
    "babel-loader": "7.1.2",
    "babel-preset-env": "1.6.0",
    "babel-preset-es2015": "6.24.1",
    "babel-preset-es2017": "6.24.1",
    "babel-preset-react": "6.24.1",
    "babel-preset-stage-0": "6.24.1",
    "compression": "1.7.0",
    "concurrently": "3.5.0",
    "express": "4.15.4",
    "express-http-proxy": "1.0.6",
    "lodash": "4.17.4",
    "nodemon": "1.12.0",
    "npm-run-all": "4.1.1",
    "react": "16.0.0",
    "react-dom": "16.0.0",
    "react-helmet": "5.2.0",
    "react-redux": "5.0.6",
    "react-router-config": "1.0.0-beta.4",
    "react-router-dom": "4.2.2",
    "redux": "3.7.2",
    "redux-thunk": "2.2.0",
    "serialize-javascript": "1.4.0",
    "webpack": "3.5.6",
    "webpack-dev-server": "2.8.2",
    "webpack-merge": "4.1.0",
    "webpack-node-externals": "1.6.0"
  }
}
````
