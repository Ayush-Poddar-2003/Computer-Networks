# FIREWALL

A Firewall is a security system (hardware or software) that monitors and controls incoming and outgoing network traffic based on predefined security rules.

To act as a barrier between a trusted internal network (like your computer or office network) and an untrusted external network (like the Internet).

## 1. Packet-Filter Firewall
Controls access to a network by analyzing individual packets and filtering them based on predefined rules like:
- Source IP address
- Destination IP address
- Port number
- Protocol

Data/payload is not checked

## 2. Proxy Firewall
It hides the internal network and filters traffic at the application layer.  
More Secure  
Checks data too  
1. Client sends request to proxy
2. Proxy checks the request, applies rules
3. If allowed, proxy forwards request to destination
4. Server responds to proxy → proxy responds to client

![alt text](image-7.png)

| Feature                      | **Packet Filtering Firewall**                               | **Proxy Firewall**                                                                   |
| ---------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **OSI Layer**                | Network Layer (Layer 3)                                     | Application Layer (Layer 7)                                                          |
| **Working Principle**        | Filters packets based on IP addresses, ports, and protocols | Acts as an intermediary between client and server; inspects full content of messages |
| **Speed**                    | Very fast (low overhead)                                    | Slower (more processing involved)                                                    |
| **Security Level**           | Basic (only header-level filtering)                         | High (can block specific content or applications)                                    |
| **State Awareness**          | Stateless (unless it's a stateful firewall)                 | Can maintain session information                                                     |
| **Configuration Complexity** | Simple rules based on IP/Port                               | Complex; requires configuring proxy settings for clients                             |
| **Examples**                 | IP tables, Cisco ACLs                                       | Squid Proxy, Blue Coat                                                               |
| **Use Case**                 | Basic filtering and routing                                 | Content filtering, logging, hiding internal IPs                                      |
| **Logging & Auditing**       | Limited                                                     | Detailed logging (URLs, requests, etc.)                                              |
| **Protection Against**       | IP spoofing, unauthorized access                            | Malicious content, malware, application-layer attacks                                |
