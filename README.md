# Arc-Tech-Labs-questions
This repo contain solution to Arc Tech Labs questions
Question1.js :
In this example, the getData function uses the fetch method to make a GET request to the https://jsonplaceholder.typicode.com/posts endpoint, which returns a Promise that resolves to a Response object.
We then use the json method of the Response object to extract the JSON data from the response, which also returns a Promise that resolves to the parsed JSON data.
Finally, we log the JSON data to the console. If an error occurs during the fetch request, we catch the error and log it to the console.
You can customize this example to fetch data from other endpoints of the JSON Placeholder API by replacing the URL used in the fetch method.

Question2.js :
In this example, we use the makeStyles hook from MUI to define a tableContainer class that sets the maximum width of 
the table container to 50% of the screen width for laptop screens, and 100% for mobile screens (using the theme.breakpoints.down method).
We then use the useState and useEffect hooks to fetch the data from the JSON Placeholder API and store it in state.
Finally, we render a TableContainer, Table, TableHead, and TableBody from MUI, along with a Paper component, to 
display the data in a table. The table is styled with the tableContainer class we defined earlier.

Question3.js: 
In this example, we create a Redux store using the createStore method from Redux,
and pass it to the Provider component from react-redux. We also import a rootReducer that combines all of our app's reducers.
We then render the Provider component as the parent of our App component using the ReactDOM.render method.
The Provider component makes the Redux store available to all components in the app through the useSelector and useDispatch hooks.
