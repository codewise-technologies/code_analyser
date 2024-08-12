
# Code Analyser

**Code Analyser** is a simple code analyzer built in Rust that supports multiple programming languages, including JavaScript, TypeScript, Python, and Go. The tool is designed to analyze your codebase for quality metrics such as cyclomatic complexity and other code quality indicators.

## Features

- **Multi-language support:** Analyze JavaScript, TypeScript, Python, and Go code.
- **Code quality metrics:** Evaluate the complexity and structure of your code.
- **Command-line interface:** Easy to use from the terminal.
- **Extensible:** Built with Rust, making it easy to extend for other languages or features.

## Installation

To install `code_analyser`, you'll need to have Rust installed on your system. You can install Rust by following the instructions [here](https://www.rust-lang.org/tools/install).

Once Rust is installed, you can install `code_analyser` using the following command:

```bash
cargo install code_analyser
```

This will install the `code_analyser` binary globally on your system.

## Usage

You can run the `code_analyser` on a specific project by passing the path to the project directory as an argument. For example:

```bash
code_analyser /path/to/your/project
```

This will analyze all JavaScript, TypeScript, Python, and Go files in the directory and print a report with the results.

### Example

```bash
code_analyser ./my_project
```

This command will analyze the `./my_project` directory and output the analysis results.

## Contributing

Contributions are welcome! If you'd like to contribute to `code_analyser`, please fork the repository and submit a pull request. We welcome improvements to the codebase, additional features, and new language support.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please contact Pool Camacho Gonzales at [tu.email@example.com](mailto:tu.email@example.com).
