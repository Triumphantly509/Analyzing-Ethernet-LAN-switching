# Analyzing-Ethernet-LAN-switching

## Objective
The objective of this project is to explore and analyze the fundamental concepts of Ethernet LAN switching, including frame forwarding, MAC address learning, and switching behavior within a local area network. Through practical lab analysis and simulation, the project demonstrates how switches build MAC address tables, forward frames efficiently, and maintain reliable communication between devices in a switched network environment.

## Skills learned
- MAC address table learning
- Ethernet frame forwarding and filtering
- Broadcast and unknown unicast behavior
- LAN switching fundamentals
- Network analysis through simulation labs

## Tools used
- Cisco Packet Tracer for network simulation
- Layer 2 Ethernet switching technologies
- Switch CLI for configuration and troubleshooting
- Network topology design and analysis

## Lab Topology
<img width="600" alt="image" src="https://github.com/user-attachments/assets/7a47b5ee-4dbf-481f-bae5-02fb90bfd5f5" />

## Arp request
<img width="600" alt="image" src="https://github.com/user-attachments/assets/5be3f1d8-d664-42e5-865a-0c1fbfb97c76" />

PC0 wants to send data to 192.168.1.3, PC0 already knows the source IP adress: 192.168.1.3 and the destination IP address: 192.168.1.3, but Ethernet communication requires MAC address
and PC0 does not know the MAC address of 192.168.1.3
So PC0 send an ARP Request.
Src IP: 192.168.1.1
Dst IP: 192.168.1.3
Src MAC: 02CF.B011.9D00
Dst MAC: FFFF.FFFF.FFFF
This is a broadcast meaning everyone in this network, please listen, who has the IP 192.168.1.3?
Tell 192.168.1.1


