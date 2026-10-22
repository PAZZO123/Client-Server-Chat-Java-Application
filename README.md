# Client-Server Chat (Java)

A chat application where several clients connect to one server and exchange messages. The server handles each client on its own thread.

## Features

- Server window that accepts client connections
- Client window to send and receive messages
- Multithreading so several clients can chat at the same time

## Built with

Java, Swing (NetBeans GUI designer), sockets and threads.

## How to run

Open the project in NetBeans (or another Java IDE) and run the main class. The `.form` files are NetBeans GUI designer files for the Swing windows.

Start the server first (`ChatServer`), then open one or more clients (`ClientChat`).
