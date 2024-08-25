## Learning Rust

The e-book [The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html) is a great resource for learning Rust. To get the necessary Rust programming skills for the course labs, students are expected to go through Chapters 1-11, Chapter 13, and Chapter 15.1. Chapters 17 and 18 will help you write cleaner code if you like to read.

The suggested IDE is [VS Code](https://code.visualstudio.com/) with the [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) extension installed.

## Minigrep

The Minigrep project is intended for students to practice fundamental Rust programming skills. It is taken from [The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html). To finish this project, students need to follow the instructions in [Chapter 12](https://doc.rust-lang.org/book/ch12-00-an-io-project.html/) and [Chapter 13.3](https://doc.rust-lang.org/book/ch13-03-improving-our-io-project.html). 

## Testing Minigrep

We will use the following two commands to test the correctness of your minigrep project

```
cargo run -- to ./src/poem.txt
IGNORE_CASE=1 cargo run -- to ./src/poem.txt
```

The expected output for the first command is:
```
Are you nobody, too?
How dreary to be somebody!
```

The expected output for the second command is:
```
Are you nobody, too?
How dreary to be somebody!
To tell your name the livelong day
To an admiring bog!
```

