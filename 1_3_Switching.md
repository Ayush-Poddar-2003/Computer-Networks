
Switching is the process of forwarding data packets between devices in a network. 
It happens at the Data Link Layer (Layer 2) or sometimes Network Layer (Layer 3).

## 1. CIRCUIT SWITCHING
Used in traditional telephone systems, Way before OSI, TCP Models.
A dedicated path is established before transmisson
Connection-oriented  
Contiguous Flow, Inorder  
No headers as dedicated path, no need of addresses

## 2. PACKET SWITCHING 
Data is divided into small packets and transmitted over the network  
Types:
1. Datagram Packet Switching (like UDP)  
Each packet treated independently
2. Virtual Circuit Switching (like TCP)  
Pre-planned routes used for all packets

## 3. MESSAGE SWITCHING
Whole message is sent and stored at intermediate nodes before forwarding  
Store-and-forward model