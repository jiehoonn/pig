# Background
- Before starting any computer science classes, I wanted to experience how to code in Python and the capabilities of the language. While following along a YouTube tutorial, I got to learn many aspects of Python and how to use them to create a simple interactive game like Pig.
- This repository hosts 'Pig Dice Game', a Python-based simulation of the classic Pig dice game supporting 2-4 players. It features a simple roll function to mimic dice rolls and an interactive game loop that manages player turns, scoring, and game decisions. Players accumulate points by rolling a die unless a 1 is rolled, which resets their turn score. The game continues until a player reaches a set score threshold, in this case, 50 points, to win the game. The code effectively handles multiple players, turn-based gameplay, and winner determination, providing a straightforward yet engaging gaming experience.

# How to Play:
- **Starting the Game:** Launch the script and enter the number of players (2-4) when prompted.
- **Taking Turns:** Each player, in turn, decides whether to roll the die by inputting 'y'. Rolling continues until the player chooses to stop or rolls a 1.
- **Scoring Points:** If a player rolls any number other than 1, that number is added to their turn total. Players can continue rolling to accumulate more points.
- **Risky Rolls:** Rolling a 1 ends the player's turn and resets their turn score to zero.
- **Ending Turn:** Players can choose to end their turn after any roll (except 1) to add their turn total to their overall score.

# How the Game Ends:
- **Reaching the Winning Score:** The first player to accumulate a total score of 50 or more wins the game.
- **Announcing the Winner:** Once a player reaches the winning score, the game announces the winner and displays their final score. If in the case player 1 crosses the threshold first, the game will allow player 2 to continue their turn. If player 2's score is more than player 1's, then player 2 will be the winner.
