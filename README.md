This repository contains simple shell program.


The shell works by using commands given by the user input. The shell commands take in the following syntax: command name {arguments}. The shell executes a command after it is written by user using the command followed by the arguments.

Compilation
1. gcc -Wall -Werror -Wextra -pedantic *.c -o <shell name here>
2. ./shell 

Built-in commands
cd - changes directory
alias - create an alias
exit - exits shell
env - list all environmental variables
setenv - sets an environmental variable
unsetenv - unsests an environmental variable


