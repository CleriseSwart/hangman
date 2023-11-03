# Hangman Game with React

This Hangman game is a simple word-guessing game built using React. The player guesses letters to reveal the hidden word. Exceeding the maximum incorrect guesses leads to a loss.

## Game Rules
- At the beginning, the game randomly selects a word, which the player tries to guess letter-by-letter.
- The player can click or input letters to guess the word. Correct guesses reveal the letters in the word.
- The game keeps track of incorrect guesses.
- The game displays the Hangman stages (six in total) as incorrect guesses accumulate.
- If the player guesses the word correctly before reaching the maximum incorrect guesses, they win. If the Hangman is completed before guessing the word, the player loses.

## How to Play

1. To start the game, run `npm start` in the terminal.
2. When the game begins, it will randomly pick a word.
3. Guess the letters by clicking on the displayed keyboard or typing on your physical keyboard.
4. If the guessed letter is correct, it will appear in the word. If incorrect, the Hangman illustration progresses.
5. The player wins if the word is correctly guessed before completing the Hangman stages. The game resets if the player loses.

## Project Details
- The project is built with React and adheres to the Create React App Starter Kit.
- It includes attractively styled components with custom CSS for an enhanced user experience.
- Components are rendered using the array.Map() method with unique keys.
- User interactions are reflected in the state of components.
- Two or more components' states are synchronized to manage the game's progress.
- The game allows users to restart the game anytime.
- Game informs the user when they "win" or "lose".
- Help is available to inform users about the game rules through UI.
- The UI is designed to be user-friendly, attractive, and intuitive.

## Running the Game Locally

To play the game on your local machine, follow these steps:

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install the necessary dependencies.
4. Start the application using `npm start`.
5. Access the game through your web browser at `http://localhost:3000`.

### File Structure and Code Style

The project is organized with the standard file structure aligned with best practices. The code follows Google's style guide, ensuring readability and maintainability.

For any other inquiries about the game, installation, or game functionality, refer to the documentation in the source code.

Enjoy playing Hangman!
