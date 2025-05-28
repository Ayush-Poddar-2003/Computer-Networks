# TCP/IP
Real-world, practical model used for modern networking and the Internet.  
It defines how data should be packaged, addressed, transmitted, routed, and received.

It is also known as the DoD model (Department of Defense).

---

| Layer No. | Layer Name           | OSI Equivalent                     | Function                                  |
| --------- | -------------------- | ---------------------------------- | ----------------------------------------- |
| 4         | Application Layer    | Application, Presentation, Session | User interaction, encryption, compression |
| 3         | Transport Layer      | Transport                          | End-to-end communication, reliability     |
| 2         | Internet Layer       | Network                            | Logical addressing, routing               |
| 1         | Network Access Layer | Data Link + Physical               | Framing, MAC, bit transmission            |


---

### 1. Network Access Layer (Layer 1)
Combines Physical + Data Link  
Handles hardware addressing (MAC), frame transmission  
Devices: NIC, Hub, Switch, Modem

---
### 2. Internet Layer (Layer 2)
Handles IP addressing and routing of packets  
Selects the best path  
Protocols: IP (IPv4/IPv6), ICMP, ARP, IGMP

---
### 3. Transport Layer (Layer 3)
Segmentation and Reassembly of data  
Ensures reliable or fast delivery  
Breaks data into segments and reassembles it  
Protocols:  
- TCP (Reliable, ordered, connection-oriented)  
- UDP (Fast, unordered, connectionless)

---
### 4. Application Layer (Layer 4)
Directly interacts with user applications  
Merges OSI's top 3 layers  
Protocols: HTTP, HTTPS, FTP, SMTP, DNS, TELNET