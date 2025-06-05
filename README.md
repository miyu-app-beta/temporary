# Hello World in Rust

This repository contains a simple "Hello World" program written in Rust.

## Project Structure

- `hello_world/`: The main Rust project directory
  - `Cargo.toml`: The manifest file for Rust's package manager, Cargo
  - `src/`: The directory containing the Rust source code
    - `main.rs`: The main program file

## Running the Program

To run the "Hello World" program, follow these steps:

1. Make sure you have Rust installed on your system. If not, you can install it from [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install).

2. Navigate to the `hello_world` directory:
   ```
   cd hello_world
   ```

3. Build and run the program using Cargo:
   ```
   cargo run
   ```

You should see the output: `Hello world`

## Testing

This simple program doesn't include any tests, as it only prints a static message to the console. However, for more complex Rust projects, you can add tests in the `src/main.rs` file or in separate test modules.