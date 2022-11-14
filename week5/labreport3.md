# Less command

My week 5 lab isn't fully functional but I will provide examples for each of the commands.

Less has the option "/" to search for a specific aspect of the file that you are searching through. 

The less command also has the option to write "n" to find the next matching command when searching though a large file. This can be especially helpful when replacing certain text that is often repeated in the file.

Another option for the less command is too offer multiple files in the terminal after the command to open up multiple different files. 


# Find command

If you write the find command and then add -mtime you can find files based on modification time. You can also add an -1 after mtime to find all of the files which have been modified in the past day. 

The command -perm after a file is used to get all the files that a certain person has permission to. For example you can use the command -444 to find files tha the owner had access to. 

You can also use the -i command in find to find case insensitive versions of different files. For example if you add the -i command before the file name it will find the file regardless of current case specified. 

# Grep commands

If you add multiple file names after a given file and text string you can test whether multiple files contain a certain string of characters. 

Similar to the find command if you add a -i before the string of characters you can search insensitive the capitilzation. 

Grep can also do many commands in relation to words such as -E which means go to the end of the current word, or W which means go to the next word. x
