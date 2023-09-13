# Operating System and You: Becoming a Power User | Week - 2

## Users, Administrators,Groups and Permissions

###  Question 1

Does an administrator user account on a computer have complete control over a machine?

Sometimes

Yes ( Correct )

No


### Question 2

In the Computer Management tool in Windows, what setting can an administrator enable if a user’s password was compromised and they need to update it?

Password must be changed

User must change password at next logon. ( Correct )

Password never expires

User cannot change password


### Question 3

Which Windows PowerShell CLI command can be used to list the Users on a given computer? 

Get-LocalGroup

Get-GPOReport

Get-LocalUser ( Correct )

Get-LocalGroupMember


### Question 4

On a Linux system, which file contains information about the users on a machine? 

/etc/group

/etc/sudoers

/etc/users

/etc/passwd ( Correct )


### Question 5

Which of the following locations and/or methods can Administrators find and/or use to change user passwords on Windows systems? (Choose all that apply)

At the CLI, using the DOS style net user command. ( Correct )

In the GUI, under Local Users and Groups in the Computer Management tool. ( Correct )

At the CLI, using the DOS style net config command.

In the GUI, under Control Panel > System and Security > Change User Account Control Settings.


### Question 6

On Linux systems, which CLI command and flags are used to force a user to change their password upon their next login? (Choose all that apply)

passwd -eusername ( Correct )

user -e username

passwd --expire username ( Correct )

password -changeusername


### Question 7

Which of the following methods can Administrators use to add a user in Windows? (Choose all that apply)

At the CLI, using the DOS style net computer computername/new command.

With Powershell, use the Create-LocalUser usernamecommand.

This should not be selected
Please review the video on adding and removing users on Windows. ( InCorrect )

At the CLI, use the DOS style net user username * /add command.

In the GUI, under Local Users and Groups in the Computer Management tool, right click Users and select New User.  ( Correct )


### Question 8

In Windows, which of the following are directory and file permissions that can be assigned to groups and/or users? (Choose all that apply)

Write ( Correct )

Change

Read & Execute ( Correct )

List folder contents


### Question 9

Imagine you are an IT administrator and you need to check that proper permissions are configured on a file in Linux. The file’s owner should have full permissions. The file’s associated group members should be able to read and write to the file, but not execute the file. Other users can only read the file. How should these file permissions look when you check them in the CLI environment?

-rwxrw-r- - ( Correct )

Drwxrw-r- -

-rwerw-r- -

-r- -rw-rwx


### Question 10

In Windows, a simple permission is actually a larger set of ___

user permissions. ( InCorrect )

admin permissions.

partial permissions.

special permissions.
