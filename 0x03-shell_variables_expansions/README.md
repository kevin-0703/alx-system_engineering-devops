# Shell Variables, Expansions, and Scripting Tasks

This repository contains scripts demonstrating various shell scripting concepts, including alias creation, environment variables, path manipulation, variable handling, calculations, and more, aligned with learning objectives for Linux shell scripting.

## Tasks

### Task 0: Create an alias for `ls`

Defines an alias `ls='rm *'` which, when sourced, overrides the default `ls` command.

### Task 1: Print greeting with current user

Prints "hello [user]" where `[user]` is obtained from the `$USER` environment variable.

### Task 2: Append `/action` to `PATH`

Adds `/action` directory to the end of the current `PATH` environment variable.

### Task 3: Count directories in `PATH`

Counts how many directories are listed in the `PATH` variable.

### Task 4: List all environment variables

Displays all environment variables using `printenv`.

### Task 5: List all variables and functions

Shows all local variables, environment variables, and functions.

### Task 6: Create a local variable `BEST` with value "School"

Creates a local variable within the script (sourcing required).

### Task 7: Create a global variable `BEST` with value "School"

Exports a global environment variable.

### Task 8: Add 128 to `TRUEKNOWLEDGE` and display the result

Calculates `128 + $TRUEKNOWLEDGE`.

### Task 9: Divide `POWER` by `DIVIDE` and display

Performs division using environment variables.

### Task 10: Calculate `BREATH` to the power of `LOVE`

Uses exponentiation operator for calculation.

### Task 11: Convert binary number in `BINARY` to decimal

Converts binary string to decimal number.

### Task 12: Generate all two-letter combinations excluding `oo`

Outputs all combinations from `aa` to `zz` except `oo`.

### Task 13: Print a float with two decimal places from `NUM`

Formats `NUM` with two decimal places.

---

## Usage

Each script is designed to be sourced or executed as needed. Ensure scripts have execution permissions:

```bash
chmod +x script_name.sh
```
