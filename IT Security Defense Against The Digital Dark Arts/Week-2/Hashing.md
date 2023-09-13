# IT Security: Defense Against The Digital Dark Arts | Week-2

## Hashing

### Question 1

How is hashing different from encryption?

It is less secure.

It is faster.

Hashing is meant for large amounts of data while encryption is meant for small amounts of data.

Hashing operations are one-directional. ( Correct )

Answer - Hash functions, by definition, are one-way, meaning that it's not possible to take a hash and recover the input that generated the hash. Encryption, on the other hand, is two-directional, since data can be both encrypted and decrypted.


### Question 2

What is a hash collision?

When two identical files generate different hash digests.

When two different files generate the same hash digest. ( Correct )

When two different hashing algorithms produce the same hash.

When a hash digest is reversed to recover the original.

Answer - If two different files result in the same hash, it is referred to as a hash collision. Hash collisions aren't good, as this would allow an attacker to create a fake file that would pass hash verification.


### Question 3

How is a Message Integrity Check (MIC) different from a Message Authentication Code (MAC)?

A MAC requires a password while a MIC does not.

A MIC only hashes the message while a MAC incorporates a secret key. ( Correct )

They're the same thing.

A MIC is more reliable than a MAC.

Answer - A MIC can be thought of as just a checksum or hash digest of a message while a MAC uses a shared secret to generate the checksum. This also makes it authenticated since the other party must also have the same shared secret, preventing a third party from forging the checksum data.


### Question 4

How can one defend against brute-force password attacks? Check all that apply.

Incorporate salts into password hashing. ( Correct )

Store passwords in a rainbow table.

Run passwords through the hashing function multiple times. ( Correct )

Enforce the use of strong passwords. ( Correct )

Answer - A brute-force password attack involves guessing the password. So, having complex and long passwords will make this task much harder and will require more time and resources for the attacker to succeed. Incorporating salts into password hashes will protect against rainbow table attacks, and running passwords through the hashing algorithm lots of times also raises the bar for an attacker, requiring more resources for each password guess.


### Question 5

______ is a type of function or operation that takes in an arbitrary data input and maps it to an output of a fixed size, called a hash or a digest. 

Phishing

Cryptography

Secure key exchange

A hash function ( Correct )

Answer - Hashing is a special type of function that's widely used in computing and especially within security.