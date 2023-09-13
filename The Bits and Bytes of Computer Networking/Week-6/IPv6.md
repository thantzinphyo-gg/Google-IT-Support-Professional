# The Bits and Bytes of Computer Networking | Week-6

## IPv6

### Question 1

An IPv6 address is how many bits long?

64

16

32

128 ( Correct )

Answer - An IPv6 address is 128 bits long


### Question 2

What is the very first field in an IPv6 header?

source address field

data payload field

traffic class field

version field ( Correct )

Answer - This field is used to indicate what version of IP is being used.


### Question 3

Which IPv6 header field indicates how many routers can forward a packet before it's discarded?

router forward field

next header field

TTL

hop limit field ( Correct )

Answer - The hop limit field configures how many routers can try to forward a packet before it's discarded.


### Question 4

The IPv4 mapped address space within IPv6 always starts with _______ zeroes.   

64

80 ( Correct )

32

"128" 

Answer - 80 zeroes, followed by 16 ones, followed by the IPv4 address itself.


### Question 5

For IPv6 traffic to travel on an IPv4 network, which two technologies are used? Select all that apply.   

Packets

Datagrams  ( Correct )

Answer - IPv6 tunnel servers take incoming IPv6 traffic and encapsulate it within traditional IPv4 datagrams.

IPv4 Tunnels

IPv6 tunnels ( Correct )

Answer - An IPv6 tunnel is used to encapsulate data between IPv6 tunnel servers.