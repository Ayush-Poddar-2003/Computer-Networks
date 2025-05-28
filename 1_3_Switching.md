
Switching is the process of forwarding data packets between devices in a network. 
It happens at the Data Link Layer (Layer 2) or sometimes Network Layer (Layer 3).

## 1. CIRCUIT SWITCHING
- A dedicated communication path or circuit is established between two devices for the entire duration of the transmission.
- Used in traditional telephone systems, Way before OSI, TCP Models.
- Connection-oriented  
- Contiguous Flow, Inorder  
- No headers as dedicated path, no need of addresses
- Fixed bandwidth is reserved.
- Low delay once circuit is established.
- Resources (like bandwidth) remain reserved even if no data is being sent.
- Ensures reliable and ordered delivery.

## 2. PACKET SWITCHING 
- Data is broken into packets, each of which is sent independently through the network. 
- The packets may take different routes and are reassembled at the destination.

Working:
- Data is divided into small packets.
- Each packet has:
  - Header (with source, destination, sequence number, etc.)
  - Payload (actual data)
- Packets are routed independently.
- Packets may arrive out of order or at different times.
- At the receiver’s end, packets are reassembled into the original message.

#### Types:
1. Datagram Packet Switching (like UDP)  
   - Each packet treated independently
   - No fixed path; routing decision made per packet.
2. Virtual Circuit Switching (like TCP)  
   - A logical path is established before transmission.
   - All packets follow the same path.

## 3. MESSAGE SWITCHING
Whole message is sent and stored at intermediate nodes before forwarding  
Store-and-forward model