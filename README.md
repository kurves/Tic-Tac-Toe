I created this simple interactive  Tic Tac Toe game using React Hooks.
It shows when there is a winner ,the next player and a draw. 
The game restarts when the restart button is clicked. 

Fistly, I initialized the Square component which is basically a button that when clicked reveals either the "X" or "O".


![square](https://user-images.githubusercontent.com/84717663/143207223-68153578-8290-436b-8f4d-995df32c4ec8.PNG)






Secondly, I created the Board component which takes the Square component and maps out the nine sqaures making up the board's grid.The grid is styled using css to achieve the desired look.
Lastly, is the game component which contains the game's logic. I started with determining the  winning moves using a teo dimension array. It returns the winning sqaure else it returns null.
The Game component also has the "checkdraw function" which checks for a draw which returns true if the condition is met.
Check out the code  





# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

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

