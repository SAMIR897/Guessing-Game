# Guessing Game

Assignment 1 for Turbine Builders. This project is a Rust implementation of the classic Guessing Game tutorial from [The Rust Programming Language Book (Chapter 2)](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html).

## Features

- Generates a random secret number between 1 and 100.
- Prompts the user to guess the number.
- Provides feedback if the guess is too high or too low.
- Handles invalid inputs gracefully without crashing.
- Ends with a congratulatory message upon a correct guess.

## Prerequisites

Make sure you have Rust and Cargo installed. If not, install them using `rustup`:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SAMIR897/Guessing-Game.git
   cd Guessing-Game
   ```

2. Compile and run the game using Cargo:
   ```bash
   cargo run
   ```

## Example Gameplay

```
Guess the number!
Please input your guess.
50
You guessed: 50
Too small!
Please input your guess.
75
You guessed: 75
Too big!
Please input your guess.
62
You guessed: 62
You win!
```

## Concepts Covered

- Basic Rust syntax and `Cargo` project management.
- Variables and mutability (`let mut`).
- Handling user input via `std::io::stdin`.
- Using external crates (`rand` for random number generation).
- Control flow (`loop`, `match`, and `break`).
- Error handling with `Result` and `match`.

## License

This project is created for learning purposes as part of the Rust Book tutorial.
