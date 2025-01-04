# Monkey Interpreter

Welcome to the Monkey Interpreter project! This interpreter is designed to execute programs written in the "Monkey" language. The Monkey language is a simple, yet powerful language that supports various features.

## Features

- **Primitive Data Types**: Supports `int`, `boolean`, and `string`.
- **Conditional Statements**: Includes support for `if-else` statements.
- **Functions**: Allows the definition and execution of functions.
- **Closures**: Supports closures for more advanced function usage.
- **Higher-Order Functions**: Functions can accept other functions as arguments and return them as results.

## Getting Started

To get started with the Monkey Interpreter, follow these steps:

1. Clone the repository:
  ```sh
  git clone https://github.com/dongrep/monkey.git
  ```
2. Navigate to the project directory:
  ```sh
  cd monkey
  ```
3. Build the project (if applicable):
  ```sh
  make build
  ```
4. Run the interpreter:
  ```sh
  ./monkey
  ```

## Usage

You can write Monkey programs and execute them using the interpreter. Here is an example of a simple Monkey program:

```monkey
let add = fn(a, b) {
  return a + b;
};

let result = add(5, 10);
if (result > 10) {
  puts("Result is greater than 10");
} else {
  puts("Result is 10 or less");
}
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Thanks to the creators of the Monkey language and all the contributors who have helped improve this interpreter.
