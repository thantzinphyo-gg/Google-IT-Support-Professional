# The Bits and Bytes of Computer Networking | Week-6

## Verifying Connectivity

### Question 1

The protocol used to communicate network errors is known as __________.

TCP

Traceroute

UDP

ICMP ( Correct )

Answer - ICMP is used to communicate errors back to the client.


### Question 2

The ping utility sends what message type?

Destination Network Unknown

Destination Network Unreachable

Echo Request ( Correct )

Echo Reply

Answer - By default, the ping utility sends an Echo Request ICMP message type.


### Question 3

What is one of the tools you can use to verify connectivity to a specific port on Windows OS?

Ping

Tracert

nc (netcat)

Test-NetConnection ( Correct )

Answer - Test-NetConnection lets you test many things, including connectivity to a specific port on a remote host.


### Question 4

Traceroute uses UDP packets on which of the following operating systems? Select all that apply.   

Linux  ( Correct )

Answer - On Linux and macOS, traceroute sends UDP packets to very high port numbers.

Windows 7

Mac Os   ( Correct )

Answer - On Linux and macOS, traceroute sends UDP packets to very high port numbers.

Windows 10


### Question 5

During a traceroute, which action does a router perform to the value in the Time To Live (TTL) field?   

Division 

Addition

Subtraction  ( Correct )

Multiplication 

Answer - The TTL field is decremented (subtracted) by one by every router that forwards the packet.