# Client-and-Server

 A lab activity that works with client and server through the C programming language!

git clone https://github.com/JerryNYang/Client-and-Server.git
cd Client-and-Server

## Overview
- **Server**: `rec09svr.c` — Listens for incoming connections and handles client requests.
- **Client**: `rec09cli.c` — Connects to the server and exchanges messages.

## Requirements
- GCC compiler
- Linux / Unix-like system (or WSL on Windows)

## How to Compile
```bash
gcc -o server rec09svr.c
gcc -o client rec09cli.c

Start the server (in one terminal): Bash./server
(It listens on a specific port – check rec09svr.c for the PORT value, e.g., 8080.)
Start the client (in another terminal):
Bash./client 127.0.0.1 <PORT>
 Example:Bash./client 127.0.0.1 8080
