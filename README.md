# FISH Language Support for Visual Studio Code

This Visual Studio Code extension provides basic syntax highlighting for the FISH programming language, commonly used in Itasca's FLAC3D and other geotechnical software.

## Features

- Syntax highlighting for FISH code
- Recognizes FISH-specific keywords, operators, and comments
- Supports `.fis` file extensions

### Highlighted Syntax Elements:

- **Keywords**: `while`, `then`, `section`, `loop`, `if`, `else`, `define`, `command`, `caseof`, etc.
- **End Keywords**: `end`, `end_case`, `end_command`, `endif`, etc.
- **Operators**: `-`, `#`, `()`, `*`, `,`, `/`, `[`, `]`, `^`, `+`, `<`, `=`, `>`, etc.
- **Comments**: Single-line comments using `;`
- **Variables**: Common FISH functions and variables like `apply`, `array`, `call`, `config`, `solve`, etc.
- **Numbers**: Numeric constants

## Installation

1. Clone or download this repository.
2. Open the folder in Visual Studio Code.
3. Press `F5` to open a new VSCode window with the extension loaded.
4. Open a `.fis` file to see the syntax highlighting in action.

Alternatively, you can install this extension from the Visual Studio Marketplace (if published).

## Usage

- Install the extension and associate `.fis` files with the FISH language.
- The syntax highlighting should automatically apply when you open a FISH file.

## Example

Here is an example of FISH code that will be highlighted:

```fis
define myFunction
    ; This is a comment
    if x < 5 then
        loop
            call someFunction()
        end_loop
    endif
end
