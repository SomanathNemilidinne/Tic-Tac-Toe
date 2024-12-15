# TicTacToe Game - Java Console Edition

## Game Overview
Welcome to the classic **Tic Tac Toe** game, implemented in Java for console play! Whether you're a casual gamer or someone looking to test your strategic skills, this game will provide you with hours of entertainment. 

In this version of the game, you and a friend (or a computer) can engage in a fun-filled round-robin competition. Choose your characters (X or O), and compete for victory on a 3x3 grid. The system randomly picks the player who goes first, and you can easily play the game by selecting positions to place your marks. Enjoy the thrill of victory or the agony of defeat in this engaging game of Tic Tac Toe!

## Features
- **Player Setup**: Enter your names for Player 1 and Player 2.
- **Random First Move**: The game randomly picks who starts first.
- **Character Selection**: Choose your character (X or O) at the beginning of the game.
- **Console Gameplay**: The game is played on the console with easy-to-follow prompts.
- **Game Flow**: Players alternate turns, marking one of the squares on the board.
- **Win Conditions**: The game checks for a win after every move.
- **Draw Condition**: If the board fills up with no winner, the game ends in a draw.
- **Clear Output**: The board is clearly displayed after each move, ensuring you always know where you stand.

## Installation
1. **Prerequisite**: Make sure you have Java installed on your computer.
   - Download and install the latest version of Java from [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
   - Make sure Java is set up correctly by running `java -version` and `javac -version` in your terminal or command prompt.

2. **Clone or Download**: 
   - Download the **TicTacToe.java** file.
   - Alternatively, you can clone it from the repository using the command:
     ```
     git clone <repository-link>
     ```

3. **Compile**:
   - Open your terminal and navigate to the directory where the `TicTacToe.java` file is located.
   - Run the following command to compile the code:
     ```bash
     javac TicTacToe.java
     ```

4. **Run**:
   - Once compiled, run the game with the following command:
     ```bash
     java TicTacToe
     ```

5. **Enjoy** playing the game in your console!

## How to Play
- Upon launching the game, the system will prompt you to enter your names for Player 1 and Player 2.
- Then, a random player is selected to choose whether they will play as "X" or "O".
- The game board will be displayed in a 3x3 grid format:
  ```
  |   |   |
  1 | 2 | 3
  |   |   |
  -----------
  |   |   |
  4 | 5 | 6
  |   |   |
  -----------
  |   |   |
  7 | 8 | 9
  |   |   |
  ```
- Players take turns to select a number between 1 and 9 (corresponding to the empty squares on the grid) to mark their character.
- The game continues in a round-robin manner until a player wins by completing a line (row, column, or diagonal) or the game ends in a draw.
  
**Winning Conditions:**
- A player wins if they can place their mark (either 'X' or 'O') in a complete row, column, or diagonal.

**Draw Condition:**
- If all squares are filled and there is no winner, the game ends in a draw.

## Game Logic
- **Round-Robin**: Players take turns marking squares on the grid.
- **Position Validation**: If a square is already taken, the game will prompt the player to choose a different position.
- **Winning Check**: After every move, the game checks if there are three consecutive marks in a row, column, or diagonal.
- **Draw Check**: The game checks if all squares are filled and no one has won, in which case it declares a draw.

The program uses an array to track the game board's state, with `0` representing Player 1's mark (X), `1` representing Player 2's mark (O), and `6, 9, 4, 2, 3, 6, 7, 8, 9` for available squares.

## A Little Humor
- **Tic Tac Toe** isn't just about the game—it's about the fun and laughter you share with friends or family as you argue over that "lucky move" or pretend your opponent didn't see the winning line!
- Who knew that a simple game could cause so much drama over a 3x3 grid? May the best player win, and if not, blame the random number generator for picking the wrong first player!

## Example Output

```
╭━━━━╮╱╱╱╭━━━━╮╱╱╱╱╱╭━━━━╮
┃╭╮╭╮┃╱╱╱┃╭╮╭╮┃╱╱╱╱╱┃╭╮╭╮┃
╰╯┃┃┣╋━━╮╰╯┃┃┣┻━┳━━╮╰╯┃┃┣┻━┳━━╮
╱╱┃┃┣┫╭━╯╱╱┃┃┃╭╮┃╭━╯╱╱┃┃┃╭╮┃┃━┫
╱╱┃┃┃┃╰━╮╱╱┃┃┃╭╮┃╰━╮╱╱┃┃┃╰╯┃┃━┫
╱╱╰╯╰┻━━╯╱╱╰╯╰╯╰┻━━╯╱╱╰╯╰━━┻━━╯
Welcome to Tic Tac Toe!
Enter your name for player 1: John
Enter your name for player 2: Alice
Player 1: John, Player 2: Alice
System will pick a random player to choose first.
Enter your choice for John (Number '1' for 'X' or Number 'O' for 'O'): 1
Player 1 (John), You are X.
Player 2 (Alice), You are O.
Choose a position where you want to mark your choice, e.g., choosing '1' will mark your character in that square.
|   |   |
 1 | 2 | 3
|   |   |
-----------
|   |   |
 4 | 5 | 6
|   |   |
-----------
|   |   |
 7 | 8 | 9
|   |   |

John Where do you want to mark? 1
|   |   |
 X | 2 | 3
|   |   |
-----------
|   |   |
 4 | 5 | 6
|   |   |
-----------
|   |   |
 7 | 8 | 9
|   |   |

Alice Where do you want to mark? 5
|   |   |
 X | 2 | 3
|   |   |
-----------
|   |   |
 4 | O | 6
|   |   |
-----------
|   |   |
 7 | 8 | 9
|   |   |

...
John Won, Congratulations!
```

## Who'll Love This Project
- **Casual Gamers**: Looking for a fun, quick, and easy game that can be enjoyed by players of all ages.
- **Programming Beginners**: Those interested in learning about game development, user input handling, and simple Java programming.
- **Tic Tac Toe Fans**: Fans of the classic game will love this console-based version and its simplicity.
- **Friends and Family**: Perfect for a lighthearted game night with loved ones!

---

Feel free to fork, clone, or download this project and share it with others! Enjoy playing Tic Tac Toe, and may the best player win!

*Created with ❤️ by Somanath Nemilidinne*
