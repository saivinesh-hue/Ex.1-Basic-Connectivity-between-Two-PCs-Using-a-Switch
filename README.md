## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 10/10/26

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

Insert the network topology from Packet Tracer (Screenshot or drawing)

<img width="398" height="307" alt="Screenshot 2026-10-22 151130" src="https://github.com/user-attachments/assets/8d7b0176-e4d6-45aa-9b60-a72bc2462f28" />

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

Insert screenshots showing ping success, configuration, or simulation results.

<img width="1911" height="1078" alt="Screenshot 2026-10-10 102739" src="https://github.com/user-attachments/assets/3dfbfb17-63bc-4867-8c74-c23198e8a9c1" />

<img width="1896" height="1078" alt="Screenshot 2026-10-10 102807" src="https://github.com/user-attachments/assets/5c0f9d2d-06a1-4f70-b323-8a569642df04" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
