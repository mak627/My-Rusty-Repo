# Installation
(Windows)
1. Download and install RUSTUP-INIT.EXE: https://www.rust-lang.org/tools/install
2. For windows system, also install Microsoft C++ Build Tools: https://visualstudio.microsoft.com/visual-cpp-build-tools/

For other installation methods, see here: https://forge.rust-lang.org/infra/other-installation-methods.html

Check if RUST is installed
    `rustc --version`
Update rust
    `rustup update`

# Using cargo
1. Check if cargo is installed
    > cargo --version
2. Create new package
    > cargo new hello_cargo
    > cd hello_cargo
3. Build
    > cargo build
4. Run
    > cargo run
Optional: You can also check for any errors without running the program
    > cargo check