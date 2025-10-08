
This project contains a script that defines a custom shell alias for the ls command. The alias redefines ls to perform a dangerous operation: it deletes all files in the current directory.

    ⚠️ Warning: This script is intentionally destructive. It should be used only in a controlled or educational environment. Never run this alias on a production system or on directories with important files.

Task Details

    Script Name: 0-alias

    Alias Created:

        Name: ls

        Value: rm *

Example Usage

$ ls
0-alias  file1  file2
$ source ./0-alias
$ ls
$ \ls
$

Explanation:

    Before sourcing the alias, running ls lists the files.

    After sourcing 0-alias, the ls command is now an alias for rm *, which deletes all files in the current directory.

    Running \ls bypasses the alias and runs the actual ls binary, showing that the directory is now empty.

Repository Information

    GitHub Repository: alx-system_engineering-devops

    Directory: 0x03-shell_variables_expansions

    File: 0-alias


# 0x03. Shell, init files, variables and expansions

## Description
This project is part of the **ALX System Engineering & DevOps** curriculum.  
It focuses on learning and practicing shell initialization files, variables, expansions, and how to use them in scripts.

You will learn:
- What happens when you start a new shell
- How to create, use, and remove variables
- The difference between local and global variables
- What is a reserved variable
- How to use command substitution
- How to perform arithmetic and string expansions

---

## Project Structure

| File Name | Description |
|------------|-------------|
| `0-alias` | Creates an alias |
| `1-hello_you` | Prints “hello user”, where user is the current Linux user |
| `2-path` | Adds `/action` to the PATH |
| `3-paths` | Counts the number of directories in the PATH |
| `4-global_variables` | Lists environment variables |
| `5-local_variables` | Lists all local and environment variables, and functions |
| `6-create_local_variable` | Creates a new local variable |
| `7-create_global_variable` | Creates a new global variable |
| `8-true_knowledge` | Prints the r_
