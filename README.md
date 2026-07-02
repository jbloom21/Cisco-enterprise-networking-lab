# Cisco-enterprise-networking-lab
Cisco Packet Tracer enterprise networking lab with VLANs, DHCP, ACLs, and Router-on-a-Stick
Cisco Enterprise Network Lab

Overview

This lab was built in Cisco Packet Tracer to practice designing and
configuring a small enterprise network. The project includes multiple
VLANs, inter-VLAN routing, DHCP, access control lists, switch
security, and an internal web server.

The goal was to simulate a real business network while gaining hands-on
experience with Cisco IOS configuration and network troubleshooting.

Technologies Used

-   Cisco Packet Tracer
-   Cisco IOS CLI
-   VLANs
-   802.1Q Trunking
-   Router-on-a-Stick
-   DHCP
-   Access Control Lists
-   Switch Port Security


Network Topology

The network consists of:

 1 Cisco 2911 Router
 2 Cisco 2960 Switches
 6 Client PCs
 1 Internal Web Server
 5 VLANs


VLANs

  VLAN   Department   Subnet
  
-  10     HR           192.168.10.0/24
-  20     Sales        192.168.20.0/24
-  30     IT           192.168.30.0/24
-  40     Guest        192.168.40.0/24
-  50     Servers      192.168.50.0/24


What I Configured

-   Created separate VLANs for each department
-   Configured access ports for end devices
-   Configured trunk links between switches and the router
-   Set up Router-on-a-Stick for inter-VLAN routing
-   Configured DHCP scopes for client VLANs
-   Assigned a static IP address to the web server
-   Created ACLs to limit Guest VLAN access
-   Enabled basic switch port security
-   Shut down unused switch ports

Security

The Guest VLAN can access the internal web server but is blocked from
reaching the HR, Sales, and IT networks. This demonstrates basic network
segmentation using ACLs.

Validation

After configuring the network, I verified:

-   DHCP assigned the correct IP addresses
-   Devices could communicate between permitted VLANs
-   The web server was reachable
-   ACLs blocked unauthorized traffic
-   Switch port security was functioning as expected

Skills Practiced

-   Enterprise network design
-   IP addressing and subnetting
-   VLAN configuration
-   802.1Q trunking
-   Inter-VLAN routing
-   DHCP configuration
-   ACL implementation
-   Cisco IOS administration
-   Network verification and troubleshooting
-   Network documentation
