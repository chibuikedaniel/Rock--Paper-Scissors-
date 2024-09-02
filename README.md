# Rock, Paper, Scissors Game
  A classic Rock, Paper, Scissors!!!

# Overview
This project is a simple implementation of the classic Rock, Paper, Scissors game. The game allows a player to compete against the computer in multiple rounds, with the first to reach three points declared the winner. The game also features a reset functionality to allow players to start a new game after a winner is determined.

--Features
Three Choices: The player can choose between "Rock", "Paper", or "Scissors".
Random Computer Selection: The computer randomly chooses one of the three options.
Score Tracking: The game tracks both the player's and the computer's scores.
Winning Condition: The first to reach three points wins the game.
Round Results: The game displays messages after each round, indicating who won the round or if it was a tie.
Reset Functionality: After a game ends, players can reset the game and play again.
Functions
getRandomComputerResult()
This function returns a random choice for the computer from the options array: "Rock", "Paper", or "Scissors".

hasPlayerWonTheRound(player, computer)
This function determines if the player has won a round based on the rules:

--Rock beats Scissors
Scissors beat Paper
Paper beats Rock
getRoundResults(userOption)
This function handles the logic for each round:

Updates the score depending on who won the round.
Returns a message indicating the result of the round.
showResults(userOption)
This function updates the user interface to display:

The round results message.
The current scores of both the player and the computer.
A message if the player or computer wins the game, along with a reset button to play again.
resetGame()
This function resets the game state by:

--Setting both scores back to zero.
Hiding the reset button and showing the game options again.
Clearing any previous round results or winner messages.
How to Play
Start the Game: Choose "Rock", "Paper", or "Scissors" to play against the computer.
Round Result: The game will display a message indicating if you won the round, if it was a tie, or if the computer won.
Winning the Game: The first to reach three points wins. A message will display the winner.
Resetting the Game: After the game ends, click the reset button to start a new game.
Example Usage
javascript
Copy code

--Technologies Used
HTML: For the structure of the game.
CSS: For basic styling of the game elements.
JavaScript: For the game logic and interactivity.
Future Enhancements
UI Improvements: Adding animations and more detailed styling.
Multiple Rounds: Allowing players to choose the number of rounds before the game starts.
Scoreboard: Adding a persistent scoreboard to track the number of games won by each player.
