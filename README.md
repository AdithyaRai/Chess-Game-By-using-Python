# Chess Game

This is a simple chess game implemented in Python using the Pygame library. The game features a graphical chessboard, pieces, and basic chess rules such as valid moves, pawn promotion, and check/checkmate detection.

## Features

- **Graphical Chessboard**: The chessboard is displayed with an 8x8 grid and alternating colors for squares.
- **Chess Pieces**: All standard chess pieces (pawn, rook, knight, bishop, queen, king) are included with their respective movement rules.
- **Valid Moves**: The game calculates valid moves for each piece, including special rules like pawn promotion.
- **Check and Checkmate Detection**: The game detects when a king is in check or checkmate.
- **Turn-Based Play**: Players alternate turns between white and black.

## Prerequisites

- Python 3.x
- Pygame library

## Installation

1. Clone this repository or download the source code.
2. Install the Pygame library if not already installed:
   `'`bash
   pip install pygame
3.Ensure the images/ directory contains the required chess piece images:
 - black_pawn.png
 - white_pawn.png
 - black_rook.png
 - white_rook.png
 - black_knight.png
 - white_knight.png
 - black_bishop.png
 - white_bishop.png
 - black_queen.png
 - white_queen.png
 - black_king.png
 - white_king.png
## How to Play
1. Run the game:
   '''bash
   python chess_game.py
2. The chessboard will appear in a window.
3. Click on a piece to select it. Valid moves will be highlighted.
4. Click on a valid square to move the piece.
5. The game alternates turns between white and black players.
6. The game ends in checkmate or stalemate.
## File Structure
- chess_game.py: Main game logic and Pygame implementation.
- images/: Directory containing chess piece images.
## Known Issues
- The game does not currently enforce all chess rules (e.g., castling, en passant).
- No AI opponent; the game is designed for two players.
## Future Improvements
- Add support for castling and en passant.
- Implement an AI opponent for single-player mode.
- Improve the user interface with additional visual effects.
- Add a move history and undo functionality.
## License
This project is open-source and available under the MIT License.

## Acknowledgments
Pygame for providing the library to build the game.
