# Network Infrastructure Discovery & Topology Analysis

## Project Overview
This project focuses on discovering and analyzing a local network environment using basic Linux networking commands. The objective is to identify IP addresses, the default gateway, and understand how devices communicate within a network.

## Objectives
- Identify network interfaces and IP addresses.
- Find the default gateway and routing information.
- Test internet connectivity.
- Understand ARP and MAC address mapping.
- Create a simple network topology diagram.

## Commands Used

### 1. View Network Interfaces
```bash
ip addr
```

### 2. View Routing Table
```bash
ip route
```

### 3. Test Connectivity
```bash
ping -c 4 8.8.8.8
```

### 4. View ARP Table
```bash
arp -a
```

## Findings

- Kali VM IP Address: `10.0.2.15`
- Network Interface: `eth0`
- Default Gateway: `10.0.2.2`
- Gateway MAC Address: `52:54:00:12:35:00`
- Internet Connectivity: Successful (0% packet loss)

## Network Topology

```text
Internet
    |
VirtualBox NAT Gateway (10.0.2.2)
    |
Kali Linux VM (10.0.2.15)
```

## Concepts Learned
- IP Addressing
- Network Interfaces
- Default Gateway
- Routing
- ARP (Address Resolution Protocol)
- Basic Network Topology Analysis

## Conclusion
This project helped in understanding how a Linux system communicates on a network, how to identify network information, and how routing and ARP work in a virtualized environment.

---
**Author:** Nida Kanwal
**Platform:** Kali Linux (VirtualBox)
