# Lab 02: Interconnecting Two Networks - Solution

## Lab Info

- Level: Begginer
- Topic: Network Fundamentals
- Tool: Cisco Packet Tracer

## Goal
Establish connection between two different networks.

## Step 1: IP Addressing

- IP address pool for right network set: 192.168.10.0/24
- IP address pool for left network set: 192.168.11.0/24

## Step 2: Router Configurations

### R-1:

<img width="305" height="232" alt="R-1" src="https://github.com/user-attachments/assets/289a1a2e-0a13-4117-81af-4ad9ed53a7fa" />
- interface gigabitEthernet 0/0 set as default gateway with ip address: 192.168.10.1
- interface gigbitEthernet 0/1 set ip address: 1.1.1.1 with subnet mask 255.255.255.0, this port is used for communication between two networks (routers).

### R-2:
![R-2 PNG](https://github.com/user-attachments/assets/e9b2574e-f2bf-4722-8d2f-ffd786132ed7)
- interface gigabitEthernet 0/0 set as default gateway with ip address: 192.168.11.1
- interface gigbitEthernet 0/1 set ip address: 1.1.1.2 with subnet mask 255.255.255.0, this port is used for communication between two networks (routers).

On both routers RIP routing protocol is used.

## Results

- Succesful connectivity (ping) between devices on the same and different networks.

## Key Concepts Learned
- Devices in the same network can communicate through a switch
- RIP routing configuration on a routers

## Verification
![verify](https://github.com/user-attachments/assets/fb6fe53c-d1ac-4d94-8da7-f3c4743e1e4c)
- successfully pinged PC3 device from PC-2
