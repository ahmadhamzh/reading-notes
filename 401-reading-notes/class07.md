# Review, Research, and Discussion

### 1- Write the following steps in the correct order:


* Register your application to get a client_id and client_secret.
* Ask the client if they want to sign in via a third party.
* Redirect to a third party authentication endpoint.
* Make a request to a third-party API endpoint.
* Receive authorization code.
* Make a request to the access token endpoint.
* Receive access token.

### 2- What can you do with an authorization code?

i can do the CRUD operations acording to it.

### 3- What can you do with an access token ?

access tokens are the thing that applications use to make API requests on behalf of a user.

### 4- What’s a benefit of using OAuth instead of your own basic authentication?

 It allows you to read data of a user from another application.

 
 Term   |   Discripe
-| -
**Client ID** | a unique identifier for a browser–device pair that helps Google Analytics link user actions on a site.
**Client Secret** |  secret known only to your application and the authorization server.
**Authentication Endpoint** | a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service.
**Access Token Endpoint** |  is where apps make a request to get an access token for a user.
**API Endpoint** |  one end of a communication channel.
**Authorization Code** |  a temporary code that the client will exchange for an access token. 
**Access Token** | thing that applications use to make API requests on behalf of a user.  


### What is JSON Web Token?

JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object

### How do JSON Web Tokens work?

In authentication, when the user successfully logs in using their credentials, a JSON Web Token will be returned. Since tokens are credentials, great care must be taken to prevent security issues. In general, you should not keep tokens longer than required.

### If I get a JWT and I can decode the payload, how is that secure? 

JWTs can be either signed, encrypted or both. If a token is signed, but not encrypted, everyone can read its contents, but when you don't know the private key, you can't change it. Otherwise, the receiver will notice that the signature won't match anymore.