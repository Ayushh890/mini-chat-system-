🗨️ Mini Chat System
A simple Python‑based chat application built as a mini project. It demonstrates socket programming, client‑server communication, and basic multi‑user chat functionality.

📖 Overview
This project implements a chat system where multiple clients can connect to a server and exchange messages in real time. It’s a great introduction to:

Socket programming in Python

Handling multiple connections

Basic networking concepts

Building interactive console applications



⚙️ Features
Multi‑client support: Multiple users can join the chat simultaneously.

Real‑time messaging: Messages are broadcast to all connected clients.

Simple interface: Console‑based input/output for easy testing.

Extensible design: Can be expanded with authentication, private chats, or GUI.



📦 Installation
Clone the repository:

bash
git clone https://github.com/Ayushh890/mini-chat-system-.git
cd mini-chat-system-


🚀 Usage
Start the Server
Run the server script:

bash
python server.py

Connect Clients
Open multiple terminals and run:

bash
python client.py
Each client will connect to the server and join the chat room.



🧑‍💻 Example
Server Output:

Code
Server started on port 12345
Client connected: 192.168.1.10
Client connected: 192.168.1.11
Client Output:

Code
Connected to server.
You: Hello everyone!
User2: Hi there 👋



📚 Topics Covered
Python socket module basics

Uses oop concept
>Abstraction
>Encapsulation
>Inheritence
>Polymorphism

Handling multiple clients with threads
Broadcasting messages
Error handling and connection management



🔮 Possible Improvements
Add user authentication

Implement private messaging

Build a GUI interface (Tkinter/PyQt)

Add encryption for secure communication


🤝 Contributing
Fork the repository

Create a feature branch (git checkout -b feature-name)

Commit changes (git commit -m "Add feature")

Push to branch (git push origin feature-name)

Open a Pull Request


📄 License
This project is licensed under the MIT License.
