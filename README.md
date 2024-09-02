# Networking Lab Project

## Overview

This project is a comprehensive exploration of essential networking concepts, including IPv4 and IPv6 addressing, routing protocols, VLAN configuration, and network planning strategies. The lab was conducted using industry-standard equipment such as Cisco 7200 routers and Cisco 3725 Ethernet switches. Through hands-on exercises, this project aims to provide practical experience in network design, configuration, and optimization, equipping participants with the necessary skills to manage complex networking environments.

## Table of Contents

1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Lab Setup](#lab-setup)
4. [Addressing and Network Planning](#addressing-and-network-planning)
5. [Routing Protocols](#routing-protocols)
6. [VLAN Configuration](#vlan-configuration)
7. [IPv6 Transition](#ipv6-transition)
8. [Results and Observations](#results-and-observations)
9. [Conclusion](#conclusion)
10. [References](#references)

## Introduction

This lab project provides an in-depth understanding of networking fundamentals, focusing on the implementation and configuration of IPv4 and IPv6 addressing schemes, routing protocols, and VLANs. The project involves setting up and configuring network devices in a simulated environment to reflect real-world scenarios.

## Objectives

- Develop an IPv4 and IPv6 addressing plan tailored to specific network requirements.
- Gain practical experience with configuring Cisco 7200 routers and Cisco 3725 Ethernet switches.
- Implement VLANs to isolate network traffic and enhance security.
- Configure and compare routing protocols (BGP, OSPF, RIP) to optimize network performance.
- Transition from IPv4 to IPv6, addressing the challenges of IP address depletion.

## Lab Setup

The lab environment was simulated using GNS3, where Cisco 7200 routers and Cisco 3725 Ethernet switches were deployed. The network topology was designed to reflect typical enterprise network setups, including multiple autonomous systems, internal and external links, and loopback interfaces.

### Equipment Used

- Cisco 7200 Routers
- Cisco 3725 Ethernet Switches
- GNS3 Network Simulator

### Topology

The network topology consists of two autonomous systems, Nextel (AS 20001) and Telstar (AS 4010), interconnected with each other and with external networks. The topology includes internal and external links, loopback interfaces, and VLANs for traffic segmentation.

## Addressing and Network Planning

The project involved designing efficient IP addressing plans for both IPv4 and IPv6:

- **IPv4 Addressing**: Subnetting strategies were employed using /30 and /29 masks for internal and external links, respectively, to optimize IP address usage.
- **IPv6 Addressing**: IPv6 prefix allocation and subnetting were performed to facilitate the transition from IPv4, ensuring scalability and future-proofing the network.

Each router interface was configured with specific IP addresses according to the addressing plan, ensuring that all network segments were correctly addressed.

## Routing Protocols

The lab explored the configuration of several routing protocols:

- **BGP (Border Gateway Protocol)**: Configured for inter-AS routing to ensure optimal path selection and policy-based routing between autonomous systems.
- **OSPF (Open Shortest Path First)**: Implemented within each AS to facilitate dynamic intra-AS routing and ensure quick convergence.
- **RIP (Routing Information Protocol)**: Configured for comparison purposes, highlighting its simplicity and limitations in large, complex networks.

Routing tables were configured and validated to ensure proper communication across the network.

## VLAN Configuration

VLANs were configured on Cisco 3725 Ethernet switches to segregate network traffic and improve security within the network. VLANs were implemented with a /25 mask to accommodate future expansion of up to 100 hosts per VLAN.

## IPv6 Transition

With the depletion of IPv4 addresses, the lab emphasized the transition to IPv6:

- **Address Planning**: IPv6 addressing plans were developed using prefix delegation and subnetting strategies.
- **Configuration**: IPv6 was configured on routers, ensuring seamless communication alongside existing IPv4 networks.

The lab provided practical experience in addressing the challenges associated with IPv4 to IPv6 transition, including dual-stack implementation and routing configuration.

## Results and Observations

Throughout the lab exercises, the following key outcomes were observed:

- Successful implementation of efficient IP addressing schemes, minimizing wastage and ensuring scalability.
- Effective configuration of VLANs, leading to improved network segmentation and security.
- Comparison of routing protocols demonstrated the strengths and weaknesses of each, with OSPF emerging as the most suitable for intra-AS routing.
- The transition to IPv6 was successfully achieved, highlighting the importance of planning and the challenges involved.

## Conclusion

This project provided valuable hands-on experience in network planning, configuration, and optimization. The practical application of IPv4 and IPv6 addressing, VLAN configuration, and routing protocols has enhanced the understanding of complex networking concepts, preparing participants for real-world networking challenges.

## References

- Cisco Systems, Inc. "Cisco 7200 Series Routers."
- Cisco Systems, Inc. "Cisco 3725 Ethernet Switches."
- GNS3 Documentation: https://docs.gns3.com/
- "IPv6 Addressing and Basic Configurations," Cisco Networking Academy.

