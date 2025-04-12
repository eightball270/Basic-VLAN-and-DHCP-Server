# Basic-VLAN-and-DHCP-Server
In this practice, creating a simple network with VLAN and DHCP configuration. 

VLAN (Virtual Local Area Network) is a way to partition one physical network into several different virtual networks even though they are connected to the same switch.

DHCP (Dynamic Host Configuration Protocol) is a network protocol that allows a server to automatically assign IP configuration (IP address, subnet mask, gateway, DNS) to devices connected to the network. This differs from static IP address configuration which assigns IP address, subnet mask, gateway and DNS manually into the client devices.

## Technology Used
1. Cisco Packet Tracer v8.2.2
2. GNS3 (MikroTik)

## Requirements
1. A router and a switch
2. Client PCs
3. Access Point and Client Wireless devices*

*) optional if creating a WLAN network, but can be replaced with a regular LAN (Client PCs)

## Configuration Completed
1. Divide into 4 VLANs on routers and switches
2. Assign an ip address to the router that will be the gateway for each VLAN and client
3. DHCP server on router
4. SSID and password on a Access Point (for WLAN network)

## VLAN and DHCP Server
### Cisco

![Basic VLAN + DHCP Server (1).png](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/Basic%20VLAN%20%2B%20DHCP%20Server%20(1).png)

The DHCP results of the representative VLAN are as follows:

![Basic VLAN + DHCP Server (2)](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/Basic%20VLAN%20%2B%20DHCP%20Server%20(2).png) ![Basic VLAN + DHCP Server (3)](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/Basic%20VLAN%20%2B%20DHCP%20Server%20(3).png) ![Basic VLAN + DHCP Server (4)](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/Basic%20VLAN%20%2B%20DHCP%20Server%20(4).png) ![Basic VLAN + DHCP Server (5)](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/Basic%20VLAN%20%2B%20DHCP%20Server%20(5).png)
