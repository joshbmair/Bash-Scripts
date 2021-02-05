# Shell Scripts
Let's say I wanted to compile a program written in C, I can just type this in my command line:
```
ccomp program.c prgrm
```
My shell automatically executes the following command:
```
gcc -Wall -Wfatal-errors program.c -o prgrm
```
This makes it much easier to quickly compile C code with multiple flags to test out some code without a Makefile, for example. This is just one of several scripts that I have written and use while programming. Take a look around to see what other scripts I wrote to make myself more efficient.

# How to use
1. Make a folder in your directory named "~/.scripts".
2. Copy/pull this repository into your new folder.
3. Copy the aliases from aliases.txt into your "~/.bashrc" file.
4. You're done! Now you can run the scripts using the aliases you just added.
