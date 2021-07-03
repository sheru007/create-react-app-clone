### hello world
This is react js app that is build from scratch like create-react-app

## Step 1: Creating the folder that will host our project

```js

mkdir my-react-project
cd my-react-project

```
## Step 2: Initializing the project

```js

npm init -y

```

## Step 3: Installing dependencies
```js

#React dependencies
npm install react react-dom react-router-dom

#Webpack dependencies
npm install --save-dev webpack webpack-cli

#Babel dependencies
npm install --save-dev @babel/core @babel/preset-react

#Loaders for Webpack
npm install --save-dev babel-loader html-loader style-loader css-loader sass-loader

#Webpack plugins
npm install --save-dev html-webpack-plugin

#Server dependencies
npm install express
npm install --save-dev nodemon

```

## Step 4: Configuring Webpack - webpack.config.js

## Step 5: Creating the HTML template - index.html

## Step 6: Creating the server - server.js

## Step 7: Creating the React app - App.js

## Step 8: Creating the entry point for the React app - index.js

## Step 9: Defining the scripts

```json

#packgae.json
{
    ...
    "build": "rm -rf dist && webpack --mode development",
    "dev": "nodemon app.js"
    ...
}
```

## Step 10: Building and running our app

```js
npm run build
npm run dev
```