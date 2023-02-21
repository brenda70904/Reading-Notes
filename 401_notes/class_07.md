# Intro to JWT

### What is a JSON Web Token [(JWT)](https://jwt.io/introduction/)?
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. 

### When should we use JSON Web Tokens?
When the server and client want to exchange the data or when we need to authorize someone. 

### Claims are expected in which structural component of a JWT?
Payload part

## [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

### If I get a JWT and I can decode the payload, how can we call that secure?
Even if you can decode the JWT, you still can’t change content because you don’t know the secret key. 
### If sending a JWT, what must the sender and receiver both know? Hint, it’s appended in the signature.
Secret key
### Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

### [Why use JWT?](https://www.youtube.com/watch?v=926mknSW9Lo)
JWTs are a good way of securely transmitting information between parties because they can be signed
### JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
JWT is compact because of the fast transmission that you can use to send via URL, HTTP header , or POST request. It’s self-contained because it contains the info about the user. 
### What are the three components (the structure) of a JWT signature?
Header ,playload , and signature


[Auth 0](https://auth0.com/docs/secure/tokens/json-web-tokens)
