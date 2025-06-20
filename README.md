# RedisClone

## Project Abstract

### This project is a from-scratch implementation of Redis, the high-performance in-memory data structure store. It delves into how Redis handles data storage, persistence, replication, and real-time streaming under the hood.

### Throughout the project, the server evolves from responding to simple commands like PING to supporting core Redis functionality including key-value operations, replication, RDB parsing, streaming with XREAD, and even transactions.

- Key Features & Learning Milestones
- Bind to a TCP port and respond to basic commands like PING
- Support concurrent clients and handle ECHO, SET, GET operations
- Implement key expiration and time-based data eviction
- Read and serve data from .rdb persistence files
- Support replication (handshakes, offsets, propagation, ACKs)
- Implement Redis Streams and support querying via XREAD
- Handle blocking reads with or without timeouts
- Implement Redis transactions with MULTI, EXEC, DISCARD, and INCR

### I'm building this project to understand how Redis works behind the scenes — from raw socket handling to memory management, replication protocols, and stream processing in distributed systems.
