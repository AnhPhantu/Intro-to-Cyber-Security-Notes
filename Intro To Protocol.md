# Intro to Protocol
Protocol notes that is important

## Protocol
 SSL and TLS (Secure Socket Layer and Transport Layer Security)
 - TLS procide encryption and authentication for client - server connection, it provide the "secure" part of many service. SSL was founded in 1995 by Netscape, the standard is refer to as TLS
 
SSH (Secure Shell)
- Provide a a secure channel for shell and other connection, as well as other protocol. Replacement of Telnet, rsh, 

IPsec (Internet  Protocol Security)
- Provide authentication, integrity and encryption for IP traffic, has two mode. Transport mode only encrypt the packet payload, the tunnel mode encrypted the entire IP packet and carries it as another payload 

AH (Authentication Header)
- used when we only wanted to ensure the authenticity of the traffic

ESP (Encapsulating Security Payload)
- provides authentication and encryption

Keberos
- Provides single sign on authentication, and used ticket to authenticates client for access to service

Secure Email
- Digital Signature: Ensures the fact that the email was sent by the person who sent it, Encryption: Only the person who was intended to received the email can read it

Virtual Private Network
- Allows a secure connection through an untrusted network, like an "encrypted tunnel". Its site to site and remote client modes. Has L2TP, SSL, IPSec, AES as encryption protocol 
