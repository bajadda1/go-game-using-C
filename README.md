# Go Game in C
Welcome to our Go game implementation in C! This project brings the intricate strategies and simplicity of the classic game of Go to your console. Whether you're a seasoned player or just starting out, our text-based interface offers an engaging way to play against a friend or challenge our AI opponent.

## Features
- Text-Based Interface: Enjoy a clean and intuitive interface right in your console.
- Player Versus Player: Challenge your friends to a game and showcase your Go skills.
- Player Versus AI: Test your strategies against our simple AI opponent.
- Rules Implemented:
  * KO Rules: Prevent repeating board states with our implementation of the KO rule.
  * Capture :Ensure captured stones are removed according to the player rule
  * Pass Rule: switch rules between players
## Getting Started
### Prerequisites
- To compile and run the game, you need a C compiler such as GCC installed on your system.

- Installation
  * Clone the repository to your local machine=>bash cmd: git clone https://github.com/your_username/go-game.git
  * Navigate to the project directory=> bash cmd: cd go-game
  * Compile the code using GCC=> bash cmd: gcc main.c All_Fcts.c -o go_game
### Usage
- Run the compiled executable=> bash cmd: ./go_game
- Follow the on-screen instructions to play the game.
- Choose your moves by entering the coordinates of the position you want to place your stone.
- The game will alternate between players, indicating whose turn it is.
- Use strategy and tactics to capture your opponent's stones and control territory.
- Enjoy the game!
