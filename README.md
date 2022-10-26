# socket-chat

CCO06027 - DISTRIBUTED SYSTEMS

Client/Server chat app using Java sockets and threads

### Client
To communicate with the server, the client uses one single socket which’s an 
object from Socket class, to send and receive data from server

run Client in other computer. Set the IP host on `Client.java`

```java
  clientSocket = new Socket("IP_HOST", 5000);
```

### Server 
To communicate with client, the server uses two types of sockets

- ServerSocket : this class is used by the server to declare a ServerSocket 
object which the server needs to listen to connection requests from the clients

- Socket : this class is used by the server to declare a Socket object, which 
the server uses to send and receive data from the client
