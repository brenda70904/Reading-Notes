
## Securing Passwords

### Explain to a non-technical friend how you would safely hash and store a password.
   Hashing turns your password (or any other piece of data) into a short string of letters and/or numbers using an encryption algorithm. If a website is hacked, cyber criminals don't get access to your password. Instead, they just get access to the encrypted “hash” created by your password.

### What is Bcrypt?
  bcrypt is a password-hashing function.
  
### Why might you use something like Bcrypt?
  To protect confidential data.


## Basic Auth

### What is Basic Authentication?
  Basic Authentication is a method for an HTTP web browser to provide a username and password when making a request.

### What properties are necessary in the header of a Basic Auth request?
  The word `Basic` with base64-encoded username: password string.

### How are username:password in Basic Auth encoded?
  Use  Base64 encoding of ID and password joined by a single colon `:`

  
## OWASP auth cheatsheet

### Define the authentication process to a non-technical recruiter.
Authentication. Users have to prove they are who they say they are.

### How should your error messaging respond (both HTTP and HTML)? Why?
It should respond with respond with a generic error message to prevent given hacker too much info 
