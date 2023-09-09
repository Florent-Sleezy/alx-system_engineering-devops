# 0x02-shell_redirections

This project consists of a collection of shell scripts that demonstrate various aspects of shell redirections and text processing. Each script corresponds to a specific task and showcases different techniques in shell scripting.

## Task 0: Hello World

**Script**: [0-hello_world](./0-hello_world)

This script simply prints "Hello, World" to the standard output when executed.

## Task 1: Confused smiley

**Script**: [1-confused_smiley](./1-confused_smiley)

When run, this script displays a confused smiley face to the standard output.

## Task 2: Let's display a file

**Script**: [2-hellofile](./2-hellofile)

This script takes a file path as an argument and displays the contents of that file.

## Task 3: What about 2?

**Script**: [3-twofiles](./3-twofiles)

The script takes two file paths as arguments and concatenates the contents of these two files, displaying the result.

## Task 4: Last lines of a file

**Script**: [4-lastlines](./4-lastlines)

Given a file as input, this script displays the last ten lines of the file.

## Task 5: I'd prefer the first ones actually

**Script**: [5-firstlines](./5-firstlines)

Similar to the previous task, this script takes a file as input but displays the first ten lines of the file.

## Task 6: Line #2

**Script**: [6-third_line](./6-third_line)

This script prints the third line of a file. It takes the file path as an argument.

## Task 7: It is a good file that cuts iron without making a noise

**Script**: [7-file](./7-file)

The script checks if a file exists. If it does, it outputs "file exists." Otherwise, it remains silent.

## Task 8: Save current state of directory

**Script**: [8-cwd_state](./8-cwd_state)

This script saves the current working directory path to a file named `ls_cwd_content` and then lists the contents of the current directory.

## Task 9: Duplicate last line

**Script**: [9-duplicate_last_line](./9-duplicate_last_line)

This script duplicates the last line of a file and saves it to a new file.

## Task 10: No more javascript

**Script**: [10-no_more_js](./10-no_more_js)

The script deletes all the files in the current directory that have a `.js` (JavaScript) extension.

## Task 11: Don't just count your directories, make your directories count

**Script**: [11-directories](./11-directories)

This script counts the number of subdirectories in the current directory.

## Task 12: What’s new

**Script**: [12-newest_files](./12-newest_files)

The script displays the ten newest files in the current directory, sorted by modification time, with the most recent file first.

## Task 13: Being unique is better than being perfect

**Script**: [13-unique](./13-unique)

This script takes a list of words as input and prints only words that appear exactly once. The output is sorted.

## Task 14: It must be in that file

**Script**: [14-findthatword](./14-findthatword)

This script displays lines containing the pattern "root" from the file `/etc/passwd`.

## Task 15: Count that word

**Script**: [15-countthatword](./15-countthatword)

The script displays the number of lines that contain the pattern "bin" in the file `/etc/passwd`.

## Task 16: What's next?

**Script**: [16-whatsnext](./16-whatsnext)

This script displays lines containing the pattern "root" and the three lines after them in the file `/etc/passwd`.

## Task 17: I hate bins

**Script**: [17-hidethisword](./17-hidethisword)

The script displays all the lines in the file `/etc/passwd` that do not contain the pattern "bin".

## Task 18: Letters only please

**Script**: [18-letteronly](./18-letteronly)

This script displays all lines of the file `/etc/ssh/sshd_config` that start with a letter, including capital letters.

## Task 19: A to Z

**Script**: [19-AZ](./19-AZ)

The script replaces all occurrences of characters 'A' and 'c' with 'Z' and 'e', respectively, in the input.

## Task 20: Without C, you would live in hiago

**Script**: [20-hiago](./20-hiago)

This script removes all instances of the letters 'c' and 'C' from the input.

## Task 21: esreveR

**Script**: [21-reverse](./21-reverse)

The script reverses its input string.

## Task 22: DJ Cut Killer

**Script**: [22-users_and_homes](./22-users_and_homes)

This script displays all users and their home directories, sorted by users, based on the `/etc/passwd` file.

## Task 23: Empty casks make the most noise

**Script**: [100-empty_casks](./100-empty_casks)

The script lists all empty files and directories in the current directory and its subdirectories. Only the names of the files and directories are displayed, one per line.

## Task 24: A gif is worth ten thousand words

**Script**: [101-gifs](./101-gifs)

This script lists all files with a `.gif` extension in the current directory and its subdirectories. It displays the file names without extensions, sorted by byte values in a case-insensitive manner.

## Task 25: Acrostic

**Script**: [102-acrostic](./102-acrostic)

This script decodes acrostics that use the first letter of each line in the input text.

## Task 26: The biggest fan

**Script**: [103-the_biggest_fan](./103-the_biggest_f

an)

Parses web server logs in TSV (Tab-Separated Values) format and displays the top 11 hosts or IP addresses that made the most requests.

## Usage

You can execute each script by running the command `./script-name` in your terminal.

For example:
```bash
./0-hello_world
./1-confused_smiley
# ... and so on for other scripts
```

Feel free to explore and utilize these scripts for various text processing and shell redirection tasks. If you encounter any issues or have questions, please don't hesitate to reach out.

Happy scripting!
