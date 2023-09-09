# 0x03. Shell, init files, variables, and expansions

This repository contains a set of scripts written in Bash to help you understand and practice various aspects of shell scripting, initialization files, variables, and expansions.

## Table of Contents

1. [General Information](#general-information)
2. [Learning Objectives](#learning-objectives)
3. [Tasks](#tasks)
4. [Requirements](#requirements)
5. [Usage](#usage)
6. [Quiz Questions](#quiz-questions)
7. [Author](#author)
8. [License](#license)

## General Information

This project is part of the DevOps curriculum and focuses on improving your understanding of shell scripting. It covers topics such as shell initialization files, variables, expansions, and more.

## Learning Objectives

After completing this project, you should be able to explain the following concepts without relying on external sources:

### General
- What happens when you type `$ ls -l *.txt`.

### Shell Initialization Files
- What are the `/etc/profile` file and the `/etc/profile.d` directory.
- What is the `~/.bashrc` file.

### Variables
- The difference between a local and a global variable.
- What a reserved variable is.
- How to create, update, and delete shell variables.
- The roles of the following reserved variables: `HOME`, `PATH`, `PS1`.
- What special parameters are.
- What the special parameter `$?` is.

### Expansions
- What expansion is and how to use them.
- The difference between single and double quotes and how to use them properly.
- How to do command substitution with `$()` and backticks.

### Shell Arithmetic
- How to perform arithmetic operations with the shell.

### The alias Command
- How to create an alias.
- How to list aliases.
- How to temporarily disable an alias.

## Tasks

This project consists of several tasks, each with its own script to be completed. Here is a brief overview of the tasks:

1. **0-alias**: Create a script that creates an alias with the name `ls` and the value `rm *`.

2. **1-hello_you**: Create a script that prints "hello user," where user is the current Linux user.

3. **2-path**: Add `/action` to the `PATH` variable as the last directory the shell looks into when looking for a program.

4. **3-paths**: Create a script that counts the number of directories in the `PATH`.

5. **4-global_variables**: Create a script that lists environment variables.

6. **5-local_variables**: Create a script that lists all local variables, environment variables, and functions.

7. **6-create_local_variable**: Create a script that creates a new local variable named `BEST` with the value `School`.

8. **7-create_global_variable**: Create a script that creates a new global variable named `BEST` with the value `School`.

9. **8-true_knowledge**: Write a script that prints the result of adding 128 to the value stored in the environment variable `TRUEKNOWLEDGE`.

10. **9-divide_and_rule**: Write a script that prints the result of dividing the value of the environment variable `POWER` by `DIVIDE`.

11. **10-love_exponent_breath**: Write a script that displays the result of raising the value of `BREATH` to the power of `LOVE`.

12. **11-binary_to_decimal**: Write a script that converts a binary number stored in the environment variable `BINARY` to its decimal equivalent.

13. **12-combinations**: Create a script that prints all possible combinations of two lowercase letters, excluding "oo".

14. **13-print_float**: Write a script that prints a number with two decimal places, given the value in the `NUM` environment variable.

15. **100-decimal_to_hexadecimal**: Write a script that converts a decimal number stored in the environment variable `DECIMAL` to its hexadecimal equivalent.

16. **101-rot13**: Write a script that encodes and decodes text using the rot13 encryption.

17. **102-odd**: Write a script that prints every other line from the input, starting with the first line.

18. **103-water_and_stir**: Write a script that adds two numbers stored in the environment variables `WATER` and `STIR` and prints the result.

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`.
- All scripts will be tested on Ubuntu 20.04 LTS.
- All scripts should be exactly two lines long (`$ wc -l file` should print 2).
- All script files must end with a new line.
- The first line of all script files should be `#!/bin/bash`.
- You are not allowed to use `&&`, `||`, or `;` in your scripts.
- You are not allowed to use `bc`, `sed`, or `awk`.
- All script files must be executable.

## Usage

1. Clone this repository:
   ```
   git clone https://github.com/julienbarbier42/alx-system_engineering-devops.git
   ```

2. Navigate to the project directory:
   ```
   cd alx-system_engineering-devops/0x03-shell_variables_expansions
   ```

3. Execute any of the scripts mentioned in the tasks using the following command:
   ```
   ./script-name
   ```

## Quiz Questions

You can find quiz questions related to the project in the quiz section of the DevOps curriculum.

## Author

- **Author:** Julien Barbier

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
