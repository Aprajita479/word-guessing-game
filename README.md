# Word Guessing Game

A simple word guessing game implemented using HTML, CSS, and JavaScript.

## Instructions

1. Clone the repository or download the code files.
2. Open the `index.html` file in a web browser.
3. Click the "Start" button to begin the game.
4. Guess the letters of the word by clicking on the corresponding buttons.
5. If the guessed letter is correct, it will be revealed in the word.
6. If the guessed letter is incorrect, you will lose a chance.
7. You have a total of 5 chances to guess the word correctly.
8. If you guess all the letters correctly, you win the game.
9. If you run out of chances, the game is over.

## Dependencies

The game uses the following dependencies:

- [Google Fonts](https://fonts.google.com/css2?family=Poppins:wght@400;600&display=swap)

## Files

The repository contains the following files:

- `index.html`: The main HTML file that displays the game interface.
- `style.css`: The CSS file that styles the game interface.
- `script.js`: The JavaScript file that implements the game logic.

## Game Logic

The game logic is implemented in the `script.js` file. It includes the following functionalities:

- Generates a random word and its corresponding hint from a predefined list of words and hints.
- Allows the user to guess letters by clicking on buttons.
- Checks if the guessed letter is correct and reveals it in the word if it is.
- Keeps track of the number of chances remaining and ends the game if the chances run out.
- Displays a message for correct and incorrect letter guesses.
- Blocks the letter buttons and displays the result when the game is won or lost.
- Provides a restart button to start a new game.

## Customization

You can customize the game by modifying the list of words and hints in the `script.js` file. Add or remove entries from the `options` object to change the words available for guessing.

```javascript
const options = {
  aroma: "Pleasing smell",
  pepper: "Salt's partner",
  halt: "put a stop to",
  jump: "Rise suddenly ",
  shuffle: "Mix cards up ",
  combine: "Add; Mix",
  chaos: "Total disorder",
  labyrinth: "Maze",
  disturb: "Interrupt; upset ",
  shift: "Move; Period of word",
  machine: "Device or appliance",
};
```

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute and have fun playing the game!
