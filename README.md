# University_Network
Network design for IT and department blocks
# University Network Design Project

This repository contains the network design for the new IT Centre and Department Building at the University. The design includes a detailed network plan, subnet and VLAN configurations, and WiFi access point configurations for optimal coverage and security.

## Project Overview

The University has recently constructed two new buildings – an IT Centre and a Department Block – which house discussion rooms, department offices, lecture halls, laboratories, meeting rooms, and computer labs. This project provides a network design for these buildings, ensuring optimal use of IP addresses and secure, segmented network access.

### Building Dimensions
- Building Floors: 2-story building
- Length: 70 meters
- Width: 30 meters
- Height per Floor: 4 meters

### Network Requirements
The design includes IP address allocation, VLANs, and subnets for various rooms and facilities across both buildings. Key requirements include:

1. IP Address Range: 10.20.0.0/16
2. Separate Network Segments: Secure segmentation for rooms and labs with restricted access.
3. WiFi Coverage: Dedicated WiFi access points for specific areas such as meeting rooms and lobby areas.

## Components

### IT Centre Block
- Director’s Office: 2 computers
- Network Manager Room: 1 computer
- Technical Officers Room: 2 computers
- Staff Office: 5 computers
- Meeting Room: WiFi and 2 data points for video conferencing
- Lobby: WiFi coverage
- Computer Labs: 2 labs with 60 computers each
- Digital Learning and Media Centre: 30 computers + 1 printer
- Printing Room: 2 printers

### Department Block
- Lecture Halls: 4 halls, each with a desktop and multimedia projector
- Staff Rooms: 14 rooms, each with a computer
- Technical Officers Room: 4 computers
- Meeting Room: WiFi and 2 data points
- Computer Labs: 2 labs with 50 computers each
- Network Engineering Lab: 10 computers
- Microprocessor Lab: 12 computers
- Computer Vision and Machine Learning Lab: 50 computers
- Department Office: 2 computers + 1 printer

### Network Security and Access Control
- Restricted access for computers in staff rooms, department office, and specific labs.
- Printers in the IT Centre and Department Office are restricted to authorized staff.
- VLANs are used to isolate different network segments, maintaining security across departments.

## Network Configuration

The configuration includes detailed settings for routers, switches, and WiFi access points. Each subnet and VLAN has been assigned IP addresses based on the available range (10.20.0.0/16).

### Subnet and VLAN Allocation
The IP allocation for each section is detailed as follows:
- IT Centre Block:
- 
- Department Block: [List of subnets and IP ranges]

### Steps to Configure Routers and Switches
1. Router Configuration: Basic steps for setting up router IP addresses, VLAN routing, and security settings.
2. Switch Configuration: Steps for VLAN creation, port assignment, and trunk configuration.
3. WiFi Access Points: Details on setting up SSIDs, IP allocation via DHCP, and configuring access controls.

## Files in This Repository

- `Network Design Report.pdf`: Full report on the network design, including diagrams, subnet allocations, and configuration steps.
- `Cisco Configuration File`: Configuration file for Cisco equipment, detailing switch and router setup.

## Reflection

This project demonstrates the setup and configuration of a secure, segmented network for educational institutions. Key networking components used include switches, routers, and wireless access points, allowing for effective communication and secure access control.

## Author

Asra S.A.F
University Network Design Project  

