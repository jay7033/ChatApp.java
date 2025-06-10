# ChatApp.java
A Multi-Client Chat System is a network-based application that allows multiple clients (users) to communicate with each other in real time through a central server. Here’s a detailed description suitable for documentation or academic submission:

ChatApp - Java Console-Based Multi-Client Chat Application

ChatApp is a simple console-based chat application written in Java that supports multiple clients communicating with each other through a central server. It demonstrates basic concepts of socket programming, multi-threading, and client-server architecture.

📌 Features
🔌 Server that listens for multiple clients

💬 Real-time messaging between all connected clients

👤 Username identification for each client

🔁 Continuous message broadcasting from the server

📚 Easy-to-read, modular code using threads and OOP principles

🧰 Technologies Used
Java (JDK 8+)

TCP Sockets

Java I/O and Threads

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/ChatApp.git
cd ChatApp
Compile the Java file:

bash
Copy
Edit
javac ChatApp.java
Start the server in a terminal:

bash
Copy
Edit
java ChatApp
When prompted, type:

nginx
Copy
Edit
server
Start clients in separate terminals (you can start multiple clients):

bash
Copy
Edit
java ChatApp
When prompted, type:

nginx
Copy
Edit
client
Then enter a username when asked.

🖼 Example
vbnet
Copy
Edit
Start as (server/client): server
Server is running on port 1234...

# In another terminal:
Start as (server/client): client
Enter your username: Alice
SERVER: Alice has entered the chat!
Alice: Hello everyone!

📦 Project Structure

bash
Copy
Edit
ChatApp.java  # Single Java file containing both client and server logic

🧠 Concepts Demonstrated

Socket programming (Java Socket and ServerSocket)

Multi-threaded client handling using Runnable

Buffered input/output streams

Clean shutdown of resources

📄 License

This project is open-source and available under the MIT License.









