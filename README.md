# -Guess-the-Number-A-Simple-Game-in-C-
A console project written in C++. The program generates a random number between 1 and 100, and the player tries to guess it based on the hints: “Too high!” or “Too low!”.

## ⚙️ Program Features
* **True randomness:** Uses the system time to generate a unique number each time the program is launched.
* **Interactive hints:** The program dynamically helps the player narrow down the search range.
* **Efficient Loop:** The game continues until the player finds the correct number, after which it terminates properly.

# Compilation and Execution
To run the game, you’ll need a C++ compiler (e.g., GCC / G++).

Open a terminal (or command line) in the folder containing the `main.cpp` file and run the following commands:

### For Linux and macOS:
```bash
# 1. Compile the main.cpp file into the guess_game executable
g++ main.cpp -o guess_game

# 2. Run the game
./guess_game
