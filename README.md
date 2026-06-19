# Rust-Decompress-Extract-zip-file-🦀 Rust ZIP Decompressor Utility

A simple and efficient ZIP extraction utility built with Rust that safely decompresses and extracts ZIP archives while preserving file structure and permissions.

Features

* Extracts ZIP archives quickly
* Handles files and directories automatically
* Creates missing folders during extraction
* Preserves Unix file permissions
* Safe path handling using enclosed_name()
* Error handling for invalid files and missing paths
* Lightweight command-line utility

⸻

Project Structure

Rust_Decompress/
│
├── src/
│   └── main.rs
├── Cargo.toml
├── Cargo.lock
└── README.md

⸻

Installation

Clone the repository:

git clone https://github.com/Hellboy28D/Rust-Decompress-Extract-ZIP-File-utility-.git

Move into the project directory:

cd Rust_Decompress

Build the project:

cargo build

⸻

Usage

Run the application with a ZIP file:

cargo run -- "sample.zip"

Example:

cargo run -- "1 (1).zip"

Output:

Trying to open: sample.zip
Archive contains 5 files
File 0 extracted to "documents/report.txt"
File 1 extracted to "images/logo.png"
Extraction completed successfully.

⸻

Technologies Used

* Rust
* ZIP crate
* Rust File System APIs
* Standard I/O library

⸻

Learning Outcomes

This project helped explore:

* File handling in Rust
* Working with external crates
* Error handling patterns
* Command-line argument processing
* Archive extraction techniques
* Memory-safe systems programming

⸻

Future Improvements

* Add support for password-protected ZIP files
* Add progress indicators
* Add support for multiple archive formats
* Build a GUI version
* Add asynchronous extraction

⸻

Author

Built with Rust and curiosity by Hellboy28D
