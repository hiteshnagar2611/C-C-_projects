# Simple Shell in C

This is a simple Unix shell implementation written in C based on the tutorial by Stephen Brennan. The shell provides basic functionalities such as executing external commands, handling built-in commands, and allowing simple input/output redirection.

## Getting Started

To compile the shell program, use the following command:

```bash
gcc -o shell shell.c
```

Then, run the shell using:

```bash
./shell
```

## Features

- Executes external commands (e.g., `ls`, `cat`, etc.).
- Supports built-in commands:
  - `cd`: Change directory.
  - `help`: Display help information about the shell.
  - `exit`: Exit the shell.
- Handles basic input/output redirection (e.g., `ls > output.txt`).

## Usage

Once the shell is running, you can enter commands just like in a standard Unix shell. For example:

```bash
ls -l
cd /path/to/directory
help
exit
```

## Notes

- This shell implementation is a simplified version and lacks advanced features such as piping, scripting, environment variables, etc.
- Error handling is basic and may not cover all edge cases.
- This project is intended for educational purposes and to demonstrate basic shell functionalities in C.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
