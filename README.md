#Tic Tac Toe using Angular and Firebase

##Requirements

- **Start a new project and implement the game in Angular JS**
- Feel free to build on top of Rails. Tic Tac Toe doesn't require API server calls, so it doesn't really matter.
- One controller and a single view is probably all you need, so no routes or resources required.
- Don't use jQuery or the native DOM API, instead bind DOM elements the Angular way.
- Use Coffeescript or Javascript.

##Suggested Implementation

1. Start by creating a 3 x 3 grid in HTML. Define styles that can be added to a cell to indicate it is either an X or O. We will be using Coffeescript to toggle on classes when a user clicks a square.

2. Brainstorm a data structure that you want to use to store the moves of the players in Coffescript. This can either be an Array, or Hash. Think carefully as you will need to examine the moves at the end to find a winning solution.

3. Start to implement behavior on the square clicks. Make it alternate between placing X and Os with the resepetive styling.


##Bonus Ideas

- Implement a way to determine if there's a tie before the board is filled up.
- Use Firebase (Angular Fire: https://www.firebase.com/quickstart/angularjs.html) to make the game play work across multiple browswers. Hint: you can bind your board to firebase.