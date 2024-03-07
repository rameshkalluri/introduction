# Linux History And Basics Linux Command

## Founder of Linux:
Linus Torvalds, a Finnish computer expert, is famous for starting the creation of Linux and the git system for keeping track of changes in software.

# History of Linux:

Linux is like a cool cousin of Unix, and it's a free computer system made by Linus Torvalds in September 1991.

Back in 1991, Linus was a student at the University of Helsinki in Finland, not the USA.

He made the starting code for Linux 0.01 and shared it on the Minix group on September 17, 1991. 
Because people liked it so much, they cheered him on to make more. 
Linus listened, made new code, and on October 5, 1991, he launched the first "official" Linux, version 0.02.

# What is Linux?:

Linux is a Kernel not OS (Operating System).

Linus distribution is the Linux kernel and a collection of software that together, create on Operating System.

# Why Linux is so important ?:

![image](https://github.com/sunspac/introduction/assets/154580560/9813b915-048e-478a-9423-e916367452a8)

# Advantage of Linux:

Open Source.
Secure.
Simplified update for all Install Software.
Light weight.

# Architecture of Window and Linux:
## Window:
Imagine a well-organized skyscraper.

The floors represent different layers of the system.

Windows is designed to work seamlessly within its structured environment.

![image](https://github.com/sunspac/introduction/assets/154580560/002b3326-a006-4fa4-81de-dee81c4dfb20)

## Linux:

Think of a versatile house with different rooms.

You can customize each room as you like.

Linux is adaptable, like having the freedom to rearrange things in your own way.

![image](https://github.com/sunspac/introduction/assets/154580560/1096e273-7988-415d-974a-0ce7aded7cbf)


# FSH(File System Hierarchy) of Linux and Window:
## Window FSH:

![image](https://github.com/sunspac/introduction/assets/154580560/f271388b-3539-4f74-88e3-e2ce6829b2e6)

## Program Files in Windows:

The "Program Files" folder in Windows is where the operating system stores the software applications and programs that you install. Each program typically has its own subfolder within "Program Files," keeping them organized.

## User Files in Windows:

The term "User Files" is a bit general, but it often refers to folders and files associated with a specific user account on a Windows system. This can include documents, pictures, downloads, and other personal files stored in the user's profile.

## Program Files (x86) in Windows:

The "Program Files (x86)" folder is where 32-bit applications are installed on a 64-bit Windows system. The "(x86)" indicates that it's for 32-bit programs. On a 32-bit Windows system, there is no "(x86)" folder because all programs are 32-bit by default.

## PerfLogs in Windows:

"PerfLogs" stands for Performance Logs, and it's a folder where Windows stores performance and reliability monitoring logs. These logs can provide information about system performance, errors, and other events that may affect the overall health and operation of the system. The information in PerfLogs can be useful for troubleshooting and performance analysis.

# Linux FSH:

![image](https://github.com/sunspac/introduction/assets/154580560/7c142db4-9bc6-44b5-8302-5c4ffa408ee1)


/:The base of the Linux directory is the root. This is the starting point of FSH. Every directory arises from the root directory. It is represented by a forward slash (/).

/root: It is home directory for root user.

/mnt: /mnt is for temporarily mounting file systems.

/home: Home directory for other user.

/media: /media is where removable media devices get mounted.

/bin: /bin contains commands used by all the user.

/user: By default software are installed in the directory.

/sbin: It contains command used by root user.

/etc: Directory is a crucial directory that stores system-wide configuration files and settings.

/dev: /dev has device files, such as terminals and USB devices.

/opt: /opt is for optional applications, often from third-party vendors.

/var: /var stores variable files, like log files in /var/log and database files in /var/lib.

Basic Linux Command:
Listing commands ls option_flag arguments --> list the sub directories and files avaiable in the present directory

Examples:

ls -l--> list the files and directories in long list format with extra information.

ls -a --> list all including hidden files and directory.

ls *.sh --> list all the files having .sh extension.

ls -i --> list the files and directories with index numbers inodes.

ls -d */ --> list only directories.(we can also specify a pattern).

Directoy commands pwd --> print work directory. Gives the present working directory.

cd path_to_directory --> change directory to the provided path.

cd ~ or just cd --> change directory to the home directory.

cd - --> Go to the last working directory.

cd .. --> change directory to one step back.

cd ../.. --> Change directory to 2 levels back.
