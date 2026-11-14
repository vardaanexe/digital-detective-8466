# Mission 7 – Computer Networking

## 1. Task / Objective
The objective of this mission is to understand basic networking concepts and learn how computers communicate over a network and the internet.

## 2. Networking Concepts

### LAN (Local Area Network)
A LAN connects computers and devices within a small geographical area, such as a home, school or office.

### MAN (Metropolitan Area Network)
A MAN connects multiple networks across a city or large campus.

### WAN (Wide Area Network)
A WAN connects networks over large geographical areas. The Internet is the biggest example.

### DNS (Domain Name System)
DNS converts domain names such as google.com into IP addresses that computers use to communicate.

### Router
A router connects different networks and forwards data packets to their destinations.

### Network Protocol
A network protocol is a set of rules that devices follow to communicate. Examples include HTTP, HTTPS and TCP/IP.

### Packet Switching
Packet switching is a method in which data is divided into small packets and sent across a network. These packets are reassembled at the destination.

### Client-Server Model
In this model, a client requests a service or resource, and a server responds to that request. A web browser and a website server are examples.

## 3. Connectivity and DNS Testing

Commands to be executed:

```bash
ping -c 4 google.com
nslookup google.com
```

The ping command tests network connectivity, while nslookup checks DNS information for a domain.
### Practical Results

**1. Ping Test**

I ran `ping -c 4 google.com` to test internet connectivity. The command completed successfully.

**2. DNS Lookup**

I ran `nslookup google.com`.

Observed results:
- DNS Server: 8.8.8.8
- Domain: google.com
- Returned IP Address: 45.117.29.113

**Conclusion:** The DNS lookup successfully returned an IP address for google.com. This shows how DNS translates domain names into IP addresses.

## 4. How a Website Loads

1. I enter a website address in my browser.
2. The browser requests the website's IP address through DNS.
3. DNS returns the IP address.
4. The browser connects to the website's server.
5. The browser sends an HTTP or HTTPS request.
6. The server processes the request and sends a response.
7. The browser displays the website.

## 5. My Understanding

I learned how devices communicate using networks and how DNS, routers and protocols help transfer information. I also understood the difference between LAN, MAN and WAN.

## 6. Practical Work

To be completed after running the networking commands.

## 7. Difficulties Faced

To be completed after practical work.

## 8. How I Resolved Them

To be completed after practical work.

## 9. Evidence / Files

- README.md
- Terminal output of ping command
- Terminal output of nslookup command

## 10. Commit Details

Commit message: Mission 7 - Computer networking