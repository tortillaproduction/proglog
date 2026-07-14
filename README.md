# proglog

A distributed commit log service built in Go, designed as a hands-on project to understand the core concepts of distributed systems.

This repository is based on the book *"Distributed Services with Go"* by Travis Jeffery.


## 🚀 Features & Tech Stack

- **Core Storage:** Append-only log architecture for high-performance write operations.
- **Networking & API:** High-performance RPC using **gRPC** and **Protocol Buffers**.
- **Observability:** Structured logging, metrics collection, and tracing.
- **Consensus & Clustering:** (If applicable) Distributed consensus and replication powerd by **Raft** / Serf.
- **Language:** Written entirely in **Go1.26.5**.