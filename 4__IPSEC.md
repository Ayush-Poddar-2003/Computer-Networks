# IPSEC

IPSec is a suite of protocols used to secure IP communications by authenticating and encrypting each IP packet in a data stream.
- IETF (Internet engineering task force) Standard
- Used by both ipv4, ipv6

Collection of protocols such as -
1. ESP : Encapsulating Security Payload
2. AH : Authentication header
3. IKE : Internet Key Excchange

Two Modes of IPSec:
| Mode               | Description                                                                | Use Case                                             |
| ------------------ | -------------------------------------------------------------------------- | ---------------------------------------------------- |
| **Transport Mode** | Only the **payload** of the IP packet is encrypted.                        | Used for **end-to-end communication** between hosts. |
| **Tunnel Mode**    | The **entire IP packet** is encrypted and encapsulated in a new IP packet. | Used for **network-to-network** (e.g., VPNs).        |
