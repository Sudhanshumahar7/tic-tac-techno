# TicTacTechno (Tic-Tac-Toe Game)

A classic, interactive, and beautifully designed Tic-Tac-Toe game built from scratch using HTML, CSS, and Vanilla JavaScript. 

## 🚀 Features
- **Custom Player Names**: At the start of the game, players are prompted to enter their names for a personalized experience.
- **Dynamic Turn Indicator**: The game clearly displays whose turn it is (e.g., "Next turn: Player 2").
- **Winner & Tie Detection**: Automatically detects when a player wins or if the game ends in a tie, and displays a modal with the result.
- **Leaderboard Score Tracking**: Keeps track of matches won by each player across sessions using browser `localStorage`.
- **Reset Functionality**: Includes confirmation modals to prevent accidental resets of the game board or the leaderboard score.
- **Responsive Design**: Clean and interactive UI crafted with CSS, complete with hover states and modal animations.

## 🛠️ Technologies Used
- **HTML5**: For the basic structure and layout of the game.
- **CSS3**: For styling, responsive layout (Flexbox/Grid), and animations.
- **JavaScript (Vanilla)**: For game logic, DOM manipulation, state management, and `localStorage` integration.

## 🎮 How to Play
1. Clone the repository or download the source code.
2. Open `index.html` in any modern web browser.
3. Enter the names for Player 1 (plays as 'X') and Player 2 (plays as 'O') when prompted.
4. Click on any empty box on the 3x3 grid to make your move.
5. The game will automatically announce the winner or declare a tie.
6. Use the **Reset** button to clear the board for a new round.
7. Use the **Reset Score** button to clear the leaderboard history.

## 📂 Project Structure
- `index.html`: Contains the layout and markup of the game, modals, and scoreboard.
- `style.css`: Contains all the styling to make the game visually appealing.
- `script.js`: Contains the core game logic, win patterns, and event listeners.
- `Assets/`: Contains images/icons like the site logo (`Logo.png`).
