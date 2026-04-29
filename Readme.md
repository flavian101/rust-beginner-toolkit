# Getting Started with Rust – A Beginner’s Toolkit

## ✅ Title & Objective

**Title:** Getting Started with Rust – A Beginner’s Toolkit  
**Objective:** Learn Rust basics, set up the environment, and run a simple Hello World program.

---

## ✅ Quick Summary of Rust

- Rust is a systems programming language focused on safety and performance.
- It prevents common bugs like memory leaks and data races.
- It’s used in web servers, operating systems, and embedded devices.
- Real-world example: Mozilla Firefox uses Rust for performance-critical components.
- Rust emphasizes **memory safety without garbage collection**, making it unique compared to other languages.

---

## ✅ System Requirements

- **OS:** Windows 10/11 (tested), Linux/Mac also supported.
- **Editor:** VS Code or any text editor.
- **Tools:** Rustup installer (includes Cargo).
- **Git:** For version control and pushing to GitHub.
- **Internet:** Required to download Rust installer and dependencies.

---

## ✅ Installation & Setup (Windows)

1. Download installer: [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install)
2. Run `.exe` and choose default installation.
3. Verify installation:
   ```powershell
   rustc --version
   ```
   Expected output: `rustc 1.xx.x (yyyy-mm-dd)`

---

## ✅ Minimal Working Example

File: `src/main.rs`

```rust
fn main() {
    println!("Hello, Moringa Capstone!");
}
```

Run with:

```powershell
cargo run
```

Expected output:

```
Hello world!
```

---

## ✅ Project Structure

When you create a new Rust project with Cargo, the folder looks like this:

```
hello_moringa/
├── Cargo.toml        # Project configuration file
└── src/
    └── main.rs       # Main source file
```

- `Cargo.toml` defines dependencies and metadata.
- `src/main.rs` contains your Rust code.
- `cargo run` compiles and executes the program.

---

## ✅ AI Prompt Journal

This section records the prompts I used with AI, the responses I received, and my reflections on how they helped me learn Rust.

---

### Prompt 1: Installation

**Prompt:**  
“Give me step-by-step instructions to install Rust on Windows and verify installation.”

**AI Response (Summary):**

- Directed me to the official Rust installer (rustup).
- Explained how to run the `.exe` file with default options.
- Showed how to verify installation using `rustc --version`.

**Reflection:**  
This saved me time compared to searching multiple blogs. The instructions were clear and matched the official documentation. I learned that Rustup also installs Cargo, which is Rust’s build tool.

---

### Prompt 2: Hello World Program

**Prompt:**  
“Show me how to write and run a Hello World program in Rust.”

**AI Response (Summary):**

- Suggested creating a new project with `cargo new hello_world`.
- Explained the project structure (`Cargo.toml`, `src/main.rs`).
- Provided sample code using `println!`.
- Showed how to run the program with `cargo run`.

**Reflection:**  
This was straightforward and helped me understand how Cargo manages projects. I realized Rust enforces a clean project structure from the start, which is different from languages like Python.

---

### Prompt 3: Common Errors

**Prompt:**  
“What common errors occur when running Rust for the first time, and how do I fix them?”

**AI Response (Summary):**

- PATH not set → restart terminal or add Rust manually.
- Git push issues → check remote URL and authentication.
- Cargo not found → ensure Rustup installed Cargo.

**Reflection:**  
This was very useful because I actually faced the PATH issue. Having the fix ready saved me from frustration. It showed me how AI can anticipate beginner mistakes.

---

### Prompt 4: Documentation Summary

**Prompt:**  
“Summarize the official Rust documentation for beginners in 5 bullet points.”

**AI Response (Summary):**

- Rust emphasizes memory safety and ownership.
- Cargo is the standard build and package manager.
- The Rust Book is the main learning resource.
- Rust has strong community support and open-source libraries.
- Beginners should start with simple projects before exploring advanced features.

**Reflection:**  
This gave me a roadmap of what to learn next. It highlighted ownership and borrowing, which I now know are core concepts in Rust.

---

### Overall Reflection

Using AI prompts made the learning process faster and more structured. Instead of searching randomly, I had guided steps with explanations and troubleshooting tips. The journal also shows how I iterated — asking about installation, then Hello World, then errors, then documentation.

## ✅ Common Issues & Fixes

- **Issue:** `rustc` not recognized in PowerShell.
  - **Fix:** Restart terminal or add Rust to PATH manually.

- **Issue:** Git push failed.
  - **Fix:** Check remote URL and authentication.

- **Issue:** Cargo not found.
  - **Fix:** Ensure Rust installation included Cargo (default option).

---

## ✅ Peer Testing

- Shared repo with a peer to follow instructions.
- Feedback: PATH setup was confusing → clarified step in README.
- Peer successfully cloned repo and ran Hello World.
- Adjusted documentation based on feedback.

---

## ✅ References

- [Rust Official Docs](https://doc.rust-lang.org/book/)
- [Rust Installation Guide](https://www.rust-lang.org/tools/install)
- Helpful blog posts / YouTube tutorials (add links you used).

---

## ✅ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/rust-beginner-toolkit.git
   ```
2. Navigate into the project:
   ```bash
   cd hello_world
   ```
3. Run the program:
   ```bash
   cargo run
   ```
   Expected output:

```
Hello world!
```

---

## ✅ Final Notes

- This toolkit is designed for beginners starting with Rust.
- It documents installation, setup, and a working example.
- AI prompts were used to guide learning and troubleshooting.
- Future improvements: add more examples (variables, functions, loops) and expand the toolkit into a mini Rust tutorial.
