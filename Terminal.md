# Practice in the Terminal

The first command we are going to learn is pwd which stands for Print Working Directory. (You'll find that a lot of commands in linux are named as an abbreviation of a word or words describing them. This makes it easier to remember them.) The command does just that. It tells you what your current or present working directory is. Give it a try now.

Something we already covered in class. 

Line 1 - We ran ls in it's most basic form. It listed the contents of our current directory.
Line 4 - We ran ls with a single command line option ( -l ) which indicates we are going to do a long listing. A long listing has the following:
First character indicates whether it is a normal file ( - ) or directory ( d )
Next 9 characters are permissions for the file or directory (we'll learn more about them in section 6).
The next field is the number of blocks (don't worry too much about this).
The next field is the owner of the file or directory (ryan in this case).
The next field is the group the file or directory belongs to (users in this case).
Following this is the file size.
Next up is the file modification time.

Finally we have the actual name of the file or directory.
Line 10 - We ran ls with a command line argument ( /etc ). When we do this it tells ls not to list our current directory but instead to list that directories contents.

Line 13 - We ran ls with both a command line option and argument. As such it did a long listing of the directory /etc.
Lines 12 and 18 just indicate that I have cut out some of the commands normal output for brevities sake. When you run the commands you will see a longer listing of files and directories.

Line 1 - We ran pwd just to verify where we currently are.
Line 4 - We ran ls providing it with a relative path. Documents is a directory in our current location. This command could produce different results depending on where we are. If we had another user on the system, bob, and we ran the command when in their home directory then we would list the contents of their Documents directory instead.

Line 7 - We ran ls providing it with an absolute path. This command will provide the same output regardless of our current location when we run it.

# pwd
Print Working Directory - ie. Where are we currently.
# ls
List the contents of a directory.
# cd
Change Directories - ie. move to another directory.

Relative path
A file or directory location relative to where we currently are in the file system.
Absolute path
A file or directory location in relation to the root of the file system.

# file
obtain information about what type of file a file or directory is.
# ls -a
List the contents of a directory, including hidden files.
Even directories.

# man <command>
Look up the manual page for a particular command.
# man -k <search term>
Do a keyword search for all manual pages containing the given search term.
# /<term>
Within a manual page, perform a search for 'term'
# n
After performing a search within a manual page, select the next found item.
  
# mkdir
Make Directory - ie. Create a directory.
  
# rmdir
Remove Directory - ie. Delete a directory.
  
# touch
Create a blank file.
  
# cp
Copy - ie. Copy a file or directory.
  
# mv
Move - ie. Move a file or directory (can also be used to rename).
  
# rm
Remove - ie. Delete a file.
  
[Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)
