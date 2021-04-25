# ppp

Workspace for example and test code in Programming Principles and Practice Using C++ (Second Edition) by Bjarne Stroustrup.

Based on the [program_selector](https://github.com/mhjlam/program_selector) repository.

## Building

Use the `build.sh` script to build a separate project for each folder in the `src` directory. Program arguments:

- `-b`: Build the source code after generating project files.
- `-r`: Generate project files, build the source code, and then run the `program_selector` executable.
- `-d`: Use the `Debug` configuration instead of `Release` configuration. Can be combined with `-b` or `-r`.
