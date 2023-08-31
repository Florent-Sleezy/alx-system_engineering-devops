# About Me - Shell Permissions Tasks

This repository contains a set of shell scripts, each designed to perform specific tasks related to user permissions in a Linux shell environment. Below is a brief description of each task:

## Task 0: My name is Betty
This script switches the current user to the user named "betty" using the `su` command.

## Task 1: Who am I
This script prints the effective username of the current user using the `whoami` command.

## Task 2: Groups
This script prints all the groups the current user is part of using the `groups` command.

## Task 3: New owner
This script changes the owner of the file named "hello" to the user "betty" using the `chown` command.

## Task 4: Empty!
This script creates an empty file called "hello" using the `touch` command.

## Task 5: Execute
This script adds execute permission to the owner of the file "hello" using the `chmod` command.

## Task 6: Multiple permissions
This script adds execute permission to the owner and the group owner, and read permission to other users, to the file "hello" using the `chmod` command.

## Task 7: Everybody!
This script adds execution permission to the owner, the group owner, and other users, to the file "hello" using the `chmod` command.

## Task 8: James Bond
This script sets specific permissions to the file "hello" using the `chmod` command. It restricts permissions for the owner and the group owner while allowing all permissions for other users.

## Task 9: John Doe
This script sets specific permissions to the file "hello" using the `chmod` command. It grants read, write, and execute permissions to the owner, read and execute permissions to the group owner, and execute permission to other users.

## Task 10: Look in the mirror
This script sets the permissions of the file "hello" to match the permissions of the file "olleh" using the `chmod` command with the `--reference` option.

## Task 11: Directories
This script adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users using the `find` command and `chmod` command.

## Task 12: More directories
This script creates a directory called "my_dir" with permissions 751 in the working directory using the `mkdir` command with the `-m` option.

## Task 13: Change group
This script changes the group owner of the file "hello" to "school" using the `chgrp` command.

Each script is designed to fulfill a specific permission-related task, providing examples of how permissions can be managed in a Linux shell environment. Feel free to explore and use these scripts as needed.
