# Rust Guessing Number Game
This is a simple guessing number game made in Rust. The program generates a random number between 1 and 10, and the user has to guess the number. The user can input their guess and the program will tell them if their guess is too small, too big, or if they have won.

## How to Play
1. Clone the repository or download the guessing_game.rs file.
2. Install Rust on your machine if you haven't already. You can do this by following the instructions here.
3. Open your terminal and navigate to the directory containing the guessing_game.rs file.
4. Compile the program by running the following command:
```bash
rustc guessing_game.rs
```
5. Run the program by running the following command:
```bash
./guessing_game
```
6. The program will prompt you to input your guess. Input a number between 1 and 10 and press enter.
7. The program will tell you if your guess is too small, too big, or if you have won. If you have not won, go back to step 6 and keep guessing until you win.

## Dependencies
This program uses the rand and std::io libraries. These are part of the Rust standard library and should be available by default.
