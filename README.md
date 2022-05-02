# Runner

A Visual Studio Code extension to provide shortcut for running commands in the terminal.

## Installation

Just download the ".vsix" file located in the "build" directory of this repository and install it in VS Code.

## Usage

Open Command Palette(Ctrl+Shift+P to open it) of VS Code and type in the required commands.

### Commands

Command "Show Commands Mapping": Opens a Webview to add or remove commands. Developers can add dynamic commands.

Command "Run Command": Lets you choose a command to run.

### Dynamic Commands

Developers can add commands with `{{file}}` in the command and the currently open file location will be inserted at runtime in the command.

## Requirements

Visual Studio Code version ^1.69.0.

**Enjoy!**