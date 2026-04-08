# Lab 03: Basic Router Security - Solution

## Lab Info
- Level: Begginer
- Topic: Network Fundamentals
- Tool: Cisco Packet Tracer

## Step 1
- Connect R1 and R2 by their GigabitEthernet0/0 interfaces

Answer:
![03-lab-topology](https://github.com/user-attachments/assets/d144aa8e-5df9-430e-a32a-a23434f2d639)

## Step 2
- Set the hostnames according to the diagram

Answer: for this we use command to set the hostname on the routers:
hostname R-1 

## Step 3
- Set the enable password on each router to cisco

Answer: go to Global Exec mode and write this command:
enable password cisco

## Step 4
- View the password in running config is it encrypted?

Answer: password is not encryped because we did not set the encryption yet

## Step 5
- Enable password encryption on each router

Answer:
- go to Global exec mode and write this command:
service password-encryption

Step 6 and 8 are already covered

## Step 7
- disable password encryption on each router

Answer:
- we use command:
no service password-encrpytion

If we check running config we will see password is not decrypted because it is for all future passwords.


