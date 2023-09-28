# Smart University Packet Tracker Simulation Project

## Project Overview

This project simulates a Smart University environment with two floors, each containing four rooms equipped with various IoT devices. The network infrastructure is designed to include VLANs, inter-VLANs, firewalls, DNS services, email services, and wireless connectivity. The Packet Tracker Simulation Project aims to provide a hands-on experience in managing a complex network setup within an educational institution.

## Table of Contents

- [Project Overview](#project-overview)
- [Simulation Setup](#simulation-setup)
- [Network Components](#network-components)
- [Usage](#usage)
- [Screenshot](#screenshot)
- [Contributing](#contributing)

## Simulation Setup

### Prerequisites

- Packet Tracer: You will need Cisco Packet Tracer installed to run this simulation. You can download it from [Cisco's official website](https://www.netacad.com/courses/packet-tracer).

### Installation

1. Clone or download the project repository to your local machine.

    git clone https://github.com/your-username/smart-university-packet-tracker.git

2.  Open Cisco Packet Tracer.
    
3.  Import the project by opening the `.pkt` file provided in the repository.
    
4.  Start the simulation.
    

## Network Components

### IoT Devices

Each room is equipped with various IoT devices, including:

-   Smart Lights
-   Temperature Sensors
-   Security Cameras
-   Smart Door Locks
-   Motion Sensors
-   ...

### VLANs and Inter-VLAN Routing

The network is segmented into VLANs for better management and security. Inter-VLAN routing allows communication between different VLANs. VLANs are organized as follows:

-   VLAN 10: Administration
-   VLAN 20: Faculty
-   VLAN 30: Students
-   VLAN 40: Guests
-   ...

### Firewall

A firewall is in place to secure the network and filter traffic between VLANs. It ensures that only authorized traffic is allowed to pass through.

### DNS

A DNS server is configured to resolve domain names to IP addresses within the university network.

### Email

An email server is set up to facilitate communication within the university. Users can send and receive emails through their respective accounts.

### Wireless Connectivity

Wireless access points are deployed throughout the university to provide seamless wireless connectivity to all devices.

## Usage

1.  Open the Packet Tracer simulation.
    
2.  Explore the network topology and configurations.
    
3.  Test different scenarios, such as inter-VLAN communication, IoT device connectivity, and firewall rules.
    
4.  Experiment with the network settings and configurations to gain hands-on experience in managing a complex network environment.
    
## Screenshot

![alt text](https://github.com/FaisalBalamash/Smart-University-Packet-Tracker-Simulation-Project/blob/main/image.png?raw=true)

## Contributing

Contributions to this project are welcome. If you have suggestions, improvements, or find any issues, please open an issue or submit a pull request.
