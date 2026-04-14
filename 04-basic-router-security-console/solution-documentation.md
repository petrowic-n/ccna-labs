# Lab 04: Basic Router Security using Console

## Lab Info

- Level: Begginer
- Topic: Network Fundamentals / Basic Security
- Tool: Cisco Packet Tracer

## Goal
Set up basic passwords and security from PC using console cable to the router.

## Step 1: Connect PC-1 to the R-1 Console port

- this step is done by selecting the blue console cable and connecting it on the PC-1 to the port RS-232 and on the R-1 console port

## Step 2: Use the console connection to set up hostname R-1 on the router from the PC-1

- for this we click on the PC-1 go on the Terminal and click OK.
- next we will get the similar interface as on the routers CLI.
- we write enable to enter Privileged Mode and configure terminal to enter Global Config mode
- write the command: hostname R-1
- with this we finished this step.

## Step 3: Set the enable secret of R-1 to "ciso"

- enter the Global Conf mode and write the command: enable secret cisco
- with this we set the secret password to "cisco"

## Step 4: Set the console password of R-1 to "ccna" and make it required to connect to R-1 by the console port.

- first we write the command: line console 0
- next command we write: password ccna
- next command is: login , this means password must be used to connect to the console

## Result:

Successfully set the password and secret on the router via PC-1 using console connection.


