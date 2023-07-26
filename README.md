# Chat

This project is a simple chat application that allows users to connect to a chat server and exchange messages with other users in real-time. The chat client has a graphical user interface (GUI) built using Java Swing.

## Features

- Connect to a chat server by providing the server address and port number.
- Choose a unique username to be identified in the chat room.
- View the list of online users.
- Send and receive messages in the chat room.
- Get notifications about user connections and disconnections.

## Technologies Used

- Java
- Java Swing for GUI
- Sockets for network communication

## Getting Started

1. Clone the repository to your local machine:
````
 git clone https://github.com/your_username/chat-client.git
````

2. Start the chat server by entering this command in the repository directory:


````
java chat.Server
````

3. Enter the correct port number, for example, 5555.

4. Open a new tab in the terminal and start the chat client:

````
java chat.client.ClientGuiController
````

5. If you are running the project on a single computer, enter "localhost" in the open tab. If you are running the project on multiple computers, enter your IP address and the port number (e.g., 172.17.255.255:5555).

6. You can also start a bot that writes the time by using the following command:

````
java chat.client.BotClient
````
and repeat step 5.
## Autors
[@Tyomnayark] (https://github.com/Tyomnayark)