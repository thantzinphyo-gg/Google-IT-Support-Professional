# Operating System and You: Becoming a Power User | Week - 4

## Filesystem Types

### Question 1

Which of the following is a characteristic of the FAT32 filesystem? Check all that apply.

It doesn't support files larger than 4GB. ( Correct )

Answer - The FAT32 filesystem is great for cross-platform compatibility, but has lots of limitations that don't make it useful for large data storage.

It supports files up to 8GB in size.

It's read and write compatible with Windows, Mac, and Linux OSes.  ( Correct )

Answer - The FAT32 filesystem is great for cross-platform compatibility, but has lots of limitations that don't make it useful for large data storage.

Its filesystem size can't be larger than 32GB. ( Correct )

Answer - The FAT32 filesystem is great for cross-platform compatibility, but has lots of limitations that don't make it useful for large data storage.


### Question 2

What’s the difference between a GPT and MBR partition table? Check all that apply. 


MBR only allows you to have volume sizes of 2TBs or less. ( Correct )

Answer - MBR has a few legacy traits that are being slowly faded out by GPT.

GPT allows you to have volume sizes larger than 2TBs and a large number of partitions. ( Correct )

Answer - MBR has a few legacy traits that are being slowly faded out by GPT.

GPT allows you to have volume sizes of 2TBs or greater.

MBR is the new standard for partition tables. 


### Question 3

Before you can store files on a hard drive, which of the following has to be done? Check all that apply. 

Format a filesystem.  ( Correct )

Answer - Before you can start using a hard drive to store files, you’ll need to partition the disk, format a filesystem, then mount the filesystem.

Mount the filesystem. ( Correct )

Answer - Before you can start using a hard drive to store files, you’ll need to partition 

the disk, format a filesystem, then mount the filesystem.

Partition the disk ( Correct )

Answer - Before you can start using a hard drive to store files, you’ll need to partition the disk, format a filesystem, then mount the filesystem.

Nothing: hard drives can be used to store files out of the box.


### Question 4

What is the name of the tool that ships with Windows and lets you partition a disk and format a file system? 

Volume label:

NTFS

Allocation Unit Size

The Disk Management Utility ( Correct )

Answer - The Disk Management Utility is a Windows tool that lets you partition and format a disk. 


### Question 5

What does Windows OS use to provide the physical memory available in the computer to applications running on the computer? 

NTFS

Virtual memory ( Correct )

GUID

Disk partitioning

Answer - Virtual memory is what the OS uses to provide physical memory available in the computer ro applications running on the computer. 


### Question 6

What’s the PowerShell commandlet you can use to extract and compress archives right from the command line? 

The first partition of the second hard drive detected on the system

The second B hard drive

The second partition of the second hard drive detected on the system ( Correct )

The first hard drive that was detected on the system

Answer - Device partitions are denoted by numbers after the device drive.


### Question 7

Which of the following commands in Windows will create a symbolic link called "cauliflower" to a file named "broccoli.txt?"

mklink broccoli.txt cauliflower

mklink cauliflower broccoli.txt ( Correct )

mklink /H cauliflower broccoli.txt 

Answer - The mklink command will, by default, create symbolic links in the form of mklink <link name> <file name>.


### Question 8

In Linux, what's the difference between the commands df and du? Check all that apply.

du is used to undelete files in a directory.

df is used to find the amount of free space on an entire machine ( Correct )

Answer - The df, or disk free, command is used to find the amount of free space on an entire machine, while the du, or disk usage, command is used to find the disk usage on a specific directory.

df is used to delete files in a directory. 

du is used to find the amount of disk usage on a specific directory. ( Correct )

Answer - Feedback:The df, or disk free, command is used to find the amount of free space on an entire machine, while the du, or disk usage, command is used to find the disk usage on a specific directory.


### Question 9

In Linux, what's the difference between a hardlink and a symlink (Symbolic Link)? Check all that apply. 

If you change the original name of the file, a hard link will still work. ( Correct )

Answer - A hardlink will still work even if you change the original name of a file.

A symlink points to a filename. ( Correct )

Answer - Symlinks are used to point to filenames, while hardlinks point to linked file numbers.

A symlink adds an entry to the MFT that points to the linked file number instead of the name of the file. 

A hardlink points to a linked file number.