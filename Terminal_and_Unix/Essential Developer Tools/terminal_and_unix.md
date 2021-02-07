# { Navigating in Terminal. }
   What is Terminal?
Terminal is an application that gives us a command line interface (or CLI) to interact with the computer. Everything you can do in Finder you can do in Terminal. Developers use Terminal because, more often than not, it is much faster to use Terminal than a graphical user interface (GUI) such as Finder.
   
   
   What is a shell? Bash/ZSH:-
The shell is the program which actually processes commands and returns output. Most shells also manage foreground and background processes, command history and command line editing. These features (and many more) are standard in bash, the most common shell in modern linux systems. (We are using zsh).


   Absolute Paths vs Relative Paths
A path is simply the way to reach a file or folder; it's like an address for the file or folder you're trying to reach. When we specify a path starting from the root directory /, we call that an absolute path. For example, if I am currently in the ~ home directory and I would like to change directories into my Desktop folder, I can do that in two of the following ways:

cd Desktop - relative to where I am currently
cd /Users/eschoppik/Desktop - absolute, starting from the root (first /, then Users, then eschoppik, then Desktop)
