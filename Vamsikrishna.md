ubuntu@ip-172-31-1-173:~$ sudo -i
root@ip-172-31-1-173:~# pwd
/root
root@ip-172-31-1-173:~# ls
abcd  python.py  snap
root@ip-172-31-1-173:~# ls -l
total 8
-rw-r--r-- 1 root root    0 Nov  4 10:46 abcd
-rw-r--r-- 1 root root   39 Nov  5 09:12 python.py
drwx------ 4 root root 4096 Nov  5 09:28 snap
root@ip-172-31-1-173:~# cd snap
root@ip-172-31-1-173:~/snap# ls
CBIT  abcd  amazon-ssm-agent  krishna.py  python.py
root@ip-172-31-1-173:~/snap# touch python.py
root@ip-172-31-1-173:~/snap# ls
CBIT  abcd  amazon-ssm-agent  krishna.py  python.py
root@ip-172-31-1-173:~/snap# cp python.py snap
root@ip-172-31-1-173:~/snap# cd snap
-bash: cd: snap: Not a directory
root@ip-172-31-1-173:~/snap# cd snap/
-bash: cd: snap/: Not a directory
root@ip-172-31-1-173:~/snap# mv python.py krishna.py
root@ip-172-31-1-173:~/snap# ls
CBIT  abcd  amazon-ssm-agent  krishna.py  snap
root@ip-172-31-1-173:~/snap# rm krishna.py
root@ip-172-31-1-173:~/snap# ls
CBIT  abcd  amazon-ssm-agent  snap
root@ip-172-31-1-173:~/snap# mkdir cbit vamsi krishna
root@ip-172-31-1-173:~/snap# ls
CBIT  abcd  amazon-ssm-agent  cbit  krishna  snap  vamsi
root@ip-172-31-1-173:~/snap# ls -l
total 20
drwxr-xr-x 2 root root 4096 Nov  4 10:42 CBIT
-rw-r--r-- 1 root root    0 Nov  4 10:45 abcd
drwxr-xr-x 4 root root 4096 Nov  4 10:02 amazon-ssm-agent
drwxr-xr-x 2 root root 4096 Nov  5 09:44 cbit
drwxr-xr-x 2 root root 4096 Nov  5 09:44 krishna
-rw-r--r-- 1 root root    0 Nov  5 09:41 snap
drwxr-xr-x 2 root root 4096 Nov  5 09:44 vamsi
root@ip-172-31-1-173:~/snap# rmdir vamsi
root@ip-172-31-1-173:~/snap# ls -l
total 16
drwxr-xr-x 2 root root 4096 Nov  4 10:42 CBIT
-rw-r--r-- 1 root root    0 Nov  4 10:45 abcd
drwxr-xr-x 4 root root 4096 Nov  4 10:02 amazon-ssm-agent
drwxr-xr-x 2 root root 4096 Nov  5 09:44 cbit
drwxr-xr-x 2 root root 4096 Nov  5 09:44 krishna
-rw-r--r-- 1 root root    0 Nov  5 09:41 snap
root@ip-172-31-1-173:~/snap# cd CBIT
root@ip-172-31-1-173:~/snap/CBIT# ls
root@ip-172-31-1-173:~/snap/CBIT# touch ab
root@ip-172-31-1-173:~/snap/CBIT# cd ..
root@ip-172-31-1-173:~/snap# rmdir CBIT
rmdir: failed to remove 'CBIT': Directory not empty
root@ip-172-31-1-173:~/snap# rm -rf
root@ip-172-31-1-173:~/snap# rm -rf CBIT
root@ip-172-31-1-173:~/snap# rm --help
Usage: rm [OPTION]... [FILE]...
Remove (unlink) the FILE(s).

  -f, --force           ignore nonexistent files and arguments, never prompt
  -i                    prompt before every removal
  -I                    prompt once before removing more than three files, or
                          when removing recursively; less intrusive than -i,
                          while still giving protection against most mistakes
      --interactive[=WHEN]  prompt according to WHEN: never, once (-I), or
                          always (-i); without WHEN, prompt always
      --one-file-system  when removing a hierarchy recursively, skip any
                          directory that is on a file system different from
                          that of the corresponding command line argument
      --no-preserve-root  do not treat '/' specially
      --preserve-root[=all]  do not remove '/' (default);
                              with 'all', reject any command line argument
                              on a separate device from its parent
  -r, -R, --recursive   remove directories and their contents recursively
  -d, --dir             remove empty directories
  -v, --verbose         explain what is being done
      --help        display this help and exit
      --version     output version information and exit

By default, rm does not remove directories.  Use the --recursive (-r or -R)
option to remove each listed directory, too, along with all of its contents.

To remove a file whose name starts with a '-', for example '-foo',
use one of these commands:
  rm -- -foo

  rm ./-foo

Note that if you use rm to remove a file, it might be possible to recover
some of its contents, given sufficient expertise and/or time.  For greater
assurance that the contents are truly unrecoverable, consider using shred(1).

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/rm>
or available locally via: info '(coreutils) rm invocation'
root@ip-172-31-1-173:~/snap# vim python.py
root@ip-172-31-1-173:~/snap# cat python.py
import cbit
import vamsi
import krishna
root@ip-172-31-1-173:~/snap# vim python.py
root@ip-172-31-1-173:~/snap# cat python.py
import cbit
import vamsi
root@ip-172-31-1-173:~/snap# vim python.py
root@ip-172-31-1-173:~/snap# cat python.py
a
b
c
d
e
f
g
h
i
j
k
l
m
n
o
p
q
r
s
t
u
v
w
x
y
z
root@ip-172-31-1-173:~/snap# head -7 python.py
a
b
c
d
e
f
g
root@ip-172-31-1-173:~/snap# tail -8 python.py
s
t
u
v
w
x
y
z
