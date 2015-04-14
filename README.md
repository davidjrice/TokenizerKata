Tokenizer
=========

Create a tokenizer which will process the following code and classify each token:

Input:
```
module Jack {
  void func main(int args) {
    do Output.write("Hello");
  }
}
```

Output:
```
[
  keyword: "module",
  identifier: "Jack",
  symbol: "{",
  keyword: "void",
  keyword: "func",
  identifier: "main",
  symbol: "{",
  keyword: "int",
  identifier: "args",
  symbol: ")",
  symbol: "{",
  keyword: "do",
  identifier: "Output",
  symbol: ".",
  identifier: "write",
  symbol: "(",
  string: "Hello",
  symbol: ")",
  symbol: ";",
  symbol: "}",
  symbol: "}"
]
```
