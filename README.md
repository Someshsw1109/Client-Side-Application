# Client-Side-Application

**This Java project is a simple client-side application for a chat system. It establishes a connection to a server using a socket at the IP address 127.0.0.1 (localhost) on port 7777. Once connected, it enables two main functionalities:**

*1- Reading Messages from the Server: The client continuously reads messages from the server using a separate thread. If the server sends a message "EXIT," the client closes the connection.*

*2- Sending Messages to the Server: The client also allows the user to input messages from the console, which are then sent to the server. If the user types "EXIT," the client closes the connection.*

**The project demonstrates basic network communication using sockets, multithreading for concurrent reading and writing, and handling I/O operations in Java.**
