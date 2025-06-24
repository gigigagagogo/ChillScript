# ChillScript 🧊

**ChillScript** is a lightweight interpreted programming language I developed during my Erasmus semester in Germany at **OTH Regensburg**, as part of the *Compiler Construction* course.

## 🚀 Overview

ChillScript offers a relaxed and expressive programming experience thanks to its syntax inspired by American slang. It's designed to be intuitive and fun — ideal for beginners and refreshing for experienced developers.

> Yes, you'll find keywords like `imagine`, `nah`, `throw up`, and `a new one` in the syntax. It's meant to be chill 😎

## 📚 Key Features

- 🧠 Custom **lexer**, **parser**, and **interpreter** built from scratch
- 🏗️ Full **Abstract Syntax Tree (AST)** implementation
- 🧵 **Dynamic typing** with custom data types (`whole y`, `floaty`, `chain`, `list`)
- 🔄 Friendly control structures: `imagine` (if), `nah` (else), `as long as` (while), `one by one` (for)
- 🧩 Functions: defined via `a new one`, returned via `send back`
- 🛠️ Built-in functions: input (`gimme`), output (`throw up`), random (`rando`), lists (`join in`, `size up`)
- ⚙️ AST optimizations: constant folding, dead code removal, loop simplifications
- 💻 Fully cross-platform, runs on Linux and Windows

## 🔧 Project Structure

- **Lexical analyzer**
- **Parser**
- **AST generator**
- **Interpreter**
- **AST optimizer**
- Example programs:
  - Tower of Hanoi
  - Bubble Sort
  - Framed Text Printer
  - Rock Paper Scissors Lizard Spock
  - Language demo

## 🧠 Course Requirements Fulfilled

✔️ Lexical scanner  
✔️ Syntax parser  
✔️ AST construction  
✔️ Interpreter  
✔️ Optional AST optimization  
✔️ Four required demonstration programs

## 💡 Sample Code

```chillscript
a_new_one zip greet(chain name) {
    throw_up("Hello, " + name + "!");
}
greet(^Luciano^);
```

## 🛠 Tech Stack

- Language: C++
- Build system: Makefile
- IDE: VS Code / CLion
- OS: Linux / Windows

## ▶️ How to Run

```bash
make
./chillscript
```

You can either write ChillScript code interactively or load it from a `.txt` script file.

## 👨‍💻 Author

**Luciano Carlo Romano**  
Built during my Erasmus exchange semester at [OTH Regensburg](https://www.oth-regensburg.de/)

## 📄 License

MIT (or leave blank if undecided — happy to help pick one)

---

_This README and project are in English to ensure accessibility for international audiences. Feel free to contact me if you prefer an Italian version._
