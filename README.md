# Chat-Application-

This README file provides instructions on how to set up and run the Chat Application. The application supports both public and private messages, as well as file transfers.

**Features**
.Public Messaging: Send messages to all connected clients.
.Private Messaging: Send messages to a specific client.
.Blockcast Messaging: Send messages to all clients except one.

**Requirements**
Java Development Kit (JDK) 8 or higher
An IDE (e.g., IntelliJ IDEA, Eclipse) or a text editor (e.g., Notepad++, Sublime Text)
Files
ChatClient.java: Client-side code to connect to the chat server.
ChatServer.java: Server-side code to handle multiple client connections.

**How to Run**
1. Compile the Java Files
Open the command prompt and navigate to the directory containing the Java files. Compile the files using the following commands:
cd..
cd java
cd jdek-19(aviable java IDE)
javac ChatClient.java
javac ChatServer.java
3. Start the Server
In the command prompt, run the server program:
![Screenshot (93)](https://github.com/user-attachments/assets/90a1417f-635f-4f95-8769-0bbe41f68890)
![Screenshot (94)](https://github.com/user-attachments/assets/117ad713-9dc2-4d7b-bd80-2106a25d1590)
![Screenshot (95)](https://github.com/user-attachments/assets/9437f5a9-204a-469b-a886-819852cfaad7)



java ChatServer
java ChatServer 1001
Note: If you do not specify a port number, the default port 1001 will be used.

3. Start the Client(s)
Open another command prompt window for each client and run the client program:

java ChatClient
java ChatClient localhost 1001
Note: If you do not specify a server and port number, the default localhost and port 1001 will be used.

Usage
1. Connect to the Server
The client will be prompted to enter a username when connecting to the server. The username must not contain the characters @ or !.

2. Send Messages
Public Message: Type the message and press Enter.
Private Message: Use the format @username: message. Example: @john: Hello John!
Blockcast Message: Use the format !username:message. Example: !john:Hello everyone except John.
Messages from other clients will be displayed automatically. Files will be saved in a directory named Received_Files.

4. Quit
To quit the chat, type /quit.

Handling Errors
Ensure the server is running before starting the client.
Check the file path and existence of the file before sending.
Use valid usernames and commands as specified.
