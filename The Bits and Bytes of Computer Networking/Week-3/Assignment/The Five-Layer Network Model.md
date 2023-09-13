# The Bits and Bytes of Computer Networking | Week-3

## The Five-Layer Network Model

### Question 1

Computer 1 on network A, with IP address of 10.1.1.205, wants to send a packet to Computer 2, with IP address of 172.16.1.57. On which network is computer 2?

Local network ( InCorrect )

Network B

Network A

Network C


### Question 2

What information is computer 1 looking at in the ARP table on Router Y?

TTL value

Destination MAC address

Port number

MAC address ( Correct )


### Question 3

Which layer constructs the IP datagram?

Application layer

Data layer

Physical Layer

Network layer ( Correct )


### Question 4

What information is in the data payload for the IP datagram?

TCP segment ( Correct )

ART table

Network B address space

The ARP discovery request


### Question 5

When constructing the Ethernet datagram to send the packet from computer 1 to its gateway (Router Y), what information needs to be in the destination MAC address?


Router Z’s MAC address

Computer 1’s MAC address

Computer 2’s MAC address

Router Y’s MAC address ( Correct )


### Question 6

Computer 1 on Network A sends a packet to Computer 2 on Network C. What's the first step that Router Z does after receiving the Ethernet frame?


Calculates a checksum and compares this checksum with the one in the Ethernet frame header  ( Correct )

Sends an ARP broadcast message

Checks the destination IP address and changes it to its own

Increases the TTL by one


### Question 7

Computer 1 on network A, with IP address of 10.1.1.8, wants to send a packet to Computer 2, with IP address of 172.16.1.64. If the TTL value was set to 64 at the beginning, what is the value of the TTL once it reaches its destination?

62 ( Correct )

0

60

65


### Question 8

Computer 1 on network C, with IP address of 172.16.1.57, wants to send a packet to Computer 2, with IP address of 192.168.1.14. Taking in consideration that computer 1 is sending a request to a web server on computer 2, listening on port 80, and the source port on computer 1 is 5000, which of the following contains the correct information for the fourth TCP segment of data?


Source Port: 8081

Destination Port: 50

Sequence Number: 4

Acknowledgment Number: 1


Source Port: 5000 ( InCorrect )

Destination Port: 80

Sequence Number: 1

Acknowledgment Number: 2


Source Port: 80

Destination Port: 5000

Sequence Number: 1

Acknowledgment Number: 1


Source Port: 5000

Destination Port: 80

Sequence Number: 4

Acknowledgment Number: 5


### Question 9

Computer 1 on network A, with IP address of 10.1.1.10, wants to send a packet to Computer 2, with IP address of 172.16.1.64. Which of the following has the correct IP datagram information for the fields: Version, minimum Header Length, Source IP, and Destination IP?

Version: 5

Header Length: 16

Source IP Address: 171.1.1.1.

Destination IP address: 172.16.1.0/24.


Version: 4  ( Correct )

Header Length: 20

Source IP Address: 10.1.1.10

Destination IP address: 172.16.1.64


Version: 6

Header Length: 20

Source IP Address: 8a:1a:2b:3c:4d:5f

Destination IP address: 2a:2b:3c:4d:8f


Version: 4

Header Length: 32

Source IP Address: 10.1.1.1

Destination IP address: 172.16.1.1


### Question 10

The Cat6 cable is part of the ______ layer. 

Transport

Network

Physical ( Correct )

Application
