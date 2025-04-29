# Writing an Interpreter in Go

This repo follows the book by Thorsten Ball which walks through building a working interpreter for a programming language called **Monkey**, using the Go programming language.
I tweaked a few steps he has recommended and changed the name to **MagicBall**

## Focus Areas

- **Lexical Scanning (Lexer)**  
  Tokenizing the source code into a stream of meaningful symbols (tokens).

- **Parsing (Parser)**  
  Constructing an Abstract Syntax Tree (AST) from tokens using a Pratt parser.

- **Evaluation (Interpreter)**  
  Walking the AST to evaluate statements and expressions.

- **Environment Handling**  
  Managing scopes and variable bindings with hash maps.

- **Built-in Functions**  
  Implementing core language functions directly in Go.

- **Testing**  
  Strong emphasis on test-driven development using Go's `testing` package.

- **Minimal Dependencies**  
  Entire project uses only Go's standard library.


