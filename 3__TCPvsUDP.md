

| Feature                | **TCP (Transmission Control Protocol)**               | **UDP (User Datagram Protocol)**               |
| ---------------------- | ----------------------------------------------------- | ---------------------------------------------- |
| **Type**               | Connection-oriented                                   | Connectionless                                 |
| **Reliability**        | Reliable (ensures delivery, order, and no duplicates) | Unreliable (no guarantee of delivery or order) |
| **Connection Setup**   | Requires 3-way handshake before data transfer         | No handshake needed                            |
| **Error Control**      | Yes (uses ACKs, sequence numbers, retransmission)     | No built-in error correction                   |
| **Flow Control**       | Yes (uses sliding window protocol)                    | No                                             |
| **Congestion Control** | Yes (e.g., TCP congestion avoidance)                  | No                                             |
| **Speed**              | Slower due to overhead                                | Faster due to low overhead                     |
| **Packet Ordering**    | Maintains order of packets                            | Does not ensure ordering                       |
| **Header Size**        | Larger (20–60 bytes)                                  | Smaller (8 bytes)                              |
| **Use Cases**          | Web (HTTP/HTTPS), Email (SMTP), File Transfer (FTP)   | Streaming (video/audio), DNS, VoIP             |
