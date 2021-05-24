---
title: Networks
description: Unit 3 of Computer Science
---

# Vocabulary

- Bus Topology: Computer network in which a "bus" connects all the devices together with a cable
- Cable: a wire that is used for networking
- Check Digit: Extra digit added to check data integrity after input, transmission, storage, or processing
- Data Integrity: Accuracy of data after input, transmission, storage, or processing
- Data Packet: Portion of a message that is transmitted through a network. Contains data such as check digits and destination address.
- Gateway: Link that resides between computer networks that convert data so that it is understood by the receiving network.
- Handshaking: exchange of predetermined signals to signify that a connection has been established between two systems.
- Hub: Network connection point for devices. Data arriving at a hub is copied over and sent to all the devices on the network.
- ISDN (Integrated Services Digital Network): An international communication standard that allows for the transmission of media over digital telephone lines.
- LAN (Local Area Network): A computer network where the computers are connected locally.
- Microwave Transmission: Wireless electronic communication
- Modem (Modulator/Demodulator): A device that converts electrical device to audio signals that travels on telephone lines.
- Network: Computer systems that are interconnected.
- Packet: Group of bits that form some sort of data.
- Packet Switching: method of network communication that transmit packets through a network.
- Networking: Using a network.
- Parity bit: Error detecting bit that is appended on data in order to check for data integrity
- Protocol: International rules that ensure the transfer of data between system.
- TCP/IP (Transmission Control Protocol/Internet Protocol): Communication protocol used for connection on the Internet.
- WAN (Wide Area Networks): A connected network of LANs.

# Network Fundamentals

## Different Types of Computer Networks

In a computer network, there is often a `Server` and a `Client`.
A `Server` provides services to the `client`.

In a network, there is three important device.
A `hub` is a connection point for devices on a network.
Network devices are connected to the hub through a cable.
When a client request some data from a server, the hub copies the data and send it to all devices connected to it.
This is sometimes problematic, as it causes extra traffic in the network.

Similar to a hub, a `switch` is a connection point for devices on a network.
However, a switch is able to identify the device on each port, and transmit data accordingly to the receiver.
_Nowadays, hubs are obsolete._

A `router` is device that join multiple networks.
One potential job of a router is joining the LAN with the Internet.
A simple switch cannot accomplish this job.
However, nowadays, routers and switch are mostly integrated into one device, allowing the creation of wireless networks connected to wired ones.

Below is a list of the common network types:
- LAN
- WLAN (Wireless LAN)
- VLAN (Virtual LAN)
- WAN
- SAN (Storage Area Network)
- Internet
- Extranet
- VPN (Virtual Private Network)
- PAN (Personal Area Network)
- Peer to Peer (P2P)

In fact, the Internet is a really big WAN that is connected to thousands of LAN around the world.

### Local Area Network

In a LAN, peripheral devices and data can be shared. There is a high data-transfer rate between computers on the network.

### WLAN

A WLAN is just a wireless LAN.
WLANs generally are not as fast as an wired network, but allows the wireless devices to move freely.
However, the use of WiFi also reduce the safety of the data transfered.
To work around this, secure protocals (WEP, WPA, WPA2) should be used.
WiFi blacklist/whitelist and MAC Address banning can also be used.

### VLAN

VLAN stands for Virtual Local Area Network.
A VLAN artificially divides a network into separate compartments.
Logically separated computer networks are similar to physically separate networks.
Unless separate rules have been set, the computer cannot see across a VLAN.
VLANs allow for easy management of the resources on a network, and improves security.

### WAN

A WAN connects many LANs across a wide geographic area.
For example, a company may have a WAN connecting its many headquarters around the world.

### SAN

A SAN network is a network specifically designed for the sharing of large storage devices.

### Intranet and Extranet

An intranet is a collection of private computer networks within an organization that is not connected to the Internet.
Intranets are secure and fast, but hard to access outside of the LAN.

Similarly, an Extranet is a collection of private computer network, but opened to the Internet.
This is less secure, but allows for more flexibility.

### Internet

The Internet is just a very large WAN connecting billions of LANs around the world together.

### IoT

Internet of Things are small devices that can connect to the Internet.
These small devices may send and receive data.

### VPN

A Virtual Private Network allows for an encrypted tunnel to be established between two computers.
This allows for remote workers to access the resources on a company Intranet while ensuring safety of data.

### PAN

A Personal Area Network is composed of devices that are centered around an individual's workspace.
These devices have very short ranges.
PANs can be both wired and wireless.
USB and bluetooth are some common PAN networks.

### P2P

A Peer to Peer network do not uses the client/server network, but instead a distributed network architecture where all computer systems are decentralized.
The same device can be both a server and a client.

## Importance of Standards

There are two main organization setting standards for computer communication.
Institute of Electrical and Electronics Engineers (IEEE) and Internet Engineering Task Force (IETF).
The standards they create help create compatibility between hardware and software, computers of different brands and origins.
Without standards, communication between computers are nearly impossible.

## Networks, Communication, and Layers

In order to simplify the many layers of inter computer communication, a network is split into a different layers, where each layer represents a module.
The `OSI Model` is created for this reason. The OSI Model stands for Open System Interconnection Model.

The OSI Model is split into 7 parts.

1. Application: Various services used by the end user
2. Presentation: Provides data format, compression, encryption information.
3. Session: Manages a connection between two users
4. Transport: Definition of data segments, assignment of numbers, data transfer, re assemblage of data
5. Networking: Handling packet switching
6. Data Link: Error handling for transitions, transmission rate, flow control
7. Physical: Transmission of 1 and 0 through cables and microwave. Definition of media and specification.

The `TCP/IP` protocal describes functions that take place in each layer.
1. Application: Perform services for software.
2. Transport: The transformation of data.
3. Internet: Packet Switching
4. Network Access: Media and devices

## Technology required for a VPN

Hardware requirements
- Internet Access
- VPN Software
- VPN Routers
- VPN Appliances
- VPN Concentrators (handles large number of incoming VPN tunnels)
- VPN Servers

For *Secure* VPN (encrypted, tunneled VPN)
1. IPSec (Internet Protocal, Security Protocal)
	- AES (Encryption)
2. SSL (Secure Socket Layer) or TLS (Transport Layer Security)

For *Trusted* VPN (Secure on provider side)
1. ATM (Asyncronous Transfer Mode) circuits
2. Frame delay circuits
3. Transport of layer 2 frames over MultiProtocol Label Switching

`Hybrid` VPNs are a mix of Trusted and Secure VPN.

## Common VPN Types

- Site to site VPN (Connecting network or facilites together)
- Remote access VPN (remote into an intranet)

## Uses of a VPN

VPN Benefits
- Easy Communication
- Secure connection
- Decrease operational cost when compared to WAN
- Extended connection
- Allows for remote work
- Allows global networking
- Simplify network topology

# Data Transmission

## Necessity of Protocols

Requirements for communication to take place:
- Presence of an identified sender
- Presence of an identified receiver
- Presence of an agreed-upon method of communicating
- Presence of a common language
- Presence of a common grammar
- Presence of an agreed-upon speed and timing of delivery
- Presence of confirmation or acknowledgment requirements

Computer Networks Protocols also provides:

- Rules about the message format
- Rules about the way intermediary devices should facilitate communication
- Rules about initiation and termination of a communication session
- Rules about the type of error checking to be used
- Rules about an error detection and correction mechanism
- Rules about recovery and resending data

Computer Network Protocol guarantee:
- Data Integrity
- Source Integrity
- Flow Control
- Congestion Management
- Deadlock Prevention
- Error Checking
- Error Correction

## Speed of Data Transmission across a network

We measure the ability of a medium to transfer data as bandwidth.
Bandwidth is measured in $Mbps$, or Mega-bits per second.
This is different from $MBps$, which means Mega-Byte per second.

The theoretical speed of data is called bandwidth, the actual transfer rate is called throughput.
While the slowest part of a network is called the bottleneck.
Goodput measures the transfer rate of usable data.

There are several factors that affect the speed of data transmission in a network:

- Bandwidth
- Data transfer rate of storage devices
- Interference
- Malicious software
- Number of connected deviecs
- Packet loss
- Bottleneck
- Client/Server specification

## Compression of Data

In order to reduce bandwidth, compression is sometimes used to reduce the file size.
There is two types of compression, Lossy and Lossless.
Text have to be compressed losslessy, but some medias can be compressed with lossy compression.

## Characteristics of different transmission media

There are three most common wires.
Fiber Optic cable, coaxial cables, and Unshielded Twisted Pair Cable (UTP).
There are many wireless communication methods.
- Microwave Radio
- Satellites
- Infrared
- RFID
- Bluetooth
- Free Space Optics

In general, fiber optics is the fastest, most secure, and most reliable.
Wireless is not as secure, and not as fast or reliable.
UTP lies between the two.

## Packet Switching

Packet switching is the communication method in which data packets are transfered through a network.
Packets are sent individually, and may take different paths to the same destination.
There is two method types of packet switching.

Datagram packet switching, where each packet is sent with an address.
The route can be different per packet.

Virtual Circuit packet switching, where the route and the destination is predetermined before hand.

## Network Topology

There are eight basic topologies:
- Point to point
- bus
- star
- ring
- mesh
- tree
- fully connected
- hybrid

# Wireless Networking

## Advantages and Disadvantages

Advantages:
- Ease to setup
- Cheap
- Wireless/Convenient
- Easier to plan

Disadvantage:
- Slow
- High error rates
- Weather dependent
- Weakest security
- Unreliable

## Hardware and Software Components

Hardware needed
- Modem
- Wireless Router/Access Point
- Wireless Network Adapter (NIC)
- Device
- Wireless antennas
- Wireless repeater
- Ethernet repeater
- Ethernet over power line

Software needed
- DHCP (IP Address assigning)
- Software Firewall
- Name/SSID (Service Set IDentification)
- NIC Drivers (Network Interface Card)
- Operating System
- Security Software
- WAP (Wireless Application Protocol)
- Web Browser
