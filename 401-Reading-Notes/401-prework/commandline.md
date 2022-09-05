# The Command Line
A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands.

Shell is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell. This tutorial will assume you are using bash as your shell.

If you would like to know which shell you are using you may use a command called echo to display a system variable stating your current shell. echo is a command which is used to display messages.

# Basic Navigation
- pwd: stands for Print Working Directorty


`pwd`

Whereas pwd is just run by itself with no arguments, ls is a little more powerful. We have run it here with no arguments in which case it will just do a plain listing of our current location. We can do more with ls however. Below is an outline of its usage:

`ls [options] [location]`


# More About Files

Ok, the first thing we need to appreciate with linux is that under the hood, everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc. To begin with, this won't affect what we do too much but keep it in mind as it helps with understanding the behaviour of Linux as we manage files and directories.

`file [path]`

# Manual Pages 

- man < someCommand > : Look up the manual page for a particular command.
`man <someCommand>`
- man -k < someSearchTerm > : Do a keyword search for all manual pages containing the given search term.
`man -k <someSearchTerm>`
- /< term > : Within a manual page, perform a search for 'term'
`/<term>`
- n : After performing a search within a manual page, select the next found item.
`n`

# File Manipulation
- mkdir: Make Directory - ie. Create a directory.
`mkdir [options] <Directory>`
- rmdir: Remove Directory - ie. Delete a directory.
`rmdir [options] <Directory>`
- touch: Create a blank file.
`touch [options] <filename>`
- cp: Copy - ie. Copy a file or directory.
`cp [options] <source> <destination>`
- mv: Move - ie. Move a file or directory (can also be used to rename).
`mv [options] <source> <destination>`

`mv [options] <oldName> <newName>`
- rm: Remove - ie. Delete a file.
`rm [options] <file>`