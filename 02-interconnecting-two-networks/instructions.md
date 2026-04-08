# Lab 02: Interconnecting Two Networks

## Lab info

- Level: Begginer
- Topic: Network Fundamentals / Routing Basics
- Tool: Cisco Packet Tracer

## Objective
The goal of this lab is to connect two separate networks and enable communication between them using a router.

By completing this lab, I practiced:
- Designing multiple networks
- Assigning IP addresses to different subnets
- Configuring router interfaces
- Verifying communication between networks
- Routing using RIP

## Topology
<img width="1421" height="623" alt="lab-02-topology" src="https://github.com/user-attachments/assets/e5f0e17b-9ee1-4692-b7d0-1958999f7623" />

## Network Design
| Network  | Subnet          | Devices        | Default Gateway |
|----------|-----------------|----------------|----------------|
| Right Network  | 192.168.10.0/24   | PC-1, PC-2| 192.168.10.1
| HR-PC2   | 192.168.11.0/24   | PC-3, PC-4| 192.168.11.1

## Requirements

- Build the network topology
- Create Two separate LAN's and connect them
- Configure Routers routing using RIP
- Verify Connectivity by pinging from different networks

## Success Criteria
- Devices within the same network can communicate
- Devices accross different networks can communicate via the router
- No packet loss during testing


