# Lab 01: Basic Network Connectivity — Solution

## Lab Info
- Level: Begginer
- Topic: Network Fundamentals
- Tool: Cisco Packet Tracer

## Goal
- Establish communication between two PCs through a switch and router.

## Topology Overview
<img width="840" height="571" alt="01-lab-topology" src="https://github.com/user-attachments/assets/730d3aa3-69ac-46df-b20c-42927b3651cc" />


## Step 1: Device Connections
| Device 1 | Port            | Device 2 | Port              | Cable Type              |
|----------|-----------------|----------|-------------------|--------------------------|
| PC-1     | FastEthernet0   | Switch   | FastEthernet0/1   | Copper Straight-Through |
| PC-2     | FastEthernet0   | Switch   | FastEthernet0/2   | Copper Straight-Through |
| Switch   | gigabitEthernet 0/1 | Router   | GigabitEthernet0/0| Copper Straight-Through |

## Step 2: IP Addressing

### PC-1 Configuration
<img width="365" height="146" alt="pc-1-conf" src="https://github.com/user-attachments/assets/4ed41dc4-ce83-42cf-b16e-0deb4edd91c6" />

### PC-2 Configuration
<img width="347" height="144" alt="pc-2-conf" src="https://github.com/user-attachments/assets/b6f7523b-4d74-4949-8995-50c1598977b1" />

## Step 3: Router Configuration
<img width="616" height="374" alt="router-conf" src="https://github.com/user-attachments/assets/03992de2-6001-49c3-9c55-9723957dd638" />

## Step 4: Connectivity Testing

### From PC-1:
<img width="437" height="180" alt="pc-1-test" src="https://github.com/user-attachments/assets/f23f25ee-3996-4f61-a55e-35f850335648" />

### From PC-2:
<img width="404" height="218" alt="pc-2-test" src="https://github.com/user-attachments/assets/bf20b514-10d4-498a-b996-ed3f98702706" />
notice how here we pinged the PC-1 and it was successful

## Results
- successful ping between PC-1 and PC-2 and towards default gateway (router)
- 0% packet loss observed

## Concepts Learned
- Devices in the same network can communicate throught a switch
- Router acts as a gateway
- Importance of correct IP addressing
- Basic CLI configuration on router




