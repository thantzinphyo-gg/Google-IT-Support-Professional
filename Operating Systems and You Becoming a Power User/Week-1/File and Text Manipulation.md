# Operating System and You: Becoming a Power User | Week - 1

## File and Text Manipulation

### Question 1

In Bash, which of the following commands can be used to view the contents of a document? Check all that apply. 

less

cat ( Correct )

dog

gat

Answer - The cat and less commands are used to view the contents of a file.


### Question 2

A Linux machine has the following files:

apple.txt

banana.jpg

chocolate.txt

orange.txt

What command can be used to search for the word "fruit" in the text files? Check all that apply.

grep fruit *.txt ( Correct )

grep fruit apple.txt chocolate.txt orange.txt ( Correct )

find fruit apple.txt chocolate.txt

find fruit apple.txt chocolate.txt orange.txt

Answer - The grep command can be used to search files for certain words. Also the * wildcard command can be used to filter by a specific pattern.


### Question 3

A Linux machine has a file named "types_of_fish.txt". Which of the following commands can be used to append the word "trout" to the file contents?


echo trout > types_of_fish.txt

echo trout >> types_of_fish.txt ( Correct )

echo trout 2> types_of_fish.txt

echo trout < types_of_fish.txt

Answer - The >> is used as an append redirector.


### Question 4

Using a linux machine, which of the following commands can be used to list through a directory called /home/ben/Documents and search for the word "important" in the filenames in that directory?

ls /home/ben/Documents< grep important

ls /home/ben/Documents >> grep important

ls /home/ben/Documents | grep important ( Correct )

ls /home/ben/Documents > grep important

Answer - The | command is used to pipe the output of one command into another.


### Question 5

Which command can be used on Windows CLI to see the first 10 lines of a file called “more_information.txt”?

cat more_information.txt -head 10 ( Correct )

ls more_information.txt -head 10

head more_information.txt

less more_information.txt -head 10

Answer - The flag -head of the cat command displays “n” number of lines from the beginning of the file.