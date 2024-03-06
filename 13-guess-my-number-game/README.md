# Guess My Number Game using JavaScript

**DEMO :** https://wonderful-speculoos-663090.netlify.app/

A simple guess my number game developed using HTML, CSS and JavaScript

> **Technologies used:** HTML, CSS, JS

# Pseudo Code

    Setup:
        - Start with a score of 20.
        - Keep track of the number of guesses made (starts at 0).
        - Pick a secret number between 1 and 20.

    Display and Input:
        - Show the current score and the high score.
        - Allow the player to input their guess.
        - When the player clicks the guess button:
            - Check if the guess is valid (between 1 and 20).
            - If it's not valid, display an error message.
            - If it is valid, compare it to the secret number.

    Compare Guess:
        - If the guess is correct:
            - Show a success message.
            - Display the secret number and update the high score if needed.
        - If the guess is too high or too low:
            - Display a message indicating if it's too high or too low.
            - Decrease the score by 1.
            - Increase the count of guesses.

    End Game:
        - If the player runs out of score (reaches 0), display a message that the game is lost.
        - Clear the input box.

    Storage:
        - Store the high score in the browser's local storage.
        - Update the high score whenever a new high score is achieved.