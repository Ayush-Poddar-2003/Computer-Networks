To ensure that the sender doesn't overwhelm the receiver by sending data faster than it can process.

Techniques Used:
## 1. Stop-and-Wait Protocol
Sender sends one frame at a time.

Waits for ACK (Acknowledgment) before sending the next.

Simple but slow.

## 2. Sliding Window Protocol
Sender can send multiple frames (within window size) without waiting for ACKs.

Receiver uses a window to control how many frames it can accept.

Types:

1. **Go-Back-N:**  
On error, receiver discards all frames after the error; sender retransmits from error frame.

2. **Selective Repeat:**  
Only the wrong frame is retransmitted, not the whole window.