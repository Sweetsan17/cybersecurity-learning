# TryHackMe — What is Networking?

## Lab Information

- **Platform:** TryHackMe
- **Room:** What is Networking?
- **Category:** Networking Fundamentals
- **Date:** 10 November 2026
- **Status:** In Progress completed
- **Room Link:** https://tryhackme.com/room/whatisnetworking

## Learning Objectives

- Understand what a computer network is.
- Learn how the Internet connects networks.
- Understand IP addresses and MAC addresses.
- Learn about ICMP and the ping command.
- Practise basic network connectivity testing.

---

## Task 1 — What is Networking?

### What I Learned

A computer network is a collection of two or
more connected devices that can communicate
and share information.

Networks are used in everyday life to connect
computers, smartphones, servers, and other devices.

### Real-World Example

My laptop and smartphone can connect to the
same Wi-Fi router and become part of a local network.

### Key Takeaways

- A network connects multiple devices.
- Devices communicate and share information.
- Networks can be small or large.
- Networking is an important foundation of cybersecurity.

---

## Task 2 — What is the Internet?

### What I Learned

The Internet is a global network that connects
many smaller computer networks.

It allows devices around the world to communicate,
exchange and share information.

### Types of Networks

**1. Private Network**

A private network is a network with restricted
access, commonly used in homes, schools,
and businesses.

Example:
My laptop and smartphone connected to
my home Wi-Fi network.

**2. Public Network**

A public network is a network that is accessible
to the general public, subject to its access rules.

Example:
The Internet is a global public network.

### Real-World Example

When I open TryHackMe using Firefox,
my laptop connects through my local network
and Internet service provider to access
TryHackMe's servers.

### Key Takeaways

- The Internet connects many smaller networks.
- Private networks restrict access to authorized users.
- Public networks provide broader connectivity.
- The Internet enables communication worldwide.

---

## Task 3 — Identifying Devices on a Network

### What I Learned

Devices connected to a network need to be
identified so they can communicate.

Two types of addresses are used to identify Devices. 
IP addresses and MAC addresses.

### 1. IP Address

An IP (Internet Protocol) address is a logical
address used to identify a network interface
and deliver data across IP networks.

Example:

192.168.1.10

IP addresses help devices send and receive
information across networks.

### 2. IPv4 Address

IPv4 stands for Internet Protocol Version 4.

An IPv4 address contains 32 bits, commonly
represented as four decimal numbers separated
by dots.

Example:

192.168.1.10

Each number represents 8 bits (one octet)
and ranges from 0 to 255.

### 3. IPv6 Address

IPv6 stands for Internet Protocol Version 6.

An IPv6 address contains 128 bits, commonly
represented as eight groups of hexadecimal
numbers separated by colons.

Example:

2001:0db8:85a3:0000:0000:8a2e:0370:7334

Each group contains 16 bits and consists
of up to four hexadecimal digits (0–9 and A–F).

IPv6 was developed to overcome IPv4 address
limitations and provide a much larger
address space.

### Key Features of IPv6

- Uses 128-bit addresses.
- Contains eight groups of hexadecimal digits.
- Groups are separated by colons (:).
- Supports approximately 340 undecillion addresses.
- Provides a much larger address space than IPv4.
- Supports automatic address configuration.

### IPv4 vs IPv6

| Feature | IPv4 | IPv6 |
|---------|------|------|
| Full Name | Internet Protocol Version 4 | Internet Protocol Version 6 |
| Address Size | 32 bits | 128 bits |
| Address Format | Decimal | Hexadecimal |
| Structure | 4 octets | 8 groups |
| Separator | Dot (.) | Colon (:) |
| Example | 192.168.1.10 | 2001:db8::1 |
| Address Space | Approximately 4.3 billion | Approximately 340 undecillion |

### 4. MAC Address

MAC stands for Media Access Control.

A MAC address is a data link-layer address
associated with a network interface.

Example:

00:1A:2B:3C:4D:5E

MAC addresses help identify network interfaces
during communication on a local network.

### 5. IP Address vs MAC Address

| IP Address | MAC Address |
|------------|-------------|
| Logical network address | Data Link-layer address |
| Used for IP communication and routing | Used for local network communication |
| Can change depending on network configuration | Often assigned to network hardware, but can be changed or randomized |
| Example: 192.168.1.10 | Example: 00:1A:2B:3C:4D:5E |

### Practical Activity

I completed the TryHackMe interactive
exercise about identifying devices
using IP and MAC addresses.

### Key Takeaways

- IP addresses are used for communication
  across IP networks.
- IPv4 addresses contain 32 bits.
- IPv6 addresses contain 128 bits.
- MAC addresses operate at the data-link layer.
- IP and MAC addresses serve different purposes.
