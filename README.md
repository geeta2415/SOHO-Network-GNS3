Project: SOHO Network Design and Simulation using GNS3
Student: Geeta
ERP: 30558
Course: Computer Communication Networks (CSE248)
Semester: Spring 2026

DRIVE LINK:
https://drive.google.com/drive/folders/1V7046m5CLCqtdFQGHHY0XTL459gGlweL

HOW TO OPEN THE PROJECT:

Install GNS3 version 2.2.x or later on Ubuntu 22.04
Open GNS3
Click File → Open Project
Navigate to this folder and select the .gns3 file
Make sure Cisco C3725 IOS image is imported in GNS3 before opening
Once opened, select all devices and click the green Play button to start
Wait for all devices to boot up (green indicators)

FOLDER STRUCTURE:
Geeta_SOHO_Network.gns3 — Main project file
project-files/ — Contains all device configurations and files
README.txt — This file

DEVICE INFORMATION:
R1 — Cisco C3725 router (LAN gateway, DHCP, NAT, ACL)
SW1 — Cisco C3725 with NM-16ESW module (Layer 2 switch)
PC1 to PC4 — VPCS virtual PCs (DHCP clients)

NETWORK DETAILS:
Network: 192.168.1.0/24
Gateway: 192.168.1.1
DHCP Pool: 192.168.1.11 to 192.168.1.100
SW1 Management IP: 192.168.1.10


SERVICES CONFIGURED:
DHCP on R1 for automatic IP assignment
NAT/PAT on R1 for internet access
ACL firewall rules on R1 WAN interface
Static default route for internet traffic


REQUIREMENTS TO RUN:
GNS3 version 2.2.x or later
Ubuntu 22.04 LTS
Cisco C3725 IOS image (c3725-adventerprisek9-mz.124-15.T14)
Minimum 4GB RAM allocated to Ubuntu VM

