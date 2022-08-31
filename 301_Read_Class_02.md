# Windows Domain
Unlike on a typical home computer, a computer joined to a domain has its settings controlled on a domain controller.

### What is a Domain?
A domain allows an administrator to manage large numbers of computers and control them from one place. Domain controllers are one or more servers that have control over the domain and the computers on it. 

Domains are generally computers on the same local network. This can expand to computers that communicate with the controller over the internet or a VPN.

Computers that join a domain use accounts and passwords that are managed on the domain controller.  This allows users to sign onto any computer that has joined the domain.

A network admin can change group policy settings on the domain controller. Computer settings are likely to be locked down on computers on the domain. 

### Workgroups vs Domains

Every Windows computer not joined to a domain is part of a workgroup.  These computers don't have control over any other computer, instead they are joined as equals.  Workgroup computers don't require passwords.