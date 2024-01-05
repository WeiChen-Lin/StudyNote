---
sidebar_position: 1
---

# OSI Model

### An Example: Sending an Email

- Layer 7 - Application

  - Initiate a POST request with JSON data to an HTTPS server

- Layer 6 - Presentation

  - Serialize JSON to flat byte strings

- Layer 5 - Session

  - Initiate a request to establish a TCP connection/TLS

- Layer 4 - Transport

  - Send a SYN request to the target port 443

- Layer 3 - Network

  - SYN is encapsulated in an IP packet(s) and adds the source/destination IPs

- Layer 2 - Data Link

  - Each packet goes into a single frame and adds the source/destination MAC addresses

- Layer 1 - Physical

  - Each frame becomes a string of bits, which is then converted into either a radio signal (Wi-Fi), an electric signal (Ethernet), or light (fiber)
