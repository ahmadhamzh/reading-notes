# Review, Research, and Discussion

### 1- When is Basic Authorization used vs. Bearer Authorization?

we use Basic Authorization with userane and password to signin and then use the bearer authorization with thirdparty api endpoint to use the token fot more security.

### 2- What does the JSON Web Token package do?

it use the user name and password and a secrete to give us a token to use in bearer authorization.

### 3- What considerations should we make when creating and storing a SECRET?

i have to keep my secret in an env file so it keep hiden in my server.

Term   |   Discripe
-| -
**encryption** | is a means of securing digital data using one or more mathematical techniques.
**token** | is nwe lvl of security so you can use it when interact with third api party without useing the password.
**bearer** | Bearer tokens enable requests to authenticate using an access key.
**secret** | s a piece of information  that is used to decrypt and encrypt messages.
**JSON Web Token** | is a JSON encoded representation of a claim(s) that can be transferred between two parties.

## what is RBAC

RBAC is the idea of assigning system access to users based on their role in an organization. It's important to remember that not every employee needs a starring role.

## Benefits of RBAC?

With the proper implementation of RBAC, the assignment of access rights becomes systematic and repeatable. Further, it is much easier to audit user rights, and to correct any issues identified.

