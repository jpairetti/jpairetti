# Hi, I'm Joaquín

CS student at FAMAF (Universidad Nacional de Córdoba), specializing in systems 
and distributed systems. This portfolio spans projects from kernel-level 
concurrency to network protocol design and REST APIs — most developed as group 
coursework, with my individual contribution documented in each repo's README.

## Featured Projects

### Operating Systems
- **[MyBash](https://github.com/jpairetti/mybash-shell-c)** — Unix shell implementation in C, with pipes, I/O redirection, and background execution. Includes a demo video.
- **[xv6 Kernel Concurrency](https://github.com/jpairetti/xv6-kernel-concurrency)** — Kernel-level named semaphores (sem_open/up/down/close) in xv6-riscv, using spinlocks and sleep/wakeup.
- **[FAT32 FUSE Filesystem](https://github.com/jpairetti/fat32-fuse-filesystem)** ⭐ — A FAT32 filesystem in userspace (FUSE), extended with hidden activity logging via an orphan FAT cluster technique, plus unlink/rmdir support.

### Networks & Distributed Systems
- **[hget](https://github.com/jpairetti/hget)** — HTTP/1.0 client built from raw sockets, with a from-scratch DNS resolver over UDP (RFC 1035).
- **[Game Backlog API](https://github.com/jpairetti/wikidata-game-api)** ⭐ — Flask REST API for tracking a video game wishlist, integrated with Wikidata, with token-based authentication and automated test coverage.
- **[HFTP over Tor](https://github.com/jpairetti/hftp-client-server)** — Custom file-transfer protocol over raw TCP (base64 and binary framing modes), deployed as a Tor hidden service.
- **[TCP Congestion Control Simulation](https://github.com/jpairetti/tcp-congestion-control-sim)** — OMNeT++ simulation of flow vs. congestion control, implementing a TCP-inspired sliding window algorithm (rwnd/cwnd, AIMD).
- **[Shortest-Path Routing for Ring Networks](https://github.com/jpairetti/dynamic-routing-omnet)** ⭐ — Custom routing algorithm with dynamic neighbor discovery (HELLO packets), ~87% latency improvement over the baseline. Includes a full research paper and poster.

## Tech Stack
C · Python · C++ · Scala · ARM Assembly · Flask · OMNeT++ · FUSE · OpenAPI

## Contact
pairettijoaquin@gmail.com
