## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 15.10.26		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1903" height="1180" alt="Screenshot 2026-10-15 222113" src="https://github.com/user-attachments/assets/bd35e6fc-71cd-4898-81b8-8548dd0b6afc" />


________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)

<img width="1908" height="1187" alt="Screenshot 2026-10-15 221756" src="https://github.com/user-attachments/assets/eae27f5b-3ab1-4dcb-a57a-b7fd7d682ef3" />
<img width="1917" height="1197" alt="Screenshot 2026-10-15 221823" src="https://github.com/user-attachments/assets/6e55e582-2013-4e35-be5e-3f58809b5f80" />
<img width="1890" height="1188" alt="Screenshot 2026-10-15 221847" src="https://github.com/user-attachments/assets/02ebb50f-3ac4-408e-9bdd-efccc802ba88" />
<img width="1888" height="1165" alt="Screenshot 2026-10-15 222042" src="https://github.com/user-attachments/assets/6cbaa8ef-8b06-4e43-9e6e-13074e45a32e" />
<img width="1903" height="1180" alt="Screenshot 2026-10-15 222113" src="https://github.com/user-attachments/assets/f5d25f60-4704-4ce5-bb32-ea9db40f8b71" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
