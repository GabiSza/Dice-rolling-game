# Dice-rolling-game
It is a dice rolling game built with JS during a course I took on Udemy. This is a simple JavaScript code for a dice game. The game allows two players to take turns rolling a dice and accumulating scores. The player who reaches a score of 100 or more wins the game.
# Instructions
To play the game, follow these steps:

1. Open the index.html file in a web browser.
2. The game starts with Player 1 (Player 0) as the active player.
3. Click the "Roll Dice" button to roll the dice.
4. The dice will display a random number between 1 and 6.
5. If the rolled number is not 1, the number will be added to the current player's score.
6. The current player's score is displayed in the "Current" section.
7. Click the "Hold" button to add the current player's score to their total score.
8. If the current player's total score reaches 100 or more, they win the game.
9. The winner is displayed by highlighting their name and removing the active player indicator.
10. Click the "New Game" button to reset the game and start a new round.
# Code overview
The code consists of the following components:

1. Selecting HTML elements: The script selects various elements from the HTML document to interact with them using JavaScript.
2. Starting conditions: The initial values for scores, current score, active player, and playing state are set in the init function.
3. init function: This function initializes the game by resetting scores, current scores, and visual elements to their default values.
4. switchPlayer function: This function is called when the active player changes. It updates the current score and toggles the active player indicator.
5. Event listeners: Event listeners are added to the "Roll Dice," "Hold," and "New Game" buttons to trigger the corresponding actions.
6. Rolling dice functionality: When the "Roll Dice" button is clicked, a random number is generated to simulate the roll. The dice image is updated accordingly. If the rolled number is 1, the active player switches to the next player; otherwise, the number is added to the current score.
7. Holding score: When the "Hold" button is clicked, the current score is added to the active player's total score. If the total score reaches 100 or more, the game ends, and the active player is declared the winner. Otherwise, the active player switches to the next player.
8. Resetting the game: Clicking the "New Game" button calls the init function to reset the game and start a new round.

# License
Feel free to modify the code or customize the game according to your preferences. Have fun playing! 
