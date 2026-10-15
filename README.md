## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 15-10-2026		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="772" height="722" alt="image" src="https://github.com/user-attachments/assets/8ea79301-50a8-4de7-b724-be4fd60e7200" />


Insert the network topology from Packet Tracer (Screenshot or drawing)

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
<img width="984" height="444" alt="Screenshot 2026-10-15 173503" src="https://github.com/user-attachments/assets/50fd4aea-df37-4a9b-a6e6-147f291689a7" />

<img width="960" height="752" alt="Screenshot 2026-10-15 173518" src="https://github.com/user-attachments/assets/f28f341d-273a-47aa-b975-f3eff9f0e932" />

<img width="1918" height="1019" alt="Screenshot 2026-10-15 173408" src="https://github.com/user-attachments/assets/dbd614fc-fe98-4876-8ae0-8c2f6a3e28f0" />

Insert screenshots showing ping success, configuration, or simulation results.
________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
