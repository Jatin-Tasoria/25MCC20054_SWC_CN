# Learning Summary 🚀

Over the past week, I focused on building a solid understanding of Computer Networks and the technologies that make modern communication possible. Instead of only learning definitions, I explored how devices identify each other, exchange information, and communicate across local and global networks. This journey helped me connect theoretical networking concepts with real-world use cases.

### Topics Covered

- Computer Network Fundamentals
- Networking Devices
- OSI Model
- IPv4 Addressing
- TCP and UDP Protocols
- DNS (Domain Name System)
- Subnetting
- IP Address Classes

Along with these concepts, I also gained a better understanding of how networks are designed, managed, and secured in practical environments.

---

# Computer Networks

## Introduction

A computer network is a collection of interconnected devices that communicate and exchange information with one another. These devices can be connected through wired technologies such as Ethernet or wireless technologies such as Wi‑Fi.

## Why Are Computer Networks Important?

Networks make collaboration and communication much easier. They allow users to share resources, transfer files, access internet services, and communicate efficiently across different locations.

### Common Examples

- The Internet
- Home Wi‑Fi Networks
- Office Networks
- Mobile Data Networks

## Types of Computer Networks

### 1. LAN (Local Area Network)

A LAN connects devices within a limited area such as a home, school, or office and provides high-speed communication.

### 2. MAN (Metropolitan Area Network)

A MAN interconnects multiple LANs across a city or metropolitan region.

### 3. WAN (Wide Area Network)

A WAN spans very large geographic areas and connects devices across countries and continents. The Internet is the largest WAN in existence.

## Key Components

- **Router** – Connects multiple networks and directs traffic between them.
- **Switch** – Connects devices within the same network.
- **Server** – Provides services or resources to clients.
- **Client** – Requests services from a server.
- **Network Cable** – Enables wired communication.

## Advantages

- Easy resource sharing
- Faster communication
- Centralized management
- Access to online services
- Improved collaboration

## Limitations

- Security concerns
- Maintenance requirements
- Possible network outages
- Malware propagation risks

## Conclusion

Computer networks form the backbone of modern digital communication and enable information sharing across the world.

---

# Networking Devices

Networking devices are specialized hardware components that help establish communication between systems and ensure smooth data transmission.

## Common Devices

### Router
Routes packets between different networks and commonly provides internet connectivity.

### Switch
Connects devices within a network and forwards data to the intended destination.

### Hub
Broadcasts incoming data to all connected devices.

### Modem
Converts signals to establish communication with an ISP.

### Repeater
Boosts weak signals to extend network coverage.

## Conclusion

These devices work together to build reliable and scalable network infrastructures.

---

# OSI Model (Open Systems Interconnection)

## Introduction

The OSI Model is a conceptual framework that explains how data moves from one device to another. It divides communication into seven layers, making networking easier to understand and troubleshoot.

+---------------------------+
| 7. Application Layer      |
+---------------------------+
| 6. Presentation Layer     |
+---------------------------+
| 5. Session Layer          |
+---------------------------+
| 4. Transport Layer        |
+---------------------------+
| 3. Network Layer          |
+---------------------------+
| 2. Data Link Layer        |
+---------------------------+
| 1. Physical Layer         |
+---------------------------+

*Note:* From reciever side.

## Benefits of the OSI Model

- Simplifies networking concepts
- Improves troubleshooting
- Promotes interoperability
- Separates responsibilities into layers

## Conclusion

The OSI Model provides a structured way to understand end-to-end communication across networks.

---

# IPv4 (Internet Protocol Version 4)

## Introduction

IPv4 is the most widely used addressing protocol in networking. Every connected device receives a unique address that allows it to send and receive information.

### Example Address

192.168.1.10

## Features

- 32-bit addressing
- Four octets
- Supports public and private addressing
- Widely adopted worldwide

## Advantages

- Easy implementation
- Broad compatibility
- Mature technology

## Limitations

- Address exhaustion
- Limited security features
- Scalability challenges

## Conclusion

IPv4 remains one of the foundational technologies of modern networking.

---

# TCP and UDP

## TCP

TCP is a reliable, connection-oriented protocol that guarantees ordered and accurate delivery of data.

### Common Uses

- Web browsing
- Email
- File transfer
- Online banking

## UDP

UDP is a lightweight, connectionless protocol optimized for speed and low latency.

### Common Uses

- Online gaming
- Live streaming
- Voice communication
- Real-time broadcasts

## Comparison

| Feature | TCP | UDP |
|----------|-----|-----|
| Connection | Required | Not Required |
| Reliability | High | Lower |
| Speed | Slower | Faster |
| Ordering | Guaranteed | Not Guaranteed |

## Conclusion

TCP prioritizes reliability, while UDP prioritizes speed and efficiency.

---

# DNS (Domain Name System)

## Introduction

DNS acts like the internet's directory service. It converts easy-to-remember domain names into IP addresses that computers can understand.

### Example

google.com → 142.250.195.100

## Benefits

- Easy website access
- No need to memorize IP addresses
- Faster navigation
- Supports web and email services

## Conclusion

DNS makes the internet more user-friendly by translating human-readable names into machine-readable addresses.

---

# Subnetting

## Introduction

Subnetting is the technique of dividing a large network into smaller and more manageable subnetworks.

## Benefits

- Efficient IP utilization
- Better performance
- Enhanced security
- Easier administration

### Example

Main Network:
192.168.1.0/24

Subnets:
- 192.168.1.0/26
- 192.168.1.64/26
- 192.168.1.128/26
- 192.168.1.192/26

## Conclusion

Subnetting improves organization, performance, and scalability in computer networks.

---

# IP Address Classes

## Overview

IPv4 addresses are grouped into different classes based on network size and purpose.

| Class | Range | Purpose |
|---------|---------|---------|
| A | 1–126 | Large Networks |
| B | 128–191 | Medium Networks |
| C | 192–223 | Small Networks |
| D | 224–239 | Multicast |
| E | 240–255 | Research |

*Note:* 127 is reserved for loopback addresses, allowing a device to communicate with itself(LocalHost).

## Easy Reminder

- A → Large Networks
- B → Business Networks
- C → Common Networks
- D → Multicast Data
- E → Experimental Use

## Conclusion

IP address classes help organize IPv4 networks according to scale and usage requirements.