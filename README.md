# 🦀 Rust Guessing Game! 

Hey there! 👋 Welcome to my very first Rust project. This is **Assignment 1** for the Turbine Builders program.

As a starting point for my Rust journey, I built this classic Guessing Game by following Chapter 2 of [The Rust Programming Language Book](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html). It was super fun putting this together and getting my hands dirty with Rust for the first time!

## ✨ What does it do?

It's pretty simple but a great learning exercise:
- The game secretly picks a random number between 1 and 100.
- It asks you to guess what the number is.
- If you guess too high or too low, it gives you a hint.
- Try to type letters instead of a number? It won't crash—it just politely asks you to try again!
- Keep guessing until you get it right, and it will congratulate you before finishing.

## 🚀 Wanna give it a spin?

If you want to play it on your own machine, make sure you have Rust and Cargo installed first. (If you don't, you can grab them from [rustup.rs](https://rustup.rs/)).

1. **Clone this repo to your computer:**
   ```bash
   git clone https://github.com/SAMIR897/Guessing-Game.git
   cd Guessing-Game
   ```

2. **Run the game:**
   ```bash
   cargo run
   ```
   *Cargo will automatically download the little `rand` dependency I used and compile the code for you.*

## 🎮 What it looks like when playing:

```text
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

## 🧠 What I learned building this

Building this little game actually taught me a bunch of fundamental Rust concepts, like:
- How to set up and manage a project using `cargo`.
- Working with variables (and making them `mut`able!).
- Taking input from the terminal with `std::io::stdin`.
- Generating random numbers with the `rand` crate.
- Writing infinite loops (`loop`) and breaking out of them when you win.
- Using `match` statements to handle different outcomes and gracefully catch errors without panicking.

Thanks for stopping by and checking out my code! ✌️
