# **Networking Notes**

## **Difference Between TCP/IP Layers and OSI Layers**

| Feature          | TCP/IP Model | OSI Model |
|-----------------|-------------|-----------|
| Number of Layers | 4           | 7         |
| Layers | Application, Transport, Internet, Network Access | Application, Presentation, Session, Transport, Network, Data Link, Physical |
| Developed By | DARPA (Defense Advanced Research Projects Agency) | ISO (International Organization for Standardization) |
| Usage | Used in real-world internet communication | Mainly theoretical and conceptual |
| Protocol Dependency | Protocol-specific | Protocol-independent |
| Examples | HTTP, TCP, IP, Ethernet | FTP, TCP, IP, Ethernet |

## **8P8C Connector or RJ45**
- **8P8C (8 Position 8 Contact)** is the modular connector used in networking.
- RJ45 (Registered Jack 45) is a common term used interchangeably with 8P8C, but technically, RJ45 is a specific standard that uses an 8P8C connector.
- Used for Ethernet networking with twisted-pair cables.

## **One-Line Definitions**
- **TCP (Transmission Control Protocol)**: A reliable, connection-oriented transport layer protocol.
- **UDP (User Datagram Protocol)**: A fast, connectionless transport layer protocol without reliability.
- **IPv4 (Internet Protocol version 4)**: A widely used IP version with a 32-bit address space.
- **IPv6 (Internet Protocol version 6)**: A newer IP version with a 128-bit address space to address IPv4 exhaustion.
- **RFC (Request for Comments)**: A formal document from IETF (Internet Engineering Task Force) describing standards and protocols.
- **Protocol**: A set of rules defining communication between devices in a network.

## **OSI Model Layers and Key Devices/Data Units**

| Layer             | Device(s) Used    | Data Unit    |
|------------------|----------------|--------------|
| **Physical Layer**  | Hub            | Bits         |
| **Data Link Layer** | Bridge/Switch  | Frames       |
| **Network Layer**   | Router         | Packets      |
| **Transport Layer** | TCP/UDP        | Segments     |
| **Application Layer** | HTTP, FTP, etc. | Application Data |

## **Port Categories**
- **Ephemeral Ports**: Short-lived ports dynamically assigned by the OS for temporary connections (range 49152–65535).
- **User Ports**: Also known as registered ports, used by user applications (range 1024–49151).
- **System Ports**: Also called well-known ports, used by system processes (range 0–1023).
- **Dynamic Ports**: Randomly assigned for temporary use by client applications.


