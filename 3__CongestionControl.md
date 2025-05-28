What is Congestion?  
Congestion happens when too many packets are sent through the network, and the routers/switches can’t handle them all, causing:
- Packet loss
- Increased delay
- Wasted bandwidth

Goal of Congestion Control:  
To prevent congestion and maintain good performance by controlling the rate of data transmission.

Congestion Control Techniques
1. Slow Start  
TCP starts by sending a small number of packets
For each ACK received, it doubles the window size
Grows exponentially until it hits a threshold

2. Congestion Avoidance  
After reaching the threshold, TCP increases the window linearly (one packet per round trip)
Prevents congestion by being cautious

3. Fast Retransmit  
If 3 duplicate ACKs are received, assume a packet is lost Retransmit immediately without waiting for a timeout

4. Fast Recovery  
After fast retransmit, instead of slow start, reduce window and grow linearly