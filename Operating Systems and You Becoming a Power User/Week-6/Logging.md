
# Operating System and You: Becoming a Power User | Week - 6

## Logging

### Question 1

If you were investigating login issues on a Windows computer, which portion of the Event Viewer logs would be a good place to start your investigation?

Application and Services 

System 

Security  ( Correct )

Answer - The Security log would be a good place to start when troubleshooting login issues.


### Question 2

In what log files can you find information about bootup errors? Select all that apply.

/var/log/kern.log ( Correct )

/var/log/syslog  ( Correct )

/var/log/auth.log 

/var/log/mail.log

Answer - You can find log information about bootup issues in kern.log and the syslog.


### Question 3

In what log files can you find information about authentication errors? 

/var/log/kern.log 

/var/log/auth.log  ( Correct )

/var/log/mail.log 

/var/log/syslog 

Answer - The auth.log file contains authentication log messages.


### Question 4

For an ssh connection to work, which of the following need to be true? Check all that apply.

The SSH server is running on the host you want to connect to.

VPN needs to be set up. 

SSH is installed on client. ( Correct )

You need to specify a hostname to SSH into.  ( Correct )

Answer - To SSH into a remote host, you'll need all of these things setup.


### Question 5

What command do you use to view error logs in real time?

/var/log/auth.log

Less var/log/syslog

Tail -f ( Correct )

-kill

Answer - -tail f is used to view error logs in real time.