STARTING WITH BASH/SHELL SCRIPTING LANGUAGE
===========================================

:Author: Avishek Kumar
:Date: September 19, 2016
:Site: URL: http://www.jointux.com/starting-with-bash-scripting-language/

A Unix/Linux shell is a command-line interpreter. Users commonly interacts with shell, using terminal emulator by entering command as text or from a file that can be interpreted by shell. The shell can be an interactive command-line as well as scripting programming language.

Features of Linux/Unix Shell
-----------------------------

#. Wildcarding
#. Piping
#. Command substituion
#. Variables
#. Control Structure
#. Condition Testing
#. Iteration

Some well known Linux shell
---------------------------

#. Bourne Shell – The most basic shell that is available on all UNIX System.
#. Korn Shell – Based on Bourne Shell with advanced features.
#. C Shell – Syntaxally close to C programming Language, the name says it all.
#. Bash Shell – The default shell on most Linux Distribution. It has the avantages of Korn and C shell.
#. tcsh – Very similar to C shell.

A short note on Bash Shell
--------------------------

Bash Shell was written by Brian Fox, the first employee of Free Software Foundation. Fox started coding bash on January 10, 1988 and the initial release was made 18 months after, on June 08, 1989. It was written in C programming language and released under GNU GPL v3+ License. The latest stable release is Version 4.4.

Features of Bash Shell
----------------------

Bash command syntax is a superset of Bournie Shell command Syntax. Most of the script of Bournie shell can be run on Bash as it is without modification.

#. Command-line editing
#. Command history
#. Directory Stack
#. POSIX Command substitution syntax
#. $RANDOM and $PPID Variables
#. Tab auto-completion
#. Arithmetic evaluation
#. I/O redirection
#. Process substituion
#. Named pipes
#. Bash 4.0 has built-in fake support for multi-dimensional arrays, like awk.
#. Portability
#. Process Management
#. Conditional execution

Bash shebang
------------

You must have noticed something like below on the first-line of shell script.::

  #!/bin/bash
  
The bash script must start with a Bash shebang. It tells the shell what environment to use.

For portability it is recommended to use it as::

  #!/usr/bin/env bash
  
Comments in Bash
----------------

Bash has support for single-line comment as well as multi-line comment. Bash interprets anything after ‘#’ as comment.

Single-line comment example::

  # This is a comment line.

Multi-line comment example::

  : '
  This is comment-line-1
  This is comment-line-2
  '
  
Hello World Program in Shell
----------------------------

::

  #!/usr/bin/env bash
  # This will print Hello, World!
  echo Hello, World!
  
You can save it to anything. However, following the convention we will save it as hello-world.sh. Next it is important to give the script executable permission. It can be done by running the below command in terminal::

  chmod 755 hello-world.sh

All you need to do, to execute the script is::

  ./hello-world.sh
  Hello, World!
  
Ainda não usa Linux? Experimente desenvolver e executar scripts em https://www.tutorialspoint.com/execute_bash_online.php


