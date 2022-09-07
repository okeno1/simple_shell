# simple_shell
# contents of our project
* Definition of shell
* About this project
* Functionalities of a simple shell
* File description
* The list of allowed functions and system calls for this project
* Bugs
* The team behind this awesome project

# Definition of shell
Shell : is a program that promps the user for a command, reads the command, parses the command and then it executes the command

# About this project
This project is a simple version of the real linux shell, it is a project created for students of Holberton School undertaking - Low-level programming & Algorithm - Linux and Unix system programming projects

This project is created using the C PROGAMMING LANGUAGE
# Functionalities of a simple shell

* Displays "#cisfun$" and prompts the user for a command input
* Reads the command the user has typed
* Parses the command typed
* Executes the commandCharlespaul wabomb
# File description
* AUTHORS - The contributors to this repository
* man_simple_shell - The manual description of the simple shell
* shell.h - The header file (contains- perror (man 3 perror)
* shell.c - the main function 
          - contains the sighandler and end of file funcions
 * strings.c - handles handles string manipulation functions
 * line_execution -  function that splits a string and returns an array of each word of the string, reallocates a memory block, and executes a command using execute
                  - uses execute, splitstring, realloc and freearv commands
 * linked_listpath - returns the value of a global varibale, it also adds a node to a singly list then it creates a singly linked list for PATH directories
             - finds the path of a command using (_which) command and frees the linked list using (free_list)
 * checkbuiltin.c - checks if a command is in built in c or shell using the (checkbuild) command
 *builtin.c - handles the exit command, changes a string into integer using (atoi), initializes a new global variable, or modify an existing one using (_setenv)
            - it then removes a global variable using (_unsetenv)
 
 # The list of allowed functions and system calls for this project
 - - access (man 2 access)
 - chdir (man 2 chdir)
 - close (man 2 close)
 - closedir (man 3 closedir)
 - execve (man 2 execve)
 - exit (man 3 exit)
 - _exit (man 2 _exit)
 - fflush (man 3 fflush)
 - fork (man 2 fork)
 - free (man 3 free)
 - getcwd (man 3 getcwd)
 - getline (man 3 getline)
 - isatty (man 3 isatty)
 - kill (man 2 kill)
 - malloc (man 3 malloc)Charlespaul wabomb
 - open (man 2 open)
 - opendir (man 3 opendir)
 - perror (man 3 perror)
 - read (man 2 read)
 - readdir (man 3 readdir)
 - signal (man 2 signal)Charlespaul wabomb
 - stat (__xstat) (man 2 stat)
 - lstat (__lxstat) (man 2 lstat)
 - fstat (__fxstat) (man 2 fstat)
 - strtok (man 3 strtok)
 - wait (man 2 wait)
 - waitpid (man 2 waitpid)
 - wait3 (man 2 wait3)
 - wait4 (man 2 wait4)
 - write (man 2 write)
 # Bugs
 * There are no known bugs for now
 
 # Team
 * Carlymax Patrick Kuria.
 * Charlespaul Masika Wabomba.
 
