# OVC React Redux Application
A react redux app to display and filter data, from a API endpoint, in [a] table/s.

## Technologies Used
- React
  - create-react-app
  - https://github.com/facebook/create-react-app
- Redux
  - State management container
  - https://redux.js.org/
- Redux Thunk 
  - Middleware for async Redux store updates
  - https://github.com/reduxjs/redux-thunk
- Jest
  - Testing framework
  - https://jestjs.io/
  
## Features
1. A table with 4 columns Name, Email, City, and Company populating the rows 
   with the response from the api endpoint https://jsonplaceholder.typicode.com/users.
2. An input field to search based on name.
3. The rows are clickable. When a row is clicked, the website should show the user's posts. 
   Utilizing this api, https://jsonplaceholder.typicode.com/posts?userId=1 for 
   retrieve a user's posts.

## Running, Testing and Building

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

