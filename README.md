# VSCode C/CPP project template

This repository contains a project template C/C++ targetting VSCode as the IDE.
This is a good starting point for developing C/C++ projects.

## VSCode Tasks

The VSCode Tasks are used for compiling the project.
The tasks have configured 3 C/C++ compilers:

1. Micorsoft MSVC
2. GCC
3. CLANG

Additionally the tasks are configured to compile with latest C++ version (`-std=c++20`).
In case an older compilation is required than the above argument can be altered as desired.

## Note

Install the [C/C++ Extension Pack]([https://](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack)) in VSCode.
The above extension pack enables support for code auto-completion and also there are some configurations which can be defined to enhance the developer experience.
The configuration can be accessed via the VSCode `Command Palette` -> `C/C++: Edit Configurations (UI)`.
