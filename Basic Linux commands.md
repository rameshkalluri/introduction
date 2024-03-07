# Basic Linux Commands
## ls: 
In Linux, the command is used to list the files and directories in a directory. It provides a way to view the contents of a directory, helping users to see what files and subdirectories are present.
## ls -l: 
The (ls -l) command in Linux is used to list files and directories in long format. It provides a detailed view of the contents of a directory, including additional information about each file or directory.
## ls -a:
The (ls -a) command in Linux is used to list files and directories, including hidden files that start with a dot (.). By default, the ls command does not display files or directories whose names begin with a dot, as these are considered hidden in Linux.

Here's a breakdown of the (ls -a) command:

ls: This is the basic command to list files and directories.

-a: This option stands for "all." When used with ls it includes hidden files and directories in the output. Hidden files are those whose names start with a dot (.).

## clear: 
The (clear) command in Linux is used to clear the terminal screen, removing the output of previous commands and providing a clean, empty terminal window.

## Ifconfig:
This is used to configure the kernel-resident network interfaces.

## ping:
The ping command in Linux is used to test the reachability of a host (usually a computer or server) on a network and to measure the round-trip time for messages sent from the originating host to a destination computer. It is a simple and widely used networking utility.

## nslookup: 
The nslookup command in Linux is used to query Domain Name System (DNS) servers to obtain domain name or IP address information.

## sudo:
The sudo command in Linux is used to execute commands with elevated privileges, typically as a superuser or administrator

## wget: 
The wget command in Linux is a utility for downloading files from the internet. It supports various protocols, including HTTP, HTTPS, and FTP. Here's the basic syntax of the wget command

## pwd:
The pwd command in Linux stands for "print working directory." It is used to display the current working directory, which is the directory in the file system where you are currently located.

## mkdir:
In Linux, the mkdir command is used to create directories (folders).
## mkdir -p:
The mkdir -p command in Linux is used to create a directory and its parent directories if they do not exist. The -p option ensures that the command creates the entire directory structure specified in the path.

## cat:
In Linux, the cat command is used to concatenate and display the content of files.

The command cat >> myfile1 in Linux is used to append the content entered through the keyboard to the end of the specified file (myfile1 in this case).

## Here's how the command works:

cat: Invokes the cat command.

>>: Redirects the output to append to the specified file.

myfile1: The name of the file to which the content will be appended.

After entering this command, you can start typing the content you want to append to myfile1 Press ctrl +d to signal the end of input and save the changes. The >>operator is used for appending, so it won't overwrite the existing content; it will add new content to the end of the file.

## touch: 
In Linux, the touch command is used to create empty files or update the timestamp of existing files.
(touch myfile1 myfile2 myfile3)This command creates multiple empty files with the specified filenames.

## vi:
In Linux, the vi command is used to launch the Vim text editor, a powerful and widely used text editor. Vim stands for "Vi IMproved." Here's how you can use the vi command:

This command opens the specified file (filename) in the Vim editor. If the file does not exist, Vim will create a new file with that name.

### Once you are inside Vim, you'll be in one of several modes:

#### Normal Mode: 
This is the mode where you can navigate, delete, copy, and paste text. You cannot directly type text in this mode.

#### Insert Mode:
This is the mode where you can actually insert or edit text. To enter insert mode, press i in normal mode.

#### Command-Line Mode:
This is where you can save changes, exit, or perform other commands. To enter command-line mode, press : in normal mode.

##### Here are some basic commands:

Saving changes and exiting:

Press esc to ensure you are in normal mode.

Type wq: and press enter to save changes and exit.

Exiting without saving changes:

Press esc to ensure you are in normal mode.

Type :q! and press enter to exit without saving changes.

Entering insert mode:

Press i in normal mode to enter insert mode.

Type or edit your text.

Deleting a character or line:

In normal mode, move the cursor to the character or line you want to delete.

Type x to delete a single character or dd to delete the entire line.

These are just a few basic commands. Vim has a rich set of features and commands, and it can take some time to become comfortable with it. If you're new to Vim, you might find it helpful to go through some tutorials or guides to get started.

# cp:
The cp command in Linux is used to copy files or directories from one location to another.

# mv:
The mv command in Linux is used to move or rename files and directories. It can also be used to move files from one directory to another.

# history: 
The history command in Linux is used to display a list of previously executed commands in the terminal session.

# tar:
The tar command in Linux is used for creating and manipulating archive files.

This command creates a new tar archive named archive.tar.gz and compresses it using gzip.

-c: Create a new archive.

-v: Verbosely list the files processed.

-z: Compress the archive using gzip.

-f: Use archive file specified.



# gzip:
The gzip command in Linux is used for compressing files.

# head -n:
The head command in Linux is used to display the beginning lines of a file. It is often used to view the first few lines of a file or the output of a command. The basic syntax of the head command is as follows:

Here's how you can use the head command with the -n option. This command displays the first N lines of the specified file(s).

# tail -n:
The tail command in Linux is used to display the last few lines of a file. It is often used to view the end of log files or monitor real-time updates to a file. The basic syntax of the tail command is as follows:
Here's how you can use the tail command with the -n option:

# rmdir:
The rmdir command in Linux is used to remove empty directories.

# rm:
The rm command in Linux is used to remove files or directories.
# rm -rf:
This forcefully removes a directory and its contents without asking for confirmation.
rm *.txt: This removes all files with the .txt extension in the current directory.

# useradd:
The useradd command in Linux is used to create a new user account.
# passwd: 
The passwd command in Linux is used to change a user's password or manage.

# su:
The su command in Linux is used to switch to another user account, often the superuser (root), by providing the correct password.

# echo:
The echo command in Linux is used to display text or output to the terminal. It is commonly used in shell scripts and command-line operations.

# Cut: 
This command is used to extract specific fields or columns from a file or standard input.

# ID:
This is used to find out user and group names and numeric ID’s (UID or group ID) of the current user or any other user in the server.

# Lsof:
It is used to display a list of all the open files on a Linux system.

# Diff:
This command is used to find the difference between two files.

# Find:
This is used to find files and directories and perform subsequent operations on them.

# Free:
This command displays the total amount of free space available along with the amount of memory used and swap memory in the system, and also the buffers used by the kernel.

# Ssh-keygen: 
This command is used to generate a public/private authentication key pair.

# Curl:
Curl is a tool used for transferring data to or from a server, using various protocols, such as HTTP, HTTPS, FTP, and more. Basic example:
-o: It will save downloaded file on the local machine with the name provided in parameters.

# Tr: 
Tr stands for translation. This command is for translating or deleting characters.

# Apt-get:
This command is used to install, update, and remove packages, as well as to manage the package repository sources.

Here are some common apt-get commands:

apt-get update: This updates the package index files from the package repositories listed in the /etc/apt/sources.list file. This is usually the first command you should run after adding a new repository or package to your system.

apt-get upgrade: This installs newer versions of packages that are already installed on the system. It will also remove any packages that are no longer required.

apt-get install: This installs one or more packages. For example, to install the nano text editor, you would run apt-get install nano.

apt-get remove: This removes one or more packages, but it does not remove the configuration files for the package.

apt-get purge: This removes one or more packages and their configuration files.

apt-get autoremove: This removes packages that were installed as dependencies but are no longer needed.



install: The install command in Linux is used to copy files and set their permissions in a single command. It is often used to install executable files or to copy files to specific locations with specific permissions.



# Ps:
We use ps command to check the unique id behind every process.

a = show processes for all users

u = display the process’s user/owner

x = also show processes not attached to a terminal.



# Kill: 
This command is used to terminate processes manually. This command basically, will send a signal that terminates it.

apt-update: The apt-update command updates the local package database with the latest information about available packages from the software repositories.



apt-upgarde: The apt-upgarde command upgrades all installed packages to their latest versions. It may prompt you for confirmation before proceeding.



**Df, du:**Df (disk free) command will have an account of available disk space, used by file system.

Du (disk usage) command reports the size of directory tree including all the content.



--version: We can use the hostnamectl command to check the Linux Operating System (OS) or we can say to check the version of Ubuntu.

