# Simple Nodejs with Express + MongoDB and React App
<p>Nodejs is used for server site language,MongoDB is used for Backend Database and for frontend used ReactJS</p>

## Features
- Express
- MongoDB
- CRUD API

## Requirement
- NodeJS & npm
- git
- MongoDB

## Installation
- npm install
- npm start
- Express
- cors
- axios
- .env
- mongoose

## GET Routes
- visit http://localhost:3000
  - /
  - /create
  - /delete/:id
  - /update
 
## Postman
 - Install Postman to interact with REST API
 - Get a form with:
   - URL  http://localhost:3000/
   - Method: GET
  
 - create a add form with:
   - URL  http://localhost:3000/create
   - Method: POST
   - Body: raw + JSON(application/json)
   - body Content: {
  "name":"",
  "email":"",
  "mobile":""
}

 - Delete a form with:
   - URL:  http://localhost:3000/delete/:id
   - Method: Delete
   - Body: raw + JSON(application/json)

  - Update a form with:
    - URL: http://localhost:3000/update
    - Method: PUT
    - Body: raw + JSON(application/json) 
      

This project was bootstrapped with [Create Nodejs MongoDB And React App](https://github.com/create-react-app).

## In this project I created add form ,Name, Email and mobile number and also edit and update.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
