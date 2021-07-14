# Network-scanner
in this repo i will be creating my own network scanner in python 
A Network Scanner is a common tool utilized to examine hosts that are available on the network.
There are two standard techniques for scanning the network which are-
# ICMP Echo request 
it is also known as 'Ping command'. An ICMP packet is sent to a host using the IP address and if the ICMP echo is received, that means that the host is online and is receiving the signals. For this, it necessary to get all the IP addresses for which you wish to test that the host is connected or not. This method works on the assumption that network devices have ICMP enabled.

# TCP Scan
To overcome the demerits of echo request method, TCP scan method is introduced which works on three-way handshake method. This method has a pre-assumption that the hosts on the networks are open ports and we have to guess which port is open or not. The ports differ in the operating system in which you are using.

3-way-Handshake method
A three-way handshake is a method used in a TCP/IP network to create a connection between a local host/client and server. It is a three-step method that requires both the client and server to exchange SYN and ACK (acknowledgment) packets before actual data communication begins.
A three-way handshake is primarily used to create a TCP socket connection. It works when:

A client node sends an SYN data packet over an IP network to a server on the same or an external network. The objective of this packet is to ask/infer if the server is open for new connections.
The target server must have open ports that can accept and initiate new connections. When the server receives the SYN packet from the client node, it responds and returns a confirmation receipt – the ACK packet or SYN/ACK packet.
The client node receives the SYN/ACK from the server and responds with an ACK packet.
