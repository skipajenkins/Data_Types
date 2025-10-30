🦀 Rust Data Types Playground

A simple and educational Rust program showcasing scalar and compound data types — the building blocks of Rust’s type system.
This project explores how Rust handles numbers, booleans, characters, tuples, and arrays, while demonstrating basic arithmetic and user input.

📖 Overview

Rust’s type system ensures memory safety and performance without sacrificing flexibility.
In this project, you’ll find examples of:

Scalar types: integers, floats, booleans, and characters

Compound types: tuples and arrays

Basic operations like addition, subtraction, multiplication, and division

Interactive user input for array element access

✨ Features

✅ Demonstrates all major data types in Rust
✅ Includes arithmetic and logical operations
✅ Shows tuple destructuring and array indexing
✅ Accepts user input for interactive learning

🧱 Project Structure
Data_Types/
├── src/
│   └── main.rs
└── Cargo.toml        # (optional if you decide to add a Rust package manifest)

⚙️ Setup & Installation
🦾 Prerequisites

Make sure Rust and Cargo are installed on your system.
You can check using:

rustc --version
cargo --version


If not installed, get Rust via rustup:

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

🚀 Running the Program

Clone the repository

git clone https://github.com/skipajenkins/Data_Types.git


Navigate into the project directory

cd Data_Types


Run the project

cargo run


You’ll be prompted to enter an array index — the program then prints the element value.

🧠 Example Output
Please enter an array index.
2
The value of the element at index 2 is: 3

🧩 Code Highlights
// Scalar Types
let x = 2.0;       // f64
let y: f32 = 3.0;  // f32
let t = true;
let c = 's';
let heart_eye_cat = '😻';

// Compound Types
let tup: (i32, f64, u8) = (500, 6.4, 1);
let (x, y, z) = tup;
println!("The value of z is: {z}");

let a = [1, 2, 3, 4, 5];

🧑‍💻 Author

Skipajenkins
🔗 GitHub Profile

⚖️ License

This project is open-source and available under the MIT License.
