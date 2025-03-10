# Network Packet Sniffer

This Python script captures and analyzes raw network packets from a network interface using the `socket` library. It parses various layers of network protocols such as Ethernet, IPv4, ICMP, TCP, and UDP, and displays relevant information. The script works by using raw sockets to listen for network traffic and then parsing the captured packets to extract useful details.

## Features

- Captures raw network data packets using a raw socket.
- Supports parsing and displaying details of the following protocols:
  - Ethernet (MAC addresses and protocol type)
  - IPv4 (Source and destination IP addresses, TTL, and protocol type)
  - ICMP (Type, Code, Checksum, and Data)
  - TCP (Source and destination ports, sequence numbers, flags, and data)
  - UDP (Source and destination ports, and size)
- Displays packet data in a readable and structured format.

## Requirements

- Python 3.x
- `socket` library (built-in Python library)
- `struct` library (built-in Python library)
- `textwrap` library (built-in Python library)

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SanjayTummala/CodeAlpha_Netork-Sniffer/blob/main/main.py
   cd main.py
