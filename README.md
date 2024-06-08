# CFileMan
CFileMan is a simple file management system implemented in C. It provides basic functionalities for creating, reading, updating, and deleting files, along with error handling and logging capabilities.

## Features

- **File Management Functions**: Allows users to perform operations like creating new files, reading existing files, updating file content, and deleting files.
- **Error Handling**: Gracefully handles common errors such as file not found, insufficient memory, and invalid input, providing informative error messages to the user.
- **Logger**: Implements a logging system to record events and errors, including timestamps, severity levels, and descriptive messages.
- **Memory Allocation/Initialization**: Ensures proper memory allocation and initialization to avoid memory leaks and undefined behavior.
- **User Interface**: Provides a simple command-line interface for users to interact with the file management system, with clear instructions and feedback for each operation.
- **Testing**: Includes comprehensive test cases to verify the correctness of functionalities, error handling, and logging under various scenarios.

## Usage

1. Clone the repository:

```bash
https://github.com/StjepanPrakljacic/CFileMan.git
```
2. Compile the source code using the provided Makefile:
```bash
make
```
3. Run the executable:

```bash
./bin/cfileman
```

5. Follow the instructions in the command-line interface to perform file operations.

## Requirements

- C compiler (e.g., GCC)
- Make

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests with improvements or additional features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
