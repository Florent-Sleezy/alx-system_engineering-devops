# 0x00-shell_basics

## Overview
This repository contains a series of shell scripts and tasks designed to help you learn the basics of using the shell, specifically focusing on Bash. These scripts cover various aspects of shell navigation, file manipulation, and command execution.

## Table of Contents
1. [General Information](#general-information)
2. [Project Tasks](#project-tasks)
3. [Usage](#usage)
4. [Quiz](#quiz)
5. [Contributing](#contributing)
6. [License](#license)

## General Information
In this project, you will learn the fundamentals of working with a Unix-like shell environment. The tasks cover topics such as navigating the file system, using essential commands, and understanding various concepts related to the shell.

### Learning Objectives
By completing the tasks in this project, you will be able to:

- Understand the basics of using the shell.
- Navigate the file system efficiently.
- Manipulate files and directories.
- Execute commands and understand their options.
- Read and interpret manual pages (man pages).
- Learn keyboard shortcuts for Bash.
- Gain familiarity with some advanced shell operations.

## Project Tasks
Here is a list of tasks included in this project:

1. **Where am I?**
   - Description: Print the absolute path name of the current working directory.
   - Script: [0-current_working_directory](./0-current_working_directory)

2. **What’s in there?**
   - Description: Display the contents list of your current directory.
   - Script: [1-listit](./1-listit)

3. **There is no place like home**
   - Description: Change the working directory to the user's home directory.
   - Script: [2-bring_me_home](./2-bring_me_home)

4. **The long format**
   - Description: Display the current directory's contents in long format.
   - Script: [3-listfiles](./3-listfiles)

5. **Hidden files**
   - Description: Display the current directory's contents, including hidden files, in long format.
   - Script: [4-listmorefiles](./4-listmorefiles)

6. **I love numbers**
   - Description: Display the current directory's contents in long format with user and group IDs displayed numerically, including hidden files.
   - Script: [5-listfilesdigitonly](./5-listfilesdigitonly)

7. **Welcome**
   - Description: Create a directory named "my_first_directory" in the /tmp/ directory.
   - Script: [6-firstdirectory](./6-firstdirectory)

8. **Betty in my first directory**
   - Description: Move the file "betty" from /tmp/ to /tmp/my_first_directory.
   - Script: [7-movethatfile](./7-movethatfile)

9. **Bye bye Betty**
   - Description: Delete the file "betty" from /tmp/my_first_directory.
   - Script: [8-firstdelete](./8-firstdelete)

10. **Bye bye My first directory**
    - Description: Delete the directory "my_first_directory" from the /tmp directory.
    - Script: [9-firstdirdeletion](./9-firstdirdeletion)

11. **Back to the future**
    - Description: Change the working directory to the previous one.
    - Script: [10-back](./10-back)

12. **Lists**
    - Description: List files from the current directory, parent directory, and /boot directory in long format.
    - Script: [11-lists](./11-lists)

13. **File type**
    - Description: Print the type of the file named "iamafile" in the /tmp directory.
    - Script: [12-file_type](./12-file_type)

14. **We are symbols, and inhabit symbols**
    - Description: Create a symbolic link to /bin/ls named "__ls__" in the current working directory.
    - Script: [13-symbolic_link](./13-symbolic_link)

15. **Copy HTML files**
    - Description: Copy HTML files from the current directory to the parent directory if they don't exist or are newer.
    - Script: [14-copy_html](./14-copy_html)

16. **Let’s move**
    - Description: Move files beginning with an uppercase letter to the directory /tmp/u.
    - Script: [100-lets_move](./100-lets_move)

17. **Clean Emacs**
    - Description: Delete files in the current working directory that end with the character "~".
    - Script: [101-clean_emacs](./101-clean_emacs)

18. **Tree**
    - Description: Create directories "welcome/", "welcome/to/", and "welcome/to/school" in the current directory.
    - Script: [102-tree](./102-tree)

19. **Life is a series of commas, not periods**
    - Description: List files and directories in the current directory, separated by commas.
    - Script: [103-commas](./103-commas)

20. **File type: School**
    - Description: Create a magic file "school.mgc" to detect School data files.
    - Script: [school.mgc](./school.mgc)

## Usage
To use these scripts, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the desired script's location in your terminal.
3. Make the script executable using the `chmod` command. For example:
   ```bash
   chmod +x script_name.sh
