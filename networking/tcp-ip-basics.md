# TCP/IP Basics

These are my notes about basic TCP/IP concepts while building my cybersecurity and networking foundations.

## What is TCP/IP?

TCP/IP is a set of communication protocols used to connect devices on networks and on the internet.

It defines how data is addressed, transmitted, routed and received.

## Main Concepts

- **IP address**: identifies a device on a network.
- **Subnet mask**: defines which part of the IP address belongs to the network and which part belongs to the host.
- **Default gateway**: the device used to send traffic outside the local network.
- **DNS**: translates domain names into IP addresses.
- **TCP**: reliable protocol that checks if data arrives correctly.
- **UDP**: faster protocol that does not guarantee delivery.
- **Port**: identifies a specific service running on a device.

## Why this matters for cybersecurity

Understanding TCP/IP is important for cybersecurity because most attacks, defenses, scans and logs are related to network communication.

Examples:

- Identifying open ports
- Understanding traffic captures in Wireshark
- Troubleshooting connectivity issues
- Recognizing suspicious network behavior
- Understanding how services communicate

## Basic Commands to Learn

```bash
ping example.com
ipconfig
tracert example.com
nslookup example.com
netstat -ano
