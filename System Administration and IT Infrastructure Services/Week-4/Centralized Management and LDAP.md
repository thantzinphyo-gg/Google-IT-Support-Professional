# System Administration and IT Infrastructure Services | Week-4

## Centralized Management and LDAP

### Question 1

Which of these are examples of centralized management? Check all that apply. 

Role-based access control ( Correct )

Centralized configuration management ( Correct )

Copying configurations to various systems

Local authentication

Answer - Right on! Role-based access control makes it easier to administer access rights by changing role membership and allowing for inheritance to grant permissions (instead of granting each permission individually for each user account). Centralized configuration management is an easier way to manage configurations for services and hardware. By centralizing this, it becomes easier to push changes to multiple systems at once.


### Question 2

Which of these are components of an LDAP entry? Check all that apply. 

Uncommon Name

Common Name ( Correct )

Organizational User

Distinguished Name ( Correct )

Answer - Wohoo! The Common Name contains a descriptor of the object, like the full name for a user account. A Distinguished Name is the unique name for the entry, and includes the attributes and values associated with the entry.


### Question 3

What's does the LDAP Bind operation do exactly? 

Modifies entries in a directory server

Looks up information in a directory server

Authenticates a client to the directory server  ( Correct )

Changes the password for a user account on the directory server

Answer - Awesome! A client authenticates to a directory server using the Bind operation. This could either be: (1) an anonymous bind; (2) a simple bind, where the password is sent in plaintext; or (3) an SASL bind, which involves a secure challenge-response authentication scheme.


### Question 4

Which of the following are authentication types supported by the LDAP Bind operation? Check all that apply. 

Anonymous ( Correct )

Simple ( Correct )

Complex

SASL ( Correct )

Answer - That's it! Bind operations support three different mechanisms for authentication: (1) Anonymous, which doesn't actually authenticate at all, and allows anyone to query the server; (2) Simple, which involves sending the password in plaintext; and (3) SASL, or Simple Authentication and Security Layer, which involves a secure challenge-response authentication mechanism.


### Question 5

Which of these are examples of centralized management? Check all that apply.

Local authentication

Copying configurations to various systems

Role-based access control ( Correct )

Centralized configuration management ( Correct )

Answer - Role-based access control makes it easier to administer access rights by changing role membership and allowing for inheritance to grant permissions (instead of granting each permission individually for each user account). Centralized configuration management is an easier way to manage configurations for services and hardware. By centralizing this, it becomes easier to push changes to multiple systems at once.


### Question 6

Which of these are components of an LDAP entry? Check all that apply.

Common Name ( Correct )

Uncommon Name

Kerberos

Distinguished Name ( Correct )

Answer - The Common Name contains a descriptor of the object, like the full name for a user account. A Distinguished Name is the unique name for the entry, and includes the attributes and values associated with the entry.


### Question 7

What does the LDAP Bind operation do exactly?

Changes the password for a user account on the directory server

Looks up information in a directory server

Authenticates a client to the directory server ( Correct )

Modifies entries in a directory server

Answer - A client authenticates to a directory server using the Bind operation. This could either be: (1) an anonymous bind; (2) a simple bind, where the password is sent in plaintext; or (3) an SASL bind, which involves a secure challenge-response authentication scheme.


### Question 8

Which of the following are authentication types supported by the LDAP Bind operation? Check all that apply.

Complex

Simple ( Correct )

SASL ( Correct )

Anonymous ( Correct )

Answer - Bind operations support three different mechanisms for authentication: (1) Anonymous, which doesn't actually authenticate at all, and allows anyone to query the server; (2) Simple, which involves sending the password in plaintext; and (3) SASL, or Simple Authentication and Security Layer, which involves a secure challenge-response authentication mechanism.


### Question 9

Which of the following are services provided for the Directory Services?

Local authentication

Centralized Authentication ( Correct )

Authorization ( Correct )

Accounting ( Correct )

Answer - Directory services provide centralized authentication, authorization, and accounting, also known as AAA.