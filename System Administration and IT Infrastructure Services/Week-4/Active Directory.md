# System Administration and IT Infrastructure Services | Week-4

## Active Directory

### Question 1

What is the difference between a policy and a preference?

A policy is enforced by AD, while a preference can be modified by a local user. ( Correct )

A policy is used to set a preference.

They are the exact same thing.

A policy can be modified by a local user, while a preference is enforced by AD.

Answer - Policies are settings that are enforced and reapplied regularly by AD, while preferences are defaults for various settings but can be modified by users.


### Question 2

Select the right order of enforcement of GPOs:

Site --> Domain --> OU ( Correct )

OU --> Domain --> Sit

Domain --> Site --> OU

Site --> OU --> Domain

Answer - When GPOs collide, they are applied according to site first and domain second. Then, any OUs are applied from least specific to most specific.


### Question 3

What can be used to determine what policies will be applied to a given machine?

A test domain

A control panel

An RSOP report ( Correct )

gpupdate

Answer - An RSOP, or Resultant Set of Policy, report will generate a report that contains a list of policies that will be applied to a given machine. It takes into account inheritance and precedence information.


### Question 4

Which of the following could prevent logging into a domain-joined computer? Check all that apply.

The are time and date are incorrect ( Correct )

The user account is locked ( Correct )

Unable to reach the domain controller ( Correct )

Your computer is connected to Wifi

Answer - If the machine is unable to reach the domain controller for whatever reason, it wouldn't be able to authenticate against AD. Since AD authentication relies on Kerberos for encryption, authentication against AD will depend on the time being synchronized to within five minutes of the server and client. And of course, if the user account is locked, authenticating or logging in to the computer will not be possible.


### Question 5

How does a client discover the address of a domain controller?

It is pushed via an AD GPO

It sends a broadcast to the local network

It makes a DNS query, asking for the SRV record for the domain ( Correct )

It is provided via DHCP

Answer - The client will make a DNS query, asking for the SRV record for the domain. The SRV record contains address information for domain controllers for that domain.