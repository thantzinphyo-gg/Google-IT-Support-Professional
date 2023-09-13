# Operating System and You: Becoming a Power User | Week - 2

## Permissions

### Question 1

What are the basic linux file permissions? Check all that apply. 

Read ( Correct )

Write ( Correct )

Modify

Execute ( Correct )

Answer - Great job! The three basic file permissions in Linux are read, write, and execute.


### Question 2

You're given the output of an ls -l of a file in Linux.  

ls -l books_file
dr-x-wxr--  1 phelan cool_group 0 Aug  20 11:10 books_file

Answer the following question: What does the first character of output signify?


The file owner has delete permissions

The file owner is a class D user

books_file is a disk device

books_file is a directory ( Correct )

Answer - Awesome work! The first character in output reflects the type of directory entry; in this case, a directory.


### Question 3

You're given the output of an ls -l of a file in Linux. 

ls -l books_file
dr-x-wxr--  1 phelan cool_group 0 Aug  20 11:10 books_file

Answer the following question: Who does the last trio of bits (r--) in the file permission and attributes refer to?

Group file belongs to

File owner  ( InCorrect )

Regular file

All other users


### Question 4

You're given the output of an ls -l of a file in Linux. 

ls -l books_file

dr-x-wxr--  1 phelan cool_group 0 Aug  20 11:10 books_file

Answer the following question: What permissions does the second trio of bits (-wx) give you? Check all that apply.

Execute ( Correct )

Write  ( Correct )

Read

Group file belongs to

Answer - Great work! w and x are the write and execute permissions.


### Question 5

If I wanted to change permissions of a file called honey_bears, what command could I use to grant write access to the owner of the file without changing other permissions? The owner currently only has read access to the file. Check all that apply.

chmod u+w honey_bears

chmod o+w honey_bears

chmod 644 honey_bears

chmod 400 honey_bears

Answer - You nailed it! You can use the symbolic or numerical form of chmod to modify permissions, but to use the numerical form you need to know what all of the existing permissions are to avoid unintended changes