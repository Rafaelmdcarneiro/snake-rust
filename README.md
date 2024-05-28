# snake-rust-game (How to run)

[Rust & WebAssembly with JS (TS) - The Practical Guide
](https://www.udemy.com/course/rust-webassembly-with-js-ts-the-practical-guide/?referralCode=B8BF2207B45019CC1B3D)

### Dependencies

1. Install rustup -> https://doc.rust-lang.org/book/ch01-01-installation.html

2. Install "wasm-pack" -> `cargo install wasm-pack`

3. Install npm dependencies -> `npm install` (must have Node JS) -> https://nodejs.org/)

### Compilation
Compile the rust code every time the changes are made in `src/lib.rs`

4. Compile rust code into web-assembly -> `wasm-pack build --target web`

5. Run the development server
`npm start`

6. Open the browser on `localhost:8080`
