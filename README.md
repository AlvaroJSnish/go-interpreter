# go-interpreter

Creating a simple interpreter for the Go programming language.

Book: [Writing An Interpreter In Go](https://interpreterbook.com/)

## Progress

- [x] Chapter 1: Lexing
- [ ] Chapter 2: Parsing
- [ ] Chapter 3: Evaluating
- [ ] Chapter 4: Extending the Interpreter
- [ ] Going further.

## Usage

### REPL

```bash
$ go run main.go
```

Pass any code to the REPL and it will be lexed.

Example:

```bash
let add = fn(x, y) { x + y; };
```
