# go-interpreter

Creating a simple interpreter in Go.

Book: [Writing An Interpreter In Go](https://interpreterbook.com/)

For the Rust version, see [here](https://github.com/AlvaroJSnish/rust-interpreter).

## Progress

- [x] Chapter 1: Lexing
- [x] Chapter 2: Parsing
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
let x = 1 + 2 + add(2, 3);
```
