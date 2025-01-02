# CompilerXArabic

A compiler implementation for an Arabic-based programming language, featuring lexical analysis, syntax parsing, and a graphical user interface for interactive testing and development.

## Features

- 🔍 Lexical Analysis (Tokenizer)
- 🔬 Syntax Parser
- 🌐 Arabic Language Support
- 🖥️ Graphical User Interface
- ✅ Built-in Test Suite
- 🔄 Auto-Update Functionality

## Project Structure

- `main.py` - Main application entry point and GUI controller
- `tokenizer.py` - Lexical analyzer implementation
- `parser.py` - Syntax parser implementation
- `gui.py` - Graphical user interface implementation
- `Grammar rules.txt` - Language grammar specification
- `Tests.txt` - Test cases for the compiler
- `Grammar Rules.png` - Visual representation of grammar rules

## Requirements

- Python 3.x
- Required Python packages:
  - GitPython
  - requests
  - (GUI framework - specific package name needed)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Omar7001-B/CompilerXArabic
cd CompilerXArabic
```

## Usage

Run the main application:
```bash
python main.py
```

The GUI will provide options to:
- Input source code
- View tokenization results
- Check syntax parsing
- Run test cases
- Check for updates

## Grammar

The compiler supports an Arabic-based programming language with features including:
- Variable declarations
- Function declarations
- Type specifications (صحیح, حقیقى, خالى)
- Array declarations
- Compound statements

For detailed grammar rules, see `Grammar rules.txt`.

## Testing

The project includes a comprehensive test suite in `Tests.txt`. Use the GUI's test navigation features to:
- Run individual tests
- Navigate through test cases
- Verify compiler output

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request