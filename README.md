# Task-5-Internship

Identified Protocols

From the packet capture, at least three distinct protocols were found — and even more beyond that. Here's a summary:
UDP (User Datagram Protocol)
A lightweight, connectionless transport protocol often used for fast data transmission.
Used by protocols like DNS and IGMP in your capture.TCP (Transmission Control Protocol)
A reliable, connection-oriented protocol used for most web traffic and secure communications.
DNS (Domain Name System)
Resolves human-readable domain names into IP addresses.
Typically uses UDP on port 53.
TLS (Transport Layer Security)
Provides secure communication over a network (used in HTTPS).
Operates over TCP.
HTTP (Hypertext Transfer Protocol)
Foundation of data communication for the web.
Used for transmitting webpages.OCSP (Online Certificate Status Protocol)
A security protocol for obtaining the revocation status of an X.509 digital certificate.
IGMP (Internet Group Management Protocol)
Used by hosts and adjacent routers to establish multicast group memberships.

Packet Details Summary

Based on the observed traffic:
The capture includes DNS queries and responses — indicating domain name resolution activity.
TLS handshakes are present, suggesting the establishment of secure HTTPS sessions.
HTTP traffic was also seen, meaning there was plaintext web browsing.
OCSP traffic implies certificate validation was happening.
IGMP traffic could relate to multicast services or device discovery.
