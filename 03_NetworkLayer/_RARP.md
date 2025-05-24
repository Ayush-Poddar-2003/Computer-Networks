
![alt text](/Images/image-1.png)

---

it maps a MAC address to an IP address.

- The machine knows its MAC address (hardwired in NIC).
- It sends a RARP request over the network “This is my MAC address what is my IP?”
- A RARP server on the network responds with the corresponding IP address.
- Broadcast request: Client sends a RARP request using its MAC address.
- Server reply: RARP server looks up a static table (MAC → IP mapping) and replies to the client with the correct IP.