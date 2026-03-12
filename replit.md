# C List & Stack Exercises Lab

## Overview
This is a student lab project for practicing C data structures (Lists and Stacks).

## Project Structure
- `exercises.c` — Student code (the only file students should modify)
- `arraylist.h` / `arraylist.c` — ArrayList (List) TDA implementation
- `stack.h` — Stack TDA header
- `test.c` — Test suite (do not modify)
- `test.sh` — Build and test runner script

## How to Run Tests
Open the Shell and run:
```bash
bash test.sh
```

## Workflow
- **Start application**: Runs `bash test.sh` — compiles and executes the test suite.

## Language & Toolchain
- Language: C (GCC 14.3.0)
- Build: `gcc -g test.c -Wall -Werror -o a.out`
- Debugger: GDB

## Notes
- Only `exercises.c` should be modified by the student.
- No frontend or web server — this is a pure CLI/C project.
