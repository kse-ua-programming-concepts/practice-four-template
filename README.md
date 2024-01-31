# Assignment: Hangman Game

### Objective: Develop a console-based version of the classic word-guessing game Hangman using Python

### Requirements:
1. Game Mechanics:
    - The program selects a random word from a predefined list.
    - The word is displayed as a series of underscores, representing each letter.
    - Players guess one letter at a time.
    - If the guessed letter is in the word, reveal its position(s).
    - If the guess is incorrect, add a part to the hangman drawing.
    - Players continue until they guess the word or the hangman drawing is complete.
2. Hangman Drawing:
    - Represent the hangman with a simple ASCII art or textual representation.
    - The hangman should have six parts (e.g., head, body, arms, and legs).
3. Input/Output:
    - Use console input for the player's guesses.
    - Output the current state of the word, the letters guessed, and the hangman drawing.
4. Word List:
    - Create a list containing various words(>20 words) of varying lengths and difficulties.
5. Game End Conditions:
    - The game ends when the word is guessed correctly, or the hangman is fully drawn (8 attempts).
    - Display a winning or losing message accordingly.
6. Additional Features (Optional):
    - Implement difficulty levels affecting word choice or the number of allowed guesses.
    - Include a hint option that reveals a random letter.
