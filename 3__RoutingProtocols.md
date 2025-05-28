![alt text](image-4.png)

INTRADOMAIN : Within same network
INTERDOMAIN : Different Networks

---
### RIP (DISTANCE VECTOR ROUTING)
-	Routers share information with direct neighbors
1. Initialization: 
   - Each router knows only about its directly connected neighbors.
   - Distance to itself = 0; to others = ∞.
2. Update:
   - Each router sends its routing table to neighbors.
   - Routers update their tables based on the received information:  
`New Distance = Distance to neighbor + neighbor's distance to destination`

---
### OSPF (LINK STATE ROUTING)
Open Shortest Path First  
uses the Dijkstra algorithm to find the shortest path.

PACKET TYPES -;
| Type | Name                           | Description                               |
| ---- | ------------------------------ | ----------------------------------------- |
| 1    | **Hello**                      | Discover neighbors and maintain adjacency |
| 2    | **DBD (Database Description)** | Summary of link-state database            |
| 3    | **LSR (Link State Request)**   | Request missing LSAs                      |
| 4    | **LSU (Link State Update)**    | Send LSAs (Link State Advertisements)     |
| 5    | **LSAck**                      | Acknowledge receipt of LSAs               |


### BGP (PATH VECTOR)