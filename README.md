# Computer-network-project
Ayomide Ayotola · CSCE 3530 — Computer Networks · Final Project (July 2026)

A small virtual client-server network built and tested in Cisco Packet Tracer, demonstrating the core protocols of the TCP/IP stack working together on a single private subnet.

Overview

The network runs on the private subnet 192.168.1.0/24. A router provides the default gateway and performs NAT toward an external "internet" node; a layer-2 switch connects the internal devices; one server hosts DHCP and DNS, another hosts a web page, and three client PCs receive their addressing automatically via DHCP.

Protocols demonstrated


DHCP — automatic IP/mask/gateway/DNS assignment to clients
DNS — hostname resolution (www.mynet.local → 192.168.1.3)
HTTP — web page served to client browsers
NAT — private LAN addresses translated to the router's outside address
ICMP — connectivity and path testing (ping, traceroute)
ARP — MAC address discovery on the local segment
TCP / UDP — reliable vs. connectionless transport, observed in packet capture

Repository contents:
AyotolaNetwork.pkt
Networks Project_Ayomide.pdf
Top graph.pdf

How to open

Open AyotolaNetwork.pkt in Cisco Packet Tracer 8.x (free with a Cisco Networking Academy account). Switch to Simulation mode to step through traffic packet by packet.
