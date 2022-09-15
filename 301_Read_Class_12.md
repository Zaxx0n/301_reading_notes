# AAA

AAA stands for Authentication, Authorization, Accounting

It is a standard-based framework used to control who is permitted to use network resources (authentication), what they are authorized to do (authorization) and caputure the actions performed while accessing the network (accounting).

1. Authentication- this is used to identify the user.
2. Authorization- this is used to enforce policies on network resourses after the user has gained access to the network.
3. Accouting- is a way of monitoring and recording the actions of the user that has gained access to the network.

AAA can be implemented by using the local database or by using an external ACS server.

- local database: create users first for authentication and the provide privilege levels for authorization.

- ACS server: ACS is the more common of the two methods used. An external ACS server is used for AAA on which configuration on both router and ACS is required. The client or NAS (Network Access Server) sends authentication requests to the ACS server and the server decides what to allow the user to access as far as network resources accordiong to their credentials.