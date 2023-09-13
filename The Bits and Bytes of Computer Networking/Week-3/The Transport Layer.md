# The Bits and Bytes of Computer Networking | Week-3

## The Transport Layer

### Question 1

What ordering of TCP flags make up the Three-Way Handshake?


SYN, SYN/ACK, ACK ( Correct )

FIN, FIN/ACK, ACK

SYN, ACK, FIN

SYN, ACK, SYN, ACK

Answer - The computer that wants to establish a connection sends a packet with the SYN flag set. Then, the server responds with a packet with both the SYN and ACK flags set. Finally, the original computer sends a packet with just the ACK flag set.


### Question 2

Transport layer protocols, like TCP and UDP, introduce the concept of a port. How many bits are in a port field?

8

32

4

16 ( Correct )

Answer - A TCP port and a UDP port are both 16-bit numbers, meaning there are theoretically 65,535 possible values it can have.


### Question 3

A device that blocks traffic that meets certain criteria is known as a ________.

Hub

Switch

Firewall( Correct )

Router

Answer - A firewall is used to block certain defined types of traffic.


### Question 4

Which TCP flag is used to make the listening program respond immediately?

ACK

PSH ( Correct )

RST

URG

Answer - When the Push (PSH) flag is set, the transmitting device wants the receiving device to push currently buffered data to the application on the receiving end as soon as possible.


### Question 5

_________are identified as ports 49152 through 65535.

Sockets

Ephemeral ports ( Correct )

System ports

User ports

Answer - Ephemeral Ports are identified as ports 49152 through 65535. Ephemeral ports are used as temporary ports for private transfers.

