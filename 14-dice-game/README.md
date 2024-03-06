# Dice Game using JavaScript

**DEMO :** https://javascript-mini-projects-dvk.netlify.app/14-dice-game

A dice roll game developed using HTML, CSS and JavaScript

> **Technologies used:** HTML, CSS, JS

# Pseudo Code

    Initialization:
        - Initialize the game by setting initial scores for both players to 0, current score to 0, and the active player to player 1.
        - Display initial scores and current scores as 0 for both players.
        Hide the dice image.

    Rolling the Dice:
        - When the roll button is clicked, if the game is still in progress:
            - Generate a random number between 1 and 6 to simulate rolling the dice.
            - Display the corresponding dice image.
            - If the dice roll is not 1:
                - Add the dice roll value to the current score of the active player.
                - Display the updated current score.
            - If the dice roll is 1:
                - Switch to the next player.
                - Reset the current score to 0.

    Switching Players:
        - When the dice roll is 1 or the player decides to hold:
            - Reset the current score of the active player to 0.
            - Switch to the next player.
            - Update the UI to reflect the active player.

    Holding Score:
        - When the hold button is clicked:
            - Add the current score to the overall score of the active player.
            - Update the UI to reflect the updated score for the active player.
            - If the active player's score reaches or exceeds 100, end the game and declare the active player as the winner.

    End Game:
        - If a player's score reaches or exceeds 100:
            - Hide the dice.
            - Highlight the winning player.
            - End the game by disabling further gameplay actions.