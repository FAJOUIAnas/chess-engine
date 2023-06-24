# chess-engine
This is a Python project that implements a chess engine using the Pygame library. The chess engine uses the Minimax algorithm to make decisions for the AI player.

## Download
To download the latest chess game, go [here](https://github.com/FAJOUIAnas/chess-engine/releases/tag/v2.0.0) and download the `chtrnj.rar` file, extract it and you'll find the six executable files.

## Usage from source
1. Clone the repository to your local machine:  
  `git clone https://github.com/your-username/chess-engine.git`
2. Navigate to the project directory:  
   `cd chess-engine`
3. Install Pygame:  
   `pip install pygame`
4. Open the project in terminal
5. Run `python Chess/ChessMain.py`

The chess board will be displayed using the Pygame window. You can interact with the game using your mouse.

To select a piece, click on it. The selected piece will be highlighted.
To move the selected piece, click on the destination square.
To deselect a piece, click anywhere on the board outside of the valid moves.
The AI player will automatically make its move after you move. The depth of the Minimax algorithm can be adjusted in the ChessAI.py file.

## Features
- Chessboard visualization using Pygame.
- Human vs. AI gameplay.
- Minimax algorithm for AI decision-making.
- Move validation and legality checking.
- Checkmate and stalemate detection.
- Piece capturing and promotion.
- Move history tracking.

## Contributing
Contributions to this chess engine project are welcome. If you find any bugs or have suggestions for improvements, please open an issue on the GitHub repository. Additionally, if you would like to contribute code, you can open a pull request.

When contributing, please ensure that your code follows the existing coding style and that you have tested it thoroughly.
