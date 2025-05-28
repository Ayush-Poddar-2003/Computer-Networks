# TRANSPORT LAYER

4th layer of the OSI Model.   
It acts like a bridge between software/apps and the network.

---
### RESPONSIBILITIES -
| Function                          | Description                                                                       |
| --------------------------------- | --------------------------------------------------------------------------------- |
| **End-to-End Communication**    | Provides a connection between processes        |
| **Segmentation and Reassembly** | Breaks large data into smaller segments and reassembles them at the destination   |
| **Reliable Data Transfer**      | Ensures data reaches without errors, duplication, or loss                         |
| **Flow Control**                | Prevents sender from overwhelming the receiver                                    |
| **Error Control**               | Uses acknowledgment and retransmissions to ensure reliability                     |
| **Multiplexing**                | Supports multiple applications using **port numbers** (e.g., HTTP = 80, FTP = 21) |

---
### PROTOCOLS USED -
1. TCP
2. UDP

# <CENTER> TCP HEADER
![alt text](image-3.png)

1. Source and Destination Port : To find processes (16 bits each)  
Range : 0 to 65535 out of which  
0 - 1023 : Well known  
1024 - 49151 : Registered Port nos. by IANA
49152 - 65535 : Dynamic / private

2. Sequence Number : First Data byte, Shouldn't start from 0
3. Acknowledgement Number : From reciever , Last data byte+1
4. Header Length : (4 bits)