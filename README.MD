BRIEF

- Create a text based/basic alien shooting game using OOP within 150 lines of code. To have 3 types of ships holding different hit scores.

- When a ship is hit the points are deducted.

- Game over is when all ships have 0 points or the Mother ship has 0 points.

FUNCTIONALITY

1. I needed a Class for the ships, including a method to deduct points when called.
2. An object was created to represent each ship on loading the game. These were then pushed into an array so one could be chosen at ranom later.
3. Created a shoot button to check for game over otherwise hit a ship. Basic animation added to shoot button using Javascript timer delay.
4. hitShip function will choose a ship at random from the array (Math.random method, checking it hasn't already been sunk with an IF statement. A message is displayed by changing the innerHTML of an element.
5. I then needed to access the HTML elements and hide the relevant ship once sunk, using classList.contains and .add.
6. A Restart button to start the game again. This iteratess over the HTML elements array to remove classlists, making them visible again.

IMPROVEMENTS NEEDED

We were asked to keep styling to a minimum and functionality basic. If I were to spend more time on it I'd like to add a timer to make game play more intense and animation for the shooting action.
I believe there is also a way to generate the HTML elements within the JavaScript rather than having it hard coded.
