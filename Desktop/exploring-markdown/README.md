# Bash Cheat Sheet  

A working cheat sheet of common bash commands and Markdown practice

Command |  Function
------- | ---------
pwd | print working directory
ls | list files in current directory
ls -a | will find all files in a directory including hidden files
cd \+ *Directory Name* | change directory to specified directory
cd .. | go back one directory
cd ~ | go back to origin directory
mkdir \+ *DirectoryName* | create a directory
rmdir \+ *DirectoryName* | remove an **empty** directory
rm -r \+ *DirectoryName* | remove an entire directory and any subdirectories
touch \+ *FileName* | create a file
rm \+ *FileName* | remove a file **PERMANENTLY**
mv \+ *startingDirectory/fileName endingDirectory* | move a file to a different directory
mv \+ *Directory/originalFileName Directory/updatedFileName* | rename a file within a specified directory
cp | copy a file
cp -R \+ *OriginalDirectory CopiedDirectory | copy a whole directory including its contents to a specified directory
clear | moves command line to a clean terminal page while preserving the history above
CMD \+ k | clears the terminal
up or down arrows | cycle through previously entered commands
history | shows you all commands since last quit

- You can do chain commands by using "&&"  
>_i.e. mkdir socks && cd socks_  
Will make the directory "socks" and change to that directory

- To create multiple files without needing to change the directory, specify the directory
>_i.e. touch pjs/warmpjs.txt pjs/favoritesocks.txt_  
Will make the files warmpjs.txt and favoritesocks.txt within the pjs directory




