# Wireless Enterprise Network Design & Implementation

A simulated enterprise wireless network built with **Cisco Packet Tracer**, featuring centralized wireless management, VLAN segmentation, and authentication-related security configurations.

## Project Overview

This project focuses on designing, configuring, and testing an enterprise wireless network that supports multiple departments and device categories. It uses a Wireless LAN Controller (WLC), lightweight access points, routers, multilayer switches, and a RADIUS server to provide managed wireless connectivity across segmented network environments.

## Network Architecture

The simulated environment includes wireless networks for:

- Sales
- Finance
- Customer Service
- Management
- Guest
- IoT

Each wireless network is associated with its intended VLAN to support logical network segmentation.

**Main components:**

- Cisco routers and multilayer switches
- Wireless LAN Controller (WLC)
- Lightweight wireless access points
- RADIUS server
- DHCP services
- Wireless clients and IoT devices

## Implementation

### 1. Wireless Configuration

- Configured multiple SSIDs for different departments and device categories.
- Mapped SSIDs to their corresponding VLANs.
- Configured the WLC and lightweight access points.
- Established wireless connectivity across the simulated network.

### 2. Network Configuration

- Configured routing and switching between network segments.
- Set up DHCP services to support IP address assignment.
- Integrated the wireless infrastructure with the enterprise network.

### 3. Security Configuration

- Integrated the WLC with a RADIUS server for authentication-related services.
- Configured AAA and 802.1X authentication.
- Enabled HTTPS for secure WLC management.
- Configured WPA2/WPA3 wireless security options.

## Security Concepts Demonstrated

- **Network Segmentation:** Separating departmental and guest wireless environments using VLANs.
- **Centralized Authentication:** Using RADIUS and AAA-related configuration.
- **802.1X:** Applying port-based network access authentication concepts.
- **Secure Management:** Using HTTPS instead of HTTP for WLC management.
- **Wireless Security:** Configuring WPA2/WPA3 security options.

## Network Topology

The following image illustrates the simulated enterprise wireless network topology.



*Replace the image path above with the actual path of the topology screenshot in the repository.*

## Tools & Technologies

- Cisco Packet Tracer
- Wireless LAN Controller (WLC)
- RADIUS
- AAA
- 802.1X
- VLANs
- Routing and Switching
- DHCP
- HTTPS
- WPA2/WPA3

## Project Files

- `Wireless-Enterprise-Network.pkt` — Cisco Packet Tracer simulation file.
- `wireless-enterprise-network.png` — Network topology screenshot.

## How to Explore the Project

1. Clone or download this repository.
2. Open `Wireless-Enterprise-Network.pkt` using a compatible version of Cisco Packet Tracer.
3. Inspect the network topology, VLAN assignments, wireless configuration, and WLC/RADIUS setup.
4. Review the relevant configurations and test connectivity using the available simulation features.

## Learning Outcomes

This project provided practical experience with enterprise wireless network design, VLAN-based segmentation, centralized wireless management, authentication concepts, and basic wireless access security.

## Disclaimer

This is an educational network simulation created in Cisco Packet Tracer. Feature availability and protocol behavior may vary depending on the Packet Tracer version and supported device models. Configurations described here reflect the project implementation as documented; this repository does not claim production deployment or independent security certification.
