# DOTS Programming Language

**Created by Goodluck Guyitson**

DOTS is an interpreted, beginner-friendly programming language inspired by Python. It is designed to be easy to learn, yet powerful enough to handle artificial intelligence, machine learning, and app development.

## Features
- Simple syntax with `set`, `if`, `else if`, `else`, `loop`, `for`, `while`
- Supports `int`, `float`, `word`, `bool`
- Neural network, machine learning, and AI integration
- Easy debugging and auto-correction
- Full interpreter written in C

## Repository Structure
- `docs/` - Full documentation, Volumes 1 & 2
- `src/` - Source code for lexer, parser, and interpreter
- `examples/` - Example DOTS programs
- `LICENSE` - Open-source license

## Installation
Clone the repository:

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/DOTS-Language.git
cd DOTS-Language/src
gcc lexer.c parser.c interpreter.c -o dots_interpreter
