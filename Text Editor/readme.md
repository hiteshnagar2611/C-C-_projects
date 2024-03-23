# RockMITx Editor

RockMITx Editor is a simple text editor written in C, based on the kilo text editor. It provides basic text editing functionalities such as creating, editing, and saving text files.

## Features

- **Syntax Highlighting**: Supports basic syntax highlighting for C files.
- **Cursor Movement**: Navigate the text using arrow keys and other navigation keys.
- **Insertion and Deletion**: Insert characters, newlines, and delete characters.
- **Find and Replace**: Search for specific strings within the text.

## How to Compile

1. Ensure you have a C compiler installed on your system (e.g., GCC).
2. Open a terminal window and navigate to the directory containing the source code files.
3. Compile the program using the following command:
   ```bash
   gcc -o editor editor.c -Wall -Wextra -pedantic -std=c99
   ```
   Replace `editor.c` with the actual filename if it's different.

## How to Run

After compiling the program, run it by executing the compiled binary:
```bash
./editor
```

## Usage

- **Navigation**: Use arrow keys (up, down, left, right) to move around the text.
- **Text Editing**: Insert characters using your keyboard. Use Backspace to delete characters.
- **Save and Exit**: Press `Ctrl + S` to save the file and `Ctrl + Q` to exit the editor.

## Additional Notes

- This editor is designed for basic text editing tasks and may not support advanced features found in modern text editors.
- For syntax highlighting to work correctly, ensure that the file extension matches one of the supported file types (e.g., `.c` for C source files).

---
