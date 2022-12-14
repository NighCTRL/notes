# CLI interface

cargo commands are a cli interface for the cargo package manager for rust
cargo init
  -> create a basic rust project inside cwd
cargo run
  ->  run the application
cargo build 
  -> build the application
cargo builld --release

# Syntax

semicolon required at the end of line;

require a file and use imported function
```rust
mod [name]
fn main() {
        [name]::[function]();
    }
```
# some remarks

```rust
// is a comment
```
variables are immutable by default
```rust
//Can't do 
let age = 43;
age = 44;

// Can be mutated
let mut age = 43;
age = 44;
```
rust is a blocked scope language

Statically typed language = must know type of every variable at compile time.
The compiler can sometime infer the type of the variable

```rust
// type of i32
let age = 30;
// type of float64
let days = 4.2;
```
tuples are fixed length collection of values of different types.
