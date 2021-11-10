# Authorization/Authentication

## Review, Research, and Discussion


**1- What header(s) are used in authentication and authorization ?**

The HTTP Authorization request header can be used to provide credentials that authenticate a user agent with a server, allowing access to a protected resource.

**2- What is safe to put into a JWT ?**

m the server so its unique , thats why its consider as new layer of security

**3- How are JWTs validated ?** 

JWT tokens are digitally signed (the signature part) using the payload content and a secret key. In order to change the content, the secret key is required to generate the signature again, otherwise, the signature will be invalid.


Term   |   Discripe
-| -
**RBAC** | Role-based access control (RBAC) is a policy-neutral access-control mechanism defined around roles and privileges.
**User Roles**|are permission sets that control access to areas and features within the Professional Archive Platform.
**JWT Token**|SON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object

---