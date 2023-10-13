# setup
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) through the following command:
`podman run --rm -v ${PWD}:/react-demo node:20-alpine3.17 npx create-react-app react-demo`  

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.
The app can be started with:  
`podman run --rm --name react -p 3000:3000 -v ${PWD}:/react-demo -w /react-demo node:20-alpine3.17 npm start`  
It will spin up the SPA on http://localhost:3000/.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed as static files served by any HTTP server.

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

