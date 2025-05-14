# GoMonkey 

[![GitHub Workflow Status](https://github.com/aiden007700/goMonkey/actions/workflows/ci.yml/badge.svg)](https://github.com/aiden007700/goMonkey/actions/workflows/ci.yml)
[![Go](https://skillicons.dev/icons?i=go)](https://skillicons.dev)

My implementation of the Monkey programming language from the book "Writing an Interpreter in Go".

## About Monkey Language

Monkey is a programming language designed to learn about interpreter and compiler construction. It features:

- C-like syntax
- Variable bindings
- First-class and higher-order functions
- Closures
- Integer arithmetic
- Built-in data structures
- A unique object system

## Getting Started

### Prerequisites

- Go 1.24 or higher

### Installation

```bash
git clone https://github.com/aiden007700/goMonkey.git
cd goMonkey
````

### Running the REPL
```bash
go run main.go
```

### Running Tests
```bash
go test ./...
```

## Project Structure

- `token/` - Token definitions and lexical analysis
- `lexer/` - Lexical analyzer implementation
- `parser/` - Syntax analyzer and AST generator
- `ast/` - Abstract Syntax Tree definitions
- `evaluator/` - Interpreter core
- `object/` - Runtime object system

## TODO LIST
- [ ] Add suport for floating point numbers




# goMonkey
