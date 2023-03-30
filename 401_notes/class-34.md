# [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

### Explain the different between a query string parameter and a path parameter.

The query string is present as key-value pair that describe the look, and the path parameter shows your program where to look. 

### What would our API URL with a path id parameter be given the following information:
- Domain: http://our-site.com 
- v3
- model name: stuff
- id: things

### We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

So, think of an API as a way for different computer programs to talk to each other and share information. It's kind of like a waiter at a restaurant taking your order and then going back to the kitchen to tell the chef what you want.

Now, in the case of a dynamic API with an "interface", the interface is like a menu that the waiter uses to take your order. It makes it really easy for the waiter to know exactly what you want, and for the chef to know exactly how to make it.

So, in this case, the interface is a set of rules or instructions that tell other programs how to interact with the API. It lays out what kind of data can be sent and received, and how it should be formatted. This makes it much easier for other programs to use the API without having to know all the technical details of how it works.

Think of it like ordering food at a restaurant where the menu tells you what kind of dishes are available, what ingredients they contain, and how they should be prepared. The interface of the API works in a similar way by providing a clear and easy-to-understand way for other programs to interact with it.

# [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)
### Describe how you would use middleware to implement basic and bearer auth.
middleware can be used to implement basic and bearer auth by intercepting each request, checking for the appropriate credentials or token, and either adding the authenticated user to the request object or returning a 401 Unauthorized response to the client.

### Describe the handshake necessary to implement OAuth.
OAuth is a protocol for authorizing third-party applications to access a user's resources on a website. It involves a handshake process between the user, the third-party application, and the website's authorization server. The handshake process includes steps such as prompting the user to log in, requesting permission to access resources, generating an access token, and using that token to access the user's resources.

### Describe how Role Based Access Control works to a non-technical friend.
