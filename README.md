# Guessing Game

This program has been written using the [tutorial][t] from the [`rust-lang`][r]
["The Book"][b].

[t]: https://doc.rust-lang.org/book/guessing-game.html "Rust: Guessing Game"
[b]: https://doc.rust-lang.org/book/ "Rust: The Book"
[r]: https://www.rust-lang.org/ "Rust Programming Language"

## Development

Clone the repository to your computer and change into the directory. Once
inside, run `cargo run` and enjoy the game.

```shell
$ cargo run
     Running `target/debug/guessing_game`
Guess the number!
Please input your guess.
10
You guessed: 10
Too small of a guess!
Please input your guess.
40
You guessed: 40
Too big of a guess!
Please input your guess.
30
You guessed: 30
Too big of a guess!
Please input your guess.
20
You guessed: 20
Too small of a guess!
Please input your guess.
22
You guessed: 22
Too big of a guess!
Please input your guess.
21
You guessed: 21
You win!
```
