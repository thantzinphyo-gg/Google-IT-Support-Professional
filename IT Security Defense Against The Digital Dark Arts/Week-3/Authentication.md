# IT Security: Defense Against The Digital Dark Arts | Week-3

## Authentication

### Question 1

How is authentication different from authorization? 

Authentication is verifying an identity; authorization is verifying access to a resource. ( Correct )

Authentication is verifying access to a resource; authorization is verifying an identity.

Authentication is identifying a resource; authorization is verifying access to an identity.

They're the same thing.

Answer - Right on! Authentication is proving that an entity is who they claim to be, while authorization is determining whether or not that entity is permitted to access resources.


### Question 2

What are some characteristics of a strong password? Check all that apply, 

Contains dictionary words

Is at least eight characters long ( Correct )

Is used across accounts and systems

Includes numbers and special characters ( Correct )

Answer - You got it! A strong password should contain a mix of character types and cases, and should be relatively long -- at least eight characters, but preferably more.


### Question 3

In a multi-factor authentication scheme, a password can be thought of as: 

something you have.

something you are. 

something you know. ( Correct )

something you use.

Answer - Wohoo! Since a password is something you memorize, it's something you know when talking about multi-factor authentication schemes.


### Question 4

What are some drawbacks to using biometrics for authentication? Check all that apply. 

There are potential privacy concerns. ( Correct )

Biometrics are easy to share.

Biometric authentication is much slower than alternatives.

Biometric authentication is difficult or impossible to change if compromised. ( Correct )

Answer - That's exactly right! If a biometric characteristic, like your fingerprints, is compromised, your option for changing your "password" is to use a different finger. This makes "password" changes limited. Other biometrics, like iris scans, can't be changed if compromised. If biometric authentication material isn't handled securely, then identifying information about the individual can leak or be stolen.


### Question 5

In what way are U2F tokens more secure than OTP generators? 

They're cheaper.

They're resistant to phishing attacks. ( Correct )

They can't be cloned.

They're password-protected.

Answer - Great job! With one-time-password generators, the one-time password along with the username and password can be stolen through phishing. On the flip side, U2F authentication is impossible to phish, given the public key cryptography design of the authentication protocol.


### Question 6

What elements of a certificate are inspected when a certificate is verified? Check all that apply. 

Trust of the signatory CA ( Correct )

"Not valid before" date ( Correct )

Certificate key size

"Not valid after" date ( Correct )

Answer - Yep! To verify a certificate, the period of validity must be checked, along with the signature of the signing certificate authority, to ensure that it's a trusted one.


### Question 7

What is a CRL? 

Certificate Revocation List ( Correct )

Certificate Recording Language

Caramel Raspberry Lemon

Certified Recursive Listener

Answer - Good job! CRL stands for "Certificate Revocation List." It's a list published by a CA, which contains certificates issued by the CA that are explicitly revoked, or made invalid.


### Question 8

What are the names of similar entities that a Directory server organizes entities into? 

Organizational Units ( Correct )

Clusters

Groups

Trees

Answer - Awesome! Directory servers have organizational units, or OUs, that are used to group similar entities.


### Question 9

True or false: The Network Access Server handles the actual authentication in a RADIUS scheme.

True

False ( Correct )

Answer - Nice work! The Network Access Server only relays the authentication messages between the RADIUS server and the client; it doesn't make an authentication evaluation itself.


### Question 10

True or false: Clients authenticate directly against the RADIUS server.

True

False ( Correct )

Answer - Clients don't actually interact directly with the RADIUS server; the authentication is relayed via the Network Access Server.


### Question 11

What does a Kerberos authentication server issue to a client that successfully authenticates? 

An encryption key

A digital certificate

A master password

A ticket-granting ticket ( Correct )

Answer - Exactly! Once authenticated, a Kerberos client receives a ticket-granting ticket from the authentication server. This TGT can then be presented to the ticket-granting service in order to be granted access to a resource.


### Question 12

What advantages does single sign-on offer? Check all that apply. 

It reduces time spent authenticating. ( Correct )

It provides encrypted authentication.

It reduces the total number of credentials, ( Correct )

It enforces multifactor authentication.

Answer - You nailed it! SSO allows one set of credentials to be used to access various services across sites. This reduces the total number of credentials that might be otherwise needed. SSO authentication also issues an authentication token after a user authenticates using username and password. This token then automatically authenticates the user until the token expires. So, users don't need to reauthenticate multiple times throughout a work day.


### Question 13

What does OpenID provide? 

Digital signatures

Cryptographic hashing

Authentication delegation ( Correct )

Certificate signing

Answer - Yep! OpenID allows authentication to be delegated to a third-party authentication service.