# 🚗 WashItNow - Java Server

WashItNow is a Java-based client-server application that simulates a service system where clients can request operations (such as services based on a zipcode) and communicate with a server through sockets.

## 📌 Overview

This project implements a **network communication system** using Java sockets, where:

- A **client** connects to a server
- Sends requests (e.g., based on zipcode)
- The server processes and responds
- Communication is handled using serialized objects

## 🧠 Technologies Used

- Java
- Sockets (TCP/IP)
- Object Serialization
- Multithreading
- Gson (for JSON handling)


## ⚙️ How It Works

1. The client connects to the server using a socket
2. A request is created (e.g., using a zipcode)
3. The request is sent as a serialized object
4. The server processes it
5. A response is returned to the client



