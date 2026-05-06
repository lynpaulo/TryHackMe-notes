Day 2 – Networking & DNS Basics
Networks
A network is a group of connected devices that communicate with each other.  
The Internet is a massive network made of many smaller networks.

Examples:
- Computers, phones, servers
- Electricity grids, transport systems

Device Identification

IP Address
- Identifies a device on a network
- Can change over time
- Types:
  - Private IP (local network)
  - Public IP (internet)

IPv4 example: `192.168.1.1` (4 octets, 0–255 each)  
IPv6 is newer and supports more addresses

MAC Address
- Unique hardware identifier
- Assigned to network card
- Format: `a4:c3:f0:85:ac:2d`
- Can be spoofed

Ping (ICMP)
- Used to test if a device is reachable
- Measures response time

Command:
ping <ip or domain>

DNS (Domain Name System)
DNS converts domain names into IP addresses.

Example:
tryhackme.com → 104.26.10.229

Domain Structure
- TLD: .com, .org, .uk
- Second-level: tryhackme
- Subdomain: admin.tryhackme.com

Limits:
- Subdomain: 63 chars max
- Full domain: 253 chars max

DNS Record Types

- A → IPv4 address
- AAAA → IPv6 address
- CNAME → points to another domain
- MX → email servers
- TXT → text data / verification

DNS Lookup Process
1. Check local cache
2. Ask ISP (recursive DNS server)
3. Root DNS server
4. TLD server
5. Authoritative server
6. Return IP address

TTL (Time To Live)
- Defines how long DNS data is cached
- Measured in seconds

Example:
3600 = 1 hour

Key Takeaways
- IP = device address
- MAC = hardware identity
- DNS = converts names to IPs
- TTL = cache duration
- Ping = checks connectivity
