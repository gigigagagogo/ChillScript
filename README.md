# ChillScript

**ChillScript** is a lightweight interpreted programming language I developed during my Erasmus semester in Germany at **OTH Regensburg**, as part of the *Compiler Construction* course.

## Overview

ChillScript offers a relaxed and expressive programming experience thanks to its syntax inspired by American slang. It's designed to be intuitive and fun — ideal for beginners and refreshing for experienced developers.

## Key Features

- Custom lexer, parser, and interpreter built from scratch
- Full Abstract Syntax Tree (AST) implementation
- Dynamic typing with custom data types (`whole y`, `floaty`, `chain`, `list`)
- Control structures: `imagine` (if), `nah` (else), `as long as` (while), `one by one` (for)
- Functions defined with `a new one`, returning with `send back`
- Built-in functions for input/output, random number generation, and list operations
- AST optimizations: constant folding, dead code removal, loop simplification
- Cross-platform support (Linux and Windows)

## Project Structure

- Lexical analyzer
- Parser
- AST generator
- Interpreter
- AST optimizer
- Example programs:
  - Tower of Hanoi
  - Bubble Sort
  - Framed Text Printer
  - Rock Paper Scissors Lizard Spock
  - Language demo

## Course Requirements Fulfilled

- Lexical scanner  
- Syntax parser  
- AST construction  
- Interpreter  
- Optional AST optimization  
- Four required demonstration programs

## Sample Code

```chillscript
a_new_one zip greet(chain name) {
    throw_up("Hello, " + name + "!");
}
greet(^Robert^);
```

## Author

Bararu Robert Daniel  
Developed during my Erasmus exchange semester at [OTH Regensburg]


---

This README and project are in English to ensure accessibility for international audiences. Feel free to contact me if you prefer an Italian version.
