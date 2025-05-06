# Basic VLAN and DHCP Server
This simulation demonstrates the creation of a simple network with VLAN and DHCP configurations, and it also illustrates how subnetting works.

VLAN (Virtual Local Area Network) is a method used to partition a single physical network into multiple virtual networks, even if they are connected to the same switch.

DHCP (Dynamic Host Configuration Protocol) is a network protocol that enables a server to automatically assign IP configuration settings, such as IP address, subnet mask, gateway, and DNS to devices connected to the network. This differs from static IP configuration, which requires manual assignment of IP address, subnet mask, gateway, and DNS on each client device.

Subnetting is the process of dividing a large IP network into smaller, more manageable sub-networks (subnets). It improves IP address utilization, enhances security, reduces network congestion, and simplifies management by isolating parts of the network. For example, the original IP network 192.168.1.0/24 has 256 addresses and can be subnetted by increasing the subnet prefix. Increasing the prefix by 1 to /25 divides the network into 2 subnets.

## Simulator Used
1. Cisco Packet Tracer
2. GNS3 (MikroTik)

## Requirement Nodes
1. A router and a switch
2. Client PCs
3. Access Point and Client Wireless devices*

*) optional if creating a WLAN connection, but can be replaced with a regular LAN (Client PCs)

## Configuration Done
1. Divide into 4 VLANs on routers and switches
2. Assign an ip address to the router that will be the gateway for each VLAN and client
3. DHCP server on router
4. SSID and password on a Access Point (for WLAN connection)

## VLAN and DHCP Server
### Cisco

![Basic VLAN + DHCP Server (1).png](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/Cisco/Basic%20VLAN%20%2B%20DHCP%20Server%20(1).png)

[Project File Link (Packet Tracer)](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/Cisco/Basic%20VLAN%20%2B%20DHCP%20Server.pkt)

The DHCP results of the representative VLAN are as follows:

![Basic VLAN + DHCP Server (2).png](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/Cisco/Basic%20VLAN%20%2B%20DHCP%20Server%20(2).png) ![Basic VLAN + DHCP Server (3).png](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/Cisco/Basic%20VLAN%20%2B%20DHCP%20Server%20(3).png) ![Basic VLAN + DHCP Server (4).png](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/Cisco/Basic%20VLAN%20%2B%20DHCP%20Server%20(4).png) ![Basic VLAN + DHCP Server (5).png](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/Cisco/Basic%20VLAN%20%2B%20DHCP%20Server%20(5).png)

### MikroTik

![Basic VLAN + DHCP Server (MikroTik).png](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/MikroTik/Basic%20VLAN%20%2B%20DHCP%20Server%20(MikroTik).png)

[Project File Link (GNS3)](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/MikroTik/Basic%20VLAN%20%2B%20DHCP%20Server%20(MikroTik).gns3project.rar) (extract the file first)

The DHCP results of the representative VLAN are as follows:

![Basic VLAN + DHCP Server (MikroTik) (1).png](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/MikroTik/Basic%20VLAN%20%2B%20DHCP%20Server%20(MikroTik)%20(1).png) ![Basic VLAN + DHCP Server (MikroTik) (2).png](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/MikroTik/Basic%20VLAN%20%2B%20DHCP%20Server%20(MikroTik)%20(2).png) ![Basic VLAN + DHCP Server (MikroTik) (3).png](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/MikroTik/Basic%20VLAN%20%2B%20DHCP%20Server%20(MikroTik)%20(3).png) ![Basic VLAN + DHCP Server (MikroTik) (4).png](https://github.com/eightball270/Basic-VLAN-and-DHCP-Server/blob/main/MikroTik/Basic%20VLAN%20%2B%20DHCP%20Server%20(MikroTik)%20(4).png)
