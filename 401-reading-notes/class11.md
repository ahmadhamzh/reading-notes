# Review, Research, and Discussion

### 1- Why is access control important ?

Access controls limit access to information and information processing systems. When implemented effectively, they mitigate the risk of information being accessed without the appropriate authorisation, unlawfully and the risk of a data breach. They apply anywhere access is required to perform a business activity and should be adhered to when accessing information in any format, on any device.

### 2- Describe an application that would need access control ?

* Login credentials (such as usernames and passwords).

* PINs and one-time passwords (OTPs).

* Virtual private network (VPN) access to internal networks.

* Physical access cards, FOBs, tokens, locks, and keys.

* Security guards with access lists.

### 3- What is a role used for ?

Roles help you grant and manage sets of privileges for various categories of users.


Term|  Discripe
-|-
Authorization | Authorization is the process of giving someone permission to do or have something. In multi-user computer systems,
Role Based Access Control | is an approach to restricting system access to authorized users.
Capabilities | is the thing that the user is apple to do .

## Event-Driven Programming 
Event-Driven Programming is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision

## EventEmitter

Node.js natively provides us with a useful module called EventEmitter that allows us to get started incorporating Event-Driven Programming in our project right away. 

## Removing Listeners

To remove event listeners in EventEmitter we can use the removeListener or removeAllListeners method. It’s important to note that in the EventEmitter that comes built-in with Node you must pass a reference to the exact function you wish to remove when using the removeListener method. 

