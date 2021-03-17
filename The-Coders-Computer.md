# The Coder's Computer

This section is a resource for definitions and information regarding basic terminal usage. 

## Text editor 

A text editor is a piece of software that allows you to write and manage text, especially the text that you write to build a web site. Mac computers are manufactured with "Text Edit," whereas Windows computers come with "Notepad." Linux computers, on the other hand, have various text editors based on the distribution. It is important to remember to create code in a plain text editor. Plain text has no formatting options, so if you see the option to make text bold, italicized or underlines, then there may be a setting that needs to be changed. 

### Text Editor Features

There are many features that experts suggest new users should look for in a text editor. The following features are deemed as "must have's" by The Older Coder in the article [Choosing A Text Editor](https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf)

#### Code Completion

To save time, it is recommended to find a text editor that offers code completion. This feature allows you to start typing, and the code completion feature will display possible suggestions based on what you originally typed. 

#### Syntax Highlighting

Syntax highlighting takes the text you type and colorizes it, making it more noticable.

#### Themes

Themes allow you to change the color of the background of your text editor, the series of colors in your text, and sometimes other aspects of your text editing software. This can make the text editor easier on the eyes. 



## IDE (Integrated Development Environment)

A text editor does simply that — edits text. However, an IDE is a suite of different software coming together as one. An IDE is a text editor, a file manager, a compiler, and a debugger all in one. 



## The Command Line

A command line, also known as a terminal, is a text based interface to the system. You can enter commands by typing them on the keyboard that will promt feedback similarly as text.

### Opening a Mac Terminal 
1. `command + space` then search "terminal"
2. open your launchpad and find the terminal
3. Go to Finder, then applications, and finally to Utilities and you'll see the terminal



## The Shell (Bash)

The shell, the part of the operating system that determines how the terminal will behave, is found within the terminal. The shell also looks after executing commands for you. 



## Commands

`PWD` Print Working Sirectory
 
`ls` is short for list

`ls [options] [location]` lets you know what is in your current location. The square brackets mean that those items are optional and you can run the command with or without them. 

`ls -l` is short for long listing

A long listing has the following:
* First character indicates whether it is a normal file ( - ) or directory ( d )
* Next 9 characters are permissions for the file or directory
* The next field is the number of blocks 
* The next field is the owner of the file or directory 
* The next field is the group the file or directory belongs to 
* Following this is the file size
* Next up is the file modification time
* Finally, we have the actual name of the file or directory

`ls /etc`  tells ls not to list our current directory but rather to list that directories contents.

`-l /etc` promts a long listing of the directory /etc

`cd` stands for change directory, to move around in the system

`cd [location]`



## Paths

A path `file [path]` is a means to get to a particular location in the system and that location is a file. There are two types of paths: absolute and relative. 

### Absolute Paths

command: forward slash `/` 

Absolute paths specify a location (file or directory) in relation to the root directory. 

### Relative Paths

Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.

* `~` (tilde) - This is a shortcut for your home directory
* `.` (dot) - This is a reference to your current directory
* `..` (dotdot)- This is a reference to the parent directory



## Spaces

A space on the command line is how we seperate items. However, this could cause issues. 

Example: `cd Holiday Photos` will render the response "No such file or directory." There are two solutions to this problem. 

### Quotes

You may use either single or double quotes, anything inside is considered a single item. 

Example: `cd 'Holiday Photos'`

### Escape characters

backslash `\` escapes (or nullifies) the special meaning of the next character. 

Example: `cd Holiday\ Photos`



## Hidden files and directories

If the file or directory's name begins with a `.` (full stop) then it is considered to be hidden

use `ls -a` to view the list the contents of a directory, including hidden files.



## Linux Information

### Everything is a file under Linux
Even directories.

### Linux is an extensionless system
Files can have any extension they like or none at all.
Under Linux the system actually ignores the extension and looks inside the file to determine what type of file it is

* ile.exe - an executable file, or program.
* file.txt - a plain text file.
* file.png, file.gif, file.jpg - an image.

### Linux is case sensitive
Beware of silly typos.



