# Tic Tac Toe JavaFX Game

This is a classic Tic Tac Toe game developed using Java and JavaFX. The game allows you to play against an AI opponent with a graphical user interface (GUI). The AI uses the minimax algorithm with alpha-beta pruning to make optimal moves.

## Features
- **Single Player Mode**: Play against an AI that uses a minimax algorithm for strategic gameplay.
- **Graphical User Interface (GUI)**: Built with JavaFX, featuring a standard Tic Tac Toe grid for a smooth user experience.
- **Game Restart**: A "Restart Now" button allows players to reset the game at any time.
- **Game Over Alerts**: Notifications are displayed when the game ends, whether due to a win, loss, or draw.
- **Move Validation**: Prevents players from selecting an already marked cell and alerts them if they try to do so.

## Installation
To run this project locally, follow these steps:

### Prerequisites
- Java (version 8 or higher)
- JavaFX SDK
- A compatible IDE, such as IntelliJ IDEA or Eclipse, or the command line for Java development

### Setup Instructions
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/tictactoe-javafx.git
   cd tictactoe-javafx
2. Ensure you have the JavaFX SDK set up in your IDE or configured in your command line.
3. Compile and run the TicTacToe class as the main entry point of the application.
  
## How to Play

1. Launch the application, and you'll see a standard Tic Tac Toe grid with a "Tic Tac Toe" title at the top.
2. Click on any empty cell to make your move as "O". 
3. The AI, which plays as "X", will then make its move.
4. The game checks for a win or a draw after each move. If the game is over, an alert will inform you of the outcome.
5. To play again, click the "Restart Now" button.

## AI Implementation

The AI opponent uses the minimax algorithm with alpha-beta pruning for optimal decision-making:
- **Minimax Algorithm**: The algorithm ensures that the AI always makes the best possible move, either maximizing its chances of winning or minimizing potential losses.
- **Alpha-Beta Pruning**: This optimization reduces the number of nodes evaluated by the minimax algorithm, making the AI's decision process more efficient.

## Project Structure

The code is structured as follows:
- **GUI Elements**: Created and managed within the `createGUI()` and `handleEvent()` methods.
- **Game Logic**: The `isWinner()`, `isBoardFull()`, and `checkForWinner()` methods handle the game's core logic.
- **AI Logic**: Implemented within the `minimaxWithAlphaBeta()` method and called within `makeMoveWithAI()` to execute the AI's moves.

## Screenshots

Add screenshots of the game window here for a better visual understanding of the project.

## Resources

- **JavaFX Documentation**: [JavaFX API](https://openjfx.io/)
- **Minimax Algorithm**: [Wikipedia - Minimax](https://en.wikipedia.org/wiki/Minimax)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- **Tanner Abraham** - Initial work - [Tanner Abraham](https://github.com/Tanner Abraham)

## Acknowledgments

- JavaFX for the GUI framework
- Inspiration from classic Tic Tac Toe games
