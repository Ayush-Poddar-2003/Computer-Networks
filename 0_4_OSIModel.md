# OSI MODEL
Developed by ISO,  
Standardizes the functions of a communication system into 7 layers, from hardware to software.

---

| Layer Name   | Function                                  | Protocols/Examples           |
| ------------ | ----------------------------------------- | ---------------------------- |
| Application  | Interface for user apps                   | HTTP, FTP, SMTP, DNS         |
| Presentation | Data translation, encryption, compression | JPEG, MP3, SSL, ASCII        |
| Session      | Manages sessions/connections           | NetBIOS, RPC, APIs           |
| Transport    | End-to-end delivery, flow control           | TCP, UDP                     |
| Network      | Routing, IP address        | IP, ICMP, Routers            |
| Data Link    | Frames, MAC address, error control  | Ethernet, PPP, Switches      |
| Physical     | Transmits raw bits    | Cables, Hubs, NICs, Voltages |

---
**DATA FLOW -**  
Sender : Application -> Physical  
Receiver : Physical -> Application