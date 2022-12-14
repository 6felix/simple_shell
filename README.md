<h1 align="center">
  0x16. C - Simple Shell Project
</h1>

</p>
  <strong>
   Description
  </strong>
</p>
This project is an implementation of the shell created as a Milestone Project for the C language at ALX Software Engineering Course. </br>
The gates of shell is a project in the first sprint, that helps students to understand the advanced concepts behind the shell program. It includes; processes, system call, bit manipulation, file managment, error handling ... </br>
Shell is a simple UNIX command interpreter that replicates functionalities of the simple shell (sh). </br>
This program was written entirely in C Language.
</p>

## COPYRIGHT
Copyright (C) 2022 by [**Felix Okoronkwo**](https://github.com/6felix) and [**Akachukwu Amasiatu**](https://github.com/Akachukwu96) </br>
All rights reserved

 ## Description :
This is a shell written in [C](https://en.wikipedia.org/wiki/C_(programming_language)).
It is based on [the Thompson Shell](https://en.wikipedia.org/wiki/Thompson_shell).

## Environment :

Our shell was built and tested on  Ubuntu 20.04 LTS..

## Features
* Display a prompt and wait for the user to type a command. A command line always ends with a new line.
* If an executable cannot be found, print an error message and display the prompt again.
* Handle errors.
* Handling the “end of file” condition (Ctrl+D)
* Handling the command line with arguments
* Handle the PATH
* Support the exit features and the exit status
* Handle the Ctrl-C to not terminate the shell
* Handling the command seperator `;`
* Handling `&&` and `||` logical operators
* Handle variable replacements `$?` and `$$`
* Handle the comments `#`
* Support the history feature
* Support the file input

## Builtins
Our shell has support for the following built-in commands:

| Command             | Definition                                                                                |
| ------------------- | ----------------------------------------------------------------------------------------- |
| exit [n]            | Exit the shell, with an optional exit status, n.                                          |
| env                 | Print the environment.                                                                    |
| setenv [var][value] | Set an environment variable and value. If the variable exists, the value will be updated. |
| alias[name[='value]]| Reads aliases name                                                                        |
| unsetenv [var]      | Remove an environment variable.                                                           |
| cd [dir]            | Change the directory.                                                                     |
| help [built-in]     | Read documentation for a built-in.                                                        |


 ## Installation : Getting HSH
 
Clone the below repository and compile the files into an executable using the GCC compiler.
```
https://github.com/martinsndifon/simple_shell.git
```

### Basic usage :bulb:
- Clone [the repository ](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).
- Create an executable by running the following command:
- `gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`
- Then type in the following command and press your enter button.
- `./hsh`
- If everything was done correctly, your simple shell should be up and running.


## Example :computer:
```
ls -la
```
![114757753-e50c2180-9d64-11eb-95ea-fb9bba776c8c](https://user-images.githubusercontent.com/57016982/186711943-65abad4d-eedf-4d65-947d-3710e189bdee.png)

## Contributors :
* [**Felix Okoronkwo**](https://github.com/6felix)
* [**Akachukwu Amasiatu**](https://github.com/Akachukwu96)

## Acknowledgments :
- The creators of the C language
- Betty Holberton | Alx-Africa
