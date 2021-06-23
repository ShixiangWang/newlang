# newlang: "Writing An Interpreter in Go" practice 

source: https://interpreterbook.com/

PARTs:

- Token: words to represent code inside.
- Lexer：creates tokens from the sequence of input characters.
- REPL (Read Eval Print Loop): reads input, sends it to the interpreter for evaluation, prints the result/output of the interpreter and starts again.
- Parser: takes input data (tokens) and builds a data structure - often some kind of parse tree, abstract syntax tree (AST for short).
