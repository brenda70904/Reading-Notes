# What is OAuth

### What is OAuth? 
Open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

### Give an example of what using OAuth would look like. 
Log on a website using other website's/service logon.

### How does OAuth work? What are the steps that it takes to authenticate the user? 

First website provides user's identity to connect to second website => Second website generate a one-time token to first website => First website presents the token to client's software and to client's authorization provider. If not already authorized, client needs to authenticate. => The approved token will be sent to first website and then to second website. => Second website allow the client to access to their website.

### What is OpenID?
OpenID serves as a single sign-in, vouching for the identities of users in other sites.

 

### What is the difference between authorization and authentication? 
Authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to.

### What is Authorization Code Flow? 
A flow that exchanges an Authorization Code for a token.

### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)? 
An extra code challenge step to enhance the security of the flow.

### What is Implicit Flow with Form Post? 
This flow is intended for Public Clients, or applications which are unable to securely store Client Secrets

### What is Client Credentials Flow?  
M2M pass along their Client ID and Client Secret to authenticate themselves and get a token.

### What is Device Authorization Flow? 
Device asks the user to go to a link on their devices and authorize the device.

### What is Resource Owner Password Flow? 
Requests users provide credentials using an interactive form.

[Authentication and Authorization Flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

[What is OAuth? How the open authorization framework works](https://auth0.com/docs/get-started/authentication-and-authorization-flow)
