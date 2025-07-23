# Distributed Network Overlay in Java

This project implements a peer-to-peer distributed network overlay that simulates internet-style routing across multiple nodes. It was developed as part of a university course in distributed systems and focuses on custom packet routing, shortest-path computation, and multithreaded communication.

---

## Project Overview

- **Language:** Java
- **Architecture:** Decentralized overlay network of 10+ nodes
- **Routing Algorithm:** Dijkstra's algorithm
- **Communication Protocol:** Custom TCP with data marshalling
- **Concurrency:** Multithreaded socket-based message passing

---

## Features

- Builds a network overlay of nodes with varying distances between connections
- Implements reliable TCP communication with custom serialization
- Uses Dijkstra’s algorithm to determine shortest paths across nodes
- Relays over **1 million packets** through the system with simulated load
- Handles concurrent message passing and simulated node failures

---

## Note

This repository is a **high-level** summary of an academic project. Source code is **not included** to comply with university plagiarism and academic integrity policies. Feel free to reach out if you'd like to discuss the project in more detail!
