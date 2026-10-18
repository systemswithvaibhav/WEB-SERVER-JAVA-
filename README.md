# 🌐 Java Web Server

A lightweight HTTP Web Server built from scratch using **Core Java**, **Socket Programming**, and **Multithreading**. This project demonstrates how a web server accepts client connections, processes requests, and responds concurrently using multiple threads.

The project contains both **Single-Threaded** and **Multi-Threaded** implementations to compare server performance under concurrent client requests.

---

# 🚀 Features

- ✅ Built using Core Java
- ✅ Socket Programming
- ✅ Single Threaded Server
- ✅ Multi Threaded Server
- ✅ Concurrent Client Handling
- ✅ Client-Server Communication
- ✅ Request Processing
- ✅ Apache JMeter Load Testing
- ✅ Successfully Tested with 60,000 Requests

---

# 🛠️ Tech Stack

- Java
- Java Sockets
- Multithreading
- TCP Communication
- Apache JMeter

---

# 📂 Project Structure

```
WEB-SERVER-JAVA
│
├── SingleThreaded
│   ├── Server.java
│   └── Client.java
│
└── MultiThreaded
    ├── Server.java
    ├── Client.java
    └── WorkerThread.java
```

---

# ⚙️ How It Works

1. The server starts listening on a specific port.
2. Clients establish TCP connections using Java Sockets.
3. The server accepts incoming connections.
4. In the Multi-Threaded version, each client is assigned a dedicated thread.
5. The server processes client requests and sends responses back.
6. Apache JMeter is used to simulate thousands of concurrent requests to evaluate server performance.

---

# 📊 Performance Testing

The Multi-Threaded server was tested using **Apache JMeter**.

### Load Test Summary

- ✅ Total Requests : **60,000**
- ✅ Successful Responses
- ✅ Concurrent Client Connections
- ✅ Stable Server Execution

---

# 📸 Screenshots

## 🌐 Server Running

<img width="1511" height="847" alt="image" src="https://github.com/user-attachments/assets/44af12a2-3c42-49b9-8a5a-f37cf49fb4df" />

<img width="1547" height="866" alt="image" src="https://github.com/user-attachments/assets/03e533ab-7a64-4fa2-9270-f9a6bc3bba6b" />

<img width="1641" height="852" alt="image" src="https://github.com/user-attachments/assets/b0fe6d54-45ad-476e-8384-810e8591f412" />

<img width="1522" height="842" alt="image" src="https://github.com/user-attachments/assets/ae86ba45-a521-4b8a-81d3-eb7b7739a15b" />



## 📈 Apache JMeter Graph Results

<img width="1550" height="865" alt="image" src="https://github.com/user-attachments/assets/263ee335-a176-46c2-a91d-d0fce88efc5f" />



## 📋 Apache JMeter Request Results

<img width="1545" height="857" alt="image" src="https://github.com/user-attachments/assets/17f803b1-77a8-48a9-819d-8738e5122d62" />


# 🧠 Concepts Used

- Socket Programming
- Client-Server Architecture
- TCP Communication
- Threads
- Runnable Interface
- Thread Lifecycle
- Concurrency
- Network Programming
- Load Testing

---

# 📚 What I Learned

- Building a Web Server from scratch
- Working with Java Sockets
- Handling Multiple Clients Concurrently
- Creating Threads using Runnable
- Server-Client Communication
- Understanding Blocking I/O
- Load Testing with Apache JMeter
- Performance comparison between Single and Multi Threaded servers

---

# 🚀 Future Improvements

- Thread Pool Implementation
- HTTP Request Parsing
- HTTP Response Headers
- Static File Serving
- Logging
- REST API Support
- HTTPS Support
- Non-Blocking I/O (Java NIO)

---

# 👨‍💻 Author

**Vaibhav Sisodia**

GitHub: https://github.com/MLwithvaibhav
