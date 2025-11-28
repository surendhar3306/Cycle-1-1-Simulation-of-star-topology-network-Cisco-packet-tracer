# Cycle-1-----1-Simulation-of-star-topology-network
# 🖧 Network Simulation using Cisco Packet Tracer

## 🎯 AIM
To simulate a network with topology using Cisco Packet Tracer and verify connectivity between computers using ICMP.

## 🛠️ EQUIPMENTS REQUIRED
- Desktop Computer  
- Cisco Packet Tracer 5.0 Software

## 📍 IP ASSIGNMENT

| NAME | IP ADDRESS     | SUBNET MASK     | NETWORK     | CLASS   |
|------|----------------|-----------------|-------------|---------|
| PC0  | 192.168.1.10   | 255.255.255.0   | 192.168.1.1 | Class C |
| PC1  | 192.168.1.30   | 255.255.255.0   | 192.168.1.1 | Class C |
| PC2  | 192.168.1.20   | 255.255.255.0   | 192.168.1.1 | Class C |
| PC3  | 192.168.2.20   | 255.255.255.0   | 192.168.1.2 | Class C |
| PC4  | 192.168.2.30   | 255.255.255.0   | 192.168.1.2 | Class C |
| PC5  | 192.168.2.10   | 255.255.255.0   | 192.168.1.2 | Class C |

## ⚙️ PROCEDURE

1. Open Cisco Packet Tracer software.  
2. Drag a 2950 Switch from the toolbar and drop it into the workspace.  
3. Drag a PC terminal from the toolbar and drop it into the workspace.  
4. Repeat Step 3 to add four more terminals.  
5. Select Copper Straight-Through cable and connect each PC to the 2950 switch using different ports.  
6. Click on each PC, select the Fast Ethernet interface, and assign the IP address and subnet mask.  
7. Repeat Step 6 for all PC terminals.  
8. Open the Terminal tab from the Desktop section of each PC and verify connectivity using the `ping` command.  
9. Use “Add Simple PDU” from the toolbar to test connectivity between source and destination PCs.

## 📊 IP CONNECTIVITY TABLE

<img width="979" height="228" alt="Screenshot 2025-11-05 155901" src="https://github.com/user-attachments/assets/22628a02-3f8d-42ce-816e-220f3cc0abde" />
## 🗺️ NETWORK DIAGRAM
---
<img width="1013" height="587" alt="image" src="https://github.com/user-attachments/assets/044f0f4d-db42-4fb3-842e-ac8bbf82110e" />


## 🧾 BASIC NETWORKING COMMANDS

## IP Configuration
## IP Configuration Details: 
## (i)	ipconfig Command(windows OS) (or) ifconfig command(Linux OS) Syntax: C:\> ipconfig 
## (ii)	ipconfig/all Command:
## Syntax:
C:\> ipconfig /all 
## Testing Connectivity: 
## (i)	Self Ping Command:
## Syntax:
## c:\> ping <ipaddress> Example:
## C:\> ping 172.17.80.201
## C:\> ping 127.0.0.1 (ii) Ping to Destination Syntax:
## c:\> ping <destination-ipaddress> Example:
## C:\ping 172.17.80.1
## To Display IP to Physical address Translation Table and trace the route
## i) Arp Command Syntax:
 
## C:\arp –a
## (ii)	To trace the route Syntax:
## C:\tracert <ipaddress (or) specific address> Example: C:\tracert 172.17.80.1
## C:\tracert www.saveetha.ac.in

## OUTPUT
---
<img width="1014" height="622" alt="image" src="https://github.com/user-attachments/assets/ce9c7920-a272-44cb-bd08-3a9599d635ba" />

## RESULT
Thus the computers in same network are able to communicate with each other and the communication between them were verified
