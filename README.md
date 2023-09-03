# MyRust

My Rust

## Online rust compiler

https://play.rust-lang.org/?version=stable&mode=debug&edition=2021

## How to quick start a simple rust hello world program?

To quickly start a simple "Hello, World!" program in Rust, follow these steps:

1. **Install Rust:**

   If you haven't already, you'll need to install Rust on your system. You can do this by visiting the official Rust website (https://www.rust-lang.org/), and following the installation instructions for your platform.

2. **Create a New Rust Project:**

   Open your terminal or command prompt, and navigate to the directory where you want to create your Rust project. To create a new Rust project, use the following command:

   ```bash
   cargo new hello_world
   ```

   This command will create a new directory named `hello_world` containing a basic Rust project structure.

3. **Edit the Rust Source Code:**

   Navigate to the project directory:

   ```bash
   cd hello_world
   ```

   Inside this directory, you'll find a `src` folder. Inside the `src` folder, there's a file named `main.rs`. Open `main.rs` with a text editor and replace its contents with the following Rust code:

   ```rust
   fn main() {
       println!("Hello, World!");
   }
   ```

   This code defines a `main` function that prints "Hello, World!" to the console.

4. **Run the Rust Program:**

   To run your Rust program, use the `cargo run` command:

   ```bash
   cargo run
   ```

   You should see the output "Hello, World!" printed to the terminal.

That's it! You've successfully created and run a simple "Hello, World!" program in Rust. You can now continue to develop more complex Rust applications using the Cargo build system.
