# MULTITHREADED CHAT APPLICATION

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: DIXANT NEGI

*INTERN ID*: CT08RWI

*DOMAIN*: JAVA

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

This Java-based chat application consists of two programs: a Chat Server and a Chat Client, enabling real-time communication between multiple users over a network. The server handles multiple clients simultaneously, while each client can send and receive messages in a group chat format.

The Chat Server runs on a specified port (12345) and continuously listens for incoming client connections using a ServerSocket. When a new client connects, the server assigns a separate ClientHandler thread to manage communication with that user. The client is prompted to enter a name, which is broadcasted to all other connected clients. Messages sent by any client are relayed to all other clients except the sender. The server also tracks active clients in a Set and removes them when they disconnect.

The Chat Client connects to the server and allows users to send messages via a console interface. It establishes a socket connection to the server and uses BufferedReader and PrintWriter to handle incoming and outgoing messages. A separate thread listens for messages from the server, ensuring real-time updates while allowing the user to type messages simultaneously. The client continuously sends user input to the server until the connection is terminated.

This chat system demonstrates core networking concepts such as socket programming, multi-threading, and message broadcasting. It can be extended with features like a GUI, private messaging, or encryption for enhanced security.

OUTPUT

![Image](https://github.com/user-attachments/assets/48708c34-0960-41d8-8b00-fbe504ec1bf8)

![Image](https://github.com/user-attachments/assets/bcc17286-bc41-43ef-a0ab-9a226fec4694)

![Image](https://github.com/user-attachments/assets/4eb21f62-584e-476b-bb1c-99af0fb507ea)
