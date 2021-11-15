## Review, Research, and Discussion

### 1- What is the benefit of transforming data into packets?

 ata packets are able to find the destination without the use of a dedicated channel. Reduces lost data packets.

 ### 2-UDP is often refereed to as a connectionless protocol. Why is this?

 Unlike TCP, UDP doesn't establish a connection before sending data, it just sends

 ### 3- Can a socket server application have multiple socket connections?
 
 yes a socket that has been established as a server can accept connection requests from multiple clients.

 ## 4- Can a socket connection application be connected to multiple socket servers?

 yes - you need one socket for each connection. A socket is a client IP address + client port + server IP address + server port combination. If a client is talking to multiple servers, it is using multiple ports on the client machine.

 ### 5- Can an application be both a socket server and a socket connection?

 You can use the same socket for whatever you want, as long as your protocol handles it.

Term|  Discripe
-|-
**Observer Pattern** | the observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers,
**Listener** | a procedure in JavaScript that waits for an event to occur.
**Event Handler** | a callback routine that operates asynchronously and handles inputs received into a program (events)
**Event Driven Programming** | is a programming paradigm in which the flow of the program is determined by events such as user actions, sensor outputs, or message passing from other programs or threads.
**Event Loop** | is a programming construct or design pattern that waits for and dispatches events or messages in a program.
**Event Queue** | a repository where events from an application are held prior to being processed by a receiving program or system.
**Call Stack** | is a stack data structure that stores information about the active subroutines of a computer program.
**Emit/Raise/Trigger** | are methods to inform that an event just happend
**Subscribe** | This is a JavaScript object that defines the handlers for the notifications you receive
**database** |  is an organized collection of structured information, or data, typically stored electronically in a computer system. 
