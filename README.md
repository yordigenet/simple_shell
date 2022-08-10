# Simple Shell
----

This is a simple implementation of  command-line interpreter for the Unix operating system created by ALX SE program students **Yordanos Girma** and **Sharleen Awinja**.

See [Unix Shell](https://en.wikipedia.org/wiki/Unix_shell)


## Features
* Display a prompt and wait for the user to type a command. A command line always ends with a new line.
* If an executable cannot be found, print an error message and display the prompt again.
* Handle errors.
* Hndling the “end of file” condition (Ctrl+D)
* Hanling the command line with arguments
* Handle the PATH
* Support the exit features and the exit status
* Handle the Ctrl-C to not terminate the shell
* Handling the command seperator `;`
* Handling `&&` and `||` logical operators
* Handle variable replacements `$?` and `$$`
* Handle the comments `#`
* Support the history feature
* Support the file input

## Files incluided in this repository
File |  Description
------------ | -------------
README.md | README file
cmd_utils.c |  Functions of previous projects
error_handler.c | Management errors
exec.c | File that execute the functions of the OS system
exec_buil_comm.c | File that execute the builtins functions
exit.c | Function of exit
find_path.c | Find the path 
fork.c | Create a new proccess
history.c | Create a history and add nodes
man_1_simple_shell | manpage
parser.c | Split the input
prompt.c | Receives the string of characters
shell.c | Content the main function
shell.h | Header file
stat.c | Verify the status of a command in the system
utils.c | Strings functions

----

## Builtins
* The exit builtin `exit [STATUS]`
* The change directory `cd [DIRECTORY] | [OPTION]`
* Display the environnment variables `env`
* Initialize a new environnment variables or created if not match `setenv [VARIABLE] [VALUE]`
* Remove an environnment variable `unsetenv [VARIABLE]`
* Support the aliases `alias [name [='value'] ...]`
* Display help `help [BUILTIN]`
* Display history `history`



## Authors

* [Yordanos Girma](https://github.com/yordigenet/simple_shell)
* [Sharleen Awinja](https://github.com/kyeeh/SharleenAwinja)
