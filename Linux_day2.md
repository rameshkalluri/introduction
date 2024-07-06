1. Clear

To clear the screen

2. Renaming the file

``` mv <oldName> <NewName> ```

![image](https://github.com/rameshkalluri/introduction/assets/22189360/01c30379-247f-437f-a443-53d6ad8b3e92)

3. how to move files from one folder to another folder

``` mv <source> <destination> ```

![image](https://github.com/rameshkalluri/introduction/assets/22189360/4f452a7f-89b7-4fb9-9e71-530fe0905730)

4. How to edit the file

vim or vi 

1. we can create file
   
2. we modify the existing file
   
=======================================================
```
vim <name of the file>

vim bridge

then you have to click ```i```

enter the data

then click ```escape```

:wq
```
![image](https://github.com/rameshkalluri/introduction/assets/22189360/89528b0a-1e53-4c4c-b68d-857dce9dad1e)

if you dont want changes after updating file 

```
press esc

:q!

```
==========================================================================
How to print last 10 lines?

```
tail  <name of the file>
```

how to print first 10 lines in a file?

```
head <name of the file>
```
how to print n values

```
tail -n <name of the file>
head -n <name of the file>
```
==============================================================

Grep: global regular expression print

``` Syntax: grep -i "<search value>" <name of the file>" ```

![image](https://github.com/rameshkalluri/introduction/assets/22189360/5578c982-9389-4827-a1d0-78ef0c6c9265)

================================================================

Redirecting output

```
 grep -i "continuous" ramesh.txt  > output.txt
 grep -i "99" ramesh.txt  > output.txt
 grep -i "99" ramesh.txt  >> output.txt
```

![image](https://github.com/rameshkalluri/introduction/assets/22189360/3723077b-427d-4f45-89a8-c42c330662f2)

#######################################################################

```
less <filename>

more <filename>
```
to ptint content of a file






