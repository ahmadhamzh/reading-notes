# CRUD

### In your own words, describe what each group of status code represents:

* 100’s = These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.

* 200’s = These are the success codes. They tell the client that its request was accepted.

* 300’s = These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore.

* 400’s = These are the client error codes. They are all about invalid requests a client sent to a server.

* 500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.

### What is a status code 202?

* Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future.

### What is a status code 308?

* This tells the client to use another URL to access the resource and not use the current URL anymore.

### What code would you use if an update didn’t return data to a client?

* 204 No Content

### What code would you use if a resource used to exist but no longer does?

* 410 Gone 

### What is the ‘Forbidden’ status code?

* 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

---------

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

* so when we push it to gethub couldn't see the url for our mongodb.

### What is middleware?

* Middleware is software that enables one or more kinds of communication or connectivity between two or more applications or application components in a distributed network. By making it easier to connect applications that weren't designed to connect with one another.

### What does app.use(express.json()) do?

* to set the server to accept JSON

### What does the /:id mean in a route?

* its a parameter and it gives us a access to what ever been passing after slash .

### What is the difference beween PUT and PATCH?

* put : will change all the information for the collection  
* patch : will change just the information that you want to change not all the information in the collections.

### How do you make a default value in a schema?

* when you do the model you can make any data in schema take default value by the key default.

### What does a 500 error status code mean?

* it means that there is error in the server side not the clinte side .

### What is the difference between a status 200 and a status 201?

* both mean that evry thing is succussfull but the 201 is more spicefic that say that you creating somthing succussfully 





----
refrence :

* [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)