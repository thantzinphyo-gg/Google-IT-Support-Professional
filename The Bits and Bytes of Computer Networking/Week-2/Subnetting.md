# The Bits and Bytes of Computer Networking | Week-2

## Subnetting

### Question 1

What does CIDR stand for?

Classful Identification Routing

Classful Interlink-Destination Routing

Class Interconnect Destination Routing

Classless Inter-Domain Routing ( Correct )


Answer -CIDR stands for Classless Inter-Domain Routing.


### Question 2

Which of the following is a correct form of CIDR notation?

192.168.1.0\24

192.168.1.0/24  ( Correct )

Answer - CIDR notation uses a forward slash and then lists the numbers of bits in the subnet mask.

192.168.1.0 + 255.255.255.0

192.168.1.0:24


### Question 3

How many octets does a subnet mask have?

3

2

1

4  ( Correct )

Answer - A subnet mask is the same length as an IP address and has two sections: the subnet ID and the host ID. The beginning part, the subnet ID, is the part of the number with all the ones (in binary representation). The second part, the host ID, is the part with all the zeros. The purpose of the mask is to tell a router what part of an IP address is the subnet ID.


### Question 4

Consider the following scenario:

Your IP address is 192.168.8.34, and your subnet mask is 255.255.0.0. What part of the subnet mask represents the subnet ID?

192.168.0.254

The first two octets of the subnet mask, 255.255   ( Correct )

The last two octets of the subnet mask, 0.0

255.255.0.1

Answer - The first two octets are all ones in binary (11111111,11111111). This tells the router that the first two octets of the IP address are the subnet ID.


### Question 5

How many possible host IDs do you always lose per network?


8

12

2   ( Correct )

4

Answer - You always lose two host IDs per network. For example, the subnet mask of 255.255.255.0 has the last octet available for host IDs (256 potential hosts). But remember, zero is generally not used, and 255 is normally reserved as a broadcast address.This means that, really, only the numbers 1-254 are available for assignment to a host.