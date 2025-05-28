# PHYSICAL LAYER  ✅

- Deals with cables, connectors.
- Deals with Physicals things
- Topologies
- Link Configuration
- Repeaters, Hubs
- Transmission Mode
- Multiplexing
- Encoding
---
- Responsible for transmitting raw bits (0s and 1s) over a physical medium such as cables or wireless.
- Converts binary data into physical signals.
- Defines the hardware characteristics like Cable types (coaxial, twisted pair, fiber optic)
- Data Rate Control : Specifies how many bits per second can be sent (bit rate).
- Ensures sender and receiver are synchronized in timing.

---

| Feature         | Unicast        | Multicast                                  | Broadcast               |
| --------------- | -------------- | ------------------------------------------ | ----------------------- |
| Communication   | One-to-One     | One-to-Many (group)                        | One-to-All (network)    |
| Address Range   | IP of receiver | Multicast IP (224.0.0.0 – 239.255.255.255) | All devices on network  |
| Efficiency      | Low for many   | High for group                             | Low for non-group tasks |
| Use in Internet | ✅ Yes          | ✅ Yes                                      | ❌ No (only in LAN)      |
