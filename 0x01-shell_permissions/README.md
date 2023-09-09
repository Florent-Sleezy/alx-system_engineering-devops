# 0x01-shell_permissions

This repository contains a set of shell scripts that demonstrate various aspects of shell permissions and user management in a Unix-like environment, specifically on Ubuntu 20.04 LTS. These scripts are part of the DevOps curriculum.

## Table of Contents

1. [My name is Betty](#my-name-is-betty)
2. [Who am I](#who-am-i)
3. [Groups](#groups)
4. [New owner](#new-owner)
5. [Empty](#empty)
6. [Execute](#execute)
7. [Multiple permissions](#multiple-permissions)
8. [Everybody](#everybody)
9. [James Bond](#james-bond)
10. [John Doe](#john-doe)
11. [Look in the mirror](#look-in-the-mirror)
12. [Directories](#directories)
13. [More directories](#more-directories)
14. [Change group](#change-group)
15. [Owner and group](#owner-and-group) - (Advanced)
16. [Symbolic links](#symbolic-links) - (Advanced)
17. [If only](#if-only) - (Advanced)
18. [Star Wars](#star-wars) - (Advanced)

## Usage

Each script is designed to perform specific tasks related to shell permissions and user management. To use these scripts, follow the instructions provided in each script's description.

## Requirements

- Allowed editors: vi, vim, emacs
- Scripts are tested on Ubuntu 20.04 LTS
- Scripts should be exactly two lines long (`$ wc -l file` should print 2)
- All files should end with a new line
- The first line of all files should be exactly `#!/bin/bash`
- A README.md file, at the root of the folder, describes what each script does
- You are not allowed to use backticks, `&&`, `||`, or `;`
- All files must be executable

## Tasks

### My name is Betty
- [Script](0-iam_betty)
- Description: Create a script that switches the current user to the user `betty`.

### Who am I
- [Script](1-who_am_i)
- Description: Write a script that prints the effective username of the current user.

### Groups
- [Script](2-groups)
- Description: Write a script that prints all the groups the current user is part of.

### New owner
- [Script](3-new_owner)
- Description: Write a script that changes the owner of the file `hello` to the user `betty`.

### Empty
- [Script](4-empty)
- Description: Write a script that creates an empty file called `hello`.

### Execute
- [Script](5-execute)
- Description: Write a script that adds execute permission to the owner of the file `hello`.

### Multiple permissions
- [Script](6-multiple_permissions)
- Description: Write a script that adds execute permission to the owner and the group owner and read permission to other users for the file `hello`.

### Everybody
- [Script](7-everybody)
- Description: Write a script that adds execution permission to the owner, the group owner, and other users for the file `hello`.

### James Bond
- [Script](8-James_Bond)
- Description: Write a script that sets the permission for the file `hello` as follows: Owner: no permission at all, Group: no permission at all, Other users: all permissions.

### John Doe
- [Script](9-John_Doe)
- Description: Write a script that sets the mode of the file `hello` to `-rwxr-x-wx`.

### Look in the mirror
- [Script](10-mirror_permissions)
- Description: Write a script that sets the mode of the file `hello` the same as the mode of `olleh`.

### Directories
- [Script](11-directories_permissions)
- Description: Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users. Regular files should not be changed.

### More directories
- [Script](12-directory_permissions)
- Description: Create a script that creates a directory called `my_dir` with permissions `751` in the working directory.

### Change group
- [Script](13-change_group)
- Description: Write a script that changes the group owner of the file `hello` to `school`.

### Owner and group (Advanced)
- [Script](100-change_owner_and_group)
- Description: Write a script that changes the owner to `vincent` and the group owner to `staff` for all files and directories in the working directory.

### Symbolic links (Advanced)
- [Script](101-symbolic_link_permissions)
- Description: Write a script that changes the owner and the group owner of `_hello` to `vincent` and `staff`, respectively. `_hello` is a symbolic link.

### If only (Advanced)
- [Script](102-if_only)
- Description: Write a script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.

### Star Wars (Advanced)
- [Script](103-Star_Wars)
- Description: Write a script that plays Star Wars Episode IV in the terminal.

## Copyright and Plagiarism

- You are tasked with coming up with solutions for the tasks yourself to meet the learning objectives.
- Plagiarism is strictly forbidden and will result in removal from the program.

Feel free to explore these scripts to learn more about shell permissions and user management in Unix-like systems. If you have any questions or need further assistance, please reach out.
