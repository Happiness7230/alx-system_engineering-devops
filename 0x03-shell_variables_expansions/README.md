Skip to content
You said:
Write a readme from these 

Create a script that creates an alias.

    Name: ls
    Value: rm *

julien@ubuntu:/tmp/0x03$ ls
0-alias  file1  file2
julien@ubuntu:/tmp/0x03$ source ./0-alias 
julien@ubuntu:/tmp/0x03$ ls
julien@ubuntu:/tmp/0x03$ \ls
julien@ubuntu:/tmp/0x03$ 

Repo:

    GitHub repository: alx-system_engineering-devops
    Directory: 0x03-shell_variables_expansions
    File: 0-alias
ChatGPT said:

Here's a professional and clear README.md file based on the information you provided:
0x03. Shell, init files, variables and expansions
Task: Alias Creation
Description

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


