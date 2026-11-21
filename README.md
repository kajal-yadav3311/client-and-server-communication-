# 🔌 Python TCP Client-Server Chat Application

A simple and robust implementation of **TCP Socket Programming** in Python, enabling structured message exchange between a client and a server.

## 🚀 Features
- Establishes a stable TCP/IP connection using Python's built-in `socket` module.
- Real-time 3-way bidirectional message exchange loop.
- Exception handling for connection errors (`ConnectionRefusedError`, `OSError`).
- Clean resource management with proper socket closing (`finally` blocks).

## 🛠️ Tech Stack
- **Language:** Python
- **Modules:** `socket`

## 📁 Project Structure
- `server.py` — Handles incoming client connections and manages server-side communication.
- `client.py` — Connects to the server and handles client-side message exchange.

## ⚙️ How to Run

1. **Start the Server** first in a terminal:
   ```bash
   python server.py
