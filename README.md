# Rust Book Code

This repo contains the code used when following the Rust Book docs.
This file is my notebook along the way.

## Project Directory

1. Getting Started
    - 1.2. [Hello, World!](https://doc.rust-lang.org/book/ch01-02-hello-world.html) | [Code](./hello_world)
    - 1.3. [Hello, Cargo!](https://doc.rust-lang.org/book/ch01-03-hello-cargo.html) | [Code](./hello_cargo)
2. [Programming a Guessing Game](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html) | [Code](./guessing_game)
3. Common Programming Concepts
    - 3.1. [Variables and Mutability](https://doc.rust-lang.org/book/ch03-01-variables-and-mutability.html) | [Code](./variables)


## Commands

### `rustc`

| Command                | Description                     |
|------------------------|---------------------------------|
| `rustc --version`      | Prints Rust version information |
| `rustc <path/to/file>` | Compiles Rust file              |

### `rustup`

| Command                 | Description            |
|-------------------------|------------------------|
| `rustup update`         | Updates Rust version   |
| `rustup self uninstall` | Uninstalls Rust        |
| `rustup docs`           | View Rust docs locally |

### `cargo`

| Command                    | Description                             |
|----------------------------|-----------------------------------------|
| `cargo --version`          | Prints Cargo version information        |
| `cargo new <project-name>` | Creates new Cargo project               |
| `cargo build`              | Compiles Cargo project                  |
| `cargo build --release`    | Compiles for release with optimizations |
| `cargo run`                | Compiles and runs Cargo project         |
| `cargo check`              | Checks code is compilable               |
| `cargo update`             | Updates Cargo packages                  |
| `cargo doc --open`         | Build and open dependency docs locally  |
