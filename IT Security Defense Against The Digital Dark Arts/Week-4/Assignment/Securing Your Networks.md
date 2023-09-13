# IT Security: Defense Against The Digital Dark Arts | Week-4

## Securing Your Networks

### Question 1

What does tcpdump do?

Generates DDoS attack traffic 

Brute forces password databases

Performs packet capture and analysis ( Correct )

Handles packet injection

Answer - tcpdump captures and analyzes packets for you, interpreting the binary information contained in the packets and converting it into a human-readable format.


### Question 2

What can protect your network from DoS attacks?

DHCP Snooping 

Flood Guard  ( Correct )

IP Source Guard 

Dynamic ARP Inspection 

Answer - Flood guards provide protection from DoS attacks by blocking common flood attack traffic when it's detected.


### Question 3

What occurs after a Network Intrusion Detection System (NIDS) first detects an attack? 

Blocks traffic

Triggers alerts  ( Correct )

Shuts down

Disables network access

Answer - A NIDS only alerts when it detects a potential attack.


### Question 4

What does a Network Intrusion Prevention System (NIPS) do when it detects an attack?

It attacks back.

It blocks the traffic. ( Correct )

It does nothing. 

It triggers an alert. 

Answer - An NIPS would make adjustments to firewall rules on the fly, and drop any malicious traffic detected.


### Question 5

How do you protect against rogue DHCP server attacks?

IP Source Guard 

Dynamic ARP Inspection 

DHCP Snooping  ( Correct )

Flood Guard

Answer - DHCP snooping prevents rogue DHCP server attacks. It does this by creating a mapping of IP addresses to switch ports and keeping track of authoritative DHCP servers.


### Question 6

What underlying symmetric encryption cipher does WEP use?

RSA 

RC4  ( Correct )

DES 

AES

Answer - WEP uses the RC4 stream cipher.


### Question 7

What traffic would an implicit deny firewall rule block?   


Nothing unless blocked

Inbound traffic only

Everything that is not explicitly permitted or allowed  ( Correct )

Outbound traffic only 

Answer - Implicit deny means that everything is blocked, unless it's explicitly allowed.


### Question 8

What allows you to take all packets from a specified port, port range, or an entire VLAN and mirror the packets to a specified switch port?

Port Mirroring  ( Correct )

Network hub 

DHCP Snooping 

Promiscuous Mode

Answer - Port mirroring allows you to capture traffic on a switch port transparently, by sending a copy of traffic on the port to another port of your choosing.


### Question 9

What kind of attack does IP Source Guard (IPSG) protect against?

DoS attacks

Rogue DHCP Server attacks

IP Spoofing attacks  ( Correct )

ARP Man-in-the-middle attacks

Answer - IP Source Guard protects against IP spoofing. It does this by dynamically generating ACLs for each switch port, only permitting traffic for the mapped IP address for that port.


### Question 10

What can be configured to allow secure remote connections to web applications without requiring a VPN?

Web browser 

Reverse proxy ( Correct )

RC4

NIDS

Answer - A reverse proxy can be used to allow remote access into a network.