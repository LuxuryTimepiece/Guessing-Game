---
# Guess the Number Game - Rust Book Tutorial

This Rust project implements a simple interactive game where players guess a 
randomly generated number within a specific range. The program demonstrates 
basic input/output handling, error management, and decision-making logic using 
Rust's standard library functions. 

## Getting Started

To run this game locally on your machine:

1. Ensure you have Rust installed (https://www.rust-lang.org/).
2. Clone or download this repository to your local machine.
3. Open a terminal and navigate to the project directory.
4. Execute the following command to compile and run the program:
```bash
cargo run
```
## How to Play

1. The game starts by prompting you to guess a number within the range of 1 to 100.
2. Enter your guess, ensuring it's a valid positive integer.
3. The program will respond with feedback on whether your guess is too small, too big, or correct (and the game ends).
4. Continue playing until you win!

## Features and Highlights

- Utilizes Rust's `rand` crate for generating random numbers within a specified range.
- Manages input validation using pattern matching and error handling mechanisms.
- Implements decision logic with `match` expressions, comparing guessed values 
to the secret number.
- Provides informative output messages based on player inputs and game state.
