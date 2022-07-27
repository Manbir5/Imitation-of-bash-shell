# Imitation-of-bash-shell

This program imitates a shell. It will implement some functions similar to bash. 

Enter the following command using the command line:
gcc -std=gnu99 -Wall smallsh.c -o smallsh
2) Enter the following command at the required directory:
./smallsh 

The commands can then be entered as needed.

The functionality for this program:

Provide a prompt for running commands
Handle blank lines and comments, which are lines beginning with the # character
Provide expansion for the variable $$
Execute 3 commands exit, cd, and status via code built into the shell
Execute other commands by creating new processes using a function from the exec family of functions
Support input and output redirection
Support running commands in foreground and background processes
Implement custom handlers for 2 signals, SIGINT and SIGTSTP
