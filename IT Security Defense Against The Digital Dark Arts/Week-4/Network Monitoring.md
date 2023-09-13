# IT Security: Defense Against The Digital Dark Arts | Week-4

## Network Monitoring

### Question 1

What does tcpdump do? Select all that apply. 

Analyzes packets and provides a textual analysis  ( Correct )

Generates packets 

Encrypts your packets

Captures packets  ( Correct )

Answer - Tcpdump is a popular, lightweight command line tool for capturing packets and analyzing network traffic.


### Question 2

What does wireshark do differently from tcpdump? Check all that apply. 

It understands more application-level protocols.  ( Correct )

It can capture packets and analyze them. 

It has a graphical interface.  ( Correct )

It can write packet captures to a file.

Answer - Awesome job! tcpdump is a command line utility, while wireshark has a powerful graphical interface. While tcpdump understands some application-layer protocols, wireshark expands on this with a much larger complement of protocols understood.


### Question 3

What factors should you consider when designing an IDS installation? Check all that apply. 

Storage capacity  ( Correct )

OS types in use 

Traffic bandwidth  ( Correct )

Internet connection speed

Answer - Wohoo! It's important to understand the amount of traffic the IDS would be analyzing. This ensures that the IDS system is capable of keeping up with the volume of traffic. Storage capacity is important to consider for logs and packet capture retention reasons.


### Question 4

What is the difference between an Intrusion Detection System and an Intrusion Prevention System? 

They are the same thing.

An IDS can alert on detected attack traffic, but an IPS can actively block attack traffic. ( Correct )

An IDS can actively block attack traffic, while an IPS can only alert on detected attack traffic.

An IDS can detect malware activity on a network, but an IPS can't

Answer - That's exactly right! An IDS only detects intrusions or attacks, while an IPS can make changes to firewall rules to actively drop or block detected attack traffic.


### Question 5

What factors would limit your ability to capture packets? Check all that apply.

Network interface not being in promiscuous or monitor mode ( Correct )

Anti-malware software

Encryption

Access to the traffic in question ( Correct )

Answer - You got it! If your NIC isn't in monitor or promiscuous mode, it'll only capture packets sent by and sent to your host. In order to capture traffic, you need to be able to access the packets. So, being connected to a switch wouldn't allow you to capture other clients' traffic.