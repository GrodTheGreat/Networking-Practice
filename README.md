# Networking Practice
This is a repo to use while I practice Networking Programming

## Projects
Languages
- Python
- C
- C++
- Go
- Rust

### 1. **Basic Socket Programming**
**Overview:** Create a simple client-server application where the client sends a message to the server, and the server echoes it back.
**Skills:** Basic understanding of TCP/IP, sockets, client-server architecture.
**Technologies:** BSD sockets (C/C++), `socket` module (Python), `net` package (Go), `std::net` (Rust).

### 2. **Multi-Client Chat Room**
**Overview:** Extend the basic socket program to support multiple clients. Implement a simple chat room where multiple clients can send messages that are broadcast to all connected clients.
**Skills:** Concurrent programming (threads or async I/O), basic message broadcasting.
**Technologies:** Threads (C/C++), `threading` or `asyncio` (Python), `goroutines` (Go), `tokio` or `async-std` (Rust).

### 3. **HTTP Server**
**Overview:** Implement a simple HTTP server that can serve static files from a directory.
**Skills:** Understanding of HTTP protocol, parsing HTTP requests, serving static files.
**Technologies:** Socket programming libraries, HTTP parsing libraries.

### 4. **Simple REST API**
**Overview:** Develop a RESTful API with basic CRUD operations, possibly backed by a simple database or in-memory storage.
**Skills:** REST principles, HTTP methods (GET, POST, PUT, DELETE), basic database operations.
**Technologies:** `sqlite` (C/C++), `flask` or `fastapi` (Python), `net/http` and `mux` (Go), `warp` or `actix-web` (Rust).

### 5. **File Transfer Protocol (FTP) Client**
**Overview:** Create an FTP client capable of connecting to an FTP server, navigating directories, and uploading/downloading files.
**Skills:** FTP protocol, file I/O operations, error handling.
**Technologies:** FTP libraries or raw socket programming.

### 6. **Load Balancer**
**Overview:** Implement a simple load balancer that distributes incoming requests to multiple backend servers.
**Skills:** Understanding of load balancing algorithms (round-robin, least connections), network traffic distribution.
**Technologies:** Networking libraries, concurrent programming.

### 7. **Proxy Server**
**Overview:** Build a proxy server that forwards requests from clients to another server, potentially adding features like caching or filtering.
**Skills:** Proxy principles, request forwarding, optional caching mechanisms.
**Technologies:** HTTP libraries, caching mechanisms (e.g., in-memory caching).

### 8. **Peer-to-Peer File Sharing**
**Overview:** Develop a peer-to-peer file-sharing application where peers can share files directly with each other.
**Skills:** P2P networking principles, distributed systems, handling NAT traversal.
**Technologies:** P2P libraries, NAT traversal techniques.

### 9. **Network Monitoring Tool**
**Overview:** Create a tool to monitor network traffic, capture packets, and analyze the data for metrics such as bandwidth usage or packet loss.
**Skills:** Packet capturing and analysis, network protocols, data visualization.
**Technologies:** `pcap` library (C/C++), `scapy` (Python), `gopacket` (Go), `libpnet` (Rust).

### 10. **Custom Application Layer Protocol**
**Overview:** Design and implement a custom application layer protocol over TCP/UDP for a specific use case (e.g., custom messaging protocol, game server protocol).
**Skills:** Protocol design, serialization/deserialization of data, network security.
**Technologies:** Protocol design principles, serialization libraries (e.g., protobuf, msgpack).

### Additional Considerations
- **Concurrency and Asynchronous Programming:** Many of these projects will benefit from a deep understanding of concurrency (threads, async/await) to handle multiple connections efficiently.
- **Security:** As you progress, consider security aspects such as encryption (TLS/SSL), authentication, and secure data handling.
- **Frameworks:** While the basics can be done with raw sockets, leveraging frameworks and libraries specific to each language can speed up development and add robustness.
