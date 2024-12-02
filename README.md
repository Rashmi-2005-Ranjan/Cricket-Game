# Cricket Game

This is a simple interactive Cricket Game made with **HTML**, **CSS**, and **JavaScript**. The game uses three buttons - **Bat**, **Ball**, and **Stump** - along with a **Reset** button to play and clear the game data. The results are stored in the browser's localStorage.

## Features
- Play the game with three options: **Bat**, **Ball**, and **Stump**.
- The computer makes random choices, and the logic determines the winner based on user input.
- Results are stored in localStorage to keep track of the game's outcomes.
- Use the **Reset** button to clear all stored data and reset the game.

## How to Play
1. Open the game in a browser.
2. Choose one of the options (**Bat**, **Ball**, or **Stump**) by clicking the respective button.
3. The computer will randomly make a choice.
4. The result will be displayed based on the following logic:
   - **Bat vs Ball**: Computer loses.
   - **Ball vs Stump**: Computer loses.
   - **Stump vs Bat**: Computer loses.
   - In other cases, the user loses.
5. The game keeps track of the results in localStorage.

## Reset
- Click the **Reset** button to erase all results stored in localStorage and start fresh.

## Code Structure
- **HTML**: Defines the game structure and UI elements.
- **CSS**: Adds basic styling to the game.
- **JavaScript**: Contains the game logic inside a `<script>` tag.
