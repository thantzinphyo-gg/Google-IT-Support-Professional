# IT Security: Defense Against The Digital Dark Arts | Week-5

## System Hardening

### Question 1

What is an attack vector? 

The classification of attack type 

The direction an attack is going in 

The severity of the attack

A mechanism by which an attacker can interact with your network or systems  ( Correct )

Answer - Nice job! An attack vector can be thought of as any route through which an attacker can interact with your systems and potentially attack them.


### Question 2

Disabling unnecessary components serves which purposes? Check all that apply. 

Reducing the attack surface  ( Correct )

Increasing performance 

Making a system harder to use 

Closing attack vectors ( Correct )

Answer - Right on! Every unnecessary component represents a potential attack vector. The attack surface is the sum of all attack vectors. So, disabling unnecessary components closes attack vectors, thereby reducing the attack surface.


### Question 3

What's an attack surface? 

The payload of the attack 

The total scope of an attack 

The target or victim of an attack 

The combined sum of all attack vectors in a system or network ( Correct )

Answer - Yep! The attack surface describes all possible ways that an attacker could interact and exploit potential vulnerabilities in the network and connected systems.


### Question 4

A good defense in depth strategy would involve deploying which firewalls? 

No firewalls 

Both host-based and network-based firewalls ( Correct )

Network-based firewalls only 

Host-based firewalls only 

Answer - You got it! Defense in depth involves multiple layers of overlapping security. So, deploying both host- and network-based firewalls is recommended.


### Question 5

Using a bastion host allows for which of the following? Select all that apply. 

Having more detailed monitoring and logging  ( Correct )

Applying more restrictive firewall rules  ( Correct )

Running a wide variety of software securely

Enforcing stricter security measures  ( Correct )

Answer - Wohoo! Bastion hosts are special-purpose machines that permit restricted access to more sensitive networks or systems. By having one specific purpose, these systems can have strict authentication enforced, more firewall rules locked down, and closer monitoring and logging.


### Question 6

What benefits does centralized logging provide? Check all that apply. 

It allows for easier logs analysis.  ( Correct )

It blocks malware infections. 

It prevents database theft. 

It helps secure logs from tampering or destruction. ( Correct )

Answer - Yes! Centralized logging is really beneficial, since you can harden the log server to resist attempts from attackers trying to delete logs to cover their tracks. Keeping logs in place also makes analysis on aggregated logs easier by providing one place to search, instead of separate disparate log systems.


### Question 7

What are some of the shortcomings of antivirus software today? Check all that apply. 

It's very expensive. 

It can't protect against unknown threats. ( Correct ) 

It only detects malware, but doesn't protect against it.

It only protects against viruses. 

Answer - Awesome! Antivirus software operates off a blacklist, blocking known bad entities. This means that brand new, never-before-seen malware won't be blocked.


### Question 8

How is binary whitelisting a better option than antivirus software? 

It has less performance impact. 

It's cheaper. 

It can block unknown or emerging threats.  ( Correct )

It's not better. It's actually terrible.

Answer - That's right! By blocking everything by default, binary whitelisting can protect you from the unknown threats that exist without you being aware of them.


### Question 9

What does full-disk encryption protect against? Check all that apply. 

IP spoofing attacks

Malware infections 

Data theft  ( Correct )

Tampering with system files  ( Correct )

Answer - Excellent job! With the contents of the disk encrypted, an attacker wouldn't be able to recover data from the drive in the event of physical theft. An attacker also wouldn't be able to tamper with or replace system files with malicious ones.


### Question 10

What's the purpose of escrowing a disk encryption key? 

Performing data recovery ( Correct )

Protecting against unauthorized access

Preventing data theft 

Providing data integrity 

Answer - Yep! Key escrow allows the disk to be unlocked if the primary passphrase is forgotten or unavailable for whatever reason.

