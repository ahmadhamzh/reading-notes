# Review, Research, and Discussion


### 1-What does it mean that web sockets are bidirectional? Why is this useful?

 WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.

 ### 2- Does socket.io use HTTP? Why?

Websocket is created when you make upgrade from http to websocket, so it kind of does need http. socket.io isn't a pure Websocket server/implementation, it depends on HTTP for its initial connection setup.

### 3- What happens when a client emits an event?

it send to the server that the event in the emit method is on so any listener in the server to this event will do it callback function.

### 4- What happens when a server emits an event?

it send to all theclient who is connected to the server that the event of this emit method is on so any client have a listner to this event will do it call back function

### 5- What happens if a client “misses” an event?

the client wouldn't know of that event so client's listner for that event wouldn't do ther callback function.

### 6- How can we mitigate this?

using the message queue so the server will save all the events in the message queue till the client tell the server that it recive that event then the server delete the events from queue.

rm   |   Discripe
-| -
**Socket** | one endpoint of a two-way communication link between two programs running on the network.
**Web Socket** | a communications protocol for a persistent, bi-directional, full duplex TCP connection from a user's web browser to a server. 
**Socket.io** | is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers. 
**Client** | an application that connect to a server  
**Server** | an application that connect with other applications clients and mange the data flow between them .   
**OSI Model** | a conceptual framework used to describe the functions of a networking system.
**TCP Model** | a set of standardized rules that allow computers to communicate on a network such as the internet.
**TCP** | is one of the main protocols of the Internet protocol suite. It originated in the initial network implementation in which it complemented the Internet Protocol 
**UDP** | is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet. 
**Packets** | is the unit of data routed between an origin and a destination on the internet 

