# BASIC COMMANDS
## Creating, Removing, Copying, Moving files & Directories
### Creating a file in Linux
#### Using cat command:
==> cat (Concatenate) command is used to create a file and to display and modify the contents
of a file.To create a file
==> cat > filename (say ktfile)
Hello World
Ctrl+d (To save the file)

#### To display the content of the file
cat filename (say ktfile)

#### To append the data in the already existing file
cat >> <filename>
cat >> ktfile
Ctrl+d (to save the changes)

#### Creating multiple files at same time using touch command
touch <filename> <filename> <filename>
touch file1 file2 file3
Note: to check the files use # ls command
