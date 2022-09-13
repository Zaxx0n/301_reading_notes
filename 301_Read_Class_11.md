# NAT

NAT is a process in which one or more local IP address is translated into one or more Global IP address or vice versa.  This allows the Internet access to local hosts. It usually operates on a router or firewall.

How it works:  Usually, the border router is configured for NAT.  Whan a packet goes outside of the the local network, NAT convertes the private IP to a global or public IP. This works the same way but opposite with incoming traffic.

If NAT runs out of IP addresses, then an "ICMP host unreachable" packet will be sent to the destination.

### NAT inside and outside addresses:

- Inside local address This is an IP assigned to a host inside the local network.
 
Inside global address – The inside host seen from outside the network.
 
Outside local address – This is the actual IP address of the destination host in the local network after translation. 
 
Outside global address - The IP address of the outside destination host before translation. 

### NAT Types
1. Static NAT - A single unregistered (public) IP address that uses 1-1 mapping.
2. Dynamic NAT - Unregistered IP address is translated into a registered public address.
3. Port Address Translation (PAT) - Also known as "NAT overload".  Many local IP addresses can be translated into a single registered IP address.