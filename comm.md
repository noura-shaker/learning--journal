# *The Command Line:*

The command line is a text interface for your computer. It’s a program that takes in commands, which it passes on to the computer’s operating system to run.

From the command line, you can navigate through files and folders on your computer, just as you would with Windows Explorer on Windows or Finder on Mac OS. The difference is that the command line is fully text-based.

Here’s an appendix of commonly used commands.

## shell:

Within a terminal you have what is known as a shell. 
This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you.
There are various shells available but the most common one is called bash which stands for Bourne again shell. 
This tutorial will assume you are using bash as your shell.

use a command called echo to display a system variable stating your current shell. 
echo is a command which is used to display messages.

# Basic Navigation

1.*pwd* which stands for Print Working Directory. 

2.*ls* The command for this task is 

#*Absolute and Relative Paths*

There are 2 types of paths we can use, absolute and relative. Whenever we refer to a file or directory we are using one of these paths. Whenever we refer to a file or directory, we can, in fact, use either type of path (either way, the system will still be directed to the same

To begin with, we have to understand that the file system under linux is a hierarchical structure. At the very top of the structure is what's called the root directory. It is denoted by a single slash ( / ). It has subdirectories, they have subdirectories and so on. Files may reside in any of these directories.

Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )

Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.
