# Encrypted File Transfer Application

## Overview

A secure client-server desktop application for encrypted file transfer between users.
The system ensures that files are encrypted before transmission and safely delivered over a TCP-based network.

This project focuses on combining networking, security, and object-oriented design in a real-world use case.

---

## Features

* File encryption before transfer
* TCP-based client-server communication
* File upload and download between users
* Error handling and connection management
* Modular and extensible architecture

---

## Architecture

The application follows a client-server model:

Client ↔ Server

* The client encrypts files before sending
* The server handles incoming connections and file routing
* Data is transmitted over TCP sockets

---

## Technologies

* **Language:** C#
* **Framework:** .NET
* **Networking:** TCP sockets
* **Concepts:** Encryption, client-server architecture, OOP

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/VCoca/Encrypted-File-Transfer-App.git
```

2. Open the solution in Visual Studio

3. Start the server application

4. Run one or more client instances

5. Transfer files securely between clients

---

## Screenshots

<img width="937" height="753" alt="Screenshot 2026-04-30 204923" src="https://github.com/user-attachments/assets/783e38f8-7fcb-4ba8-aee4-38fc4dcce7ab" />

<img width="935" height="755" alt="Screenshot 2026-04-30 205153" src="https://github.com/user-attachments/assets/2ded4a87-cfdb-45de-9002-9f5ce6a0ebc1" />

---

## What I Learned

* Implementing TCP-based communication in C#
* Designing a client-server architecture
* Applying encryption in real-world scenarios
* Handling concurrency and multiple connections
* Structuring a modular and maintainable codebase

---

## Future Improvements

* Add authentication system
* Improve encryption mechanism
* Add GUI enhancements

---

## Author

Veljko Cocojević
GitHub: https://github.com/VCoca
