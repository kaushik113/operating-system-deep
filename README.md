# 🧩 Multithreaded Web Proxy Server with LRU Cache

## 📘 Overview
This project implements a **multithreaded web proxy server** that efficiently handles multiple client requests simultaneously while caching frequently accessed web pages using an **LRU (Least Recently Used)** cache mechanism.  
It demonstrates core **Operating System** and **Networking** concepts including:
- Multithreading and synchronization (using pthreads and semaphores)
- Socket programming
- Request forwarding and caching
- Thread-safe resource management

---

## ⚙️ Features
- 🌐 Acts as an intermediary between clients and web servers  
- 🧵 Handles multiple clients concurrently using threads  
- 🧠 Implements an **LRU cache** to store and reuse recent web pages  
- 🔄 Updates or invalidates stale cache entries automatically  
- 🧰 Thread-safe cache operations with mutex locks and semaphores  
- 📄 Logs every request, cache hit, and cache miss  

---

## 🧠 Concepts Used
- **Multithreading:** Efficient request handling using pthreads  
- **Synchronization:** Mutex and semaphore for safe concurrent access  
- **Socket Programming:** Handles HTTP requests over TCP/IP  
- **LRU Cache:** Hash Map + Doubly Linked List implementation  
- **File I/O:** For caching and request logging  

---

## 🧩 Architecture
