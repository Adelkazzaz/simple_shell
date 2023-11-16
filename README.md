# Simple Shell (Version 0x16 - C Implementation)

<p align="center">
   📄 🚀
</p>

<p align="center">
  <strong>Description</strong>
</p>

<p align="center">
  Welcome to Simple Shell 2023! This project is a milestone achievement in C code at ALX Africa Software Engineering, designed to delve into advanced concepts in shell programming. Developed in the first trimester, the Simple Shell explores intricate elements like processes, system calls, bit manipulation, file management, and error handling. This UNIX command interpreter, written entirely in C, mirrors the functionalities of the classic shell (sh).
</p>

## Contributor :
[**Adel Kazzaz**](https://github.com/Adelkazzaz)</br>
All rights reserved 

## Overview
This shell, built in [C](https://en.wikipedia.org/wiki/C_(programming_language)), draws inspiration from [the Thompson Shell](https://en.wikipedia.org/wiki/Thompson_shell).

## Environment
Tested and optimized for Ubuntu 20.04 LTS.

## Features
- User-friendly prompt awaiting commands, each concluding with a new line.
- Graceful handling of executable not found scenarios, with detailed error messages.
- Robust error handling, including addressing the "end of file" condition (Ctrl+D).
- Command line support for arguments, PATH management, exit features, status tracking, non-termination with Ctrl-C, command separator `;`, logical operators `&&` and `||`, variable replacements `$?` and `$$`, comments `#`, history feature, and file input.

## Builtins
Empowers users with built-in commands:

| Command             | Definition                                                                                |
| ------------------- | ----------------------------------------------------------------------------------------- |
| exit [n]            | Safely exit the shell, with an optional exit status, n.                                   |
| env                 | Display the environment.                                                                  |
| setenv [var][value] | Set an environment variable and its value. Updates if the variable already exists.        |
| alias[name[='value]]| Define and read aliases.                                                                  |
| unsetenv [var]      | Remove an environment variable.                                                           |
| cd [dir]            | Swiftly change the directory.                                                             |
| help [built-in]     | Access documentation for a built-in command.                                              |
