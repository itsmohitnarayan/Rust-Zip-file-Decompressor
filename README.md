# Rust-Zip-file-Decompressor

📦 **Project Description**

A simple Rust program for extracting files from a ZIP archive, with added functionality for handling comments, directory creation, and Unix permissions. The program utilizes the `zip` crate to work with ZIP files and provides a command-line interface for extracting files.

🚀 **Getting Started**

To use this program, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/itsmohitnarayan/Rust-Zip-file-Decompressor
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repo
   ```

3. Build and run the program:

   ```bash
   cargo run --release <filename.zip>
   ```

   Replace `<filename.zip>` with the path to your ZIP file.

🔧 **Prerequisites**

Make sure you have Rust installed on your machine. If not, you can install it by following the instructions on the [official Rust website](https://www.rust-lang.org/tools/install).

👨‍💻 **Usage**

```bash
cargo run --release <filename.zip>
```

- Replace `<filename.zip>` with the path to the ZIP file you want to extract.

📜 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

🌐 **Acknowledgments**

- The program uses the `zip` crate for working with ZIP files. Check out the [zip crate documentation](https://docs.rs/zip) for more information.

👀 **Note**

This is a simple utility designed for basic ZIP extraction needs. Feel free to enhance or modify the code according to your requirements. 
This program is not supported with the zip having passowrd, will upgrade in future.
Contributions are welcome!

🚨 **Disclaimer**

This project is provided as-is and does not guarantee compatibility with all ZIP file variations. Use it responsibly and make sure to test it on various ZIP files to ensure expected behavior.
