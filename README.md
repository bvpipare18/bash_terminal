# bash_terminal
Learn all UNIX based bash commands

- The command line is a text interface for the computer’s operating system. To access the command line, we use the terminal.

- A filesystem organizes a computer’s files and directories into a tree structure. It starts with the root directory. Each parent directory can contain more child directories and files.

## From the command line, you can navigate through files and folders on your computer:

 1. **pwd** outputs the name of the current working directory.
 
2. **ls** lists all files and directories in the working directory.

3. **cd** switches you into the directory you specify.

4. **mkdir** creates a new directory in the working directory.

5. **touch** creates a new file inside the working directory.


## Options modify the behavior of commands:

1. **ls -a** lists all contents of a directory, including hidden files and directories

2. **ls -l** lists all contents in long format

3. **ls -t** orders files and directories by the time they were last modified

4. Multiple options can be used together, like **ls -alt**

## From the command line, you can also copy, move, and remove files and directories:

1. **cp** copies files

2. **mv** moves and renames files

3. **rm** removes files

4. **rm -r** removes directories

- Wildcards are useful for selecting groups of files and directories

## Redirection reroutes standard input, standard output, and standard error.

- The common redirection commands are:

1. **>** redirects standard output of a command to a file, overwriting previous content.

2. **>>** redirects standard output of a command to a file, appending new content to old content.

3. **<** redirects standard input to a command.

4. **|** redirects standard output of a command to another command.

## A number of other commands are powerful when combined with redirection commands:

1. **sort**: sorts lines of text alphabetically.

2. **uniq**: filters duplicate, adjacent lines of text.

3. **grep**: searches for a text pattern and outputs it.

4. **sed** : searches for a text pattern, modifies it, and outputs it.
