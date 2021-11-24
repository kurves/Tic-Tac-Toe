I created this simple interactive  Tic Tac Toe game using React Hooks.
It shows when there is a winner ,the next player if no winner yet and a draw. 
The game restarts when the restart button is clicked. 

Fistly, I initialized the Square component which is basically a button that when clicked reveals either the "X" or "O".


![square](https://user-images.githubusercontent.com/84717663/143207223-68153578-8290-436b-8f4d-995df32c4ec8.PNG)


Secondly, I created the Board component which takes the Square component and maps out the nine sqaures making up the board's grid.The grid is styled using css to achieve the desired look.


![board](https://user-images.githubusercontent.com/84717663/143211823-40833686-2fb3-4225-a3a9-8752c6d1e57c.PNG)

Lastly, is the game component which contains the game's logic. I started with determining the  winning moves using a two dimension array. It returns the winning square else it returns null.

![lines](https://user-images.githubusercontent.com/84717663/143212612-1bd88c68-a063-4f8d-8915-a3cc4ad0c933.PNG)

The Game component also has the "checkdraw function" which checks for a draw which returns true if the condition stated is met.


![checkdraw](https://user-images.githubusercontent.com/84717663/143213409-81a3e27c-1142-4237-a7a0-ff940cb0ff55.PNG)

The Board component also takes the "handelClick function" which defines the state and the the layout of the board.


![handleclick](https://user-images.githubusercontent.com/84717663/143221216-9af1c0e1-e328-41c5-9fe3-7c77f22711fd.PNG)


The restart button restarts the game when clicked.

![restart](https://user-images.githubusercontent.com/84717663/143216757-bd7155d7-0c56-4cb7-9d34-9f5b6a08a396.PNG)

The game component also returns a div tag that handles user clicks using the "handleClick function" and the status and the restart

![status](https://user-images.githubusercontent.com/84717663/143218262-f1967207-a33d-498a-b219-67daece7ce2d.PNG)


![Board](https://user-images.githubusercontent.com/84717663/143219619-548ac115-6dfc-4871-8c26-c87d5391d30c.PNG)

I alo used CSS to style the app.

![css](https://user-images.githubusercontent.com/84717663/143220577-807d2b24-8b20-4138-ad53-cbb5cdaa3cda.PNG)







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

