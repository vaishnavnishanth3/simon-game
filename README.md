# Simon Game (JavaScript)

A browser-based memory game inspired by the classic **Simon** game.
Watch the color sequence, repeat it in order, and see how many levels you can complete.

## How to Play

1. Open the game in your browser.
2. Press any key to start.
3. A color flashes with a sound.
4. Click the buttons in the exact sequence shown.
5. Each level adds one new step to the pattern.
6. A wrong click ends the game and shows **Game Over**.
7. Press any key to restart.

## Run Locally

This project has no build step and no dependencies to install.

1. Clone or download this repository.
2. Open `index.html` in your browser.

For the best experience, keep the folder structure unchanged so audio files in `sounds/` are found correctly.

## Tech Stack

- HTML5
- CSS3
- JavaScript (jQuery)

## Project Structure

- `index.html` – game layout and script imports
- `styles.css` – game styling and button states
- `script.js` – game logic (sequence generation, input checks, restart)
- `sounds/` – audio files used for button and wrong-answer sounds

## Game Logic Summary

- Stores the generated pattern and user input in separate arrays.
- Compares each user click against the generated pattern.
- Advances level after a correct full sequence.
- Resets game state after an incorrect input.
